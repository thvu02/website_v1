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

I started my journey with [Sandia National Laboratories](https://www.sandia.gov/) as a summer Cybersecurity R&D intern. For 10 weeks in Albuquerque, New Mexico, I worked on two projects: operational technology (OT) network activity analysis and browser exploits. For the first project, I used unsupervised learning techniques such as clustering and decision trees to pinpoint what traits constitute malicious MODBUS behavior. MODBUS is a communication protocol commonly used by OT devices. Taking that understanding, I attempted to write rules on Splunk that would automatically flag suspicious network activity and generate summary reports. For the second project, I investigated a zero-day exploit called patch gapping that was used on Chromium to build a firm understanding of how Chromium's V8 Engine worked. From there, I proceeded to analyze HAR data to find browser exploit indicators and worked to determine if browser isolation can protect users from zero-day exploits.

I transferred to Sandia’s California site the next summer where I continued working on my OT project and started a new project for a [DHS]( https://www.dhs.gov/) client. For the OT project, I continued writing Splunk alerts to flag suspicious network activity, but I also began developing Python scripts to aggregate Sandia’s IT and OT device inventory datasets to provide enriched and more accessible data for Sandia’s incident responders. For the DHS project, I designed dashboards to aggregate risk and visibility assessment data from various clients and developed those dashboards using HTML and CSS.

I landed my internship with Sandia without any cybersecurity knowledge, and I’ve been able to learn a lot through the company. If you have any interest in breaking into cybersecurity, consider applying for the Center for Cyber Defenders (CCD) internship program! Interning at Sandia is a great way to enter cybersecurity and having their name on your resume will greatly increase your odds of working at any other national laboratory.


{{< /accordion >}}

{{< accordion "NASA Jet Propulsion Laboratory" >}}

Position: Data Science Intern   
Dates: Jun 2022 - Sep 2022

At [JPL,](https://www.jpl.nasa.gov/) my goal was to use a deep learning approach to reconstruct Earth's historical global warming rate and reliably predict its future trend using a combination of input features, including both natural and human-caused climate drivers. With a well-trained deep neural network (DNN), I was to reaffirm the ongoing warming acceleration and gain a reliable prediction of its future trend, which will give humanity an early alarm on when a “tipping point” in climate change will come.

To this end, I analyzed surface temperature anomalies from 1850-2021 using the Berkeley Earth dataset, determining that regional warming occurs at varying rates. I observed that the Arctic began increasing in temperature faster than other regions (Tropics, Antarctic) starting in 2010 and found papers discussing the Arctic amplification phenomenon to support this observation. With that discovery, I pivoted to analyze latitude-dependent surface temperature simulations from CMIP6 models to understand their behavior and reliability. I attempted to determine whether CMIP6 models emulated observed regional and globally warming trends and whether large variance existed between different CMIP6 models and their regional/global temperature projections. CMIP6 models were designed specifically by climate scientists to consider human and natural factors that will impact climate and use those to accurately project future climates. If CMIP6 models are reliable, they would be a great training dataset for the DNN.

Using CMIP6 data from ESGF, I determined there exists a large variance between different CMIP6 models and their regional/global temperature projections. Due to this, I analyzed 65 CMIP6 models to identify “best-performing” models based on regional and global surface temperature anomaly accuracy with observed data. From the analysis, I compiled a 16-model ensemble composed of “best-performing” CMIP6 models to have a strong training dataset for my DNN. To prove that the ensemble was worthy to use as a training dataset, I demonstrated that it performs relative to observational data globally and regionally. As a bonus, I also utilized the ensemble to project surface temperatures from 2015 to 2075 under various shared socio-economic pathways (SSP), highlighting the need and impact of immediate climate mitigation and adaptation.

With a strong training dataset, I developed a DNN using PyTorch and trained it using the ensemble to the point where it can affirm ongoing warming acceleration and predict when a 2.0-2.5°C warming (a “tipping point” in climate change) will occur. The work I produced from this internship allowed me to have the 2nd best presentation out of all other JSIP interns for our final presentations.

This internship opportunity was achieved through [UCLA's Joint Institute for Regional Earth and System Science & Engineering](https://jifresse.ucla.edu/) (JIFRESSE) which is a scientific collaboration between UCLA and JPL. I encourage all those interested in tackling climate change to explore this opportunity!

{{< /accordion >}}

{{< accordion "SISYPHUS Global Systems" >}}

Position: Software Engineering Intern   
Dates: Mar 2021 - Jun 2022

[SISYPHUS Global Systems](https://sisyphus-gs.com/) is a climate tech startup developing a web-portal that utilizes ArcGIS maps and WebXR to provide users an immersive augmented reality experience of assessing their property's flood risk and viewing their city's green and grey infrastructure. Their AI model is designed to predict flood risk for individual properties and visualize potential damage via 3D rendered maps of city infrastructure. This product will be useful for individual homeowners as well as officials as city planners implement flood mitigation strategies.

During my internship, I helped develop green and grey infrastructure maps for New Orleans, LA with ArcGIS API for JavaScript to improve the company's GIS database and disaster risk/mitigation method calculations. I also researched and implemented several IBM software, such as Watson Assistant, App Connect, Code Engine, and etc., into the product's system architecture. Furthermore, I played a key role in re-designing the company's website to intricately showcase the product and its underlying tech stack, enhancing the company's ability to appeal to both customers and investors. Lastly, I managed and maintained the company's code-base on GitHub using Git version control.

I enjoyed working at SISYPHUS because I got exposed to various pieces of technology and was doing something new almost every week. This is very different than working at a large, well-established company where you just stick to one or two things. Participating in various hackathons with the company, I got to explore various open-source software and figure out how to integrate each technology into the company's system architecture. Beyond this, working at a startup let me experience more than the engineering side of a company. I learned various entrepreneurial skills like competitive analysis, value chain analysis, identifying market-fit, etc. I also learned how LLC creation laws differed in each state and the pros/cons of claiming intellectual property in broad/specific manners. Lastly, working at SISYPHUS gave me personal satisfaction as I know the product I'm helping develop is designed specifically to tackle the impending effects of climate change and the combat the systemically racist settlement patterns in American cities. Sadly, exploitation and gentrification have resulted in wealthy (mostly white) populations settling in geographically high-lying areas whilst low-income, minority populations are left to settle in low-lying areas with greater flood risk and less flood protection. While SISYPHUS's product will help everyone protect their properties from flood damage, the product will bring about some equity by providing underserved, low-income, minority communities with a free resource to protect their properties.

{{< /accordion >}}

## Research

<hr>

{{< accordion "Computer-Aided Drug Design Group" >}}

Position: Machine Learning Researcher   
Dates: Aug 2024 - Present

[Computer-Aided Drug Design Group](https://sites.google.com/site/lynayunluo/) is research group at [Western University of Health Sciences](https://www.westernu.edu/) directed by [Dr. Yun (Lyna) Luo.](https://www.westernu.edu/bios/?bio=luoy) There are many projects within the lab, but the one I'm working on is identifying efficient methods to cluster compounds.

Take this explanation with a grain of salt because I have no medical background, but basically, drug discovery is a field in the medical industry that involves discovering new medications. Obviously, drug discovery is important because that's how we find cures to diseases and etc. Traditionally, drug discovery has been done using physical testing of compounds. You can imagine that it's a very time-consuming process to test each compound because you have to put the experimental compound on trays with each of the testing compounds, let it do magical medical stuff, record results, and move to the next. As technology evolved, this physical process has been moved over to software where processes like virtual screening and docking allow you to experiment with compounds significantly faster than doing it manually. These processes take several seconds to run for each compound, which seems short, but there are over 10^16 compounds out there (that's what I heard). Even with all the computational power in the world, it's going to take too long to test every single compound with software. That's where we hope AI can come in. Compounds have certain properties and scores associated with them that denote how well they bind to other compounds. With AI, we can cluster compounds and come up with a subset of compounds that are most likely to be successful in fulfilling our goals. That's what my research project centers around.

There's two parts to what I'm doing. First, current clustering algorithms don't have great time/space complexity, so they don't scale well enough to handle datasets with millions/billions of data points. Publications are constantly releasing new algorithms though, so I'm testing them to see if they work for us. One I'm focusing on is BitBirch. The algorithm was developed by a lab at the University of Florida and it's so new that it hasn't even been peer reviewed yet. Second, there's no standardized set of features/properties to cluster from and there are a variety of methodologies to score compounds. This can be the type of software used (e.g. Glide, Vina, etc.), the resolution at which you analyze compounds, the fingerprinting method, and etc.. Different methods of clustering may be more productive than others so I'm currently working to identify the best set of features/properties.

The lab recently started collaborating with TandemAI, a drug discovery company based in New York, to combine our knowledge and hopefully produce promising research. I've only spent a short amount of time with this lab, but I love the collaborative and supportive culture here. It's also a nice change of pace to work with medical students/faculty instead of computer science students/faculty. My research has been going quite well, so I hope I can turn this work into my Master's thesis in the future.

{{< /accordion >}}

{{< accordion "Scalable Analytics Institute" >}}

Position: Machine Learning Researcher  
Dates: Apr 2023 - Jun 2024

[Scalable Analytics Institute](https://scai.cs.ucla.edu/) (ScAI) is one of the research labs within the Computer Science Department at UCLA and is directed by Professor [Wei Wang.](https://web.cs.ucla.edu/~weiwang/) The lab covers multiple areas of research, but I'm specifically working on Graph-based Analytics for biomedicine.

Bioconjugation chemistries are generally designed to be chemoselective and thus react only with a select amino acid side chain types. However, when multiple copies of the same residue type are present on a protein, their relative reactivities, site selectivity, is governed by the local microenvironment surrounding each site. Predicting site selectivity of bioconjugation reagents for a given protein is an outstanding challenge which the UCLA ScAI lab and UC Berkeley Toste Lab aim to address.

My research is on applying graph neural networks (GNN) to predict protein site modification. The goal is to develop a GNN that can reliably predict protein modification status. The reason why I'm using GNNs is because, unlike typical ML models, GNNs can take advantage of the structural properties of proteins and potentially yield more accurate prediction results.

Given protein data compiled by UC Berkeley's Toste, I needed to convert the data into a graphical structure so it can be fed into the GNN. To do this, I represented each amino acid in a protein as a node containing features such as the amino acid’s bespoke descriptors and three-dimensional structure. I then scaled these features to ensure one feature does not have greater influence over others when fed into the GNN. Since features such as “atom element” are composed of categorical values, they are one-hot encoded to prevent unintentional ordinal bias. After all of that, I used the raw three dimensional structure data of each amino acid to draw edges between nodes within 8 angstroms of one another. The justification behind choosing 8 as this threshold stems from the results of papers using other thresholds. After this process is done for each protein, I saved the information to a binary file so this computation does not have to be done again and now have a dataset that can be fed into the GNN. To speed up the preprocessing of the protein data, I used the joblib library to utilize multiprocessing. This was necessary as some protein data provided by the Toste Lab would have taken over 25 labs to completely process (this is an optimistic estimate). With multiprocessing, the process was still long, but shortened to 1.0-2.5 days.

I developed the GNN using Deep Graph Library (DGL). The GNN is composed of 3-layers with a sigmoid activation function for each hidden layer. Taking the produced graphs, I did an 80/20 split to use 80% of the dataset for training the GNN and the remaining 20% for testing. Furthermore, to increase computational efficiency and generalization, I performed batching on the graphs in the training and testing datasets. Batching is a technique where sample graphs are combined into a single, bigger, batched graph. The resulting graph is a merge of all the sample graphs as separately connected components without losing any of the information held within each sample graph. I organized the graphs in the training and testing datasets in batches of 20. With the training and testing data prepared and the GNN developed, I proceeded to train the GNN.

The training loop of the GNN iterates over all the batched graphs for 20 epochs. My loss function only considers the amino acid of interest (methionine or tryptophan) and I used the AdamW optimizer to update the model parameters. After the GNN is trained, I ran the test dataset through the model and output performance metrics such as accuracy, precision, recall, and f1-score to evaluate its performance.

Preliminary results dictated that the GNN is not able to effectively predict site selectivity of bioconjugation reagents. However, modifying certain parameters like angstrom threshold, number of GNN layers, activation functions, batch size, and optimizers can potentially yield better performance metrics. This is what I'm working on right now. It is clear though that the GNN is suffering from an imbalanced dataset since the ratio of modified amino acids to unmodified amino acids is extremely skewed. Of course, the dataset can be artificially balanced, but then that doesn't create a realistic environment since in real life, we don't expect to see many (if any) amino acids modified per protein. Therefore, I am currently working with Toste Lab to see if more feature information can be provided in the raw dataset, so the GNN has more data to utilize. Furthermore, I am exploring techniques such as GraphSMOTE which can potentially address imbalanced node classification with GNNs.

{{< /accordion >}}

## Other Employment
<hr>

{{< accordion "UCLA Samueli School of Engineering" >}}

Positions: Group Tutor, Researcher, and Teaching Assistant  
Dates: Sep 2021 - Jun 2024

- Taught: Fall 21, Spr 22, Fall 22, Fall 23, Spr 24    

After taking the course in winter quarter 2021, I joined the teaching staff of Engineering 96i: Internet of Things as a Group Tutor in fall quarter 2021. As a Group Tutor, I assisted [Professor William Kaiser](https://www.ee.ucla.edu/william-kaiser/) in teaching over 150 students how to develop IoT motion detection functionality using the STMicroeletronics SensorTile and EmbeddedML Neural Network. More specifically, I taught students about C programming, the STM32L4 microprocessor on the [STMicroelectronics SensorTile,](https://www.st.com/en/evaluation-tools/steval-stlkt01v1.html#st_description_sec-nav-tab) and machine learning. This was to have them develop a solid foundation on which they can begin developing their own IoT motion detection device using the SensorTile's accelerometer and gyroscope. As students developed their own projects, I helped them debug code and provided insight on how to expand the neural network to realize their project ideas.

Beyond Engineering 96i, I also assisted Professor Kaiser in teaching Engineering 96c: Cybernetics by tutoring students in robotic control systems and teaching them how to use MATLAB. After giving students enough background knowledge, I guided them in developing their own cybernetics project. Unfortunately, this course isn't being offered anymore.

Outside the classroom, I worked to refine Engineering 96i. More specifically, I reviewed the current tutorials being used for the course to identify points where clarity can be improved and patched inconsistencies. I also compiled a comprehensive course guidebook with tutorial solutions and insightful hints that course instructors and Group Tutors can utilize to better and more easily help students. Furthermore, I developed learning modules using the [B-U585I-IOT02A IoT node](https://www.st.com/en/evaluation-tools/b-u585i-iot02a.html#) for future adaptation into the course since this IoT device will be replacing the SensorTile.

Joining the Engineering 96i teaching staff was one of the best decisions I've made at UCLA as it allowed me to combine my passions of tech and service. Having tutored multiple iterations of the course for 3 years, I feel great satisfaction helping students build their skillsets and develop projects they can highlight during interviews. Alongside teaching, I'm proud of the technical accomplishments I made towards improving the course. Using the draft course guidebook I compiled over summer, the new Group Tutors commented on how it allowed them to better help students and quickly identify solutions to the issues students faced. I hope the R&D I did contributes major refinements to the course so students at UCLA and other education institutions which use the material for their own IoT courses have an even better learning experience when taking the course.

As of Spring 2024, the IoT course is now being taught by [Professor Hooman Darabi,](https://scholar.google.com/citations?user=LGSleTsAAAAJ&hl=en) and as of Fall 2024, the course has been renamed to Engineering 1IT: Internet of Things.

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
Dates: Sep 2021 - Jun 2024

- Prev: Entrepreneurship Chair, Entrepreneurship Intern

[Upsilon Pi Epsilon](https://upe.acm.org/) (UPE) is the international honors society for the computing and information disciplines. UPE was founded at Texas A&M University, College Station, Texas in 1967 and since then has chapters at various colleges and universities such as UCLA, Berkeley, Georgia Tech, CPP, and USC. The UCLA chapter of UPE serves as the premier honor society for the following computing majors: CS, CSE, CE, Ling & CS, Math of Comp. I inducted into UPE in Fall 2021 and ended as the External Vice President (EVP).

As EVP of [UCLA UPE,](https://upe.seas.ucla.edu/) I supervised three of UPE’s committees: Alumni, Corporate, and Entrepreneurship. Supervising these committees meant ensuring they met their annual goals, hosted events properly, and did not exceed their allocated budget. I provided the committees guidance and suggestions while they planned events, giving date suggestions that would yield greater attendance, alternative plans that would keep them within budget, and resources to contact potential guest speakers or companies. Under my supervision, the Alumni Committee hosted successful alumni dinners, alumni mentorship programs, and virtual panels; the Entrepreneurship Committee hosted a successful Hot Ones Panel, resume review session, and multiple networking nights; and the Corporate Committee hosted multiple networking and recruiting events with companies like Lockheed Martin, Sandia National Laboratories, and DRW.

Another responsibility I had as EVP was being liaison between UPE and the CS Department as well as the other engineering honors societies at UCLA. I facilitated meetings between UPE and CS Department staff to discuss the affiliate program and EDI initiatives. I also ensured effective communication between both parties while planning large-scale welcome events and career fairs for the over 2000 UCLA computer science related undergraduate students. With the other honors societies, I collaborated to organize joint events or discuss methods to improve member retention as well as involvement.

Lastly, I provided free tutoring services in computer science coursework for 2 hrs/wk at the UPE clubhouse. One of UPE's greatest services to the UCLA community is our tutoring services. We have all our officers either tutor or supervise the tutoring room each week and have our inductees support the tutoring room as well. Our tutoring service is quite popular as the room is always packed when a big deadline approaches. It's unfortunate that we can't get a bigger to support the amount of traffic we get, but I'm just happy that I can help other students succeed in their coursework.

Beyond my primary responsibilities as EVP, one of my goals was improving the CS Department’s industry affiliate program benefits to attract more companies into joining the program and increase the amount of companies UCLA students can network with. To that end, I conducted interviews with companies of all levels to understand their budgets and needs. I then used that data to successfully negotiate modifications to the affiliate program, with the most impactful modifications being a new $500 first-year trial for startups and zero costs for federal and non-profit entities. In my time as EVP, I was able to get Jane Street, DRW, and Glean to join the affiliate program. With more companies in the affiliate program, my next goal was to increase engagement with them. I helped Jane Street host their first event at UCLA, working with company representatives to organize a tech talk led by one of their software engineers that was attended by 160 students. Additionally, I organized a tech talk with another affiliate, Sandia National Laboratories, where a software engineer highlighted the complex challenges Sandia tackles daily and the advanced tech stack they utilize. I worked with Sandia National Laboratories to host a hackathon as well. Furthermore, I collaborated with the UCLA CS Department to organize a career fair for our industry affiliates and UCLA Computer Science students, with over 800 students attending. Hosting all these professional events with the industry affiliates has improved the relationship between them, the CS Department, and UPE, and has also provided students valuable networking experiences from which many gained internships. 

Knowing that not all students are interested in immediately entering the workforce and want to pursue a Master's or PhD instead, I also put effort into bringing engineering graduate schools to UCLA. More specifically, I collaborated with ACM to bring Cornell's graduate school admissions team to UCLA. The collaboration with Cornell Tech included a workshop providing tips and tricks in creating a strong application, financial aid, and how to succeed in industry. As such, even if students did not intend on applying to Cornell, they still left with advice that is applicable to applying to any other university.

Given UPE's collaborative nature, committees often planned joint events and helped one another. Though these committees are not technically under my supervision, I provided my services to the other 8 committees in UPE, volunteering at or helping plan events. Some events I helped with were Induction Orientation Mixer, Summer Planning Workshop, Tech in the Park, CS Townhall, CS Welcome Day, UPE Intro Event, Demystifying CS Clubs, and Engineering Welcome Day.

Before becoming EVP, I collaborated with Entrepreneurship Committee members to organize and host Hot Ones panel, bringing in UCLA alumni entrepreneurs to share their stories and answer questions for over 100 student attendees. I also led a team of 3 to organize UPE Entrepreneurship's Poker and Board Game Night, providing UCLA students the opportunity to casually chat, play, and network with established entrepreneurs. Furthermore, I worked in collaboration with Bruin Entrepreneurs to organize UCLA's first Foundathon, an event for UCLA students interested in entrepreneurship with a product pitching competition and workshops. I helped develop workshops and guidelines for product pitch judging among other things.

This is already getting quite long, so I'm refraining from expanding on the other miscellaneous things I did as EVP as well as what I did before becoming EVP. But if you're curious about that, reach out and we can have a chat.

{{< /accordion >}}

{{< accordion "Vietnamese Student Union / SEA CLEAR" >}}

Position: Workshop Facilitator and Mentor
Dates: Oct 2022 - Jun 2024

- Presented at: VSU High School Conference '22, Southeast Asian Admit Weekend '23, Southeast Asian Transfer Enrichment Day '23 

UCLA's [Vietnamese Student Union](https://vsubruins.com/) (VSU) and [Southeast Asian Campus Learning Education and Retention program](https://uclaseaclear.wixsite.com/mysite) (SEA CLEAR) are different entities, but they collaborate so much to the point where I just consider them as one. The two clubs host a variety of programs targeted towards Southeast Asian students. These include High School Conference (HSC) for high school students, Southeast Asian Admit Weekend (SEA ADMIT) for high school students admitted to UCLA, and Southeast Asian Transfer Enrichment Day (SEATED) for prospective UCLA transfer students. I served as a Workshop Facilitator for all of these programs, organizing and presenting workshops covering a range of topics including academics, Southeast Asian education, and mental health. For each program, I facilitated a different set of workshops.

For HSC, I worked with two UCLA students, Ashley and Karen, to organize and present two workshops to roughly 75 high schoolers. These workshops were SEApotlighting Your BestSEAller Moments (AKA building a resume) and Time Management + SEAlf-Care (AKA time management and self-care). For the former, we described what constitutes a strong resume and using certain formatting, strong action verbs, and metrics distinguishes strong resumes from weak ones. We also had the students go through exercises where they were asked to identify examples of strong and weak resumes. In the second workshop, we provided tips and resources to improve time management and discussed the benefits of self-care. As a fun activity, we took our students outside to do yoga (a form of self-care) and handed out positive affirmation notecards.

For SEA ADMIT, I worked with my buddy [Nat Nguyendinh](https://www.linkedin.com/in/nathan-nguyendinh/) to develop two workshops: SEA-ites to SEA in LA (AKA what to do in LA) and AdvocaSEA PoliSEA Advicism (AKA Southeast Asian advocacy, policy, and activism). We ran these workshops for about 40 students. Making the first workshops was fun because the topic was light and casual, giving us more flexibility and creative freedom in organizing the slides and activities. I found an anime girl themed slideshow template and used it for the workshop after getting Nathan's approval. Additionally, I used React to create a family-friendly version of the popular Rice Purity test called Uniqueness Test which served as the icebreaker for the workshop. If you want to learn more about how I made the game, check out the [Projects page.](https://trunghvu.com/projects/#uniqueness-test) Anyways, the content of our workshop covered activities to do at UCLA, Westwood, Sawtelle, Santa Monica Beach, K-Town, and Little Tokyo. We (or Nathan since he's actually in a relationship) also added in a slide of good date spots around the LA area. Additionally, we discussed transportation options students have to travel around such as public transit or Uber and Lyft. I'm quite happy we took a deep dive into using public transit because of the free tap cards UCLA students get now. Hopefully the students found the workshop helpful. For our second workshop, Nathan and I discussed some of the issues the Southeast Asian community currently faces: deportation, race data aggregation, representation in higher education. We gave a thorough explanation of the problem and then provided methods students can take to remedy the issue (i.e. increasing awareness, contacting government officials). Despite already knowing a bit about these issues, I learned much more while organizing this workshop.

For SEATED, I organized one workshop, SEArching for ProfeSEAional Opportunities (AKA Networking and Professional Development), with Laura Dinh. We presented the workshop to about 60 students. Seeing how Uniqueness Test was a hit during SEA ADMIT, I made another version of that game catered towards transfer students. In this workshop, Laura and I covered things such as cover letters, resumes, and letters of recommendation. We only skimmed these topics though since transfer students generally already know about this. What we spent more time on were the resources and opportunities at UCLA students can take advantage of such as career fairs and research. We discussed when certain career fairs would occur, how to get involved in research labs, and the resources UCLA provides to find internships and prepare for interviews. Lastly, we discussed the power of networking and how to network successfully. This segment of the workshop was useful to the SEATED attendees as the program had a time blocked off for students to network with UCLA alumni.

Beyond being Workshop Facilitator for these programs, I also served as a uncle (AKA mentor) for SEA ADMIT and SEATED. To provide some context, attendees were organized into groups called families and within these families, there are the family heads as well as uncles and aunts. The family heads, uncles, and aunts stayed with their assigned attendees throughout the event. They direct attendees to the next program activity, keep them entertained, and answer questions. Simply put, they serve as a friend and guide. I loved being an uncle because it allowed me to interact with the attendees at a deeper level and help in ways I could not as a Workshop Facilitator. After the conclusion of the programs, it is up to the attendee and family head, aunt, or uncle on whether they want to stay connected. I only shared my information with SEATED attendees because they were of college age and keep in touch with many of them today. In fact, the family had a little reunion at the beginning of Fall quarter 2024 by going out to get Korean BBQ in K-Town.

All in all, I would say that being involved in VSU and SEA CLEAR was a great decision. I made lots of great friends through the clubs and learned a lot about issues the Southeast Asian community faces as well as the ongoing efforts to remedy those issues. Most importantly, being involved in this space allowed me to help and inspire Southeast Asian students, many of which come from underserved communities. The work I did let me provide these students the support and resources I never had when I entered UCLA, and I hope that made their transition from high school or community college to UCLA smooth and seamless.

{{< /accordion >}}

{{< accordion "Vietnamese Culture Night" >}}

Position: Fiscal Committee Member  
Dates: Sep 2023 - Jan 2024

[Vietnamese Culture Night](https://www.instagram.com/uclavcn/?hl=en) (VCN) is an annual student production by UCLA's [Vietnamese Student Union](https://vsubruins.com/) done in Royce Hall to highlight the experiences of Vietnamese Americans. The production is generally a play with performances from Vietnamese Tradition Dance, Awechords Acapella, VSU Modern, and Vietnamese Moditional Dance. VCN is free for everyone to attend, but the costs to run the program is anything but free. From renting Royce Hall, hiring Royce staff, buying dance team outfits, printing itineraries, and etc., there is a serious amount of money that needs to be raised in order to make VCN happen. This is where the Fiscal Committee comes in.

As a member of VCN's Fiscal Committee, I primarily focused on managing and budgeting projected expenses and available funds for the approximately $50,000 production cost of VCN. More specifically, I managed and delegated funds to the multitude of committees involved with VCN for the purchase of supplies and materials, acting as liaison between VCN committees and their requests as well as POs. Additionally, I assisted the Fiscal Head in recording all payments and reimbursements related to VCN.

I also served as a flex member between the different teams within the Fiscal Committee (management, inreach, outreach), providing any support I could whenever needed. For example, I helped with baking pandan waffles when the inreach committee hosted a Vietnamese coffee and pandan waffle fundraiser. I honestly wasn't expecting to be baking waffles. I imagined I'd be manning the table and selling the coffee and waffles since I was not person who spent the days before the fundraiser experimenting to perfect the correct oil, egg, water, and mix ratios. But life always throws curveballs and after some trial and error (I did not sell the failed waffles), I got the ratios down and was baking some tasty pandan waffles. For 3-4 hours, I was pumping out as many pandan waffles as I could with the help of VCN's director, Tracy Tran. It was honestly stressful because we had three waffle irons that all baked at different rates despite being on the same setting. Keeping track of when each waffle would be done baking was a struggle, but after some time, we got the hang of it and it felt like second nature. This fundraising brought in a few hundred bucks which was great!

{{< /accordion >}}

{{< accordion "Vietnamese Traditional Dance" >}}

Position: Dance Team Member   
Dates: Oct 2022 - Apr 2024

When I attended VCN during my sophomore year, I came in halfway through the program because I had to finish homework for COM SCI 35L: Software Construction. After some struggle, I was able to pick up what was happening in the play and enjoy the remainder of it. I was deeply moved by the story and applied the lessons told from that story to my life. When I think of VCN though, what comes to mind is the Vietnamese Traditional Dance team and all the bright, vibrant colors from the ao dai and the rice hats moving in harmony to create beautiful images. I wanted to be part of this team and be the one who creates the beautiful images I remember seeing when attending VCN. Additionally, I wanted to get more in touch with my roots as it was something I had not prioritized all my life. I hoped being part of the team and learning traditional dance would allow me to develop a stronger connection to Vietnamese culture and history.

After trying out and getting a stroke of luck, I made the team! It was quite crazy that I made it because only 1/3 of those who tried out were accepted. As someone who did not have any dancing background, I was surprised. In any case, I embraced the opportunity and am eternally grateful that I was on the team. Dancing for 2 hours twice a week gave me good cardio and allowed me to meet some of the most amazing people at UCLA. The attitude of those on the dance team differed significantly from students within the engineering space. No one cared what company you interned at, and no one touted about how little sleep they got. Everyone just accepted people for who they were, and that made me so happy. Despite the late and long hours, I was always happy to attend practice because it was my outlet and way to de-stress from the toxic engineering environment. Beyond this, being part of the team just improved my confidence. I don't think there will be a point in my life where I won't be nervous about dancing in front of 1800 people, but doing this for VCN has changed my attitude and perspective about what I can and can't do.

I enjoyed my time being part of the Vietnamese Traditional Dance team for VCN 43 so much so that I decided to join the team again for VCN 44. While lots of the friends I made the year before graduated, many of my friends who did not make the team or did not try out the year before were on the team now. Dancing and joking around with them brought about the same joy I experienced while on the team for VCN 43.

VCN is free for all to attend, though you need to secure yourself a ticket and that's somewhat hard since they sell out in less than a day. However, VCN is also livestreamed on YouTube! So, even if you aren't in the LA-area to see the performance in-person, you can still join and enjoy the production virtually.

Wrapping this up, something I urge engineering (really all) students to understand is that not everything you do has to be related to your major. Balance is key. Some students stick only to activities related to their major and are fine, but college is the time to explore and expand your horizons. Vietnamese Traditional Dance let me get in touch with my roots, provided me daily exercise, and helped me refresh my mental state. Yes, being part of the team did not improve my computer science skills, but the memories and joy I received from being part of the team put myself in a positive state of mind to function as a better student and engineer. Furthermore, being part of this team and performing in Royce Hall in front of a huge crowd was a unique, once in a lifetime experience I never would have experienced if I just stayed in computer science clubs.

{{< /accordion >}}

## Awards and Honors

<hr>

{{< accordion "UPE National Scholarship" >}}

Each year the Executive Council of Upsilon Pi Epsilon evaluates many scholarship applications from students at both the undergraduate and graduate levels. All scholarship applicants are required to complete a comprehensive application form including a statement on their long-term plans in the profession, a summary of their contributions to their respective UPE chapters and related student activities at their college or university. Applicants are also required to submit all college-level transcripts and a recommendation from the UPE faculty adviser.

I received a $1,000 scholarship from UPE national for demonstrating exceptional academic record, extra-curricular activities and having a strong recommendation from my UPE chapter Advisor.

{{< /accordion >}}

{{< accordion "Computer Science Wang NSF REU" >}}

I received a $1,500 scholarship to perform research on applying graph neural networks to protein modification prediction with UCLA Scalable Analytics Institute lab and Berkeley Toste lab.

{{< /accordion >}}

{{< accordion "MIT Climate & Energy Prize" >}}

I worked part-time with SISYPHUS Global Systems while doing full-time school during my sophomore year. At the time, the company wanted to participate in as many startup accelerators as possible to get more funding and spread the name of the company.

MIT's Climate & Energy Prize (MIT CEP) is the world's longest running and largest climate tech startup competition for university students. Many alumni of the program have successfully launched companies and with the MIT branding and monetary prizes, SISYPHUS say this as a perfect opportunity to secure funding, mentorship, and advertising.

I helped SISYPHUS organize an application package to MIT CEP, outlining our mission, product, recent success, and plans. With this, SISYPHUS was accepted into the competition and began the virtual rounds where MIT CEP judges selected the best business plans to move to the regional semi-finals. At this point, I handed off the task to a more capable member of the SISYPHUS team since I had no formal business background, and they did.

{{< /accordion >}}

{{< accordion "IBM Call for Code Global Challenge ( NA regional finalist )" >}}

With other staff members of SISYPHUS Global Systems, I participated in IBM's 2021 Call for Code Global Challenge. We worked on our web-portal product that utilizes ArcGIS maps and WebXR to provide users an immersive augmented reality experience of assessing their property’s flood risk and viewing their city’s green and grey infrastructure. Throughout the months of the hackathon, I helped integrate various IBM software into the product's system architecture and improved the MVP. Near the end of the challenge, I assembled a GitHub repository to showcase all the work my team has done to submit to the judges. When the results came in, my team was [recognized](https://developer.ibm.com/callforcode/solutions/2021-solutions/#regionalfinalists) as one of five regional finalists for North America.

{{< /accordion >}}

{{< accordion "Verizon & CGI U Social Innovation Challenge ( 1st )" >}}

I participated in VentureWell, Verizon, and CGI U's startup accelerator program in 2021 as a representative for SISYPHUS Global Systems. There, I worked with the SISYPHUS team to organize a product pitch and presented it to Clinton Foundation Vice Chair Chelsea Clinton, Verizon representative Nicki Palmer, and VentureWell CEO Phil Weilerstein. Despite initial fears of not being good enough to beat the other startups, the product pitch my team gave was much stronger than that of our peers. My team beat the 12 other startups in the program and secured SISYPHUS a slot in VentureWell’s second phase of the E-Team program. We also received a [shoutout](https://venturewell.org/pitch-competitions-2/) from VentureWell on their website!

{{< /accordion >}}

{{< accordion "IBM AI Spot Challenge ( 2nd )" >}}

IBM's [Call for Code: AI Spot Challenge](https://community.ibm.com/community/user/ai-datascience/blogs/julianna-delua/2021/07/26/announcing-call-for-code-ai-spot-challenge-for-a-s) was a 2-day hackathon that is part of the larger Call for Code Global Challenge. The purpose of this hackathon was for developers to build and contribute to sustainable, open-source technology projects that make our planet safer using cloud and AI tools. I participated in this hackathon with staff members of SISYPHUS Global Systems. 

We utilized a hybrid data-management strategy. We tested multiple supervised machine learning algorithms using the Cloud Pak Auto AI service with our ground-up built dataset. We also explored Watson Studio & Cloud Pak for future unsupervised ML (e.g., dimensionality reduction) with our multi-cloud data platform. We can scale the data architecture across government, professional and community stakeholders for needed capabilities to drive smarter mitigation planning decisions and prioritize project implementation. Our aim was to reliably predict the flood risk associated with properties in New Orleans (our pilot city for this project) and deliver the results to different stake holders (homeowners, government officials etc.) in an interactive manner combining the power of machine learning/AI and augmented reality.

Through this hackathon, we took the first step towards completing the back-end code to enable automated predictions of flood risk for individual properties. Since we were not at liberty to release data from individual properties, we aggregated the data according to census blocks. We used a test dataset describing various attributes (land use, water area, tree count, number of buildings, repetitive flood loss, etc.) of these census blocks to predict the FIRM score---a "flood insurance rating" issued by the Federal Emergency Management Agency (FEMA), with a high FIRM score indicating a high flood risk.

After [repository](https://github.com/uqktiwar/IBM_SpotAI_SISYPHUS) got evaluated, we were granted 2nd place and a [shoutout](https://community.ibm.com/community/user/ai-datascience/blogs/julianna-delua/2021/08/24/and-call-for-code-ai-spot-challenge-grand-prize-go) on IBM's community page. You'll notice that my name is not on the list of members on SISYPHUS's team. This is because I did not officially register for the hackathon since we thought we had already hit the member limit.

{{< /accordion >}}

{{< accordion "IBM Code Engine Hackathon ( 2nd )" >}}

IBM's [Call for Code: Code Engine Hackathon](https://developer.ibm.com/events/call-for-code-code-engine-hackathon/) was a 2-day hackathon that is part of the larger Call for Code Global Challenge. In this hackathon, teams were expected to integrate IBM's Cloud Code Engine---a fully managed, serverless platform that runs containerized workloads, including web apps, microservices, event-driven functions, or batch jobs---into a product that fights climate change.

I participated in this hackathon with staff members of SISYPHUS Global Systems and worked to integrate the Cloud Code Engine service into the system architecture of SISYPHUS's web-portal product. This was the bulk of my team's work during the hackathon as beyond this, we just made small improvements to our product to demonstrate that we are making progress as the Call for Code Global Challenge progresses. After the judges analyzed our [repository](https://github.com/thvu02/SISYPHUS_GLOBAL_SYSTEMS), my team was rewarded 2nd place in the hackathon.

{{< /accordion >}}

{{< accordion "Howard Hackathon for Environmental Justice ( 2nd )" >}}

I participated in IBM's Call for Code University Challenge: Howard Hackathon for Environmental Justice as a member of Global Flood Equity Extended Reality (later reorganized as SISYPHUS Global Systems). I worked alongside 4 team members to develop the beta version of an interactive web-portal that calculates flood risk of individual properties and its optimum flood mitigation from a GIS platform with a focus on environmental justice and equity. My team ended winning 2nd place and got a [shoutout](https://www.businessinsider.com/us-risks-climate-apartheid-if-grassroots-ideas-ignored-activist-says-2021-4) on a Business Insider podcast.

{{< /accordion >}}

{{< accordion "Dean's Honor List ( 20F, 21S, 23W )" >}}

I got recognized by the UCLA Samueli School of Engineering in these quarters for taking over 15 units of coursework and having an average GPA of 3.7+ for those courses. I believe the requirements for Dean's Honor List has changed recently, but those were the requirements before.

{{< /accordion >}}