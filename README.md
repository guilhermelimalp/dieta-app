# Meu Plano — Recomposição Corporal

Site mobile-first com o plano alimentar completo, protocolos de treino e dicas.

---

## Como publicar na Vercel (3 passos)

### Opção 1 — Upload direto (mais fácil, sem código)

1. Acesse [vercel.com](https://vercel.com) e faça login (pode usar conta Google)
2. Clique em **"Add New Project"**
3. Escolha **"Deploy from file upload"** (ou arraste a pasta do projeto)
4. Faça upload da pasta `dieta-app` inteira (ou do arquivo `index.html`)
5. Clique em **Deploy** — em menos de 1 minuto seu site estará no ar
6. A Vercel vai gerar um link tipo `meu-plano-xxxx.vercel.app` — acesse pelo celular!

---

### Opção 2 — Via GitHub (recomendado se quiser editar depois)

1. Crie um repositório no [github.com](https://github.com) (pode ser privado)
2. Faça upload dos arquivos `index.html` e `vercel.json`
3. Na Vercel, clique em **"Add New Project"** → conecte seu GitHub
4. Selecione o repositório → clique **Deploy**
5. Toda vez que editar o arquivo no GitHub, o site atualiza automaticamente

---

### Opção 3 — Via Vercel CLI (para quem usa terminal)

```bash
# Instalar a CLI da Vercel
npm install -g vercel

# Na pasta do projeto
cd dieta-app
vercel

# Seguir as instruções no terminal
# O link do site aparece no final
```

---

## Adicionar ao celular como app (PWA)

### iPhone (Safari)
1. Abra o link no Safari
2. Toque no ícone de compartilhar (quadrado com seta)
3. Escolha **"Adicionar à Tela Inicial"**
4. O app aparece igual a um app nativo, sem barra do navegador

### Android (Chrome)
1. Abra o link no Chrome
2. Toque nos 3 pontinhos (menu)
3. Escolha **"Adicionar à tela inicial"**

---

## Estrutura dos arquivos

```
dieta-app/
├── index.html     ← todo o site (HTML + CSS + JS em um arquivo)
├── vercel.json    ← configuração de deploy
└── README.md      ← este arquivo
```

---

Plano criado para: 65kg · 1,71m · 24% gordura · ectomorfo  
Proteína diária: 155g | Treino: PPL + Upper/Lower
