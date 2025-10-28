# Gerenciamento de Instâncias EC2 na AWS

## Desafio DIO – AWS EC2

Este repositório documenta a experiência prática adquirida durante o laboratório de gerenciamento de instâncias EC2 na AWS. O objetivo é consolidar conhecimentos técnicos, registrar insights e servir como material de referência para estudos e futuras implementações.

---

## Objetivos do Desafio

- Aplicar conceitos aprendidos sobre **instâncias EC2** em um ambiente prático.  
- Documentar **processos técnicos** de forma clara e estruturada.  
- Utilizar o **GitHub** como ferramenta para **compartilhamento de documentação técnica**.  

---

## Conteúdo do Repositório

- `README.md` – Este arquivo contendo todas as informações sobre o desafio.  
- `/images` – Capturas de tela da prática no console da AWS.  
- `/scripts` – Scripts utilizados para automatizar tarefas ou testes na instância.  
- `/notes` – Anotações, insights e observações durante a prática.  

---

## Passo a Passo da Experiência

### 1. Criação da Instância EC2

- Seleção do **tipo de instância** adequado ao teste.  
- Escolha do **sistema operacional** (Linux/Windows).  
- Configuração do **tamanho do armazenamento EBS**.  
- Configuração de **chaves SSH** para acesso remoto seguro.  

### 2. Configuração de Segurança

- Criação de **Security Groups** com regras de entrada e saída definidas.  
- Ativação de **Multi-Factor Authentication (MFA)** para a conta root e usuários IAM.  
- Definição de **políticas de permissão IAM** para controle de acesso.  

### 3. Operações com a Instância

- Conexão via **SSH (Linux)** ou **RDP (Windows)**.  
- Instalação de softwares e configuração de aplicações de teste.  
- Criação de **snapshots EBS** para backup.  
- Testes de desligamento, reinicialização e expansão de volume EBS.  

### 4. Monitoramento e Manutenção

- Acompanhamento do **status da instância** pelo console AWS.  
- Uso de métricas básicas de **CPU, memória e armazenamento**.  
- Avaliação de **custos e otimização** usando diferentes classes de instância.  

---

## Aprendizados e Insights

- A importância de **selecionar a região correta** para criar instâncias.  
- Diferença entre **instâncias on-demand, reserved e spot**.  
- Como os **snapshots EBS** permitem backup seguro e restauração de volumes.  
- Gestão de **usuários e permissões** usando IAM para maior segurança.  
- Controle de **custos** através de desligamento de instâncias e escolha de tipos adequados.  

---

## Referências

- [Documentação Oficial AWS – Gerenciamento de EC2](https://docs.aws.amazon.com/ec2/)  
- [Guia GitHub Markdown](https://guides.github.com/features/mastering-markdown/)  
- [GitHub Quick Start](https://docs.github.com/en/get-started/quickstart)  

---

## Conclusão

Este laboratório permitiu consolidar conceitos teóricos sobre **instâncias EC2**, aplicando-os na prática. A documentação organizada neste repositório serve como material de referência para futuras implementações e estudos avançados em AWS.
