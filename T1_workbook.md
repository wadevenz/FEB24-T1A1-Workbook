# **Wade Venz T1A1**

## Workbook

### _**Question 1: Identify and explain common and important components and concepts of web development markup languages**_

    When considering markup languages for web development, one of the most common markup languages is HTML or 'Hypertext Markup Language'. Basically, HTML enables data to be seperated into elements to make it easier to structure a webpage. These elements form the building blocks to be styled and designed to create an engaging experience for the user.
    
    There are other languages such as XML (eXtensible Markup language) or Markdown, however HTML appears to be the main markup language in web development (Lenovo, 2024). Components and elements are annotated by 'tags' which help organise and collate data, and assist in its styling as the structure and tags are easily referenced and understood (Britannica, 2024). Some example components or tags in HTML include, header, body, section, main or footer in which appropriate input can be organised.

### _**Question 2: Define the features of the following technologies that are essential in terms of the development of the internet:**_ <br/><br/> - **_packets_** <br/> - **_IP addresses (IPv4 and IPv6)_** <br/> - **_routers and routing_** <br/> - **_domains and DNS_** <br/> <br/>**_Explain how each technology has contributed to the development of the internet._**

#### Packets

    A packet is a compartmentalised section of data sent over a network, utilising a set of standards or protocols. By segmenting messages or data this way, it enables more efficient transfers through traffic avoidance. Packets are not constrained to single pathways but are able to split up and take different pathways or routes to their final destination allowing them to travel the path of least resistence. Packets are also able to contain their own encryption allowing for better security. 
    Each packet is divided into parts, a header, which contains information including that of the sender and the recipient, the main part of the packet, and in some cases a signature or aka, trailer or footer. (Yasar & Zola, 2022)

#### IP addresses (IPv4 and IPv6)

    IP or 'Internet Protocol' is the rules or standards mentioned above to facilitate transfer of packets over a network. IP addresses are essentially unique identifiers for each device. The initial version of IP addresses or 'v4' was 32-bit addresses utilising a series of numbers and decimals. However that finite sequence of numbers has been outgrown with the vast popularity and widespread use of the internet over an ever growing number of devices (Duò, 2023). Therefore a larger library of IP addresses is required, enter IPv6. Using a 128-bit address, integers and letters are used to increase the pool of possible unique addresses on an exponential scale. Ipv6 also comes along with with some other features, such as embedded security, larger packet header, ability to send packets to multiple locations in one operation, and potentially faster speeds due to eliminating the need for NAT or Network Address Translation (Duò, 2023).

#### Routers and Routing

    For data or information to be sent or retrieved over a network, an appropriate path must be selected, that path is called its route. A router is essentially a type of hardware connected to the network that decides the route that data packets will take to reach its destination (Cloudfare, 2024). 
    When a router receives a data packet it will read its associated address and unique information to identify where the data needs to go. It will then utilise data it has for best pathways to take and send the data the most efficient route, this is called 'routing'(Fig. 1). When a pathway in a network has been set up by an admin and doesnt change, this is called 'static routing', however as networks grow, so does the amount of data being sent. Dynamic changes can be required to prevent blockages and delays, which can make 'dynamic routing' far more desirable.(AWS, 2024)
![Routing](routing.png ("Fig. 1"))
Fig. 1 (Cloudfare, 2024)

#### Domains and DNS

    Each and every accessible area on the internet needs identification or a website address, this is where Domain names or 'Domains' become useful. Generally organised into three main sections or levels (Singh, 2021), they help identify unique web addresses and seperate them from others. 

    These domains are collated into directories or systems which is called the DNS or 'Domain Name System'. As Domain names are more easily understood and memorised than IPs or long lists of numbers, the DNS matches a Domain to an IP address so humans and computers can communicate more efficiently together. The DNS is essentially the internets infrastructure and therefore vital for its usability. (Singh, 2021)

### **_Question 3: Define the features of the following technologies that are essential in terms of the development of the internet:_**<br/><br/> - **_TCP_**<br/>- **_HTTP and HTTPS_**<br/>- **_web browsers (requests, rendering and developer tools)_** <br/><br/>**_Explain how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)_**

#### TCP

    Data transmission is made possible by breaking down data into manageble pieces called 'packets' and sent to a target using an 'IP' address. While this may result in successful data transmission, the packets may not arrive in the correct order, and may appear meaningless. Essentially TCP or Transmission Control Protocol, works over IP to solve this problem (Khan Academy). It keeps communication open between the source and the target so that when data has been transmitted it can arrange the data in the correct way so that is useful to the recipient. Communication is kept open via what is referred to as a "three-way handshake" as shown in Fig.2. Simply the source computer sends a 'SYN' or syncronisation, which is returned by the target with an 'ACK' or acknowledgemnt. The acknowledgement is then returned back from the source computer, and actual data is transferred from the source being constantly acknowledged from recipient. The TCP then utilises the information embedded in packets, to then organise and deliver to the target as intended (Cloudfare, 2024). 
![Three Way Handshake](tcp-handshake-diagram.png (Fig.2))
Fig. 2 (Cloudfare, 2024)

#### HTTP & HTTPS

        HTTP stands for Hypertext Transfer Protocol and was the pioneering technology for communication over the internet. As the name protocol would suggest, it refers to the guidelines for sending and receiving data from a web server. When a user accesses a browser, HTTP sends a request to the web server, which then responds, enabling data transfer (AWS, 2024). However this data is in plaintext and is not secure from external parties, therefore a more secure method was devised, HTTPS or HTTP Secure. Rather than plaintext, data over HTTPS in encrypted. For communication from the browser and the server to occur, an SSL certificate (Vocell, 2022) must be issued and security keys are traded to encrypt the data and increase security. 
        On top of security as an advantage to HTTPS, increased authority and performance are also benefits. Also due to HTTPS being more trusted, search engine results are optimised making secure sites a priority. 

#### Web Browsers

        A Web browser is simply software that enables a user to interact with websites on the internet. There has been numerous different web browsers since the genesis of the internet, however there are a few common popular ones currently being used including Google Chrome, Safari and Mozilla (Rouse, 2023). A user can navigate to websites via URLs or Uniform Resource Locators. URLs are basially addresses that enable users to navigate all over the internet to specific websites or 'resources'.

### **_Question 4: Describe the features of interpreters and compilers and how they are different._**

    Source code written in high level programming languages makes it easier for a programmer to use and understand, however computers operate in binary or a low level language, therefore code needs to be converted for programs to be executed (baeldung, 2024)

    Compilers convert source code to machine or (object) code before executing a program. The language only need to be compiled once, which is slower to initially analyse, however more efficient to run as the language has already been converted to machine code and doesn't need to persistently put load on the server (Sassi, 202). 

    Interpreters act a bit differently as they directly read and execute source code during program runttime, then convert to macine code for output (baeldung, 2024). However interpreters do run slower as the language is being converted at each line and it has to acces the RAM for interpretation, in comparison to compilers which only convert the language once (baedung, 2024).

    Compilers will identify errors and bugs as the code is compiled, and errors are required to be fixed prior to compilation being completed. 

    Interpreters will find and notify of errors in code as they are identified as each line is being executed. 

    Finally, programming languages can contain both functions as compiled languages contain interpreter implementations and interpreters dont nullify the need for compilers. The merging features of compilers and interpreters can be seen in languages such as Javascript which will be described below. 

### **_Question 5: Identify TWO commonly used programming languages and explain the benefits and drawbacks of each._**

#### Javascript

    As of last year, Javascript was the most popular programming language (Logan, 2023). Javascript historically has been known as an interpreted language that over time developed methods to operate with the benefits of compilers. JIT or Just in Time compilation, which essentially converts source code into machine code at point of execution, will only convert that code necessary for function. This reduces the load and increases speed and efficiency. (FreeCodeCamp, 2020). Javascripts popularity can also be attributed to its wide versatilty and access to numerous libraries and environments such as React and Angular. These create widespread platform accessibilty and use, both front and back end (Neville, 2023). 
    Although Javascript does have sercurity protocols and redundancies built-in, especially into the compatible frameworks, the client side nature of Javascript makes it vulnerable to implanted malicious code, and if not used properly a user can be exposed to leaks of sensitive data. Also it is necessary to run multiple tests in different environments, as Javascript does not always run consistently across all browsers (Neville, 2023). Also compared to compiled languages, Javascript can lower on speed and also debugging efficiency as the tools used are not advanced as some other languages. Overall however Javascript is a powerful high level language that is widely used and has enabled a vast majority of browsers and apps that are used today (Neville, 2023).

#### Python

    Taking the second most popular language spot was Python (Logan, 2023). The high level nature of this language (closely resembling written English), makes it an easy introduction to programming and enables programmers fast learning with a wide support network. Its uses are expansive, like Javascript, it has access to many libraries such as Flask, which enable the ability to build apps and web pages. The code is also adaptable and embeddable, meaning it works well wiht other coding languages and databases and tools such as SQL (Gavrilova, 2023). However as Python is an interpreted language it does come at the cost of slower processing speeds than its compiled counterparts. Also with the increased flexiblity of Python can come increased drawbacks. Like Javascript, Pythons popularity leaves it vulnerable to malicious attack if not used properly, and although it has in built security features, like Javascript can be vulnerable if not used properly. Python also can have debugging issues especially at high density projects (Gavrilova, 2023). The versatility and high level of the Python language can also lead to frustrating type errors that would be identified earlier in other languages, increasing debugging time and slowing down development (Gavrilova, 2023). Overall however, it would seem that Pythons broad access and ease of its use combined with its wide capabilities overcome its limitations and contribute to its massive popularity. 

    The languages above share a lot of similarities as they are both popular, dynamically typed, high level languages. They share widespread use in a vast amount of browser and applications. And while they share a number of aspects, the frameworks and environments they associate with lend each language to be utilised in different ways. Javascripts frameworks enable a lot of visual components and aspects leaning to its expansive front end application, where python languages functionailty and use will see it moreso applied in the back end.  

### **_Question 6: A hypothetical client has sent you an email, asking for you to build them a website. Write an appropriate, professional email response that shows your understanding of the client’s needs for the website, as well as an understanding of appropriate technologies or tools needed to build the website yourself._**

*Hello there!*

*My name is Alex, and I’m the director of the Super Awesome Museum (SAM). We display a variety of interesting artefacts, objects, and paraphernalia about all sorts of things from all over the world.*

*I’m writing to you because the SAM needs a website. The museum is new in the city, we’re fully funded and don’t sell our items but we just need to encourage people to visit the museum.*

*We would need a website that showcases some of our interesting exhibits and items, helps people find their way to the museum, and helps people contact the museum.*

*We don’t know much about this website stuff - does this sound like something that you can do?*

*Looking forward to hearing from you,*

*Alex*  
*Director*  
*Super Awesome Museum*

---

Hi Alex,

I'm Wade, thanks for reaching out to the Super Awesome Development Company for assistance with your new website build. This sounds like an exciting project and I'd love to hear more!

From what I understand, you have three objectives:  
    1. Create a website that attracts prospective visitors of all ages by displaying some of your interesting exhibits in a formate that generates interest and is easy to navigate  
    2. Help prospective visitors easily find their way to your museum with simple instructions, a map and important information (opening times, public transport, parking, etc.)  
    3. Make it easy to contact the museum via multiple methods.

Did I miss anything?

To achieve these objectives, I propose we create a small (4 page) website. As the website does not require any complex functionality the entirety of the website can be completed utilising a simple stack of HTML5 and CSS with small touches from Javascript for some user interface enhancements.<br/>  
The pages I think would suit include:  
    - A visually engaging homepage with a carousel of major current exhibits.  
    - An 'About' page with a brief synopsis of the museum  
    - An FAQs page with important information about the exhibits, getting to the museum and how different groups can get in touch with the right person (e.g. Partnerships, Events, School Tours).  
    - A 'Contact' page with general contact information, a responsive 'Contact Form' with recaptcha validation that would send form submissions to an email of your choice.

How does this sound? We can deploy the site as per your preference — I tend to use GitHub pages.

If you're happy to proceed, let's set up a meeting to discuss the functionality I've outlined. I'll be able to provide you with a quote and timeline for you to review.

Looking forward to hearing from you,

Wade
Dev, SADC

### **_Question 7: Think back to a scenario or situation in your own software development projects or work. Explain how you would do things differently if you had a chance to go through that scenario again, using an appropriate reflective cycle or reflection technique._**

**Description**  
As my journey in software development is new and extremely brief, I have very minimal experiences to reflect upon. However having recently completed a Portfolio website, I have fresh insight into a specific project. The project was to create a simple Portfolio website to present myself in a professional manner, giving a target audience a brief insight into my personality and professional aspirations.

Eager to get started, I began wireframing the site in Figma without carefully thinking about what I was trying to achieve, the content that I wanted to present, or the best functionality to complement each page. Once I'd hastily mocked up a nice looking site, I started building. It was only at this point that I realised that I hadn't spent enough time thinking things through and would need to backtrack. I'm going to use the ERA Reflective cycle to reflect on this situation in more detail.

**Experience**  
This situation happened a couple of weeks into my first ever software project. Overall, building the site was a really positive experience, but I really learned a lot in this particular part of the project.

Because I'd never built a portfolio website before (or any website for that matter), I had researched other professional portfolios in order to gain insight into what I thought would look good and serve me well once I graduated from Coder Academy. This process also helped me to determine what I didn't like. However, it also resulted in a Frankenstein planning process, where I simply gained inspiration from others, rather than properly thinking through what would truly work for me.

Unfortunately it wasn't until I was deep into the development part of the process where I realised that this approach wasn't the best, and that I would need to retrace some steps in order to build the best site for my future career.

**Reflection**  
In the initial stages I felt very eager to get started with code. Most likely due to anxiety over time limitations and the sense of scale I had created in my mind over the project. I admit I had felt overwhelmed and therefore did not spend enough time in the planning phases. I believe I underestimated the function of processes such as sitemaps and wireframes and there role in a completed website.

Once I reached the point where I had to start again, I felt deflated. I had built a number of 'complex' functionalities (well at least for beginner me), including a blog post carousel and a burger menu for mobile, and I realised they weren't the best solutions for my site. Incomplete planning and changes to the design also caused me to feel a lot of indecision and confusion in later parts of the project. Part of the indecison also came from me wanting to ascertain as much skill and knowledge, but also create a realistic and quality product within my relatively small skillset. 

Once I decided to stop coding, and take some time to plan, I started to feel a lot more clarity about the project. I replaced the 'rubber duck' with my wife who helped me to understand my priorities and then created a solution that worked towards these goals.

**Action**  
It's well known that good planning prevents poor outcomes, and this has certainly been the case for me!

I have a lot of learnings from this scenario. Next time I have a similar project, I'm going to:
1.Get clear on my goals for the website.
2.Develop a plan that will achieve these goals
3.Determine the layout, user experience and functionality needed
4.Create a wireframe that demonstrates how the site will look, with notes that explain the functionality
5.Once I'm happy, THEN I'll start coding!
6.Be generous with commenting and pseudocode to help visually represent ongoing thought processes and desired outcomes.

Spending time on complete planning, and having a comprehensive knowldege of expectations and processes to achieve will not only improve time managment and efficiency but also prevent anxiety and a feeling of being overwhelmed.

On top of this, a frequent review and update of processes utilising tools such as a kan ban board will aid in future projects to compartmentalise larger projects into smaller and more manageable pieces.

### **_Question 8: A large part of career growth as an information technology professional happens through networking and workshops, often found at online or in-person events or workshops.<br/> <br/> Create an action plan that identifies several relevant networking opportunities for you to participate in or attend, and add some information about what you expect to gain or grow through each item in the action plan._**

Within the following events or opportunitues is a brief description and expected outcomes and goals for each. The list encompasses a plan of action for present and future networking in pursuing a career in IT. It is understood that real engagement and effort is required for each of these, as networking is far more likely to occur to the proactive than the reactive. 

    1. Attend The Design Conference (June 2024) - This conference is attended by Australia's best design teams, both in-house and agency side. I hope to gain a deeper understanding of the design world, and exactly what design teams need from good developers and how we can work synergistically together. In my experience the best developers work hand-in-hand with design teams to create websites, apps and programs that are not only functional but have an additional focus on the user experience and design of the product as well.  The Design Conference also has a specific focus on creating networking opportunities, and I plan on making the most of them. Ideally, I will meet my future employer, or someone who can introduce me to them.

    2. Join a hackathon (or mini hackethon)(July, 2024) - Hackathons are designed for community engagement to spark innovation and creativity for people with similar interests and aspirations. Working together with people on a software project towards achieving solutions and often solving real world issues is a great way to both meet and engage with a multitude of people from the industry all the while gaining invaluable experience and knowledge. These events can happen in person, or online. Advertisements for these can come via sites like [Hackathons Australia](https://www.hackathonsaustralia.com/) or [Hackathons](https://www.hackathons.com.au/.com) which display global events. While already passed, a mini hackathon like the one put on by [IXDA](https://events.humanitix.com/ixda-brisbane-mini-hackathon-march-2024) would be a great event to be on the lookout for in the future.

    3. Join or contribute to an open source project (July, 2024) - One of the ways it is said to learn to code is to... code. Once I feel Ive gained a solid foundation of coding knowldege, with a timeframe set around end of second trimester, my plan of action is to practically apply the skills learnt through real life contribution. Open Source projects allow real world application to everyone from beginners to advanced, and I imagine help get a feel for and understand coding. My plan is to as soon as possible, find a suitable Open Source project, for example utilising GitHub or peruse around Mozilla, and take a shot at contributing some code or experiencing some techniques utilised in the software development industry. By getting real hands on experience not only do I hope to engage with other developers of like mindedness I hope to advance my own skills and knowledge in preparing for employment. These projects are saturated full of knowledge and experience and people that are willing to share collaborate on ideas.

    4. Online networking/ skill development resources (Present - Ongoing) - [Just Digital People](https://www.justdigitalpeople.com.au/), [hackster.io](https://www.hackster.io/), These are a couple of the vast number of online resources developed for networking and engaging in the community of software development. As time goes on, it is becoming more apparent how much networking is necessary for gaining entry and traction in the industry. Community pages such as these are resources of people and experience to tap into.  My plan is to interact with these resources more and more as time goes on, and it is my expectation that through this I would gain valuable knowledge of the industry and also come into contact with people that will be able to guide me into paths of entry into professional software development and IT.

    5. Meeting with industry professionals (Present - Ongoing) - Through immediate contacts with people I know who work in or adjacent to the tech or software industry, I have planned and continually hope to organise meetings and create ongoing relationships. Through these contacts I hope to gain valuable insight into skills and experience required to be employed in the field. The plan includes onging exposure to people and contacts that are in the fields I desire to be apart, and with knowledge gained, create avenues of employment and also advice how to achieve persisting development and upskilling. My expectation is that, through better rapport with known contacts I will be able to present more in depth questions and receive honest answers to further enhance my journey into the field.  

### **_Question 9: Explain the uses of language-learning model technologies (such as ChatGPT) on written and technical works, such as reports and software projects._**

    Language-learning models (LLM) or Artificial Intelligence (AI) responsible for interpreting langauage (Gotay, 2024), in many respects,  is relatively new and still in its infancy. It would seem that while creativity and ingenuity are requried for software engineering and development, AI, at least for now will remain at the whims of the human mind. However, AI's uses in collating vast amounts of data, machine learning and pattern recognition give it the ability to perform complex or large scale routines very quickly and that can be of immense benefit to the worker (Barenkamp, Rebstadt & Thomas, 2020). Fig. 3 below shows the uses and applications of AI and language learning on the software development process. Specifically in the software development process, tasks such as generating simple code, utilising huge computing power to calculate problems and ascertain mathematical solutions and utilising predcitive models to analyse and find code bugs and errors make it a compelling support to the programmer, and potentially one day replacing many tasks that creat a push to optimise human capability and capacity (intellectSoft, 2023).

    Yet while the use of machine learning and AI to automate tasks from data colletction and coding, to compiling and integration is interesting, AI is not without its drawbacks. No doubt AI is the future of software development (Barenkamp, Rebstadt & Thomas, 2020), and those that leave it behind may be left behind, however it currently relies on human creativity and supervision. It also is not error proof, which can and has led to security and ethical issues which will be discussed below.

![AI Application](AI_application.png)
Fig. 3 (Barenkamp, Rebstadt & Thomas, 2020)

### **_Question 10: Explain the legal and ethical impacts of the usage of language-learning model technologies (such as ChatGPT) in written and technical works, such as reports and software projects._**

    AI has infiltrated the gobal population, creating vast uses and vast accountability and liability (Olvington, 2023),(Rodrigues, 2022). There are growing ethical concerns over its utilisation in a wide range of scenarios, which have led to call for continued reasearch and analysis to its legal and ethical ramifications on a global scale in all fields from academia to to tech (Ankita Guleria, et al. 2023).

    Some of the most notable legal and ethical problems for AI are; cyber security or vulnerabilty to data leaks (Olvington, 2023), Intellectual Property rights, lack of transparency (Rodrigues, 2022) and technical limitations (Khurram, 2023). Potentially even more concerning are personal human factors and concerns such as; discrimination and bias (Rodrigues, 2022), that can evidently lead to responses from AI causing personal hurt (Khurram, 2023).

    In the case for cyber vulnerabilites and data breaches, the large databases that AI banks and build can be fed sensitive information, even accidentally, which is then embedded into its model and prone to being misused or accessed. This obviously presents serious concerns and risks for conglomerates looking to protect information (Olvington, 2023)

    Intellectual Property rights also become a grey area when considering difficulties arising from unknown inpits and sources (Olvington, 2023). Also AI can beg the question of who is in charge of machine learning and information and data that is produced from AI (Rodrigues, 2022).

    Also it has been seen in academia and reports that AI is not consistent with accurate information which can have significant impacts considering the reach of AI (Ankita Guleria, Kewal Krisha, Vishal Sharma, Tanuj Kanchan, 2023). This can also lead to an issue of transparency of processes on how calculations, decisions and data was accessed and distributed (Rodrigues, 2022). 

    AI is reliant on data models and stores that then processes into automated outputs. This can lead to unequal treatment of peoples and groups that cause harmful discrimination, all without the current accountablity for damage (Rodrigues, 2022)

    Also lastly, AI takes a substantial amount of computing power and therefore resources, so while a giant, is not wihtout its technical limitations (Khurram, 2023). 

    As mentioned previously, this technoogy has reached all over the world and it has lawmakers and governments attempting to create effective solutions (Rodrigues, 2022). However, as displayed the limitations and legal implications and risks of AI are significant and it is imperative that these issues are resolved faster than they occur. 

### **_Question 11: Explain multiple skills from each of the categories below, and how they’re useful to a software development workplace. <br/><br/> - soft skills <br/> - hard skills_**

#### Soft Skills

##### Communication

    Communication is vital in a team environment as the ability to receive instruction and data and relay clear and understandable information back is fundamental to any collaboration. The software development ecosystem is so relient on communication that version control software such as GitHub have become vital to a project. While the skill of communication can act as an umbrella for many other skills such as active listening, effective presentation and feedback, the ability to understand tasks and effectively and efficiently instruct and advise is paramount.

##### Problem Solving

    Software development is basically, solving problems. By taking advantage of critical thinking, problem solving is the ability to analyse a problem comprehensively research and map out a path, sometimes multiple paths to overcome and complete the task.  This will not only assist in completing the tasks assigned, but also when encountering errors or bugs that need to be worked through to find effective solutions. 

##### Time Management

    In professional software development, clients and team collaboration is scheduled and functions on deadlines. The ability to compartmentalise a task into smaller manageable components, and creaete a clear and achievable plan is crucial in the industry.

##### Adabtability and Patience

    When changes arise in projects or new problems occur, alongside with the other skills listed previously, the skill of being flexible and malleable to a task can be neccessary. As discussed, plans are vital, however sometimes variables occur which require new solutions and approaches which is not possible with a rigid and unadaptable mindset. I would also like to include the idea of patience, as while possibly a skill of its own, can be incorporated to an adaptable mindset. Sometimes things take time, and how you adapt and manage that through patience and adaptability may determing success. 
    (University  of Denver)

#### Hard Skills

##### Programming languages

    Having an understanding and experience in a wide range of programming languages is a useful weapon in any software developers arsenal. From C+ through JavaScript and Python there are a number of languages that all have pros and cons, and unique environments making them better suited for different applications. The developer who has versatility in programming languages will be useful at developing the full stack both back and front end. There is also increasing desirability for OOP or Object Oriented Programming as it is useful for large scale projects and applications. Understanding the principles of OOP is a skill that should not be underestimated. (LinkedIn, 2023)

##### Databases

    As data is the core commodity of the IT professional, it should be of no surporse that understanding where and how it can be accessed is fundamental. Long lasting languages such as SQL (Structured Query Language) is the method that programmers and developers utilise to interact with databses and this has become a skill that is expected for the field. (LinkedIn, 2024)

##### Cloud and cloud security

    Moving data and operating in the coud is becoming immensely popular with large companies as ease and scalabiltiy coupled with reduced cost of local infrastructure makes internet data access and cloud computing very desirbale (edX, 2024). Understanding the nuances of the cloud and security aspects is now and ever more so a neccessary skill for the developer (University of Denver). 

#### Web Development

    Another crucial skill for software developers is web development. Being comfortable in the environment of web design and production with tools such as HTML, CSS, Javascript and libraries is only becoming more useful as the internet grows and expands (LinkedIn, 2024). And while a software developer might not always work in the landscape of web development, it is one of those fundamental basic skills that developers should have in the toolkit as it enables a better and more comprehensive understanding of how projects can be utilised and aids in rounding out a fully qualified software developer. (University of Denver)

### **_Question 12: Explain multiple roles or job positions that would be found in a medium-sized software development company._**

#### Project Manager

    A project manager is responsible for understanding client requirements, assembling a team, setting milestones and deliverables, keeping a project moving and on track and then reporting back to clients. They will also evaluate and reflect at project completion.

#### UX/UI designer

    Creates designs that are optimised for user interaction based on research, user testing and best practice princples. Ieally these designs are both visually exciting and pleasing as well as user friendly. 

#### Software Architect

    A software architect is responsible for understanding client needs and providing a creative solution. A software architect utilises research and planning to identify current and future problems and how to construct a successful product. (Motiso, 2023)

#### Software Developer

    A software developer is a veratile role utilising a number of different skills. From design, implementing code through programming languges and testing and debugging, software developers are responsible for creating the deliverable at the source. (Sartore, 2024)

#### DevOps engineer

    A DevOps engineer supervises and coordinates the operations of the software development. Through team collaboration and leadership, a DevOps goal is to increase efficiency and sustainable workflow and and maintain accountability for problem free software releases. The overarching job description is in the name DevOps which stands for 'development and operations'. (Staff, 2024)

### REFERENCES

#### Question 1

1 Britannica 2024, markup language, viewed April 2024, [https://www.britannica.com/technology/markup-language]

2 Lenovo 2024, What is a markup language?, viewed April 2024, [https://www.lenovo.com/au/outlet/en/glossary/markup-language/?orgRef=https%253A%252F%252Fwww.google.com%252F]

#### Question 2

1 Yasar, K; Zola, A 2022, network packet, viewed April 2024, [https://www.techtarget.com/searchnetworking/definition/packet]

2 Duò, M 2023, Ipv4 vs Ipv6: What's the Difference Between the Two Protocols?, viewed April 2024, [https://kinsta.com/blog/ipv4-vs-ipv6/]

3 Cloudfare 2024, What is routing? | IP routing, viewed April 2024, [https://www.cloudflare.com/en-gb/learning/network-layer/what-is-routing/]

Fig 1, Routing Diagram, viewed April 2024, [https://cf-assets.www.cloudflare.com/slt3lc6tev37/5biqo5wm6nM8GSmiNyiAnl/b6b5c9befeda6ba99b4380d84953de18/routing-diagram.svg]

AWS 2024, What is routing?, viewed April 2024, [https://aws.amazon.com/what-is/routing/]
  
4 Singh, A 2021, What is a Domain Name System (DNS)?, viewed April 2024, [https://www.okta.com/au/blog/2021/03/what-is-a-domain-name-system-dns/]

#### Question 3

1  Cloudfare 2024, What is TCP/IP?, viewed April 2024, [https://www.cloudflare.com/en-gb/learning/ddos/glossary/tcp-ip/]

Fig.2, viewed April 2024, sourced from [https://www.cloudflare.com/en-gb/learning/ddos/glossary/tcp-ip/]

Khan Academy, Transmission Control Protocol (TCP), viewed April 2024, [https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:the-internet/xcae6f4a7ff015e7d:transporting-packets/a/transmission-control-protocol--tcp]

2 AWS 2024, What's the Difference Between HTTP and HTTPS?, viewd Aprl 2024, [https://aws.amazon.com/compare/the-difference-between-https-and-http/]

Vocell, J 2022, A Beginner's Guide to SSL: What It is & Why It Makes Your Website More Secure, viewed April 2024, [https://blog.hubspot.com/marketing/what-is-ssl]

3 Rouse, M 2023, Web Browser, viewed April 2024, [https://www.techopedia.com/definition/288/web-browser]

#### Question 4

Sassi, RB 2023, Compiler vs. Interpreter in Programming, viewed April 2024, [https://builtin.com/software-engineering-perspectives/compiler-vs-interpreter]

baeldung; Albin, M 2024, Compiled vs Interpreted: Programming Languages, viewed April 2024, [https://www.baeldung.com/cs/compiled-vs-interpreted-languages]

#### Question 5

 Logan,d 2023, Top 8 Most Demanded Programming Languages in 2023, viewed April 2024, [https://www.devjobsscanner.com/blog/top-8-most-demanded-programming-languages/]

freeCodeCamp 2020, Just in Time Compilation Explained, viewed April 2024, [https://www.freecodecamp.org/news/just-in-time-compilation-explained/]

Neville, M 2023, The Advantages and Disadvantages of Javascript, viewed April 2024, [https://softjourn.com/insights/the-advantages-and-disadvantages-of-javascript]

Gavrilova, Y 2023, Pros and Cons of Python Programming Language, viewed April 2024, [https://serokell.io/blog/python-pros-and-cons]

#### Question 9

Barenkamp, M; Rebstadt, J & Thomas, O 2020, Applications of AI in classical software engineering, viewed April 2024 [https://link.springer.com/article/10.1186/s42467-020-00005-4]

Fig. 3, viewed April 2024, sourced from [https://www.cloudflare.com/en-gb/learning/ddos/glossary/tcp-ip/]

Dr Attri, RK 2023, Successful Leadership Practices in the Era of AI as a Learning technology Strategist, viewed April 2024, [https://elearningindustry.com] successful-leadership-practices-in-the-era-of-ai-as-a-learning-technology-strategist

intellectsoft 2023, Benefits and Perspectives of Artificial Intelligence in Software Development, viewed April 2024, [https://www.intellectsoft.net/blog/benefits-and-perspectives-of-artificial-intelligence-in-software-development/]

#### Question 10

Ovington, T 2023, 7 AI legal issues and how to deal with them, viewed April 2024, [https://www.walkme.com/blog/ai-legal-issues/#:~:text=Examples%20of%20AI%20legal%20issues,Large%20fines]

Guleria, A; Krishan, K; Sharma, V & Kanchan, T 2023, ChatGPT: ethical concerns and challenges in academics and research, viewed April 2024,  [https://jidc.org/index.php/journal/article/view/37824352/3172J]; Infect Dev Ctries 2023; 17(9):1292-1299. doi:10.3855/jidc.18738

Rodrigues, R 2020, Legal and human rights issues of AI: Gaps, challenges and vulnerabilities, viewed Aprl 2024,[https://www.sciencedirect.com/science/article/pii/S2666659620300056:]

Khurram, M 2023, ChatGPT for Software Development and its Ethical Concerns, viewed April 2024, [https://remotebase.com/blog/chat-gpt-for-software-development-and-its-ethical-concerns-1]

#### Question 11

LinkedIn 2023, Top Hard Skills to Land a JOb as a Software Developer, viewed April 2024, [https://www.linkedin.com/pulse/top-hard-skills-land-job-software-developer-careerscale]

edX 2024, What is cloud computing?, viewed April 2024, [https://www.edx.org/learn/cloud-computing?_gl=1*vjud1v*_ga*MTg2MTY0MzQ0LjE3MTM0MTQ3NzU.*_ga_D3KS4KMDT0*MTcxMzQxNDc3NS4xLjEuMTcxMzQxNTU0MC4yNC4wLjA.]

University of Denver, 18 Skills all programmers need to have, Coding, viewed 18 April 2024 [https://bootcamp.du.edu/blog/programming-skills/]

#### Question 12

Motiso, D 2023, What does a Software Architect Do? (Duties and Requirements), viewed April 2024, [https://www.indeed.com/career-advice/careers/what-does-a-software-architect-do#:~:text=Software%20architects%20identify%20and%20determine,of%20the%20software%20development%20team.]

Sartore, M; Kenebrew, D 2024, Software eveloper Career Overview, viewed April 2024, [https://www.computerscience.org/careers/software-developer/#:~:text=Software%20developers%20write%20code%20using,updates%2C%20and%20upgrades%20as%20needed.]

Staff, Coursera 2024, What Does a DevOps Engineer Do? A Career Guide, viewwed April 2024, [https://www.coursera.org/articles/devops-engineer]

Wade Venz, 15494
