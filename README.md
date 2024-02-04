# Configuração do YAML para Instalação Automática 🚀

**Fonte** -> [Winget Configure](https://learn.microsoft.com/en-us/windows/package-manager/configuration/)

Este script YAML utiliza o **Winget** para configurar automaticamente seu ambiente de desenvolvimento. Aqui estão os principais objetivos e como usar:

## Objetivos 🎯

1. Verificar a versão mínima do sistema operacional.
2. Habilitar o Modo Desenvolvedor.
3. Instalar pacotes essenciais usando o **winget**:
   - Git
   - Bitwarden
   - Notion
   - Rider
   - Postman
   - Dev Home
   - Zoom
   - Acrobat Reader
   - Oh My Posh
   - PowerShell
   - WhatsApp
   - SQL Server Management Studio
   - .NET 6 SDK
   - PowerToys
   - Azure CLI
   - Visual Studio Code
   - Visual Studio 2022 Enterprise (Pré-requisito para as cargas de trabalho do VS)

## Como Usar 🛠️

1. **Clone este repositório:**

   ```powershell
   git clone https://github.com/fazedordecodigo/ConfigInit.git
   cd ConfigInit
   ```

2. **Execute o Script:**
   - Certifique-se de ter o **Winget** instalado.
   - Use o script YAML fornecido:

     ```powershell
     winget configure configuration.dsc.yaml
     ```

3. **Aproveite seu Ambiente de Desenvolvimento!** 🚀

Divirta-se codificando! ✨
