# 🌻🌼 Flowers Recognition

> Data set Link : https://www.kaggle.com/alxmamaev/flowers-recognition
![Capture](https://user-images.githubusercontent.com/63875409/104835069-01b1ce00-58ca-11eb-89be-6fb637dc616f.PNG)

### Steps to run in your On Google Collab :
* Download the dataset from : https://www.kaggle.com/alxmamaev/flowers-recognition/discussion
* Save the zip file to your google drive .
* Open google collab notebook and mount the google drive to your collab notebook.
* Use `!unzip "SOURCE FOLDER WITH THE NAME OF ZIPPED FILE" -d "DESTINATION FOLDER"` to unzip file and saving it to drive .
* Then you will get a 'flowers' folder with 6 sub folders => 'daisy', 'dandelion', 'flowers', 'rose', 'sunflower', 'tulip' .
* As our dataset consist of 5 classes ,but here we may have an extra 'flowers' subfolder as a bug so we need to remove it .
* Use :
  
  `import shutil`
  
  `data_dir = 'FOLDER PATH'`
  
  `shutil.rmtree(data_dir + '/flowers')`
  
* Then you are good to go :)

### Note :
`flowers-resnet34.pth` and `flowers-resnet9.pth` are not included here as it exceeds the size limit, so you need to retrain the model to generate those files, the training will not take much time and change the path to save the file accordingly .
