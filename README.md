# Electron Netease Cloud Music

**UNOFFICAL** client for music.163.com . Powered by [Electron](https://electronjs.org), [Vue](https://vuejs.org), and [Muse-UI](https://muse-ui.org).

[![build status](https://api.travis-ci.org/Rocket1184/electron-netease-cloud-music.svg?branch=master)](https://travis-ci.org/Rocket1184/electron-netease-cloud-music/builds)
[![dependencies staus](https://david-dm.org/rocket1184/electron-netease-cloud-music/status.svg)](https://david-dm.org/rocket1184/electron-netease-cloud-music)
[![devDependencies staus](https://david-dm.org/rocket1184/electron-netease-cloud-music/dev-status.svg)](https://david-dm.org/rocket1184/electron-netease-cloud-music?type=dev)

## ScreenShots

### Now Playing

![Player](https://user-images.githubusercontent.com/13914967/43312528-32f7d44c-91c0-11e8-8098-124b86d2d260.png)

<details>

<summary>All screenshots</summary>

### 收藏歌曲到歌单

![Add to Playlist](https://user-images.githubusercontent.com/13914967/43312533-34e6c5e2-91c0-11e8-8d7d-1dac526bdb63.png)

### 我的歌单

![Playlists](https://user-images.githubusercontent.com/13914967/43312550-3d2664e2-91c0-11e8-81db-dc709f7c89f4.png)

### 侧栏

![Sidebar](https://user-images.githubusercontent.com/13914967/43313146-ce4a345c-91c1-11e8-86b9-a85962451769.png)

### 首页（目前仅有每日推荐歌曲）

![Index](https://user-images.githubusercontent.com/13914967/43312538-37863dbe-91c0-11e8-98a5-ad1ffbb82a62.png)

### 搜索

![Search Music](https://user-images.githubusercontent.com/13914967/43312543-3893de3c-91c0-11e8-9eaf-99c7f55d2c48.png)

### 应用设置

![Settings](https://user-images.githubusercontent.com/13914967/43312886-2b208cae-91c1-11e8-8645-f9eee37bb4e1.png)

### 自定义色调

![Color Picker](https://user-images.githubusercontent.com/13914967/43312879-250465c0-91c1-11e8-91af-3e7a601381c4.png)

### 暗色主题

![Player_Dark](https://user-images.githubusercontent.com/13914967/43312592-5ea44ec2-91c0-11e8-83bd-0d1c55fee9e3.png)

![Collect_Dark](https://user-images.githubusercontent.com/13914967/43312598-62f658ee-91c0-11e8-89c1-c863a39d6e84.png)

![Playerlists_Dark](https://user-images.githubusercontent.com/13914967/43312602-64305a48-91c0-11e8-8f88-1e12a367d191.png)

</details>

## Features

- ~~高仿~~ 音乐播放界面
- 用户登录（手机号/邮箱/用户名）
- 每日签到（可同时签到 PC 端和移动端）
- 播放每日歌曲推荐
- 播放收藏/创建的歌单
- 喜欢音乐（加红心）
- 收藏音乐到歌单
- Linux 桌面媒体控制（ MPRIS ）集成
- 自定义主题颜色，可选全局暗色主题

## Installation

### Arch Linux

[electron-netease-cloud-music<sup>AUR</sup>](https://aur.archlinux.org/packages/electron-netease-cloud-music/) is avalible in AUR now!

Clone the repo

```sh
git clone https://aur.archlinux.org/electron-netease-cloud-music.git
```

or install with your favorite AUR helper

```sh
yay -S electron-netease-cloud-music
```

### Other GNU/Linux distro or macOS

Download prebuilt binary packages (include bundled electron) there -> [![hreoku status](https://heroku-badge.herokuapp.com/?app=ncm-releases&style=flat&svg=1)](https://ncm-releases.herokuapp.com/)

### asar archive without electron

Install electron with `npm` or your distro's package manager first.

Jump to [release page](https://ncm-releases.herokuapp.com/) and download `asar` package, then run with

```sh
electron /path/to/electron-netease-cloud-music_*.asar
```

## TODOs

<details>
<summary>All TODOs</summary>

- [ ] 各种搜索
  - [ ] 单曲
    - [x] 显示结果
    - [x] 播放搜索到的歌曲
    - [ ] 浏览/发布歌曲评论
  - [ ] 歌手
    - [x] 显示结果
    - [ ] 歌手页面
  - [ ] 专辑
    - [x] 显示结果
    - [ ] 专辑详情页面
  - [ ] 歌单
    - [ ] 显示结果
    - [ ] 歌单内容页面
    - [ ] 收藏歌单
  - [ ] MV
    - [ ] 显示结果
    - [ ] 播放 MV
  - [ ] 用户
    - [ ] 显示结果
    - [ ] 用户信息页面
- [ ] 私人 FM （这个功能我几乎不用，就先鸽着吧）

</details>

## Development & Build

``` bash
# install dependencies
yarn

# serve with hot reload at http://localhost:24353
yarn dev

# bundle JavaScript and CSS
yarn dist

# package the app
yarn build linux
yarn build darwin
```
