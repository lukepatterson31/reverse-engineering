# Reverse Engineering
Reverse engineering course notes

## Cheetsheat

Mona:

Find EIP offset from cyclic values
`!mona findmsp -distance <VALUE-LENGTH>`

bytearray
`!mona bytearray -cpb "\x00"`

Find badchars
`!mona compare -f C:\mona\process -a esp`

Find jump point
`!mona jmp -r esp -cpb "\x00"`

Find ASLR protection
`!mona modules`
