
來源:[How to Create a PWA With Next.js in 10 Minutes](https://www.youtube.com/watch?v=ARNN_zmrwcw)


1.建立sample
npx create-next-app next-pwa-demo

2.安裝next-pwa

```
cd next-pwa-demo
npm install next-pwa
```

https://www.npmjs.com/package/next-pwa


3.產生manifest.zip

https://www.simicart.com/manifest-generator.html/

![Imgur](https://i.imgur.com/iA7nFgo.png)

下載manifest.zip，將內容檔案copy到public底下

將manifest.webmanifest 更名為manifest.json


4.新增 pages/_document.js

5.測試

```
npm run build
npm run start
```

開啟chrom，可以看到安裝
![Imgur](https://i.imgur.com/JM983Ax.png)
