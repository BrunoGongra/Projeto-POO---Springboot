Download e Instalação do IntelliJ

	Para este projeto, foi utilizado a IDE IntelliJ, sendo assim, será descrito abaixo seu processo de download e instalação:
1.	Download da IDE IntelliJ IDEA (Community Edition)
    •	Acesse o site oficial da JetBrains para baixar o IntelliJ IDEA: JetBrains IntelliJ IDEA
    •	Na página de download, clique na opção de baixar a versão Community Edition.
    •	Você será redirecionado para a página de download da versão Community Edition. Escolha a opção de download para o seu sistema operacional (Windows, macOS ou Linux). Aguarde o download ser concluído.
2.	Instalação do IntelliJ IDEA (Community Edition)
    •	Após o download, localize o arquivo de instalação baixado.
    •	Siga as instruções do assistente de instalação para o seu sistema operacional.
    •	Durante a instalação, você pode ser solicitado a escolher as configurações de instalação padrão. Você pode optar por aceitar as configurações padrão ou personalizá-las conforme desejar.
    •	Após a conclusão da instalação, abra o IntelliJ IDEA.
3.	Ativação da Licença Gratuita (para Estudantes)
    •	Ao abrir o IntelliJ IDEA pela primeira vez, você pode ser solicitado a ativar a licença.
    •	Como somos alunos da FATEC Arthur de Azevedo da cidade de Mogi Mirim, S.P., estamos usando a versão gratuita. Neste contexto, selecione a opção "Activation Code" e insira o código de ativação fornecido pela JetBrains para alunos da instituição de ensino Fatec Arthur de Azevedo de Mogi Mirim, S.P.
    •	Siga as instruções na tela para concluir a ativação da licença gratuita.

Download e Instalação do Postman

  Para proporcionar uma interface interativa que pudesse ser usada para testar os endpoints da API, (neste caso API RESTful), foi utilizado a ferramenta “Postman”.
1.	Download do Postman
    •	Acesse o site oficial do Postman para baixar o aplicativo: Postman Download
    •	Na página de download, escolha a opção de download para o seu sistema operacional (Windows, macOS ou Linux).
    •	Aguarde o download ser concluído.
2. Instalação do Postman
    •	Após o download, localize o arquivo de instalação baixado.
    •	Siga as instruções do assistente de instalação para o seu sistema operacional.
    •	Durante a instalação, você pode ser solicitado a escolher as configurações de instalação padrão. Você pode optar por aceitar as configurações padrão ou personalizá-las conforme desejar.
    •	Após a conclusão da instalação, abra o aplicativo Postman.
  Com esses passos, você deve conseguir baixar e instalar o IntelliJ IDEA (Community Edition) e o Postman no seu sistema sem problemas.

Spring Initializr

  Esse projeto também contou com a utilização de uma ferramenta chamada Spring Initialzr. 
  O Spring Initializr é uma ferramenta online que permite aos desenvolvedores criarem rapidamente projetos Spring Boot personalizados. Ele oferece uma interface simples onde você pode configurar as dependências, versões do Spring Boot e outras opções do projeto, gerando automaticamente um esqueleto de projeto com as configurações escolhidas, que simplifica o processo de inicialização e configuração de projetos Spring Boot, permitindo que desenvolvedores foquem mais no desenvolvimento de aplicações.
Utilização do Spring Initializr
1.	Acessando o Spring Initializr
    •	Abra um navegador da web e acesse o site oficial do Spring Initializr: https://start.spring.io/
    •	Na página inicial do Spring Initializr, você será apresentado com opções para configurar o seu projeto Spring Boot.
2.	Configuração do Projeto
    •	Escolha as seguintes opções de configuração para o seu projeto:
      o	Project: Selecione "Maven Project" ou "Gradle Project" dependendo da sua preferência de gerenciamento de dependências.
      o	Language: Escolha a linguagem de programação desejada, geralmente Java.
      o	Spring Boot: Escolha a versão do Spring Boot que deseja utilizar. Selecione a versão mais recente disponível, a menos que haja requisitos específicos para uma versão anterior.
      o	Project Metadata: Preencha os campos "Group", "Artifact" e "Name" com informações relevantes para o seu projeto. Esses campos definirão as configurações básicas do seu projeto Spring Boot.
      o	Packaging: Escolha o formato de empacotamento desejado para o seu projeto, geralmente JAR ou WAR.
      o	Java: Selecione a versão do Java que você deseja usar para o desenvolvimento do projeto.
      o	Dependencies: Adicione as dependências de software necessárias para o seu projeto. Isso pode incluir dependências comuns como Spring Web, Spring Data JPA, H2 Database, entre outras, dependendo dos requisitos do seu projeto. Selecione as dependências adequadas para o seu caso de uso.
3.	Gerando o Projeto
  •	Após configurar todas as opções necessárias para o seu projeto, clique no botão "Generate" para gerar o projeto.
  •	O Spring Initializr irá criar um arquivo compactado (ZIP) contendo o esqueleto do seu projeto Spring Boot com as configurações e dependências selecionadas.
4.	Importando o Projeto na IDE
  •	Após baixar o arquivo ZIP gerado pelo Spring Initializr, descompacte-o em um diretório de sua escolha.
  •	Abra a sua IDE de desenvolvimento (como IntelliJ IDEA, Eclipse, etc.).
  •	Importe o projeto recém-criado na IDE seguindo as instruções específicas da sua IDE para importar um projeto Maven ou Gradle.
  •	Aguarde a IDE carregar e configurar o projeto.
5.	Configurações Adicionais
  •	Dependendo das necessidades do seu projeto, você pode precisar realizar configurações adicionais, como configurar o banco de dados, ajustar as propriedades do Spring Boot no arquivo application.properties ou application.yml, adicionar novas classes, etc.
  •	Consulte a documentação do Spring Boot e das bibliotecas adicionais que você está utilizando para obter informações sobre configurações avançadas e personalizações.
Com esses passos, você deve conseguir criar e configurar um novo projeto Spring Boot usando o Spring Initializr. Certifique-se de revisar as dependências e configurações do projeto para garantir que atendam às necessidades do seu aplicativo. 

Configurando o Ambiente de Desenvolvimento para Executar a Aplicação

Configuração do Ambiente

1.	Instale o Java 17 ou superior:
  o	Verifique se o Java está instalado no seu sistema abrindo um terminal e digitando java -version.
  o	Caso não esteja instalado, baixe a versão mais recente do Java do site oficial (https://www.oracle.com/java/technologies/javase-jdk17-downloads.html) e siga as instruções de instalação fornecidas para seu sistema operacional.
2.	Configuração do arquivo application.properties ou application.yml:
  o	No diretório src/main/resources, localize o arquivo application.properties ou application.yml.
  o	Configure as propriedades do banco de dados para o H2 Database, um banco de dados em memória. Você pode adicionar as seguintes linhas ao arquivo de configuração: 
  o Essas configurações configuram o H2 Database como banco de dados padrão para a aplicação, usando uma instância em memória.

Compilação e Execução da Aplicação

1.	Abra seu ambiente de desenvolvimento:
  o	Utilize uma IDE como IntelliJ IDEA ou Eclipse para abrir seu projeto Spring Boot.
2.	Compilar a aplicação:
  o	No IntelliJ IDEA, você pode compilar o projeto clicando em Build > Build Project no menu superior.
  o	No Eclipse, você pode compilar o projeto clicando com o botão direito do mouse no projeto e selecionando Run As > Maven install (para projetos Maven) ou Run As > Gradle Build (para projetos Gradle).
3.	Executar a aplicação:
  o	No IntelliJ IDEA, execute o projeto clicando em Run > Run no menu superior ou clicando no ícone de execução verde.
  o	No Eclipse, clique com o botão direito do mouse no projeto e selecione Run As > Spring Boot App.
4.	Verifique se a aplicação está em execução:
  o	Após iniciar a aplicação, verifique o console da IDE para garantir que não há erros.
  o	A aplicação Spring Boot geralmente estará disponível em http://localhost:8080 por padrão.
Seguindo essas instruções, é esperado que você consiga configurar e executar a aplicação utilizando o H2 Database como banco de dados.

