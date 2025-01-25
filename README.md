<div>
  <h1 align="center">IMDb Non-Commercial Datasets Cleanup</h1>
  <h4 align="center">Cleanup IMDb Open Datasets for a Movies Watchlist Educational Project</h4>
</div>

## Motivation

Turn tabular data from IMDb Open Datasets into a relationship friendly structure.
Then this data is used to fill up database in our educational project: https://github.com/Jorgealvarezpb7/movies-watchlist.

## Run Locally

> Pickles, output CSV and input TSV files are not included in the repository.
> Refer to them in: https://huggingface.co/datasets/EstebanBorai/imdb-non-commercial

Build an run containers using `docker compose`

```bash
docker compose up --build notebook
```

> Using `Justfile` this is a matter of running `just build` and from
> there on `just dev`

After working you can release resources using:

```bash
docker compose down
```

> A [Justfile][1] is included!

[1]: https://just.systems
