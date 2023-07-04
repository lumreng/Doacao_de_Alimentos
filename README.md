# Projeto de Doação de Alimentos

O projeto foi desenvolvido durante as aulas do curso Jovem Programador, ministrado na cidade de Chapecó-SC e oferecido pelo SENAC. (www.jovemprogramador.com.br)

## Objetivos

Desenvolver um software, em linguagem JAVA, de cunho social. Com isto, eu e meu grupo desenvolvemos um programa para ajudar na doação de alimentos. O objetivo é facilitar a doação de alimentos onde o doador poderá doar diretamente para famílias cadastradas e/ou empresas que se cadastraram para serem pontos de coleta de alimentos.

## Tecnologias

- Linguagem JAVA
- Banco de Dados PostgreSQL
- API Gráfica JAVA Swing
- IDE Netbeans

## Tela Principal

Na tela principal temos os principais botões de navegação onde o usuário (Família ou Empresa) pode se cadastrar ou ir a procura de uma família ou ponto de doação para doar seu alimento.

## Cadastros e Login

Temos duas telas de cadastro, uma para a família e outra para empresas. A única diferença é o CPF (família) e o CNPJ (empresa).
Estes dados serem importantes para logar! juntamente, é claro, da senha.

Nestas telas foram usadas máscaras para facilitar o armazenamento de dados no banco de dados e validações. Tudo para não bagunçar o banco de dados ou cadastrar algum usuário sem preencher algum campo ou utilizar algum dado "errado".

Já nas telas de login, verificamos se o CPF/CPNJ e a senha dão match no banco de dados! Se sim, os dados desse usuário são 'levados' para as próximas telas. Se não, uma mensagem de erro é mostrada. 

## Tela Principal da Família

Depois de fazer o login, o representando da família que está cadstrado no sistema pode alterar ou excluir seus dados. Uma funcionalidade única desta tela é a possibilidade de adicionar qual alimento esta família
esta necessitando. Esta lista de necessidades são mostradas tanto aqui, quanto na tela de 'Famílias Cadastradas'.

## Famílias Cadastradas

Tela onde podemos achar informações de famílias que necessitam de sua doação, assim como uma lista de alimentos que esta família ficaria feliz de receber.

## Pontos de Doações

Aqui podemos ver quais empresas estão cadastradas no sistema, obtendo infomações de localização e contato. Não deixe de doar!
