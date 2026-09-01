# Finanças

App de orçamento pessoal: potes, cartões, dívidas e projeção mês a mês.

Página única, sem backend. Os dados **não** ficam aqui: cada save grava um `state.json`
num repositório privado separado, via API do GitHub, usando um token que fica guardado
apenas no navegador de cada aparelho. Este repositório é só o código.

## Uso

1. Abra a página.
2. Em **Sincronização**, cole um fine-grained token com acesso de leitura e escrita
   ao repositório de dados e clique em Conectar.
3. No celular, "Adicionar à tela inicial" instala como app.
