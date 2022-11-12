# Automated Medical Laboratory Test Analysis using Image Processing

## Welcome

In today’s world due to accretion of contagious diseases, analyzing and providing insights on laboratory experiments are tedious and require a large amount of time.<br>
A great amount of experience and knowledge in their appropriate fields is required to provide insights and provide medications accordingly. In recent days due to wrong medical diagnosis, wrong medications have been provided to the patients. In addition to the monetary cost, patients experience psychological and physical pain and suffering as a result of medication errors. Finally, a major consequence of medication errors is that it leads to decreased patients satisfaction and a growing lack of trust in the healthcare system.
<br>The most common reasons for errors include failure to communicate drug orders, illegible handwriting, wrong drug selection chosen from a drop-down menu, confusion over similarly named drugs, confusion over similar packaging between products, or errors involving dosing units or weight. Medication errors may be due to human errors, but it often results from a flawed system with inadequate backup to detect mistakes.
<br>This tool helps businesses in the healthcare sector automate processes for diagnostic testing & ensure the regulatory compliance of lab equipment, lets users store all information in a unified repository for future reference. Hence to avoid such problems, this tool is being developed with the motive to provide correct diagnosis with high accuracy.

## Features

- User Dashboard
- Automatic Report Generation
- Supporting Diseases - Glaucoma, Diabetes, Alzheimers
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
