# Patient Information Silos Problem Research  

# Problem Statement Rich Picture  

To visualize the problem statement, I prompted ChatGPT 5.2 with:

```prompt
I am collaborating with others thru Upskilling Labs (https://theupskillinglabs.org/) to improve my skills using artificial intelligence services. I have submitted the problem statement in `problem statement.md` as a topic I would like to investigate as I improve my artificial intelligence programming skills. The problem statement is:

**The Problem**: Healthcare system silos make it difficult for patients to share their ongoing healthcare information with providers as the patients move between providers.

**Context**: Patients are repeatedly asked to provide their health history when seeing a healthcare provider. When new information is available from one provider the patient is often the messenger who has to hand-carry the information to another provider. The need for the patient to transpose and transmit their health data can potentially lead to errors or omissions especially during time-critical periods.  

**Who is closest to this problem**: Individuals / Workers.

**Why it matters now**: Improving the flow of patient information between providers offers the potential to improve healthcare outcomes. Rather than trying to break down the silos between systems, there is an opportunity for individuals to be in control of their own healthcare information in an accurate and timely manner.

Review my problem statement and generate a Rich Picture using Markdown that describes the problem statement?
```

ChatGPT responded with a text-based rich picture.  

```response
 ┌─────────────────────┐        ┌─────────────────────┐
 │  Provider A System  │        │  Provider B System  │
 │  (Hospital / PCP)   │        │  (Specialist / Lab) │
 │                     │        │                     │
 │  • EHR A            │        │  • EHR B            │
 │  • Local records    │        │  • Local records    │
 │  • Internal silo    │        │  • Internal silo    │
 └─────────┬───────────┘        └─────────┬───────────┘
           │                              │
           │   ❌ No direct sharing       │
           │   ❌ Incompatible formats    │
           │                              │
           ▼                              ▼
                 🧍 PATIENT
        ┌────────────────────────────┐
        │  • Asked to recall history │
        │  • Repeats same story      │
        │  • Carries documents       │
        │  • Transcribes results     │
        │  • Manages timelines       │
        │                            │
        │  😟 Stress                 │
        │  ⚠️ Risk of error          │
        │  ⏱  Time pressure          │
        └────────────────────────────┘
           ▲                              ▲
           │                              │
           │  Paper, PDFs, portals        │
           │  Verbal explanations         │
           │  Email / fax / printouts     │
 ┌─────────┴───────────┐        ┌─────────┴───────────┐
 │  Provider C System  │        │  Provider D System  │
 │  (Urgent Care / ER) │        │  (Pharmacy / Rehab) │
 │                     │        │                     │
 │  • EHR C            │        │  • EHR D            │
 │  • Local records    │        │  • Local records    │
 │  • Another silo     │        │  • Another silo     │
 └─────────────────────┘        └─────────────────────┘
```


The detailed ChatGPT reponse with the rich picture is in [2_1_Rich_picture.md](./2_1_Rich_picture.md).  

## Infographic  

I also prompted Google NotebookLM to provide an infographic based on the problem statement.

![Disconnected Data, Empowered Patients Infographic](./2_2_infographic.png)  

The infographic is in [Disconnected Data, Empowered Patients Infographic](./2_2_infographic.png)