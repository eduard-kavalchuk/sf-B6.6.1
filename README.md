Before you run a playbook create a VM and specify its external IP address in ``hosts`` file.  

To install and configure vsftpd:
```
ansible-playbook --tags "install,configure" -i hosts vsftpd.yaml -v
```
To uninstall vsftpd:
```
ansible-playbook --tags "uninstall" -i hosts vsftpd.yaml -v
```
