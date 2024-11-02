- 👋 Hi, I’m @ERdem555555
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
ERdem555555/ERdem555555 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f0f0f0;
    margin: 0;
}

.heart {
    position: relative;
    width: 100px;
    height: 100px;
    background-color: red;
    transform: rotate(-45deg);
    animation: pulse 1s infinite;
}

.heart::before,
.heart::after {
    content: '';
    position: absolute;
    width: 100px;
    height: 100px;
    background-color: red;
    border-radius: 50%;
}

.heart::before {
    top: -50px;
    left: 0;
}

.heart::after {
    left: 50px;
    top: 0;
}

@keyframes pulse {
    0%, 100% {
        transform: scale(1);
    }
    50% {
        transform: scale(1.1);
    }
}

