GENIUS LEARNING APP — By Ashish Sir
====================================

यह एक शुरुआती mobile-friendly Progressive Web App (PWA) prototype है।
इसमें होम पेज, विषय सूची, नोट्स/वीडियो लिंक जोड़ना, 5 प्रश्नों का demo quiz
और इसी डिवाइस पर सेव होने वाली छात्र प्रोफाइल शामिल हैं।

महत्वपूर्ण सीमाएँ:
- यह APK फाइल नहीं है। यह वेब ऐप है जिसे HTTPS hosting पर प्रकाशित करके
  समर्थित Android ब्राउज़र से इंस्टॉल किया जा सकता है।
- विद्यार्थी प्रोफाइल और संसाधन लिंक केवल उसी डिवाइस/ब्राउज़र के local storage
  में रहते हैं; कोई वास्तविक server/database या teacher admin panel नहीं है।
- लॉगिन, password, cloud sync, video hosting और online result system अभी
  जोड़ने होंगे। छात्र पासवर्ड जैसी निजी जानकारी इस prototype में न लें।
- service worker के लिए ऐप को HTTPS या localhost से चलाएँ; file:// से नहीं।

चलाने का तरीका:
1. ZIP को extract करें।
2. पूरी folder को HTTPS static hosting पर upload करें।
3. अपनी वेबसाइट पर index.html खोलें।
4. Android Chrome में menu से “Install app” / “Add to Home screen” चुनें।

APK बनाने के लिए अगला चरण: वेबसाइट को Android Studio के Trusted Web Activity
(TWA) या Capacitor project में पैक करना, signing key बनाना और build करना।
