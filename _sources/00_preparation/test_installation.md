# Testing the installation

After setting up the installation and configuring the OpenAI API key, start up Jupyter Lab and create a new Notebook:

![](test_bob1.png)

Execute this code to test if the installation worked:

```
from bia_bob import bob
```

```
%%bob
What's the mission of ScaDS.AI's living lab?
```

It should come up with results such as these:

![](test_bob2.png)
