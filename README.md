# Body Book
            Body Book is a company that will ensure you can keep your personal health in tact, while dealing with 
        the hustle and bustle of everyday life. Information such as vaccine history or your last checkup may not seem 
        overly important, but without it we subject ourselves to uninformed professionals, resulting in questionable 
        medical procedures. With Body Book you can keep all your health information at your finger tips, including, 
        but not limited to, setting up new appointments and a list of medications you are allergic to. Here at Body 
        Book we strive to minimize the amount of medical mixups, regardless of how serious or trivial they may be.
    
    *Check out the latest version of the working site at: 
[Body Book](https://secure-wildwood-86684.herokuapp.com/)
        
        *If you don't want to sign-up just use this login info:
            account: guest@guest.com
            password: password

# Prerequisites:
    To run locally off your machine follow these steps:
        1. clone this repository to your local machine. For help on how to do this visit: 
[https://services.github.com/on-demand/github-cli/clone-repo-cli](https://services.github.com/on-demand/github-cli/clone-repo-cli)

        2. run "npm i" to install the following npm packages:
            *bcrypt-nodejs
            *body-parser
            *express
            *express-handlebars
            *express-session
            *mysql2
            *passport
            *passport-local
            *sequelize
        3. Next you'll want to fire up your MAMP and your mySQL manging app (I use HeidiSQL).  If you need these 
        check out the links below: 
[MAMP](https://www.mamp.info/en/) && [HeidiSQL](https://www.heidisql.com/download.php)

        4. with your mySQL manager make sure everything aligns with the config.json info.
[Configuration](./gifs/config-match.gif)

        5. lastly, fire up the server in bash and got to "localhost:8080" in your web browser (chrome works best)
[Server](./gifs/server-demo.gif)


# Step-by-Step Walkthrough: 
    1. sign up with an email OR (for online only) use the guest account credentials:
        *sign up demo: 
[Sign Up](./gifs/sign-up.gif)

        *guest account info/demo: 
[Guest Login](./gifs/guest-login.gif)

            *email: guest@guest.com
            *password: password
    2. In the body book you can add medical information in an easy to reach location, we have broken it down into 4 
    categories: History of Body, Fix my Body, Medicate my Body, and Insure my Body.
        *History of Body (medical history):
            *this is where you can easily store and access your medical history:
[History Demo](./gifs/history-demo.gif)

        *Fix my Body (appointments):
            *this is where you can easily store all your upcoming medical appointments:
[Appointment Demo](./gifs/appointment-demo.gif)

        *Medicate my Body (prescriptions):
            *this is where you can easily store all your medications:
[Medication Demo](./gifs/meds-demo.gif)

        *Insure my Body (medical insurance):
            *this is where you can easily store all your insurance information:
[Insurance Demo](./gifs/insurance-demo.gif)

    3. The last feature is the log out button:
[Log Out](./gifs/log-out.gif)

# Built With
    *HTML
    *CSS
    *UIKit
    *Handlebars
    *Javascript
    *jQuery
    *Sequelize
    *Express
    *mySQL
    *Node.js
    Passport.js

# Authors:
    * Dantel Williamson - UI, UX, & API Calls
    * Derek Minney - Routing
    * Justin Moore - Server & Authorization
    * Stephen Ermisch - Database & Models