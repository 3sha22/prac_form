document.getElementById("loginForm").addEventListener("submit", function(event) {
    event.preventDefault();

    // Inputs
    const username = document.getElementById("username").value.trim();
    const password = document.getElementById("password").value;

    // Error + success elements
    const usernameError = document.getElementById("usernameError");
    const passwordError = document.getElementById("passwordError");
    const successMsg = document.getElementById("successMsg");

    // Reset messages
    usernameError.textContent = "";
    passwordError.textContent = "";
    successMsg.textContent = "";

    let valid = true;

    // Validate username
    if (username === "") {
        usernameError.textContent = "Username is required";
        valid = false;
    }

   
});