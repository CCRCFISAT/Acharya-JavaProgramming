# Acharya-JavaProgramming

This repo contains contributions to project Acharya, an Open Smart Education Initiative. Submissions in the domain of Java programming  are welcome.  You are contributions will be made available in the Acharya E-Learning platform.



# How to make Contributions

You can submit Jupyter notebooks that illustrates the working of java programs. Please check the topics to be covered. However, you do not have to restrict the submissions to the list of topics to be covered. Make sure to include figures and videos in your notebook.

For those who are confused as to how jupyter notebooks are possible for java, please refer to IJava, which is a jupyter kernel for java.

So now let us install IJava

Open your terminal and do the following:
```
git clone https://github.com/SpencerPark/IJava.git
cd IJava/
```

What you have done above is that you cloned a repository and changed your directory to the cloned directory, after doing the above steps, do the following:
```
gradlew installKernel
```

Now you should have got a `BUILD SUCCESSFUL` message, if you got `BUILD FAILED` message with Could not get jupyter data-dir as the reason then [click here](https://github.com/SpencerPark/IJava/issues/89) for the solution.


Now to checkout whether everything is working do the following:
```
jupyter kernelspec list
```
you should see java listed in the list, if it is missing you have made some mistake please redo the steps and you should see java listed over there.


Now you have a jupyter notebook kernel that can handle java code.

Want to know more about IJava ? [click here](https://github.com/SpencerPark/IJava#install-pre-built-binary)



# Topics to be covered

Java Overview: 
Java virtual machine, data types, operators, control statements, Introduction to Java programming.

Classes fundamentals, objects, methods, constructors, parameter passing, overloading, access control keywords.

Inheritance basics, method overriding, abstract classes, interface. Defining and importing packages. Exception handling fundamentals,multiple catch and nested try statements.

