# NOVA — instalador

A NOVA é uma assistente pessoal por voz para Mac e Windows. Aqui ficam as versões para instalar.

## Mac

1. Baixe o **[NOVA-Mac.zip](https://github.com/marcusvaz35/nova-instalador/releases/latest/download/NOVA-Mac.zip)** e abra o arquivo: aparece a pasta **NOVA**.
2. Dê dois cliques em **Instalar NOVA**.
3. Se o Mac disser que não pode abrir: clique em OK, vá em **Ajustes do Sistema → Privacidade e Segurança**, role até o fim, clique em **Abrir Mesmo Assim** e depois em **Abrir**.
4. Uma janela mostra a instalação. Se pedir a **senha do Mac**, digite e aperte Enter. No fim aparece **Pronto!** e a NOVA liga sozinha. Permita o **microfone** quando o Mac pedir.

<details><summary>Prefere pelo Terminal?</summary>

```bash
/bin/bash -c "$(curl -fsSL https://github.com/marcusvaz35/nova-instalador/releases/latest/download/instalar-mac.sh)"
```
</details>

## Windows

1. Baixe o **[NOVA-instalador.zip](https://github.com/marcusvaz35/nova-instalador/releases/latest/download/NOVA-instalador.zip)**.
2. Clique com o botão direito no arquivo → **Extrair tudo**.
3. Na pasta extraída, dê dois cliques em `instalar-windows.cmd`.

## Depois de instalar

- A NOVA se atualiza sozinha.
- Para conversar com inteligência e voz humanizada, abra o **Painel de controle da NOVA** e coloque as suas chaves de API (OpenAI e, se quiser, ElevenLabs). Cada instalação usa a própria chave e tem a própria memória.
