# CV_on_Raspberry_Pi_4
This is my test for learning CV on Raspberry Pi 4.

# Preparations
CV needs Python3, and library Pytorch and OpenCV. You can use the commands below to install them without `pip`:

```
$ sudo apt install python3-torch python3-torchvision python3-torchaudio python3-opencv
```

# Usage

Use following command to run:

```
$ python3 infer.py
```

Not use `#!/usr/local/bin/python3` at the beginning of `infer.py`, because in different platforms, python3 may be in different path.

# Files
 - imgclass.txt: imagenet1000 clsidx to [yrevar/imagenet1000_clsidx_to_labels.txt](https://gist.github.com/yrevar/942d3a0ac09ec9e5eb3a) (will be customs)
 - infer.py (code to CV using Camera)
 - README.md

# Todo
```[tasklist]
 - [ ] custom imgclass.txt to improve accuracy
 - [ ] from image or camera by flags
```

# References
[REAL TIME INFERENCE ON RASPBERRY PI 4 (30 FPS!)](https://pytorch.org/tutorials/intermediate/realtime_rpi.html)
