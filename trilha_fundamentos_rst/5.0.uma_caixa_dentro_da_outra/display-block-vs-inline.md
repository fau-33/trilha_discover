## display: block vs display:inline

- Como as caixas se comportam em relação as outras
- Comportamento externo das caixas

**block
- Ocupa toda a linha,colocando o próximo elemento abaixo dele
- width e height são respeitados
- padding, margin, border irão funcionar normalmente  

**inline
- Elemento ao lado do outro
- width e height não funcionam
- Somente valores horizontais de margin, padding e border

Exemplos:
block: `<p> <div> <section>` todos os headings `<h1><h2>...`
inline: `<a> <strong> <span> <em>`