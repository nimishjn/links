# Links and skills
![Baner](https://user-images.githubusercontent.com/63140632/135496771-2c2c2464-e4a7-4543-8ec4-36687c8471cf.png)

A website built using HTML, CSS and JavaScript to host all the important links and skills of an individual.  
Make changes to info.json and the website will render itself based on it.

## Structure of [assets/info.json](./assets/info.json)
```
(start)
├── name (String)
├── image (String)
├── designation (String)
├── heading (String)
├── skills (Array)
|   ├── <Skill 1>
|   ├── <Skill 2>
|   ├── <Skill 3>
|   └── ...
|
└── sections (Array)
    ├── Section 1 (Object)
    |   ├── heading (String / false)
    |   └── links (Array)
    |       ├── Link 1 (Object)
    |       |   ├── title (String)
    |       |   ├── icon (String)
    |       |   |   Note: Use font awesome <i> tags
    |       |   |   Example: "<i class='fas fa-file-alt'></i>"
    |       |   └── url (String)
    |       |
    |       ├── Link 2 (Object)
    |       |   ├── title (String)
    |       |   ├── icon (String)
    |       |   |   Note: Use font awesome <i> tags
    |       |   |   Example: "<i class='fas fa-file-alt'></i>"
    |       |   └── url (String)
    |       |
    |       └── ...
    |
    ├── Section 2 (Object)
    |   ├── heading (String / false)
    |   └── links (Array)
    |       ├── Link 1 (Object)
    |       |   ├── title (String)
    |       |   ├── icon (String)
    |       |   |   Note: Use font awesome <i> tags
    |       |   |   Example: "<i class='fas fa-file-alt'></i>"
    |       |   └── url (String)
    |       |
    |       ├── Link 2 (Object)
    |       |   ├── title (String)
    |       |   ├── icon (String)
    |       |   |   Note: Use font awesome <i> tags
    |       |   |   Example: "<i class='fas fa-file-alt'></i>"
    |       |   └── url (String)
    |       |
    |       └── ...
    |
    └── ...
(end)
```
