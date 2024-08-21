
The objective of this script was to extract a comprehensive list of USA Olympians fromn the Team USA website. The process involved several challenges:

1. Pagination and Ads: Initially, the table displayed only 10 Olympians along with an ad and a "View More Athletes" button. Clicking this button revealed 10 additional athletes along with another ad and button. With a over 590 Olympians to retrieve, the script needed to repeatedly click the "View More Athletes" button to load all entries.

2. Pop up Interference: a pop-up ad obscured the "View More Athletes" button, requiring the script to handle this distraction.

3. Table Structure: Each row in the Olympian table contained a nested header with additional information. The script had to extract the Olympian names from these nested headers and then combine this information with the rest of the data for each olympian.

Overall, the script efficiently navigates through dynamic content and handles complex table structures to compile a complete list of athletes.
