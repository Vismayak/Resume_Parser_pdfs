# Resume Parser

The Resume parser was created in order to aid recruiters parse through large number of resumes in order to find those which have the required skills. This is not a complete tool but an aid to help shortlist resumes. 

The single notebook allows the data to focus in one resume while the multiple resume parser extracts from a folder, which has to be provided.
# Packages required 

```bash
pip3 install pdfminer
pip3 install spacy
pip3 install nltk
pip3 install pandas

```

# Credits

I was largely inspired by the methods and techniques used by Omkar Pathak for more details -
https://omkarpathak.in/2018/12/18/writing-your-own-resume-parser/

# Notes for those who use it or want to emulate the project

From the notebook, you can see how much harder it is to extract data from PDF rather than words and the accuracy of extraction is also much lower. I think this is a possible place of improvement

For better classification increase the number of skills in the skills.csv file under the appropriate headers 