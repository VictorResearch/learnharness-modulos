# Módulos do LearnHarness

Atualizações assinadas das telas (a interface de cada aba), da lógica e dos prompts do app. O app instalado
(Windows, Mac e celular) lê `indice.json` daqui, baixa o pacote `.lhmod`, confere a assinatura oficial e o hash e só
então troca a versão — sem reinstalar. Um pacote sem a assinatura oficial é recusado.

Publicado com `scripts/modulo-publicar.ts` (no código do app); não edite os arquivos à mão.
