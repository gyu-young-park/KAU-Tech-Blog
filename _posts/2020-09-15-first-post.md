---
title:  "KAU 테크 블로그 시작하기"
excerpt: "너무 어려운 테크 블로그 개발"

categories:
  - Blog
  - gyu
tags:
  - Blog
  - gyu
last_modified_at: 2020-09-15T08:06:00-10:00
---
![alt]({{ site.url }}{{ site.baseurl }}/assets/images/gyu/881.jpg)
안녕하세요. 
KAU너드들의 첫번째 개발자 gyu 입니다.  

사용 방법과 규칙에 대해서 설명드리겠습니다.  

1. 글을 올리는 방법
        해당 [git_repository](https://github.com/gyu-young-park/KAU-Tech-Blog)을 다운로드 해주세요.  
        그 다음, post를 올리는 방법은 다음의 두 폴더를 이용해서 글을 올리시면 됩니다.

    ```
    _posts: 시간 별로 구분되는 포스트들을 올리는 공간입니다. 형식은 'yyyy-mm-dd-이름.md' 형식입니다.
    _pages: 시간에 구애받지 않는 글을 올리는 공간입니다. 이름.md 로 올리시면 됩니다.
    ```
    각 post와 page들에는 상단에 다음과 같은 YFM가 있습니다. 
    해당 YFM은 현재 게시물의 YFM입니다.
    ```
    ---
    title:  "KAU 테크 블로그 시작하기"
    excerpt: "너무 어려운 테크 블로그 개발"

    categories:
    - Blog
    - gyu
    tags:
    - Blog
    - gyu
    last_modified_at: 2020-09-15T08:06:00-10:00
    ---
    ```
    각 요소들이 어떤 의미인지는 알 수 있을 것 입니다. 추가적인 요소들은 아래에 블로그를 첨부해놓았으니 참고해주세요.

    * 주의 : YFM은 꼭 영어로 써주세요. 한글로 적을 시에는 인코딩에러가 발생할 수 있습니다.
    
    추가적으로, 자신이 게시물 처음에는 자신의 이름을 적어주시길 바랍니다.  
    ```
    안녕하세요. 
    KAU너드들의 첫번째 개발자 gyu 입니다.  
    ```
    이렇게 적어주시면 됩니다.  

    또한, 카테고리와 tags에 자신의 영어이름을 적어주세요.  
    ```
    categories:
    - Blog
    - gyu
    tags:
    - Blog
    - gyu
    ```
    이렇게 적어주시면 됩니다.  

    이후 markdown형식에 맞게 글을 적어주시면 됩니다.   
    따라서 모든post들과 page들은 YFM과 markdown이 같이 쓰여 있는 형식으로 되었습니다.  

2. 포스트에 이미지 추가하기  
    생각보다 어렵지만 어렵지 않습니다. 왜냐구요? 제가 여기에 적어놓기 때문이죠!  
    모든 이미지들은 assets/images 폴더에서 관리하기로 (제멋대로) 결정했습니다.  
    그리고 이미지 이름 간의 충돌을 막기위해 images 폴더 안에 각자의 영어이름 폴더를 만들어주세요.  
    저는 gyu 이니까 gyu 폴더를 만들겠습니다.   
    
    해당 폴더에 이미지를 넣어주고 다음과 같이 써줍니다.  
    ```
    ![alt]({{ site.url }}{{ site.baseurl }}/assets/images/gyu/881.jpg)
    ```
    현재 아마 gyu와 881.png 말고는 나머지는 똑같을 것 입니다.
    다만 md 파일 preview해주는 기능으로는 다음의 사진들이 안보일 것 입니다.  
    신뢰의 도약으로 써주시거나, `ruby ` 를 설치하시고 `jekyll server` 로 구동시키면, 자신의 포스트들이 어떻게 나올 지 볼 수 있습니다.

    이 밖에 사용하는 방법은 아래에 아주 잘 기술되어있습니다.  
    [기술 블로그 사용방법](https://devinlife.com/categories/)  


그럼 이만!
gyu 올림  