# Properties Schema

```txt
http://www.example.com/schemas/components/Button.json#/properties/properties
```

Properties of Button.


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                          |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | --------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [Button.json\*](Button.json "open original schema") |

## properties Type

`object` ([Properties](button-properties-properties.md))

# Properties Properties

| Property      | Type     | Required | Nullable       | Defined by                                                                                                                                                    |
| :------------ | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [type](#type) | `string` | Optional | cannot be null | [Button](button-properties-properties-properties-type.md "http&#x3A;//www.example.com/schemas/components/Button.json#/properties/properties/properties/type") |

## type

The type of the Button (not used for anchors).


`type`

-   is optional
-   Type: `string` ([Type](button-properties-properties-properties-type.md))
-   cannot be null
-   defined in: [Button](button-properties-properties-properties-type.md "http&#x3A;//www.example.com/schemas/components/Button.json#/properties/properties/properties/type")

### type Type

`string` ([Type](button-properties-properties-properties-type.md))

### type Constraints

**enum**: the value of this property must be equal to one of the following values:

| Value      | Explanation |
| :--------- | ----------- |
| `"button"` |             |
| `"submit"` |             |
| `"reset"`  |             |
