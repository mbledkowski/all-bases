# All numerical bases
### Repository with as many number systems as possible. Feel free to contribute.
#### By saying "ASCII printable characters", I meant printable characters without Space [SP, 0x20] and Delete [DEL, 0x7F]
#### Inspired by
 * https://en.wikipedia.org/wiki/Base64
 * https://en.wikipedia.org/wiki/List_of_numeral_systems
 * and by my own needs
1. # Base64 - Tetrasexagesimal
    1. Privacy-Enhanced Mail (PEM; RFC 1421; deprecated)
    1. Transfer encoding for MIME (RFC 2045)
    1. RFC 4648 (previously, RFC 3548; standard)
    1. Radix-64 for OpenPGP (RFC 4880)
        * Plain text
        ```
        ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/=
        ```
    1. YouTube video ID
        * Plain text
        ```
        ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789-_
        ```

# Base92 - Duononagesimal
#### Using all of ASCII printable characters except for "`` ` ``" and "`"`"
> Plain text
```
0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ!#$%&'()*+,-./:;<=>?@[\]^_{|}~ 
```
# Base93 - Trinonagesimal
#### Using all of ASCII printable characters with Space, except for "`,`" and "`-`"
##### http://kiwigis.blogspot.com/2013/09/base-93-integer-shortening-in-c.html
> Plain text
```
0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ !?"'`^#$%@&*+=/.:;|\_<>[]{}()~
```
> Python
```python
base93str = '0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ !?"\'`^#$%@&*+=/.:;|\_<>[]{}()~'
```
# Base94 - Tetranonagesimal
#### Using all of ASCII printable characters
> Plain text
```
0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ!"#$%&'()*+,-./:;<=>?@[\]^_`{|}~
```
# Base95 - Pentanonagesimal
#### Using all of ASCII printable characters and Space
> Plain text
```
0123456789abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ!"#$%&'()*+,-./:;<=>?@[\]^_`{|}~ 
```


Sources:
https://en.wikipedia.org/wiki/Base64, https://en.wikipedia.org/wiki/List_of_numeral_systems, https://www.systutorials.com/4670/ascii-table-and-ascii-code/
