Mobile Developer Candidate

The Mobile Team at Tquila ANZ strives to keep up to date and working with the bleeding edge of technology. We’re fond of experimental developers as they bring the best practices of different skills into the technology stack.


Our technology stack for our web builds use:

* React.js
* React Router
* Babel
* Redux/Redux Sagas/Reselect Selectors
* ImmutableJS
* CSS Modules
* Webpack 2

# Prerequisite


Feel free to use the packages you are most comfortable with, but we will require the following:

* The server must be written in Node/Express.
* Hot reloading must be supported the if NODE_ENV=development.
* The JavaScript must be loaded from a webpack generated bundle if NODE_ENV=production.
* The web application must be built using React.
* The web application must be written as a single page app.
* Choose any database that you are comfortable with.( Please host the supplied data in a suitable database).

And would like to see:

* Use of redux-sagas. Reference: https://github.com/redux-saga/redux-saga
* CSS Modules or another mechanism for enforcing scoping and/or preventing style leakage.
* CSS vendor prefixes automatically generated via webpack loaders.

# Requirements

Please include any additional packages or build tools that you may need and specify in your README.md.


Please refer to the JSON attached with this sheet for the data source required for the application.


1.     Create a list to list out all the Accounts in the data source.

2.     When a list item is selected, display the information associated to the Account.

3.     The Account should also display in a similar list, each and every one of the Contacts with their relevant information.

4.     When a contact is selected, flag the contact as ‘high risk’ and display it accordingly.


We would like to leave the UI/UX up to your discretion.


Assessment


We understand that time is important, and we have structured this in a way that we don’t expect this assessment to take more than a few hours.


What we want to see from this assessment is:

*  Good development practices
        ○  Componentization

        ○  TDD/BDD

        ○  Well set-up technology stack and environment

* Functional, custom application
* Great UI/UX
* Great Developer Experience


Submission


1.     Please host the source code on a public repository in GitHub, with a separate branch to hold the GitHub Pages application.

2.     Provide a README.md file to allow us to set up the environment on our end easily, including all the commands to run the scripts.


JSON Data Source:


{

        "Accounts" : [

                    {

                                "Name": "Team A",

                                "Phone": "0412345678",

                                "Email": "team@teama.com",

                                "Contacts": [

                                            {

                                                        "Name": "Contact AA",

                                                        "High_Risk": false,

                                                        "Amount": 20000

                                            },

                                            {

                                                        "Name": "Contact AB",

                                                        "High_Risk": false,

                                                        "Amount": 20000

                                            }

                                ]

                    },

                    {

                                "Name": "Team B",

                                "Phone": "0412123123",

                                "Email": "team@teamb.com",

                                "Contacts": [

                                            {

                                                        "Name": "Contact BA",

                                                        "High_Risk": false,

                                                        "Amount": 30000

                                            },

                                            {

                                                        "Name": "Contact BB",

                                                        "High_Risk": true,

                                                        "Amount": 50000

                                            }

                                ]

                    },

                    {

                                "Name": "Team C",

                                "Phone": "0402021244",

                                "Email": "team@teamc.com",

                                "Contacts": [

                                            {

                                                        "Name": "Contact CA",

                                                        "High_Risk": false,

                                                        "Amount": 1600

                                        }

                                ]

                    },

                    {

                                "Name": "Team D",

                                "Phone": "0429060332",

                                "Email": "team@teamd.com",

                                "Contacts": [

                                            {

                                                        "Name": "Contact DA",

                                                        "High_Risk": false,

                                                        "Amount": 22500

                                            },

                                            {

                                                        "Name": "Contact DB",

                                                        "High_Risk": false,

                                                        "Amount": 5000

                                            },

                                            {

                                                        "Name": "Contact DC",

                                                        "High_Risk": false,

                                                        "Amount": 20000

                                            }

                                ]

                    }

        ]

}



