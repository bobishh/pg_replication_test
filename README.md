# Postgres replication test environment

## Parts:

+ Vagrant boxes with ubuntu trusty (14.04)
+ PGPoolII
+ Asynchronous streaming replication
+ Ansible scripts for rolling shit out

## To start this shit up

1) ``` ansible-galaxy install -r requirements.yml ```

2) ```vagrant up```

3) ```ansible-playbook keys.yml --ask-pass``` and the pass is vagrant

4) ```ansible-playbook site.yml```

5) PROFIT!
