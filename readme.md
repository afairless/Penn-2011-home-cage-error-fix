HCerrorfix
Andrew Fairless, July 2011

This program/macro detects several kinds of possible errors in the home cage scoring.  It copies the original data from "Sheet1" (renamed "original data") to a new sheet ("fixed data").  It then reads the data from the sheet "fixed data", detects several errors and corrects a few of them on "fixed data", and then writes a table of the errors onto a new sheet ("error table").

Following is a list of the errors that this program detects.

Error #1:  All entries in the original data table should be marked with a "1" when the behavior is present and with a "" (a blank) when the behavior is absent.  Any other marks are counted as an error.

Error #2:  Each mouse at each time point can be engaged in a maximum of 1 social behavior.  If more than 1 social behavior is marked, it is counted as an error.

Error #3:  If a mouse at a particular time point is erroneously marked as engaging in more than 1 social behavior and if the mouse was marked as engaging in 1 active social behavior and 1 passive social behavior, then only the active behavior should be counted.  The mark for the passive behavior is eliminated.

Error #4:  Each mouse at each time point can be engaged in a maximum of 1 nonsocial behavior.  If more than 1 nonsocial behavior is marked, it is counted as an error.

Error #5:  After examination of the inter-rater reliability of the data, it was decided that "little dig" would not be counted as a behavior.  All "little digs" are changed to "N/A".

Error #6:  If one mouse is sniffing the other mouse's nose, then the other mouse must also be engaged in nose sniffing.  No other social behavior is possible.  If another behavior is marked, it is counted as an error.

Error #7:  Each mouse at each time point must have at least one mark, either a behavior or "N/A".  An absent mark is counted as an error
