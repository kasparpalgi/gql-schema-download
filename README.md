# Download GraphQL remote schema with NodeJS

1. `npm install -g gq-cli`
2. Example: `gq http://localhost:1337/v1/graphql -H 'x-hasura-admin-secret: myadminsecretkey' --introspect > C:\git\tools\gql-schema-download\schema.graphql`