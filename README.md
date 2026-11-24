# 🔐 Lockbox

<div align="center">
  <img src="https://img.shields.io/badge/language-C-blue.svg" alt="Language">
  <img src="https://img.shields.io/badge/GUI-GTK+3-green.svg" alt="GUI">
  <img src="https://img.shields.io/badge/database-SQLite-orange.svg" alt="Database">
  <img src="https://img.shields.io/badge/crypto-libsodium-red.svg" alt="Crypto">
  <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg" alt="License">
</div>

## 📌 Descrição

Um aplicativo de desktop seguro para gerenciamento de notas, que utiliza criptografia para proteger os dados do usuário.

Este projeto é uma aplicação de desktop desenvolvida em **C**, que combina:  
- Uma interface de usuário elegante e nativa com **GTK+ 3**;  
- Um sistema de banco de dados leve e eficiente com **SQLite**;  
- Um forte sistema de criptografia com a biblioteca **libsodium**.  

---

## 📸 Screenshots da Aplicação


### Login 
![Login](captura/captura1.png)
*Janela de login*

### Tela Principal
![Tela Principal](captura/captura2.png)
*Interface principal do aplicativo*



### Visualizando Nota
![Visualizar Nota](captura/captura4.png)
*Interface de leitura e edição de notas existentes*

---



## 🚀 Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| **C/C++** | Linguagem de programação principal |
| **GTK+ 3** | Interface gráfica nativa |
| **SQLite** | Sistema de banco de dados leve |
| **libsodium** | Biblioteca de criptografia |
| **CMake** | Sistema de build |

---

## 📦 Pré-requisitos

Para compilar e executar o projeto, você precisará ter as seguintes bibliotecas instaladas no seu sistema:

```
- CMake  
- GTK+ 3 (libgtk-3-dev)  
- SQLite3 (libsqlite3-dev)  
- libsodium (libsodium-dev)  
```

---

## 🛠 Instalação das Dependências

### Debian/Ubuntu
```bash
sudo apt-get install libgtk-3-dev libsqlite3-dev libsodium-dev cmake make
```

### Fedora
```bash
sudo dnf install gtk3-devel sqlite-devel libsodium-devel cmake make
```

### Arch Linux
```bash
sudo pacman -S gtk3 sqlite libsodium cmake make
```

---

## ⚙️ Compilação

O projeto usa o **CMake** para gerenciar a compilação.

### Passo 1: Clone o repositório
```bash
git clone https://github.com/Daniel-X2/cofre_pessoal.git
cd cofre_pessoal
```

### Passo 2: Crie o diretório de build
```bash
mkdir build
cd build
```

### Passo 3: Configure o projeto
```bash
cmake ..
```

### Passo 4: Compile o projeto
```bash
make
```

---

## ▶️ Como Executar

Após a compilação, o executável estará no diretório `build`.

```bash
./build/meu_app
```

---

## 🗂️ Estrutura do Projeto

```
cofre_pessoal/
├── src/                    # Código fonte
├── include/               # Arquivos de cabeçalho
├── screenshots/           # Capturas de tela da aplicação
├── build/                 # Arquivos de compilação
├── CMakeLists.txt         # Configuração do CMake
├── LICENSE               # Arquivo de licença
└── README.md             # Este arquivo
```

---

## 🔐 Recursos de Segurança

- ✅ **Criptografia forte** com libsodium
- ✅ **Armazenamento local seguro** com SQLite
- ✅ **Interface nativa** sem dependências web
- ✅ **Dados protegidos** contra acesso não autorizado
- ✅ **Performance otimizada** desenvolvido em C

---

## 🤝 Contribuição

Contribuições são bem-vindas!

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b minha-feature`)
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`)
4. Push para a branch (`git push origin minha-feature`)
5. Abra um Pull Request

### Como contribuir:
- Abra uma *issue* para discutir mudanças propostas
- Ou envie um *pull request* com suas alterações
- Reporte bugs e problemas encontrados
- Sugira melhorias na documentação

---

## 📄 Licença

Este projeto está licenciado sob a Licença **MIT**.
Veja o arquivo [`LICENSE`](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

<div align="center">
  <strong>Daniel-X2</strong>
  <br>
  <em>Desenvolvedor Back-end & Entusiasta de Segurança</em>
</div>

### 🌐 Conecte-se comigo:

<div align="center">
  <a href="https://github.com/Daniel-X2" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://linkedin.com/in/daniel-da-silva-32814636b" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</div>

---

<div align="center">
  <strong>⭐ Se este projeto foi útil, considere dar uma estrela no repositório! ⭐</strong>
</div>
