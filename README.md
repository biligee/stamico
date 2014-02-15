Stamico 定远正书体
================
A hand-written font.
一个手写字体。

Introduction 简介
----------------
The font is named _Stamico_ or _Dingyuan Regular Script_. The name _Stamico_ came from the idea of pronounciation, while the name _Dingyuan Regular Script_ came from the author's name in a Chinese input method and the style of the font.

There are now 6007 glyphs in the font, including whitespaces, while there are 5352 CJK glyphs in it. The font currently contains all basic ASCII characters. There are also some Latin, Greek, math symbols, dingbats, punctuations, Bopomofo symbols, Chinese characters (mostly simplified) in an arbitrary selection.

The font is licenced under the [Open Font License](http://scripts.sil.org/OFL).
The scripts used to create the font are licenced under the GNU General Public License v3 or later.

The current version of the font is 1.1.2.1402. Build date: Feb. 6, 2014.


字体中文名“定远正书体”，英文名Stamico。英文名字没有来历，只是因为读起来顺口。中文名来源于作者名字的输入法提示以及字体风格。

字体共有6007个字符（包括空白），其中汉字5352个。字体现在包括所有基础ASCII字符。另有一些随机选择的拉丁、希腊字母，一些特殊符号和数学符号，注音符号，标点符号等。中文字符大部分为简体、大陆写法。

字体授权协议：OFL（开放字体授权），即您可以自由使用、修改、以相同协议再发行，但再发行时不可使用原字体名。
脚本授权协议：GNU通用公共授权，版本3+。

当前版本：1.1.2.1402。创建日期：2014年2月6日。

Screenshots 截图
---------------
![Sample](https://github.com/gumblex/stamico/blob/master/stamico.png?raw=true)

I CANNOT eat glass. It's just the sentence in the GNOME Font Viewer.

我不能吞下玻璃而不伤身体。只是字体查看器用了这句话。

Download 下载
------------
[Stamico.ttf](https://github.com/gumblex/stamico/blob/master/Stamico.ttf?raw=true)

The auto adjusting scripts 自动调整脚本
-------------------------------------
To reduce the manual work, and as a workaround for the Chinese part of the font which was generated by tracing low-quality smart phone pictures, automatic scripts are used for adjusting the font to make them look similar.

WARNING: The scripts may also contains some workaround for speeding up the calculation through the PyPy Interpreter without FontForge or avoiding some annoying bugs of FontForge. The names and descriptions of the scripts, modules, functions and variables may be nonsense, so use them AFTER you HAVE understood the code.

为减少手工工作量，也为了提高由手机照片自动描线生成的中文字部分的质量，我写了一些自动化脚本用来调整字体。

警告：这些脚本可能为了使用不含FontForge的PyPy解释器加快计算速度而优化，也可能做了一些迂回措施来避免FontForge中某些糟糕的问题。我可能给脚本、模块、函数、变量等瞎取名字，所以请在使用前务必认真阅读代码。

* `autowidth.py` calculates the stroke width.
* `awerr.py` runs `awff.py` and analyzes the error log.
* `awff.py` actually runs FF to change glyphs in a small number to avoid FF's bugs.
* `bdflib.py` works with BDF font files.
* `centerglyph.py` is embeded in FF and adds some tools to it.
* `DYRegscript.sfd` is the `Stamico.ttf`'s source.
* `dyz-all.pdf` is the font demo.
* `englishkernpairs.txt` contains the kerning pairs from FontForge.
* `genbdf.pe` generates the BDF of the Chinese part.
* `gwid_dict.json` is the dict of stroke width of every glyph.
* `k3m.py` is the K3M skeletonization algorithm.
* `LICENSE` is the GPL license of the scripts.
* `LICENSE-FONT` is the OFL license of the font.
* `MergedFont.sfd` is the original Chinese part of the font.
* `MergedResized.sfd` is the auto-adjusted `MergedFont.sfd`.
* `merge.pe` merges the two parts of the font.
* `README.md` explains the project.
* `stamico.png` shows the font.
* `Stamico.sfd` is the part containing no Chinese characters.
* `Stamico.ttf` is the complete font.
