Today I built a simple calculator using only pure HTML and basic JavaScript — no CSS, no external libraries, just core logic and structure.

🔸 Key Features:

    Built with basic <form>, <table>, and input tags.

    Used the eval() function to perform arithmetic operations.

    Utilized name and value attributes to control input and buttons.

    The readonly attribute prevents direct typing in the display area.

    Reset button clears the calculator instantly.

🧠 What I learned:

    How to structure a project using only HTML elements.

    Accessing form elements using formName.inputName.value.

    How eval() evaluates string expressions (like "1+2" into 3).

    The importance of understanding how attributes like name, value, and readonly work in forms.

👨‍💻 Code Preview:

<form name="f1">
  <input type="text" name="one" size="30" readonly>
  <input type="button" value="7" onclick="f1.one.value += '7'">
  <input type="button" value="+" onclick="f1.one.value += '+'">
  <input type="button" value="=" onclick="f1.one.value = eval(f1.one.value)">
  <input type="button" value="Reset" onclick="f1.one.value = ''">
</form>

If you're starting out in web development, this is a great mini-project to learn the basics of form handling and JavaScript logic.
