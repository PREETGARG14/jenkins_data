pipeline { agent any stages { stage("Compile") { steps { //pip install requirements.txt echo "Python compile done" } } stage("Unit test") { steps { sh "python <your_test_script>.py" } } } } 
