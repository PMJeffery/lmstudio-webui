
# 🤖 Splunky Chat AI Assistant

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

A powerful, single-file AI chat interface designed specifically for Splunk Sales Engineers and Solution Architects. Features real-time streaming responses, markdown support, and a beautiful dark-themed UI.

[Features](#-features) • [Demo](#-demo) • [Installation](#-installation) • [Configuration](#-configuration) • [Usage](#-usage) • [Contributing](#-contributing)

</div>




---

<!-- ABOUT THE PROJECT -->
## About The Project

[![Splunky Chat Example][Splunky Chat Example]](images/screenshot1.png)

After 10 years of being a SE and now SA, I found it difficult to account for every customer situation and spending a lot of time researching the customer's organization, customer's profile in LinkedIn and working with various Sales Reps...

Splunky Chat is a AI-based Assistant for Techncial Sellers!  

A single HTML file combines ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) to make the installation and deployment super easy!

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

| Frontend | Backend | Hardware |
|:-------------|:------------|:-------------|
| ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) | LM Studio | Ryzen 7 9700X |
| ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) | gpt-oss-120b | 64GB DDR5 6000MT |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) | | 3x 3090s (72GB VRAM Total) |


<p align="right">(<a href="#readme-top">back to top</a>)</p>

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



### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/pmjeffery/lmstudio-webui.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```
5. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin pmjeffery/lmstudio-webui
   git remote -v # confirm the changes
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
    - [ ] Nested Feature

See the [open issues](https://github.com/pmjeffery/lmstudio-webui/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top contributors:

<a href="https://github.com/pmjeffery/lmstudio-webui/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=pmjeffery/lmstudio-webui" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the project_license. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/pmjeffery/lmstudio-webui](https://github.com/pmjeffery/lmstudio-webui)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/pmjeffery/lmstudio-webui.svg?style=for-the-badge
[contributors-url]: https://github.com/pmjeffery/lmstudio-webui/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/pmjeffery/lmstudio-webui.svg?style=for-the-badge
[forks-url]: https://github.com/pmjeffery/lmstudio-webui/network/members
[stars-shield]: https://img.shields.io/github/stars/pmjeffery/lmstudio-webui.svg?style=for-the-badge
[stars-url]: https://github.com/pmjeffery/lmstudio-webui/stargazers
[issues-shield]: https://img.shields.io/github/issues/pmjeffery/lmstudio-webui.svg?style=for-the-badge
[issues-url]: https://github.com/pmjeffery/lmstudio-webui/issues
[license-shield]: https://img.shields.io/github/license/pmjeffery/lmstudio-webui.svg?style=for-the-badge
[license-url]: https://github.com/pmjeffery/lmstudio-webui/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username
[product-screenshot]: images/screenshot.png
<!-- Shields.io badges. You can a comprehensive list with many more badges at: https://github.com/inttter/md-badges -->
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
