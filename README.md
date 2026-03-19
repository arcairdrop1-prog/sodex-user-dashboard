# sodex-user-dashboard
Web3 Connectivity (Ethers.js)
The core of this application is powered by Ethers.js (v5.7.2).

Provider Integration: I implemented a Web3Provider to interface with the user's browser-based wallet (MetaMask).

Asynchronous Authentication: Used eth_requestAccounts to securely request wallet access, ensuring a smooth UX with real-time feedback.

Dynamic UI Updates: The dashboard logic identifies the connected wallet address and triggers an immediate interface update, slicing the address for security and visual clarity (e.g., 0x123...abcd).

Modern UI/UX (Tailwind CSS)
To achieve a "dark mode" premium look compatible with SoDEX branding:

Utility-First Design: Leveraged Tailwind CSS for rapid styling, focusing on responsiveness and micro-interactions (hover effects and active-state scaling).

Glassmorphism: Applied custom CSS backdrops with backdrop-filter: blur() to create a high-end layer effect for the cards and sidebar.

SPA Navigation: Developed a custom JavaScript-based routing system to switch between "Dashboard" and "Ranking" sections without reloading the page, providing a seamless Single Page Application experience.

🛠️ Built With
HTML5/JS - Core structure and logic.

Tailwind CSS - Layout and styling.

Ethers.js - Blockchain interaction.

FontAwesome - Vector icons for professional UI.
