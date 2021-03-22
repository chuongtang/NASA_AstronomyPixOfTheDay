# NASA Astronomy Pictures of the Day
* This mobile responsive project incorporating the **NASA API** to get random astronomy pictures of the day.
* The results are formatted into cards with image title, description, date and copyright information.
* Using *localStorage*, users can also add images to their favorites page.

* To improve performance, images will be "lazy" loaded when it comes close to being scroll to.

## Credit for API from : * https://api.nasa.gov/*

### New cool things that I learned: :rocket: 

1. Creating custom  loading animation.
2. Use "&nbsp" (&NonBreakingSpace) to reserver some "spaces" in the html . (ln.35)
3. Fetch request to pull NASA API.
4. *append()* VS *appendChild()*: with *appendChild* we can only append **1** item. *Append(**the order of items here does matter!**)* will let us do more than one.
5. A common use of JSON is to exchange data to/from a web server. When sending data to a web server, the data has to be a string. Convert a JavaScript object into a string with *JSON.stringify()*.
6. (@Ln 28)The *Object.values()* returns an **array** which contains the given object's own enumerable property values, **in the same order** as that provided by a *for...in*  loop.
7. Apply *Window.scrollTo()* prior to loading will helps append the new contents at lower section of the page.
8. **Declarative** programming focuses on what the program should accomplish while **Imperative** programming focuses on how the program should achieve the result. ==> This is a stepping-stone concept for leanring React. :+1: :tada:


