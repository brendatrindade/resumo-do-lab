# Resumo do Lab - Computação em Nuvem
Durante o desenvolvimento do lab, aprendi os principais conceitos sobre **computação em nuvem**, seus modelos e formas de utilização.  

## Definição
A computação em nuvem é o fornecimento de serviços de TI (servidores, armazenamento, banco de dados, redes, software, etc.) pela internet, possibilitando maior flexibilidade, escalabilidade e redução de custos.  

## Modelos de Nuvem
- **Nuvem Pública**: recursos fornecidos por terceiros (ex.: Azure, AWS, Google Cloud), acessíveis pela internet.  
- **Nuvem Privada**: recursos dedicados para uma única organização, oferecendo maior controle e segurança.  
- **Nuvem Híbrida**: combinação entre nuvem pública e privada, permitindo mais flexibilidade e integração.  

## Modelo Baseado em Consumo
O pagamento é feito conforme o uso dos recursos, semelhante a uma conta de energia ou água. Esse modelo garante eficiência de custos, já que a empresa paga apenas pelo que realmente utilizar.  

## Comparação de Modelos de Preços
- **CapEx (Capital Expenditure)**: investimento inicial em infraestrutura, com custos fixos e altos investimentos antes do uso.  
- **OpEx (Operational Expenditure)**: pagamento contínuo pelo uso, reduzindo custos iniciais e oferecendo maior previsibilidade e escalabilidade.  

## Conclusão
O aprendizado mostrou como a computação em nuvem transforma a maneira como empresas e desenvolvedores consomem recursos de TI, permitindo otimização de custos, elasticidade e maior foco no negócio. Além disso, compreender as diferenças entre modelos de nuvem e de preços é fundamental para tomar decisões estratégicas no uso de tecnologia em projetos reais.  

# Resumo do Lab - Máquinas Virtuais na Azure

Este repositório contém o resumo da minha experiência e aprendizados durante o laboratório sobre **Máquinas Virtuais na Azure**, proposto pela DIO.  

## Objetivo do Lab
Consolidar conhecimentos em **computação em nuvem** aplicados na criação e gerenciamento de **máquinas virtuais (VMs)** no Microsoft Azure, utilizando práticas reais em ambiente de nuvem.

## O que aprendi
- Como criar uma **máquina virtual no Azure** a partir do portal de gerenciamento.  
- Diferenças entre sistemas operacionais disponíveis (Windows e Linux).  
- Configuração de **tamanho, região e recursos da VM**, considerando custo e desempenho.  
- Importância da definição de **usuário e senha/SSH key** para autenticação segura.  
- Entendimento sobre **custos baseados em consumo**, de acordo com o uso da VM.  

## Passo a passo
1. Acessar o **Portal do Azure**
2. Selecionar a opção **Criar recurso > Máquina Virtual** 
3. Definir as configurações principais:  
   - Nome da VM  
   - Sistema operacional  
   - Região (datacenter)  
   - Tamanho da VM (CPU/RAM)  
   - Método de autenticação (senha ou chave SSH)  
4. Configurar **rede e segurança** 
5. Revisar e criar a máquina virtual 
6. Testar o acesso via **RDP (Windows)** ou **SSH (Linux)** 

## Conclusão
Com este laboratório, consegui aplicar os conceitos de **infraestrutura em nuvem** em um cenário prático. A experiência reforçou a importância de entender os diferentes parâmetros de configuração de uma VM, os impactos em custo e desempenho, além de boas práticas de segurança.  

# Resumo do Lab - Banco de Dados no Azure

Este repositório contém minhas anotações, resumos e dicas sobre a configuração de uma **instância de Banco de Dados no Microsoft Azure**, desenvolvidas durante o desafio da DIO.  

## Objetivo do Lab
Praticar o processo de **criação e configuração de um banco de dados gerenciado no Azure**, entendendo suas opções de uso, segurança e custos.

## O que aprendi
- Diferença entre **Banco de Dados local** e **Banco de Dados na nuvem**.  
- Como criar uma **Instância Gerenciada de SQL Server no Azure**.  
- Escolher parâmetros como:  
  - Nome do servidor e banco de dados  
  - Região do datacenter  
  - Tipo de autenticação (SQL ou Azure AD)  
  - Definição de usuário e senha de administrador  
- Configurar **firewall e rede** para permitir conexões externas.  
- Testar conexão com o banco usando ferramentas como **Azure Data Studio** ou **SQL Server Management Studio (SSMS)**.  
- Entender os **custos baseados em consumo** para bancos de dados na nuvem.  

## Passo a passo
1. Acessar o **Portal do Azure**.  
2. Selecionar **Criar recurso > Banco de Dados SQL**.  
3. Definir as configurações principais (nome, servidor, autenticação, região).  
4. Ajustar parâmetros de desempenho (DTUs ou vCores, conforme necessidade).  
5. Configurar rede e regras de firewall para permitir conexões.  
6. Criar e validar a instância.  
7. Testar o acesso ao banco com credenciais configuradas.  

## Conclusão
Este laboratório me permitiu praticar a configuração de um **Banco de Dados SQL no Azure**, entendendo os principais parâmetros técnicos e boas práticas de segurança.  


---

Criado como parte do desafio da [DIO](https://www.dio.me).  


