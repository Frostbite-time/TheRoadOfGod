唯一要说明的就是，在原版文件中我添加的代码都带有 super_的前缀，你可以通过这个快速找到我的修改

如果我很久不更新这个mod，想要更新这个mod代码的人理论上只需要更新那些原版文件即可(除非p社大改了游戏机制机制)。

修改过的文件都会写在下面
common\character_interactions\00_alliance.txt
common\character_interactions\00_character_interactions.txt
common\character_interactions\00_marriage_interactions.txt
common\character_interactions\00_religious_interactions.txt
common\character_interactions\00_revoke_title_interaction.txt
common\character_interactions\00_vassal_interactions.txt
common\character_interactions\00_courtier_and_guest_interactions.txt
common\character_interactions\00_war.txt
common\character_interactions\00_scheme_interactions.txt
common\scripted_effects\00_mongol_invasion_effects.txt
common\laws\00_realm_laws.txt

以下是修改过的gui文件，这部分文件基本没有以super_来做前缀  按照需求更新
gui\window_character_lifestyle.gui    添加了一个滑条，增加了组件长度
gui\window_faith.gui                  把核心教义的部分改为可滑动，以便容纳更多的教义
gui\window_faith_creation.gui         把核心教义的部分改为可滑动，以便容纳更多的教义