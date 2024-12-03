# cleaned-musescore
An uBlock Origin filter list

Before:
![Before](bf.png)

After:
![After](af.png)

[filter code](cleaned-musescore.txt):
```txt
! 2024/12/03 update
! Hide discount banner
musescore.com##._sQKq

! Hide Recommended Course
musescore.com##section.RJd4n.g1QZl:nth-of-type(1)

! Hide upgrade to pro in sidebar
musescore.com##div.g1QZl.Bckv4.SqnhX:nth-of-type(1)

! Hide Why am i seeing this
musescore.com##.CgHMj.g1QZl.z03Al.hQ6hq.Bz0hi.AJXCt.ASx44

! Hide Start Free Trial
musescore.com##.u_VDg.utani.nOTLW.tDPQ9.HFvdW.o8abo.Mh_fD.A_Jr2.TtlUw

! Hide Scores Songbooks and Courses
musescore.com##.MXIPY > .g1QZl.TtJOf.oJw2k.lPCDt

! Hide Trending Search
musescore.com##.ifsT0

! Hide Go Pro
musescore.com##section.ehbCW.GgGe4:nth-of-type(1) > .WX4zB > a.u_VDg.zj781.Cl2SE.O9yD2.HFvdW.OX2Fm.uBrVm:nth-of-type(8)

! Hide your discount
musescore.com##.u_VDg.zj781.Cl2SE.O9yD2.HFvdW.undefined.OX2Fm.uBrVm

! Hide gift pro
musescore.com##section.ehbCW.GgGe4:nth-of-type(1) > .WX4zB > a.u_VDg.zj781.Cl2SE.O9yD2.HFvdW.OX2Fm.uBrVm:nth-of-type(3)

! Hide Try this score
musescore.com##.VQlJ3

! hide blank
musescore.com##div.g1QZl.GemQU.SqnhX:nth-of-type(2)

! Hide why am i seeing this
musescore.com##div.g1QZl.GemQU.SqnhX:nth-of-type(4)

! Hide mobile app in sidebar
musescore.com##div.g1QZl.GemQU.SqnhX:nth-of-type(12)

! hide unlock full access
musescore.com##.Pbc53

! Hide buttom ads
musescore.com##.g1QZl.s3Wga

! hide please rate this song
musescore.com##.FCSZc.KkvbQ
```
