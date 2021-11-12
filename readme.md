# 小小星空扩展方案集

## 项目介绍

搜集了一些第三方制作或修改的方案，例如星空一道、星空两笔ZV、星空两笔单字版等，并移植到[小小星空输入法](https://xkinput.gitee.io/xxxk-help/)，制成扩展方案包。目前有以下扩展方案包：

| 扩展方案包            | 方案名           | 源项目                                      | 作者      | 简介                                                   | 更新日期   |
| --------------------- | ---------------- | ------------------------------------------- | --------- | ------------------------------------------------------ | ---------- |
| `xxxk-schema-xkyd`    | 星空一笔道       | [Gitee](https://gitee.com/dzyht/rime_xkybd) | 歌颂      | 一笔的双拼+键道的笔画                                  | 2018-09-19 |
| `xxxk-schema-xklbzv`  | 星空两笔ZV       | [星空QQ群][星空QQ群]                        | 冉冉      | 基于星空两笔，Z键和V键换位以改善手感                   | 2018年     |
| `xxxk-schema-xklbdz`  | 星空两笔单字版   | [星空QQ群][星空QQ群]                        | 右耍      | 基于星空两笔，摒弃词组，重排单字                       | 2018年     |
| `xxxk-schema-xklbddr` | 星空两笔单字DR版 | [Gitee](https://gitee.com/xkinput/xklbDR)   | DRGICEAKE | 基于星空两笔，摒弃词组，重排单字，添加少量二重和无理码 | 2019-08-24 |
| `xxxk-schema-xklbs`   | 星空两笔S        | [Gitee](https://gitee.com/xkinput/xklbs)    | cheliox   | 基于星空两笔，改造为单字二码顶，词组五码顶             | 2019-11-13 |

方案的规则细节请参考各方案的源项目页，或相应`xxxk-schema-????`目录下的`doc`文件夹。

> 为了保持小小星空风格的统一，各扩展方案包只移植了源项目里的主要码表，符号码表统一采用小小星空的公用码表。

## 使用方法

1. 下载感兴趣的扩展方案包（例如`xxxk-schema-xklbs`），将其中的文件覆盖到小小输入法的程序目录下（例如Windows版的`C:\Program Files (x86)\xxxk`，安卓版的`sdcard\yong`）。

   > 这些方案都依赖于小小星空的公用包`xxxk-xkcommon`。如果想用于小小星空以外的小小类输入法，需先[下载](https://github.com/xkinput/xxxk)小小星空项目，将其中`xxxk-xkcommon`目录下的文件覆盖到小小输入法的程序目录下。

2. 在小小星空输入法中加载方案。如果原来已经加载了该方案，请先卸载该方案，再重新加载。加载、卸载方案的方法，请参考小小星空文档中的[相关说明](https://xkinput.github.io/xxxk-help/#/intro-custom?id=%e5%8d%b8%e8%bd%bd%e5%8a%a0%e8%bd%bd%e6%96%b9%e6%a1%88)。

3. 热重启输入法，切换到该方案。

## 参与贡献

参考[教程](https://xkinput.github.io/xxxk-help/#/intro-custom)移植或制作自己的方案，并贡献到本项目。

##  更新记录

##### 20201216

* 新增：不完美移植星空两笔S
* 项目迁移到小小星空组织



[星空QQ群]: https://jq.qq.com/?_wv=1027&k=5tVcZlL "星空QQ群"

