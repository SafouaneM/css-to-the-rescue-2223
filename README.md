# CSS to the Rescue @cmda-minor-web 2022 - 2023

Creating a firework show for this project, already made a sketch in my notebook how I would like to realise that.

## What am I going to build

### Start up

I want to start with some basic stuff, as I'm not the strongest in CSS yet.

- [x] Create sketch for project

## Research

- [x] Research how I can change my png's to svg cutouts and fill them with for example a blackbackground
- [x] Research how I can make those svg cutouts animte in a "breathing" matter
- [] Research how I can make all these cutouts clickable, and make them do something for example opening a modal or changing a value (for testing purposes let them change the background color of the page fe)
- [] Research how I can spawn and animate patterns and shapes when something is clicked

## SVG'S
- [x] I have ~5 png's that are now svg cutouts filled with a background color of my liking

## Events
- [x] I can click on a checkbox and it does something with the page it changes the color of the firework

## Shapes and patterns
- [] I can make a simple turtle pattern with CSS
- [] I can make a simple orange pattern with CSS
- [] I can animate all of the above in a way that firework would

## End result (hopefully)
- [] When I click on the svg in the middle I first get a modal prompt that her default firework has been set and that I change the colors and patterns by clicking on the other images.
- [] I have a working firework show, when I click on the svg in the middle I can shoot default fireworks from her bow. If I click on the svg's on the left and the right I can change the pattern/color of the firework that gets shot from the middle svg. 

## End result (neutral)
I got a mixed sort of playground of all kind of things I could in my power with animations, I got a looping rocket some exploding text if you click on it and we got a nuke bottom that was orignally the firerocket button but maybe its also fun to just nuke everything.
Learned how to make an okay gradient etc.

It's far away from the concept I had in mind but that's okay in my opinion.

# Process in het nederlands:

1. Begon met een blokje in de lucht afvuren op advies van 1 van de docenten gewoon simpel beginnen niet? Dit was dan ook de eerste keyframe die ik had gemaakt genaamd ascend.
2. Ik heb de svgtjes al gift gekregen van een student, dus daar ga ik niet verder over maar het was eingelijk de bedoeling dat ik mijn eigen svg cutouts daar zou plaatsen dat is helaas niet gelukt.
3. Ik heb hier wat foto's over hoe ik oorspronkelijk alles in elkaar wou zetten, ik had een best grandioos idee.

fotos content van notitieboek

[Screenshot 2023-03-09 at 17.29.10.png](..%2F..%2F..%2F..%2F..%2Fvar%2Ffolders%2Fyg%2F49psmmj57mz9slvc180rpzr00000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_Qm7e1H%2FScreenshot%202023-03-09%20at%2017.29.10.png)
![Screenshot 2023-03-09 at 17.29.33.png](..%2F..%2F..%2F..%2F..%2Fvar%2Ffolders%2Fyg%2F49psmmj57mz9slvc180rpzr00000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_RFUiso%2FScreenshot%202023-03-09%20at%2017.29.33.png)


Eindstatus!
![Screenshot 2023-03-09 at 17.28.13.png](..%2F..%2F..%2F..%2F..%2Fvar%2Ffolders%2Fyg%2F49psmmj57mz9slvc180rpzr00000gn%2FT%2FTemporaryItems%2FNSIRD_screencaptureui_DJYkq4%2FScreenshot%202023-03-09%20at%2017.28.13.png)

4. TLDR er had nog meer in kunnen zitten, maar ik vond het vrij lastig om met nieuwe dingen te komen met mijn hudige kennis, ik zeg niet dat dit mijn limiet is maar dit is wat ik mijn huidige kennis online kan zetten :)





## Leerdoelen
- Je kunt experimenteren met (voor jou) nieuwe css-technieken - om de mogelijkheden op waarde te schatten en te gebruiken waar gepast.
- Je hebt begrip van de volle kracht en mogelijkheden van CSS. Je laat zien dat CSS meer kan dan allen web pages 'stylen'.
- Je hebt begrip van de interactie-technieken van CSS (en HTML). De UX is aangenaam bruikbaar binnen de gekozen context(en).
- Je hebt begrip hoe progressive enhancement elegant toe te passen. Je laat zien dat je cascade, inheritance en specificity kunt toepassen.


## De Selector First CSS & No JS aanpak
Het **eerste uitgangspunt** is dat je *geen* ID's en classes gebruikt. Niet omdat ze niet nuttig zijn, maar om te oefenen met de [vele CSS selectoren](https://css-tricks.com/almanac/) die je tot je beschikking hebt. ID's mag je alleen gebruiken om de :target selector te triggeren en uiteraard om labels te koppelen aan inputs. En als het echt echt echt niet anders kan, heb je permissie om een enkele class toe te voegen.

Een **tweede uitgangspunt** is dat je *geen* JavaScript gebruikt. Als iets niet kan met CSS, dan zal je iets anders moeten verzinnen om te maken. We onderzoeken de mogelijkheden van CSS in dit vak, en niet die van JS.
