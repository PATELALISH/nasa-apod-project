#Functional requirements and notes

Using vite server with react frame work.

Gonna have two pages

- image that fetch from api
- info about api key

Nasa Api key

- https://api.nasa.gov/
- Github -- https://github.com/nasa/apod-api
- Using Apod api that gives daily new picture taken by Nasa.
- api is giving new <mark>picture</mark> of universe, <mark>name</mark> of the picture or the object, <mark>description</mark> of the picture, <mark>date</mark> of the day. This is the only information I need, there is other information api is givinig.
- Probably have to use <mark>hdurl</mark> for the picture that is gonna fetched from api.(need to look into this)
- api key place - response = apod_object_parser.get_data(<your_api_key>)
- Api key has to go into .env file. Added .env file into gitignore done

fonts

- fontawesome (cdnjs) --https://cdnjs.com/libraries/font-awesome

icons

- fontawsome --https://fontawesome.com/

Demo Picture

- https://unsplash.com/
