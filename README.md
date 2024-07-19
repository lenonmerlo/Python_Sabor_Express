# Sistema de Gerenciamento de Restaurantes

Este projeto foi desenvolvido por Lenon Merlo, com a tutoria de [Guilherme Lima](https://www.linkedin.com/in/guilherme-lima-developer/) da [Alura](https://alura.com.br/). O sistema permite gerenciar restaurantes, oferecendo funcionalidades para cadastrar novos restaurantes, listar restaurantes cadastrados e alternar o estado de cada restaurante (ativo/inativo).

## Funcionalidades

- **Cadastrar Restaurante:** Permite adicionar novos restaurantes à lista com nome e categoria.
- **Listar Restaurantes:** Exibe todos os restaurantes cadastrados com suas informações.
- **Alternar Estado do Restaurante:** Permite ativar ou desativar um restaurante cadastrado.

## Estrutura do Código

O código é organizado em funções, cada uma responsável por uma funcionalidade específica:

- `exibir_nome_do_programa()`: Exibe o nome do programa de forma estilizada.
- `exibir_opcoes()`: Exibe as opções do menu principal.
- `finalizar_app()`: Finaliza a aplicação.
- `voltar_ao_menu_principal()`: Retorna ao menu principal após uma ação.
- `opcao_invalida()`: Trata entradas inválidas do usuário.
- `exibir_subtitulo(texto)`: Exibe um subtítulo estilizado.
- `cadastrar_novo_restaurante()`: Cadastra um novo restaurante.
- `listar_restaurantes()`: Lista todos os restaurantes cadastrados.
- `alternar_estado_restaurante()`: Alterna o estado de um restaurante entre ativo e inativo.

## Como Executar

1. Certifique-se de ter o Python instalado em sua máquina.
2. Clone este repositório.
3. Execute o arquivo `app.py` com o comando `python app.py`.

## Exemplo de Uso

```bash
$ python app.py
