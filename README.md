1- Download STNet preprocessed test dataset of FE240hz and put it in the main folrder -> https://drive.google.com/drive/folders/1pNY8kahrof9l9zCw7TtXY4RhvJ4GGx37 

2- Download the pretrained model and put it into main/snapshots/stnet. -> https://drive.google.com/file/d/1xD-d24TRoMHRAQKIxE7CxMhI2UffSiUG/view 

3- Change dataset path at line 32 in main/videoanalyst/engine/tester/tester_impl/eventdata.py. data_root="/your_data_path/img_120_split"

to run the code you can find inside the main folder a file called main you can run it 

- The predicted bounding box format: An N×4 matrix with each line representing object location [xmin, ymin, width, height] in one event frame.

https://github.com/Jee-King/CVPR2022_STNet#citation 
