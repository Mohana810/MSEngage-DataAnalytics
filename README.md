# MSEngage-DataAnalytics
Microsoft Intern Engage 2022, Track -II Data Analysis Project Submission
# Data On Wheels

Got doubts on trends? Want to know whatβs wrong and whatβs right? You are at the right place! There are several visualizations made for you after a through analysis and accurate data. Just visualize and decide. Donβt be data driven, be analytics driven!

### LanguagesβπΌ

<img src="https://img.icons8.com/color/35/000000/python--v1.png"/> <img src="https://cdn-images-1.medium.com/max/1200/1*4R9HdZXaBGLPD_xPoit7iA.png" width="35px" height="35px"/> <img src="https://img.icons8.com/color/35/000000/html-5--v1.png"/> <img src="https://img.icons8.com/color/35/000000/css3.png"/>  <img src="https://img.icons8.com/color/35/000000/bootstrap.png"/> 

### DevOps & Cloud ToolsβοΈ

<img src="https://img.icons8.com/color/35/000000/elasticsearch.png"/> <img src="https://img.icons8.com/external-tal-revivo-color-tal-revivo/35/000000/external-kibana-is-an-open-source-data-visualization-plugin-for-elasticsearch-logo-color-tal-revivo.png"/> <img src="https://img.icons8.com/color/35/000000/pycharm.png"/> <img src="https://img.icons8.com/color/35/000000/tableau-software.png"/> <img src="https://img.icons8.com/color/35/000000/figma--v2.png"/> <img src="https://img.icons8.com/color/35/000000/git.png"/> <img src="https://img.icons8.com/color/35/000000/github.png"/>

## Project code structure
  <details>
    <summary>Click to view project structure</summary>
        π DataProjectMSFT/ <br>
        ββπ app.py <br>
        ββπ assets/ <br>
        β ββπ bg2.jpg <br>
        β ββπ dashbrd.css <br>
        β ββπ dropIcon.jpg <br>
        β ββπ fullL.jpg <br>
        β ββπ home.css <br>
        β ββπ iconDrop.jpg <br>
        β ββπ jumboBg.png <br>
        β ββπ logo.jpg <br>
        β ββπ sidebarStyle.css <br>
        ββπ datasets/ <br>
        β ββπ cars_enagage_2022_simpleData.csv <br>
        β ββπ createVizTest.xlsx <br>
        β ββπ EngageData.xlsx <br>
        ββπ main.py <br>
        ββπ pages/ <br>
        β ββπ createViz.py <br>
        β ββπ dashboard.py <br>
        β ββπ findCar.py <br>
        β ββπ home.py <br>
        β ββπ sidebar.py <br>
        β ββπ _init_.py <br>
        β ββπ _pycache_/ <br>
        β   ββπ createViz.cpython-37.pyc <br>
        β   ββπ dashboard.cpython-37.pyc <br>
        β   ββπ findCar.cpython-37.pyc <br>
        β   ββπ home.cpython-37.pyc <br>
        β   ββπ sidebar.cpython-37.pyc <br>
        β   ββπ _init_.cpython-37.pyc <br>
        ββπ requirements.txt <br>
        ββπ _pycache_/ <br>
          ββπ app.cpython-37.pyc <br>
  </details>
    

  - **Pages :**
    Includes python files for each page in website
  - **Assets :**
    All the rrequired external style sheets and images of the project
  - **Datasets :**
    Includes the data files(.csv and .excel) used for building tableau dashboards and elasticsearch filters<br>
      - *EngageData.xlsx* - used for creating the 'Dashboard' page.
      - *createVizTest.xlsx* - used for testing the 'Create Viz' feature.
      - *cars_enagage_2022_simpleData.csv* - used for implementing the 'Find your car' feature.
  - **app.py :**
    Initialisation and configuration of the dash app running with Flask server
  - **main.py :**
    Indexing and mapping of all the pages together
    
 ## Quick Start
    
  Before running the project, make sure you have all of the [required packages](https://github.com/Mohana810/MSEngage-DataAnalytics/blob/main/DataProjectMSFT/requirements.txt).

  From there, the easiest way to get the app started is is to open the terminal with project file path and run `python main.py`

  Now, Open your [localhost](http://127.0.0.1:8888/) and check out the website.
  
 ## *Important Instructions
  
  - For viewing the [*elasticsearch dashboard](https://github.com/Mohana810/MSEngage-DataAnalytics/blob/main/DataProjectMSFT/pages/findCar.py), **click on 'Login with Elasticsearch'** <br> 
  <html><img src="https://user-images.githubusercontent.com/79496726/170841683-8645441f-8929-451d-ae1e-5b59e18f572f.png", width="300px", height="400px"></html>
  
  
  - And then use the following **login credentials** <br>
  <details>
    <summary>Click to expand</summary>
    <strong>username:</strong> elastic <br>
    <strong>password:</strong> MxsStYProC58mjehMKuOET0j
  </details><br>
  
  
  - **Note:** *Please ignore* the warning shown in the elasticsearch dashboard '*Error restoring state from URL*'. It is due to null fields in the available data.

  
 ## Future scope
 
  Well, this absolutely is not the end of this amazing web application. It still has a lot of future scope. <br>
  Future features-
  - A live updating dashboard.
  - Advanced Create Viz feature.
  - Auto Generation of summary points based on graphs
