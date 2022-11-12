# Automated Medical Laboratory Test Analysis using Image Processing

## Welcome

In today’s world due to accretion of contagious diseases, analyzing and providing insights on laboratory experiments are tedious and require a large amount of time.<br>
The most common reasons for errors include failure to communicate drug orders, illegible handwriting, wrong drug selection chosen from a drop-down menu, confusion over similarly named drugs, confusion over similar packaging between products, or errors involving dosing units or weight. Medication errors may be due to human errors, but it often results from a flawed system with inadequate backup to detect mistakes.
<br>This tool helps businesses in the healthcare sector automate processes for diagnostic testing & ensure the regulatory compliance of lab equipment, lets users store all information in a unified repository for future reference. Hence to avoid such problems, this tool is being developed with the motive to provide correct diagnosis with high accuracy.

## Features

- User Dashboard
- Automatic Report Generation
- Supporting Diseases - Glaucoma, Diabetes, Alzheimers
<hr>

## Future Scope

Adding additional features such as providing tools for editing and viewing the X-Ray images.
Extension of the application to mobile platform

<hr>

## Social Impact

Many government medical facilities, especially in the rural parts of the country, do not have the facility or resources to classify X-Rays of diseases. It could take a lot of time when done manually and also there is the chance of human error. Implementing our XRC model could help save a lot of time and also reduce the error margin significantly. Especially wrt to diabetes, The prevalence in urban areas ranges between 10.9% and 14.2% and prevalence in rural India was 3.0-7.8% among population aged 20 years and above with a much higher prevalence among individuals aged over 50 years. By using our model, the pre diagnosis stage can be completed quicker and that results in more people who can go ahead for their treatment earlier.

<hr>

## Built With

- [Bootstrap](https://getbootstrap.com)
- [Flask](https://flask.palletsprojects.com/en/2.0.x/)
- [OpenCV](https://docs.opencv.org/4.5.2/d6/d00/tutorial_py_root.html)

```sh
├── reports
├── screenshots
├── README.md
├── app.py
├── config.py
├── requirements.txt
├── static
│   ├── css
│   ├── font
│   ├── ico
│   ├── img
│   └── js
└── templates
    ├── errors
    │   ├── 404.html
    │   └── 500.html
    └── pages
        ├── home.html
        └── user.html
```

### Screenshots
<img src="https://github.com/sinking8/Automated-Medical-Laboratory-Test-Analysis-using-Image-Processing/blob/main/screenshots/2.PNG"/>
<img src="https://github.com/sinking8/Automated-Medical-Laboratory-Test-Analysis-using-Image-Processing/blob/main/screenshots/1.PNG"/>
<img src="https://github.com/sinking8/Automated-Medical-Laboratory-Test-Analysis-using-Image-Processing/blob/main/screenshots/3.PNG"/>
<br/>

### Quick Start

1. Clone the repo

```
$ git clone https://github.com/sinking8/Automated-Medical-Laboratory-Test-Analysis-using-Image-Processing.git
$ cd Automated-Medical-Laboratory-Test-Analysis-using-Image-Processing
```

2. Initialize and activate a virtualenv:

```
$ virtualenv --no-site-packages env
$ source env/bin/activate
```

3. Install the dependencies:

```
$ pip install -r requirements.txt
```

5. Run the development server:

```
$ python app.py
```

6. Navigate to [http://localhost:5000](http://localhost:5000)
