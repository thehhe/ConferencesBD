# ConferencesBS
SQL design of database for conference managment

Table decsription:

- Conferences - basic information of a single conference: name, date of beginning and end of the conference, address.
- ConferenceDays - info about the day of the conference. Contains max possible number of attendants
- Prices - price of the ticket with the date up to which the price changes
- Workshops - workshop information
- WorkshopSignUps - connection between workshop and people who signed up
- ConferenceSignUps - connection between ConferenceDays and people who signed up
- Customers - data about the attendant (company or single person). Also has their login and password
- People - individual attendants and people signed by their companies
- SignedConferences - reservation of the conference attendants
- SignedWorkshops - analogically as SignedConferences
- Payments - the amount of money customer paid.
