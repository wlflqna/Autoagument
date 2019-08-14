참고 사이트
https://github.com/hohoins/ml/tree/master/ImageBinaryGenerator

나만의 데이터로 BIN형태로 이미지를 구성시키는 단계

예제만 하기 위헤서는 cifar10 등 이미 있는것을 해도 되지만 자신의 것 을 하려면 바이너리형태로 만들어야되요.

일단 이미지 바이너리 생성기 코드는 참고사이트에서 참고..

Bin 형태는 다음 그림과 같이 생성되어있음

<img src="./cifar10 binaray type.JPG">


augment 오류 날텐데 float error

https://github.com/aleju/imgaug/issues/358 해당 사이트에 적힌 것처럼 수정하면 에러 수정됨
