Pollard rho Kangaroo & Quadratic-sieve Cuda
Pollard_s kangaroo-Windows 10, Ubuntu 18.04 LTS

For both the tame and wild kangaroo, the (i+1)st hop that the kangaroo takes, wi+1, is given by wi+1=wi⊕(H(wi+1)⊗G) Here, H is a hash function, ⊗ is scalar multiplication, and ⊕ is point addition on an elliptic curve, and G is a base point on the curve. You can also compute the distance di that each kangaroo travels after i steps, with d0=0 and di+1=di+H(wi). If you want to search for a discrete log in an interval [a,b], let the tame kangaroo lay N "traps", one at each hop. Then set the wild kangaroo loose, starting at bG. The hope is that the wild kangaroo will hop into a tame trap. If their paths intersect, we immediately have a solution to the ECDLP. program to find discrete logarithms using Pollard's lambda method for catching kangaroos. This algorithm appears to be the best. 

Tutorial PDF

File windows: Pollard_s kangaroo-Windows 10 run.bat pkangaroo.exe

Linux: File: Pollard_s kangaroo make all run ./pkangaroo 

https://en.wikipedia.org/wiki/Pollard%27s_kangaroo_algorithm

Demo 105Bit search
-----
pollaed-rho-kangaroo(105Bit).exe

pollaed-rho-kangaroo-V2-(105Bit).exe


FULL Code Cuda:
---------------

Cuda 10.1 Windows, Linux
------------------------
https://satoshidisk.com/pay/C7KL4U

Bitcoin challenge transaction: ~102 BTC total bounty to solvers!

Bitcoin puzzle transaction    

https://www.blockchain.com/btc/tx/08389f34c98c606322740c0be6a7125d9860bb8d5cb182c02f98461e5fa6cd15

-----------------------Bitcrack -------------------------

56 000000000000000000000000000000000000000000000000009d18b63ac4ffdf   
17aPYR1m6pVAacXg1PTDDU7XafvK1dxvhi

57 00000000000000000000000000000000000000000000000001eb25c90795d61c    
15c9mPGLku1HuW9LRtBf4jcHVpBUt8txKz

58 00000000000000000000000000000000000000000000000002c675b852189a21    
1Dn8NF8qDyyfHMktmuoQLGyjWmZXgvosXf

59 00000000000000000000000000000000000000000000000007496cbb87cab44f    
1HAX2n9Uruu9YDt4cqRgYcvtGvZj1rbUyt

60 0000000000000000000000000000000000000000000000000fc07a1825367bbe     
1Kn5h2qpgw9mWE5jKpk8PP4qvvJ1QVy8su

61 00000000000000000000000000000000000000000000000013C96A3742F64906     
1AVJKwzs9AskraJLGHAZPiaZcrpDr1U6AB

63 0000000000000000000000000000000000000000000000007CCE5EFDACCF6808     
1NpYjtLira16LfGbGwZJ5JbDPh3ai9bjf4

--------------------Bitcrack --END !!  -----------------------


--------------------Break-short-------------------------------       


65 000000000000000000000000000000000000000000000001A838B13505B26867     
18ZMbwUFLMHoZBbfpCjUJQTCMCbktshgpe

70 0000000000000000000000000000000000000000000000349B84B6431A6C4EF1     
19YZECXj3SxEZMoUeJ1yiPsw8xANe7M7QR

--------------------Pollard's kangaroo------------------------

75 0000000000000000000000000000000000000000000004C5CE114686A1336E07    
1J36UjUByGroXcCvmj13U6uwaVv9caEeAt

80 00000000000000000000000000000000000000000000ea1a5c66dcc11b5ad180     
1BCf6rHUW6m3iH2ptsvnjgLruAiPQQepLe

85 00000000000000000000000000000000000000000011720c4f018d51b8cebba8    
1Kh22PvXERd2xpTQk3ur6pPEqFeckCJfAr

90 000000000000000000000000000000000000000002ce00bb2136a445c71e85bf    
1L12FHH2FHjvTviyanuiFVfmzCy46RRATU

95 0000000000000000000000000000000000000000527a792b183c7f64a0e8b1f4     
19eVSDuizydXxhohGh8Ki9WY9KsHdSwoQC

100 000000000000000000000000000000000000000af55fc59c335c8ec67ed24826     
1KCgMv8fo2TPBpddVi9jqmMmcne9uSNJ5F
