<div align="center">

# 👋 Daniel Alexis Cruz

### ☕ Full-stack dev with a caffeine problem

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00D4AA&center=true&vCenter=true&width=600&lines=Building+stuff+that+hopefully+works+%F0%9F%92%BB;From+Cebu+%F0%9F%87%B5%F0%9F%87%AD+coding+at+weird+hours+%F0%9F%8C%99;Blockchain+%2B+AI+%2B+too+much+coffee+%E2%98%95;Stack+Overflow+is+my+second+home+%F0%9F%8F%A0" alt="Typing SVG" />

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Let's_connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dacruz24)
[![Email](https://img.shields.io/badge/Email-I_actually_reply-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dcruz@up.edu.ph)
![Profile Views](https://komarev.com/ghpvc/?username=Exalt24&color=blueviolet&style=for-the-badge)

</div>

## The short version

UP Cebu CS grad who did an internship at ChatGenie where I learned Rails and Vue while building a dating platform and hotel booking system. Turns out I kind of enjoy figuring out new tech stacks under pressure.

Recently went down the blockchain rabbit hole - built an NFT marketplace, blockchain explorer that doesn't suck performance-wise, and a Web3 game. Before that, led a team building an AI study assistant. Also got to present research at Kyoto University in Japan, which was pretty cool.

Currently working on MAGSEL, a metaverse learning platform. Yes, metaverse. Yes, I can hear you groaning. No, it's not just Zoom with avatars. I promise it's actually useful for education.

```javascript
const daniel = {
  location: "Cebu, Philippines 🇵🇭",
  currentlyDoing: "Making AI that doesn't hallucinate your data away",
  recentProjects: "NFT marketplace, blockchain explorer, Web3 game",
  codingStyle: "Ship fast, test thoroughly, debug with console.log",
  hotTake: "Documentation is overrated if your code is clean enough",
  coffeeStatus: "CRITICAL DEPENDENCY"
}

// Yes, I use console.log for debugging. No, I will not apologize.
// Come at me, debugger users.
```

## Stuff I've actually built

### NFT Trading Platform (Oct 2025)
**Tech**: Solidity, Hardhat, React 19, Node.js, PostgreSQL, IPFS, Docker
[Code](https://github.com/Exalt24/nft-trading-platform)

Production-ready NFT marketplace because I wanted to understand how this whole Web3 thing actually works (and maybe prove I could build something in the space without making it a scam). ERC-721 contracts with batch minting (up to 20 NFTs at once), royalty management, IPFS storage via Pinata. Real-time trading feed with WebSocket, analytics dashboard with Recharts. 

The boring but important part: 52 smart contract tests and 50+ integration tests covering the complete lifecycle. Turns out testing matters when real money might be involved. Who knew?

### Blockchain Explorer (Oct 2025)
**Tech**: Solidity, React 19, Node.js, PostgreSQL, WebSocket, Docker
[Code](https://github.com/Exalt24/blockchain-explorer)

Built this to index blockchain events in real-time. The fun challenge was making it actually fast - implemented an in-memory LRU cache that delivers 8-10x performance improvement with 80-90% hit rate. Now handles 200-500 req/s with sub-200ms P95 response times.

Interactive analytics dashboard shows player leaderboards and event distribution. Batch processing handles 50 events at once with WebSocket throttling for real-time updates without melting your server.

### MiniWorld (Oct 2025)
**Tech**: Solidity, React 19, TypeScript, Node.js, PostgreSQL, Socket.IO, Docker
[Code](https://github.com/Exalt24/miniworld)

Web3 game with on-chain mechanics. 10x10 grid where players claim tiles and place items, achieving sub-100ms real-time state synchronization (because laggy blockchain games are everyone's worst nightmare). Built a complete TypeScript SDK that abstracts all the Web3 complexity with bundled contract ABI distribution.

Dual frontends: Canvas-based game client and a creator dashboard with analytics. Both consume the centralized SDK. One-command Docker deployment because deployment shouldn't require a PhD or three Stack Overflow tabs.

### AI Math Problem Generator (Oct 2025)
**Tech**: Next.js 14, TypeScript, Google Gemini AI, Supabase, Tailwind CSS
[Try it](https://math-problem-generator-one.vercel.app/) | [Code](https://github.com/Exalt24/math-problem-generator)

AI-powered math problems for Primary 5 students aligned with Singapore Mathematics syllabus. Three-tier difficulty system with progressive AI-generated hints that guide without just giving the answer. Because teaching kids to think > teaching them to copy.

Deployed on Vercel with Gemini 2.0 Flash integration. Has 6 automated test scripts because even educational tools should work properly.

### RataTutor (May 2025)
**Tech**: Django, React, Docker, AI
[Try it](https://ratatutor.onrender.com/) | [Code](https://github.com/Exalt24/RataTutor)

Led a 5-person team building an AI study assistant. Transforms notes into personalized flashcards and quizzes, processing PDF, DOCX, TXT, and PPTX formats. 

The interesting technical challenge: preventing AI context overload. Built hybrid context management using rolling summaries plus recent messages. Turns out AI models have memory limits just like humans who study at 2 AM. 30+ Django REST API endpoints, Dockerized, deployed to Render.

### Other projects worth mentioning

**Dijkstraverse** - Pathfinding visualizer ([try it](https://dijkstraverse.vercel.app/) | [code](https://github.com/Exalt24/Dijkstraverse))
Watch Dijkstra's algorithm find the shortest path in real-time. Built with vanilla JS and min-heap optimization because sometimes you don't need a framework.

**PennywAIse** - AI budgeting ([try it](https://pennywaise.onrender.com/) | [code](https://github.com/Exalt24/PennywAIse))
AI-driven budgeting dashboard that tells you where your money disappears to. Django + Chart.js for visualization.

**SQAN** - QR Technology Platform
Co-founded startup that won Philippine Startup Challenge 8 (Best Video Pitch, 2023). Democratizing digital access through QR code technology.

**MAGSEL** - Metaverse Learning Platform (Dec 2024 - Present)
AI-powered metaverse for gender-sensitive social-emotional education. Presenting research at WILLS 2025 Conference at Kyoto University, Japan. Unity + Flask + AI + way too much caffeine.

## Tech stack (the stuff I actually use)

**Currently obsessed with**: React 19, Next.js 14, Solidity, Hardhat, Node.js, PostgreSQL, Docker, WebSocket, IPFS, Google Gemini AI

**Also pretty good at**: Vue.js, Ruby on Rails, TypeScript, Python, Django, Java, MongoDB, Firebase, React Native, Flutter, Unity, Godot

**For when things need to actually deploy**: Vercel, Render, AWS, Docker, Git

**For when I pretend to be responsible**: Hardhat tests, integration tests, E2E tests (because shipping broken code to production is a special kind of embarrassing)

## Stats (because we all secretly care)

<div align="center">
  
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Exalt24&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Exalt24&layout=compact&langs_count=7&theme=tokyonight"/>
  
</div>

<div align="center">
  
  [![GitHub Streak](https://streak-stats.demolab.com/?user=Exalt24&theme=tokyonight)](https://git.io/streak-stats)
  
</div>

*The green squares are proof I touch grass between commits.*

## Let's talk tech (or argue about tabs vs spaces)

I respond to emails surprisingly fast for someone who codes all day. Down for conversations about:
- Why your security is probably broken (spoiler: SQL injection)
- AI that doesn't hallucinate fake citations
- Blockchain architecture without the crypto bro energy
- That startup idea you've been sitting on
- Whether pineapple belongs on pizza (it does, and I will die on this hill)

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-The_professional_version-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dacruz24)
[![Email](https://img.shields.io/badge/Email-I_actually_check_this-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dcruz@up.edu.ph)

**Star my repos if they don't suck. Open an issue if they do.**

</div>

---

<div align="center">
  
  ![Snake animation](https://github.com/Exalt24/Exalt24/blob/output/github-contribution-grid-snake.svg)
  
  *Thanks for reading this far. You either think I'm interesting or you're really good at procrastinating. Either way, respect.*
  
  **Now go build something. Or star my repos. Or both. I'm not your manager.**
  
</div>
