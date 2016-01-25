# Text Statistics
A simple webpage to give basic statistics on text, and to work with selection of the same. I built this because I recently faced an issue while experimenting with [cTakes Parser](http://wiki.apache.org/tika/cTAKESParser). A quick introduction to what cTakes Parser does is, is that it searches for various terms, like symptoms, dates, medical terms and highlights them to the user. Now, when you run cTakes parser on a huge document, its output is in [this](http://wiki.apache.org/tika/cTAKESParser#Putting_it_all_together:_Tika-App) format.

For instance, this is one line in the output
```
ctakes:AnatomicalSiteMention: stem cell:21200:21209:C0038250,C0018956,C0038250
```
Here, `21200` is the start index, and `21209` is the end index and that contains the word `stem`. So this is where the problem comes in. I had to find a simple way in which if I specify the start index and the end index, then that part of the document would be highlighted. Now, there are various websites that gives you simple tools to work on text, but unfortunately, I couldn't find one at my disposal and simlpy built this simple tool.

# Usage
Its very simple to use. Simply copy the text that you want to work with, and thats it! You can immediately see the text statistics. You can also select some part of the text, and see the details about that. And you want to go to a particular index, or highlight some text by specifying the start and end index, you can do that too.
