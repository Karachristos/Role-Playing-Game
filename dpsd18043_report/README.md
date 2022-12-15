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
Ο ήρωας ξεκινάει τη περιπέτεια του σε κελί ενός μπουντρουμιού. 
Τα κάγκελα της πόρτας είναι ήδη σπασμένα χωρίς εκείνος να ξέρει ακόμα πως έσπασαν.
Σκοπός του είναι να επιβιώσει μέσα στο μπουντρούμι καθώς ψάχνει το δρόμο για την ελευθερία,
ανακαλύπτοντας στη πορεία το πως βρέθηκε στο μπουντρούμι εξ'αρχής.


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
 
 Για το 2ο παραδοτέο εμπλούτισα τη πρώτη πίστα του παιχνιδιού και πρόσθεσα διάφορα props μαζί με τους απαραίτητους colliders έτσι ώστε η πίστα να
 θυμίζει και να μοιάζει περισσότερο με ένα μπουντρούμι.
 
 
 ![1η πίστα](https://user-images.githubusercontent.com/117390085/207917856-d11b4944-9a8c-433e-a497-21c8a3e8174a.PNG)
 ![1η πίστα_2](https://user-images.githubusercontent.com/117390085/207917893-3590986f-d633-4ff0-ae80-41c2e5138ee2.PNG)
 ![1η πιστα_3](https://user-images.githubusercontent.com/117390085/207917903-1b72ea02-d9e1-463f-b677-8d2c5c0f94df.PNG)
 
 
 Επιπλέον άλλαξα το main ήρωα και έβαλα άλλον ο οποίος ταιριάζει περισσότερο με το στυλ του παιχνιδιού.
 (πιθανότατα να αλλάξει πάλι μελλοντικά)
 
 
 ![2ndcharacter](https://user-images.githubusercontent.com/117390085/207928350-60f3dc99-4f96-479f-8b5e-33e970275796.PNG)

 
 
 Στη συνέχεια, αφού του έδωσα πόντους ζωής, δημιούργησα coolectible potions τα οποία εκείνος μπορεί να πάρει μονάχα αν οι πόντοι ζωής του δεν είναι γεμάτοι.
 Τα potions αναπληρώνουν 1 πόντο ζωής το καθένα, είναι διασκορπιζμένα στο χάρτη με μερικά από αυτά να είναι πιο δύσκολα αποκτήσιμα από άλλα και εξαφανίζονται μετά τη χρήση. Ο ήρωας τα αγνοεί αν οι πόντοι ζωής του είναι γεμάτοι.
 
![healthpot](https://user-images.githubusercontent.com/117390085/207926673-2ad6a514-42b9-4e5e-9286-0bb66e0c4782.PNG)


Στη συνέχεια όρισα ως damage zones καρφία στο πάτωμα τα οποία εκτείνονται σε όλη τη πίστα. Στη πίστα επίσης, υπάρχουν και wall mounted καρφιά τα οποία μπορούν να τραυματίσουν τον ήρωα καθώς και sawblades στα οποία θα προσθεθεί κίνηση μελλοντικά.
Τα swablades, τα καρφιά στο πάτωμα και στο τοίχο έχουν ακριβή colliders και θα τραυματίσουν το χαρακτήρα για 1 πόντο ζωής αν εκείνος έρθει σε επαφή με οποιοδήποτε από αυτά. Ο ήρωας έχει invincibility frames και μπορεί να τρυματίζεται κάθε 2 δευτερόλεπτα από τη στιγμή που τραυματίζεται αρχικά.

Sawblade

![sawblade](https://user-images.githubusercontent.com/117390085/207930857-65912576-40ab-4623-b81c-83ff0ae5c077.PNG)

Wall mounted spikes

![wallmounted](https://user-images.githubusercontent.com/117390085/207930922-f63ace40-83a0-4584-a0ed-43abe2231fb8.PNG)

Floor Spikes

![stopatwma](https://user-images.githubusercontent.com/117390085/207930963-297611a5-96b6-4fa1-acb1-4ba8c71a4043.PNG)


Μετά πρόσθεσα και τους εχθρούς του παιχνιδιού, τους ποντικάνθρωπους. Η επαφή του ήρωα με αυτούς επίσης των τραυματίζει για 1 πόντο ζωής

Axe rat

![axerat](https://user-images.githubusercontent.com/117390085/207932871-87e1e26d-9d62-4766-941a-86ae7f55c1d9.PNG)

Mage rat

![magerat](https://user-images.githubusercontent.com/117390085/207932897-0bd3e2f7-c7e2-4b47-9040-590884280977.PNG)



# 3rd Deliverable 



# Conclusions


# Sources
-Ruby's adventure unity course: https://learn.unity.com/project/ruby-s-2d-rpg 

-Assets που χρησιμοποιήθηκαν: https://game-endeavor.itch.io/mystic-woods (χαρακτήρας) , https://anokolisa.itch.io/crawler-dungeon-prison (χάρτης)
