# ๐YouTube ํด๋ก  ์ฝ๋ฉ ํ๋ก์ ํธ ๐

### ๐จ๐ปโ๐ป ํ๋ก์ ํธ ๊ธฐ๊ฐ
2021.06.01 ~  2021~06.17 

### ๐๐ป ์ฌ์ฉ๋ ๊ธฐ์  & ๋ผ์ด๋ธ๋ฌ๋ฆฌ

+ <img src="https://img.shields.io/badge/React-blue?style=flat-square&logo=React&logoColor=white"/><br/>
+ <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=Node.js&logoColor=white"/><br/>
+ <img src="https://img.shields.io/badge/Javascript-important?style=flat-square&logo=Javascript&logoColor=white"/><br/>
+ <img src="https://img.shields.io/badge/Redux-3766AB?style=flat-square&logo=Redux&logoColor=white"/><br/>
+ <img src="https://img.shields.io/badge/MongoDB-lightgray?style=flat-square&logo=MongoDB&logoColor=white"/><br/>
+ <img src="https://img.shields.io/badge/Ant Design-0170FE?style=flat-square&logo=Ant-Design&logoColor=white"/><br/>

- - - - -
### ํ๋ก์ ํธ ์คํ
    server - npm install
    client - npm install
    npm run dev
</br>

### ๐ป ํ๋ก์ ํธ ๊ตฌํ

#### 1.[LadingPage](https://github.com/hyunbeanohh/YoutubeClone/blob/main/client/src/components/views/LandingPage/LandingPage.js)
+ boiler-plate์ ๋ก๊ทธ์ธ ๊ธฐ๋ฅ์ ํตํด ๋ก๊ทธ์ธ ํ ๋์์์ ์๋ก๋ ํ  ์ ์๋๋ก ๊ตฌํ.
+ `ffmpeg`๋ฅผ ํตํด์ Thumbnail์ ์์ฑํ๊ณ  ๋น๋์ค์ ๋ํ ์ธ๋ค์ผ์ ์์ฑ ํ ๋ณด์ฌ์ค.
+ ๋ชฝ๊ณ DB์์ ํ์๋ค์ ๋ํ ์ ๋ณด๋ฅผ ์ ์ฅํ๋ฉฐ ์ ๋ณด๋ค์ ๋ฐํ์ผ๋ก ์์ ์ ๋ชฉ,์๋ก๋,์๊ฐ,์กฐํ์,์๋ก๋ ์๊ฐ์ ์ถ๋ ฅ.
+ ๊ฐ๊ฐ์ ๋น๋์ค์ ๋ง๋ ID ๊ฐ์ ์ค์ ํ์ฌ ํด๋น ๋น๋์ค์ ๋ํ ํ์ด์ง๋ก ์ด๋ํ  ์ ์๋๋ก ํจ. `http://localhost:3000/video/609514aec793ed5b50d0c52d`

#### 2.[VideoUploadPage](https://github.com/hyunbeanohh/YoutubeClone/blob/main/client/src/components/views/VideoUploadPage/VideoUploadPage.js)
+ antd์ ํตํด์ ์ ์ฒด์ ์ธ ํ์ ๊ตฌ์ฑ.
+ ๋น๋์ค์ ๋ํ ์ ๋ณด๋ ๋ชฝ๊ณ DB์ ์ ์ฅ๋๋ฉฐ ์ ์ฅ๋ ์ ๋ณด๋ค์ ๋ฐํ์ผ๋ก LandingPage์ ์ฌ๋ ค์ง๊ฒ ๋จ.

#### 3.[VideoDetailPage](https://github.com/hyunbeanohh/YoutubeClone/blob/main/client/src/components/views/VideoDetailPage/VideoDetailPage.js)
+ videoId ๊ฐ์ ๋ง๋ ๋น๋์ค๋ฅผ ๋ณด์ฌ์ฃผ๋ฉฐ ๋น๋์ค ์๋ก๋๋ฅผ ํ ํ์์๊ฒ๋ ๊ตฌ๋ ๋ฒํผ์ด ํ์ฑํ ๋์ง ์๋๋ก ํจ.
+ ๋๊ธ ๊ธฐ๋ฅ์ ๊ตฌํํ์ผ๋ฉฐ ๊ฐ ๋๊ธ์ ๋ํ ๋๋๊ธ์ ๋ณผ ์ ์๋๋ก ๊ตฌํ.
+ ๋๊ธ ์ ๋ณด๋ ๋ชฝ๊ณ DB์์ ์ ์ฅํ๊ณ  ์ ์ผ ์ต ์๋จ์ ๋๊ธ์ด๋ฉด ๋ณด์ฌ์ง์ง ์๋๋ก ํจ.
+ ๊ฐ ๋๊ธ์ ๋ํ ๊ฐ์๋ 
    - [Comment](https://github.com/hyunbeanohh/YoutubeClone/blob/main/client/src/components/views/VideoDetailPage/Section/Comment.js)
        + 3-1. VideoDetailPage์ Comment State์ ์ ์ฅ๋๋ฉฐ ๊ฐ ์์ ์ปดํฌ๋ํธ๋ค์๊ฒ ์ ๋ฌ๋๊ณ  
        + 3-2. ReplyComment์์ map ๋ฉ์๋๋ฅผ ํตํด ๊ณ์ฐ ํ 
        + 3-3. setChildStateNumner์ ์ ์ฅ๋์ด ChildStateNumber๋ก ๋ ๋๋ง ๋จ.
+ SideVideo๋ ์ค๋ฅธ์ชฝ Nav์ ๋ ๋๋ง๋๋ฉฐ ๋ชฝ๊ณ DB์ ์ ์ฅ๋์ด ์๋ ๋น๋์ค๋ค์ ์ ๋ณด๋ฅผ ๊ฐ์ ธ์ ์ถ๋ ฅํจ.
+ ๊ฐ๊ฐ์ SideVideo๋ ๊ณ ์  id๊ฐ์ด ๋งํฌ๋์ด ์์ผ๋ฉฐ ํด๋ฆญ์ ํด๋น ๋น๋์ค ํ์ด์ง๋ก ์ด๋ํจ.
+ ์ข์์,์ซ์ด์์ ๋ํ ๊ธฐ๋ฅ์ ๊ตฌํํ์ฌ ๊ฐ๊ฐ์ ๋ฒํผ ํด๋ฆญ์ ์ข์์,์ซ์ด์ ์ซ์๊ฐ ์ฆ๊ฐ,๊ฐ์ํจ.

#### 4.[SubscriptionPage](https://github.com/hyunbeanohh/YoutubeClone/blob/main/client/src/components/views/SubscriptionPage/SubscriptionPage.js)
+ ๋น๋์ค์ ๋ํ ์ ๋ณด๋ฅผ ๋ชฝ๊ณ DB์์ ๋ฐ์์ ๊ตฌ๋ํ๋ ๋น๋์ค์ ์ ๋ณด๋ฅผ ์ถ๋ ฅ.
+ ๋น๋์ค๊ฐ ๋ง์์ง๋ค๋ฉด antd์ ํตํด์ ์ ์ ํ๊ฒ ๋๋์ด ์ง ์ ์๋๋ก lg,md,xs ๋ง๋ค ์ฌ์ด์ฆ ๊ตฌํ.
+ ๊ตฌ๋ํ๊ณ  ์๋ ๋น๋์ค์ ์ธ๋ค์ผ์ map ํจ์๋ฅผ ํตํด ๊ฐ๊ฐ ์ธ๋ค์ผ ์ด๋ฏธ์ง๋ฅผ ์ถ๋ ฅ ํ  ์ ์๋๋ก ํจ.

- - - - -


### ๐ก ํ๋ก์ ํธ ๊ฒฐ๊ณผ
1. LadingPage
<img width="720" alt="LandingPage" src="https://user-images.githubusercontent.com/39178226/122348922-a1ad7980-cf86-11eb-81eb-c65b7343ed8d.png">
</br>


2.VideoUploadPage
<img width="720" alt="VideoUploadPage" src="https://user-images.githubusercontent.com/39178226/122351874-8a23c000-cf89-11eb-9f63-4cfb61d064b1.png">


3.VideoDetailPage
<img width="720" alt="VideoDetailPage" src="https://user-images.githubusercontent.com/39178226/122349053-cd306400-cf86-11eb-9fa6-5bdb6bcf780a.png">
</br>


4.Comment
<br/>
<img width="720" alt="Comment Part" src="https://user-images.githubusercontent.com/39178226/122349192-f5b85e00-cf86-11eb-9c24-2ac6076d2816.png">
</br>

5.SubscriptionPage
<img width="720" alt="SubscriptionPage" src="https://user-images.githubusercontent.com/39178226/122349278-11236900-cf87-11eb-95de-f6d3d1f75473.png">
</br>

- - - - -

### โ๏ธ๋๋์  ๋ฐ ํ๋ค์๋ ์ 
    1.๋ถ๋ชจ ์ปดํฌ๋ํธ์ ์์ ์ปดํฌ๋ํธ๋ค์ props๋ฅผ ์ ๋ฌํ๋ ๋ฐฉ์์ด ์ด๋ ค์์ ๋ค์ํ ์๋ฃ๋ฅผ ์ฐพ์๊ฐ๋ฉด์ ๊ณต๋ถ๋ฅผ ํ๊ฒ ๋์๋ค.
    2.route์์ client๋ถ๋ถ์ผ๋ก DB์ ์ ๋ณด๋ค์ ๋ณด๋ด์ค๋ ๋ํ๋๋ ์๋ฌ๋ค์ ์ก์ง ๋ชปํ๋๋ฐ proxy ๊ด๋ จ ์๋ฌ์ด๊ธฐ ๋๋ฌธ์ ๊ณต๋ถ๋ฅผ ๋ ํด์ ์๋ฌ๋ฅผ ์์ ํ  ์ ์๋๋ก ํด์ผ๊ฒ ๋ค.
    3.DB์ ์คํค๋ง๋ฅผ ๊ฐ๊ฐ ๊ตฌํํ๋ฉด์ ํ๋ก ํธ ๋จ์ ๋ฟ๋ ค์ฃผ๋ ๊ฒ์ด ์ฌ์ด ์์์ด ์๋๋ผ๋๊ฒ์ ๊นจ๋ฌ์๋ค.
    4.antd์ ์ฌ์ฉํ๋ฉด์ ๊ฐ๋จํ ๋์์ธ์ ๊ตฌํํ  ์ ์๊ฒ ๋์๋ค.
    5.๊ฐ๊ฐ์ ์ปดํฌ๋ํธ๋ฅผ ์ ์ ํ๊ฒ ํ์ฉํ์ฌ ์ฌ์ฌ์ฉํ  ์ ์๋๋ก ๊ด๋ฆฌํด์ผ ํ๋ค.
    6.ํจ์์ ๋ค์ด๋ฐ์ ์ข ๋ ์์๋ณผ ์ ์๋๋ก ์์ฑํ๊ณ  ์ฝ๋ ๊ฐ๋์ฑ์ ๋์ฌ์ผ ํ๋ค.
    7.๋๊ธ์ ์ถ๊ฐํ  ๋ ์น์ด ๋๋ ค์ง๋ ๊ฒฝ์ฐ๊ฐ ์๋๋ฐ ์ต์ ํ๋ฅผ ๊ณ ๋ฏผํด๋ด์ผ ๊ฒ ๋ค.
    8.Redux๋ฅผ ์ด์ฉํ ์ํ๊ด๋ฆฌ๊ฐ ๋งค์ฐ ํธํ๋ค๋๊ฒ์ ์๊ฒ ๋์๋ค.
    9.๋๋ฒ์งธ ํด๋ก ์ฝ๋ฉ์ ํ๋๋ฐ ์ด๋์ ๋ ๋์ ๋ค์ด์จ๋ค๋๊ฒ ๋ฟ๋ฏํ๋ค.

### ์ฐธ๊ณ ์๋ฃ
[์ธํ๋ฐ](https://www.inflearn.com/course/%EB%94%B0%EB%9D%BC%ED%95%98%EB%A9%B0-%EB%B0%B0%EC%9A%B0%EB%8A%94-%EB%85%B8%EB%93%9C-%EB%A6%AC%EC%95%A1%ED%8A%B8-%EC%9C%A0%ED%8A%9C%EB%B8%8C-%EB%A7%8C%EB%93%A4%EA%B8%B0/dashboard)
