# Changelog - Sistema de Login

Todas as alterações relevantes deste projeto serão documentadas neste arquivo.  
O formato é baseado no padrão [Keep a Changelog](https://keepachangelog.com/pt-BR/1.0.0/).

---

## [1.1] - 2026-08-20

### Adicionado
- Estruturação do projeto no padrão arquitetural **MVC (Model-View-Controller)** com separação clara dos pacotes `view`, `controller` e `model`.
- Diagrama de classes UML para documentação da arquitetura e relacionamento entre componentes.

### Alterado
- Refatoração completa do código-fonte para desacoplar a interface gráfica (Swing) da regra de negócio e modelo de dados.

---

## [1.0] - 2026-08-18

### Adicionado
- Mecanismo de autenticação com validação de credenciais (usuário e senha fixos).
- Mensagens de feedback e alertas visuais utilizando `JOptionPane` (sucesso e erro de autenticação).

### Alterado
- Integração entre os campos da interface visual e a lógica de verificação no backend.

---

## [0.3] - 2026-08-15

### Adicionado
- Inclusão do ícone oficial da aplicação na janela do sistema (`ICONS`).
- Definição do título oficial na barra superior do `JFrame`.
- Aplicação de tema visual via `Look and Feel` para modernização dos componentes Java Swing.

---

## [0.2] - 2026-08-14

### Adicionado
- Campos de entrada para usuário (`JTextField`) e senha (`JPasswordField`).
- Botões de ação da interface (*Entrar* e *Cancelar*).
- Layout estruturado para a tela estática de login em Java Swing.

---

## [0.1] - 2026-08-12

### Adicionado
- Instanciação inicial da janela principal da aplicação via `JFrame`.
- Configurações fundamentais da janela (dimensões, centralização na tela e encerramento do processo ao fechar).
