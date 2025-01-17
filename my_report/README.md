# Lesson: Advanced Interaction Technologies & Applications

### First and Last Name: Paraskevi Xenoktistaki
### University Registration Number: DPSD19143
### GitHub Personal Profile: EvitaXen
### Advanced Interaction Tecnologies & Applications Github Personal Repository

# Introduction
O σκοπός της εργασίας ήταν να αναπτύξουμε διαδραστικές εφαρμογές κάνοντας χρήση προηγμένων τεχνικών αλληλεπίδρασης με χρήση της γλώσσας προγραμματισμού Processing, και με την χρήση kinect κάμερας.

# Summary
* Για πρώτο παραδοτέο, στο πρώτο ζητούμενο σύνδεσα το Prossessing με την κάμερα ώστε αυτή να καταγράφει βίντεο. Στο το δεύτερο, με ένα δικό μου μικρής διάρκειας βίντεο έφτιαξα τον κώδικα ώστε να παίζει σε επανάληψη, για το τρίτο ζητήθηκε το Processing να εμφανίζει εικόνα με το προσωπικό μου QRCode και όταν αναγνωρίζεται να ανοίγει το URL που είναι αποθηκευμένο σε αυτό, σε μια νέα ιστοσελίδα. Στο τέταρτο ζητούμενο η κάμερα έπρεπε να διαβάζει το QRCode και να ανοίγει το URL. Τέλος, έπρεπε από την κάμερα να γίνεται αναγνώριση του marker Hiro και να εμφανίζεται μια εικόνα ή ένα βίντεο.  
* Για το δεύτερο παραδοτέο κρέμασα ένα πράσινο πανί από πίσω μου και μέσω του Processing έγινε αφαίρεση του υπόβαθρου και αντικαταστήθηκε από μια εικόνα. Στο δεύτερο ζητούμενο, γινόταν εντοπισμός κίνησης με την κάμερα και ένα σχήμα ακολουθούσε ένα κινούμενο αντικείμενο. Για το τρίτο, μέσα από την κάμερα γινόταν εντοπισμός των κινούμενων αντικειμένων και μωβ γραμμές το ακολουθούσαν, ενώ για το τέταρτο γινόταν είσοδος από ένα αντικείμενο από την κάμερα και σχηματιζόταν ένα φιδάκι με βάση το χρώμα αυτού.
* Για το τρίτο παραδοτέο έφτιαξα μια εφαρμογή επεξεργασίας εικόνας φωτογραφιών (μεγέθυνση,αντίθεση,αφαίρεση χρώματος) που χρησιμοποιεί την κάμερα για την αναγνώριση και παρακολούθηση των κωδικών fiducials.Οι κωδικοί fiducials αντιπροσωπεύουν είτε φωτογραφία, είτε φίλτρο επεξεργασίας.
* Για το bonus 1, έχοντας ως είσοδο την kinect για το κοντινότερο σημείο ως προς την κάμερα εμφανιζόταν ένα φιδάκι που ακολουθούσε την κίνηση αυτού. Για το δεύτερο ζητούμενο υλοποιήθηκε background removal με μια εικόνα. Στο τελευταίο ζητούμενο, εμφανιζόταν ένα φιδάκι που ακολουθούσε την κίνηση του δεξιού χεριού του χρήστη.

# 1st Deliverable
### 1. Video Capture
Αφότου έκανα προσθήκη της βιβλιοθήκης **Video Library for Processing 4**, πήρα από το [Learning Processing, 2nd Edition](http://learningprocessing.com/) το παράδειγμα 16-1 και το έτρεξα στο **Processing**. 

<img src="https://user-images.githubusercontent.com/101424559/197458277-a40ba716-e47f-4dc9-bc9e-a9a059ae76f0.png" width="310" height="210">


### 2. Recorded video
Αρχικά κατέβασα ένα βίντεο 10sec από [εδώ](https://www.videvo.net/video/glowing-purple-grid-lines-tracking-in/393674/) και το αποθήκευσα σε έναν φάκελο data που έφτιαξα στο Processing --> sketch_221023b σύμφωνα με το παράδειγμα 16-4 του [βιβλίου](http://learningprocessing.com/). Μετά, σύμφωνα με το 16-5 (σελίδα 337 του βιβλίου)  έκανα import το Video Library for Processing 3 --> Movie --> Speed όπου έβαλα το βίντεο και άλλαξα τις διαστάσεις του παραθύρου για να φαίνεται.

<img src="https://user-images.githubusercontent.com/101424559/197757334-6b76e5c4-1ed4-4065-9a11-3d20603b2884.png" width="310" height="210">

### 3. QR Code
Πρώτα έκανα προσθήκη της [βιβλιοθήκης Processing QRCode](https://shiffman.net/p5/qrcode-processing/) στο Processing, ενώ μετά έκανα το [QR Code](https://www.qrcode-monkey.com/) και το αποθήκευσα στον φάκελο του sketch .Έπειτα έκανα αντιγραφή τον κώδικα του παραδείγματος 15-1 από το βιβλίο και άλλαξα την εικόνα σε αυτή του QR Code, επίσης άλλαξα τις διαστάσεις του παραθύρου ώστε να φαίνεται ομοιόμορφο. 

<img src="https://user-images.githubusercontent.com/101424559/197763268-5526842b-418e-470e-820b-2ce98f80a742.png" width="210" height="210">

### 4. QR Code - Camera Read
Eτρεξα το example για το QR Code, έκανα αντιγραφή τον κώδικα και μετά έφτιαξα έναν φάκελο data εκεί που είναι αποθηκευμένος ο κώδικας sketch και έβαλα το QR code ως png. Έτρεξα τον κώδικα και όταν πατούσα το spacebar μου έβγαζε το URL.

<img src="https://user-images.githubusercontent.com/101424559/197786593-fbf8a7db-fc34-4931-8f83-68d77c2db81e.png" width="250" height="210">

### 5. Augmented Reality
Αρχικά, εγκατάστησα την τελευταία έκδοση της βιβλιοθήκης NyARToolkit, συγκεκριμένα το [nyar4psg.zip](https://github.com/nyatla/NyARToolkit-for-Processing/releases).  Πήρα τον κώδικα από το έτοιμο παράδειγμα simpleLite και έφτιαξα ένα άλλο sketch. Έπειτα έβαλα την φωτογραφία στα data που έβαλα στον φάκελο που είναι αποθηκευμένος ο κώδικας και πρόσθεσα στον κώδικα από το παράδειγμα QR Code το κομμάτι για την εικόνα.

<img src="https://user-images.githubusercontent.com/101424559/197820765-8c6dac7c-df68-488e-8d22-0e0d8ec605c3.png"  width="220" height="210">

# 2nd Deliverable
### 1. Background Removal
Πρώτα κόλλησα ένα πράσινο σεντόνι από πίσω μου για να δημιουργήσω ένα ομοιόμορφο backround, έπειτα έκανα copy paste το [example 16-12](http://learningprocessing.com/examples/chp16/example-16-12-BackgroundRemove) στο sketch, άλλαξα το threshold από 20 στο 70, έβαλα μεταβλητή backround float g3 = green(bgColor); μόνο πράσινο και τέλος αποθήκευσα μία εικόνα στον φάκελο data του sketch με διαστάσεις 320x240 με βοήθεια από [εδώ](http://learningprocessing.com/exercises/chp16/exercise-16-06-greenscreen).

<img src="https://user-images.githubusercontent.com/101424559/201982889-57b7d30b-dccb-4a4b-9189-b60b20b22c11.png" width="300" height="210">

### 2. Motion Detection
Άνοιξα το παράδειγμα [16-7](http://learningprocessing.com/exercises/chp16/exercise-16-07-track-motion), το έκανα copy paste στο sketch και πείραξα το χρώμα, το μέγεθος της έλλειψης και αύξησα το threshold = 150;. 

<img src="https://user-images.githubusercontent.com/101424559/202160980-7c7d50d2-ccb8-4dd9-a23d-facad04a5ccd.png" width="290" height="180">

### 3. Background Substraction - Library use
Αρχικά κατέβασα την βιβλιοθήκη OpenCV for Processing, άνοιξα το παράδειγμα BackgroundSubstractio και με βοήθεια από το παράδειγμα [capture](http://learningprocessing.com/examples/chp16/example-16-01-Capture) έφτιαξα τον κώδικα. Αλλαξα το size(320, 240), πρόσθεσα το 
video = new Capture(this, 320, 240);  video.start();, άλλαξα το stroke. 

"Ποιά είναι τα πλεονεκτήματα και μειονεκτήματα της έτοιμης βιβλιοθήκης έναντι του κώδικα από το πρώτο ερώτημα;"

Η χρήση βιβλιοθήκης μας γλιτώνει χρόνο και χώρο, εφόσον παρέχουν προ-γραμμένα  κομμάτια κώδικα κάνοντας έπειτα αυτόν που γράφουμε πιο ευνόητο (σαν την λύση του 3ου ερωτήματος). Όμως σε περιπτώσεις που οι ανάγκες που θέλουμε να καλύψουμε είναι αρκετά συγκεκριμένες, η τροποποίηση μπορεί να είναι δύσκολη ή αδύνατη, και απαιτεί πρώτα την πλήρη κατανόηση και του τρόπου υλοποίησης αυτής.

<img src="https://user-images.githubusercontent.com/101424559/202005796-5e9c0d4c-fbfd-4464-94c5-7d82eb52f261.png" width="240" height="210">

### 4. Object Tracking
Άνοιξα το example [16-11](http://learningprocessing.com/examples/chp16/example-16-11-ColorTrack), το [example 9-8](http://learningprocessing.com/examples/chp09/example-09-08-mouse-history), και έφτιαξα τον κώδικα στο sketch "xpos[xpos.length-1] = closestX;"  "ypos[ypos.length-1] = closestY;" , έτσι ώστε  η είσοδος να γίνεται από ένα αντικείμενο της επιλογής μου με αριστερό κλικ από το ποντίκι, και το φιδάκι να ακολουθεί αλλά και να είναι το χρώμα αυτού.

"Σε σχέση με το παραδοσιακό ποντίκι ποια είναι τα πλεονεκτήματα και ποια τα μειονεκτήματα αυτής της τεχνικής ελέγχου ενός ή περισσότερων σημείων σε μια οθόνη;¨

Με το ποντίκι υπάρχει μεγαλύτερη ακρίβεια και απόκριση σε σύγκριση με την τεχνική ελέγχου ενός σημείου, στην οποία η ταχύτητας κίνησης της ενός ή περισσότερων σημείων ή η θέση τους μπορεί να επηρεάσουν την αποδοτικότητα της ανταπόκρισης του υπολογιστικού συστήματος σε αυτή. Η χρήση του ποντικιού σε μεγάλες οθόνες δεν καθίσταται κουραστική ενώ στην 2η περίπτωση μπορεί να απαιτείται μεγαλύτερος βαθμός κινητικότητας, αλλά μπορεί να θεωρηθεί και πιο «διασκεδαστική». Ο αριθμός σημείων που μπορούν να καθοριστούν από ένα ποντίκι είναι μόνο 1 και μπορεί να χρησιμοποιηθεί μόνο σε υπολογιστή, οπότε υπάρχουν μεγαλύτεροι περιορισμοί.

<img src="https://user-images.githubusercontent.com/101424559/202160010-8fd9354f-2480-437e-b9a6-ad2cfa83cdcf.png" width="220" height="210">

# 3rd Deliverable 
Έκανα εγκατάσταση την εφαρμογή reacTIVision vision engine, την βιβλιοθήκη reacTIVision στο Processing, την εφαρμογή TUIO Simulator και άνοιξα το παράδειγμα TUIO demo. Στην αρχή ήταν λευκή η οθόνη αλλά όταν έβαζα τα σχήματα μέσα στον κύκλο από το simulator φαινόντουσαν ταυτόχρονα και στο παράθυρο. 

<img src="https://user-images.githubusercontent.com/101424559/210105392-97ddcbf3-89b6-4b28-81b9-6ae54aab3335.png"  width="300" height="210">
<img src="https://user-images.githubusercontent.com/101424559/210105502-ee1b4d2e-8e8e-429c-8a80-fe9c91dddd67.png" width="300" height="210">

Έπειτα, με την βοήθεια αυτού του [βίντεο](https://www.youtube.com/watch?v=qKXlI4zAMAY&ab_channel=SergioL%C3%B3pezRey) κατάλαβα την λογική και έφτιαξα τον κώδικα έτσι ώστε όταν αναγνωρίζεται ένας κωδικός στην κάμερα από τον simulator, να εμφανίζεται και μία [εικόνα](https://processing.org/reference/image_.html) στο παράθυρο του processing.
Στην συνέχεια πήρα τον κώδικα από το παράδειγμα και από [εδώ](https://forum.processing.org/two/discussion/4991/help-with-detecting-fiducial-markers) έμαθα τι να γράψω ώστε κάποιοι κώδικες να έχουν συγκεκριμένες ιδιότητες ενώ από [εδώ](https://forum.processing.org/one/topic/how-do-i-hide-a-image-when-it-s-pressed.html) πως να εμφανίζεται και να εξαφανίζεται μία εικόνα.
(ID = 0 [για αντιστροφή χρωμάτων](https://processing.org/reference/filter_.html), ID = 1 για ασπρόμαυρο φίλτρο, ID = 2 [για μεγέθυνση](https://processing.org/reference/scale_.html), ID = 3 πρώτη εικόνα, ID = 4 δεύτερη εικόνα.)

ΙD = 3 & ID = 0 

<img src ="https://user-images.githubusercontent.com/101424559/210827103-ed9331e2-076f-473c-8ed2-86335f9e3b37.png" width="300" height="210">
<img src="https://user-images.githubusercontent.com/101424559/210827355-a9c10a88-11c1-46e8-b08d-71445f736493.png" width="300" height="210">

ΙD = 4 & ID = 1

<img src="https://user-images.githubusercontent.com/101424559/210827595-bdc6a975-8880-4c21-9e39-482bd1b94ad8.png" width="300" height="210">
<img src="https://user-images.githubusercontent.com/101424559/210827803-57f37afd-029f-4a84-93d7-6df5808b171a.png" width="300" height="210">

ΙD = 3 & ID = 2

<img src="https://user-images.githubusercontent.com/101424559/210828112-d7e356bd-0a8e-4f97-91ec-4d9663ffd274.png" width="300" height="210">
<img src="https://user-images.githubusercontent.com/101424559/210829219-d69f5cbe-0472-4a45-8ec4-5cd86fef332b.png" width="300" height="210">

"Σε ποια φάση της σχεδίασης και ανάπτυξης του υλικό/λογισμικού της διάδρασης θα διαλέγατε την κανονική κάμερα ή τον προσομοιωτή?"
Όσον αφορά την εισχώρηση δεδομένων (δηλαδή των fiducial-markers) για την αναγνώρηση τους από το πρόγραμμα θα μπορούσε να χρησιμοποιηθεί ο simulator μιάς και έχει μεγαλύτερη ακρίβεια, αλλά για την εμφάνιση δεδομένων (π.χ. οι εικόνες και τα φίλτρα) και για μία πιο άμμεση διάδραση του χρήστη είναι πιο επιθυμητή επιλογή η κανονική κάμερα.
# Bonus 
Συνεργασία με [DPSD18140](https://github.com/Zantzou)
### 1. Kinect – Nearest Point Tracking

Δεν χρειάστηκε η διαδικασία Kinect – SimpleOpenNI – Installation, καθώς η εργασία υλοποιήθηκε στο εργαστήριο. Συνδέσαμε την κάμερα στον υπολογιστή, κατεβάσαμε την βιβλιοθήκη SimpleOpenNI και ανοίξαμε το παράδειγμα DepthInfrared. Ουσιαστικά πήραμε από το παράδειγμα DepthInfrared τον τρόπο κράτησης των συντεταγμένων του κοντινότερου σημείου closeX και closeY . Aπο το  [παράδειγμα 9-8](http://learningprocessing.com/examples/chp09/example-09-08-mouse-history) του βιβλίου learning processing 2  χρησιοποιησαμε τους πίνακες closestX[i] και closestY[i] για το κράτημα των προηγουμενων θέσεων του κοντινοτερου σημειου με αποτέλεσμα την δημιουργια του φιδιου εκχωρόντας τις τιμες closeX και closeY στους πίνακες.

<img src="https://user-images.githubusercontent.com/101424559/211901834-e00493a7-11bb-4e79-811a-f05ecd05ba22.png" width="300" height="210">

###  2. Kinect – Background Removal

Eπεξεργαστήκαμε το έτοιμο παράδειγμα Remove_Background_RGB, αποθηκεύσαμε μία εικόνα στον φάκελο data αλλάξαμε το pixels[i] από color σε backgroundReplace.pixels[i]; όπου για αυτό ισχύει  backgroundReplace = loadImage("image2.jpg"); μέ την λογική από το από το παράδειγμα [16-6](http://learningprocessing.com/exercises/chp16/exercise-16-06-greenscreen) του learning processing."Τι διαφορά έχει η χρήση της έτοιμης βιβλιοθήκης για την αφαίρεση του υποβάθρου σε σχέση με τον τρόπο που αφαιρέσατε το υπόβαθρο στο 2ο παραδοτέο;" Ήταν πιο γρήγορη και εύκολη η διαικασία και ο κώδικας περισσότερο κατανοητός.

<img src="https://user-images.githubusercontent.com/101424559/211910428-9e5aef8b-fd18-4402-952a-211b4be682a0.png" width="300" height="210">

### 3. Kinect – Right-Hand Tracking

Ανοίξαμε το παράδειγμα [tracking sceleton](https://github.com/totovr/SimpleOpenNI/blob/master/SimpleOpenNI/SimpleOpenNI/examples/OpenNI/Tracking_Skeleton/Tracking_Skeleton.pde) και επεξεργαστήκαμε τον κώδικα με την ίδια λογική όπως το πρώτο ζητούμενο μέσα από το παράδειγμα [παράδειγμα 9-8](http://learningprocessing.com/examples/chp09/example-09-08-mouse-history).


<img src="https://user-images.githubusercontent.com/101424559/211933391-17fa8da1-a1c4-4e6b-a214-d46387f5312f.png" width="300" height="210">


# Conclusions
Αρχικά, αυτή η διεπαφή μεταξύ του χρήστη και της τεχνολογίας είχε πολύ ενδιαφέρον, λόγω της αλληλεπίδρασης ήταν πολύ πιο ευχάριστη διαδικασία από το να σχεδιάζεις π.χ ένα πρόγραμμα στο visual studio. Τα ζητούμενα που μας θέσατε ήταν υλοποιήσιμα, περισσότερο φαινόντουσαν δύσκολα στην αρχή (λόγω του οτι ήταν η πρώτη μας επαφή με αυτά) από οτι ήταν στην πραγματικότητα. Το Processing ήταν όντως ένα προγραμματιστικό περιβάλλον πολύ φιλικό ως προς τον χρήστη αλλά πιστεύω έχει ακόμα πολλά περιθώρια βελτίωσης ως προς την αποδοτικότητα του. Πριν το μάθημα περίμενα οτι το κομμάτι της κιναισθητικής θα ήταν κατι πολύ εξειδικευμένο, ενώ τωρα θεωρώ οτι μπορεί να ασχοληθεί ο καθ΄ένας αρκεί να έχει όρεξη. 

# Sources 
Τα sources υπάρχουν όλα σε hyperlinks στο κείμενο.
