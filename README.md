<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/GraphQL_Logo.svg/512px-GraphQL_Logo.svg.png" width="100" alt="graphql logo"/>
</p>

# Cascadia GraphQL

Welcome! We're really glad that you're here. Below you'll find all of the resources that we'll use throughout this course. If you're looking for slides, samples, links, etc., this is the place to look.

## Instructor Info

- **Eve Porcello**: [Twitter](https://twitter.com/eveporcello) | [Email](mailto:eve@moonhighway.com)
- **Moon Highway Training**: [Moon Highway Website](https://www.moonhighway.com) | [Mailing List](http://bit.ly/moonhighway) | [Articles](https://www.moonhighway.com/articles)

## Unions and Interfaces

- [Unions & Interfaces Slides](https://slides.com/moonhighway/unions-interfaces)
- [Refactored Pet Library](http://funded-pet-library.moonhighway.com/)
- [Union Types](https://codesandbox.io/s/rm2rx3opqm)
- [Interfaces](https://codesandbox.io/s/71x8n304r1)
- [Event Interfaces](https://codesandbox.io/s/mm36pp93p9)
- [Union Search - Start](https://github.com/graphqlworkshop/snowtooth-unions/)
- [Employee Interface](https://github.com/graphqlworkshop/interface-lab)

## Microservices with Apollo Federation

**Slides**

- [GraphQL at Scale](https://slides.com/moonhighway/scale-cube/)
- [Apollo Federation Lab Challenge](https://slides.com/moonhighway/federation-lab)

**Samples**

- [Hue Review: Start Files](https://github.com/graphqlworkshop/hue-review-activity)
- [Hue Review: Finished Files](https://github.com/graphqlworkshop/hue-review-activity/tree/complete)
- [Snowtooth Federation Lab: Start Files](https://github.com/graphqlworkshop/snowtooth-federation-lab)

**Resources**

- [Apollo Federation - Apollo Docs](https://www.apollographql.com/docs/apollo-server/federation/introduction/)
- [egghead Playlist - Apollo Federation by Alex Banks](https://egghead.io/playlists/getting-started-with-apollo-federation-60ad0165)
- [Apollo Federation Blog](https://blog.apollographql.com/apollo-federation-f260cf525d21)
- [Managed Federation Blog](https://blog.apollographql.com/announcing-managed-federation-265c9f0bc88e)
- [Advanced Federation Features](https://www.apollographql.com/docs/apollo-server/federation/advanced-features/)
- [Migrating from Schema Stitching](https://www.apollographql.com/docs/apollo-server/federation/migrating-from-stitching/)

## Apollo Studio

- [Apollo Studio - Student Challenge](https://slides.com/moonhighway/graph-manager/)
- [TypeScript & Apollo CLI - Finished Project + Instructions](https://github.com/graphqlworkshop/snowtooth-typescript)
- [Snowtooth API](https://snowtooth.moonhighway.com)
- [Lift Manager Sample Client Code](https://github.com/eveporcello/lift-manager/blob/master/src/index.js)
- [Lift Manager Website](https://lift-manager.netlify.com)
- [Big Basin Sample Client Code](https://github.com/eveporcello/big-basin/blob/master/src/index.js)
- [Big Basin Website](https://big-basin.netlify.com)
- [Snowtooth Project Repo](https://github.com/moonhighway/snowtooth)
- [Client Side Mocking - CodeSandbox](https://codesandbox.io/s/client-mocking-epqmp)
- [Apollo REST Data Sources](https://github.com/MoonHighway/countries-datasources)
- [Batch Link](https://github.com/eveporcello/batching)

**Commands to Copy/Paste**

_Sample Engine API Key_

`ENGINE_API_KEY=service:eveporcello-6318:RQYT_LtqhrYG8Taw7ORtzA`

_Download the Schema_

`npx apollo schema:download --endpoint=https://snowtooth.moonhighway.com graphql-schema.json`

_Generate Types_

`npx apollo codegen:generate --localSchemaFile=graphql-schema.json --target=typescript --includes=src/**/*.ts --tagName=gql --addTypename --globalTypesFile=src/types/graphql-global-types.ts types`

## Relay

- [Pet Library Demo](https://github.com/eveporcello/pet-library-demo/)
