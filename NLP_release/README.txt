############################################################################################
# This is the code for Natural Language Processing Module of
# "Language-Driven Synthesis of 3D Scenes from Scene Databases"
# Rui Ma, Akshay Gadi Patil, Matthew Fisher, Manyi Li, Sören Pirk,
# Binh-Son Hua, Sai-Kit Yeung, Xin Tong, Leonidas Guibas, Hao Zhang
# ACM Transactions on Graphics (Proc. SIGGRAPH ASIA), 2018
# The code is free for research use. For commerical use, please contact: Matthew Fisher(techmatt@gmail.com)
# Version: 1.0
############################################################################################

Step 0: Required Software
Python2.7
JDK 8
IntelliJ IDEA
Visual studio 2015

Step 1:
1) Setup JDK 8 path in IntelliJ IDEA
2) Run JavaScene/src/nlp/Main.java with IntelliJ to start NLP server at the background

Step 2:
1) In the file matt-SEL-playground/SEL-params.txt, modify the nlpRoot path to the absolute path of the NLP_release folder on your computer 
(note: do not miss the last backslash at the end of the path)

Step3:
1) Enter the sentences you want to parse in the file in.txt. Multiple sentences separated by "." could be used.
2) Open matt-SEL-playground.sln using Visual Studio 2015, compile and run the program. The parsed sentences will be saved in file out.txt.

* If you are using python 3.6 enviroment, place use the file JavaScene\py3.6\processDocument.py to replace the one in the folder JavaScene.
