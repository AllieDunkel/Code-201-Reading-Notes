## Reading Assignment 13

### Local Storage and How To Use It On Websites

1. Why would a developer use local storage for a web application?

- you need to store the state of your interface somewhere. Normally, this is done server-side, and you would check the username to know which state to revert to. But what if you don't want to force people to sign-up. This is where local storage comes in. You would keep up a key on the users computer and read it out when the user returns 

2. What information should not be stored in local storage?

- Personal Information

3. Local storage can store what type of data? How would you convert it to that type before storing?

- You can only store strings in the different keys . So if you have an object it will not be stored right away. You can work around by using the native.JSON.stringify() and JSON.parse() methods

## Things I Want to Know More About