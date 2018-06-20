# Facial landmarks
Demo project to detect facial landmarks using 68 coordinates in images



## How to run the project using python 2
### Image demo

```
python facial_landmarks.py
```

### Dependancies

* tensorflow >= 1.0
* keras >= 2.0
* opencv >= 3.0
* dlib 
* numpy

* [shape_predictor_68_face_landmarks.dat][sp]

#### N.B

* **opencv should be compiled with ffmpeg support.**
* **Conda virtual environment can be created using the following command.**

 ```
 conda env create -f requirements.yml -n emopy_2
 ```
* **shape_predictor should be inside root directory of this project. Shape predictor can be downloaded to project using the following script.**
```
cd /path-to-project
wget "http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2"
bzip2 -d shape_predictor_68_face_landmarks.dat.bz2
```

 [sp]: http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
