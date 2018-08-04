# Tohoku-University-6D-Pose-Estimation-Dataset-
This is an open dataset for evaluating pose estimation algorithms which are designed for the bin pikcing task using chanllenging industrial parts. 
To evalaute the performance of pose estimation for bin picking system, the scenes in this dataset are made to close to the real situation in the factory.

## Characteristics of Scenes
* Only one type of parts are randomly piled up in a scene.
* The number of parts in each scene is more than 15. 
* The parts are normally made of resin, no discriminative color, no texture, often same in shape.

## Constructions 
This dataset is divided into 2 parts, namely, simulation and real scene data.  
In each part, you could find the scene files and pose files. 
(Now, only the simulation data of 3 parts are uploaded. 
More parts and their real scene data are being prepared and coming soon.) 

## Sensors
We used the 3D sensor named Ensenso n35 and a 2D camera named USB 3 uEye CP Rev. 2.
The relative postition between the 3D sensor and 2D camera is calibrated, so that the correspondence between each pixel of the image and each point in point cloud can be obtained and stored in an .csv file.

## Authors
Diyi Liu, Shogo Arai, Jiaqi Miao, Kinugawa Jun and Kosuge Kazuhiro

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Note
The parts in the data set are still in the preparetion stage, we are going to realse them until 15th September. 
