# Автоматизация для GTA 5
Что было бы неплохо сделать
* Автопилот для машин
* Автопилот для авиации
* Определение людей
* Оценка расстояния
* Корректировка снайперского выстрела

Проект начат [под впечатлением от цикла этих статей](https://pythonprogramming.net/game-frames-open-cv-python-plays-gta-v/). Код для первой части взят из исходной статьи.


```
$ python --version
Python 3.6.1
```

## Установка зависимостей
### OpenCV 3.1.0
Качаем неоффициальную сборку для python 3
[вот тут](http://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv)

_cpXX_ - версия вашего питона

```
$ pip install <локальный_путь>/opencv_python-3.1.0-cp35-none-win32.whl
```

[Чуть более подробно об установке читайте тут](http://san-tit.blogspot.ru/2016/03/opencv-310-python-35-windows.html)
### Numpy, Pillow
```
$ pip install numpy
$ pip install Pillow
```
### Imutils
A series of convenience functions to make basic image processing functions such as translation, rotation, resizing, skeletonization, displaying Matplotlib images, sorting contours, detecting edges, and much more easier with OpenCV and both Python 2.7 and Python 3.

```
$ pip install imutils
```

### PyAutoGUI 
A cross-platform module for GUI automation for human beings. Control the keyboard and mouse from a Python script.

```
$ pip install pyautogui
```
### matplotlib
```
$ pip install matplotlib
```
## Полезные ссылки
### Общие ссылки
* [Image Segmentation with Watershed Algorithm](http://docs.opencv.org/3.1.0/d3/db4/tutorial_py_watershed.html)
* [Clustering in OpenCV](http://docs.opencv.org/3.0-beta/doc/py_tutorials/py_ml/py_kmeans/py_kmeans_opencv/py_kmeans_opencv.html)
### Задача по определению людей 
* [Определение людей на изображении](http://www.pyimagesearch.com/2015/11/09/pedestrian-detection-opencv/)
* [Partial Human Detection](http://stackoverflow.com/questions/43099540/opencv-3-python-partial-human-detection)
