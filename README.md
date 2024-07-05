# FaceWise

"FaceWise: Streamlining Attendance with Facial Recognition Technology"

## Overview

FaceWise is a face-based attendance system implemented using Python and OpenCV. It provides a convenient way to automate attendance tracking by recognizing faces in images or live video streams.

## Features

- **Face Detection**: Utilizes OpenCV's face detection algorithms to locate faces within images or video frames.
- **Face Recognition**: Recognizes faces using pre-trained deep learning models to identify individuals accurately.
- **Attendance Logging**: Records attendance automatically by matching recognized faces with a database of registered individuals.
- **User-Friendly Interface**: Simple and intuitive interface for easy interaction.

## Technologies Used

- Python
- OpenCV
- Deep Learning Models for Face Recognition

## Libraries Used

- numpy
- opencv-contrib-python
- opencv-python
- openpyxl
- pandas
- Pillow
- pyttsx3


## Getting Started

### Installation

To install FaceWise, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/ashutosh786palhare/FaceWise.git
    ```

2. Navigate to the project directory:
    ```bash
    cd FaceWise
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
	
### What steps you have to follow??
- Download or clone my Repository to your device
- type `pip install -r requirements.txt` in command prompt(this will install required package for project)
- Create a `TrainingImage` folder in a project folder.
- open `attendance.py` and `automaticAttendance.py`, change all the path accoriding to your system
- Run `attandance.py` file

### Project flow & explaination
- After you run the project you have to register your face so that system can identify you, so click on register new student
- After you click a small window will pop up in that you have to enter you ID and name and then click on `Take Image` button
- After clicking `Take Image` button A camera window will pop up and it will detect your Face and take upto 50 Images(you can change the number of Image it can take) and stored in the folder named `TrainingImage`. more you give the image to system, the better it will perform while recognising the face.
- Then you have to click on `Train Image` button, It will train the model and convert all the Image into numeric format so that computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.
- It will take some time(depends on you system).
- After training model click on `Automatic Attendance` ,you have to enter the subject name and then it can fill attendace by your face using our trained model.
- it will create `.csv` file for every subject you enter and seperate every `.csv` file accoriding the subject
- You can view the attendance after clicking `View Attendance` button. It will show record in tabular format.
   
## ScreenShots
### UI

![Home](https://github.com/ashutosh786palhare/FaceWise/assets/53346137/94726082-86b9-43b0-af84-25ac27806faf)

### Take Image

![Take image](https://github.com/ashutosh786palhare/FaceWise/assets/53346137/113fe53b-4410-486c-85be-371bc39f25e3)

## Filling Attendance

![Filling Attendance](https://github.com/ashutosh786palhare/FaceWise/assets/53346137/a5fd4334-4e26-4439-9a3c-78993d7aad66)


## Contribution Guidelines
If you'd like to contribute or suggest improvements, feel free to open an issue or submit a pull request. Your feedback and contributions are highly appreciated!

Here's how you can contribute to FaceWise:
1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/new-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push to the branch: `git push origin feature/new-feature`.
5. Submit a pull request.

## Contact Information
For any further information, collaborations, or inquiries, feel free to reach out to me:
- Email: ap4all@aol.com
- LinkedIn: [Ashutosh Palhare](https://in.linkedin.com/in/ashutosh786palhare)
- Website: https://ashutosh786palhare.github.io

## Acknowledgments
- Special thanks to the developers of OpenCV for their amazing library.
- Thanks to the Python community for their continuous support and contributions.

## Credit
Modified by: [ME](https://github.com/ashutosh786palhare)

Made by: [This Guy](https://github.com/Patelrahul4884) Big thanks to @Patelrahul4884


## Thank-You
**Thank you for visiting my repository and exploring my Profile!**


   
