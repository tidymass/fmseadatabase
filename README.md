# fmseaDatabases

Metabolite and Pathway Databases for fMSEA Analysis

## Installation

```r
# Install from GitHub
remotes::install_github("tidymass/fmsea_databases")
```

## Available Databases

### MS1 Databases (Total: ~1.7MB)
- `kegg_compound_ms1` - KEGG metabolite MS1 database (712KB)
- `hmdb_compound_ms1` - HMDB metabolite MS1 database (1.0MB)

### Pathway Databases (Total: ~3.6MB)
- `kegg_pathway` - KEGG metabolic pathways (608KB)
- `reactome_pathway` - Reactome metabolic pathways (736KB)
- `hmdb_pathway` - HMDB metabolic pathways (1.0MB)
- `imetpd_pathway` - IMet-PD metabolic pathways (1.0MB)
- `wiki_pathway` - WikiPathways database (240KB)

**Total package size: ~5.3MB**

## Usage

```r
library(fmseaDatabases)

# Load databases
data("kegg_compound_ms1")
data("kegg_pathway")

# List all available data
data(package = "fmseaDatabases")

# Use in fMSEA analysis
# ...
```

## Data Sources

- **KEGG**: Kyoto Encyclopedia of Genes and Genomes
- **HMDB**: Human Metabolome Database
- **Reactome**: Reactome Pathway Database
- **IMet-PD**: Integrated Metabolomics Pipeline for Drug Discovery
- **WikiPathways**: Community-curated pathway database