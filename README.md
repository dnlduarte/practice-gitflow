# 🚀 Meu Projeto GitFlow

Este é um projeto simples para praticar fluxo de branches usando Git.

---

## 📁 Estrutura de branches

- `main` → versão estável (produção)
- `dev` → integração de desenvolvimento
- `feature/*` → novas funcionalidades

---

## 🌿 Exemplo de fluxo

1. Criar uma feature:
```bash
git checkout -b feature/site
```

2. Desenvolver e commitar:
```bash
git add .
git commit -m "feat: adiciona site simples"
```

3. Enviar para o repositório:
```bash
git push -u origin feature/site
```
