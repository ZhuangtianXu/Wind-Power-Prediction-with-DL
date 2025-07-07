# Wind Power Prediction with Deep Learning

## Abstract

**Overall Objective**: wind power forecast using deep learning approach.


## Requirements

1. Make sure GPU is avaible and `CUDA>=11.0` has been installed on your computer. You can check it with
    ```bash
        nvidia-smi
    ```
2. Simply create an virtural environment with `python>=3.8` and run `pip install -r requirements.txt` to download the required packages. If you use `anaconda3` or `miniconda`, you can run following instructions to download the required packages in python. 
    ```bash
        conda create -y -n forecast python=3.8
        conda activate forecast
        pip install pip --upgrade
        pip install -r requirements.txt
        conda activate forecast
        conda install pytorch torchvision torchaudio cudatoolkit=11.3 -c pytorch
    ```

## Git Usage

Here are some simple instructions about how to use `Git`.

1. If you want to download the whole project, run following command.

```bash
    git clone --recurse-submodules -j8 git@github.com/ZhuangtianXu/Wind-Power-Prediction-with-DL.git
```

2. If you want add files to our local git project and remote git project on `github`, run following command.

```bash
    # Firstly, plz avoid adding files to master branch on github directly. You can create your own branch locally and remotely.

    git branch wind # create my local branch. Here I name the branch as 'wind'. If you have already created a branch, you can jump to next command.

    git checkout wind # switch to 'wind' branch.

    git add * # add all the files to local branch 'wind'.

    git commit -m "update" # confirm to add files to local branch 'wind'

    git push origin wind # create branch 'wind' remotely on github and copy your the content on your local branch 'wind' to the remote 'wind'.
```

3. If you want to synchronize files on remote project on `github`, you should run:

```bash
    git pull origin master # synchronize files on remote master branch.
    git pull origin "you branch name" # the 'master' can be replaced by the name of the other branch created on remote project on github, then you can synchronize files on the specific remote branch.
```

## Contributing

if you would like to contribute some codes, please submit a PR, and feel free to post issues via Github.
    
---------------------------------------------------------------------------------
UM-SJTU Joint Institute 交大密西根学院
