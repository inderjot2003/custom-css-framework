# **Custom CSS Framework**

A lightweight and customizable CSS framework built with Sass, designed to provide a cohesive and appealing theme for standard HTML elements along with utility classes for common styling needs.

---

## **Features**
- Custom theme for standard HTML elements, including:
  - Headings
  - Lists
  - Buttons
  - Forms
  - Inputs
  - Tables
- Utility classes for:
  - Colors
  - Font weight
  - Font size
  - Margins
  - Padding
  - Borders
- Built using **Sass** for easy customization.
- Includes a precompiled CSS file for quick use.

---

## **Installation**

1. Clone the repository:
   ```bash
   git clone https://github.com/inderjot2003/custom-css-framework.git
   ```
2. Navigate to the project directory:
   ```bash
   cd custom-css-framework
   ```
3. Install the dependencies (Node.js and npm are required):
   ```bash
   npm install
   ```

---

## **Usage**

### Include in Your Project
1. Add the compiled CSS file (`css/main.css`) to your project:
   ```html
   <link rel="stylesheet" href="path/to/main.css">
   ```
2. Start using the prebuilt classes and styled components in your HTML.

---

### **Customization**
To customize the framework:
1. Modify the **Sass variables** in the `_variables.scss` file (located in the `scss` directory):
   ```scss
   $primary-color: #3498db;
   $secondary-color: #2ecc71;
   ```
2. Recompile the Sass files:
   ```bash
   npm run build
   ```

---

## **Project Structure**
```
custom-css-framework/
├── css/               
├── scss/              
│   ├── base/          
│   ├── components/    
│   ├── utilities/     
│   ├── _variables.scss 
│   └── main.scss      
├── node_modules/      
├── .gitignore         
├── package.json       
├── README.md          
```

---

## **Development**

### **Compile Sass**
Run the following command to compile Sass into CSS:
```bash
npm run build
```

---

## **Contribution**
Contributions are welcome! Feel free to fork the repository and submit pull requests.

---

## **Author**
Created by **Inder Kaur**.

---
