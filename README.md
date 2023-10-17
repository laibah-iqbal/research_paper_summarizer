# Research Paper Summarizer
As a Master's student, sometimes I don't always have the time to complete all my readings especially lengthy research papers that supplement the course material. So, to be able to keep up with them when I'm in a crunch, I used Python packages to parse research paper PDFs, summarize them and output the summary as an audio file so I can listen to research papers with all my other chores.

I used fitz from the pymuPDF package to read in the PDF in xml format. I parsed the XML using the ElementTree package. Summarizing of the text was done use the Natural Language Toolkit and I output the audio as an mp3 file using Google's text to speech API. 
