# 2016

## Week 1

* Content was pitched at the right level, not too much, not too little. 
* Good to do a recap of HTML & CSS (especially CSS)
* Used CityMapper as a reference to illustrate the use of libraries and APIs (could have included http://stackshare.io/citymapper/citymapper maybe?), and when styling the `app template`
* Interesting discussion around the difference between `website` and `app`. *Is this an app or a website?* in most cases the answer can be *both*: it uses Web technologies and it's accessible online so it's technically a `website`, but the way you use it is more like a *tool*
* Used https://randomuser.me to play around with the idea of using URLs to request data; getting fun, visual results 
* Introducing jQuery as a `CSS-like` library seemed to make sense
* People got really excited when they got the `Back` button to switch between sections. Seems like a digestible way to introduce programming (brackets are still quite confusing though)
* Had fun with camel cases and variable names, eg: `var £ = jQuery`

## Week 2

* Peer-learning: most groups opted for the safe powerpoint-style presentation, only one team proposed an unplugged activity. Maybe force them to use unplugged. And/or I should have modelled an unplugged activity (like the robot-game) in class before! 
* USER+HTML+JS+DB unplugged seems to engage people and it's a digestible demonstration of the app mechanics.
* Workshop was a bit too long (10-15 minutes) and people seemed to be overwhelmed by the end of the session (probably also for the lack of fresh air in the room.

### Peer-learning

##### Will & Akvile | What are **algorithms**?

Good:

* Examples of algorithms in action on the Web, even on daily life
* Who's a social media addict unplugged activity
* > Algorithm shows a list of results based on a search

Maybe narrowed it down to much on search algorithms. 

##### Dean | What are **functions** and how do you use them?

Good: 

* Really nice presentation-page 
* Started with the theory and benefits of using functions

Can improve:

* Demo could have explained what the purpose of the function was before demoing it
* Didn't use unplugged computing...

##### Afsara & Malore | What are `if` statements (aka **conditionals**) and how do you use them?

Good:

* Intro explanation, nice video with Bill Gates
* Simple demo

Can improve:

* tripped up a bit on the variable
* no unplugged computing

##### Francisco & Ajay | What are **loops** and how do you use them?

Can improve:

* F demo a bit too fast
* no unplugged computing

##### Ben & Rosie | What is the **JavaScript Console** and how do you use it? 

Can improve:

* bit rushed explanation of the console.table
* other Console methods mentioned but right through heads 

##### Joe & Rajeev | What is the **GeoLocation** API and how do you use it?  

Good:

* Explained APIs first `What is an API?`
* Asked `What are interesting uses of geolocation?`
* > in 7 steps :)
* Demo: shared template + finished code 

## Week 3

### Notice a pattern?

Noticed several people had

```js
var resultsList = filterAndSortList(peopleList, chosenOption) 
var chosenOption = homeDropdown.val()
```

I must have explained it in a twisted way.

Maybe I should put number in the comment lines, eg:

```js
// 1. capture the user chosen option
```

### What happens when someone clicks on a result?

Many people didn't understand the `$('#results li').click` code had to be nested inside the function reacting to `homeGoButton.click`. [See Dean for instance](https://github.com/deanlc/apptemplate/commit/31d0e576d40f62dfcfeb9f32ed9d26463b3e1690#diff-77ab163850ef0fa98d6a9ee9fb6bbcafR51), who wasn't in class and used the gh tutorial to build his app.

Maybe put the whole, finished function on the gh tutorial? 

### Group interface variables?

```js
var interface = 
{
	home:
	{
		section: $('#home')
		// etc.
	}
}
```

### Refactoring

Functions like `showList` and `showDetails` are not really showing, but rather using a template to inject data in the DOM. Should be renamed... 

### Brainswarming

Try it on the wall? Easier to photograph...













# 2015

## Week 2

### Peer learning

* Make the groups and/or assign topics?

* [Objects of intense feeling](http://computationalculture.net/article/objects-of-intense-feeling-the-case-of-the-twitter-api) too long and hard to make sense of. Maybe give them only one section of it to research and comment on (3-4 minutes read).

### Tutorials

Didn't get time to do that..


