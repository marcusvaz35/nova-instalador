# NOVA — instalador

A NOVA é uma assistente pessoal por voz para Mac e Windows. Aqui ficam as versões para instalar.

## Mac — instalar com um comando

1. Abra o **Terminal**: aperte **⌘ Command + Espaço**, digite **Terminal** e aperte Enter.
2. Copie o comando abaixo, cole no Terminal (**⌘ Command + V**) e aperte **Enter**:

```bash
/bin/bash -c "$(curl -fsSL https://github.com/marcusvaz35/nova-instalador/releases/latest/download/instalar-mac.sh)"
```

3. Se pedir, digite a **senha do Mac** (ela não aparece enquanto você digita) e aperte Enter.
4. Espere terminar (de 5 a 20 minutos na primeira vez). A NOVA liga sozinha e se apresenta. Permita o **microfone** quando o Mac pedir.

## Windows

1. Baixe o **[NOVA-instalador.zip](https://github.com/marcusvaz35/nova-instalador/releases/latest/download/NOVA-instalador.zip)**.
2. Clique com o botão direito no arquivo → **Extrair tudo**.
3. Na pasta extraída, dê dois cliques em `instalar-windows.cmd`.

## Depois de instalar

- A NOVA se atualiza sozinha.
- Para conversar com inteligência e voz humanizada, abra o **Painel de controle da NOVA** e coloque as suas chaves de API (OpenAI e, se quiser, ElevenLabs). Cada instalação usa a própria chave e tem a própria memória.
