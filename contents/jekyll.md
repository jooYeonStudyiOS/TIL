## jekyll

* jekyll ?
[공식홈페이지](https://jekyllrb-ko.github.io/)

* 지킬 다운 받기
    > gem install bundler  
    gem install jekyll

* 에러 발생 -> `루비` 미설치 
>ERROR:  While executing gem ... (Gem::FilePermissionError)
    You don't have write permissions for the /Library/Ruby/Gems/2.6.0 directory.  

(에러, 루비 페이지로 이동 예정)

* 루비 설치
> brew install rbenv ruby-build

* 루비 버전 확인
> rbenv versions

* 설치 가능한 버전 확인
> rbenv install -l

* 루비 버전 지정 설치
> rbenv install 3.2.2

* 시스템 루비를 사용하고 있는 것을 알 수 있다 
```
 jooyeonkang@Jooyeonui-iMac ~ % rbenv versions     
* system
  3.2.2
```

* 루비 변경
> rbenv global 3.2.2
```jooyeonkang@Jooyeonui-iMac ~ % rbenv versions     
  system
* 3.2.2 (set by /Users/jooyeonkang/.rbenv/version)
-> 변경된 것을 확인할 수 있음
```

```vim
export PATH={$Home}/.rbenv/bin:$PATH && \
eval "$(rbenv init -)"
```

* echo $SHELL  
/bin/zsh 설정 파일을 사용 중

* 번들 다시 다운 받고 지킬 다시 설치
git root 주소에서 실행시켜야함  
> jekyll new ./

* 번들 실행
> bundle install  


* 지킬 실행
> bundle exec jekyll serve



[참고사이트](https://blog.chulgil.me/how-to-make-blog-using-github/)
[참고사이트2](https://supermemi.tistory.com/entry/%EB%82%98%EB%A7%8C%EC%9D%98-%EB%B8%94%EB%A1%9C%EA%B7%B8-%EB%A7%8C%EB%93%A4%EA%B8%B0-Git-hub-blog-GitHubio)
