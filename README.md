# ISTE SMP 19
ISTE Summer Mentorship Programme 2019 Projects


## Instructions to submit assignments

**1) Fork the repository.**

**2) Clone the forked repo:**

     git clone https://github.com/your-username/SMP19.git

**3) CHange directories and then change into the directory for your respective SMP**

     cd SMP19
     cd <SMP Name>
  
**4) Create a folder with the current week number. Then inside that create a directory with your name.**
     Inside the folder create a text file with your details.
     
     mkdir Week-<X>
     cd Week-<X> // where X corresponds to the week number
     mkdir your-name
     cd your-name

**5) Add and commit changes. Push it to your repository.**

    git add .	// adds all files
    git commit -m "Your message"
    git push origin master

**6) Login to github and send a pull request to *ISTE-NITK/SMP19****
To configure upstream:

    git remote add upstream https://github.com/ISTE-NITK/SMP19.git
    
To pull the latest changes:

    git fetch upstream
    git checkout master
    git merge upstream/master

