Stash split override pack

说明：
1. cr_style 文件使用 CR-only 换行。GitHub Raw 有时会看起来像一整行，但不是把 YAML 硬压缩成伪一行。
2. lf_standard 是普通 LF 换行备份。
3. 建议先上传 cr_style 里的文件到 GitHub 仓库 override/ 目录。
4. 先只导入 01_local_direct_rules.stoverride 测试。若成功，再导入后续文件。
5. 01_local_direct_rules.stoverride 和 05_rules_replace_all.stoverride 不要长期同时启用；05 已包含 01 的规则。
6. 07_ports_controller_optional.stoverride 是可选风险项；若导入失败或 Stash 不需要，不要启用。

建议导入顺序：
1. 01_local_direct_rules.stoverride（测试远程覆写导入）
2. 02_dns_replace.stoverride
3. 03_rule_providers.stoverride
4. 04_proxy_groups_replace.stoverride
5. 05_rules_replace_all.stoverride
6. 06_general_settings_optional.stoverride
7. 07_ports_controller_optional.stoverride（可选）

安装地址：

01_local_direct_rules.stoverride
Raw: https://raw.githubusercontent.com/limidfield/stash/main/override/01_local_direct_rules.stoverride
Install: https://link.stash.ws/install-override/raw.githubusercontent.com/limidfield/stash/main/override/01_local_direct_rules.stoverride

02_dns_replace.stoverride
Raw: https://raw.githubusercontent.com/limidfield/stash/main/override/02_dns_replace.stoverride
Install: https://link.stash.ws/install-override/raw.githubusercontent.com/limidfield/stash/main/override/02_dns_replace.stoverride

03_rule_providers.stoverride
Raw: https://raw.githubusercontent.com/limidfield/stash/main/override/03_rule_providers.stoverride
Install: https://link.stash.ws/install-override/raw.githubusercontent.com/limidfield/stash/main/override/03_rule_providers.stoverride

04_proxy_groups_replace.stoverride
Raw: https://raw.githubusercontent.com/limidfield/stash/main/override/04_proxy_groups_replace.stoverride
Install: https://link.stash.ws/install-override/raw.githubusercontent.com/limidfield/stash/main/override/04_proxy_groups_replace.stoverride

05_rules_replace_all.stoverride
Raw: https://raw.githubusercontent.com/limidfield/stash/main/override/05_rules_replace_all.stoverride
Install: https://link.stash.ws/install-override/raw.githubusercontent.com/limidfield/stash/main/override/05_rules_replace_all.stoverride

06_general_settings_optional.stoverride
Raw: https://raw.githubusercontent.com/limidfield/stash/main/override/06_general_settings_optional.stoverride
Install: https://link.stash.ws/install-override/raw.githubusercontent.com/limidfield/stash/main/override/06_general_settings_optional.stoverride

07_ports_controller_optional.stoverride
Raw: https://raw.githubusercontent.com/limidfield/stash/main/override/07_ports_controller_optional.stoverride
Install: https://link.stash.ws/install-override/raw.githubusercontent.com/limidfield/stash/main/override/07_ports_controller_optional.stoverride
