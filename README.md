# Assignment-3.3
1. Test whether two vectors are exactly equal (element by element).

          vec1 = c(rownames(mtcars[1:15,]))
          vec2 = c(rownames(mtcars[11:25,]))
          identical(vec1, vec2)
2. Sort the character vector in ascending order and descending order.

          vec1 = c(rownames(mtcars[1:15,]))
          vec2 = c(rownames(mtcars[11:25,]))
          sort(vec1)-ascending
          sort(vec2)-ascending
          sort(vec1, decreasing=TRUE)
          sort(vec2, decreasing=TRUE)
          
3.	What is the major difference between str() and paste() show an example.

          Str() –Provides the information of an object.
          Paste()-Concatenates the strings.
          
4. Introduce a separator when concatenating the strings.

        Paste(“My name is”, “Supriya”, sep=”-“)
        Cat(“My name is Surpiya”, “I goto R Analytics class”, sep=”-“)
