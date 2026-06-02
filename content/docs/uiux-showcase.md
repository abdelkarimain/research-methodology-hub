---
draft: false
title: UI/UX Mockup Showcase
weight: 60
---

This page demonstrates documentation visuals, card sections, placeholder dashboards, badges, tabs, and collapsible panels for a modern academic developer portal.

![Documentation interface placeholder](/images/docs-interface.svg)

## Interface Principles

{{< cards cols="3" >}}
  {{< card title="Scannable" subtitle="Short headings, compact cards, and clear sidebar labels." tag="UX" tagColor="blue" >}}
  {{< card title="Documentation First" subtitle="Every section supports reading, search, reference, or contribution." tag="Docs" tagColor="green" >}}
  {{< card title="Academic Calm" subtitle="Restrained colors, precise spacing, and focused content density." tag="Style" tagColor="purple" >}}
{{< /cards >}}

## Mock Dashboard

<div class="rmh-dashboard">
  <div class="rmh-panel rmh-panel-wide">
    <span>Proposal readiness</span>
    <strong>82%</strong>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer nec odio.</p>
  </div>
  <div class="rmh-panel">
    <span>Topics</span>
    <strong>24</strong>
    <p>Sed cursus ante dapibus diam.</p>
  </div>
  <div class="rmh-panel">
    <span>Reviews</span>
    <strong>09</strong>
    <p>Praesent mauris fusce nec.</p>
  </div>
  <div class="rmh-panel rmh-panel-wide">
    <span>Workflow status</span>
    <div class="rmh-progress"><i style="width:68%"></i></div>
    <p>Curabitur sodales ligula in libero. Sed dignissim lacinia nunc.</p>
  </div>
</div>

## Component Tabs

{{< tabs >}}
  {{< tab name="Cards" selected=true >}}
  Use cards for repeated resources, domain previews, contributor summaries, methodology options, and proposal sections.
  {{< /tab >}}
  {{< tab name="Callouts" >}}
  Use callouts for placeholder notices, review warnings, contribution reminders, and academic caveats.
  {{< /tab >}}
  {{< tab name="Tables" >}}
  Use tables for method comparison, scope constraints, artifact matrices, and milestone summaries.
  {{< /tab >}}
{{< /tabs >}}

## Status Badges

{{< badge content="Draft" color="amber" >}} {{< badge content="Reviewed" color="green" >}} {{< badge content="Placeholder" color="blue" >}} {{< badge content="No real claims" color="purple" >}}

## Quote Treatment

> Lorem ipsum dolor sit amet, consectetur adipiscing elit. The best documentation pages create trust through structure before asking readers to trust the content.

## Collapsible UI Notes

{{% details title="Spacing system" closed="true" %}}
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Use consistent vertical rhythm, compact sections, and generous reading width.
{{% /details %}}

{{% details title="Responsive behavior" closed="true" %}}
Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Cards collapse cleanly and panels keep stable dimensions.
{{% /details %}}

## Frontend Snippet

```html
<section class="research-card">
  <p class="eyebrow">Placeholder method</p>
  <h3>Lorem Ipsum Evaluation</h3>
  <p>Academic-style demo copy for a methodology resource card.</p>
</section>
```
