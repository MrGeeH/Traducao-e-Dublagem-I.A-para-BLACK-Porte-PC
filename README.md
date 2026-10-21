# BLACK PT-BR — Tradução + Dublagem para o BLACK PC Port

**Tradução e port de dublagem I.A por: MrGeH**

Patch que deixa o **BLACK** (Criterion Games, 2006) em **português do Brasil**, com **cutscenes dubladas**, no BLACK PC, o port nativo para Windows feito a partir da versão de Xbox (NTSC-U).

Este repositório tem as ferramentas que convertem esse conteúdo para os formatos de dados do Xbox usados pelo port, sem mexer no executável do jogo.

> ⚠️ **Este repositório não contém arquivos do jogo.** Para gerar o patch você precisa da sua própria cópia do BLACK (Xbox NTSC-U para o port e uma ISO de PS2 traduzida/dublada como fonte).

---

## Sumário

- [Recursos](#recursos)
- [Instalação (jogadores)](#instalação-jogadores)
- [Limitações conhecidas](#limitações-conhecidas)
- [Aviso legal](#aviso-legal)

---

## Recursos

- **Textos 100% em português**: menus, objetivos, dicas, black intel e créditos (1.724 textos)
- **Fontes com acentuação completa**: os glifos **Ã/ã** e **Õ/õ** foram adicionados às fontes do Xbox, que não tinham til
- **Cutscenes dubladas**: 9 streams de áudio convertidos de PS-ADPCM (PS2) para o codec do Xbox, com a mesma duração e sincronia
- **Textos adaptados para PC**: mensagens de Memory Card, DualShock e botões do PS2 foram reescritas
- **Saves preservados**: o nome interno do perfil não é traduzido, então os saves existentes continuam funcionando
- **Instalador visual** (`Instalar.bat`): detecta a pasta do jogo, confere a versão, faz backup e permite restaurar o original

---

## Instalação (jogadores)

1. Tenha o **BLACK PC port funcionando** (testado com a versão 0.2.0), com a pasta `game` extraída do disco **Xbox NTSC-U**.
2. Baixe o zip da página de [Releases](../../releases) e extraia ao lado das pastas `game` e `port`.
3. Dê dois cliques em **`Instalar.bat`**, confira a pasta do jogo e clique em **Instalar**.

Para desinstalar, abra o `Instalar.bat` e clique em **Restaurar original**. Os originais ficam em `backup_ptbr`, ao lado da pasta `game`.

---

## Limitações conhecidas

- O menu **PC SETTINGS** e o botão **QUIT**, criados pelo port dentro do `blackrt.dll`, continuam em inglês.
- A **fala do tutorial** (`levels/level_00/SPCH_EN.*`, outro formato de banco) não foi convertida.
- Os **vídeos** são os do Xbox (XMV/WMV2), sem as legendas embutidas das versões de PS2.
- **CredRoll** (música dos créditos) ficou a original: o arquivo veio truncado na ISO dublada.
- Na ISO dublada, o último sub-stream de cada arquivo vem cortado. A parte que falta é preenchida com silêncio.

Contribuições são bem-vindas, principalmente para os itens acima.

---

## Aviso legal

Projeto de fã, gratuito e sem fins lucrativos, sem ligação com a Criterion Games ou a Electronic Arts. **BLACK** é marca registrada da Electronic Arts Inc.

Este repositório contém **apenas código e textos próprios**. Nenhum arquivo do jogo (executável, áudio, fontes, textos originais) é distribuído aqui. Para usar, você precisa da sua própria cópia legal do jogo.

---
Tags
#TraduçãoBLACK #TraduçãoPortBLACK
