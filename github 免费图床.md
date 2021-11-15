# 使用GitHub+PicGO创建免费图床

## Github部分配置

访问网址https://github.com/settings/tokens/，前提是自己有GitHub账号并登录

![tempsnip](https://raw.githubusercontent.com/yezhoubing/yzbimghost/main/img/tempsnip.png)

点击创建新的token

![tempsnip](https://raw.githubusercontent.com/yezhoubing/yzbimghost/main/img/1.png)

之后会出现一串字母与数字的字符串，复制下来

![2](https://raw.githubusercontent.com/yezhoubing/yzbimghost/main/img/2.png)

在Github中创建一个仓库储存图片，当你创建仓库时是没有后面的img的文件的，是由于后续PicGO配置的。

## PicGO配置

首先下载PicGO（https://github.com/Molunerfinn/PicGo），按照下图配置

![3](https://raw.githubusercontent.com/yezhoubing/yzbimghost/main/img/3.png)

自定义域名的作用是在上传图片后成功后，`PicGo`会将“自定义域名+上传的图片名”生成的访问链接，放到剪切板上https://raw.githubusercontent.com/用户名/RepositoryName/分支名，自定义域名需要按照这样去填写，例如我这里是：https://raw.githubusercontent.com/yezhoubing/yzbimghost/main，后续可以直接通过域名查看图片

ctrl+shift+p：将剪贴板的图片上传

这样可以在PicGo上传时传到对应仓库中，如果图片比较多，建议批量上传

## Typora配置

如下图配置

![4](https://raw.githubusercontent.com/yezhoubing/yzbimghost/main/img/4.png)

当验证图片上传选项点击显示成功时，说明配置成功。

之后便可以开心的在typora中使用图床了！

注：上传图片不要上传同名图片，否则会报错。

​        Github有防盗链，所以在传到第三方网址时，me文件中的图片不可见（适用于个人使用），如果想要在第三方访问，推荐阿里云或腾讯云（收费），可以参考下面这篇[文章](https://www.cnblogs.com/keeya/archive/2018/08/17/9495460.html)

