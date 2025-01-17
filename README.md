<!--
# Desafio DevOps & Cloud

## Links das Aulas

Curso Veronez 
https://imersao.devopspro.com.br/aulas/

Aula 1 - Docker
https://www.youtube.com/watch?v=uUzO2Sh1dR0

Aula 2 - Kubernetes
https://www.youtube.com/watch?v=CCwiVpfOnto

Aula 3 - AWS
https://www.youtube.com/watch?v=XZk-359q9xQ

Aula 4 - CI/CD (Github Actions)
https://www.youtube.com/watch?v=dPeeqzWcs58

Aula 5 - Observabilidade (Prometheus + Grafana)
https://www.youtube.com/watch?v=orXJjhvo49A


Outros: 

System Design
https://www.youtube.com/watch?v=F2FmTdLtb_4

Kubernetes
https://blog.bytebytego.com/p/kubernetes-made-easy-a-beginners?utm_source=substack&utm_medium=email


## Aula 01 - Desafio Docker

Link para o repositório do projeto conversão de distância:

[https://github.com/KubeDev/conversao-distancia](https://github.com/KubeDev/conversao-distancia)


## Aula 03 - AWS e EKS

Endereço do template de rede para o CloudFormation:

https://s3.us-west-2.amazonaws.com/amazon-eks/cloudformation/2020-10-29/amazon-eks-vpc-private-subnets.yaml

Link para o repositório do projeto fake shop:

https://github.com/KubeDev/fake-shop

## Aula 05 - Prometheus e Grafana

Arquivo de manifesto para o Prometheus e o Grafana:

https://gist.githubusercontent.com/fabricioveronez/3ffbc3ddf826a75c508d5bca9b5a6adb/raw/8677f2ac7a3d9df2d43f63213b936e2a6248592c/deploy-prometheus.yaml

Arquivo com o Flask Dashboard:

https://gist.githubusercontent.com/fabricioveronez/3ffbc3ddf826a75c508d5bca9b5a6adb/raw/8677f2ac7a3d9df2d43f63213b936e2a6248592c/flask-dashboard.json

Comando para obter a senha do Grafana:

```
kubectl get secret --namespace default grafana -o jsonpath="{.data.admin-password}" | base64 --decode ; echo
```
-->

