# 程序员自制饮品指南

[![build](https://github.com/MoYuM/HowToDrink/actions/workflows/build.yml/badge.svg)](https://github.com/MoYuM/HowToDrink/actions/workflows/build.yml)
[![License](https://img.shields.io/github/license/MoYuM/HowToDrink)](./LICENSE)
[![GitHub contributors](https://img.shields.io/github/contributors/MoYuM/HowToDrink)](https://github.com/MoYuM/HowToDrink/graphs/contributors)
[![npm](https://img.shields.io/npm/v/how-to-cook)](https://www.npmjs.com/package/how-to-cook)
![Man hours](https://manhours.aiursoft.cn/r/github.com/MoYuM/HowToDrink.svg)
[![Docker](https://img.shields.io/badge/docker-latest-blue?logo=docker)](https://github.com/MoYuM/HowToDrink/pkgs/container/how-to-cook)

这是一个 [HowToCook](https://github.com/Anduin2017/HowToCook) 的 fork，只不过本仓库专注于饮品的制作方式，包括但不限于咖啡、茶、酒、以及其他饮料。

除了常见的饮品配方外，也欢迎分享自己开发的好喝饮品，并给它取一个独特的名字~

同样，我希望它是一个由社区驱动和维护的开源项目，使更多人能够一起做一个有趣的仓库。所以非常欢迎大家贡献它~

## 本地部署

如果需要在本地部署菜谱 Web 服务，可以在安装 Docker 后运行下面命令：

```bash
docker pull ghcr.io/anduin2017/how-to-cook:latest
docker run -d -p 5000:5000 ghcr.io/anduin2017/how-to-cook:latest
```

如需下载 PDF 版本，可以在浏览器中访问 [/document.pdf](https://cook.aiursoft.cn/document.pdf)

## 如何贡献

针对发现的问题，直接修改并提交 Pull request 即可。

在写新菜谱时，请复制并修改已有的菜谱模板: [示例菜](https://github.com/Anduin2017/HowToCook/blob/master/dishes/template/%E7%A4%BA%E4%BE%8B%E8%8F%9C/%E7%A4%BA%E4%BE%8B%E8%8F%9C.md?plain=1)。

## 做菜之前

{{before}}

## 菜谱

{{index_stars}}

{{main}}

## 进阶知识学习

如果你已经做了许多上面的菜，对于厨艺已经入门，并且想学习更加高深的烹饪技巧，请继续阅读下面的内容：

{{after}}
