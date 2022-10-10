## Educational-Role-play-Game-Avatar-Inferences
### Challenge description
Dataset: gain insights from the player data from the Play2Prevent lab's PlayForward: Elm City game https://docs.google.com/presentation/d/1iYCEFOiZKJ8BKYyfmbQPLCyU9cPK1cKkULuJ-YLlNr0/edit?usp=sharing

### Project description
Thesis questions
To what extent do playing experiences differ for students with different avatars? How do we characterize playing experience and categorize students based on it?

### Tools
R: data clean up & factor building
Panda: data combination & manipulation
Sklearn: data clustering & analysis
Matplotlib/Plotly: 3D visualization

### Approach
Distill to related variables: 
Avatars types (age, gender, ethnicity) Game experience (stack progress/session, total playtime, average skill points/session) 
Categorize players with K-Means clustering on normalized data Examine game experiences among different avatars by: 
Coloring based on avatar types Performing ANOVA test to compare group means
