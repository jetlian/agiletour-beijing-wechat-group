# 北京敏捷社区活动粉丝群

这是一个面向北京敏捷社区参与者的微信群邀请页面。访问者可以扫描页面中的二维码加入社区微信群；当二维码失效时，也可以通过页面展示的电话、微信或邮箱联系社区志愿者。

## 官方网站
[北京敏捷社区网站](http://wwww.agiletour-beijing.com)

## 页面预览

![北京敏捷社区活动粉丝群二维码](images/agile-bj-wechat.jpg)

## 功能特点

- 展示北京敏捷社区微信群二维码
- 提供二维码失效后的志愿者联系方式
- 采用响应式布局，适配手机与桌面浏览器
- 使用深色主题，界面简洁、重点突出
- 无需构建工具，可作为静态页面直接部署

## 项目结构

```text
group.agiletour-beijing/
├── images/
│   └── agile-bj-wechat.jpg  # 微信群二维码图片
├── index.html               # 页面入口及样式
└── README.md                # 项目说明
```

## 本地预览

项目没有额外依赖，直接使用浏览器打开 `index.html` 即可预览。

也可以在项目目录中启动一个本地静态服务器：

```bash
python3 -m http.server 8000
```

然后访问：

```text
http://localhost:8000
```

## 部署

这是一个纯静态页面，可以部署到 GitHub Pages、Netlify、Vercel 或任意静态网站服务器。

使用 GitHub Pages 时，可在仓库的 **Settings → Pages** 中选择对应分支和目录进行发布。

## 内容维护

### 更新微信群二维码

将新的二维码图片替换到以下路径，并保持文件名不变：

```text
images/agile-bj-wechat.jpg
```

如需使用其他文件名，请同步修改 `index.html` 中 `<img>` 标签的 `src` 属性。

### 更新联系方式

在 `index.html` 的 `.contact-info` 区域修改电话、微信或邮箱信息，并确保 `tel:` 与 `mailto:` 链接中的内容保持一致。

## 联系方式

- 邮箱：agiletourbeijing@hotmail.com

