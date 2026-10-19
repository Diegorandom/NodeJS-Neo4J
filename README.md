# Quoting tool on Neo4j

An industrial-products quoting app: a Node.js server over a **graph database**, modelling products, components and prices as relationships instead of join tables.

- `index.js` — Express server · `Notas de desarrollo` — design notes · `cotizacion.pdf` — sample output
- `out.csv` — exported quotes

**Context:** 2017–2018. The reason it is worth keeping is the modelling exercise: a quote is a path through a graph, and storing it as one changes every query on the page.
