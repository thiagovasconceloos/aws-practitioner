
# Preparatorio - AWS Practitioner:



## 1. Vantagens da Computação em Nuvem

- Trocar despesa de capital (CAPEX) por despesa operacional (OPEX): pagar conforme demanda; não possuir hardware físico.
- Beneficiar-se de economias de escala massivas, resultando em preços reduzidos.
- Parar de adivinhar capacidade e escalar baseado no uso real.
- Aumentar velocidade e agilidade para lançar novos serviços.
- Parar de gastar com operação e manutenção de data centers próprios.
- Expandir globalmente em minutos, aproveitando infraestrutura global da AWS.

---

## 2. Três Fundamentos da Precificação AWS

- **Compute (Computação):** custo pelo uso de recursos computacionais (ex: EC2, Lambda, containers).
- **Storage (Armazenamento):** custo pelo espaço utilizado para guardar dados (ex: S3, EBS).
- **Data Out (Dados de saída):** custo pela transferência de dados para fora da AWS (internet). A entrada de dados (Data In) é geralmente gratuita.

---

## 3. Pontos para Escolha de Região AWS

- **Conformidade (compliance):** atender às leis e regulamentos locais, como a LGPD no Brasil.
- **Latência:** escolher uma região próxima dos usuários para reduzir atrasos e melhorar a experiência.
- **Preço:** custos dos serviços AWS podem variar entre regiões, influenciando o orçamento.

---

## 4. Serviços com Escopo Global e Regionais

- **Globais:** Route 53 (DNS), IAM (gerenciamento de identidade e acesso), CloudFront (CDN), AWS WAF (firewall).
- **Regionais:** EC2 (máquinas virtuais), S3 (armazenamento), RDS (banco de dados relacional).

---

## 5. Infraestrutura da AWS

- **Regiões:** agrupamentos geográficos com múltiplas Zonas de Disponibilidade (AZs).
- **Zonas de Disponibilidade (AZs):** data centers independentes com energia, rede e refrigeração próprios. Cada região tem pelo menos 2 AZs para garantir resiliência.
- **Edge Locations:** pontos de presença espalhados globalmente usados para acelerar a entrega de conteúdo via CDN, como no CloudFront.

---

## 6. Modelo de Responsabilidade Compartilhada AWS

- **AWS:** responsável pela segurança da nuvem — infraestrutura física, hardware, software, rede, data centers.
- **Cliente:** responsável pela segurança na nuvem — dados, identidade, aplicações, sistemas, redes e firewalls.
- Importante para o cliente entender essa divisão para garantir compliance e segurança.

---

## 7. Modelo Pay As You Go

- Paga-se apenas pelo uso efetivo dos recursos, sem necessidade de investimento antecipado ou contratos fixos.

---

## 8. Modelos de Cloud Computing

- **On-premises:** infraestrutura própria no local da empresa.
- **IaaS (Infrastructure as a Service):** aluguel de recursos virtuais (ex: EC2, S3).
- **PaaS (Platform as a Service):** plataforma para desenvolver e rodar aplicações (ex: RDS, ECS).
- **SaaS (Software as a Service):** software pronto para uso (ex: Gmail, WorkSpaces).

---

## 9. Diferença entre Tolerância a Falhas e Recuperação de Desastres

- **Tolerância a falhas:** manter o sistema funcionando mesmo quando partes falham, com redundância ativa.
- **Recuperação de desastres:** restaurar serviços após falhas severas, com possível downtime.



---

## 10. Política de Uso Aceitável da AWS (Acceptable Use Policy - AUP)

- Define o que não é permitido na plataforma AWS. 
- Proíbe uso ilegal, ofensivo ou prejudicial.
- Proíbe ataques, invasões, spam, abuso de rede, e mensagens fraudulentas.
- Link oficial: [https://aws.amazon.com/aup/](https://aws.amazon.com/aup/)

---

## 11. Serviços AWS e Seus Modelos de Nuvem

``` 
AWS Serviços

├── IaaS (Infraestrutura como Serviço)
│ ├── Amazon EC2
│ │ └─ Máquinas virtuais para rodar apps
│ ├── Amazon S3
│ │ └─ Armazenamento de objetos (arquivos, imagens)
│ ├── Amazon EBS
│ │ └─ Armazenamento em blocos para EC2 (tipo HD virtual)
│ ├── Amazon CloudFront
│ │ └─ CDN para distribuir conteúdo globalmente
│
├── PaaS (Plataforma como Serviço)
│ ├── Amazon RDS
│ │ └─ Banco de dados gerenciado (MySQL, PostgreSQL, etc)
│ ├── AWS Lambda
│ │ └─ Computação serverless por função (FaaS)
│ ├── Amazon ECS
│ │ └─ Orquestração de containers Docker
│ ├── Amazon DynamoDB
│ │ └─ Banco NoSQL gerenciado
│
└── SaaS (Software como Serviço)
└── Amazon WorkSpaces
└─ Desktop virtual na nuvem para usuários
```
