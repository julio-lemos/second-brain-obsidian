### Slide 1: Introdução ao DevOps

- [ ] Dar Boa tarde
- [ ] Perguntar como eles estão
- [ ] Aplicação de DevOps em aplicações Web
- [ ] Visão geral sobre práticas de DevOps
- [ ] E como ele acelera os processos de desenvolvimento e entrega

---
### Slide 2: Apresentação

- [ ] Me chamo Julio
- [ ] Atuo na área de desenvolvimento em média a uns 3 anos
- [ ] Palestrei no TDC em 2023 na trilha WEB
- [ ] Sou engenheiro de software na Justa Soluções Financeiras
- [ ] Fintech
- [ ]  Com sede em SP
- [ ]  Time de tecnologia é em sua grande parte de Recife
- [ ]  Estamos migrando para o modelo 100% Remoto


---
### Slide 3: Instruções

- [ ] A idéia da palestra de hoje é que vocês participem ao máximo em tempo real
- [ ] Para isso deve escanear QrCode ou acessar esse site e adicionar este código
- [ ] Poderão acompanhar os slides pelo celular
- [ ] E participar das dinamicas
- [ ] Esperar um tempo para que vocês consigam se conectar
- [ ] Inclusive, vocês poderão ver o slide pelo celular
- [ ] E Fazer Perguntas pelo Botão Open Q&A

---
### Slide 4: Agenda

- [ ] Ler a agenda da palestra

---
### Slide 5: O que é DevOps?

- [ ] Peça para eles definirem em uma palavra o que eles pensam ao ouvir a palavra DevOps

---

### Slide 6: Introdução ao DevOps

- [ ] DevOps é uma cultura que integra desenvolvimento e operações
- [ ] O significado de DevOps é justamente essa relação entre Dev e Operações
- [ ] Entrega de software mais rápida e eficiente
- [ ] Foco em colaboração das equipes
- [ ] Ciclo de desenvolvimento ágil e confiável
- [ ] Renovação drástica de processos com o advento do DevOps

---
### Slide 7: Práticas Essenciais

- [ ] A área de DevOps possui alguns pilares
- [ ] Integração Contínua
- [ ] Entrega Contínua
- [ ] Infraestrutura como Código
- [ ] Monitoramento
- [ ] Esses processos garantem automação e visibilidade no ciclo de desenvolvimento

---

### Slide 8: CI

- [ ] Detecta problemas rapidamente com automações
- [ ] Podemos automatizar tudo que acreditamos ser essencial para manutenabilidade do projeto
- [ ] Desde Testes, Builds ou execução de scripts
- [ ] Sua função é garantir e validar que todo código seja validado antes de ser disponibilizado em produção
- [ ] Reduz risco e melhora a qualidade
- [ ] Contar história de joãozinho e seu teste quebrado que quase foi pra produção

---
### Slide 9: CD

- [ ] É uma extensão do processo de CI
- [ ] E tem como foco a automatizar a preparação de pipelines para deploy em produção
- [ ] Existem algumas técnicas como Blue/Green e Canary Releases
- [ ] Minimizam o impacto de novas releases

#### Técnica Blue/Green

- [ ] Essa técnica mantém duas versões do ambiente de produção simultaneamente
- [ ] **Blue**: A versão antiga, que está atualmente em uso pelos usuários.
- [ ] **Green**: A nova versão do software, pronta para ser lançada.
- [ ] A versão Green é testada em paralelo com a Blue
- [ ] Assim que a Green estiver pronta só direcionamos o tráfego para ela (geralmente por balanceamento de carga)
- [ ] Qualquer problema que ocorrer na Green, é facilmente resolvida revertendo o tráfego para a versão Blue

Vantagens:

- [ ] Rollback Imediato
- [ ] Zero Downtime

Desvantagens:

- [ ] Custo

#### Técnica Canary Deployment

- [ ] Nova versão do software é lançada de forma gradual para um subconjunto de usuários, ao invés de todos de uma vez
- [ ] O nome "Canary" vem da prática antiga de levar canários para minas de carvão para detectar gases perigosos antes dos mineiros.
- [ ] Uma pequena parte dos usuários (por exemplo, 5%) começa a usar a nova versão do software.
- [ ] A equipe monitora a nova versão para garantir que tudo esteja funcionando como esperado.
- [ ] Se não houver problemas, o número de usuários que recebe a nova versão aumenta gradualmente até que todos estejam usando a nova versão.
- [ ] Caso algum problema seja detectado, a implantação pode ser interrompida ou revertida apenas para a parcela de usuários que está utilizando a nova versão.

Vantagens:

- [ ] Implantação controlada
- [ ] Feedback rápido

Desvantagens:

- [ ] **Mais complexidade**: Requer ferramentas mais sofisticadas para controle de tráfego e monitoramento granular.

Obs.: Algumas ferramentas auxiliares para essas técnicas:

- Istio
- Argo Rollouts
- Flagger
- NGINX
- Rollout.io
- AWS Elastic Load Balancing

---
### Slide 10: IaC

- [ ] É um dos pilares do DevOps que eu mais admiro
- [ ] Permite versionar e automatizar a criação de infraestrutura
- [ ] É o poder de versionar todo seu ecossistema na Nuvem
- [ ] Ferramentas como Terraform, Ansible e CloudFormation
- [ ] Garante escalabilidade e otimização de custos

---
### Monitoramento e Observabilidade

- [ ] Foi meu tema no TDC 2023
- [ ] Tem papel crucial dentro de uma companhia
- [ ] Monitora a performance de uma aplicação
- [ ] Identificação de problemas antes que afetem usuários
- [ ] Ferramentas de Logging e rastreamento
- [ ] Visibilidade total do Sistema

---
### Impactos Positivos do DevOps

- [ ] Ler lista

---
