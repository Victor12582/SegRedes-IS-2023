## Objetivo
In RSA d is a lot bigger than e, why don't we use d to encrypt instead of e? Connect with `nc jupiter.challenges.picoctf.org 57464`.
## Solución
```python
c: 4594109242249574510086290920042046343586925575812298972906162840489790915559366213194224601811314135323408030611965431097547919041126015967829758120345776163652442180566775024329008806036214265264847491273430950878857240558050189596137551711980745555226974110885548099662309004178999837922097627223104595625
n: 143844292428190876160712145932895052307865692869106190580632296469081491164836168255328303750713468199562853518803708974931457514282304859386141533840010995690189501663457158326042240107301546865664398448528550797692264004795166979390434170033658114527019963177069344155246759229971764870392274204630204740423
e: 3933182355483437601354901284949691528994237173221818110693090548432092286302186757305771096041602987833081061166917107635033215826081302287562226355208503002609508759950178574506823085163051944700041846895184429479130591078841771372069052731342099034791201433807341002887739179067952244720275574133353029633

hex(pow(4594109242249574510086290920042046343586925575812298972906162840489790915559366213194224601811314135323408030611965431097547919041126015967829758120345776163652442180566775024329008806036214265264847491273430950878857240558050189596137551711980745555226974110885548099662309004178999837922097627223104595625.65537.143844292428190876160712145932895052307865692869106190580632296469081491164836168255328303750713468199562853518803708974931457514282304859386141533840010995690189501663457158326042240107301546865664398448528550797692264004795166979390434170033658114527019963177069344155246759229971764870392274204630204740423))
=
0x7069636f4354467b6261645f31643361355f323135323732307d
=
picoCTF{bad_1d3a5_2152720}
```
Tenemos que codificar en python un hexpow patra que nos de la bandera codificada y ya solamente la convertimos a ASCII 