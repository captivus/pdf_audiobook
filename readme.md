# Buildilng a PDF to audiobook converter in Python + CoPilot
We're going to run through this iteratively, making improvements as we go.  To start, we'll write a program that will:
1. Convert a number of pages of a PDF file to a text file
1. Convert that text file into an mp3 file using Microsoft Edge's excellent text-to-speech AI service

Incrementally, we'll make improvements to:
1. Ignore headers and other text which we don't want read to us in the audiobook
1. Convert the entire PDF to an audiobook
1. Properly format the text file so that paragraphs aren't broken by newlines
1. Provide indication of progress being made in the audiobook conversion (as this can take a while)

Let's get started!