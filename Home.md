Welcome to the CommunityCodeReview wiki!

## Useful Snippets

Accessing the current Monticello commit and its ancestors:

```Smalltalk
(Morph>>#step) methodClass packageInfo workingCopy ancestry ancestors first ancestors first id
```
