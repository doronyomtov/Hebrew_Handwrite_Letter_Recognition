# Hebrew_Handwrite_Letter_Recognition
A CNN model that have been trained and tested on hebrew letters
end goal will be to build a model that will be able to "translate" entire handwritten documents (The main problem we have is the lack of labeled data)
so in the next few days ill try different models and choose the one with the highest accuarcy. current (0.82)


Regular CNN Accuarcy (0.82)


Alexnet Accuarcy (0.74)



Current Issues:
-low accuarcy (probably due to small data set (about 200 images per letter)
-segmenting letters from images (in hebrew there are letters that have 2 parts (ק,ה) and letter that is very small (י) making it hard to successfuly identify them and segmenting them 
