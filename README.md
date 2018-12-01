# サンプルPlaybook
## リポジトリの説明
[Software Design 2018年12月号](https://gihyo.jp/magazine/SD/archive/2018/201812) 特集1「[超速]入門 Ansible」内の第3章「Ansibleでネットワーク作業も自動化」のサンプルPlaybook一式です。
### [master ブランチ](https://github.com/akira6592/sd2018-ansible-nw/tree/master)
誌面に対応する Playbook 一式
### [extra ブランチ](https://github.com/akira6592/sd2018-ansible-nw/tree/extra)
応用編を加えた Playbook 一式

## ファイルの説明
### 01_show_version.yml
- Cisco IOS ネットワーク機器に対して `show version` コマンドを実行し、内容を画面に出力する Playbook。

### 02_set_snmp.yml
- Cisco IOS ネットワーク機器に対して SNMPコミュニティ名を設定する Playbook。

### 03_set_logging.yml ([extra ブランチ](https://github.com/akira6592/sd2018-ansible-nw/tree/extra)のみ)
- Cisco IOS ネットワーク機器に対して Syslog サーバーを設定する Playbook。
- 誌面非掲載につき、詳細は「[グループと変数を活用したネットワーク機器への Syslog サーバー追加[(https://tekunabe.hatenablog.jp/entry/2018/12/01/ansible_sd_extra)」へ。

## リンク集
記事中に登場するリンクを以下に掲載します。

- 注1）[ネットワークモジュール一覧](https://docs.ansible.com/ansible/latest/modules/list_of_network_modules.html)
- 注2）[Ansible for Network Automation](https://docs.ansible.com/ansible/latest/network/index.html)
- 注4）[サンプルのPlaybookなどの一式](https://github.com/akira6592/sd2018-ansible-nw/)
- 注5）[ios_command モジュール詳細](https://docs.ansible.com/ansible/latest/modules/ios_command_module.html)
- 注6）[debug モジュール詳細](https://docs.ansible.com/ansible/latest/modules/debug_module.html)
- 注7）[*_command モジュールの戻り値の構造について](https://www.ansible.com/blog/command-module-deep-dive-for-networks)
- 注9）[ios_config モジュール詳細](https://docs.ansible.com/ansible/latest/modules/ios_config_module.html)
- 注A）[Cisco Japan Blog のCisco DevNet の紹介記事](https://gblogs.cisco.com/jp/2018/10/cisco-devnet-introduction/)
- 注B）[Cisco DevNet Sandbox](https://developer.cisco.com/site/sandbox/)

