# Robotics Teaching Kit with 'Jet'

The Robotics Teaching Kit with 'Jet' includes example code, lecture slides, quiz/exam problem sets, labs/solutions, and projects for teaching a full-term curriculum robotics course. The material is organized into modules that cover specific topics. It is logical to teaching in order through the modules, but each module is self-contained so instructors can re-order modules as needed.

The kit is produced jointly by NVIDIA and Cal Poly San Luis Obispo.  All material is available under the [Creative Commons Attribution-NonCommercial License](http://creativecommons.org/licenses/by-nc/4.0/).

## 'Jet' Robot Hardware

**The Jetson TX1 has reached End of Life (EOL) and the 'Jet' Robot Kit has been discountinued by Servocity. You can still purchase the parts separately using the BOMs linked below and use Jetson TX2 instead of TX1 with some modifications to the configuration software.**

* [TX1 ‘Jet’ Robot Kit](https://www.servocity.com/tx1-jet-robot-kit)

The full hardware bill of materials (BOM), including pricing and where to buy now, can be found here:  

* [TX2 ‘Jet’ Robot Kit BOM (TX2)](https://docs.google.com/spreadsheets/d/1jGn7AG5NivTjxPEppJEdIUVxhm5nB17T3ZtRTCYyuQg/edit?usp=sharing)
* [TK1 ‘Jet’ Robot Kit BOM (TK1)](https://docs.google.com/spreadsheets/d/14N_tkfNsItY9CV0vUGHCPpcZ-mqgsZsC87CQEHBXMmY/edit?usp=sharing)
 
The [HardwareTemplates](https://drive.google.com/drive/folders/0B8F3iGtBky5JQUIzR1JTd0xWRzg?usp=sharing) shared directory includes design files that can be used to laser cut the Jet's base mounting plate and sonar holders.  The `JetbotPlate` files are the layout of the base plate in different, common file formats. The `SonarHolders` files are the layout of the sonar holders.

## About the Content

#### Examples

The `/examples` folder includes a variety of demonstrations.  Many of the examples
have been converted into lab assignments; therefore the examples should not be provided
to students because the examples contain solutions to many labs.
You can run an example by following the instructions below:

1. Build and launch the rosjet platform (following the instructions in lab 1).
2. Navigate to the examples folder
3. Enter the command `catkin_make && source devel/setup.sh`
4. Run any of the examples by typing `rosrun [example_name] [example_name]`

#### Docs

The `/docs` folder contains the quizzes, projects and labs for the course.  To create the .pdf and .docx versions
of the documents, you must install [pandoc](http://pandoc.org/installing.html).

**NOTE: We currently recommend using the recently updated files in `/lab1_building_robot` from the latest Robotics-Teaching-Kit-with-Jet.zip static download instead of the files in `/lab1_building_robot` here in the repo (those files here in the repo will be updated soon). All other source files and documents generated from this repo are up to date.**

**NOTE: Although we provide instructions for Pandoc on Windows, it has not yet been extensively tested - Linux is highly recommended**

Then the labs can be built with the command `python make_labs.py` when you are in the
`/docs` directory.  The build folder will then contain the compiled documentation as
well as zipped folders that contain the code and solutions for the labs.

Students should receive both the lab description (.docx or .pdf) and the code.zip folder.
The solution.zip should be kept by the instructor.

## NVIDIA DLI Online Courses and Certification

The NVIDIA Robotics Teaching Kit with 'Jet' includes access to free online DLI courses – **a value of up to $90 per person per course**. 

## About the NVIDIA Deep Learning Institute (DLI)
The NVIDIA Deep Learning Institute (DLI) offers hands-on training for developers, datascientists, and researchers looking to solve challenging problems with deep learning and accelerated computing. Through built-in assessments, students can earn certifications thatprove subject matter competency and can be leveraged for professional career growth.

#### Attend Instructor-led Training
In addition to online, self-paced courses, DLI offers all fundamentals and industry-specific courses as in-person workshops led by DLI-certified instructors. View upcoming workshops near you at [www.nvidia.com/dli](https://www.nvidia.com/dli).

Want to schedule training for your school? Request an onsite workshop at your university at [www.nvidia.com/requestdli](https://www.nvidia.com/requestdli).
