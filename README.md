# postgres_learning_250629

## **Preprocessing** 
* Construct a container:
    * Install the **docker**
    
    `Can be download from  https://docs.docker.com/`

    * Construct a container for "miniconda" in **docker**.

    Please input the following command in Terminal (https://github.com/roberthsu2003/python/tree/master/%E4%BD%BF%E7%94%A8Dock%E5%AE%B9%E5%99%A8%E9%96%8B%E7%99%BC)
    
    `docker run -it --name python-miniconda continuumio/miniconda3`

* Visual Studio Code (VSCode)
    * Install VSCode 

    `Can be download from `https://code.visualstudio.com/`

    * Install the packages:
    - [x] Container Tools
    - [x] Dev Containers

    * Link to Github
        * Open VSCode
        * Click package "Container Tools"
        * Right click --> Choose "attach ... "
        * Click file --> choose our github repository

        Note that
        `For the first time to link to github account, input the following commands in Terminal ("miniconda" container):`

        ```js
        git config --global user.name "____"
        git config --global user.email "__@__.com"
        git config --global pull.rebase false
        python --version
        ```

        * Search **repository name** that we would like to modified in the search box and click it!
        * Congrats! We can finally modify the repository in VSCode.