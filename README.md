# Zero to Prod

## Useful commands

    cargo watch -x check -x test -x run

    docker run -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=password -e POSTGRES_DB=newsletter -p "5432:5432" -d postgres postgres -N 1000

    sqlx migrate run --database-url postgres://postgres:password@127.0.0.1:5432/newsletter
