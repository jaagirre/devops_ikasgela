# Ikasgela sortzeko emandako pausuak

Karpeta honetan ikasgela eta ikasgai dseinatzerako emandako pausu guztiak gorde egiten dira

### Ikasgelaren github errepositorioaren sorkuntza

```
+Github erabiltzailea sortu

+Ikasgairako errepositorio bat sortu

+Ikasgaiako zure errepositorioa lokalki lan egiteko klonatu
git clone https://github.com/jaagibas/devops-ikasgela.git

+Errepositorioaren README.md fitxategia modifikatu eta github errepositorioa eguneratu.
    +Markdown editore moduan Visual Code erabili (Extentzioa Auto Markdown)
    +Ikasgelako oinarrikzo karpeta eta fitxategi batzuk sortu
    +Egindako lehen aldaketak github-ra eraman
    
    git pull (konprotabu up to date gauzen)
    git add . 
    git commit -am "Ikasgelaren oinarrikzo egitura/eskeletoa sortua"
    git push

    +Visual code instalatu git extentzioa

    +github erabiltzailea ezartzen
    git config user.email "jaagibas@gmail.com"
    git config user.email


```



###Ikasgelarekin elkartrukea edukitzeko pausuak
```
+Ikasgelaren Fork bat egin github webgunetik zuzenean 
[Fork tutoriala 1] (http://aprendegit.com/fork-de-repositorios-para-que-sirve/)
[Fork tutoriala 2](http://aprendegit.com/mantener-tu-fork-al-dia/)
[Fork Tutorial 3](http://aprendegit.com/que-es-un-pull-request/)
+Ondoren Fork-a lokalki klonatu
git clone https://github.com/jaagirre/devops_ikasgela.git
(jaagirre ikasle erabiltzailea da)

+Ondoren upstream sortu proiektu errealera PULL-REQUEST-ak egiteko
git remote add upstream https://github.com/jaagibas/devops_ikasgela.git

+Azkenik ondo eguneratu gure fork lokala upstream-a erabiliz, hau jaagirre@mondragon.edu (iakslea) egiten dugu.
git pull upstream master

+Eta behin lokalean dugularik eguneratuta dugularik , gure fork-era igo egiten dugu

git push origin master  (Orain @jaagirre fork-a eguneratuta dago)

+Ikasgelaren FORK-ean zure aldaketak egiteko branch bat sortu
git checkout master
git branch Ariketak_jaagirre
git push --all -u

+Ikasgela errealean "ariketak" deritzon karpetako ariketa0.md fitxategian zure github erabiltzailea, zure izen abizena , ikasgaiko ariketak  gordetzeko sortu duzuen github errepositorioaren URL-a eta errepositorioaren bertsioa idatzi. Horretarako PULL-REQUEST prosezua erabili.

+Orain brach berrian aldaketak egin Visual Code erabiliz. Kasu honetan @jaagirre github informazioa bere iaksgaiko proiektuarenerrepositorioaren URL-a jarriz. 
git commit -am "Ariketa/0.md fitxategira @jaagirre ikaslea gehituta. lehen mugarria eginda"
git push origin Ariketak_jaagirre

+Eta orain fork/merge-a egin , lokalean eta gero push egin
git checkout master
git merge Ariketak_jaagirre
git push origin master

+PULL_REQUEST
Esto lo realizamos mediante la web de git
@jaagirre realzia la peticion. Github analzia si hay conflicto
@jaagibas recibe el pull requets , con la información necesaria
@jaagibas acepta el pull request
```
### Bigarren praktika prestatzeko pausuak