git init - inicializirovat novii git repozitorii v tekushei papke.

git add . - proindeksirovat vse faili
git add <imya faila> - proindeksirovat odin fail.
git commit -m "text soobsheniya" (init ) - sohranit tekushuyu versiyu koda.

clear - ochistit terminal
ctr + L -analog clear
 cntr + c - prervat operaciyu v terminale

 ### text commitov
 init- inicialization(inicializaciya)
 upd- update (obnovlenie)
 fix- fix(izmeneniya)- (ispravleniya bagov)
 add- add(dobavlenie)
 ref- refactor(refaktoring)
 rm- remove(udalenie chegoto)

 git log - posmotret istoriyu comitov
 git log --oneline - (korotkaya istoriya comitov)
 git checkout id commita - (pereklyuchitsya na commit iz proshlogo)
vernutsya v tekushuyu vetku : git checkout master(imya osnovnoi vetki)
git remote add origin ssilka na git(hab) -privyazka k udalennamu repozitoriyu
git remote -v proverka privyazki k remote(udalennomu) repozitoriyu
git branch -M main pereimenovivaet vetku master v vetku main
git push -u origin main delaet push v udalennuyu vetku

git config-global init.defaultBranch main - 
delaet main vetkoi po umolchaniu(bila vetka master stala main)

git pull - "vlit" izmeneniya iz remove(udalennoi) vetki(main githab)
git checkout -b script  ()