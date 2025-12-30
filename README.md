# 📊 SurveyEngine Pro - Interactive POC

A professional, hierarchical survey management system designed for real-time feedback and performance analytics. This Proof of Concept (POC) demonstrates a fully reactive "Single Page Application" (SPA) that works entirely in the browser.

---

## 🚀 Live Demo Link
**[CLICK HERE TO VIEW THE APP](https://ggkh-autogenix.github.io/survey-app/))** 

---

## 🌟 Key Features

### 🛠️ Admin Control Center
* **The "Tree" Organizer:** Build surveys like a folder structure. Create a Main Survey (Level 1), Sub-Categories (Level 2), and detailed Topics (Level 3).
* **Full CRUD Engine:** Add, Edit, or Delete questions and their multiple-choice options instantly.
* **Weighted Scoring:** Assign numerical values (1–5) to text answers to turn opinions into hard data.

### 📝 Interactive Survey Page
* **Drill-Down Navigation:** Users aren't overwhelmed. They select a "Root Survey" first, then choose a category to provide feedback.
* **Mobile-First Design:** Fully responsive interface that works on phones, tablets, and desktops.
* **Zero-Refresh Sync:** Changes made in Admin appear on the survey page immediately without refreshing.

### 📈 Instant Results Dashboard
* **Live Analytics:** View average performance scores and total submission counts per category.
* **Activity Logs:** See a running list of the most recent feedback submissions.

---

## 📖 Quick User Manual

### 1. Building your Survey (Admin)
1.  Click **Admin** in the top menu.
2.  Click **+ Add Root Survey** to start.
3.  Hover over your new survey and click **SUB** to add a sub-category.
4.  Select a category to open the **Question Editor**.
5.  Add a question, then click **+ ADD OPTION** to define your multiple-choice answers.

### 2. Testing the User Experience
1.  Switch to the **Take Survey** tab.
2.  Select the Survey you just built.
3.  Select the Category.
4.  Answer the questions and hit **SUBMIT**.

### 3. Reviewing Data
1.  Go to the **Reports** tab.
2.  Observe how the "Average Score" and "Response Count" have updated instantly.

---

## 🛠️ Technical Details
* **Frontend:** React 18, Tailwind CSS.
* **Database:** LocalStorage API (No login required, data stays on your device).
* **Math Logic:** Calculates weighted averages:
    $$\text{Avg} = \frac{\sum(\text{Choice Value})}{\text{Total Responses}}$$

---

## 👤 For Reviewers
This app is a standalone POC. Since it uses **Local Storage**, the data you create is private to your browser. To show others your setup, you would demo it on your screen or have them create their own test data via the Admin link.
