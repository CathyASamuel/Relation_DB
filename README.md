# Relation_DB
Information on Relation Databases


jcbc.png is the model for: The Jonesburgh County Basketball Conference (JCBC) is an amateur basketball association. Each city in the county has one team that represents it. Each team has a maximum of 12 players and a minimum of 9 players. Each team also has up to 3 coaches (offensive, defensive, personal training). Each team plays 2 games (home and away) against each of the other teams during the season.

  In the City and Team relationship - each city has 1 Team and each team belongs to 1 City - 1:1
  In the Team and Player relationship - each Team has many Players and each Player belongs to 1 Team - M:1
  In the Team and Coach relationship - each Team has many Coaches and each Coach has 1 team - M:1
  In the Team and Game relationship - each Team plays many Games and each Game has many teams - M:M
    The Team and Game entities are decomposed (projected) to a 1:M relationship with Team_Game


The Hudson engineering group has contracted you to create a conceptual model whose application will meet the expected database requirements for its training program. The HEG administration gives you the following description of the training group’s operating environment. The HEG has 12 instructors and can handle up to 30 trainees per class. HEG offers five advanced technology courses, each of which can generate several classes. If a class has fewer than 10 trainees in it, it will be canceled. It is, therefore, possible for a course not to generate any classes. Each class is taught by one instructor. Each instructor may teach up to two classes or may be assigned to do research only. Each trainee may take up to two classes a year.

    In the Course and Class relationship - each Course generates many Classes and each class belongs to 1 course - M:1
    In the Class and Trainee relationship - each class has many Trainees and each trainee has many Classes - M:M
      Class and Trianee would be projected (decomposed) into 1:M relationships with Trainee_Class
    In the Class and Instructor relationship - each Class has 1 Instructor and each Instructor has many Classes - 1:M
  
