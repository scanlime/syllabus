Unit 1 - Using Git!
----

From this point forward you will keep all your exercises in a git repository!
By doing this you can share your progress with your mentor easily. Additionally
your mentor will be able to provide you with feedback and suggestions via git,
which will get you acquainted to the way programmers work together in teams!

The next step is to make your first local repository:

**Your first Commit!**

1) At the command line create a new directory for you git repository:

    mkdir helloworld

2) Change your current working directory to the directory you just made:

    cd helloworld

3) Turn your directory into a *git repository* by initializing it with the following command:

    git init

4) Create an empty `README.txt` file as our first file:

    echo "Hello world" > README.txt

5) Now lets **add** our changes to git:

    git add README.txt

6) Before our changes are saved, we must **commit** our work:

    git commit -m 'Added README.txt file'

7) Check to see if our changes were commited, you should see the message you added "Added README.txt file":

    git log

And thats it! You did it. You should now have your first repository with your first commit!


### **Exercises**

* Create a Python program to print out "Hello Python!" with the text editor. Save the file as `Unit1.py` and then **add** and **commit** it to your repository.
* Create a new repository on https://github.com named `hypatia-exercises` and then add the **remote** repository and **push** your repository to it.
