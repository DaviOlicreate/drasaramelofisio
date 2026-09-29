# Dra. Sara Melo — Fisioterapia domiciliar

Landing page da fisioterapeuta Sara Melo (Arapiraca – AL), atendimento em domicílio.
Página única, sem build: HTML + Tailwind CSS (CDN) + JavaScript puro.

Mesma arquitetura do site da Dra. Cristiane Gomes, com a identidade da Sara
(paleta Boowie: off-white `#f4f0ed`, sálvia `#b4b89f`, dourado `#fff8e5→#69481d`,
marrom `#635548`; tipografia Montserrat).

## Seções

Topo · Isso é para você se… · Quem é a Dra. Sara · O que eu trato ·
Como funciona o atendimento · Onde eu atendo · Histórias de pacientes ·
Dúvidas frequentes · Agendar avaliação · Instagram

## Rodar localmente

```bash
python3 -m http.server 4180
```

Depois abra <http://localhost:4180/index.html>.
O linktree fica em <http://localhost:4180/linktree/>.

Ao escolher entre as versões A e B do hero, apague a outra e a tarja de comparação.

## Pendências — buscar com a Sara

| Item | Onde aparece |
|---|---|
| **Número do CREFITO** | seção "Quem é a Dra. Sara", rodapé e JSON-LD |
| **Logomarca** (`logo.webp`) e `favicon.png` | cabeçalho e aba do navegador |
| **Bairros e cidades reais atendidos** | seção "Onde eu atendo" e JSON-LD |
| **Horário de atendimento** | contato, rodapé e JSON-LD |
| **Duração/frequência das sessões e política de valores** | FAQ (virá no PDF que ela está redigindo) |
| **Depoimentos** de pacientes ou familiares | seção "Histórias de pacientes" |
| **Link de avaliação do Google** (`g.page/r/.../review`) | seção "Histórias de pacientes" |
| **Links dos posts do Instagram** | array `INSTAGRAM_POSTS` no script final |
| Pixel do Meta, GA4 e GTM | comentários no `<head>` |
| `action` do formulário (FormSubmit) | `<form id="form-lead">` |

Os trechos a confirmar estão marcados no código com comentários `CONFERIR`.

## Imagens

Geradas a partir da sessão de fotos em `Sara/` (35 originais, 4000×6000 — fora do versionamento):

| Arquivo | Origem | Onde |
|---|---|---|
| `hero-sara.webp` | DSC04695 (recorte 3:4) | topo, no celular |
| `hero-sara-wide.webp` | DSC04695 recomposta em 16:9, fundo estendido | topo, no desktop |
| `sara-perfil.webp` | DSC05173 (recorte 4:5) | seção "Quem é a Dra. Sara" |
| `hero-sara-centro.webp` | DSC04695 sem recorte | topo da versão B |
| `linktree/avatar.webp` | DSC05173 (quadrado no rosto) | avatar do linktree |
| `favicon.png` | provisório, do mesmo recorte | aba do navegador — trocar pela logo |

Ainda disponíveis na pasta e não usadas: fotos com o aparelho de reabilitação de
mão (DSC04202, DSC04216), com tablet de avaliação (DSC04666, DSC04671) e com
material de terapia (DSC04674–04679).

## Dados já aplicados

- WhatsApp: **5582998427638** — (82) 99842-7638
- E-mail: **Dr.saramello@gmail.com**
- Instagram: **@fisio.saramello**
- Escopo: Neurologia (pós-AVC e Parkinson), Geriatria e Funcional — traumatologia ficou de fora
