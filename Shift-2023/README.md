# Shift Winter 2023

<img src="https://raw.githubusercontent.com/akscent/kaggle-competitions/main/Shift-2023/img/banner.png">

# Описание задачи
В соревновании создается классификатор изображений. Цель - находить размытые (blurred) фото.

*Метрика соревнования* - [AUC ROC](https://en.wikipedia.org/wiki/Receiver_operating_characteristic).

# Решение

> Базовым решением было обучение различных простых ml сеток для ознакомления с их особенностями и последующий вбор наилучших моделей и усреднение результата между ними.

> Здесь так же были использованы различные преобразования картинок для аугментации данных. Методологии этих преобразований взят из следующих источников:

* 1) Bolan Su, Shijian Lu, and Chew Lim Tan. 2011. Blurred image region detection and classification. In Proceedings of the 19th ACM international conference on Multimedia (MM '11). Association for Computing Machinery, New York, NY, USA, 1397–1400. doi: [10.1145/2072298.2072024](https://dl.acm.org/doi/10.1145/2072298.2072024)


* 2) Tong, Hanghang & Li, Mingjing & Zhang, Hongjiang & Zhang, Changshui. (2004). Blur detection for digital images using wavelet transform. IEEE International Conference on Multimedia and EXPO. 1. 17 - 20 Vol.1. doi: [10.1109/ICME.2004.1394114](http://tonghanghang.org/pdfs/icme04_blur.pdf)


* 3) R. A. Pagaduan, M. C. R. Aragon, and R. P. Medina, ‘iBlurDetect: Image Blur Detection Techniques Assessment and Evaluation Study’, in International Conference on Culture Heritage, Education, Sustainable Tourism, and Innovation Technologies (CESIT2020), 2020, pp. 286–291, doi: [10.5220/0010307702860291](https://www.scitepress.org/Papers/2020/103077/pdf/index.html)


* 4) Hypermedia Image Processing Reference (HIPR): [9780471962434](https://homepages.inf.ed.ac.uk/rbf/HIPR2/fourier.htm): Fisher, Robert B., Perkins, Simon, Walker, Ashley, Wolfart, Erik: Libros.


* 5) Mobile Image Blur Detection with Machine Learning [by Benedikt Brief](https://link.medium.com/Y3LKvLnBpwb )

# Результат
В результате я оказался на 13 позиции в лидерборде.
