# Resumo das tarefas que deverão ser executadas para o aprendizado.

Salvem todos os arquivos, retornos e comandos que julgarem importântes em uma pasta em suas respectivas branches desse repositório.
Isso depois poderá servir de guia para vocês no futuro.

## Tarefa 1

### Implementação do kubernete deplyment yaml file

- Neste primeiro exercício você deverá criar um deployment com a imagem de hello world.
- Varie a quantidade de pods existentes, a quantidade de ram e cpu.
- Adicione um volume para a sua aplicação.
- Crie e adicione namespaces para seus projetos.
- Faça uma alteração na imagem e faça uma atualização de deployment via rolling update.
- Faça um canary deployment da sua aplicação.
- Passe variáveis de ambiente para a sua aplicação.
- Crie um secret passando essas variáveis de ambiente.
- Passe um comando custumizado pelo yaml, não utilizando o comando da imagem original.
- Configure um registro privado para o poll de suas imagens.
- Configure QoS dos pods e dos namespaces.
- Execute deploys em nós específicos do kubernetes.


### Implementação do kubernete service yaml file

- Crie um yaml file referente ao serviço que será disponibilizado pelo seu deployment.
- Altere a porta de saída do seu serviço.
- Crie labels para mapear seus serviços.
- Crie um distribuidor de carga para sua aplicação
- Crie um DNS com ingress para sua aplicação.


## Tarefa 2

### Checagem de status dos recursos

- Acesse todos os seus recursos via CLI do kubernetes (deployment, service, nodes, etc.).
- Gere logs dos seus serviços.
- Gere Debugg de deployments e status de seus recursos.
- Acesse seu cluster via API do kubernetes (grafica)


## Tarefa 3

### Auto scaler

- Configure um serviço de auto scaling das aplicações (horizontal e vertical)
- Pode ser utilizado o proprio do kubernetes presentes em: https://github.com/kubernetes/autoscaler/tree/master/cluster-autoscaler
