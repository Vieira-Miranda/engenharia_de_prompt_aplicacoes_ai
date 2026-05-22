# 📌 Desafio Escolhido

Criação de um sistema inteligente de alerta climático e recomendação de vestuário.
O projeto tem como objetivo desenvolver uma aplicação automatizada capaz de consultar informações climáticas em APIs públicas e enviar recomendações personalizadas aos usuários por e-mail, auxiliando na escolha adequada de roupas e acessórios para o dia.

A solução permite que o usuário realize um cadastro simples com cidade e e-mail, recebendo diariamente notificações com temperatura, previsão do tempo e sugestões práticas, como uso de casaco, guarda-chuva ou roupas leves.

---

# 🖥️ Protótipo

## Funcionalidades Principais

✅ Cadastro de usuários com cidade e e-mail
✅ Integração com API climática (OpenWeatherMap)
✅ Consulta automática da previsão do tempo
✅ Envio automatizado de e-mails personalizados
✅ Sistema de recomendações de vestuário baseado na temperatura
✅ Interface responsiva e intuitiva
✅ Fluxos automatizados utilizando Bubble IA

---

## Como Funciona

### Cadastro do Usuário

O usuário informa sua cidade e endereço de e-mail na plataforma.

### Consulta Climática

Todos os dias, o sistema acessa automaticamente uma API pública de clima para verificar as condições meteorológicas da cidade cadastrada.

### Processamento das Informações

A aplicação interpreta os dados recebidos, como temperatura, chuva e sensação térmica.

### Geração de Recomendações

Com base nas condições climáticas, o sistema cria mensagens personalizadas, por exemplo:

> “Hoje vai chover e fazer 15°C em São Paulo. Não esqueça o guarda-chuva e o casaco!”

### Envio Automatizado

As notificações são enviadas automaticamente para o e-mail do usuário através dos workflows da plataforma Bubble.

---

# ⚙️ Plataforma Utilizada

## Plataforma: Bubble IA

### Justificativa da Escolha

🎯 Facilidade de utilização
⚡ Desenvolvimento rápido de protótipos
🔧 Interface visual intuitiva
📦 Integração simplificada com APIs externas
🤖 Automação de processos sem necessidade de programação avançada
📱 Desenvolvimento responsivo utilizando componentes visuais

O Bubble foi escolhido principalmente pela sua capacidade de acelerar o desenvolvimento do projeto através de ferramentas low-code/no-code, permitindo focar mais na lógica da aplicação e menos na infraestrutura técnica.

---

# 🤖 Ferramentas Utilizadas

## Bubble IA

🔧 Desenvolvimento visual da aplicação
⚙️ Configuração dos workflows automatizados
📦 Integração com APIs externas
📧 Automação de envio de e-mails

## OpenWeatherMap API

🌦️ Fornecimento de dados meteorológicos em tempo real
📊 Consulta de temperatura, chuva e clima
🌍 Informações climáticas baseadas na cidade cadastrada

---

# ✅ Vantagens Identificadas

## 1. Protótipo Rápido

Aplicação no projeto:
O Bubble permitiu criar rapidamente telas funcionais, banco de dados e fluxos automatizados sem necessidade de desenvolver toda a estrutura manualmente. Em poucos minutos já era possível testar o sistema online.

---

## 2. Integração Simples

Aplicação no projeto:
A conexão com a API OpenWeatherMap foi realizada utilizando o API Connector do Bubble, eliminando a necessidade de programar requisições HTTP complexas manualmente.

---

## 3. Automação de Processos

Aplicação no projeto:
Toda a lógica de envio automático de mensagens e recomendações foi configurada visualmente nos workflows da plataforma, simplificando tarefas que normalmente exigiriam servidores, CRON jobs e serviços externos.

---

# ⚠️ Limitações Encontradas

## 1. Customização Limitada

Aplicação no projeto:
Embora o Bubble ofereça muitos recursos visuais, funcionalidades extremamente personalizadas e animações avançadas exigiriam integração com códigos externos, reduzindo a proposta no-code.

---

## 2. Dependência da Plataforma

Aplicação no projeto:
O funcionamento completo do sistema depende diretamente da infraestrutura do Bubble. Caso a plataforma apresente instabilidades, o serviço de alertas deixa de funcionar temporariamente.

---

## 3. Risco de Lock-in Tecnológico

Aplicação no projeto:
A lógica criada dentro do Bubble não pode ser facilmente exportada para linguagens tradicionais como React ou Node.js, dificultando uma futura migração para outra tecnologia.

---

# 📚 Reflexão Crítica

## Como Lidamos com as Limitações

### Problema: Compartilhamento limitado na versão gratuita

✅ Solução criativa:
O grupo centralizou o desenvolvimento principal em um computador compartilhado e os demais integrantes ficaram responsáveis por tarefas complementares, mantendo a colaboração ativa.

---

### Problema: Responsividade da interface

✅ Solução criativa:
Foram realizados diversos ajustes nos componentes visuais do Bubble para garantir melhor adaptação em diferentes tamanhos de tela.

---

### Problema: Limitações de customização

✅ Solução proposta:
O grupo optou por priorizar funcionalidades essenciais e usabilidade, evitando recursos visuais excessivamente complexos que demandariam código externo.

---

# 👥 Colaboração

## Responsabilidades e Organização

Nosso grupo foi composto por 3 integrantes.

### Organização do Trabalho

📌 Primeiro, realizamos uma discussão coletiva para definir possíveis ideias de protótipos.

📌 Em seguida, escolhemos em conjunto o projeto final do sistema de alerta climático.

📌 Depois, dividimos as tarefas da seguinte maneira:

* Um integrante ficou responsável pela organização do roteiro;
* Outro desenvolveu a lógica principal do projeto;
* O terceiro realizou ajustes finais e refinamento visual.

📌 Por fim, todos os integrantes participaram da elaboração do documento final em PDF.

---

## Como Nos Organizamos

🤝 Trabalho colaborativo entre todos os integrantes
📊 Divisão clara de responsabilidades
🔄 Desenvolvimento simultâneo de partes complementares
📱 Testes coletivos da interface e funcionalidades
📝 Revisão conjunta da documentação final

---

# 📝 Registro da Aula

📅 Data: **11/05/2026**

📚 Atividade: Discussão crítica + mini-projeto de aplicação

🏫 Local: Laboratório de informática / Quadro branco

👩‍🏫 Professora: **Kadidja Valéria**

---

# 🚀 Próximos Passos

## Melhorias Futuras

✅ Implementar notificações via WhatsApp e SMS
✅ Adicionar recomendações mais detalhadas de vestuário
✅ Criar painel com histórico climático do usuário
✅ Melhorar a personalização visual da interface
✅ Implementar autenticação mais segura

---

## Evoluções para o Projeto Final

🚀 Expansão para múltiplas cidades por usuário
📊 Uso de inteligência artificial para recomendações mais precisas
🌎 Integração com mapas climáticos em tempo real
📱 Desenvolvimento de versão mobile
☁️ Migração futura para infraestrutura própria visando maior escalabilidade
