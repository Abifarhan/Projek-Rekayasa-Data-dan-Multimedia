# Projek-Rekayasa-Data-dan-Multimedia
DIkerjakan untuk memenuhi tugas project

Text : Indexing Text and Image

A. Indexing text:

1. Download swish-e  swishe.org/download/
2. go to folder swish e you have been download and extract it.
3. Then go to swish-e folder and write this syntax on terminal:
a. /configure (for configuration).
b. make (compile automatically).
c. make check/make test(for testing).
d. sudo su (go to root).
e. make install (for instalation).

if you want to check if swish-e already installed in your OS just type this syntax = swish-e -V


B. Indexing Image
- in this tutorial I using Pyhton, Flask, and OpenCV.
- directory of image in : app/static/image
The step :
1. First you have to clone this repository and install pip with the syntax : sudo apt install python3-pip.

2. write this syntax in your terminal:
  - pip install -r requirements.txt
  - cd app
  - python index.py --dataset static/images --index index.csv
  
  
  Sources :
  - Text-Indexing : Install Swish-e(Install the package in Ubuntu)
  - Image-Indexing : https://github.com/kudeh/image-search-engine
