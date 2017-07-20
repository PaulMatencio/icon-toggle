
#  Toogle Icon 


##  Installation 

1.  Install `bower` and the Polymer CLI:

        npm install -g bower polymer-cli

2.  Clone this repo:

        https://github.com/PaulMatencio/icon-toggle


4.  Change directory to your local repo and install dependencies with `bower`:

        cd icon-toggle
        bower install

5.  To preview your element, run the Polymer development server from the repo directory:

        polymer serve --open 


##  Properties 

1.  Public properties 
     
	toggle-icon 	String 	
	pressed		Boolean



### Examples


1.	`<icon-toggle toggle-icon="star"> <icon-toggle>   
	Icon is not pressed`


2.	`<icon-toggle toggle-icon="star" pressed> <icon-toggle>  
	Icon is pressed`


3.	`<icon-toggle toggle-icon="star" pressed="{{variable}}"> </icon-toggle> 
	Icon is pressed if variable is True`
