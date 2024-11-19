
# **Coffee Code Scanner**

### 🚀 **Descrição**
**Coffee Code Scanner** é um aplicativo mobile para Android que permite escanear e gerar QR Codes e Códigos de Barras. Criado para ser simples, eficiente e acessível, o app é ideal para usuários que desejam armazenar, compartilhar ou consumir informações rapidamente.

---

### 🛠 **Tecnologias Utilizadas**
O projeto foi desenvolvido utilizando **Flutter** e gerencia estados reativos com **MobX**. Abaixo, os principais pacotes utilizados:

- `flutter_mobx: ^2.2.1+1` - Integração do MobX com Flutter.
- `mobx: ^2.4.0` - Biblioteca para gerenciamento de estado reativo.
- `mobx_codegen: ^2.6.2` - Gerador de código para reatividade com MobX.
- `qr_code_scanner: ^1.0.1` - Biblioteca para escanear QR Codes.
- `pretty_qr_code: ^3.3.0` - Ferramenta para geração de QR Codes estilizados.

---

### 📱 **Funcionalidades**
1. **Escanear QR Codes e Códigos de Barras**:
   - Leitura instantânea utilizando a câmera do dispositivo.
   - Compatível com diversos formatos de códigos.

2. **Gerar QR Codes**:
   - Criação de QR Codes personalizados a partir de textos, links ou números de telefone.
   - Opções de customização de cor e tamanho.

3. **Histórico de Códigos**:
   - Registro das leituras e criações para consulta posterior.
   - Opções de gerenciamento do histórico.

4. **Compartilhamento**:
   - Compartilhe os códigos diretamente para redes sociais ou outros apps.

---

### 🎨 **Design**
O aplicativo segue uma interface simples e intuitiva, garantindo uma navegação fluida entre as telas:

- **Tela Inicial**: Menu principal com as opções de escanear ou gerar.
- **Tela de Escaneamento**: Leitura rápida de códigos com exibição de resultados.
- **Tela de Geração**: Personalização e criação de QR Codes.
- **Tela de Histórico**: Consulta de códigos gerados ou escaneados anteriormente.

---

### 🌟 **Como Rodar o Projeto**

#### Pré-requisitos:
- Flutter SDK instalado ([Guia oficial](https://flutter.dev/docs/get-started/install)). Versão do Flutter nessa última versão do App: Flutter 3.22.0
- Android Studio ou VS Code configurado.

#### Passos:
1. Clone o repositório:
   ```bash
   git clone https://github.com/pauloRodri29/coffee_code_scanner.git
   cd coffee_code_scanner
   ```
2. Instale as dependências:
   ```bash
   flutter pub get
   ```
3. Conecte um dispositivo Android ou inicie um emulador.
4. Rode o app:
   ```bash
   flutter run
   ```

---

### 🛠 **Roadmap do Projeto**
- **Versão 1.0**:
  - Escaneamento e geração de QR Codes/Códigos de Barras.
  - Histórico de códigos.
- **Versão 1.1**:
  - Customização avançada de QR Codes.
- **Versão 2.0**:
  - Suporte offline para geração de códigos.
  - Modo claro/escuro.

---

### 📩 **Contato**
Para mais informações ou contribuições:

- **Email**: rodriguesjp29@gmail.com  
- **Portfólio**: [paulorodrigues29.pythonanywhere.com](https://paulorodrigues29.pythonanywhere.com/)

---

### 📄 **Licença**
Este projeto está licenciado sob a [MIT License](https://opensource.org/licenses/MIT).