# o9-glo: Global Scope Organization

Welcome to **o9-glo** — a unique GitHub organization that serves as the global scope representation for multiple GitHub Enterprises.

## What is o9-glo?

**o9-glo** is a meta-organizational structure that maps the global scope of multiple GitHub Enterprises onto itself as a GitHub organization. It provides a unified view and microcosm representation of distributed enterprise structures.

## The Microcosm Mapping Pattern

We use a novel approach to represent complex enterprise structures in a simplified, navigable format:

- **Enterprises** → GitHub Repositories (in o9-glo)
- **Organizations** (within enterprises) → Folders (in those repositories)
- **Repositories** (within orgs) → Files (in those folders)

### Example Structure
```
o9-glo/cog (repository representing cog enterprise)
├── 9cog/ (folder = organization)
│   ├── repo1.md (file = repository)
│   └── repo2.md
├── cogpy/ (folder = organization)
│   └── ...
└── README.md (enterprise overview)
```

## Our Enterprises

**o9-glo** currently maps three GitHub Enterprises:

### 1. [cog](https://github.com/o9-glo/cog) Enterprise
- **Organizations**: 4
- **Total Repositories**: 186
- Organizations include: 9cog, cogpy, corgent, orgitcog

### 2. [o9](https://github.com/o9-glo/o9) Enterprise
- **Organizations**: 3
- **Total Repositories**: 112
- Organizations include: e9-o9, o9-glo, o9nn

### 3. [RegimA](https://github.com/o9-glo/regima) Enterprise
- **Organizations**: 22
- **Total Repositories**: 181
- Organizations include: Regional organizations (RegimA-UK, RegimA-US, RegimA-EU, etc.), hyperholmes, rzonedevops

## The Self-Referential Mapping

Here's where it gets interesting: **o9-glo maps itself!**

Within the [o9 enterprise repository](https://github.com/o9-glo/o9), you'll find an `o9-glo/` folder. This is the self-referential mapping where o9-glo appears as an organization within the o9 enterprise microcosm. This creates a meta-structural loop where:

1. **o9-glo** is a GitHub organization (the global scope)
2. **o9** is an enterprise (represented as a repository in o9-glo)
3. **o9-glo** appears as an organization within the o9 enterprise (as a folder in the o9 repository)

This self-referential structure demonstrates how o9-glo serves both as:
- A **container** (the global organization holding enterprise mappings)
- A **member** (an organization within one of those enterprises)

## The .github Repository

This repository ([o9-glo/.github](https://github.com/o9-glo/.github)) is a special GitHub repository that:
- Defines the public organization profile
- Provides documentation about the o9-glo structure
- Serves as the entry point for understanding our global scope mapping

## Why This Matters

This structure provides several benefits:

1. **Unified View**: See all enterprises, organizations, and repositories in one place
2. **Navigability**: Easily browse complex multi-enterprise structures
3. **Documentation**: Each level (enterprise, org, repo) is documented with metadata
4. **Scalability**: New enterprises and organizations can be added seamlessly
5. **Self-Awareness**: The system maps its own structure, creating transparency

## Exploring the Microcosms

To explore our enterprise microcosms:

1. Visit the [cog repository](https://github.com/o9-glo/cog) for the cog enterprise structure
2. Visit the [o9 repository](https://github.com/o9-glo/o9) for the o9 enterprise structure (including o9-glo's self-mapping)
3. Visit the [regima repository](https://github.com/o9-glo/regima) for the RegimA enterprise structure

Each repository contains folders representing organizations, and files within those folders representing individual repositories, complete with statistics and metadata.

---

*Part of the o9-glo global scope representation*  
*Microcosm mappings are auto-generated and regularly updated*
