# One Minute -Pitch Project
one minute-Pitch is an application that allows users to create  one minute pitches. The users will submit their one minute pitches and other users will vote on them and leave comments to give their feedback on them.

## Author
>  Jack Owuor.

## Installations

The following command installs all the application requirements
>``pip freeze -r requirements.txt`` 

## Setup
Run 
``git clone https://github.com/jn-mic/1m-Pitchbase.git``

or download the zip file from github.

After extracting the files, 

1. Navigate to the project folder
>`` cd gitSearch.`` 

2. Creating a virtual environment
>``virtual env virtual.``

3. Activating the virtual environment
>``source venv/bin/activate.``

4. Running the application
>``python3.8 manage.py server 
       or
    chmod a+x start.sh
  ./start.sh

``

5. Running tests

 > ``python3.8 manage.py test.``

## Technologies used
* Python3.8
* Flask
* Javascript
* Html5
* Css
* Bootstrap

## User Stories
* As a user, I would like to see the pitches other people have posted.
* As a user, I would like to vote on the pitch they liked and give it a downvote or upvote.
* As a user, I would like to be signed in for me to leave a comment
* As a user, I would like to receive a welcoming email once I sign up.
* As a user, I would like to view the pitches I have created in my profile page.
* As a user, I would like to comment on the different pitches and leave feedback.
* As a user, I would like to submit a pitch in any category.
* As a user, I would like to view the different categories. 

## BDD(Behaviour Driven Development)
>Login Inputs

| Inputs |  Description |
| Username  | Account username, ``eg Jack``|
| Password  | Account password, ``eg Password``|

>login inputs
| Inputs |  Description |
| Username  | Account username, ``eg john``|
| Email  | User email, ``eg doty@testmail.com``|
| Password  | Account password, ``eg password``|
| Confirm Password  | Account password, ``eg password``|

> Pitches inputs

| Inputs | Description  | Find Pitches on submit
| Comment| A comment on the pitch|

## License
> MIT License &copy; 2021 Jack  Owuor.

## Collaborate
To collaborate, reach me on:[jackotienokey@gmail.com]()
