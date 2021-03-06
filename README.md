# skypotato.github.io
skypotato's git blog coming soon.<br>

## History
- 2020.07.31 : 
>요즘 티스토리 블로그 활동도 점점 뜸해지고, Git에 더욱 친숙해 지기 위해 Git Blog를 만들어 보기로 결심했다.<br>
열심히 찾아보니 Jekll로 작성하는 방법과 Hexo이 있었는데, <br> 
더 많은 사람이 선택한 Jekll를 선택하게 되었다.
- 2020.08.10 :
>다른 약속에 바쁘다가 드디어 맥북에 사용환경 구성을 했다. 짬짬히 가이드 따라 구성해볼 계획이다.
- 2020.08.16 : 
>연휴가 되어 시간이 조금 생겨 해당 프로젝트를 진행하는 중...

## 목차

- [Jekyll 사용 환경 구성](#jekyll-사용-환경-구성)
    - [전제조건](#전제조건)
    - [사용 환경 확인](#사용-환경-확인)
- [참고](#참고)

## Jekyll 사용 환경 구성

### 전제조건
[전제조건](http://jekyllrb-ko.github.io/docs/installation/#requirements)에서 각 운영체제에 맞는 가이드를 따라 환경을 구성하면 된다.

- [Ruby 설치](https://www.ruby-lang.org/en/downloads/)
- [MinGW 설치](http://www.mingw.org/)
- [Make 설치](http://gnuwin32.sourceforge.net/packages/make.htm)

### 사용 환경 확인
```shell script
ruby -v #Ruby
gem -v #RubyGems
gcc -v #GCC <- window 환경에서는 MinGW 설치
g++ -v #GCC <- window 환경에서는 MinGW 설치
make -v #Make
```

## Jekyll 시작하기

### Bundle 구성
./myblog 에 새 Jekyll 사이트를 생성한다.

~~~shell script
jekyll new myblog
~~~

### 로컬 서버 적용
생성된 bundle의 경로로 이동하여 아래 명령어로 사이트를 빌드하고 로컬 서버에 적용한다.

~~~shell script
bundle exec jekyll serve
~~~

### 로컬 서버 확인
그 후 브라우저를 통해 [http://localhost:4000](http://localhost:4000)를 확인한다.

![Jekll 첫번째 페이지](./assets/img/FirstJekllPage.png)

### Jekll Theme 적용
마음에 드는 테마를 찾던 중 Moon Theme를 적용했다.<br>
깔끔하구 어두운 분위기가 맘에 들어 이 테마를 기초로 커스터 마이징을 진행할 예정이다.<br>
블로그에 필요한 기본 정보를 입력 후 필요 없는 기능을 제거하고 필요한 기능을 추가하여 사용해야겠다.
 
![Moon Theme 적용](./assets/img/MoonTheme.png)

## 참고
- [GitHub Pages](https://pages.github.com/)
- [Jekyll](https://jekyllrb.com/)
- [Collaborating on projects using issues and pull requests](https://help.github.com/categories/collaborating-on-projects-using-issues-and-pull-requests/)
- [Moon Theme](https://github.com/TaylanTatli/Moon)
