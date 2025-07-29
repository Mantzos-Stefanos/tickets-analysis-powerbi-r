# Tickets-analysis-powerbi-R

Project combining R analysis and Power BI visualizations for ticket data.

## Περιεχόμενα φακέλων

- [PowerBI_Project.pbix](./PowerBI_Project.pbix) : Το αρχείο του Power BI dashboard.
- [dataset-tickets-multi-lang-4-20k.csv](./dataset-tickets-multi-lang-4-20k.csv) : Το αρχικό dataset με τα tickets.
- [rpubs analysis](https://rpubs.com/StefanosMan/1332157) : Αναλυτική ανάλυση και preprocessing στο R.

- ## Screenshot από το Power BI Dashboard
- ![Power BI Dashboard](./powerbi_dashboard.png)





## Περιγραφή

Αυτό το project συνδυάζει ανάλυση δεδομένων και text mining σε R με τη δημιουργία διαδραστικών dashboards στο Power BI.  
Στόχος είναι να αναλυθούν τα tickets υποστήριξης με βάση προτεραιότητα, τύπο, γλώσσα και άλλα χαρακτηριστικά, και να παρουσιαστούν εύκολα τα insights.

## Οδηγίες χρήσης

### R scripts

1. Ανοίξτε το RStudio ή τρέξτε τα scripts στο R.
2. Εγκαταστήστε τις απαραίτητες βιβλιοθήκες, π.χ.:

```r
install.packages(c("tidyverse", "tm", "wordcloud", "cluster"))

