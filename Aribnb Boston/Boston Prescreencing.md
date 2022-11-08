# Boston Airbnb Data Exploation and Strategy outline

## Research Problem
What can hosts do to improve their property occupancy per month?

## Research Significance
Being a respected Airbnb host has emotional and financial benefits. Emotionally, good hosts enjoy meeting new people, learn about different ways of lives, and make new friends. Financially, good hosts means a boost in income, including higher overnight prices for room listings, higher booking frequencies, and longer stays. Therefore, aside from financial earnings through hosting properties on Airbnb, hosts derive sense of accomplishment by improve their ways of managing their listings. 

To be a better host, a host may be interested in what they are doing well, and what they need to improve through look into their customers' ratings and reviews on their various properties. If there is a model to tell them what areas they can improve on and by how many days of stay can the a change bring to them, they are able to make decision based on concrete open data, and they can less rely on personal experience. This means less financial and time cost of trying different host strategies, higher occupancy rate means more revenue and more stability in revenue. Beisdes, higher and more consistent occupancy means affection shown by customers, which brings invaluable emotional values to the hosts.

## Assumptions
Actions hosts performed correlate with occupancy rate; 
past review scores correlate with occupancy rate;
seasons in a year affect customer and host behaviour, and possibly has some effect;

### Calendar Factors
* Move-in date matters

### Listing Data
* Key words used in sumamry, description, neighborhood overview affects customers' first impressions, and thus affect occupancy rate
* Space description affects customer expectation of size of the room
* Host location affects convenience (most are in Boston, don't consider this)
* Access means what rooms, facility guests can access, it affects
* Interaction means how hosts prefer to interact with guests--never speaking, or answer questions, respond to needs, or create memory together. It affects
* Host_since measures a host's experience. More experienced hosts should have high occupancy rate.
* Host about reveals the hosts' occupation, age, and hobbies. This helps customers to relate. And the overall tone affect customers' choices.
* Host reponse rate and time affect communication and first impression online. Take them into account.
* Host neighhood indicates geosptatial distribution, it affects since guests prefer proximity
* Host street number has the similar effect, keep it for more accuracy geospatial representation
* Host verification matters because theose with government id verified are more trustworthy
* Host has profile photo demonstrate trust and create first impression
* Property type and room type may not be something that hosts can directly act on, but they can learn about the contribution of these factors
* The # bedrooms, beds, and bathrooms affects the # of people can be accommodated
* Amenities covers some inelastic needs such as internet, AC, heating, smoke detector, etc. They affect customers' comfortness. Elastic needs such as breakfast, pets allowed are bonus
* Price affects guests' willingness to pay for the stay
* The cumulative number of reviews affects credibility of information
* Calculated host listing count measures a host's experience, and possibly chances to interact with guests

### Review Comments
* Culture (i.e Islam)
* Location
* Friendiness
* Cleaniness
* Accuracy

## Design
* **Observation**: one property listing
* **Variates**: 
* **Measurement**:
    * Occupancy rate = 30 - # of days in 30 day period that the property is available
    * 
