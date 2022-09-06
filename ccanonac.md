# Project Summary
A tournament analyzer that takes in the status of a tournament bracker/group and calculates the possible combinations of match outcomes to reach a particular group/bracket outcome. An example could be using the current state of an in-progress round-robin group calculating possible combinations of opponents a particular player would need to beat and by how much in order to achieve a particular placement in the group.

# Problem being Solved
Following a tournament with a round-robin format can be difficult when trying to figure out how the team or player you're cheering for could advance from the group given their current standings. Often this might involve quite a bit of mental math to figure out what match outcomes are necessary for a given outcome, but if the group isn't near completion there are too many possibilities to easily keep track of. This program will make following theses types of tournaments much simpler by taking in the current status of a group and providing tools to analyze what opponents a team would need to beat in order to advance for example.

# Major Features
- Recieve input containing the current state of a round-robin group
  - Potentially support more formats such as double/triple/quadruple elimination brackets
- Given a target team and outcome, calculate possible combinations of future match outcomes that would lead to the given outcome
- Allow for quick and easy modification of the input to match the real group state or test potential scenarios
- Allow for customization of tiebreakers and score format
- Allow user to quickly cycle between what team to focus on and what outcome is desired
  - Potentially support focusing on multiple teams and outcomes at once
- Present information to user in an intuitive way

# Technologies
- C++
  - Can be run entirely locally as a console application
- Web framework?
  - Potentially accessible as a web application

# Target Audience
People that enjoy following tournaments and thinking about what their favorite player or team needs to do to advance, or thinking about what outcomes make certain other outcomes possible or impossible.