# A Esperança — Jovens Adventistas Cidade da Esperança

Site de convite interativo com tema Copa do Mundo 2026, criado para ser compartilhado via QR Code.

## Como funciona

O usuário acessa o link/QR Code e passa por uma experiência em 4 etapas:

1. **Tela de recompensa** — chamada para resgatar um convite especial
2. **Pacote Panini** — pacote estilo Copa 2026 para ser aberto
3. **Figurinhas** — 6 cartas com atributos de Cristo (Amor, Graça, Paz, Poder, Fidelidade, Esperança) + a carta especial do Jesus
4. **Mensagem** — texto "A Nossa Única Esperança" com versículo de João 14:1-3 e chamada para fazer parte do grupo

## Arquivos

```
index.html       → site completo (HTML + CSS + JS em um único arquivo)
carta-Gzus.jpeg  → imagem da figurinha especial do Jesus
vercel.json      → configuração de deploy na Vercel
```

## Deploy na Vercel

1. Faça o push para o GitHub
2. Acesse [vercel.com](https://vercel.com) e importe o repositório
3. Clique em **Deploy** — nenhuma configuração adicional necessária

## Personalização

Dentro do `index.html`, os pontos de ajuste estão comentados:

| O que mudar | Onde encontrar |
|---|---|
| Link do botão CTA | `href="https://linktr.ee/adventistasesperanca..."` |
| Texto da mensagem | Seção `msg-body` no HTML |
| Rodapé | Tag `<footer class="ft">` |
| Imagem da carta | Substituir `carta-Gzus.jpeg` |
