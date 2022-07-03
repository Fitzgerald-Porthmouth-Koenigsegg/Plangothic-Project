![Image text](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic/blob/main/pic/31.png)

# Plangothic Project（遍黑体项目）

## 概述
遍黑体是基于[思源黑体](https://github.com/adobe-fonts/source-han-sans)进行字符扩展及补充的项目。该项目由本人在大约 2020 年 6 月份所开启，其最终目标是尽可能补全整个 Unicode，并制作出一部分原本没有黑体风格字符的黑体（以中日韩統一表意文字为主）。

## 收录范围
需注意：一个字体文件所能容纳的字符数量有限，因此遍黑体项目分成了两个字体。其中 Part1 以中日韩統一表意文字为主，Part2 以尽可能补全 Unicode 为主。

### Part1 收录范围
- C0, C1 控制字符
- 思源黑体特有的字母I的写法
- 与汉字等宽的12个国际象棋符号
- 4个注音符号补充
- 中日韩統一表意文字基本区，扩展A区有字形改动的或者字形不符合G源的汉字
- 中日韩統一表意文字基本区补充，扩展 A 区补充
- 假名补充，假名扩展A，扩展B，小型假名扩展
- 中国象棋
- 中日韩統一表意文字扩展 B 区，扩展 C 区，扩展 D 区，扩展 E 区，扩展 F 区
- 部分中日韩統一表意文字兼容区和兼容补充区的汉字
- 其他各处搜寻到的目前尚未收录进 Unicode 的汉字（详见下方“私用区收录范围”）
  * **※注意：Mob的收录范围即在Part1的基础上去除了私用区，去除了思源黑体自带的汉字，加入了扩展G区汉字。Mob版本旨在顾及到一些无法将自己手机进行root从而更换字体这种操作的用户**

### Part2 收录范围
- C0, C1 控制字符
- ASCII 字符
- 大量的大部分终端所不能支持的基本平面和第一平面字符（包括东亚、南亚、西亚的文字，以及一些其他符号等，因为其分布范围过于琐碎，无法全部列出）
- 中日韩統一表意文字扩展 G 区，扩展 H 区（草案）
- 其他各处搜寻到的目前尚未收录进 Unicode 的汉字（详见下方“私用区收录范围”）

### 私用区收录范围
- [WFG 所作“全宋体”](http://fgwang.blogspot.tw/)私用区（已剔除目前已经加入 Unicode 的汉字）
- [Sinzengo 所作二简字字体](https://tieba.baidu.com/p/6544045146)（大多为《第二次汉字简化方案（草案）》第二表中目前没有加入 Unicode 的汉字）
- 使用 [Glyphwiki](https://glyphwiki.org/)（字形维基）所作目前没有加入 Unicode 的变体假名
- 《说文解字》小篆字形（来自[字统网 (zi.tools)](https://zi.tools/)）
- [中华书局宋一体](http://www.ancientbooks.cn/helpcore?font)私用区
- [すきまゴシック / Sukima Gothic](https://oppekebekkanko.booth.pm/items/2117070)（隙间黑体）私用区
- David Evillious 所作维基风格注音符号扩展（已剔除目前已经加入 Unicode 的符号）
- [Hulenkius](https://github.com/Hulenkius) 所作窄仓颉字母
- [Hulenkius](https://github.com/Hulenkius) 所作带圈字符区块简写
- [Nôm Na Tống](https://github.com/nomfoundation/font)（喃那宋）私用区
- [Han-Nom Minh](https://www.facebook.com/groups/hannom.revival/permalink/5493179204047328)（汉喃明体）私用区（以及 [Hulenkius](https://github.com/Hulenkius) 的补充）
- [BabelStone Han](https://www.babelstone.co.uk/Fonts/index.html) 私用区（已剔除目前已经加入 Unicode 的汉字）
- Sawndip（古壮字用字体）私用区（已剔除目前已经加入 Unicode 的汉字）
- 中国大百科全书内置字体私用区（已剔除目前已经加入 Unicode 的汉字）
- 其他各处搜寻到的来源无法考证并且目前尚未收录进 Unicode 的汉字

## 字体特色
- 已支持截止到 Unicode 14.0 较新的绝大多数字符。
- 字体本身的风格以思源黑体为蓝本。
- 思源黑体中存在的部件，则直接套用，反之则借助其他的辅助工具。
- 所有汉字的字形均为国标字形或假想国标字形，并且也解决了一些字同源不同规范写法等的问题（例如同为 G 源的𰃙、𰃜、𰃟三字），并不会完全按照 Unicode 文档中的字形进行制作，并严格遵循笔画避让原则。
- 会根据提前发布的 Unicode 文档，抢占先机，先行收录即将确定的字符。

## 制作要求
任何人都可以参与到遍黑体项目的制作过程当中。可加入 QQ群[1135661191](https://jq.qq.com/?_wv=1027&k=xRTzFAfD)，来对本项目进行更详细的商讨和质询。

本群长期招贤纳士，您可以动用自己的一份力，让身边更多的人了解这样的一个企划，亦欢迎会制作字体的技术型人才，遍黑体项目未来的发展离不开你的宣传和鼓励。

### 主要贡献者
- 主制作：[FIZ](https://github.com/Fitzgerald-Porthmouth-Koenigsegg)、[HLK](https://github.com/Hulenkius)
- 联合制作：[SMM](https://github.com/SomeyaMako)、MAT、SCH、CKG
- 其他协助：[AAF](https://github.com/0xAA55)、[HNC](https://github.com/hfhchan)、ESC
- 过往贡献者：SZG、ITM、BNZ、AKT

另外还有不少曾经对遍黑体项目给予相应支持、参与制作，但退出了本项目并且无法考证姓名的人员，我们为他们的离去而感到遗憾，也在此对他们予以感谢，祝愿他们前程似锦。

## 字体授权
本字体基于 SIL Open Font License 修改、补充思源黑体和发布。详见[授权文件](LICENSE.txt)。

遍黑体项目下所有的字体，任何个人、企业、团队皆可免费使用。但请注意，在进行二次修改时，严禁再使用“Plangothic”、“遍黑体”等名称，二次修改过后的版本亦必须以 SIL Open Font License 发表。

严禁任何个人、企业、团队对该字体文件进行售卖（包括但不限于将字体文件单独售卖，与其他字体进行捆绑售卖、需付费办理特殊权限才可使用字体等行为），如您是付费获得的此字体，请立刻对其进行举报，必要时可协助相关司法机关。

## 支持我们
遍黑体项目制作难度巨大，制作时间很长，若愿意支持我们，在此致以诚挚感谢！您的捐助可以帮助遍黑体项目以更好的方向发展。若您因为种种原因无法进行捐助，您仍可以通过其他方式为此项目做出贡献，如帮助检查错误字形、对不美观字形提出自己的改进意见等，正所谓“不积跬步，无以至千里，不积小流，无以成江海”。

在您捐助之前请务必注意以下几点：
- 捐款前请务必仔细确付款账户（支付宝：Fitzgerald K.、微信：㘜䘈䚖䜚䟐䠪䀌䆐䉵䎚䑇䒐🙃。如用户名有改动，则第一时间会做出更正），我们无法承担您受骗的损失。
- 目前只有这一个页面是正式的受捐页面。如果您在其它地方看到此项目的捐款链接，请立刻对其进行举报，必要时可协助相关司法机关。
- 您向本项目捐助，即默认表明您赞同我们的理念，并愿意以此种方式支持我们的发展。捐助者提出的意见会被认真考虑，但捐款再多也没有权利以个人意志改变本项目的宗旨和公益性质。
- 捐助后如愿意，可留言写明您的捐款时间和金额，感谢您对本项目的支持。
- 所有捐助资金均会逐一记录，并将全部用于该项目的技术支持等开销，不会被私用。
![Image text](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic/blob/main/pic/1650383987393.jpg)

## 联系方式
- GitHub: https://github.com/Fitzgerald-Porthmouth-Koenigsegg
- Twitter: https://twitter.com/Fitzgerald_P_K_/
- 字形维基: http://zhs.glyphwiki.org/wiki/User:fitzgerald
- QQ邮箱: 374601620@qq.com
- QQ: 374601620
- Gmail: fitzgeraldkoenigsegg@gmail.com
- Telegram: @Fitzgerald_P_K
