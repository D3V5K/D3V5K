<!DOCTYPE html>
<html>
<body>
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=35&duration=3000&pause=1000&color=00A6FF&center=true&vCenter=true&width=700&height=70&lines=Oussama+Nyqech;MERN+Stack+Architect;Full-Stack+Engineer;UI%2FUX+Designer;Creative+Developer" alt="Typing Animation" />
</div>

<!-- Profile Header with Matrix Effect -->
<div align="center">
  <pre style="font-family: 'Courier New', monospace; color: #00A6FF;">
╔═══════════════════════════════════════════════════════════════════╗
║  ██████╗ ██╗   ██╗███████╗███████╗ █████╗ ███╗   ███╗ █████╗     ║
║ ██╔═══██╗██║   ██║██╔════╝██╔════╝██╔══██╗████╗ ████║██╔══██╗    ║
║ ██║   ██║██║   ██║███████╗█████╗  ███████║██╔████╔██║███████║    ║
║ ██║   ██║██║   ██║╚════██║██╔══╝  ██╔══██║██║╚██╔╝██║██╔══██║    ║
║ ╚██████╔╝╚██████╔╝███████║███████╗██║  ██║██║ ╚═╝ ██║██║  ██║    ║
║  ╚═════╝  ╚═════╝ ╚══════╝╚══════╝╚═╝  ╚═╝╚═╝     ╚═╝╚═╝  ╚═╝    ║
║                                                                   ║
║                  MERN STACK ARCHITECT | CREATIVE DEVELOPER        ║
╚═══════════════════════════════════════════════════════════════════╝
  </pre>
</div>

<div align="center">
  <img src="https://github.com/SP-XD/SP-XD/blob/main/images/hellocoders_rounded.gif?raw=true" width="55%"/>
  <br/>
  <img src="https://github.com/SP-XD/SP-XD/blob/main/images/dev-working_rounded.gif?raw=true" width="35%"/>
</div>

<!-- Professional Metrics Bar -->
<div align="center">
  <table border="0" cellpadding="10">
    <tr>
      <td align="center">
        <img src="https://komarev.com/ghpvc/?username=OussamaNyqech&style=flat-square&color=00A6FF&label=PROFILE+VIEWS" alt="Profile Views"/>
      </td>
      <td align="center">
        <img src="https://img.shields.io/github/followers/OussamaNyqech?style=flat-square&logo=github&color=00A6FF&label=FOLLOWERS" alt="Followers"/>
      </td>
      <td align="center">
        <img src="https://img.shields.io/github/stars/OussamaNyqech?style=flat-square&logo=github&color=00A6FF&label=TOTAL+STARS" alt="Stars"/>
      </td>
      <td align="center">
        <img src="https://img.shields.io/badge/Status-Active-00A6FF?style=flat-square&logo=statuspal" alt="Status"/>
      </td>
    </tr>
  </table>
</div>

---

<!-- Professional Code Presentation Section -->
<details open>
<summary><b>📋 PROFESSIONAL PROFILE</b> (Click to expand)</summary>

```typescript
/**
 * @author Oussama Nyqech
 * @description MERN Stack Developer | Creative Technologist
 * @version 2.0.0
 */

interface IDeveloper {
  name: string;
  title: string;
  location: string;
  expertise: string[];
  currentFocus: string;
  designTools: string[];
  languages: { [key: string]: string };
  socials: { [key: string]: string };
}

class MERNArchitect implements IDeveloper {
  public name: string = "Oussama Nyqech";
  public title: string = "Full Stack MERN Developer";
  public location: string = "Casablanca, Morocco 🇲🇦";
  
  public expertise: string[] = [
    "React.js / Next.js",
    "Node.js / Express.js",
    "MongoDB / Mongoose",
    "MySQL / PostgreSQL",
    "RESTful APIs / GraphQL",
    "JWT / OAuth Authentication",
    "Docker / CI-CD",
    "AWS / Cloud Deployment"
  ];
  
  public currentFocus: string = "Building Scalable Enterprise Applications";
  
  public designTools: string[] = [
    "Adobe Photoshop CC",
    "Figma",
    "Adobe XD",
    "Canva Pro"
  ];
  
  public languages: { [key: string]: string } = {
    "Arabic": "Native",
    "English": "Professional",
    "French": "Intermediate",
    "JavaScript": "Expert",
    "TypeScript": "Advanced"
  };
  
  public socials: { [key: string]: string } = {
    "GitHub": "https://github.com/OussamaNyqech",
    "LinkedIn": "https://linkedin.com/in/oussama-nyqech",
    "Portfolio": "https://oussama-nyqech.dev",
    "Email": "oussama@nyqech.dev"
  };
  
  constructor() {
    this.initialize();
  }
  
  private initialize(): void {
    console.log(`🚀 ${this.name} - ${this.title} initialized`);
    console.log(`📍 Based in ${this.location}`);
    console.log(`💻 Ready for collaboration`);
  }
  
  public getTechStack(): object {
    return {
      frontend: ["React", "Next.js", "TailwindCSS", "Redux"],
      backend: ["Node.js", "Express", "NestJS"],
      database: ["MongoDB", "MySQL", "Redis"],
      devops: ["Docker", "AWS", "Vercel", "Netlify"]
    };
  }
  
  public async buildProject(requirements: string[]): Promise<string> {
    // Always delivering high-quality, scalable solutions
    return "✨ Enterprise-grade application delivered successfully";
  }
}

// Instantiate the developer
const oussama = new MERNArchitect();

// Display current status
console.table(oussama.getTechStack());
