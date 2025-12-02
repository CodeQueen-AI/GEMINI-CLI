Gemini CLI ek command-line tool hai jo aapko AI ki madad se content, code ya projects banane, edit karne aur manage karne ki sahulat deta hai. Isme extensions ka istemal karke naye features add kiye ja sakte hain, aur logs ke zariye aap actions aur errors track karke problems solve kar sakte hain.
**Why do we use Gemini CLI?**

Gemini CLI ko use karne ke kuch main reasons ye hain:

1. **AI-powered content creation**

   * Aap easily **text, code, ya documents** generate kar sakte ho AI ki help se.
   * Urdu: Ye tool AI ka use karke content ya code banane ka process bohot easy bana deta hai.

2. **Command-line efficiency**

   * Terminal se directly kaam kar sakte ho, GUI ke bina.
   * Urdu: Command-line use karne se speed aur control zyada hota hai, aur repetitive tasks automate ho sakte hain.

3. **Extensions support**

   * Extra features add karne ke liye extensions install kar sakte ho.
   * Urdu: Agar aapko additional functionality chahiye, extensions se wo easily add ho jati hai.

4. **Project management**

   * Projects ko organize aur manage karna easy ho jata hai, including folders, builds, aur deployment.
   * Urdu: Gemini CLI se projects ko structured aur efficient tarike se handle kar sakte hain.

5. **Logs & debugging**

   * Actions aur errors ko track karna easy hota hai.
   * Urdu: Logs dekh kar aap errors trace kar sakte ho aur problems solve kar sakte ho.

**Simple Urdu Summary:**
Hum Gemini CLI is liye use karte hain kyunki ye **AI ki madad se content aur code banata hai**, **projects manage karta hai**, aur **errors track karna easy banata hai**, sab kuch **fast aur efficient** command-line ke zariye.

Agar chaho to mai ab **Gemini CLI ke core commands aur features** step-by-step bata doon, English headings aur Urdu explanations ke saath.


GUI ek aisa interface hai jahan aap visual elements jaise buttons, icons, menus, aur windows use karke computer ya software ke saath interact karte ho, instead of sirf text commands likhne ke. 



**Gemini CLI ke aur features** jo aapko cover karne chahiye, wo ye hain:

---

### **1. AI-Powered Commands**

* Aap **text, code, aur content** generate kar sakte ho directly terminal se.
* Urdu: AI ki madad se writing aur coding ka kaam bohot fast aur easy ho jata hai.

### **2. Editing & Refactoring**

* Existing files ko edit ya improve kar sakte ho AI ke instructions se.
* Urdu: Aap apni files ko modify kar sakte ho without manually changing everything.

### **3. Extensions Support**

* New features add karne ke liye extensions install kar sakte ho.
* Urdu: Extensions se Gemini ki capabilities aur bhi zyada ho jati hain.

### **4. Project Management**

* Projects ko organize karne ke liye folders aur builds manage kar sakte ho.
* Urdu: Aap easily projects create, manage aur deploy kar sakte ho.

### **5. Logs & Debugging**

* Actions aur errors ko track kar sakte ho.
* Urdu: Problems solve karna easy ho jata hai kyunki logs se errors trace hote hain.

### **6. CLI Efficiency**

* Direct terminal commands se kaam fast aur repeatable hota hai.
* Urdu: GUI ke bajaye CLI zyada fast aur automated workflows allow karta hai.

### **7. Cross-Platform Support**

* Windows, macOS, aur Linux pe kaam karta hai.
* Urdu: Har OS pe easily install aur use kiya ja sakta hai.

---

Agar chaho to mai **Gemini CLI ke core commands ka full list** bhi bana doon step-by-step, English headings aur Urdu explanation ke saath, taake aap practice ke liye ready ho jao.



**What are tokens in Gemini CLI?**

Gemini CLI me **tokens** ka kaam AI ke interactions me hota hai.

**Urdu Explanation:**

* **Tokens** basically AI ko diya gaya **unit of text** hai.
* Har word ya punctuation ka AI ke liye ek **token** banta hai.
* Jab aap Gemini me prompt ya instructions dete ho, AI usko **tokens me convert karke process** karta hai.

**Example:**

* "Hello world!" → AI ke liye yeh 3 tokens ho sakte hain: `"Hello"`, `"world"`, `"!"`.
* Zyada tokens ka matlab zyada text aur zyada computation.

**Simple Urdu Summary:**
Tokens AI ke liye **text ke chhote pieces** hote hain jo process kiye jate hain. Gemini CLI me tokens ka istemal **AI ko instructions samajhne aur respond generate karne** ke liye hota hai.

Agar chaho to mai **Gemini CLI me tokens ka practical use aur limit** bhi bata doon, taake concept clear ho jaye.
 


Good question, Code Queen 👑 — depends ki aap Gemini CLI kis version/plan ke sath use kar rahe hain — lekin yeh pata hai ke Gemini (aur uske models) me tokens aur token‑limits ka concept hota hai. ([Google AI for Developers][1])

### 🎯 Token‑limit kya hai?

* Har input (text, image, audio, etc.) aur output jab Gemini process karta hai, usko “tokens” me convert kiya jata hai. ([Google AI for Developers][1])
* Token roughly chhote pieces of text hain — jaise ek token ≈ ~4 characters ka hota hai. ([Firebase][2])

### ✅ Gemini ke token‑limits (aur constraints)

* Kuch Gemini models (e.g. Gemini 1.5 Flash ) ka input‑token limit up to **1,048,576 tokens** hai. ([Google AI for Developers][3])
* Output token limit us model ke liye **8,192 tokens** hai. ([Google AI for Developers][3])
* Agar aap large codebases ya lambi documents CLI ke through process kar rahe hain, to yeh high token‑limit useful hai (matlab aap bohat zyada content ek hi request me bhej/sun) ([Research Memex][4])
* Lekin — CLI use ke sath daily ya per‑minute quotas bhi ho sakte hain. For example free‑tier users ke liye request‑per‑minute ya requests‑per‑day limits hai. ([Google for Developers][5])

### 🔎 Matlab agar aap Gemini CLI use kar rahi hain — yeh cheezein yaad rakhna:

* Jab aap bohat lambi files, documents, ya projects input/send karengi — ensure karein ke total tokens (input + expected output) model ke limit ke andar ho.
* Agar token limit cross hogaya, to Gemini truncate ya error de sakta hai (ya pura process na kare) — isliye thodi soch samajh ke input split karna ya summarise karna useful hai.
* Agar aap free‑tier ya limited‑quota plan use kar rahi hain, to requests count ya daily limit bhi hit ho sakti hai — isliye heavy usage ya bada project ho to plan/limits check karna theek hai.

---

Agar chaho, to **2025 ke hisaab se** Gemini 2.5 Pro model ke **exact token‑limit, request quotas, aur CLI ke liye recommended usage guidelines** tumhare liye fetch kar sakti ho — taake aap sahi tarah plan bana sako. Chahengi Code Queen?

[1]: https://ai.google.dev/gemini-api/docs/tokens?utm_source=chatgpt.com "Understand and count tokens  |  Gemini API  |  Google AI for Developers"
[2]: https://firebase.google.com/docs/vertex-ai/count-tokens?utm_source=chatgpt.com "Count tokens for Gemini models  |  Firebase AI Logic"
[3]: https://ai.google.dev/gemini-api/docs/models/gemini?utm_source=chatgpt.com "Gemini models  |  Gemini API  |  Google AI for Developers"
[4]: https://research-memex.org/implementation/agentic-ai-tools/gemini-cli-setup-guide?utm_source=chatgpt.com "Research Memex - AI-Powered Research"
[5]: https://developers.google.com/gemini-code-assist/resources/quotas?utm_source=chatgpt.com "Quotas and limits  |  Gemini Code Assist  |  Google for Developers"
      


Welcome to Gemini CLI documentation

Copy as Markdown
This documentation provides a comprehensive guide to installing, using, and developing Gemini CLI, a tool that lets you interact with Gemini models through a command-line interface.

Gemini CLI overview
Gemini CLI brings the capabilities of Gemini models to your terminal in an interactive Read-Eval-Print Loop (REPL) environment. Gemini CLI consists of a client-side application (packages/cli) that communicates with a local server (packages/core), which in turn manages requests to the Gemini API and its AI models. Gemini CLI also contains a variety of tools for tasks such as performing file system operations, running shells, and web fetching, which are managed by packages/core.

Navigating the documentation
This documentation is organized into the following sections:

Overview
Architecture overview: Understand the high-level design of Gemini CLI, including its components and how they interact.
Contribution guide: Information for contributors and developers, including setup, building, testing, and coding conventions.
Get started
Gemini CLI quickstart: Let’s get started with Gemini CLI.
Gemini 3 Pro on Gemini CLI: Learn how to enable and use Gemini 3.
Authentication: Authenticate to Gemini CLI.
Configuration: Learn how to configure the CLI.
Installation: Install and run Gemini CLI.
Examples: Example usage of Gemini CLI.
CLI
Introduction: Gemini CLI: Overview of the command-line interface.
Commands: Description of available CLI commands.
Checkpointing: Documentation for the checkpointing feature.
Custom commands: Create your own commands and shortcuts for frequently used prompts.
Enterprise: Gemini CLI for enterprise.
Headless mode: Use Gemini CLI programmatically for scripting and automation.
Keyboard shortcuts: A reference for all keyboard shortcuts to improve your workflow.
Model selection: Select the model used to process your commands with /model.
Sandbox: Isolate tool execution in a secure, containerized environment.
Settings: Configure various aspects of the CLI’s behavior and appearance with /settings.
Telemetry: Overview of telemetry in the CLI.
Themes: Themes for Gemini CLI.
Token caching: Token caching and optimization.
Trusted Folders: An overview of the Trusted Folders security feature.
Tutorials: Tutorials for Gemini CLI.
Uninstall: Methods for uninstalling the Gemini CLI.
Core
Introduction: Gemini CLI core: Information about Gemini CLI core.
Memport: Using the Memory Import Processor.
Tools API: Information on how the core manages and exposes tools.
Policy Engine: Use the Policy Engine for fine-grained control over tool execution.
Tools
Introduction: Gemini CLI tools: Information about Gemini CLI’s tools.
File system tools: Documentation for the read_file and write_file tools.
Shell tool: Documentation for the run_shell_command tool.
Web fetch tool: Documentation for the web_fetch tool.
Web search tool: Documentation for the google_web_search tool.
Memory tool: Documentation for the save_memory tool.
Todo tool: Documentation for the write_todos tool.
MCP servers: Using MCP servers with Gemini CLI.
Extensions
Introduction: Extensions: How to extend the CLI with new functionality.
Get Started with extensions: Learn how to build your own extension.
Extension releasing: How to release Gemini CLI extensions.
IDE integration
Introduction to IDE integration: Connect the CLI to your editor.
IDE companion extension spec: Spec for building IDE companion extensions.
Development
NPM: Details on how the project’s packages are structured.
Releases: Information on the project’s releases and deployment cadence.
Changelog: Highlights and notable changes to Gemini CLI.
Integration tests: Information about the integration testing framework used in this project.
Issue and PR automation: A detailed overview of the automated processes we use to manage and triage issues and pull requests.
Support
FAQ: Frequently asked questions.
Troubleshooting guide: Find solutions to common problems.
Quota and pricing: Learn about the free tier and paid options.
Terms of service and privacy notice: Information on the terms of service and privacy notices applicable to your use of Gemini CLI.
We hope this documentation helps you make the most of Gemini CLI!


