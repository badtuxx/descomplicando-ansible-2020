# Treinamento Descomplicando o Ansible

Projeto do treinamento para instalação de um cluster Kubernetes utilizando o Ansible + kubeadm + AWS EC2 + e outras coisitas mais.

Projeto com contribuição dos alunos e o chat da Twitch.

## Fases do projeto

- Provisioning => Criar as instâncias/vms para o nosso cluster.
- Install_K8s => Criação do cluster, adiciona os workers, instalação do Helm e instala ferramentas de monitoração (Prometheus e Grafana).
- Deploy_app_v1 => Deploy de uma aplicação exemplo na versão 1
- Deploy_app_v2 => Deploy de uma aplicação exemplo na versão 2
- Extra => Segredo

## Ansible Lint

- Vamos conhecer e utilizar o ansible-lint para deixar o código que criamos um bocado melhor. (https://ansible-lint.readthedocs.io/en/latest/usage.html)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
