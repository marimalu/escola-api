# Escola-API

Projeto criado para desenvolvimento na disciplina de Programação Orientada a Serviços.

## Descrição
O projeto da escola é constituído por três serviços que se comunicam entre si. São estes:
- O serviço da **Escola**, que é responsável por disponibilizar o cadastro de alunos, professores e turmas;
- O serviço da **Biblioteca**, que é encarregado de manter o registro de controle de empréstimo de livros por parte dos usuários, podendo ser esses não só os alunos e professores da escola, mas também pessoas de fora;
- O serviço de **Autenticação**, que tem como intuito armazenar as credenciais dos usuários, tanto da Escola como da Biblioteca.

## Como executar
O projeto foi criado com auxílio do framework da linguagem PHP [Laravel](https://laravel.com/docs/10.x), portanto será necessário digitar o seguinte comando no terminal a fim de executá-lo:

```
php artisan serve --port=1234
```
