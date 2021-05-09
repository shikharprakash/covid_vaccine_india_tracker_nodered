# Covid Vaccine India Tracker Nodered

# Description
Using node red flow editor a UI for checking vaccine availablity in any district is achieved.
![Interface](https://user-images.githubusercontent.com/83905561/117569714-a871e280-b0e4-11eb-8c92-1740495cd469.jpg)

This flow allows one to message a certain number ,the link to register.
State-wise stats of total confirmed and recovered cases as well as India's total statistics are also shown.

The Flow:
![flow1](https://user-images.githubusercontent.com/83905561/117569721-b7589500-b0e4-11eb-8c49-1aea556fde04.jpg)
![flow2](https://user-images.githubusercontent.com/83905561/117569724-ba538580-b0e4-11eb-827d-3d18863be8aa.jpg)



# References
Metadata API for list of districts is used.
Appointment API , findbyDistrict is also used form the following link:
https://apisetu.gov.in/public/api/cowin#/

Current day numbers across districts and states is taken using the API from the following link:
https://github.com/covid19india/api
