# Introduction to North Seattle College Events
North Seattle College (NSC) provides a dynamic range of opportunities for students seeking engagement in campus life. This encompasses a diverse selection of events sponsored by Student Leadership and faculity, encompassing both entertaining and informative gatherings. Additionally, students can participate in thought-provoking lectures, community meetings, captivating library exhibits, and events tailored for transfer students.

Currently, these events are conveniently listed in a table-like format on the [NSC website](https://northseattle.edu/campus-life/campus-events). Clicking on a specific event's hyperlink expands to reveal additional details. To streamline communication, students can sign up for email notifications for events or clubs of interest. Notifications are also sent through Canvas and NSC mail servers, keeping students informed about all upcoming events.

In a significant move to enhance accessibility and consolidate how many times students are notified, NSC-Events collaborated with the NSC Application Development department in June 2023. Together, we have developed separate web and mobile applications to showcase, register, and track event participation across the entire campus. The shared backend app facilitates seamless connectivity with cloud services, streamlining data collection from pre-event clicks to the actual number of attendees.

This service enhancement, particularly the robust data collection, will prove invaluable to event planners and administrators alike. Increased knowledge about which events are being viewed, coupled with post-event participation data, will empower planners to organize more successful events with higher attendance rates.
  
## Table of Contents
- [About The Project](#about-the-project)
- [MVP Progress](#mvp-progress)
- [Wiki](#wiki)
- [Acknowledgements](#acknowledgements)
- [License](#license)
 
## About The Project
- NSC-Event's [web-based](https://github.com/SeattleColleges/nsc-events-nextjs) frontend utilizes `Typescript` via `NextJs`.

   [![11.png](https://i.postimg.cc/QCC5CzXf/11.png)](https://postimg.cc/tn07m2n6)

- The [android-based](https://github.com/SeattleColleges/nsc-events-android) frontend was developed using `Kotlin` within `Android Studio`.

  [![22.png](https://i.postimg.cc/hPkX9vD8/22.png)](https://postimg.cc/Wh7pV2Jt)

- `NestJs` was selected for [backend](https://github.com/SeattleColleges/nsc-events-nestjs) services also using `Typescript`. 

- `Google Cloud` powers our storage and `MongoDB` hosts our database.

### Software & Tools Used
- [Next.js](https://nextjs.org/): for the web application
- [Android Studio](https://developer.android.com/studio?gclid=Cj0KCQiAmNeqBhD4ARIsADsYfTekXQtjhqJ8cl8GBV4Lmza-3twj7fpJ6BC73tf5vPeYJYChgA9M3JAaAlGTEALw_wcB&gclsrc=aw.ds): for the android application
- [Nest.js](https://nestjs.com/): for the server-side backend application 
- [Postman](https://www.postman.com/): for testing API endpoints
- [MongoDB](https://www.mongodb.com/): for collecting data
- [JWT](https://jwt.io/): for authenticating users
- [Google Cloud](https://cloud.google.com/gcp?utm_source=google&utm_medium=cpc&utm_campaign=na-US-all-en-dr-bkws-all-all-trial-e-dr-1605212&utm_content=text-ad-none-any-DEV_c-CRE_665735450627-ADGP_Hybrid+%7C+BKWS+-+EXA+%7C+Txt_Google+Cloud-KWID_43700077223807304-kwd-6458750523&utm_term=KW_google%20cloud-ST_google+cloud&gad_source=1&gclid=Cj0KCQiAgqGrBhDtARIsAM5s0_lZss9iNTytw2uZ_WJ8_H0PGVmFvXwkK06n99z0LeosNebnEEVAkI4aAoWCEALw_wcB&gclsrc=aw.ds): for storage and eventually deploymnent
- Hosting: for availing these apps to the masses... TBD
 
## MVP Progress
As a student team primarily operating asynchronously, our journey commenced in late June '23, working diligently under a grant-approved program at NSC for the initial 100 days. Throughout the summer, we not only made significant strides in our project but also forged strong team bonds, marking our first collaborative experience. Collectively, we reached the milestone of MVP1 by November 3, 2023 within the mobile app.
- The following video links demonstrate our progress along the way:
	- Pre MVP1
		- [Web](https://www.youtube.com/watch?v=0t_JNORHuo0) 
		- [Mobile](https://youtu.be/4WY4ZIA2664?feature=shared)
	- MVP1
		- Web (The work on this application will continue April of 2024.)
		- [Mobile](https://www.youtube.com/watch?v=i3xTs-7_xp8)
	- Pre MVP2
		- Web (The work on this application will continue April of 2024.)
		- Mobile (Coming soon!)
	- MVP2
		- Web (Coming soon!)
   		- Mobile (Coming soon!)
 
## Wiki
- Though the nsc-events repository serves as our "main" repo for this client, visit our other Wikis for more information on topics that include:
  - [mobile app](https://github.com/SeattleColleges/nsc-events-android/wiki)
  - [web app](https://github.com/SeattleColleges/nsc-events-nextjs/wiki)
  - [backend app](https://github.com/SeattleColleges/nsc-events-nestjs/wiki)
 
## Acknowledgements
- Thanks to our professor BC Ko for his leadership, knowledge, and patience.
- Thanks to STUB at NSC-Events and the NSC EDIC team for your endless passion in serving students.
- Thanks to [Miro](https://miro.com/app/dashboard/), [Smartsheet](https://www.smartsheet.com/welcome-customers-home), and [Notion](https://www.notion.so/product?utm_source=google&utm_campaign=2075789710&utm_medium=80211061601&utm_content=500427479647&utm_term=notion&targetid=kwd-312974742&gad_source=1&gclid=Cj0KCQiAgqGrBhDtARIsAM5s0_kCuNK8I-F-4u_Mj1ClGopPfB_VlD-Ris4aRIu9ospGViBIqqjhXqYaAgWpEALw_wcB) for student licensing of your product. 
 
## License
Copyright (c) 2023 North Seattle College Application Development Department

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
