# 🖥️ Automação de Preenchimento de Formulário com Python + Selenium

Este projeto utiliza **Python** e **Selenium** para automatizar o preenchimento de um formulário online.  
O script abre o navegador, acessa uma página de inscrição, preenche os campos necessários e envia o formulário de forma automática.

# ⚠️ Importante sobre coordenadas de tela
Este projeto utiliza a biblioteca PyAutoGUI para simular ações no navegador (como pressionar Enter ou fechar abas). Algumas dessas ações podem depender de coordenadas específicas da tela, como posição do botão de fechar aba ou campos clicáveis.

# 🖥️ Por que isso importa?
Cada monitor tem uma resolução diferente (ex: 1920x1080, 1366x768), e o posicionamento dos elementos na tela pode variar. Por isso, as coordenadas usadas no script podem não funcionar corretamente em outro computador.

# 🛠️ Como ajustar para sua tela
Execute este comando no terminal Python:
import pyautogui
pyautogui.position()
Passe o mouse sobre o local desejado (ex: botão de fechar aba) e anote as coordenadas exibidas.

Substitua no código os valores de pyautogui.click(x, y) com suas coordenadas personalizadas.

💡 Dica: Você pode usar pyautogui.moveTo(x, y) para testar visualmente antes de clicar.
## 🚀 Funcionalidades
- Acessa automaticamente a página alvo.
- Preenche campos de **nome**, **e-mail** e outros dados.
- Simula o clique no botão de envio.
- Pode ser adaptado para diferentes formulários e sites.

## 🛠️ Tecnologias Utilizadas
- [Python](https://www.python.org/)
- [Selenium](https://www.selenium.dev/)
- [WebDriver Manager](https://github.com/SergeyPirogov/webdriver_manager)
- Google Chrome

## 📋 Pré-requisitos
Antes de rodar o projeto, você precisa ter instalado:
- Python 3.8 ou superior
- Google Chrome
- Pip (gerenciador de pacotes do Python)

## 📦 Instalação
Clone este repositório:
```bash
git clone https://github.com/seuusuario/nome-do-repositorio.git


⚠️ Importante sobre coordenadas de tela
Este projeto utiliza a biblioteca PyAutoGUI para simular ações no navegador (como pressionar Enter ou fechar abas). Algumas dessas ações podem depender de coordenadas específicas da tela, como posição do botão de fechar aba ou campos clicáveis.

🖥️ Por que isso importa?
Cada monitor tem uma resolução diferente (ex: 1920x1080, 1366x768), e o posicionamento dos elementos na tela pode variar. Por isso, as coordenadas usadas no script podem não funcionar corretamente em outro computador.

🛠️ Como ajustar para sua tela
Execute este comando no terminal Python:
import pyautogui
pyautogui.position()
Passe o mouse sobre o local desejado (ex: botão de fechar aba) e anote as coordenadas exibidas.

Substitua no código os valores de pyautogui.click(x, y) com suas coordenadas personalizadas.

💡 Dica: Você pode usar pyautogui.moveTo(x, y) para testar visualmente antes de clicar.
