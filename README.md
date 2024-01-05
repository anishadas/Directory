# DIRECTORY with ReactJS
-------------------------------
## Deployment Site
### live : [https://mydirectorytm.netlify.app/](`https://mydirectorytm.netlify.app/`)
## Components
- Directory
  - It consists of all users with their post counts
  - API for users: `https://jsonplaceholder.typicode.com/users`
  
- Profile
  - Specific routes based on user id
  - post count is passed through queries
  - Getting a user : `https://jsonplaceholder.typicode.com/users/${id}`
  - Getting posts : `https://jsonplaceholder.typicode.com/posts?_limit=${postsCount}`
  - Single post based on Id : `ttps://jsonplaceholder.typicode.com/posts/${id}`

- Loader
  - An UI enhancing element- shows a loading UI for server requests
  
- Clock
  - `worldtime api` is used for all functionalities
  - timezones: `https://worldtimeapi.org/api/timezone`
  - local time : `https://worldtimeapi.org/api/timezone/${timezone}`
  
## Hooks
- useState()
- useEffect()
- useRef()
- useNavigate()
- useLocation()
- useParams()

## Modules
- `moment-timezone`  
  - The moment-timezone module is a part of the Moment.js library that provides functionality for working with time zones. 
  - Moment.js is a popular JavaScript library for parsing, validating, manipulating, and formatting dates. 
