 
# Document Tracking System (DTS)

## Description / Overview
The Document Tracking System is a web-based application developed for our midterm examination. It provides functionality to manage and track documents efficiently with a user-friendly interface built using HTML, CSS, and JavaScript.

## Objectives
- Create a functional document management system
- Implement CRUD operations for document handling
- Design an intuitive user interface
- Practice version control using Git and GitHub
- Collaborate effectively as a team using GitHub workflows

## Features / Functionality
- **Document Registration**: Add new documents to the system
- **Document Search**: Find documents quickly using search filters
- **Document Tracking**: Monitor document status and location
- **User Interface**: Clean and responsive design
- **Data Persistence**: Store document information locally
- **Real-time Updates**: Instant feedback on user actions

## Installation Instructions

### Prerequisites
- Web browser (Chrome, Firefox, Safari, or Edge)
- Git installed on your computer
- Text editor (VS Code recommended)

### Setup Steps
1. Clone the repository:
```bash
   git clone https://github.com/bocchiee13/dts_midterm-project.git
```

2. Navigate to the project directory:
```bash
   cd dts_midterm-project/DTS
```

3. Open `index.html` in your web browser:
   - Double-click the file, or
   - Right-click → Open with → Browser

## Usage

### Basic Operations
1. **Adding a Document**:
   - Fill in the document details in the form
   - Click "Add Document" button
   - Document appears in the list below

2. **Searching Documents**:
   - Use the search bar to filter documents
   - Results update automatically

3. **Viewing Document Details**:
   - Click on any document in the list
   - View full details in the detail panel

### Example Code Snippet
```javascript
// Sample function from script.js
function addDocument(title, category, status) {
    const document = {
        id: Date.now(),
        title: title,
        category: category,
        status: status,
        createdAt: new Date()
    };
    documents.push(document);
    renderDocuments();
}
```

## Screenshots

### Main Interface
![DTS Main Screen](screenshots/main-screen.png)
*The main dashboard showing document list and search functionality*

### Add Document Form
![Add Document](screenshots/add-form.png)
*Form for adding new documents to the system*

## Project Structure
```
dts_midterm-project/
├── DTS/
│   ├── index.html      # Main HTML file
│   ├── styles.css      # Styling stylesheet
│   └── script.js       # JavaScript functionality
└── README.md           # Project documentation
```

## Technologies Used
- **HTML5**: Structure and content
- **CSS3**: Styling and layout
- **JavaScript**: Functionality and interactivity
- **Git**: Version control
- **GitHub**: Remote repository hosting

## Contributors
- **Bryan** ([@bocchiee13](https://github.com/bocchiee13)) - Lead Developer
- **Nagi** ([@kidongkun69-rgb](https://github.com/kidongkun69-rgb)) - Collaborating Developer

## Version History
- **v1.0.0** (October 2025) - Initial release with core features

## License
This project is created for educational purposes as part of our midterm examination.

## Acknowledgments
- Thanks to our instructor for guidance
- Course materials and references provided in class

## Repository Link
[GitHub Repository](https://github.com/bocchiee13/dts_midterm-project)

---
*Last Updated: October 23, 2025*