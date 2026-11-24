# Loja do Marcone para o Umbrel

Loja comunitária do [umbrelOS](https://umbrel.com) com um app:

- **Painel de Controle**: vigia as mineradoras de Bitcoin (LuxOS, AxeOS, pools e aluguéis) e traz a **Leda**, uma assistente de voz. Código: [Painel-de-Controle](https://github.com/marconecerqueira/Painel-de-Controle).

## Como instalar
1. No Umbrel, abra a **App Store**, toque nos **⋯** (canto de cima) e escolha **Community App Stores**.
2. Cole `https://github.com/marconecerqueira/umbrel-loja` e toque em **Add**.
3. Abra a **Marcone App Store** e instale o **Painel de Controle**.
4. Na primeira vez, o app cria `config.toml` na pasta de dados (`~/umbrel/app-data/marcone-painel/data/`). Preencha com as suas máquinas (veja o `config.example.toml` do Painel) e reinicie o app.

Os seus endereços, chaves e senhas ficam só no `config.toml` do seu Umbrel. Nunca vão para a imagem nem para o GitHub.
