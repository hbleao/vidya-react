# ![Vidya Logo](./assets/vidya-logo.png)

# **Vidya** — Design System Modular & Transparente

**Vidya** vem do sânscrito, significando *conhecimento verdadeiro, clareza e sabedoria*. Esse nome representa a alma do projeto: **componentes modulares, abertos, confiáveis e sem caixas-pretas**.

---

## ✨ Conceito

> **Vidya é um design system para quem busca controle, clareza e escala.**

Nada de estilização mágica, nem componentes ocultos. Cada parte é pensada para ser **visível, previsível e extensível**.

---

## 🧠 Princípios

* 🔹 **Modularidade real**: cada componente é isolado, testável e customizável
* 🔹 **Sem black-box**: estilos explícitos, tokens abertos, sem abstrações fechadas
* 🔹 **Clareza e tipagem**: uso de TypeScript para DX forte e documentação viva
* 🔹 **Design técnico**: Sass com BEM, tokens separados, controle total

---

## ⚙️ Stack Tecnológico

* ⚛️ **React 19** com suporte moderno a Suspense e Server Components
* ✍️ **TypeScript** com tipagem forte e propagação de props segura
* 💅 **Sass + BEM** para estilo sem dependência de frameworks utilitários
* 🧱 **Tokens de design** centralizados para cores, espaçamento e tipografia
* 🧪 **Jest + RTL** para testes automatizados por componente
* 📚 **Storybook** para documentação visual interativa
* 🧰 **CLI `vidya`** (em construção) para scaffold e automação

---

## 📦 Instalação

```bash
npm add @vidya/ui
```

> Requer Sass configurado no bundler do seu projeto.

---

## 🚀 Exemplo rápido

```tsx
import { Button } from '@vidya/ui'

export function App() {
  return <Button variant="primary">Enviar</Button>
}
```

---

## 📁 Componentes disponíveis

* `Button`
* `Input`
* `Textarea`
* `Switch`
* `Dialog`
* *e mais em construção...*

---

## 🧪 Testes

```bash
pnpm test
```

* Todos os componentes possuem testes unitários e integração
* Utilizamos Jest + React Testing Library

---

## 📚 Documentação com Storybook

```bash
pnpm storybook
```

* Documentação interativa com suporte a variantes e playground

---

## 📦 Design Tokens (exemplo)

```scss
$blue: (
  500: #2E90FA,
  600: #1570EF,
  700: #175CD3
);

$gray: (
  100: #EAECF5,
  500: #4E5BA6,
  900: #101323
);
```

---

## 🧩 Roadmap

* [x] Base de componentes com Sass + BEM
* [x] Tipagem forte com TypeScript
* [x] Tokens centralizados em SCSS
* [x] Testes automatizados com Jest
* [x] Storybook + MDX
* [ ] CLI `vidya` para scaffolding (`create`, `add`, `tokens sync`)
* [ ] Theming com CSS Variables
* [ ] Documentação em site público (`vidya.dev`)

---

## 🤝 Contribuindo

```bash
npm run dev
```

* Lint automático (`eslint`, `prettier`)
* Commits semânticos (`commitlint`)
* Testes locais com Jest
* Documentação com Storybook

---

## 📄 Licença

MIT — com 💙 por \ [Henrique Leão]

---
