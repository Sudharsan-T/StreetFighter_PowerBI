# 🎮 **Street Fighter Character Selection Dashboard** 🎮

### 🔗 **Dashboard Link**: [Click Here](https://app.powerbi.com/view?r=eyJrIjoiMGExZjRhODItYTRjMy00YTc5LWEzOGMtN2FjMWFhMjczZTU2IiwidCI6IjFjNmQwOGQ3LTA2NGMtNDdiNC1hODgwLWRlYmZhNjk4YWVlOCJ9)

### 🔍 **Dashboard Overview**
This Power BI project is a **dynamic and interactive character selection dashboard** inspired by Street Fighter. The dashboard utilizes **SVG, HTML content, and image URLs** to display character details and allow users to explore various fighters visually.

## 📊 **Problem Statement**
The goal of this project is to create an engaging **character selection interface** within Power BI, demonstrating the platform's ability to handle **interactive visual elements**. The dashboard allows users to:

- 🔄 **Browse Street Fighter characters** with images and stats.
- 🌟 View details like **height, weight, likes, dislikes, and background story**.
- ⚖️ **Filter characters** based on attributes.
- 💻 **Enhance Power BI visualization** by integrating **SVG and HTML content**.

### 🎨 **What is SVG in Power BI?**
SVG (Scalable Vector Graphics) is a powerful vector image format used to create high-quality and interactive visuals. In Power BI, SVG can be used to:
- ✨ Generate **custom visuals and dynamic elements**.
- 📚 Enable **interactive graphics**, such as **custom character selection interfaces**.
- 🎉 Improve dashboard aesthetics with **scalable and high-resolution images**.

### 🖼️ **What is ImageURL and Its Importance?**
ImageURL is a method used in Power BI to display images dynamically from an external or internal source. Key benefits and uses include:
- 🌐 **Efficient image rendering** without embedding large image files.
- 🔄 **Dynamic updates** based on dataset changes.
- 🌟 **Enhanced user experience** with high-quality visuals in reports.
- 🛠️ Allows **web-based image integration** directly into Power BI dashboards.

### 🔢 **Steps Followed**

- **Step 1**: 📖 Collected character data and images. **[Dataset Link Here]**
- **Step 2**: 🌄 Designed the dataset with attributes such as name, height, weight, likes, dislikes, and bio.
- **Step 3**: 🖼️ Stored **image URLs** for seamless integration into Power BI.
- **Step 4**: 🛠️ Used **SVGs and HTML content** for enhanced interactivity.
- **Step 5**: 💾 Loaded data into Power BI using an **Excel file**.
- **Step 6**: 📱 Utilized the **HTML Viewer Custom Visual** to render images.
- **Step 7**: 🧪 Created **DAX measures** to manage filtering logic and interactivity.
- **Step 8**: 💎 Styled the dashboard with a **Street Fighter-inspired theme**.
- **Step 9**: 🎨 Implemented **conditional formatting** for visual appeal.
- **Step 10**: 📰 Published the report to **Power BI Service**. **[Project File Link Here]**

# 🎥 **Snapshot of the Dashboard (Power BI Service)**

![Image](https://github.com/user-attachments/assets/sample-image.png)

# 🎨 **Technical Implementation**

### 💡 **DAX Measures Used**

#### 👨‍💻 **Character Count**
```DAX
Total Characters = COUNT(CharacterData[CharacterName])
```

#### 🔄 **Filter Selection Based on User Input**
```DAX
Selected Character = SELECTEDVALUE(CharacterData[CharacterName], "Select a Character")
```

# 💡 **Insights & Features**

### 💪 **1. Character Attributes Overview**
- Displays essential **character stats** like height, weight, and preferences.
- Provides an **immersive experience** using images and text.

### 🔮 **2. Interactive Filtering**
- Users can filter characters **by attributes** (likes, dislikes, etc.).
- 👉 **Clicking a character** updates the information panel dynamically.

### 🎉 **3. Visual Enhancements**
- **SVG integration** ensures smooth character selection.
- **Custom HTML content** provides high-resolution character visuals.
- **Image URLs** enable seamless rendering of external images.

# 🚀 **Conclusion**
This Power BI project showcases how **advanced visuals and interactivity** can be achieved beyond traditional dashboards. By leveraging **SVG, HTML content, and Power BI’s dynamic features**, this character selection dashboard provides an **engaging and functional** user experience.

## 👤 **Published by**: Sudharsan T

## 📅 **Date**: 11-02-2025

