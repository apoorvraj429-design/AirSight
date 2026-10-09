# AirSight

Urban air-quality intelligence, from signal to informed action.

AirSight is an early-stage project by Apoorv Raj exploring how city teams could connect air-quality signals, source context and field-review workflows. The current Delhi NCR prototype runs entirely in the browser with simulated data.

## Current status

**Interactive prototype. No live data connectors, trained scientific models, operational integrations or Claude API calls are included.** All readings, source shares, confidence intervals, response times, performance scores and impact estimates in the demo are illustrative. They are not measured results.

## Explore

Open `index.html` for the project website, or `AirSight_Prototype.html` for the interactive demonstration. No installation or build step is needed.

For a local HTTP preview from the repository directory:

```sh
python3 -m http.server 8000
```

Then open `http://localhost:8000/`.

| View | What the prototype demonstrates |
| --- | --- |
| Command Center | Simulated city grid, station signals and episode playback |
| Source Attribution | Illustrative ward source mixes and evidence chains |
| Stubble Watch | Simulated plot lifecycle and burn-risk workflow |
| Enforcement | Mock priority queue, route, review status and downloadable demo evidence record |
| Forecast & Advisory | Illustrative ward forecasts and six language templates |

Dispatch and verification change browser memory only. Reloading resets the simulation. Downloaded evidence is a plain-text simulation record. No team is contacted, no legal action is taken and no model is retrained.

## Planned use of Claude

The proposed next step is a server-side assistant that turns approved, timestamped inputs into evidence-linked briefings and multilingual drafts for human review. Scientific models and data validation would remain separate from language generation. See [the implementation plan](docs/CLAUDE_PLAN.md).

## Project files

- `index.html`, `styles.css`: project website.
- `AirSight_Prototype.html`: canonical interactive simulation.
- `index.html.html`: compatibility redirect to the prototype.
- `privacy.html`: current prototype data-handling note.
- `AirSight_Architecture.png`: original concept diagram. Its metrics and “built” annotations are conceptual claims, not validated implementation evidence; use the status table above as the implementation record.
- [Launch guide](docs/LAUNCH_GUIDE.md): publication, domain and email setup.
- [Application copy](docs/APPLICATION_COPY.md): drafts grounded in the actual project.
- [Claude implementation plan](docs/CLAUDE_PLAN.md): proposed architecture, prompt and evaluation.

## Data and evaluation

The simulation uses hardcoded station values, source mixes, seeded pseudo-random plot records and illustrative forecast functions. References to CAAQMS, Sentinel, VIIRS/MODIS and IMD describe intended inputs, not active connections or partnerships. No validated backtest dataset, training pipeline or evaluation artefact is included.

Before operational use: secure data permissions, connect and quality-check sources, establish real baselines, validate models on held-out data, assess uncertainty and run a human-supervised pilot.

## Licence and contributions

The repository is publicly viewable. No open-source licence has been selected; public visibility alone is not a licence grant. The owner should confirm rights to all code and assets before choosing a licence. Do not describe this project as licensed open source until that is done.

For public, non-sensitive feedback, [open a GitHub issue](https://github.com/apoorvraj429-design/AirSight/issues). Please do not post personal information, credentials or operational enforcement records.
