---
title: "Experience"
# meta title
meta_title: "Trung's Experience"
# meta description
description: "Trung's technical and other experience"
# save as draft
draft: false
---

{{< toc >}}

## Internships

<hr>

{{< accordion "Sandia National Laboratories" >}}

Position: Cybersecurity R&D Intern  
Dates: Jun 2023 - Present

I started my journey with [Sandia National Laboratories](https://www.sandia.gov/) as a summer Cybersecurity R&D intern. For 10 weeks in Albuquerque, New Mexico, I worked on two projects: operational technology (OT) network activity analysis and browser exploits. For the first project, I used unsupervised machine learning (ML) techniques such as clustering and decision trees to pinpoint what traits constitute malicious MODBUS behavior. MODBUS is a communication protocol commonly used by OT devices. Taking that understanding, I attempted to write rules on Splunk that would automatically flag suspicious network activity and generate summary reports. For the second project, I first looked into a zero-day exploit called patch gapping that was used on Chromium to build a firm understanding of how Chromium's V8 Engine worked. From there, I proceeded to analyze HAR data to find browser exploit indicators and also worked to determine if browser isolation can protect users from zero-day exploits.

At the end of summer, I converted to a year-round Cybersecurity R&D intern where I remotely continuing working on the OT project. I wanted to continue working on both projects, but year-round interns can only work on one project since Sandia wants interns to focus on school (rightfully so). At the moment, I'm still working on the writing rules on Splunk to flag suspicious network activity. However, I'm also taking up some additional responsibility as I get to work on writing Python scripts that aggregate Sandia's IT and OT device inventory datasets to provide enriched and more accesible device information for Sandia staff.

I can't provide more details about the work I do for security reasons. But, I'd be more than happy to talk about living in Albuquerque and the Center for Cyber Defenders (CCD) internship program in general. Interning at Sandia is a great way to enter cybersecurity and I recommend those interested in the field to apply!

{{< /accordion >}}

{{< accordion "NASA Jet Propulsion Laboratory" >}}

Position: Data Science Intern   
Dates: Jun 2022 - Sep 2022

At [JPL](https://www.jpl.nasa.gov/), my goal was to use a deep learning approach to reconstruct Earth's historical global warming rate and reliably predict its future trend using a combination of input features, including both natural and human-caused climate drivers. With a well-trained deep neural network (DNN), I was to reaffirm the ongoing warming acceleration and gain a reliable prediction of its future trend, which will give humanity an early alarm on when a “tipping point” in climate change will come.

To this end, I analyzed surface temperature anomalies from 1850-2021 using the Berkeley Earth dataset, determining that regional warming occurs at varying rates. I observed that the Arctic began increasing in temperature faster than other regions (Tropics, Antarctic) starting in 2010 and found papers discussing the Arctic amplification phenomenon to support this observation. With that discovery, I pivoted to analyze latitude-dependent surface temperature simulations from CMIP6 models to understand their behavior and reliability. I attempted to determine whether CMIP6 models emulated observed regional and globally warming trends and whether large variance existed between different CMIP6 models and their regional/global temperature projections. CMIP6 models were designed specifically by climate scientists to consider human and natural factors that will impact climate and use those to accurately project future climates. If CMIP6 models are reliable, they would be a great training dataset for the DNN.

Using CMIP6 data from ESGF, I determined there exists a large variance between different CMIP6 models and their regional/global temperature projections. Due to this, I analyzed 65 CMIP6 models to identify “best-performing” models based on regional and global surface temperature anomaly accuracy with observed data. From the analysis, I compiled a 16-model ensemble composed of “best-performing” CMIP6 models to have a strong training dataset for my DNN. To prove that the ensemble was worthy to use as a training dataset, I demonstrated that it performs relative to observational data globally and regionally. As a bonus, I also utilized the ensemble to project surface temperatures from 2015 to 2075 under various shared socio-economic pathways (SSP), highlighting the need and impact of immediate climate mitigation and adaptation.

With a strong training dataset, I developed a DNN using PyTorch and trained it using the ensemble to the point where it can affirm ongoing warming acceleration and predict when a 2.0-2.5°C warming (a “tipping point” in climate change) will occur. The work I produced from this internship allowed me to have the 2nd best presentation out of all other JSIP interns for our final presentations.

This internship opportunity was achieved through [<u>UCLA's Joint Institute for Regional Earth and System Science & Engineering</u>](https://jifresse.ucla.edu/) (JIFRESSE) which is a scientific collaboration between UCLA and JPL. I encourage all those interested in tackling climate change to explore this opportunity!

{{< /accordion >}}

{{< accordion "SISYPHUS Global Systems" >}}

Position: Software Engineering Intern   
Dates: Mar 2021 - Jun 2022

[SISYPHUS Global Systems](https://sisyphus-gs.com/) is a climate tech startup developing a web-portal that utilizes ArcGIS maps and WebXR to provide users an immersive augmented reality experience of assessing their property's flood risk and viewing their city's green and grey infrastructure. Their AI model is designed to predict flood risk for individual properties and visualize potential damage via 3D rendered maps of city infrastructure. This product will be useful for individual homeowners as well as officials as city planners implement flood mitigation strategies.

During my internship, I helped develop green and grey infrastructure maps for New Orleans, LA with ArcGIS API for JavaScript to improve the company's GIS database and disaster risk/mitigation method calculations. I also researched and implemented several IBM software, such as Watson Assistant, App Connect, Code Engine, and etc., into the product's system architecture. Furthermore, I played a key role in re-designing the company's website to intricately showcase the product and its underlying tech stack, enhancing the company's ability to appeal to both customers and investors. Lastly, I managed and maintained the company's code-base on GitHub using Git version control.

I enjoyed working at SISYPHUS because I got exposed to various pieces of technology and was doing something new almost every week. This is very different than working at a large, well-established company where you just stick to one or two things. Participating in various hackathons with the company, I got to explore various open-source software and figure out how to integrate each technology into the company's system architecture. Beyond this, working at a startup let me experience more than the engineering side of a company. I learned various entrepreneurial skills like competitive analysis, value chain analysis, identifying market-fit, etc. I also learned how LLC creation laws differed in each state and the pros/cons of claiming intellectual property in broad/specific manners. Lastly, working at SISYPHUS gave me personal satisfaction as I know the product I'm helping develop is designed specifically to tackle the impending effects of climate change and the combat the systemically racist settlement patterns in American cities. Sadly, exploitation and gentrification have resulted in wealthy (mostly white) populations settling in geographically high-lying areas whilst low-income, minority populations are left to settle in low-lying areas with greater flood risk and less flood protection. While SISYPHUS's product will help everyone protect their properties from flood damage, the product will bring about some equity by providing underserved, low-income, minority communities with a free resource to protect their properties.

{{< /accordion >}}

## Other Employment

<hr>

{{< accordion "Scalable Analytics Institute" >}}

Position: Undergraduate Researcher  
Dates: Apr 2023 - Present

At [ScAI](https://scai.cs.ucla.edu/), I'm working with graph neural networks (GNN) using PyTorch and DGL to uncover intrinsic patterns underlying unlabeled protein sequence databases to assist in advanced property modeling. More specifically, I'm attempting to create an ML model that can accurately detect methionine modification. The reason why I'm using GNNs is because, unlike typical ML models, GNNs can take advantage of the structure of proteins and potentially yield more accurate prediction results.

{{< /accordion >}}

{{< accordion "UCLA Samueli School of Engineering" >}}

Position: Group Tutor and Researcher  
Dates: Sep 2021 - Present

- Taught: Fall 21, Spr 22, Fall 22, Fall 23       
- Will be teaching: Spr 24

After taking the course in winter quarter 2021, I joined the teaching staff of Engineering 96i: Internet of Things as a Group Tutor in fall quarter 2021. As a Group Tutor, I assist Professor William Kaiser in teaching over 150 students how to develop IoT motion detection functionality using the STMicroeletronics SensorTile and EmbeddedML Neural Network. More specifically, I teach students about C programming, the STM32L4 microprocessor on the [<u>STMicroelectronics SensorTile</u>](https://www.st.com/en/evaluation-tools/steval-stlkt01v1.html#st_description_sec-nav-tab), and machine learning. This is to have them develop a solid foundation on which they can begin developing their own IoT motion detection device using the SensorTile's accelerometer and gyroscope. As students develop their own projects, I help them debug code and provide insight on how to expand the neural network to realize their project ideas.

Beyond Engineering 96i, I also assist Professor Kaiser in teaching Engineering 96c: Cybernetics by tutoring students in robotic control systems and teaching them how to use MATLAB. After giving students enough background knowledge, I guide them in developing their own cybernetics project. Unfortunately, this course isn't being offered anymore.

Outside the classroom, I am working to refine Engineering 96i. More specifically, I am reviewing the current tutorials being used for the course to identify points where clarity can be improved and patch inconsistencies. I am also compiling a comprehensive course guidebook with tutorial solutions and insightful hints that course instructors and Group Tutors can utilize to better and more easily help students. Furthermore, I am developing and testing learning modules using the [<u>B-U585I-IOT02A IoT node</u>](https://www.st.com/en/evaluation-tools/b-u585i-iot02a.html#) for future adaptation into the course since this IoT device will be replacing the SensorTile.

Joining the Engineering 96i teaching staff was one of the best decisions I've made at UCLA as it allowed me to combine my passions of tech and service. Tutoring for multiple iterations of the course over the past 2 years, I feel great satisfaction helping students build their skillsets and develop projects they can highlight during interviews. Alongside teaching, I'm proud of the technical accomplishments I've made towards improving the course. Using the draft course guidebook I compiled over summer, the Group Tutors this fall quarter complimented on how it allowed them to better help students and quickly identify solutions to the issues students were facing. With the R&D I'm doing with the new IoT node, I hope to contribute major refinements to the course material so students at UCLA and other education institutions which use this material for their own IoT courses have an even better experience when taking the course.

{{< /accordion >}}

{{< accordion "UCLA Extension" >}}

Position: Teaching Assistant  
Dates: Sep 2023 - Sep 2023

As a staff member of UCLA Extension's [Technical Management Program](https://www.uclaextension.edu/engineering/technical-management-program) (TMP), I assist office staff and instructors in facilitating leadership and management workshops for over 130 technical managers.

TMP is a wonderful program hosted twice a year, once before Fall quarter starts and during Spring break. Being a TA for this program is a great opportunity for students to network with technical managers across various industries and develop leadership skills.

{{< /accordion >}}

{{< accordion "VentureWell" >}}

Position: Tech Innovator   
Dates: Jun 2021 - Sep 2021

As a participant of [VentureWell's](https://venturewell.org/) startup accelerator, I determined value chain, computed competitive analysis, and identified product-market fit for SISYPHUS Global Systems. I also attended workshops to develop the entrepreneurial skills necessary to successfully launch a startup and participated in coaching/mentorship with Verizon and VentureWell representatives to refine SISYPHUS's technology and marketing strategies.

Additionally, I organized and presented a product pitch to Chelsea Clinton, Verizon representative Nicki Palmer, and VentureWell CEO Phil Weilerstein that won against 12 startups and secured SISYPHUS a position in VentureWell's Propel program.

{{< /accordion >}}

## Extracurriculars

<hr>

{{< accordion "Upsilon Pi Epsilon (CS Honors Society)" >}}

Position: External Vice President  
Dates: Sep 2021 - Present

- Prev: Entrepreneurship Chair, Entrepreneurship Intern
          
As External Vice President of [UPE](https://upe.seas.ucla.edu/), I supervise UPE's Alumni, Corporate, and Entrepreneurship Committees, ensuring they meet their annual goals, host events properly, and are spending within their allocated budget. I also offer my support to any of the 6 other committees within the club. Additionally, I work closely with the Computer Science Department, ACM at UCLA, and Exploretech.LA to organize various corporate, entrepreneurship, and publicity events for the over 2000 UCLA computer science related undergraduate students. Some events I've organized or will organize are CS Townhall, CS Welcome Day, CS Career Fair, and Tech Talk with Jane Street. Something else I do is recruit companies into the Computer Science Department's affiliate system and act as liaison between the companies and the CS Department. Lastly, I provide free tutoring services in computer science coursework for 2 hrs/wk at the UPE clubhouse.

Before becoming EVP, I collaborated with Entrepreneurship Committee members to organize and host Hot Ones panel, bringing in UCLA alumni entrepreneurs to share their stories and answer questions for over 100 student attendees. I also, led a team of 3 to organize UPE Entrepreneurship's Poker and Board Game Night, providing UCLA students the opportunity to casually chat, play, and network with established entrepreneurs. Furthermore, I worked in collaboration with Bruin Entrepreneurs to organize UCLA's first Foundathon, an event for UCLA students interested in entrepreneurship with a product pitching competition and workshops. I helped develop workshops and guidelines for product pitch judging among other things.

{{< /accordion >}}

{{< accordion "Vietnamese Student Union / SEA CLEAR" >}}

Position: Workshop Facilitator  
Dates: Oct 2022 - Present

- Presented at: VSU High School Conference '22, Southeast Asian Admit Weekend '23, Southeast Asian Transfer Enrichment Day '23 

I organize and present a variety of workshops to southeast asian high school students, high school students admitted to UCLA, and propsective UCLA transfer students. These workshops range from academics to southeast asian education to mental health awareness. More specifically, the workshops I present cover topics such as race data aggregation, southeast asian deportation and representation in higher education, resume building, obtaining research and internship positions, how to network, time management, and self-care benefits and methods. In total, I have presented my workshops to approximately 175 people.

{{< /accordion >}}

{{< accordion "Vietnamese Culture Night" >}}

Position: Fiscal Committee Member  
Dates: Sep 2023 - Present

As a member of the Fiscal Committee for [Vietnamese Culture Night](https://www.instagram.com/uclavcn/?hl=en) (VCN), I primarily focus on managing and budgeting projected expenses as well as available funds for the approximately $50,000 production. More specifically, I am managing and delegating funds to the multitude of committees involved with VCN for the purchase of supplies and materials, acting as liason between VCN committees and their requests as well as POs. Additionally, I am assisting the Fiscal Head in recording all payments and reimbursements related to VCN.

{{< /accordion >}}

{{< accordion "Vietnamese Traditional Dance" >}}

Position: Dance Team Member   
Dates: Oct 2022 - Present

As a member of the Vietnamese Traditional Dance team, I get to improve my dancing skills as I work with over 30 team members to master choreography that will be performed in front of over 1800 people during Vietnamese Culture Night.

While this extracurricular does not improve my technical skills, it definitely does give me my daily exercise and helps me refresh my mental state. I highly encourage students to pursue this opportunity as being part of this team and performing in Royce Hall in front of a huge crowd is an experience money can't buy.

{{< /accordion >}}

## Awards & Recognition

<hr>

{{< accordion "MIT Climate & Energy Prize" >}}

Accepted into startup competition

{{< /accordion >}}

{{< accordion "2021 Call for Code Global Challenge" >}}

One of five regional finalist in North America

{{< button label="Feature" link="https://developer.ibm.com/callforcode/solutions/2021-solutions/#regionalfinalists" style="solid" >}}

{{< /accordion >}}

{{< accordion "2021 Verizon & CGI U Social Innovation Challenge" >}}

Beat 12 startups in startup accelerator

{{< button label="Article Mention" link="https://venturewell.org/pitch-competitions-2/" style="solid" >}}

{{< /accordion >}}

{{< accordion "IBM AI Spot Challenge" >}}

2nd place

{{< /accordion >}}

{{< accordion "IBM Code Engine Challenge" >}}

2nd place

{{< /accordion >}}

{{< accordion "Howard Hackathon for Environmental Justice" >}}

2nd place

Participated in IBM's Call for Code University Challenge: Howard Hackathon for Environmental Justice as a member of Global Flood Equity Extended Reality (later reorganized as SISYPHUS Global Systems). Worked along 4 other team members to develop the beta version of an interactive web-portal that calculates flood risk of individual properties and its optimum flood mitigation from a GIS platform with a focus on environmental justice and equity.

{{< button label="Video Shoutout" link="https://www.businessinsider.com/us-risks-climate-apartheid-if-grassroots-ideas-ignored-activist-says-2021-4" style="solid" >}}

{{< /accordion >}}