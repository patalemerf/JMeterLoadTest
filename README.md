# Lojinha teste de performance com Apache JMeter

Esse é um repisitório que contém alguns testes de API Rest de um software denominado Lojinha. Os sub tópicos abaixo descreve algumas decisões tomadas na estruturação do projeto.
## Descrição
Este projeto utiliza Apache JMeter para realizar testes de performance. O plano de teste realiza login e o cadastro de um produto através de requisições HTTP.

## Estrutura do Projeto
Test Plan: Simula um grupo de usuários que faz login e cadastra produtos.
Relatórios: Relatórios de desempenho são gerados automaticamente após a execução.

## Pré-requisitos
Apache JMeter: Faça o download do Apache JMeter e extraia-o no seu sistema.
JMeter Plugins Manager (opcional): Recomendamos o uso do JMeter Plugins Manager para visualizar melhor os resultados e gerar relatórios mais detalhados.

## Configuração
Configuração do CSV: Certifique-se de que o arquivo CSV com as credenciais de login e dados de produtos está corretamente localizado no caminho especificado no plano de teste.
Configuração do JMeter: Configure o JMeter no seu ambiente e abra o arquivo .jmx através da interface gráfica do JMeter.

## Executando os Testes
Abra o JMeter e carregue o arquivo .jmx.
Execute o teste clicando no botão Iniciar.
Os resultados serão exibidos na visualização "View Results Tree" e no "Summary Report". Use o JMeter Plugins Manager para relatórios mais avançados.
