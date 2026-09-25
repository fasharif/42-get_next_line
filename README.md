# get_next_line

This project now lives in **[42-Libft-C](https://github.com/fasharif/42-Libft-C/tree/main/get_next_line)**, as part of my C library, with tests at buffer sizes of 1, 42 and 10,000. This repository is kept as it was, for reference.

`get_next_line` returns one line at a time from a file descriptor; the bonus version reads from several descriptors at once. The version in libft also fixes an out-of-bounds write for file descriptor 256, and a leak when `read` fails.
