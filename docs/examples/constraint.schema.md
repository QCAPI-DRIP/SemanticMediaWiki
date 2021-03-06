Examples of schema definitions that can be mixed or created as separate schemata and assigned to property.

## Must exists

```json
{
    "type": "PROPERTY_CONSTRAINT_SCHEMA",
    "constraints": {
        "must_exists": true
    },
    "tags": [
        "property constraint",
        "must exists"
    ]
}
```

## Single value

Properties such as `place of birth` or `maternity hospital` are prime examples where only a `single` value is expected to exists for a person entity.

```json
{
    "type": "PROPERTY_CONSTRAINT_SCHEMA",
    "constraints": {
        "single_value_constraint": true
    },
    "tags": [
        "property constraint",
        "single value"
    ]
}
```

## Non negative

```json
{
    "type": "PROPERTY_CONSTRAINT_SCHEMA",
    "constraints": {
        "non_negative_integer": true
    },
    "tags": [
        "property constraint",
        "integer",
        "number"
    ]
}
```

## See also

- [`property.constraint.md`](https://github.com/SemanticMediaWiki/SemanticMediaWiki/blob/master/src/Schema/docs/property.constraint.md)