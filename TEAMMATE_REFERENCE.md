# TEAMMATE QUICK REFERENCE SHEET
## How to Complete Your Section

---

## 📝 EDITING YOUR SECTION

### Method 1: Edit on GitHub (Recommended)
1. Go to repository: `https://github.com/rs-its/IT304-Final-Project`
2. Click your assigned file:
   - Team Member 2 → `application1.html`
   - Team Member 3 → `application2.html`
   - Team Member 4 → `ethics.html`
   - Team Member 5 → `recommendations.html`
3. Click **pencil icon** (Edit this file)
4. Follow the **orange instruction boxes**
5. Replace all `[bracketed placeholders]` with your content
6. Scroll to bottom, click **"Commit changes"**
7. Changes appear on website in 1-2 minutes

### Method 2: Download & Edit Locally
1. Download your HTML file from repository
2. Open in text editor (Notepad, VS Code, etc.)
3. Follow instructions in orange boxes
4. Save file
5. Upload back to GitHub (Add file → Upload files)

---

## 🖼️ ADDING IMAGES - 3 STEPS

### Step 1: Find or Create Your Image
- Screenshots of news articles
- Infographics you create
- Diagrams explaining concepts
- Charts/graphs

### Step 2: Get image url

**Option A - Right click on an image and click: Copy image link (Easiest):**
1. Find image you want
2. Right Click on it
3. Press: Copy image link
4. Paste Img link to img source in html

### Step 3: Add Image to HTML

Find this placeholder in your file:
```html
<div class="image-placeholder">
    <p>📸 INSERT IMAGE HERE</p>
</div>
```

**Replace entire block with:**
```html
<img src="PASTE_YOUR_IMAGE_URL_HERE" alt="Brief description of image" class="content-image">
```

**Example:**
```html
<img src="https://i.imgur.com/abc123.png" alt="Political deepfake example" class="content-image">
```

---

## 📚 ADDING REFERENCES

### Find the References Section at Bottom of Your File

Look for:
```html
<div class="references">
    <h3>References</h3>
    <ol>
        <li>[Replace with your first source]</li>
```

### Format Each Reference:
```
Author Last Name, First Initial. (Year). Title of article. Publication. URL
```

### Examples:

**News article:**
```html
<li>Johnson, M. (2024). Deepfakes threaten election integrity. <em>The New York Times</em>. <a href="https://www.nytimes.com/article" target="_blank">https://www.nytimes.com/article</a></li>
```

**Academic paper:**
```html
<li>Smith, J., & Brown, K. (2023). Ethical implications of synthetic media. <em>Journal of Technology Ethics</em>, 15(2), 45-67. <a href="https://doi.org/10.xxxx" target="_blank">https://doi.org/10.xxxx</a></li>
```

**Website/blog:**
```html
<li>Wilson, R. (2024). How to detect deepfakes. <em>MIT Technology Review</em>. <a href="https://www.technologyreview.com" target="_blank">https://www.technologyreview.com</a></li>
```

---

## ✅ QUALITY CHECKLIST FOR YOUR SECTION

Before you commit changes, verify:

### Content:
- [ ] All orange instruction boxes removed
- [ ] All `[bracketed placeholders]` replaced with real content
- [ ] All rubric requirements addressed
- [ ] No spelling/grammar errors

### Images:
- [ ] 2-3 images added (per your instructions)
- [ ] All image URLs work (test by pasting in browser)
- [ ] Images are relevant to your content
- [ ] Each image has descriptive alt text

### References:
- [ ] Minimum number of sources met
- [ ] Sources are credible (news outlets, academic journals, research orgs)
- [ ] Proper citation format used
- [ ] All URLs work when clicked

### HTML Formatting:
- [ ] No broken tags (every `<p>` has a `</p>`)
- [ ] Headings use correct tags (`<h3>`, `<h4>`)
- [ ] No leftover template comments

---

## 🎯 SECTION-SPECIFIC TIPS

### Team Member 2 (Political Deepfakes):
- Choose 2 specific, different cases (different countries/years)
- Include: what happened, who made it, impact, response
- Good sources: NYT, Washington Post, BBC, Reuters, academic papers
- Focus on democratic implications

### Team Member 3 (Media & Fraud):
- Cover TWO areas: entertainment AND fraud
- Entertainment: movies (The Irishman), celebrity impersonation
- Fraud: CEO scams, romance scams, financial fraud
- Good sources: Tech news, FBI reports, case studies

### Team Member 4 (Ethical Analysis):
- Recommended: Consequentialism + Rights-Based Ethics
- Don't just define frameworks but also apply them to examples
- Show how different lenses reach different conclusions
- Good sources: Philosophy encyclopedias, ethics journals

### Team Member 5 (Recommendations):
- Be SPECIFIC: "pass laws requiring disclosure" not "make better laws"
- Cover: policy, technology, education, platform responsibility
- Identify stakeholders clearly
- Good sources: Policy proposals, research papers, white papers

---

## 🔧 COMMON MISTAKES TO AVOID

❌ Leaving instruction boxes visible in final version  
✅ Delete all orange boxes when done

❌ Using image page links instead of direct image URLs  
✅ Right-click image → "Copy image address"

❌ Forgetting to close HTML tags  
✅ Every `<p>` needs `</p>`, every `<h3>` needs `</h3>`

❌ References without clickable links  
✅ Use `<a href="URL">URL</a>` format

---

## 📞 GETTING HELP

### If you're stuck:
1. Read the orange instruction boxes in your file carefully
2. Look at the completed Introduction section (introduction.html) as example
3. Check the README.md for detailed guidance
4. Contact group chat with any questions!

### Testing your work:
1. Commit your changes
2. Wait 2 minutes
3. Visit: `https://rs-its.github.io/IT304-Final-Project/`
4. Navigate to your section
5. Verify everything looks good

---