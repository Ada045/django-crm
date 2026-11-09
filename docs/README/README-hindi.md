<p align="right">
<a href="https://github.com/DjangoCRM/django-crm/blob/main/README.md">English</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-hindi.md">हिन्दी</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-spanish.md">Español</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-portuguese.md">Português</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-french.md">Français</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-german.md">Deutsch</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-dutch.md">Dutch</a> |
<a href="https://github.com/DjangoCRM/django-crm/blob/main/docs/README/README-italian.md">Italiano</a>
</p>

# Django-CRM

*(संबंध प्रबंधन सॉफ्टवेयर जो सहयोग और विश्लेषणात्मक क्षमताओं पर केंद्रित ह)*

**Django-CRM** एक खुला स्रोत संबंध प्रबंधन समाधान है जिसका निर्माण **दो मुख्य लक्ष्यों** के साथ किया गया है:

- **उपयोगकर्ताओं के लिए**: उद्यम स्तर के खुले स्रोत CRM सॉफ्टवेयर की प्रदान करें जिसमें एक व्यापक व्यावसायिक समाधान सूट शामिल हो।
- **विकासकर्ताओं के लिए**: विकास, अनुकूलन और उत्पादन सर्वर समर्थन को सरल बनाने की प्रक्रियाओं को सरल बनाएँ।

**किसी भी संपत्ति फ्रेमवर्क जानने की आवश्यकता नहीं है**: सब कुछ लोकप्रिय Django फ्रेमवर्क का उपयोग करके बनाया गया है। CRM भी पूरी तरह से Django Admin साइट का लाभ उठाता है, जिसमें सभी दस्तावेज़ एक एकल वेब पृष्ठ पर रखे गए हैं!

[<img src="https://github.com/DjangoCRM/django-crm/raw/main/docs/pics/deals_screenshot.png" alt="Django-CRM स्क्रीनशॉट" align="center"/>](https://github.com/DjangoCRM/django-crm/blob/main/docs/pics/deals_screenshot.png)

## संबंध प्रबंधन विशेषताएँ

|                           |                              |                            |
|---------------------------|------------------------------|----------------------------|
| ☑️ **टीम कार्य और परियोजनाएँ**  | ☑️ **नेतृत्व प्रबंधन**              | ☑️ **ईमेल मार्केटिंग**          |
| ☑️ **संपर्क प्रबंधन**           | ☑️ **डील ट्रैकिंग और बिक्री पूर्वानुमान** | ☑️ **भूमिका-आधारित पहुँच नियंत्रण** |
| ☑️ **बबिक्री विश्लेषण**        | ☑️ **आंतरिक चैट एकीकरण**        | ☑️ **मोबाइल-अनुकूल डिजाइन**    |
| ☑️ **अनुकूलन योग्य रिपोर्ट**    | ☑️ **सस्वचालित ईमेल सिंक**         | ☑️ **बहु-मुद्रा समर्थन**          |

[सॉफ़्टवेयर की क्षमताओं के बारे में अधिक जानें](https://github.com/DjangoCRM/django-crm/blob/main/docs/crm_system_overview.md)।

Django CRM एक खुला स्रोत संबंध प्रबंधन सॉफ़्टवेयर है। यह CRM Python में लिखा गया है <a href="https://www.python.org" target="_blank"><img src="https://github.com/DjangoCRM/django-crm/raw/main/docs/site/icons/python-logo.svg" style="vertical-align: middle" alt="python logo" width="25" height="25"> Python</a>.  
Frontend और backend दोनों Django [Admin साइट](https://docs.djangoproject.com/en/dev/ref/contrib/admin/) पर आधारित हैं।  
CRM ऐप आउट-ऑफ-द-बॉक्स अनुकूली एडमिन HTML टेम्पलेट्स का उपयोग करता है।  
Django एक उत्कृष्ट दस्तावेज़ीकृत फ्रेमवर्क है जिसमें कई उदाहरण हैं।  
एडमिन साइट पर दस्तावेज़ीकरण केवल एक वेब पेज पर होता है।
💡 **मूल विचार** यह है कि Django Admin पहले से ही एक पेशेवर ऑब्जेक्ट प्रबंधन इंटरफ़ेस है जिसमें लचीले अनुमतियों की एक प्रणाली है (दृश्य, संशोधित, जोड़ें, और हटाएँ) - Django Admin में ऑब्जेक्ट्स (जैसे नेतृत्व, अनुरोध, सौदे) के लिए मॉडल बनाना और व्यावसायिक तर्क जोड़ना सभी के लिए आसान है।

इससे निम्नलिखित सुनिश्चित होता है:

- परियोजना अनुकूलन और विकास काफी आसान
- सरल उत्पादन सर्वर समर्थन और तैनाती

सॉफ़्टवेयर पैकेज दो वेबसाइटें प्रदान करता है:

- सभी उपयोगकर्ताओं के लिए CRM साइट
- प्रशासकों के लिए साइट

**यह परियोजना परिपक्व एवं स्थिर है**, और वास्तविक अनुप्रयोगों के लिए कई वर्षों तक सफलतापूर्वक उपयोग किया गया है।

## मुख्य अनुप्रयोग

CRM सॉफ़्टवेयर सूट में निम्नलिखित **मुख्य अनुप्रयोग** और उनके मॉडल शामिल हैं:

- **कार्य प्रबंधन ऐप**:
  (डिफ़ॉल्ट रूप से सभी उपयोगकर्ताओं के लिए उपलब्ध, उनकी भूमिका की परवाह किए बिना)
  - कार्य (संबंधित फ़ाइलों, चैट, याद दिलाने और टैग - [कार्य विशेषताओं](https://github.com/DjangoCRM/django-crm/blob/main/docs/django-crm_task_features.md) के लिए देखें)
    - उप-कार्य
  - मेमो (ऑफ़िस मेमो - [मेमो विशेषताओं](https://github.com/DjangoCRM/django-crm/blob/main/docs/django-crm_memo_features.md) के लिए देखें)
    - कार्य / परियोजना
  - **परियोजनाएँ**:
  - ... (+ *4 अधिक <a href="https://github.com/DjangoCRM/django-crm/tree/main/tasks/models" target="_blank">मॉडल</a>)
- **CRM ऐप**:
  - अनुरोध
  - नेतृत्व
  - कंपनियाँ
  - संपर्क व्यक्ति (अपनी कंपनियों से जुड़े)
  - सौदे (जैसे "अवसर")
  - ईमेल संदेश (उपयोगकर्ता ईमेल खातों से सिंक्रनाइज़)
  - उत्पाद (उत्पाद और सेवाएँ)
  - भुगतान (प्राप्त, गारंटीकृत, उच्च और निम्न संभावना के)
  - ... (*+ 12 अधिक [विश्लेषणात्मक रिपोर्टों](https://github.com/DjangoCRM/django-crm/blob/main/docs/django-crm_analytics_app_overview.md) सहित*)

[<img src="https://github.com/DjangoCRM/django-crm/raw/main/docs/pics/income_summary_thumbnail.png" alt="विश्लेषणात्मक CRM रिपोर्ट" align="right"/>](https://github.com/DjangoCRM/django-crm/blob/main/docs/pics/income_summary_screenshot.png)

- **विश्लेषणात्मक ऐप**: ([विस्तृत सॉफ़्टवेयर अवलोकन](https://github.com/DjangoCRM/django-crm/blob/main/docs/django-crm_analytics_app_overview.md))
  - आय सारांश रिपोर्ट (*देखें [स्क्रीनशॉट](https://github.com/DjangoCRM/django-crm/blob/main/docs/pics/income_summary_screenshot.png)*)
  - बिक्री फ़ंडल रिपोर्ट
  - नेतृत्व स्रोत सारांश रिपोर्ट
  - ... (+ *5 अधिक विश्लेषणात्मक रिपोर्टें)
- **मेल ऐप**:
  - ईमेल खाते
  - ईमेल संदेश (समाचार पत्रों के माध्यम से संपर्कों तक पहुँचना)
  - ईमेल साइनेचर (उपयोगकर्ता हस्ताक्षर)
  - मेलिंग

## सहायक अनुप्रयोग

CRM पैकेज **सहायक अनुप्रयोगों** जैसे:

- चैट ऐप (कार्य, परियोजनाओं, मेमो और सौदों के हर उदाहरण में उपलब्ध)
- VoIP ऐप (परियोजना कॉल के लिए)
- सहायता ऐप (डायनामिक मदद पृष्ठ जो उपयोगकर्ता की भूमिका के आधार पर निर्भर करते हैं)
- सामान्य ऐप:
  - 🪪 उपयोगकर्ता प्रोफ़ाइल
  - ⏰ याद दिलाने (कार्य, परियोजनाओं, मेमो और सौदों के लिए)
  - 📝 टैग (कार्यों, परियोजनाओं, मेमो और सौदों के लिए)
  - 📂 फ़ाइलें (कार्यों, परियोजनाओं, मेमो और सौदों के लिए)

## अतिरिक्त कार्यक्षमता

- वेब फ़ॉर्म एकीकरण: CRM संपर्क फ़ॉर्म में अंतर्निहित हैं:
- reCAPTCHA v3 सुरक्षा
- स्वचालित भौगोलिक स्थान
- उपयोगकर्ता के ईमेल खाते का एकीकरण और सिंक्रनाइज़ेशन। ईमेल संदेश स्वचालित हैं:
- CRM डेटाबेस में सहेजे गए
- उपयुक्त CRM ऑब्जेक्ट्स (जैसे: अनुरोध, लीड, डील, आदि) से लिंक किए गए
- स्मार्टफ़ोन पर VoIP कॉलबैक
- मैसेंजर के ज़रिए संदेश भेजना (जैसे: Viber, WhatsApp, ...)
- एक्सेल सहायता: आसानी से संपर्क विवरण आयात/निर्यात करें।

## ईमेल क्लाइंट

पाइथन CRM सिस्टम में एक अंतर्निहित ईमेल क्लाइंट शामिल है जो **SMTP** और **IMAP** प्रोटोकॉल का उपयोग करके संचालित होता है।
यह Django-CRM को अपने डेटाबेस में प्रत्येक अनुरोध और सौदे से संबंधित सभी पत्राचार की प्रतियों को स्वचालित रूप से संग्रहीत करने में सक्षम बनाता है।
कार्यक्षमता यह सुनिश्चित करती है कि भले ही संचार उपयोगकर्ता के बाहरी ईमेल खाते (CRM के बाहर) के माध्यम से हो।
उन्हें **टिकटिंग तंत्र** का उपयोग करके सिस्टम के भीतर कैप्चर और व्यवस्थित किया जाता है।

CRM उन ईमेल सेवा प्रदाताओं (जैसे जीमेल) के साथ एकीकृत हो सकता है, जिन्हें तृतीय-पक्ष अनुप्रयोगों के लिए अनिवार्य द्वि-चरणीय प्रमाणीकरण (OAuth 2.0 प्रोटोकॉल का उपयोग करके) की आवश्यकता होती है।

## उपयोगकर्ता सहायता

- प्रत्येक CRM पृष्ठ में संदर्भ-सचेत सहायता पृष्ठ का लिंक शामिल होता है, जिसमें अधिक प्रासंगिक मार्गदर्शन के लिए उपयोगकर्ता की भूमिका के अनुरूप सामग्री को गतिशील रूप से तैयार किया जाता है।
- टूलटिप्स पूरे इंटरफ़ेस में उपलब्ध हैं, जैसे कि आइकन, बटन, लिंक या तालिका शीर्षक।
- एक व्यापक [उपयोगकर्ता गाइड](https://github.com/DjangoCRM/django-crm/blob/main/docs/django-crm_user_guide.md) फ़ाइल भी शामिल है।

## अपनी टीम के उत्पादकता स्तर को बढ़ाएँ

यह CRM टीमों के बीच सहयोग बढ़ाने और परियोजना प्रबंधन प्रक्रियाओं को कारगर बनाने के लिए डिज़ाइन किया गया है।  
एक सहयोगी CRM के रूप में, यह उपयोगकर्ताओं को आसानी से मेमो, कार्य और प्रोजेक्ट बनाने और प्रबंधित करने की अनुमति देता है।  
[कार्यालय मेमो](https://github.com/DjangoCRM/django-crm/blob/main/docs/django-crm_memo_features.md) विभाग प्रमुखों या कंपनी के अधिकारियों को निर्देशित किए जा सकते हैं, जो फिर इन मेमो को कार्यों या परियोजनाओं में बदल सकते हैं, जिम्मेदार व्यक्तियों या निष्पादकों को नियुक्त कर सकते हैं।  
[कार्य](https://github.com/DjangoCRM/django-crm/blob/main/docs/django-crm_task_features.md) व्यक्तिगत या सामूहिक हो सकते हैं।  
कार्य चैट चर्चा, अनुस्मारक, फ़ाइल साझाकरण, उप-कार्य बनाना और परिणाम साझा करने जैसी सुविधाएँ प्रदान करते हैं।  
उपयोगकर्ताओं को सीधे CRM में और ईमेल के माध्यम से सूचनाएँ प्राप्त होती हैं, जिससे यह सुनिश्चित होता है कि वे सूचित रहें।  
प्रत्येक उपयोगकर्ता को अपने कार्य-स्टैक की स्पष्ट जानकारी होती है, जिसमें प्राथमिकताएं, स्थितियां और अगले चरण शामिल होते हैं, जिससे सहयोगात्मक ग्राहक संबंध प्रबंधन में उत्पादकता और जवाबदेही बढ़ती है।

## परियोजना स्थानीयकरण

Django CRM में इंटरफ़ेस के अनुवाद, दिनांक, समय और समय क्षेत्रों के प्रारूपण के लिए पूर्ण समर्थन है।  
<img src="https://github.com/DjangoCRM/django-crm/raw/main/docs/site/icons/languages.svg" alt="django logo" width="30" height="30" style="vertical-align: middle"> ग्राहक सेवा सॉफ्टवेयर अब **कई भाषाओं में उपलब्ध है:**   
`de, en, es, fr, hi, it, nl, pt-BR, ru, uk`

## क्यों Django-CRM चुनें?

- **सहयोगी CRM**: कार्य प्रबंधन, परियोजना सहयोग और आंतरिक संचार के लिए उपकरणों के साथ टीम की उत्पादकता को बढ़ावा दें।
- **विश्लेषणात्मक CRM**: बिक्री फ़नल, आय सारांश और लीड स्रोत विश्लेषण जैसी अंतर्निहित रिपोर्टों के साथ कार्रवाई योग्य जानकारी प्राप्त करें।
- **पायथन और Django-आधारित**: किसी भी मालिकाना ढांचे की आवश्यकता नहीं है - सब कुछ एक सहज व्यवस्थापक इंटरफ़ेस के साथ Django पर बनाया गया है।

## शुरू करना आसान है

Django-CRM को नियमित Django परियोजना के रूप में आसानी से तैनात किया जा सकता है।

📚 कृपया देखें:

- [स्थापना और कॉन्फ़िगरेशन गाइड](https://github.com/DjangoCRM/django-crm/blob/main/docs/installation_and_configuration_guide.md)
- [उपयोगकर्ता गाइड](https://github.com/DjangoCRM/django-crm/blob/main/docs/django-crm_user_guide.md)

यदि आपको Django-CRM उपयोगी लगता है, तो कृपया इसके विकास का समर्थन करने के लिए GitHub पर इस रेपो को ⭐️ **स्टार** करें!

<img src="https://github.com/DjangoCRM/django-crm/raw/main/docs/pics/Django-CRM_star_history.png" alt="Django-CRM स्टार हिस्ट्री" align="center"/>

### संगतता

- <img src="https://github.com/DjangoCRM/django-crm/raw/main/docs/site/icons/django-logo.svg" alt="django logo" width="30" height="30" style="vertical-align: middle"> Django 5.1.x
- <img src="https://github.com/DjangoCRM/django-crm/raw/main/docs/site/icons/python-logo.svg" alt="python logo" width="30" height="30" style="vertical-align: middle"> Python 3.10+
- <img src="https://github.com/DjangoCRM/django-crm/raw/main/docs/site/icons/mysql_logo.svg" alt="mysql logo" width="30" height="30" style="vertical-align: middle"> MySQL 8.0.11+
- <img src="https://github.com/DjangoCRM/django-crm/raw/main/docs/site/icons/postgresql_logo.svg" alt="postgresql logo" width="30" height="30" style="vertical-align: middle"> PostgreSQL 12+

## योगदान

योगदान का स्वागत है! सुधार और नई सुविधाओं की गुंजाइश है।
शुरू करने का तरीका जानने के लिए हमारी [योगदान मार्गदर्शिका](https://github.com/DjangoCRM/django-crm/blob/main/CONTRIBUTING.md) देखें।
हर योगदान, चाहे बड़ा हो या छोटा, फर्क लाता है।

## लाइसेंस

Django-CRM `AGPL-3.0` लाइसेंस के तहत जारी किया गया है - [लाइसेंस फ़ाइल](https://github.com/DjangoCRM/django-crm/blob/main/LICENSE) को देखें।

## श्रेय

- Google [आइकॉन](https://fonts.google.com/icons).
- [NicEdit](https://nicedit.com/) (WYSIWYG सामग्री संपादक.)
- अन्य लाइसेंस के तहत उपयोग किए गए सभी संसाधन