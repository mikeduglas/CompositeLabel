# Composite Label
The class allows to change the properties (font name, size, style, color) of any part of contents in PROMPT and STRING controls.

### Demo program
The demo initially shows a plain string. Below is the window definition and a screenshot.
```
Window                        WINDOW('Composite label demo'),AT(,,319,91),CENTER,GRAY,FONT('Segoe UI',10)
                                STRING('lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eius' & |
                                  'mod tempor'),AT(10,16,296),USE(?STRING1),LEFT,FONT(,10)
                                BUTTON('Change style'),AT(10,68,78),USE(?bChangeStyle),DEFAULT
                                BUTTON('Reset'),AT(105,68,52),USE(?bReset)
                                BUTTON('Close'),AT(258,68,48),USE(?bClose),STD(STD:Close)
                              END
```
![cl1](https://github.com/mikeduglas/CompositeLabel/blob/master/screenshots/cl1.png?raw=true)    

Next screenshot shows same string, with some style changing (the word "consectetur" in bold, the word "eiusmod" in red and underlined).
![cl2](https://github.com/mikeduglas/CompositeLabel/blob/master/screenshots/cl2.png?raw=true)    


### Requirements
- C6 and higher, ABC/Legacy

### Contacts
- <mikeduglas@yandex.ru>
- <mikeduglas66@gmail.com>

### Price
- $50 [PayPal](https://www.paypal.me/mikeduglas?ppid=PPC000628&cnac=RU&rsta=ru_RU(ru_RU)&cust=8W29QJ6GKY9HS&unptid=75f96da6-24a4-11e9-ae2c-441ea14e9560&t=&cal=ff0291196b3f5&calc=ff0291196b3f5&calf=ff0291196b3f5&unp_tpcid=ppme-social-user-profile-created&page=main:email&pgrp=main:email&e=op&mchn=em&s=ci&mail=sys)
