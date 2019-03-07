# Mac環境構築用

## 事前準備
1. Xcodeをインストール
2. `$ sudo easy_install pip`
3. `$ sudo pip install ansible`
4. `$ sudo pip install ansible --upgrade`
5. ansible.cfg を設置
```
$ sudo mkdir /etc/ansible
$ sudo curl -L https://raw.githubusercontent.com/ansible/ansible/devel/examples/ansible.cfg -o /etc/ansible/ansible.cfg
```

## ansible実行
`$ ansible-playbook main.yml -i inventory`

## 参考URL
* https://qiita.com/susieyy/items/ac2133e249f252dc9a34
* https://dev.classmethod.jp/etc/mrmo-first-mac-setup-ansible/
