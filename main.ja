// ==========================================
// CORE APPLICATION ENGINE (main.js)
// ==========================================

document.addEventListener("DOMContentLoaded", () => {
    console.log("🚀 main.js has successfully connected to index.html!");

    // 1. HUNT AND DISMISS THE LOADING SCREEN
    // This looks for the most common IDs used for loading overlays
    const loader = document.getElementById("loading-screen") || 
                   document.getElementById("loader") || 
                   document.getElementById("loading") ||
                   document.querySelector(".loader");

    if (loader) {
        console.log("📦 Loading screen detected. Dismissing now...");
        // Smooth fade out
        loader.style.transition = "opacity 0.5s ease, visibility 0.5s";
        loader.style.opacity = "0";
        loader.style.visibility = "hidden";
        
        // Completely remove from layout after fade
        setTimeout(() => {
            loader.style.display = "none";
        }, 500);
    } else {
        console.warn("⚠️ Couldn't find a standard loading element. Check your index.html for its exact ID.");
    }

    // 2. YOUR CUSTOM LOGIC GOES HERE
    // You can start building your app features below this line
    
});


