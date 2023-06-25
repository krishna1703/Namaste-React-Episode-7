# Namaste React ❤️

# Episode - 7 Finding the path 🚀

# planning for the food ordering web app 🍴

- Header
- log0
- Nav-items

      - Body
        - Search
        - Restaurant Container
        - Restaurant card

- Footer
- copyright
- links
- Address



# Two approach how webapps fetch the data from backend data ❤️
- 1.st way

- loads > api > render 

- 2nd way

- loads > render > api > render (in React  js 2nd way  of fetch the data from backend is best way to fetch the data to  webapps)

# useEffect Hook ❤️
-  useEffect(()=>{
   <!-- call back function --> 
   <!-- []= dependency array -->
},[]);

- first component willbe render and after render the component useEffect render(call back function)

# optional chaining(?) ❤️

- the optional chaining operator return undefined if an object is undefined or null ( instead of throwing an error)
- instead of throwing an error returns undefined;

# shimmer ui  ❤️
- its called as skeleton screen (this is fake ui)
 
# state react variable   ❤️
- when ever state variable update react triggers a reconciliation cycle (re- render the component)

# useEffect  Hook❤️

-  use Effect always  called by initial render.

#  1st no dependency 

  - if no dependency  array then useEffect is called on every render.

  - useEffect(()=>{

   });

#  2nd  dependency  array is empty []

  - if  dependency  array is empty [] then useEffect is called on only Initial render(just once) render.

  - useEffect(()=>{

   },[]);

#  3rd  dependency  array with state variable []

  - if  dependency  array with state variable  then useEffect is called  everytime when state variable update .

  -  useEffect(()=>{

     },[state variable]);

# lets talk about React Router ❤️    

- react router is a lightweightfully featured routing library for the react . react router runs everywhere that react runs ; on the web , on the server using node js and for apps react native.

- createBrowserRouter (Router)
- BrowserRouter(RouterComponent)
- Link (component)
- outlet (component)- it don't show in dom element. outlet it is replace by the children (components) paths

# Single page Application

- Because of client side routing

# SPA Single Page Appliction❤️

-  Single Page Application (SPA) is a web application that dynamically updates the webpage with data from web server without reloading/refreshing the entire page. All the HTML, CSS, JS are retrieved in the initial load and other data/resources can be loaded dynamically whenever required. An SPA is sometimes referred to as a single-page interface (SPI).

#  Client Side Routing  and  Server Side Routing❤️

- In Server-side routing or rendering (SSR), every change in URL, http request is made to server to fetch the webpage, and replace the current webpage with the older one.

- In Client-side routing or rendering (CSR), during the first load, the webapp is loaded from server to client, after which whenever there is a change in URL, the router library navigates the user to the new page without sending any request to backend. All Single Page Applications uses client-side routing.