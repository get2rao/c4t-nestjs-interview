# Coding 4 Tomorrow NestJS Interview

## ☑️ Instructions
1-	List the movies in side-by-side cards (responsive) and display :
  a.	the poster image
  b.	the title in bold
  c.	the category
2-	Add a button in the cards to delete them
3-	Add a like/dislike system
  a.	Display a toggle like and dislike button
  b.	Display the number of like and dislike
4-	Add a multi-select filter by category
  a.	This filter allows you to select multiple categories to display
  b.	Categories must be retrieved dynamically
  c.	If all the movies of a category are deleted, this one should not appear anymore
5-	Add a pagination system
  a.	Display 6 movies per page
  b.	Previous/Next buttons
6-	Add a search field by movie title constrained by the selected category(ies)
  a.	Use React Hook Form to make the search field work
7-	Add unit tests and test :
  a.	The filter function
  b.	The search function
  c.	The like / dislike system
  d.	The movie map component
8-	Create the e2e tests:
  a.	Test the pagination
  b.	Test the search
  c.	Test the category filtering
  d.	Test the like / dislike system

### Conditions
1-	Using TypeScript
2-	Using NextJS
3-	Using React hooks
4-	Using React Hook Form
5-	Use Contexts or RecoilJS or Zustand
6-	Use Tailwind for design
7-	Use Cypress and Jest for testing
8-	Use all the libraries of your choice to implement these instructions

### The plus (optional)
1-	Loading management and reflection on the display strategy (Skeleton ? Just a loader ? Which part of the page ? etc...)
2-	Use of ESLint and Use of Prettier
3-	Use of Storybook

### Important
1-	Removing the asynchronous behaviour in movies.js will cancel the test, movies.js will be provided.
2-	Special attention will be paid to the structure of the code and the project.
3-	Movies posters jpgs and array with movie ID, title, category, thumbnail, likes will be provided.

##French Version

## ☑️ Instructions

1. Créer une authentication avec JWT

2. CRUD de films contenant les champs suivants :
  - title (120 caractères max)
  - description (500 caractères max)
  - releaseDate (date dans le passé)
  - rating (1 à 5)
  - genre (enum)
  - actors (array de string)
  - poster (url)

3. Gestion d'accès
  - Public : Récupérer la liste des films
  - Privé (auth) : Création / modification / suppression d'un film

### Pré-requis
- Utilisation de MongoDB avec Mongoose
- Tests unitaires pour tous les services
- Tests end to end (in memory database) pour toutes les routes
- Documentation complète de l'API avec Swagger
- DTO + validation
- Gestion d'erreur
- Gestion de rôles
- Typescript
