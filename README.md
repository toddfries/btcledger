If you like ledger (cli), and you own some bitcoin, instead of having to
manually input your transactions, I give you .. 'listtx' .. a perl program
that munges the output of 'listtransactions <account>' into ledger entries.

Example usage:

	listtx -a ttf -p 8336 -w ttf:coins -m Income:donations:forme

Example output:

<pre>
; 7. txid 8b057fa1bb1e8d1e59543be54b8b34d9ebbb49d7b7c2656b7206372029419fa1
; 7. addr 1ttfD9CMYB67dp6Uj1hvE5kni8tGEmkQj
2013/11/12 20:58:44 coin
    Assets:Wallets:ttf:coins    BTC     0.00015000
    Income:donations:forme
</pre>
