# hello-world
my first repository-hello-world

Hi Humans!

Hubot here, I like Node.js and Coffeescript (that's what I'm made of!).
I've had tacos on the moon and find them far superior to Earth tacos.

2016-4-5

Learn to push.

git remote add origin git@github.com:LinHuican/hello-world.git

git add README.md

git commit -m "Learn to push."

git push origin master

git push -u origin master


/**********************************************************************************/

要关联一个远程库，使用命令

git remote add origin git@server-name:path/repo-name.git；

关联后，使用命令git push -u origin master第一次推送master分支的所有内容；

此后，每次本地提交后，只要有必要，就可以使用命令git push origin master推送最新修改；


#create a new repository on the command line
echo "# ROS_Tutorial" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/LinHuican/ROS_Tutorial.git
git push -u origin master

#push an existing repository from the command line
git remote add origin https://github.com/LinHuican/ROS_Tutorial.git
git push -u origin master
