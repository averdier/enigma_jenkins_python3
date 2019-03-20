# enigma_jenkins_python3
Enigma | Jenkins | Python 3 | Image Jenkins avec Python 3

Build image
```
docker build -t jenkins/python3 .
```

Run image
```
docker run --name jenkins_python_dev -p 8080:8080 jenkins/python3
```