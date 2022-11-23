It's fullform has changed from `yet another markup language` to `yaml ain't markup language`\
It is preferred from application.properties because of cleaner heirarchial syntax.\
yaml syntax is of key-value

### In application.properties
```
db.connection.port = 5000
```

### In application.yml
```
db:
  connection:
    port: 5000
```

In yaml, to indent use spaces, instead of tabs. - (Sometimes compiler can cry with tabs)\
yaml is intelligent enough to understand string and numbers, but if there are special characters in value, then make is string\
eg. `key: "{yo}"`