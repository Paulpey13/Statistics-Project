# Employee Entry PC Configuration

Date : 20/02/2024
GPU : Nvidia Quadro T2000
CPU : Intel(R) Core(TM) i7-10750H CPU @ 2.60GHz
OS : Ubuntu 22.04.4 LTS

## Nvidia Pilot

sudo apt install nvidia-driver-535 nvidia-dkms-535

replace the name of the driver with the one adapted to your GPU.

In order to see GPU info and process that are using Nvidia GPU :

nvidia-smi

## Docker & Nvidia Docker

Follow these instructions :

https://medium.com/@linhlinhle997/how-to-install-docker-and-nvidia-docker-2-0-on-ubuntu-18-04-da3eac6ec494

If the cuda:10.1-base is not working you might want to use the cuda:12.3.1-base-ubuntu20.04

## VS Code

Download VS Code on the Unbuntu Software Application.

Python3 should already be installed with ubuntu but if pip is not installed, you can use :

sudo apt install python3-pip

## Git

sudo apt install git-all

## Atlassian & Jira

Submit a ticket to helpdesk@veracyte.com in order to create your account.

Once you have your account, you can go to https://veracyte.atlassian.net/jira/your-work to check if it is working.

## Chrome browser

Download at https://www.google.com/chrome/?platform=linux then open with Software Install.

Chrome might be needed to use some applications.

## Fiji Imagej

Download at https://fiji.sc/ 
You will find an executable file called ImageJ-linux64 in the archive.







