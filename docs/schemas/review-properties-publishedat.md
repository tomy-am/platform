# Untitled string in Review Schema

```txt
https://platform.codeclimate.com/schemas/review#/properties/publishedAt
```

The time this review was published


| Abstract            | Extensible | Status         | Identifiable            | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                                           |
| :------------------ | ---------- | -------------- | ----------------------- | :---------------- | --------------------- | ------------------- | ------------------------------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | Unknown identifiability | Forbidden         | Allowed               | none                | [Review.schema.json\*](../../spec/schemas/Review.schema.json "open original schema") |

## publishedAt Type

`string`

## publishedAt Constraints

**date time**: the string must be a date time string, according to [RFC 3339, section 5.6](https://tools.ietf.org/html/rfc3339 "check the specification")
