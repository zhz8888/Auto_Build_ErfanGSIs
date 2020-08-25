<h1 align="center"> Get_ErfanGSIs_Source_Code </h1>

<p align="center">
	一个基于 Github Actions 制作的自动打包 ErfanGSI 源代码的脚本
</p>

#注意：该脚本的功能在<code>[Build_ErfanGSIs.yml](.github/workflows/Build_ErfanGSIs.yml)</code>里已包含，如果你有足够的时间和耐心获取源代码，大可不必执行该脚本！

### 运行步骤如下： 
- 首先， Fork 这个仓库；
- 接着，编辑<code>[Get_ErfanGSIs_Source_Code.yml](.github/workflows/Get_ErfanGSIs_Source_Code.yml)</code>文件，按需求选择你需要的源码（可选）；
- 然后，按右上角的 Star小 星星就可以开始了！
- 最后，点击上面的`Actions`，再点击`Get_ErfanGSIs_Source_Code`，在`Artifacts`里即可看到上传的源代码，点击即可下载。 

##注意：为了解决按 Start 小星星时两个项目同时开始的冲突，默认全部注释所有触发条件，如需使用请注释<code>[Build_ErfanGSIs.yml](.github/workflows/Build_ErfanGSIs.yml)</code>里的所有触发条件或两个脚本使用不同的触发条件。
