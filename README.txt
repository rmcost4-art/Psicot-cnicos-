# Treino Psicotécnicos VMER — PWA V5.0

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

V5.0: ícone alterado para amarelo de alta visibilidade com elementos azuis.

V5.0:
- Ícone amarelo com o nome “Psicotécnicos”.
- No treino de antecipação temporal, após a resposta a zona oculta é revelada.
- A bola amarela/azul mostra a posição real no instante do clique.
- É indicada a distância que ainda faltava para o alvo ou quanto o alvo foi ultrapassado.

V5.0: ícone final aprovado, amarelo, com “Psicotécnicos” e Estrela da Vida azul.

V5.0:
- No treino principal de Antecipação, o toque fica ativo imediatamente quando a bola entra na zona oculta.
- É possível responder antes do reaparecimento real.
- O erro temporal passa a distinguir resposta precoce e tardia.
- Após a resposta, verde mostra o ponto real de reaparecimento e vermelho a previsão.

V5.0:
- Novo módulo “Destreza bimanual”.
- 10 exercícios: toque simultâneo, reação mão correspondente, sequências independentes, manter + responder, seguimento duplo, movimentos espelho, movimentos opostos, inibição cruzada, ritmo bimanual e equilíbrio + resposta.
- Sessão automática de 10 minutos.
- Métricas separadas por mão, assimetria e índice bimanual.
