# Adaptive Metro with Max
Adaptive Metro este o aplicatie care isi propune sa adapteze viteza unui metronom in functie de precizia cu care executi exercitii de metrica. 

## (Instalare)
Puteți descărca Max | Cycling '74 de aici: https://cycling74.com/downloads 
Există și o perioadă de testare de 30 de zile. 

SYSTEM REQUIREMENTS
Windows 8 or later
64-bit Intel® or AMD multi-core processor. Intel® Core™ i5 processor or faster recommended
4 GB RAM (8 GB or more recommended)

Instalare op.beatitude~
Descarcă op.beatitude~ de pe pagina creatorului Olivier Pasquet: https://www.opasquet.fr/dl/
Crează un folder cu denumirea Max Objects(sau poti alege propria denumire) pe PC. 
În Max, selecteaza „Oprions>File Preferences” și adaugă noul folder în „Search Path”.
Când vei reporni Max, orice nou obiect pe care îl adaugi în folder vor fi disponibile. 

Pentru alte informații, vezi linkul:
http://www.maxobjects.com/?v=objects&id_objet=3798&requested=beat&operateur=AND&id_plateforme=0&id_format=0 

Descarcă fisierul „Metronom Adaptiv.zip”, dezarhivează și folosește. 


## (Utilizare)
Interfața folosește 4 cadrane:
Cadranul dreapta-sus: Activează microfonul și playoutul și tot aici poți selecta driverele și matricile. 
Cadranul stanga-sus: Selectezi bpm-ul de pornire. Butonul on/off. 
Cadranul dreapta-jos: Selectezi recurența cu care aplicația verifică și ajustează bpm-ul. Pentru dezactivarea funcției de ajustare, selectează „inf”. 
Cadranul stanga-jos: Indică în timp real „Targetul” și bpm-ul „Current”, cât și în ce sens activează ajustarea: roșu pentru ajustare în jos, albastru pentru ajustarea în sus. 

## (Istoric)
(01.00) - Aplicația este funcțională.



## (Link-uri)
https://www.youtube.com/watch?v=Y4YLy7kqcr8&ab_channel=Ableton 
http://www.maxobjects.com/?v=objects&id_objet=3798&requested=beat&operateur=AND&id_plateforme=0&id_format=0
https://www.opasquet.fr/dl/
https://docs.cycling74.com/max8/refpages/tempo
https://www.opasquet.fr/op-beatitude/


# Dezvoltarea proiectului

Pentru început:

1. Creează-ți cont pe Github
2. Download și install [Github Desktop](https://desktop.github.com/)
3. Citește [acest ghid](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) și ține la îndemână [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet).

Apoi, procesul este următorul (inspirat de [aici](https://cs.anu.edu.au/courses/comp1720/deliverables/05-major-project/#submission-process)):

1. *fork* al acestui template către propriul tău cont de Github

![](assets/fork.gif)

_(dacă preferi cumva ca repo-ul să nu fie vizibil de către public, îl poți seta ca Private din Settings - "Change visibility". Atunci trebuie să mă adaugi drept colaborator, ca eu să am acces.)_

2. *clone* al repo-ului din Github Desktop pentru a-l downloada local

![](assets/clone.gif)

3. *commit* și *push* pe măsură ce lucrezi la proiect. Ultima versiune push-ată pe server înainte de deadline va conta pentru evaluare.

![](assets/commit.gif)

## Elemente obligatorii

1. Acest readme completat. Titlu, descriere, mod de utilizare, istoric, link-uri utile.

   Poți include și imagini și chiar [gif-uri animate](https://www.screentogif.com/), sau link-uri către materiale audio/video.
   
   Vezi [aici](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) mai multe sugestii.

2. [Declarația de originalitate](statement-of-originality.yml) completată. Tot ce nu este inclus acolo va fi considerat 100% contribuție proprie.

    *(formatul este adaptat de [aici](https://gitlab.cecs.anu.edu.au/comp1720/2018/comp1720-2018-major-project/-/blob/master/statement-of-originality.yml). Da, este un pic ironic să refolosim un doc [de altundeva](https://cs.anu.edu.au/courses/comp1720/resources/faq/#how-do-i-fill-out-my-statement-of-originality), dar menționăm sursa deci nu este plagiat!)*

3. Proiectul în sine. Tot codul trebuie să fie prezent, proiectul trebuie să poată rula conform instrucțiunilor din readme. Dacă e nevoie de asset-uri mari (sunete, video etc), [folosește Git LFS](https://git-lfs.github.com/) sau include link de download în instrucțiunile de instalare.

