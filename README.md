# Install Autopsy and Analyze the Disk File and Folder Configuration
#### Name: Divya R V
#### Reg no : 212223100005

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results

<img width="1920" height="1080" alt="Screenshot 2025-09-04 095956" src="https://github.com/user-attachments/assets/a1c1ea31-ff19-416b-bad0-26cb8247701c" />

<img width="1920" height="1080" alt="Screenshot 2025-09-04 100026" src="https://github.com/user-attachments/assets/e7b2d469-a890-4328-a9c2-e066860c3ec9" />

<img width="1920" height="1080" alt="Screenshot 2025-09-04 100113" src="https://github.com/user-attachments/assets/c0a4ee9b-8229-4445-a68d-b01abdd49a71" />

<img width="1920" height="1080" alt="Screenshot 2025-09-04 100408" src="https://github.com/user-attachments/assets/8be10c7d-bb85-494f-a633-dcb90069f573" />

<img width="1920" height="1080" alt="Screenshot 2025-09-04 100440" src="https://github.com/user-attachments/assets/8ccdfaaf-cf72-4bb9-85af-8499a2d19076" />

<img width="1920" height="1080" alt="Screenshot 2025-09-04 100504" src="https://github.com/user-attachments/assets/dbed7992-b6ec-4187-82f1-e8f68ac2a8fd" />

<img width="1920" height="1080" alt="Screenshot 2025-09-04 100529" src="https://github.com/user-attachments/assets/2c9b7ec0-8862-40d5-a3cd-f80f64d7e64d" />

<img width="1920" height="1080" alt="Screenshot 2025-09-04 101452" src="https://github.com/user-attachments/assets/108c35b3-c8e3-4e7c-9ace-c5eed4d0ff6e" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ab2961b6-7d12-4b60-9ca7-ed429440b10f" />

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
