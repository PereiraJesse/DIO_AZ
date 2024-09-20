# DIO_AZ
Diretório temporário 


**Resumo sobre Azure: Criando uma Conta de Armazenamento e Aplicações**

O Azure é a plataforma de nuvem da Microsoft, que oferece uma variedade de serviços para criar, gerenciar e implantar aplicações. Vou te explicar como criar uma conta de armazenamento e como desenvolver aplicações no Azure, além de falar sobre alguns tipos de serviços disponíveis.

### Criando uma Conta de Armazenamento no Azure

1. **Acessar o Portal do Azure**: Primeiro, você precisa acessar o [Portal do Azure](https://portal.azure.com/).
2. **Criar um Grupo de Recursos**: Antes de criar a conta de armazenamento, é recomendável criar um grupo de recursos. Isso ajuda a organizar seus recursos. No portal, vá em "Grupos de Recursos" e clique em "Adicionar".
3. **Criar a Conta de Armazenamento**:
   - No portal, procure por "Contas de Armazenamento" e clique em "Adicionar".
   - Preencha as informações necessárias, como nome da conta, região e tipo de desempenho (Standard ou Premium).
   - Escolha o tipo de redundância (LRS, GRS, RA-GRS, etc.), que define como seus dados serão replicados.
   - Clique em "Revisar + Criar" e depois em "Criar".

### Criando Aplicações no Azure

1. **Escolher o Serviço**: O Azure oferece vários serviços para hospedar suas aplicações, como Azure App Service, Azure Functions, e Azure Kubernetes Service (AKS).
2. **Azure App Service**:
   - Ideal para hospedar aplicações web e APIs.
   - No portal, procure por "App Services" e clique em "Adicionar".
   - Preencha as informações da aplicação, como nome, sistema operacional (Windows ou Linux) e plano de serviço.
   - Clique em "Revisar + Criar" e depois em "Criar".
3. **Azure Functions**:
   - Usado para executar pequenos pedaços de código (funções) sem gerenciar a infraestrutura.
   - No portal, procure por "Functions" e clique em "Adicionar".
   - Preencha as informações necessárias e escolha um plano de hospedagem.
   - Clique em "Revisar + Criar" e depois em "Criar".
4. **Azure Kubernetes Service (AKS)**:
   - Ideal para aplicações em contêineres.
   - No portal, procure por "Kubernetes services" e clique em "Adicionar".
   - Preencha as informações do cluster, como nome, região e configuração do nó.
   - Clique em "Revisar + Criar" e depois em "Criar".

### Tipos de Serviços no Azure

Resumo do aprendiado 

- **Computação**: Máquinas Virtuais, App Services, Functions, AKS.
- **Armazenamento**: Contas de Armazenamento, Blobs, Files, Discos.
- **Banco de Dados**: Azure SQL Database, Cosmos DB, MySQL, PostgreSQL.
- **Rede**: Virtual Network, Load Balancer, VPN Gateway.

De forma bem resumida, isso foi o que consegui captar na aula, acredito que são os pontos mais imporante anotados por mim. 



Identidade, acesso e segurança


Oi, pessoal! Hoje eu vou falar um pouco sobre **Identidade, Acesso e Segurança** no mundo do Azure. Eu ainda estou aprendendo, então vou tentar explicar de um jeito simples, ok?

### Identidade
No Azure, a identidade é tipo o nosso RG ou CPF. É como o sistema sabe quem somos. A gente usa o **Azure Active Directory (AAD)** para gerenciar essas identidades. Com o AAD, a gente pode criar contas de usuário e grupos, e dar permissões específicas para cada um. Isso ajuda a manter tudo organizado e seguro.

### Acesso
Acesso é sobre quem pode fazer o quê. No Azure, a gente usa o **Role-Based Access Control (RBAC)**. Com o RBAC, a gente pode dar diferentes níveis de acesso para diferentes pessoas. Por exemplo, um administrador pode fazer tudo, mas um leitor só pode ver as informações, sem mudar nada. Isso é importante para garantir que só as pessoas certas possam acessar e modificar os recursos.

### Segurança
Segurança é super importante no Azure. A gente tem várias ferramentas para proteger nossos dados e recursos. Uma delas é o **Azure Security Center**, que ajuda a monitorar e proteger o ambiente. Ele dá dicas de como melhorar a segurança e avisa se algo estranho estiver acontecendo. Outra ferramenta legal é o **Azure Key Vault**, onde a gente guarda senhas e chaves de criptografia de forma segura.

### Conclusão
Então, resumindo, no Azure a gente usa o AAD para gerenciar identidades, o RBAC para controlar o acesso e várias ferramentas para garantir a segurança. Ainda estou aprendendo, mas já dá pra ver que o Azure tem muitas coisas legais para ajudar a gente a manter tudo seguro e organizado.

