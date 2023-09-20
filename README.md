# ReactBasics-ReadingListApp
A simple React app that uses forms to create a reading list. At the bottom of the page, the user enters a book title and when they click the "Create!" button, a book entry gets created on the same page with a random image and that title. The book element's title can be edited and the entire element can be deleted. 

## How to Use
* In the CLI, run `npm run start`. The main page will be located on "localhost:3000" or a similar available port.
* The Reading List book entries are saved on a local database at "db.json". This fake backend is created by the "json-server" API. This server needs to be run simultaneously with the Reading List App by running `npm run server`

## Things I Learned
* Connecting a back-end database (a fake one with JSON Server) to a React app with a basic form that posts data
* Using Context creation and a Provider to organize and distribute the app's book functionality (creating books, deleting books, etc.) to different components in the app
* Handling forms in React with Axios
* Creating a custom hook for a useContext call for cleaner code
  
## To-Do List
- [ ] Add category/genre tags to each book
- [ ] Add a sort function to only show books of a certain genre 
- [ ] \(Optional) Eventually, incorporate some sort of API for real books and change implementation of images to match those books
