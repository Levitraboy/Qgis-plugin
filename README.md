# Team-99 Final Assignment Report 
* Introduction 
  * Collaboration principles
    * GitHub repo URL: https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99.git
    * Main branch used <br/>
  * Teammates & contribution
    * Ali Gürcan Baki: First of all, Ali Gürcan Baki established the basic scaffolding of the study and created the necessary buttons and functions. After that, Ali initialized the folder he was going to upload to github using the "git init" command. Then the branch changed its name from master to maine which is the primary branch of the project. Then "git add." Added all files using Then he used the command "git remote add origin <REMOTE_URL>" to connect the repo to the local computer. Finally, he added the files to our repo using the command "git push origin main".
    * Semih Güzel: First of all, Semih Güzel pulled the existing Github repo to the local repo using "git clone <REMOTE_URL>". Afterwards, Semih Güzel did the part of the work, saving the shortest and the farthest distance on the shape file when the point layer was selected. Upon the user's choice, an id or name column has been added to the existing shapefile file. Afterwards, he completed the process of opening the saved shape file in QGIS. Finally, "git add." Added using the command. Following this step, he has uploaded the latest version of the project to github by using "git commit -m" and "git push origin main" commands.
    * Emre Demiriz: First of all, Emre Demiriz pulled the existing Github repo to the local repo using "git clone <REMOTE_URL>". Afterwards, Emre Demiriz created the function of calculating the shortest and furthest distance using the line layer. He added the current outputs as a column on the active line layer. Following this step, he has uploaded the final version of the project as v1 to github by using the "git commit -m" and "git push origin main" commands.
* Methodology
  * Work of Semih Güzel: During the plugin development phase, Semih Güzel developed the plugin that allows to change the properties such as color and thickness of the shortest and longest distance line obtained. In the plugin section, 2 different buttons have been developed so that values such as color and thickness can be obtained from the user. </br>
    ## Semih's color and thickness extension
    <img src="https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99/blob/main/images/semih_eklenti.png" width="400"> </br>
    ## Result of color and thickness extension
    <img src="https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99/blob/main/images/semih_work.png" width="400"> </br>
  * Work of Ali Gürcan Baki: In the plugin development phase, Ali Gürcan Baki developed the plugin that allows to change the opacity value of the shortest and longest distance line obtained. In the plug in part, he obtained the opacity value from the users by using the horizontal slide bar. </br>
    ## Ali's opacity extension
    <img src="https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99/blob/main/images/ali_eklenti.png" width="400"> </br>
    ## Result of opacity extension
    <img src="https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99/blob/main/images/ali_work.png" width="400"> </br>
  * Work of Emre Demiriz: During the plugin development phase, Emre Demiriz developed a plugin that displays the shortest and longest distances on the screen. By using the pop-up message method in the plugin section, he allowed users to see the shortest and longest distances without looking at the attribute table.
    ## Emre's pop-up extension
    <img src="https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99/blob/main/images/v2_proof_2.jpg" width="400"> </br>

* Final Task: Revert back to Version 1 </br>
  In the final task of the project, we needed to revert to V1 of our work. To complete this task, we started by getting the commit id of the V1 files that we have uploaded to our github repo. This is our commit id for V1 "be00c7846574d389faa0607a342aca2ef915af63". Then in our github local repository we opened new git bash. Later, we reverted back to V1 by using "git revert --no-commit <your commit id>" command. The proof of the successful completion of the task were given as screenshots in the images folder.
  * Proof of Reverting Back
  ## We acquired commit id from our github repository
  <img src="https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99/blob/main/images/v1_completed.png" width="700"> </br>
  ## Reverting process in cmd
  <img src="https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99/blob/main/images/revert%20back%20cmd.png" width="400"> </br>
  ## Representation of commit id in code
  <img src="https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99/blob/main/images/revert%20back%20python.png" width="400"> </br>
  ## Reverting process in PyCharm GUI
  <img src="https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99/blob/main/images/reverting.png" width="400"> </br>
  ## Version 1 displayed on QGIS
  <img src="https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99/blob/main/images/v1_proof.png" width="400"> </br>
  ## Fields added to the layer when No ID button clicked
  <img src="https://github.com/GMT-456-GIS-Programming/qgis-plugin-team-99/blob/main/images/v1_proof_3.jpg.png" width="400"> </br>
  
