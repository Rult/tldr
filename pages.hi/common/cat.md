# cat

> फ़ाइलों को प्रिंट और संक्षिप्त करें।
> अधिक जानकारी: <https://www.gnu.org/software/coreutils/manual/html_node/cat-invocation.html>.

- मानक आउटपुट में फ़ाइल की सामग्री प्रिंट करें:

`cat {{फ़ाइल}}`

- लक्ष्य फ़ाइल में कई फ़ाइलों को संयुक्त करें:

`cat {{फ़ाइल1}} {{फ़ाइल2}} > {{लक्ष्य_फ़ाइल}}`

- लक्ष्य फ़ाइल के अंत में कई फ़ाइलें संलग्न करें:

`cat {{फ़ाइल1}} {{फ़ाइल2}} >> {{लक्ष्य_फ़ाइल}}`

- सभी आउटपुट लाइनों की संख्या:

`cat -n {{फ़ाइल}}`

- गैर-मुद्रण योग्य और सफेदस्थान पात्र प्रदर्शित करें (M-उपसर्ग के साथ यदि गैर-ASCII):

`cat -v -t -e {{फ़ाइल}}`
