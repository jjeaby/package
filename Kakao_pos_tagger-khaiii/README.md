#kakao pos tagger(카카오 형태소 분석기)
## python package install 방법
```
easy_install https://github.com/jjeaby/package/blob/master/Kakao_pos_tagger-khaiii/khaiii-0.2-py3.6.egg?raw=true
```
## khaiii 가 미리 설치 되어 있어야 동작한다.
## 테스트 코드
```
from khaiii import KhaiiiApi
api = KhaiiiApi()
for word in api.analyze('안녕, 세상.'):
    print(word)
```


