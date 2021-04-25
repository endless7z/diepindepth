# Build Archives
Although the goal is to be able to fetch and parse all data from any build at any time, we still keep some data archived.

Abstract Format:
```py
utf8(build) length=40 or 20 # build hash
[
  ...{
    u8(entry type id)
    bytes[u32(entry data size)] # bytes are to be read based on the entry type
  } # entries are read until the magic bytes (size - 4)
]
utf8("ABC\xFF") # magic bytes at the end
```