# qq-music-desktop
`
?$ npm install request --save
?$ npm install request-promise --save
`
## package.json安装
`
$ npm init -y
`
## Electron 安装
### 1.全局安装
`
$ sudo ELECTRON_MIRROR=https://npm.taobao.org/mirrors/electron/ npm install electron -g --verbose
`
### 2.文件夹安装
`
$ ELECTRON_MIRROR=https://npm.taobao.org/mirrors/electron/ npm install electron --save --verbose
`

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## Main Pages
`GET /musicmac/v4/client_url.json?r=39781 HTTP/1.1`

```json
{
  "kUrlRecommend": "https://c.y.qq.com/node/musicmac/v4/index.html",
  "kUrlRanking": "https://y.qq.com/musicmac/v4/toplist/index.html",
  "kUrlChannel": "https://y.qq.com/musicmac/v4/playlist/index.html",
  "kUrlRadio": "https://y.qq.com/musicmac/v4/radio/index.html",
  "kUrlSingerDetailMID": "https://y.qq.com/musicmac/v4/singer/detail.html?singermid=%@",
  "kUrlSingerDetailSingerID": "https://y.qq.com/musicmac/v4/singer/detail.html?singerid=%@",
  "kUrlSingerSongListByMID": "https://y.qq.com/musicmac/v4/singer/songlist.html?singermid=%@",
  "kUrlSingerAlbumListByMID": "https://y.qq.com/musicmac/v4/singer/albumlist.html?singermid=%@",
  "kUrlAlbumDetailMID": "https://y.qq.com/musicmac/v4/album/detail.html?albummid=%@",
  "kUrlAlbumDetailAlbumID": "https://y.qq.com/musicmac/v4/album/detail.html?albumid=%@",
  "kUrlFolderDetailFolderID": "https://y.qq.com/musicmac/v4/playlist/detail.html?id=%@",
  "kUrlRecoverFolder": "https://y.qq.com/#type=mymusic&p=list_recover.html",
  "kUrlYQQDownload": "https://y.qq.com/#type=down&p=index",
  "kUrlUserTips": "https://y.qq.com/musicmac/v4/usertips.html",
  "kUrlUserProfileByUin": "https://y.qq.com/musicmac/v4/profile/profile.html?uin=%@",
  "kUrlEditFolderInfo": "https://y.qq.com/musicmac/v4/create_taoge.html?dirid=%@",
  "kUrlBuyAlbum": "https://y.qq.com/musicmac/v4/buyalbum.html",
  "kUrlShareSong": "https://y.qq.com/musicmac/v4/music_share.html?sharetype=0&id=%@",
  "kUrlShareMyFoler": "https://y.qq.com/musicmac/v4/music_share.html?dirid=%@&sharetype=3",
  "kUrlShareTaoFoler": "https://y.qq.com/musicmac/v4/music_share.html?dirid=%@&sharetype=2",
  "kUrlCategory": "https://y.qq.com/musicmac/v4/playlist/index.html?categoryId=%@",
  "kUrlMVRoot": "https://y.qq.com/musicmac/v4/mv/index.html",
  "kUrlPlayMvID": "https://y.qq.com/musicmac/v4/mv/player.html"
}
```
