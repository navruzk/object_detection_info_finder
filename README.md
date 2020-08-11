# Object Detector and Info Finder

ODIF detects object from the picture and finds the relevant information from clearnet. 

Objects are first detected through tensorflow's pretrained inception network and the chosen object is used to find more detailed information.

## Getting Started

Detailed instruction's [link](https://navruzbek1992.github.io/data_science_challenges/projects/object_detection.html)

### Prerequisites

Basic knowledge of tensorflow pretrained models is needed in order to be able to change and make the detector more robust. 

### Installing

Copy github repo to a local file.

Install important libraries. 

```bash
pip install -r requirements.txt
```

Install [Microsoft Visual Studio](https://visualstudio.microsoft.com/downloads/) since it is requried for running tensorflow. 

Install [Chrome driver](https://chromedriver.chromium.org/downloads) for selenium. It is required for google search.

## Deployment

From CMD run 


```bash
python odif.py
```

## Authors

[navruz](https://github.com/navruzbek1992)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
