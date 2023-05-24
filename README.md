# Projeto html_controle_passagem

Este projeto Java Web Maven com o Tomcat é uma aplicação de controle de voo usando RMI. Ele contém interfaces gráficas em HTML para verificar o status e marcar voos.

## Estrutura do Projeto

O projeto possui a seguinte estrutura:

- `src/main/webapp/` : Contém os arquivos HTML para as páginas e formulários da aplicação.
  - `FrmVerificarStatus.html` : Formulário para verificar o status de um voo.
  - `FrmMarcarVoo.html` : Formulário para marcar um voo.
  - `VerificarStatus.html` : Página de resposta para exibir o status de um voo.
  - `MarcarVoo.html` : Página de resposta para confirmar a marcação do voo.
  - `index.html` : Página inicial que funciona como um menu para acessar os formulários.

## Como executar o projeto

1. Certifique-se de ter o Apache Tomcat e o Maven instalados no seu sistema.
2. Clone o repositório do projeto ou faça o download dos arquivos.
3. Navegue até o diretório raiz do projeto.
4. Execute o comando `mvn tomcat7:run` para iniciar o servidor Tomcat embutido.
5. Abra um navegador e acesse `http://localhost:8080/html_controle_passagem` para acessar o menu principal.

Certifique-se de que o servidor Tomcat esteja em execução antes de executar o projeto.

## Contribuição

Este projeto foi desenvolvido como parte de uma aula e não aceitamos contribuições neste momento.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
