

### Description
Practice interview question not appearing elsewhere in the curriculum. Validation of byte values of stream as conforming with UTF-8 characters.

### Provided file(s)
* [`0-main.py`](./0-main.py)

---

## Mandatory Tasks

### :white_check_mark: 0. UTF-8 Validation
Write a method that determines if a given data set represents a valid UTF-8 encoding.

* Prototype: `def validUTF8(data)`
* Return: `True` if data is a valid UTF-8 encoding, else return `False`
* A character in UTF-8 can be 1 to 4 bytes long
* The data set can contain multiple characters
* The data will be represented by a list of integers
* Each integer represents 1 byte of data, therefore you only need to handle the 8 least significant bits of each integer



