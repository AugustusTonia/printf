team work (by Abraham Adusei and Anthonia Akpan )
"printf" is the name of one of the main C output functions, and stands for "print formatted".
printf format strings are complementary to scanf format strings, which provide formatted input.
You can print all of the normal C types with printf by using different placeholders:

also add this line to ensure things are working 

**Prototype:** `int _printf(const char *, ...);`

## Examples

**String**

- Input: `_printf("%s\n", 'This is a string.');`
- Output: `This is a string.`

int (integer values) uses %d.

float (floating point values) uses %f.

char (single character values) uses %c.

character strings (arrays of characters, discussed later) use %s.
