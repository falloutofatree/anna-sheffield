# Brand Guidelines

## Typography

### Typefaces

| Role | Font | Fallbacks | Style |
|------|------|-----------|-------|
| Body | Styrene A | Futura, sans-serif | Regular |
| Subheading | Styrene A | Futura, sans-serif | Regular |
| Heading | Pegasus | Baskerville, serif | Regular |
| Accent | Styrene A | Futura, sans-serif | Regular |

Additional custom typefaces loaded but not currently assigned to roles:
- **Portrait** — display/editorial use
- **Styrene B** — alternate grotesque variant

---

### Type Scale

Sizes below 48px are fixed; sizes at or above 48px scale fluidly with viewport width using `clamp()`.

| Element | Font | Size (px) | CSS Value | Line Height | Letter Spacing | Case |
|---------|------|-----------|-----------|-------------|----------------|------|
| H1 | Pegasus | 72 | `clamp(3rem, 7.2vw, 4.5rem)` | 1.1 | 0em | none |
| H2 | Pegasus | 48 | `clamp(2.25rem, 4.8vw, 3rem)` | 1.1 | 0em | none |
| H3 | Pegasus | 32 | `2rem` | 1.1 | 0em | none |
| H4 | Styrene A | 24 | `1.5rem` | 1.1 | 0em | none |
| H5 | Styrene A | 18 | `1.125rem` | 1.1 | 0em | none |
| H6 | Styrene A | 16 | `1rem` | 1.1 | 0em | none |
| Body / p | Styrene A | 14 | `0.875rem` | 1.4 | 0em | — |

---

### Fixed Size Tokens

| Token | rem | px |
|-------|-----|----|
| `--font-size--3xs` | 0.625rem | 10 |
| `--font-size--2xs` | 0.75rem | 12 |
| `--font-size--xs` | 0.8125rem | 13 |
| `--font-size--sm` | 0.875rem | 14 |
| `--font-size--md` | 1rem | 16 |
| `--font-size--lg` | 1.125rem | 18 |
| `--font-size--xl` | 1.25rem | 20 |
| `--font-size--2xl` | 1.5rem | 24 |
| `--font-size--3xl` | 2rem | 32 |
| `--font-size--4xl` | 2.5rem | 40 |
| `--font-size--5xl` | 3rem | 48 |
| `--font-size--6xl` | 3.5rem | 56 |

---

### Line Height

| Category | Tight | Normal | Loose |
|----------|-------|--------|-------|
| Display | 1.0 | 1.1 | 1.2 |
| Heading | 1.15 | 1.25 | 1.35 |
| Body | 1.2 | 1.4 | 1.6 |

---

### Letter Spacing (Tracking)

| Category | Tight | Normal | Loose |
|----------|-------|--------|-------|
| Display | −0.03em | 0em | 0.03em |
| Heading | −0.03em | 0em | 0.03em |
| Body | −0.03em | 0em | 0.03em |

Utility tokens: `--letter-spacing-sm: 0.06em` · `--letter-spacing-md: 0.13em`

---

### UI Typography

| Context | Font | Notes |
|---------|------|-------|
| Primary button | Styrene A | Default case |
| Secondary button | Styrene A | Default case |
| Cart price | Styrene A | Subheading role |
| Filter drawer heading | Styrene A | 14px, uppercase |
| Variant option labels | Styrene A | 11px, uppercase |
| Mobile menu items | Styrene A | 11px |
| Mega-menu parent links | Styrene A | Bold, underlined |
