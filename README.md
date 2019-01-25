# hex2bin_exec
Simplle firmware file converter from Intel Hex to binary format.

This program provides to convert Intel Hex files to custom binary files with .efa extension. Output file contains header and custom 128 bytes blocks with CRC16 at the end of each block. Header includes firm name, board version, size of firmware and CRC16. To convert file choose .hex file and enter the board version (4 bytes).
