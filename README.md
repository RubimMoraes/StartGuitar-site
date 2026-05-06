# StartGuitar

StartGuitar é uma plataforma web para iniciantes no violão, criada para guiar o aluno do primeiro contato com o instrumento até as primeiras músicas. O site combina uma apresentação visual elegante, conteúdos de teoria musical e ferramentas práticas de treino em uma experiência simples de navegar.

## Sobre o projeto

O objetivo do StartGuitar é oferecer um caminho inicial estruturado para quem quer aprender violão no próprio ritmo. A interface apresenta uma página inicial com chamada para começar os estudos, uma área de teoria musical organizada por assuntos e uma área de treino com recursos interativos.

O design usa uma estética escura com destaque em tons dourados, tipografia refinada e navegação fluida entre as seções principais.

## Funcionalidades

- Página inicial com apresentação do método e chamada para iniciar os estudos.
- Navegação entre as áreas de Início, Treino e Teoria.
- Setas laterais para avançar ou voltar entre as telas.
- Ferramenta de acordes com diagramas visuais para acordes maiores e menores.
- Treino de ouvido com reprodução de notas e escolha da resposta correta.
- Metrônomo interativo com ajuste de BPM, compasso e presets.
- Área de teoria musical com tópicos organizados por categoria.
- Conteúdo sobre notas musicais, partes do violão, afinação, intervalos, escalas, formação de acordes e progressões harmônicas.
- Layout responsivo para desktop e dispositivos móveis.

## Estrutura das telas

### Início

A tela inicial apresenta a proposta do site: aprender violão do zero, no seu ritmo. Ela traz botões para começar pela teoria musical ou acessar diretamente as ferramentas de treino.

### Treino

A área de treino reúne três ferramentas:

- **Acordes:** exibe diagramas de acordes básicos, com filtros por categoria.
- **Ouvido:** toca notas musicais para o usuário identificar, mostrando acertos e taxa de desempenho.
- **Metrônomo:** permite controlar BPM, compasso e presets de velocidade.

### Teoria

A área de teoria musical organiza conteúdos fundamentais para iniciantes, incluindo introdução à música, funcionamento do violão, harmonia e formação de acordes.

## Como abrir

Depois de baixar ou clonar o projeto, abra o arquivo `index.html` no navegador.

Também é possível rodar como servidor local:

```bash
python -m http.server 4173
```

Depois acesse:

```text
http://127.0.0.1:4173/
```

## Tecnologias

- HTML
- CSS
- JavaScript
- React empacotado em build estático

## Observação

Este projeto é uma versão estática do site StartGuitar, preparada para funcionar localmente e ser publicada em repositórios ou hospedagens estáticas.
