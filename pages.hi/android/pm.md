# pm

> एंड्रॉइड डिवाइस पर ऐप्स के बारे में जानकारी प्रदर्शित करें।
> अधिक जानकारी: <https://developer.android.com/studio/command-line/adb#pm>.

- सभी इंस्टॉल किए गए ऐप्स की सूची बनाएं:

`pm list packages`

- सभी इंस्टॉल किए गए सिस्टम ऐप्स की सूची बनाएं:

`pm list packages -s`

- सभी इंस्टॉल किए गए तृतीय-पक्ष ऐप्स की सूची बनाएं:

`pm list packages -3`

- विशिष्ट कीवर्ड से मेल खाने वाले ऐप्स की सूची बनाएं:

`pm list packages {{कीवर्ड1 कीवर्ड2 ...}}`

- किसी विशिष्ट ऐप के एपीके का पथ प्रदर्शित करें:

`pm path {{ऐप}}`