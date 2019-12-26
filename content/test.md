---
title: "Testsida"

views:
    byline:
        region: main
        sort: 2
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/byline

    kursrepo:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo

    redovisa:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa
---
Testsida för Markdown
=========================

Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/test.md`.

[FIGURE src="image/bali3.jpg?w=300" class="right" caption="Detta är en bild från Bali, i Indonesien"]
<br>
<br>
# Mina sociala kanaler
<br>
Här hittar du mig i social media  
* [Instagram] [insta]  
* [Facebook] [fb]

[insta]: https://instagram.com/burrmode "Instagram"
[fb]: https://www.facebook.com/emmaburens "Facebook"

<br>
<br>


All kärlek och värme,
Emma Burén
