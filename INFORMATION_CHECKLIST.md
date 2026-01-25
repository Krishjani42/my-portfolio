# 📋 Portfolio में Information भरने की Complete Checklist

## ✅ File: `index.html` में यहाँ-यहाँ भरें:

---

## 1️⃣ **Page Title** (Line 6)
```html
<title>Your Name - Portfolio</title>
```
**भरें:** अपना नाम
**Example:** `<title>Krish - Portfolio</title>`

---

## 2️⃣ **Navigation Brand** (Line 17)
```html
<div class="nav-brand">Your Name</div>
```
**भरें:** अपना नाम
**Example:** `<div class="nav-brand">Krish</div>`

---

## 3️⃣ **Hero Section - Name** (Line 44)
```html
Hi, I'm <span class="highlight">Your Name</span>
```
**भरें:** अपना नाम
**Example:** `Hi, I'm <span class="highlight">Krish</span>`

---

## 4️⃣ **Hero Section - Profession** (Line 46)
```html
<p class="hero-subtitle">Your Profession/Role</p>
```
**भरें:** अपनी profession/role
**Examples:**
- `Web Developer`
- `Software Engineer`
- `Full Stack Developer`
- `UI/UX Designer`

---

## 5️⃣ **Hero Section - Description** (Line 47-49)
```html
<p class="hero-description">
    A brief description about yourself...
</p>
```
**भरें:** अपने बारे में 2-3 lines
**Example:**
```html
<p class="hero-description">
    Passionate Full Stack Developer with expertise in building modern web applications. 
    Love creating user-friendly interfaces and solving complex problems.
</p>
```

---

## 6️⃣ **Social Media Links** (Lines 55-58)
```html
<a href="#" target="_blank" aria-label="LinkedIn">
<a href="#" target="_blank" aria-label="GitHub">
<a href="#" target="_blank" aria-label="Twitter">
<a href="#" target="_blank" aria-label="Email">
```
**भरें:** अपने social media URLs
**Examples:**
- LinkedIn: `href="https://www.linkedin.com/in/yourprofile"`
- GitHub: `href="https://github.com/yourusername"`
- Twitter: `href="https://twitter.com/yourusername"`
- Email: `href="mailto:your.email@gmail.com"`

---

## 7️⃣ **About Section - Bio** (Lines 75-83)
```html
<p>Write a compelling paragraph about yourself here...</p>
<p>Add another paragraph if needed...</p>
```
**भरें:** अपने बारे में detailed description (2 paragraphs)
**Example:**
```html
<p>
    I'm a passionate developer with 3+ years of experience in web development. 
    I specialize in React, Node.js, and modern JavaScript frameworks. 
    I love building scalable applications and learning new technologies.
</p>
<p>
    Currently working on innovative projects and always looking for new challenges. 
    When I'm not coding, I enjoy contributing to open-source projects and sharing knowledge with the community.
</p>
```

---

## 8️⃣ **About Section - Statistics** (Lines 85-96)
```html
<h3>50+</h3>
<p>Projects Completed</p>

<h3>3+</h3>
<p>Years Experience</p>

<h3>20+</h3>
<p>Happy Clients</p>
```
**भरें:** अपने actual numbers
**Examples:**
- Projects: `25+`, `50+`, `100+`
- Experience: `2+`, `3+`, `5+`
- Clients: `10+`, `20+`, `50+`

---

## 9️⃣ **Skills Section** (Lines 111-151)
```html
<span data-percent="90%">JavaScript</span>
<div class="skill-progress" style="width: 90%"></div>
```
**भरें:** अपनी skills और percentages
**Examples:**
- `JavaScript` - 85%
- `Python` - 90%
- `React` - 80%
- `Node.js` - 75%

**Note:** 
- Skill name change करें
- `data-percent` में percentage
- `style="width: XX%"` में same percentage

---

## 🔟 **Projects Section** (Lines 163-222)

### Project 1 (Lines 163-182):
```html
<h3>Project Name 1</h3>
<p>Brief description of your project...</p>
<span>React</span>
<span>Node.js</span>
<a href="#" target="_blank">Live Demo</a>
<a href="#" target="_blank">Code</a>
```
**भरें:**
- Project name
- Description
- Technologies used
- Live demo URL (अगर है)
- GitHub/Code URL

### Project 2 (Lines 183-202):
**Same format - अपना project details भरें**

### Project 3 (Lines 203-222):
**Same format - अपना project details भरें**

**Note:** अगर 3 से कम projects हैं, तो extra project cards delete कर दें

---

## 1️⃣1️⃣ **Experience Section** (Lines 232-264)

### Experience 1 (Lines 232-244):
```html
<div class="timeline-date">2023 - Present</div>
<h3>Job Title</h3>
<h4>Company Name</h4>
<p>Description of your role...</p>
<li>Key achievement</li>
```
**भरें:**
- Date range (जैसे: `2023 - Present` या `2022 - 2023`)
- Job title
- Company name
- Role description
- Key achievements (bullet points)

### Experience 2 (Lines 245-256):
**Same format - previous job details**

### Experience 3 (Lines 257-264):
**Same format - education/internship**

**Note:** अगर कम experiences हैं, तो extra items delete कर दें

---

## 1️⃣2️⃣ **Contact Section** (Lines 277-297)

### Email (Line 281):
```html
<p>your.email@example.com</p>
```
**भरें:** अपना email

### Phone (Line 288):
```html
<p>+91 1234567890</p>
```
**भरें:** अपना phone number

### Location (Line 295):
```html
<p>Your City, Country</p>
```
**भरें:** अपना location
**Example:** `Mumbai, India` या `Delhi, India`

---

## 1️⃣3️⃣ **Footer** (Line 322)
```html
<p>&copy; 2024 Your Name. All rights reserved.</p>
```
**भरें:** अपना नाम
**Example:** `<p>&copy; 2024 Krish. All rights reserved.</p>`

---

## 1️⃣4️⃣ **Footer Social Links** (Lines 324-326)
```html
<a href="#" target="_blank"><i class="fab fa-linkedin"></i></a>
<a href="#" target="_blank"><i class="fab fa-github"></i></a>
<a href="#" target="_blank"><i class="fab fa-twitter"></i></a>
```
**भरें:** Same URLs जो hero section में दिए हैं

---

## 🖼️ **Optional: Profile Photo** (Line 62-64)

अगर photo add करना है:
```html
<div class="hero-image">
    <img src="your-photo.jpg" alt="Your Name" style="width: 320px; height: 320px; border-radius: 50%; object-fit: cover;">
</div>
```

**Steps:**
1. Photo को portfolio folder में save करें
2. `image-placeholder` div को replace करें
3. Photo file name update करें

---

## 📝 **Quick Summary:**

| Section | Line Numbers | What to Fill |
|---------|-------------|--------------|
| Title | 6 | Your name |
| Nav Brand | 17 | Your name |
| Hero Name | 44 | Your name |
| Hero Profession | 46 | Your role |
| Hero Description | 47-49 | About you |
| Social Links | 55-58 | LinkedIn, GitHub, etc. |
| About Bio | 75-83 | Detailed bio |
| Statistics | 85-96 | Numbers (projects, experience) |
| Skills | 111-151 | Your skills & percentages |
| Projects | 163-222 | 3 projects details |
| Experience | 232-264 | Work experience |
| Contact Email | 281 | Your email |
| Contact Phone | 288 | Your phone |
| Contact Location | 295 | Your location |
| Footer | 322 | Your name |
| Footer Links | 324-326 | Social media URLs |

---

## ✅ **Checklist:**

- [ ] Page title updated
- [ ] Navigation name updated
- [ ] Hero section name & profession
- [ ] Hero description written
- [ ] Social media links added
- [ ] About section bio written
- [ ] Statistics updated
- [ ] Skills updated with percentages
- [ ] Projects details filled (at least 1-2)
- [ ] Experience/Work history added
- [ ] Contact information updated
- [ ] Footer updated
- [ ] Profile photo added (optional)

---

**Tip:** एक-एक करके सभी sections भरें और browser में check करते रहें! 🚀

