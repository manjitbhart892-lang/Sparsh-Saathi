# स्पर्श साथी (Sparsh Saathi)
### स्पर्श राजकीय दृष्टिबाधित इंटर कॉलेज, लालडिग्गी, गोरखपुर

एक पूर्णतः सुगम (Accessible), मोबाइल-प्रथम वेब एप्लिकेशन जो दृष्टिबाधित विद्यार्थियों और शिक्षकों के लिए समर्पित है।

## 🌟 प्रमुख विशेषताएं (Key Features)

1. **पूर्णतः सुगम (TalkBack & Screen Reader 100% Friendly)**:
   - सभी इंटरैक्टिव तत्वों के लिए स्पष्ट ARIA लेबल्स और रोल।
   - पीला-काला उच्च कंट्रास्ट (Yellow-Black High Contrast Mode)।
   - फॉन्ट आकार विस्तारक (A, A+, A++ Text Resizing)।
   - कीबोर्ड शॉर्टकट्स (Alt+1, Alt+2, Alt+3, Alt+L)।

2. **द्विभाषी समर्थन (Dual Language Support)**:
   - एक क्लिक में संपूर्ण ऐप हिंदी और अंग्रेजी में परिवर्तित होता है।

3. **तीन मुख्य अनुभाग (Main Sections)**:
   - **हमारा विद्यालय (About School)**: विद्यालय का इतिहास, पता, पावन संकल्प, सुबह की प्रार्थनाएं ("इतनी शक्ति हमें देना दाता", "वह शक्ति हमें दो दयानिधे") व राष्ट्रगान (ऑडियो सहित), एवं विद्यालय सूचना पट्ट।
   - **उपयोगी टूल्स (Accessible Tools)**: बोलने वाला कैलकुलेटर (Talking Calculator), सटीक आयु एवं जन्म दिन गणक (Age & Day of Birth Finder), लाइव समय व डिवाइस बैटरी स्थिति, और 6-डॉट ब्रेल लिपि अन्वेषक।
   - **ज्ञान एवं संदर्भ (Study & Rights)**: दिव्यांगजन अधिकार अधिनियम 2016 (RPwD Act) के तहत परीक्षा व लेखक (Scribe) अधिकार, 20 मिनट/घंटा अतिरिक्त समय, आरक्षण, भारतीय संविधान के मौलिक अधिकार (अनुच्छेद 14, 15, 21, 21A, 41), एवं गोरखपुर व उत्तर प्रदेश का सामान्य ज्ञान।

4. **डेवलपर प्रोफाइल (Developer Profile)**:
   - **नाम:** मंजीत भारती (Manjeet Bharti)
   - **पद:** छात्र, स्पर्श राजकीय दृष्टिबाधित इंटर कॉलेज, लालडिग्गी, गोरखपुर
   - **भूमिका:** ऐप निर्माता / App Developer
   - **ईमेल:** manjitbharti892@gmail.com

---

## 🚀 लोकल मशीन पर कैसे चलाएं (How to Run Locally)

### पूर्वापेक्षाएँ (Prerequisites):
- Node.js (संस्करण 18 या उससे अधिक)
- npm या bun

### स्थापना (Installation):

```bash
# 1. निर्भरताएं स्थापित करें
npm install

# 2. विकास सर्वर शुरू करें
npm run dev

# 3. ब्राउज़र में खोलें
# http://localhost:3000
```

### प्रोडक्शन बिल्ड (Production Build):

```bash
npm run build
npm run preview
```

---

## 📁 प्रोजेक्ट संरचना (Project Structure)

```text
├── index.html
├── metadata.json
├── package.json
├── tsconfig.json
├── vite.config.ts
├── public/
│   └── sparsh-saathi-source.zip
├── src/
│   ├── main.tsx
│   ├── App.tsx
│   ├── index.css
│   ├── types/
│   │   └── index.ts
│   ├── data/
│   │   └── content.ts
│   ├── utils/
│   │   └── speech.ts
│   └── components/
│       ├── Header.tsx
│       ├── TabsNav.tsx
│       ├── DeveloperCard.tsx
│       ├── AboutSchoolTab.tsx
│       ├── AccessibleToolsTab.tsx
│       ├── StudyRightsTab.tsx
│       ├── VoiceCommandAssistant.tsx
│       └── Footer.tsx
└── README.md
```

---
© 2026 स्पर्श साथी — स्पर्श राजकीय दृष्टिबाधित इंटर कॉलेज, लालडिग्गी, गोरखपुर
