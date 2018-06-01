# PFPL
*Practical Foundations for Programming Languages* (2nd Edition). R.Harper.  Cambridge University Press, 2016. Chinese Translation.

章节翻译分配 :  [google docs](https://docs.google.com/spreadsheets/d/1025pcs6RuDSXPrbbuoRkvBvwtOjqgKYXbw5eQ7m1RDk/edit?usp=sharing)

## 重要日期 （暂行）

- 2018.6.29 22:00 前，提交第1版；同时，由学生提交结对修订的结对名单（如果总数为奇数，则形成3人为一组的两两结对修订）
- 2018.7.6 22:00 前，提交修订版本（包括修订者的反馈以及原译者的最后修订），我们将以此版本来进行评估

## 使用方法

### 编译

- 执行：

  `make`

  可以编译获得 main.pdf，然后阅读其中的**翻译注意事项**.

- 以持续预览模式编译

  `make pvc`

### 编辑你的翻译稿

请在 [tex](./tex) 下找到你要翻译的章节所在的子目录，在该子目录增加你的翻译文稿；你需要修改该子目录下的 `part.tex` ，补充Part名称并用 `\subimport` 导入你的翻译文稿文件。

**注意**：

- 每一小节写入独立的tex文件中，便于多人 review
- 对经常使用的格式，可以定义一些命令(可参照 [setting.tex](setting.tex))，并在 [Piazza](https://piazza.com/ustc.edu.cn/spring2018/01116701/home) 上广而告之

## 提交方法

提交 pull request.
