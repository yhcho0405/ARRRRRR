# ARRRRRR
Chessboard 이미지를 사용해 카매라를 Calibration하고, 그 위에 AR object 그리기
> repo 이름이 ARRRRRR인 이유는 이름을 정하던 당시 블루투스 키보드에 오류가 있었기 때문입니다.


## How to run
```
# install dependencies
$ python main.py
```

## Camera Calibration Results(example)
* The number of selected images = 11
* RMS error = 0.7079366179004347
* Camera matrix (K) = 
[[1.10277709e+03 0.00000000e+00 6.22968525e+02]
 [0.00000000e+00 1.08597696e+03 3.11474950e+02]
 [0.00000000e+00 0.00000000e+00 1.00000000e+00]]
* Distortion coefficient (k1, k2, p1, p2, k3, ...) = [ 0.14025057  0.68898444 -0.02085494 -0.00781788 -5.38093654]
> filmed with iphone14 pro (main camera, fixed focal length)

## Camera calibration
![](https://user-images.githubusercontent.com/52823519/234536482-ebd915f6-8e20-4bca-bcaa-eb85bbde28d2.png)
</br>
## Display "YH" letters in AR (initials of my name)
![](https://user-images.githubusercontent.com/52823519/234536720-4eba2273-f0e3-419d-a88b-e1ea04cb7b67.png)
</br>
## Running video
![CVAR](https://user-images.githubusercontent.com/52823519/234536241-61c54c16-c156-4fd9-b28d-ad4a9dbe73ec.gif)
