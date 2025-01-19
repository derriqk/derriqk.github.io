---
layout: project
type: project
image: img/modelbrain.jpg
title: "Basic Language Model in Java"
date: 2023
published: true
labels:
  - Java
summary: "This uses multiple class files to build a program. This program holds individual words in a hashttable. Each word on the table has its own array of words that follow it and the amount of that word. By using the table and the frequency, it uses Math.random() based on the frequency to generate text. Based on that follow up text, it then uses the words following that one, and so on."
---

<hr>

<pre>

  This purpose of this project was to get an understanding of iteration, hash tables, and sorting, and more. This was done by first 
  initializing a hash table to hold individual words. These words would be read from a text file and stored into the hashtable. As it 
  continues to read word by word, the scanner keeps track of a current word and a following word. The following word would then be 
  stored in the appropriate key and incremented if it was a duplicate. Then, the following word becomes the current word, and the new 
  following word would be the next word. This allows it to create all the necessary words and frequencies in the table until the last 
  word is read. By default, the following word of the last word is a period. 

  This project was a solo project done for my class to demonstrate the material I have learned and so the sole contributor was me.
  From this experience I was able to learn key concepts. For one, hash table and the idea of pseudorandomness to create instant access 
  to keys and their values. By using hashtables, an index could be found instantly and gain the data in constant time, where the only 
  extra time cost would be creating more room in the array by making a new array.
  I was also able to learn about sorting when it came to sorting the frequencies so that they were in order. I also learned about file 
  reading of text files and storing those values into the table. 

  Overall, this project helped me further understand the lessons taught in class becuase afterall, being able to apply knowledge and 
  do hands-on work solidifies the understanding. 

</pre>

<hr>
