# hse_hw1_meth

Ссылка на Colab: https://colab.research.google.com/drive/1NythSDWdjgvl8WtRStkHupEtXQn3Htz5?usp=sharing

## 1.

### 1)
Все fastqc файлы лежат в одноименной папке /fastqc

(1 картинка - какой-то секвенирование RNA с прошлой дз, 2 картинка - SRR5836473_1)

<p float="left">
  <img src="/fig/RNA1.png " width="400" />
  <img src="/fig/myth1_1.png" width="400" />
</p>
из этих картинок делаем вывод, что к концу секвенирования митилирования - падает quality score

<p float="left">
  <img src="/fig/RNA2.png " width="400" />
  <img src="/fig/myth2_1.png" width="400" />
</p>

У митилирования на протяжении всего секвенирования % нуклеотида одинаковый, но по количеству разный, а в RNA - стабилизуруется и становится одинаковый у всех нуклеотидов 

<p float="left">
  <img src="/fig/RNA3.png " width="400" />
  <img src="/fig/myth3_1.png" width="400" />
</p>

У митилирования график очень сильно отличается от теоритического, а у RNA - нет

### 


## 2.
### a)

![alt](./fig/task1.png)

### b)

Скрипт находится в /scr/duplicate_all.sh

![alt](./fig/task2.png)
### c)

Done. 1.5 часа, мда...

### d)
Отчеты в /html.

### e)

![alt](./fig/dist_8cell.png)

![alt](./fig/dist_epi.png)

![alt](./fig/dist_icm.png)

Код построения гистограммы(пример c ICM):

![alt](./fig/example.png)

### f)
Митилирование:

![alt](./fig/myth.png)

Покрытие:

![alt](./fig/cov.png)
