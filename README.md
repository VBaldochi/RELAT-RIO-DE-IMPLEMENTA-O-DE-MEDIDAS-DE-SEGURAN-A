# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 30/10/2023
Empresa: Abstergo Industries 
Responsável: Vincius Baldochi Cardoso

# Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries , realizado por Romario Santos. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

# Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: 
- Controle de Acesso: Gerencie o acesso aos seus recursos da AWS usando políticas de controle de acesso granulares. Utilize o AWS Identity and Access Management (IAM) para criar usuários, grupos e funções com permissões específicas. Dessa forma, você pode controlar quem tem acesso a quais recursos e quais ações eles podem realizar. É importante seguir o princípio do "privilégio mínimo", garantindo que os usuários tenham apenas as permissões necessárias para realizar suas tarefas

Medida 2: 
- Proteção de Dados em Repouso e em Trânsito: Criptografe seus dados tanto em repouso quanto em trânsito. Utilize o AWS Key Management Service (KMS) para gerenciar chaves de criptografia e criptografar volumes de armazenamento (por exemplo, Amazon EBS) e bancos de dados (por exemplo, Amazon RDS). Para proteger os dados em trânsito, utilize conexões seguras, como HTTPS (TLS) para comunicações web e VPN (Virtual Private Network) para conexões de rede privada.

Medida 3: 
- Monitoramento e Detecção de Anomalias: Estabeleça uma estratégia de monitoramento abrangente para identificar possíveis ameaças e atividades suspeitas. Use serviços como o AWS CloudTrail para registrar todas as ações realizadas na sua conta da AWS, o que pode ajudar na auditoria e na investigação de incidentes. Além disso, você pode utilizar o Amazon GuardDuty para detectar atividades maliciosas, como tentativas de acesso não autorizado ou comportamentos anormais nas suas contas e recursos da AWS.


# Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado que seja bem o berneficio da empresa, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

# Anexos

 Medidas de Segurança na Implementação de Ferramentas na AWS

Ao implementar ferramentas na Amazon Web Services (AWS), é crucial priorizar a segurança dos recursos e dados armazenados na nuvem. A AWS oferece uma série de recursos e serviços para ajudar a garantir a proteção dos seus ativos digitais. Neste anexo, discutiremos três medidas de segurança essenciais para a implementação de ferramentas na AWS: controle de acesso, proteção de dados em repouso e em trânsito, e monitoramento e detecção de anomalias.

1. Controle de Acesso:
O controle de acesso é uma parte fundamental da estratégia de segurança na AWS. Através do AWS Identity and Access Management (IAM), é possível criar e gerenciar identidades com diferentes níveis de permissões. Com o IAM, é recomendado seguir o princípio do "privilégio mínimo", ou seja, conceder apenas as permissões necessárias para os usuários, grupos e funções realizarem suas tarefas. Isso ajuda a reduzir os riscos de acesso não autorizado aos recursos. O IAM também permite a configuração de políticas de acesso granulares, que definem quais ações podem ser executadas em cada recurso da AWS.

2. Proteção de Dados em Repouso e em Trânsito:
A proteção adequada dos dados é crucial para garantir a segurança da informação. Na AWS, é possível proteger os dados tanto em repouso (armazenados) quanto em trânsito (durante a comunicação). Para proteger os dados em repouso, é recomendado o uso de criptografia. O AWS Key Management Service (KMS) permite gerenciar e controlar as chaves de criptografia utilizadas na plataforma. Com o KMS, é possível criptografar volumes de armazenamento, bancos de dados e outros recursos que armazenam dados sensíveis. Isso fornece uma camada adicional de segurança, mesmo que alguém obtenha acesso físico aos dispositivos de armazenamento.

Para proteger os dados em trânsito, é essencial utilizar conexões seguras. A AWS suporta a comunicação segura por meio do protocolo HTTPS (TLS) para aplicações web e a conexão de rede privada por meio de VPN (Virtual Private Network). Essas medidas garantem que os dados sejam transmitidos de forma criptografada, impedindo que terceiros interceptem e acessem informações confidenciais durante a transmissão.

3. Monitoramento e Detecção de Anomalias:
O monitoramento constante é essencial para identificar possíveis ameaças e atividades suspeitas na AWS. A plataforma oferece serviços dedicados ao monitoramento de segurança. O AWS CloudTrail é um serviço que registra todas as ações realizadas na sua conta da AWS, como a criação de instâncias EC2, alterações em políticas de segurança e acesso a recursos. Isso permite uma auditoria detalhada e a capacidade de rastrear eventos em caso de incidentes de segurança.

Outra ferramenta importante é o Amazon GuardDuty, que realiza a detecção de atividades maliciosas na sua infraestrutura AWS. O GuardDuty utiliza algoritmos de aprendizado de máquina para analisar logs e eventos, identificando comportamentos anormais e possíveis ameaças, como acesso não autorizado, tentativas de comprometimento de contas e comunicações suspeitas. Ao habilitar o GuardDuty, você pode receber alertas em tempo real sobre atividades maliciosas, permitindo uma resposta rápida e efetiva aos incidentes de segurança.

Implementar essas medidas de segurança na AWS é fundamental para proteger seus recursos e dados contra ameaças cibernéticas. No entanto, é importante lembrar que a segurança é um processo contínuo e em constante evolução. Mantenha-se atualizado com as melhores práticas de segurança da AWS, monitore regularmente sua infraestrutura e faça ajustes conforme necessário para garantir a proteção contínua dos seus ativos digitais

Assinatura do Responsável pelo Projeto:

Vinicius Baldochi Cardoso
