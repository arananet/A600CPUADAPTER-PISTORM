# A600CPUADAPTER-PISTORM
This simple adapter allows to relocate the pistorm to use it on an A600 and be able to properly close the case. It has been designed specially to use with the PISTORM board (Claude's Schwarz design).

# Images

<img src="https://github.com/arananet/A600CPUADAPTER-PISTORM/blob/main/images/1.png?raw=true" width="700">

# PCB information

2 layer board. Use your favorite pcb manufacturer to build this pcb using the gerbers available on the gerbers folder. Recommended PCB manufacturers: ALLPCB, JLCPCB and PCBWAY.

# Bom

|Name |Value|Footprint |
|-----|-----|--------- |
|C2	  |1uf	|C0805   |
|PWR  |RED  |LED0805 |
|R2   |220  |0805    |
|R3   |1k   |0805    |

In order to build your relocator, you will need 2 female pins and 1 PLCC68 socket. As for the pins, Here are the example references.

2x 1x40 male to female pins.

https://es.aliexpress.com/item/32854325182.html?spm=a2g0o.detail.1000060.2.350fada9Xv7nRh&gps-id=pcDetailBottomMoreThisSeller&scm=1007.13339.169870.0&scm_id=1007.13339.169870.0&scm-url=1007.13339.169870.0&pvid=9b1afe58-2a7a-4338-a981-ace8b2a98808&_t=gps-id:pcDetailBottomMoreThisSeller,scm-url:1007.13339.169870.0,pvid:9b1afe58-2a7a-4338-a981-ace8b2a98808,tpp_buckets:668%230%23131923%230_668%230%23131923%230_668%23888%233325%2314_668%23888%233325%2314_668%232846%238115%232000_668%235811%2327180%2341_668%232717%237567%23940_668%231000022185%231000066059%230_668%233468%2315613%23444_668%232846%238115%232000_668%235811%2327180%2341_668%232717%237567%23940_668%233164%239976%2356_668%233468%2315613%23444

PLCC68 socket (you will need to remove the internal plastic molds of the socket in order to avoid socket popup and sand a little bit too) (sorry but this as many other solutions is literally a hack).

https://es.aliexpress.com/item/32959126757.html?spm=a2g0o.productlist.0.0.6a3a30e5VRxVzE&algo_pvid=e67ce8d5-7d2f-4181-8a61-1c03062f6360&algo_expid=e67ce8d5-7d2f-4181-8a61-1c03062f6360-50&btsid=2100bdcf16230936838054620e444f&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_

# Update

07-06-2021 - Initial release.

# Note

This is a work in progress, more testing needs to be done, but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. USE AT YOUR OWN RISK!

If you like the project or want to support it, you can buy me a beer or a KO-FI :) 
[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H51MPWG)

# License

ATTENTION: This is for eBay sellers: this project was made for the retro community and not for resale on eBay. So only retro hardware forums and individual people can build this project. IT'S NOT FOR EBAY SALE.

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
