# Marcus Amerine | Cyber Portfolio

I study computer science with a minor in cybersecurity at Saint Francis University. This portfolio collects my digital forensics coursework. The two reports below follow the same classroom case across two disk images.

## Investigation reports

| Report | Investigative question and findings |
| --- | --- |
| [Mantooth forensic report (Word)](reports/Mantooth_Forensic_Report.docx) | What connects the device to a proposal involving ATM cards? I verified the disk image against its acquisition hashes, then compared browser searches with an email describing proposed equipment. |
| [Washer forensic report (PDF)](reports/Washer_Forensic_Report.pdf) | Did the second mailbox contain an independent record of the proposal? I found the incoming message with three equipment photos and a sent reply. Together they support participation by the account, while the identity of the person at the keyboard remains uncertain. |

## Tools Used

These are tools I worked with across my digital forensics labs.

| Tool | Website | What it does |
| --- | --- | --- |
| Registry Explorer | [Eric Zimmerman's Tools](https://ericzimmerman.github.io/) | Opens Windows Registry hives for offline analysis. In the registry lab, I examined RecentDocs to see which filenames Windows recorded for a user. |
| ExifTool | [ExifTool project](https://github.com/exiftool/exiftool) | Reads metadata embedded in files. In an image-analysis lab, I used it to locate GPS coordinates stored in a photograph. |
| Volatility | [Volatility Foundation](https://volatilityfoundation.org/) | Analyzes captured memory. Its process listings can show which programs were running when the memory image was captured. |
