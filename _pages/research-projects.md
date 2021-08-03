---
layout: archive
title: "Research & Projects"
permalink: /research-projects/
author_profile: true
redirect_from:
  - /resume
---

<p align="justify">
My research goal is to develop autonomous resilient systems using cyber deception and moving target defense to detect and mitigate advanced persistent threats (APT), especially malware, spear-phisher, and network reconnaissance attacks. 

My research aims to build intelligent agents that make adaptive, risk-aware, and cost-effective defense decisions autonomously by learning the environment and considering the uncertainty of the attacker’s true strategy while ensuring resiliency and fulfilling of business policy.

For optimal defense action planning and system orchestration, I use discrete optimization (SMT), sequential decision making (MDP/POMDP), reinforcement learning, etc. 

I have hands-on experience building software for diverse fields using the MITRE ATT&CK framework, software-defined networking (SDN), cryptography, email protocols, payment applications, and more. 
</p>

<h2>ActiveSDN</h2> <a href="https://github.com/rakeb/activesdn/commits/clipstranslation">[code-activesdn]</a> <a href="https://github.com/rakeb/activesdn_middleware">[code-activesdn-middleware]</a> <a href="https://rakeb.github.io/files/publications/deception_secdev/Active_Deception_Framework_SecDev.pdf">[paper-1]</a> <a href="https://rakeb.github.io/files/publications/mtdsynth/mtdsynth.pdf">[paper-2]</a>

<p align="justify">
An open programming environment that enables developing and prototyping advanced active cyber defense mechanisms (such as IP or route mutation, honey network creation) rapidly and safely on Software Defined Networking (SDN). ActiveSDN also provides a language for security policy specification.<br>
<b>Tools/languages:</b> OpenDaylight, OpenFlow, Java, Python, VMware, TCP, UDP, ICMP.
</p>


<h2>Email Mutation</h2> <a href="https://github.com/rakeb/email-address-mutation">[code]</a> <a href="https://rakeb.github.io/files/publications/em/Email_Mutation_Paper.pdf">[paper]</a>

<p align="justify">
Sender Email address Mutation is a novel protocol to detect the lateral spear-phishing attack in which an adversary sends phishing emails to a victim from a legitimate but compromised email account. The protocol works with any mail service providers such as Gmail, Apple iCloud, and mail clients, such as mail.gogole.com, Outlook, Thunderbird, etc.<br>
<b>Tools/languages:</b> SMTP, IMAP, Django, Python, Java, Chrome Extension.
</p>


<h2>Panacea: Email Header Analytics</h2> <a href="https://github.com/rakeb/email-header-classifier">[code]</a>

<p align="justify">
Panacea is a multi-layer system to defend against email borne threats such as spamming, spoofing, and spear-phishing attacks. In Panacea, we use different techniques, including Machine Learning, NLP, real time active investigation such as evaluating domain reputation to detect such threats.<br>
<b>Tools/languages:</b> Scikit-learn, Django, Python, C++, Git, Docker, Kubernetes, Apache Kafka.
</p>


<h2>Chimera: Autonomous Cyber Deception Planer</h2>

<p align="justify">
Chimera is an autonomous orchestrator to design a deception environment in order to detect and deceive advanced persistent threats such as Ransomware, Information Stelar, RAT. 
Due to the uncertainty and dynamic nature of the attackers, I use Partially Observable Markov Decision Processes (POMDP) to observe adversary techniques based on MITRE ATT\&CK framework and reinforcement learning to learn from the environment to choose the optimal deception actions.<br>
<b>Tools/languages:</b> MITRE ATT&CK, POMDP, Python, C++, OpenAI, EasyHook, Windows API.
</p>

<h2>FIPS Certification for KONA N41M0 Smart Card</h2>
<p align="justify">
Developed and documented the Demonstration Applet to achieve Security Requirements for Cryptographic Modules FIPS 140-2. The secure module KONA N41M0 get certified on November 25, 2015 (<a href="https://csrc.nist.rip/groups/STM/cmvp/documents/140-1/140crt/FIPS140ConsolidatedCertNov2015.pdf">certificate no. 2476 and 2478</a>).<br>
<b>Tools/languages:</b> JavaCard, JAVA, specs: FIPS-140, PKI, Elliptic Curve Cryptography, NIST.
</p>

<h2>Payment Applet</h2>
<p align="justify">
As a team-lead, I designed the architecture of AMEX, JCB, and Discover Payment applications. I developed the critical crypto modules such as application cryptogram generation, cardholder verification, secure massaging, etc.<br>
<b>Tools/languages:</b> JavaCard, Java, specs: Amex, JCB, Discover and PCKS.
</p>

<h2>KonaPay</h2>
<p align="justify">
I was a Scrum Master and team lead of the project KonaPay which is a payment solution compliant with EMV, VISA and MasterCard Payment Specifications.<br>
<b>Tools/languages:</b> JavaCard, Java, specs: EMV, GlobalPlatform, Mastercard and VISA specifications, PCKS, NIST.
</p>
