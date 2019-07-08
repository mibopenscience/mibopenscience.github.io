# MiB Helpdesk, toolbox and training
Pilot

## Website
https://mibopenscience.github.io

## Content
De inhoud van de verschillende hoofdstukken en paragrafen wordt geschreven in [Markdown](https://www.markdownguide.org/).
Dit komt als html op de website m.b.v. [Jekyll](https://jekyllrb.com/). 
De pilot website dient als een platform om snel producten en oplossingen te testen en ontwikkelen. 

## Installatie
Nodig: Github-pages, Jekyll, Ruby

## \_Config.yml
Comments aan/uit voor lokale ontwikkelomgeving vs remote github
Collections

-- Voor local deployment:
1) Zorg dat in de _config.yml file de url en baseurl goed staan voor local development
--- url: "http://localhost"
--- baseurl: "" (of "/")
2) Ga in de Ruby command line naar de lokale map
3) Start de server met het commando: bundle exec jekyll serve
4) Ga naar: http://localhost:4000
