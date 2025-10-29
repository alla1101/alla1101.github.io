---
layout: default
title: Documents
---

# Documents

This section contains shared documents, resources, and materials available for download.

## How to Share Documents

You can share documents in two ways:

### Method 1: Direct File Links

1. Place your PDF, Word, or other document files in a `documents/` folder in your repository
2. Link to them directly from this page

### Method 2: Using GitHub Releases

1. Upload documents as releases in your GitHub repository
2. Link to the release assets here

Much exciting approach would be to create a `documents/` folder and organize files there. Here's how you can add documents:

---

## Available Documents

<ul class="document-list">
  <li class="document-item">
    <i class="fas fa-file-pdf"></i>
    <div class="document-info">
      <div class="document-title">Sample Document</div>
      <div class="document-description">Example document to demonstrate the layout</div>
    </div>
    <a href="#" class="button">Download</a>
  </li>
  
  <li class="document-item">
    <i class="fas fa-file-word"></i>
    <div class="document-info">
      <div class="document-title">Lecture Notes</div>
      <div class="document-description">Course materials and lecture notes</div>
    </div>
    <a href="#" class="button">Download</a>
  </li>
  
  <li class="document-item">
    <i class="fas fa-file-pdf"></i>
    <div class="document-info">
      <div class="document-title">Research Paper</div>
      <div class="document-description">Published or working paper</div>
    </div>
    <a href="#" class="button">Download</a>
  </li>
</ul>

---

## Instructions for Adding Documents

### Step 1: Create a documents folder

Create a `documents/` folder in your repository root.

### Step 2: Upload your files

Upload your document files (PDF, DOCX, etc.) to the `documents/` folder through GitHub's web interface or Git.

### Step 3: Update this page

Edit this `documents.md` file and add entries in the format:

```markdown
<li class="document-item">
  <i class="fas fa-file-pdf"></i> <!-- Change icon: fa-file-pdf, fa-file-word, fa-file-powerpoint, etc. -->
  <div class="document-info">
    <div class="document-title">Your Document Title</div>
    <div class="document-description">Brief description of the document</div>
  </div>
  <a href="/documents/your-file.pdf" class="button">Download</a>
</li>
```

### Supported File Types

Common file types that work well:
- PDF (`.pdf`) - Recommended for academic papers
- Word (`.docx`, `.doc`)
- PowerPoint (`.pptx`, `.ppt`)
- Excel (`.xlsx`, `.xls`)
- Text files (`.txt`, `.md`)

---

*Note: Make sure document files are publicly accessible. Files in private repositories won't be accessible to visitors.*

