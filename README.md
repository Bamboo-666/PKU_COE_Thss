# PKU_COE_Thss
北京大学工学院本科毕业论文参考模版。作者在写本科毕业论文的时候编写了此模版，在此发布在网上给大家使用，遵守 MIT License。

## 注意事项

- 本模版根据 2019 年 11 月修订的 [本科生毕业论文的基本要求及格式](https://www.coe.pku.edu.cn/docs/20191122105033554079.pdf) 进行了修订。[官网](https://www.coe.pku.edu.cn/jxzs/bksjy/cyxz/xscyxz/bylw/index.htm)。
- 请使用完整的 TeX live 包进行编译，此模版使用了大量的包，请勿使用 CTeX 软件（非包）， CTeX 软件已停止更新。
- 本模版不包括封面，请用学院给的模版的封面生成 PDF 后放到第一页。
- 您可以使用您电脑上的字体，$\LaTeX$ 默认字体可能无法显示某些生僻字。

## 使用建议

- 建议使用多文件的方式，文章主体内容在 `chap` 文件夹里，您可以复制 `chap1` 后编写之后的章节，并在 `main.tex` 里导入。

## 个性化设置

- 各种设置都放在了 `setting.tex` 文件夹里，可以方便地修改设置。
- 字体设置在 `main.tex` 文件夹里。
- 链接的颜色设置为了[北大红](https://vim.pku.edu.cn/bsgf/index.htm)，在 `setting.tex` 的第 83 行，您可以根据自己的喜好修改颜色。

```tex
\definecolor{PKUred}{cmyk}{0,1,1,0.45}
```

## 联系方式

如有问题，欢迎给我发邮件，或者在 GitHub 上发 issue。

袁磊祺 yuanlq@pku.edu.cn

