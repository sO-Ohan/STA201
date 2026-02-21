# STA201: Elements of Statistics & Probability
**Spring 2026 | RFI Section 05 | Collaborative Notes Vault**

> 🔗 **Access Official Course Material (Google Drive)**

## 📌 Repository Objective
This repository serves as a centralized, collaborative environment for STA201 students in Section 05. The primary objective is to aggregate lecture notes, reference materials, and study guides to maximize academic success and efficiency for the entire class. Peer-to-peer sharing is highly encouraged.

## 📂 Directory Structure
To maintain organization, all student-contributed notes must be placed within the `Notes` directory, categorized within a folder bearing your name.

**Example Path:** `Notes/Firstname_Lastname/Lecture_01_Summary.pdf`

## 🛠️ Contribution Guidelines (Pull Requests)
We welcome and encourage contributions from all students. Please follow the instructions below based on your operating system or preferred platform to submit your notes via a Pull Request.

<details>
<summary><b>🌐 1. Web Browser Method (No installation required)</b></summary>

* **Fork the Repository:** Click the Fork button at the top right of this page to create a personal copy of this repository.
* **Navigate:** Open the `Notes` directory in your forked repository.
* **Create Directory:** Click Add file > Create new file. Type `Your_Name/` to create your personal folder, followed by your file name (e.g., `Your_Name/Lecture_Notes.md`).
* **Upload/Write:** Upload your PDF/Document or write your notes directly in the editor.
* **Commit:** Scroll to the bottom, provide a brief summary of your upload, and click Commit changes.
* **Pull Request:** Return to the main page of your forked repository, click Contribute, and select Open pull request. Submit the request.

</details>

<details>
<summary><b>🐧 2. Linux CLI Method (Arch / Ubuntu)</b></summary>

Execute the following commands in your terminal:

```bash
# 1. Clone the repository locally
git clone [https://github.com/YOUR_USERNAME/STA201.git](https://github.com/YOUR_USERNAME/STA201.git)
cd STA201

# 2. Create a dedicated branch for your contribution
git checkout -b update-notes-yourname

# 3. Create your personal directory and add your files
mkdir -p Notes/Your_Name
cp ~/path/to/your/document.pdf Notes/Your_Name/

# 4. Stage, commit, and push your changes
git add Notes/Your_Name/
git commit -m "Add lecture notes by Your_Name"
git push -u origin update-notes-yourname
