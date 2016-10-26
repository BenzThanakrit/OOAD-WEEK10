# OOAD-WEEK10
Sequence Diagram



## code login
```
@startuml

title login

user -> loginpage : insert username password
loginpage -> loginDB : validate information
loginDB -> userMainscreen : success
userMainscreen -> user : login success

@enduml
```
## รูป
![](http://www.plantuml.com/plantuml/img/NOv13i8m30JlVeK_m0Sue0fnxIEin5IM4gUA7VW-BgKWSVJkpCgJENKVjG2uU64iRH456COTJvVzN6bXFADeX8vRfLGPLp9xjfxX1nt6xHhyWufaSWxntdebbwPmr45kGpF5QkhC6eADbDWC_eeF6i1R_c8miUPu_GK0)

## code 
```
@startuml

title sale


customers -> Owner : order
customers -> Owner : Payment
Owner  -> product : pack up

customers <- Owner : receive order
@enduml
```
## ![](http://www.plantuml.com/plantuml/img/ROxB2O0m40NlMyKsO0CYOWVQGaZUGSoFpKQnUnL5F7Xy36-OeQWHhS4JwQmUN8m74TbQD0L8uQRdSOiGRZc9W_oZoUm1KUdU5ycINBLwicpimZL_fLtpFWKMyuf7FY2wi-O0)


##code 
```
@startuml

title atm


cardholder -> ATMmachine : insert card
cardholder -> ATMmachine : enter password
cardholder <-- ATMmachine : requst password
cardholder -> ATMmachine : choosetranstype
ATMmachine  -> account  : checkpassword
cardholder <- ATMmachine : follow manu
cardholder <- ATMmachine : issue card
@enduml
```
##![](http://www.plantuml.com/plantuml/img/VT313S8m30NGUwRm0bq08LG6uCO2LcAKYCGkiQEAxMdBXQ2gL_lfVzcZ6bPh9JjdoJ81Md7EUQmXIWvKORZ0zNuhw6DYWXCaLge6gpXYnBPC9rITfPVdOUXffLTJsxN_gJwAA5b5LdjFv7wMgqNlfR719ia_z-lxo8VaB3CKv7R4acgZxzKZSLW-zW40)

##code
```
@startuml

title student


student -> seminar : enroll
seminar -> course : eligible
course -> student : getseminar

@enduml
```
##รูป 
![](http://www.plantuml.com/plantuml/img/DOr12i0W30Jl-ufye1_mKFoAhK64g934_rV1tfPPPZUQ9_NP1F3gmcG-CtS7S19TDnctsfDI8EuwHF23rRrZgl6kf9Rw2EEGxPs9G8NzE43adjVZ1m00)


##code
```
@startuml

title Hospital

customer ->nurse:cheak history
doctor -> customer : heal
customer -> staff :payment 
nurse -> doctor :Sent Data preliminary 
@enduml
```
##รูป
![](http://www.plantuml.com/plantuml/img/JKwv3SCm3Emv1HV80Ye25odIPm92fc4Y-a1HXROt7HX6giEzkAKRgOsS04miCRvhRsBaF8vkDRFYurc6TWvnP_hYBYxhXBL6HpVn3WRqHFeleizl6uP6CtCnXD_IQLpry3db5nbXKqwIfP1EX8NBwgyE)
