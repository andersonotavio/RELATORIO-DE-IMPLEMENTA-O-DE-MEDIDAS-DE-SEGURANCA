# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

**Data:** 29/10/2026 
**Empresa:** Abstergo Industries  
**Responsável:** Anderson Otávio

## Introdução

Este relatório apresenta o processo de implementação de ferramentas de segurança na empresa Abstergo Industries, realizado por Anderson Otávio. O objetivo do projeto foi estabelecer três medidas de segurança em conjunto com os serviços da Amazon Web Services (AWS), visando aumentar a segurança da empresa e proteger seus recursos e dados armazenados na nuvem.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em três medidas de segurança. A seguir, serão descritas as etapas da implementação.

### Medida 1 — Controle de Acesso

Gerenciar o acesso aos recursos da AWS utilizando políticas de controle de acesso granulares. Para isso, utiliza-se o AWS Identity and Access Management (IAM), que permite criar usuários, grupos e funções com permissões específicas.

Dessa forma, é possível controlar quem tem acesso a cada recurso e quais ações podem ser realizadas. É importante seguir o princípio do privilégio mínimo, garantindo que os usuários tenham apenas as permissões necessárias para executar suas tarefas.

### Medida 2 — Proteção de Dados em Repouso e em Trânsito

Criptografar os dados tanto em repouso quanto em trânsito. Para proteger os dados armazenados, recomenda-se utilizar o AWS Key Management Service (KMS) para gerenciar as chaves de criptografia e proteger volumes de armazenamento, como Amazon EBS, e bancos de dados, como Amazon RDS.

Para proteger os dados em trânsito, devem ser utilizadas conexões seguras, como HTTPS com TLS para comunicações web e VPN (Virtual Private Network) para conexões de rede privada.

### Medida 3 — Monitoramento e Detecção de Anomalias

Estabelecer uma estratégia abrangente de monitoramento para identificar possíveis ameaças e atividades suspeitas. O AWS CloudTrail permite registrar as ações realizadas na conta AWS, contribuindo para auditorias e investigações de incidentes.

Além disso, o Amazon GuardDuty pode ser utilizado para detectar atividades potencialmente maliciosas, como tentativas de acesso não autorizado e comportamentos anormais nas contas e nos recursos da AWS.

## Conclusão

A implementação dessas medidas de segurança tem como objetivo contribuir para a proteção dos recursos e dados da empresa Abstergo Industries, além de favorecer a eficiência e a produtividade dos processos organizacionais.

Recomenda-se manter as ferramentas de segurança atualizadas, monitorar continuamente a infraestrutura e buscar novas tecnologias e práticas que possam aprimorar a proteção dos ativos digitais da empresa.

## Anexos

### Medidas de Segurança na Implementação de Ferramentas na AWS

Ao implementar ferramentas na Amazon Web Services (AWS), é fundamental priorizar a segurança dos recursos e dos dados armazenados na nuvem. A AWS oferece diversos serviços e recursos que auxiliam na proteção dos ativos digitais. Neste anexo, são apresentadas três medidas essenciais de segurança: controle de acesso, proteção de dados em repouso e em trânsito, e monitoramento e detecção de anomalias.

**1. Controle de Acesso**

O controle de acesso é uma parte fundamental da estratégia de segurança na AWS. Por meio do AWS Identity and Access Management (IAM), é possível criar e gerenciar identidades com diferentes níveis de permissões.

Recomenda-se seguir o princípio do privilégio mínimo, concedendo apenas as permissões necessárias para que usuários, grupos e funções realizem suas atividades. Essa prática ajuda a reduzir os riscos de acesso não autorizado aos recursos.

O IAM também permite configurar políticas de acesso granulares, que definem quais ações podem ser executadas em cada recurso da AWS.

**2. Proteção de Dados em Repouso e em Trânsito**

A proteção adequada dos dados é essencial para garantir a segurança da informação. Na AWS, é possível proteger os dados tanto em repouso, quando estão armazenados, quanto em trânsito, durante a comunicação entre sistemas.

Para proteger os dados em repouso, recomenda-se utilizar criptografia. O AWS Key Management Service (KMS) permite gerenciar e controlar as chaves de criptografia utilizadas na plataforma. Com esse serviço, é possível criptografar volumes de armazenamento, bancos de dados e outros recursos que armazenam informações sensíveis.

Para proteger os dados em trânsito, é essencial utilizar conexões seguras. A AWS oferece suporte à comunicação por meio do protocolo HTTPS com TLS para aplicações web e à utilização de VPN para conexões de rede privada. Essas medidas ajudam a impedir que terceiros interceptem e acessem informações confidenciais durante a transmissão.

**3. Monitoramento e Detecção de Anomalias**

O monitoramento contínuo é essencial para identificar possíveis ameaças e atividades suspeitas na AWS. A plataforma oferece serviços dedicados ao monitoramento e à segurança.

O AWS CloudTrail registra atividades realizadas na conta AWS, como a criação de instâncias EC2, alterações em políticas de segurança e operações relacionadas aos recursos. Esses registros permitem realizar auditorias e rastrear eventos durante investigações de incidentes.

Outra ferramenta importante é o Amazon GuardDuty, que detecta atividades potencialmente maliciosas na infraestrutura AWS. O serviço analisa fontes de dados e eventos para identificar comportamentos anormais e possíveis ameaças, como acessos suspeitos, tentativas de comprometimento de contas e comunicações potencialmente maliciosas.

Ao habilitar e configurar o GuardDuty, é possível receber alertas sobre ameaças detectadas, permitindo uma resposta mais rápida e eficaz aos incidentes de segurança.

A implementação dessas medidas de segurança na AWS é fundamental para proteger os recursos e os dados contra ameaças cibernéticas. Entretanto, a segurança é um processo contínuo e em constante evolução. Por isso, é importante acompanhar as melhores práticas de segurança da AWS, monitorar regularmente a infraestrutura e realizar ajustes sempre que necessário para garantir a proteção contínua dos ativos digitais.

## Assinatura do Responsável pelo Projeto

**Anderson Otávio**
