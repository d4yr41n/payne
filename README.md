# log2

It's insane but beautiful, at least for me.

## Values

- #1f1f1f (background/text)
- #3f3f3f
- #7f7f7f
- #efefef
- #bfbfbf (text/background)

## Calculations

We use index, because min value is 0 and max - 255.

- 2 ^ 5 = 1f (32nd value of hex)
- 2 ^ 6 = 3f (64th)
- 2 ^ 7 = 7f (128th)
- 2 ^ 8 - 2 ^ 4 = ef ((256-16)th)
- 2 ^ 8 - 2 ^ 6 = bf ((256-64)th)
