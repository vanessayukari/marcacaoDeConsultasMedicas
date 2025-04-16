# 🩺 Marcação de Consultas Médicas

Aplicativo mobile desenvolvido com **React Native** e **Expo**, projetado para facilitar o agendamento, visualização e gerenciamento de consultas médicas. A solução oferece uma interface intuitiva e funcionalidades práticas para pacientes, médicos e administradores.

- RM: 558092
- Vanessa Yukari
  
---

## 📱 Funcionalidades Principais

- ✅ **Agendamento de Consultas**: Permite aos pacientes selecionar data, hora e especialidade médica para marcar consultas.
- 📋 **Listagem de Consultas Agendadas**: Visualize todas as consultas futuras em uma interface clara.
- 🗑️ **Cancelamento de Consultas**: Gerencie e remova consultas com facilidade.
- 📅 **Interface intuitiva com DateTimePicker**: Selecione datas e horários de forma prática.
- 🧠 **Armazenamento Local com AsyncStorage**: Mantém dados no dispositivo para acesso rápido.
- 🎨 **Design estilizado com Styled-Components**: Interface moderna e agradável.

---

## 👤 Perfis de Usuário

O sistema possui 3 perfis principais com permissões distintas:

- 🧑 **Paciente**:
  - Marcar novas consultas.
  - Visualizar suas consultas agendadas.
  - Cancelar suas próprias consultas.

- 👨‍⚕️ **Médico**:
  - Visualizar as consultas marcadas com ele(a).
  - Atualizar o status das consultas (opcional).
  - Ver informações básicas dos pacientes.

- 🧑‍💼 **Administrador**:
  - Acessar todas as consultas do sistema.
  - Gerenciar (criar/editar/deletar) médicos e pacientes.
  - Visualizar estatísticas gerais do sistema (potencial futura melhoria).

---

## 🛠️ Tecnologias Utilizadas

- **React Native**: Framework para desenvolvimento de aplicativos móveis.
- **Expo**: Plataforma para desenvolvimento e build de aplicativos React Native.
- **Styled-Components**: Biblioteca para estilização de componentes.
- **AsyncStorage**: API para armazenamento local de dados.
- **DateTimePicker**: Componente para seleção de data e hora.

