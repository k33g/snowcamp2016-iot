# SnowCamp 2016 - Internet Of Things "in action"

Hands-On IOT **[SnowCamp 2016](http://snowcamp.io/2016/fr/)** - **Durée 1 heure**

## Nous verrons:

*Ceci est le programme non détaillé, un plan détaillé sera mis à jour bientôt*

**Sujet/Titre:** "Et si on codait l'IOT?"

L'IOT est le buzzword du moment (même si ça existe finalement depuis longtemps). Plutôt qu'uniquement en parler, je vous propose un atelier où vous apprendrez à "faire" du **[MQTT](http://mqtt.org/)**, ce qu'est **[CoAP](http://coap.technology/)**, ... J'aurais des "objets connectés" avec différents capteurs. Vous devrez vous connecter et interagir avec eux à partir de ce que je vous montrerai. Il y aura beaucoup JavaScript, (peut-être du Java) et même un peu de Python. A la sortie de l'atelier, vous aurez les idées plus claires sur ce que peut être l'IOT et comment en devenir un acteur.

**Objectifs:**

- apprendre à utiliser MQTT (broker+client)
- survoler CoAP
- Utiliser MQTT, le SDK [Groove](http://www.dexterindustries.com/grovepi/) et [Johnny Five](https://github.com/rwaldron/johnny-five) pour interagir avec du matériel physique (Raspberry Pi, GrovePi, Arduino)
- Et si vous êtes assez rapides vous apprendrez à piloter un drone "en équipe", avec MQTT et [CylonJS](http://cylonjs.com/) (et si vous ne l'êtes pas, on pourra toujours continuer dehors, mes "Raspberries" fonctionnent sur batteries)

J'aurais à ma disposition, au moins:

- 2 RaspberryPI avec un [GroveShield](http://www.dexterindustries.com/grovepi/)
- 1 RaspberryPI relié à un Arduino Uno
- 1 Rolling Spider

(et peut-être d'autres jouets, mais nous n'avons qu'une heure ...)

**Vous ne toucherez pas physiquement les RaspberryPI** mais ils seront connectés en réseau (je fournis le routeur et un "serveur") et **vous y accéderez en ssh**.

## Pré-requis

### Obligatoires

- **un client SSH**: Vous aurez besoin d'accéder aux RaspberryPI en SSH
- **un client Samba**: (normalement en standard sur les OS) si vous êtes allergiques à **vi** ou à **pico** pour éditer les scripts via ssh sur les RaspberryPI ou le serveur

### Optionnels ... Mais ça serait bien pratique quand même

- **NodeJS** (je fournirais les autres dépendances)

Si vraiment vous n'avez, pour une raison inconnue (m'enfin!), pas pu installer NodeJS sur votre poste, j'aurais prévu des users sur le serveur pour que vous puissiez utiliser NodeJS via SSH.

### Connaissances

- JavaScript (HTML c'est pas la peine, le DOM on s'en fout) et vous n'avez pas besoin d'être un champion du monde
- Python (pas d'inquiétude, je vous aurez mâché le boulot en préparant quelques helpers), pas d'inquiétude non plus sur le niveau requis, je dois juste avoir quelques jours d'avance sur vous, le Python c'est facile
- **En électronique ? AUCUNE!!!**


### Autre

- Votre bonne humeur
- Un peu de discipline (n'allez pas faire n'importe quoi sur mes jouets, je ne suis pas sponsorisé)


##Vous allez participer ?

- **Interactions avec le matériel**: Vous imaginez bien que l'on ne peut pas forcément se connecter à 30 sur 3 RaspberryPI pour interagir avec quelques capteurs (je ne vous parle même pas du drone). Donc en fonction du nombre de présents, il faudra faire des groupes (ou pour les "individualistes" juste écouter et ne pas interférer sur les groupes)
- **Pour les parties plus génériques, comme utiliser MQTT ou CoAP**, peu importe le nombre de personnes


**S'IL VOUS PLAÎT:** Si vous avez décidez de venir, faites moi un petit tweet [@k33g_org](https://twitter.com/k33g_org), ça me permettra de me faire une idée et de m'organiser en fonction.

@+
*Philippe*