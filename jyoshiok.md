# Problem
Although The University of Tennessee offers a variety of dining locations throughout campus, it can sometimes be a challenge to obtain food without excessive wait times due to overcrowdedness. This can negatively impact students' well-being, whether disrupting their busy schedules or persuading them to abandon their nutritional needs (i.e., skipping a meal). Efforts have been made to resolve this, such as food trucks, "Grab & Go" options, and Starship delivery robots. However, overcrowdedness at dining locations has persisted. Although this issue may be unavoidable without a costly solution (e.g., opening new dining location(s)), providing situational awareness of wait times at each dining location would improve students' decision-making and enable administrative optimizations of dining operations.

# Solution
A web-based app that provides analytics and suggestions centered around college campus dining locations. This would include real-time and historical wait times at each location, number of people currently in line, abandonment rates (i.e., people who leave the line), and suggestions on where to eat based on current wait times. These insights would be derived from data collected using computer vision to detect and track individuals in line at each dining location. Students' identities would be kept anonymous, only storing the analytics. Looking forward, this could be integrated into the dining website to offer a centralized tool.

# Major Features
- Real-time vision-based algorithm that counts the number of individuals in line and tracks how long they wait.
- List/map of campus dining locations; when clicked, analytics for that location display.
    - Analytics to display: real-time wait times, historical wait times (line chart), number of people currently in line, and abandonment rates.
    - For proof of concept, actual dining location data may not be collected; instead, we may collect "simulated" data (i.e., just standing in a line and pretending to wait for food).
- Suggestions on where to eat based on current wait times (and maybe current location).

# Tech Stack
- Front-End: React, SASS
- Back-End: Python, Django, SQL
- Data Collection: Python, Tensorflow, OpenCV
    - [Reference Article](https://medium.com/@madhawavidanapathirana/https-medium-com-madhawavidanapathirana-real-time-human-detection-in-computer-vision-part-1-2acb851f4e55)

# Target Audience
For proof of concept, this would be implemented at The University of Tennessee for students and the administration. This could be expanded to other colleges or any restaurant, as long as the appropriate hardware is installed (i.e., cameras).