Its just a personal portfolio and MY FIRST PROJECT EVER which is built using HTML and CSS (and soon JavaScript!) to highlight my journey in web development, including projects I’ve worked on, technologies I’m learning, and how to reach me.

Connecting github to our local machine: (if you wanna know else you may skip it)
We created a folder on our local machine and opened it in the VS Code editor.
Then, we moved into the terminal and connected the project (or the local machine) with GitHub.
To do this, we moved into the project directory and ran the command "git init".
After checking with the command "ls -a" which lists all files, including hidden ones,we saw that Git was now tracking our project.
Then, We connected our github repo to the local machine. Used the following command: 
git remote add origin https://github.com/your-username/your-repo.git
Then we created our desired files, which in our case were the HTML and CSS files.
We added them as usual using the command "git add ." (git add all).
Then we committed those files using the command: "git commit -m "wrote our message""
and then pushed all of our content 
and boom, we were live yaay :)

Summary:
cd your-project-folder         # Navigate to your project folder
git init                      # Initialize Git repo
git remote add origin https://github.com/your-username/your-repo.git   # Link remote repo
git add .                     # Stage all files
git commit -m "your message"  # Commit changes with a message
git push -u origin main       # Push to GitHub (replace 'main' if needed)
