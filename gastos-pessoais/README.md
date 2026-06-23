# 💸 Controle de Gastos Pessoais

Sistema pessoal de controle financeiro — fatura do cartão, extrato bancário, gastos evitáveis e análises mensais.

## ✨ Funcionalidades

- **Dashboard mensal** com totais de receita, gastos, saldo e gastos evitáveis
- **Lançamentos** manuais com categorias, origem e flag de "evitável"
- **Análise** de gastos que podem ser evitados + recomendações automáticas
- **Importação** de extratos CSV (Nubank, Itaú, Bradesco, Inter e outros)
- Navegação por mês
- Filtros por categoria, tipo e evitabilidade
- Dados armazenados localmente no navegador (apenas você tem acesso)

## 🚀 Deploy no GitHub Pages

### 1. Criar repositório

```bash
git init
git add .
git commit -m "feat: v1.0.0 — controle de gastos pessoais"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/gastos-pessoais.git
git push -u origin main
```

### 2. Ativar GitHub Pages

1. Acesse **Settings** do repositório
2. Clique em **Pages** (menu lateral)
3. Em **Source**, selecione **GitHub Actions**
4. O deploy ocorre automaticamente a cada `git push`

### 3. Acessar o sistema

O URL será: `https://SEU_USUARIO.github.io/gastos-pessoais`

---

## 🔄 Controle de Versão

| Versão | Data | O que mudou |
|--------|------|-------------|
| v1.0.0 | Jun/2025 | Versão inicial — dashboard, lançamentos, análise, importação CSV |

### Para atualizar

```bash
git add .
git commit -m "feat: v1.1.0 — descrição da melhoria"
git push
```

O GitHub Actions faz o deploy automaticamente em ~1 minuto.

---

## 📂 Estrutura

```
gastos-pessoais/
├── index.html          # Interface principal
├── style.css           # Estilos
├── app.js              # Lógica
├── .github/
│   └── workflows/
│       └── deploy.yml  # Deploy automático
└── README.md
```

## 🔒 Privacidade

Os dados ficam armazenados **apenas no seu navegador** (localStorage). Nenhuma informação é enviada para servidores externos.
