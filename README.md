# 📸 Invoice Automation Demonstration

This section showcases the invoice dataset preparation and automated invoice report generation used within the project workflow.

---

## 📊 Invoice Dataset (Google Sheets)

![Invoice Dataset](./assets/invoice-dataset.png)

A structured invoice dataset was created and maintained in Google Sheets to simulate real business invoice operations and reporting.

### Highlights
- Professional invoice data structure with **15 business-oriented columns**
- Includes invoice details, client information, service records, and payment tracking
- Automatic financial calculations using **GST and total invoice values**
- Designed as an input source for reporting and automation workflows

### Key Dataset Fields
| Field |
|-------|
| Invoice Number |
| Invoice Date |
| Due Date |
| Company |
| Client Name |
| Client City |
| Invoice Type |
| Service Description |
| Quantity |
| Unit Price |
| Line Amount |
| GST % |
| GST Amount |
| Total Amount |
| Payment Status |

---

## 📁 Source Excel Dataset

![Excel Dataset](./assets/invoice-excel.png)

The invoice dataset was also maintained in Excel format for structured storage, validation, and workflow execution.

### Business Purpose
- Store invoice records in a reusable format
- Enable automated extraction and reporting
- Support finance and operational monitoring
- Provide clean input data for downstream automation

### Dataset Features
- Multi-column structured financial data
- GST-based calculations
- Client and invoice tracking
- Paid and pending payment monitoring
- Ready for business reporting workflows

---

## 📄 Professional Invoice Report (Generated Output)

![Professional Invoice Report](./assets/professional-invoice-report.png)

A professional PDF invoice report was generated automatically from the prepared invoice dataset.

### Output Features
- Automated invoice extraction
- Business-ready PDF formatting
- Clean invoice summary presentation
- Supports financial documentation and reporting

### Generated Report Includes
- Invoice Number
- Date
- Vendor
- Subtotal
- Tax Calculation
- Final Invoice Amount

---

### 📌 Automation Flow

```text
Excel / Google Sheets
        ↓
Invoice Extraction
        ↓
Data Validation
        ↓
Report Generation
        ↓
Professional PDF Output
```

This demonstrates an end-to-end invoice processing and reporting workflow integrated into the automation project.
