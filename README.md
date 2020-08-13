# HLODSystemDemo
HLODSystem is applied to 3DGameKit.

https://docs.google.com/document/d/1nHzYJ6KXgYUvIv1HjCGrx6tcSkhOezQfVkUC2zqcZXQ/edit?usp=sharing

## Prerequisites
### Unity
```
Unity Version: 2019.4.6f1

```
### Git 

You need Git Client which can work with GitHub.
If you don't have Git installed on your machine, download and install it from [Git Home][gitHome].

### Git LFS

This project has a file which is grater than 100MB.
For handle these files, git-lfs required.
Download and install it from [Git LargeFileStore Home][gitLfsHome]

### Connecting to GitHub with SSH

To clone the project, your Git must be configured to work with SSH Authentication, as HLODSystem uses SSH Authentication to work with Git Submodules. Check [this][gitSSHSetup] link to set up your git to use SSH to connect to GitHub. 

## Getting the project
### Cloning
The project uses a number of other projects as dependencies, and they are included into it as Git Submodules.
To have a fully working project, you should those submodules included into the project after you clone the project.

First, run the following command to clone the project:
```sh
$ git clone git@github.com:Unity-Technologies/HLODSystemDemo.git
```
After cloning is finished, navigate to the root folder of the project, and run the following command to initialize and clone all submodules:
```sh
$ git submodule update --init --recursive
```

### License
Copyright (c) 2019 Unity Technologies ApS
Licensed under the Unity Companion License for Unity-dependent projects see [Unity Companion License][license].
Unless expressly provided otherwise, the Software under this license is made available strictly on an **“AS IS”** BASIS WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED. Please review the license for details on these and other terms and conditions.

[gitHome]:<https://git-scm.com/downloads>
[gitLfsHome]:<https://git-lfs.github.com/>
[gitSSHSetup]: <https://help.github.com/articles/connecting-to-github-with-ssh/>
[license]: <https://unity3d.com/legal/licenses/Unity_Companion_License>
