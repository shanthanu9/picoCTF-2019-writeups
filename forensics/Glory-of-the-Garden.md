# Glory of the Garden

Points: 50

## Question

> This [garden](https://2019shell1.picoctf.com/static/86137520022d967547d5a2c99f4231f2/garden.jpg) contains more than it seems.

### Hint

> What is a hex editor?

## Solution

I use [Bless](https://github.com/bwrsandman/Bless) hex editor to view binary data for a file.

Open the given file in Bless and find for 'picoCTF' in the file. Remember to choose 'Find as text' option.

The flag happens to be at the end of the file.
