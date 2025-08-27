<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Profile</title>
  <style>
    body {
      background-color: #0d1117;
      color: #e6edf3;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }

    header {
      text-align: center;
      padding: 40px 20px;
      border-bottom: 1px solid #30363d;
    }

    header h1 {
      font-size: 3rem;
      margin: 0;
    }

    header p {
      font-size: 1.2rem;
      color: #a1a1a1;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 20px;
      border-bottom: 2px solid #30363d;
      padding-bottom: 10px;
    }

    .skills {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(80px, 1fr));
      gap: 20px;
      text-align: center;
    }

    .skills img {
      width: 60px;
      height: 60px;
      transition: transform 0.3s;
    }

    .skills img:hover {
      transform: scale(1.2);
    }

    footer {
      text-align: center;
      padding: 20px;
      margin-top: 40px;
      border-top: 1px solid #30363d;
      color: #a1a1a1;
    }
  </style>
</head>
<body>

  <!-- Header Section -->
  <header>
    <h1>👋 Hi, I'm Rohan</h1>
    <p>I'm an enthusiastic Techie and Developer who loves contributing to Open Source.</p>
  </header>

  <!-- Skills Section -->
  <section>
    <h2>💻 My Skills</h2>

    <h3>Languages</h3>
    <div class="skills">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript">
    </div>

    <h3>Frameworks</h3>
    <div class="skills">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next.js">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap">
    </div>

    <h3>Tools</h3>
    <div class="skills">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" alt="Linux">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VSCode">
    </div>

    <h3>Designing & Photo Editing</h3>
    <div class="skills">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/photoshop/photoshop-plain.svg" alt="Photoshop">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/illustrator/illustrator-plain.svg" alt="Illustrator">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gimp/gimp-original.svg" alt="GIMP">
    </div>
  </section>

  <!-- Footer -->
  <footer>
    © 2025 Rohan | Built with ❤️ using HTML & CSS
  </footer>

</body>
</html>
