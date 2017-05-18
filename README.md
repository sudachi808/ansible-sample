# ansible-sample
Ansible練習用

## Playbook実行方法

### step_1 と step_2

ホスト名の後ろに半角カンマが必要なので注意

```bash
$ ansible-playbook -i ホスト名またはIPアドレス, site.yml
```

### step_3

```bash
$ ansible-playbook -i inv_production.ini site.yml
```
