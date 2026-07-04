# Chinook Sample

Welcome to the Chinook Sample workspace — Orchid's guided starter project. It walks you from
a first look at a relational schema all the way to revenue and customer-value analysis, using a
small, self-contained digital-music-store database. Every notebook ships with its results already
computed, so you can read the story end to end before running a single cell.

## What's inside

- **Chinook Sample — Quick Tour** — an orientation notebook that introduces the 11 tables, their
  relationships, and a few starter SQL queries.
- **Sales & Revenue** — total revenue, genre and country breakdowns, yearly trend, and a Plotly
  chart of where the money comes from.
- **Customers & Retention** — customer lifetime value, order counts, top-customer concentration,
  and a 60-month activity trend.
- **Analysis Notes.md** — plain-language observations about the dataset and its quirks.
- **report/chinook-report.tex** — a LaTeX revenue snapshot you can compile to PDF with pdflatex.
- **data/genre_revenue.csv** — revenue and units sold for every genre with sales.
- **data/top_customers.csv** — the ten highest-value customers by lifetime spend.

## How to use it

The SQL cells are pre-connected to the **Chinook (sample)** SQLite integration and ship with baked
results, so the notebooks render fully even before you run anything. Open the project in Orchid
desktop to re-run or edit any cell against the live database, or ask the agent to extend the
analysis — add a cohort breakdown, a new chart, or a fresh question of your own.

## Dataset

This workspace is built on the **Chinook database** by Luis Rocha
(github.com/lerocha/chinook-database), released into the public domain. Chinook models a digital
music store: artists, albums, tracks, playlists, customers, invoices, and staff. Note that this
bundled copy has had its invoice dates shifted so they span **2021–2025** rather than the original
range. Headline figures for this copy: **$2,328.60** in total revenue across **412 invoices** from
**59 customers**, over a catalog of **3,503 tracks**.
