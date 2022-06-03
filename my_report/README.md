# Lesson: Interaction Design

### First and Last Name: Thanasis Slavidis
### University Registration Number: dpsd19120
### GitHub Personal Profile: https://github.com/ThanosSl
### Augmented Reality Personal Repository: https://github.com/ThanosSl/Augmented-Reality

# Introduction

# Summary


# 1st Deliverable
* At first, I downloaded Atom and I linked my GitHub account so I could adjust the code. I found the code for the other two shapes, the sphere and the cylinder. Then I entered the code for the other two shapes(cylinder, sphere) and at last I found the code from the links to enter the voice and the snow. For the voice, I changed some commands to 'start' - 'stop", to start and stop snowing with the shapes. 


# 2nd Deliverable
* Αρχικά έφτιαξα το εσωτερικό του marker, για το dpsd marker, στην ζωγραφική. Στη συνέχεια, μέσω του [AR.js Marker Training] (https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html) έβαλα τις jpg εικόνες του dpsd, του οξυγόνου, του υδρογόνου (οι οποίες υπήρχαν ήδη) και έφτιαξα τα markers. Έπειτα ανέβασα στο φάκελο assets τα παρακάτω, ώστε να τα εντάξω στον κώδικά μου. ![This is an image](/marker_based/Assets.png) 
* Μετά έφτιαξα τα δύο άτομα υδρογόνου και οξυγόνου στο blender: ![This is an image](https://github.com/ThanosSl/Augmented-Reality/blob/main/marker_based/Hydrogen_Atom_Blender.png) ![This is an image](https://github.com/ThanosSl/Augmented-Reality/blob/main/marker_based/Oxygen_Atom_Blender.png) 

* Tα αποθήκευσα σαν .gltf αρχείο και τα πέρασα στον κώδικα. Έτσι λοιπόν έκανα τα απαραίτητα adjustments στον κώδικα έτσι ώστε να εμφανίζει το κάθε τι όταν πρέπει, ανάλογα με το κάθε marker (pattern-dpsd.patt, pattern-card-H.patt, pattern-card-O.patt). 

* Έπειτα, έφτιαξα και ένα animation για το νερό: ![This is an image](https://github.com/ThanosSl/Augmented-Reality/blob/main/marker_based/H2O_Atom_Blender.png) 
 
 και προσάρμοσα τον κώδικα για το τρίτο <<υποπαραδοτέο>>, με τη απόσταση των δύο markers, οι οποίοι όταν θα είναι σε απόσταση μικρότερη των 2 μέτρων θα εμφανίζουν το    animation του νερού, ενώ όταν απομακρίνονται θα εμφανίζουν πάλι τα δύο άτομα υδρογόνου και οξυγόνου αντίστοιχα.

# 3rd Deliverable 
* Όσων αφορά το index.html, το αρχείο δηλαδή με αξιοθέατο επιλογής μας, στο location based φάκελο πάντα, αρχικά επέλεξα το 3D model από το [Sketchfab] (https://sketchfab.com/3d-models/christ-the-redeemer-d143e5357efd42529777438d0f72c79c) ![This is an image](https://github.com/ThanosSl/Augmented-Reality/blob/main/location_based/assets/Christ_The_Redeemer_Photo.png) 
 
* Το κατέβασα ως gltf αρχείο, το έβαλα στον κώδικα και έκανα τις απαραίτητες αλλαγές έτσι ώστε να κλικάρεις πάνω στο 3D μοντέλο και να βγάζει κείμενο με πληροφορίες για αυτό, από [Wikipidia] (https://en.wikipedia.org/wiki/Christ_the_Redeemer_(statue)).

* Έπίσης, έβαλα και εντολή έτσι ώστε να περιστρέφεται το αγαλματίδιο και τέλος, το έκανα adjust ώστε να φαίνεται καλύτερα στην οθόνη.  

# Conclusions


# Sources
A-Frame Library , https://www.npmjs.com/package/aframe-speech-command-component , https://aframe.io/aframe-school/#/ , https://aframe.io/blog/arjs/ , https://stackoverflow.com/questions/61239107/how-to-get-marker-position-x-y-ar-js, https://www.latlong.net/, https://en.wikipedia.org/wiki/Christ_the_Redeemer_(statue), https://glitch.com/~salty-partner-1, https://sketchfab.com/3d-models/christ-the-redeemer-d143e5357efd42529777438d0f72c79c, https://github.com/AR-js-org/AR.js/issues/216, https://sparkar.facebook.com/ar-studio/learn/reference/classes/touchgesturesmodule/#properties, https://sketchfab.com/3d-models/christ-the-redeemer-d143e5357efd42529777438d0f72c79c 
