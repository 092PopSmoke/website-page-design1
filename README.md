# Website design
Lage en nettside ved hjelp av HTML &amp; CSS, kopiere bildene lærer har gitt oss

Jeg delte alle de forskjellige elementene inn i forskjellige klasser istede for å "objekt orintere de" som hadde hvert lurere hvis dette var et større prosjekt, men kom til konklusjonen at det ville ikke være nødvendige å generalisere alle classene, helle bare lage individuelle klasser for alle de forskjellige brukområdene.


## header
```html
  <header>
        <div class="header">
            <h1><a href="#" class="logo"><span>SD</span> Web Design</a></h1>
            <div class="header-right">
                <a class="active" href="homepage.html"><b>HOME</b></a>
                <a href="about.html"><b>OM OSS</b></a>
                <a href="services.html"><b>TJENESTER</b></a>
            </div>
        </div>
        <header>
```

og
## footeren 
```html
    <footer class="pp">
    <p>SD Web Design, Copywrite &copy; 2021-2022 <br> <b> Laget av Nael Hassan</b></p>
    </footer>
```


# Design
Jeg har prøvd min best til å følge etter oppgaven fordi jeg synes det er lettest, jeg har gjort den tredje siden mens Mardin har jobbet med side 1 og Hussain side 2.
Som kritikk til meg selv hadde jeg valgt andre farger neste gang og eventuelt satt opp en font men jeg vet ikke om det ville hvert et bonus poeng på oppgaven.

Jeg valgte å lage unike design på hver av sidene og ble generelt ganske fornøyd med sidene til tross for at klokken nå nærmer seg halv 7 på morgenen.
beholdt temaet og fargene men brukte ikke like mye bilder på alle siden, samt forsøkte jeg å holde de svært minimalistiske.

# Problemer
Jeg hadde ikke så mange problemer med designet av oppgaven, men hadde noen problemer anngående å sette opp Github Pages, spessielt fordi linkene mine må referes på annen måte i github pages fordi det må via repositoriet. 
f.eks:
### I **min** kode
```html
        <ul>
            <li><a href="/løsning/index.html">HOME</a></li>
            <li><a href="/løsning/about.html">OM OSS</a></li>
            <li><a href="/løsning/services.html">TJENESTER</a></li>
        </ul>
```

Dette går på min maskin fordi den finner filene på riktig sted. Men Github Pages må refere via et bestemt directory i Github Pages. [artikkel på det](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#choosing-a-publishing-source).
For å løse dette måtte jeg flytte alle filene til Root directoriet på main-branchen på Github og re-referere til de riktige filene.

### sånn her
```html
        <ul>
            <li><a href="/website-page-design/index.html">HOME</a></li>
            <li><a href="/website-page-design/about.html">OM OSS</a></li>
            <li><a href="/website-page-design/services.html">TJENESTER</a></li>
        </ul>
```

Dette problemet var ikke vanskelig å løse men repositoriet ser litt mer rotete ut nå. 🤨
