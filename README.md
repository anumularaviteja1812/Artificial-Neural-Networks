# Project- Artificial Neural Networks


## Dataset

The datasets you will be working with is available at: https://drive.google.com/drive/folders/1SskWLR1WAjTkfYSGjesz0xbNnki-Z0uY?usp=sharing

### Note:
Made different training and testing files for question1 and question2,3 since I used different kernels for the questions.
1. training_q1 - uses Tensorflow-2.7.0
2. training_q2_q3 - uses own kernel from art.yml
3. test_q1 - uses own kernel from art.yml
4. test_q2_q3 - uses own kernel from art.yml
   
### Files for submission
1. training_q1 (2).ipynb - training file for question 1
2. training_q2_q3 (1).ipynb - training file for question 2 and 3
3. test_q1 (1).ipynb - test file for question 1
4. test_q2_q3 (1).ipynb - test file for question 2 and 3
5. training_q1.pdf - pdf file for question 1
6. training_q2_q3.pdf -  pdf file for question 2 and 3
7. test_q1.pdf - test pdf file for question 1
8. test_q2_q3.pdf - test pdf file for question 2 and 3
9. learning-curves.png -  learning curves obtained from question2
10. project 3_report.pdf - project report
11. makesense files.zip -  zip folder containing images and labels folder
12. art.yml - environment file for training_q2_q3 (1).ipynb, test_q1 (1).ipynb, test_q2_q3 (1).ipynb

### gdrive for models
https://drive.google.com/drive/folders/1ROHkTFYqxk0YPZgeSOuPCOSyB_kTT2DI?usp=sharing
1. best_model.keras - best_model file for question1
2. runs- folder contains the best model for question 2 (use the entire folder as the path for loading model in test file is the same).

### Instructions to run training_q1 file:
1. Use Tensorflow-2.7.0 as kernel for the code.
2. Upload the folder 'flower_species_classification' in the same directory as ipynb file.
3. Run the code on the above mentioned kernel and generate best_model.keras.
   
### Instructions to run training_q2_q3 file:
1. Use kernel obtained from art.yml file for running the ipynb file.
2. Upload the 'car_detection_dataset' in the same directory as ipynb file.
3. Run the code for question2 on 'art' kernel created.
4. To run code for question3, Download makesense files.zip from files uploaded and unzip it, Upload the folders 'Makes sense' and 'Makes sense labels' from main folder into the the curent directory separately.
5. Download the 'runs' folder from Gdrive and upload it to current directory to run the code on saved model.

### Instructions to run test_q1 file:
1. Use kernel obtained from art.yml file
2. Download the 'best_model.keras' from Gdrive and upload it to current directory.
3. Upload the folder 'flower_species_classification' in the same directory as ipynb file
4. Load the .keras file and run the code on art kernel

### Instructions to run test_q2_q3 file:
1. Use kernel obtained from art.yml file
2. Upload the 'car_detection_dataset' in the same directory as ipynb file.
3. Download the 'runs' folder from Gdrive and upload it to current directory to run the code on saved model.
4. Run the code for question2 on 'art' kernel created.
5. To run code for question3, Download makesense files.zip from files uploaded and unzip it, Upload the folders 'Makes sense' and 'Makes sense labels' from main folder into the the curent directory separately.
6. Repeat steps 2 and 3 for running question3 as well.
7. Run the code for question3 on 'art' kernel created.
