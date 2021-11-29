# Table_Detection_Structure_Recogntion
IT416 - Computer Vision Course Project
Done by - 
<br />
1.Udbhav Bisarya (181IT150)<br />
2.Vishwas Parekh (181IT252)

<br />
The dataset used is the ICDAR 2019 dataset. The TrackA and TrackB datasets can be found on the official site. The link for the dataset is given here:-  https://cndplab-founder.github.io/cTDaR2019/

## Steps to Run code
Let us consider the Track A dataset, a similar process must be emplyed for the TrackB dataset
<br />
1.The dataset must be organized into an images folder and an annotations folder. The images folder should contain all the jpeg files and the annotations folder should contain all the xml files<br />
2. This should now be upladed to google drive to allow it to be run on colab<br />
3. Once done, run the colab notebook and mount your drive to colab<br />
4. Now, change the img_dir_path variable in the ground_truth_to_COCO function and xml_files variable to the images and annotations files respectively<br />
5. Update the json_file variable to the desired output json file location<br />
6. Change accordingly in the load_data function which can be seen below<br />
7. Model is now ready!<br />
