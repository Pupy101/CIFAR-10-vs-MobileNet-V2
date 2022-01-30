### Ноутбук с обучением MobileNet сетей на датасете CIFAR10


Были обучены:
1. MobileNetV2;
2. MobileNetV3 small;
3. MobileNetV3 large.

Сетки обучались с батчом 224 и аккумуляцией градиентов по 2-м батчам. Также используется следующий критерий останова обучения - сеть перестает обучаться, если значение функции потерь на тренировочном датасете превышает значение на валидационном датасете.

Accuracy на валидационном датасете:
1. [MobileNetV2](https://drive.google.com/file/d/1KiiqQEkrNgZr5NMkHf6m8C3gHMBBz_sy/view?usp=sharing) - 91.86%
2. [MobileNetV3 small](https://drive.google.com/file/d/1aP3prTYmahKbx2EnUxYSy3F5UzhTVo9n/view?usp=sharing) - 91.86%;
3. [MobileNetV3 large](https://drive.google.com/file/d/1gR0Fxdw_LL7Sa8PGKflSW5l86yQ4hxC6/view?usp=sharing) - 92.79%;
4. [MobileNetV3 large + FocalLoss](https://drive.google.com/file/d/1BCNn6ZUwjIMcSDpm7J5Gq75fNAly0NiP/view?usp=sharing) - 90.93$.


