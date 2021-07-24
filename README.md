# Ocular-disease-classifier
ODIR-5K 데이터셋을 이용한 안저 질환 분류기

## Dataset
- Normal (N)
- Diabetes (D)
- Glaucoma (G)
- Cataract (C)
- Age related Macular Degeneration (A)
- Hypertension (H)
- Pathological Myopia (M)
- Other diseases/abnormalities (O)

1. only used -> A / C / G / M / N
   (5 class used because of the data unbalance)

2. data size -> 512*512

<img src="https://user-images.githubusercontent.com/59918820/126447386-db94c753-1394-4809-be45-53bd22066cc9.jpg" width="100" height="100"> <A>

<img src="https://user-images.githubusercontent.com/59918820/126447443-806ea753-b8d5-4f89-9240-6c197252a639.jpg" width="100" height="100"> <C>

<img src="https://user-images.githubusercontent.com/59918820/126447474-dadfe4f6-c3b8-4a0c-bbb4-d28f27db226c.jpg" width="100" height="100"> <G>

<img src="https://user-images.githubusercontent.com/59918820/126447508-7752e01e-88a2-4447-b1e6-6e533ba1d33d.jpg" width="100" height="100"> <M>

<img src="https://user-images.githubusercontent.com/59918820/126447539-c52bbe5e-1b72-448e-bb24-8116029d6edc.jpg" width="100" height="100"> <N>

## Sota model
- ResNet50 V2
- Xception
- EfficientNet B0
- MobileNet V1
- DenseNet121

## Embedded board
- Latte Panda
