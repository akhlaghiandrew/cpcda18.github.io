## Week 5:



### Class Objective

String manipulation
concatenation (e.g. addition of strings)
indexing
slicing
len()

Open Terminal in macOS and launch our Docker container:

```
docker rm -f pcda_ubuntu
docker pull pcda17/ubuntu-container
docker run --name pcda_ubuntu -ti -p 8889:8889 --volume ~/Desktop/sharedfolder/:/sharedfolder/ pcda17/ubuntu-container
```

In Windows 10, open PowerShell and enter the following to launch the Docker container:

```
docker rm -f pcda_ubuntu
docker pull pcda17/ubuntu-container
docker run --name pcda_ubuntu -ti -p 8889:8889 --volume C:\Users\***username_here***\Desktop\sharedfolder:/sharedfolder/ pcda17/ubuntu-container
```

Right click the following link and choose "Save as ...," then save the file in `sharedfolder` on your desktop.

http://nbviewer.jupyter.org/github/fbkarsdorp/python-course/blob/master/Chapter%201%20-%20Getting%20started.ipynb

Go to: String Manipulation.


<!--

[https://raw.githubusercontent.com/pcda17/pcda17.github.io/master/week-05.ipynb](https://raw.githubusercontent.com/pcda17/pcda17.github.io/master/week-05.ipynb)


Go to [localhost:8889](localhost:8889) and click on `week-05.ipynb` to launch the notebook.

-->
