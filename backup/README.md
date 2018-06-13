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

+Azkenik ondo eguneratu gure fork lokala upstream erabiliz

+Ikasgelaren FORK-ean zure aldaketak egiteko branch bat sortu

+Ikasgela errealera upstream bat sortu

+Ikasgela errealean "ariketak" deritzon karpetako ariketa0.md fitxategian zure github erabiltzailea, zure izen abizena , ikasgaiko ariketak  gordetzeko sortu duzuen github errepositorioaren URL-a eta errepositorioaren bertsioa idatzi. Horretarako PULL-REQUEST prosezua erabili.
```