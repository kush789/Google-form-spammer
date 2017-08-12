# Google Form Spammer


        As of 13/12/16 this script no longer works. Google changed the type of each 
        form control to "HiddenControl". Earlier on it was something like "text",
        "select", "radio" etc. Because of this it is impossible to identify what kind
        a form control is, so filling it is not so trivial (it could be anything such as
        text/date/select etc.).


A python script that spams a google form as many times as you want.

Instructions for setup
------------

- Clone the project

        git clone https://github.com/kush789/Google-form-spammer.git google_form_spammer
        cd google_form_spammer

- Install the project's runtime requirements

        pip install -r requirements.txt

- Run the script with arguments

        python spammer.py 'url' (in quotes) times
        
  ``url`` : URL of the google form <br>
  ``times`` : number of times you want to spam the form

**That was it, happy spamming!**

About
-----------

* What can it spam ? (1)
  
  - Single page Google forms
  - The following controls :
    - text
    - textarea
    - select
    - radio
    - checkbox

* What can it not spam?
  
  - Multi page forms
  - Forms that require login (Duh!)
  - A google form which has stuff not mentioned in (1)

Issues
------------

Please report any bugs or requests that you have using the GitHub issue tracker!

License
------------

                               Licensed under WTFPL
                   Do What the Fuck You Want to Public License
                              http://www.wtfpl.net/

                   Author is nor liable for misuse; Use carefully!

            2015 (C) Kushagra Singh | kushagra14056 [at thingy] iiitd.ac.in
