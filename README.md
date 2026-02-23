Oma Portfolio / Github Pages

Toteuta oma portfolio. Saat itse päättää toteutustavan, sisällön ym. Tämän projektin yhteydessä voit testailla halutessasi Gitin käyttöä versionhallinnassa, tehdä muutokset suoraan Githubiin selaimen kautta tai käyttää Github desktopia. Sivuston voi tehdä html+ css tai GIthubin markdownilla.

Saatat siis tarvita ohjelmia kuten:

VS Code: https://code.visualstudio.com/ tai joku muu editori
Github desktop https://desktop.github.com
Git: https://git-scm.com/download/win (Valitse asentaessa “use Visual studio code as Git’s default editor, jos käytät VS Codea editorina)
Tms. 
Photoshopin, illustratorin ym lisenssit on mahdollista saada myös, jos sellaisia tarvitset.
Tee alkuvalmisteluina seuraavat stepit:

Luo uusi GitHub-repositorio ja anna sille nimi username.github.io, jossa username on käyttäjätunnuksesi GitHubissa. Voit laittaa repon halutessasi privateksi vielä toistaiseksi. 
Kloonaa repositorio paikallisesti.
Voit valita kloonaatko repon Github desktopiin vai Git bashilla komennolla
git clone https://github.com/username/username.github.io.git.
Kloonaamisesta löytyy tietoa täältä: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository 
Kloonaamalla siis teet paikallisen version reposta koneellesi, josta pusket (push) muutokset githubiin.
Luo koneellesi uusi tiedosto nimeltä index.html ja lisää siihen seuraava sisältö tai käytä vs coden html boilerplatea ja lisää siihen jotain sisältöä. Tallenna file.
<html>

  <head>

    <title>Omat sivut</title>

  </head>

  <body>

    <h1>Teretulemast sivuilleni!</h1>

    <p>Tässä olisi eka sivu.</p>

  </body>

</html>

 

Lisää index.html githubiin joko github desktopin, githubin selainversion tai git bashin kautta (
git add index.html

git commit -m "Add index.html"

git push)

Avaa selaimella osoite https://username.github.io. Sivustosi pitäisi nyt näkyä selaimessa.
Muokkaa index.html tiedostoa ja tee muutoksia sivustoosi. Voit lisätä muutokset versionhallintaan Git Bashilla ja pushata ne GitHubiin komennoilla git add, git commit ja git push. Muutokset tulevat näkyviin osoitteessa https://username.github.io hetkisen kuluttua.
Jatka portfoliota, kunnes olet tyytyväinen siihen. Saatat tarvita lisää html-sivuja, css-filejä, javascript-tiedostoja ja mitä lie, riippuen ihan siitä, millaisen portfolion toteutat.
Lisätietoja oman sivuston tekemisestä/hostaamisesta Github pagesissa löytyy esim täältä: 

https://www.khanacademy.org/computing/computer-programming/html-css/web-development-tools/a/hosting-your-website-on-github

Lisätietoja versionhallinnasta löytyy esim täältä: https://docs.github.com/en/get-started/using-git/about-git

Palauta tehtävään oman portfolio-sivustosi URL.
