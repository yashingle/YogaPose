# Yoga Poses Images Extraction Automation
This project uses UiPath RPA client to automate the extraction of the Yoga poses images from the web in the following manner:

- Reading the name of an Asana from csv file.
- Creating the folder of that Asana name in a common folder.
- Searching for the Asana pose on the web.
- Downloading the image of the pose.
- Transfering that image to the corresponding folder created before.
- Exiting the web browser.

More than one image can be extracted by this automation by changing the selectors after each run.

These extracted images can be used as training data for Yoga Pose estimation model created by Neural Networks and Deep learning.
