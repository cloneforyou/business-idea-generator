# business-idea-generator
Business idea generator is only a proof of concept draft made for Eduardo Duque; A series of random messages ('business ideas') are generated randomly from a vector of strings in JavaScript, which is written to a HTML+CSS page, as HTML DOM allows JavaScript to change the content of HTML elements, in this case, using `innerHTML` to do so. 

## How is it done
Because the formatting of the page takes a considerable amount of code (it was only made to be contextualized, it is not an end product brilliant finished project), the "important" part is this:

```
var businessIdea=document.getElementById('businessIdea');

		for(x=0;x<Math.round(Math.random()*10);x++)
		{
		var tempVar=Math.random();
		}

		window.onload=Math.random;
		window.onload=generateBusinessIdea();

function generateBusinessIdea()
		{
			businessIdea.innerHTML=inicio[Math.round(Math.random()*(inicio.length-1))]+' '+mitad1[Math.round(Math.random()*(mitad1.length-1))]+'\n';
		}
```

## Expanding the number of generated phrases
Since when iterating through all entries of the vector the property `length` is used, you can add directly new strings to the existing variables without changing anything else.
