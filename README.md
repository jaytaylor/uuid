# DEPRECATED DUE TO POOR RELIABILITY

## PLEASE DO DO NOT USE!

This package is deprecated due to my having observed it generating duplicate UUID's in the wild from `uuid.NewV4()`.

## Recommendation

The current recommended UUID package for go is [satori/go.uuid](https://github.com/satori/go.uuid).

### Also, RE: nu7hatch

If I could, I would also nuke [nu7hatch/go-uuid](https://github.com/nu7hatch/gouuid) from existence, as the core
of this package is identical to it.

