# BetterRead
## Contributors
* Will Cupp: cuppwm@mail.uc.edu
* Maddie Eckhart: eckharme@mail.uc.edu
* Sean Hearne: hearnesc@mail.uc.edu
* Isiah Lloyd: lloydij@mail.uc.edu  
  
All contributers are computer science majors
## Faculty Advisor
* Dr. Badri Vellambi

## Abstract

BetterRead is an accessibility tool built to work with websites that don’t conform to accessibility standards in order to make the web more accessible for those with visual impairments.

## Full Description

BetterRead is an accessibility tool meant to improve the web browsing experience for those with visual impairments. BetterRead uses machine learning to identify important content of web pages and ignore the superfluous information that someone with visual impairments shouldn’t worry about. BetterRead’s purpose is to promote diverse internet usage by allowing vision-impaired users to navigate the internet and give them experiences similar to able-bodied users.

The system is described visually in our design diagrams. Here, we provide an in-depth description of the system. A visually impaired user surfing the web will be able to use our browser extension to get an audio description of the webpage that they are currently accessing. In order to do this, the web extension will grab the webpage's Document-Object-Model (ruther referred to as DOM). The DOM is sent to a service that will transform it into a data format that can be fed into a machine learning service. We will have a service running a REST API that will handle moving this data between the user and the machine learning service. The machine learning service will take the transformed DOM data and produce a tet description. This text description will include important information about the pages content and exclude extraneous information that is not useful to the user. The REST API service will send this text description to the web extension. The web extension will use the text-to-speech API available in the user's browser to convert the text description to audio and play that audio to the user.
