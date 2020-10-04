<h1 align="center"> Auto_Build_ErfanGSIs </h1>

<p align="center">
	一个基于 Github Actions 制作的利用 ErfanGSI 自动生成 GSI 镜像的脚本
</p>

## 运行步骤如下： 
- 首先， Fork 这个仓库；
- 接着，编辑<code>[Build_ErfanGSIs.yml](.github/workflows/Build_ErfanGSIs.yml)</code>文件，把其中的`ROM_URL`改成你要做 GSI 的底包（注意直链），还有`ROM_NAME`改成你的 ROM 名称；
- 然后，按右上角的 Star 小星星就可以开始了！
- 最后，点击上面的`Actions`，再点击`Auto_Build_ErfanGSIs`，在`Artifacts`里即可看到上传的文件，点击即可下载。 

#### 注意：因为使用了不同的压缩方式，完全执行该脚本需要约两个小时，请耐心等待脚本跑完。

### 更改内容
<details markdown='1'><summary>点击展开/收起</summary>

1.使用 Github Actions 项目上传，避免随时间的推移出现的上传成功但无法下载或直接上传失败的问题

2.更改了压缩方式，使上传文件体积减小，也加快了下载速度

3.把不同的镜像分别打包上传，避免无效下载，缩短了下载时间

4.增加了打包源代码的操作，方便更新和获取源代码

2020.09.27
删去`Get_ErfanGSIs_Source_Code.yml`,修改`Build_ErfanGSIs.yml`执行项目顺序

2020.10.04
修正`Build_ErfanGSIs.yml`错误的代码导致的脚本执行失败
</details>

### 附： ErfanGSI 支持的 ROM
> `ROM_NAME`里填一摸一样的，下的 ROM 也要一样； Generic 是（类）原生的意思。

### 9 Pie：
<details markdown='1'><summary>点击展开/收起</summary>

> ColorOS Flyme Generic MIUI Moto Nubia OneUI OxygenOS Pixel Xperia ZUI ZenUI
</details>

### 10 Q：
<details markdown='1'><summary>点击展开/收起</summary>

> Generic MIUI OxygenOS Pixel
</details>

### 11 R：
<details markdown='1'><summary>点击展开/收起</summary>

> Generic Pixel
</details>
