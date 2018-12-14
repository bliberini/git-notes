# Notes on Git

The following summary of git's commands and structure uses *Mastering Git* as its main source and the cookbook example as use case.

## Use case

The use case used throughout these notes is that of a cookbook. The cookbook is a directory that has the following structure:

```
cookbook
|
|__ menu.txt
|__ recipes/
  |_ recipe1.txt
  |_ recipe2.txt
  ...
  |_ recipeN.txt  
```

The `menu.txt` file contains the names of the dishes in some menu. For each of these dishes, there is a .txt file with the same name under the `recipes/` folder that contains its recipe. 

The **repository rules** for the cookbook are the following:

1. Each item in the menu should appear only once, in a different line
2. Each commit that adds an item to the `menu.txt` file should also add its recipe under the `recipe/` folder