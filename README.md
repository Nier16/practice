# practice

Ideas : 

1- Like Youtube : 
  - Upload videos
  - create playlists 
  - create profiles
  - play content

2- Workout app : 
  - upload excercices (description, video)
  - build workout sessions
  - fill workout session report 
  - Create profiles



Create And Add SSH key to GIT : 
- open git bach
- enter commande : ssh-keygen -o -t rsa -C "{mail}" (enter + enter + enter)
- enter commande : eval "$(ssh-agent -s)"
- enter commande : ssh-add ~/.ssh/id_rsa
- enter commande : cat ~/.ssh/id_rsa.pub
- copy content
- go to git hub -> settings -> SSH AND GPS KEY -> NEW SSH KEY 
- enter any title you want and past content of what you did copy in "key" field
- create

Clone Project : 
- Go to the projet on git : https://github.com/Nier16/workoutAmigoFront
- Code -> SSH -> copy the link
- open cmd in the folder you want to clone the project on your local pc
- enter : git clone {the copied link}

Create new branch :
- open cmd in the project folder on your pc
- enter commande : git checkout -b {branch_name}
- convention name is everything in lowercase with words separeted with '-'
- "-b" tell to git to create a new branch, when not using it, you tell to git to just change for a branch that already exist.

Commit : 
- git add * (to add all files that you did modify, delete, or create)
- OR git add {file_name} (to add file by file to the commit)
- git commit -m "{comment_of_the_commit}"
- git push
- if the branch is new, git will tell you that you have to use another commande, just copy that commande and past it
