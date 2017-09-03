![alt text](https://raw.githubusercontent.com/yanshiyason/satori-github-viewer/master/githubEvents3.png "Screenshot3")

# What is it?

It's a real time visualization of the commit count of all github repositories.
It uses [Satori's github events channel](https://www.satori.com/channels/github-events) for the data.

# Credits

I used @mbostock's d3 [Bubble Chart template](https://bl.ocks.org/mbostock/4063269)
for the visualization.

# How is this useful?
It's not. It will suck up all your computer's memory in about 10 minutes.

# What did you find out?
Some people do terrible things to GitHub's servers...

[nicopeters/sigrhtest](https://github.com/nicopeters/sigrhtest)

[This guy made 800+ automated commits with the same commit message.](https://github.com/nicopeters/sigrhtest/commits/master?before=47347a0546b4c77f9be6094fe04e8eeb21fd3962+350) in a few minutes 🤣. His repo is now over 250k automated commits.


![alt text](https://raw.githubusercontent.com/yanshiyason/satori-github-viewer/master/githubEvents1.png "Screenshot1")

[curtclifton/curtclifton.github.io](https://github.com/curtclifton/curtclifton.github.io)

[This other guy made over 2k commits in a few minutes](https://github.com/curtclifton/curtclifton.github.io/commits/master?after=833ca49922541782159f794ab0bfe2ca66559502+34)
His repo is over 142k automated commits.

![alt text](https://raw.githubusercontent.com/yanshiyason/satori-github-viewer/master/githubEvents2.png "Screenshot2")

# Conclusion

Finding any relevant data through this method is completely useless.
Make's me wonder how github finds trending repositories...
They must have a way to exclude such repos with high frequency automated commits..
