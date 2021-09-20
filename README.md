<!-- markdownlint-disable -->
<p align="center">
  <a href="https://bhagavadgita.io">
    <img src="https://raw.githubusercontent.com/gita/bhagavad-gita-graphql/main/.github/gita.png" alt="Logo" width="300">
  </a>

  <h3 align="center">Bhagavad Gita GraphQL API</h3>

  <p align="center">
    Code for the BhagavadGita.io GraphQL API, which is an app built for Gita readers by Gita readers.
    <br />
    <br />
    <a href="https://github.com/gita/bhagavad-gita-graphql/blob/master/LICENSE">
    <img alt="LICENSE" src="https://img.shields.io/badge/License-MIT-yellow.svg?maxAge=43200">
  </a>
  <a href="https://gql.bhagavadgita.io/graphiql"><img src="https://img.shields.io/badge/docs-passing-green" alt="Docs"></a>
  <a href="https://starcharts.herokuapp.com/gita/bhagavad-gita-graphql"><img alt="Stars" src="https://img.shields.io/github/stars/gita/bhagavad-gita-graphql.svg?style=social"></a>
</p>


## Usage

The Bhagavad Gita GraphQL API allows any developer to use content from Gita in their apps.

Documentation for this API is available here: [GraphiQL UI](https://gql.bhagavadgita.io/graphiql)

## How it works?

We are using [PostGraphile](https://www.graphile.org/postgraphile/) to instantly spin up a GraphQL API from our PostgreSQL database.

## Projects

Here is a list of interesting projects using this API.

- [BhagavadGita.io](https://bhagavadgita.io)
- [Android App](https://play.google.com/store/apps/details?id=com.hanuman.bhagavadgita)

Have you build something with this API ? Open a "Show and tell" discussion. The maintainers will feature your project on the README if they find it interesting.

## Self Hosting
<!-- markdownlint-enable -->

The official API is free to use for all.
But If you wish you can self host anywhere you want.

If you want to deploy your own instance,You can deploy
the API server on your system or VPS using [`docker`](https://www.docker.com/):

  ```shell
  docker-compose -f docker-compose.prod.yml up --build -d
  ```

<!-- markdownlint-disable -->
Now open http://localhost:5433/graphiql to see the docs.
To stop the server, press <kbd>Ctrl</kbd> + <kbd>C</kbd> on your keyboard.
<!-- markdownlint-enable -->

## Configuration

Here is the list of supported environment variables.

<!-- markdownlint-disable -->
| Name                      | Description                           | Default                       |
| ------------------------- | ------------------------------------- | ----------------------------- |
| `DATABASE_URI`            | The DSN for your database connection. | `postgres://` (PostgresQL db) |
<!-- markdownlint-enable -->

To set the environment variables, you may simply use a `.env` file where you
specify the values in the format of `KEY=VALUE`.

## Development

Feel free to use the [issue tracker](https://github.com/gita/bhagavad-gita-graphql/issues)
for bugs and feature requests.

Looking to contribute code ? PRs are most welcome!

## Community

Join the [Discord chat server](https://discord.gg/gX8dstApZX) and
hang out with others in the community.

You can also use [GitHub Discussions](https://github.com/gita/bhagavad-gita-graphql/discussions)
to ask questions or tell us about
projects you have built using this API.
