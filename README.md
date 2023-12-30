# FBPROX
SOME FACEBOOK TOOLS WHICH I COMBINED TO AN MODULE
>PYTHON  V3.10 - V3.12   
<br>

## HOW TO INSTALL
```python
pip install FBPROX
```
<br>  
<br>

### GENERATE TOKEN USING COOKIE
```python
from FBPROX import GetToken

cookie = "cookie"
PROX = GetToken(cookie)
token = PROX.generate_token_eaab()
print(f"Generated Token: {token}")
TokenEAAG = PROX.EAAG()
TokenEAAB = PROX.EAAB()
TokenEAAI = PROX.EAAI()
TokenEAAD = PROX.EAAD()
TokenEAAC = PROX.EAAC()
TokenEAAE = PROX.EAAE()
TokenEAAD = PROX.EAAD()
TokenEAAF = PROX.EAAF()
TokenEABB = PROX.EABB()

```
Result  
>Generated Token : EAAB................

<br>  
<br>

### GENERATE TOKEN USING ID&PASS
```python
from FBPROX import LOGIN

email = "Enter your email "
password = "Enter your password "
PROX = Login(email, password)
cookie = PROX.generate_cookie()
print(f"Generated Cookie: {cookie}")
if cookie:
  PROX = GetToken(cookie)
	TokenEAAG = PROX.EAAG()
	TokenEAAB = PROX.EAAB()
	TokenEAAI = PROX.EAAI()
	TokenEAAD = PROX.EAAD()
	TokenEAAC = PROX.EAAC()
	TokenEAAE = PROX.EAAE()
	TokenEAAD = PROX.EAAD()
	TokenEAAF = PROX.EAAF()
	TokenEABB = PROX.EABB()
	<br>
	EXAMPLE : 
    print(f"Generated Token: {TOKEN_EAAG}")
else:
    EXAMPLE:
    print("Cookie generation failed.")

```
Result  
>Generated Token : EAAB................
<br>  
<br>

## Auto Post

### Parameter
```python
cookie = "Enter your cookie "
caption = "Enter the caption "
photo_url = "Enter the Url "
privacy = "Enter the privacy (EVERYONE, FRIENDS, SELF)"
```

### Post To Feed
```python
from FBPROX import POST
AP = Post(cookie, caption, photo_url, privacy)
AP.feed()

```


### Return
```python
{'status':'Success'}
{'status':'Fail'}
```

<br>  
<br>


FBPROX is an facebook automation module written in python . Which can help you on various tasks . #facebook #hack #facebookhack
