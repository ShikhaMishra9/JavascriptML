# JavascriptML
#Javascript with Machine learning

***************
# Artificial Intelligence JS
Machine Learning and AI experiments using Node.js as server, **client-side JavaScript** operations and and MongoDB as data source.

../data/ folder contains the example database, called 'dataset', with a training set in every collection.

All the important stuff is client side and is in the ../public/javascripts/ folder, Node.js is only used as a server and to retreive data from MongoDB.


## Implemented algorithms
* a simple C4.5
* a simple K-Means
* Cross Validation
* Simulated Annealing
* Genetic Algorithm

***

##Installation
To use the main functions we really just need a browser and the stuff in the ../public/javascripts/ folder.
Just give it a data set in JSON format (se demo.js or tests.html for some examples).

For server and database functions we must first install [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.org/).
Then simply open a terminal and run this command:
```bash
cd /your/path/to/Machine-Learning-JS/
npm install
```
It has to be done only the first time in order to install the required modules.

Then  run one of those commands in a terminal (depending on your OS):
```bash
#(Unix)
/your/path/to/mongod --dbpath /your/path/to/Machine-Learning-JS/data
```
```command
::(Windows)

"Drive:\your\path\to\mongod.exe" --dbpath "Drive:\your\path\to\Machine-Learning-JS\data"
```
And this one in another terminal to start the server (of course current directory has to be the project folder again):
```bash
cd /your/path/to/Machine-Learning-JS/
npm start
```
Finally go to [localhost:3000](http://localhost:3000) in your browser and wait for the data to be loaded (it may take a while depending on your hardware).

***

Some important libraries:

http://caza.la/synaptic/#/

https://brain.js.org/#/

https://www.tensorflow.org/js

http://stevenmiller888.github.io/mindjs.net/

https://cs.stanford.edu/people/karpathy/convnetjs/

https://ml5js.org/

https://transcranial.github.io/keras-js/#/
