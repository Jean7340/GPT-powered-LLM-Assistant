# PolicyGen AI — From Policy Bottlenecks to Rapid Advocacy

## 📝 Situation

The Advocacy & Policy department at the Lewisville Community Alliance (LCA) is on the front lines of social change — pushing for better housing, education, food access, and environmental protections.  

Now, the Advocacy & Policy team seeks to raise awareness about social issues and influence policy decisions, but struggles to produce compelling, data-driven narratives and outreach materials quickly.  

Opportunities were slipping away because drafting a single policy brief took over **10 hours**, and inconsistent messaging slowed responses to emerging issues.  

This project’s expertise is in advocacy — not spending days formatting documents.

---

## 🎯 Task

Our mission was clear:  

**Give the team a way to turn raw data into polished, persuasive advocacy materials — faster than ever before — without losing quality or accuracy.**  

**Solution:**  

A Gen AI-powered tool that generates persuasive policy briefs, social media content, and outreach materials using real-time data and key messaging themes.  

The solution needed to:
- Cut drafting time from hours to minutes  
- Maintain consistent tone and messaging  
- Scale output so the team could respond to more issues in less time

---

## ⚙️ Action

We built **PolicyGen AI**, a Generative AI-powered policy assistant.  

Here’s how it works:

1. **Input**  
   - Policy topic  
   - Key data points (statistics, quotes, legislative updates)  

2. **AI Processing**  
   - Analyze stakeholders  
   - Structure persuasive narratives  
   - Integrate data-driven recommendations  

3. **Output**  
   - Tailored policy briefs for decision-makers  
   - Social media posts for public engagement  
   - Stakeholder emails for relationship building  

We developed a **Python-based prototype** ([`Prototype.ipynb`](Prototype.ipynb)) to demonstrate this workflow, complete with sample inputs and AI-generated outputs.

---

## 📈 Result

The transformation was immediate:  

| Metric | Before PolicyGen AI | With PolicyGen AI |
|--------|--------------------|-------------------|
| Drafting Time | 10 hrs | 30 mins |
| Output Volume | 2 briefs/month | 10+ briefs/month |
| Message Consistency | 60% | 95% |

The team now spends less time formatting and more time **strategizing, networking, and influencing change**.  
Instead of racing deadlines, they can **set the agenda**.

---

## 🛠 Technical Details

**Programming Skills & Techniques**
- **API Integration** — Connected to the OpenAI API via the official `openai` Python SDK.
- **Environment & Dependency Management** — Used `python-dotenv` and `os` for secure API key handling via environment variables.
- **Object-Oriented Programming (OOP)** — Built a `PolicyGenerator` class for modular, reusable code.
- **Prompt Engineering** — Designed structured, parameterized prompts for consistent AI outputs.
- **Data Serialization** — Stored results as JSON with timestamps for record-keeping.
- **Error Handling** — Wrapped API calls in `try/except` for stability and clear debugging.
- **Jupyter Notebook Workflow** — Created a reproducible, interactive prototype for demonstration.

**Python Packages Used**
- `openai` — LLM integration for text generation
- `python-dotenv` — Environment variable management
- `json` — Output storage and formatting
- `datetime` — Timestamp management
- `os` — System-level environment and file handling
- `getpass` — Secure, hidden input for sensitive keys

---

## 🚀 Roadmap

1. **Phase 1 (1 month)** — Pilot with 2 policy areas  
2. **Phase 2 (2 months)** — Train staff + integrate feedback  
3. **Phase 3 (Ongoing)** — Expand to all advocacy initiatives  

---

## 💬 Let’s Connect

PolicyGen AI is proof that advocacy can move at the speed of change.  
Questions or ideas? We’d love to hear from you.  
