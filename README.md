# Frequent-Words-Python-Docker
This code determines the 10 most frequent words in a text file using Python in Docker Framework.</br>

To execute this code, install docker platform on your system and follow the steps given below - </br>
i) Download and save the given files in a common directory.</br>
ii) Execute data.py in Node1 and data1.py in Node2 using the following command - </br>
    python data.py and python data1.py</br>
iii) Copy the text files generated into the CNode directory.</br>
iv) Start docker and type the following commands in the terminal to build and run the container</br>
    docker build -t output</br>
    docker run -p 4000:80 output</br>
v) Go to the browser and type localhost:4000 to obtain the final result.</br>
