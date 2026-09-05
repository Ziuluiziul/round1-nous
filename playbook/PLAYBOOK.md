# Playbook Nous Free — smoke + cotas (R$50)

**Recebedor PIX:** LUIZ · **tag54=50.00** (`qr_2` / `pix_copia_cola_2`)  
**Host API:** https://inference-api.nousresearch.com/v1  
**Docs:** https://portal.nousresearch.com/api-docs · Free **50 RPM / 500k TPM**

## Em 10 minutos
1. Abra o portal e use só Free (sem top-up).
2. `GET /v1/models` — filtre IDs com sufixo `:free` (catálogo vivo ≠ lista Hermes da api-docs).
3. `POST /v1/chat/completions` com um ID preferido (`meituan/longcat-2.0:free`).
4. Guarde HTTP + `usage` + headers `x-ratelimit-*` (não invente remaining).
5. Compare remaining ao teto 50 / 500000. Alerta prático: rem req <15 ou tokens <20%.

## Preferir / evitar
| Preferir | Evitar |
|---|---|
| longcat-2.0 · laguna-s/xs-2.1 · ling-3.0-flash-fin/sante | Hermes-* (404) · step/solar (400 tags) |

## Entregáveis do kit
- Relatório 1 página (`RELATORIO.md`) + `SAMPLE.md` + `smoke-response.json` (sem secret)
- Ebook PDF: https://ziuluiziul.github.io/round1-nous/ebook/nous-free-smoke-cotas.pdf
- Landing PIX: https://ziuluiziul.github.io/round1-nous/

## Preço
- Smoke + cotas: **R$ 50** (PIX tag54=50.00)
- Pack ampliado: **R$ 100** (tag54=100.00 · `qr_0`)

## Fora do escopo
Hermes, top-up pago, chave do vendedor, cold-DM, trycloudflare efêmero.
