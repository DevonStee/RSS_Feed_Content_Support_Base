# 📡 RSS Content Support Base

This repository contains assets and support files related to RSS feeds. It includes icons, metadata files, and other resources to enhance RSS feed presentations.

## 📂 Directory Structure

/RSS_Content_Support_Base │── assets/ # Stores RSS-related icons, images, and metadata │── templates/ # Stores predefined RSS feed templates (if applicable) │── config/ # Stores configuration files for RSS customization │── README.md # Project documentation


## 🔧 Usage

### 1️⃣ **Using an `.ico` file for RSS Feeds**
If an RSS feed does not have an associated icon, you can use one from this repository.

### 2️⃣ Referencing RSS Templates
If you have predefined RSS templates, they can be used as follows:

```xml
<rss version="2.0">
  <channel>
    <title>My RSS Feed</title>
    <link>https://example.com</link>
    <description>Sample RSS feed with custom assets.</description>
    <image>
      <url>https://raw.githubusercontent.com/DevonStee/RSS_Content_Support_Base/main/assets/feed-icon.png</url>
      <title>My RSS Icon</title>
      <link>https://example.com</link>
    </image>
  </channel>
</rss>
```
## 📥 Contributing
Contributions are welcome! If you want to add new icons, templates, or any other RSS-related resources, please follow these steps:

Fork this repository and clone it to your local machine.
Add or update assets in the appropriate folders.
Commit your changes and push them to your forked repo.
Open a pull request with a short description of the changes.
## 🛠 Future Plans
Add more RSS feed templates for common platforms.
Include additional .ico variations for different themes.
Automate icon selection based on domain or feed metadata.
## 📜 License
This project is open-source under the MIT License. You are free to use, modify, and distribute the files as long as you provide attribution.
