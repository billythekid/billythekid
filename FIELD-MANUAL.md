<div align="center">

# The Regulator's field manual

<kbd>COWBOY</kbd> + <kbd>CODE</kbd> + <kbd>DARTS</kbd>

<sub>Fort Sumner's least conventional software department</sub>

</div>

<br>

<table>
  <tr>
    <td width="58%" align="center" valign="middle">
      <img src="./assets/billythekid-octocat.png" width="480" alt="Billy the Kid Octocat with a laptop, dartboard, and running haggis">
    </td>
    <td width="42%" valign="top">
      <h2>Billy the Kid</h2>
      <p><strong>Class</strong><br><code>cowboy-programmer</code></p>
      <p><strong>Companion</strong><br><code>one extremely mobile haggis</code></p>
      <p><strong>Current quest</strong><br>Change the world, pending source-code access.</p>
      <hr>
      <p>
        <kbd>⌘</kbd> <kbd>↵</kbd> ship it<br>
        <kbd>⌘</kbd> <kbd>Z</kbd> put it back<br>
        <kbd>180</kbd> pretend this happens regularly
      </p>
    </td>
  </tr>
</table>

> [!NOTE]
> Five tentacles are enough when one has a laptop, one throws darts, and the others are busy keeping a haggis out of production.

## Loadout

| Slot | Equipment | Condition | Notes |
| :--- | :--- | :---: | ---: |
| Head | Battered cowboy hat | `FIELD TESTED` | +10 authority |
| Eyes | Rectangular glasses | `REQUIRED` | +20 perception |
| Left hand-ish | Steel-tip dart | `ARMED` | 23g |
| Right hand-ish | Terminal | `CONNECTED` | `git status` |
| Ground support | Tartan haggis | `UNCONTAINED` | very fast |

## Match board

<table>
  <thead>
    <tr>
      <th align="left">Round</th>
      <th align="center">Target</th>
      <th align="right">Result</th>
      <th align="left">Official explanation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>01</code></td>
      <td align="center"><strong>20</strong></td>
      <td align="right">60</td>
      <td>Deliberate.</td>
    </tr>
    <tr>
      <td><code>02</code></td>
      <td align="center"><strong>BULL</strong></td>
      <td align="right">50</td>
      <td>Also deliberate.</td>
    </tr>
    <tr>
      <td><code>03</code></td>
      <td align="center"><strong>1</strong></td>
      <td align="right">1</td>
      <td>Dependency issue.</td>
    </tr>
    <tr>
      <td colspan="2"><strong>Total after three darts</strong></td>
      <td align="right"><strong>111</strong></td>
      <td><sub>No averages were harmed.</sub></td>
    </tr>
  </tbody>
</table>

## Release pipeline

```mermaid
flowchart LR
    A[Good idea] --> B[Write code]
    B --> C{Darts break}
    C -->|180| D[Ship it]
    C -->|26| E[Debug it]
    E --> B
    D --> F[Regulators saddle up]
```

> [!TIP]
> If the build fails, stare at the dartboard until causation becomes correlation.

<details>
  <summary><strong>Open the saddlebag</strong></summary>
  <br>
  <table>
    <tr>
      <th align="left">Inventory</th>
      <th align="center">Qty</th>
      <th align="left">Purpose</th>
    </tr>
    <tr>
      <td><code>git reflog</code></td>
      <td align="center">∞</td>
      <td>Time travel</td>
    </tr>
    <tr>
      <td>Rubber duck</td>
      <td align="center">1</td>
      <td>Senior architecture review</td>
    </tr>
    <tr>
      <td>Backup flight</td>
      <td align="center">3</td>
      <td>The carpet monster is undefeated</td>
    </tr>
    <tr>
      <td>Haggis treats</td>
      <td align="center">0</td>
      <td>Explains the current velocity</td>
    </tr>
  </table>

  <details>
    <summary><sub>There is a smaller pocket inside the saddlebag</sub></summary>

  - [x] Hat
  - [x] Darts
  - [x] Laptop
  - [ ] Permission to change the world

  </details>
</details>

## Palette

| Western leather | Neckerchief | Terminal | Background |
| :---: | :---: | :---: | :---: |
| `#7A431D` | `#9E3925` | `#66E58A` | `#BDEFF2` |

---

<div align="center">

<sup>Built from plain GitHub Flavored Markdown, a little permitted HTML, and unreasonable confidence.[^gfm]</sup>

**[Return to the profile](./README.md)**

</div>

[^gfm]: GitHub renders tables, alerts, collapsed sections, footnotes, task lists, syntax highlighting, diagrams, and a safe subset of HTML directly in Markdown files.
