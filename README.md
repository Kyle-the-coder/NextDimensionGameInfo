# Next Dimension Gaming Info
A front-end React app created using CSS for styling and RAWG for the API
---
-We open up Next Dimension Game Info with an eye opening landing page, styled with CSS using the game art from the API call, which was made using Axios and the React useEffect hook. "Entrance Button" is the name I gave the button you must click to 'Enter into the Next Dimension', a play on words as well as a on click event that runs a lock and key effect to make the user feel as if they are opening and entering into the next dimension.


https://user-images.githubusercontent.com/111798115/216848613-d3160788-2609-4a1d-8bbc-f25d7762698f.mov

---
-This brings us to the first content page the user sees. We make a general API call to bring in "Games of Interest". Game art to that specific game is displayed in a carousel. The genre and meta critic are stored in state and then ran through formatting functions to make sure the info is displayed properly. Also cards on the left are for different API filters made with CSS styling and displayed with JSX.


https://user-images.githubusercontent.com/111798115/216849019-63315280-3c81-4dec-93f1-64311231dd54.mov

---
-Next is the search bar. The user's input is stored in a state created in the App.js file. I use the lift state technique to pass the function down the to the child component and then bring the result back up to the App.js file to pass the result back down to the display search page. The API call is set to a loose search that uses the user's input to match with game titles


https://user-images.githubusercontent.com/111798115/216849310-e4eb2915-7e70-4219-b935-233411111b67.mov

---

-Next is the display one page. There is five API calls on this page that all happen through useEffect and the game Id. I use useParams to access the id and make the API calls to get the info that is related to this particular game. This page is styled with CSS along with a little bit of Bootstrap(for some margins). I loved making use of the opacity, hover, and gradients with this page. I feel like it allows the user to have many focal points based on their choice of where to look, or they can just enjoy the game art.



https://user-images.githubusercontent.com/111798115/216849972-dd4f08b6-5dba-4fee-a791-36b511a2f556.mov

---
-Lastly is the platform filter pages. Each one is written the same, only change is the platform_parent id number in the Axios call to keep results related to the right platform. This was a tricky api call as I could only get an array of 40 objects per api call. In order to get accurate information I needed to nest an api call withen an api call three times. Set each api call to a different variable and then set those to an array using the spread operator. I then created a sorting function to sort the results by meta critic level so the user can easily see the top games at the top of the page.




https://user-images.githubusercontent.com/111798115/216850400-328f9a01-8ec2-40e5-bb52-5ada3970b27d.mov

---
In conclusion I really enjoyed this project. Working with React has been an amazing and challenging experience, I will be continuing my React journey into Typescript. Thank you for taking the time to look at my project!


