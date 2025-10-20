# WESTPA Tutorials Landing Page/Hub

This is the landing page/hub for all [WESTPA Tutorials](https://github.com/westpa/westpa/wiki/tutorials), including those we have published in LiveCoMS and those we have provided at workshops. If you are here to learn how to use WESTPA, you are at the right place!

If you are new to WESTPA, start off with our LiveCoMS suite of tutorials for WESTPA 2.0 \([Bogetti et al. 2023](https://doi.org/10.33011/livecoms.5.1.1655 )\) in the `paper` directory ([pdf](https://github.com/westpa/tutorials/blob/main/paper/CombinedSuiteofWESTPATutorials.pdf)). [Tutorials 7.1-7.4](https://github.com/westpa/westpa_tutorials) are our basic and intermediate tutorials. [Tutorials 7.5-7.10](https://github.com/westpa/westpa2_tutorials) are our advanced tutorials.

## Getting Started

You can download all of the tutorial files from this repository. The easiest way is to clone this repository using `git` in the command line. Run `git clone --recursive https://github.com/westpa/tutorials` so you also clone the tutorial files submodules (tutorial 7.1-7.10 files). If you already cloned this repo without the `--recursive` flag, run `git submodule update --init --recursive` in the root level of the clone to download the submodules.

## Updating this repository

This repository is linked to a specific commit of each tutorial repository using `git submodule` and updated weekly using a dependabot. To manually update the existing links to the newest commits, run `git submodule update --remote --merge` and push the commit to this repository.

If you need to move/remove the submodules for any reason, follow the instructions here:
https://gist.github.com/myusuf3/7f645819ded92bda6677?permalink_comment_id=3936499#gistcomment-3936499
