# Face_reco
The directory Original contains the function format of face recognition code(face.py) which is called in call.py. loc.txt is the real time location of a person in terms of pixels in camera. In this only one image of a person is sed to create encodings of a person.
The code call.py in th directory Himanshu is the same version of the code in Original, just difference is the code for face encoding (encodings.py) and face recognition (frame.py) is seperated. The function call.py here calls both the functions together. Whereas save_en.py is used to call encoding.py and reco.py is used to call frame.py.
The code is implemented for images saved in images directory. In this directory you can save multiple images of a person to get better results in the format as saved in the directory.
So in simple three steps-
1. Save the images you want to be recognised in images directory.
2. Run the code save_en.py and then
3. Run the code reco.py.
