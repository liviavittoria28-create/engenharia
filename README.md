# Portugol World: A Jornada de Esperioux

Projeto de estudo de lógica de programação no formato de jogo. O conteúdo é um mapa com 11 "casas" de lições e uma torre final. Cada casa tem explicação passo a passo e um quiz, e acertar o quiz abre a próxima. O guia é o Esperioux, um robô companheiro de estudos.

**Demonstração:** [liviavittoria28-create.github.io/engenharia](https://liviavittoria28-create.github.io/engenharia/) · **Autora:** [Lívia Vittoria](https://github.com/liviavittoria28-create)

![Tela inicial do Portugol World](docs/screenshot.jpg)

---

## Objetivo

Reunir os fundamentos de lógica de programação num material de estudo interativo, útil para revisão própria e para outros iniciantes.

## Problema que resolve

Os primeiros conceitos de programação costumam ser apresentados em listas de exercícios soltas e sem retorno imediato. O Portugol World organiza o conteúdo em sequência, mostra o progresso (XP, casas desbloqueadas e vidas) e corrige os exercícios na hora.

## Conteúdo

| Casa | Tema |
|---:|---|
| 1 | O que é um algoritmo |
| 2 | Como construir um algoritmo (entrada, processamento e saída) |
| 3 | Formas de representar: narrativa, fluxograma e Portugol |
| 4 | Variáveis |
| 5 | Tipos de dados |
| 6 | Sequência e operações |
| 7 | Decisões (`se` / `senao`) |
| 8 | Repetições (`enquanto`, `para`) |
| 9 | Problemas reais |
| 10 | Teste de mesa |
| 11 | Guia de bolso (resumo) |
| 👑 | Torre do BOSS: 10 desafios de código em Portugol |

## Funcionalidades

- Mapa de progresso com casas bloqueadas e desbloqueadas.
- Quiz em cada casa, com XP e vidas.
- Desafios de código corrigidos por uma rubrica local, que confere com expressões regulares se o código atende a cada critério do enunciado.
- Progresso salvo no `localStorage` do navegador.
- Layout adaptado ao celular, com zoom permitido.

## Tecnologias

HTML5, CSS3 e JavaScript puros, num único arquivo e sem dependências. Os cenários (céu, nuvens, casas e estrada) são desenhados em CSS, sem imagens.

## Estrutura de pastas

```
index.html        jogo completo (estrutura, estilos e scripts)
docs/
  screenshot.jpg  captura usada neste README
```

## Como executar

Abra `index.html` no navegador. Não precisa de instalação nem de servidor.

Não há variáveis de ambiente nem banco de dados.

## Testes

Não há testes automatizados. Verificação manual feita em 17/11/2026 no Chrome: a página carrega sem erros de JavaScript, os 10 desafios da torre aparecem e a correção pela rubrica local funciona.

## Limitações conhecidas

- O progresso fica só no navegador em que foi feito.
- A rubrica local avalia padrões no texto do código. Ela não executa o programa, então uma solução correta escrita de forma muito diferente pode não ser reconhecida.
- A correção por IA (Dify) está desativada: a chave de acesso não pode ficar no navegador, onde qualquer visitante conseguiria copiá-la.

## Melhorias futuras

- Reativar a correção por IA por meio de um servidor intermediário que guarde a chave.
- Um interpretador de Portugol no navegador, para executar o código do aluno.
- Separar HTML, CSS e JavaScript em arquivos próprios.

---

Desenvolvido por **Lívia Vittoria** · [Portfólio](https://liviavittoria28-create.github.io) · [LinkedIn](https://www.linkedin.com/in/livia-vittoria-732b8a430/)
