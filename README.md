# Álbum Bíblico — A Seleção de Cristo

Página de vendas estática pronta para publicar no GitHub e conectar com a Vercel.

## O que foi atualizado

- A seção **Prévia interativa** foi atualizada com a nova prévia do álbum **Valentes na Fé**.
- As 7 páginas enviadas foram colocadas na mesma ordem solicitada.
- A prévia agora permite **folhear pelas setas** e também **arrastar para os lados** para simular a virada de página.
- As imagens da prévia estão **incorporadas dentro do próprio `index.html`**, então você continua podendo subir somente `index.html` e `README.md` para o GitHub.

## Arquivos do projeto

- `index.html` — página principal com HTML, CSS e JavaScript em um único arquivo.
- `README.md` — instruções de uso e publicação.

## Como publicar no GitHub

1. Crie um repositório novo no GitHub.
2. Envie os arquivos `index.html` e `README.md` para a raiz do repositório.
3. Faça o commit das alterações.

## Como conectar na Vercel

1. Acesse sua conta na Vercel.
2. Clique em **Add New Project**.
3. Importe o repositório do GitHub.
4. Em framework, deixe como **Other** ou **Static HTML**.
5. Não é necessário configurar build command.
6. Publique o projeto.

## Observações importantes

- A página ainda usa algumas imagens externas que já existiam no seu HTML original.
- A nova prévia do álbum **Valentes na Fé** foi embutida diretamente no `index.html`.
- O botão de compra aponta para o checkout:
  `https://checkout.pague-cerebroemjogo.shop/VCCL1O8SD1RR`
- Caso queira trocar o link de pagamento, procure por esse endereço dentro do `index.html` e substitua pelo novo link.

## Estrutura recomendada no GitHub

```text
album-biblico/
├── index.html
└── README.md
```
