# Requisitos Funcionais (RF)

## RF01 — Autenticação de Usuário
O sistema deve permitir login com usuário e senha.

---

## RF02 — Controle de Acesso por Perfil
O sistema deve diferenciar permissões entre:
- Analista de Dados
- Gestor Hospitalar/Coordenador de Setor

---

## RF03 — Upload de Planilhas
O sistema deve permitir que o analista envie planilhas com dados hospitalares.

---

## RF04 — Processamento Automático de Dados
O sistema deve processar automaticamente os dados enviados nas planilhas.

---

## RF05 — Geração de Indicadores
O sistema deve gerar indicadores hospitalares automaticamente a partir dos dados processados.

---

## RF06 — Visualização de Relatórios
O sistema deve permitir visualizar relatórios dos indicadores.

---

## RF07 — Visualização de Gráficos
O sistema deve exibir gráficos com os indicadores gerados.

---

## RF08 — Filtragem por Período
O sistema deve permitir consultar dados por:
- mês;
- trimestre;
- semestre;
- ano.

---

## RF09 — Navegação por Setores
O sistema deve permitir visualizar indicadores separados por setores hospitalares.

---

## RF10 — Compartilhamento de Indicadores
O sistema deve permitir compartilhar indicadores entre setores autorizados.

---

## RF11 — Armazenamento de Histórico
O sistema deve armazenar os dados e indicadores já processados.

---

# Requisitos Não Funcionais (RNF)

## RNF01 — Usabilidade
O sistema deve possuir uma interface intuitiva e de fácil utilização, permitindo que profissionais hospitalares utilizem as funcionalidades sem necessidade de treinamento avançado.

---

## RNF02 — Facilidade de Aprendizado
O usuário deve conseguir compreender as funcionalidades principais do sistema em pouco tempo.

---

## RNF03 — Desempenho
O sistema deve processar planilhas e gerar indicadores em tempo adequado, evitando lentidão perceptível durante o uso.

---

## RNF04 — Tempo de Resposta
As páginas e relatórios devem ser carregados rapidamente após a solicitação do usuário.

---

## RNF05 — Segurança
O sistema deve impedir acessos não autorizados através de autenticação por login e senha.

---

## RNF06 — Confidencialidade
Os dados hospitalares devem ser acessados apenas por usuários autorizados.

---

## RNF07 — Integridade dos Dados
O sistema deve garantir que os dados enviados nas planilhas não sejam alterados incorretamente durante o processamento com taxa de sucesso superior a 99%.

---

## RNF08 — Disponibilidade
O sistema deve permanecer disponível durante o dia inteiro.

---

## RNF9 — Manutenibilidade
O sistema deve permitir futuras alterações e adição de novas funcionalidades sem necessidade de grandes modificações estruturais.

---

## RNF10 — Escalabilidade
O sistema deve suportar aumento na quantidade de usuários, setores e dados processados.

---

## RNF11 — Portabilidade
O sistema deve funcionar em diferentes navegadores modernos e dispositivos conectados à internet.

---

## RNF12 — Backup de Dados
O sistema deve possuir mecanismos de armazenamento e recuperação de dados para evitar perda de informações importantes.

---

## RNF13 — Auditabilidade
O sistema deve registrar ações importantes realizadas pelos usuários para possibilitar rastreamento e controle.
