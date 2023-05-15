GIT KOMANDE
ls - izlistava fajlove
cd - promjena direktorija 
mkdir - kreiranje foldera
git init - kreiranje praznog repositorija 
ls -la - provjerava fajlove unutar repositorija 
touch - kreiranje fajla
git status - provjeravanje statusa 
git add - da git prati sve izmjene na našem file-u
git add . - za pracenje svih novih fajlova (registrovani)

git remote add origin - za spajanje s udaljenim gitom s lokalnog 
git remote -v - za provjeru da smo dodali git repositorij
git commit -m  da pushujemo fileove na git
git push -u origin main - push files na remote gitu 
ako zelimo prebacivati s https kroz ssh moramo ukloni remove origin pa opet add origin za ponovno postavljanje

novi korisnik moze jednostavno iskopirati ssh kod prebaciti na url 
odnosno git clone naseg origina

potrebno je nekad neke izmjene na posebnu granu pa tek na main branch 

komanda git pull za povlacenje svega i sto je radio developer 1 i developer 2

git branch za provjeravanje na kojem smo branchu
a komandom checkout se prebacujemo na drugu granu 

za poredjenje izmjena koda koristimo pull request

da bismo mogli merge branch za pull request testiranje koda potrebno je merge pull request
