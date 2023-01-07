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
![clplain](https://github.com/mikeduglas/CompositeLabel/blob/master/screenshots/clplain.png?raw=true)    

Next screenshot shows same string, with some style changing (the word "consectetur" in bold, the word "eiusmod" in red and underlined).
![clstyled](https://github.com/mikeduglas/CompositeLabel/blob/master/screenshots/clstyled.png?raw=true)    

## Features
- Supported left, center, right justified strings.

### Requirements
- C6 and higher, ABC/Legacy

### Contacts
- <mikeduglas@yandex.ru>
- <mikeduglas66@gmail.com>

### Price
[Buy now](https://www.clarionshop.com/checkout.cfm?pid=1664&q=1&)