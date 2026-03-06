```notes
**The Problem**: Healthcare system silos make it difficult for patients to share their ongoing healthcare information with providers as the patients move between providers.

**Context**: Patients are repeatedly asked to provide their health history when seeing a healthcare provider. When new information is available from one provider the patient is often the messenger who has to hand-carry the information to another provider. The need for the patient to transpose and transmit their health data can potentially lead to errors or omissions especially during time-critical periods.  

**Who is closest to this problem**: Individuals / Workers.

**Why it matters now**: Improving the flow of patient information between providers offers the potential to improve healthcare outcomes. Rather than trying to break down the silos between systems, there is an opportunity for individuals to be in control of their own healthcare information in an accurate and timely manner.
```

```notes
**The Problem**: It is hard to keep track of/have access to one's complete medical records across multiple providers over time.

**Context**: Often, when we go to urgent care, ER, or a new provider, we are asked questions about our medical history that we cannot remember the answer to: when was the last time you had a certain vaccine, specific medications, etc. We might be able to find an answer to some on different platforms (e.g. proprietary EHR systems, etc) but not all providers use the same platform. It would help if there is a way to have access to our medical records across multiple providers over time and without any (or minimal) manual effort.

**Who is closest to this problem**: Individuals/patients.
```
```notes
The provided sources explore the mechanisms and impacts of Health Information Exchange (HIE), focusing on the distinct roles of “push” and “pull” technologies. The Fast Healthcare Interoperability Resources (FHIR)standard is highlighted as a modern, web-based framework designed by HL7 to facilitate this data sharing through flexible, discrete resources. While “push” HIE automates the delivery of specific records to providers, “pull” HIE allows clinicians to query across multiple organizations for a comprehensive patient history. Research indicates that physicians often prefer push HIE for its ease of use and workflow integration, yet pull HIE is uniquely associated with reducing avoidable hospitalizations. These technologies are increasingly managed through public-private initiatives like the eHealth Exchange to bridge fragmented medical records. Ultimately, the sources suggest that combining both exchange models is essential for achieving interoperability and improving the overall quality of clinical care.
```

```notes
Once upon a time before smart phones, there was a tool called a “Mingle Stick” that people could use to send their contact information to someone else with the push of a button. In that vein, I’m thinking of an encrypted app that an individual could use to send a health record link/connection to all of their physicians. For instance, a single user controlled database to which both the individual and their physicians could add information.  It’s a push/pull model in that information from one physician or the patient would automatically be available to all.  
  
To overcome the obstacle of data locked in entrenched organizational health apps, AI could recognize fields in existing systems and bring all the information together in one view.  When a patient enters a new health care facility, they could grant permission to that facility to have access to their health records.  
  
This is all based on my old pre-AI thinking. Smash it down or reform at will.
```

```notes
Resource for thinking/ideas:  [https://ehealthexchange.org](https://ehealthexchange.org)
```

```notes
I too get frustrated `having to hand re-write information at multiple health care facilities.` This is what promoted me to write the problem statement.  
I also get frustrated when told something cannot be done because of HIPAA. I get the feeling that HIPAA is an excuse to create systems in a _walled garden_.
```

```notes
CURES reduces information blocking which could have triggered HIPAA violations . CURES is about when and how entities must share data - more info at :[CURES and HIPAA Compliance](https://chatgpt.com/c/69836e7e-b5b0-8327-8ca0-e176f2ab3b11)
```

```notes
I was recently surprised when I visited an elderly relatives's physician and she did not familiarize herself with with historical data about prior surgery which she actually performed 12 months ago.  That said she is a very proficient surgeon and the day of the surgery she had a good bedside manner.
```

```notes
As there are already several, proprietary medical information databases that various medical facilities use, I’m wondering if AI would update whichever one a health provider is using with the owning individual’s information, i.e., I suspect it will take a critical mass before health providers switch to a patient owned model.  There’s also the question of working with old school offices that still use paper. Maybe a formatted print-out?  Just thoughts.
```

```notes
About a year ago I was talking to a Hospital VP about this issue, and he said that alot of health systems and providers use a proprietary EHR system([proprietary system URL redacted]) to share your health data (the patient has given permission for health systems to view this data).  TBH, I haven't looked into it any further than this, but this might be an interesting place to dig into Medical record sharing.
```

```notes
In follow up to the info as it relates to the hospitals who use a proprietary EHR system - here is a presentation about their roadmap and approach to supporting FHIR interoperability  (which will support standard data  formats for sharing ) [[proprietary system FHIR roadmap URL redacted]]([proprietary system FHIR roadmap URL redacted])
```

```notes
I started looking at the vendor services PDF and found a proprietary EHR system - [[proprietary system URL redacted]]([proprietary system URL redacted])

It doesn't say anything about the patient being able to update info about themselves... seems like this info only comes from the doctors office, but is not pushed from patient to all doctors offices (unless going through a check in process).  That might be an interesting opportunity to sus out.
```

```notes
In my experience the proprietary EHR system patient portal looks different across health systems (of course) depending on what they desire to track from their patients. I've noticed that for Healthsystems that receive state funding or are tied to an academic institution there are more features available for patients to add medical history and in many cases requested changes to incorrect information.
```

```notes
I took a Introduction to Vibe Coding class yesterday and encountered the issue of patient updates. I came out of the class with a basic website that displays fake patient data. I want to update it to allow patient updates and interfaces to the various patient information proprietary EHR systems. I’m not a coder and am just learning vibe coding, so this will take a while.
```

```notes
ChatGPT told me that a proprietary EHR system supports FHIR which would allow a third party to update patient data.  we would also have to give thought of how the patient consent step is addressed ( more here: [proprietary EHR system & FHIR](https://chatgpt.com/c/69836c18-5f7c-8329-84db-3a9f1629278d) )
```

```notes
I signed on to one of the proprietary EHR systems I have access to this afternoon.  It allows me to update my immunizations.  The challenge I  need to research is that I had my flu shot so I need to get the info from pharmacy, sign back on and then update the proprietary EHR system.
```

```notes
After reading the comment about getting info from multiple doctors, I can see if there is a way to share that info with my primary care / physician practice.
```

```notes
I used [Perplexity.ai](http://Perplexity.ai) to dig into whether a solution could ride on a proprietary health platform, rather than reinventing the data transfer wheel.  The results are [here](https://www.perplexity.ai/search/is-apple-health-hipaa-complian-LJApavjURM._5lon1EJMYA#0).  While there is much that is positive, there are significant barriers to adoption  on the provider side.  To that end, Perplexity lists some suggested areas for work that would lower the barrier to adoption.
```