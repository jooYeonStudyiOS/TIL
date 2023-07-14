```
Warning: /opt/homebrew/bin is not in your PATH.
  Instructions on how to configure your shell for Homebrew
  can be found in the 'Next steps' section below.
```

homebrew 설치 시 나오는 에러  

```
==> Homebrew has enabled anonymous aggregate formulae and cask analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics data has been sent yet (nor will any be during this install run).

==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Next steps:
- Run these two commands in your terminal to add Homebrew to your PATH:
    (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/jooyeonkang/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv)"
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh
```

아마도 m1칩이라서 그런 것 같다  
여기 나와 있는 코드 2줄 입력해주면(친절한 홈브류) 에러 해결  

-> 설치 잘 됐는지 확인하는 방법  
brew --version




jooyeonkang@Jooyeonui-iMac ~ % gem install bundler 
ERROR:  While executing gem ... (Gem::FilePermissionError)
    You don't have write permissions for the /Library/Ruby/Gems/2.6.0 directory.


결론부터 말하면, 시스템 ruby를 이용하고 있기 때문에 권한이 없어 gem 설치가 안된 것입니다.

sudo를 통해 root 권한으로 실행하면 설치가 가능하지만, 보안상 이유로 권장하지 않는 설치법입니다.

그래서 rbenv를 통해 문제를 해결해보겠습니다.

 in `bind’: Address already in use - bind(2) for 127.0.0.1:4000 (Errno::EADDRINUSE)
서버가 하나 작동되고 있어서 안되었던 것인데, 비주얼코드에서 커맨드창 하나 닫으니까 잘 됐다
그 때 그게 계속 켜져 있었던 것 같음 
