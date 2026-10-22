# BA / PO Toolkit

Four browser-based tools for Business Analysts and Product Owners. Each tool opens with a worked example, runs entirely in the browser (no backend, no sign-up), and exports its results as Markdown or CSV for Jira, Confluence, Notion or Excel.

**Live demo:** https://viswanathan-paramasivan.github.io/ba-po-toolkit/

| Tool | What it does | Practices shown |
|---|---|---|
| [Backlog Prioritizer](backlog-prioritizer.html) | Scores backlog items with RICE or WSJF and compares the ranking between methods | RICE, WSJF (SAFe), data-driven prioritization |
| [Story Quality Checker](story-checker.html) | Checks user stories and Given/When/Then acceptance criteria against INVEST and flags untestable wording | User stories, BDD / Gherkin, INVEST, Definition of Ready |
| [Stakeholder Power Map](stakeholder-map.html) | Places stakeholders on a power/interest grid and generates an engagement plan | Stakeholder analysis (BABOK), communication planning |
| [Traceability Matrix Builder](traceability-matrix.html) | Links requirements → stories → tests, measures coverage and lists gaps | Requirements traceability (RTM), MoSCoW, test coverage |

## Why I built it

These tools turn the frameworks I use day to day into something you can try in a minute. They show how I approach prioritization, requirement quality, stakeholder engagement and scope coverage.

## Tech

- Plain HTML, CSS and JavaScript, one self-contained file per tool
- Light and dark mode, works on mobile
- Data is saved only in the visitor's browser (localStorage)

## Run it locally

Download the repository and open `index.html` in any browser. No build step is needed.

## Author

Viswanathan Paramasivan · [LinkedIn](https://www.linkedin.com/in/viswanathan-paramasivan)
