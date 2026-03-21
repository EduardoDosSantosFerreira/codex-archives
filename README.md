# 📚 Codex Archives

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.3-7952B3?logo=bootstrap)](https://getbootstrap.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E?logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> **Um repositório completo de comandos, scripts, ferramentas e recursos para profissionais de TI, desenvolvedores e entusiastas de tecnologia.**

## 📖 Sobre o Projeto

Codex Archives é uma central de conhecimento técnico que reúne comandos essenciais para Windows e Linux, ferramentas de desenvolvimento, recursos de segurança, utilitários de sistema e inteligência artificial. O projeto foi desenvolvido para servir como um guia rápido e prático para profissionais de tecnologia.

### ✨ Características Principais

- 🖥️ **Comandos CMD/PowerShell** - Scripts úteis para administração do Windows
- 🐧 **Comandos Linux** - Scripts essenciais para Debian/Ubuntu
- 🔐 **Ativação Windows** - Scripts de ativação para diversas versões
- 🤖 **Inteligência Artificial** - Curadoria das melhores ferramentas de IA
- 🛡️ **Segurança Digital** - Antivírus, VPNs e ferramentas de segurança
- 🛠️ **Utilitários** - Ferramentas essenciais para o dia a dia
- 📦 **Downloads** - Recursos e pacotes úteis
- 🧩 **Extensões** - Extensões essenciais para navegadores

## 🚀 Tecnologias Utilizadas

| Tecnologia | Versão | Finalidade |
|------------|--------|-------------|
| HTML5 | - | Estrutura do site |
| CSS3 | - | Estilização personalizada |
| Bootstrap | 5.3.3 | Layout responsivo e componentes |
| JavaScript | ES6 | Funcionalidades interativas |
| Bootstrap Icons | 1.11.1 | Ícones vetoriais |
| Google Fonts | Poppins | Tipografia moderna |

## 📁 Estrutura do Projeto

```
codex-archives/
│
├── index.html                 # Página principal
├── style.css                  # Estilos customizados
├── src/
│   ├── assets/
│   │   ├── css/
│   │   │   ├── bootstrap.min.css
│   │   │   └── components/
│   │   │       └── navbar.css
│   │   ├── js/
│   │   │   ├── bootstrap.min.js
│   │   │   ├── popper.min.js
│   │   │   └── index.js
│   │   ├── dist/
│   │   │   ├── ultimate_activator.txt
│   │   │   ├── ativação_windows_7.txt
│   │   │   ├── ativação_windows_8.1.txt
│   │   │   ├── ativação_windows_10.txt
│   │   │   ├── ativação_windows_11.txt
│   │   │   ├── ativação_windows_98.txt
│   │   │   ├── ativação_windows_server_2022.txt
│   │   │   ├── office2024.txt
│   │   │   ├── office2022.txt
│   │   │   ├── Pacote Office 2021.rar
│   │   │   ├── Minecraft.rar
│   │   │   └── Minecraft_Mod_Installer_1.21.130+.zip
│   │   └── img/
│   │       ├── angels/
│   │       ├── linux/
│   │       ├── windows/
│   │       └── securaty/
│   └── ...
│
└── README.md                  # Documentação
```

## 🎯 Funcionalidades

### 1. Menu de Navegação
- Menu offcanvas responsivo
- Categorias organizadas por temas
- Links âncora para navegação rápida

### 2. Blocos de Código com Cópia
```javascript
// Botões de copiar para cada comando individual
function copyToClipboard(text, button) {
    navigator.clipboard.writeText(text);
    // Feedback visual de sucesso/erro
}
```

### 3. Seções Principais

| Seção | Conteúdo |
|-------|----------|
| **Comandos CMD/PowerShell** | Gerenciamento do sistema, rede, arquivos, processos |
| **Scripts Debian/Ubuntu** | Comandos APT, rede, systemd, automação |
| **Ativação Windows** | Scripts para Windows 7, 8.1, 10, 11, Server |
| **Distribuições Linux** | Ubuntu, Mint, Arch, Kali, Tails, etc. |
| **Downloads** | Office, Minecraft, utilitários |
| **Ferramentas Dev** | Editores, Git, bancos de dados, testes |
| **IA e Assistentes** | ChatGPT, Gemini, Claude, Copilot, etc. |
| **Segurança Digital** | Antivírus, VPNs, gerenciadores de senhas |
| **Utilitários Sistema** | Limpeza, backup, recuperação, monitoramento |
| **Extensões** | Produtividade, segurança, desenvolvimento |

## 🔧 Instalação e Uso

### Pré-requisitos
- Navegador web moderno (Chrome, Firefox, Edge, Safari)
- Conexão com internet (para CDNs e links externos)

### Instalação Local

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/codex-archives.git

# Navegue até o diretório
cd codex-archives

# Abra o arquivo no navegador
# Windows:
start index.html

# Linux:
xdg-open index.html

# macOS:
open index.html
```

### Servidor Local (Opcional)

```bash
# Usando Python
python -m http.server 8000

# Usando Node.js (live-server)
npx live-server
```

## 📱 Responsividade

O site é totalmente responsivo e otimizado para:
- 💻 Desktops (1200px+)
- 💻 Laptops (992px - 1199px)
- 📱 Tablets (768px - 991px)
- 📱 Smartphones (menos de 768px)

## 🎨 Personalização

### Cores
```css
:root {
    --primary: #007bff;
    --success: #28a745;
    --danger: #dc3545;
    --warning: #ffc107;
    --info: #17a2b8;
    --dark: #343a40;
    --light: #f8f9fa;
}
```

### Fontes
- **Principal**: Poppins (Google Fonts)
- **Código**: Courier New, monospace

## 🤝 Contribuições

Contribuições são bem-vindas! Siga os passos:

1. Faça um Fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

### Diretrizes
- Mantenha o código limpo e organizado
- Adicione comentários quando necessário
- Teste em diferentes navegadores
- Atualize a documentação

## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## 📞 Contato

**Codex Archives** - [@codexarchives](https://twitter.com/codexarchives)

Link do Projeto: [https://github.com/seu-usuario/codex-archives](https://github.com/seu-usuario/codex-archives)

## 🙏 Agradecimentos

- [Bootstrap](https://getbootstrap.com/) - Framework CSS
- [Font Awesome](https://fontawesome.com/) - Ícones (via Bootstrap Icons)
- [Google Fonts](https://fonts.google.com/) - Tipografia
- Todos os contribuidores e mantenedores das ferramentas listadas

## ⚠️ Aviso Legal

Este site é um repositório educacional e informativo. Alguns scripts e ferramentas podem estar sujeitos a termos de uso específicos. Verifique sempre a legalidade e os termos de uso antes de utilizar qualquer recurso disponibilizado.

---

## 📊 Estatísticas do Projeto

| Métrica | Valor |
|---------|-------|
| Comandos CMD | 20+ |
| Comandos Linux | 25+ |
| Ferramentas Listadas | 50+ |
| Distribuições Linux | 15+ |
| IAs/Assistentes | 25+ |
| Extensões | 10+ |
| Downloads Disponíveis | 10+ |

## 🔄 Atualizações Futuras

- [ ] Sistema de busca integrada
- [ ] Modo escuro
- [ ] Favoritos/Bookmarks
- [ ] Seção de tutoriais
- [ ] API para comandos
- [ ] Versão PWA
- [ ] Internacionalização (i18n)

---

⭐ **Se este projeto foi útil para você, considere dar uma estrela no GitHub!**
```

Este README inclui:

1. **Visão geral** do projeto
2. **Tecnologias utilizadas** com badges
3. **Estrutura de diretórios** completa
4. **Funcionalidades** detalhadas
5. **Instruções de instalação** e uso
6. **Personalização** (cores, fontes)
7. **Guia de contribuição**
8. **Licença** e contato
9. **Agradecimentos**
10. **Aviso legal**
11. **Estatísticas** do projeto
12. **Roadmap** de atualizações

O documento é profissional, informativo e segue as melhores práticas de documentação de projetos open-source.