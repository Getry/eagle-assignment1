#Change Log

Team membership:  Teah Elaschuk (Captain) &  Nathan Miles & Lancelei Herradura
Team conventions: Allman notation, markdown for changelog
Changelog format: [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## *Version 1.0.0*
Release Date: 2017-10-5

### Added
	- created starter project (TE)
	- created changelog and readme (TE)
### Updated 

## *Version 1.0.1*
Release Date: 2017-10-5
### Added
        - Added Bootstrap and menubar and fleet page (LH)
        - Added Flights page with it's controller and views (LH)
### Updated 
        - welcome.php and template.php (LH)
        - updated bootstrap version and added the flights page onto (LH)
        - nav bar using config.php (LH)

## *Version 1.0.2*
Release Date: 2017-10-5

### Added
	- created model Fleet (NM)
	- created model Flights (NM)
### Updated 


## *Version 1.0.3*
Release Date: 2017-10-7

### Added

### Updated
        - models/Flights.php: changed file name to FlightInfo to fix a naming conflict (TE)
        - controllers/Flights.php: loaded model data and passed to view (TE)
        - views/flights.php: created a table to display flight info (TE)

## *Version 1.0.4*
Release Date: 2017-10-8
### Added

### Updated
        - controllers/FlightInfo.php: added data2 to pass in the connecting airports (LH)
        - views/welcome.php: displayed airline info (LH)

## *Version 1.0.5*
### Added
        
### Updated
        - controllers/Welcome.php: added comments, fixed fleetinfo bug changed it to Info instead of info
        - controllers/Flights.php: fixed flightinfo bug and changed 'info' to 'Info'
        - models/FlightInfo.php: added port1 and port2 for mouseover, added comments
        - views/flighs.php: added hover over flight number function

## *Version 1.0.6*
### Added
        
### Updated
        - controllers/Flights.php: fixed the bug for real this time


## *Version 1.0.7*
### Added
        - added planes.php to views and added information from plane (NM)
### Updated
        - controller/fleet.php added fleet tables and subcontroler for each plane (NM)
        - views/fleet.php setup table to display fleet correctly (NM)
        - config/routes.php corrected routes from fleet to allow each plane to be displayed (NM)
        
## *Version 1.0.8*
### Added
        
### Updated
        - models/FleetInfo added more information (NM)
        - views/planes.php setup table to display planes correctly (NM)
        - controller/Fleet Fixed and error (NM)
      