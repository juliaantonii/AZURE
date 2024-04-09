# Guia Inicial para Azure

Guia de introdução básica ao Microsoft Azure para iniciantes, abordando conceitos essenciais e recursos importantes para começar.

<div align="center">

  <img src="images/AZURE.png" alt="Azure" width="400">

</div>

## O que é Azure?

Azure é a plataforma de computação em nuvem da Microsoft, oferecendo uma ampla gama de serviços e ferramentas para desenvolvimento, implantação e gerenciamento de aplicativos e recursos de TI na nuvem. Com Azure, você pode construir, implantar e gerenciar aplicativos em uma rede global de datacenters da Microsoft.

A Microsoft fornece uma grande variedade de recursos de aprendizado para ajudar você a se familiarizar mais com Azure:

- [Documentação do Azure](https://docs.microsoft.com/azure/): Explore os guias e tutoriais detalhados sobre os serviços do Azure.
- [Azure Learning Pathways](https://docs.microsoft.com/learn/azure/): Cursos gratuitos e trilhas de aprendizado para desenvolvedores, administradores e profissionais de TI.
- [Microsoft Learn](https://learn.microsoft.com/azure/): Uma plataforma de aprendizado interativo com módulos de aprendizado específicos do Azure.

## Começando com Azure (INTRODUÇÃO)

Aqui estão os passos básicos para começar com Azure:

### 1. Criar uma Conta Azure:
   - Acesse o [site do Azure](https://azure.microsoft.com/), clique em "Comece gratuitamente" e siga as instruções para criar uma conta gratuita.

<div align="center">

![Página Inicial do Azure Microsoft](<images/Página Inicial do Azure Microsoft.png>)

</div>

### 2. Explorar o Portal do Azure:
   - Depois de criar uma conta, acesse o [Portal do Azure](https://portal.azure.com/) para explorar os serviços e recursos disponíveis.

<div align="center">

![Página Inicial do Azure Microsoft](<images/Página com a conta logada.png>)

</div>

### 3. Criar um Resource Group:
No Portal do Azure, você pode criar um grupo de recursos para organizar os recursos relacionados ao seu projeto. Um grupo de recursos é um contêiner lógico que agrupa esses recursos, simplificando a navegação e o gerenciamento. Além disso, ele ajuda na compreensão dos custos associados aos seus recursos, facilita a localização dos recursos e permite a exclusão rápida e fácil quando necessário. Essa prática é fundamental para manter seu ambiente de nuvem organizado e eficiente.

<div align="center">

![Crie um Grupo de Recursos](<images/Crie um Grupo de Recursos.png>)

</div>

&nbsp;

A área de marcação permite que você categorize, organize e rotule seus recursos de acordo com suas próprias necessidades e processos de negócios. Isso pode ser útil para várias finalidades, incluindo:

- **Organização:** Tags podem ajudar na organização de recursos, permitindo que você os agrupe de acordo com critérios específicos, como departamento, ambiente (produção, desenvolvimento, teste), proprietário etc.

- **Rastreamento de Custos:** Ao atribuir tags aos recursos, você pode acompanhar os custos associados a esses recursos com mais precisão. Isso é especialmente útil em ambientes onde vários projetos ou departamentos compartilham os mesmos recursos do Azure.

- **Gestão de Acesso:** As tags podem ser usadas em políticas de acesso e controle para conceder ou negar permissões com base em critérios específicos. Por exemplo, você pode conceder acesso apenas aos recursos com uma determinada tag.

- **Automação e Gestão de Recursos:** Tags podem ser usadas em scripts de automação e ferramentas de gestão para filtrar, identificar e operar sobre conjuntos específicos de recursos de maneira mais eficiente.

&nbsp;

<div align="center">

![Crie um Grupo de Recursos pt.1](<images/Criar um GR pt1.png>)

![Crie um Grupo de Recursos pt.2](<images/Criar um GR pt2.png>)

![Crie um Grupo de Recursos pt.3](<images/Criar um GR pt3.png>)

![Crie um Grupo de Recursos pt.4](<images/Criar um GR pt4.png>)

</div>

### 4. Provisionar uma Máquina Virtual:
Experimente implantar uma máquina virtual para entender o processo de provisionamento e gerenciamento de recursos no Azure. A máquina virtual do Azure permite que você execute aplicativos e cargas de trabalho como se estivesse executando em um computador físico, mas com os benefícios adicionais da nuvem, como escalabilidade, flexibilidade e gerenciamento simplificado.

Aqui estão algumas das principais finalidades e benefícios de usar máquinas virtuais no Azure:

- **Implantação de Aplicações:** Você pode usar máquinas virtuais para implantar e executar uma ampla variedade de aplicativos e serviços, incluindo sistemas operacionais Windows e Linux, aplicativos da web, bancos de dados, servidores de aplicativos, servidores de arquivos e muito mais.

- **Desenvolvimento e Testes:** As máquinas virtuais do Azure são ideais para desenvolvimento e testes de software. Você pode criar ambientes isolados para desenvolver e testar aplicativos sem comprometer seu ambiente de produção.

- **Escalabilidade:** O Azure permite dimensionar verticalmente (aumentar ou diminuir o tamanho das máquinas virtuais) e horizontalmente (adicionar ou remover instâncias de máquinas virtuais) de acordo com as necessidades do seu aplicativo ou carga de trabalho.

- **Flexibilidade:** Você pode escolher entre uma variedade de tamanhos de máquinas virtuais e configurar recursos de computação, armazenamento e rede de acordo com os requisitos específicos da sua aplicação.

- **Gerenciamento Simplificado:** O Azure fornece ferramentas e recursos para simplificar o gerenciamento de suas máquinas virtuais, incluindo monitoramento, backup, atualizações automáticas, integração com serviços de segurança e muito mais.

&nbsp;

<div align="center">

![Crie uma VM pt.1](<images/Criar uma VM pt1.png>)

![Crie uma VM pt.2](<images/Criar uma VM pt2.png>)

![Crie uma VM pt.3](<images/Criar uma VM pt3.png>)

![Crie uma VM pt.4](<images/Criar uma VM pt4.png>)

![Crie uma VM pt.5](<images/Criar uma VM pt5.png>)

![Crie uma VM pt.6](<images/Criar uma VM pt6.png>)

![Crie uma VM pt.7](<images/Criar uma VM pt7.png>)

![Crie uma VM pt.8](<images/Criar uma VM pt8.png>)

</div>


Com a máquina virtual criada, precisamos coloca-la em funcionamento, faremos isso através do nosso computador local. Onde abriremos o recurso de Virtual Machine e Selecionaremos conexão por SSH Nativo, neste iremos recuperar alguns comandos e acrescemtar a chave privada para então entrarmos dentro da máquina virtual.

<div align="center">

![Conectar VM pt.1](<images/Conectar VM pt.1.png>)

![Conectar VM pt.2](<images/Conectar VM pt.2.png>)

![Conectar VM pt.3](<images/Conectar VM pt.3.png>)

![Conectar VM pt.4](<images/Conectar VM pt.4.png>)

</div>

### 5. Experimente os Serviços de Armazenamento e Banco de Dados:
   - Crie e gerencie blobs de armazenamento ou crie um banco de dados SQL para começar a armazenar e gerenciar dados na nuvem.

<div align="center">

![BD Azure para MySQL pt.1](<images/BD Azure Para MySQL pt.1.png>)

![BD Azure para MySQL pt.2](<images/BD Azure Para MySQL pt.2.png>)

![BD Azure para MySQL pt.3](<images/BD Azure Para MySQL pt.3.png>)

</div>

&nbsp;

## Principais Conceitos em Resumo

Aqui estão alguns conceitos fundamentais para entender ao trabalhar com Azure:

### 1. **Máquina Virtual (VM)**:
   - Uma VM é uma emulação de um computador físico, hospedada na nuvem. Azure oferece diferentes tipos e tamanhos de VMs para atender às necessidades específicas de computação.

### 2. **Azure Resource Group**:
   - Um grupo de recursos é um contêiner lógico no qual os recursos do Azure são implantados e gerenciados. Agrupar recursos facilita a implantação, gerenciamento e monitoramento deles como uma única unidade.

### 3. **Azure App Service**:
   - Um serviço totalmente gerenciado que permite criar, implantar e dimensionar aplicativos web, móveis, de API ou lógicos rapidamente. Ele oferece integração contínua e entrega contínua (CI/CD) e suporte a vários idiomas e estruturas.

### 4. **Azure Blob Storage**:
   - Um serviço de armazenamento de objetos massivamente escalonável para armazenar grandes quantidades de dados não estruturados, como arquivos de texto ou binários, como imagens e vídeos.

### 5. **Azure SQL Database**:
   - Um serviço de banco de dados relacional totalmente gerenciado, baseado no mecanismo de banco de dados Microsoft SQL Server. Ele oferece recursos de escalabilidade, desempenho e segurança.