# Copyright Check

A Docker Image which supports checking Copyright. The script works by scanning a diff for changed files. Then checking these files for the correct copyright.

#### Proposed Usage

```
python3 /usr/local/bin/check_copyright_headers.py $TARGET_BRANCH
```


### Supported Versions

| Version |                       Image                        |
| :-----: | :------------------------------------------------: |
| latest  | ghcr.io/khronosgroupactions/copyright-check:latest |
|  1.0.0  | ghcr.io/khronosgroupactions/copyright-check:1.0.0  |