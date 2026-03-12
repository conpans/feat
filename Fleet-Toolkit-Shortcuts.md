# Fleet Toolkit — Keyboard Shortcut Reference

---

## Global (works everywhere)

| Shortcut | Action |
|----------|--------|
| `Ctrl+S` | Save current edit, return to view mode |
| `Ctrl+K` | Open search |
| `Ctrl+M` | Jump to map |
| `Ctrl+Shift+L` | New shift log entry |
| `Ctrl+Shift+C` | Toggle case panel (map page) |
| `Escape` | Blur field → exit item level → close search/modal |
| `@` in textarea | Autocomplete tool/chamber names |
| `p` (frame/chamber) | Pin/unpin current tool or chamber |

---

## Map Page — Case Panel

Open with `Ctrl+Shift+C` or click the "Open Cases" bar.

| Key | Action |
|-----|--------|
| `j` / `↓` | Focus next case chip |
| `k` / `↑` | Focus previous case chip |
| `Enter` / `l` | Open focused case in a pane |
| `e` | Toggle edit/view (auto-focuses first field) |
| `h` | Close focused case's pane |
| `Escape` | Exit nav mode |

Select two cases to compare side-by-side.

---

## Frame / Chamber / Vendor / Ref Pages

### Level 1 — Tab Selection

| Key | Action |
|-----|--------|
| `1` | First tab |
| `2` | Second tab |
| `3` | Third tab |
| `4` | Fourth tab |
| `5` | Fifth tab |
| `Enter` | Drop into items (Level 2) |
| `n` | New item on active tab |

**Tab numbers per page:**

| Page | 1 | 2 | 3 | 4 | 5 |
|------|---|---|---|---|---|
| Frame | Learning | Cases | Questions | PM | TC |
| Chamber | Learning | Cases | Questions | PM | — |
| Vendor/Ref | Pinned | Concepts | Patterns | Questions | Archive |

### Level 2 — Item Navigation

Press `Enter` from Level 1 to activate. Focused item gets a teal outline.

| Key | Action |
|-----|--------|
| `j` | Next item |
| `k` | Previous item |
| `e` | Toggle edit (auto-focuses first field) |
| `s` | Cycle status |
| `n` | New item |
| `Escape` | Back to Level 1 |

**Status cycling with `s`:**
- Cases: open → monitoring → resolved → escalated → unknown
- Questions: unanswered → partial → answered

### Inside an Edit Form

| Key | Action |
|-----|--------|
| `Tab` | Next field (trapped within the form) |
| `Shift+Tab` | Previous field |
| `Ctrl+S` | Save and exit edit |
| `Escape` | Blur current field |

---

## Delete Confirmation

All deletes use inline double-click — no browser popups.

1. Click `del` / `✕` → text changes to **Sure?** (red)
2. Click again within 2.5s to confirm
3. If ignored, resets automatically

Factory reset is the only action using a browser dialog.

---

## Typical Workflows

**Quick case triage from map:**
```
Ctrl+Shift+C → j j → Enter → e → type → Ctrl+S → j → s s (resolved)
```

**Edit a case on frame page:**
```
2 → Enter → j → e → Tab through fields → Ctrl+S → j → e → Ctrl+S
```

**Add shift log from anywhere:**
```
Ctrl+Shift+L → type → Ctrl+S
```

**Quick status change:**
```
2 → Enter → j (find case) → s (cycle status)
```

**Add a new case:**
```
2 → n → type title → Tab → type trigger → Tab → continue → Ctrl+S
```

**Pin a tool for quick access:**
```
p (on frame page) → chip appears in header → click chip from anywhere
```

**Search and jump:**
```
Ctrl+K → type → click result → Ctrl+M (back to map)
```

**Navigate vendor knowledge:**
```
1 (Pinned) → Enter → j j → e → edit concept → Ctrl+S → Escape → 3 (Patterns)
```
