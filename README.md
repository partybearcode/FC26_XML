# FC26 Game Data XML Project

This project stores and validates FC26 game user data in XML format using a custom DTD definition.
It's designed to simulate FIFA Ultimate Team (FUT)-style data including players, teams, stats, competitions, and account profiles.
The main goal is to provide a structured XML + DTD dataset for learning, testing, or integration purposes.


## Getting Started

These instructions will give you a copy of the project up and running on
your local machine for development and testing purposes. See deployment
for notes on deploying the project on a live system.

### Prerequisites

- [A text editor such as VS Code, Notepad++, or Sublime Text.]
- [An XML validator tool or plugin (examples: xmllint, XML Copy Editor, or online validators).]

### Usage


1. Clone this repository:

    git clone
    cd FC26_XML

2. Open the file FC26_users.xml in your XML editor.

3. Validate the XML file against the FC26_users.dtd (in this example i'm using xmllint):

    xmllint --noout --dtdvalid FC26_users.dtd FC26_users.xml

4. Modify the data (teams, users, stats, etc.) to create your own simulation scenarios.


## Built With

  - [Visual Studio Code](https://code.visualstudio.com/) - Used for XML, DTD and README.md



## Authors

  - **PartyBear** - *Generated the XML and DTD documents* -
    [partybearcode](https://github.com/partybearcode)
  - **DefaultBear** - *Provided his FC26 team stats for trying out the project*
  - **Billie Thompson** - *Provided README Template* -
    [PurpleBooth](https://github.com/PurpleBooth)

## Acknowledgments


Helpful resources and tutorials that supported this project:

- [W3Schools - XML Tutorial](https://www.w3schools.com/xml/)
- [W3C - XML Specification](https://www.w3.org/XML/)
- [W3Schools - XML DTD Guide](https://www.w3schools.com/xml/xml_dtd_intro.asp)
- [FreeFormatter - XML Validator & Formatter](https://www.freeformatter.com/xml-validator-xsd.html)
