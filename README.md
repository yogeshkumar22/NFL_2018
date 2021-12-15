# NFL_2018

In this project we've used the NFL 2018 dataset for data analysis and visualization

## Analyzing the NFL games
The first dataset that we will be looking is the dataset containing information about the NFL games. Such kind of datasets are very helpful in giving us an idea about how a sport's season was/will be played out.

This dataset contains the following information:

- gameId: Game identifier, unique (numeric)

- gameDate: Game Date (time, mm/dd/yyyy)

- gameTimeEastern: Start time of game (time, HH:MM:SS, EST)

- homeTeamAbbr: Home team three-letter code (text)

- visitorTeamAbbr: Visiting team three-letter code (text)

- week: Week of game (numeric)


## Knowing the NFL players
The second dataset that we will be looking is the dataset containing infromation about the NFL players. Such kind of datasets are very helpful in giving us an idea about the physical attributes of a player and the distribution of player statistics amongst different team positions.

This dataset contains the following information:

- nflId: Player identification number, unique across players (numeric)

- height: Player height (text)

- weight: Player weight (numeric)

- birthDate: Date of birth (YYYY-MM-DD)

- collegeName: Player college (text)

- position: Player position (text)

- displayName: Player name (text)


## Visualizing the American Football Field
In this lesson, we will be visualizing the American football field using Matplotlib. This lesson takes inspiration from the work of the Kaggle Grandmaster, Rob Mulla, and we will be following his footsteps with some little changes of our own. 

The main objective is to learn how to create advanced plots using Matplotlib in order to build up confidence in creating any kind of plot that we want. 


## Visualizing Players onto the Field
The fourth dataset that we will be looking at is the dataset containing the tracking information of the players. Such kind of datasets are very helpful in breaking down different players gameplays on a personal level.

We will be visualizing the players on the field that we had built.

This dataset contains the following information:

- time: Time stamp of play (time, yyyy-mm-dd, hh:mm:ss)

- x: Player position along the long axis of the field, 0 - 120 yards. See Figure 1 below. (numeric)

- y: Player position along the short axis of the field, 0 - 53.3 yards. See Figure 1 below. (numeric)

- s: Speed in yards/second (numeric)

- a: Acceleration in yards/second^2 (numeric)

- dis: Distance traveled from prior time point, in yards (numeric)

- o: Player orientation (deg), 0 - 360 degrees (numeric)

- dir: Angle of player motion (deg), 0 - 360 degrees (numeric)

- event: Tagged play details, including moment of ball snap, pass release, pass catch, tackle, etc (text)

- nflId: Player identification number, unique across players (numeric)

- displayName: Player name (text)

- jerseyNumber: Jersey number of player (numeric)

- position: Player position group (text)

- team: Team (away or home) of corresponding player (text)

- frameId: Frame identifier for each play, starting at 1 (numeric)

- gameId: Game identifier, unique (numeric)

- playId: Play identifier, not unique across games (numeric)

- playDirection: Direction that the offense is moving (text, left or right)

- route: Route ran by offensive player (text)


