唯一要说明的就是，在原版文件中我添加的代码都带有 super_的前缀，你可以通过这个快速找到我的修改

如果我很久不更新这个mod，想要更新这个mod代码的人理论上只需要更新那些原版文件即可(除非p社大改了游戏机制机制)。

11.3/23修改
对该mod修改原版代码的方法进行了重构，放弃了复制整个原版文件的方式，只是单独把需要修改的片段拿出来一起每种放到同一个文件中，修改方式不变
另外，对gui部分的修改仍然引用整个原版文件

修改过的文件都会写在下面
common\character_interactions\super_vanilla_reset_character_interactions.txt
common\scripted_effects\super_vanilla_reset_scripted_effects.txt
common\laws\00_realm_laws.txt    #此文件几乎完全修改，没有再度添加其他文件的必要，故直接保留

以下是修改过的gui文件，这部分文件基本没有以super_来做前缀  按照需求更新
gui\window_character_lifestyle.gui    添加了一个滑条，增加了组件长度
gui\window_faith.gui                  把核心教义的部分改为可滑动，以便容纳更多的教义
gui\window_faith_creation.gui         把核心教义的部分改为可滑动，以便容纳更多的教义