#  📌 Sobre o projeto
#  Este é o frontend da aplicação CIPA, desenvolvido em Angular.
#  Ele fornece a interface para gerenciamento de eleições, cadastramento de candidatos, geração de senhas de votação, processo de votação e visualização da        #   apuração.
#  
#  🚀 Funcionalidades
#  Interface administrativa para eleições e candidatos
#  
#  Geração e impressão de senhas de votação
#  
#  Simulação de urna eletrônica para votação
#  
#  Apuração em tempo real
#  
#  Visualização das fotos dos candidatos
#  
#  📋 Pré-requisitos
#  Antes de iniciar, você precisa ter instalado:
#  
#  Node.js (versão LTS recomendada)
#  
#  NPM
#  
#  Angular CLI (se não quiser usar npx)
#  
#  bash
#  npm install -g @angular/cli
#  ⚙️ Configuração
#  Clonar o repositório
#  
#  bash
#  git clone <seu_repositorio_frontend>
#  cd frontend
#  Instalar dependências
#  
#  bash
#  npm install
#  Configurar URL da API
#  No arquivo src/app/services/cipa.ts:
#  
#  ts
#  private apiUrl = 'http://SEU_IP_LOCAL:3000/api';
#  E nas variáveis para imagens (ex: backendUrl nos componentes):
#  
#  ts
#  backendUrl = 'http://SEU_IP_LOCAL:3000';
#  ▶️ Executar o frontend
#  Para rodar e permitir acesso de outros dispositivos na rede:
#  
#  bash
#  ng serve --host 0.0.0.0 --port 4200
#  O frontend ficará disponível em:
#  
#  text
#  http://localhost:4200      (apenas no seu PC)
#  http://SEU_IP_LOCAL:4200   (qualquer dispositivo da sua rede)
# ✅ Dica final: Coloque o IP da sua máquina no lugar de SEU_IP_LOCAL para que outros dispositivos da rede (celulares, tablets, outros PCs) possam usar a aplicação #   completa, incluindo exibição das imagens.#
#
#
####################################################################################################################################################################
