## Homebrew

* Homebrew 란  
루비로 개발된 맥용 패키지 관리 어플
설치 파일 다운해서 설치하는 것이 아닌
터미널에서 명령어로 설치할 수 있도록 도와줌

    [공식 홈페이지](https://brew.sh/index_ko)

* 설치 방법  
터미널 실행  
> /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

맥 패스워드 입력

계속 진행을 위해 엔터
> Press RETURN/ENTER to continue or any other key to abort:

M1칩일 때  
(이미지 추후 추가)
``` ==> Next steps: - Run these two commands in your terminal to add Homebrew to your PATH:
    (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/jooyeonkang/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh
```

침절하게 알려 준다 

* 버전 확인  
brew --version
>jooyeonkang@Jooyeonui-iMac ~ % brew --version
Homebrew 4.0.28

설치 완료  

[참고사이트](https://whalec.io/mac/mac-homebrew-%EC%84%A4%EC%B9%98-%EB%B0%8F-%EC%82%AC%EC%9A%A9-%EB%B0%A9%EB%B2%95/)

[참고사이트2](https://eunhee-programming.tistory.com/259)