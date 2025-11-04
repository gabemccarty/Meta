[README.md](https://github.com/user-attachments/files/23341656/README.md)
# Meta Organizational Chart - README

## 📋 Overview

This repository contains a comprehensive organizational analysis of **Meta** (formerly Facebook) based on 2,654 employees from the Gem talent database. The analysis provides hierarchical organizational charts, employee directories, and detailed insights into Meta's departmental structure and talent distribution.

**Generated on**: November 4, 2025  
**Data Source**: Gem candidate/employee database  
**Total Employees Analyzed**: 2,654  
**Departments Identified**: 14

---

## 📁 Files Included

### 1. **Meta_Org_Chart.html** (Interactive Org Chart)
- **Type**: Interactive HTML visualization
- **Size**: ~380 KB
- **Purpose**: Browser-based organizational chart with full interactivity
- **Features**:
  - ✅ Expandable/collapsible department sections
  - ✅ Real-time employee search (by name, title, location)
  - ✅ Hierarchical tier visualization (10 levels)
  - ✅ Complete employee details (name, title, location, email)
  - ✅ Expand All / Collapse All controls
  - ✅ Department and tier statistics
  - ✅ Responsive design for mobile and desktop

**How to Use**:
1. Open `Meta_Org_Chart.html` in any modern web browser
2. Click department headers to expand/collapse sections
3. Use search box to filter employees
4. Click tier headers to view employees at each level
5. Use Expand All/Collapse All buttons for quick navigation

---

### 2. **Meta_Employees_Directory.csv** (Employee Database)
- **Type**: CSV spreadsheet
- **Size**: ~319 KB
- **Records**: 2,654 employees
- **Columns**:
  - First Name
  - Last Name
  - Job Title
  - Department
  - Hierarchy Tier (0-9)
  - Hierarchy Level (name)
  - Location
  - Email

**How to Use**:
- Import into Excel, Google Sheets, or any spreadsheet application
- Filter by department, tier, or location
- Create pivot tables for custom analysis
- Export subsets for specific departments or roles
- Integrate with ATS, HRIS, or talent management systems

---

### 3. **Meta_Organization_Summary.csv** (Department Statistics)
- **Type**: CSV spreadsheet
- **Size**: ~2 KB
- **Purpose**: Aggregated statistics by department and hierarchy level
- **Columns**:
  - Department
  - Hierarchy Level
  - Count (number of employees)

**How to Use**:
- Quick reference for department sizes
- Create summary reports and dashboards
- Analyze organizational composition
- Compare department structures

---

### 4. **Meta_Org_Analysis.md** (Detailed Report)
- **Type**: Markdown document
- **Purpose**: Comprehensive written analysis with insights and recommendations
- **Sections**:
  - Executive Summary
  - Key Statistics
  - Organizational Hierarchy (tier-by-tier breakdown)
  - Department Analysis (14 departments)
  - Leadership Structure
  - Talent Distribution Insights
  - Geographic Distribution
  - Organizational Recommendations
  - Methodology and Data Quality Notes

**How to Use**:
- Read as a standalone analysis report
- Open in any markdown viewer or text editor
- Convert to PDF for presentations
- Share with stakeholders for strategic planning

---

### 5. **org_data.json** (Raw Data Export)
- **Type**: JSON data file
- **Size**: ~367 KB
- **Purpose**: Complete hierarchical data structure for system integration
- **Structure**:
```json
{
  "company": "Meta",
  "total_employees": 2654,
  "total_departments": 14,
  "hierarchy": {
    "Department Name": {
      "tier_number": {
        "level": "Hierarchy Level Name",
        "count": employee_count,
        "employees": [
          {
            "name": "Full Name",
            "title": "Job Title",
            "location": "Location",
            "email": "Email Address"
          }
        ]
      }
    }
  }
}
```

**How to Use**:
- Import into custom applications
- Integrate with APIs and data pipelines
- Use for programmatic analysis with Python, JavaScript, etc.
- Build custom visualizations or dashboards

---

## 🏢 Organizational Structure Overview

### Hierarchical Tiers (0-9)

| Tier | Level Name | Count | % of Workforce |
|------|------------|-------|----------------|
| 0 | Executive | 0 | 0.0% |
| 1 | C-Suite | 22 | 0.8% |
| 2 | Senior Director | 0 | 0.0% |
| 3 | Director | 2 | 0.1% |
| 4 | Senior Manager | 10 | 0.4% |
| 5 | Manager | 337 | 12.7% |
| 6 | Tech Lead / Principal | 17 | 0.6% |
| 7 | Staff IC | 42 | 1.6% |
| 8 | Senior IC | 312 | 11.8% |
| 9 | Individual Contributor | 1,912 | 72.1% |

### Department Distribution

| Department | Employee Count | % of Workforce |
|------------|---------------|----------------|
| Reality Labs | 1,800 | 67.8% |
| Software Engineering | 1,641 | 61.8% |
| Other | 352 | 13.3% |
| AI & Machine Learning | 261 | 9.8% |
| Product Design | 124 | 4.7% |
| Technical Program Management | 42 | 1.6% |
| Recruiting | 22 | 0.8% |
| Product Management | 17 | 0.6% |
| Android/OS | 7 | 0.3% |
| Data Engineering | 7 | 0.3% |
| Design | 6 | 0.2% |
| Infrastructure & Platform | 5 | 0.2% |
| Ads/Monetization | 5 | 0.2% |
| Systems Engineering | 4 | 0.2% |

---

## 🎯 Key Insights

### 1. **Reality Labs Dominance**
67.8% of employees (1,800 people) work in Reality Labs, Meta's immersive technology division focused on AR/VR, Meta Quest, and Ray-Ban smart glasses. This reflects Meta's strategic pivot toward spatial computing and the metaverse.

### 2. **Engineering-Heavy Organization**
72.1% of employees are individual contributors, indicating a highly technical, engineering-focused workforce. The manager-to-IC ratio of approximately 1:6 is standard for tech companies.

### 3. **AI Investment**
261 employees (9.8%) dedicated to AI & Machine Learning, including Llama model development, applied ML, and AI infrastructure—demonstrating significant investment in generative AI capabilities.

### 4. **Lean Leadership**
Only 24 employees (0.9%) at C-Suite and Director levels, indicating a flat organizational structure with minimal bureaucratic layers.

### 5. **Strong Manager Pipeline**
337 managers (12.7%) provide structured team organization and support scaling of engineering teams.

---

## 💡 Use Cases

### For Recruiters & Talent Teams
- Identify organizational gaps and hiring needs
- Understand Meta's departmental structure for competitor analysis
- Map target candidates to specific teams and managers
- Benchmark team sizes against industry standards

### For Business Intelligence
- Analyze organizational composition and workforce distribution
- Create executive dashboards and reports
- Track departmental growth trends
- Inform strategic workforce planning

### For Sales & Partnerships
- Understand Meta's organizational priorities (Reality Labs, AI)
- Identify decision-makers and key contacts
- Map relationship networks across departments
- Inform account planning and engagement strategies

### For Internal Teams
- Navigate organizational structure
- Identify cross-functional collaboration opportunities
- Understand reporting relationships
- Plan resource allocation and team composition

---

## 🔧 Technical Requirements

### For HTML Org Chart
- **Browser**: Any modern web browser (Chrome, Firefox, Safari, Edge)
- **JavaScript**: Enabled
- **Internet**: Not required (standalone HTML file)

### For CSV Files
- **Spreadsheet Software**: Excel, Google Sheets, LibreOffice Calc
- **Data Tools**: Tableau, Power BI, Python pandas, R

### For JSON Data
- **Programming Languages**: Python, JavaScript, Java, etc.
- **JSON Parsers**: Built-in or library-based (e.g., `json` in Python)

---

## 📊 Methodology

### Data Collection
Employee data sourced from Gem talent database containing 3,260 total records. Filtered to include only Meta employees (2,654 records).

### Tier Classification
Employees classified into 10 hierarchical tiers (0-9) based on job title keyword analysis:
- **Executive keywords**: CEO, Chief Executive, President
- **C-Suite keywords**: CTO, CFO, COO, CMO, Chief Officer
- **Director keywords**: Director, Head of
- **Manager keywords**: Manager, Engineering Manager, Tech Lead Manager
- **IC keywords**: Engineer, Scientist, Designer, Analyst

### Department Categorization
14 primary departments identified through job title keyword clustering:
- AI & Machine Learning: ML, AI, Llama, Applied Scientist
- Reality Labs: RealityLab, XR, AR, VR, Quest, Ray-Ban
- Product Design: Product Design, UX, UI
- Software Engineering: Software Engineer
- And 10 additional specialized departments

### Data Quality
- **Coverage**: Represents employees visible in recruitment/talent tracking systems
- **Accuracy**: Title-based classification validated against known Meta structure
- **Completeness**: Location and email fields may be incomplete for some employees

---

## ⚠️ Limitations & Disclaimers

1. **Data Snapshot**: Analysis represents a point-in-time snapshot (November 2025)
2. **Partial Coverage**: Dataset may not include all Meta employees (public data only)
3. **Title-Based Classification**: Hierarchical tiers inferred from job titles, not confirmed org structure
4. **Department Assignment**: Single department per employee; cross-functional roles may be underrepresented
5. **Privacy**: Email addresses and contact information included only when available in source data

---

## 🚀 Getting Started

### Quick Start (5 minutes)
1. Open `Meta_Org_Chart.html` in your browser
2. Click "Expand All" to view the complete organization
3. Use search to find specific employees or roles
4. Export sections as needed

### Advanced Analysis (30 minutes)
1. Import `Meta_Employees_Directory.csv` into Excel or BI tool
2. Create pivot tables by Department and Tier
3. Filter for specific locations or role types
4. Cross-reference with `Meta_Organization_Summary.csv` for validation

### Custom Development
1. Load `org_data.json` into your application
2. Parse JSON structure to extract hierarchy
3. Build custom visualizations or integrations
4. Implement additional filtering or search logic

---

## 📧 Support & Questions

For questions about this organizational analysis:
- Review the `Meta_Org_Analysis.md` detailed report
- Examine the interactive HTML chart for employee details
- Reference the CSV files for specific data points

---

## 📄 License & Attribution

**Data Source**: Gem talent database  
**Analysis Generated**: November 4, 2025  
**Usage**: Internal analysis and strategic planning  

---

## 🔄 Updates & Maintenance

This analysis is a static snapshot. For updated organizational data:
- Re-run analysis with fresh Gem database export
- Update tier classification rules as needed
- Refine department categorization based on organizational changes
- Validate against Meta's official organizational announcements

---

## 🏆 Best Practices

### When Using This Data
✅ Cross-reference with multiple sources for validation  
✅ Update regularly as organizational structure evolves  
✅ Respect employee privacy and data handling policies  
✅ Use for strategic planning, not for unauthorized contact  

### When Sharing
✅ Share only with authorized stakeholders  
✅ Redact sensitive information as appropriate  
✅ Clearly mark as analysis, not official Meta org chart  
✅ Attribute data source and analysis date  

---

**Last Updated**: November 4, 2025  
**Version**: 1.0  
**Employees Analyzed**: 2,654  
**Departments**: 14  
**Files Generated**: 5
