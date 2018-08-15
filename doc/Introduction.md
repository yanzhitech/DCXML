
This document describes DCXML, the Dialogue Control eXtensible Markup Language. 

[^_^]:
DCXML provides declarative markup to describe dialogue control.

[^_^]: DCXML is a language that is used with a dialog system. 

如何将自然语言的描述，转换为机器可执行的运算？如何使得“机器人”具有类人的行为？ 唯有将人类语言及行为建模，使得机器具有可参考的内容。
而建模则先得有一套描述体系，能将人类语言及行为统一的表示出来。在统一的表示基础上，赋予“表示”间的计算能力，从而使得机器有了类人的决策的可能性。

在机器交互系统中，将人类语言结构化的表示出来的技术称为自然语言理解(natural language understanding, NLU)。基于NLU结果及context输出系统的action的技术成为对话管理(dialogue management, DM)。 以下先就这两部分分别定义一套描述语言，并实现其对应的解码器。
