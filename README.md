# JSON Resume Template
[JSON Resume](https://jsonresume.org/) is an open source initiative to create a JSON-based standard for resume. This repository aims to provide you a sample file containing a valid definition based on [v1.0 schema](https://github.com/jsonresume/resume-schema/blob/v1.0.0/schema.json) that can be used on multiple projects and services like [Me](https://github.com/jkga/me) !

[![JSON RESUME](https://img.shields.io/badge/format-JSON%20RESUME%20-yellow?style=for-the-badge&logo=json)](http://jsonresume.org) 

## [Me](https://github.com/jkga/me) 
A next-gen JAMSTACK template for developers that leverage the use of JSON Resume Schema to create a web based vitae / portfolio. Stop worrying with a complex setup and deployment process.

![me logo](https://user-images.githubusercontent.com/10413754/79948155-e5e9da80-84a5-11ea-83eb-34e2f5aa89f6.png)

> Docs: https://me-docs.now.sh/   

> Repository: https://github.com/jkga/me

## :loudspeaker: NOTICE TO THE PUBLIC
> :lock: All the information you included in your `JSON` files are public and **MUST NOT CONTAIN** any information that you do not want to share to everyone. Thus, you are fully accountable on what you share on your public repositories and we should not be held responsible or liable for your negligence.

## Getting Started
1. Click the `"Use this template"` button on this page to create a new repository based on this template
  ![use template image](https://user-images.githubusercontent.com/10413754/80201503-d4940000-8656-11ea-9ce9-bae19f70cc00.png)
2. Name your new repository `about.me`
> **Note:** The service only looks for `about.me` repository on github and changing it to something else would make your resume undiscoverable
![create repository from template](https://user-images.githubusercontent.com/10413754/80216230-53496700-8670-11ea-87ca-64230825a666.png)
3. Go to :waning_gibbous_moon:
 https://me-web.now.sh/write-your-github-username to view your ready made online portfolio 
4. Update `index.json` content with your information and please validate it using [this json schema validator](https://www.jsonschemavalidator.net/) before you commit

![validator](https://user-images.githubusercontent.com/10413754/80218198-7295c380-8673-11ea-8e15-ad52d3840da1.png)


## JSON Resume Definition
Please see  `index.json` for comple example
```javascript
  {
    "basics": {},
    "profiles": [],
    "work": [],
    "volunteer": [],
    "education": [],
    "awards": [],
    "publications": [],
    "skills": [],
    "languages": [],
    "interests": [],
    "references": [],
    "projects": []
  }

```

### Basic Information

```json
  {
    "basics": {
      "name": "John Doe",
      "label": "developer",
      "image": "https://user-images.githubusercontent.com/...",
      "email": "johndoe@gmail.com",
      "phone": "(111) 333-4567",
      "website": "http://johndoe.com",
      "summary": "Lorem ipsum dolor sit amet, consecte...",
      "location": {
        "address": "22111 Makiling",
        "postalCode": "4027",
        "city": "Calamba",
        "countryCode": "PH",
        "region": "Philippines"
      }
    }
  }
```

### Profiles

```json
  {
    "profiles": [
      {
        "network": "Twitter",
        "username": "johndoe",
        "url": "http://twitter.com/johndoe"
      }
    ]
  }

```

### Work Experience

```json
  {
    "work": [
      {
        "company": "Company",
        "position": "Developer",
        "website": "http://somecompany.com",
        "startDate": "2020-01-01",
        "endDate": "2020-01-01",
        "summary": "Lorem ipsum dolor sit amet, consectet...",
        "highlights": [
          "Lead Developer of Innovation hub"
        ]
      }
    ]
  }
```

### Volunteer Experience

```json
  {
    "volunteer": [
       {
        "organization": "Organization",
        "position": "Volunteer",
        "website": "http://organization.com/",
        "startDate": "2020-01-01",
        "endDate": "2020-01-01",
        "summary": "Lorem ipsum dolor sit amet, consectetu...",
        "highlights": [
          "Awarded 'Volunteer of the Month'"
        ]
      }
    ]
  }
```

### Education

```json
  {
    "education": [
      {
        "institution": "University",
        "area": "Software Development",
        "studyType": "Bachelor",
        "startDate": "2020-01-01",
        "endDate": "2020-01-01",
        "gpa": "4.0",
        "courses": [
          "WEB101 - Web Development",
          "SYS123 - Object Oriented Programming"
        ]
      }
    ]
  }
```

### Awards

```json
  {
    "awards": [
      {
        "title": "Award",
        "date": "2020-11-01",
        "awarder": "Company",
        "summary": "Programmer of the Year 2020"
      }
    ]
  }
```

### Publications

```json
  {
    "publications": [
      {
        "name": "Publication",
        "publisher": "Company",
        "releaseDate": "2020-10-01",
        "website": "http://publication.com",
        "summary": "Lorem ipsum dolor sit amet, consectetur..."
      }
    ]
  }
```


### Skills

```json
  {
    "skills": [
      {
        "name": "Web Development",
        "level": "Master",
        "keywords": [
          "HTML",
          "CSS",
          "Javascript"
        ]
      }
    ]
  }
```

### Language

```json
  {
    "languages": [
      {
        "language": "English",
        "fluency": "Native speaker"
      }
    ],
  }
```


### Interests

```json
  {
    "interests": [
      {
        "name": "Electronics",
        "keywords": [
          "PCB",
          "IOT"
        ],
        "description": "Lorem ipsum dolor sit amet, consectetur..."
      }
    ]
  }
```

### References

```json
  {
    "references": [
      {
        "name": "Jane Doe",
        "reference": "Lorem ipsum dolor sit amet, consectetur..."
      }
    ]
  }
```

### Projects

```json
  {
    "projects": [
      {
        "name": "Project Name",
        "description": "Lorem ipsum dolor sit amet",
        "highlights": ["COVID19 Patient Tracker"],
        "keywords": ["PHP", "NodeJS", "Javascript"],
        "startDate": "2020-01-01",
        "endDate": "2020-01-01",
        "url": "https://project.example.com",
        "roles": ["Lead Developer", "Designer"],
        "image": "https://user-images.githubusercontent.com...",
        "entity": "Facebook, Google, Microsoft, Amazon",
        "type": "web application"
      }
    ]
  }
```