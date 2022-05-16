# Deep API Learning (for Python dataset)

This is a fork of the [Deep API Learning](https://github.com/guxd/deepAPI) project.  The project is modified to be able
to load the Python dataset at [zenodo](https://zenodo.org/record/6388030).  The main difference is that the Python 
dataset does not explicitly store the size of each instance; instead, each instance is assumed to continue until the
start of the next instance or until the end of the array.  (There is no particular reason why it had to be done this
way.)

For more information, see the [Deep API Learning Revisited](https://github.com/hapsby/deepAPIRevisited) repository.