# Biomejs_config

```json
{
    "$schema": "./node_modules/@biomejs/biome/configuration_schema.json",
    "organizeImports": {
        "enabled": true
    },
    "formatter": {
        "indentStyle": "space",
        "indentWidth": 2,
        "lineWidth": 80
    },
    "javascript": {
        "formatter": {
            "arrowParentheses": "asNeeded",
            "jsxQuoteStyle": "double",
            "quoteStyle": "single",
            "semicolons": "asNeeded",
            "trailingCommas": "es5"
        }
    },
    "linter": {
        "enabled": true,
        "rules": {
            "recommended": true
        }
    },
    "files": {
        "ignore": [
            "node_modules"
        ]
    }
}
```
