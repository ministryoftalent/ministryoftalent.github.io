---
layout:     post
title:      "Super-programiści czyli rzecz o trendach na GitHubie?(część 2)"
subtitle:  Sourcin na Githubie dla początkujących
date:       2017-08-08 11:00:00 
author:     "Ministry of Talent"
img:  octowan1.png
categories: praca, github, sourcing
index: true
---

 <img src="/images/supercat.png" class="img-responsive" alt="Picture">
 
 https://octodex.github.com/okal-eltocat Gif pochodzi stąd
 
<b>Wróżenie z kuli, połączyć kropki?
Czy rekruter może posiadać wystraczające kompetencje do interpretacji kodu na githubie?</b>

Odpowiem na poniższe pytania:

- Jak interpretować dane z GitHuba?

- Jak wykorzystywać owe informacje w wiadomościach rekrutacyjnych? 

- Jak odnaleźć adres e-mail na GitHubie?





<b><font size="5,5"> Dlaczego warto posługiwać się Githubem w rekrutacji?</font></b>

<a href="https://github.com/" target="_blank">GitHub</a>  


<b><font size="5,5">Trendy na Githubie czyli co w trawie piszczy</font></b>


Pierwsza zakładka na <a href="https://github.com/trending" target="_blank">Github Trending</a> pozwoli ci poznać co w GitHubie piszczy czyli jakimi projektami ekscytują się jego użytkownicy. Wyrazem uznania repozytorium jest oczywiście liczba gwiazdek. Trendy są przejawem tego jak rozwija się technologia w sferze open source. Do każdego repozytorium można zaglądnąć i przejrzeć kto udziela w projekcie. Często są to programiści nieobecni w żadnych innych sieciach społecznościowych. 

W następnej zakładce znajdziesz <b>ranking deweloperów</b>. Na czele rankingu znajdziesz firmy które na co dzień współtworzą oprogramowanie open source. Możesz przeszukiwać obie kategorie w kontekście interesujących cię języków programowania.

Kolejną znakomitą opcją są Open source showcases  


<img src="/images/showcases.png" class="img-responsive" alt="Pict ure">



<b><font size="5,5">Github Awards czyli ranking top programistów</font></b>


<a href="http://git-awards.com/" target="_blank">Github Awards</a> nie jest narzędziem GitHuba. Pewien programista hobbystycznie zaciągnął z API Githuba dane i tak powstał ranking najlepszych programistów. Dadam, że całkiem rzetelny. 

Dzięki wyszukiwarce z łatwością możemy odnaleźć programistów z największą reputacją w danym <b>mieście</b>, <b>kraju</b> i w danej <b>technologii programistycznej</b>. Jeśli sama/sam sie udzielasz w serwisie możesz sprawdzić jak wygląda twoja punktacja.
 
Załóżmy, że interesują nas programiści JavaScript w Warszawie. <a href="http://git-awards.com/users?utf8=%E2%9C%93&type=city&language=javascript&city=Warszawa" target="_blank">Tutaj zobaczysz jak wygląda ów warszawski ranking.</a>


<img src="/images/ranking.png" class="img-responsive" alt="Picture">




Na GitHubie sporo jest profili nie aktualizowanych przez lata i właściwie jedyne co możemy się z nich dowiedzieć to adres e-mail. Z pomocą przychodzi moduł monitorujący aktywność użytkownika. Na dole profilu można zobaczyć okienko wkazujące kiedy ostatni raz zanotowano <b>commity</b> użytkownika na GitHubie (w tym przypadku <i>"971 contributions in the last year"</i>). Im więcej zielonych kwadracików, tych więcej jego/jej aktywności. Możemy kliknąć na kwadracik i zobaczyć nad czym pracował użytkownik danego dnia. Będzie ono o tyle istotne jeśli zależy nam na kandydacie aktywnie kodującym w danym języku lub committującym do danego projektu open sourcowego. 

Przy przeglądaniu profilu kandydata zwróć uwagę na liczbę <b>forków</b> czyli tego ile osób skopiowało projekt. Świadczy to o popularności repozytorium wśród użytkowników społeczności, co w teorii powinno się przełożyć na wyższą jakość kodu i umiejętności programistyczne użytkownika. Podobnie rzecz ma się z <b>gwiazdkowaniem</b> repozytoriów.

Kolejnym rozwiązaniem jest przejrzenie kto buduje dany projekt (<b>contributors</b>, pomarańczowa ramka poniżej: 6 contributors) i wten sposób można wyłonić kolejnych potencjalnych kandydatów. 

<img src="/images/forks1.png" class="img-responsive" alt="Picture">



<b><font size="5,5">Za pan brat z zaawansowaną wyszukiwarką</font></b>

Github to nie LinkedIn. Koniec i kropka. 

Na GitHubie można wykorzystać logikę booleanowską, ale dużo prostsze jest wykorzystanie <a href="https://github.com/search/advanced" target="_blank">wyszukiwarki zaawansowanej</a>.

Załóżmy, że poszukujemy programisty JavaScript z więcej niż 150 śledzących użytkowników i z co najmniej pięcioma repozytorium.

<img src="/images/github_advanced_search.png" class="img-responsive" alt="Picture">


Poniższy string można wykorzystać przy wykorzystaniu prostej wyszukiwarki w GitHubie:

<i>type:user language:javascript location:"london" created:"2009-01-01 .. 2009-12-31" followers:"20 .. *"</i>


<b><font size="5,5">Jak w poszukiwaniach wykorzystać "x-ray search"</font></b>


Przykład do wykorzystania w przeglądarce Google z wykorzystanie x-ray Githuba:

<i>site:github.com London “Javascript” "joined on" "100..1000 followers" "joined on* 2009"</i>


Zakładamy, że reputacja programisty oceniania jest w liczbie osób śledzących na Githubie. Teoretycznie, im więcej tym lepiej.

Jeśli szukamy bardziej doświadczonych programistów warto zwrócić uwagę na datę dołączenia do Githuba. 

Możemy także przeszukiwać paltformę pod kątem ilości projektów na profilu. Paradoksalnie liczba repozytoriów jest najmniej ważna - ilość nie zawsze idzie w parze z jakością.

Pomocny w przeszukiwania Githuba może być <a href="https://source.socialtalent.co/" target="_blank">SocialHub</a> pozwalający bezboleśnie się przeprawić przez booleanowskie zawiłości. 

Warto dodać sobie do przeglądarki <a href="https://chrome.google.com/webstore/detail/octohr/beiklbdjdmfkgchmiabjejdlpaoicbef/" target="_blank"> OctoHR</a>. Ten dodatek do Chroma pozwoli ci  sprawdzić co jest dominującą technologią na profilu kandydata, dodatkowo zazwyczaj wskazuje adres emailowy z profilu właściciela konta. 

----------------------------


<b>Happy Sourcing! 
W kolejnej części dowiesz się:</b>


- Jak wykorzystać trendy w repozytoriach? Co to jest GitHub awards?

- Jak interpretować dane z GitHuba?

- Jak wykorzystywać owe informacje w wiadomościach rekrutacyjnych? 

- Jak odnaleźć adres e-mail na GitHubie?

- Co to jest open source i co to ma wspólnego z Githubem

- Co różni BitBucket od GitHuba?


NA DOKŁADKĘ:

<a href="https://www.eremedia.com/sourcecon/secrets-you-may-not-know-about-github-sourcing/" target="_blank"> Secrets you may know about GitHub Sourcing - EREmedia </a>

<a href="http://booleanstrings.com/2017/06/03/lesser-known-github-sourcing-tips/" target="_blank"> Więcej o X-rayu GitHuba </a> 