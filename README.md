# basic-calculator

How to finish this assignment

1. download node from website for your operating system
    * https://nodejs.org/en/
2. download a code editor such as VSCode 
    * https://code.visualstudio.com/
3. Install git on your computer 
    * https://gitforwindows.org/
4. fork this repository 
    * https://docs.github.com/en/get-started/quickstart/fork-a-repo
5. clone the forked repository onto your computer
    * https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository
5. from `git bash` or cmd line navigate to the cloned repository
    1. from cmd line use cmd `cd to/your/folder` do get to your folder
6. run `npm install` when your in the folder
7. then run `npm test`
8. you should see some thing like this
    1. ```
       add success
       subtract failed 1 - 1 = 0
       mulitply failed example multiply(10, 10) = 100
       divide failed example divide(10, 2) = 2
       double failed example double(5) = 10
       ```
9. go look at the file `basic-calculator.js` and open it. You can probably just open the folder in VSCode.
10. write the code where it says write your code here. It should look similar to the `add` function just for subtract and stuff
12. run `npm test` and you should see it succeed. there is a little suprise printed
13. now push your changes to your forked repository
    1. you can simply run `git add basic-calculator.js` and then run `git commit -m "commit"` then run `git push`
