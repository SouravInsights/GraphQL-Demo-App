GitHub GraphQL Sample App
=========================
This is a demo GitHub Graph QL API based app that shows whether a purticular user is hireable or not. It also shows whether an user is campus expert or not.

The Graph QL query for this app is as follows: 
```query {
  user(login: "souravinsights") {
    isHireable
    isCampusExpert
  }
}
```