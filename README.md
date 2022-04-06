# Relation_DB
Information on Relation Databases
jcbc.png is the model for: The Jonesburgh County Basketball Conference (JCBC) is an amateur basketball association. Each city in the county has one team that represents it. Each team has a maximum of 12 players and a minimum of 9 players. Each team also has up to 3 coaches (offensive, defensive, personal training). Each team plays 2 games (home and away) against each of the other teams during the season.
It identifies:
a. The connectivity and cardinality of each relationship
  In the City and Team relationship - each city has 1 Team and each team belongs to 1 City - 1:1
  In the Team and Player relationship - each Team has many Players and each Player belongs to 1 Team - M:1
  In the Team and Coach relationship - each Team has many Coaches and each Coach has 1 team - M:1
  In the Team and Game relationship - each Team plays many Games and each Game has many teams - M:M
  The Team and Game entities are decomposed (projected) to a 1:M relationship with Team_Game
b. The Crow's Foot ER diagram to represent the JCBC database


