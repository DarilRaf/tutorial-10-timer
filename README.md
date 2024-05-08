<h1>Understanding how it works</h1>
![alt text](image.png)

The "Daril's Komputer: hey hey" line is executed first because it was out of the asynchronous scope.
Meanwhile "Daril's Komputer: howdy!" and "Daril's Komputer: done!" lines executed after because it is waited first, after the "hey hey" line.
