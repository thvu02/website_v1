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

I started my journey with [Sandia National Laboratories](https://www.sandia.gov/) as a summer Cybersecurity R&D intern. For 10 weeks in Albuquerque, New Mexico, I worked on two projects: operational technology (OT) network activity analysis and browser exploits. For the first project, I used unsupervised learning techniques such as clustering and decision trees to pinpoint what traits constitute malicious MODBUS behavior. MODBUS is a communication protocol commonly used by OT devices. Taking that understanding, I attempted to write rules on Splunk that would automatically flag suspicious network activity and generate summary reports. For the second project, I first looked into a zero-day exploit called patch gapping that was used on Chromium to build a firm understanding of how Chromium's V8 Engine worked. From there, I proceeded to analyze HAR data to find browser exploit indicators and also worked to determine if browser isolation can protect users from zero-day exploits.

At the end of summer, I converted to a year-round Cybersecurity R&D intern where I remotely continuing working on the OT project. I wanted to continue working on both projects, but year-round interns can only work on one project since Sandia wants interns to focus on school (rightfully so). At the moment, I'm still working on the writing rules on Splunk to flag suspicious network activity. However, I'm also taking up some additional responsibility as I get to work on writing Python scripts that aggregate Sandia's IT and OT device inventory datasets to provide enriched and more accesible device information for Sandia staff.

I can't provide more details about the work I do for security reasons. But, I'd be more than happy to talk about living in Albuquerque and the Center for Cyber Defenders (CCD) internship program in general. Interning at Sandia is a great way to enter cybersecurity and I recommend those interested in the field to apply!

{{< /accordion >}}

{{< accordion "NASA Jet Propulsion Laboratory" >}}

Position: Data Science Intern   
Dates: Jun 2022 - Sep 2022

At [JPL,](https://www.jpl.nasa.gov/) my goal was to use a deep learning approach to reconstruct Earth's historical global warming rate and reliably predict its future trend using a combination of input features, including both natural and human-caused climate drivers. With a well-trained deep neural network (DNN), I was to reaffirm the ongoing warming acceleration and gain a reliable prediction of its future trend, which will give humanity an early alarm on when a “tipping point” in climate change will come.

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

[Scalable Analytics Institute](https://scai.cs.ucla.edu/) (ScAI) is one of the research labs within the Computer Science Department at UCLA and is directed by Professor [Wei Wang.](https://web.cs.ucla.edu/~weiwang/) The lab covers multiple areas of research, but I'm specifically working on Graph-based Analytics for biomedicine.

Bioconjugation chemistries are generally designed to be chemoselective and thus react only with a select amino acid side chain types. However, when multiple copies of the same residue type are present on a protein, their relative reactivities, site selectivity, is governed by the local microenvironment surrounding each site. Predicting site selectivity of bioconjugation reagents for a given protein is an outstanding challenge which the UCLA ScAI lab and UC Berkeley Toste Lab aim to address.

My research is on applying graph neural networks (GNN) to predict protein site modification. The goal is to develop a GNN that can reliably predict protein modification status. The reason why I'm using GNNs is because, unlike typical ML models, GNNs can take advantage of the structural properties of proteins and potentially yield more accurate prediction results.

Given protein data compiled by UC Berkeley's Toste, I needed to convert the data into a graphical structure so it can be fed into the GNN. To do this, I represented each amino acid in a protein as a node containing features such as the amino acid’s bespoke descriptors and three-dimensional structure. I then scaled these features to ensure one feature does not have greater influence over others when fed into the GNN. Since features such as “atom element” are composed of categorical values, they are one-hot encoded to prevent unintentional ordinal bias. After all of that, I used the raw three dimensional structure data of each amino acid to draw edges between nodes within 8 angstroms of one another. The justification behind choosing 8 as this threshold stems from the results of papers using other thresholds. After this process is done for each protein, I saved the information to a binary file so this computation does not have to be done again and now have a dataset that can be fed into the GNN. To speed up the preprocessing of the protein data, I used the joblib library to utilize multiprocessing. This was necessary as some protein data provided by the Toste Lab would have taken over 25 labs to completely process (this is an optimistic estimate). With multiprocessing, the process was still long, but shortened to 1.0-2.5 days.

I developed the GNN using Deep Graph Library (DGL). The GNN is composed of 3-layers with a sigmoid activation function for each hidden layer. Taking the produced graphs, I did an 80/20 split to use 80% of the dataset for training the GNN and the remaining 20% for testing. Furthermore, to increase computational efficiency and generalization, I performed batching on the graphs in the training and testing datasets. Batching is a technique where sample graphs are combined into a single, bigger, batched graph. The resulting graph is a merge of all the sample graphs as separately connected components without losing any of the information held within each sample graph. I organized the graphs in the training and testing datasets in batches of 20. With the training and testing data prepared and the GNN developed, I proceeded to train the GNN.

The training loop of the GNN iterates over all the batched graphs for 20 epochs. My loss function only considers the amino acid of interest (methionine or tryptophan) and I used the AdamW optimizer to update the model parameters. After the GNN is trained, I ran the test dataset through the model and output performance metrics such as accuracy, precision, recall, and f1-score to evaluate its performance.

Preliminary results dictated that the GNN is not able to effectively predict site selectivity of bioconjugation reagents. However, modifying certain parameters like angstrom threshold, number of GNN layers, activation functions, batch size, and optimizers can potentially yield better performance metrics. This is what I'm working on right now. It is clear though that the GNN is suffering from an imbalanced dataset since the ratio of modified amino acids to unmodified amino acids is extremely skewed. Of course, the dataset can be artificially balanced, but then that doesn't create a realistic environment since in real life, we don't expect to see many (if any) amino acids modified per protein. Therefore, I am currently working with Toste Lab to see if more feature information can be provided in the raw dataset, so the GNN has more data to utilize. Furthermore, I am exploring techniques such as GraphSMOTE which can potentially address imbalanced node classification with GNNs.

{{< /accordion >}}

{{< accordion "UCLA Samueli School of Engineering" >}}

Position: Group Tutor and Researcher  
Dates: Sep 2021 - Present

- Taught: Fall 21, Spr 22, Fall 22, Fall 23       
- Will be teaching: Spr 24

After taking the course in winter quarter 2021, I joined the teaching staff of Engineering 96i: Internet of Things as a Group Tutor in fall quarter 2021. As a Group Tutor, I assist Professor William Kaiser in teaching over 150 students how to develop IoT motion detection functionality using the STMicroeletronics SensorTile and EmbeddedML Neural Network. More specifically, I teach students about C programming, the STM32L4 microprocessor on the [<u>STMicroelectronics SensorTile,</u>](https://www.st.com/en/evaluation-tools/steval-stlkt01v1.html#st_description_sec-nav-tab) and machine learning. This is to have them develop a solid foundation on which they can begin developing their own IoT motion detection device using the SensorTile's accelerometer and gyroscope. As students develop their own projects, I help them debug code and provide insight on how to expand the neural network to realize their project ideas.

Beyond Engineering 96i, I also assist Professor Kaiser in teaching Engineering 96c: Cybernetics by tutoring students in robotic control systems and teaching them how to use MATLAB. After giving students enough background knowledge, I guide them in developing their own cybernetics project. Unfortunately, this course isn't being offered anymore.

Outside the classroom, I am working to refine Engineering 96i. More specifically, I am reviewing the current tutorials being used for the course to identify points where clarity can be improved and patch inconsistencies. I am also compiling a comprehensive course guidebook with tutorial solutions and insightful hints that course instructors and Group Tutors can utilize to better and more easily help students. Furthermore, I am developing and testing learning modules using the [<u>B-U585I-IOT02A IoT node</u>](https://www.st.com/en/evaluation-tools/b-u585i-iot02a.html#) for future adaptation into the course since this IoT device will be replacing the SensorTile.

Joining the Engineering 96i teaching staff was one of the best decisions I've made at UCLA as it allowed me to combine my passions of tech and service. Tutoring for multiple iterations of the course over the past 2 years, I feel great satisfaction helping students build their skillsets and develop projects they can highlight during interviews. Alongside teaching, I'm proud of the technical accomplishments I've made towards improving the course. Using the draft course guidebook I compiled over summer, the Group Tutors this fall quarter complimented on how it allowed them to better help students and quickly identify solutions to the issues students were facing. With the R&D I'm doing with the new IoT node, I hope to contribute major refinements to the course material so students at UCLA and other education institutions which use this material for their own IoT courses have an even better experience when taking the course.

{{< /accordion >}}

{{< accordion "UCLA Extension" >}}

Position: Instructor Aide  
Dates: Sep 2023 - Sep 2023

UCLA Extension's [Technical Management Program](https://www.uclaextension.edu/engineering/technical-management-program) (TMP) is a week-long program designed to improve the leadership and management skills of aspiring and current technical managers in industry. This is done through a variety of workshops which help managers gain leadership skills, enrich interpersonal skills, and discover a library of methods to resolve issues, plan effectively, and motivate staff members.

As a Instructor Aide, I worked alongside 5 other aides to assist office staff and instructors in facilitating leadership and management workshops for over 130 technical managers from companies such as Blizzard, Credit Karma, Sandia National Laboratories, and Lawrence Livermore National Laboratories. The days were long and hard. It wasn't your typical CS job where you sit in a chair, think, and write code all day. I was moving around doing print jobs, setting up banners, etc. But I got to participate in the workshops I TA-ed for and engage with the managers in various activities and exercises, so that's a plus.

Naturally, my position had me working with the TMP organizers which consisted of Joon Lee, Gina Springer, and Nicole Lim. While I understood that Joon was my boss, the work dynamic felt more like a nephew working with his cool uncle. I had great conversations with Joon as well as Gina and Nicole, and they were all very kind and understanding. Dr. William Goodin would sometimes stop by as well since he was the previous director of the program. It was great getting to talk and joke around with him as I work with Dr. Goodin as EVP for UPE, but never got to interact with him much through that position. As TMP progressed, I got to engage with Dr. Goodin and built a strong working relationship with him. We discussed UPE objectives, but also talked about more casual topics such as the food or his unique set of UCLA themed ties.

Speaking of food, the catering for TMP was amazing! I was excited for every single meal and enjoyed everything I got served. I remember raving about the bacon the most as it was different each day. I ranked the bacon quality each day and even had a passionate debate with the other Instructor Aides about which bacon was best. By the end of TMP, I think everyone knew I loved bacon.

Beyond food, TMP was great in that I developed connections with the technical managers and got referrals from them. Furthermore, my time with TMP brought to light my growth as a leader. On the last day of the program, I remember Joon saying that I was like the leader of the Instructor Aides. He said that I initially seemed shy, but he saw me become more open as the program progressed and how the other Instructor Aides sort of followed and looked up to me. I didn't expect to hear this. Even though I hold multiple leadership positions, I never saw myself as a leader. I felt that me and the other Instructor Aides were all equals. It never felt as if I was the one leading or being looked up to. Hearing that compliment from Joon boosted my confidence and belief that I can be a strong leader. Also, I think not realizing this fact is also a good thing because I don't want to be a leader that stands above my team. Instead, I want to be a leader that stands alongside my team and promotes a positive, friendly working environment.

Wrapping all this up, TMP is a wonderful program and being an Instructor Aide for this program is a great opportunity to network with technical managers across various industries and develop leadership skills.

{{< /accordion >}}

{{< accordion "VentureWell" >}}

Position: Tech Innovator   
Dates: Jun 2021 - Sep 2021

[VentureWell,](https://venturewell.org/) alongside Verizon and Clinton Global Initiative University (CGI U), hosted a startup accelerator which I participated in as a representative of SISYPHUS Global Systems along with some other SISYPHUS staff. The startup accelerator was called Verizon and CGI U Social Innovation Challenge and is the first of three phases for VentureWell's E-Team program. The three phases, in order, are Pioneer, Propel, and Aspire.

During this program, I planned value proposition, determined value chain, computed competitive analysis, identified product-market fit, and conducted informational interviews with various subject experts in environmental science, urban planning, and engineering. This allowed me to better orient SISYPHUS's product to ensure the most success and opened my eyes to all the factors that need to be considered when creating a product. Beyond this, I attended workshops to develop the entrepreneurial skills necessary to successfully launch a startup and participated in coaching and mentorship sessions with Verizon and VentureWell staff to refine SISYPHUS's technology stack and marketing strategies. Going through all these exercises and sessions, I was able to help SISYPHUS improve not only its web-app product, but also how the company pitched the product. 

When the program reached the final stages, all the startup teams participating were told that they'd be doing a product pitch to a panel composed of VentureWell, Verizon, and CGI U staff. The performance of each startup on this product pitch would determine whether they can move to the next stage of VentureWell's E-Team program, Propel. I was slightly worried for SISYPHUS because the startup was quite young compared to the other startups. Additionally, the other startups had more staff and connections than us. Nevertheless, I didn't show fear and prepared for the product pitch competition with confidence.

I worked with the SISYPHUS team to organize our product pitch and presented it to Clinton Foundation Vice Chair Chelsea Clinton, Verizon representative Nicki Palmer, and VentureWell CEO Phil Weilerstein. Despite initial fears of not being good enough to beat the other startups, the product pitch my team gave was much stronger than that of our peers. My team beat the 12 other startups in the program and secured SISYPHUS a slot in VentureWell's second phase of the E-Team program. Unfortunately, the Propel stage was going to start when school would start, so I decided to yield my spot on SISYPHUS's team to another SISYPHUS staff member.

All in all, I received a lot from participating in this startup accelerator. I knew that launching a startup was no easy task, but I didn't realize it was so complex. This program opened my eyes to perspectives I've never considered before and taught me many skills that I never would have learned in my major coursework. Furthermore, seeing all the unique problems each startup in the program attempted to solve made me realize how many issues the world is currently facing and bolstered my motivation to utilize my skillset towards societal betterment. Lastly, participating in this program taught me to be confident in myself regardless of the odds and to never back down from a challenge. The lessons and realizations I gained from this program changed my perspective on my undergraduate education and put me on the path to where I am today. If I didn't participate in this program, I don't think I would be anything near what I am now.

{{< /accordion >}}

## Extracurriculars

<hr>

{{< accordion "Upsilon Pi Epsilon (CS Honors Society)" >}}

Position: External Vice President  
Dates: Sep 2021 - Present

- Prev: Entrepreneurship Chair, Entrepreneurship Intern

[Upsilon Pi Epsilon](https://upe.acm.org/) (UPE) is the international honor society for the computing and information disciplines. UPE was founded at Texas A&M University, College Station, Texas in 1967 and since then has chapters at various colleges and universities such as UCLA, Berkeley, Georgia Tech, CPP, and USC. The UCLA chapter of UPE serves as the premier honor society for the following computing majors: CS, CSE, CE, Ling & CS, Math of Comp. I inducted into UPE in Fall 2021 and am currently the External Vice President (EVP).

As EVP of [UCLA UPE,](https://upe.seas.ucla.edu/) I supervise three of UPE’s committees: Alumni, Corporate, and Entrepreneurship. Supervising these committees means ensuring they meet their annual goals, host events properly, and do not exceed their allocated budget. I provide the committees guidance and suggestions while they plan events, giving date suggestions that would yield greater attendance, alternative plans that would keep them within budget, and resources to contact potential guest speakers or companies. Under my supervision, the Alumni Committee has hosted successful alumni dinners, alumni mentorship programs, and virtual panels, the Entrepreneurship Committee has hosted a successful Hot Ones Panel, resume review session, and multiple networking nights, and the Corporate Committee has hosted multiple networking and recruiting events with companies like Lockheed Martin. 

Another responsibility I have as EVP is being liaison between UPE and the CS Department as well as the other engineering honors societies at UCLA. I facilitate meetings between UPE and CS Department staff to discuss the affiliate program and EDI initiatives. I also ensured effective communication between both parties while planning large-sacle welcome events and career fairs for the over 2000 UCLA computer science related undergraduate students. With the other honors societies, I’d occasionally communicate and collaborate to organize joint events or discuss methods to improve member retention as well as involvement.

Lastly, I provide free tutoring services in computer science coursework for 2 hrs/wk at the UPE clubhouse. One of UPE's greatest services to the UCLA community is our tutoring services. We have all our officers either tutor or supervise the tutoring room each week and have our inductees support the tutoring room as well. Our tutoring service is quite popular as the room is always packed when a big deadline approaches. It's unfortunate that we can't get a bigger to support the amount of traffic we get, but I'm just happy that I can help other students succeed in their coursework.

Beyond my primary responsibilities as EVP, one of my goals is improving the CS Department’s industry affiliate program benefits to attract more companies into the program and increase the amount of companies UCLA students can network with. To that end, I have conducted interviews with companies of all levels to understand their budgets and needs. I then used that data to successfully negotiate modifications to the affiliate program, with the most impactful modification being a new $500 first-year trial for startup affiliates that addresses financial concerns of startups interested in joining the program. This effort has resulted in Jane Street and Glean joining the affiliate program. Having recruited more companies into the affiliate program, my next goal was to increase engagement with them. I helped Jane Street host their first event as an affiliate member, working with company representatives to organize a tech talk led by one of their software engineers that was attended by 160 students. Additionally, I organized a tech talk with another affiliate, Sandia National Laboratories, where a software engineer highlighted the complex challenges Sandia tackles daily and the advanced tech stack they utilize. I worked with Sandia National Laboratories to host a hackathon as well. Furthermore, I collaborated with the UCLA CS Department to organize a career fair for our industry affiliates and UCLA Computer Science students, with over 800 students attending. Hosting all these professional events with the industry affiliates has improved the relationship between them, the CS Department, and UPE, and has also provided students valuable networking experiences from which many gained internships. 

Knowing that not all students are interested in immediately entering the workforce and want to pursue a Master's or PhD instead, I am also putting effort into bringing engineering graduate schools to UCLA. More specifically, I have collaborated with ACM to bring the Cornell Tech graduate school admissions team to UCLA and have them network with students. The collaboration with Cornell Tech included a workshop providing tips and tricks in creating a strong application, financial aid, and how to succeed in industry. As such, even if students did not intend to apply to Cornell, they still left with advice that is applicable to applying to any other university. Though I’ve been able to significantly improve the CS Department’s industry affiliate program, improve the relationship with current affiliates, and provide more resources to students pursuing graduate school, I know there is much more I can do and will be dedicating the remainder of my term towards this end.

Given UPE's collaborative nature, committees often plan joint events and help one another. Though these committees are not technically under my supervision, I provide my services to the other 8 committees in UPE, volunteering at or helping plan events. Some events I have helped with are Induction Orientation Mixer, Summer Planning Workshop, Tech in the Park, CS Townhall, CS Welcome Day, UPE Intro Event, Demystifying CS Clubs, and Engineering Welcome Day.

Before becoming EVP, I collaborated with Entrepreneurship Committee members to organize and host Hot Ones panel, bringing in UCLA alumni entrepreneurs to share their stories and answer questions for over 100 student attendees. I also led a team of 3 to organize UPE Entrepreneurship's Poker and Board Game Night, providing UCLA students the opportunity to casually chat, play, and network with established entrepreneurs. Furthermore, I worked in collaboration with Bruin Entrepreneurs to organize UCLA's first Foundathon, an event for UCLA students interested in entrepreneurship with a product pitching competition and workshops. I helped develop workshops and guidelines for product pitch judging among other things.

This is already getting quite long, so I'm refraining from expanding on the other miscellaneous things I do as EVP as well as what I did before becoming EVP. But if you're curious about that, read this [blog post]() I made about my journey with UPE.

{{< /accordion >}}

{{< accordion "Vietnamese Student Union / SEA CLEAR" >}}

Position: Workshop Facilitator  
Dates: Oct 2022 - Present

- Presented at: VSU High School Conference '22, Southeast Asian Admit Weekend '23, Southeast Asian Transfer Enrichment Day '23 

UCLA's Vietnamese Student Union and Southeast Asian Campus Learning Education and Retention program (SEA CLEAR) are different entities, but they collaborate so much to the point where I just consider them as one. The two clubs host a variety of programs targeted towards Southeast Asian students from the around LA area. These include High School Conference (HSC) for high school students, Southeast Asian Admit Weekend (SEA ADMIT) for high school students admitted to UCLA, and Southeast Asian Transfer Enrichment Day (SEATED) for prospective UCLA transfer students. I served as a Workshop Facilitator for all of these programs.

As a Workshop Facilitator, I organize and present a variety of workshops covering a range of topics including academics, Southeast Asian education, and mental health. More specifically, the workshops I present cover topics such as race data aggregation, southeast asian deportation and representation in higher education, resume building, obtaining research and internship positions, how to network, time management, and self-care benefits and methods. In total, I have presented my workshops to approximately 175 people.

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

{{< accordion "UPE National Scholarship" >}}

Each year the Executive Council of Upsilon Pi Epsilon evaluates many scholarship applications from students at both the undergraduate and graduate levels. All scholarship applicants are required to complete a comprehensive application form including a statement on their long-term plans in the profession, a summary of their contributions to their respective UPE chapters and related student activities at their college or university. Applicants are also required to submit all college-level transcripts and a recommendation from the UPE faculty adviser.

Received $1,000 scholarhip from UPE national for demonstrating exceptional academic record, extra-curricular activities and strong recommendation from UPE Advisor.

{{< /accordion >}}

{{< accordion "Computer Science Wang NSF REU" >}}

Received $1,500 scholarship to perform research on applying graph neural networks to protein modification prediction with UCLA Scalable Analytics Institute lab and Berkeley Toste lab.

{{< /accordion >}}

{{< accordion "MIT Climate & Energy Prize" >}}

Accepted into startup competition.

{{< /accordion >}}

{{< accordion "2021 Call for Code Global Challenge" >}}

One of five regional finalist in North America.

{{< button label="Feature" link="https://developer.ibm.com/callforcode/solutions/2021-solutions/#regionalfinalists" style="solid" >}}

{{< /accordion >}}

{{< accordion "2021 Verizon & CGI U Social Innovation Challenge" >}}

Beat 12 startups in startup accelerator.

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