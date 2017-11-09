# io-benchmark
Scripts to determine the best byte size to read &amp; write with
Original script author https://github.com/tdg5

To determine the "BLOCK_SIZE=" variable in io-read.sh run blockdev --getbsz /dev/device
and replace the "BLOCK_SIZE=" with the result
