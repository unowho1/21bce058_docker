

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"


  // flask code for basic crud operations for hms system.

  commands to upload hms with docker image into the github repo
  # Navigate to your project directory
cd /path/to/your/project

# Initialize a git repository if you haven't already
git init

# Add your files to the staging area
git add .

# Commit your changes
git commit -m "Initial commit with Docker image"

# Add the remote GitHub repository
git remote add origin https://github.com/your-username/your-repo-name.git

# Push your changes to GitHub
git push -u origin master
docker push your-dockerhub-username/your-image-name:latest
docker login
docker tag your-image-name your-dockerhub-username/your-image-name:latest

