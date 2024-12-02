![Obrázok](./obrázok.png)

# 🐍 Užovka - slovenské programovacie nárečie! 🐍

Vitajťe, milí priateľja programovaňja! Užovka je programovacie nárečie podobné Pitónu, ale v šatách slovenskích, štúrovskích. Preložili sme moderné sintaksi do reči našich predkov, abi všetko znelo ako kebi [sťa] z pera samotného Ľudevíta Štúra, alebo tak dajako.

## Čo je Užovka?

Užovka je programovacie nárečie. Ak viete písať v nárečí Pitón, tak budete jednoducho vedijeť písať aj v nárečí Užovka. Keďže máte lásku k Štúrovi a zároveň radi kódíte, Užovka je pre vás ako stvorená! Všetki funkcije, operátori a vírazi sú stvorené do jednej staroslovenskej krási.

## Jak sa to inštaluje?

Najprv skopírujte zdrojoví kód Užovki:

```bash
git clone https://github.com/tzatko/Užovka.git
cd Užovka
```

Teraz viskúšajťe spustiť vaše programi v Užovke s príkazom:
```
./užovka súbor.🐍
```

# Príklad kódu v Užovke
Pozrime sa na jednoduchý príklad programu v Užovke, kde vipíšeme pozdrav:

```
# Ustanovenie funkcije, čo vipíše pozdrav
ustanoviť pozdrav():
    vipísať("Ahoj, svet!")

# Hlavní program
keďbi __meno__ rovnje "__hlavné__":
    pozdrav()
```
Jednoduchšja verzija je napísaná v súbore `ahojsvet.🐍`
Ďaľším praktickím príkladom je program v súbore `eratosthenes.🐍`. Ten vie spočítať prvích en prvočísel. Také pánske huncútstvo.

```
# Ustanovenie funkcije sito pre nájďeňje prvočísel do N
ustanoviť sito (N:celuo):
# Vitvoríme súpis pravďivuo hodnôt pre každé číslo až do N
    prvočísla=[pravďivuo] násobňe (N sčítať 1)

    # Začňeme pre 2, lebo 1 ňeje prvočíslo
    prvočísla[0]=ňič 
    prvočísla[1]=ňič 

    # Pre každé číslo od 2 do odmocnini N
    pre i v rozmedzie (2,celuo (N**0.5) sčítať 1):
    # Keďbi i je prvočíslo, odstráňime jeho násobki
        keďbi prvočísla [i]:
        # Pre každí násobok i od i^2 do N
            pre j v rozmedzie (i násobňe i,N sčítať 1,i):
                prvočísla [j]=nepravďivuo 

                # Vipíšeme všetki prvočísla
    vipísať ([i pre i v rozmedzie (N sčítať 1 ) keďbi prvočísla [i]])

# Hlavní program
keďbi __name__ rovnje "__main__":
# Požjadaj užívaťeľa o zadaňje hornej hranice N
    N=celuo (vipítaj ("Zadaj číslo N: "))

    # Zavolaj funkciju sito pre N
    sito (N)
```

Všimnime si, že namiesto `def` máme `ustanoviť`, namiesto `print` máme `vipísať`, a takto ďaľej. Váš kód teraz znie ako rozprava v reči slovenkej!

# Ukážka
![](demo.svg)

# Klúčové slová v Užovke
Užovka má svoje vlastné verzije známich Pitónovskích kľúčovích slov, napríklad:

| Užovka         | Pitón  |
|----------------|--------|
| ustanoviť      | def    |
| vipísať        | print  |
| navráťiť       | return |
| pravďivuo      | True   |
| nepravďivuo    | False  |
| ňič            | None   |
| sčítať         | +      |
| odčítať        | -      |
| násobňe        | *      |
| děliť          | //     |

Všetki slová prirovnané ku Pitónovím slovám sú zapísané v súbore `nárečja.čoh` a ako prípona súboru narieka, je to zapísané vo formáťe čiarkou odďelené hodnoti.

# Jak funguje prostredie vikonávaňia Užovki?
Prostredie vikonávaňia zaťjaľ funguje pomocou čara, čo všetki .🐍 súbori najskôr preloží do .pitón súborov a spustí ich cez vikonávač Pitónu. Užovka potom po sebe vičistí pitónové súbori – po skončeňí všetko čo je naviše zmizne ako dim!

```
./užovka noví_program.🐍
```

# Prispievajťe do Užovki
Máťe nové nápadi na zľepšenie vikonávacieho prostredia? Chcete zľepšiť nárečia a pridať nové kľúčové slová? Raďi privítame každého, kto bi rád prispel k slovnej zásobe Užovki! 

Našim vzňešením cieľom je dosiahnúť abi služobníctva vládi slovenskej Užovku užívali ako preferované nárečie pri tvorbe nového softvéru v štátnej správe.

# Dovolenije
Nie sme veru mi žiadňi fiškáli, ale bi sme použiľi GNU VVD - Všeobecné verejné dovoľeňije. Ňevjem ktorej verzije [:smutnik:].

# Slovo kurátora k obrázku
*Autor simboľicki viužíva farbi trikolóri spolu s vhodním víberom fontu ako referencije na slovenskí ľudoví puovod nárečia už z čias Ľudevíta Štúra. Sám Hurban sa o nárečí vijadril, citujem "Ci Pána, to ťi je janovô!". Hodža smaotné nárečie komentoval ako "Ja už v inôm písať aňi nedokážem.. žena mi to logo aj na košuľku višila, aha..." (ukazuje na obrázok višití krížikovím stehom na svojej konopnej košuľke)* Kredity patria [domineemu](https://github.com/dominee).

# Inšpirácia a odporúčaňja na iné zaujímavé projekťi

Toto programovacje nárečje bolo inšpirované i projektami tímito:

* [OSTRAJava](https://github.com/tkohout/OSTRAJava)
* [BRA Recursive Acronym](https://github.com/tzatko/BRA)
* [Šaral 2.0 - Šariš algorithmic language 2.0 implementation for JVM](https://github.com/PaulNoth/saral)

# Záverom
Virovnaj sa s tím!
![](Ludovit_Velislav_Stur_virovnaj_sa_s_tim-deal_with_it.jpg)
