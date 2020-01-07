# Air-Quality-Analyzer
     Ένα από τα μεγαλύτερα προβλήματα των μεγάλων αστικών περιοχών είναι η ατμοσφαιρική ρύπανση. Με τον όρο ατμοσφαιρική ρύπανση, εννοούμε την προσθήκη ουσιών στην ατμόσφαιρα, που υπό φυσιολογικές συνθήκες δε θα υπήρχαν. Πολλές από αυτές τις ουσίες είναι βλαβερές όχι μόνο για τον ανθρώπινο, αλλά και για πολλούς άλλους ζωντανούς οργανισμούς. Τα αποτελέσματα της έκθεσή τους στους ρύπους αυτούς λειτουργούν αθροιστικά σε αυτούς. Όσο μεγαλύτερη είναι η έκθεση σε αυτές, τόσο μεγαλύτερες και οι βλάβες που μπορεί να προκληθούν. Διαπιστώθηκε επίσης ότι η συχνότητα εμφάνισης έντονου θερμικού στρες είναι στην Αθήνα δύο έως τρεις φορές μεγαλύτερη από τα τέλη της δεκαετίας του 1990 και μετά, σε σχέση με τις προηγούμενες δεκαετίες.
     Στόχος του έργου μας, είναι να κάνουμε μια μελέτη σύγκρισης της ποιότητας του αέρα σε σχολικές μονάδες. Η ανάλυση των δεδομένων που θα συλλέξουμε, έχει πρωταρχικό στόχο την κατάταξη των σχολείων αυτών ως προς την ατμοσφαιρική ρύπανση και τη θερμική δυσφορία που είναι πιθανό κανείς να βιώσει, ώστε να μπορούμε εύκολα να αναγνωρίζουμε τα πιο ανθυγιεινά σχολικά περιβάλλοντα, αρχικά για την ενημέρωση και στη συνέχεια για την εύρεση τρόπων βελτίωσής τους. Έτσι, θα μπορούμε να προστατεύσουμε τις ευπαθείς ομάδες παρέχοντάς τες αναλυτικές πληροφορίες για την ποιότητα του αέρα ενός χώρου.
     Η ατμοσφαιρική ρύπανση που οφείλεται σε ανθρωπογενείς πηγές, αποτελεί ένα σημαντικό περιβαλλοντικό πρόβλημα, με επιπτώσεις στην υγεία. Το διοξείδιο του αζώτου, το τροποσφαιρικό όζον και ιδιαίτερα τα αιωρούμενα σωματίδια που είναι αποτέλεσμα της καύσης βιομάζας και ορυκτών καυσίμων, ιδιαίτερα από τα νοικοκυριά όταν έχουμε χαμηλές θερμοκρασίες, αναγνωρίζονται ως κάποιους από τους σημαντικότερους ρύπους από την άποψη των επιπτώσεων για την υγεία. Για τις μετρήσεις που θα διεξάγουμε, θα τοποθετηθούν αισθητήρες μέτρησης των κυριότερων αυτών δεικτών σε διάφορα σχολεία της πόλης μας, της Θεσσαλονίκης και στη συνέχεια θα αποθηκεύονται σε μία βάση δεδομένων για ανάλυση.
     Εάν γίνει μια κατάταξη των σχολείων σύμφωνα με τους δείκτες ποιότητας του αέρα που εισπνέουμε, θα δημοσιεύσουμε τις μετρήσεις ώστε να βοηθήσουμε την πολιτεία να πάρει μέτρα - όπου χρειάζεται,  για τη βελτίωση τους. 
     Με το έργο μας ευελπιστούμε να τοποθετηθούν σε κάθε σχολείο και οπουδήποτε αλλού κριθεί αναγκαίο για την προστασία των ευπαθών ομάδων, οι συγκεκριμένοι σταθμοί μέτρησης που θα υλοποιήσουμε, ώστε να υπάρχει συνεχής παρακολούθηση του επιπέδου ρύπανσης της ατμόσφαιρας.


**Τα υλικά που χρησιμοποιήσαμε:**

 * Για την κατασκευή του μετρητή:
   * Raspberry Pi 3 -- 41,47€
   * DHT11 Humidity sensor -- 4,81€
   * Particulate Sensor SDS011 -- 22,53€
   
 * Για την κατασκευή του Server και της βάσης δεδομένων:
   * Raspberry pi 4 -- 55,88€
  
Το λογισμικό που χρησιμοποιήσαμε:
  * Apache
  * MariaDB (MySQL)


Κατάσταση ποιότητας αέρα  Τιμές δείκτη ποιότητας αέρα
Καλή                       0-10
Ικανοποιητική             10-20
Μέτρια                    20-25
Κακή                      25-50
Πολύ-κακή                 50+
