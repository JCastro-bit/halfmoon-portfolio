# **Web Developer Portfolio**

This is a portfolio website for a web developer, Javier Castro. The website showcases his skills, work experience, education, and projects.

## **Technologies Used**

- HTML
- CSS (Halfmoon Framework)
- JavaScript (Halfmoon Framework, SweetAlert2, Fontawesome)

## **Features**

- Responsive design
- Dark mode using Halfmoon framework
- Navigation menu
- About me section
- Education and work experience section
- Skills section
- Projects section

## **How to Use**

1. Clone the repository
2. Open **`index.html`** in your web browser
3. Navigate through the different sections of the website using the navigation menu

## **Dark Mode**

This website uses the Halfmoon framework to implement a dark mode feature. To toggle the dark mode on and off, click on the lightbulb icon located on the top right corner of the navigation menu.

### **Example Code**

```
htmlCopy code
<button class="btn btn-primary" type="button" onclick="toggleDarkMode()">
    <i id="lightbulb-icon" class="fa-solid fa-lightbulb fa-lg"></i>
</button>
<!-- JavaScript -->
<script src="https://cdn.jsdelivr.net/npm/halfmoon@1.1.1/js/halfmoon.min.js"></script>

<script>
    function toggleDarkMode() {
        const icon = document.getElementById("lightbulb-icon");
        if (halfmoon.getPreferredMode() === "dark-mode") {
            icon.classList.remove("fa-regular", "fa-lightbulb-on");
            icon.classList.add("fa-solid", "fa-lightbulb");
        } else {
            icon.classList.remove("fa-solid", "fa-lightbulb");
            icon.classList.add("fa-regular", "fa-lightbulb-on");
        }
        halfmoon.toggleDarkMode();
    }
</script>

```

## **Author**

- **[Javier Castro](https://github.com/JCastro-bit)**