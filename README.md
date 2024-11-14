# 🏆 AWS Certified Cloud Practitioner - Guia de Preparação

Prepare-se para a certificação **AWS Certified Cloud Practitioner** (CLF-C02) com este guia prático. Ele contém as principais informações sobre o exame, seus domínios de conteúdo e requisitos para aprovação.

## 🎯 Informações do Exame

| 🔍 Detalhe                  | 📋 Descrição                         |
|-----------------------------|--------------------------------------|
| **Quantidade de questões**  | 65                                  |
| **Duração da prova**        | 90 minutos                          |
| **Preço**                   | 100 USD                             |
| **Nota mínima para aprovação** | 700/1000                          |

---

## 📚 Domínios do Exame e Distribuição de Pontos

O exame é dividido em quatro domínios principais, cada um com um percentual específico do conteúdo pontuado. Organize seus estudos com foco nesses domínios para otimizar sua preparação.

| 🌐 Domínio                       | 📊 Percentual no Exame |
|----------------------------------|------------------------|
| **Domínio 1:** Conceitos da Nuvem       | 24%                   |
| **Domínio 2:** Segurança e Conformidade | 30%                   |
| **Domínio 3:** Tecnologia e Serviços da Nuvem | 34%         |
| **Domínio 4:** Cobrança, Preços e Suporte | 12%               |

---

## ☁️ Domínio 1: Conceitos da Nuvem (24% do conteúdo pontuado)

Este domínio cobre os fundamentos e vantagens da nuvem AWS, além dos princípios de design e estratégias de migração.

### 📌 Benefícios da Nuvem AWS
- **Proposta de Valor**: Economia de custos, escalabilidade e alcance global.
- **Infraestrutura Global**: Alta disponibilidade, elasticidade e agilidade da AWS.

### 📌 Princípios de Projeto
- **AWS Well-Architected Framework**: Excelência operacional, segurança, confiabilidade, desempenho, otimização de custos e sustentabilidade.

### 📌 Migração para a Nuvem
- **Estratégias de Migração**: Redução de risco, aumento de eficiência, apoio à governança e uso de ferramentas como o **AWS Cloud Adoption Framework (AWS CAF)** e o **AWS Snowball**.

### 📌 Aspectos Econômicos da Nuvem
- **Economia de Custos**: Custos variáveis vs. fixos, otimização de licenciamento (BYOL), automação e serviços gerenciados (Amazon RDS, ECS, EKS, DynamoDB).

---

## 🔒 Domínio 2: Segurança e Conformidade (30% do conteúdo pontuado)

Este domínio abrange o modelo de responsabilidade compartilhada, segurança, governança e conformidade na nuvem AWS, além de práticas de gerenciamento de acesso e segurança.

### 📌 Modelo de Responsabilidade Compartilhada
- **Componentes do Modelo**: Responsabilidades do cliente, responsabilidades da AWS e responsabilidades compartilhadas.
- **Alterações nas Responsabilidades**: Dependem do serviço utilizado (ex.: Amazon RDS, AWS Lambda, Amazon EC2).

### 📌 Conceitos de Segurança, Governança e Conformidade
- **Governança e Conformidade**: AWS Artifact para conformidade, segurança de dados, criptografia e monitoramento de logs.
- **Proteção de Recursos**: Serviços como Amazon Inspector, AWS Security Hub, Amazon GuardDuty, AWS Shield.
- **Criptografia**: Em trânsito e em repouso, com opções de governança (ex.: CloudWatch, CloudTrail, AWS Config).

### 📌 Gerenciamento de Acesso
- **AWS IAM**: Princípio de menor privilégio, AWS IAM Identity Center, proteção da conta de usuário-raiz.
- **Autenticação e Segurança**: MFA, AWS Secrets Manager, IAM Policies, grupos e usuários configurados para menor privilégio.

### 📌 Componentes e Recursos de Segurança
- **Recursos de Segurança da AWS**: Grupos de segurança, ACLs de rede, AWS WAF.
- **Documentação e Suporte**: AWS Knowledge Center, AWS Security Center, blog de segurança.
- **Identificação de Problemas de Segurança**: AWS Trusted Advisor, AWS Security Hub, produtos de terceiros disponíveis no AWS Marketplace.

---

## 💻 Domínio 3: Tecnologia e Serviços da Nuvem (34% do conteúdo pontuado)

Este domínio aborda os métodos de implantação, infraestrutura global, serviços de computação, banco de dados, rede, armazenamento, IA/ML e outras categorias de serviços da AWS.

### 📌 Métodos de Implantação e Operação
- **Formas de Provisionamento e Acesso**: APIs, SDKs, CLI, console de gerenciamento e IaC (infraestrutura como código).
- **Modelos de Implantação**: Nuvem, híbrido e on-premises.
- **Opções de Conectividade**: AWS VPN, AWS Direct Connect, Internet pública.

### 📌 Infraestrutura Global da AWS
- **Componentes**: Regiões, Zonas de Disponibilidade, locais de borda.
- **Alta Disponibilidade**: Uso de múltiplas Zonas de Disponibilidade e Regiões (ex.: recuperação de desastres, baixa latência).
- **Locais de Borda**: CloudFront, AWS Global Accelerator para melhorar a entrega de conteúdo.

### 📌 Serviços Computacionais da AWS
- **Serviços e Instâncias**: EC2 para computação e armazenamento, Amazon ECS e Amazon EKS para contêineres, AWS Fargate e Lambda para computação sem servidor.
- **Elasticidade e Auto Scaling**: Proporciona escalabilidade automática.
- **Balanceamento de Carga**: Finalidades e uso.

### 📌 Serviços de Banco de Dados da AWS
- **Opções de Banco de Dados**: Amazon RDS, Amazon Aurora para bancos relacionais, DynamoDB para NoSQL, bases de dados em memória.
- **Migração de Banco de Dados**: AWS DMS e AWS SCT para migração e conversão de esquemas.

### 📌 Serviços de Rede da AWS
- **Componentes de VPC**: Sub-redes, gateways, ACLs de rede, grupos de segurança.
- **Roteamento e Conectividade**: Amazon Route 53, CloudFront, Global Accelerator, AWS VPN e Direct Connect.

### 📌 Serviços de Armazenamento da AWS
- **Tipos de Armazenamento**: Armazenamento de objetos no S3, armazenamento em bloco no EBS e EFS, storage classes do S3, políticas de ciclo de vida e AWS Backup.
- **Soluções de Arquivos e Cache**: Amazon EFS, Amazon FSx, AWS Storage Gateway.

### 📌 Serviços de Inteligência Artificial e Machine Learning (IA/ML) e Analytics
- **Serviços de IA/ML**: Amazon SageMaker, Amazon Lex, Amazon Kendra para diferentes necessidades de IA e ML.
- **Data Analytics**: Amazon Athena, Amazon Kinesis, AWS Glue e Amazon QuickSight para análise de dados.

### 📌 Outras Categorias de Serviços
- **Integração de Aplicativos**: Amazon EventBridge, SNS, SQS para mensagens e alertas.
- **Aplicativos de Negócios e Atendimento**: Amazon Connect, Amazon SES, AWS Support, AMS.
- **Ferramentas para Desenvolvedores**: AWS AppConfig, AWS Cloud9, CodePipeline, CodeCommit, entre outros.
- **Computação para Usuários Finais**: Amazon WorkSpaces, AppStream 2.0.
- **Front-end e IoT**: AWS Amplify e AppSync para front-end, AWS IoT Core e IoT Greengrass para dispositivos IoT.

### 📌 Habilidades em Seleção de Serviços
- **Escolha de Serviços**: Serviços para alertas e notificações, aplicativos de negócios, suporte ao cliente, ferramentas de desenvolvimento, visualização de VMs, criação de serviços para front-end e dispositivos móveis, e gerenciamento de dispositivos IoT.

---

## 💰 Domínio 4: Cobrança, Preços e Suporte (12% do conteúdo pontuado)

Este domínio cobre os modelos de preços da AWS, recursos de gerenciamento de cobrança, orçamento e custos, além dos recursos técnicos da AWS e opções de suporte.

### 📌 Modelos de Preços da AWS
- **Opções de Compra de Computação**: Instâncias sob demanda, instâncias reservadas, Spot Instances, Savings Plans, hosts dedicados, instâncias dedicadas e reserva de capacidade.
- **Cobranças de Transferência de Dados**: Custos de transferência entre Regiões ou dentro da mesma Região.
- **Opções e Níveis de Armazenamento**: Diferenças nos preços e opções de armazenamento.

### 📌 Recursos de Gerenciamento de Cobrança, Orçamento e Custos
- **Ferramentas de Gerenciamento de Custos**: AWS Budgets, Cost Explorer e Billing Conductor.
- **AWS Pricing Calculator**: Cálculos de custos estimados.
- **AWS Organizations e Alocação de Custos**: Cobrança consolidada, tags de alocação de custos.

### 📌 Recursos Técnicos da AWS e Opções de Suporte
- **Documentação e Recursos**: Whitepapers, blogs, AWS Knowledge Center e AWS re:Post.
- **Planos de Suporte AWS**: Developer Support, Business Support, Enterprise Support, entre outros.
- **Funções do AWS Trusted Advisor e Health Dashboard**: Otimização de custos e monitoramento do ambiente AWS.
- **Rede de Parceiros da AWS**: AWS Marketplace, provedores independentes de software e integradores de sistemas.

