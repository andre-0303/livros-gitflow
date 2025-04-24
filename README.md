# Livros Divertidos

Este é um projeto simples desenvolvido como atividade prática da disciplina técnica **Laboratório de Software**, com foco no uso de **Gitflow** e da **Fetch API**. O objetivo é criar uma página web que exibe uma lista de livros aleatórios obtidos da API Gutendex.

## Descrição do Projeto

A aplicação consiste em uma página HTML que utiliza JavaScript para buscar dados de livros da API pública [Gutendex](https://gutendex.com/) e exibi-los em uma lista. O projeto foi estruturado seguindo boas práticas de controle de versão com Gitflow.

### Funcionalidades
- Exibe os 5 primeiros livros retornados pela API Gutendex.
- Mostra o título do livro e o nome do autor (ou "Autor desconhecido" caso o autor não esteja disponível).
- Tratamento básico de erros no console em caso de falha na requisição.

## Tecnologias Utilizadas
- **HTML**: Estrutura da página.
- **JavaScript**: Lógica para buscar e exibir os dados usando a Fetch API.
- **API Gutendex**: Fonte dos dados dos livros.
- **Git/GitHub**: Controle de versão utilizando a estratégia Gitflow.

## Estrutura do Repositório
```
├── index.html       # Arquivo principal da página
├── script.js        # Script para buscar e exibir os livros
└── README.md        # Este arquivo
```

## Como Executar o Projeto
1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/livros-divertidos.git
   ```
2. Abra o arquivo `index.html` em um navegador web moderno.
3. Certifique-se de estar conectado à internet para que a Fetch API possa buscar os dados da Gutendex.

## Fluxo de Trabalho com Gitflow
Este projeto utiliza o **Gitflow** como estratégia de branching:
- **main**: Contém a versão estável do projeto.
- **develop**: Contém as últimas alterações em desenvolvimento.
- **feature branches**: Usadas para desenvolver novas funcionalidades (ex.: `feature/fetch-api`).
- **release branches**: Preparação para uma nova versão estável.
- **hotfix branches**: Correções rápidas na branch `main`.

Exemplo de criação de uma feature:
```bash
git checkout develop
git checkout -b feature/nova-funcionalidade
# Desenvolva a funcionalidade
git add .
git commit -m "feat: adiciona nova funcionalidade"
git push origin feature/nova-funcionalidade
```

## Atividade Prática
Esta aplicação foi desenvolvida como parte da disciplina **Laboratório de Software**, com o objetivo de praticar:
- Integração com APIs externas usando Fetch.
- Estruturação de projetos com HTML e JavaScript.
- Gerenciamento de versionamento com Gitflow.

## Contribuições
Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias ou correções!

## Licença
Este projeto é de uso livre para fins educacionais.
