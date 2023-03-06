## Augmented Reality
 
## Description
              In this Module, I will show you how Augment Reality works in your Mendix using AR.js. This helps us the possibility to reduce design, production, and maintenance costs
              
## Dependencies:
       Mendix Modeler 9.21.0
## Configuration:


  Add these two scripts in the index.HTM file 
  
  
	<script src="https://aframe.io/releases/0.6.0/aframe.min.js"></script>
  
  
	<script src="https://jeromeetienne.github.io/AR.js/aframe/build/aframe-ar.js"></script>
  
  
	Add Entity to include the Image and generalization with System.Image and generate Overview pages.
  
  
	Add the Blank page and include a Data container (Dataview) and configure the entity.
  
  
	Add the AR Snippet.
  
  
	Add the js External file in the HTML snippet - It will enable your device camera
  
  
	I have added the AR.js dependency files in your project path (\themesource\augmentedreality\web\ARJS) location.
  
  
	configure the exact path in HTML Snippet.
  
  
	Finally we got the AR glass 
