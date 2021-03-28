# GeoDataProcessing

GeoDataProcessing is a Python application I designed and developped to meet the needs of a geotechnical PhD student studiying in the university of Lorraine, France. 

The purpose of the application is to significantly speed up experimental data processing, which can be a dull, repetitive task. It is also meant to output customizable, stylish graphs and excel files to highlight your relevant data.

### Requirements

The application can only be run on Windows 10.

### Installation

Go to "Releases" and click on "Source code".

### User guide

Note: For now, the application can only process data measured during pressuremeter tests.

To automatically process your data, you must provide:

- an input file, the path to the excel file holding your data. To know how your data should be stored in your input file, open Test_file.xlsx and respect carefully the format: three worksheets each containing, in this order, the data relative to the tube calibration, the air calibration and finally the data of your pressuremeter test

- a target file, the path to an excel file again. If the path provided already exists, your excel file will be overwritten, else the file is created for you.

Other parameters like the path to the folder in which the graphs are to be saved, the file extension of the graphs  and many others can be modified in the parameters menu but have a default value so it is not required to set those up. All the parameters of your application are stored in the "parameters.txt" file, and any corrupted value would be replaced by a default value (if the file cannot be found, a new one is created with default values).

Once you have set up the application, you can launch the process of your data and see your output graphs as well as your excel file storing all the calculated data!

### Upcoming features for future updates

- triaxial tests data processing

- possibility to really customize your graphs and your output excel file (and save your templates for future processes).

- possibility to directly send requests / report bugs via an in-app menu

- possibility to choose between French and English for text display


