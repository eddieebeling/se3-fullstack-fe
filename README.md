# Full Stack & Front-End Developer Assessment 

The scope of this assessment is to use the following mockup to build a "Meet our team" page using HTML, CSS, and JavaScript.  You will be asked to provide a link to your project prior to your technical or team interview.

![Meet our team](meet-our-team.jpg)

### Requirements
* Make an API call to get the list of team members
* Using the API response, render the following data for each team member in the array:
  * Name
  * Job Title
  * Profile Image
  * Twitter icon with a link to their Twitter profile
  * LinkedIn icon with a link to their LinkedIn profile

```
// Example Object //

{
    "name":"Leonard Krasner",
    "title":"Senior Designer",
    "profileImg":"https://res.cloudinary.com/dot-foods/image/upload/v1649374854/sse-3-images/leonard-krasner_k6wogh.png",
    "twitterUrl":"https://twitter.com/leokras92",
    "linkedInUrl":"https://linkedin.com/in/leokras92"
}
```

### Specifications

#### API URL
[https://mocki.io/v1/21381c90-7cd0-4507-be37-0ea209a61d35](https://mocki.io/v1/21381c90-7cd0-4507-be37-0ea209a61d35)

#### Typography
You may use any **sans-serif** system or [Google font](https://fonts.google.com/). 

#### Hex Colors
```
$bgDark: "#0e131e";
$bgLight: "#191f2b";
$textWhite: "#ffffff";
$textLight: "#c5cdd8";
$textHighlight: "#6f71f1";
```
#### Content
```
{
    "heading": "Meet our team",
    "intro": "Donec dapibus scelerisque orci, sed consectetur est posuere sed. Duis viverra interdum vulputate."
}
```
#### Images 
All profile image references are included in the API response. The Twitter and LinkedIn social media icons are included in this project or can be accessed here:

* Twitter Icon - [https://res.cloudinary.com/dot-foods/image/upload/v1649377334/sse-3-images/twitter-icon_vrfevs.png](https://res.cloudinary.com/dot-foods/image/upload/v1649377334/sse-3-images/twitter-icon_vrfevs.png)
* LinkedIn Icon - [https://res.cloudinary.com/dot-foods/image/upload/v1649377334/sse-3-images/linkedin-icon_knv4dg.png](https://res.cloudinary.com/dot-foods/image/upload/v1649377334/sse-3-images/linkedin-icon_knv4dg.png)

### JavaScript
Bonus points for using any modern JavaScript framework like [Vue.js](https://vuejs.org/), [React](https://reactjs.org/), [Angular](https://angular.io/), or [AlpineJs](https://alpinejs.dev/), but feel free to use vanila JavaScript ES6 or jQuery if you feel more comfortable.

### You may use
Any web-based developer tool that allows you to share a link to your project like [Codepen](https://codepen.io/) or [CodeSandbox](https://codesandbox.io/).