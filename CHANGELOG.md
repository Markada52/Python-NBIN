## NBIN 1.1

**Update - new library!**

**Changes**:
1. Add functions `load` and `dump`
2. NBIN 1 specification created
3. Added corresponding types for Python

**Specification**:
1. Supported data types:
    * i8 - 1 sign byte
    * i16 - 2 sign bytes
    * i32 - 4 sign bytes
    * i64 - 8 sign bytes
    * u8 - 1 unsigned byte
    * u16 - 2 unsigned bytes
    * u32 - 4 unsigned bytes
    * u64 - 8 unsigned bytes
    * str - UNICODE string
    * bool - logical type
    * float - 32-bit fractional number
    * command - command
    * block - block with commands
    * list - not a typed list
    * null - no value
2. The length of any collection NBIN is a 32-bit unsigned number
3. Any NBIN object can be written in a binary file (it is not necessary that everything be wrapped in a block)
4. NBIN tries to support as many types as possible
5. NBIN types should satisfy both low-level and high-level programming needs


## NBIN 1.2

**New None/null**

* Fixing bugs and errors
* Python Command, list and Block objects can now be used with empty fields
