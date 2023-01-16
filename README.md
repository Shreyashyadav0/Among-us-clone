of data are created and thus we can use the data whatever we want 

Loaders- these are plugins 
plugins are node modules which are passed to webpack to handle your bundle js
vendur js- node modules are very very large so we pack vender.js and cache them in the memory.

package webpack : "4.0.0"
Scripts:{ "start": webpack -dev-server
index.js
}
'
webpack are for optimization 

Phaser :
Then sir explained about classes they just template for reuseablity purpose, we create instance of it with constructor known 
as objects , javscript is not object oriendted programming language it gave us jugad for constructor
class Mygam extends Phaser.scene
constructor(){
Super();

}
Here we are going to create Among-us which is multi player game 
now we are creating out boundries inside the png image of ship also we have png image of 3 players
we use fs here where we define the boundries using logic
then we made out constants
then we made out server connected it to socket.io any request from 8080 will be alowed and then we made the connection and 
move from side to side, it is just a formula to get all the boundries
we are using css sprites to cut the images into pieces so that we can replicate the movement 
then we made out utils 
as we have webpack in frontend we are using import as it is supported by es6
then we wrote the player up and down logic how much we have to move up and down according the speed
move up, move down , move left , move right
then we check if player is playing the game or just running around 
then we have our webpacks where we have base.js and prod.js
then we load our different players and load different images and gave there size to them
then we made out event listeners to key down and key up events
then we wrote the logic of moving 
we preloaded everything and then create and then updated everything 
