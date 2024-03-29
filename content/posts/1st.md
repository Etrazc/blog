---
title: "Lembar Tips Markdown"
date: 2024-03-19T22:32:45+07:00
description: "Eirmod sed erat nonumy diam et ut, est sit dolor duo invidunt dolore et magna."
tags: ["Markdown", "Tips", "Cheat Sheet"]
featured_image: "/images/post/markdown.jpg"
# images is optional, but needed for showing Twitter Card
images: ["/images/post/markdown.jpg"]
categories: Guide
comment: true
draft: false
---

Eirmod sed erat nonumy diam et ut, est sit dolor duo invidunt dolore et magna. Elitr voluptua justo erat dolor. Sighed wight thee only to each the ee. Long ah.


## **A. Basic Syntax** (Dasar)
Eirmod sed erat nonumy diam et ut, est sit dolor duo invidunt dolore et magna. Elitr voluptua justo erat dolor. Sighed wight thee only to each the ee. Long ah. Eirmod sed erat nonumy diam et ut, est sit dolor duo invidunt dolore et magna. Eirmod sed erat nonumy diam et ut, est sit dolor duo invidunt dolore et magna.

### 1. Heading (Judul)
Tambahkan tanda pagar `#` di depan kata atau frasa. Jumlah tanda pagar yang Anda gunakan harus sesuai dengan tingkat judul. Misalnya, untuk membuat judul tingkat tiga `<h3>`, gunakan tiga tanda pagar `### Judul Paragraf`.

| Markdown       | HTML               |
| -------------- | ------------------ |
| # Judul 1      | `<h1>Judul 1</h1>` |
| ## Judul 2     | `<h2>Judul 2</h2>` |
| ### Judul 3    | `<h3>Judul 3</h3>` |

Alternatifnya, pada baris di bawah teks, tambahkan sejumlah karakter `==` untuk **judul tingkat 1** atau `--` untuk **judul tingkat 2**.

```md
Judul 1 | <h1>Judul 1</h1>  
======= | 
Judul 2 | <h2>Judul 2</h2>
------- | 
```

### 2. Bold (Tebal)
### 3. Italic (Miring) 
### 4. Blockquote (Kutipan)
### 5. Ordered List (Daftar Berurut)
### 6. Unordered List (Daftar Tak Berurut)
### 7. Horizontal Rule (Garis)
### 8. Link (Tautan)
### 9. Image (Gambar)

## B. Extended Syntax

### 1. Table (Tabel)
### 2. Fenced Code Block (Blok Kode Terpagar)
### 3. Footnote (Catatan Kaki)
### 4. Heading ID (Id Judul)
### 5. Definition List (Daftar Definisi)
### 6. Strikethrough (Tanda Coret)
### 7. Task List (Daftar Tugas)

```
|     Element     | Markdown Syntax                  |
| --------------- | -------------------------------- |
|  ```Heading```  | # H1                             |
|                 | ## H2                            |
|                 | ### H3                           |
|      Bold       | **bold text**                    |
|     Italic      | *italicized text*                |
|   Blockquote    | > blockquote                     |
|  Ordered List   | 1. First item                    |
|                 | 2. Second item                   |
|                 | 3. Third item                    |
| Unordered List  | - First item                     |
|                 | - Second item                    |
|                 | - Third item                     |
|      Code       | `code`                           |
| Horizontal Rule | ---                              |
|      Link       | [title](https://www.example.com) |
|      Image      | ![alt text](image.jpg)           |
```

```
|     Element     | Markdown Syntax                  |
| --------------- | -------------------------------- |
| Table |                                          |
| |                                                |
| |                                                |
| |                                                |
| Fenced Code Block ```                            |
| {                                                |
| "firstName": "John",                             |
| "lastName": "Smith",                             |
| "age": 25                                        |
| }                                                |
| ```                                              |
| Footnote Here's a sentence with a footnote. [^1] |
| Syntax | Description |                           |
| ------ | ----------- |                           |
| Header | Title |                                 |
| Paragraph | Text |                               |
| [^1]: This is the footnote.                      |
| Heading ID ### My Great Heading {#custom-id}     |
| Definition List term                             |
| : definition                                     |
| Strikethrough ∼∼The world is flat.∼∼             |
| Task List - [x] Write the press release          |
| - [ ] Update the website                         |
| - [ ] Contact the media                          |
```
