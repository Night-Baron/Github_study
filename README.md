# Github_study
깃허브 공부용

환경: "Ubuntu 18.04.1 LTS"  
https://backlog.com/git-tutorial/kr/ && https://orga.cat/posts/most-useful-git-commands 을 참조할 예정

GIT 설치 방법
-----------
(자세한 내용은 https://git-scm.com/downloads 또는 https://git-scm.com/download/linux 참조할 것  

최신 GIT을 설치하기 위해서는 GIT에 대한 PPA(Personal Package Archive)를 설정해야한다. 

터미널에서 `sudo add-apt-repository ppa:git-core/ppa`  

![1_ppa-github](https://user-images.githubusercontent.com/17330864/52937363-49f4a880-33a2-11e9-9959-00d71f41aaa4.png)

그후 터미널에서 `sudo apt-update; sudo apt-get install git` 을 통해 GIT 설치한다.  

![2_install-git](https://user-images.githubusercontent.com/17330864/52937611-f6cf2580-33a2-11e9-8d36-bf1b25d0a0e1.png)


GIT 버전 확인
-----------
터미널에서 `git --version`
