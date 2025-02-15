ai-chatbot/
├── app
│   ├── (auth)
│   │   ├── api
│   │   │   └── auth
│   │   │       └── [...nextauth]
│   │   │           └── route.ts
│   │   ├── login
│   │   │   └── page.tsx
│   │   ├── register
│   │   │   └── page.tsx
│   │   ├── actions.ts
│   │   ├── auth.config.ts
│   │   └── auth.ts
│   ├── (chat)
│   │   ├── api
│   │   │   ├── chat
│   │   │   │   └── route.ts
│   │   │   ├── document
│   │   │   │   └── route.ts
│   │   │   ├── files
│   │   │   │   └── upload
│   │   │   │       └── route.ts
│   │   │   ├── history
│   │   │   │   └── route.ts
│   │   │   ├── suggestions
│   │   │   │   └── route.ts
│   │   │   └── vote
│   │   │       └── route.ts
│   │   ├── chat
│   │   │   └── [id]
│   │   │       └── page.tsx
│   │   ├── actions.ts
│   │   ├── layout.tsx
│   │   ├── opengraph-image.png
│   │   ├── page.tsx
│   │   └── twitter-image.png
│   ├── favicon.ico
│   ├── globals.css
│   └── layout.tsx
├── artifacts
│   ├── code
│   │   ├── client.tsx
│   │   └── server.ts
│   ├── image
│   │   ├── client.tsx
│   │   └── server.ts
│   ├── sheet
│   │   ├── client.tsx
│   │   └── server.ts
│   ├── text
│   │   ├── client.tsx
│   │   └── server.ts
│   └── actions.ts
├── components
│   ├── ui
│   │   ├── alert-dialog.tsx
│   │   ├── button.tsx
│   │   ├── card.tsx
│   │   ├── dropdown-menu.tsx
│   │   ├── input.tsx
│   │   ├── label.tsx
│   │   ├── select.tsx
│   │   ├── separator.tsx
│   │   ├── sheet.tsx
│   │   ├── sidebar.tsx
│   │   ├── skeleton.tsx
│   │   ├── textarea.tsx
│   │   └── tooltip.tsx
│   ├── app-sidebar.tsx
│   ├── artifact-actions.tsx
│   ├── artifact-close-button.tsx
│   ├── artifact-messages.tsx
│   ├── artifact.tsx
│   ├── auth-form.tsx
│   ├── chat-header.tsx
│   ├── chat.tsx
│   ├── code-block.tsx
│   ├── code-editor.tsx
│   ├── console.tsx
│   ├── create-artifact.tsx
│   ├── data-stream-handler.tsx
│   ├── diffview.tsx
│   ├── document-preview.tsx
│   ├── document-skeleton.tsx
│   ├── document.tsx
│   ├── icons.tsx
│   ├── image-editor.tsx
│   ├── markdown.tsx
│   ├── message-actions.tsx
│   ├── message-editor.tsx
│   ├── message-reasoning.tsx
│   ├── message.tsx
│   ├── messages.tsx
│   ├── model-selector.tsx
│   ├── multimodal-input.tsx
│   ├── overview.tsx
│   ├── preview-attachment.tsx
│   ├── sheet-editor.tsx
│   ├── sidebar-history.tsx
│   ├── sidebar-toggle.tsx
│   ├── sidebar-user-nav.tsx
│   ├── sign-out-form.tsx
│   ├── submit-button.tsx
│   ├── suggested-actions.tsx
│   ├── suggestion.tsx
│   ├── text-editor.tsx
│   ├── theme-provider.tsx
│   ├── toolbar.tsx
│   ├── use-scroll-to-bottom.ts
│   ├── version-footer.tsx
│   ├── visibility-selector.tsx
│   └── weather.tsx
├── docs
│   ├── 01-quick-start.md
│   ├── 02-update-models.md
│   └── 03-artifacts.md
├── hooks
│   ├── use-artifact.ts
│   ├── use-chat-visibility.ts
│   └── use-mobile.tsx
├── lib
│   ├── ai
│   │   ├── tools
│   │   │   ├── create-document.ts
│   │   │   ├── get-weather.ts
│   │   │   ├── request-suggestions.ts
│   │   │   └── update-document.ts
│   │   ├── models.ts
│   │   └── prompts.ts
│   ├── artifacts
│   │   └── server.ts
│   ├── db
│   │   ├── migrations
│   │   │   ├── meta
│   │   │   │   ├── 0000_snapshot.json
│   │   │   │   ├── 0001_snapshot.json
│   │   │   │   ├── 0002_snapshot.json
│   │   │   │   ├── 0003_snapshot.json
│   │   │   │   ├── 0004_snapshot.json
│   │   │   │   └── _journal.json
│   │   │   ├── 0000_keen_devos.sql
│   │   │   ├── 0001_sparkling_blue_marvel.sql
│   │   │   ├── 0002_wandering_riptide.sql
│   │   │   ├── 0003_cloudy_glorian.sql
│   │   │   └── 0004_odd_slayback.sql
│   │   ├── migrate.ts
│   │   ├── queries.ts
│   │   └── schema.ts
│   ├── editor
│   │   ├── config.ts
│   │   ├── functions.tsx
│   │   ├── react-renderer.tsx
│   │   └── suggestions.tsx
│   └── utils.ts
├── public
│   ├── fonts
│   │   ├── geist-mono.woff2
│   │   └── geist.woff2
│   └── images
│       └── demo-thumbnail.png
├── LICENSE
├── README.md
├── biome.jsonc
├── components.json
├── drizzle.config.ts
├── middleware.ts
├── next.config.ts
├── package.json
├── pnpm-lock.yaml
├── postcss.config.mjs
├── tailwind.config.ts
└── tsconfig.json

39 directories, 134 files
