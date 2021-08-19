This repository includes a detailed Data Analytics Report I had prepared for an e-commerce company.

The data is provided in the form of a json file.

The data has 5 columns: 
- date: date of the ping
- timestamp: ping timestamp
- uid: unique id assigned to users (if the string is purely numeric, this means the user is registered, otherwise it's a device id)
- isFirst: true if this is the user's first ping ever (some users have been using the app before February)
- utmSource: traffic source from which the user came

The dates are based on Pacific time. So, for example, the minimum timestamp corresponds to midnight February 1st in Pacific time, not GMT.

**Tasks:**
- Show the daily active users over the month, including all users. A user is considered active if they pinged at least once on a given day.
- Calculate the daily retention curve for users who used the app for the first time on the following dates: Feb 4th, Feb 10th, and Feb 14th. Also, show the number of users from each cohort.
    - Daily retention curve is defined as the % of users from the cohort, who used the product that day.
- Determine if there are any differences in usage based on where the users came from. From which traffic source does the app get its best users? Its worst users?

