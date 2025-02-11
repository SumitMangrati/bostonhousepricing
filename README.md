### Boston House Pricing Prediction

### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [VScode]()
3. [HerokuAccount](https://heroku.com)
4. [GitCLI]()


### Create a new environment

```
conda create -p venv python==3.7 -y
```   
### activate the environment
``` 
conda activate venv/
```
### install the requirements
```
pip install -r requirements.txt
```
### Testing the predict_api
use postman or thunderclient with [localhost ip]/predict_api
Test with this json data
```
{
    "data":{
        "CRIM": 0.00632,
        "ZN": 18.0,
        "INDUS":2.31,
        "CHAS": 0.0,
        "NOX": 0.538,
        "RM": 6.575,
        "AGE": 65.2,
        "DIS": 4.0900,
        "RAD": 1.0,
        "TAX": 296,
        "PTRATIO": 15.3,
        "B": 396.90,
        "LSTAT": 4.98
    }
}
```