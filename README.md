# AR Development for Design and Construction at Geopogo

This project is developed by Yongjae Chung, Om Babar, and Navein Suresh at Geopogo, a startup that brings design and construction management into augmented reality (AR). The team is working on the main application, Creator Pro, which is currently available for Magic Leap. The goal of the project is to enable the placement and manipulation of models (buildings or landscape) in the AR space.


## Plane detection
The team used the AR camera to detect flat surfaces in a 3D space. Model placement was achieved by adding an additional script to the plane detection scene that allows the user to touch (select) a flat surface to place a model.

## Model placement and manipulation

The current implementation of model placement and manipulation is handled by MRTK.
The team is currently working on an alternative approach for model manipulation using gizmos, which will allow the user to move the models more precisely by limiting input to one dimension at a time. This will require the incorporation of multiple scripts for object selection and gizmo selection and control.

The final goal is to integrate these demos into the Magic Leap headsets. This will allow the project to be further developed and successfully launched as a product.