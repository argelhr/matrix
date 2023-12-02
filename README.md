# Projeto de Animação Matrix Rain

## Visão Geral

Este projeto cria uma animação de chuva Matrix usando HTML, CSS e JavaScript. A animação exibe caracteres caindo, lembrando o icônico efeito de "chuva digital" visto no filme "Matrix". Os caracteres são uma mistura de símbolos alfanuméricos aleatórios e a sigla "CSTSI".

## Sumário

- [Introdução](#projeto-de-animação-matrix-rain)
- [Uso](#uso)
- [Estrutura do Código](#estrutura-do-código)
- [Licença](#licença)

## Uso

Para utilizar esta animação de chuva Matrix em seu projeto:

1. Copie o código HTML para o seu arquivo HTML.
2. Certifique-se de que o script `main.js` está corretamente referenciado e localizado na pasta `src`.
3. Abra o arquivo HTML em um navegador da web para visualizar a animação de chuva Matrix.

## Estrutura do Código

### Estrutura HTML

O arquivo HTML inclui um elemento canvas para renderizar a animação. O script está vinculado ao arquivo `main.js`.

### Estilos CSS

Os estilos CSS definem a cor de fundo, posição do canvas e garantem que o canvas cubra toda a área visível.

### JavaScript (main.js)

- **Inicialização do Canvas:** O script inicializa o canvas e seu contexto 2D.
- **Arrays de Caracteres:** Dois arrays (`letras` e `CSTSI`) contêm caracteres para geração aleatória na animação.
- **Loop de Animação:** A função `loop` gerencia os quadros da animação, atualizando o canvas com caracteres em queda.


---