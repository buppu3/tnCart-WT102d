## tnCart WT1.02d

This is just swapping the port numbers in the cst file.
I simplified it because I don't know what caused it not to work.

I have created 3 types of files.

### Runs at 27 MHz on-board(UMA module asynchronous).

[tnCart_WT102d_27MHz_async.fs](https://github.com/buppu3/tnCart-WT102d/raw/main/rtl/impl/pnr/tnCart_WT102d_27MHz_async.fs)

### Runs at 27 MHz on-board.

[tnCart_WT102d_27MHz.fs](https://github.com/buppu3/tnCart-WT102d/raw/main/rtl/impl/pnr/tnCart_WT102d_27MHz.fs)

### Runs on MSX 3.58 MHz clock(Boot loader reboots repeatedly and MSX may not boot).

[tnCart_WT102d_3_58MHz.fs](https://github.com/buppu3/tnCart-WT102d/raw/main/rtl/impl/pnr/tnCart_WT102d_3_58MHz.fs)
