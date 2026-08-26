# doutrina

**Build step 4 of 4** · Publish host for **doutrina.org**

---

## 📑 Table of contents

1. 🇺🇸 [English](#-english--build-step-4-of-4)
   1. 🎯 [Audience](#-audience)
   2. 🗺️ [Pipeline position](#-pipeline-position)
   3. 🌐 [This host](#-this-host)
   4. ⚠️ [Do not hand-edit the app](#️-do-not-hand-edit-the-app)
   5. 🤝 [How to help](#-how-to-help)
2. 🇧🇷 [Português](#-português--etapa-4-de-4)
   1. 🎯 [Público](#-público)
   2. 🗺️ [Posição no pipeline](#-posição-no-pipeline)
   3. 🌐 [Este host](#-este-host)
   4. ⚠️ [Não edite o app à mão](#️-não-edite-o-app-à-mão)
   5. 🤝 [Como ajudar](#-como-ajudar)

---

# 🇺🇸 English — Build step 4 of 4

GitHub Pages **deployment mirror** of `librus-shell` `dist/` for **https://doutrina.org** (flavor `doutrina`).

## 🎯 Audience

1. Maintainers checking Pages / CNAME for doutrina.org  
2. Volunteers routing feedback to content vs shell  
3. External collaborators assessing the Spiritist study surface  

**Not** end-user documentation.

## 🗺️ Pipeline position

1. [`doutrina-content`](https://github.com/sergioSHKLR/doutrina-content) — Kardec Markdown  
2. [`librus-linker`](https://github.com/sergioSHKLR/librus-linker) — provider injection  
3. [`librus-shell`](https://github.com/sergioSHKLR/librus-shell) — SPA build (`VITE_FLAVOR=doutrina`)  
4. **This repo** — live publish  

## 🌐 This host

1. **Site:** [doutrina.org](https://doutrina.org)  
2. **Flavor:** `doutrina` (codification shelf, Luz + full providers)  
3. **UI source:** [`librus-shell`](https://github.com/sergioSHKLR/librus-shell)  
4. **Content source:** [`doutrina-content`](https://github.com/sergioSHKLR/doutrina-content)  
5. **Live beta UX** (owned by shell): narrow screens blocked; first-visit Device/How to onboard — see [`librus-shell` README](https://github.com/sergioSHKLR/librus-shell).  

## ⚠️ Do not hand-edit the app

1. Change product code in **librus-shell**, then deploy.  
2. Change book text / anchors in **doutrina-content** (then linker → shell).  
3. Files under this repo’s published tree are **generated** by CI.  

## 🤝 How to help

1. Proofreading / page anchors → doutrina-content.  
2. Reader UX / PWA / panes → librus-shell.  
3. DNS / Pages only → open an issue here.  
4. Ecosystem map: see [`librus` README](https://github.com/sergioSHKLR/librus).  

## 🏅 Credits

1. See [CREDITS.md](./CREDITS.md) — Sergio SHKLR (lead, git metrics) · Grok / xAI (assisted docs & shell collaboration).  

---

# 🇧🇷 Português — Etapa 4 de 4

Espelho de publicação (GitHub Pages) do `dist/` de `librus-shell` em **https://doutrina.org** (sabor `doutrina`).

## 🎯 Público

1. Mantenedores de Pages / CNAME de doutrina.org  
2. Voluntários que direcionam feedback (conteúdo vs shell)  
3. Colaboradores externos que avaliam a superfície de estudo  

**Não** é documentação para o leitor final.

## 🗺️ Posição no pipeline

1. [`doutrina-content`](https://github.com/sergioSHKLR/doutrina-content) — Markdown de Kardec  
2. [`librus-linker`](https://github.com/sergioSHKLR/librus-linker) — injeção  
3. [`librus-shell`](https://github.com/sergioSHKLR/librus-shell) — build (`VITE_FLAVOR=doutrina`)  
4. **Este repo** — publicação  

## 🌐 Este host

1. **Site:** [doutrina.org](https://doutrina.org)  
2. **Sabor:** `doutrina`  
3. **UI:** [`librus-shell`](https://github.com/sergioSHKLR/librus-shell)  
4. **Conteúdo:** [`doutrina-content`](https://github.com/sergioSHKLR/doutrina-content)  
5. **UX beta ao vivo** (no shell): telas estreitas bloqueadas; onboard Dispositivo/Como usar na 1ª visita — ver [README do librus-shell](https://github.com/sergioSHKLR/librus-shell).  

## ⚠️ Não edite o app à mão

1. Código de produto → **librus-shell**, depois deploy.  
2. Texto / âncoras → **doutrina-content** (depois linker → shell).  
3. Árvore publicada aqui é **gerada** pelo CI.  

## 🤝 Como ajudar

1. Revisão / páginas → doutrina-content.  
2. UX do leitor / PWA → librus-shell.  
3. Só DNS / Pages → issue neste repo.  
4. Mapa: [`librus` README](https://github.com/sergioSHKLR/librus).  

## 🏅 Créditos

1. Ver [CREDITS.md](./CREDITS.md) — Sergio SHKLR (líder, métricas git) · Grok / xAI (docs e colaboração no shell).  
