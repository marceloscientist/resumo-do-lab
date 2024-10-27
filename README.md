<a id="menu"></a>
## Menu de Labs  
- [1# Lab: Resumo do Primeiro Lab - Azure Essentials](#personalizacao)  
- [2# Lab: Resumo do Segundo Lab - Benefícios da Nuvem Azure e SLA](#sla)
- [3# Lab: Resumo do Terceiro Lab - IaaS, PaaS e SaaS na Azure](#modelosServico)
- [4# Lab: Resumo do Quarto Lab - Componentes de Arquitetura do Azure](#grupoRecursos)
- [5# Lab: Resumo do Quinto Lab - Serviços de Computação e Máquinas Virtuais do Azure](#virtualLab)
- [6# Lab: Resumo do Sexto Lab - Redundância e Serviços de Armazenamento do Azure](#armazenamentoAzure)
- [7# Lab: Resumo do Sétimo Lab - Identidade, Acesso e Segurança no Azure](#identidade)
- [8# Lab: Resumo do Oitavo Lab - Gerenciamento de Custos e Otimização no Azure](#custos)
- [9# Lab: Governança, Conformidade e Proteção de Dados no Azure 🔒](#conformidade)
- [10# Lab: Ferramentas de Gerenciamento e Implantação no Azure](#ferramentasImplantacao)

---

<a id="personalizacao"></a>
### 🌐 1# Lab: Resumo do Primeiro Lab - Azure Essentials 🚀  
O primeiro laboratório do Azure Essentials foi super simples e direto! 👌

💻 **Objetivo Principal**: Explorar a plataforma Azure e se familiarizar com sua interface e serviços.

🔧 **O que foi feito?**  
**Personalização do Ambiente**:  
- Mudamos o idioma e a aparência da plataforma, deixando-a do nosso jeito! 🌍🎨  

**Exploração de Serviços**:  
- Fizemos buscas por serviços, organizados por categorias (ou "mundos"), para entender as várias opções que a Azure oferece e em quais áreas cada serviço se encaixa. 🔍📂

📚 **Conclusão**:  
Esse laboratório foi uma ótima introdução para quem está começando na Azure! Ele oferece uma visão geral das funcionalidades e te ajuda a entender a plataforma sem se assustar com as opções. É um verdadeiro "mergulho suave" no universo da computação em nuvem. 🌥️🛠️  

---
[Topo](#menu)


<a id="sla"></a>
### 🌐 2# Lab: Resumo do Segundo Lab - Benefícios da Nuvem Azure e SLA 🚀  
Este laboratório foi essencial para entender os principais benefícios da Nuvem Azure, com destaque para o conceito de SLA (Service Level Agreement). 🔧

💻 **Objetivo Principal**: Explorar como a Nuvem Azure oferece escalabilidade, confiabilidade e segurança, com ênfase em como configurar a disponibilidade dos serviços.

🔧 **O que foi feito?**  
**Conceitos de SLA e Alta Disponibilidade**:  
- Aprendemos sobre a importância da **SLA** na garantia de disponibilidade dos serviços. Quanto maior o número de "nines" (99,9%, 99,99%, etc.), maior é o tempo garantido de funcionamento da aplicação. ⏳🔒

**Replicação de Aplicações em Múltiplas Regiões**:  
- O laboratório demonstrou como a replicação da aplicação em diferentes regiões geográficas é uma estratégia eficiente para aumentar a disponibilidade. Isso reduz o impacto de falhas e mantém o serviço ativo. 🌍📶

📚 **Conclusão**:  
Esse laboratório destacou a flexibilidade da Azure em se adaptar às necessidades específicas dos clientes, seja para ambientes de teste ou produção (PRD). Com configurações ajustadas corretamente, é possível garantir alta disponibilidade e minimizar falhas, garantindo uma experiência mais confiável. 🛡️💼  

---
[Topo](#menu)


<a id="modelosServico"></a>
### 🌐 3# Lab: Resumo do Terceiro Lab - IaaS, PaaS e SaaS na Azure 🚀  
Neste laboratório, exploramos os modelos de serviço da Azure: **IaaS (Infrastructure as a Service)**, **PaaS (Platform as a Service)** e **SaaS (Software as a Service)**, além do modelo de **Responsabilidade Compartilhada**. 🔧

💻 **Objetivo Principal**: Compreender as diferenças entre os modelos de serviço e como a responsabilidade é compartilhada entre o provedor de nuvem e o usuário.

🔧 **O que foi feito?**  
**Exploração dos Modelos de Serviço**:  
- **IaaS**: Ao criar um servidor na Azure, a configuração e a gestão da infraestrutura ficam sob responsabilidade do usuário. Isso significa que você precisa gerenciar desde a configuração do servidor até a instalação de sistemas operacionais e aplicações. 🖥️⚙️

- **PaaS**: Aqui, a Azure cuida da infraestrutura e da plataforma subjacente, permitindo que o usuário se concentre no desenvolvimento e na configuração de suas aplicações. Por exemplo, ao alocar um servidor de banco de dados, a responsabilidade pela configuração do servidor fica com a Azure, enquanto o usuário foca nas configurações específicas do banco. 💻📊

- SaaS: Este modelo oferece aplicações completas que estão prontas para uso, eliminando a necessidade de gerenciar a infraestrutura e a plataforma. O usuário simplesmente acessa a aplicação, e toda a gestão fica por conta do provedor de serviços. Claro, existe um gerenciamento básico, como o controle de acessos e de usuários, que fica a cargo do usuário. ☁️📦

📚 **Conclusão**:  
Esse laboratório destacou a importância de entender como as responsabilidades variam entre os diferentes modelos de serviço. Saber qual modelo usar pode facilitar o gerenciamento de recursos e otimizar o tempo e os esforços dos usuários, permitindo que eles se concentrem no que realmente importa: suas aplicações e dados. 🌟📈  

---
[Topo](#menu)


<a id="grupoRecursos"></a>
### 🌐 4# Lab: Resumo do Quarto Lab - Componentes de Arquitetura do Azure 🚀  
No quarto laboratório, exploramos os **Componentes de Arquitetura do Azure**, com foco em **Grupos de Recursos**, **Pares de Região**, e **Assinaturas do Azure**. Este lab foi prático, abordando a criação de uma Rede Virtual e a importância de organizar recursos dentro de grupos. 🌍🔧

💻 **Objetivo Principal**: Entender como os componentes de arquitetura são fundamentais para organizar e gerenciar recursos no Azure, garantindo escalabilidade e controle de custos.

🔧 **O que foi feito?**  
**Grupos de Recursos**:  
- Ao criar uma Rede Virtual, o primeiro passo foi configurar um **Grupo de Recursos**. Ele funciona como uma "caixa organizadora" onde você pode agrupar recursos relacionados (como redes, bancos de dados, máquinas virtuais) de forma lógica e gerenciável. Um recurso só pode ser criado se estiver associado a um Grupo de Recursos. 🗂️

- **Organização e Tags**: Dentro do grupo, você pode adicionar **Tags** para identificar os recursos com base em critérios específicos, como ambiente (produção, desenvolvimento), departamento, ou até projetos. Isso facilita a gestão e o rastreamento, principalmente no controle de custos no final do mês. 💸

- **Controle de Custos**: Os Grupos de Recursos são fundamentais para o gerenciamento financeiro, permitindo que os custos de cada recurso sejam monitorados de forma clara e precisa. Isso é especialmente útil para separar ambientes e organizar as faturas conforme o uso e o propósito de cada grupo (desenvolvimento, teste, produção). 📊💰

**Pares de Região**:  
- Durante o lab, exploramos também o conceito de **Pares de Região**. Regiões no Azure são sempre emparelhadas (como Brasil e EUA), o que oferece alta disponibilidade, permitindo a replicação de recursos entre regiões em caso de falha em uma delas. Isso é crucial para garantir a continuidade dos serviços e minimizar o impacto de possíveis interrupções. 🌎🌍

**Assinatura da Azure e Grupos de Gerenciamento**:  
- Cada recurso no Azure está associado a uma **Assinatura**, que é um contrato de uso dos serviços da Azure. As assinaturas podem ser organizadas em **Grupos de Gerenciamento**, o que facilita o controle e a governança de várias assinaturas dentro de uma mesma organização. Isso permite que empresas maiores organizem suas infraestruturas e gerenciem permissões, custos e políticas de maneira eficiente. 🔐🧾

📚 **Conclusão**:  
Esse laboratório nos ensinou que uma arquitetura bem organizada é essencial para o bom uso da plataforma Azure. Ao criar Grupos de Recursos, Pares de Região e configurar corretamente suas assinaturas, é possível garantir alta disponibilidade, controle de custos, e uma gestão mais eficiente dos recursos. Essas práticas organizam seu ambiente em nuvem e facilitam a administração tanto técnica quanto financeira. 🏗️💼  

---
[Voltar ao Menu](#menu)

<a id="virtualLab"></a>
### 🌐 5# Lab: Resumo do Quinto Lab - Serviços de Computação e Máquinas Virtuais do Azure 🚀  

No quinto laboratório, aprofundamos nosso conhecimento nos **Serviços de Computação do Azure**, abordando conceitos de **Máquinas Virtuais (VMs)**, **Conjuntos de Disponibilidade**, **Área de Trabalho Virtual**, **Contêineres**, e **Azure Functions**. Esse lab apresentou um panorama abrangente das ofertas de IaaS e PaaS da Azure, com detalhes importantes sobre configuração e uso. ☁️🖥️

💻 **Objetivo Principal**: Entender como criar e configurar Máquinas Virtuais, Conjuntos de Disponibilidade, e explorar recursos como Área de Trabalho Virtual, Azure Functions e Serviços de Aplicativo.

🔧 **O que foi feito?**

**Máquinas Virtuais (VMs)**:  
- Criamos **Máquinas Virtuais** na plataforma Azure e exploramos as configurações de **IaaS (Infrastructure as a Service)**. As VMs oferecem total controle sobre o sistema operacional, configurações de rede, discos e mais. As opções de configuração variam de acordo com a necessidade do usuário (desde pequenos servidores a configurações mais complexas). ⚙️💾

- **Conjuntos de Disponibilidade**: Ao configurar VMs, reforçamos a importância dos **Conjuntos de Disponibilidade (Availability Sets)**, que são usados para aumentar a resiliência e garantir que, em caso de falha no hardware ou manutenção, suas VMs não sejam afetadas simultaneamente. Isso distribui as máquinas virtuais entre diferentes domínios de falha e atualização, garantindo maior tempo de atividade. Este ponto é frequentemente abordado em provas como a **AZ-900**, pois reflete boas práticas de alta disponibilidade. 🛡️⏳

**Área de Trabalho Virtual (Virtual Desktop)**:  
- Exploramos a tela de configuração da **Área de Trabalho Virtual** (Virtual Desktop), que é um serviço **PaaS (Platform as a Service)**. Ele permite disponibilizar recursos para múltiplos usuários que podem compartilhar o mesmo host, garantindo flexibilidade e escalabilidade.
- É uma solução excelente para empresas que precisam de desktops gerenciados de forma centralizada e segura. 🖥️👥

**Azure Functions**:  
- Tivemos uma visão geral do **Azure Functions**, um serviço de **computação sem servidor (Serverless)** que permite executar pequenos pedaços de código sob demanda, sem a necessidade de gerenciar infraestrutura.

📚 **Conclusão**:  
Esse laboratório foi essencial para entender a vasta gama de opções de computação oferecidas pelo Azure. Ao criar e configurar **Máquinas Virtuais**, **Conjuntos de Disponibilidade** e explorar **Virtual Desktop** e **Azure Functions**, vimos na prática como a plataforma Azure é flexível e pode se adaptar às diferentes necessidades de infraestrutura e computação. Esses conceitos e configurações são extremamente importantes para quem está estudando para a **certificação AZ-900**, especialmente tópicos como alta disponibilidade, VMs, e serviços de computação escalável. 🌐📈

---
[Voltar ao Menu](#menu) 

<a id="armazenamentoAzure"></a>

🌐 6# Lab: Resumo do Sexto Lab - Redundância e Serviços de Armazenamento do Azure 🚀
No sexto laboratório, exploramos os Serviços de Armazenamento do Azure, com foco na Redundância, Migrações para o Azure, e Gerenciamento de Arquivos. Aprendemos sobre a criação de contas de armazenamento e as diferentes opções que a plataforma oferece para gerenciar dados de forma segura e eficiente. ☁️📦

💻 Objetivo Principal: Entender as opções de armazenamento disponíveis no Azure, como configurar a redundância e as migrações, e conhecer os diferentes serviços de gerenciamento de arquivos.

🔧 O que foi feito?

Criação de Conta de Armazenamento:

Iniciamos o lab criando uma Conta de Armazenamento, onde destacamos a importância de ter um nome único e as opções de tipo de desempenho, como Standard e Premium. Esses tipos definem a performance e o custo associado ao uso do armazenamento no Azure. 🏷️⚙️
Redundância:

Discutimos os quatro tipos principais de Redundância disponíveis no Azure, que garantem a proteção dos dados contra falhas. Esses tipos incluem:
Locally Redundant Storage (LRS): Mantém cópias dos dados em várias máquinas dentro de uma única região.
Geo-Redundant Storage (GRS): Replica os dados em uma região secundária para maior resiliência.
Zone-Redundant Storage (ZRS): Distribui os dados entre várias zonas de disponibilidade em uma mesma região.
Read-Access Geo-Redundant Storage (RA-GRS): Oferece leitura dos dados replicados em uma região secundária.
Esses conceitos são fundamentais para garantir a disponibilidade e integridade dos dados, sendo frequentemente abordados em provas como a AZ-900. 🔒🌍

Migrações para o Azure:
O lab também abordou as diversas opções de migração para o Azure, como a transferência de servidores, bancos de dados, e aplicativos web. Discutimos ferramentas como o Azure Data Box, que facilita a migração de grandes volumes de dados de forma segura e eficiente. 🛠️📤

Gerenciamento de Arquivos:
Aprendemos sobre as diferentes opções de gerenciamento de arquivos disponíveis no Azure, como o Azure File Storage, que permite compartilhar arquivos em uma rede usando o protocolo SMB. Também exploramos os conceitos de tokens de acesso compartilhado (SAS) e como eles podem ser utilizados para fornecer acesso temporário a recursos em uma conta de armazenamento. 🔑📂

---
[Voltar ao Menu](#identidade)

<a id="lab7"></a>
### 🔐 7# Lab: Resumo do Sétimo Lab - Identidade, Acesso e Segurança no Azure 🚀

No sétimo laboratório, exploramos as práticas de **Identidade, Acesso e Segurança** no Azure, com foco em **Microsoft Entra ID (antigo Azure AD)**, **Autenticação e Autorização**, **Acesso Condicional** e **Microsoft Defender for Cloud**. Este lab trouxe uma visão prática e detalhada sobre como gerenciar o acesso e a segurança no ambiente de nuvem.

💻 **Objetivo Principal**: Compreender como os serviços de identidade e segurança do Azure ajudam a proteger recursos, gerenciar acessos e monitorar atividades, especialmente em cenários que envolvem integração com ambientes **on-premises**.

🔧 **O que foi feito?**

**Microsoft Entra ID e Gerenciamento de Identidade**:  
- Exploramos o **Microsoft Entra ID** e como ele gerencia a identidade e o acesso aos recursos na nuvem. Diferente de outros sistemas, usuários não são automaticamente sincronizados do ambiente **on-premises** para o Entra ID. Precisamos configurar o **Entra Connect** ou **Connect Sync** para realizar essa sincronização.
- **Roles e Administradores**: Analisamos as permissões de acesso que podem ser configuradas através de **roles** (papeis) e **administradores**, que facilitam o controle sobre os privilégios dos usuários. É importante lembrar que papéis específicos como P1 e P2 exigem licenças pagas, não estando disponíveis em contas free trial.
- **Autenticação e Autorização**: Revisamos os conceitos de **autenticação** (quem é o usuário) e **autorização** (o que ele pode acessar), essenciais para definir o nível de acesso em cada recurso. ✋👥

**Acesso Condicional e Controle de Acesso (IAM)**:  
- Configuramos o **Acesso Condicional**, definindo políticas que controlam como e quando os usuários podem acessar determinados recursos. Esse controle é fundamental para prevenir acessos não autorizados.
- **IAM (Identity and Access Management)**: No IAM, criamos políticas de acesso personalizadas para diferentes **resource groups**, permitindo um gerenciamento seguro e granular de permissões em todo o ambiente de nuvem. 👮‍♂️🔑

**Microsoft Defender for Cloud**:  
- No **Microsoft Defender for Cloud**, visualizamos o nível de segurança dos nossos recursos e criamos **políticas de segurança** para aumentar a proteção.
  - **DevOps Security** e **Security Alerts**: Utilizados para monitorar e alertar sobre potenciais ameaças de segurança. O recurso **Defender CSPM** fornece insights avançados, embora seja uma funcionalidade paga.
  - **Foundation CSPM**: Disponível gratuitamente e essencial para a gestão de segurança básica.
  - **Attack Paths**: Identifica possíveis rotas de ataque, permitindo antecipar e mitigar riscos antes que se tornem incidentes de segurança.

---
[Voltar ao Menu](#menu)


<a id="custos"></a>
### 💰 8# Lab: Resumo do Oitavo Lab - Gerenciamento de Custos e Otimização no Azure 📊

No oitavo laboratório, exploramos como **gerenciar e calcular custos** no Azure para otimizar gastos e planejar investimentos em nuvem. Com ferramentas como o **TCO Calculator** e a **Calculadora de Preços**, analisamos cenários e configuramos estimativas de custo baseadas em diferentes cargas de trabalho e estratégias.

💡 **Objetivo Principal**: Aprender a usar as ferramentas de análise de custos do Azure, entender os fatores que afetam o orçamento e gerenciar gastos de maneira eficiente.

🔧 **O que foi feito?**

**1. Calculadora do TCO (Custo Total de Propriedade)**:
- A **Calculadora TCO** ajuda a simular quanto se gastaria ao migrar de um ambiente **on-premise** para a nuvem.
- Definimos **cargas de trabalho** (ambiente, sistemas operacionais, banco de dados, rede, etc.), ajustamos suposições e geramos relatórios que indicam uma projeção de economia.
- A ferramenta permite inserir licenças que a empresa já possui, o que ajuda a reduzir custos, e exibe um **dashboard de economia** ao final da configuração, facilitando a análise de viabilidade da migração. 📈💵

**2. Calculadora de Preços**:
- A **Calculadora de Preços** do Azure é a ferramenta oficial para estimar custos de serviços específicos, como **Virtual Machines**, **Banco de Dados**, **Rede**, entre outros.
- Com ela, simulamos cenários ajustando configurações e observamos como **pequenas mudanças** (como o tipo de instância, licenciamento, horas ativas e reservas) afetam o valor total. Isso possibilita uma simulação que reflete a necessidade real da empresa, ajudando a planejar o orçamento. 💳💼

**3. Cost Management e Tags**:
- Utilizamos o **Cost Management** para monitorar e gerenciar a assinatura e os custos em tempo real, com recursos como:
  - **Advisor Recommendations**: recomendações automáticas para otimizar gastos, oferecendo sugestões de melhorias.
  - **Alertas de Custo**: configuramos alertas para não ultrapassar o limite de orçamento definido, garantindo o controle financeiro.
  - **Orçamento (Budget)**: configuramos limites de gastos e ativamos validações para evitar despesas inesperadas.
- **Tags**: As **tags** são usadas para organizar e categorizar recursos, facilitando o gerenciamento e a alocação de custos no Azure Cost Center. 🎯🏷️

---
[Topo](#menu)



<a id="conformidade"></a>
### 🛡️ 9# Lab: Governança, Conformidade e Proteção de Dados no Azure 🔒

Neste laboratório, exploramos as ferramentas de **Governança e Conformidade** do Azure, focando no uso de **Blueprints, Políticas e Bloqueios de Recursos** para gerenciar segurança, proteção de dados e manter as configurações conforme os padrões regulatórios.

💡 **Objetivo Principal**: Aprender a configurar bloqueios, políticas e outras ferramentas de governança que ajudam a proteger dados, garantir conformidade e gerenciar os recursos com segurança.

🔧 **O que foi feito?**

**1. Trust Center e Compliance Manager**:
- O **Portal de Confiança de Serviços (Service Trust Portal)** do Azure fornece documentos e relatórios de conformidade que ajudam a provar que os serviços estão alinhados com regulamentos, como a **Resolução Bacen** e padrões de proteção de dados.
- Com o **Compliance Manager**, é possível acessar checklists e relatórios específicos que auxiliam em auditorias, ajudando a manter a conformidade com normas como LGPD, ISO e outros padrões globais. 📄✅

**2. Bloqueios de Recursos (Locks)**:
- No **Resource Groups**, configuramos **bloqueios de exclusão e modificação** (Delete e Read-only) para evitar alterações acidentais nos recursos.
- Observamos que o bloqueio se aplica apenas ao **nível onde ele é configurado** (grupo de recursos ou recurso específico). Por exemplo, mover um recurso bloqueado para outro grupo sem o bloqueio permite que ele seja alterado ou excluído. 🔒🗄️

**3. Microsoft Purview e Governança de Dados**:
- **Microsoft Purview** é uma plataforma de governança que facilita o gerenciamento, coleta e auditoria de dados. Ele oferece:
  - **Compliance Manager**: para monitorar o status de conformidade.
  - **Records Management** e **Microsoft Priva**: soluções de conformidade para LGPD e outras leis de privacidade, facilitando a gestão de dados pessoais e auditorias de proteção de dados.
- **Reports de análise** do Purview ajudam a identificar pontos fortes e fracos de segurança e conformidade. 📊🔍

**4. Políticas (Policies)**:
- **Azure Policies** permite criar e aplicar regras em diversos níveis, desde o nível de assinatura até grupos de recursos e recursos individuais.
  - Exemplos incluem a política de **Allowed Locations** (Localizações Permitidas), que limita onde recursos podem ser criados.
  - **Parametrização e Remediação**: políticas podem ser personalizadas com parâmetros específicos, com mensagens de não conformidade, além de configurações de remediação para corrigir automaticamente recursos fora de conformidade.
- Políticas criadas garantem que **todos os usuários**, independentemente do cargo, sigam as regras definidas, assegurando a uniformidade na aplicação de normas. 📜✅


---
[Voltar ao Menu](#menu)


Aqui está o **Resumo do 10# Lab** sobre Ferramentas de Gerenciamento e Implantação no Azure:

---

<a id="ferramentasImplantacao"></a>
### 🛠️ 10# Lab: Ferramentas de Gerenciamento e Implantação no Azure ⚙️

**Objetivo Principal**: Explorar diferentes ferramentas e métodos de criação e gerenciamento de recursos no Azure, desde interfaces gráficas até linhas de comando e scripts automatizados.

### 🔑 Pontos Principais:

1. **Criação de Recursos**:
   - Embora a criação de recursos no Azure seja intuitiva pela **interface gráfica**, o Azure permite também a configuração e gerenciamento por linhas de comando, oferecendo alternativas para maior controle e automação.
   - Os métodos de **CLI (Command-Line Interface)**, **PowerShell** e **Azure Portal** são os principais. O administrador pode escolher o que preferir, dependendo da familiaridade e das necessidades de automação. 

2. **Ferramentas CLI e PowerShell**:
   - **Azure CLI** e **PowerShell** facilitam a criação e gerenciamento de recursos usando comandos.
   - **Funcionalidades**: Autocomplete de comandos, suporte de help integrado, e facilidade para baixar e exportar recursos configurados.
   - **Armazenamento**: Certos comandos requerem uma **Storage Account** associada para armazenamento temporário e persistência de dados. Essa conta de armazenamento é essencial para comandos que lidam com recursos significativos.

3. **Uso de Modelos e Automação**:
   - O **Azure Automation** permite utilizar modelos de recursos exportáveis, que podem ser configurados e replicados em diferentes ambientes, melhorando a padronização e agilizando a implantação.
   - **Templates Bicep**: Bicep é uma linguagem para definir infraestrutura como código no Azure, simplificando o gerenciamento e tornando a configuração mais intuitiva. Ele permite criar templates reutilizáveis que podem ser facilmente integrados ao processo de automação.

4. **Azure Arc**:
   - O **Azure Arc** permite gerenciar recursos **externos ao Azure**, como servidores locais e clusters Kubernetes, centralizando o controle e facilitando a governança de infraestrutura híbrida.
   - Através do Arc, a mesma experiência de gerenciamento do Azure pode ser aplicada em ambientes multicloud e on-premises.


---
[Voltar ao Menu](#menu)











