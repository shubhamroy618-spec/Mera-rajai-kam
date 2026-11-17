मेरा काम हिसाब — Android APK प्रोजेक्ट

यह आपके भेजे V7 HTML ऐप को Android WebView में चलाने के लिए बनाया गया प्रोजेक्ट है।

APK बनाने का तरीका:
1. इस ZIP के अंदर की सभी फाइलें GitHub repository के मुख्य पेज पर अपलोड करें (ZIP को extract करके अंदर की फाइलें अपलोड करें)।
2. GitHub में Actions टैब खोलें।
3. Build Android APK workflow चुनें और Run workflow दबाएँ।
4. काम पूरा होने पर workflow run खोलें और नीचे Artifacts में mera-kaam-hisaab-apk डाउनलोड करें।
5. ZIP खोलकर app-debug.apk मोबाइल में इंस्टॉल करें।

नोट:
- यह debug/test APK है, Play Store release नहीं।
- ऐप का डेटा इसी फोन के ऐप स्टोरेज में रहता है। ऐप uninstall या app data clear करने से डेटा मिट सकता है। इसलिए ऐप के बैकअप पेज से नियमित JSON बैकअप सेव करें।
- GitHub Actions build करने के लिए है; यह आपके काम के रिकॉर्ड को इंटरनेट पर sync नहीं करता।
