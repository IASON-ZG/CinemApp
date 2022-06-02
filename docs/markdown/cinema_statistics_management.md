# ΠΧ Διαχείριση μηνιαίων στατιστικών

**Πρωτεύον actor:** Ιδιοκτήτης

**Ενδιαφερόμενοι:** Ιδιοκτήτης: θέλει να δεί, να διαχειριστεί τα στατιστικά δεδομένα μιας τανίας.

**Προϋποθέσεις:** Ο ιδιοκτήτης έχει πραγματοποιήσει εγγραφή ιδιοκτήτη και ταυτοποιήση χρήστη.

## Βασική Ροή
#

### A) Download Στατιστικών
1. Το Σύστημα παρουσιάζει τις ταινίες αλφαβητικά σε μορφή λίστας.
2. Ο ιδιοκτήτης αναζητά την τανία που επιθυμεί.
3. Το Σύστημα εμφανίζει την επιλογή προβολής των μηναιάων στατιστικών στοιχείων της ταινίας.
4. Μετά την επιλογή του ιδιοκτήτη το σύστημα του εμφανίζει ημερολόγιο για την επιλογή του μήνα.
5. Ο ιδιοκτήτης επιλέγει τον μήνα που επιθυμεί.
6. Το Σύστημα παρουσιάζει τα δεδομένα.
7. Το Σύστημα εμφανίζει την επιλογή ο ιδιοκτήτης να κατεβάσει τα δεδομένα.
8. Ο ιδιοκτήτης επιλέγει να κατεβάσει τα δεδομένα.
9. Το Σύστημα στέλνει τα δεδομένα στον χρήστη.
10. Το σύστημα επιστρέφει στην αρχική οθόνη.

**Εναλλακτικές Ροές**

*2α. Η τανία δεν υπάρχει.*  
    1. Το σύστημα εμφανίζει μύνημα σφάλματος.  
    2. Η ΠΧ επιστρέφει στο βήμα 1 της βασικής ροής.

### Β) Διαγραφή Στατιστικών
1. Το Σύστημα παρουσιάζει τις ταινίες αλφαβητικά σε μορφή λίστας
2. Ο ιδιοκτήτης αναζητά την τανία που επιθυμεί.
3. Το Σύστημα εμφανίζει την επιλογή προβολής των μηναιάων στατιστικών στοιχείων της ταινίας.
4. Μετά την επιλογή του ιδιοκτήτη το σύστημα του εμφανίζει ημερολόγιο για την επιλογή του μήνα.
5. Ο ιδιοκτήτης επιλέγει τον μήνα που επιθυμεί.
6. Το Σύστημα ανακτά τα δεδομένα.
7. Το σύστημα παρουσιάζει τα δεδομένα.
8. Το Σύστημα εμφανίζει την επιλογή στον χρήστη να διαγράψει τα δεδομένα.
9. Ο ιδιοκτήτης επιλέγει να διαγράψει τα δεδομένα.
10. Το Σύστημα  εμφάνιζει στον ιδιοκτήτη μήνυμα να επαληθεύσει την επιλογή του.
11. Ο ιδιοκτήτης επαληθέυει την επιλογή του.
12. Το Σύστημα διαγράφει τα δεδομένα.
13. Το σύστημα επιστρέφει στην αρχική οθόνη.

**Εναλλακτικές Ροές**
    
*9α. Δεν υπάρχουν δεδομένα να διαγραφούν.*  
1. Το σύστημα εμφανίζει μήνυμα σφάλματος.  
2. Η ΠΧ τερματίζει.

*11α. Ο ιδιοκτήτης δεν αποδέχεται.*  
1. Η ΠΧ συνεχίζει στο βήμα 7 της βασικής ροής.