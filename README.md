# Projeto Final: MeuPrimeiroProjeto
**Curso:** Residência em TIC 29 | Trilha: Web 3.0.
**Aluna:** Gisele Vigato

## 📝 Descrição do Projeto
Este projeto consiste na criação de um ambiente imersivo e temático em Realidade Virtual (XR) utilizando o Unity 6. O objetivo foi desenvolver um cenário de deserto/oásis tridimensional que seja totalmente navegável, aplicando conceitos práticos de importação de modelos 3D externos, otimização de polígonos (Low Poly) e conversão de materiais para o pipeline gráfico moderno.

## 📦 Elementos da Cena
O cenário foi estruturado de forma lógica e coerente para ambientar um oásis isolado no deserto, contando com os seguintes elementos integrados:
1. **Terreno/Chão:** Um plano configurado com uma textura detalhada de dunas e transição de areia.
2. **Oásis (Água):** Um pequeno poço/lagoa de água adicionado estrategicamente na base do cenário, consolidando o conceito do bioma.
3. **Vegetação Nativa:** Palmeiras tropicais altas e cactos desérticos compondo a flora ao redor do acampamento.
4. **Estrutura Principal:** Uma tenda de viagem/acampamento rústica detalhada no centro da cena.
5. **Fauna (Animais):** Inclusão de dois camelos característicos do deserto, um tigre posicionado para proteção da área e um cão de guarda.
6. **Composição de Props:** Conjunto de pedras (stones) espalhadas de forma orgânica para dar realismo e profundidade ao solo.
7. **XR Camera Rig:** Sistema de câmera VR [BuildingBlock] configurado para suporte nativo a headsets Meta Quest.

## 🛠️ Configuração Técnica
* **Engine:** Unity 6
* **Pipeline Gráfico:** Universal Render Pipeline (URP) para garantir alta performance e correção de materiais (resolução de shaders incompatíveis).
* **SDK Integrado:** Meta XR SDK / XR Plugin Management
* **Plataforma Target:** Android (Meta Quest)
* **Navegação de Teste:** Movimentação configurada para funcionamento direto no PC via teclado/mouse, cumprindo o requisito de testes no Unity Editor sem dependência obrigatória do óculos de VR para a validação inicial.

## 🚀 Como Executar
1. Abra o Unity Hub e adicione este projeto.
2. Certifique-se de que o projeto está aberto utilizando o Unity 6.
3. Abra a cena principal localizada na pasta de Scenes do projeto.
4. Clique no botão **Play** no topo do editor para navegar e inspecionar o oásis usando os controles de PC (Teclado/Mouse).
