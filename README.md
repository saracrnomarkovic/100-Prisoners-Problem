# Problem 100 zatvorenika i 100 kutija

Matematička i programska analiza poznatog problema „100 zatvorenika i 100 kutija“ korišćenjem teorije verovatnoće, permutacija, ciklusa i Python simulacija.

Repozitorijum sadrži:
- Jupyter notebook sa simulacijama i eksperimentalnom analizom različitih strategija,
- propratni PDF sa matematičkom analizom problema, teorijskim izvođenjima i interpretacijom rezultata.

U okviru projekta analizirane su:
- nasumične strategije,
- strategije otvaranja kutija redom,
- blok strategije,
- strategija praćenja ciklusa,
- eksperimentalno traženje boljih strategija,
- asimptotsko ponašanje problema i konvergencija ka vrednosti \(1 - \ln 2\),
- struktura ciklusa slučajnih permutacija.

Simulacije eksperimentalno potvrđuju teorijsku verovatnoću uspeha od približno **31%** za strategiju praćenja ciklusa.

## Struktura repozitorijuma

- `Strategy simulations.ipynb`  
  Python implementacija simulacija, eksperimenata i vizualizacija.

- `Mathematical aspects of strategies.pdf`  
  Matematička analiza problema, teorijska objašnjenja, analiza verovatnoća, ciklusa i interpretacija rezultata simulacija.

## Oblasti

- teorija verovatnoće
- kombinatorika
- permutacije i ciklusi
- algoritamsko razmišljanje
- Monte Carlo simulacije
- eksperimentalna matematika
- Python

## Korišćene tehnologije

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

## O projektu

Cilj projekta bio je povezivanje teorijske matematike i programske simulacije kroz analizu jednog poznatog logičko-verovatnosnog problema.  

Poseban fokus stavljen je na razumevanje zbog čega strategija praćenja ciklusa daje značajno bolji rezultat od intuitivnih pristupa, kao i na eksperimentalnu proveru teorijskih rezultata pomoću velikog broja simulacija.

Detaljna matematička analiza i interpretacija rezultata nalaze se u propratnom PDF dokumentu.
