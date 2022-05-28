# MSEngage-DataAnalytics
Microsoft Intern Engage 2022, Track -II Data Analysis Project Submission
# Data On Wheels

Got doubts on trends? Want to know what’s wrong and what’s right? You are at the right place! There are several visualizations made for you after a through analysis and accurate data. Just visualize and decide. Don’t be data driven, be analytics driven!

### Languages✍🏼

<img src="https://img.icons8.com/color/35/000000/python--v1.png"/> <img src="https://cdn-images-1.medium.com/max/1200/1*4R9HdZXaBGLPD_xPoit7iA.png" width="35px" height="35px"/> <img src="https://img.icons8.com/color/35/000000/html-5--v1.png"/> <img src="https://img.icons8.com/color/35/000000/css3.png"/>  <img src="https://img.icons8.com/color/35/000000/bootstrap.png"/> 

### DevOps & Cloud Tools⚒️

<img src="https://img.icons8.com/color/35/000000/elasticsearch.png"/> <img src="https://img.icons8.com/external-tal-revivo-color-tal-revivo/35/000000/external-kibana-is-an-open-source-data-visualization-plugin-for-elasticsearch-logo-color-tal-revivo.png"/> <img src="https://img.icons8.com/color/35/000000/pycharm.png"/> <img src="https://img.icons8.com/color/35/000000/tableau-software.png"/> <img src="https://img.icons8.com/color/35/000000/figma--v2.png"/> <img src="https://img.icons8.com/color/35/000000/git.png"/> <img src="https://img.icons8.com/color/35/000000/github.png"/>

## Project code structure
  <details>
    <summary>Click to view project structure</summary>
        📁 DataProjectMSFT/ <br>
        ├─📄 app.py <br>
        ├─📁 assets/ <br>
        │ ├─📄 bg2.jpg <br>
        │ ├─📄 dashbrd.css <br>
        │ ├─📄 dropIcon.jpg <br>
        │ ├─📄 fullL.jpg <br>
        │ ├─📄 home.css <br>
        │ ├─📄 iconDrop.jpg <br>
        │ ├─📄 jumboBg.png <br>
        │ ├─📄 logo.jpg <br>
        │ └─📄 sidebarStyle.css <br>
        ├─📁 datasets/ <br>
        │ ├─📄 cars_enagage_2022_simpleData.csv <br>
        │ ├─📄 createVizTest.xlsx <br>
        │ └─📄 EngageData.xlsx <br>
        ├─📄 main.py <br>
        ├─📁 pages/ <br>
        │ ├─📄 createViz.py <br>
        │ ├─📄 dashboard.py <br>
        │ ├─📄 findCar.py <br>
        │ ├─📄 home.py <br>
        │ ├─📄 sidebar.py <br>
        │ ├─📄 _init_.py <br>
        │ └─📁 _pycache_/ <br>
        │   ├─📄 createViz.cpython-37.pyc <br>
        │   ├─📄 dashboard.cpython-37.pyc <br>
        │   ├─📄 findCar.cpython-37.pyc <br>
        │   ├─📄 home.cpython-37.pyc <br>
        │   ├─📄 sidebar.cpython-37.pyc <br>
        │   └─📄 _init_.cpython-37.pyc <br>
        ├─📄 requirements.txt <br>
        └─📁 _pycache_/ <br>
          └─📄 app.cpython-37.pyc <br>
  </details>
    

  - *Pages :*
    Includes python files for each page in website
  - *Assets :*
    All the rrequired external style sheets and images of the project
  - *Datasets :*
    Includes the data files(.csv and .excel) used for building tableau dashboards and elasticsearch filters
  - *app.py :*
    Initialisation and configuration of the dash app running with Flask server
  - *main.py :*
    Indexing and mapping of all the pages together
    
 ## Quick Start
    
  Before running the project, make sure you have all of the [required packages](https://github.com/Mohana810/MSEngage-DataAnalytics/blob/main/DataProjectMSFT/requirements.txt).

  From there, the easiest way to get the app started is is to open the terminal with project file path and run `python main.py`

  Now, Open your [localhost](http://127.0.0.1:8888/) and check out the website.
  
 ## *Important Instructions
  
  - For viewing the [*elasticsearch dashboard](https://github.com/Mohana810/MSEngage-DataAnalytics/blob/main/DataProjectMSFT/pages/findCar.py), **click on 'Login with Elasticsearch'** and please use the following **login credentials** <br> 
  <html><img src="https://user-images.githubusercontent.com/79496726/170841683-8645441f-8929-451d-ae1e-5b59e18f572f.png", width="300px", height="400px"></html>

  <details>
    <summary>Click to expand</summary>
    <strong>username:</strong> elastic <br>
    <strong>password:</strong> MxsStYProC58mjehMKuOET0j
  </details>
  
  
  - The warning shown in the elasticsearch dashboard is due to null fields in the available data. (*Please ignore*)
  <html><img src="https://user-images.githubusercontent.com/79496726/170841735-33680dc8-cf81-4b3b-a76d-a9dbd5344d05.png", width="250px", height="200px"></html>
  
 ## Future scope
 
  Well, this absolutely is not the end of this amazing web application. It still has a lot of future scope. <br>
  Future features-
  - Making the dashboard a live updating dashboard.
  - Improving the Create Viz feature.
  - Generating summary points based on graphs
