<p align="center">
  <img src="https://img.shields.io/badge/Ayarit%20Sanchez-Portfólio-%231E1E1E?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="Banner Ayarit Sanchez">
  <br>
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical&quote=Transformando%20ideias%20em%20experiências%20digitais%20frontend." alt="Citação Tech">
</p>

# Olá, eu sou a Ayarit! 👋

<p align="left">
  <imgsrc="https://img.shields.io/badge/Status-Estudante%20de%20ADS-%23FFD700?style=flat-square&logo=react" alt="Status">
  <img src="https://img.shields.io/badge/Foco-Desenvolvimento%20Frontend-%232196F3?style=flat-square&logo=html5" alt="Foco">
</p>

Sou apaixonada por tecnologia e design. Atualmente, curso **Análise e Desenvolvimento de Sistemas** e dedico meus estudos a criar interfaces modernas, acessíveis e focadas na experiência do usuário (UX).

---

### 🚀 Sobre Mim

* 🎓 **Educação:** Graduanda em Análise e Desenvolvimento de Sistemas na **UFBRA**.
* 💻 **Interesses:** Desenvolvimento Web (React, JavaScript), UX/UI Design e animações web.
* ⚖️ **Background:** Formação em Direito, que contribui com forte lógica e atenção aos detalhes.
* 🗣️ **Idiomas:** Espanhol (Nativo) e Português (Fluente).
* 📍 **Localização:** Cascavel, PR.

---

### 🛠️ Tecnologias e Ferramentas

| Categoria | Stack |
| :--- | :--- |
| **Frontend** | ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=plastic&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=plastic&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=plastic&logo=javascript&logoColor=black) |
| **Frameworks (Estudando)** | ![React](https://img.shields.io/badge/React-%2320232a.svg?style=plastic&logo=react&logoColor=%2361DAFB) |
| **Ferramentas & Design** | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=plastic&logo=git&logoColor=white) ![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=plastic&logo=visual-studio-code) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=plastic&logo=figma&logoColor=white) |

---

### 📊 Estatísticas do GitHub

![Estatísticas de Ayarit](https://github-readme-stats.vercel.app/api?username=ayarit04&show_icons=true&theme=radical&count_private=true)

![Linguagens mais usadas](https://github-readme-stats.vercel.app/api/top-langs/?username=ayarit04&layout=compact&theme=radical&langs_count=6)

---

### 💻 Destaque de Código (Frontend)

Este é um exemplo simples de como eu estruturo componentes React em meus estudos:

```javascript
// Exemplo de um Botão Interativo em React
import React, { useState } from 'react';

const PortfolioButton = ({ label, link }) => {
  const [hovered, setHovered] = useState(false);

  const buttonStyle = {
    padding: '10px 20px',
    backgroundColor: hovered ? '#2196F3' : '#1E1E1E',
    color: 'white',
    border: 'none',
    borderRadius: '5px',
    cursor: 'pointer',
    transition: 'background-color 0.3s ease',
  };

  return (
    <a href={link} target="_blank" rel="noopener noreferrer">
      <button 
        style={buttonStyle}
        onMouseEnter={() => setHovered(true)}
        onMouseLeave={() => setHovered(false)}
      >
        {label}
      </button>
    </a>
  );
};

export default PortfolioButton;
