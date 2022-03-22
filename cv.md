# Dima Korolev
**Junior Frontend Developer** 
********* 
### Contact information:
Republic of Belarus, Minsk.
* Mobile: +375296235797
* Email: korolev@tut.by
* [github.com/Dmitri-Korolev](https://github.com/Dmitri-Korolev "github link")
********* 
### About Myself:
I am applying for the position of I am a frontend developer looking for a job in a good team where I can be helpful, develop my technical and social skills to use them to solve interesting problems. Everyday I work to improve my technical and programming skills, improve my English to become a high-class specialist. 
********* 
### Skills and Proficiency:
* HTML, CSS (SASS / SCSS)
* JavaScript 
* React / Redux
* Webpack / Gulp
* Git
********* 
### Code example:
Implement the loadPosts() function that returns a Promise with posts
loaded from [https://jsonplaceholder.typicode.com/posts](https://jsonplaceholder.typicode.com/posts "jsonplaceholder link") and alphabetically sorted by title
```
 function loadPosts() {
    return new Promise(function(resolve, reject){
        fetch('https://jsonplaceholder.typicode.com/posts')
        .then(response => {
            return response.json();
        })
        .then(body => {
            return body;
        }) 
        .then(body => {
          	function SortArray(x, y){
   					 			if (x.title < y.title) {return -1;}
    							if (x.title > y.title) {return 1;}
    							return 0;
			}
            let sorted = body.sort(SortArray);
            return sorted
        });        
    });
}
```
********* 
### Courses:
1. [WEB Developer 2021](https://udemy.com/course/webdeveloper/ "WEB Developer 2021") 
2. [Full course on JavaScript + React - from scratch to the result](https://udemy.com/course/javascript_full/ "JavaScript + React courses")
3. [React + Redux - Professional Development](https://udemy.com/course/pro-react-redux/ "React + Redux courses") 
*********
### Languages:
1. English - Intermediate
2. Russian - Native
