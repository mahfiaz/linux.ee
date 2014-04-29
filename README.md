linux.ee
========

Tegu siis ilmselgelt katsega linux.ee saiti kambakesi hoida enamvähem värske ja viisakana.

Allpool arusaam kuidas seda projekti aidata for dummies (thats me)

Peamine, on leida paat, st teha fork.
Forgi teed veebis.

Oletame et git on sul mingi ime läbi seadistatud, siis edasi peale veebis forkimist läheb käsurealt umbes nii:

```
git clone git@github.com:SINUNIMI/linux.ee.git
```

Edasi tee seal mis meeldib. Ja kui saab hea, siis läed repo kataloogi ning ütled:

```
git add fail mida-mudisid-või-muutsid
git commit -m "mingi ilus lühikokkuvõte" 
```

Kui kõik läks hästi siis on sul nüüd giti veebis uus seis, koos asjakohaste märgetega.

See on koht, kus tuleks teha nüüd jällegi weebis pull request algupärasesse projekti. 
Kui algupärase projekti maintainer arvab, et see, mis sa tegid on hea, rahuldab ta sinu requesti ära ja maailm on ilus.

Mõnda aega vähemalt.. Kuni originaalprojektis midagi muudetakse ja sinu fork on ajast maas. 
Weebis ei paista olema (head?) moodust seda sünkida...

Siis lähed oma giti projektikataloogi ja ütled järgnevad maagilised sõnad:

```
git remote add upstream git@github.com:4nd3r/linux.ee.git
git pull upstream master
git push
```

ja sinu projekt veebis peaks olema jälle identne algupärase projektiga - kuni seda vahepeal jälle ei muudeta.




