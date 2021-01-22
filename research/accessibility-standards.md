# Current Accessibility Standards

## W3C Accessibility Standards
- Accessibility is essential for developers and organizations that want to create high quality websites and web tools, and not exclude people from using their products and services
- The [UN Convention on the Rights of Persons with Disabilities](https://www.un.org/development/desa/disabilities/convention-on-the-rights-of-persons-with-disabilities/article-9-accessibility.html) recognizes access to information and communications technologies, including the Web, as a **basic human right**.
- Case studies show that accessible websites have better search results, reduced maintenance costs, and increased audience reach, among other benefits.

### Transcripts for Audio
- Providing a text transcript makes the audio information accessible to people who are deaf or hard of hearing, as well as to search engines and other technologies that can't hear
- It's easy and relatively inexpensive for websites to provide transcripts
  - There are also transcription services that create text transcripts in HTML format.

### Functionality is available from a keyboard
- Many people do not use the mouse and rely on the keyboard to interact with the Web. This requires keyboard access to all functionality, including form controls, input, and other user interface components.
- All functionality that is available by mouse is also available by keyboard
- Keyboard focus does not get trapped in any part of the content
- Web browsers, authoring tools, and other tools provide keyboard support
- Meeting this requirement helps keyboard users, including people using alternative keyboards such as keyboards with ergonomic layouts, on-screen keyboards, or switch devices. It also helps people using voice recognition (speech input) to operate websites and to dictate text through the keyboard interface.

### Users can easily navigate, find content, and determine where they are
- Pages have clear titles and are organized using descriptive section headings
- There is more than one way to find relevant pages within a set of web pages
- Users are informed about their current location within a set of related pages
- There are ways to bypass blocks of content that are repeated on multiple pages
- The keyboard focus is visible, and the focus order follows a meaningful sequence
- The purpose of a link is evident, ideally even when the link is viewed on its own

### Users have enough time to read and use the content
- Some people need more time than others to read and use the content. For instance, some people require more time to type text, understand instructions, operate controls, or to otherwise complete tasks on a website.
- Stop, extend, or adjust time limits, except where necessary
- Pause, stop, or hide moving, blinking, or scrolling content
- Postpone or suppress interruptions, except where necessary
- Re-authenticate when a session expires without losing data

### Sources
- [Accessibility Principles](https://www.w3.org/WAI/fundamentals/accessibility-principles/)
- [W3C](https://www.w3.org/standards/webdesign/accessibility.html)

## Apple's VoiceOver
- VoiceOver enables users with visual disabilities to control their computer using a rich set of keyboard commands and gestures
- VoiceOver is a built-in screen reader that describes aloud what appears on your computer screen: it speaks the text that’s in documents and windows
  - To turn on VoiceOver on a Mac, press Command-F5
- When VoiceOver is on, you can use VoiceOver commands to navigate and interact with items on the screen
  - You enter VoiceOver commands by holding down the Control and Option keys together, along with one or more other keys. 
  - The Control and Option keys are called the “VoiceOver keys,” or “VO keys” for short. 
  - They are shown in commands as VO, as in VO-F1. 
  - You can assign VoiceOver commands to numeric keypad keys, keyboard keys, braille display input keys, and trackpad gestures, so you can use the commands with fewer keystrokes.
- You use the VoiceOver cursor to move around the screen and hear descriptions of the items in the cursor. 
- You use it to select buttons and other controls, and to read and edit text. 
- The keyboard focus and mouse pointer work with the VoiceOver cursor in a variety of ways. 
  - You can configure them to follow each other, or use them separately to move in different applications at the same time.
- When VoiceOver is on, you can start the tutorial at any time by pressing VO-Command-F8.
### About the VoiceOver cursor, mouse pointer, and keyboard focus
- When you use VoiceOver to move to areas of the screen or within the text in a document, a dark rectangle is drawn around the area where VoiceOver is focused. This rectangle is called the “VoiceOver cursor.”
- By default, the keyboard focus and VoiceOver cursor match, so that wherever you move the keyboard focus using standard keyboard navigation (Tab key and arrow keys), the VoiceOver cursor follows. And wherever the VoiceOver cursor goes, the keyboard focus follows (if possible). 
  - This is called “cursor tracking.” You can also turn on cursor tracking for the mouse.
- When you open a new window, the VoiceOver cursor and the keyboard focus are positioned on the same item. For example, when you open a New Message window in Mail, the VoiceOver cursor and the keyboard focus are positioned on the To field. If you prefer, you can make the initial position of the VoiceOver cursor be on the first item in the window.
- You can turn off cursor tracking. For example, you might want to leave the keyboard focus in one place and move the VoiceOver cursor around to read a dialog that just appeared, check email messages, or perform other tasks. If you turn off cursor tracking, you can use VoiceOver commands to move the VoiceOver cursor to where the keyboard is focused when you need to. You can do the same for the mouse.
  - You set preferences for the initial position of the cursor and for cursor tracking using VoiceOver Utility.

### Sources
- [Apple.com](https://www.apple.com/accessibility/vision/)
- [VoiceOver Guide](https://www.apple.com/voiceover/info/guide/_1121.html)

## NVDA Screenreader
- NVDA allows blind and vision impaired people to access and interact with the Windows operating system and many third party applications.
- Support for popular applications including web browsers such as Mozilla Firefox and Google Chrome, email clients, internet chat software, music players, and office programs such as Microsoft Word and Excel
- Built-in speech synthesizer supporting over 50 languages, plus support for many other 3rd party voices
- Reporting of textual formatting where available such as font name and size, style and spelling errors
- Automatic announcement of text under the mouse and optional audible indication of the mouse position
- Support for many refreshable braille displays, including input of Braille via braille displays that have a braille keyboard
- Ability to run entirely from a USB flash drive or other portable media without the need for installation
- Easy to use talking installer
- Translated into more than 50 languages
- Support for modern Windows Operating Systems including both 32 and 64 bit variants
- Ability to run on Windows logon and other secure screens
- Announcing controls and text while interacting with gestures on touch screens

### Sources
- [NVDA Homepage](https://www.nvaccess.org)

## JAWS
### Features
- Two multi-lingual synthesizers: Eloquence and Vocalizer Expressive
- Talking installation
- Convenient OCR feature for image files or inaccessible PDF documents
- Supports PEARL Camera for direct access to Print documents or books
- Built-in free DAISY Player and full set of DAISY-formatted basic training books
- Works with Microsoft Office, Google Docs, Chrome, Internet Explorer, Firefox, Edge, and much more
- Supports Windows® 10, Windows 8.1, and Windows 7, including touch screens and gestures
- Support for MathML content presented in Internet Explorer that is rendered with MathJax
- Save time with Skim Reading and Text Analyzer
- Fast information look-up at your fingertips with Research It
- Fully compatible with ZoomText, Fusion, MAGic, and the OpenBook Scanning and Reading Software

### Sources
- [JAWS Homepage](https://www.freedomscientific.com/products/software/jaws/)

## Interesting Insights
- This [wired.com article](https://www.wired.com/story/web-accessibility-blind-users-dominos/) really emphasizes that "people who use screen readers are regularly confronted with readouts like “unlabeled button” or “image1.jpg” in place of the descriptive information they need to navigate." Especially when most retail and shopping is online nowadays
  - Big reason to include image recognizer
- Beyonce got sued for her website [not being accessible](https://www.hollywoodreporter.com/thr-esq/beyonces-parkwood-entertainment-sued-1172909)















