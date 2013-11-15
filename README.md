If you like ledger (cli), and you own some bitcoin, instead of having to
manually input your transactions, I give you .. 'listtx' .. a perl program
that munges the output of 'listtransactions <account>' into ledger entries.

Example usage:

	listtx -a ttf -p 8336 -w ttf:coins -m Income:donations:forme
