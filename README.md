# TextExtractionToExcel
## Its a Simple Project where our task is to extract text and symbols from a given set of images and transfer the arranged data to csv file.
## With the help of pytesseract I could do this.
## Below is the step by stpe explaination
### 1st I installed tesseract and then imported pytessearct library and then I passed every images through.
### All the text present in the images got extracted in string form and then I arranged the string properly and then using simple for loop I got the columns
### For Symbols I used template matching algorithm which helped in the getting the similarity score after which I used the cosine distance to find the relation between the symbols
## Link to CSV File
https://docs.google.com/spreadsheets/d/1FsFHWiz_pbAVEaDzalrPC-xLccGeYHY1g-S8gX96nb0/edit?usp=sharing
