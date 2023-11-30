# videoSwin을 이용한 버피테스트 검사

## 설치 방법

mmaction2 설치 아래 링크 참조
(https://github.com/open-mmlab/mmaction2) 

## 개발환경

google colab

## 내용

SwinTransformer 모델의 동영상 버전인 videoSwin을 이용하여 
입력된 동영상에서 사람이 수행하는 **버피테스트의 동작이 정확한지 부정확한지** 이진 분류(true, false)

## 특징

주어진 데이터의 수가 적고 라벨간 불균형이 심해(True:False = 1:9) True만 data augmentation을 통해 데이터 수를 늘림.
데이터 샘플링을 통해서 균형을 맞추기에는 주어진 데이터 수가 매우 적어 수행하지 않음(총 1000개의 동영상)


