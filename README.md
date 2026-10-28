# pi-questionnaire

Add a structured single- and multi-question questionnaire tool.

In interactive TUI sessions it shows a custom option-list/tab UI. In RPC mode
(e.g. T3 Code) it falls back to pi's extension-UI `select`/`input` dialogs, which
the host maps to its own structured question UI; questions run sequentially and
dismissing any dialog cancels the questionnaire. Non-interactive modes error.

Install as a Pi git package:

```json
"git:git.quinntyx.dev/quinntyx/pi-questionnaire"
```
