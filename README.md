# WoWHoneypot_Ansible
WoWHoneypot_Ansible

## 環境
ubuntu20.04

## 設定ファイルの追加(host/hosts)
<pre>
vim an_Wow/host/hosts

[webserver]
Target01 ansible_ssh_host='global_IP'

[webserver:vars]
ansible_ssh_user='User_name'
ansible_ssh_private_key_file='key'

</pre>
