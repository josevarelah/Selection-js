<p align="center">
  <a href="https://prateekkalra.github.io/Selection-js"><img alt="SelectionJS" src="./logo.png" width="150px"></a>
</p>
<p align="center">
  A lightweight javascript library which provides users with a set of options in the form of a small popover over the selected portion of text.
</p>  

 <p align="center">
  <a href="https://prateekkalra.github.io/Selection-js" target="_">Live Demo</a>
</p>

## 🚀 Features  

✔️ Lightweight and easy to integrate  
✔️ Customizable popover menu with multiple actions  
✔️ Supports copying, searching, sharing, and text-to-speech  
✔️ Simple API for configuration  
✔️ Works seamlessly with any website  

## 📥 Installation

To get started with Selection.js, download the [Script](https://github.com/prateekkalra/Selection-js/files/1920677/SelectionJS.zip) and add it to your project

## 📌 Usage

### **Basic Setup**  
To initialize Selection.js with default settings:  
```html
<script src="selection.min.js"></script>
<script>
  var selection = new Selection();
  selection.init();
</script>
```

### **Advanced Setup**
Customize popover actions and styles:
```html
<script src="selection.min.js"></script>
<script>
  var selection = new Selection();
  selection.config({
    facebook: true,
    twitter: true,
    search:true,
    copy:true,
    speak:true,
    backgroundColor: 'crimson',
    iconColor: '#fff',
  }).init();
</script>
```
## Configuration Options  

| Option          | Type    | Default | Description                                      |
|----------------|--------|---------|--------------------------------------------------|
| `facebook`     | Boolean | `false` | Enables sharing selected text on Facebook       |
| `twitter`      | Boolean | `false` | Enables sharing selected text on Twitter        |
| `search`       | Boolean | `false` | Adds a Google search option for selected text   |
| `copy`         | Boolean | `false` | Enables copying the selected text               |
| `speak`        | Boolean | `false` | Adds a text-to-speech feature                   |
| `backgroundColor` | String  | `#000`  | Customizes the popover background color        |
| `iconColor`    | String  | `#fff`  | Sets the icon color for actions                 |

## 💡 Contributing  
We welcome contributions! Follow these steps:  

1. **Fork the repository** on GitHub.  
2. **Clone your fork**:  
   ```sh
   git clone https://github.com/your-username/Selection-js.git
   cd Selection-js
   ```
3. Make updates to documentation or code
4. Commit and Push Changes
  ```sh
   git add .
   git commit -m "Your Message"
   git push origin your-branch-name
  ```
5. Open a Pull Request on GitHub.

## 📜 License
Selection.js is licensed under the [MIT License](./LICENSE), allowing free use and modification.


# 📌 Result
Below is a preview of Selection.js in action:  

<p align="center">
<img alt="Demo" src="https://user-images.githubusercontent.com/29385192/38880290-f5e173ce-4282-11e8-9447-6cab91540735.PNG">
</p>

🔹 **Features Displayed:** Selection popover with social sharing, search, and copy options.  
🔹 **How to Test Locally:**  
   - Follow the [Usage](#usage) instructions to set up Selection.js.  
   - Select any text on your webpage to see the popover in action.  
