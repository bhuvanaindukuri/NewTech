## Purpose
- Query language
- Meant for easy querying from different sources

### Core concepts
- Fields
   - Fields to be retreived
- Arguments
  - Filters for data to be retrieved Ex: last 3 
- Alias
  - Similar to alias in sql. Generally used when same part has to be repeated with different arguments Ex: firstEvents , lastEvents 
- Fragments 
  - Similar to a class and has the fields that can be reused
  <pre>
  fragment userInfo on User {
     id
     bio
     bioHTML
     avatarUrl
   }
  </pre>
- Variables
  - Can be used to pass parameters to the queries 
