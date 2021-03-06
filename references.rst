.. _references:

References
==========

**Please remember all values are case sensitive**
-------------------------------------------------

Encodings
---------

Handshake requires your file uploads to be UTF-8  (http://www.utf8-chartable.de/)

Example command to check your file's encoding `file ./input_file.csv`

Example command to convert your file to UTF-8 `iconv -f MACROMAN -t UTF-8 ./input_file.csv > ./output_file.csv`

Booleans
--------

If specifying a boolean value (true or false) please use all lower case or all upper case letters
Good: TRUE true FALSE false
Bad: True False

Dates
-----
| When using dates or datetimes in the CSV or API, please provide them in one of the following formats:
| yyyy-mm-dd
| yyyy-mm-ddThh:mm:ss (assumes UTC time if no offset is present)  
| yyyy-mm-ddThh:mm:ss offset (where timezone offset is either + or -, and hh:mm)  
| **Example with offset: 2016-11-01T08:15:00-08:00**

School Years
------------

The following standardized list of school years are supported in Handshake::
   
   Freshman
   Sophomore
   Junior
   Senior
   Masters
   Doctorate
   Postdoctoral Studies
   Alumni


Gender
------

The following standardized list of genders supported in Handshake::

    Male
    Female
    Other


Work Authorizations
-------------------

The following standardized list of work authorizations supported in Handshake::

    U.S. Citizen
    Student (F-1) Visa
    J-1 Visa (Exchange Program)
    Permanent U.S. Resident
    Employment (H-1) Visa
    TN Visa
    L1 Visa
    Work Card
    H4 Visa


Education Levels
----------------

The following standardized list of education levels are supported in Handshake::

   High School
   Associates
   Certificate
   Advanced Certificate
   Bachelors
   Masters
   Doctorate
   Postdoctoral Studies


Administrative Roles
----------------------
The following roles are supported in Handshake::

   Experiences
   Articles
   Manage Own Appointments
   Manage All Appointments
   External Feeds
   Jobs
   Employer Approvals
   Manage Students
   View as Student
   Events
   Surveys
   Interview Schedules
   Reports
   Manage Staff
   Upload Attachments
   Career Plans
   Rooms
   Mass Emails
   Mentorships
   Outcomes
   Posts
   Student Reviews
   Applications
   Career Fairs
   Pins
   View Shared Notes
   Manage Labels
   Launch Check-in Kiosk

Salary Type Names
-----------------

The following standardized list of salary types is supported in Handshake::

   Paid
   Unpaid
   Commission Only
   Commission Plus Salary

Job Type Names
--------------

The following standardized list of job types is supported in Handshake::

   Job
   Internship
   Cooperative Education
   Experiential Learning
   On Campus Student Employment
   Fellowship
   Graduate School

Employment Type Names
---------------------

The following standardized list of employment types is supported in Handshake::

   Full-Time
   Part-Time
   Seasonal

Ethnicity
---------------------

The following standardized list of ethnicities is supported in Handshake::

   Native American/Alaskan Native
   Black or African American
   Asian/Asian American
   Native Hawaiian/Pacific Islander
   Latino(a)
   White/Caucasian
   Middle Eastern


Industries
----------

The following standardized list of industries are supported in Handshake::

    Accounting
    Advertising, PR & Marketing
    Aerospace
    Animal & Wildlife
    Architecture and Planning
    Automotive
    Biotech & Life Sciences
    Civil Engineering
    Commercial Banking & Credit
    Computer Networking
    Construction
    CPG - Consumer Packaged Goods
    Defense
    Design
    Electronic & Computer Hardware
    Environmental Services
    Farming, Ranching and Fishing
    Fashion
    Food & Beverage
    Forestry
    Government - Local, State & Federal
    Healthcare
    Higher Education
    Hotels & Accommodation
    Human Resources
    Insurance
    Interior Design
    International Affairs
    Internet & Software
    Investment Banking
    Investment / Portfolio Management
    Journalism, Media & Publishing
    K-12 Education
    Legal & Law Enforcement
    Management Consulting
    Manufacturing - Other
    Medical Devices
    Movies, TV, Music
    Natural Resources
    NGO
    Non-Profit - Other
    Oil & Gas
    Other Agriculture
    Other Education
    Other Industries
    Performing and Fine Arts
    Pharmaceuticals
    Politics
    Real Estate
    Religious Work
    Research
    Restaurants & Food Service
    Retail Stores
    Scientific and Technical Consulting
    Social Assistance
    Sports & Leisure
    Telecommunications
    Tourism
    Transportation & Logistics
    Utilities and Renewable Energy
    Veterinary
    Wholesale Trade

Job Functions
-------------

The following standardized list of job functions are supported in Handshake::

    Accounting
    Actuary
    Administration
    Advertising, Media & PR
    Architecture & Planning
    Business Development
    Community & Social Services
    Construction / Contracting
    Consulting
    Counseling
    Customer/Technical Support
    Data & Analytics
    Design / Art
    Education / Teaching / Training
    Engineering - Civil / Mechanical / Other
    Engineering - Web / Software
    Entrepreneurship
    Environmental / Sustainability Mgmt
    Finance
    Fundraising & Event Management
    General Management
    Healthcare Services
    Hotel / Restaurant / Hospitality
    Human Resources
    Information Technology
    Legal
    Logistics & Supply Chain
    Marketing - Brand Management
    Marketing - General
    Military & Protective Services
    Operations / Production
    Other
    Political Organizing / Lobbying
    Product / Project Management
    Purchasing
    Quality Assurance
    Real Estate
    Research
    Sales
    Veterinary / Animal Care
    Writing / Editing


Time Zone Options
-----------------

The supported options for time zones in Handshake are::

    "American Samoa"
    "International Date Line West"
    "Midway Island"
    "Hawaii"
    "Alaska"
    "Pacific Time (US & Canada)"
    "Tijuana"
    "Arizona"
    "Chihuahua"
    "Mazatlan"
    "Mountain Time (US & Canada)"
    "Central America"
    "Central Time (US & Canada)"
    "Guadalajara"
    "Mexico City"
    "Monterrey"
    "Saskatchewan"
    "Bogota"
    "Eastern Time (US & Canada)"
    "Indiana (East)"
    "Lima"
    "Quito"
    "Caracas"
    "Atlantic Time (Canada)"
    "Georgetown"
    "La Paz"
    "Santiago"
    "Newfoundland"
    "Brasilia"
    "Buenos Aires"
    "Greenland"
    "Montevideo"
    "Mid-Atlantic"
    "Azores"
    "Cape Verde Is."
    "Casablanca"
    "Dublin"
    "Edinburgh"
    "Lisbon"
    "London"
    "Monrovia"
    "UTC"
    "Amsterdam"
    "Belgrade"
    "Berlin"
    "Bern"
    "Bratislava"
    "Brussels"
    "Budapest"
    "Copenhagen"
    "Ljubljana"
    "Madrid"
    "Paris"
    "Prague"
    "Rome"
    "Sarajevo"
    "Skopje"
    "Stockholm"
    "Vienna"
    "Warsaw"
    "West Central Africa"
    "Zagreb"
    "Athens"
    "Bucharest"
    "Cairo"
    "Harare"
    "Helsinki"
    "Istanbul"
    "Jerusalem"
    "Kyiv"
    "Pretoria"
    "Riga"
    "Sofia"
    "Tallinn"
    "Vilnius"
    "Baghdad"
    "Kuwait"
    "Minsk"
    "Nairobi"
    "Riyadh"
    "Tehran"
    "Abu Dhabi"
    "Baku"
    "Moscow"
    "Muscat"
    "St. Petersburg"
    "Tbilisi"
    "Volgograd"
    "Yerevan"
    "Kabul"
    "Islamabad"
    "Karachi"
    "Tashkent"
    "Chennai"
    "Kolkata"
    "Mumbai"
    "New Delhi"
    "Sri Jayawardenepura"
    "Kathmandu"
    "Almaty"
    "Astana"
    "Dhaka"
    "Ekaterinburg"
    "Rangoon"
    "Bangkok"
    "Hanoi"
    "Jakarta"
    "Novosibirsk"
    "Beijing"
    "Chongqing"
    "Hong Kong"
    "Krasnoyarsk"
    "Kuala Lumpur"
    "Perth"
    "Singapore"
    "Taipei"
    "Ulaanbaatar"
    "Urumqi"
    "Irkutsk"
    "Osaka"
    "Sapporo"
    "Seoul"
    "Tokyo"
    "Adelaide"
    "Darwin"
    "Brisbane"
    "Canberra"
    "Guam"
    "Hobart"
    "Melbourne"
    "Port Moresby"
    "Sydney"
    "Yakutsk"
    "New Caledonia"
    "Solomon Is."
    "Vladivostok"
    "Auckland"
    "Fiji"
    "Kamchatka"
    "Magadan"
    "Marshall Is."
    "Wellington"
    "Chatham Is."
    "Nuku'alofa"
    "Samoa"
    "Tokelau Is."
    
Major Groups
------------

The following list of major groups is supported in Handshake. The categories are listed at the top level, with the major groups themselves underneath.

Arts and Design::

    Architecture
    Art History
    Design and Applied Arts
    Drama and Theatre Arts
    Fine and Studio Arts
    Graphic Design
    Industrial Design
    Interior Design
    Museum Studies
    Music and Music Education
    Photography
    Product Design/Packaging
    Textiles and Clothing

Business and Entrepreneurship::

    Accounting
    Actuarial/Risk Analysis
    Business Administration and Management
    Business Analytics
    Consulting
    Economics
    Entrepreneurship
    Finance and Financial Management
    Food Industry Management
    Human Resources
    Marketing
    Operations Management
    Parks, Recreation, and Leisure Studies
    Real Estate
    Retail and Hospitality Administration
    Sales
    Sport Business and Marketing
    Supply Chain Management

Communications::

    Advertising
    Communication and Media Studies
    Digital Communication
    Documentary/Film
    Journalism
    Public Relations
    Radio, Television, Media

Computer Science, Information Systems, and Technology::

    Computer Programming
    Computer Science
    Cyber Security
    Data Mining
    Information Systems Management
    Library Sciences
    Software Design
    User Experience/Social Computing

Education::

    Early Childhood Education
    Education Administration
    Elementary Education
    Health and Physical Education
    Language Arts Education
    Mathematics Education
    Secondary Education
    Special Education

Engineering::

    Aerospace Engineering
    Agriculture and Biological Engineering
    Biomedical Engineering
    Chemical Engineering
    Civil/Environmental Engineering
    Computer Engineering
    Construction Engineering & Management
    Electrical Engineering
    General Engineering
    Industrial Engineering
    Materials Science & Engineering
    Mechanical Engineering
    Nautical/Naval Engineering
    Network Engineering
    Nuclear Engineering

Health Professions::

    Athletic Training
    Communication Disorders Sciences and Services
    Dentistry
    Health/Exercise Science
    Health/Hospital Administration
    Kinesiology
    Medicine
    Movement Science
    Nursing
    Nutrition
    Pharmacy
    Physical/Occupational Therapy
    Public Health
    Speech Pathology

Social Sciences::

    Anthropology
    Cognition & Neuroscience/Biopsychology
    Counseling
    Family and Consumer Science
    Human and Child Development
    Psychology
    Social Work/Human Services
    Sociology

Civics and Government::

    Criminal Justice/Criminology
    Emergency Management/Homeland Security
    Forensics
    International Studies/Comparative Politics
    Law
    Political Science and Government
    Public Administration
    Public Policy
    Urban Planning

Humanities and Languages::

    Classical Studies
    Comparative Literature
    Creative Writing
    Cultural and Ethnic Studies
    English
    Foreign Languages and Literature
    Gender Studies
    History
    Linguistics
    Philosophy/Ethics
    Religious Studies/Divinity/Theology

Life Science::

    Animal Science
    Anthropology/Zoology
    Biology
    Ecology
    Epidemiology
    Genetics
    Immunology
    Marine Biology
    Microbiology
    Physiological Science

Math and Physical Sciences::

    Chemistry
    Physics
    Mathematics
    Statistics

Natural Resources, Sustainability and Environmental Science::

    Agriculture
    Cartography
    Conservation
    Earth Sciences
    Fisheries and Wildlife
    Forestry
    Geology/Mining
    Natural Resource Management
    Oceanography
    Plant Sciences/Horticulture
