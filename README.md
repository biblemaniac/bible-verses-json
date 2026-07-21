# Updated README.md for Username: biblemaniac

````markdown
# Bible Verses JSON Dataset

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

Free open-source Bible verse datasets in JSON format for developers, Christian websites, Bible applications, and researchers.

## Repository

https://github.com/biblemaniac/bible-verses-json

---

## Features

✅ Bible books metadata

✅ Bible verses by topic

✅ Healing scriptures dataset

✅ Faith scriptures dataset

✅ Strength scriptures dataset

✅ Love scriptures dataset

✅ Anxiety scriptures dataset

✅ Search indexes

✅ API examples

---

## Installation

```bash
git clone https://github.com/biblemaniac/bible-verses-json.git
```

---

## Example Usage

### Load Healing Scriptures

```javascript
const healing =
require('./topics/healing.json');

console.log(healing[0]);
```

Output:

```json
{
  "reference": "Jeremiah 30:17",
  "book": "Jeremiah",
  "topic": "Healing",
  "text": "For I will restore health unto thee..."
}
```

---

## Example Search

```javascript
const verses =
require('./all-verses.json');

function search(reference){

return verses.find(
v => v.reference === reference
);

}

console.log(search("John 3:16"));
```

---

# Related Christian Resources

Project Website:

https://www.alivechristians.com/

Bible Verse of the Day:

https://www.alivechristians.com/bible-verse-of-the-day

Healing Scriptures:

https://www.alivechristians.com/bible-verses-about-healing-sickness

Spiritual Gifts Test:

https://www.alivechristians.com/spiritual-gifts-test

Biblical Definitions:

https://www.alivechristians.com/acblog/category/biblical-definitions

Daily Prophetic Word Repository:

https://www.alivechristians.com/acblog/category/prophetic-words-for-today-and-week

---

# Planned Datasets

- Complete KJV Bible JSON
- Strong's Hebrew Dictionary JSON
- Strong's Greek Dictionary JSON
- Biblical Names Dataset
- Psalms Dataset
- Hymn Lyrics Dataset
- Bible Character Dataset
- Spiritual Gifts Dataset
- Five-Fold Ministry Dataset

---

# API Roadmap

### Random Verse

```http
GET /api/random
```

### Verse By Reference

```http
GET /api/reference/john-3-16
```

### Topic Search

```http
GET /api/topic/healing
```

### Daily Verse

```http
GET /api/verse-of-the-day
```

---

# SEO Keywords

Bible JSON, Bible API, KJV JSON, Scripture API,
Bible Dataset, Healing Scriptures JSON,
Christian Developer Resources,
Bible Verses By Topic.

---

# Contributing

Pull requests are welcome.

Please open an issue first to discuss major changes.

---

# License

MIT License
````

---

# Suggested Repository Description

```text
Free open-source Bible verses JSON datasets, Bible APIs, healing scriptures and Christian developer resources.
```

---

# Suggested Repository Topics

```text
bible
bible-api
json
kjv
scripture
christian
healing-scriptures
spiritual-gifts
api
open-source
dataset
```
