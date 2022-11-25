# Databases systems

- The slides folder contains the material teached during classes.

## whoami

<img width="831" alt="image" src="https://user-images.githubusercontent.com/41596745/203931143-aa69e1e1-643f-45cb-8ea2-14b723fafa0e.png">

## Install

- Install `docker`
    - Windows: https://docs.docker.com/desktop/windows/install/
    - Mac: https://docs.docker.com/desktop/mac/install/
    - Linux: https://docs.docker.com/engine/install/ubuntu/
- Install `docker-compose`
    - Windows and Mac: Docker Compose is already included in Docker Desktop
    - Linux: https://docs.docker.com/compose/install/
- Run docker (sometimes docker has to be (re)started over and over again)
    - Windows
        - Double click on Docker Desktop from the Windows Desktop
        - This warning will pop up, DO NOT close it, but click on the link!
        ![image](https://user-images.githubusercontent.com/41596745/203927854-f3ec2e5f-c35d-4931-bb0e-157911bfea1e.png)
        - Download the WSL kernel from here
        ![image](https://user-images.githubusercontent.com/41596745/203928010-a23705b5-7036-4afe-a046-5ade2b5efdf7.png)
        - Click on restart
        ![image](https://user-images.githubusercontent.com/41596745/203928081-e18e4a5e-f4d8-47c2-a333-04613599de8d.png)
- Check that docker works by opening a *new* terminal (`cmd.exe` in Windows or `/bin/bash` in Linux) and running `docker run hello-world`
