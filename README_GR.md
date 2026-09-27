# Ordinox Desk

[English](README.md) · [Ελληνικά](README_GR.md)

**Local-first εφαρμογή Windows για διαχείριση πελατών και καθημερινή οργάνωση μικρών επιχειρήσεων.**

Το Ordinox Desk είναι desktop εφαρμογή για Windows, σχεδιασμένη ώστε να βοηθά μικρές επιχειρήσεις να διαχειρίζονται πελάτες, ραντεβού, υπηρεσίες, έσοδα, υπενθυμίσεις και καθημερινές επαγγελματικές ροές από ένα ενιαίο περιβάλλον.

Το project ξεκίνησε ως αρχική ιδέα και εξελίχθηκε σταδιακά σε λειτουργική desktop εφαρμογή, με έμφαση στην ευχρηστία, την οργανωμένη διαχείριση δεδομένων, την αξιοπιστία και την πρακτική καθημερινή χρήση.

Η εφαρμογή είναι σχεδιασμένη για **Windows PCs και Windows tablets** και μπορεί να διατίθεται με **Αγγλικό και Ελληνικό περιβάλλον**.

---

## Tech Stack

- **Tauri 2** — desktop framework και Windows packaging
- **Vanilla JavaScript** — λογική εφαρμογής και state management
- **HTML5** — δομή εφαρμογής
- **CSS3** — custom interface και desktop layout
- **WebView localStorage** — τοπική αποθήκευση δεδομένων
- **JSON** — backup και import/export δεδομένων
- **Windows desktop packaging** — standalone εφαρμογή και installer

Το Ordinox Desk είναι **local-first εφαρμογή**.

Η βασική επιχειρησιακή λογική υλοποιείται σε JavaScript, ενώ το Tauri παρέχει το native Windows application shell και το packaging layer.

Για την κανονική λειτουργία δεν απαιτείται remote backend ή εξωτερικός database server.

---

## Παρουσίαση εφαρμογής

### Ημερολόγιο & Ραντεβού

![Ordinox Desk Calendar](assets/screenshots/calendar.png)

Η εφαρμογή περιλαμβάνει ολοκληρωμένη ροή διαχείρισης ραντεβού με:

- Δημιουργία νέου ραντεβού
- Διαχείριση ημερομηνίας και ώρας
- Στοιχεία πελάτη
- Επιλογή υπηρεσίας
- Παρακολούθηση τιμής
- Σημειώσεις
- Αναζήτηση ραντεβού
- Επερχόμενα ραντεβού
- Πλοήγηση μέσω ημερολογίου
- Διαχείριση κατάστασης ραντεβού

---

### Διαχείριση Πελατών

![Ordinox Desk Clients](assets/screenshots/clients.png)

Το Ordinox Desk περιλαμβάνει οργανωμένο σύστημα πελατολογίου για γρήγορη πρόσβαση σε πληροφορίες πελατών και σχετική επαγγελματική δραστηριότητα.

Περιλαμβάνει:

- Δημιουργία νέου πελάτη
- Επεξεργασία στοιχείων
- Αναζήτηση πελατών
- Οργανωμένη λίστα πελατών
- Πληροφορίες σχετικές με τον πελάτη
- Πρόσβαση σε προηγούμενη δραστηριότητα
- Γρήγορη πρόσβαση σε σχετικές ενέργειες και αρχεία

---

### Στοιχεία Πελάτη

![Ordinox Desk Client Details](assets/screenshots/client-details.png)

Κάθε πελάτης μπορεί να διαθέτει ξεχωριστό οργανωμένο αρχείο με χρήσιμες πληροφορίες και ιστορικό.

Στόχος είναι οι βασικές πληροφορίες να βρίσκονται συγκεντρωμένες σε ένα σημείο, χωρίς ανάγκη για διαφορετικές εφαρμογές, έγγραφα ή spreadsheets.

---

### Διαχείριση Εσόδων

![Ordinox Desk Revenue](assets/screenshots/revenue.png)

Η εφαρμογή περιλαμβάνει εργαλεία οργάνωσης και επισκόπησης πληροφοριών σχετικών με τα έσοδα.

Παρέχει πρακτική εικόνα των οικονομικών στοιχείων που συνδέονται με ραντεβού, υπηρεσίες και επιχειρησιακή δραστηριότητα.

---

### Υπενθυμίσεις

![Ordinox Desk Reminders](assets/screenshots/reminders.png)

Ένα ξεχωριστό σύστημα υπενθυμίσεων βοηθά τον χρήστη να παρακολουθεί σημαντικές εργασίες και υποχρεώσεις μέσα στην ίδια εφαρμογή.

Έτσι οι επαγγελματικές υπενθυμίσεις παραμένουν συνδεδεμένες με την υπόλοιπη καθημερινή ροή.

---

### Υπηρεσίες

Το Ordinox Desk επιτρέπει την οργάνωση συχνά χρησιμοποιούμενων υπηρεσιών ώστε να μπορούν να επαναχρησιμοποιούνται στα ραντεβού και στις σχετικές ροές.

Αυτό μειώνει την επαναλαμβανόμενη καταχώριση και βοηθά στη διατήρηση συνεπών πληροφοριών.

---

### Backup & Import

![Ordinox Desk Backup and Import](assets/screenshots/backup-import.png)

Η φορητότητα και η ανάκτηση δεδομένων αποτέλεσαν σημαντικό μέρος του project.

Η εφαρμογή περιλαμβάνει:

- Backup δεδομένων
- JSON export
- Data import
- Validation και normalization εισαγόμενων δεδομένων
- Ανάκτηση αποθηκευμένων πληροφοριών
- Προστασία από μη έγκυρα ή απρόσμενα imported data

Τα δεδομένα εργασίας αποθηκεύονται τοπικά, ώστε η εφαρμογή να λειτουργεί κανονικά χωρίς remote server.

---

## Windows Desktop Application

Το Ordinox Desk λειτουργεί ως standalone Windows desktop εφαρμογή μέσω **Tauri 2**.

Το project περιλαμβάνει ρυθμίσεις για:

- Native Windows execution
- Application identity και branding
- Application icons
- Release builds
- Windows packaging
- Installer generation

Το interface και η βασική λογική υλοποιούνται με HTML, CSS και Vanilla JavaScript, ενώ το Tauri παρέχει το native desktop runtime και το packaging environment.

Έτσι η εφαρμογή εγκαθίσταται και χρησιμοποιείται σαν κανονικό πρόγραμμα Windows.

---

## Local-First Αρχιτεκτονική

Το Ordinox Desk είναι σχεδιασμένο για τοπική λειτουργία στον υπολογιστή του χρήστη.

Για την κανονική χρήση:

- Δεν απαιτείται remote backend
- Δεν απαιτείται εξωτερικός database server
- Τα δεδομένα αποθηκεύονται τοπικά
- Ο χρήστης μπορεί να δημιουργεί backup αρχεία
- Υπάρχει δυνατότητα restore/import των αποθηκευμένων δεδομένων
- Δεν απαιτείται συνεχής σύνδεση στο Internet

---

## Προσέγγιση Ανάπτυξης

Το Ordinox Desk αναπτύχθηκε σταδιακά και όχι μέσα από μεγάλα one-time rewrites.

Η διαδικασία ανάπτυξης περιλαμβάνει:

1. Κατανόηση της υπάρχουσας συμπεριφοράς
2. Σχεδιασμό της απαιτούμενης λειτουργίας ή διόρθωσης
3. Υλοποίηση της μικρότερης κατάλληλης αλλαγής
4. Έλεγχο του επηρεαζόμενου κώδικα
5. Εκτέλεση και δοκιμή της εφαρμογής
6. Έλεγχο για regressions
7. Βελτίωση του interface όπου χρειάζεται
8. Αποφυγή άσχετων αλλαγών

---

## AI-Assisted Development

Η χρήση AI-assisted development εργαλείων αποτελεί μέρος του workflow μου, ιδιαίτερα μέσω **OpenAI Codex**.

Τα εργαλεία AI χρησιμοποιούνται για:

- Ανάλυση υπάρχοντος κώδικα
- Υλοποίηση λειτουργιών
- Debugging
- Εντοπισμό πιθανών προβλημάτων
- Code refinement
- Διερεύνηση εναλλακτικών υλοποιήσεων
- Έλεγχο πιθανών επιπτώσεων μιας αλλαγής
- Υποστήριξη testing και validation

Οι αλλαγές που προτείνονται από AI δεν εφαρμόζονται μηχανικά. Ελέγχονται και δοκιμάζονται σταδιακά, με έμφαση στη διατήρηση της υπάρχουσας λειτουργικότητας.

---

## Διαχείριση Δεδομένων & Αξιοπιστία

Καθώς η εφαρμογή εξελίχθηκε, δόθηκε ιδιαίτερη προσοχή στην ασφαλή και προβλέψιμη διαχείριση τοπικών δεδομένων.

Το project περιλαμβάνει μηχανισμούς για:

- Input validation
- Data normalization
- Backup και import workflows
- Recovery από malformed stored data
- Ασφαλέστερο rendering user-controlled values
- CSV-compatible data handling
- Rollback behavior όπου απαιτείται

---

## Τι αποκόμισα από το project

Η ανάπτυξη του Ordinox Desk μου έδωσε πρακτική εμπειρία σε:

- Ανάπτυξη πλήρους desktop εφαρμογής
- Σχεδιασμό application workflows
- Διαχείριση πελατών και επιχειρησιακών δεδομένων
- Application state management
- Local data persistence
- HTML, CSS και Vanilla JavaScript
- UI/UX design και refinement
- Debugging και troubleshooting
- Feature implementation
- Regression checking
- Data validation
- Backup και recovery workflows
- Tauri configuration
- Windows packaging και installers
- Iterative product development
- AI-assisted software development

---

## Δομή Project

Η εφαρμογή χρησιμοποιεί web-based frontend μέσα σε Tauri desktop environment.

Η βασική δομή περιλαμβάνει:

- HTML για τη δομή της εφαρμογής
- CSS για το custom interface
- JavaScript για business logic, state και user interactions
- Tauri configuration για το native desktop περιβάλλον
- Rust/Tauri bootstrap code για το desktop shell
- Local storage και JSON-based backup workflows

Η πλειονότητα της business logic υλοποιείται σε JavaScript.

---

## Test Data & Privacy

Όλα τα ονόματα, τηλέφωνα, ραντεβού και λοιπά προσωπικά στοιχεία που εμφανίζονται στα screenshots είναι **φανταστικά demo/test δεδομένα**.

Δεν αντιστοιχούν σε πραγματικούς πελάτες ή πρόσωπα.

Δεν περιλαμβάνονται πραγματικά δεδομένα πελατών σε αυτό το portfolio repository.

---

## Source Code

Ο πλήρης production source code του Ordinox Desk διατηρείται ιδιωτικός.

Αυτό το repository λειτουργεί ως **project showcase και portfolio παρουσίαση**, με documentation και οπτικό υλικό της εφαρμογής.

Ο πλήρης πηγαίος κώδικας δεν περιλαμβάνεται στο public showcase repository.

---

## Κατάσταση Project

**Ενεργό προσωπικό software project.**

Το Ordinox Desk είναι λειτουργική Windows desktop εφαρμογή και συνεχίζει να εξελίσσεται με επιπλέον δυνατότητες, διορθώσεις και βελτιώσεις χρηστικότητας.
