# Лабораторные работы по курсу:

## Методы, средства и технологии мультимедиа
Выполнил: Белоусов Е.Л., группа М8О-408Б-21

## Выбранные датасеты

Классификация: https://www.kaggle.com/datasets/nirmalsankalana/apple-tree-leaf-disease-dataset

Сегментация: https://www.kaggle.com/datasets/bulentsiyah/semantic-drone-dataset

Object Detection: https://www.kaggle.com/datasets/andrewmvd/helmet-detection

## Итоги работы

<table>
    <tr>
        <th rowspan="1">Задача</th>
        <th>Модель</th>
        <th>Бейзлайн</th>
        <th>Улучшенный бейзлайн</th>
        <th>Самостоятельная имплементация модели</th>
    </tr>
    <tr>
        <td rowspan="2">Классификация</td>
        <td>ResNet18</td>
        <td>Acc=0.9668; F1=0.9620</td>
        <td>Acc=0.9419; F1=0.9340</td>
        <td>Acc=0.9336; F1=0.9333</td>
    </tr>
    <tr>
        <td>ViT (torchvision)</td>
        <td>Acc=0.9876; F1=0.9834</td>
        <td>Acc=0.9710; F1=0.9722</td>
        <td>Acc=0.3402; F1=0.1015</td>
    </tr>
    <tr>
        <td rowspan="2">Сегментация</td>
        <td>ResNet-Unet</td>
        <td>Acc=0.4988; IoU=0.0625</td>
        <td>Acc=0.4902; IoU=0.0606</td>
        <td>Acc=0.5499; IoU=0.0954</td>
    </tr>
    <tr>
        <td>ViT-Unet</td>
        <td>Acc=0.5688; IoU=0.0730</td>
        <td>Acc=0.5059; IoU=0.0726</td>
        <td>Acc=0.2320; IoU=0.0228</td>
    </tr>
    <tr>
        <td rowspan="1">Object Detection</td>
        <td>YOLO</td>
        <td>mAP@0.5=0.806; mAP@0.5:0.95=0.469</td>
        <td>mAP@0.5=0.835; mAP@0.5:0.95=0.485</td>
        <td>mAP@0.5=0; mAP@0.5:0.95=0</td>
    </tr>
</table>