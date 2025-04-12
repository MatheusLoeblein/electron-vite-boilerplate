# ⚡ Electron Vite Boilerplate

Um boilerplate moderno e leve para construir aplicações desktop com **Electron**, **Vite**, **React** e **TypeScript**.

> Ideal para projetos que precisam de performance, organização e hot reload no desenvolvimento.

---

## 🚀 Tecnologias

- [Electron](https://www.electronjs.org/) — Criação de aplicações desktop cross-platform
- [Vite](https://vitejs.dev/) — Bundler ultrarrápido para o frontend
- [React](https://react.dev/) — Biblioteca para criação de interfaces reativas
- [TypeScript](https://www.typescriptlang.org/) — Tipagem estática para maior segurança
- [tsc-watch](https://github.com/gilamran/tsc-watch) — Watcher com suporte a hooks para rebuilds automáticos

---

## 📁 Estrutura de Pastas

```bash
.
├── src/
│   ├── main/        # Código principal do Electron
│   └── renderer/    # Código React (interface)
├── dist/            # Build final para produção
├── public/          # Arquivos públicos do Vite
├── vite.config.ts   # Configuração do Vite
├── tsconfig.json    # Configuração do TypeScript
├── electron.vite.config.ts # Configuração customizada para Electron
└── package.json
