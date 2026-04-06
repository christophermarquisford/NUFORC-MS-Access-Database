Microsoft Access database created using 2018 NUFORC data.

The NUFORC table I downloaded was a bit messy (I can't remember where I got it since this was several years ago, but maybe Kaggle?), so I wrote a few queries and modules to delete mostly blank records and include state/province/country abbreviation as appropriate.

Database sections include:
NUFORC
	Contains a cleaned up NUFORC table
Internal Trackers
	Includes tables for abbreviation updates, as well as a table showing frequency by date to allow notes about said date
Frequency Queries
	Various COUNT aggregate queries I thought were interesting
Simple Sorts
	Simple queries
Data Detergent
	Queries/modules/macros which update tables.
		(I wanted to come up with more complex modules so I could practice Access VBA, but I couldn't come up with a good reason to do so.  Maybe if I want to append records from updated NUFORC tables, although even then I can prbably do that just with SQL.)
Unassigned Objects
	I added a BFRO table and planned to do comparative queries but got sidetracked away from this project at that point and never came back T.T
	
Since it was a personal project, I had fun with naming some of the elements of the database.