# Wordpress/Flywheel Process

## Setup
1. Purchase Domain
2. Flywheel site creation
    1. In Flywheel, create a new site.
    2. Use "Streamlined Studio" as site owner
    3. Enter in a Site Name
    4. Enter in a temporary domain
    5. Use streamlinedadmin as admin username
    6. Enter in standard streamlined studio password
    7. For "how would you like to pay?" Select "Bulk Method"
3. Wordpress Setup
    1. Log in to sites WP Dashboard (/wp-admin)
    2. Install [Envato Market Plugin](http://envato.github.io/wp-envato-market/) by going to Plugins -> Add New -> Upload
    3. Go to envato plugin tab in sidebar and click "Generate a personal token" to generate token
    4. Go to envato plugin tab in sidebar and insert token in the token input and click save changes
    5. Under themes tab in envato plugin install salient theme
    6. Under plugins tab in envato plugin install Salient Visual Composer
    7. Create a new page named Home
    8. Got to settings -> reading -> Front Page Displays -> A State Page : Select "Home" Page
    
## Desigin / Development
1. Use [salient demos](http://themenectar.com/demo/salient-promo/#demos) for inspiration 

## Deployment to Production
1.  At the Domain registrar:
    1. Point the domain's A record to the IP Address for Flywheel
    2. Create a CName for www that points to the root domain
2. At the hosting (Flywheel) level:
    1. Setup the Domain in flywheel (setup both www and naked, but make www the primary)
    2. Add the SSL
    3. Force the SSL
    4. Update images/apis (edited)

---------------------

- Estimated time: 4 hours
- Flywheel/Wordpres Setup time: 20 min
- Wordpres Design/Development time: 4 Hours
- Deployment: TBD


**At the Registrar**
1) Point the domain to the IP Address for Flywheel
2) Create a CName for www that points to the root domain

**At Flywheel**
3) Setup the Domain in flywheel (setup both www and naked, but make www the primary)
4) Add the SSL
5) Force the SSL
6) Update images/apis (edited)
