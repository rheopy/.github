# rheopy ⚗️

**Open rheology, end to end** — from curated measurements to guarded model fits
to in-browser exploration. Every tool ships with the knowledge to use it:
libraries bundle agent skills, docs stay in sync with code.

```mermaid
mindmap
  root((rheopy<br/>open rheology, end to end))
    ⚗️ rheofit
      Flow-curve fitting library
      models · guarded fitting · skill · browser app
    📊 rheodata
      Curated, quality-checked datasets
      training · simulation · benchmarking
    💻 rheolite
      JupyterLite playground
      rheofit walkthroughs in your browser
    🌊 rheoflow
      Non-Newtonian flow calculators
      pipes · slits · annuli
    📐 rheomodel
      Flow-curve model collection
```

## The pieces

| Repository | What it is |
|---|---|
| [rheofit](https://github.com/rheopy/rheofit) | ⚗️ Flow-curve fitting library: nine models, guarded fitting engine, an agent skill that ships with the package, and a browser fit app |
| [rheodata](https://github.com/rheopy/rheodata) | 📊 Pip-installable library of quality-checked rheology datasets — literature & community, each with provenance, sample and measurement metadata |
| [rheolite](https://github.com/rheopy/rheolite) | 💻 JupyterLite playground reproducing the rheofit walkthroughs entirely in the browser |
| [rheoflow](https://github.com/rheopy/rheoflow) | 🌊 Engineering calculators for non-Newtonian flow in pipes, slits and annuli |
| [rheomodel](https://github.com/rheopy/rheomodel) | 📐 Collection of rheology flow-curve models |

## Philosophy

*Ship the skill with the tool.* Each library carries its own agent skill and
documentation generated from the same source of truth — so the knowledge of
how to use it can never drift from the code itself. Data you cannot trust is
worse than no data; every dataset and every fit carries its provenance.
