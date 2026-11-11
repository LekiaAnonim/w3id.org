# Prometheus canonical URLs

Permanent identifiers for the records of [Prometheus](https://pr.omethe.us/), a
database of combustion kinetic models, species, reactions, thermochemistry and
experiments.

| Identifier | Redirects to |
|---|---|
| `https://w3id.org/prometheus-kinetics/` | `https://pr.omethe.us/` |
| `https://w3id.org/prometheus-kinetics/<kind>/<key>` | `https://pr.omethe.us/id/<kind>/<key>` |

The key of a record comes from its chemistry or from an outside identifier
(InChIKey, DOI, ORCID iD, ROR ID), not from a database row number, so a rebuild
of the database keeps the identifiers. Examples:

- `https://w3id.org/prometheus-kinetics/species/XLYOFNOQVPJJNP-UHFFFAOYSA-N-1` (water)
- `https://w3id.org/prometheus-kinetics/source/10.1002/kin.20603` (Burke et al., H2/O2 model)

## Maintainers

- Lekia Prosper (GitHub: [@LekiaAnonim](https://github.com/LekiaAnonim))
- Richard West (GitHub: [@rwest](https://github.com/rwest))
