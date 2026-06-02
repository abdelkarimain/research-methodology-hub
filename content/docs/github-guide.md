---
draft: false
title: GitHub Contribution Guide
weight: 40
---

Lorem ipsum dolor sit amet, consectetur adipiscing elit. This guide simulates how contributors might collaborate on a documentation repository while keeping all content placeholder-only.

{{< callout type="info" >}}
Use this page to demonstrate commands, task lists, branch conventions, review states, and contribution etiquette.
{{< /callout >}}

## Contribution Flow

{{% steps %}}

### Create a branch

Use a clear branch name for the placeholder documentation area.

```bash
git checkout -b docs/lorem-methodology-card
```

### Edit the page

Add lorem ipsum sections, Hextra cards, callouts, tables, tabs, or collapsible notes.

### Preview locally

```bash
hugo server --disableFastRender
```

### Open a pull request

Summarize the demo section, list visual changes, and note that no real research claims were added.

{{% /steps %}}

## Pull Request Checklist

- [ ] Page title and sidebar order are clear.
- [ ] Content uses academic-style placeholder text.
- [ ] Hextra shortcodes render correctly.
- [ ] No real dataset, citation, or research claim appears.
- [ ] Screenshots or visual notes are attached when UI changes are made.

## Branch Naming

| Branch | Purpose |
|---|---|
| `docs/topic-map-placeholder` | Topic catalog and research domain demos |
| `docs/proposal-template-demo` | Problem statement and proposal structure |
| `ui/mockup-showcase` | Component and visual examples |
| `fix/sidebar-order` | Navigation and metadata cleanup |

## Review States

{{< tabs >}}
  {{< tab name="Draft" selected=true >}}
  Lorem ipsum pull requests may be incomplete while layout, headings, and placeholder structure are refined.
  {{< /tab >}}
  {{< tab name="Ready" >}}
  Sed do eiusmod pull requests include final demo copy, screenshots, and rendering checks.
  {{< /tab >}}
  {{< tab name="Merged" >}}
  Ut enim ad minim veniam changes are published after review and a successful Hugo build.
  {{< /tab >}}
{{< /tabs >}}

## Keyboard Shortcuts

Use <kbd>Ctrl</kbd> + <kbd>K</kbd> for search-like command palettes in many documentation systems. Use <kbd>G</kbd> then <kbd>D</kbd> as a simulated shortcut for jumping to docs.

{{% details title="Maintainer note" closed="true" %}}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maintain a consistent voice, avoid real claims, and keep examples compact enough for scanning.
{{% /details %}}
