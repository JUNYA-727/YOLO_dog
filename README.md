# Description 
YOLOv5を用いて自分の犬の物体検出を行うためのモデルを作成した.特にYOLOはEfficientDetに比べ速度が高く精度も向上してきており､リアルタイムで物体検出するのに適していると言えるので今回はこちらを使用してモデルを作成した｡

![yolo](https://user-images.githubusercontent.com/61785070/145219120-0cff7da3-827e-4d0e-bc97-ac82d916d481.png)

## 学習に使用したフォルダの中身
<img width="213" alt="スクリーンショット 2021-12-08 21 31 14" src="https://user-images.githubusercontent.com/61785070/145218515-55f84c45-7459-477c-a0fe-5e3b6908c97b.png">

犬と猫のラベル付けされているデータを用いて､YOLOv5を使用して学習を行った｡

## モデルの学習後
### テストデータ
![mydog](https://user-images.githubusercontent.com/61785070/145218508-e90503aa-bd01-43c3-9f72-370713a8ad85.jpg)
### 結果
![yolo_mydog](https://user-images.githubusercontent.com/61785070/145218492-67653474-04c0-404c-b81b-fb8ce9d41a98.jpg)
