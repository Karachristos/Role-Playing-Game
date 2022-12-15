# Lesson: Digital & Serious Games

### First and Last Name: Νικόλας Καραχρήστος	
### University Registration Number: dpsd18043
### GitHub Personal Profile: https://github.com/Karachristos
### Digital & Serious Games Personal Repository: https://karachristos.github.io/Role-Playing-Game/

# Introduction

Εργασία εξαμήνου για το μάθημα "Ψηφιακά παιχνίδια και παιγνιώδης μάθηση".

Εξάμηνο: 9o

Διδάσκων: Αλέξανδρος Μερκούρης

# Summary

Δημιουργία 2d top down role playing παιχνιδιού με χρήση unity.
Το παιχνίδι βασίζεται στο template/course της unity ονόματι ruby's adventure. 
https://learn.unity.com/project/ruby-s-2d-rpg

*plot subject to change*
Ο ήρωας ξεκινάει τη περιπέτεια του αναίσθητος σε ένα κελί ενός μπουντρουμιού. 
Το μόνο που θυμάται είναι πως ήταν ληστής του οποίου η τελευταία ληστεία δεν πήγε καλά.
Βρίσκοντας τις αισθήσεις του συνειδητοποιεί πως όλοι οι ανθρώποι του μπουντρουμιού έχουν εξαφανιστεί και τα μόνα πλάσματα που τριγυρνούν σε αυτό είναι οπλοισμένοι ποντικοί.
Σκοπός του είναι να επιβιώσει μέσα στο μπουντρούμι καθώς ψάχνει το δρόμο για την ελευθερία,
ανακαλύπτοντας στη πορεία το τι έγινε όσο εκείνος ήταν αναίσθητος.


# 1st Deliverable

Δημιουργία πρώτου χάρτη και διακόσμηση του με διάφορα objects.

Aντικατάσταση της Ruby με κατάλληλο για το plot playable χαρακτήρα (ο οποίος ίσως να αλλάξει στη συνέχεια).
Ο χαρακτήρας μπορεί να κινείται ελεύθερα στο χάρτη.

Ο χάρτης και ο χαρακτήρας δημιουργήθηκαν από έτοιμα assets που βρέθηκαν στο itch.io

Χάρτης:

![Map_prwtou_paradoteou](https://user-images.githubusercontent.com/117390085/202004835-0b1cd3f7-e13b-40c4-bbb4-fa46b7e80bd8.PNG)

Χαρακτήρας:

![arxikos_xarakthras](https://user-images.githubusercontent.com/117390085/201998603-7827f72a-c708-4c89-b0f9-f7e46d007f68.PNG)

Κώδικας μέχρι στιγμής:

![κωδικας](https://user-images.githubusercontent.com/117390085/201998691-1f23b24b-24e1-4300-84b4-d2b9ff1b4b77.PNG)

# 2nd Deliverable
 
 Για το 2ο παραδοτέο εμπλούτισα τη πρώτη πίστα του παιχνιδιού και πρόσθεσα διάφορα props μαζί με τους απαραίτητους colliders έτσι ώστε η πίστα να μοιάζει περισσότερο με ένα μπουντρούμι.
 
 
 ![1η πίστα](https://user-images.githubusercontent.com/117390085/207917856-d11b4944-9a8c-433e-a497-21c8a3e8174a.PNG)
 ![1η πίστα_2](https://user-images.githubusercontent.com/117390085/207917893-3590986f-d633-4ff0-ae80-41c2e5138ee2.PNG)
 ![1η πιστα_3](https://user-images.githubusercontent.com/117390085/207917903-1b72ea02-d9e1-463f-b677-8d2c5c0f94df.PNG)
 
 
 Επιπλέον άλλαξα το main ήρωα και έβαλα άλλον ο οποίος ταιριάζει περισσότερο με το στυλ του παιχνιδιού.
 (πιθανότατα να αλλάξει πάλι μελλοντικά)
 
 
 ![2ndcharacter](https://user-images.githubusercontent.com/117390085/207928350-60f3dc99-4f96-479f-8b5e-33e970275796.PNG)

 
 
 Στη συνέχεια, αφού του έδωσα πόντους ζωής, δημιούργησα collectible potions τα οποία εκείνος μπορεί να πάρει μονάχα αν οι πόντοι ζωής του δεν είναι γεμάτοι.
 Τα potions αναπληρώνουν 1 πόντο ζωής το καθένα, είναι διασκορπιζμένα στο χάρτη (με μερικά από αυτά να είναι πιο δύσκολα αποκτήσιμα από άλλα) και εξαφανίζονται μετά τη χρήση. Ο ήρωας τα αγνοεί αν οι πόντοι ζωής του είναι γεμάτοι.
 
![healthpot](https://user-images.githubusercontent.com/117390085/207926673-2ad6a514-42b9-4e5e-9286-0bb66e0c4782.PNG)


Στη συνέχεια όρισα ως damage zones καρφία στο πάτωμα τα οποία εκτείνονται σε όλη τη πίστα. Στη πίστα επίσης, υπάρχουν και wall mounted καρφιά τα οποία μπορούν να τραυματίσουν τον ήρωα καθώς και sawblades στα οποία θα προσθεθεί κίνηση μελλοντικά.
Τα swablades, τα καρφιά έχουν colliders και θα τραυματίσουν το χαρακτήρα για 1 πόντο ζωής αν εκείνος έρθει σε επαφή με οποιοδήποτε από αυτά. Ο ήρωας έχει invincibility frames και μπορεί να τρυματίζεται κάθε 2 δευτερόλεπτα από τη στιγμή που τραυματίζεται αρχικά. 

Sawblade

![sawblade](https://user-images.githubusercontent.com/117390085/207930857-65912576-40ab-4623-b81c-83ff0ae5c077.PNG)

Wall mounted spikes

![wallmounted](https://user-images.githubusercontent.com/117390085/207930922-f63ace40-83a0-4584-a0ed-43abe2231fb8.PNG)

Floor Spikes

![stopatwma](https://user-images.githubusercontent.com/117390085/207930963-297611a5-96b6-4fa1-acb1-4ba8c71a4043.PNG)


Μετά πρόσθεσα και τους εχθρούς του παιχνιδιού, τους ποντικάνθρωπους. Έχουν τη δυνατότητα να κοινούνται κατα μήκος του άξονα x ή του άξονα y, ανάλογα με το που θέλω να τους τοποθετήσω. Υπάρχει δυνατότητα διαμόρφωσης της ταχύτητας τους, καθώς και της στιγμή που εκείνοι θα αλλάξουν μεριά κίνησης. Η επαφή του ήρωα με αυτούς τoν τραυματίζει για 1 πόντο ζωής

Axe rat

![axerat](https://user-images.githubusercontent.com/117390085/207932871-87e1e26d-9d62-4766-941a-86ae7f55c1d9.PNG)

Mage rat

![magerat](https://user-images.githubusercontent.com/117390085/207932897-0bd3e2f7-c7e2-4b47-9040-590884280977.PNG)


Στη συνέχεια έκανα animate τον ήρωα αλλά και τους εχθρούς χρησιμοποιώντας τον animator της unity. Ο ήρωας έχει idle animations ανάλογα με το πιο πλήκτρο έχω πατήσει τελευταίο (IdleLeft αν το τελευταίο πατημένο πλήκτρο ήταν το A). Επίσης έχει διαφορετικά animations ανάλογα με το ποιά μεριά κινείται. Ωστόσο, επειδή τα assets του ήρωα είναι φτιαγμένα για sidescroller, δεν είχα animation sheets για up and down movement γι'αυτό και έβαλα στη θέση τους τα animations για left and right movement. (Όταν βρω κατάλληλο χαρακτήρα θα προσθεθεί και το σωστό up and down movement). O ήρωας παίζει επίσης ένα hit animation κάθε φορα που τραυματίζεται.

Το ίδιο έκανα και με του εχθρούς. Οι ποντικάνθρωποι τώρα έχουν movement animations αλλά και death animations.


Επιπρόσθετα, έκανα τον ήρωα να πετάει ένα projectile με το πλήκτρο C. Αν ο ήρωας πετύχει με το projectile οποιοδήποτε από τους ποντικούς ο ποντικός πεθαίνει.
Ο ήρωας τώρα παίζει attack animation κάθε φορά που πατιέται το πλήκτρο C και το projectile εκτοξεύεται ανάλογα με το direction στο οποίο κινείται εκείνος (αν μετακινείται προς τα πάνω το projectile εκτοξεύται προς τα πάνω). Αν το projectile χτυπήσει κάποιο άλλο object του παιχνιδιού, το projectile εξαφανίζεται.

Το projectile 

![Uploading projectile.PNG…]()

Τέλος, έφτιαξα και οριοθέτησα τη κάμερα (η οποία τώρα ακολουθεί τον ήρωα και δεν βγαίνει εκτός των "εξωτερικών" τοιχών του μπουντρουμιού) χρησιμοποιώντας το cinemachine της unity.

Ο κώδικας μέχρι στιγμής 

Player Controller

![player script1](https://user-images.githubusercontent.com/117390085/207944381-25129d18-b9a0-4a7b-8b95-b2a52f2a674b.PNG)
![player script2](https://user-images.githubusercontent.com/117390085/207944391-dba50ede-60e6-45a9-9873-a68a27db0c82.PNG)

Health Collectible

![collectible script](https://user-images.githubusercontent.com/117390085/207944441-103bb121-7f9c-40a2-8d1b-4274e8361c97.PNG)

Damage Zones

![damagezone script](https://user-images.githubusercontent.com/117390085/207944491-9ffdfb46-48ae-429e-b765-62db415734c7.PNG)

Enemy Controller

![enemy controller script1](https://user-images.githubusercontent.com/117390085/207944548-14f636c5-5ab4-465c-9740-8f776c364212.PNG)
![enemy controller script2](https://user-images.githubusercontent.com/117390085/207944562-140ff329-ab55-4619-a4b2-5b094a283be4.PNG)

Projectile

![projectile script](https://user-images.githubusercontent.com/117390085/207944610-cabfa29d-3c1a-41db-99fb-c28665da247c.PNG)


# 3rd Deliverable 



# Conclusions


# Sources
-Ruby's adventure unity course: https://learn.unity.com/project/ruby-s-2d-rpg 

-Assets που χρησιμοποιήθηκαν: 
https://game-endeavor.itch.io/mystic-woods (χαρακτήρας) 

https://anokolisa.itch.io/crawler-dungeon-prison (χάρτης)

https://elthen.itch.io/2d-pixel-art-ratfolk-mage-sprites (εχθρός)

https://elthen.itch.io/2d-pixel-art-ratfolk-axe-sprites (εχθρός)
