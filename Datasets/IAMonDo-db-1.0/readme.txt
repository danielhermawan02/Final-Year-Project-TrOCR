Description
The dataset contains 941 online handwritten documents by 189 writers. The documents consists of text blocks, lists, tables, formulas, diagrams and drawings. Such pieces of content have been placed in arbitrary positions on each document.

In the acquisition phase, the writers have been asked to copy the content of a template to a sheet of paper (A4). The writing was recorded online by a digital pen. A total of 1000 templates are composed of text coming from the Brown corpus and of drawings, diagrams, and formulas provided by Wikimedia Commons and Wikipedia, respectively. Thereby a total of 200 different diagrams, 200 different drawings and 200 different formulas are used. The text for the text blocks, lists, and tables has been selected randomly from 11 categories of the Brown corpus.

After a document has been written, the writer has marked the document with a small set of marking elements including underlining of text, marking of text on one or multiple lines by an angle on the top left as a start mark, and an angle on the bottom right as an end mark, marking of text enclosing it in square brackets, marking of entire text lines by a vertical stroke on the right or left side of the text block, encircling, annotation of these markings by small text labels, and lines connecting these text labels with the markings. Of all documents a subset of 839 contain an average of 10 such marking elements.

Some of the documents have landscape orientation, others have portrait orientation. On some documents, separate text parts have a different orientation.

The dataset contains:

941 documents
68841 words
7616 text lines in text blocks
1478 text blocks
2068 list items
536 lists
2550 table cells
450 tables
5698 labels in diagrams
917 drawings in diagrams
910 diagrams
546 drawing not part of diagrams
489 formulas
355,097 strokes
As file format InkML as defined by W3C in a working draft 2006 is used. Each document is placed in its individual InkML file. The handwriting is recorded by collecting a sample point every 13 to 14 milliseconds along the pen trajectory. Sample points in a straight line have been removed by the recording device. Each sample point is given by its coordinates on the sheet, a timestamp in milliseconds, and a pressure value from 0 to 255. The sample points recorded, beginning from the moment where the pen touches the paper on to the moment when the pen is lifted again, are grouped together to form a stroke, or trace.

The ground truth annotation and the meta data are integrated together with the plain writing information in the InkML file of an individual document.

All the documents together use 126 MB of space on the hard disk.