#Chris Hope's Johnny Papa React Style Guide

If you're like me, the single most frustrating thing about learning how to develop a React application is that every tutorial uses its own unique-snowflake version of the syntax. Couple that with the fact that React code now spans the ES5-7 range and you're quickly saying "hello nightmare" instead of "hello world".

####But don't worry help is here

I've got the opinionated guide on how to write your react components in a way that everyone can understand and follow.  With the help of this guide you'll quickly be writing code that you can, and anyone else that has to look at it, can understand.

####How's this possible, you ask?

Simple. *Rules, and lots of 'em.*

People love lists, that's obvious so let's start there

1. Declaring React Components

You'd think this one is basic, but you'd be surprised...

```javascript
//What the docs provide, and what you should NOT be doing

var StupidComponent = React.createClass({
	render: function () {
		<div>
			<h1>I am written using dated syntax!</h1>
		</div>
	}
});


//A much better, ES6 syntax

class AwesomeComponent extends React.Component {
	render () {
		<div>
			<h1>Now your friends will think you are so cool</h1>
		</div>
	}
}
```