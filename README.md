# dater-nginx

Un server Nginx executé par Docker

# Demo

  # Environnement Requis

    VSCode
    Python 3
    Docker Desktop
    nginx:alpine image

  # Installation

    Telechargement

    $ git clone git@github.com:tissiaka/dater-nginx.git

    Ouvrir Docker Desktop,
    Puis (Dans le Terminal) Vérifiez son installation, Télécharger l'image nginx:alpine :

    ./dater-nginx $ docker -v
    ./dater-nginx $ docker pull nginx:alpine

    Ouvrir le dossier dans VSCode et build l'image dater-nginx:

    ./dater-nginx $ docker build -t dater-nginx .

    Run l'image dater-nginx

    ./dater-nginx $ docker run -dp 8080:80 dater-nginx

    Ouvrir localhost:8080
    
    ![dater-nginx](https://user-images.githubusercontent.com/96181307/147486830-36ba610b-7306-4769-a46c-14fdbe21f92e.png)

