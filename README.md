justpick
========

Node CLI app to make an arbitrary choice.


Whenever trying to decide what to watch/eat/believe, I'd often find myself pulling open a REPL and writing a line or two to randomly pick from a set of options, so I figure I'm saving myself a handful of keystrokes every week by writing a little module to do it for me. 

Install with `npm install -g justpick` and hand `justpick` however many arguments you care to. It'll pick+log a single one to spit back:

```
$ justpick cupcakes pie cookies icecream "an entire bag of sprinkles"
cookies
```

The module itself exports a function that you can pass an array and get back the choice:
```
var pick = require('justpick');
pick(['foo', 'bar', 'baz']); 
//baz
```


Enjoy now-convenient third-party random decisions to handle your meal selections and career choices.
