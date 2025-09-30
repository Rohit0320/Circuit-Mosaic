
# Circuit Mosaic – Certificate Portal  

This is a web-based portal to allow participants of the **Circuit Mosaic** event to search for their name and download their participation or winner certificates in **PDF/PNG format**.  

## 🚀 Features  
- Search participants by name.  
- Click to **download certificates** in PDF or image format.  
- Mobile-friendly responsive design.  
- Customizable participant list and certificate files.  

## 📂 Project Structure  

```
project-folder/
│── index.html              # Main portal file
│── /certificates/          # Folder containing certificates (PDF/PNG)
│   ├── Aditya-Jadhav.pdf
│   ├── Nitin Gupta.png
│   └── ...
│── /assets/                # (optional) images, logos, CSS
```

## ⚙️ Setup Instructions  

1. Place all participant certificates inside the **`certificates/`** folder.  
   - Supported formats: `.pdf`, `.png`, `.jpg`  
   - Example filenames:  
     - `Aditya-Jadhav.png`  
     - `Nitin Gupta.png`  

2. Open **`index.html`** and update the **participants array** in the script:  

```js
const participants = [
  { id: 1, name: "Aditya Jadhav", certificateUrl: "certificates/Aditya-Jadhav.png" },
  { id: 2, name: "Nitin Gupta", certificateUrl: "certificates/Nitin-Gupta.png" },
  { id: 3, name: "Aryan Chauhan", certificateUrl: "certificates/Aryan-Chauhan.png" }
];
```

3. Launch the portal by opening **`index.html`** in any browser.  

4. Users can type their name in the search box and click **Download Certificate** to get their file.  

## 🖼️ Example Workflow  
1. User searches for **"Aditya Jadhav"**.  
2. The system finds the entry.  
3. User clicks **Download Certificate** → `Aditya-Jadhav.pdf` is downloaded.  

## 🔧 Customization  
- To add more participants, just extend the `participants` array in the script.  
- You can style the portal further with CSS inside `index.html`.  

## 📜 License  
This project is created for **Circuit Mosaic** event at **Thakur Shyamnarayan Engineering College**.  
Free to use and customize for academic/college event purposes.  
