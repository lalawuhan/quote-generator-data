## About 
I would like to add more quotes to my women in tech quote generator and also help some of my cohort members who have not made their first contributions using github. This is used as a learning guide for me too. 

### Contributions needed
I would like more quotes from **women in tech** that inspire you. 

### How to contribute
1. Fork this repository by clicking on the fork button on the top of this page. 
2. This will create a copy of this repository in your account.
3. Now clone the forked repository to your computer to create a local copy.

**If you are not sure on how to do step 3** :
* Go to your GitHub account, open the forked repository, click on the clone button and then click the copy to clipboard icon.
* Open your terminal and run the following git command :
```
git clone "url you just copied"
```
### Next Steps
1. Change to the repository on your computer, if you are not there already
   ```
   cd quote-generator-data
   ```
2. Create a branch using the git checkout method
    ```
    git checkout -b "yourname"
    ```
3. Add the quotes from women in tech into the quotes.json file. 
   * Please follow the quotes.json file format, add your quotes to the end.
   * Each individual quote should be in one json block. 
  
**Example:**
   ```
    {
        "author": "write the author in here",
        "quote": "Write the quote in here",
        "position": "Write the job position here"
    },
   ```
1. Save the file
2. Add changes to the branch by using the **git add** command:
   

    ``` git add quotes.json ```
3. Commit the changes using the **git commit** command:
   ``` 
   git commit -m "Added new quote - <your name>
   ```
   replace `<your name>` with your name. 
### Push Changes to Github
   Push your changes to your branch 
   ``` 
   git push origin <your-branch name>
   ```
replace `<your branch name>` with your name. 
### Submit your changes for review
1. If you go to your repository, you will see a `Compare & pull request` button. Click on that button. 
2. Now submit the pull request
3. I will check if the json format is valid and merging your changes into the master branch of the project. 

Congrats, you did it and thank you for contributing.

### Acknowledgements
* [first-contributions](https://github.com/firstcontributions/first-contributions)