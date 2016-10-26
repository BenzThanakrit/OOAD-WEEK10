# OOAD-WEEK10
Sequence Diagram



# code login
```
@startuml

title login

user -> loginpage : insert username password
loginpage -> loginDB : validate information
loginDB -> userMainscreen : success
userMainscreen -> user : login success

@enduml
```
# รูป
![](http://www.plantuml.com/plantuml/img/NOv13i8m30JlVeK_m0Sue0fnxIEin5IM4gUA7VW-BgKWSVJkpCgJENKVjG2uU64iRH456COTJvVzN6bXFADeX8vRfLGPLp9xjfxX1nt6xHhyWufaSWxntdebbwPmr45kGpF5QkhC6eADbDWC_eeF6i1R_c8miUPu_GK0)

# code 
```
@startuml

title sale


customers -> Owner : order
customers -> Owner : Payment
Owner  -> product : pack up

customers <- Owner : receive order
@enduml
```
# ![](http://www.plantuml.com/plantuml/img/ROxB2O0m40NlMyKsO0CYOWVQGaZUGSoFpKQnUnL5F7Xy36-OeQWHhS4JwQmUN8m74TbQD0L8uQRdSOiGRZc9W_oZoUm1KUdU5ycINBLwicpimZL_fLtpFWKMyuf7FY2wi-O0)
