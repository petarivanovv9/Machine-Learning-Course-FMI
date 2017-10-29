# Machine-Learning-Course-FMI
All tasks during Machine Learning with Python course at @FMI - Sofia University.

## Run jupyter via Docker
1. Install docker on your computer
2. Run ```docker pull jupyter/scipy-notebook``` in your terminal to download the jupyter image from the docker repository
3. Run ```docker run -it --rm -p 8888:8888 -v $PWD:/home/jovyan/work jupyter/scipy-notebook``` in your terminal to launch the jupyter server
