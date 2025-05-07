# Curso Kubernetes - Labs e Projeto Final

Este repositório contém o material criado durante o curso **Kubernetes Completo: Orquestração Docker + Projeto DevOps**, disponível na Udemy e ministrado pelo instrutor **Arnaldo Souza**.

## Conteúdo Abordado

Ao longo do curso, foram desenvolvidos diversos **labs práticos** usando o minikube, cobrindo os principais conceitos e recursos do Kubernetes:

- Criação e gerenciamento de **Pods**
- Exposição de aplicações via **Services**
- Uso de **ReplicaSets** para alta disponibilidade
- Deploy de aplicações com **Deployments**
- K8s Networking
- Probes
- Gerenciamento de volumes
- Jobs e cronjobs
- ConfigMaps e secrets
- DaemonSet
- Endpoint e endpointslices
- Armazenamento e gerenciamento de estado com **StatefulSets**
- Gerenciamento de permissões com:
  - **Roles**
  - **RoleBindings**
  - **ClusterRoles**
  - **ClusterRoleBindings**

## Projeto Final

No encerramento do curso, foi desenvolvido um **projeto final** que consistiu em:

- Conteinerização de uma aplicação **Jupyter Notebook**
- Criação de um **Deployment** para gerenciar a aplicação
- Exposição da aplicação com um **Service**
- Organização do projeto dentro de um **Namespace dedicado**

## Estrutura

O repositório está organizado por diretórios conforme os tópicos abordados. Cada pasta contém os arquivos YAML utilizados nos labs e no projeto final. O conteúdo da pasta 'labs' se refere a labs realizados no decorrer do curso e os arquivos jupyter-dp.yaml, jupyter-svc.yaml e jupyter-ns.yaml são referentes ao projeto final.

---

Este repositório serve como apoio prático para revisão e aprendizado contínuo dos conceitos essenciais de Kubernetes aplicados em ambientes DevOps.

O curso está disponível na udemy: https://www.udemy.com/course/kubernetes-power-profissional-formacao-inicial-completa/?couponCode=ST6MT60525G3
