# LeetCode 450 Roadmap & Daily Progress Tracker

A minimalist, high-performance interactive dashboard and NeetCode-style pattern roadmap to track progress across **450 high-frequency LeetCode interview questions**.

---

## 🌟 Key Features

- **🗺️ NeetCode-Style Dependency Roadmap**: Visual dependency tiers covering 16 core DSA patterns (Arrays & Hashing, Two Pointers, Sliding Window, Trees, Graphs, DP, Intervals, etc.) with real-time completion progress on each pattern card.
- **🎯 Daily 5-Problem Target System**:
  - Daily goal: **2 Easy, 2 Medium, and 1 Hard** problem per day.
  - Category / Pattern focus selection.
  - **⚡ Auto-Pick Button**: Automatically selects the highest-frequency unsolved problems (2 Easy, 2 Med, 1 Hard) from your chosen category.
  - Check off daily targets and mark the day's challenge complete.
- **📋 Interactive Problem Directory**:
  - Full dataset of 450 problems with frequency, acceptance rate, topic tags, difficulty badges, and direct LeetCode links.
  - Instant search and multi-criteria filters (Difficulty, Completion Status, Pattern).
  - Checkbox toggle for every question with local storage persistence (`localStorage`).
- **📱 Clean Minimalist Design**:
  - Self-contained, single-file HTML application with zero build steps or heavy dependencies.
  - Responsive, dark-mode dashboard aesthetics.

---

## 🚀 Getting Started

Simply open `index.html` in any web browser, or serve it locally:

```bash
# Python 3 local server
python3 -m http.server 3000
```

Then visit [http://localhost:3000](http://localhost:3000).

---

## 📁 Repository Structure

```text
├── index.html           # Main standalone interactive dashboard
├── problems_data.json   # Processed problem dataset with pattern classifications
├── 2. Three Months.csv  # 450 high-frequency problem source data
└── README.md            # Documentation
```
