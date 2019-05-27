### Overview
1) This project uses Vue Router and Vuex which is state management library for vuejs

2) There is a simple form which need to be filled, if the form doesn't get appropriate data 
then validation rule restrict the form to submit.


3) For front end validation VeeValidate is used.

4) DatePicker library is used for date

### Javascript Style Guide : Airbnb
### HTML BEM pattern follwed

### How it works
When user submit the form,validation rules check whether data is appropirate or not. If the data is appropriate then it is stored in vuex store otherwise form is not submitted.

Another component (Profile) access the data stored in vuex store and displays it. 

### For demo
1) Clone this repository

2) cd inside Vuejs-Assessment

3) npm install

4) npm run serve


