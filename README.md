# Linneahs första webbplats

## Introduktion

Denna webbplats skapades som första projektuppgift för studier i webbutveckling vid Mittuniversitetet. Mina förkunskaper var mycket grundläggande för både HTML och CSS och jag upplevde att detta första projekt gav mig en bättre förståelse för semantik och grundläggande struktur inom HTML.

## Använda tekniker

För tillfället används endast HTML och CSS på denna webbplats.

## Publiceringar

Webbplatsen är publicerad på [Netlify](https://linneahs.netlify.app/) och [Github pages](https://zvintlinn.github.io/Linneahs-f-rsta-webbplats/)

## Svar på frågor om git

**Vad är skillnaden mellan git add och git commit?**

Git add lägger till en eller flera filer i staging area. När man sedan gör en git commit så commitar man alla filer som ligger i staging area på en och samma gång. Man kan se det som att staging area är en korg för filer som är redo att commitas. När man commitar skapas en snapshot i repot för hur just de filerna såg ut vid den givna tidpunkten.

**Varför använder man branches istället för att jobba direkt i main?**

Branches är användbara för att utveckla koden och testa nya lösningar utan att riskera oönskad interaktion med den kod som finns i main. På så sätt kan man vara säker på att nya funktioner man lägger till fungerar som de ska innan man lägger till de permanent genom merge till main. Det är även användbart då tex. Github pages kan vara inställt på att uppdatera publiceringen så fort något pushas till main. För att undvika små uppdateringar hela tiden är det därför bra att arbeta i branches.

**Vad händer rent praktiskt när man gör en merge?**

När man utför en merge så läggs de ändringar man gjort i en branch till i antingen en annan branch eller till main. Det kan både handla om kod som raderats, ändrats eller lagts till. Om samma rad har ändrats i båda grenarna som ska mergeas ihop så kommer en konflikt uppstå där man manuellt behöver välja vilken kod som är rätt och som ska sparas.

**Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?**

När man pushar till github så uppdateras filerna i remote repository, men koden behöver inte nödvändigtvis publiceras om inte sidan ligger uppe med automatiserad publicering. Man kan koppla ihop sitt remote repo med exempelvis Netlify och ställa in att den publicerade sidan ska uppdateras automatiskt när man pushar nya commits till sin main branch.

**Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?**

För att en fil ska exkluderas från versionshanteringen behöver den läggas in i .gitignore.
