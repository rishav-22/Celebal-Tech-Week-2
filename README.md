# Initial setup
cd path/to/your/directory
git init
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
echo "Hello, World!" > hello.txt
git add hello.txt
git commit -m "Add hello.txt with initial content"
git push -u origin master

# Creating and working with a new branch
git checkout -b new-branch
echo "This is a new line" >> hello.txt
git add hello.txt
git commit -m "Add a new line to hello.txt"
git push -u origin new-branch
