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

# Infographic  

I also prompted Google NotebookLM to provide an infographic based on the problem statement.

![Disconnected Data, Empowered Patients Infographic](./2_2_infographic.png)  

The infographic is in [Disconnected Data, Empowered Patients Infographic](./2_2_infographic.png)

Based on your problem statement, a **Rich Picture** illustrates the complex interactions and "pain points" within the current healthcare information exchange process. A Rich Picture is a visual representation used to capture the stakeholders, their relationships, and the underlying conflicts or challenges in a system.

## **Rich Picture Components**

Google NotebookLM was prompted:

```prompt
I am collaborating with others thru Upskilling Labs (https://theupskillinglabs.org/) to improve my skills using artificial intelligence services. I have submitted the problem statement in problem statement.md as a topic I would like to investigate as I improve my artificial intelligence programming skills. The problem statement is:


**The Problem**: Healthcare system silos make it difficult for patients to share their ongoing healthcare information with providers as the patients move between providers.

**Context**: Patients are repeatedly asked to provide their health history when seeing a healthcare provider. When new information is available from one provider the patient is often the messenger who has to hand-carry the information to another provider. The need for the patient to transpose and transmit their health data can potentially lead to errors or omissions especially during time-critical periods.

**Who is closest to this problem**: Individuals / Workers.

**Why it matters now**: Improving the flow of patient information between providers offers the potential to improve healthcare outcomes. Rather than trying to break down the silos between systems, there is an opportunity for individuals to be in control of their own healthcare information in an accurate and timely manner.

Review my problem statement and generate a Rich Picture that describes the problem statement?
```

Google NotebookLM was responded:

The following elements represent the primary actors and issues identified in your problem statement:

*   **The Central Actor (The Patient):** Often an individual or worker who finds themselves in the middle of disconnected systems.
*   **The Silos (Healthcare Providers):** Multiple independent healthcare providers (e.g., General Practitioners, Specialists, Hospitals) that do not communicate directly with one another.
*   **The Burden of Transmission:** The physical or manual movement of data—often described as the patient acting as a "messenger"—where information is hand-carried from one provider to another.
*   **The Repetition Loop:** The constant requirement for patients to provide their health history from scratch every time they visit a new provider.

### **The "Pain Points" and Risks**

In a Rich Picture, these are often depicted with "jagged" speech bubbles or symbols indicating conflict or danger:

*   **Data Vulnerability:** The high risk of **errors or omissions** when a patient is required to transpose their own health data.
*   **Temporal Pressure:** The increased danger during **time-critical periods** where delayed or inaccurate information can impact care.
*   **Communication Gaps:** The literal "silos" that block the flow of information, forcing the patient to bridge the gap manually.

### **Visual Summary of the Problem State**

| Element | Description in the System |
| :--- | :--- |
| **Actors** | Individuals/Workers (Patients) and disconnected Healthcare Providers. |
| **Primary Action** | Patients hand-carrying and transposing information between providers. |
| **Key Conflict** | **System silos** preventing automatic information flow. |
| **Major Risks** | Inaccurate data, omissions, and poor healthcare outcomes due to fragmented info. |
| **Desired Shift** | Transitioning from silos to **individual control** of healthcare information. |

### **The Opportunity for Your AI Project**

Your goal of using AI to address this fits into the "Why it matters now" section of your statement. Rather than trying to dismantle massive institutional silos, your project focuses on empowering the **individual to be in control** of their own information. This suggests a solution where AI might assist the patient in accurately capturing, transposing, or managing their data to ensure it is **accurate and timely**.

**Clarifying Question:** As you move into the programming phase, are you planning to focus on the **extraction/transposition** of data (to reduce errors) or a **centralized platform** for the individual to manage the flow of information?

## Research (investigation) phase

```prompt
Part of this investigation phase is to identify if the development (programming) phase should focus on either the extraction/transposition of data (to reduce errors) or a centralized platform for the individual to manage the flow of information, or both.
```

The investigation phase suggests that your development phase should likely focus on **both** extraction/transposition and a centralized platform to fully address the issues identified in your problem statement.

Focusing on both areas allows you to solve the immediate mechanical failure of data movement while fulfilling the long-term goal of patient empowerment.

### **Focus 1: Extraction and Transposition**
Developing tools for the accurate extraction of data is essential to mitigate the risks currently faced by patients acting as manual "messengers".
*   **Reducing Human Error:** Currently, patients must transpose and transmit their own data, a process prone to **errors or omissions**.
*   **Time-Critical Accuracy:** Improving the speed and accuracy of data extraction is vital during **time-critical periods** where manual handling may fail.
*   **Relieving the "Messenger" Burden:** AI-driven extraction can automate the transition of information that patients are currently forced to hand-carry between providers.

### **Focus 2: Centralized Platform for Individual Control**
While extraction solves the "how" of data movement, a centralized platform addresses the "where" and "who," directly tackling the issue of **healthcare system silos**.
*   **Individual Agency:** The core opportunity identified is for **individuals to be in control** of their own healthcare information.
*   **Bypassing Silos:** Rather than attempting to dismantle existing institutional silos, a platform allows the individual to maintain an **accurate and timely** record that moves with them.
*   **Coherent Health History:** A platform prevents the need for patients to be "repeatedly asked" for their history, as the information is stored in a centralized, patient-controlled environment.

### **Summary of Development Priorities**

| Feature Area | Problem Addressed | Goal |
| :--- | :--- | :--- |
| **Extraction/Transposition** | Errors, omissions, and manual "messenger" work. | Ensure data integrity and reduce the burden on the patient. |
| **Centralized Platform** | System silos and lack of patient control. | Provide a timely, individual-controlled flow of information. |

**Clarifying Question:** To help narrow the scope of your programming phase, do you intend to prioritize a specific type of healthcare data first (e.g., medication lists, lab results, or general history), or are you looking to build a general-purpose tool for all health information?

# Bringing Together Research

Google NotebookLM was given other sources identified by collaborators on the Patient Information Silo project and it was asked:

```prompt
Other colleagues on the Patient Information Silos project team have identified additional sources related to patient information. Review the sources and consider how the information from the sources can be used in solving the problem outlined in the problem statement.
The sources are not likely to provide a complete answer to the problem statement. However they may provide additional information which will help in finding a solution.
```

The additional sources provided by your colleagues offer several technical and strategic pathways to address the healthcare system silos identified in your problem statement. Specifically, they highlight established standards for data exchange, existing national networks, and patient-facing tools that can be leveraged to put individuals in control of their information.

### **1. Leveraging Interoperability Standards (FHIR)**
The sources emphasize the role of **Fast Healthcare Interoperability Resources (FHIR®)** as the foundational standard for modern healthcare data exchange.
*   **Structured Health History**: FHIR defines specific resources for the very information patients are repeatedly asked to provide, such as **AllergyIntolerance, Immunizations, and MedicationAdministration**.
*   **Reducing Transposition Errors**: By using FHIR-based **REST APIs**, data can be moved programmatically rather than manually. This directly addresses the risk of "errors or omissions" caused by patients acting as manual messengers.
*   **Standardized Summaries**: The **International Patient Summary (IPS)** is identified as a key implementation guide for document exchange, allowing for a standardized clinical summary that moves with the patient across different systems and even borders.

### **2. Utilizing Existing "Networks of Networks"**
The **eHealth Exchange** is described as the largest healthcare information network in the country, connecting federal agencies, medical groups, and 75% of U.S. hospitals.
*   **Individual Access**: A specific use case for this network is to **"Empower individuals with easy and transparent access to their health records"**. This provides a pre-existing infrastructure for your goal of individual control.
*   **Vendor Agnosticism**: The network is vendor-agnostic and connects to any EHR system using industry standards, which helps bypass the problem of institutional silos without needing to "break them down" individually.
*   **TEFCA Integration**: The network supports the **Trusted Exchange Framework and Common Agreement (TEFCA)**, a national initiative to expand secure data access through a single connection.

### **3. Patient-Controlled Portals and Sharing Tools**
Tools like **Epic’s MyChart** are already being used by over 190 million patients to manage their health.
*   **Unified Access**: **MyChart Central** provides a way for patients to use a **single login** to share data from multiple medical records across different organizations.
*   **Direct Portability**: Features like **"Share Everywhere"** allow patients to grant providers access to their records on the spot, fulfilling the "timely manner" requirement of your statement.

### **4. Enhancing Experience with AI and Digital-First Tech**
The sources suggest that the majority of Americans (79%) prefer using technology to manage their healthcare and 81% want **self-service** options.
*   **Streamlining Interactions**: AI-driven digital technology can optimize patient-provider interactions, making the flow of information "seamless" rather than a burden on the patient.
*   **Automated Guidance**: AI can support **Clinical Decision Support (CDS)** through tools like **CDS Hooks**, which provide real-time suggestions to providers based on the patient's data, potentially improving the healthcare outcomes mentioned in your statement.

### **Application to Your Project**
These sources suggest that your development phase doesn't need to invent new ways to move data. Instead, it can focus on **AI-driven interfaces** that interact with these established **FHIR APIs**. 

For example, your project could focus on an AI assistant that help an individual **extract and verify** their history from a FHIR endpoint (addressing transposition errors) and then **manage the sharing** of that verified record through an established network like the eHealth Exchange (addressing the centralized platform/control goal).

**Confirmation Request:** Would you like me to generate a **Tailored Report** that synthesizes these sources into a formal technical strategy for your programming phase?

## Bridging Healthcare Silos Infographic

```prompt
Please create an infographic that shows how the additional sources help in solving the problem statement, as described in the note `Bridging Healthcare Silos Through FHIR and Patient-Centric AI`.
```

![Bridging Healthcare Silos Infographic](./2_3_Bridging_Healthcare_Silos_Infographic.png)

# Architectural Blueprint for Universal Health Data Integration

```prompt
Please generate a Tailored Report that synthesizes these sources into a formal technical strategy for your programming phase?
```

I have generated a **Technical Strategy Report** for your programming phase. This report synthesizes the information from the sources to outline how you can use industry standards like **FHIR** and **IPS**, alongside national networks like the **eHealth Exchange**, to solve the problem of healthcare silos. You can find this artifact in the Studio tab.

### **Technical Strategy Overview**

*   **Foundation in FHIR Standards**: The strategy prioritizes the use of **Fast Healthcare Interoperability Resources (FHIR®)** to programmatic movement of data, specifically focusing on resources like **AllergyIntolerance, Patient, Immunization, and MedicationAdministration**. 
*   **Leveraging National Networks**: Instead of building point-to-point integrations, the strategy utilizes the **eHealth Exchange**, which connects 75% of U.S. hospitals and specifically supports **Individual Access** to empower patients with easy and transparent access to their records.
*   **Standardized Portability**: A key technical pillar is the **International Patient Summary (IPS)**, which provides a standardized clinical summary that can move with the patient across different systems.
*   **AI and Workflow Integration**: The strategy incorporates **SMART App Launch** protocols to embed your solution within existing portals like **MyChart** (which has over 190 million users) and uses **CDS Hooks** to provide real-time clinical support during time-critical care periods.
*   **Patient Agency**: By using a single set of APIs and adhering to the **Trusted Exchange Framework and Common Agreement (TEFCA)**, the solution allows individuals to maintain an accurate and timely record without the risk of manual **errors or omissions**.

Would you like me to create an **Infographic** that visualizes this data flow and the different FHIR resources involved in your strategy?

## Infographic

```prompt
Please generate an infographic based on the data you have just generated for the `Architectural Blueprint for Universal Health Data Integration` note.
The infographic should show how the new sources help address the problem statement.
```

![Health Data Integration Blueprint](./2_4_Health_Data_Integration_Blueprint.png)

