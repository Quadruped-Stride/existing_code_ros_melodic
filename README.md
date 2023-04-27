## Steps
Follow the follwing steps to clone and upload your work.  

    git clone https://github.com/Quadruped-Stride/existing_code_ros_melodic.git

    cd existing_code_ros_melodic/

Make a new branch and change your branch to the new branch using the following line. Keep your branch name to be your name. Always work on this branch only.

    git checkout -b <your branch name>

Add all the files in this particular branch in your local directory. The following command adds all the files locally 

    git add . 

To push your files locally we use commit. 

    git commit -m "<write sensible comment about what files you have uploaded or what changes you made>"

Now to push your files to github use git push 

    git push origin <your branch name>
