# MI Lottery Analytics

A standalone, cloud-deployable desktop-and-web analytical platform focused on localized statistical trends, position heat mapping, and historical tracking of Michigan Lottery draw sequences. Built intentionally around high-performance vanilla browser mechanics to operate inside modern desktop app execution contexts (such as Electron) or lightweight cloud staging ecosystems.

---

## 🎯 Platform Core Architecture

The single structural dashboard entry point utilizes a unified layout optimized for viewport containment (`100vh` tracking). It eliminates rendering pipeline bloat by running an asynchronous navigation runtime over modular views:

1. **Overview Dashboard:** Aggregates macro stats including sample metrics, schedule grids, and ticket pricing. Renders color-coded `🔥 Hot` and `🧊 Cold` statistical vectors dynamically calculated from mathematical generation arrays.
2. **Frequency Modules:** Tracks raw probability weighting charts natively styled to scale directly against the project’s contextual interface themes.
3. **Position Map (Heatmap):** Uses explicit multi-axis grid logic to cross-reference historical number occurrences by their exact horizontal ball drop index position.
4. **Smart Picks Engine:** Employs programmatic weighted probability sampling models to generate combination rows protected by automated constraint layers.
5. **Historical Ledger Tables:** Exposes a granular, structured data frame to review prior tracking sequences with full time-of-day query filtering.
6. **Regulatory Rule Frameworks ("How to Play"):** Integrates game instruction sets, step logic, odds documentation, and responsible gaming helpline layers.

---

## 🎲 Game Configuration Runtimes

The calculation framework is configured out-of-the-box to handle multiple game layout mechanics strictly matched to official state criteria:

* **Digit Matrices (`daily3`, `daily4`):** Fixed order multi-position calculations modeling localized digit spaces (`0-9`).
* **Standard Lotto Trackers (`fantasy5`, `lotto47`):** Non-repeating randomized sample distributions without replacement rules.
* **High-Volume Matrices (`keno`):** Specially engineered to calculate state-specific 22-ball draws pulled out of an 80-number universe.
* **Rapid Target Cycles (`cashpop`):** Focuses strictly on specialized isolated value spaces (`1-15`) running under condensed scheduling patterns.
* **Card-Rank Classifiers (`pokerlotto`):** Parses multi-suit deck logic array mappings (`52 cards`) to process instant hand evaluations.
* **Multi-State Jackpot Engines (`powerball`, `megamillions`, `millionaireforlife`):** Double-layer tracking structures evaluating high-range primary matrices against independent isolated bonus ball categories.

---

## 🔒 Integrated User Tier Verification

Features a self-contained profile tracking runtime backed by browser `localStorage` persistence. The system monitors access permissions globally:

* **Anonymous / Free Tier:** Standard utility access. The smart pick combination generator limits operations to a standard threshold. Attempts to increase sampling capacity display interactive barrier layers.
* **Premium Analytics Account ($9.99/mo):** Fully unlocks expanded generation pipelines up to 20 deep lines backed by complex weighting logic. Includes client-side credit card forms with built-in validation formatting masks.

---

## ⚙️ Automated Security Constraints

* **Rigid Content Security Policy (CSP):** Employs strict browser security policies right in the headers (`default-src 'self'`). It explicitly white-lists secure visual dependency channels (`cdnjs.cloudflare.com`, Google Fonts tracking paths, and AdSense domains) to systematically mitigate Cross-Site Scripting (XSS) risks.
* **IPC Inter-Process Bridge Ready:** Built with specific hooks to bind cleanly against local native runtime systems (`window.electronAPI`), allowing seamless file generation workflows (such as CSV data exports).

---

## 🚀 Deployment Instructions

### Local Development
To test or execute local UI variations, spawn a lightweight server context inside your directory:
```bash
# Using Python
python -m http.server 8000

# Using Node.js (if installed)
npx serve .
