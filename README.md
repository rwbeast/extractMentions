# extractMentions
Extract @mentions from a given string

This lib does not uses regex. it automatically handles punctuation marks like "." and "," etc.

```javascript

let str = `

  hello @name, welcome to @delhi! // [{name: "name", index: 6}, {name: "delhi", index: 24}]
  
`;

```
