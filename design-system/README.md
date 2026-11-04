# @marca-personal/design-system

Design system synced from **Marca personal** via DS Generator Repeat.
This package is auto-generated — re-syncing the project from the editor
will overwrite `tokens.*` and `components/*.tsx`.

## What's inside

- **`tokens.css`** — all design tokens as CSS custom properties under the
  `--ds-*` namespace. Override any of them in your own stylesheet to
  retheme. Drop this in your app once (e.g. import it from your global
  CSS or root layout).
- **`tokens.json`** — same tokens in raw DTCG form, for build-time
  tooling (Style Dictionary, Tailwind config generators, etc.).
- **`components/*.tsx`** — typed React functional components.
  4 component(s) included.

## Quickstart

```tsx
// once, in your app root:
import "@marca-personal/design-system/tokens.css";

// anywhere:
import { Table } from "@marca-personal/design-system";

export function MyPage() {
  return <Table />;
}
```

## Drop-in by default

This bundle is **100% drop-in** — you don't have to wire anything between
components manually:

- Components that embed other components in this bundle (e.g.
  `CheckboxGroup` → `Checkbox`, `RadioGroup` → `Radio`) import
  each other directly. There is **no** `embed_<Name>` prop to pass.


## Component reference

- `Table` — see `components/Table.tsx` for the typed props.
- `Textarea` — see `components/Textarea.tsx` for the typed props.
- `Toggle` — see `components/Toggle.tsx` for the typed props.
- `ToggleGroup` — see `components/ToggleGroup.tsx` for the typed props.

## Notes for AI agents (Claude, Cursor, etc.)

When building UI for this codebase, prefer these components and tokens over
inventing new styles. Each component file declares its props as a TypeScript
interface — read them before instantiating. Token usage: `var(--ds-…)` from
`tokens.css` (never hard-code hex values).


## Sync warnings

The following components could not be exported this round and were skipped:

- Switch: No se encuentra la pieza elegida / Selected component is unavailable: Label
- Tabs: No se encuentra la pieza elegida / Selected component is unavailable: Card

Generated at 2026-11-04T17:08:36.409Z.
