# nosql-challenge
Module 12 Challenge

#########################################################################################################################################################3

Which establishments have a hygiene score equal to 20?
Based on the provided information, The Chase Rest Home located at 5-6 Southfields Road, Eastbourne, East Sussex has a hygiene score of 20. Here's a summary of the relevant details:
	• Business Name: The Chase Rest Home
	• Business Type: Caring Premises
	• Address: 5-6 Southfields Road, Eastbourne, East Sussex, BN21 1BU
	• Local Authority: Eastbourne
	• Hygiene Score: 20 (highest rating)
	• Confidence in Management: 20
	• Structural Score: 20
	• Rating Date: 23rd September 2021
This establishment has received a hygiene score of 20, indicating top-level hygiene standards. If you're looking for additional establishments with the same score, you'd need to provide more data or search for other businesses with the same rating.

########################################################################################################333
Which establishments in London have a RatingValue greater than or equal to 4?

Based on the data you provided:
	• Business Name: Charlie's
	• Business Type: Other catering premises
	• Address: Oak Apple Farm Building 103 Sheernes Docks, Sheppy Kent, ME12
	• Local Authority: City of London Corporation
	• RatingValue: 4
	• Rating Date: 18th October 2021
This establishment fits the query because its LocalAuthorityName ("City of London Corporation") includes "London", and its RatingValue is 4.
If you have more establishments to check, you can run this query against your full dataset to retrieve all businesses in London with a rating of 4 or higher.

##############################################################################################################################################33




What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

Sorted by Hygiene Score (lowest first):
Since all the selected establishments have a Hygiene score of 0, we will sort them by distance from the new restaurant.
Top 5 establishments by proximity to "Penang Flavours":
	1. Volunteer (Plumstead High Street, Greenwich)
		○ Hygiene Score: 0
		○ Distance: 4646.97 meters
	2. Atlantic Fish Bar (Lakedale Road, Greenwich)
		○ Hygiene Score: 0
		○ Distance: 4646.97 meters
	3. Plumstead Manor Nursery (Old Mill Road, Greenwich)
		○ Hygiene Score: 0
		○ Distance: 4646.97 meters
	4. Iceland (Plumstead High Street, Greenwich)
		○ Hygiene Score: 0
		○ Distance: 4646.95 meters
	5. Howe and Co Fish and Chips - Van 17 (Plumstead High Street, Greenwich)
		○ Hygiene Score: 0
		○ Distance: 4646.96 meters
Since they all have the same hygiene score (0), the distance from the new restaurant was used to order them.
Conclusion:
The establishments above are the 5 nearest businesses to Penang Flavours, all with a RatingValue of 5 and the same hygiene score. They are all located in the same general area in Plumstead, Greenwich.

###############################################################################################################################################################################################################3

How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
• Thanet has the highest count of establishments with a hygiene score of 0, with 1130 such establishments.
• Greenwich is second with 882 establishments.
• The top ten results are sorted from the highest to the lowest count of establishments with a hygiene score of 0.
This query will provide you with the top ten Local Authority areas based on the number of establishments that have a hygiene score of 0.
