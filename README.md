# 『밑바닥부터 시작하는 딥러닝』 (원서 : ゼロから作る Deep Learning)

---

:red_circle: **[긴급 공지!!]** 2017년 3월 21일 현재, 실습용 손글씨 데이터셋 다운로드 사이트( http://yann.lecun.com/exdb/mnist/ )가 연결되지 않습니다.
그래서 예제 수행에 필요한 데이터셋 파일을 임시로 /dataset/ 디렉터리에 올려뒀습니다.

**처음 시작하시는 분**은 별다른 추가 작업 없이 깃허브 소스 폴더 전체를 내려받으시면 예제를 실행해보실 수 있으며,

**이미 작업하시던 분 중 데이터셋을 아직 내려받지 않으신 분**은 /dataset/ 디렉터리에 있는 아래의 4개 파일을 내려받아 각자의 <예제 소스 홈>/dataset/ 디렉터리로 옮겨놓으시면 됩니다.

* [t10k-images-idx3-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/t10k-images-idx3-ubyte.gz)
* [t10k-labels-idx1-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/t10k-labels-idx1-ubyte.gz)
* [train-images-idx3-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/train-images-idx3-ubyte.gz)
* [train-labels-idx1-ubyte.gz](https://github.com/WegraLee/deep-learning-from-scratch/raw/master/dataset/train-labels-idx1-ubyte.gz)

★ 간단히, 위의 파일 4개를 각자의 <예제 소스 홈>/dataset/ 디렉터리 밑에 복사해두면 됩니다. ^__^

---

<img src="https://github.com/WegraLee/deep-learning-from-scratch/blob/master/cover_image.jpg" width="360">

---

이 저장소는 『[밑바닥부터 시작하는 딥러닝](http://www.hanbit.co.kr/store/books/look.php?p_code=B8475831198)』(한빛미디어, 2017)의 지원 사이트입니다.

## 새소식
:white_check_mark: **2017.02.26** - 각 챕터 디렉터리에 README.md 파일을 추가했습니다. 각 파일의 '용도', '관련 절', '등장 페이지'를 명기했고, 책에서 각 장의 '도입부', '목차', '이번 장에서 배운 내용'을 발췌해서 책이 없어도 큰 그림을 파악할 수 있도록 했습니다.

차차 파일 안의 소스 코드에도 친절한 설명을 덧붙이도록 하겠습니다.

:white_check_mark: **2017.02.20** - 3쇄가 출간되었습니다. 크고 작은 오류를 잡는 김에 책 전체를 한 번 더 교정했습니다. 그렇다고 다른 책이 된 게 아니니 1, 2쇄를 보신 분은 오탈자 정보만 확인하시면 충분합니다. 살아 있는 책으로 만들기 위해 이번처럼 기회가 올 때마다 지속해서 품질을 업그레이드할 것이니 궁금하거나 설명이 잘 이해되지 않으면 언제든 문의하세요~

## 책 미리보기
[issuu](https://issuu.com/hanbit.co.kr/docs/____________________________________38d0e6451f0ddf) | [SlideShare](http://www.slideshare.net/wegra/ss-70456623) | [Yumpu](https://www.yumpu.com/xx/document/view/56594155/-)

## 파일 구성

|폴더 이름 |설명                         |
|:--        |:--                          |
|ch01       |1장에서 사용하는 소스 코드 |
|ch02       |2장에서 사용하는 소스 코드    |
|...        |...                          |
|ch08       |8장에서 사용하는 소스 코드    |
|common     |공통으로 사용하는 소스 코드  |
|dataset    |데이터셋용 소스 코드 |


소스 코드 해설은 책을 참고하세요.

## 요구사항
소스 코드를 실행하려면 아래의 소프트웨어가 설치되어 있어야 합니다.

* 파이썬 3.x
* NumPy
* Matplotlib

※ Python은 3 버전을 이용합니다.

## 실행 방법

각 장의 디렉터리로 이동한 후 파이썬 명령을 실행하세요(**다른 디렉터리에서는 제대로 실행되지 않을 수 있습니다!**).

```
$ cd ch01
$ python man.py

$ cd ../ch05
$ python train_nueralnet.py
```

## 라이선스

이 저장소의 소스 코드는 [MIT 라이선스](http://www.opensource.org/licenses/MIT)를 따릅니다.
비상용뿐 아니라 상용으로도 자유롭게 이용하실 수 있습니다.

## 책의 오류

이 책의 오탈자 등 오류 정보는 아래 페이지에서 확인하실 수 있습니다.

http://www.hanbit.co.kr/store/books/look.php?p_code=B8475831198


## 인공지능/딥러닝 관련 도서 로드맵
[개앞맵시] 스카이넷도 딥러닝부터 : https://www.mindmeister.com/812276967/_
<a href="https://www.mindmeister.com/812276967/_"><img src="https://github.com/WegraLee/deep-learning-from-scratch/blob/master/map.png" width="720"></a>

## 머신러닝/딥러닝 번역 용어표

이 책을 번역하며 정리한 [용어표](https://docs.google.com/spreadsheets/d/1ccwGiC01X-gs3PPcXPUz67W9rS6l994LD4AL18KF1_0)입니다.
