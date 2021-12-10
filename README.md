## Prisma 2 SDL and Apollo Server 2

## migrate schema to database

this will take your schema and attempt to apply the changes to your database

prisma migrate commands:

- `prisma migrate dev`: Create a migration from changes in Prisma schema, apply it to the database, trigger generators (e.g. Prisma Client)
- `prisma migrate reset`: Reset your database and apply all migrations
- `prisma migrate deploy`: Apply pending migrations to the database in production/staging
- `prisma migrate status`: Check the status of migrations in the production/staging database
- `prisma migrate status --schema=./schema.prisma`: Specify a schema

project commands:

- `prisma migrate dev`: migrate your local sqllite file
- `yarn prisma studio`: Will open up a database manager

## Resources

- [Autogenerate GraphQL API from Prisma schema](https://www.youtube.com/watch?v=v6cNeHCfSHs&ab_channel=Prisma)
- [generator sdl !official](https://paljs.com/generator/sdl/)
- [prisma binding to sdl first](https://www.prisma.io/docs/guides/upgrade-guides/upgrade-from-prisma-1/upgrading-prisma-binding-to-sdl-first)
- [the guilds GraphQL Code Generator](https://www.graphql-code-generator.com/)
- [code generator getting started](https://www.graphql-code-generator.com/docs/getting-started)
