<h1 align="center">Projeto "Passa ou Repassa"</h1>

Este é um projeto de um jogo de perguntas e respostas, inspirado no clássico jogo de perguntas "Passa ou Repassa". O objetivo do projeto é permitir que os jogadores escolham o nível de dificuldade das perguntas e façam um sorteio para responder questões relacionadas a diversos temas, com diferentes níveis de dificuldade.

## Tecnologias Utilizadas

- **HTML**: Estruturação das páginas.
- **CSS**: Estilização das páginas para uma aparência moderna e responsiva.
- **JavaScript**: Para interatividade e sorteio das perguntas.
- **Google Fonts**: Para a utilização da fonte "Poppins" no design do site.

## Funcionalidades

1. **Página Principal (`index.html`)**: Página de introdução com um botão "Vamos jogar", que leva o jogador à página de seleção de dificuldades.
   
2. **Seleção de Dificuldade (`dificuldade.html`)**: Onde o jogador pode escolher entre 4 níveis de dificuldade: 
   - Fácil
   - Médio
   - Difícil
   - Aleatório
   
3. **Sorteio de Perguntas**: Ao clicar no botão de sorteio, o sistema escolhe aleatoriamente uma pergunta do nível selecionado e a exibe em um prompt, junto com suas alternativas (A, B, C, D).

## Como Usar

1. Clone o repositório ou baixe os arquivos do projeto.
2. Abra o arquivo `index.html` no seu navegador.
3. Clique no botão **"Vamos jogar"** para ser direcionado à página de seleção de dificuldades.
4. Escolha o nível de dificuldade desejado.
5. Clique no botão **"Sorteio"** para visualizar a pergunta e as opções.

## Estrutura de Pastas

```
/PassaOuRepassa
├── index.html              # Página principal
├── dificuldade.html        # Página de seleção de dificuldade
├── css/
│   ├── styles.css          # Arquivo CSS com os estilos do site
├── js/
│   ├── scripts.js          # Arquivo JavaScript com a lógica de sorteio
├── perguntas.json          # Arquivo com as perguntas divididas por dificuldade
└── README.md               # Este arquivo
```

## Como Contribuir

1. Fork este repositório.
2. Crie uma branch para suas alterações (`git checkout -b feature/nova-funcionalidade`).
3. Commit suas alterações (`git commit -m 'Adicionando nova funcionalidade'`).
4. Push para a branch (`git push origin feature/nova-funcionalidade`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT).
