# Treino Psicotécnicos VMER — PWA V5.6

## Publicar gratuitamente no GitHub Pages
1. Crie um repositório no GitHub (por exemplo `vmer-treino`).
2. Coloque na raiz do repositório todos os ficheiros desta pasta:
   - index.html
   - manifest.webmanifest
   - sw.js
   - icon-192.png
   - icon-512.png
3. No GitHub: Settings → Pages.
4. Em Build and deployment, escolha **Deploy from a branch**.
5. Selecione `main` e `/ (root)` e guarde.
6. Abra no Safari do iPhone/iPad o endereço HTTPS fornecido pelo GitHub Pages.
7. Safari → Partilhar → **Adicionar ao ecrã principal**.
8. Abra a aplicação pelo novo ícone e, no módulo Movimento, toque **Ativar sensores de movimento**.

## Offline
Depois de a app ter sido aberta pelo menos uma vez com internet, o Service Worker guarda os ficheiros essenciais em cache. A aplicação pode então abrir sem ligação à internet.

Nota: a disponibilidade de DeviceOrientation/giroscópio depende das permissões e políticas da versão do iOS/iPadOS/Safari.

V5.6: ícone alterado para amarelo de alta visibilidade com elementos azuis.

V5.6:
- Ícone amarelo com o nome “Psicotécnicos”.
- No treino de antecipação temporal, após a resposta a zona oculta é revelada.
- A bola amarela/azul mostra a posição real no instante do clique.
- É indicada a distância que ainda faltava para o alvo ou quanto o alvo foi ultrapassado.

V5.6: ícone final aprovado, amarelo, com “Psicotécnicos” e Estrela da Vida azul.

V5.6:
- No treino principal de Antecipação, o toque fica ativo imediatamente quando a bola entra na zona oculta.
- É possível responder antes do reaparecimento real.
- O erro temporal passa a distinguir resposta precoce e tardia.
- Após a resposta, verde mostra o ponto real de reaparecimento e vermelho a previsão.

V5.6:
- Novo módulo “Destreza bimanual”.
- 10 exercícios: toque simultâneo, reação mão correspondente, sequências independentes, manter + responder, seguimento duplo, movimentos espelho, movimentos opostos, inibição cruzada, ritmo bimanual e equilíbrio + resposta.
- Sessão automática de 10 minutos.
- Métricas separadas por mão, assimetria e índice bimanual.

V5.6:
- Corrigido o menu superior.
- Adicionados os botões visíveis para Treino temporal, Destreza bimanual e Movimento.
- Menu horizontal otimizado para deslizar no iPhone/iPad.

V5.6 — Destreza bimanual dinâmica
- Consola contínua com duas mãos.
- Modos combinados e misto adaptativo.
- Controlo + reação + inibição + mudança de regra.
- Sessão de 90 s e sessão mista de 10 min.

V5.6:
- Aumentada significativamente a velocidade dos alvos na destreza bimanual.
- Modo precisão ainda mais rápido.
- Dificuldade adaptativa progride mais depressa.
- Estímulos de reação aparecem com intervalos menores.
- No modo misto, as regras mudam com maior frequência.

V5.6 — Dificuldade adaptativa global
- Criado perfil persistente de dificuldade 1–10 por módulo.
- Antecipação: velocidade, inclinação e extensão da oclusão adaptam-se.
- Temporal: dificuldade inicial e evolução adaptadas.
- Reação: janela de resposta e proporção de estímulos seletivos adaptadas.
- Atenção: grelha, densidade e semelhança dos distratores adaptadas.
- Pressão: intervalos progressivamente mais curtos.
- Periferia: frequência de estímulo lateral e tempos disponíveis adaptados.
- Stroop: maior incongruência e tempo de resposta menor.
- Memória: nível inicial, exposição e ritmo adaptados.
- Coordenação: alvo acelera conforme o nível.
- Destreza bimanual: dificuldade inicial e progressão ligadas ao perfil.
- Giroscópio: limiar e avaliação adaptados.
- A dificuldade sobe com desempenho consistente >=84 e reduz se o desempenho médio cair abaixo de 55.
- A simulação permanece padronizada para permitir comparação entre sessões.
- Personalidade permanece não adaptativa para evitar condicionar respostas.

V5.6 — Condução psicomotora com giroscópio
- Módulo de giroscópio totalmente substituído.
- Carro controlado pela inclinação lateral do iPad.
- Estrada curva e dinâmica, com avaliação contínua de permanência dentro da faixa.
- Dupla tarefa: símbolos externos surgem durante a condução e exigem resposta por toque.
- Velocidade aumenta progressivamente durante toda a sessão.
- Dificuldade inicial e aceleração dependem do nível adaptativo.
- Mede percentagem de tempo na estrada, número de saídas, acertos aos estímulos, erros, tempo de reação e índice global.
- Sessão de 90 segundos e sessão de 5 minutos.

V5.6 — Correção crítica: removido bloco JavaScript duplicado que impedia os botões da aplicação de responder.
