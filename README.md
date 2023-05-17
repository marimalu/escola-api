# Escola-API

Projeto criado para desenvolvimento na disciplina de Programação Orientada a Serviços.

## Descrição
O projeto da escola é constituído por três serviços que se comunicam entre si. São estes:
- O serviço da **Escola**, que é responsável por disponibilizar o cadastro de alunos, professores e turmas;
- O serviço da **Biblioteca**, que é encarregado de registrar o controle de empréstimo de livros dos usuários, podendo ser esses não só os alunos e professores da escola, mas também pessoas de fora;
- O serviço de **Autenticação**, que tem como intuito armazenar as credenciais dos usuários, tanto da Escola como da Biblioteca.

## Como executar
O projeto foi desenvolvido na linguagem [PHP](https://www.php.net/), com auxílio do framework [Laravel](https://laravel.com/docs/10.x). É necessário que o PHP e o [Composer](https://getcomposer.org/) estejam instalados e configurados em sua máquina. Dado isso, a fim de executar o projeto corretamente, utilize os seguintes comandos no terminal:

1. Execute o comando do Composer para fazer o download das dependências e aguarde a instalação ser concluída.
```
composer update
```

2. Execute o comando do artisan para ligar o servidor. Note que em ```<port>``` deve ser inserido quatro números à sua escolha.
```
php artisan serve --port=<port>
```
