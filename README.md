# Coding Challenge

The whole idea is to make this challenge fun and interesting. Do not feel bad if there is something you don't know or if you feel like your code turned a little bit into spaghetti. We are not looking for perfection but we are always looking for improvement.

**BEFORE EVEN OPENING YOUR FAVORITE IDE OR TEXT EDITOR, TAKE A COUPLE OF MINUTES AND READ ALL THE INSTRUCTIONS**

## BACK

Using the language and framework that you feel more comfortable with, you will be using the [Marvel API](https://developer.marvel.com/) for retrieving and displaying comic and superheroes information.

_Make sure to get all your API credentials first_

Create a service to interact with the Marvel API. Remember to provide the right credentials in order for the requests to be accepted.

Make sure to create REST compliant endpoints in order to retrieve the following:

- A list of characters by name (full name and "beginning with")
- An specific character with detailed information of it (passing an ID)
- The list of comics in which a character appears
- An specific comic with detailed information of it (passing and ID)

Please, make sure of handling request errors nicely and to comment your code as much as you can.

BONUS

- Dockerize
- Create microservices for the above and connect them using docker-compose

## FRONT

To develop the front side of this challenge, we need you to use either Angular (5+) or ReactJS. We know there is plenty of options out there, but for the moment we are using and exploiting this ones.

If you prefer, instead of creating your own components, feel free to use an open source UI library.

Try the following:

1) The first screen should have a search bar which will be used to look for a comic character. Using a submit button or the submit key, the client will request the API to retrieve the possible results. The results should be displayed below the search bar in a box.

2) Still on the first screen and once the results are retrieved and displayed, the user must be able to click on one of the results in order to fetch detailed information about the character. Once the information comes back from the server, show the character details in a new screen.

3) On this second screen, use your imagination and good taste to show everything that you would like to show about the superhero (or villain). It's on you how much information you want to show and how you want to show it, but just make sure to include, at least, one image.

4) Still on the second screen, make sure to show a list of comics in which the character appears. How to show the list (carrousel, regular list), is up to you, just make sure to use the comic artwork and not only text. When the user clicks on one of this comics, go to the server and retrieve the information and once it gets back, **open a modal** and show the comic information.

BONUS

- Live search (for the characters search bar)
- Dockerize
- Styled Components
- async/await
- Typescript
- Animations (Pose - Popmotion, Greensock)


Please, remember to comment your code as much as you can.

Once you are done with the challenge, send us the GitHub link to the public repo in order for us to take a look at it.

Have fun coding!
