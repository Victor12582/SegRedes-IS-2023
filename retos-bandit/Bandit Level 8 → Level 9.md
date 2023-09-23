## Level 8 → Level 9
## Objetivo
The password for the next level is stored in the file **data.txt** and is the only line of text that occurs only once
## Datos de acceso al nivel
```
bandit8
TESKZC0XvTetK0S9xNwm25STk5iWrBvP
```
## Solución
```bash
bandit8@bandit:~$ cat data.txt | sort | uniq -c
     10 08Jd2vmb6FjR4zXPteGHhpJm8A0OOA5B
     10 0dEKX1sDwYtc4vyjrKpGu30ecWBsDDa9
     10 0YDTDPCLc585IaFu911ukE9QfD6Ykrlz
     10 0zP9wfUcMKjZM2hiQUYR1nTfmaRdYSQE
     10 11FFcDRW5ZXXmX7geZORYRwiJfj8B3Gh
     10 1jZv2X1O2JypCBIgDNRwWQzS1CyhvByt
     10 1MUdfR7bGGCpNfGEOXaIEdrA8hT2L8Tk
     10 2fepTygKSkWHQJS2GrmGwjyl36eXSWJe
     10 3cTCUFe6MTl1FDAL0Z49cRByfq1MRlxJ
     10 3PB0nBOh1WKb1K6MImHdvwQjItFcxfdF
     10 3QXFsSepZUIOznxndwnQNnxvbpcXG05c
     10 47eFxPAuZ4tlWbT4P5ADs1tC0twlr51V
     10 4aOtDpqjXGIMOcyqirndla7J8S3jZZAy
     10 4Fi1Ig3hG4mDdl64v3gRPre3qNx26k0U
     10 4u67BT7FonRZeibEb9iOl6pHcMtzq03H
     10 6R258gRryXf9CBoG6erTEgGjb8ykWYrV
     10 7J5LX5IxjJ75DSStY7k9QTXgY8Hcygxu
     10 7rUrQcuUE8W3u7sHw6GqIw5KIm1vnvT0
     10 8fa6npI57h2Bc2yVSHJTKYwkGF1f25nm
     10 8mUGsbsFDyMVhqsbCIu5VQdKyNS6B4yK
     10 9b0fkcvfVG8ClmKfqmzFFSxszfYoGje3
     10 9rdQWtaWPaCwsiYUmcR7DZsTjlDzCIDk
     10 9uChpqBSAkMtOSNBVj1HAzRR5SQePFZe
     10 a6SMGsFpTKq8UGdndarh86o0ohHccjb0
     10 AWuhqidoTFNEaYmsX7njF8elfk6UTt8V
     10 Bap5iwr9yiz7NNLdn2pRIBDuzjS4apt6
     10 bbFQ44ZGHTUPiPEBvfADGWpwXzdhco23
     10 cBuyMeLeTl5bFQMjlzWIGHpbVwqQZkWQ
     10 cmtlazWcnfmS07dz52EdwhfVXD5hm8Ox
     10 DCEBvsEhDdFKdhuYgoK5615G0hkxkRbS
     10 dMNfFW0t7tDLsN6jM4t15q7sGdXIJlDO
      1 EN632PlfYiZbn3PhVK3XOGSlNInNE00t
     10 EoxGdakqWSJE03uzpJBLKabYEb5J458U
     10 eRgm0TR1FqHWaSneu0XDIC7r2MZVeLMU
     10 FJHGxIQ8lboC0UFsaF91voZjntUpyHPW
     10 FUx7SEMtclai0dBobiV7AbALW69gIBXZ
     10 FyYEOUkyJZD6zV0jpupw2KT8s82SRqMW
     10 gbvJah32y6gjm2AFPdOBRHJ8iCojKRrM
     10 gByqAo56n9wcRfMCkURoEB6JDzo0koeB
     10 H06jDLvch1Uq9N3QIOjHGmt1G34Gu5WM
     10 H8EBEqXygVzAE1hqQL8hmm5T5QC2D0rO
     10 HQxr86CUUjCkJw3NAMKRh58nsrrj0MvD
     10 hTG5ZZVYTMdjYXsfPkhvyoAmJjdq9C8P
     10 i2B5hPBHqvuFHFgKLtRAraOeCSnf0t2N
     10 I2Bcs4Rj9yrvTEjKhvLv0e5xZAiFKTN5
     10 I2Fe3M2fsgREVi1t7gsF7BUeii95f1vA
     10 i4nyRlk5UsNce0xutOfeTvK7LOmvQiqc
     10 iruOHH7XTt9nTI4Gx7siKujRGJjJjwSK
     10 ITQY9WLlsn3q168qH29wYMLQjgPH9lNP
     10 ixUopdQaDHWTH5oW0lqe17FmRIWemARs
     10 JddNHIO2SAqKPHrrCcL7yTzArusoNwrt
     10 JHuHJ4RkyqhV4yawJ4M7vztZYLQXmbyu
     10 JI1N2QF0ztjs2IXNOWCW4lkyMXN83xRJ
     10 jOtUiI3GKTuTNRl6BhEe2qdBHCdVJNLR
     10 kas4TO2Bk2KZgPbOqm1lCgwdv0X9Nu1L
     10 kbWzBlmQqHogFQlrHFwIXR4WDYOP0rzY
     10 kPs5Xm6uNWF7XmlOuAEMRYONR7cj8HvJ
     10 KzsSoDTds9Q8qA3uRuxg7og60JZ93tdA
     10 l4gvzZTw1FF3we43Vi4t6sSooCRHWnGW
     10 LHdCVT0iGyBfIK20to1WrWKMhJRmpW66
     10 lpRbCU2vMhGMRbAv65HhLyKEauDjtzeh
     10 lqxcTXcF9EuMgNF9J2TeEwKvz9ZoSGeZ
     10 LWbyPVHJfWrCcic0nuzZVWGnkiPq3mSo
     10 lzyn2IJxShNscaNmM8m5yQvViw5qluaU
     10 M14I2C6xu2tOmXvyWHIMuFaxktQOtIFs
     10 MDmXBu8iPJl03znbQctcHj8oCZbulXDS
     10 N2I3twf58Vw76J8n7sixyDqxKybAeUcQ
     10 NaOfWAtaagxr32dnqud7mkYeCsSH5BDB
     10 o7U2dEUFSCmddG7CGlgZxohaMKTBbTQ8
     10 OCIRfgKSXxjLD5YCbwGJBBg2OcOCvgxd
     10 pI3SEH0Rq3gd0sNEi8038Sh5SAtY1nrR
     10 QbKQeOYoUQULmEFOvagIzwC3EF2Gmu1S
     10 qeQlhBkJIQ9Yg7JSGavnLVpGXTTCSOyw
     10 QPghVHMln5b5ckZQQ4GrJkL69sCQCNp7
     10 QWiiBJhqUoMj0lCD9XNrkTM1M94eIPMV
     10 s00Iqlwp2FLBVu5yZFazJrpjypOL5sru
     10 S9dq4wwCTyH9TyUrDfO8bOVywef9rVsh
     10 s9wGQkxKUMfEW0ulhF1QuCfkK1x06RLZ
     10 TeLCC3zSYgKgI2wlYE2tO5vzaeEKkzXO
     10 TiXMHNCJEvOQyLXoZhDMdFpmXfR7orEU
     10 tpAGLljTdBsRqjZI9vIc3CpbaDAB9MTN
     10 tWedWHXUyRvVn4vH0I3zJcD3rdI48WrC
     10 txpoO5Sv4NR55wTu62j7uGlRKNxridyM
     10 uaKvbirBhTjHpZNhGKGgpuBygADEEOfo
     10 UkKkkIJoUVJG6Zd1TDfEkBdPJptq2Sn7
     10 UsCWtdouvPXeu6zkAx1dzviUyNnbEgCk
     10 uuax66Z7cDLABlBkrIMsqPUTyQDXsDqL
     10 Uy1DDzbL8hoD4nY8PHzSPbtkoJG9BKpO
     10 vmg8trbLZvXazswE0yEND17vH978enVX
     10 VOhHVQ6DG3wyFZoEYbfUMboYycjFeuDF
     10 vUazil5hHRQ63T0cQlfK5CV8MOrpDSBX
     10 W576pWH7nfuesidcso7OvqqviVVss1ms
     10 wiwZ8UvDRBE36vjUdEcK3g7KiOsQ2E2c
     10 wObmKQw05XwirIfvzToTNd7GZhkPeIfN
     10 WYU7r3ZVSfNk3WEvu5T7HDAAHIryHzNR
     10 XBrYZfQUBd5NJdAbSOG92hsfAEnhE8YO
     10 XHvIqr0IlONuOjXsOiHtDDuUk66tYJBY
     10 XK6pbTxxVhc0CSi7Y5rXtVkpWL4KdTTp
     10 yhJxWzo1jFPzfs1RP6cGonphKTjFVBXg
     10 YHtWBWO7CPN1EV2qcSnAtSl8Xi9kLtQI
     10 yvtL2C3x6iw7XOluSnoS1avXFUCsRSfg
bandit8@bandit:~$ cat data.txt | sort | uniq -u
EN632PlfYiZbn3PhVK3XOGSlNInNE00t
bandit8@bandit:~$
```

## Notas adicionales
Hay dos tipos de soluciones y el comando (uniq -u) me muestra el texto que solo es único y no se repite y (sort) los ordena por abecedario. Pero OJO para que funcione el uniq se tiene que ordenar alfabéticamente la listota de textos del cuyo quiera buscar.
## Referencias