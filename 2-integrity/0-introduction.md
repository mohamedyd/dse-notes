# Data Integrity
Data integrity is about protecting data against improper maintenance, modification, or alteration. Integrity has to do with the accuracy of information, including its authenticity and trustworthiness. Information with low integrity concerns may be considered unimportant to precise operational functions or not necessary to vigorously check for errors. Information with high integrity concerns is considered critical and must be accurate in order to prevent negative impact on University activities.

## Threat Models
The first question that we should ask is "why might our data be wrong?". There are three main considerations.

Type of corruption:
- Bit-level corruption: errors in the underlying storage or software system lead to incorrect interpretation of the data. (e.g., a faulty hardrive causes a TRUE Boolean to be interpreted as FALSE.)
- Databse-level corruption: values are incorrect because they were entered into the system incorrectly due to human or software error.

Threat model:
- Random: data are incorrect largely due to random chance (e.g., device failures)
- Intentional: data are incorrect due to deliberate manipulation.

Definition of incorrect:
- Exact: data must exactly match some reference value. 
- Syntactic: data must conform to some general format constraint or data type constraint.
- Semantic: data must preserve some certain relationships.

## Cost of Faulty Data
Data that businesses employ could come from anywhere, and support key business decisions. 
Ride-hailing apps will purchase location data on a regular basis to ensure their maps are up-to-date and accurate; marketing firms will purchase location data on consumer travel patterns allowing them to sell out-of-home advertising space; and a new healthcare start-up will purchase data on health patterns and trends, to provide some examples. While it is hard to accurately pin down the cost of faulty data, numerous industry surveys have tried to assess the impact that faulty data can have on an organization. Gartner suggest that bad data is estimated to cost the US more than $3 trillion per year. 
