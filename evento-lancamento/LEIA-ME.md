# E-mail Marketing — Elo 28 · A noite de lançamento

E-mail **institucional / retrospectiva do evento de lançamento** do Elo 28. Conta a noite pela ordem em que ela aconteceu (chegada → apresentação no palco → homenagens → show → time Bilfor) e fecha com um convite comercial leve: falar com um assessor.

Segue a mesma identidade dos e-mails anteriores do Elo 28: fundo bege `#F4EFE7`, container branco de 600px, tipografia **Quattrocento Sans**, kickers em dourado `#C98A3E`, botão âmbar `#FFBF6F` e texto em marrom `#260D03` / `#4A3B33`.

## Ritmo visual (por que ele não é um e-mail "de blocos iguais")

| # | Bloco | Tratamento |
|---|---|---|
| 1 | Hero | Foto do salão lotado, scrim + headline embutida e pill "LANÇAMENTO" |
| 2 | Abertura | Fundo branco, texto respirado + faixa creme com os dados do produto |
| 3 | No palco | Foto larga com cantos arredondados sobre branco |
| 4 | Reconhecimento | Grid de 2 colunas (empilha no mobile) |
| 5 | Show | **Faixa marrom escuro `#260D03`** — quebra total de contraste, clima de noite |
| 6 | Time | Foto full-bleed com texto embutido |
| 7 | CTA | Card creme arredondado, botão âmbar + link secundário |
| 8 | Rodapé | Lockup Elo 28 · Bilfor + legal |

## Arquivos desta pasta

| Arquivo | O que é |
|---|---|
| `email-evento-lancamento.html` | O e-mail (HTML de tabelas + CSS inline, Gmail/Outlook/Apple Mail) |
| `hero-evento.jpg` | Hero 1200×800 — salão lotado com o Elo 28 no telão |
| `palco-apresentacao.jpg` | 1200×700 — apresentação no palco com o telão Bilfor |
| `premiacao-01.jpg` / `premiacao-02.jpg` | 560×560 cada — homenagens no palco |
| `show-encerramento.jpg` | 1200×620 — banda Sr. Bonifácio |
| `time-bilfor.jpg` | 1200×720 — time no backdrop, com "Feito por gente, para gente." embutido |
| `footer-logos.png` | Lockup do rodapé (cópia do que já está no repositório) |
| `_preview-local.html` | Versão só para abrir no navegador com as imagens locais — **não é essa que vai pro RD** |

**Peso total das imagens: ~690 KB** — dentro do que Gmail e Outlook carregam sem cortar.

### Fotos usadas (originais)
`BILFOR-348` (hero) · `BILFOR-418` (palco) · `BILFOR-548`, `BILFOR-549` (reconhecimento) · `BILFOR-570` (show) · `BILFOR-564` (time).
Ficaram de fora `BILFOR-1`, `BILFOR-543` e `BILFOR-583` (eram as polaroids, removidas a pedido), `BILFOR-515` (tabela de venda direta — mostra valores em close) e `BILFOR-556` (redundante com a foto do palco).

## Assunto e preview text (RD Station)

**Assunto:**
> Foi assim a noite de lançamento do Elo 28

**Preview text (preheader):**
> Casa cheia, telão aceso e boa parte das unidades vendida na mesma noite. Reveja o lançamento do Elo 28.

**Variações para teste A/B:**
1. `Foi assim a noite de lançamento do Elo 28`
2. `A noite em que o Elo 28 aconteceu`
3. `Salão cheio, unidades vendidas: o lançamento do Elo 28`

## ⚠️ Antes de disparar

1. **Confirmar os 3 links.** Hoje todos apontam para `https://www.bilfor.com.br/elo-28`:
   - imagem do hero → landing do empreendimento;
   - botão **FALAR COM UM ASSESSOR** → se quiser, troque por WhatsApp do comercial, ex.: `https://wa.me/55DDDNUMERO?text=Vi%20o%20lan%C3%A7amento%20do%20Elo%2028%20e%20quero%20falar%20com%20um%20assessor`;
   - link secundário **Conhecer o Elo 28** → landing.
2. **Checar o texto do rodapé legal** com o jurídico da Bilfor — ele fala em "imagens de evento reais; perspectivas do empreendimento em desenvolvimento e meramente ilustrativas".
3. **Autorização de imagem.** O e-mail mostra rostos de convidados, parceiros e do time. Confirmar com a Bilfor se todos assinaram o termo de uso de imagem do evento.
4. **Quem subiu ao palco.** O texto do bloco de reconhecimento é propositalmente vago ("quem acreditou no Elo 28 desde o começo") porque não sabemos se são parceiros, imobiliárias ou clientes. Se a Bilfor confirmar quem são, dá pra nominar.
5. O e-mail **não cita data do evento nem números de vendas** — só "boa parte das unidades saiu no lançamento", mesma linha já aprovada no e-mail anterior. Se a Bilfor liberar número oficial (% vendido, nº de convidados), dá pra incluir na faixa de dados.

## Como subir no RD Station

As imagens ficam no mesmo repositório dos e-mails anteriores, agora numa subpasta:

```
rafaelas-web/elo28-email-lancamento/evento-lancamento/
```

**Passo a passo:**
1. Suba **todos os `.jpg` desta pasta** para `evento-lancamento/` na raiz do repositório (o `footer-logos.png` já está hospedado na raiz e é reaproveitado — não precisa subir de novo).
2. No RD Station: **Marketing > E-mails > Criar e-mail** → importar/criar a partir de HTML.
3. Cole o conteúdo de `email-evento-lancamento.html` (as imagens já apontam para URLs públicas).
4. Ajuste os links do item ⚠️ acima.
5. O `*UUID*` do link de descadastro é substituído automaticamente pelo RD.

**URLs das imagens:**
```
https://raw.githubusercontent.com/rafaelas-web/elo28-email-lancamento/master/evento-lancamento/hero-evento.jpg
https://raw.githubusercontent.com/rafaelas-web/elo28-email-lancamento/master/evento-lancamento/palco-apresentacao.jpg
https://raw.githubusercontent.com/rafaelas-web/elo28-email-lancamento/master/evento-lancamento/premiacao-01.jpg
https://raw.githubusercontent.com/rafaelas-web/elo28-email-lancamento/master/evento-lancamento/premiacao-02.jpg
https://raw.githubusercontent.com/rafaelas-web/elo28-email-lancamento/master/evento-lancamento/show-encerramento.jpg
https://raw.githubusercontent.com/rafaelas-web/elo28-email-lancamento/master/evento-lancamento/time-bilfor.jpg
https://raw.githubusercontent.com/rafaelas-web/elo28-email-lancamento/master/footer-logos.png
```

## Se a conta só tiver editor de blocos

| Bloco | Conteúdo |
|---|---|
| 1. Imagem | `hero-evento.jpg`, linkada para a landing |
| 2. Título pequeno | "O LANÇAMENTO" |
| 3. Título | "Foi assim a noite de lançamento do Elo 28." |
| 4. Texto | "A Bilfor reuniu clientes, parceiros e o time comercial para apresentar o Elo 28 — e o salão ficou cheio do começo ao fim. No telão, o empreendimento que nasce no ponto exato entre a vida da cidade e a calma de chegar em casa." |
| 5. Texto | "Foi uma noite de apresentação, brinde, reconhecimento — e de muita gente saindo daqui com a unidade garantida." |
| 6. Texto destacado | "90 m² \| 74 m² \| 70 m² · 2 e 3 dormitórios · +20 áreas de lazer" |
| 7. Título pequeno + título | "NO PALCO" / "O Elo 28, apresentado por inteiro." |
| 8. Texto | "Plantas, áreas de lazer, localização e condições de pagamento: tudo apresentado ao vivo, com o time da Bilfor no palco para responder o que viesse." |
| 9. Imagem | `palco-apresentacao.jpg` |
| 10. Título pequeno + título | "RECONHECIMENTO" / "Quem fez essa noite acontecer." |
| 11. Texto | "A noite também foi de homenagem: quem acreditou no Elo 28 desde o começo subiu ao palco para celebrar junto." |
| 12. Duas colunas | `premiacao-01.jpg` + `premiacao-02.jpg` |
| 13. Imagem + texto (fundo escuro) | `show-encerramento.jpg` / "E a noite terminou como começou: junto." / "Com música ao vivo, brinde e o salão inteiro de pé." |
| 14. Imagem | `time-bilfor.jpg` |
| 15. Texto | "Por trás de cada detalhe da noite, um time que acredita que empreendimento bom se constrói com gente boa. Obrigado a todos que estiveram com a gente." |
| 16. Título pequeno + título | "AINDA DÁ TEMPO" / "Ficou com vontade de conhecer o Elo 28?" |
| 17. Texto | "Boa parte das unidades saiu no lançamento, mas ainda tem opção para quem chegou agora. Fale com um assessor Bilfor e conheça as plantas, os valores e o que está disponível." |
| 18. Botão | "FALAR COM UM ASSESSOR" → link |
| 19. Imagem + texto | `footer-logos.png` + legal/descadastro |
