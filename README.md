
### 添加图片

将要上传的图片压缩并上传到CDN

* 压缩软件推荐 `Squash`，在线压缩可以使用 [https://tinypng.com/](https://tinypng.com/)
* 上传CDN 使用[图床工具](https://sm.ms/) 

#### 在文章中添加图片

将上述图片添加到图床后，切换到 `Markdown` 这个选项，复制上传后的地址，粘贴到文件中即可。

![dmoe.png](https://i.loli.net/2019/05/31/5cf0a1378340331201.png)

#### 在配置文件yml中添加图片

将图片上传图床后，切换到 `URL` 选项卡，复制其中的链接，将其粘贴到需要的配置文件位置

![demo.png](https://i.loli.net/2019/05/31/5cf0a0f0581af84689.png)

```yaml
async:
  name: 交替传译
  items:
    "全球黑客“奥斯卡” DEFCON China 2018（北京，2018年）":
      avatar: https://i.loli.net/2019/05/31/5cf09f315198582608.jpg
```
