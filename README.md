# ansible-heron

## Ussage:
1. Create a hosts file based on hosts/test.template
2. Generate `roles/common/files/id_rsa` and `roles/common/files/id_rsa.pub` using ssh-keygen.
3. Run ansible playbook `ansible-playbook -i hosts/test heron_install.yml`

Note:
This is an experimental playbook.

