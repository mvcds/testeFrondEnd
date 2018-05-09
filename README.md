# testeFrondEnd
Repositório para teste


O layout será enviado pelo e-mail.
Fork esse repositório e, após terminar, faça um pull request.

A ideia é desenvolver o layout do Zeplin sem cabeçalho e rodapé. Responsivo. E que as informações da página sejam dinâmicas, carregadas de um arquivo externo (JSON)
As informações podem ser aleatórias

## Checklist

- [X] Versão mobile
- [ ] No mobile (e tablet) o background de beneficios pode ser usado?
- [ ] Aplicar carrosel nos beneficios do mobile? Talvez também no clube wine?
- [ ] Arrumar tamanho de imagens no mobile
- [ ] Versao tablet
- [ ] Versão do zeplin
- [ ] Arrumar media queries
- [ ] Informações carregadas através de um JSON

## O que eu fiz

Usei o chrome pra desenvolver, só espero que funcione nele, pois considerei o tempo curto (devido à ser no meio da semana)

Para testes manuais no mobile, usei meu S8 para acessar https://mvcds.github.io/testeFrondEnd

### Estilo

0. Comecei com CSS puro, pois não sabia se eu pudia usar um preprocessador, mas depois pensei que fica um teste mais bonitinho usando algo do genero
1. Instalei o stylus :heart: via `npm install stylus -g`
2. Durante o ciclo de desenvolvimento estou rodando `stylus -w src/style/style.styl -o ./style.css`
3. Como a minha folha de estilo é gerada automaticamente, trato ela como um arquivo binário via *.gitattributes*
4. Para me auxiliar a estruturar o stylus, gosto de usar um mixto de ITCSS, BEM e atomic design, junto com estilização de componentes (quando usando um framework como o React)
