# 음을 그리다 - Drawing Sound (Android)
사용자에게 **작곡**과 **음악 검색** 서비스를 제공하는 Java 기반의 **Android 애플리케이션** </br></br>
<img width="250" alt="drawingsound main screenshot" src="https://user-images.githubusercontent.com/33407123/80936257-3f89c780-8e0b-11ea-8937-76929eb46ea3.png">
</br></br>

사용자로부터 *Humming*  데이터를 입력받아 다음과 같은 서비스를 제공합니다.
1. **악보 생성** </br>
    추출한 음성 데이터를 일정한 박자 단위로 변형하여 실제 오선지 상에 기보하여 악보 이미지를 생성합니다. </br></br>
2. **음악 검색** </br>
    Deep Learning을 통해 음성 데이터를 기존의 곡들과 비교하여, 목소리만으로 유사한 음악을 찾아냅니다.
</br>


## 기능 흐름도
1. **악보 생성**
<img width="700" alt="drawingsound main screenshot" src="https://user-images.githubusercontent.com/33407123/80946243-8f2abc00-8e28-11ea-9042-916cb17bbc53.png">
</br>

2. **음악 검색**
<img width="700" alt="drawingsound main screenshot" src="https://user-images.githubusercontent.com/33407123/80946247-905be900-8e28-11ea-86f1-85d19832df9a.png">
</br>


## App Image
#### 1. 작곡 </br></br>
<div>
<img width="220" height="400" alt="drawingsound screenshot" src="https://user-images.githubusercontent.com/33407123/80937597-c2f9e780-8e10-11ea-863b-07f1d03a996d.PNG">
<img width="220" height="400" alt="drawingsound screenshot" src="https://user-images.githubusercontent.com/33407123/80937599-c5f4d800-8e10-11ea-853e-2c54fd614402.PNG">
<img width="220" height="400" alt="drawingsound screenshot" src="https://user-images.githubusercontent.com/33407123/80937607-cc834f80-8e10-11ea-98a4-3661339c8f03.PNG">
</div>
</br>

 * **악보 만들기**</br>
 작곡 시작 화면으로 진입할 수 있습니다.
 
 * **허밍 시작하기**</br>
 노래를 부르면 화면에 현재 내고 있는 음이 어떤 음계인지 나타납니다.
 
 * **악보 생성하기**</br>
 허밍 종료 후, '제목', '작곡가', '분위기'를 선택하여 나만의 악보를 만들 수 있습니다.
 
</br></br>

#### 2. 악보 뷰어 </br></br>
<div>
<img width="220" height="400" alt="drawingsound screenshot" src="https://user-images.githubusercontent.com/33407123/80937746-621edf00-8e11-11ea-801d-7ad2234e220c.PNG">
<img width="220" height="400" alt="drawingsound screenshot" src="https://user-images.githubusercontent.com/33407123/80937747-63e8a280-8e11-11ea-9cf0-8a7cb70ade20.PNG">
<img width="220" height="400" alt="drawingsound screenshot" src="https://user-images.githubusercontent.com/33407123/80937748-65b26600-8e11-11ea-8f84-415ffdbc0601.PNG">
</div>
</br>

 * **분위기 선택하기**</br>
 악보 저장 시 지정했던 분위기별로 악보를 모아 볼 수 있습니다.
 
 * **악보 리스트**</br>
 선택한 분위기에 속한 악보들의 리스트가 나타납니다.
 
 * **악보 VIEW**</br>
 선택한 악보 이미지를 볼 수 있으며, 삭제할 수 있습니다.
 
</br></br>

#### 3. 음악 검색 </br></br>
<div>
<img width="220" height="400" alt="drawingsound screenshot" src="https://user-images.githubusercontent.com/33407123/80937840-a1e5c680-8e11-11ea-927d-6efda67452b0.PNG">
<img width="220" height="400" alt="drawingsound screenshot" src="https://user-images.githubusercontent.com/33407123/80937842-a4482080-8e11-11ea-80c5-a43c52dac626.PNG">
<img width="220" height="400" alt="drawingsound screenshot" src="https://user-images.githubusercontent.com/33407123/80937844-a611e400-8e11-11ea-846e-f223a08fb6bf.PNG">
</div>
</br>

 * **음악 검색하기**</br>
 음악 검색 시작 화면으로 진입할 수 있습니다.
 
 * **녹음 시작하기**</br>
 노래를 부르면 음성 데이터가 이미지로 변환되어 서버로 전송되며, 서버에서 유사한 노래를 검색합니다.
 
 * **음악 검색 결과 VIEW**</br>
 부른 노래와 유사한 노래가 나타납니다. (현재 비교 가능한 노래는 10곡입니다.)
 
</br></br>


## Develop Environment
- 개발 기간: 2019.03~2019.11
- 개발 인원: 4명
- 개발 환경: Andriod Studio, AWS EC2
- 개발 언어: Java, XML, python
- 웹 서버: Express
- 데이터베이스: Firebase
- 협업 툴: GitHub, Trello
</br>

## Demo
https://www.youtube.com/watch?v=8nIA9JS46q8
</br>
**2019 한이음 공모전 동상(한국정보연합회장상) 수상**
</br></br></br>
