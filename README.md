# Dockerfiles

Dockerfile Templates for various courses

## Install following tools

1. Docker Desktop: [https://docs.docker.com/desktop/](https://docs.docker.com/desktop/)

### Windows System

It takes a bit of extra work.

1. Install git along with git-bash: [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Follow the instructions here: [https://www.makeuseof.com/how-to-install-docker-windows-10-11/](https://www.makeuseof.com/how-to-install-docker-windows-10-11/)

## Running Docker for Python-related courses

Follow these instructions for Beginning Python, Advanced Python, Python Machine Learning

### Initial setup

Note that the initial setup may take some time to build docker image.

1. Create a course folder
    - e.g., `Users/<username>/<semester>/<course>`
    - `Users/rbasnet/fall2023/beg-python`
    - NOTE - course folder must be lowercase as it's the name used for docker image

2. Copy all the files from python folder into your course folder

3. Using a Terminal (git-bash on Windows):

    - change working directory to your course folder
    
    ```bash
    $ cd <Users/rbasnet/fall2023/beg-python>
    $ pwd
    $ ls
    ```
    - run the run.sh script using bash program

    ```bash
    $ bash run.sh
    ```
    - if all goes well, you'll see a Ubuntu Bash Terminal
    - type the following for a quick test:

    ```bash
    $ uname -a
    $ pwd
    $ ls
    $ python hello.py
    ```

4. Clone the course jupyter notebook repository


### Run Jupyter notebook server

1. Open a Terminal (git-bash on Windows)
2. Change current working directory to your course folder
  
  ```bash
  $ cd <course folder>
  ```

3. Run run-jupyter.sh script

  ```bash
  $ bash run-jupyter.sh
  ```

4. Press Ctrl+C to quit the jupyter notebook server
