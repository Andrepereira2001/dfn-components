## Start local candid-ui

`dfn-components\packages\candid-ui` -> `npm start`

## Start local canister

In folder `.\test` -> `dfx build` -> `dfx start --background`

## Setup canister id

In `CandidUI.ts` l.689 `const candidCanister = this.#isLocal` make sure to have local control canister id.
In `index.html` l.10 `<candid-ui canisterId="..." logLevel="debug" >` make sure to have the backend canister id.

## Questions

Funciona com **module** mas não com **actor** pq? `$(dfx cache show)/mo-doc`
Como vejo os comentarios no codigo compilado?? Quais são a version notes disso?
