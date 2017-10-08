
## Requirements


```
sudo dnf install ansible
```

```
ansible-galaxy install gantsign.intellij
ansible-galaxy install geerlingguy.java
ansible-galaxy install gantsign.oh-my-zsh
```

## Run

```
ansible-playbook -i "localhost," -c local ./playbook.yml
```
