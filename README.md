# Claude Cowork Plugins for Dobbies

A curated marketplace of Claude Cowork plugins for academic research.

## Plugins

| Plugin | Description | Auth Required |
|--------|-------------|:---:|
| [scopus-plugin](https://github.com/Yumbang/scopus-plugin) | Search Scopus for papers, authors, and citations via Elsevier API | Yes (API key) |
| [crossref-plugin](https://github.com/Yumbang/crossref-plugin) | Search CrossRef metadata registry for papers and DOIs | No |
| [zotero-plugin](https://github.com/Yumbang/zotero-plugin) | Query Zotero library and import CrossRef results | Local Zotero |
| [korea-patent-plugin](https://github.com/Yumbang/korea-patent-plugin) | Search Korean patent database (KIPRIS) | TBD |

## Installation

Install the marketplace, then install individual plugins:

```bash
/plugin install-marketplace Yumbang/claude-cowork-plugins-for-dobbies
/plugin install scopus-plugin
```

Or install a plugin directly from its repo:

```bash
/plugin install Yumbang/scopus-plugin
```

## Plugin Overview

### Scopus Plugin
Search the Elsevier Scopus database — find papers by keyword, author, or affiliation, retrieve abstracts and citation data, and export results as CSV or BibTeX.
- Requires a free Scopus API key from [dev.elsevier.com](https://dev.elsevier.com/)
- Institutional token optional for full-text access

### CrossRef Plugin
Search 150M+ DOIs from the CrossRef open metadata registry. No API key needed — just provide your email for higher rate limits (polite pool).

### Zotero Plugin
Query your local Zotero library for paper metadata. Import results from the CrossRef plugin directly into Zotero collections.
- Requires Zotero desktop app running locally

### Korea Patent Plugin
Search the Korean Intellectual Property Rights Information Service (KIPRIS) for patent documents.

## License

MIT
