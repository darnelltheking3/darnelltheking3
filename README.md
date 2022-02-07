- 👋 Hi, I’m @darnelltheking3
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
darnelltheking3/darnelltheking3 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# See https://help.github.com/articles/ignoring-files/ for more about ignoring files.

# dependencies
/node_modules
/.pnp
.pnp.js

# testing
/coverage

# production
/build

# misc
.DS_Store
.env
.env.local
.env.development.local
.env.test.local
.env.production.local

npm-debug.log*
yarn-debug.log*
yarn-error.log* 
 3  .vscode/settings.json 
@@ -0,0 +1,3 @@
{
    "git.ignoreLimitWarning": true
} 
 40  README.md 
@@ -0,0 +1,40 @@
![Five Nights at Freddy's](https://vignette.wikia.nocookie.net/freddy-fazbears-pizza/images/0/0c/Show_stage_nocamera.png/revision/latest?cb=20150119023526)

# ~ Five Nights at Freddy's Web

A web version I've made of the popular horror game [Five Nights at Freddy's](fnafar.com/). 
⚛️ It was made using popular technologies like [ReactJS](https://pt-br.reactjs.org/) and [Redux](https://redux.js.org/).

Uma versão na Web que eu fiz do famoso jogo de terror [Five Nights at Freddy's](fnafar.com/). 
⚛️ Foi feito usando tecnologias populares como [ReactJS](https://pt-br.reactjs.org/) e [Redux](https://redux.js.org/).

## VERSION 3.0 ⭐
- Added custom night!

~ Link: [https://five-nights-at-freddys-web.herokuapp.com/](https://five-nights-at-freddys-web.herokuapp.com/)

![Five Nights at Freddy's](https://wendelldesousa.netlify.app/assets/FNAF.webp)

## Installation

First you need to clone this repository

```
git clone https://github.com/wellsousaaa/Five-Nights-at-Freddys-Web.git
```

Then start it using npm or yarn

```
npm install
```

Then start localhost

```
npm start
```

## Credits

This project was made by Wendell Sousa :D
 103  asset-manifest.json 
This file was deleted.

 1  index.html 
This file was deleted.

 41  package.json 
@@ -0,0 +1,41 @@
{
  "name": "fnaf",
  "version": "0.1.0",
  "private": true,
  "homepage": "http://wellsousaaa.github.io/five-nights-at-freddys",
  "dependencies": {
    "@testing-library/jest-dom": "^4.2.4",
    "@testing-library/react": "^9.3.2",
    "@testing-library/user-event": "^7.1.2",
    "gh-pages": "^3.2.3",
    "react": "^16.13.1",
    "react-dom": "^16.13.1",
    "react-image-mapper": "^0.0.15",
    "react-redux": "^7.2.2",
    "react-scripts": "3.4.1",
    "redux": "^4.0.5"
  },
  "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
    "start": "react-scripts start",
    "build": "react-scripts build",
    "test": "react-scripts test",
    "eject": "react-scripts eject"
  },
  "eslintConfig": {
    "extends": "react-app"
  },
  "browserslist": {
    "production": [
      ">0.2%",
      "not dead",
      "not op_mini all"
    ],
    "development": [
      "last 1 chrome version",
      "last 1 firefox version",
      "last 1 safari version"
    ]
  }
}
 362  precache-manifest.1bcec33662cf983227433b51595f1723.js 
This file was deleted.

 0  favicon.ico → public/favicon.ico 
File renamed without changes.
 0  icon-192x192.png → public/icon-192x192.png 
File renamed without changes.
 0  icon-256x256.png → public/icon-256x256.png 
File renamed without changes.
 0  icon-384x384.png → public/icon-384x384.png 
File renamed without changes.
 0  icon-512x512.png → public/icon-512x512.png 
File renamed without changes.
 29  public/index.html 
@@ -0,0 +1,29 @@
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <link rel="icon" href="%PUBLIC_URL%/favicon.ico" />
    <meta name="viewport" content="minimal-ui, width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
    <meta name="theme-color" content="#000000" />
    <meta name="author" content="Wendell de Sousa" />
    <meta name="description" content="A web version of the popular game Five Nights at Freddy's" />

    <link rel="manifest" href="%PUBLIC_URL%/manifest.json" />

    <title>Five Nights at Freddy's Web</title>
  </head>

  <body>
    <noscript>You need to enable JavaScript to run this app.</noscript>

    <div id="root"></div>

    <script>
      var css = "text-shadow: -1px -1px hsl(0,100%,50%), 1px 1px hsl(5.4, 100%, 50%), 3px 2px hsl(10.8, 100%, 50%), 5px 3px hsl(16.2, 100%, 50%), 7px 4px hsl(21.6, 100%, 50%), 9px 5px hsl(27, 100%, 50%), 11px 6px hsl(32.4, 100%, 50%), 13px 7px hsl(37.8, 100%, 50%), 14px 8px hsl(43.2, 100%, 50%), 16px 9px hsl(48.6, 100%, 50%), 18px 10px hsl(54, 100%, 50%), 20px 11px hsl(59.4, 100%, 50%), 22px 12px hsl(64.8, 100%, 50%), 23px 13px hsl(70.2, 100%, 50%), 25px 14px hsl(75.6, 100%, 50%), 27px 15px hsl(81, 100%, 50%), 28px 16px hsl(86.4, 100%, 50%), 30px 17px hsl(91.8, 100%, 50%), 32px 18px hsl(97.2, 100%, 50%), 33px 19px hsl(102.6, 100%, 50%), 35px 20px hsl(108, 100%, 50%), 36px 21px hsl(113.4, 100%, 50%), 38px 22px hsl(118.8, 100%, 50%), 39px 23px hsl(124.2, 100%, 50%), 41px 24px hsl(129.6, 100%, 50%), 42px 25px hsl(135, 100%, 50%), 43px 26px hsl(140.4, 100%, 50%), 45px 27px hsl(145.8, 100%, 50%), 46px 28px hsl(151.2, 100%, 50%), 47px 29px hsl(156.6, 100%, 50%), 48px 30px hsl(162, 100%, 50%), 49px 31px hsl(167.4, 100%, 50%), 50px 32px hsl(172.8, 100%, 50%), 51px 33px hsl(178.2, 100%, 50%), 52px 34px hsl(183.6, 100%, 50%), 53px 35px hsl(189, 100%, 50%), 54px 36px hsl(194.4, 100%, 50%), 55px 37px hsl(199.8, 100%, 50%), 55px 38px hsl(205.2, 100%, 50%), 56px 39px hsl(210.6, 100%, 50%), 57px 40px hsl(216, 100%, 50%), 57px 41px hsl(221.4, 100%, 50%), 58px 42px hsl(226.8, 100%, 50%), 58px 43px hsl(232.2, 100%, 50%), 58px 44px hsl(237.6, 100%, 50%), 59px 45px hsl(243, 100%, 50%), 59px 46px hsl(248.4, 100%, 50%), 59px 47px hsl(253.8, 100%, 50%), 59px 48px hsl(259.2, 100%, 50%), 59px 49px hsl(264.6, 100%, 50%), 60px 50px hsl(270, 100%, 50%), 59px 51px hsl(275.4, 100%, 50%), 59px 52px hsl(280.8, 100%, 50%), 59px 53px hsl(286.2, 100%, 50%), 59px 54px hsl(291.6, 100%, 50%), 59px 55px hsl(297, 100%, 50%), 58px 56px hsl(302.4, 100%, 50%), 58px 57px hsl(307.8, 100%, 50%), 58px 58px hsl(313.2, 100%, 50%), 57px 59px hsl(318.6, 100%, 50%), 57px 60px hsl(324, 100%, 50%), 56px 61px hsl(329.4, 100%, 50%), 55px 62px hsl(334.8, 100%, 50%), 55px 63px hsl(340.2, 100%, 50%), 54px 64px hsl(345.6, 100%, 50%), 53px 65px hsl(351, 100%, 50%), 52px 66px hsl(356.4, 100%, 50%), 51px 67px hsl(361.8, 100%, 50%), 50px 68px hsl(367.2, 100%, 50%), 49px 69px hsl(372.6, 100%, 50%), 48px 70px hsl(378, 100%, 50%), 47px 71px hsl(383.4, 100%, 50%), 46px 72px hsl(388.8, 100%, 50%), 45px 73px hsl(394.2, 100%, 50%), 43px 74px hsl(399.6, 100%, 50%), 42px 75px hsl(405, 100%, 50%), 41px 76px hsl(410.4, 100%, 50%), 39px 77px hsl(415.8, 100%, 50%), 38px 78px hsl(421.2, 100%, 50%), 36px 79px hsl(426.6, 100%, 50%), 35px 80px hsl(432, 100%, 50%), 33px 81px hsl(437.4, 100%, 50%), 32px 82px hsl(442.8, 100%, 50%), 30px 83px hsl(448.2, 100%, 50%), 28px 84px hsl(453.6, 100%, 50%), 27px 85px hsl(459, 100%, 50%), 25px 86px hsl(464.4, 100%, 50%), 23px 87px hsl(469.8, 100%, 50%), 22px 88px hsl(475.2, 100%, 50%), 20px 89px hsl(480.6, 100%, 50%), 18px 90px hsl(486, 100%, 50%), 16px 91px hsl(491.4, 100%, 50%), 14px 92px hsl(496.8, 100%, 50%), 13px 93px hsl(502.2, 100%, 50%), 11px 94px hsl(507.6, 100%, 50%), 9px 95px hsl(513, 100%, 50%), 7px 96px hsl(518.4, 100%, 50%), 5px 97px hsl(523.8, 100%, 50%), 3px 98px hsl(529.2, 100%, 50%), 1px 99px hsl(534.6, 100%, 50%), 7px 100px hsl(540, 100%, 50%), -1px 101px hsl(545.4, 100%, 50%), -3px 102px hsl(550.8, 100%, 50%), -5px 103px hsl(556.2, 100%, 50%), -7px 104px hsl(561.6, 100%, 50%), -9px 105px hsl(567, 100%, 50%), -11px 106px hsl(572.4, 100%, 50%), -13px 107px hsl(577.8, 100%, 50%), -14px 108px hsl(583.2, 100%, 50%), -16px 109px hsl(588.6, 100%, 50%), -18px 110px hsl(594, 100%, 50%), -20px 111px hsl(599.4, 100%, 50%), -22px 112px hsl(604.8, 100%, 50%), -23px 113px hsl(610.2, 100%, 50%), -25px 114px hsl(615.6, 100%, 50%), -27px 115px hsl(621, 100%, 50%), -28px 116px hsl(626.4, 100%, 50%), -30px 117px hsl(631.8, 100%, 50%), -32px 118px hsl(637.2, 100%, 50%), -33px 119px hsl(642.6, 100%, 50%), -35px 120px hsl(648, 100%, 50%), -36px 121px hsl(653.4, 100%, 50%), -38px 122px hsl(658.8, 100%, 50%), -39px 123px hsl(664.2, 100%, 50%), -41px 124px hsl(669.6, 100%, 50%), -42px 125px hsl(675, 100%, 50%), -43px 126px hsl(680.4, 100%, 50%), -45px 127px hsl(685.8, 100%, 50%), -46px 128px hsl(691.2, 100%, 50%), -47px 129px hsl(696.6, 100%, 50%), -48px 130px hsl(702, 100%, 50%), -49px 131px hsl(707.4, 100%, 50%), -50px 132px hsl(712.8, 100%, 50%), -51px 133px hsl(718.2, 100%, 50%), -52px 134px hsl(723.6, 100%, 50%), -53px 135px hsl(729, 100%, 50%), -54px 136px hsl(734.4, 100%, 50%), -55px 137px hsl(739.8, 100%, 50%), -55px 138px hsl(745.2, 100%, 50%), -56px 139px hsl(750.6, 100%, 50%), -57px 140px hsl(756, 100%, 50%), -57px 141px hsl(761.4, 100%, 50%), -58px 142px hsl(766.8, 100%, 50%), -58px 143px hsl(772.2, 100%, 50%), -58px 144px hsl(777.6, 100%, 50%), -59px 145px hsl(783, 100%, 50%), -59px 146px hsl(788.4, 100%, 50%), -59px 147px hsl(793.8, 100%, 50%), -59px 148px hsl(799.2, 100%, 50%), -59px 149px hsl(804.6, 100%, 50%), -60px 150px hsl(810, 100%, 50%), -59px 151px hsl(815.4, 100%, 50%), -59px 152px hsl(820.8, 100%, 50%), -59px 153px hsl(826.2, 100%, 50%), -59px 154px hsl(831.6, 100%, 50%), -59px 155px hsl(837, 100%, 50%), -58px 156px hsl(842.4, 100%, 50%), -58px 157px hsl(847.8, 100%, 50%), -58px 158px hsl(853.2, 100%, 50%), -57px 159px hsl(858.6, 100%, 50%), -57px 160px hsl(864, 100%, 50%), -56px 161px hsl(869.4, 100%, 50%), -55px 162px hsl(874.8, 100%, 50%), -55px 163px hsl(880.2, 100%, 50%), -54px 164px hsl(885.6, 100%, 50%), -53px 165px hsl(891, 100%, 50%), -52px 166px hsl(896.4, 100%, 50%), -51px 167px hsl(901.8, 100%, 50%), -50px 168px hsl(907.2, 100%, 50%), -49px 169px hsl(912.6, 100%, 50%), -48px 170px hsl(918, 100%, 50%), -47px 171px hsl(923.4, 100%, 50%), -46px 172px hsl(928.8, 100%, 50%), -45px 173px hsl(934.2, 100%, 50%), -43px 174px hsl(939.6, 100%, 50%), -42px 175px hsl(945, 100%, 50%), -41px 176px hsl(950.4, 100%, 50%), -39px 177px hsl(955.8, 100%, 50%), -38px 178px hsl(961.2, 100%, 50%), -36px 179px hsl(966.6, 100%, 50%), -35px 180px hsl(972, 100%, 50%), -33px 181px hsl(977.4, 100%, 50%), -32px 182px hsl(982.8, 100%, 50%), -30px 183px hsl(988.2, 100%, 50%), -28px 184px hsl(993.6, 100%, 50%), -27px 185px hsl(999, 100%, 50%), -25px 186px hsl(1004.4, 100%, 50%), -23px 187px hsl(1009.8, 100%, 50%), -22px 188px hsl(1015.2, 100%, 50%), -20px 189px hsl(1020.6, 100%, 50%), -18px 190px hsl(1026, 100%, 50%), -16px 191px hsl(1031.4, 100%, 50%), -14px 192px hsl(1036.8, 100%, 50%), -13px 193px hsl(1042.2, 100%, 50%), -11px 194px hsl(1047.6, 100%, 50%), -9px 195px hsl(1053, 100%, 50%), -7px 196px hsl(1058.4, 100%, 50%), -5px 197px hsl(1063.8, 100%, 50%), -3px 198px hsl(1069.2, 100%, 50%), -1px 199px hsl(1074.6, 100%, 50%), -1px 200px hsl(1080, 100%, 50%), 1px 201px hsl(1085.4, 100%, 50%), 3px 202px hsl(1090.8, 100%, 50%), 5px 203px hsl(1096.2, 100%, 50%), 7px 204px hsl(1101.6, 100%, 50%), 9px 205px hsl(1107, 100%, 50%), 11px 206px hsl(1112.4, 100%, 50%), 13px 207px hsl(1117.8, 100%, 50%), 14px 208px hsl(1123.2, 100%, 50%), 16px 209px hsl(1128.6, 100%, 50%), 18px 210px hsl(1134, 100%, 50%), 20px 211px hsl(1139.4, 100%, 50%), 22px 212px hsl(1144.8, 100%, 50%), 23px 213px hsl(1150.2, 100%, 50%), 25px 214px hsl(1155.6, 100%, 50%), 27px 215px hsl(1161, 100%, 50%), 28px 216px hsl(1166.4, 100%, 50%), 30px 217px hsl(1171.8, 100%, 50%), 32px 218px hsl(1177.2, 100%, 50%), 33px 219px hsl(1182.6, 100%, 50%), 35px 220px hsl(1188, 100%, 50%), 36px 221px hsl(1193.4, 100%, 50%), 38px 222px hsl(1198.8, 100%, 50%), 39px 223px hsl(1204.2, 100%, 50%), 41px 224px hsl(1209.6, 100%, 50%), 42px 225px hsl(1215, 100%, 50%), 43px 226px hsl(1220.4, 100%, 50%), 45px 227px hsl(1225.8, 100%, 50%), 46px 228px hsl(1231.2, 100%, 50%), 47px 229px hsl(1236.6, 100%, 50%), 48px 230px hsl(1242, 100%, 50%), 49px 231px hsl(1247.4, 100%, 50%), 50px 232px hsl(1252.8, 100%, 50%), 51px 233px hsl(1258.2, 100%, 50%), 52px 234px hsl(1263.6, 100%, 50%), 53px 235px hsl(1269, 100%, 50%), 54px 236px hsl(1274.4, 100%, 50%), 55px 237px hsl(1279.8, 100%, 50%), 55px 238px hsl(1285.2, 100%, 50%), 56px 239px hsl(1290.6, 100%, 50%), 57px 240px hsl(1296, 100%, 50%), 57px 241px hsl(1301.4, 100%, 50%), 58px 242px hsl(1306.8, 100%, 50%), 58px 243px hsl(1312.2, 100%, 50%), 58px 244px hsl(1317.6, 100%, 50%), 59px 245px hsl(1323, 100%, 50%), 59px 246px hsl(1328.4, 100%, 50%), 59px 247px hsl(1333.8, 100%, 50%), 59px 248px hsl(1339.2, 100%, 50%), 59px 249px hsl(1344.6, 100%, 50%), 60px 250px hsl(1350, 100%, 50%), 59px 251px hsl(1355.4, 100%, 50%), 59px 252px hsl(1360.8, 100%, 50%), 59px 253px hsl(1366.2, 100%, 50%), 59px 254px hsl(1371.6, 100%, 50%), 59px 255px hsl(1377, 100%, 50%), 58px 256px hsl(1382.4, 100%, 50%), 58px 257px hsl(1387.8, 100%, 50%), 58px 258px hsl(1393.2, 100%, 50%), 57px 259px hsl(1398.6, 100%, 50%), 57px 260px hsl(1404, 100%, 50%), 56px 261px hsl(1409.4, 100%, 50%), 55px 262px hsl(1414.8, 100%, 50%), 55px 263px hsl(1420.2, 100%, 50%), 54px 264px hsl(1425.6, 100%, 50%), 53px 265px hsl(1431, 100%, 50%), 52px 266px hsl(1436.4, 100%, 50%), 51px 267px hsl(1441.8, 100%, 50%), 50px 268px hsl(1447.2, 100%, 50%), 49px 269px hsl(1452.6, 100%, 50%), 48px 270px hsl(1458, 100%, 50%), 47px 271px hsl(1463.4, 100%, 50%), 46px 272px hsl(1468.8, 100%, 50%), 45px 273px hsl(1474.2, 100%, 50%), 43px 274px hsl(1479.6, 100%, 50%), 42px 275px hsl(1485, 100%, 50%), 41px 276px hsl(1490.4, 100%, 50%), 39px 277px hsl(1495.8, 100%, 50%), 38px 278px hsl(1501.2, 100%, 50%), 36px 279px hsl(1506.6, 100%, 50%), 35px 280px hsl(1512, 100%, 50%), 33px 281px hsl(1517.4, 100%, 50%), 32px 282px hsl(1522.8, 100%, 50%), 30px 283px hsl(1528.2, 100%, 50%), 28px 284px hsl(1533.6, 100%, 50%), 27px 285px hsl(1539, 100%, 50%), 25px 286px hsl(1544.4, 100%, 50%), 23px 287px hsl(1549.8, 100%, 50%), 22px 288px hsl(1555.2, 100%, 50%), 20px 289px hsl(1560.6, 100%, 50%), 18px 290px hsl(1566, 100%, 50%), 16px 291px hsl(1571.4, 100%, 50%), 14px 292px hsl(1576.8, 100%, 50%), 13px 293px hsl(1582.2, 100%, 50%), 11px 294px hsl(1587.6, 100%, 50%), 9px 295px hsl(1593, 100%, 50%), 7px 296px hsl(1598.4, 100%, 50%), 5px 297px hsl(1603.8, 100%, 50%), 3px 298px hsl(1609.2, 100%, 50%), 1px 299px hsl(1614.6, 100%, 50%), 2px 300px hsl(1620, 100%, 50%), -1px 301px hsl(1625.4, 100%, 50%), -3px 302px hsl(1630.8, 100%, 50%), -5px 303px hsl(1636.2, 100%, 50%), -7px 304px hsl(1641.6, 100%, 50%), -9px 305px hsl(1647, 100%, 50%), -11px 306px hsl(1652.4, 100%, 50%), -13px 307px hsl(1657.8, 100%, 50%), -14px 308px hsl(1663.2, 100%, 50%), -16px 309px hsl(1668.6, 100%, 50%), -18px 310px hsl(1674, 100%, 50%), -20px 311px hsl(1679.4, 100%, 50%), -22px 312px hsl(1684.8, 100%, 50%), -23px 313px hsl(1690.2, 100%, 50%), -25px 314px hsl(1695.6, 100%, 50%), -27px 315px hsl(1701, 100%, 50%), -28px 316px hsl(1706.4, 100%, 50%), -30px 317px hsl(1711.8, 100%, 50%), -32px 318px hsl(1717.2, 100%, 50%), -33px 319px hsl(1722.6, 100%, 50%), -35px 320px hsl(1728, 100%, 50%), -36px 321px hsl(1733.4, 100%, 50%), -38px 322px hsl(1738.8, 100%, 50%), -39px 323px hsl(1744.2, 100%, 50%), -41px 324px hsl(1749.6, 100%, 50%), -42px 325px hsl(1755, 100%, 50%), -43px 326px hsl(1760.4, 100%, 50%), -45px 327px hsl(1765.8, 100%, 50%), -46px 328px hsl(1771.2, 100%, 50%), -47px 329px hsl(1776.6, 100%, 50%), -48px 330px hsl(1782, 100%, 50%), -49px 331px hsl(1787.4, 100%, 50%), -50px 332px hsl(1792.8, 100%, 50%), -51px 333px hsl(1798.2, 100%, 50%), -52px 334px hsl(1803.6, 100%, 50%), -53px 335px hsl(1809, 100%, 50%), -54px 336px hsl(1814.4, 100%, 50%), -55px 337px hsl(1819.8, 100%, 50%), -55px 338px hsl(1825.2, 100%, 50%), -56px 339px hsl(1830.6, 100%, 50%), -57px 340px hsl(1836, 100%, 50%), -57px 341px hsl(1841.4, 100%, 50%), -58px 342px hsl(1846.8, 100%, 50%), -58px 343px hsl(1852.2, 100%, 50%), -58px 344px hsl(1857.6, 100%, 50%), -59px 345px hsl(1863, 100%, 50%), -59px 346px hsl(1868.4, 100%, 50%), -59px 347px hsl(1873.8, 100%, 50%), -59px 348px hsl(1879.2, 100%, 50%), -59px 349px hsl(1884.6, 100%, 50%), -60px 350px hsl(1890, 100%, 50%), -59px 351px hsl(1895.4, 100%, 50%), -59px 352px hsl(1900.8, 100%, 50%), -59px 353px hsl(1906.2, 100%, 50%), -59px 354px hsl(1911.6, 100%, 50%), -59px 355px hsl(1917, 100%, 50%), -58px 356px hsl(1922.4, 100%, 50%), -58px 357px hsl(1927.8, 100%, 50%), -58px 358px hsl(1933.2, 100%, 50%), -57px 359px hsl(1938.6, 100%, 50%), -57px 360px hsl(1944, 100%, 50%), -56px 361px hsl(1949.4, 100%, 50%), -55px 362px hsl(1954.8, 100%, 50%), -55px 363px hsl(1960.2, 100%, 50%), -54px 364px hsl(1965.6, 100%, 50%), -53px 365px hsl(1971, 100%, 50%), -52px 366px hsl(1976.4, 100%, 50%), -51px 367px hsl(1981.8, 100%, 50%), -50px 368px hsl(1987.2, 100%, 50%), -49px 369px hsl(1992.6, 100%, 50%), -48px 370px hsl(1998, 100%, 50%), -47px 371px hsl(2003.4, 100%, 50%), -46px 372px hsl(2008.8, 100%, 50%), -45px 373px hsl(2014.2, 100%, 50%), -43px 374px hsl(2019.6, 100%, 50%), -42px 375px hsl(2025, 100%, 50%), -41px 376px hsl(2030.4, 100%, 50%), -39px 377px hsl(2035.8, 100%, 50%), -38px 378px hsl(2041.2, 100%, 50%), -36px 379px hsl(2046.6, 100%, 50%), -35px 380px hsl(2052, 100%, 50%), -33px 381px hsl(2057.4, 100%, 50%), -32px 382px hsl(2062.8, 100%, 50%), -30px 383px hsl(2068.2, 100%, 50%), -28px 384px hsl(2073.6, 100%, 50%), -27px 385px hsl(2079, 100%, 50%), -25px 386px hsl(2084.4, 100%, 50%), -23px 387px hsl(2089.8, 100%, 50%), -22px 388px hsl(2095.2, 100%, 50%), -20px 389px hsl(2100.6, 100%, 50%), -18px 390px hsl(2106, 100%, 50%), -16px 391px hsl(2111.4, 100%, 50%), -14px 392px hsl(2116.8, 100%, 50%), -13px 393px hsl(2122.2, 100%, 50%), -11px 394px hsl(2127.6, 100%, 50%), -9px 395px hsl(2133, 100%, 50%), -7px 396px hsl(2138.4, 100%, 50%), -5px 397px hsl(2143.8, 100%, 50%), -3px 398px hsl(2149.2, 100%, 50%), -1px 399px hsl(2154.6, 100%, 50%); font-size: 40px;";
      console.log("Made by")
      console.log("%cWendell Sousa", css);
      console.log("~ 2020");

      </script>
  </body>
</html>
 0  manifest.json → public/manifest.json 
File renamed without changes.
 0  robots.txt → public/robots.txt 
File renamed without changes.
 39  service-worker.js 
This file was deleted.

 135  src/Controller.js 
@@ -0,0 +1,135 @@
import React, { useState, useEffect } from "react";
import BlackoutSound from "./media/Sounds/powerdown.mp3";
import { connect } from "react-redux";
import Game from "./Game";

import StaticImage from "./media/Textures/Static-Cam.webp";
import StaticSound from "./media/Sounds/Dead.mp3";
import VictoryGIF from "./media/Textures/Victory.gif";
import VictorySound from "./media/Sounds/Clock.mp3";

///89000
const TIME_TO_CHANGE_HOUR = 89000;

let gameOverAudio = new Audio(StaticSound);
let hourInterval = null;

function Controller({
    isPlaying,
    hour,
    time,
    energy,
    jumpscare,
    setStart,
    dispatch,
    stages,
}) {
    const [gameOver, setGameOver] = useState(false);
    const [victory, setVictory] = useState(false);


    useEffect(() => {
        dispatch({ type: "CLEAR_DATA" });
        changeEnergy();

        return () => {
            // clearInterval(hourInterval);
            dispatch({ type: "CLEAR_DATA" });
            gameOverAudio.pause();
        };
    }, []);

    useEffect(() => {
        setTimeout(() => {
            if (hour === 5 && !gameOver) endGame(true);
            else changeHour(hour);
        }, TIME_TO_CHANGE_HOUR);
    }, [hour])

    useEffect(() => {
        if (energy <= 0) {
            setBlackout();
        } else changeEnergy(energy);
    }, [energy]);

    async function changeHour(h) {
        if (isPlaying && !jumpscare && !gameOver && h < 6) {
            dispatch({ type: "CHANGE_HOUR" });
        }
    }

    async function changeEnergy(e) {
        if (isPlaying && !gameOver && e > 0) {
            setTimeout(() => {
                dispatch({ type: "CHANGE_ENERGY" });
            }, time);
        }
    }

    const setBlackout = () => {
        new Audio(BlackoutSound).play();

        dispatch({ type: "FORCE_CAMERA_CLOSE" });
        dispatch({ type: "CHANGE_CAMERA_BUTTON" });
    };

    const endGame = (hasWon) => {
        if (hasWon) {
            setVictory(true);
            let VictoryMusic = new Audio(VictorySound);
            VictoryMusic.play();

            const victories = JSON.parse(localStorage.getItem("victories")) || {};
            if(stages.mode !== "CUSTOM") victories[stages.mode] = "★"

            localStorage.setItem("victories", JSON.stringify(victories));
        } else {
            setGameOver(true);
            gameOverAudio.currentTime = 0;
            gameOverAudio.play();
        }
        dispatch({ type: "SET_GAME_OVER" });
        setTimeout(() => {
            setStart(false);
        }, 10000);
    };

    return (
        <>
            {gameOver ? (
                <img
                    alt="static"
                    src={StaticImage}
                    style={{ width: "100vw" }}
                />
            ) : null}
            {victory ? (
                <div
                    style={{
                        width: "100vw",
                        height: "100vh",
                        display: "flex",
                        justifyContent: "center",
                        alignItems: "center",
                    }}
                >
                    <img alt="victory" src={VictoryGIF} />
                </div>
            ) : null}
            <Game stages={stages} gameOver={gameOver || victory} endGame={endGame} />
        </>
    );
}

const mapStateToProps = (state) => {
    return {
        time: state.configReducer.time,
        hour: state.configReducer.hour,
        isPlaying: state.configReducer.isPlaying,
        jumpscare: state.configReducer.jumpscare,
        energy: state.configReducer.energy,
        animatronics: state.animatronicsReducer,
    };
};

export default connect(mapStateToProps)(Controller);
 156  src/CustomNight.js 
@@ -0,0 +1,156 @@
import React from 'react';
import styles from "./css/CustomNight.module.css"

import Freddy from "./media/Textures/CustomNight/freddy.png";
import Bonnie from "./media/Textures/CustomNight/bonnie.png";
import Chica from "./media/Textures/CustomNight/chica.png";
import Foxy from "./media/Textures/CustomNight/foxy.png";

const images = {
    Freddy,
    Bonnie,
    Chica,
    Foxy
}

const AnimatronicContainer = (props) => {
    const {range, changeRange, character} = props;

    return (
        <div className={styles.animatronic}>
            <img
                alt="Five Nights At Freddy's"
                src={images[character]}
                title={character}
                alt={character}
            />

            <div className={styles.range_buttons}>
                <button onClick={() => {changeRange(-1, character)}} disabled={range === 0}> {"<"} </button>
                <span> {range} </span>
                <button onClick={() => {changeRange(+1, character)}} disabled={range === 20}> {">"} </button>
            </div>
        </div>
    )
};

const CustomNight = ({state, setStart}) => {
    const changeMode = (value) => {

        let animatronics = {};

        switch(value) {
            case "EASY": 
                animatronics = {Bonnie: 2, Freddy: 2, Chica: 2, Foxy: 2};
                break;
            case "NORMAL": 
                animatronics = {Bonnie: 10, Freddy: 10, Chica: 10, Foxy: 10};
                break;
            case "HARD": 
                animatronics = {Bonnie: 15, Freddy: 15, Chica: 15, Foxy: 15};
                break;
            case "IMPOSSIBLE":
                animatronics = {Bonnie: 20, Freddy: 20, Chica: 20, Foxy: 20};
                break;
            default: 
                return;
        }

        state.setStages((stages) => ({...animatronics, mode: value}));
    };

    const changeRange = (value, character) => {
        const handleValue = (state, value) => 
            (state === 0 && value < 0) || (state === 20 && value > 0) ? state : state + value


        state.setStages((stages) => ({...stages, mode: "CUSTOM", [character]: handleValue(stages[character], value)}));
    }

    const hasWon = (mode) => {
        const victories = JSON.parse(localStorage.getItem("victories")) || {};

        return victories[mode] || " ";
    }

    return (
        <div className={styles.custom_night_container}>

                <a href="https://github.com/wellsousaaa/Five-Nights-at-Freddys-Web" target="_blank" className={styles.github_icon}>
                    <img src="https://icon-library.com/images/github-icon-white/github-icon-white-6.jpg" width="50" height="50" />
                </a>

            <h1>{"Five Nights at Freddy's Web"}</h1>

        <div className={styles.animatronics_container}>
            <AnimatronicContainer character={"Freddy"} range={state.ranges.Freddy} {...{changeRange}} />
            <AnimatronicContainer character={"Bonnie"} range={state.ranges.Bonnie} {...{changeRange}} />
            <AnimatronicContainer character={"Chica"} range={state.ranges.Chica} {...{changeRange}} />
            <AnimatronicContainer character={"Foxy"} range={state.ranges.Foxy} {...{changeRange}} />
        </div>


            <div className={styles.start_screen} style={{margin: "2% auto 1% auto"}}>
                <button className={styles.ready_button} onClick={() => setStart(true)}>
                    READY {"▶"}
                </button>
            </div>

            <div className={styles.start_screen}>
                {/* <span>Ou então escolha uma dificuldade: </span> */}
                <button onClick={() => {
                    changeMode("EASY")
                }} data-selected={state.ranges.mode === "EASY"}>
                    EASY {hasWon("EASY")}
                </button>
                <button onClick={() => {
                    changeMode("NORMAL")
                }} data-selected={state.ranges.mode === "NORMAL"}>
                    NORMAL {hasWon("NORMAL")}
                </button>
                <button onClick={() => {
                    changeMode("HARD")
                }} data-selected={state.ranges.mode === "HARD"}>
                    HARD {hasWon("HARD")}
                </button>
                <button onClick={() => {
                    changeMode("IMPOSSIBLE")
                }} data-selected={state.ranges.mode === "IMPOSSIBLE"}>
                    IMPOSSIBLE {hasWon("IMPOSSIBLE")}
                </button>
            </div>

            <footer className={styles.footer}>
                <p>Made by Wendell de Sousa | 2021 </p>
                {/* <p>Five Nights at Freddy's © Scott Cawthon</p> */}
            </footer>
        </div>
        // <div>
        //     {localStorage.getItem("★") ? (
        //                 <div
        //                     style={{
        //                         position: "absolute",
        //                         fontSize: "50pt",
        //                         color: "white",
        //                         marginLeft: "2vw",
        //                     }}
        //                 >
        //                     ★
        //                 </div>
        //             ) : null}
        //             <div className="start-screen">
        //                 <div>
        //                     <img
        //                         alt="Five Nights At Freddy's"
        //                         src={FreddyImage}
        //                     />
        //                     <button onClick={() => setStart(true)}>
        //                         READY
        //                     </button>
        //                 </div>
        //             </div>
        // </div>
    )
}; 

export default CustomNight;
 125  src/Game.js 
@@ -0,0 +1,125 @@
import React, { useEffect } from "react";
import { connect } from "react-redux";

import Animatronic from "./components/Animatronic";
import Office from "./components/Office";
import Camera from "./components/Camera";
import Hud from "./components/Hud";
import Media from "./components/Media";

let isBlackout = false;

let { Ambience } = Media.Sounds;
Ambience.loop = true;

let officeProps = { leftDoor: false, rightDoor: false };

const Game = ({
  office,
  isCameraOpen,
  energy,
  gameOver,
  stages,
  endGame,
  dispatch,
}) => {
  useEffect(() => {
    Ambience.currentTime = 0;
    Ambience.play();
    isBlackout = false;
    officeProps = { leftDoor: false, rightDoor: false };
  }, []);

  useEffect(() => {
    if (gameOver) Ambience.pause();
  }, [gameOver]);

  useEffect(() => {
    if (energy <= 0) {
      isBlackout = true;
      Ambience.pause();
    }
  }, [energy]);

  useEffect(() => {
    let newTime = 6300;
    if (office.leftDoor) newTime -= 1100;
    if (office.rightDoor) newTime -= 1100;
    if (office.leftLight) newTime -= 500;
    if (office.rightLight) newTime -= 500;
    if (isCameraOpen) newTime -= 1100;

    dispatch({ type: "CHANGE_TIME", content: newTime });
    officeProps = {
      leftDoor: office.leftDoor,
      rightDoor: office.rightDoor,
    };
  }, [
    office.leftDoor,
    office.rightDoor,
    office.leftLight,
    office.rightLight,
    isCameraOpen,
  ]);

  const handleJumpscare = (character) => {
    if (isBlackout || gameOver) return;
    dispatch({
      type: "CHANGE_ANIMATRONIC",
      animatronic: character,
      animatronicState: {
        door: null,
        camera: null,
        jumpscare: true,
      },
    });

    dispatch({ type: "CHANGE_JUMPSCARE", animatronic: character });
    if (character === "Foxy" || character === "Freddy")
      dispatch({ type: "FORCE_CAMERA_CLOSE" });
    setTimeout(() => {
      if (!isCameraOpen) dispatch({ type: "FORCE_CAMERA_CLOSE" });
    }, 10000);
  };

  async function isThisDoorOpen(door) {
    const isDoorOpen = await officeProps[door];
    return isDoorOpen;
  }

  return (
    <>
      <Animatronic
        stages={stages}
        handleJumpscare={handleJumpscare}
        gameOver={gameOver}
        isThisDoorOpen={isThisDoorOpen}
        blackout={energy <= 0}
      />

      {!gameOver ? (
        <>
          {energy <= 0 ? null : <Hud />}
          <Camera handleJumpscare={handleJumpscare} />
          {isCameraOpen ? null : (
            <Office endGame={endGame} blackout={energy <= 0} />
          )}
        </>
      ) : null}
    </>
  );
};

const mapStateToProps = (state) => {
  return {
    animatronics: state.animatronicsReducer,
    time: state.configReducer.time,
    hour: state.configReducer.hour,
    energy: state.configReducer.energy,
    office: state.officeReducer,
    camera: state.cameraReducer.camera,
    isCameraOpen: state.cameraReducer.isCameraOpen,
  };
};

export default connect(mapStateToProps)(Game);
 229  src/components/Animatronic.js 
@@ -0,0 +1,229 @@
import React, { useState, useEffect } from "react";
import Functions from "./Functions";
import Media from "./Media";
import { connect } from "react-redux";

let FreddyIterator = Functions.Freddy();
let BonnieIterator = Functions.Bonnie();
let ChicaIterator = Functions.Chica();
let FoxyIterator = Functions.Foxy();

FreddyIterator.next();

let FreddyTime = 10000;
let BonnieTime = 5000;
let ChicaTime = 7300;
let FoxyTime = 13000;

const ranges = {
  Freddy: 1,
  Bonnie: 1,
  Chica: 2,
  Foxy: 1,
}

let isBlackout = false;
let isGameOver = false;

function Animatronic({
  animatronics,
  config,
  handleJumpscare,
  isThisDoorOpen,
  dispatch,
  stages
}) {
  const { hour, gameOver, blackout } = config;

  useEffect(() => {
    ranges["Freddy"] = stages.Freddy;
    ranges["Bonnie"] = stages.Bonnie;
    ranges["Chica"] = stages.Chica;
    ranges["Foxy"] = stages.Foxy;

    if(stages.Bonnie) willMove("Bonnie", BonnieIterator, BonnieTime);
    if(stages.Chica) willMove("Chica", ChicaIterator, ChicaTime);
    if(stages.Foxy) willMove("Foxy", FoxyIterator, FoxyTime, true);
    if(stages.Freddy && stages.Chica && stages.Bonnie)willMove("Freddy", FreddyIterator, FreddyTime, true);

    return () => {
      FreddyIterator = Functions.Freddy();
      BonnieIterator = Functions.Bonnie();
      ChicaIterator = Functions.Chica();
      FoxyIterator = Functions.Foxy();

      FreddyIterator.next();

      FreddyTime = 10000;
      BonnieTime = 5000;
      ChicaTime = 7300;
      FoxyTime = 13000;
      ranges["Freddy"] = stages.Freddy;
      ranges["Bonnie"] = stages.Bonnie;
      ranges["Chica"] = stages.Chica;
      ranges["Foxy"] = stages.Foxy;

      isBlackout = false;
      isGameOver = false;
    };
  }, []);

  useEffect(() => {
    if (hour === 2) {
      FreddyTime = 9500;
      BonnieTime = 4700;
      ChicaTime = 6800;
      FoxyTime = 10000;


      ranges["Bonnie"] = ranges["Bonnie"] + 1;
      ranges["Chica"] = ranges["Chica"] + 1;
    } else if (hour === 4) {
      ranges["Bonnie"] = ranges["Bonnie"] + 2;
      ranges["Chica"] = ranges["Chica"] + 2;
      ranges["Freddy"] = ranges["Freddy"] + 1;
      ranges["Foxy"] = ranges["Foxy"] + 1;
    } else if (hour === 5) {
      ranges["Bonnie"] = ranges["Bonnie"] + 2;
      ranges["Chica"] = ranges["Chica"] + 2;
      ranges["Freddy"] = ranges["Freddy"] + 2;
      ranges["Foxy"] = ranges["Foxy"] + 2;
    }
  }, [hour]);

  useEffect(() => {
    if (gameOver) isGameOver = gameOver;
  }, [gameOver]);

  const changeAnimatronic = (func) => {
    dispatch({ type: "CHANGE_ANIMATRONICS_MOVING", content: true });

    func();

    setTimeout(() => {
      dispatch({
        type: "CHANGE_ANIMATRONICS_MOVING",
        content: false,
      });
    }, 1500);
  };

  const animatronicFailed = (character) => {
    changeAnimatronic(() => {
      dispatch({
        type: "CHANGE_ANIMATRONIC",
        animatronic: character,
        animatronicState: {
          door: false,
          camera:
            character === "Freddy"
              ? "Stage"
              : character === "Foxy"
              ? ""
              : "Dinning Area",
          jumpscare: false,
        },
      });

      if (character === "Bonnie") {
        BonnieIterator = Functions.Bonnie();
        willMove("Bonnie", BonnieIterator, BonnieTime);
      } else if (character === "Chica") {
        ChicaIterator = Functions.Chica();
        willMove("Chica", ChicaIterator, ChicaTime);
      } else if (character === "Foxy") {
        FoxyIterator = Functions.Foxy();
        Media.Sounds.FoxyPunch.play();
        willMove("Foxy", FoxyIterator, FoxyTime, true);
      } else if (character === "Freddy") {
        FreddyIterator = Functions.Freddy();
        FreddyIterator.next();
        willMove("Freddy", FreddyIterator, FreddyTime, true);
      }
    });
  };

  const freddyLaugh = () => {
    if (isBlackout) return;
    let FreddyNumber = Math.floor(Math.random() * 2);
    if (FreddyNumber == 0) {
      Media.Sounds.FreddyLaugh1.play();
    } else {
      Media.Sounds.FreddyLaugh2.play();
    }
  };
  useEffect(() => {
    if (blackout) isBlackout = true;
  }, [blackout]);

  function willMove (character, iterator, animaTime) {
    const thisInterval = setInterval(() => {
      const max = character === "Bonnie" || character === "Chica" ? 22 : 30;
      let luckyNumber = Math.floor(Math.random() * max);

      let condition = luckyNumber < ranges[character] && !animatronics[character].door;

      let newPlace;
      if (condition) {
        changeAnimatronic(() => {
          newPlace = iterator.next().value;

          const newState = {
            door: newPlace === "Door" || newPlace === "_3",
            jumpscare: false,
            camera: newPlace,
          };
          dispatch({
            type: "CHANGE_ANIMATRONIC",
            animatronic: character,
            animatronicState: newState,
          });
        });

        if (character === "Freddy") freddyLaugh();
      }

      if (isBlackout || isGameOver) clearInterval(thisInterval);

      if (newPlace === "Door" || newPlace === "_3") {
        if (!isBlackout) checkDoors(character);
        clearInterval(thisInterval);
      }
    }, animaTime);
  };

  async function checkDoors(character) {
    const door =
      character === "Bonnie" || character === "Foxy" ? "leftDoor" : "rightDoor";

    setTimeout(async () => {
      const isDoorOpen = await isThisDoorOpen(door);
      if (!isDoorOpen) {
        setTimeout(async () => {
          const isDoorOpen = await isThisDoorOpen(door);
          if (!isDoorOpen) {
            setTimeout(async () => {
              const isDoorOpen = await isThisDoorOpen(door);
              if (!isDoorOpen) {
                handleJumpscare(character);
              } else animatronicFailed(character);
            }, 3000);
          } else animatronicFailed(character);
        }, 5000);
      } else animatronicFailed(character);
    }, 10000);
  }

  return <></>;
}

const mapStateToProps = (state) => {
  return {
    leftDoor: state.officeReducer.leftDoor,
    rightDoor: state.officeReducer.rightDoor,
    animatronics: state.animatronicsReducer,
    config: state.configReducer,
  };
};

export default connect(mapStateToProps)(Animatronic);
 175  src/components/Camera.js 
@@ -0,0 +1,175 @@
import React, { useState, useEffect, useRef } from "react";
import { connect } from "react-redux";
import getCam from "./Images";

import AnimatronicsMoving from "../media/Sounds/garble1.mp3";
import AnimatronicsMoving2 from "../media/Sounds/garble2.mp3";
import Static from "../media/Textures/Static-Cam.webp";
import Black from "../media/Textures/black.jpg";
import Media from "./Media";

import CameraMap from "../components/CameraMap";
import CameraButton from "../components/CameraButton";

function Camera({
    animatronics,
    areAnimatronicsMoving,
    isCameraOpen,
    office,
    camera,
    cameraButtonDisappear,
    dispatch,
}) {
    const [Image, setImage] = useState(Media.Images.Stage);

    const closeCameraRef = useRef(null);
    const cameraDivRef = useRef(null);

    const handleCameraButton = () => {
        dispatch({ type: "SET_IS_OPEN" });
    };

    const handleCameraChange = (e) => {
        e.preventDefault();
        Media.Sounds.CameraChange.play();
        dispatch({ type: "CHANGE_CAMERA", content: e.target.title });
    };

    useEffect(() => {
        if (cameraDivRef.current) {
            if (isCameraOpen)
                setTimeout(() => {
                    cameraDivRef.current.style.display = "flex";
                }, 350);
            else
                setTimeout(() => {
                    cameraDivRef.current.style.display = "none";
                }, 100);
        }
    }, [isCameraOpen]);

    useEffect(() => {
        const { Bonnie, Chica, Freddy, Foxy } = animatronics;
        let result = "";
        if (Bonnie.camera === camera) result += "_b";
        if (Chica.camera === camera) result += "_c";
        if (Freddy.camera === camera) result += "_f";

        const newCamera = getCam(result, camera, Foxy.camera);
        setImage(newCamera);
    }, [camera, animatronics, areAnimatronicsMoving, animatronics.Foxy.camera]);

    useEffect(() => {
        if (areAnimatronicsMoving && isCameraOpen) {
            let MusicNumber = Math.floor(Math.random() * 2);
            let Sound;
            if (MusicNumber == 1 || MusicNumber == 2) {
                Sound = new Audio(AnimatronicsMoving);
            } else {
                Sound = new Audio(AnimatronicsMoving2);
            }
            Sound.play();
        }
    }, [areAnimatronicsMoving]);

    return (
        <div>
            {cameraButtonDisappear ? null : (
                <CameraButton
                    handleCameraButton={handleCameraButton}
                    style={{ zIndex: "1" }}
                />
            )}
            {isCameraOpen ? (
                <>
                    <img
                        draggable="false"
                        className="camera opening animation"
                        data-left-door={office.leftDoor}
                        data-right-door={office.rightDoor}
                        id="camera"
                        src={Media.Images.Up}
                        alt="Opening camera"
                        style={{
                            margin: 0,
                            width: "100vw",
                            height: "100vh",
                            position: "absolute",
                            top: 0,
                        }}
                    />
                    <div
                        className="camera-container"
                        style={{ display: "none" }}
                        ref={cameraDivRef}
                    >
                        <CameraMap handleCameraChange={handleCameraChange} />
                        {areAnimatronicsMoving ? (
                            <img
                                draggable="false"
                                src={Black}
                                alt="Animatronics are moving"
                                className="animatronics-true"
                                style={{
                                    height: "100vh",
                                    width: "100vw",
                                    backgroundColor: "black",
                                    position: "absolute",
                                }}
                            />
                        ) : (
                            <img
                                src={Image}
                                alt="Camera"
                                className="camera-img"
                                style={{
                                    width: "100vw",
                                    position: "absolute",
                                }}
                            />
                        )}
                        <img
                            alt="Static"
                            src={Static}
                            style={{
                                opacity: "0.1",
                                width: "100vw",
                                height: "100vh",
                            }}
                            draggable="false"
                            className="static-open"
                        />
                    </div>
                </>
            ) : (
                <img
                    draggable="false"
                    className={`camera opening`}
                    id="camera"
                    ref={closeCameraRef}
                    src={Media.Images.Down}
                    alt="Closing camera"
                    style={{
                        width: "100vw",
                        height: "100vh",
                        position: "absolute",
                    }}
                />
            )}
        </div>
    );
}

const mapStateToProps = (state) => {
    return {
        animatronics: state.animatronicsReducer,
        camera: state.cameraReducer.camera,
        office: state.officeReducer,
        isCameraOpen: state.cameraReducer.isCameraOpen,
        areAnimatronicsMoving: state.cameraReducer.areAnimatronicsMoving,
        jumpscare: state.configReducer.jumpscare,
        cameraButtonDisappear: state.configReducer.cameraButtonDisappear,
    };
};

export default connect(mapStateToProps)(Camera);
 33  src/components/CameraButton.js 
@@ -0,0 +1,33 @@
import React from "react";
import Media from "./Media";

function CameraButton(props) {
    const { handleCameraButton } = props;

    const handleCamera = ({ target }) => {
        if (target.dataset.disabled == "true") {
            target.dataset.disabled = "false";
            Media.Sounds.OpenCamera.play();
            handleCameraButton();
            setTimeout(() => {
                target.dataset.disabled = "true";
            }, 700);
        }
    };
    return (
        <div>
            <img
                draggable="false"
                className="camera-button"
                alt="Botão da camera"
                data-disabled="true"
                src={Media.Images.CameraButton}
                style={{ position: "absolute", zIndex: 1 }}
                onMouseOver={handleCamera}
                onTouchStart={handleCamera}
            />
        </div>
    );
}

export default CameraButton;
 162  src/components/CameraMap.js 
@@ -0,0 +1,162 @@
import React from "react";
import Media from "./Media";

function CameraMap(props) {
    const { handleCameraChange } = props;
    return (
        <div className="map" style={{ position: "absolute", zIndex: 10 }}>
            <img
                alt="Mapa da câmera"
                draggable="false"
                src={Media.Images.Map}
                style={{ zIndex: "1", width: "100%" }}
                useMap="#map"
            />
            <a
                href=""
                onClick={handleCameraChange}
                title="Stage"
                style={{
                    position: "absolute",
                    left: "27.25%",
                    top: "5%",
                    width: "13.25%",
                    height: "9.25%",
                    zIndex: 2,
                }}
            ></a>
            <a
                href=""
                onClick={handleCameraChange}
                title="Restrooms"
                style={{
                    position: "absolute",
                    left: "79.75%",
                    top: "24.25%",
                    width: "12.75%",
                    height: "8.25%",
                    zIndex: 2,
                }}
            ></a>
            <a
                href=""
                onClick={handleCameraChange}
                title="Dinning Area"
                style={{
                    position: "absolute",
                    left: "24%",
                    top: "20.5%",
                    width: "12.25%",
                    height: "8.25%",
                    zIndex: 2,
                }}
            ></a>
            <a
                href=""
                onClick={handleCameraChange}
                title="Backstage"
                style={{
                    position: "absolute",
                    left: "0%",
                    top: "27%",
                    width: "13.5%",
                    height: "9%",
                    zIndex: 2,
                }}
            ></a>
            <a
                href=""
                onClick={handleCameraChange}
                title="Pirate Cove"
                style={{
                    position: "absolute",
                    left: "12%",
                    top: "39.5%",
                    width: "12.75%",
                    height: "9%",
                    zIndex: 2,
                }}
            ></a>
            <a
                href=""
                onClick={handleCameraChange}
                title="Supply Closet"
                style={{
                    position: "absolute",
                    left: "8.25%",
                    top: "62.5%",
                    width: " 12%",
                    height: "8.25%",
                    zIndex: 2,
                }}
            ></a>
            <a
                href=""
                onClick={handleCameraChange}
                title="West Hall"
                style={{
                    position: "absolute",
                    left: "26.5%",
                    top: " 70.5%",
                    width: "12.5%",
                    height: "9.25%",
                    zIndex: 2,
                }}
            ></a>
            <a
                href=""
                onClick={handleCameraChange}
                title="East Hall"
                style={{
                    position: "absolute",
                    left: "49%",
                    top: "70%",
                    width: "14.5%",
                    height: "9.5%",
                    zIndex: 2,
                }}
            ></a>
            <a
                href=""
                onClick={handleCameraChange}
                title="W. Hall Corner"
                style={{
                    position: "absolute",
                    left: "26%",
                    top: "81.75%",
                    width: "14%",
                    height: "8.25%",
                    zIndex: 2,
                }}
            ></a>
            <a
                href=""
                onClick={handleCameraChange}
                title="E. Hall Corner"
                style={{
                    position: "absolute",
                    left: " 49.25%",
                    top: "81.25%",
                    width: "14.25%",
                    height: "10%",
                    zIndex: 2,
                }}
            ></a>
            <a
                href=""
                onClick={handleCameraChange}
                title="Kitchen"
                style={{
                    position: "absolute",
                    left: "79.5%",
                    top: "57.75%",
                    width: "14.25%",
                    height: "9.25%",
                    zIndex: 2,
                }}
            ></a>
        </div>
    );
}

export default CameraMap;
 73  src/components/Functions.js 
@@ -0,0 +1,73 @@
function* Bonnie() {
    yield* [
        "Dinning Area",
        "Backstage",
        "Supply Closet",
        "West Hall",
        "W. Hall Corner",
        "Door",
    ];
}

function* Chica() {
    yield* [
        "Dinning Area",
        "Restrooms",
        "Kitchen",
        "East Hall",
        "E. Hall Corner",
        "Door",
    ];
}

function* Freddy() {
    yield* [
        "Stage",
        "Dinning Area",
        "Restrooms",
        "Kitchen",
        "East Hall",
        "E. Hall Corner",
        "Door",
    ];
}

function* Foxy() {
    yield* ["_1", "_2", "_3"];
}

const changeAnimatronic = (Localization, iterator, setAnimatronics, change) => {
    Localization = iterator.next().value;
    setAnimatronics(change);
};

const checkAnimatronicsPosition = (
    BonnieLocal,
    ChicaLocal,
    FreddyLocal,
    search
) => {
    let res = "";
    if (BonnieLocal == search) {
        res += "-b";
    }
    if (ChicaLocal == search) {
        res += "-c";
    }
    if (FreddyLocal == search) {
        res += "-f";
    }

    return res;
};

const Functions = {
    Freddy,
    Chica,
    Bonnie,
    Foxy,
    changeAnimatronic,
    checkAnimatronicsPosition,
};

export default Functions;
 20  src/components/Hud.js 
@@ -0,0 +1,20 @@
import React from "react";
import { connect } from "react-redux";

function Hud({ hour, energy }) {
  return (
    <div style={{ zIndex: 10 }}>
      <h1 className="hour">{hour === 0 ? "12AM" : `${hour}AM`}</h1>
      <h2 className="energy">{energy}%</h2>
    </div>
  );
}

const mapStateToProps = (state) => {
  return {
    hour: state.configReducer.hour,
    energy: state.configReducer.energy,
  };
};

export default connect(mapStateToProps)(Hud);
 116  src/components/Images.js 
@@ -0,0 +1,116 @@
///SHOW STAGE
import Stage from "../media/Textures/Cams/Stage.webp";
import Stage_b_c_f from "../media/Textures/Cams/Stage-b-c-f.webp";
import Stage_b_f from "../media/Textures/Cams/Stage-b-f.webp";
import Stage_c_f from "../media/Textures/Cams/Stage-c-f.webp";
import Stage_f from "../media/Textures/Cams/Stage-f.webp";

///DINNING AREA
import DinningArea from "../media/Textures/Cams/DinningArea.webp";
import DinningArea_b from "../media/Textures/Cams/DinningArea-b.webp";
import DinningArea_c from "../media/Textures/Cams/DinningArea-c.webp";
import DinningArea_f from "../media/Textures/Cams/DinningArea-f.webp";
import DinningArea_b_c from "../media/Textures/Cams/DinningArea-b-c.webp";
import DinningArea_c_f from "../media/Textures/Cams/DinningArea-c-f.webp";
import DinningArea_b_f from "../media/Textures/Cams/DinningArea-b-f.webp";
import DinningArea_b_c_f from "../media/Textures/Cams/DinningArea-b-c-f.webp";

///BACKSTAGE
import Backstage from "../media/Textures/Cams/Backstage.webp";
import Backstage_b from "../media/Textures/Cams/Backstage-b.webp";

///PIRATE COVE
import PirateCove from "../media/Textures/Cams/Pirate_Cove.webp";
import PirateCove_1 from "../media/Textures/Cams/Pirate_Cove-1.webp";
import PirateCove_2 from "../media/Textures/Cams/Pirate_Cove-2.webp";
import PirateCove_3 from "../media/Textures/Cams/Pirate_Cove-3.webp";

///SUPPLY ROOM
import SupplyCloset from "../media/Textures/Cams/SupplyRoom.webp";
import SupplyCloset_b from "../media/Textures/Cams/SupplyRoom-b.webp";

///WEST HALL
import WestHall from "../media/Textures/Cams/West_Hall.webp";
import WestHall_b from "../media/Textures/Cams/West_Hall-b.webp";
import FoxyHallway from "../media/Textures/Foxy-Hallway.webp";

///WEST HALL CORNER
import WHallCorner from "../media/Textures/Cams/WHallCorner.webp";
import WHallCorner_b from "../media/Textures/Cams/WHallCorner-b.webp";

///RESTROOMS
import Restrooms from "../media/Textures/Cams/Restrooms.webp";
import Restrooms_c from "../media/Textures/Cams/Restrooms-c.webp";
import Restrooms_f from "../media/Textures/Cams/Restrooms-f.webp";
import Restrooms_c_f from "../media/Textures/Cams/Restrooms-c-f.webp";

///EAST HALL
import EastHall from "../media/Textures/Cams/East_Hall.webp";
import EastHall_c from "../media/Textures/Cams/East_Hall-c.webp";
import EastHall_f from "../media/Textures/Cams/East_Hall-f.webp";
import EastHall_c_f from "../media/Textures/Cams/East_Hall-c-f.webp";

///EAST HALL CORNER
import EHallCorner from "../media/Textures/Cams/EHallCorner.webp";
import EHallCorner_c from "../media/Textures/Cams/EHallCorner-c.webp";
import EHallCorner_f from "../media/Textures/Cams/EHallCorner-f.webp";

import Kitchen from "../media/Textures/black.jpg";
import Kitchen_c from "../media/Textures/black.jpg";
import Kitchen_f from "../media/Textures/black.jpg";
import Kitchen_c_f from "../media/Textures/black.jpg";

const cameraImages = {
  Stage,
  Stage_b_c_f,
  Stage_b_f,
  Stage_c_f,
  Stage_f,
  DinningArea,
  DinningArea_b_c_f,
  DinningArea_c_f,
  DinningArea_b_f,
  DinningArea_b_c,
  DinningArea_b,
  DinningArea_c,
  DinningArea_f,
  Backstage,
  Backstage_b,
  SupplyCloset,
  SupplyCloset_b,
  WestHall,
  WestHall_b,
  WHallCorner,
  WHallCorner_b,
  Restrooms,
  Restrooms_c,
  Restrooms_c_f,
  Restrooms_f,
  EastHall,
  EastHall_c,
  EastHall_c_f,
  EastHall_f,
  EHallCorner,
  EHallCorner_c,
  EHallCorner_f,
  EHallCorner_c_f: EHallCorner_f,
  PirateCove,
  PirateCove_1,
  PirateCove_2,
  PirateCove_3,
  Kitchen,
  Kitchen_c,
  Kitchen_f,
  Kitchen_c_f,
};

export default function getCam(animatronics, camera, foxy = "") {
  let location = camera.trim().replaceAll(" ", "");

  if (location === "W.HallCorner") location = "WHallCorner";
  if (location === "E.HallCorner") location = "EHallCorner";

  return cameraImages[
    `${location}${animatronics}${location === "PirateCove" ? foxy : ""}`
  ];
}
 45  src/components/Media.js 
@@ -0,0 +1,45 @@
/// AUDIO
import CameraSound from "../media/Sounds/put down.mp3";
import CameraChange from "../media/Sounds/blip3.mp3";
import Ambience from "../media/Sounds/MainAmbience.mp3";
import FreddyLaugh1 from "../media/Sounds/FreddyLaugh1.mp3";
import FreddyLaugh2 from "../media/Sounds/FreddyLaugh2.mp3";
import Door from "../media/Sounds/Door.mp3";
import FoxyPunch from "../media/Sounds/knock2.mp3";
import Surprise from "../media/Sounds/windowscare.mp3";
import Jumpscare from "../media/Sounds/jumpscare.mp3";

/// IMAGES
import CameraButton from "../media/Textures/CameraButton.png";
import Up from "../media/Textures/Up.webp";
import Down from "../media/Textures/Down.webp";
import Map from "../media/Textures/Cams/Complete_Map.png";
import Stage from "../media/Textures/Cams/Stage-b-c-f.webp";

const Sounds = {
    OpenCamera: new Audio(CameraSound),
    CameraChange: new Audio(CameraChange),
    Ambience: new Audio(Ambience),
    FreddyLaugh1: new Audio(FreddyLaugh1),
    FreddyLaugh2: new Audio(FreddyLaugh2),
    Door: new Audio(Door),
    FoxyPunch: new Audio(FoxyPunch),
    Surprise: new Audio(Surprise),
    Jumpscare: new Audio(Jumpscare),
};

const Images = {
    CameraButton,
    Up,
    Down,
    Map,
    Stage,
    Ambience,
};

const Media = {
    Sounds,
    Images,
};

export default Media;
 383  src/components/Office.js 
@@ -0,0 +1,383 @@
import React, { useState, useEffect } from "react";
import { connect } from "react-redux";

import Default from "../media/Textures/Office/Default.webp";
import Media from "./Media";

import Blackout from "../media/Textures/Office/304.webp";
import MusicBox from "../media/Sounds/music box.mp3";
import FreddyBlackout from "../media/Textures/Freddy.webp";

import JumpscareMP3 from "../media/Sounds/jumpscare.mp3";
import BonnieJumpscare from "../media/Textures/Bonnie-Jumpscare.webp";
import ChicaJumpscare from "../media/Textures/Chica-Jumpscare.webp";
import FreddyJumpscare1 from "../media/Textures/Freddy-Jumpscare1.gif";
import FreddyJumpscare2 from "../media/Textures/Freddy-Jumpscare.webp";
import FoxyJumpscare from "../media/Textures/Foxy-Jumpscare.gif";

import LD from "../media/Textures/Office/LD.webp";
import RD from "../media/Textures/Office/RD.webp";
import RD_LD from "../media/Textures/Office/RD_LD.webp";
import LD_RL from "../media/Textures/Office/LD_RL.webp";
import RD_LL from "../media/Textures/Office/RD_LL.webp";

import RD_LL_BONNIE from "../media/Textures/Office/RD_LL_BONNIE.webp";
import LD_RL_CHICA from "../media/Textures/Office/LD_RL_CHICA.webp";
import RL from "../media/Textures/Office/RL.webp";

import RL_LL_BONNIE from "../media/Textures/Office/RL_LL_BONNIE.webp";
import LL from "../media/Textures/Office/LL.webp";
import LL_BONNIE from "../media/Textures/Office/LL_BONNIE.webp";
import RL_LL from "../media/Textures/Office/RL_LL.webp";
import RL_CHICA from "../media/Textures/Office/RL_CHICA.webp";
import RL_LL_CHICA from "../media/Textures/Office/RL_LL_CHICA.webp";
import RL_LL_BONNIE_CHICA from "../media/Textures/Office/RL_LL_BONNIE_CHICA.webp";

let canJumpscare = true;

const officeImages = {
  LD,
  RD,
  RD_LD,
  LD_RL,
  RD_LL,
  RD_LL_BONNIE,
  LD_RL_CHICA,
  RL,
  RL_LL_BONNIE,
  LL,
  LL_BONNIE,
  RL_CHICA,
  RL_LL,
  RL_LL_CHICA,
  RL_LL_BONNIE_CHICA,
};

let musicBox = new Audio(MusicBox);
let jumpscareSound = new Audio(JumpscareMP3);
musicBox.loop = "true";

function Office({
  blackout,
  animatronics,
  officeConfig,
  jumpscare,
  isCameraOpen,
  endGame,
  dispatch,
}) {
  const [isJumpscare, setIsJumpscare] = useState(null);
  const [background, setBackground] = useState(Default);
  const [blackoutBackground, setBlackoutBackground] = useState(Blackout);

  useEffect(() => {
    checkBackground();
  }, [
    officeConfig.leftDoor,
    officeConfig.leftLight,
    officeConfig.rightDoor,
    officeConfig.rightLight,
  ]);

  useEffect(() => {
    if (isCameraOpen) return;
    checkBackground();

    if (jumpscare) {
      dispatch({ type: "CHANGE_CAMERA_BUTTON" });
      setIsJumpscare(jumpscare);
      jumpscareSound.play();
      setTimeout(() => {
        endGame(false);
      }, 5000);
    }
  }, [isCameraOpen]);

  useEffect(() => {
    if (animatronics.Foxy.jumpscare) {
      dispatch({ type: "CHANGE_CAMERA_BUTTON" });
      setIsJumpscare("Foxy");
      jumpscareSound.play();
      setTimeout(() => {
        endGame(false);
      }, 5000);
    }
  }, [animatronics.Foxy.jumpscare]);

  useEffect(() => {
    if (animatronics.Freddy.jumpscare) {
      dispatch({ type: "CHANGE_CAMERA_BUTTON" });
      setIsJumpscare("Freddy");
      jumpscareSound.play();
      setTimeout(() => {
        endGame(false);
      }, 5000);
    }
  }, [animatronics.Freddy.jumpscare]);

  async function checkBackground() {
    const { leftDoor, rightDoor, leftLight, rightLight } = officeConfig;
    const { Bonnie, Chica } = animatronics;

    function getBackground() {
      const result = [];

      if (rightDoor) result.push("RD");
      if (leftDoor) result.push("LD");

      if (rightLight && !rightDoor) result.push("RL");
      if (leftLight && !leftDoor) result.push("LL");
      if (Bonnie.door && leftLight) result.push("BONNIE");
      if (Chica.door && rightLight) result.push("CHICA");

      return result;
    }

    const result = await getBackground();
    if (result.length === 0) setBackground(Default);
    else setBackground(officeImages[result.join("_")]);
  }

  const checkDoorSounds = (light) => {
    const { leftDoor, rightDoor } = officeConfig;
    const { Bonnie, Chica } = animatronics;

    let condition1 = light === "leftLight" && !leftDoor && Bonnie.door;
    let condition2 = light === "rightLight" && !rightDoor && Chica.door;

    if (condition1 || condition2) Media.Sounds.Surprise.play();
  };

  useEffect(() => {
    if (blackout) FreddyJumpscare();
  }, [blackout]);

  useEffect(() => {
    canJumpscare = true;
    return () => {
      canJumpscare = false;
      musicBox.pause();
    };
  }, []);

  const FreddyJumpscare = () => {
    const musicBoxInterval = setInterval(() => {
      let musicBoxNumber = Math.floor(Math.random() * 9);
      if (!canJumpscare) clearInterval(musicBoxInterval);
      if (musicBoxNumber < 3 && canJumpscare) {
        musicBox.currentTime = 0;
        musicBox.play();
        setBlackoutBackground(FreddyBlackout);
        clearInterval(musicBoxInterval);

        const pauseMusicInterval = setInterval(() => {
          let pauseNumber = Math.floor(Math.random() * 3);
          if (!canJumpscare) clearInterval(pauseMusicInterval);
          if (pauseNumber == 0 && canJumpscare) {
            setBlackoutBackground(null);
            musicBox.pause();
            clearInterval(pauseMusicInterval);

            const freddyInterval = setInterval(() => {
              let freddyNumber = Math.floor(Math.random() * 9);
              if (!canJumpscare) clearInterval(freddyInterval);
              if (freddyNumber == 0 && canJumpscare) {
                const JumpscareImage = FreddyJumpscare1;
                setBlackoutBackground(JumpscareImage);
                jumpscareSound.play();
                dispatch({
                  type: "CHANGE_JUMPSCARE",
                  animatronic: true,
                });
                clearInterval(freddyInterval);
                setTimeout(() => {
                  endGame(false);
                  setBlackoutBackground(Blackout);
                }, 5000);
              }
            }, 3000);
          }
        }, 5000);
      }
    }, 3000);
  };

  if (isJumpscare === "Bonnie" && !isCameraOpen)
    return (
      <div className="office-container">
        <img
          alt="Office"
          draggable="false"
          style={{ width: "100vw" }}
          src={BonnieJumpscare}
          className="office-img"
          useMap="#office"
        />
      </div>
    );
  else if (isJumpscare === "Foxy")
    return (
      <div className="office-container">
        <img
          alt="Office"
          draggable="false"
          style={{ width: "100vw" }}
          src={FoxyJumpscare}
          className="office-img"
          useMap="#office"
        />
      </div>
    );
  else if (isJumpscare === "Freddy")
    return (
      <div className="office-container">
        <img
          alt="Office"
          draggable="false"
          style={{ width: "100vw" }}
          src={FreddyJumpscare2}
          className="office-img"
          useMap="#office"
        />
      </div>
    );
  else if (isJumpscare === "Chica" && !isCameraOpen)
    return (
      <div className="office-container">
        <img
          alt="Office"
          draggable="false"
          style={{ width: "100vw" }}
          src={ChicaJumpscare}
          className="office-img"
          useMap="#office"
        />
      </div>
    );

  return (
    <>
      {!blackout ? (
        <div className="office-container">
          <div style={{ width: "fit-content" }}>
            <img
              alt="Office"
              draggable="false"
              style={{ width: "100vw" }}
              src={background}
              className="office-img"
              useMap="#office"
            />
            <a
              href=""
              title="leftDoor"
              style={{
                position: "absolute",
                left: "1.63%",
                top: "46.53%",
                width: "3.13%",
                height: "10.56%",
                zIndex: 2,
              }}
              onClick={(e) => {
                e.preventDefault();
                dispatch({
                  type: "CHANGE_OFFICE_CONFIG",
                  obj: "leftDoor",
                });
                checkBackground();
                Media.Sounds.Door.play();
              }}
            ></a>
            <a
              href=""
              title="leftLight"
              style={{
                position: "absolute",
                left: "1.75%",
                top: "58.06%",
                width: "3.13%",
                height: "10.56%",
                zIndex: 2,
              }}
              onClick={(e) => {
                e.preventDefault();
                dispatch({
                  type: "CHANGE_OFFICE_CONFIG",
                  obj: "leftLight",
                });
                checkBackground();
                checkDoorSounds("leftLight");
              }}
            ></a>

            <a
              href=""
              title="rightDoor"
              style={{
                position: "absolute",
                left: "94.25%",
                top: "46.94%",
                width: "3.13%",
                height: "10.56%",
                zIndex: 2,
              }}
              onClick={(e) => {
                e.preventDefault();
                dispatch({
                  type: "CHANGE_OFFICE_CONFIG",
                  obj: "rightDoor",
                });
                checkBackground();
                Media.Sounds.Door.play();
              }}
            ></a>

            <a
              href=""
              title="rightLight"
              style={{
                position: "absolute",
                left: "94.44%",
                top: "58.47%",
                width: "3.13%",
                height: "10.56%",
                zIndex: 2,
              }}
              onClick={(e) => {
                e.preventDefault();
                dispatch({
                  type: "CHANGE_OFFICE_CONFIG",
                  obj: "rightLight",
                });
                checkBackground();
                checkDoorSounds("rightLight");
              }}
            ></a>
          </div>
        </div>
      ) : (
        <div className="office-container">
          <img
            alt="Office"
            draggable="false"
            style={{ width: "100vw" }}
            src={blackoutBackground}
            className="office-img"
          />
        </div>
      )}
    </>
  );
}

const mapStateToProps = (state) => {
  return {
    officeConfig: state.officeReducer,
    animatronics: state.animatronicsReducer,
    isCameraOpen: state.cameraReducer.isCameraOpen,
    jumpscare: state.configReducer.jumpscare,
  };
};

export default connect(mapStateToProps)(Office);
 198  src/css/CustomNight.module.css 
@@ -0,0 +1,198 @@
.custom_night_container {
  overflow: auto;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  color: white;
  backdrop-filter: blur(7px) brightness(0.5);

  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  height: 100vh;
}

.github_icon {
  width: fit-content;
  height: fit-content;
  position: absolute;
  bottom: 2%;
  right: 2%;
  cursor: pointer;
  transition: transform 200ms 50ms;
}

.github_icon a {
  width: fit-content;
  height: fit-content;
}

.github_icon:hover {
  transform: scale(1.2);
  transition: transform 200ms 50ms;
}

.custom_night_container h1 {
  font-weight: 400;
  margin-left: 30px;
  opacity: 0.8;
}

.animatronics_container {
  display: flex;
  justify-content: space-evenly;
}

.animatronic {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.animatronic img {
  max-width: 200px;
  width: 20vw;
}

.animatronic > span {
  font-size: 20pt;
  margin-bottom: 15px;
}

.range_buttons {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-top: 25px;
  font-size: 1.5rem;
  font-family: "Consolas";
  width: 100%;
}

.range_buttons button {
  border-radius: 5px;
  width: 50px;
  outline: none;
  background-color: var(--button-color);
  color: inherit;
  font-weight: bolder;
  border: none;
  font-size: inherit;
  cursor: pointer;
  transition: transform 200ms 50ms;
}

.range_buttons button:not(:disabled):hover,
.range_buttons button:not(:disabled):focus-within {
  transform: scale(1.15);
  transition: transform 200ms 50ms;
}

.range_buttons button:disabled {
  cursor: default;
  opacity: 0.8;
}

.start_screen {
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
  /* height: 100vh; */
  display: flex;
  align-self: center;
  justify-content: space-evenly;
  flex-wrap: wrap;
  align-items: center;
}

.start_screen span {
  flex: 100%;
  margin-bottom: 15px;
  font-size: 12.5pt;
}

.ready_button {
  font-weight: 800;
  padding: auto 10px;

  font-size: 17pt;
}

.start_screen button:not(.ready_button) {
  font-size: 15pt;
}

.start_screen button:not(.ready_button)[data-selected="false"] {
  opacity: 0.6;
}

.start_screen button:not(.ready_button)[data-selected="true"]:before {
  content: "▶ ";
}

.start_screen button {
  border-radius: 6.5px;
  /* width: 100px; */
  cursor: pointer;
  height: 100%;
  outline: none;
  color: white;
  background-color: var(--button-color);
  border: none;
}

.footer {
  opacity: 0.8;
  height: 50px;
  text-align: center;
}

.footer p {
  margin-top: 0;
}

@media screen and (min-width: 750px) {
  .custom_night_container h1 {
    margin-bottom: 30px;
  }
  .start_screen {
    width: 50%;
  }
  .start_screen button {
    margin-top: 10px;
    height: 50px;
  }

  .range_buttons button {
    height: 50px;
  }

  .footer {
    margin-top: 50px;
  }
}

@media screen and (max-width: 750px) {
  .custom_night_container h1 {
    /* margin-bottom: 2%; */
    margin-top: 2%;
    font-size: 15pt;
  }

  .start_screen {
    width: 90%;
  }
  .ready_button {
    margin: 1.2% auto 1% auto;
  }

  .start_screen button {
    font-size: 10pt !important;
    height: 35px;
  }

  .range_buttons {
    margin-top: 15px;
    max-height: 30px;
  }

  .footer {
    margin: 1% 0px 1% 0px;
  }
}
 227  src/css/Game.css 
@@ -0,0 +1,227 @@
* {
  -webkit-touch-callout: none; /* iOS Safari */
  -webkit-user-select: none; /* Safari */
  -khtml-user-select: none; /* Konqueror HTML */
  -moz-user-select: none; /* Old versions of Firefox */
  -ms-user-select: none; /* Internet Explorer/Edge */
  user-select: none; /* Non-prefixed version, currently supported by Chrome, Edge, Opera and Firefox */
}

:root {
  --background-color: black;
  --button-color: rgba(255, 255, 255, 0.2);
}

body {
  width: 100vw;
  height: 100vh;
}

.custom-night {
  background-image: url("https://wendelldesousa.netlify.app/assets/FNAF.webp");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}

.animation {
  background-size: 100vw;
  background-repeat: no-repeat;
  background-position: center;
}

.animation[data-right-door="false"][data-left-door="false"] {
  background-image: url("../media/Textures/Office/Default.webp");
}
.animation[data-right-door="true"][data-left-door="false"] {
  background-image: url("../media/Textures/Office/RD.webp");
}
.animation[data-right-door="false"][data-left-door="true"] {
  background-image: url("../media/Textures/Office/LD.webp");
}
.animation[data-right-door="true"][data-left-door="true"] {
  background-image: url("../media/Textures/Office/RD_LD.webp");
}

@keyframes up {
  0% {
    background-position: 0px;
  }
  85% {
    background-position: -9500px;
    opacity: 1;
  }
  100% {
    opacity: 0;
  }
}
@keyframes down {
  0% {
    background-position: -9500px;
    opacity: 1;
  }
  100% {
    background-position: 0px;
  }
}

@keyframes disappear {
  from {
    display: unset !important;
    z-index: 1;
    opacity: 1;
  }
  to {
    display: none !important;
    opacity: 0;
    z-index: -10;
  }
}

body {
  margin: 0;
  overflow: hidden;
  background-color: var(--background-color);
}

.camera-button {
  pointer-events: all !important;
  margin-left: 26vw;
  bottom: 0;
  opacity: 0.5;
}

.true,
.false {
  transform: scale(1.3);
  animation: up 0.6s steps(8) forwards;
}

.map {
  bottom: 0;
  right: 0;
  width: fit-content;
}
@media only screen and (max-width: 750px) {
  .map img {
    width: 250px !important;
    opacity: 0.7;
  }
  .map {
    margin-bottom: 30px;
  }
  .camera-button {
    width: 100vh !important;
  }
}

area {
  outline: none;
}

area.hover {
  cursor: pointer;
}

.true,
.false,
.animatronics-true,
.static {
  width: 100vw;
  height: 100vh;
}
.animatronics-true {
  background-color: var(--background-color);
}

.static {
  opacity: 0.9;
  animation: noise 0.12s infinite alternate-reverse;
}

.hour,
.energy {
  font-weight: lighter;
  opacity: 0.4;
  z-index: 1;
  font-family: "Consolas";
  color: white;
  position: "absolute";
}
.hour {
  position: absolute;
  margin-right: 0;
  margin-left: 90vw;
}
.energy {
  position: absolute;
  bottom: 0;
  margin-left: 3vw;
  font-size: 15pt;
}

.opening {
  z-index: 1;
  animation: disappear 0.5s steps(1) forwards;
}

@keyframes opening {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

.open {
  animation: opening 0.5s steps(1) forwards;
}

img[data-disabled="false"] {
  opacity: 0.3;
}

@media screen and (max-width: 700px) {
  .camera-img {
    width: 100vw;
    height: 90vh;
  }

  .hour {
    font-size: 17pt;
  }
  .camera-button {
    margin-left: 22vw;
  }
}
.office-img {
  margin: auto;
  width: 100vw;
}

.office-container {
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

img {
  pointer-events: none;
}

* {
  -moz-user-select: none;
  -webkit-user-select: none;
  user-select: none;
}

.camera-container {
  width: 100vw;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}
 55  src/index.js 
@@ -0,0 +1,55 @@
import React, { useState, useEffect } from "react";
import ReactDOM from "react-dom";
import Controller from "./Controller";
import "./css/Game.css";
import * as serviceWorker from "./serviceWorker";
import { Provider } from "react-redux";
import store from "./store/store";
import CustomNight from "./CustomNight";

const initialState = {
  mode: "NORMAL",
  Freddy: 10,
  Bonnie: 10,
  Chica: 10,
  Foxy: 10,
};

const Start = () => {
  const [Start, setStart] = useState(false);
  const [stages, setStages] = useState(initialState);

  useEffect(() => {
    console.log(window.innerHeight > window.innerWidth);
    if (window.innerHeight > window.innerWidth) {
      window.alert(
        `Para uma melhor experiência, vire seu celular para o modo de paisagem (modo deitado)
                 ~ For a better experience, please rotate your phone to landscape mode`
      );
    }
  }, []);

  return (
    <>
      {!Start ? (
        <div className="custom-night">
          <CustomNight
            setStart={setStart}
            state={{ ranges: stages, setStages }}
          />
        </div>
      ) : (
        <Controller stages={stages} setStart={setStart} />
      )}
    </>
  );
};

ReactDOM.render(
  <Provider store={store}>
    <Start />
  </Provider>,
  document.getElementById("root")
);

serviceWorker.register();
 BIN +3.52 MB src/media/Sounds/Ambience.mp3 
Binary file not shown.
 BIN +130 KB src/media/Sounds/CameraIdle 2.mp3 
Binary file not shown.
 0  static/media/Clock.e3b5674e.mp3 → src/media/Sounds/Clock.mp3 
File renamed without changes.
 0  static/media/Dead.1dc7e9d8.mp3 → src/media/Sounds/Dead.mp3 
File renamed without changes.
 0  static/media/Door.88d0c222.mp3 → src/media/Sounds/Door.mp3 
File renamed without changes.
 0  static/media/FreddyLaugh1.74fb79b7.mp3 → src/media/Sounds/FreddyLaugh1.mp3 
File renamed without changes.
 0  static/media/FreddyLaugh2.9d962f5d.mp3 → src/media/Sounds/FreddyLaugh2.mp3 
File renamed without changes.
 BIN +43.5 KB src/media/Sounds/FreddyLaugh3.mp3 
Binary file not shown.
 0  static/media/MainAmbience.cb39bd7f.mp3 → src/media/Sounds/MainAmbience.mp3 
File renamed without changes.
 0  static/media/blip3.2c193f64.mp3 → src/media/Sounds/blip3.mp3 
File renamed without changes.
 0  static/media/garble1.7299925a.mp3 → src/media/Sounds/garble1.mp3 
File renamed without changes.
 0  static/media/garble2.116d58fe.mp3 → src/media/Sounds/garble2.mp3 
File renamed without changes.
 0  static/media/jumpscare.a11ecaf8.mp3 → src/media/Sounds/jumpscare.mp3 
File renamed without changes.
 0  static/media/knock2.5dffb4c9.mp3 → src/media/Sounds/knock2.mp3 
File renamed without changes.
 0  static/media/music box.06a9f2bb.mp3 → src/media/Sounds/music box.mp3 
File renamed without changes.
 0  static/media/powerdown.0ad32954.mp3 → src/media/Sounds/powerdown.mp3 
File renamed without changes.
 BIN +180 KB src/media/Sounds/powerdown2.mp3 
Binary file not shown.
 0  static/media/put down.2f56cfdc.mp3 → src/media/Sounds/put down.mp3 
File renamed without changes.
 0  static/media/windowscare.e3f2eecb.mp3 → src/media/Sounds/windowscare.mp3 
File renamed without changes.
 0  static/media/Bonnie-Jumpscare.157447f6.webp → src/media/Textures/Bonnie-Jumpscare.webp 
File renamed without changes.
 BIN +6.54 KB src/media/Textures/CameraButton.png 

 0  static/media/Backstage-b.f9279547.webp → src/media/Textures/Cams/Backstage-b.webp 
File renamed without changes.
 0  static/media/Backstage.0cd64672.webp → src/media/Textures/Cams/Backstage.webp 
File renamed without changes.
 0  static/media/Complete_Map.eb335a3f.png → src/media/Textures/Cams/Complete_Map.png 
File renamed without changes.
 0  static/media/DinningArea-b-c-f.eba61ee6.webp → ...edia/Textures/Cams/DinningArea-b-c-f.webp 
File renamed without changes.
 0  static/media/DinningArea-b-c.03091868.webp → src/media/Textures/Cams/DinningArea-b-c.webp 
File renamed without changes.
 0  static/media/DinningArea-b-f.8b34e98c.webp → src/media/Textures/Cams/DinningArea-b-f.webp 
File renamed without changes.
 0  static/media/DinningArea-b.b4b88aa7.webp → src/media/Textures/Cams/DinningArea-b.webp 
File renamed without changes.
 0  static/media/DinningArea-c-f.9452fc2c.webp → src/media/Textures/Cams/DinningArea-c-f.webp 
File renamed without changes.
 0  static/media/DinningArea-c.d3cfc1ff.webp → src/media/Textures/Cams/DinningArea-c.webp 
File renamed without changes.
 0  static/media/DinningArea-f.92853636.webp → src/media/Textures/Cams/DinningArea-f.webp 
File renamed without changes.
 0  static/media/DinningArea.710e140f.webp → src/media/Textures/Cams/DinningArea.webp 
File renamed without changes.
 0  static/media/EHallCorner-c.652bffaa.webp → src/media/Textures/Cams/EHallCorner-c.webp 
File renamed without changes.
 0  static/media/EHallCorner-f.3227e43b.webp → src/media/Textures/Cams/EHallCorner-f.webp 
File renamed without changes.
 0  static/media/EHallCorner.24248709.webp → src/media/Textures/Cams/EHallCorner.webp 
File renamed without changes.
 0  static/media/East_Hall-c-f.254211d5.webp → src/media/Textures/Cams/East_Hall-c-f.webp 
File renamed without changes.
 0  static/media/East_Hall-c.24976d62.webp → src/media/Textures/Cams/East_Hall-c.webp 
File renamed without changes.
 0  static/media/East_Hall-f.f36ca7d5.webp → src/media/Textures/Cams/East_Hall-f.webp 
File renamed without changes.
 0  static/media/East_Hall.8c34432b.webp → src/media/Textures/Cams/East_Hall.webp 
File renamed without changes.
 0  static/media/Pirate_Cove-1.8f1cb29b.webp → src/media/Textures/Cams/Pirate_Cove-1.webp 
File renamed without changes.
 0  static/media/Pirate_Cove-2.e0d657a1.webp → src/media/Textures/Cams/Pirate_Cove-2.webp 
File renamed without changes.
 0  static/media/Pirate_Cove-3.e55d10ad.webp → src/media/Textures/Cams/Pirate_Cove-3.webp 
File renamed without changes.
 0  static/media/Pirate_Cove.edbfd0bf.webp → src/media/Textures/Cams/Pirate_Cove.webp 
File renamed without changes.
 0  static/media/Restrooms-c-f.12d653ef.webp → src/media/Textures/Cams/Restrooms-c-f.webp 
File renamed without changes.
 0  static/media/Restrooms-c.1679cc0b.webp → src/media/Textures/Cams/Restrooms-c.webp 
File renamed without changes.
 0  static/media/Restrooms-f.d147116a.webp → src/media/Textures/Cams/Restrooms-f.webp 
File renamed without changes.
 0  static/media/Restrooms.f3b1bdf1.webp → src/media/Textures/Cams/Restrooms.webp 
File renamed without changes.
 0  static/media/Stage-b-c-f.4485140c.webp → src/media/Textures/Cams/Stage-b-c-f.webp 
File renamed without changes.
 0  static/media/Stage-b-f.4f5d612b.webp → src/media/Textures/Cams/Stage-b-f.webp 
File renamed without changes.
 0  static/media/Stage-c-f.9a2cd03d.webp → src/media/Textures/Cams/Stage-c-f.webp 
File renamed without changes.
 0  static/media/Stage-f.9e3f050c.webp → src/media/Textures/Cams/Stage-f.webp 
File renamed without changes.
 0  static/media/Stage.abcca924.webp → src/media/Textures/Cams/Stage.webp 
File renamed without changes.
 0  static/media/SupplyRoom-b.e5e5d598.webp → src/media/Textures/Cams/SupplyRoom-b.webp 
File renamed without changes.
 0  static/media/SupplyRoom.4a1bc400.webp → src/media/Textures/Cams/SupplyRoom.webp 
File renamed without changes.
 0  static/media/WHallCorner-b.a9698cab.webp → src/media/Textures/Cams/WHallCorner-b.webp 
File renamed without changes.
 0  static/media/WHallCorner.b96bb659.webp → src/media/Textures/Cams/WHallCorner.webp 
File renamed without changes.
 BIN +134 KB src/media/Textures/Cams/West-Hall-b.webp 
Binary file not shown.
 BIN +131 KB src/media/Textures/Cams/West-Hall.webp 
Binary file not shown.
 0  static/media/West_Hall-b.d400bfc4.webp → src/media/Textures/Cams/West_Hall-b.webp 
File renamed without changes.
 0  static/media/West_Hall.61dc6ca3.webp → src/media/Textures/Cams/West_Hall.webp 
File renamed without changes.
 0  static/media/Chica-Jumpscare.0ce85db5.webp → src/media/Textures/Chica-Jumpscare.webp 
File renamed without changes.
 0  static/media/bonnie.c928fb88.png → src/media/Textures/CustomNight/bonnie.png 
File renamed without changes.
 0  static/media/chica.2ccb8091.png → src/media/Textures/CustomNight/chica.png 
File renamed without changes.
 0  static/media/foxy.618aad28.png → src/media/Textures/CustomNight/foxy.png 
File renamed without changes.
 0  static/media/freddy.a3eb8395.png → src/media/Textures/CustomNight/freddy.png 
File renamed without changes.
 0  static/media/Down.b9786df1.webp → src/media/Textures/Down.webp 
File renamed without changes.
 0  static/media/Foxy-Hallway.39ac94de.webp → src/media/Textures/Foxy-Hallway.webp 
File renamed without changes.
 0  static/media/Foxy-Jumpscare.7c425050.gif → src/media/Textures/Foxy-Jumpscare.gif 
File renamed without changes.
 0  static/media/Freddy-Jumpscare.d39468d3.webp → src/media/Textures/Freddy-Jumpscare.webp 
File renamed without changes.
 0  static/media/Freddy-Jumpscare1.09936815.gif → src/media/Textures/Freddy-Jumpscare1.gif 
File renamed without changes.
 0  static/media/Freddy.b24921e2.webp → src/media/Textures/Freddy.webp 
File renamed without changes.
 0  static/media/304.6261b129.webp → src/media/Textures/Office/304.webp 
File renamed without changes.
 BIN +63.1 KB src/media/Textures/Office/305.webp 
Binary file not shown.
 0  static/media/Default.21fc08f1.webp → src/media/Textures/Office/Default.webp 
File renamed without changes.
 0  static/media/LD.f419bc74.webp → src/media/Textures/Office/LD.webp 
File renamed without changes.
 0  static/media/LD_RL.36c1416c.webp → src/media/Textures/Office/LD_RL.webp 
File renamed without changes.
 0  static/media/LD_RL_CHICA.b66ef877.webp → src/media/Textures/Office/LD_RL_CHICA.webp 
File renamed without changes.
 0  static/media/LL.48c57171.webp → src/media/Textures/Office/LL.webp 
File renamed without changes.
 0  static/media/LL_BONNIE.e5288d07.webp → src/media/Textures/Office/LL_BONNIE.webp 
File renamed without changes.
 0  static/media/RD.b9cb0bf6.webp → src/media/Textures/Office/RD.webp 
File renamed without changes.
 0  static/media/RD_LD.46ef2f0d.webp → src/media/Textures/Office/RD_LD.webp 
File renamed without changes.
 0  static/media/RD_LL.2fdd028a.webp → src/media/Textures/Office/RD_LL.webp 
File renamed without changes.
 0  static/media/RD_LL_BONNIE.675c5c4c.webp → src/media/Textures/Office/RD_LL_BONNIE.webp 
File renamed without changes.
 0  static/media/RL.fb0877af.webp → src/media/Textures/Office/RL.webp 
File renamed without changes.
 0  static/media/RL_CHICA.31af1a29.webp → src/media/Textures/Office/RL_CHICA.webp 
File renamed without changes.
 0  static/media/RL_LL.ac77442e.webp → src/media/Textures/Office/RL_LL.webp 
File renamed without changes.
 0  static/media/RL_LL_BONNIE.c46c4ca7.webp → src/media/Textures/Office/RL_LL_BONNIE.webp 
File renamed without changes.
 0  ...ic/media/RL_LL_BONNIE_CHICA.539b9c1f.webp → ...a/Textures/Office/RL_LL_BONNIE_CHICA.webp 
File renamed without changes.
 0  static/media/RL_LL_CHICA.deb8677b.webp → src/media/Textures/Office/RL_LL_CHICA.webp 
File renamed without changes.
 0  static/media/Static-Cam.94568d3d.webp → src/media/Textures/Static-Cam.webp 
File renamed without changes.
 0  static/media/Up.2d6dde8d.webp → src/media/Textures/Up.webp 
File renamed without changes.
 0  static/media/Victory.ca620353.gif → src/media/Textures/Victory.gif 
File renamed without changes.
 BIN +38.4 KB src/media/Textures/Victory.webp 
Binary file not shown.
 BIN +651 Bytes src/media/Textures/black.jpg 

 48  src/reducers/animatronicsReducer.js 
@@ -0,0 +1,48 @@
const originalState = {
    Freddy: {
        camera: "Stage",
        door: false,
        jumpscare: false,
    },
    Bonnie: {
        camera: "Stage",
        door: false,
        jumpscare: false,
    },
    Chica: {
        camera: "Stage",
        door: false,
        jumpscare: false,
    },
    Foxy: {
        camera: "",
        door: false,
        jumpscare: false,
    },
};

export default function animatronics(state = originalState, action) {
    switch (action.type) {
        // case "CHANGE_FREDDY_CAMERA":
        //   return { ...state, Freddy: { ...state.Freddy, camera: action.content } };
        // case "CHANGE_BONNIE_CAMERA":
        //   return { ...state, Bonnie: { ...state.Bonnie, camera: action.content } };
        // case "CHANGE_CHICA_CAMERA":
        //   return { ...state, Chica: { ...state.Chica, camera: action.content } };
        // case "CHANGE_FOXY_CAMERA":
        //   return { ...state, Foxy: { ...state.Foxy, camera: action.content } };

        case "CHANGE_ANIMATRONIC":
            let animatronicProps = state[action.animatronic];

            animatronicProps = { ...action.animatronicState };
            state[action.animatronic] = animatronicProps;
            return state;
        case "SET_FOXY_NULL":
            return { ...state, Foxy: { ...state.Foxy, camera: null } };
        case "CLEAR_DATA":
            return { ...originalState };
        default:
            return state;
    }
}
 24  src/reducers/cameraReducer.js 
@@ -0,0 +1,24 @@
const originalState = {
    camera: "Stage",
    isCameraOpen: false,
    areAnimatronicsMoving: false,
};

export default function camera(state = originalState, action) {
    switch (action.type) {
        case "CHANGE_CAMERA":
            return { ...state, camera: action.content };
        case "SET_IS_OPEN":
            return {
                ...state,
                isCameraOpen: state.isCameraOpen ? false : true,
            };
        case "FORCE_CAMERA_CLOSE":
            return { ...state, isCameraOpen: false };
        case "CHANGE_ANIMATRONICS_MOVING":
            return { ...state, areAnimatronicsMoving: action.content };

        default:
            return state;
    }
}
 35  src/reducers/configReducer.js 
@@ -0,0 +1,35 @@
const originalState = {
    hour: 0,
    isPlaying: true,
    energy: 100,
    time: 7000,
    blackout: false,
    jumpscare: false,
    gameOver: false,
    cameraButtonDisappear: false,
};

export default function config(state = originalState, action) {
    switch (action.type) {
        case "CHANGE_HOUR":
            if (state.jumpscare || state.gameOver) return state;
            return { ...state, hour: state.hour + 1 };
        case "CHANGE_ENERGY":
            if (state.hour === 6) return state;
            return { ...state, energy: state.energy - 1 };
        case "CHANGE_TIME":
            return { ...state, time: action.content };
        case "CHANGE_BLACKOUT":
            return { ...state, blackout: true };
        case "CHANGE_IS_PLAYING":
            return { ...state, isPlaying: action.content };
        case "CHANGE_JUMPSCARE":
            return { ...state, jumpscare: action.animatronic };
        case "CHANGE_CAMERA_BUTTON":
            return { ...state, cameraButtonDisappear: true };
        case "SET_GAME_OVER":
            return { ...state, gameOver: true };
        default:
            return state;
    }
}
 20  src/reducers/index.js 
@@ -0,0 +1,20 @@
import { combineReducers } from "redux";
import cameraReducer from "./cameraReducer";
import configReducer from "./configReducer";
import officeReducer from "./officeReducer";
import animatronicsReducer from "./animatronicsReducer";

const appReducer = combineReducers({
    cameraReducer,
    configReducer,
    officeReducer,
    animatronicsReducer,
});

export default function rootReducer(state, action) {
    if (action.type === "CLEAR_DATA") {
        state = undefined;
    }

    return appReducer(state, action);
}
 31  src/reducers/officeReducer.js 
@@ -0,0 +1,31 @@
const originalState = {
    leftDoor: false,
    rightDoor: false,
    leftLight: false,
    rightLight: false,
};

export default function office(state = originalState, action) {
    switch (action.type) {
        case "CHANGE_OFFICE_CONFIG":
            if (action.obj === "leftLight" && state.leftDoor) return state;
            if (action.obj === "rightLight" && state.rightDoor) return state;

            if (action.obj === "leftDoor" && !state.leftDoor && state.leftLight)
                return { ...state, leftLight: false, leftDoor: true };
            if (
                action.obj === "rightDoor" &&
                !state.rightDoor &&
                state.rightLight
            )
                return { ...state, rightLight: false, rightDoor: true };
            state[action.obj] = !state[action.obj];
            return state;

        case "CLEAR_DATA":
            return { ...originalState };

        default:
            return state;
    }
}
 116  src/service-worker.js 
@@ -0,0 +1,116 @@
/* eslint-disable no-restricted-globals */

// This service worker can be customized!
// See https://developers.google.com/web/tools/workbox/modules
// for the list of available Workbox modules, or add any other
// code you'd like.
// You can also remove this file if you'd prefer not to use a
// service worker, and the Workbox build step will be skipped.

import { clientsClaim } from "workbox-core";
import { ExpirationPlugin } from "workbox-expiration";
import { precacheAndRoute, createHandlerBoundToURL } from "workbox-precaching";
import { registerRoute } from "workbox-routing";
import {
  StaleWhileRevalidate,
  NetworkFirst,
  CacheFirst,
} from "workbox-strategies";
// import { googleFontsCache } from "workbox-recipes";

// googleFontsCache();

clientsClaim();

// Precache all of the assets generated by your build process.
// Their URLs are injected into the manifest variable below.
// This variable must be present somewhere in your service worker file,
// even if you decide not to use precaching. See https://cra.link/PWA
precacheAndRoute(self.__WB_MANIFEST);

// Set up App Shell-style routing, so that all navigation requests
// are fulfilled with your index.html shell. Learn more at
// https://developers.google.com/web/fundamentals/architecture/app-shell
const fileExtensionRegexp = new RegExp("/[^/?]+\\.[^/]+$");
registerRoute(
  // Return false to exempt requests from being fulfilled by index.html.
  ({ request, url }) => {
    // If this isn't a navigation, skip.
    if (request.mode !== "navigate") {
      return false;
    } // If this is a URL that starts with /_, skip.

    if (url.pathname.startsWith("/_")) {
      return false;
    } // If this looks like a URL for a resource, because it contains // a file extension, skip.

    if (url.pathname.match(fileExtensionRegexp)) {
      return false;
    } // Return true to signal that we want to use the handler.

    return true;
  },
  createHandlerBoundToURL(process.env.PUBLIC_URL + "/index.html")
);

// An example runtime caching route for requests that aren't handled by the
// precache, in this case same-origin .png requests like those from in public/
registerRoute(
  // Add in any other file extensions or routing criteria as needed.
  ({ url }) =>
    url.origin === self.location.origin &&
    (url.pathname.endsWith(".webp") || url.pathname.endsWith(".png")), // Customize this strategy as needed, e.g., by changing to CacheFirst.
  new CacheFirst({
    cacheName: "images",
    plugins: [
      // Ensure that once this runtime cache reaches a maximum size the
      // least-recently used images are removed.
      new ExpirationPlugin({
        maxAgeSeconds: 24 * 60 * 60,
      }),
    ],
  })
);

registerRoute(
  // Add in any other file extensions or routing criteria as needed.
  ({ url }) =>
    url.origin === self.location.origin && url.pathname.endsWith(".mp3"), // Customize this strategy as needed, e.g., by changing to CacheFirst.
  new CacheFirst({
    cacheName: "audios",
    plugins: [
      // Ensure that once this runtime cache reaches a maximum size the
      // least-recently used images are removed.
      new ExpirationPlugin({
        maxAgeSeconds: 24 * 60 * 60,
      }),
    ],
  })
);

registerRoute(
  ({ request }) => request.destination === "style",
  new StaleWhileRevalidate({
    cacheName: "static",
    plugins: [new ExpirationPlugin({ maxEntries: 50 })],
  })
);

registerRoute(
  ({ request }) =>
    request.destination === "script" || request.destination === "worker",
  new NetworkFirst({
    cacheName: "static-script",
    plugins: [new ExpirationPlugin({ maxEntries: 50 })],
  })
);

// This allows the web app to trigger skipWaiting via
// registration.waiting.postMessage({type: 'SKIP_WAITING'})
self.addEventListener("message", (event) => {
  if (event.data && event.data.type === "SKIP_WAITING") {
    self.skipWaiting();
  }
});

// Any other custom service worker logic can go here.
 141  src/serviceWorker.js 
@@ -0,0 +1,141 @@
// This optional code is used to register a service worker.
// register() is not called by default.

// This lets the app load faster on subsequent visits in production, and gives
// it offline capabilities. However, it also means that developers (and users)
// will only see deployed updates on subsequent visits to a page, after all the
// existing tabs open on the page have been closed, since previously cached
// resources are updated in the background.

// To learn more about the benefits of this model and instructions on how to
// opt-in, read https://cra.link/PWA

const isLocalhost = Boolean(
  window.location.hostname === "localhost" ||
    // [::1] is the IPv6 localhost address.
    window.location.hostname === "[::1]" ||
    // 127.0.0.0/8 are considered localhost for IPv4.
    window.location.hostname.match(
      /^127(?:\.(?:25[0-5]|2[0-4][0-9]|[01]?[0-9][0-9]?)){3}$/
    )
);

export function register(config) {
  if (process.env.NODE_ENV === "production" && "serviceWorker" in navigator) {
    // The URL constructor is available in all browsers that support SW.
    const publicUrl = new URL(process.env.PUBLIC_URL, window.location.href);
    if (publicUrl.origin !== window.location.origin) {
      // Our service worker won't work if PUBLIC_URL is on a different origin
      // from what our page is served on. This might happen if a CDN is used to
      // serve assets; see https://github.com/facebook/create-react-app/issues/2374
      return;
    }

    window.addEventListener("load", () => {
      const swUrl = `${process.env.PUBLIC_URL}/service-worker.js`;

      if (isLocalhost) {
        // This is running on localhost. Let's check if a service worker still exists or not.
        checkValidServiceWorker(swUrl, config);

        // Add some additional logging to localhost, pointing developers to the
        // service worker/PWA documentation.
        navigator.serviceWorker.ready.then(() => {
          console.log(
            "This web app is being served cache-first by a service " +
              "worker. To learn more, visit https://cra.link/PWA"
          );
        });
      } else {
        // Is not localhost. Just register service worker
        registerValidSW(swUrl, config);
      }
    });
  }
}

function registerValidSW(swUrl, config) {
  navigator.serviceWorker
    .register(swUrl)
    .then((registration) => {
      registration.onupdatefound = () => {
        const installingWorker = registration.installing;
        if (installingWorker == null) {
          return;
        }
        installingWorker.onstatechange = () => {
          if (installingWorker.state === "installed") {
            if (navigator.serviceWorker.controller) {
              // At this point, the updated precached content has been fetched,
              // but the previous service worker will still serve the older
              // content until all client tabs are closed.
              console.log(
                "New content is available and will be used when all " +
                  "tabs for this page are closed. See https://cra.link/PWA."
              );

              // Execute callback
              if (config && config.onUpdate) {
                config.onUpdate(registration);
              }
            } else {
              // At this point, everything has been precached.
              // It's the perfect time to display a
              // "Content is cached for offline use." message.
              console.log("Content is cached for offline use.");

              // Execute callback
              if (config && config.onSuccess) {
                config.onSuccess(registration);
              }
            }
          }
        };
      };
    })
    .catch((error) => {
      console.error("Error during service worker registration:", error);
    });
}

function checkValidServiceWorker(swUrl, config) {
  // Check if the service worker can be found. If it can't reload the page.
  fetch(swUrl, {
    headers: { "Service-Worker": "script" },
  })
    .then((response) => {
      // Ensure service worker exists, and that we really are getting a JS file.
      const contentType = response.headers.get("content-type");
      if (
        response.status === 404 ||
        (contentType != null && contentType.indexOf("javascript") === -1)
      ) {
        // No service worker found. Probably a different app. Reload the page.
        navigator.serviceWorker.ready.then((registration) => {
          registration.unregister().then(() => {
            window.location.reload();
          });
        });
      } else {
        // Service worker found. Proceed as normal.
        registerValidSW(swUrl, config);
      }
    })
    .catch(() => {
      console.log(
        "No internet connection found. App is running in offline mode."
      );
    });
}

export function unregister() {
  if ("serviceWorker" in navigator) {
    navigator.serviceWorker.ready
      .then((registration) => {
        registration.unregister();
      })
      .catch((error) => {
        console.error(error.message);
      });
  }
}
 6  src/store/store.js 
@@ -0,0 +1,6 @@
import { createStore } from "redux";
import reducers from "../reducers/index";

const store = createStore(reducers);

export default store;
 2  static/css/main.25f9cd0d.chunk.css 
This file was deleted.

 1  static/css/main.25f9cd0d.chunk.css.map 
This file was deleted.

 3  static/js/2.82173691.chunk.js 
This file was deleted.

 50  static/js/2.82173691.chunk.js.LICENSE.txt 
This file was deleted.

 1  static/js/2.82173691.chunk.js.map 
This file was deleted.

 2  static/js/main.b3dd4667.chunk.js 
This file was deleted.

 1  static/js/main.b3dd4667.chunk.js.map 
This file was deleted.

 2  static/js/runtime-main.79dfb199.js 
This file was deleted.

 1  static/js/runtime-main.79dfb199.js.map 
This file was deleted.

 11,394  yarn.lock 
Large diffs are not rendered by default.

0 comments on commit e15f066
Please sign in to comment.
© 2022 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Loading complete
