# QSIS-ACADEMIC-FILES-MANAFGER

Academic file storage for the **QSIS-ARMS** platform — International Islamic University Chittagong (IIUC).

## Browse Files
Files are viewable at **[qsis-arms.eu.cc](https://qsis-arms.eu.cc)**

## New Structure (All Departments)

```
upload_academic_files/
├── qsis/           ← Qur'anic Sciences & Islamic Studies
│   ├── 1st-semister/
│   │   ├── sheet/
│   │   ├── NOTES/
│   │   ├── Previous Questions/
│   │   ├── Syllabus/
│   │   └── Other/
│   ├── 2nd-semister/
│   └── ...
├── cse/            ← Computer Science & Engineering
├── cce/            ← Computer & Communication Engineering
├── eee/            ← Electrical & Electronic Engineering
├── ete/            ← Electronic & Telecommunication Engineering
├── civil/          ← Civil Engineering
├── pharmacy/       ← Pharmacy
├── ba/             ← Business Administration
├── finance/        ← Department of Finance
├── ell/            ← English Language & Literature
├── all/            ← Arabic Language & Literature
├── lis/            ← Library & Information Science
├── law/            ← Department of Law
├── eb/             ← Economics & Banking
├── cge/            ← Center for General Education
├── dawah/          ← Da'wah & Islamic Studies
├── hadith/         ← Science of Hadith & Islamic Studies
└── related-kitabs/ ← Cross-semester & Shariah resources
```

## Department Folder IDs

| Department | Folder ID | Faculty |
|---|---|---|
| Qur'anic Sciences & Islamic Studies | `qsis` | Shariah & Islamic Studies |
| Da'wah & Islamic Studies | `dawah` | Shariah & Islamic Studies |
| Science of Hadith & Islamic Studies | `hadith` | Shariah & Islamic Studies |
| Computer Science & Engineering | `cse` | Science & Engineering |
| Computer & Communication Engineering | `cce` | Science & Engineering |
| Electrical & Electronic Engineering | `eee` | Science & Engineering |
| Electronic & Telecommunication Engineering | `ete` | Science & Engineering |
| Civil Engineering | `civil` | Science & Engineering |
| Pharmacy | `pharmacy` | Science & Engineering |
| Business Administration | `ba` | Business Studies |
| Department of Finance | `finance` | Business Studies |
| English Language & Literature | `ell` | Arts & Humanities |
| Arabic Language & Literature | `all` | Arts & Humanities |
| Library & Information Science | `lis` | Arts & Humanities |
| Department of Law | `law` | Law |
| Economics & Banking | `eb` | Social Science |
| Center for General Education | `cge` | General Education |

## Upload Path Format

**New uploads:**
```
upload_academic_files/{department}/{semester}/{category}/{CourseCode-CourseTitle}/{filename}
```

**Example:**
```
upload_academic_files/cse/3rd-semister/sheet/FSC-1208-IslamicStudies/Midterm-Sheet.pdf
```

## Categories

| Category | Folder Name |
|---|---|
| Sheets | `sheet` |
| Notes | `NOTES` |
| Previous Questions | `Previous Questions` |
| Syllabus | `Syllabus` |
| Other | `Other` |

## Semesters

`1st-semister`, `2nd-semister`, `3rd-semister`, `4th-semister`, `5th-semister`, `6th-semister`, `7th-semister`, `8th-semister`

## Contributing

1. **Fork** this repository
2. Navigate to `upload_academic_files/{your-department}/{semester}/{category}/{CourseCode-CourseTitle}/`
3. Upload your files
4. Create a **Pull Request**

> **Note:** Only IIUC departmental emails (`@ugrad.iiuc.ac.bd` or `@iiuc.ac.bd`) are accepted.

## Legacy Files

Files in semester folders directly under `upload_academic_files/` (without a department folder) are legacy QSIS files. They remain accessible for backward compatibility.

---

*Presented by **Programming Light** & Developed by **Sayed Atiqur Rahman***
