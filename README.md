
# 🤖 Splunky Chat AI Assistant

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

A powerful, single-file AI chat interface designed specifically for Splunk Sales Engineers and Solution Architects. Features real-time streaming responses, markdown support, and a beautiful dark-themed UI.
</div>
---
<!-- ABOUT THE PROJECT -->
## About The Project

[![Splunky Chat Example][]](./images/screenshot1.png)

After 10 years of being a SE and now SA, I found it difficult to account for every customer situation and spending a lot of time researching the customer's organization, customer's profile in LinkedIn and working with various Sales Reps...

Splunky Chat is a AI-based Assistant for Techncial Sellers!  

A single HTML file combines ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) to make the installation and deployment super easy!

### Built With

| Frontend | Backend | Hardware |
|:-------------|:------------|:-------------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) | LM Studio | Ryzen 7 9700X |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) | gpt-oss-120b | 64GB DDR5 6000MT |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) | | 3x 3090s (72GB VRAM Total) |

---

<!-- GETTING STARTED -->
## Getting Started

## ⚠️This is NOT an official tool from Cisco/Splunk - use at your own risk!!⚠️
Splunky AI Chat is a free tool for Splunk SEs and SAs to help them get help with Sales and Discovery meetings with RSMs and customers.  Splunky can provide guided sales motions to help maximize everyone's time.  

**Splunky will:**
- Guide you through sales motions from prep-meetings, live meetings and to closing deals
- Recommend appropriate Splunk and Cisco products
- Explain integration architecture
- Provide implementation guidance
- Suggest best practices

---

### Prerequisites

If using the AIaaS (Default) you will need a Web Browser like Chrome, Firefox, Edge, Safari and an active internet connection.

If you are wanting to host your own, download and install LM Studio on your on hardware like a GPU-enabled AI server or on your Cisco-issued laptop.
Your choice of GGUF LLMs from Huggingface.co will determine the quality and speed of the AI output.  Larger models tend to be more accurate and concise, but slower output generation and requires >20GB of VRAM.  Nvidia GPUs w/ 12GB of VRAM is the minimum for decent quality output.  

LM Studio supports inferencing on CPU, GPU (Intel, AMD, Nvidia) as well as Mac M-series GPUs.

---
### Installation
From Git:
1.  Clone the repo
   ```sh
   git clone https://github.com/pmjeffery/lmstudio-webui.git
   ```

2. Open the HTML file in your web browser

Manual:

* Download splunkychat.html

or

* Copy/pasta HTML code to a text file and save as HTML file (filename does not matter)

---

<!-- USAGE EXAMPLES -->
# Usage

## 💡 Pro Tips for Best Results

### Be Specific
❌ "Help me with a customer meeting"  
✅ "I'm meeting with the VP of IT Operations at a retail company next week to discuss their cloud migration monitoring needs"

### Provide Context
Include details like:
- Is this a new/prospective or existing customer
- Customer industry and size, link to the website
- Attendee roles and personas, link to the person's LinkedIn page
- Meeting objectives
- Known pain points or requirements
- Competitor evaluations in play

### Use Follow-Up Questions

Splunky is conversational—engage in back-and-forth dialogue to refine answers and explore alternatives.

### Leverage the "Choose Your Own Adventure" Flow
When preparing for sales calls, let Splunky guide you through the structured preparation process step-by-step.

### Verify Critical Information
While Splunky is highly knowledgeable, always validate:
- Technical specifications for customer environments
- Pricing and licensing details are NOT included!
- Compliance and legal requirements
- Product feature availability

---

## 🎓 Example Workflows

### Workflow 1: Customer Discovery Call Prep
1. "I have a discovery call with [Company Name] in the retail industry"
2. Splunky analyzes their business and suggests discussion topics
3. "Their CTO will be on the call"
4. Splunky provides CTO-focused talking points
5. "They're concerned about application performance"
6. Splunky suggests Splunk Observability solutions and demo angles

### Workflow 2: SPL Query Development
1. "I need to find security events where authentication failed 5+ times"
2. Splunky generates base SPL query
3. "Can you make it more efficient?"
4. Splunky optimizes with summary indexing suggestions
5. "How do I visualize this as a timechart?"
6. Splunky adds visualization commands and explains options

### Workflow 3: Post-Meeting Follow-Up
1. "Generate a follow-up email after a successful demo"
2. Splunky drafts professional email
3. "Include next steps for a POC"
4. Splunky adds POC structure and timeline
5. "Make it more executive-focused"
6. Splunky adjusts tone and adds business value emphasis

---
<!-- ROADMAP -->
## Roadmap
- Documentation for Self-Hosting
    - [ ] Setup LM Studio Server (headless)
    - [ ] Setup LM Studio offline 
    - [ ] Integrate varioud MCP Servers    

- MCP Services
    - [x] Web link Analysis MCP
    - [ ] Web Search MCP (SearXNG)
    - [ ] Splunk MCP

- Functioanal Features

- [x]  Stop/Cancel Button
- [ ]  Loading/Thinking Animation

---
<!-- CONTRIBUTING -->
## Contributing

Find me on Slack to collaborate or contribute
---
<!-- LICENSE -->
## License

Distributed under the Apache 2.0 License
---

<!-- CONTACT -->
## Contact

Find me on Slack
<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

<!-- Shields.io badges. You can a comprehensive list with many more badges at: https://github.com/inttter/md-badges -->
