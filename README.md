### Hi, I'm Jaret 👋

PhD student in **Genetics, Bioinformatics & Computational Biology** at Virginia Tech ([Wright lab](https://sites.google.com/vt.edu/wrightlab), co-advised by [David Haak](https://spes.vt.edu/faculty-staff/faculty/haak-david.html)). I work on plant genomics and plant computer vision, and I build the MCP servers and CLI tools I use to do that research with LLMs.

#### 🌱 Research

- **PhD work:** auxin / ARF genomics and RNA-seq differential expression.
- **[orchid-clip](https://github.com/musharna/orchid-clip)**: a BioCLIP 2 fine-tune for orchid identification. The [demo](https://huggingface.co/spaces/musharna/orchid-genus-id) reports a genus and names a species only when it is confident. [Write-up](https://musharna.github.io/projects/OrchidCLIP/).
- **Undergraduate research** (Case lab, Kent State): leaf measurement and whole-plant silhouettes from _Lobelia_ herbarium specimens. [Write-up](https://musharna.github.io/projects/LobeliaSilhouettes/).

#### 🧬 Tools for genomics research

To try one: `uvx plant-genomics-mcp` starts a server, and each repo's README has the one-line config for Claude Code or any other MCP client.

- **[plant-genomics-mcp](https://github.com/musharna/plant-genomics-mcp)** [![PyPI](https://img.shields.io/pypi/v/plant-genomics-mcp)](https://pypi.org/project/plant-genomics-mcp/) — 50+ genomics tools over 23 backends (Ensembl Plants, Phytozome, UniProt, AlphaFold DB, JASPAR, KEGG, …).
- **[data-aggregator-mcp](https://github.com/musharna/data-aggregator-mcp)** [![PyPI](https://img.shields.io/pypi/v/data-aggregator-mcp)](https://pypi.org/project/data-aggregator-mcp/) — search and fetch datasets from Zenodo, DataCite, GEO/SRA, PubMed and OpenAIRE through one interface.
- **[plantcv-mcp](https://github.com/musharna/plantcv-mcp)** [![PyPI](https://img.shields.io/pypi/v/plantcv-mcp)](https://pypi.org/project/plantcv-mcp/) — PlantCV trait measurements, returned together with the segmentation overlay so you can check them.
- **[breedsim-mcp](https://github.com/musharna/breedsim-mcp)** [![PyPI](https://img.shields.io/pypi/v/breedsim-mcp)](https://pypi.org/project/breedsim-mcp/) — breeding-scheme simulation with AlphaSimR. Reports mean, sd and CI across replicates.
- **[phylokit-mcp](https://github.com/musharna/phylokit-mcp)** [![PyPI](https://img.shields.io/pypi/v/phylokit-mcp)](https://pypi.org/project/phylokit-mcp/) — phylogenetic inference with IQ-TREE 2, with bootstrap support included.
- **[taxon3d](https://github.com/musharna/taxon3d)** — blind comparison benchmark for AI-generated 3D models of organisms, judged against reference photographs.

#### 🛠 Tools for doing research with LLMs

- **[ghostcite](https://github.com/musharna/ghostcite)** [![PyPI](https://img.shields.io/pypi/v/ghostcite)](https://pypi.org/project/ghostcite/) — checks author/year against the DOI's CrossRef record and flags retractions. No LLM involved. Runs as a pre-commit hook or GitHub Action.
- **[llm-panel](https://github.com/musharna/llm-panel)** [![PyPI](https://img.shields.io/pypi/v/llm-panel)](https://pypi.org/project/llm-panel/) — send one question to several LLMs, see all the answers, then let them rebut each other anonymously.
- **[jobd](https://github.com/musharna/jobd)** [![PyPI](https://img.shields.io/pypi/v/jobd)](https://pypi.org/project/jobd/) — a small job broker for your own machines. Routes by GPU/tool tags and exposes the queue over MCP.

#### 📫 Find me

[musharna.github.io](https://musharna.github.io) · [Hugging Face](https://huggingface.co/musharna) · ORCID [0009-0003-4055-5238](https://orcid.org/0009-0003-4055-5238)
