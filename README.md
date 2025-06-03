Its just a personal portfolio and MY FIRST PROJECT EVER which is built using HTML and CSS (and soon JavaScript!) to highlight my journey in web development, including projects I’ve worked on, technologies I’m learning, and how to reach me.

Connecting github to our local machine: (if you wanna know else you may skip it) <br>
We created a folder on our local machine and opened it in the VS Code editor.
Then, we moved into the terminal and connected the project (or the local machine) with GitHub.
To do this, we moved into the project directory and ran the command "git init".
After checking with the command "ls -a" which lists all files, including hidden ones,we saw that Git was now tracking our project.
Then, We connected our github repo to the local machine. Used the following command: <br>
git remote add origin https://github.com/your-username/your-repo.git <br> 
Then we created our desired files, which in our case were the HTML and CSS files.
We added them as usual using the command "git add ." (git add all).
Then we committed those files using the command: "git commit -m "wrote our message""
and then pushed all of our content 
and boom, we were live yaay :)

Summary: <br>
cd your-project-folder         # Navigate to your project folder <br>
git init                      # Initialize Git repo <br>
git remote add origin https://github.com/your-username/your-repo.git   # Link remote repo <br>
git add .                     # Stage all files <br>
git commit -m "your message"  # Commit changes with a message <br>
git push -u origin main       # Push to GitHub (replace 'main' if needed) <br>

Faced a problem: 
Local machine was not able to push the commits to the git hence we used the following command and then pushed it and yeah it worked >3
Command: 
git pull origin main --rebase

