
## Informações Gerais

- Data: 31/05/2026
- Sistema Operacional: Windows
- Versão do VS Code: 1.122

---

## settings.json
```json
{

  "terminal.integrated.env.windows": {},
  "window.zoomLevel": 1,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.5,
  "editor.fontFamily": "Fira Code",
  "editor.rulers": [
      80,
      120
  ],
  "editor.tabSize": 2,
  "symbols.hidesExplorerArrows": false,
  "git.autofetch": true,
  "explorer.confirmDelete": false,
  "editor.fontLigatures": true,
  "workbench.startupEditor": "newUntitledFile",
  "editor.renderLineHighlight": "gutter",
  "workbench.editor.labelFormat": "short",
  "explorer.compactFolders": false,
  "terminal.integrated.defaultProfile.windows": "Command Prompt",
  "editor.minimap.enabled": false,
  "editor.semanticHighlighting.enabled": false,
  "breadcrumbs.enabled": false,
  "editor.scrollbar.horizontal": "hidden",
  "editor.scrollbar.vertical": "hidden",
  "files.associations": {
      ".env.*": "dotenv",
      ".prettierrc": "json",
      "*.css": "css",
      ".dev.vars": "dotenv"
  },

  "github.copilot.nextEditSuggestions.enabled": true,
  "gitlens.ai.model": "vscode",
  "gitlens.ai.vscode.model": "copilot:gpt-4.1",
  "workbench.colorTheme": "Min Dark",
  "workbench.iconTheme": "symbols",
  "symbols.files.associations": {
      "*.module.ts": "nest",
      "*.guard.ts": "typescript",
      "*.spec.ts": "ts-test",
      "*.e2e-spec.ts": "ts-test",
      "*.mock.ts": "ts-test",
      "vitest.config.e2e.ts": "vite",
      ".env.development.local": "gear",
      ".env.test.local": "gear",
      ".env.local": "gear",
      ".env.example": "gear"
  },
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",
  "tailwindCSS.experimental.classRegex": [
      [
          "tv\\(([^)]*)\\)",
          "[\"'`]([^\"'`]*).*?[\"'`]"
      ],
      "class:\\s*?[\"'`]([^\"'`]*).*?,"
  ],
  "[prisma]": {
      "editor.formatOnSave": true,
      "editor.defaultFormatter": "Prisma.prisma"
  },
  "cSpell.language": "en,pt",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "editor.suggestSelection": "first",
  "terminal.integrated.showExitAlert": false,
  "typescript.suggest.autoImports": true,
  "typescript.preferences.preferTypeOnlyAutoImports": true,
  "terminal.integrated.env.osx": {
      "FIG_NEW_SESSION": "1"
  },
  "explorer.fileNesting.enabled": true,
  "emmet.includeLanguages": {
      "javascript": "javascriptreact",
      "mdx": "javascriptreact"
  },
  "emmet.syntaxProfiles": {
      "javascript": "jsx",
      "mdx": "jsx"
  },
  "cSpell.enableFiletypes": [
      "!asciidoc",
      "!c",
      "!cpp",
      "!csharp",
      "!go",
      "!handlebars",
      "!haskell",
      "!jade",
      "!java",
      "!latex",
      "!php",
      "!pug",
      "!python",
      "!restructuredtext",
      "!rust",
      "!scala",
      "!scss"
  ],
  "editor.acceptSuggestionOnCommitCharacter": false,
  "git.enableSmartCommit": true,
  "editor.accessibilitySupport": "off",
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "Fira Code",
  "editor.codeActionsOnSave": {
      "source.fixAll.eslint": "explicit"
  },
  "security.workspace.trust.untrustedFiles": "newWindow",
  "files.exclude": {
      "**/.DS_Store": true,
      "**/.hg": true,
      "**/.svn": true,
      "**/.git": true,
      ".idea": true,
      "**/__pycache__": true,
      "**/__init__.py": true
  },
  "update.mode": "manual",
  "terminal.integrated.gpuAcceleration": "on",
  "terminal.integrated.defaultProfile.osx": "fish",
  "[jsonc]": {
      "editor.defaultFormatter": "vscode.json-language-features"
  },
  "[json]": {
      "editor.defaultFormatter": "vscode.json-language-features"
  },
  "git.openRepositoryInParentFolders": "always",
  "[javascript]": {
      "editor.defaultFormatter": "vscode.typescript-language-features"
  },
  "workbench.editor.empty.hint": "hidden",
  "update.showReleaseNotes": false,
  "security.promptForLocalFileProtocolHandling": false,
  "editor.hideCursorInOverviewRuler": true,
  "explorer.sortOrder": "foldersNestsFiles",
  "explorer.fileNesting.patterns": {
      "package.json": ".eslint*, prettier*, tsconfig*, vite*, pnpm-*, bun.lockb, nest*, package-lock*",
      "tailwind.config.*": "tailwind.config*, postcss.config*",
      ".env.local": ".env*",
      ".env": ".env*"
  },
  "cSpell.userWords": [
      "automations",
      "bootcamp",
      "chakra",
      "checkin",
      "checkins",
      "cloudflare",
      "clsx",
      "Codegen",
      "datadog",
      "Datetime",
      "dayjs",
      "Dotenv",
      "Elysia",
      "esbuild",
      "fastify",
      "Fastify",
      "feedbackwidget",
      "ffprobe",
      "gamificada",
      "Hasher",
      "hono",
      "Hono",
      "ilike",
      "IUGU",
      "jamjuree",
      "jupiter",
      "ksuid",
      "liveblocks",
      "LIVEBLOCKS",
      "Marguerita",
      "middlewares",
      "mixpanel",
      "monaco",
      "nestjs",
      "nivo",
      "omni",
      "Omni",
      "Onboarded",
      "pallas",
      "postgres",
      "postgresql",
      "prefetch",
      "reactflow",
      "retriable",
      "roboto",
      "rocketseat",
      "rotion",
      "rsxp",
      "Sandpack",
      "shiki",
      "skylab",
      "sqlite",
      "supergraph",
      "svgr",
      "sympla",
      "tailwindcss",
      "textblock",
      "tiptap",
      "trpc",
      "TRPC",
      "tsup",
      "unfollow",
      "Unfollow",
      "unform",
      "Unform",
      "unmark",
      "upsert",
      "Usuario",
      "webm",
      "WEBPUSH"
  ],
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "keyword.other.dotenv",
        "settings": {
          "foreground": "#FF000000"
        }
      }
    ]
  },
  "window.autoDetectColorScheme": true,
  "workbench.preferredDarkColorTheme": "Mermaid Dark",
  "workbench.preferredLightColorTheme": "Min Light",
  "explorer.confirmPasteNative": false,
  "window.menuBarVisibility": "compact",
  "redhat.telemetry.enabled": true,
  "makefile.configureOnOpen": true,
  "mssql.connectionGroups": [
    {
      "name": "ROOT",
      "id": "ROOT"
    }
  ],
  "terminal.integrated.enableMultiLinePasteWarning": "never",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "mssql.autoDisableNonTSqlLanguageService": true,
  "[python]": {
	"editor.defaultFormatter": "ms-python.black-formatter",
	"editor.formatOnSave": true
  }
```
}
```

---

## keybindings.json
```json
[
]
```

---

## Extensões Instaladas
- Better Comments
- Color Highlight
- Angular Language Service
- DotENV
- Todo Tree
- REST Client
- Black Formatter
- Markdown Preview Mermaid Support
- Mermaid
- Image preview
- Draw.io Integration
- Markdown Preview Enhanced
- Rainbow Brackets
- Path Intellisense
- Svg Preview
- Swagger Viewer
- Symbols
- Brazilian Portuguese - Code Spell Checker
- Emoji File Icons

---

## Temas e Aparência
- Tema: Dark+ (Default Dark)
- Ícones: Symbols
- Fonte: Fira Code

---

## Observações
- Ambiente configurado para desenvolvimento.
- Utiliza Fira Code como fonte principal.
- Extensão Better Comments instalada para melhorar a leitura dos comentários.
