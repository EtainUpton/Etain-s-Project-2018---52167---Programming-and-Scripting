# Etain-s-Project-2018---52167---Programming-and-Scripting
Etain’s Project 2018 - 52167 - Programming and Scripting

# Research on the subject of Fisher’s Iris data set
This project is based on Fisher’s Iris data set. In this document I intend to lay out a summary of my findings based on my research on background information about this topic.
According to [Wikipedia](https://en.wikipedia.org/wiki/Iris_flower_data_set) the data set is composed of 50 samples from 3 species of Iris, which is a flower. 

![Image of an Iris Flower](https://upload.wikimedia.org/wikipedia/commons/4/49/Iris_germanica_%28Purple_bearded_Iris%29%2C_Wakehurst_Place%2C_UK_-_Diliff.jpg)

Four features of the flower were measured on each sample - the length and the width of the sepals and petals, which were measured in centimetres. 
Based on the combination of these four features, Ronald Fisher (a British statistician and biologist) developed a linear discriminant model to identify and distinguish the species from each other.

![Image of Robert Fischer](https://upload.wikimedia.org/wikipedia/commons/4/46/R._A._Fischer.jpg)

As per Wikipedia, the dataset contains a set of 150 records under 5 attributes;
1.	Petal Length, 
2.	Petal Width, 
3.	Sepal Length, 
4.	Sepal Width and 
5.	Class.

According to [‘Case Study: IRIS Classification’](http://rstudio-pubs-static.s3.amazonaws.com/269829_8285925c922e445097f47925b112841f.html) the data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). 
Four features were measured from each sample: the length and the width of the sepals and petals, in centimetres. The fifth column is the species of the flower observed. 

Although familiar with what a petal was, I was unsure what exactly a sepal was, so I conducted some research into this. A sepal is a leaf-shaped structure found in flowering plants. It is found on the outermost part of the flower, and like a petal, a sepal is considered to be a modified leaf. ([Biology Dictionary](https://biologydictionary.net/sepal/)). 

Fisher’s Iris data set proved significant, as it became a typical test case for many statistical classification techniques in machine learning (https://en.wikipedia.org/wiki/Iris_flower_data_set). It is a very famous and widely used dataset by everyone trying to learn machine learning and statistics ([‘Case Study: IRIS Classification’](http://rstudio-pubs-static.s3.amazonaws.com/269829_8285925c922e445097f47925b112841f.html)).

Machine learning is a field of computer science which uses statistical techniques to give computer systems the ability to ‘learn’ with data, without being explicitly programmed ([Wikipedia – Machine Learning](https://en.wikipedia.org/wiki/Machine_learning)).

Fisher’s Iris data set itself is as follows;

5.1	3.5	1.4	0.2	Iris-setosa

4.9	3	1.4	0.2	Iris-setosa

4.7	3.2	1.3	0.2	Iris-setosa

4.6	3.1	1.5	0.2	Iris-setosa

5	3.6	1.4	0.2	Iris-setosa

5.4	3.9	1.7	0.4	Iris-setosa

4.6	3.4	1.4	0.3	Iris-setosa

5	3.4	1.5	0.2	Iris-setosa

4.4	2.9	1.4	0.2	Iris-setosa

4.9	3.1	1.5	0.1	Iris-setosa

5.4	3.7	1.5	0.2	Iris-setosa

4.8	3.4	1.6	0.2	Iris-setosa

4.8	3	1.4	0.1	Iris-setosa

4.3	3	1.1	0.1	Iris-setosa

5.8	4	1.2	0.2	Iris-setosa

5.7	4.4	1.5	0.4	Iris-setosa

5.4	3.9	1.3	0.4	Iris-setosa

5.1	3.5	1.4	0.3	Iris-setosa

5.7	3.8	1.7	0.3	Iris-setosa

5.1	3.8	1.5	0.3	Iris-setosa

5.4	3.4	1.7	0.2	Iris-setosa

5.1	3.7	1.5	0.4	Iris-setosa

4.6	3.6	1	0.2	Iris-setosa

5.1	3.3	1.7	0.5	Iris-setosa

4.8	3.4	1.9	0.2	Iris-setosa

5	3	1.6	0.2	Iris-setosa

5	3.4	1.6	0.4	Iris-setosa

5.2	3.5	1.5	0.2	Iris-setosa

5.2	3.4	1.4	0.2	Iris-setosa

4.7	3.2	1.6	0.2	Iris-setosa

4.8	3.1	1.6	0.2	Iris-setosa

5.4	3.4	1.5	0.4	Iris-setosa

5.2	4.1	1.5	0.1	Iris-setosa

5.5	4.2	1.4	0.2	Iris-setosa

4.9	3.1	1.5	0.1	Iris-setosa

5	3.2	1.2	0.2	Iris-setosa

5.5	3.5	1.3	0.2	Iris-setosa

4.9	3.1	1.5	0.1	Iris-setosa

4.4	3	1.3	0.2	Iris-setosa

5.1	3.4	1.5	0.2	Iris-setosa

5	3.5	1.3	0.3	Iris-setosa

4.5	2.3	1.3	0.3	Iris-setosa

4.4	3.2	1.3	0.2	Iris-setosa

5	3.5	1.6	0.6	Iris-setosa

5.1	3.8	1.9	0.4	Iris-setosa

4.8	3	1.4	0.3	Iris-setosa

5.1	3.8	1.6	0.2	Iris-setosa

4.6	3.2	1.4	0.2	Iris-setosa

5.3	3.7	1.5	0.2	Iris-setosa

5	3.3	1.4	0.2	Iris-setosa

7	3.2	4.7	1.4	Iris-versicolor

6.4	3.2	4.5	1.5	Iris-versicolor

6.9	3.1	4.9	1.5	Iris-versicolor

5.5	2.3	4	1.3	Iris-versicolor

6.5	2.8	4.6	1.5	Iris-versicolor

5.7	2.8	4.5	1.3	Iris-versicolor

6.3	3.3	4.7	1.6	Iris-versicolor

4.9	2.4	3.3	1	Iris-versicolor

6.6	2.9	4.6	1.3	Iris-versicolor

5.2	2.7	3.9	1.4	Iris-versicolor

5	2	3.5	1	Iris-versicolor

5.9	3	4.2	1.5	Iris-versicolor

6	2.2	4	1	Iris-versicolor

6.1	2.9	4.7	1.4	Iris-versicolor

5.6	2.9	3.6	1.3	Iris-versicolor

6.7	3.1	4.4	1.4	Iris-versicolor

5.6	3	4.5	1.5	Iris-versicolor

5.8	2.7	4.1	1	Iris-versicolor

6.2	2.2	4.5	1.5	Iris-versicolor

5.6	2.5	3.9	1.1	Iris-versicolor

5.9	3.2	4.8	1.8	Iris-versicolor

6.1	2.8	4	1.3	Iris-versicolor

6.3	2.5	4.9	1.5	Iris-versicolor

6.1	2.8	4.7	1.2	Iris-versicolor

6.4	2.9	4.3	1.3	Iris-versicolor

6.6	3	4.4	1.4	Iris-versicolor

6.8	2.8	4.8	1.4	Iris-versicolor

6.7	3	5	1.7	Iris-versicolor

6	2.9	4.5	1.5	Iris-versicolor

5.7	2.6	3.5	1	Iris-versicolor

5.5	2.4	3.8	1.1	Iris-versicolor

5.5	2.4	3.7	1	Iris-versicolor

5.8	2.7	3.9	1.2	Iris-versicolor

6	2.7	5.1	1.6	Iris-versicolor

5.4	3	4.5	1.5	Iris-versicolor

6	3.4	4.5	1.6	Iris-versicolor

6.7	3.1	4.7	1.5	Iris-versicolor

6.3	2.3	4.4	1.3	Iris-versicolor

5.6	3	4.1	1.3	Iris-versicolor

5.5	2.5	4	1.3	Iris-versicolor

5.5	2.6	4.4	1.2	Iris-versicolor

6.1	3	4.6	1.4	Iris-versicolor

5.8	2.6	4	1.2	Iris-versicolor

5	2.3	3.3	1	Iris-versicolor

5.6	2.7	4.2	1.3	Iris-versicolor

5.7	3	4.2	1.2	Iris-versicolor

5.7	2.9	4.2	1.3	Iris-versicolor

6.2	2.9	4.3	1.3	Iris-versicolor

5.1	2.5	3	1.1	Iris-versicolor

5.7	2.8	4.1	1.3	Iris-versicolor

6.3	3.3	6	2.5	Iris-virginica

5.8	2.7	5.1	1.9	Iris-virginica

7.1	3	5.9	2.1	Iris-virginica

6.3	2.9	5.6	1.8	Iris-virginica

6.5	3	5.8	2.2	Iris-virginica

7.6	3	6.6	2.1	Iris-virginica

4.9	2.5	4.5	1.7	Iris-virginica

7.3	2.9	6.3	1.8	Iris-virginica

6.7	2.5	5.8	1.8	Iris-virginica

7.2	3.6	6.1	2.5	Iris-virginica

6.5	3.2	5.1	2	Iris-virginica

6.4	2.7	5.3	1.9	Iris-virginica

6.8	3	5.5	2.1	Iris-virginica

5.7	2.5	5	2	Iris-virginica

5.8	2.8	5.1	2.4	Iris-virginica

6.4	3.2	5.3	2.3	Iris-virginica

6.5	3	5.5	1.8	Iris-virginica

7.7	3.8	6.7	2.2	Iris-virginica

7.7	2.6	6.9	2.3	Iris-virginica

6	2.2	5	1.5	Iris-virginica

6.9	3.2	5.7	2.3	Iris-virginica

5.6	2.8	4.9	2	Iris-virginica

7.7	2.8	6.7	2	Iris-virginica

6.3	2.7	4.9	1.8	Iris-virginica

6.7	3.3	5.7	2.1	Iris-virginica

7.2	3.2	6	1.8	Iris-virginica

6.2	2.8	4.8	1.8	Iris-virginica

6.1	3	4.9	1.8	Iris-virginica

6.4	2.8	5.6	2.1	Iris-virginica

7.2	3	5.8	1.6	Iris-virginica

7.4	2.8	6.1	1.9	Iris-virginica

7.9	3.8	6.4	2	Iris-virginica

6.4	2.8	5.6	2.2	Iris-virginica

6.3	2.8	5.1	1.5	Iris-virginica

6.1	2.6	5.6	1.4	Iris-virginica

7.7	3	6.1	2.3	Iris-virginica

6.3	3.4	5.6	2.4	Iris-virginica

6.4	3.1	5.5	1.8	Iris-virginica

6	3	4.8	1.8	Iris-virginica

6.9	3.1	5.4	2.1	Iris-virginica

6.7	3.1	5.6	2.4	Iris-virginica

6.9	3.1	5.1	2.3	Iris-virginica

5.8	2.7	5.1	1.9	Iris-virginica

6.8	3.2	5.9	2.3	Iris-virginica

6.7	3.3	5.7	2.5	Iris-virginica

6.7	3	5.2	2.3	Iris-virginica

6.3	2.5	5	1.9	Iris-virginica

6.5	3	5.2	2	Iris-virginica

6.2	3.4	5.4	2.3	Iris-virginica

5.9	3	5.1	1.8	Iris-virginica

It was my intention to assess the results in Python, and then investigate how to display this information in a more visually appealing way to an audience. 

I used ___________to complete this graph. This may be more digestible to an audience who is unfamiliar with Python, and I personally think it simplifies the information.

I watched the ‘Project 2018 overview’ video supplied on Moodle by Dr Ian McLoughlin which gave me some good pointers and a starting point for this project.

Explain to the reader of the project how Data Analytics can be useful in this regard, and how Python is a good tool for this purpose. (Sell Python to them).

Discuss the route other researchers have taken when investigating this dataset and my own opinions on this.

I researched how to correctly upload information to a README as I want to submit my research and findings in text format.

I realised while watching the ‘READMEs’ video supplied by Dr Ian McLoughlin on Moodle that I had forgotten to include a gitignore in my repository for this project. However, I had already submitted the Project URL via Moodle, so I could not amend this.

I realised while researching READMEs for this project that I had incorrectly submitted my previous repositories while completing the weekly exercises – I know for one README I inserted a Microsoft Word Document.

While researching READMEs I wondered how I would upload an image (e.g. a chart) to GitHub.
I learned this from https://guides.github.com/features/mastering-markdown/ and have included some in this README.
I also learned that it is possible to hyperlink [Python]( https://www.python.org/).

When we download Fischer’s Iris Data Set from http://archive.ics.uci.edu/ml/datasets/Iris originally, the data set looks like this;

## Visual Studio Code

I used [Visual Studio Code](https://code.visualstudio.com/) to run Python. Prior to commencing this module I had never heard of Visual Studio Code, so I conducted some research on it. According to [Wikipedia]( https://en.wikipedia.org/wiki/Visual_Studio_Code); Visual Studio Code is a source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring. It is also customizable, so users can change the editor's theme, keyboard shortcuts, and preferences. It is free and open-source, although the official download is under a proprietary license.

# List of References;
*	Wikipedia - (https://en.wikipedia.org/wiki/Iris_flower_data_set)
*	Biology Dictionary (https://biologydictionary.net/sepal/)
* Case Study: IRIS Classification (http://rstudio-pubs-static.s3.amazonaws.com/269829_8285925c922e445097f47925b112841f.html)
*	UC Irvine Machine Learning Repository. Iris data set. (http://archive.ics.uci.edu/ml/datasets/Iris)
* Wikipedia README page (https://en.wikipedia.org/wiki/README)
*	Markdown Cheatsheet (https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
*	Markdown Wikipedia (https://en.wikipedia.org/wiki/Markdown)
*	Mastering Markdown (https://guides.github.com/features/mastering-markdown/)
*	Python Website (https://www.python.org/)
*	The Old Farmer’s Almanac https://www.almanac.com/plant/irises
*	The Python Tutorial https://docs.python.org/3/tutorial/
