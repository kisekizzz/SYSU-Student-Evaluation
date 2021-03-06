# SYSU-Student-Evaluation
中山大学教务系统学生自动评教脚本

## 更新

* 2019秋季学期新版教务评教系统，出现了区分大小写的验证码，出现概率为首次100%及随后约20%。
* 本次更新加入了检测验证码的机制。
  * Console出现红字POST无需惊慌
* 鸣谢：[双鸭山电报小组](https://t.me/sbddy2019)给予我的启发和帮助
---

## 如何使用
1. [登录教务系统](https://jwxt.sysu.edu.cn/)后，打开[评教页面](https://jwxt.sysu.edu.cn/jwxt/mk/evaluation/#/evaluation)
2. 打开 [AutoEval.js](./AutoEval.js)，全选，复制
* [方便Ctrl+A的版本](https://raw.githubusercontent.com/oudoubleyang/SYSU-Student-Evaluation/master/AutoEval.min.js)
3. 切换到[评教页面](https://jwxt.sysu.edu.cn/jwxt/mk/evaluation/#/evaluation)，按F12打开控制台 (Console)，粘贴代码，回车
* 如果没有控制台，请切换到Chromium内核浏览器
4. 等待自动评教完成。若有无法评价的项目，将会提示。

## FAQ
* 一定要使用Chromium内核浏览器
* 如果运行出错，请更新浏览器
* 好评率可以调```goodrate```参数，但是……尽量全五星吧（
* 如果你不知道什么是Console，请点击下图查看
<img src="https://github.com/oudoubleyang/Hosting/raw/master/SYSU-Student-Evaluation/console.png" width="300">

## 鸣谢
**[双鸭山电报频道](https://t.me/cshs_edu_pill)的[这个脚本](https://t.me/cshs_edu_pill/273)**

## 免责声明
* 本脚本虽然经过测试，但无法保证适用所有情况，且作者不承担因程序出错产生的任何后果。
