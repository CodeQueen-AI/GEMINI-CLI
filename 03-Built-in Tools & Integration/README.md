Bilkul Code Queen 👑! Mai tumhare liye **sirf Built-in Tools & Integration** ka **clean aur README-friendly version** ready kar deti hoon:

---

# **🛠️ Gemini CLI Built-in Tools & Integration**

**Topic Name:**
**Gemini CLI Built-in Tools Integration**
*(Ye topic batata hai ke CLI ke andar jo tools built-in hote hain, wo kaise kaam karte hain aur kaise integrate hote hain.)*

---

## **1️⃣ File System Tools 📂**

* **Tools:** `read_file`, `write_file`
* **Functionality:**

  * `read_file` → File ka content read karna
  * `write_file` → File me data likhna ya update karna
* **Example Use Case:** Notes save aur read karna
* **Integration Example:**

```python
content = read_file("notes.txt")
write_file("notes.txt", "New note added")
```

---

## **2️⃣ Shell Tools 💻**

* **Tool:** `run_shell_command`
* **Functionality:** System commands CLI ke through run karna (e.g., `mkdir`, `ls`)
* **Example Use Case:** Folder create karna ya system info check karna
* **Integration Example:**

```python
output = run_shell_command("mkdir myfolder")
print(output)
```

---

## **3️⃣ Web Tools 🌐**

* **Tools:** `web_fetch`, `google_web_search`
* **Functionality:**

  * `web_fetch` → Kisi URL se content fetch karna
  * `google_web_search` → Google search result fetch karna
* **Example Use Case:** CLI se kisi topic ka summary fetch karna
* **Integration Example:**

```python
page_content = web_fetch("https://example.com")
search_results = google_web_search("AI news")
```

---

## **4️⃣ Memory / Todo Tools 📝**

* **Tools:** `save_memory`, `write_todos`
* **Functionality:**

  * `save_memory` → Temporary ya permanent info store karna
  * `write_todos` → User ke tasks/notes save karna
* **Example Use Case:** AI assistant me user instructions ya todo list save karna
* **Integration Example:**

```python
save_memory("user_name", "Sumbal")
write_todos("Complete AI project")
```

* **Where to write in Gemini CLI:**

  * **Interactive CLI Session:** Open CLI → commands directly type karo.
  * **Script / Extension:** Script me import aur call karo → automation ke liye use karo.

---

## **💡 Integration Tips**

1. Identify karo kis functionality ke liye tool chahiye
2. Core ya extension me call karo
3. Input pass karo → output handle karo → next step me use karo

---

Agar chaho to mai **ek simple visual diagram** bhi bana doon jo **Built-in Tools ka workflow** dikhaye, taake instantly samajh aaye.

Chahogi mai wo bana doon?
