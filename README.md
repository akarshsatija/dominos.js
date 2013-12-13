Instruction
=============

1. Navigate to Dominos pizza selection page.
2. Add 2 pizzas in the cart
3. Press `Ctrl + Shift + J` for Windows / `Cmd + Opt + J` for Mac
4. Paste the content of `dominos.js`
5. Sit back while the coupon is applied. (Might take a minute).


Advanced
=============

Type in `halt = true` to stop execution anytime.

If the coupons don't work, call `applyCoupon` manually with different parameter.


```
applyCoupon('e', 0);
```

Troubleshoot
=============

Make sure you set `halt = false` before calling `applyCoupon` function.
