html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dashboard</title>
    <link rel="stylesheet" href="/admin dashbord/style.css">
</head>
<body>
    <nav>
        <div class="logo">Dashboard</div>
        <ul>
            <li> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="home"><path d="M10,20V14H14V20H19V12H22L12,3L2,12H5V20H10Z"  /></svg>Home</li>
            <li> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="profile"><title>card-account-details-outline</title><path d="M22,3H2C0.91,3.04 0.04,3.91 0,5V19C0.04,20.09 0.91,20.96 2,21H22C23.09,20.96 23.96,20.09 24,19V5C23.96,3.91 23.09,3.04 22,3M22,19H2V5H22V19M14,17V15.75C14,14.09 10.66,13.25 9,13.25C7.34,13.25 4,14.09 4,15.75V17H14M9,7A2.5,2.5 0 0,0 6.5,9.5A2.5,2.5 0 0,0 9,12A2.5,2.5 0 0,0 11.5,9.5A2.5,2.5 0 0,0 9,7M14,7V8H20V7H14M14,9V10H20V9H14M14,11V12H18V11H14" /></svg>Profile</li>
            <li> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="messages"><title>message</title><path d="M20,2H4A2,2 0 0,0 2,4V22L6,18H20A2,2 0 0,0 22,16V4C22,2.89 21.1,2 20,2Z" /></svg>Messages</li>
            <li> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="history"><title>history</title><path d="M13.5,8H12V13L16.28,15.54L17,14.33L13.5,12.25V8M13,3A9,9 0 0,0 4,12H1L4.96,16.03L9,12H6A7,7 0 0,1 13,5A7,7 0 0,1 20,12A7,7 0 0,1 13,19C11.07,19 9.32,18.21 8.06,16.94L6.64,18.36C8.27,20 10.5,21 13,21A9,9 0 0,0 22,12A9,9 0 0,0 13,3" /></svg>History</li>
            <li> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="tasks"><title>checkbox-marked-circle-plus-outline</title><path d="M14.3 21.7C13.6 21.9 12.8 22 12 22C6.5 22 2 17.5 2 12S6.5 2 12 2C13.3 2 14.6 2.3 15.8 2.7L14.2 4.3C13.5 4.1 12.8 4 12 4C7.6 4 4 7.6 4 12S7.6 20 12 20C12.4 20 12.9 20 13.3 19.9C13.5 20.6 13.9 21.2 14.3 21.7M7.9 10.1L6.5 11.5L11 16L21 6L19.6 4.6L11 13.2L7.9 10.1M18 14V17H15V19H18V22H20V19H23V17H20V14H18Z" /></svg>Tasks</li>
            <li> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="communities"><title>google-circles-communities</title><path d="M15,12C13.89,12 13,12.89 13,14A2,2 0 0,0 15,16A2,2 0 0,0 17,14C17,12.89 16.1,12 15,12M12,20A8,8 0 0,1 4,12A8,8 0 0,1 12,4A8,8 0 0,1 20,12A8,8 0 0,1 12,20M12,2A10,10 0 0,0 2,12A10,10 0 0,0 12,22A10,10 0 0,0 22,12A10,10 0 0,0 12,2M14,9C14,7.89 13.1,7 12,7C10.89,7 10,7.89 10,9A2,2 0 0,0 12,11A2,2 0 0,0 14,9M9,12A2,2 0 0,0 7,14A2,2 0 0,0 9,16A2,2 0 0,0 11,14C11,12.89 10.1,12 9,12Z" /></svg>Communities</li>
            <li> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="settings"><title>cog</title><path d="M12,15.5A3.5,3.5 0 0,1 8.5,12A3.5,3.5 0 0,1 12,8.5A3.5,3.5 0 0,1 15.5,12A3.5,3.5 0 0,1 12,15.5M19.43,12.97C19.47,12.65 19.5,12.33 19.5,12C19.5,11.67 19.47,11.34 19.43,11L21.54,9.37C21.73,9.22 21.78,8.95 21.66,8.73L19.66,5.27C19.54,5.05 19.27,4.96 19.05,5.05L16.56,6.05C16.04,5.66 15.5,5.32 14.87,5.07L14.5,2.42C14.46,2.18 14.25,2 14,2H10C9.75,2 9.54,2.18 9.5,2.42L9.13,5.07C8.5,5.32 7.96,5.66 7.44,6.05L4.95,5.05C4.73,4.96 4.46,5.05 4.34,5.27L2.34,8.73C2.21,8.95 2.27,9.22 2.46,9.37L4.57,11C4.53,11.34 4.5,11.67 4.5,12C4.5,12.33 4.53,12.65 4.57,12.97L2.46,14.63C2.27,14.78 2.21,15.05 2.34,15.27L4.34,18.73C4.46,18.95 4.73,19.03 4.95,18.95L7.44,17.94C7.96,18.34 8.5,18.68 9.13,18.93L9.5,21.58C9.54,21.82 9.75,22 10,22H14C14.25,22 14.46,21.82 14.5,21.58L14.87,18.93C15.5,18.67 16.04,18.34 16.56,17.94L19.05,18.95C19.27,19.03 19.54,18.95 19.66,18.73L21.66,15.27C21.78,15.05 21.73,14.78 21.54,14.63L19.43,12.97Z" /></svg>Settings</li>
            <li> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="support"><title>face-agent</title><path d="M18.72,14.76C19.07,13.91 19.26,13 19.26,12C19.26,11.28 19.15,10.59 18.96,9.95C18.31,10.1 17.63,10.18 16.92,10.18C13.86,10.18 11.15,8.67 9.5,6.34C8.61,8.5 6.91,10.26 4.77,11.22C4.73,11.47 4.73,11.74 4.73,12A7.27,7.27 0 0,0 12,19.27C13.05,19.27 14.06,19.04 14.97,18.63C15.54,19.72 15.8,20.26 15.78,20.26C14.14,20.81 12.87,21.08 12,21.08C9.58,21.08 7.27,20.13 5.57,18.42C4.53,17.38 3.76,16.11 3.33,14.73H2V10.18H3.09C3.93,6.04 7.6,2.92 12,2.92C14.4,2.92 16.71,3.87 18.42,5.58C19.69,6.84 20.54,8.45 20.89,10.18H22V14.67H22V14.69L22,14.73H21.94L18.38,18L13.08,17.4V15.73H17.91L18.72,14.76M9.27,11.77C9.57,11.77 9.86,11.89 10.07,12.11C10.28,12.32 10.4,12.61 10.4,12.91C10.4,13.21 10.28,13.5 10.07,13.71C9.86,13.92 9.57,14.04 9.27,14.04C8.64,14.04 8.13,13.54 8.13,12.91C8.13,12.28 8.64,11.77 9.27,11.77M14.72,11.77C15.35,11.77 15.85,12.28 15.85,12.91C15.85,13.54 15.35,14.04 14.72,14.04C14.09,14.04 13.58,13.54 13.58,12.91A1.14,1.14 0 0,1 14.72,11.77Z" /></svg>Support</li>
            <li> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="privacy"><title>lock-check-outline</title><path d="M14 15C14 16.11 13.11 17 12 17C10.89 17 10 16.1 10 15C10 13.89 10.89 13 12 13C13.11 13 14 13.9 14 15M13.09 20C13.21 20.72 13.46 21.39 13.81 22H6C4.89 22 4 21.1 4 20V10C4 8.89 4.89 8 6 8H7V6C7 3.24 9.24 1 12 1S17 3.24 17 6V8H18C19.11 8 20 8.9 20 10V13.09C19.67 13.04 19.34 13 19 13C18.66 13 18.33 13.04 18 13.09V10H6V20H13.09M9 8H15V6C15 4.34 13.66 3 12 3S9 4.34 9 6V8M21.34 15.84L17.75 19.43L16.16 17.84L15 19L17.75 22L22.5 17.25L21.34 15.84Z" /></svg>Privacy</li>
        </ul>
    </nav>
    <div class="content">
        <div class="header">
            <div class="search-bar">
                <input type="text" placeholder="Search...">
            </div>
            <div class="user-info">
                <img> <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" class="notification-icon"><title>bell</title><path d="M21,19V20H3V19L5,17V11C5,7.9 7.03,5.17 10,4.29C10,4.19 10,4.1 10,4A2,2 0 0,1 12,2A2,2 0 0,1 14,4C14,4.1 14,4.19 14,4.29C16.97,5.17 19,7.9 19,11V17L21,19M14,21A2,2 0 0,1 12,23A2,2 0 0,1 10,21" /></svg></img>
                <span class="user-name">Abdikarim Ali</span>
            </div>
        </div>
        <div class="main">
            <div class="projects">
                <h2>Your Projects</h2>
                <div class="project-card">
                    <h3>Super Cool Project</h3>
                    <p>Sed tempus ut lacus ut scelerisque. Suspendisse sollicitudin nibh erat, id facilisis felis accumsan nec.</p>
                    <div class="project-actions">
                        <span class="icon">⭐</span>
                        <span class="icon">💬</span>
                        <span class="icon">🔗</span>
                    </div>
                </div>
                <div class="project-card">
                    <h3> Cool Project</h3>
                    <p>Nullam condimentum ipsum ut lectus vehicula consectetur. Quisque sed dolor tincidunt, consectetur sapien et, facilisis dolor.</p>
                    <div class="project-actions">
                        <span class="icon">⭐</span>
                        <span class="icon">💬</span>
                        <span class="icon">🔗</span>
                    </div>
                </div>
                <div class="project-card">
                    <h3>Impossible App</h3>
                    <p>In hac habitasse platea dictumst. Vivamus dictum rutrum arcu, a placerat velit sagittis id.</p>
                    <div class="project-actions">
                        <span class="icon">⭐</span>
                        <span class="icon">💬</span>
                        <span class="icon">🔗</span>
                    </div>
                </div>
                <div class="project-card">
                    <h3>Easy Peasy App</h3>
                    <p>Etiam cursus eros ac efficitur fringilla. Vestibulum dignissim urna eget accumsan aliquam.</p>
                    <div class="project-actions">
                        <span class="icon">⭐</span>
                        <span class="icon">💬</span>
                        <span class="icon">🔗</span>
                    </div>
                </div>
                <div class="project-card">
                    <h3>Ad Blocker</h3>
                    <p>Quisque eget rutrum nisl. Nam augue justo, cursus vitae metus vel, pharetra hendrerit felis.</p>
                    <div class="project-actions">
                        <span class="icon">⭐</span>
                        <span class="icon">💬</span>
                        <span class="icon">🔗</span>
                    </div>
                </div>
                <div class="project-card">
                    <h3>Money Maker</h3>
                    <p>Praesent convallis, libero quis congue elementum, nunc ante faucibus sapien, ac scelerisque tortor purus sit amet ex.</p>
                    <div class="project-actions">
                        <span class="icon">⭐</span>
                        <span class="icon">💬</span>
                        <span class="icon">🔗</span>
                    </div>
                </div>
            </div>
            <div class="sidebar">
                <div class="announcements">
                    <h3>Announcements</h3>
                    <p>Site Maintenance: Vestibulum condimentum tellus lacus, in accumsan elit maximus ac.</p>
                    <p>Community Share Day: Nam vel lectus tincidunt, rutrum nulla eu, ornare libero.</p>
                    <p>Updated Privacy Policy: Phasellus efficitur nisi eget elit consectetur, eget condimentum ante auctor.</p>
                </div>
                <div class="trending">
                    <h3>Trending</h3>
                    <p>@tegan: World Peace Builder</p>
                    <p>@morgan: Super Cool Project</p>
                    <p>@kendall: Life Changing App</p>
                    <p>@alex: No Traffic Maker</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>


css

body {
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    margin: 0;
    display: grid;
    grid-template-columns: 240px 1fr;
    height: 100vh;
}

nav {
    background-color: #FFF2E1;
    padding: 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
    width: 100%;
    background-color: #EAD8C0;
    border-radius: 16px;
}

nav ul li {
    padding: 20px;
    text-align: left;
    cursor: pointer;
}

nav ul li:hover {
    background-color: #D1BB9E;
    border-radius: 16px;
}

nav .logo {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 20px;
}

.home, .profile, .messages, .history, .tasks, .communities, .settings, .support, .privacy {
    width:20px;
    height:15px;
    margin-right: 5px;
}

.content {
    display: grid;
    grid-template-rows: auto 1fr;
    background-color: #F6E6CB;
}

.header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 30px;
    background-color: #A79277;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.search-bar input {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 50px;
    width: 500px;
}

.user-info {
    display: flex;
    align-items: center;
}

.notification-icon {
    margin-right: 20px;
}

.user-name {
    margin-right: 50px;
}

.main {
    display: grid;
    grid-template-columns: 2fr 1fr;
    padding: 20px;
    gap: 20px;
}

.projects {
    display: grid;
    grid-template-rows: auto 1fr;
    gap: 20px;
}

.project-card {
    background-color: #D1BB9E;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.project-card:hover {
    background-color: #A79277;
}

.project-actions {
    display: flex;
    justify-content: space-between;
    margin-top: 10px;
}

.project-actions .icon {
    cursor: pointer;
}

.sidebar {
    display: grid;
    grid-template-rows: auto 1fr;
    gap: 20px;
}

.announcements, .trending {
    background-color: #D1BB9E;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.home {
    width:20px;
    height:15px;
    margin-right: 5px;
}
