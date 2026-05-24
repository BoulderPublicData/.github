## Hi there 👋

We're **Boulder Public Data** — a small, volunteer effort to liberate and publish open code and data about Boulder, Colorado. We turn government records that arrive as PDFs, scanned images, hand-keyed spreadsheets, and proprietary export formats into tidy, documented, openly licensed datasets that journalists, students, researchers, advocates, and curious neighbors can actually use.

We believe public data should be *actually* public — machine-readable, well-documented, openly licensed, and durable enough to outlive whatever vendor contract, staff turnover, or website redesign would otherwise quietly retire it.

### What lives in this organization

This GitHub organization is the public home for our data liberation projects. Each repository pairs the code we used to acquire and clean a source with the resulting dataset, so anyone can reproduce, audit, or extend the work.

- **[Election-Results](https://github.com/BoulderPublicData/Election-Results)** — Code and data for cleaning and joining precinct-level statement-of-vote data from Boulder County elections.
- **[Cast-Vote-Records](https://github.com/BoulderPublicData/Cast-Vote-Records)** — Anonymized ballot-level records from historical Boulder County elections, restructured for analysis.
- **[City-Council-Members](https://github.com/BoulderPublicData/City-Council-Members)** — Records of who has served on Boulder City Council, with terms and other biographical details.
- **[City-Council-Minutes](https://github.com/BoulderPublicData/City-Council-Minutes)** — Source material and tooling for working with Boulder City Council meeting minutes.

New repositories tend to grow out of a specific question we couldn't answer with the records as published.

### How we work 🛠️

A few principles we try to hold ourselves to, borrowed from neighbors in the public-interest data world:

- **Open by default.** Code is released under the [MIT License](https://opensource.org/licenses/MIT), and data products under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/), unless an upstream source license forces something narrower.
- **Reproducible, not just public.** The pipeline that produced a dataset lives next to the dataset. If a script can be re-run to refresh a file from source, we prefer that to a one-off CSV dump.
- **Document the path back to the original.** Source URLs, retrieval dates, field-level data dictionaries, and known caveats live in the repo so future users — including us — don't have to guess where a number came from.
- **Privacy for individuals, sunlight on institutions.** Records that identify private people get anonymized or aggregated before publication; records of how public bodies and public officials act in their public roles get published as completely as possible.

### Get involved 🤝

- **Open an issue.** Found a row that looks wrong, a field that needs a definition, or a dataset Boulder ought to have? File it on the most relevant repository.
- **Send a pull request.** Fixes, new vintages, additional sources, and improved documentation are all welcome. Smaller, focused PRs are easier to review than big ones.
- **Suggest a dataset.** If there's a Boulder-area public record stuck inside a PDF or a vendor portal that you wish you could query, open an issue on this `.github` repository describing what you'd want and where it lives.
- **Reuse the data.** Cite it, link back, and tell us where it ended up — knowing how the data gets used helps us prioritize what to liberate next.

### Friends & neighbors 💞

A few of the people and organizations doing related work in and around Boulder and Colorado that we learn from and lean on:

- [City of Boulder Open Data](https://open-data.bouldercolorado.gov/) — the city's official open data portal.
- [Boulder County Open Data](https://opendata-bouldercounty.hub.arcgis.com/) — county-level geospatial and administrative data.
- [Colorado Information Marketplace](https://data.colorado.gov/) — statewide open records.
- [Boulder Reporting Lab](https://boulderreportinglab.org/) — civic journalism with a strong data bent.
- [CU Boulder Public Interest Data Science (CUPIDS) Clinic](https://www.colorado.edu/cmci/cupids) — the campus clinic that trains students in this kind of work.
- [Catalyst Cooperative](https://github.com/catalyst-cooperative) — a model for how to do public-interest data engineering, at a larger scale and on a different sector (US energy).

### Contact 💌

The best place to reach us is on the relevant repository's **Issues** tab. For anything that doesn't belong on a specific repo, open an issue on this [`.github`](https://github.com/BoulderPublicData/.github) repository.
