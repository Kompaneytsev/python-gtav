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

