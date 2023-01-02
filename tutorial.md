fiz meu readme segguindo o seguinte tutorial e acresentando outras partes que achei interessante deixando o do meu jeito mas se você também quer um README automatizado?
Resolvi fazer isso porque é muito fácil pegar o mesmo que eu peguei como base, e você fica livre para customizar do jeito que quiser a qualquer momento,  creditos ao Nick Gabe(https://github.com/Nick-Gabe) por proporcionar essa automacao no readme, sendo que no perfil dele tem um video ensinando

### Basta seguir estes passos:
- **Fork meu repositório**
  - Em vez de apenas criar um repositório do zero, você precisa usar o meu como modelo. Você pode entrar [neste link](https://github.com/Nick-Gabe/Nick-Gabe/fork) para gerá-lo. Coloque seu nome de usuário do Github como o nome do repositório, assim ele será exibido em seu perfil.
- **Edite o código**
  - Para facilitar a sua vida, o código que escrevi em Javascript já vem pronto, basta você definir as variáveis ​​de ambiente. Eles estão localizados em [.env](/.env), também se você quiser saber o que é cada opção, aqui está o [.env exemplo](/.env.example). Basta modificá-los em .env e seu README automático já começará a funcionar.
- **Instale as dependências**
  - Basta executar "npm install" no seu terminal e ele instalará as dependências que o projeto usa atualmente.

### Personalizando seu README:
- **Não altere o próprio README**
  - Existe um arquivo chamado ["README_TEMPLATE"](./README_TEMPLATE.md), é o arquivo que você deve modificar se quiser fazer alterações em seu Readme.
  - Você pode adicionar substitutos personalizados dentro da [pasta replacers](./src/replacers), você pode imaginar os substitutos como componentes do React, com cada arquivo tendo sua própria coisa para substituir, e o nome do arquivo é o que substituirá.
- **Como testar se está funcionando?**
  - Isso é simples! Depois de criar seu README_TEMPLATE e talvez alguns substitutos personalizados, você só precisa executar `npm start` e seu README será atualizado com as novas informações. Magia, certo?
