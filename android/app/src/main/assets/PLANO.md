# 📋 Plano do Projeto: code-editor. 1

**Gerado em:** 01/06/2026 13:50:51

---

## 📊 Visão Geral

| Item | Valor |
|------|-------|
| Total de arquivos | 143 |
| Total de linhas | 39.535 |
| Linguagens | 8 |
| Rotas de API | 20 |

---

## 🌳 Árvore de Arquivos

```
📄 artifact.toml
🔷 capacitor.config.ts
📋 components.json
🟡 app.js
🟠 extrator.html
📄 favicon.svg
📄 icon-192.png
📄 icon-512.png
🟠 index.html
📋 manifest.json
📄 opengraph.jpg
🟡 sw.js
📋 package.json
🟡 server_assets.js
🟡 server_embedded.js
🟡 server_final.js
🟡 server_main.js
🟡 server.js
🟡 app.js
🟠 extrator.html
📄 favicon.svg
📄 icon-192.png
📄 icon-512.png
🟠 index.html
📋 manifest.json
📄 opengraph.jpg
🟡 sw.js
💜 index-CQchCeow.css
🟡 index-D_jjJPtL.js
📄 favicon.svg
📄 icon-192.png
📄 icon-512.png
🟠 index.html
📋 manifest.json
📄 opengraph.jpg
🟡 sw.js
🟠 index.html
📝 MANUAL-APK.md
📋 package.json
🟠 extrator.html
📄 favicon.svg
📄 icon-192.png
📄 icon-512.png
📋 manifest.json
📄 opengraph.jpg
🟡 sw.js
🔷 App.tsx
🔷 AbrirOnline.tsx
🔷 AIChat.tsx
🔷 AssistenteJuridico.tsx
🔷 BrowserTerminal.tsx
🔷 CampoLivre.tsx
🔷 CodeEditor.tsx
🔷 DriveBackupPanel.tsx
🔷 EditorLayout.tsx
🔷 Extrator.tsx
🔷 FileTree.tsx
🔷 GitHubPanel.tsx
🔷 InAppBrowser.tsx
🔷 manual.tsx
🔷 PackageSearch.tsx
🔷 Preview.tsx
🔷 QuickPrompt.tsx
🔷 RealTerminal.tsx
🔷 Scanner.tsx
🔷 StreamTerminal.tsx
🔷 TemplateSelector.tsx
🔷 Terminal.tsx
🔷 accordion.tsx
🔷 alert-dialog.tsx
🔷 alert.tsx
🔷 aspect-ratio.tsx
🔷 avatar.tsx
🔷 badge.tsx
🔷 breadcrumb.tsx
🔷 button-group.tsx
🔷 button.tsx
🔷 calendar.tsx
🔷 card.tsx
🔷 carousel.tsx
🔷 chart.tsx
🔷 checkbox.tsx
🔷 collapsible.tsx
🔷 command.tsx
🔷 context-menu.tsx
🔷 dialog.tsx
🔷 drawer.tsx
🔷 dropdown-menu.tsx
🔷 empty.tsx
🔷 field.tsx
🔷 form.tsx
🔷 hover-card.tsx
🔷 input-group.tsx
🔷 input-otp.tsx
🔷 input.tsx
🔷 item.tsx
🔷 kbd.tsx
🔷 label.tsx
🔷 menubar.tsx
🔷 navigation-menu.tsx
🔷 pagination.tsx
🔷 popover.tsx
🔷 progress.tsx
🔷 radio-group.tsx
🔷 resizable.tsx
🔷 scroll-area.tsx
🔷 select.tsx
🔷 separator.tsx
🔷 sheet.tsx
🔷 sidebar.tsx
🔷 skeleton.tsx
🔷 slider.tsx
🔷 sonner.tsx
🔷 spinner.tsx
🔷 switch.tsx
🔷 table.tsx
🔷 tabs.tsx
🔷 textarea.tsx
🔷 toast.tsx
🔷 toaster.tsx
🔷 toggle-group.tsx
🔷 toggle.tsx
🔷 tooltip.tsx
🔷 VoiceCard.tsx
🔷 VoiceMode.tsx
🔷 use-mobile.tsx
🔷 use-toast.ts
💜 index.css
🔷 ai-service.ts
🔷 github-service.ts
🔷 projects.ts
🔷 store.ts
🔷 templates.ts
🔷 tts-service.ts
🔷 utils.ts
🔷 virtual-fs.ts
🔷 zip-service.ts
🔷 main.tsx
🔷 not-found.tsx
📋 tsconfig.json
🔷 vite.config.apk.ts
🔷 vite.config.standalone.ts
🔷 vite.config.ts
```

---

## 🗣️ Linguagens

🔷 typescript: 96 arquivos
📄 plaintext: 16 arquivos
🟡 javascript: 12 arquivos
📋 json: 8 arquivos
🟠 html: 7 arquivos
💜 css: 2 arquivos
📄 toml: 1 arquivo
📝 markdown: 1 arquivo

---

## 🚀 Pontos de Entrada

  • app.js
  • server.js
  • index.html

---

## 🔌 Rotas de API Detectadas

  `GET /api/items` — app.js
  `GET /api/items/:id` — app.js
  `POST /api/items` — app.js
  `GET /api/health` — app.js
  `POST /register` — app.js
  `POST /login` — app.js
  `GET /perfil` — app.js
  `/API/SEARCH?Q=${ENCODEURICOMPONENT(PE)} /api/search?q=${encodeURIComponent(pe)}` — app.js
  `/API/WORKSPACE/INSTALL /api/workspace/install` — app.js
  `/API/WORKSPACE/SYNC /api/workspace/sync` — app.js
  `/API/DB/QUERY /api/db/query` — app.js
  `/API/AI/CHAT /api/ai/chat` — app.js
  `/API/LEGAL/PROCESS /api/legal/process` — app.js
  `/API/UPLOAD/EXTRACT-TEXT /api/upload/extract-text` — app.js
  `GET /api/items` — app.js
  `GET /api/items/:id` — app.js
  `POST /api/items` — app.js
  `GET /api/health` — app.js
  `POST /register` — app.js
  `POST /login` — app.js

---

## 💡 Sugestões de Melhoria

  📝 Adicionar README.md com instruções do projeto
  🚫 Adicionar .gitignore para evitar commits desnecessários
  🧪 Criar testes automatizados para as funcionalidades principais
  🔐 Criar .env.example para variáveis de ambiente
  📖 Documentar as rotas de API com exemplos de uso
  📁 Organizar arquivos em subpastas por funcionalidade
  🔷 Migrar arquivos .js para TypeScript para maior segurança de tipos

---

## 📖 Descrição

Importado de code-editor. 1.zip — 143 arquivo(s)

---

*Gerado pelo DevMobile IDE*
