# tickets-analysis-powerbi-r

Project combining R analysis and Power BI visualizations for ticket data.

## Περιεχόμενα

- `/data` : Αρχείο dataset με τα αρχικά δεδομένα.
- `/R_scripts` : R scripts για προεπεξεργασία, text mining και ανάλυση.
- `/PowerBI` : Power BI dashboard αρχείο (.pbix) με interactive visualizations.
- `/docs` : Επιπλέον documentation, screenshots, και οδηγίες.

## Περιγραφή

Αυτό το project συνδυάζει ανάλυση δεδομένων και text mining σε R με τη δημιουργία διαδραστικών dashboards στο Power BI.  
Στόχος είναι να αναλυθούν τα tickets υποστήριξης με βάση προτεραιότητα, τύπο, γλώσσα και άλλα χαρακτηριστικά, και να παρουσιαστούν εύκολα τα insights.

## Οδηγίες χρήσης

### R scripts

1. Ανοίξτε το RStudio ή τρέξτε τα scripts στο R.
2. Εγκαταστήστε τις απαραίτητες βιβλιοθήκες, π.χ.:

```r
install.packages(c("tidyverse", "tm", "wordcloud", "cluster"))

