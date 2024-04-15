# playing with AI
Building AI course project
## Summary

Describe briefly in 2-3 sentences what your project is about. About 250 characters is a nice length! 


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

This is how you make a list, if you need one:
* problem 1
* problem 2
* etc.


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Images will make your README look nice!
Once you upload an image to your repository, you can link link to it like this (replace the URL with file path, if you've uploaded an image to Github.)
![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
* 
  JAVA & DATABASE
•	Steps1 : Create a database using SQL/ Microsoft Access 
•	Stept2: Make a ODBC connection, that connect with the database and give a name of the connector. For ODBC connection go to Control Panel --> Administrative Tools  and click on  Data Sources (ODBC) . Click on Add button and then give a name of the connector and connect with the database.
•	Step3: Design a  Form in NetBean under java desktop application with the button Insert, Delete, Update and Search.
Add the given code under Insert button:


 try{
     Connection con;
     Statement stmt;
     ResultSet rs;

    Class.forName("sun.jdbc.odbc.JdbcOdbcDriver");
    con=DriverManager.getConnection("jdbc:odbc:asd");
    stmt=con.createStatement();

  int s1 = Integer.parseInt(jTextField1.getText()) ;
 String s2 = jTextField2.getText() ;

stmt.executeUpdate("Insert into Table1(Id,Name)values("+s1+",'"+s2+"')"); //modify this command if needed. For delete, update and query, you just have to change this command. 

   JOptionPane.showMessageDialog(null,"You have successfully Insert the value.");
          }
catch(SQLException kk)
    {
   System.out.println(kk);
   }
catch(ClassNotFoundException ca)
   {
   System.out.println(ca);
   }
   SIMILAR IMAGE IDENTIFICATION
   Identification of similar images from a photo timeline to enable storage savings.
This solution could be used in a mobile or desktop app giving the user the ability to choose the photos to retain
among a set of similar looking image 
What is the perception of AI? 
Medical Image Learning with Noisy and Limited Data (MILLanD)” held in conjunction with the 26th International Conference on Medical Image Computing and Computer Assisted Intervention (MICCAI 2023)so AI is portrayed Medical Image & depth image Filtering 
Related Titles:=Lecture Notes in Computer Science
Publisher:= Cham: Springer

Medical Image Learning with Limited and Noisy Data: Second International Workshop, MILLanD 2023, Held in Conjunction with MICCAI 2023, Vancouver, BC, Canada, October 8, 2023, Proceedings

But sometimes using TOOLS is  image location finder using AI is not possible ?
 because uploaded a photo from  Stockholm Sweden. in this tools https://picarta.ai/ but it shows Micro, United States, , so no exact  data involved , so accurate representation of image location not visible 
so its my general impression to get about AI from the image search 


Implications of AI
real-life examples on using AI to help homeless youth, diabetes patients, and other social welfare interventions. so it was one of the vital implication of AI  , so we use social service technological innovation using artificial intelligence 
Title Artificial Intelligence and Social Work
Authors: Milind Tambe and Eric Rice
https://ebookcentral-proquest-com.db.ub.oru.se/lib/universitetsbiblioteket-ebooks/detail.action?docID=5569639

