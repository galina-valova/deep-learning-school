
# 26. Генеративные модели

Сегодня мы познакомимся с еще двумя архитектурами нейронных сетей - сети для **переноса стиля** с одной картинки на другую и **GAN**'ы.

### Neural Style Transfer

Neural Style Transfer - техника, которая позволяет перенести стиль одной картинки на другую. Картинка, с которой переносится стиль называется *Style Image*, а та, на которую переносится стиль, называется *Content Image* (потому что с нее мы берем содержание, т.е. content):

<p align="center">
  <img src="https://cdn-images-1.medium.com/max/1040/0*h5YONGux0M4j1Bdf" width=600>
</p> 

Из таких двух картинок может получиться такой езультат:
<p align="center">
  <img src="https://cdn-images-1.medium.com/max/1040/0*qdJ0aARvEcEuJ92l" width=400>
</p> 

**Лекция:**

Часть 1: [**Генеративные модели, автоэнкодеры**](https://www.youtube.com/watch?v=6qVfC7P9dEc)

Часть 2: [**Генеративные модели. Генеративно-состязательные сети**](https://www.youtube.com/watch?v=An20DOEOctc)

### Generative Adversarial Network (GAN)

Еще одна интересная архитектура - **GAN**. Такая сеть на самом деле состоит из двух сетей: **генератор**, который пытается генерировать изображения, похожие на картинки из обучающей выборки, чтобы обмануть вторую сеть -- **дискриминатор**, который пытается как можно лучше отличать реальные картинки от сгенерированных генератором "фейков". 
В итоге борьбы может получится сеть-генератор, способная генерировать картинки, **похожие на реальные**. Как пример можно привести генерацию лиц. Вы можете определить, какое лицо сгенерировано нейронной сетью?

<p align="center">
<img src="https://cdn-images-1.medium.com/max/1040/0*WdnAdf4Ir0pO1TbN" width=400>
</p>  
  
В действительности... оба лица нарисованы нейросетью :)

Чтобы более детально узнать как работают GAN'ы, предлагаем посомтреть вторую часть [**записи нашего семинара**](https://www.youtube.com/watch?v=Anocy4ey0vs) и прорешать ноутбук: [**[seminar]gan.ipynb**](./[seminar]gan.ipynb) [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/drive/1Ub3c79XxiGmHOqKnuSDtjE5TscWhJVak). Также вам помогут [слайды](./Generative%20models%20pt.2.pdf), которые использовались на семинаре.

---

## Заключение

Это последнее занятие первого семестра. Спасибо за время, которое вы уделили нашему курсу! Если Вы официально прослушиваете наш курс, то следующим шагом станет **финальный проект** по первой части курса. 

Желаем вам удачи и надеемся увидеться в следующем семестре, где мы рассмотрим еще более интересные темы из мира глубокого обучения.
