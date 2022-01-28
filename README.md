# Jenkins-pipeline-node

### First build your image, open docker desktop and a cmd as admin to run this commands :

<br>

- docker build . -t <your username>/nodejenkins


<br>

### Second, run the image

<br>

- docker run -p 49160:8080 -d <your username>/nodejenkins

<br>

### Third, open your localhost to :

<br>

- http://localhost:49160/