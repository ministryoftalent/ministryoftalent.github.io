---
layout:     post
title:      "Sourcing na Githubie - podstawy"
subtitle:  Sourcin na Githubie dla początkujących
date:       2016-08-05 11:00:00 
author:     "Ministry of Talent"
img:  rsz_github1.png
categories: praca, github, sourcing
index: true
---
<b>Dziś dowiesz się:</b>

-  Do czego służy GitHub?

-  Jak szukać programistów na Githubie?

-  Jak sourcować z zaawansowaną wyszukiwarką? 

-  Jak w poszukiwaniach wykorzystać "x-ray search"?


3,2,1... start!

 <img src="/images/monitor.jpg" class="img-responsive" alt="Picture">

<b><font size="5,5">Dlaczego warto posługiwać się Githubem w rekrutacji?</font></b>

<a href="https://github.com/" target="_blank">GitHub</a>  to społeczność zrzeszająca <b>26 milionów użytkowników</b> (marzec 2017) i miliony stworzonych przez nich projektów (<b>repositories</b>). Platforma może służyć za alternatywę LinkedIn, albo być uzupełnieniem profilu kandydata dając wgląd w jego praktyczne umiejętności. 

Dobre repozytorium powie nam o programiście więcej niż jakiekolwiek CV. Ale co najważniejsze, dzięki GitHubowi można odnaleźć <b>prawdziwe programistyczne perełki</b> nieobecne w żadnych innych sieciach społecznościowych.

Github może być doskonałym miejscem na sourcing szczególnie w przypadku stanowisk związanych z tworzeniem rozwiązań front-endowych (bo takich projektów jest na GitHubie najwięcej). 


<iframe src="https://giphy.com/embed/3oD3YveOJWdwIAfZ5e" width="480" height="269" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/silicon-valley-3oD3YveOJWdwIAfZ5e"></a></p>


<b><font size="5,5">Do czego służy GitHub?</font></b>

Github umożliwia umieszczenie kodu w repozytoriach na ich serwerach.
 
Cały koncept można porównać do zapobiegawczych pasjonatów fotografii wrzucających swoje zdjęcia na wirtualne dyski, po to aby ich nie utracić w najbardziej niespodziewanym momencie. 

Jako, że zdjęcia zostały wrzucone na darmowy serwer, aby je tam umieścić zrzekasz się praw autorskich i każdy ze społeczności może ściągnąć twoje fotografie, przerobić na kolaż, wydrukować i powiesić na ścianie. 

Jeśli chcesz je zachować tylko dla siebie, oczywiście musisz zapłacić za korzystanie z serwera. Ale jeśli pozostaniesz przy darmowej opcji, <b>obecność społeczności pasjonatów</b> takich jak ty pozwoli ci do woli chwalić się swoją twórczością, dzielić się ciekawymi rozwiązaniami, uczyć od innych, poznać najnowsze nowinki z branży czy poprosić o opinię na temat twojej pracy. 

Mniej więcej tak samo jest kodem tworzonym przez programistów. 


<img src="/images/lifehacker.jpg" class="img-responsive" alt="Picture">
Oryginał zdjęcia <a href="http://lifehacker.com/5983680/how-the-heck-do-i-use-github" target="_blank">tutaj</a> 

<b><font size="5,5">Jak szukać programistów na Githubie czyli gwiazdki, forki i commity</font></b>

Z kodem jak z fotografiami, zdarzają się mniej lub bardziej udane. 
Programiści na Githuba wrzucają projekty z których są dumni, ale gro z nich wrzuca tamże  swoje wprawki w technologii w którą po prostu chcieli się pobawić. 

Github to taka duża <b>programistyczna piaskownica</b>. Sztuką jest odnaleźć te kilka nieodkrytych jeszcze diamentów zakopane pod kupą piachu. Obecność repozytorium z JavaScriptem na czele nie od razu oznacza, że mamy do czynienia z front-endowcem.

Github umożliwia przeszukanie przez: lokalizację (<b>location</b>), język programowania (<b>language</b>), liczbę śledzących dany profil (<b>followers</b>), gwiazdki, które można uznać za odpowiednik Facebookowego lajka (<b>stars</b>), datę stworzenia profilu (<b>created</b>), pełne imię i nazwisko użytkownika (<b>fullname</b>). Teoretycznie im więcej gwiazdek ma repozytorium i im więcej śledzących na uzytkownik, tym lepiej. Trochę jak z pokemonami i ich mocami ;)

<b>Nick</b> (w tym przypadku "bart") będzie nam potrzebny do zweryfikowania tożsamości użytkownika, a potem jego e-maila.


<img src="/images/github_all.png" class="img-responsive" alt="Pict ure">

Na dole profilu można zobaczyć okienko z częstotliwością udzielania się użytkownika na GitHubie. Im więcej zielonych kwadracików (<b>commits</b>), tych więcej aktywności. Możemy klikąnć nań i zobaczyć co rozwijał danego dnia. Będzie ono istotne jeśli zależy nam na kandydacie aktywnie kodującym w danym języku lub committującym do danego projektu open sourcowego. Na GitHubie sporo jest profili nie aktualizowanych przez lata, z których właściwie jedyne co możemy się dowiedziec to adres email, zatem zielone kwadraciki są jak najbardziej pożądane!

Przy przeglądaniu profilu kandydata zwróć uwagę na liczbę <b>forków</b> czyli tego ile osób skopiowało projekt. Świadczy to o popularności repozytorium wśród użytkowników społeczności.  co powinno się przełożyć wysoką jakość kodu.

Kolejnym rozwiązaniem jest przejrzenie kto buduje dany projekt (<b>contributors</b>, pomarańczowa ramka poniżej: 6 contributors) i wten sposób można wyłonić kolejnych potencjalnych kandydatów. 

<img src="/images/forks1.png" class="img-responsive" alt="Picture">



<b><font size="5,5">Za pan brat z zaawansowaną wyszukiwarką</font></b>

Github to nie LinkedIn. Koniec i kropka. Nie dziwne więc, że przeszukiwanie platformy jest nieco bardziej mozolne. 

Można wykorzystać logikę booleanowską, ale dużo prostsze jest wykorzystanie <a href="https://github.com/search/advanced" target="_blank">wyszukiwarki zaawansowanej</a>.


<img src="/images/github_advanced_search.png" class="img-responsive" alt="Picture">


A taki string można wykorzystać przy wykorzystaniu prostej wyszukiwarki w GitHubie:

<i>type:user language:javascript location:"london" created:"2009-01-01 .. 2009-12-31" followers:"20 .. *"</i>




<b><font size="5,5">Jak w poszukiwaniach wykorzystać "x-ray search"</font></b>

Jeśli szukamy bardziej doświadczonych programistów warto zwrócić uwagę na datę dołączenia do Githuba.

Pzykład do wykorzystania w Googlu:

<i>site:github.com London “C++” "joined on" "100..1000 followers" "joined on* 2009"</i>





<br>

<b>W kolejnej części dowiesz się:</b>



- Jak wykorzystać trendy w repozytoriach? Co to jest GitHub awards?

- Jak odnaleźć adres e-mail na GitHubie?

- Co to jest open source i co to ma wspólnego z Githubem

- Co różni BitBucket od GitHuba?

- Jak interpretować dane z GitHuba?

- Jak wykorzystywać te informacje w wiadomościach rekrutacyjnych? 
