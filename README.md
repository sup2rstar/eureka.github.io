/* style.css */

/* --- 1. Full-Screen Background --- */
body {
    /* YOUR CORRECT DIRECT LINK */
    background-image: url('https://i.postimg.cc/5NPjYHJx/Sans-titre-1122-20251207182508.png'); 
    
    background-size: cover; 
    background-attachment: fixed; 
    background-position: center center;
    
    margin: 0; 
    padding: 0;
    min-height: 100vh;
    font-family: sans-serif; 
}

/* --- 2. Button and Navigation Layout --- */
.hero-section {
    min-height: 100vh;
    width: 100%;
    /* Subtle overlay for contrast */
    background-color: rgba(0, 0, 0, 0.3); 
    padding: 20px;
    box-sizing: border-box; 
}

nav {
    /* Ensures buttons are aligned to the top right */
    display: flex;
    justify-content: flex-end; 
    gap: 15px; 
}

/* --- 3. Button Styling --- */
.auth-button {
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    color: white; 
    background-color: #007bff; 
    border: 2px solid white; 
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.auth-button:hover {
    background-color: #0056b3; 
    text-decoration: underline;
}

/* REMOVED: h1 styling */
