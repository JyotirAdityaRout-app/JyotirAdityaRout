import pypandoc

readme = r'''<div align="center">

<!-- CYBERPUNK PROFILE HEADER -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050816,45:111827,100:00F5FF&height=210&section=header&text=ADI_TECH2.0&fontSize=48&fontColor=00F5FF&animation=fadeIn&fontAlignY=36&desc=BUILD%20%E2%80%A2%20SECURE%20%E2%80%A2%20EXPLORE&descAlignY=58&descSize=15" width="100%" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=00F5FF&center=true&vCenter=true&width=650&lines=Initializing+digital+workspace...;Cybersecurity+%7C+Python+%7C+Technology;Learning+to+think+like+an+attacker%2C;building+like+a+defender.;Curiosity+is+my+terminal." alt="Animated typing intro" />
</a>

<br/>

<img src="https://img.shields.io/badge/STATUS-ONLINE-00F5FF?style=for-the-badge&labelColor=050816" />
<img src="https://img.shields.io/badge/MODE-LEARNING-9D4EDD?style=for-the-badge&labelColor=050816" />
<img src="https://img.shields.io/badge/MINDSET-ETHICAL_HACKING-00FF9C?style=for-the-badge&labelColor=050816" />

</div>

---

## `> whoami`

```bash
┌──(adi㉿cyberlab)-[~]
└─$ whoami
Adi | Tech enthusiast | Cybersecurity learner
```

Hey! I'm **Adi**, a technology enthusiast exploring the world of **cybersecurity, ethical hacking, Python, and digital systems**.

I enjoy understanding how technology works, experimenting in safe lab environments, and building practical skills one project at a time.

- 🔐 Exploring cybersecurity fundamentals and defensive security
- 🐍 Learning Python, scripting, and automation
- 💻 Interested in Linux, networking, and system administration
- 🧪 Practising in legal, controlled labs and beginner CTF challenges
- 🚀 Always learning, building, and improving

> **Mission:** Learn responsibly. Build creatively. Secure the digital world.

---

## `> tech_stack`

<div align="center">

### Languages & scripting

<img src="https://skillicons.dev/icons?i=python,bash,html,css,js&theme=dark" />

### Systems & tools

<img src="https://skillicons.dev/icons?i=linux,windows,vscode,git,github&theme=dark" />

</div>

*Currently exploring:* networking, Linux command line, Git, Python automation, web security fundamentals, and security best practices.

---

## `> cyber_lab`

```text
[01] NETWORKING       █████░░░░░  Learning
[02] LINUX            █████░░░░░  Learning
[03] PYTHON           █████░░░░░  Learning
[04] WEB SECURITY     ███░░░░░░░  Exploring
[05] DIGITAL DEFENCE  ████░░░░░░  Exploring
```

My learning roadmap:

- [ ] TCP/IP, DNS, HTTP/HTTPS, and ports
- [ ] Linux fundamentals and shell scripting
- [ ] Python automation projects
- [ ] OWASP Top 10 and secure coding
- [ ] Log analysis and basic incident response
- [ ] Beginner CTFs and authorised security labs

---

## `> featured_projects`

> Replace these sample entries with your real repositories as you publish them.

| Project | Description | Status |
|---|---|---|
| `Cyber-Lab-Notes` | Notes from cybersecurity and networking study | Planning |
| `Python-Automation` | Small scripts to automate everyday tasks | Building |
| `Linux-Toolkit` | Useful Linux commands and learning resources | Planning |

---

## `> github_stats`

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&hide_border=true&bg_color=050816&title_color=00F5FF&icon_color=9D4EDD&text_color=C9D1D9&ring_color=00F5FF" alt="GitHub statistics" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&hide_border=true&bg_color=050816&title_color=00F5FF&text_color=C9D1D9" alt="Most used languages" />

<br/>

<img src="https://streak-stats.demolab.com?user=YOUR_GITHUB_USERNAME&hide_border=true&background=050816&ring=00F5FF&fire=9D4EDD&currStreakLabel=00F5FF&sideLabels=C9D1D9&dates=7D8590&currStreakNum=FFFFFF&sideNums=FFFFFF" alt="GitHub contribution streak" />

</div>

---

## `> connect`

<div align="center">

<a href="https://github.com/YOUR_GITHUB_USERNAME">
  <img src="https://img.shields.io/badge/GitHub-050816?style=for-the-badge&logo=github&logoColor=00F5FF" />
</a>
<!-- Add your other public profile links here when ready. -->

<br/><br/>

<img src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&style=for-the-badge&color=00F5FF&label=PROFILE+SCANS" alt="Profile views" />

</div>

---

<div align="center">

### `ACCESS GRANTED // KEEP LEARNING`

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F5FF,50:111827,100:050816&height=110&section=footer" width="100%" />

<sub>Designed in a cyberpunk terminal aesthetic • No snake animation • Ethical learning only</sub>

</div>
'''
path = "/mnt/data/README.md"
pypandoc.convert_text(readme, "md", format="md", outputfile=path, extra_args=["--standalone"])
print(path)
