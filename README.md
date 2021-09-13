# JSON Resume Template
[JSON Resume](https://jsonresume.org/) is an open source initiative to create a JSON-based standard for resume. This repository aims to provide you a sample file containing a valid definition based on [v1.0 schema](https://github.com/jsonresume/resume-schema/blob/v1.0.0/schema.json) that can be used on multiple projects and services

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
      "url": "http://johndoe.com",
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
        "name": "Company",
        "position": "Developer",
        "url": "http://somecompany.com",
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
        "url": "http://organization.com/",
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
        "url": "https://institution.ph",
        "area": "Software Development",
        "studyType": "Bachelor",
        "startDate": "2020-01-01",
        "endDate": "2020-01-01",
        "score": "4.0",
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
        "url": "http://publication.com",
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

### Languages

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

## Related Projects
| Name | Description |
|---|---|
| [me](https://github.com/jkga/me) | :rocket: A next-gen JAMSTACK template for **developers** that leverage the use of [JSON Resume Schema](https://jsonresume.org/schema) in creating a web based vitae and portfolio. Stop worying with a complex setup and deployment process.