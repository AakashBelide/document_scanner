# document_scanner
Document scanner created using OpenCV in Python.

The images provided are sample images. You can add images of the document which you want to scan in the folder where you place the Python files.
You can rename the pathImage variable in the Python file accordingly.

Make and empty folder with the name "Scanned". After the document is scanned properly, you can click "s", the document will be saved in the Scanned folder created.

# Procedure:
• RESIZE IMAGE

• CREATE A BLANK IMAGE FOR TESTING

• CONVERT IMAGE TO GRAY SCALE

• ADD GAUSSIAN BLUR

• GET TRACK BAR VALUES FOR THRESHOLDS (You can control them to get select proper edges of document)

• APPLY CANNY BLUR

• APPLY DILATION

• APPLY EROSION

• FIND AND DRAW ALL DETECTED CONTOURS

• FIND AND DRAW THE BIGGEST CONTOUR AMONG ALL THE CONTOURS

• PREPARE POINTS FOR WARP

• REMOVE 20 PIXELS FORM EACH SIDE (You can change it if you want) - to remove unwanted edges if the documents edges are folded, etc.

• APPLY ADAPTIVE THRESHOLD

• DISPLAYING VARIOUS STEPS OF SCANNING

• SAVING THE IMAGE
