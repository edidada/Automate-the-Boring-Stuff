# Python 示例说明

本仓库的 `src/` 保存了《Python 编程快速上手——让繁琐工作自动化》中的独立示例。它们大多是教学脚本而不是可组合的应用模块；许多会读取标准输入、访问剪贴板/网络、修改当前目录文件或调用桌面程序。

运行前请先阅读源码，尤其不要直接运行会发送邮件、短信、下载文件或批量改名的脚本。下面按主题说明每个 `.py` 文件所演示的内容。

## 基础语法、流程控制与函数

| 文件 | 演示内容 |
| --- | --- |
| `hello.py` | 读取姓名和年龄，演示 `input()`、类型转换与字符串拼接。 |
| `fiveTimes.py` | 用 `for` 循环重复输出文本。 |
| `allMyCats1.py` | 逐个变量保存猫名，说明重复变量写法的局限。 |
| `allMyCats2.py` | 用列表和循环保存、输出猫名。 |
| `buggyAddingProgram.py` | 字符串相加导致“数字”拼接的常见错误。 |
| `littleKid.py` | `if` / `elif` / `else` 的条件分支。 |
| `swordfish.py` | `while`、`continue`、`break` 与口令校验。 |
| `validateInput.py` | `isdecimal()`、`isalnum()` 的输入验证循环。 |
| `exitExample.py` | 使用 `sys.exit()` 退出交互循环。 |
| `guessTheNumber.py` | 随机数、比较和限定次数的猜数字游戏。 |
| `coinFlip.py` | 重复随机试验并统计正面次数。 |
| `printRandom.py` | 生成并输出随机整数。 |
| `magic8Ball.py` | 函数根据随机数返回不同答案。 |
| `magic8Ball2.py` | 使用列表索引简化“魔法八球”答案选择。 |
| `helloFunc.py` | 定义并多次调用无参数函数。 |
| `helloFunc2.py` | 函数参数与个性化问候。 |
| `boxPrint.py` | 带参数的函数、输入检查和文本方框输出。 |
| `zeroDivide.py` | 除零异常，以及用 `try` / `except` 处理异常。 |
| `errorExample.py` | 函数调用栈发生异常时的 traceback。 |
| `sameName.py` | 全局变量和局部变量同名时的作用域。 |
| `sameName2.py` | 函数内读取全局变量。 |
| `sameName3.py` | 嵌套函数及其作用域查找顺序。 |
| `sameName4.py` | 局部赋值使同名全局变量不可直接读取的错误。 |
| `vampire.py` | 条件判断顺序会影响可达分支。 |
| `vampire2.py` | 重排条件以正确处理年龄范围。 |
| `passingReference.py` | 列表作为可变对象传参时会被原地修改。 |
| `catnapping.py` | 三引号多行字符串。 |
| `calcProd.py` | 计算大量整数乘积并用 `time` 计时。 |
| `factorialLog.py` | 用 `logging` 记录阶乘函数的调试过程。 |
| `threadDemo.py` | 创建线程，在主线程继续执行时运行后台任务。 |

## 容器、字符串与正则表达式

| 文件 | 演示内容 |
| --- | --- |
| `birthdays.py` | 用字典查询和新增生日资料。 |
| `myPets.py` | 用 `in` / `not in` 判断列表成员。 |
| `inventory.py` | 遍历字典并格式化输出游戏物品库存。 |
| `characterCount.py` | 用字典统计字符串中每个字符的出现次数。 |
| `prettyCharacterCount.py` | 使用 `pprint` 更易读地输出字符统计字典。 |
| `picnicTable.py` | 按列宽格式化字典内容，生成野餐清单表格。 |
| `isPhoneNumber.py` | 用逐字符检查实现简易电话号码验证。 |
| `phoneAndEmail.py` | 用正则表达式从剪贴板提取电话号码和邮箱，并复制结果。 |

## 文件、压缩包与文档

| 文件 | 演示内容 |
| --- | --- |
| `backupToZip.py` | 把指定文件夹及其内容备份到递增编号的 ZIP 文件。 |
| `renameDates.py` | 用正则表达式把文件名中的美国日期格式改为欧洲格式。 |
| `removeCsvHeader.py` | 批量删除当前目录 CSV 文件的首行。 |
| `bulletPointAdder.py` | 给剪贴板中每一行添加项目符号。 |
| `getDocxText.py` | 将 Word 文档段落提取为文本的辅助函数。 |
| `readDocx.py` | 读取 `.docx` 中段落文本的另一种实现。 |
| `combinePdfs.py` | 合并当前目录中的 PDF 文件。 |
| `countdown.py` | 倒计时结束后用系统命令播放音频。 |

## 表格、图片与其他办公自动化

| 文件 | 演示内容 |
| --- | --- |
| `readCensusExcel.py` | 用 `openpyxl` 汇总人口普查表格中各县的人口和普查区数据。 |
| `census2010.py` | 保存上述人口普查结果的嵌套字典数据。 |
| `updateProduce.py` | 批量更新 Excel 销售表中指定农产品的价格。 |
| `sendDuesReminders.py` | 根据 Excel 会费状态通过 SMTP 发送催缴邮件。 |
| `resizeAndAddLogo.py` | 批量缩放图片，并在右下角添加徽标。 |
| `formFiller.py` | 用 PyAutoGUI 自动填写桌面表单；坐标需按本机调整。 |
| `mouseNow.py` | 持续显示鼠标指针坐标和像素颜色。 |
| `mouseNow2.py` | 显示鼠标坐标的简化版本。 |
| `stopwatch.py` | 通过 Enter 键记录分段时间的秒表。 |

## 网络、浏览器与外部服务

| 文件 | 演示内容 |
| --- | --- |
| `mapIt.py` | 从命令行或剪贴板读取地址，并在浏览器打开地图。 |
| `lucky.py` | 搜索 Google 并在浏览器打开多个结果。 |
| `quickWeather.py` | 调用 OpenWeatherMap API，输出指定地点的天气预报。 |
| `downloadXkcd.py` | 顺序下载 XKCD 漫画。 |
| `multidownloadXkcd.py` | 用多个线程并行下载 XKCD 漫画。 |
| `textMyself.py` | 封装 Twilio 短信发送函数；需要有效账号凭据。 |
| `torrentStarter.py` | 轮询邮件中的磁力链接并启动下载程序；需要邮件和本机程序配置。 |

## 生成内容与交互项目

| 文件 | 演示内容 |
| --- | --- |
| `randomQuizGenerator.py` | 随机生成州府选择题及答案文件。 |
| `ticTacToe.py` | 用字典表示棋盘并实现双人井字棋回合。 |
| `pw.py` | 把预设账户密码复制到剪贴板的简易密码保管示例；仅用于教学，不安全。 |

## 运行提示

纯标准库示例可在 `src/` 下直接运行，例如：

```shell
poetry run python fiveTimes.py
```

其余脚本可能依赖 `requests`、`beautifulsoup4`、`pyperclip`、`openpyxl`、`PyPDF2`、`Pillow`、`pyautogui`、`twilio` 等第三方库；这些历史教学示例的运行依赖和账号配置并未全部纳入当前 Poetry 依赖清单。
