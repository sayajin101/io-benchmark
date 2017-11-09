# io-benchmark
Scripts to determine the best byte size to read &amp; write with

To determine the "BLOCK_SIZE=" variable in io-read.sh run blockdev --getbsz /dev/device
and replace the "BLOCK_SIZE=" with the result
