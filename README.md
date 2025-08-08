# Audit template

## How to generate a report
1. Generate a pdf report 
```
markdown2pdf -p REPORT.md -o REPORT.pdf
```
2. Update `front_page_template.kra` with protocol details
3. Export `front_page_template.kra` to `png`
4. Convert `front_page_template.png` to `pdf` via https://www.ilovepdf.com/jpg_to_pdf
5. Merge `front_page_template.pdf` and `REPORT.pdf` via https://www.ilovepdf.com/merge_pdf
