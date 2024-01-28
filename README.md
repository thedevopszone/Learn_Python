# Learn_Python


## .env files


```
pip install -U python-dotenv
```


```
from dotenv import load_dotenv
import os
load_dotenv()

print("Der Webmaster heißt: "+str(os.getenv("WEBMASTER_NAME")))
```
