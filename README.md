# belajar_git

**create a new repository on the command line**

~~~
echo "# belajar_git" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/smartwarehouse/belajar_git.git
git push -u origin master
~~~

**or push an existing repository from the command line**

~~~
git remote add origin https://github.com/smartwarehouse/belajar_git.git
git push -u origin master
~~~


**Tambah USER GLOBAL**
~~~
git config --global user.email "email@example.com"
~~~

**Tambah EMAIL GLOBAL**
~~~
git config --global user.name "username githubmu"
~~~
