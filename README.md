# ChunkSafe — versões para Windows

Backups automáticos e restauração segura de mundos Minecraft Java do CurseForge, launcher oficial e pastas personalizadas.

## Instalação e atualização

Baixe o instalador Windows x64 em [Releases](https://github.com/BlackGen3ral/chunksafe-releases/releases/latest). Se já usa a versão 1.1.1 ou posterior, abra **Atualizações → Verificar atualizações** no aplicativo. A atualização é instalada após sua confirmação e espera operações em andamento terminarem.

O canal público é `https://github.com/BlackGen3ral/chunksafe-releases/releases/latest/download/`. O app verifica a assinatura do catálogo e o SHA-512 do instalador.

## Novidades da versão 1.6

- Início com cartões mais claros, animações discretas e avisos para backups ausentes, antigos ou com falha.
- Opção **O que guardar?** em cada mundo: escolha incluir configurações, mods ou pacotes de recursos. O padrão continua salvando apenas o mundo.
- Histórico com busca e filtros por mundo, tipo e local.
- Na restauração, pastas extras só são incluídas após escolha explícita. As pastas atuais ficam preservadas ao lado das originais.

O histórico completo das versões está no cartão **Novidades desta versão** do aplicativo, inclusive sem internet.

## Backup e Google Drive

Os backups locais funcionam sem conta e sem internet. Para uma cópia extra, abra **Google Drive → Conectar com Google** e escolha sua conta no navegador. O acesso usa somente arquivos criados pelo ChunkSafe (escopo `drive.file`). O consentimento Google está em produção, separado da verificação de marca.

Salve e feche o Minecraft antes de copiar ou restaurar. Na restauração, o ChunkSafe verifica a cópia, salva o estado atual e preserva a pasta anterior. Os ZIPs dos mundos não são cifrados.

Leia a [Política de Privacidade](PRIVACY.md). O repositório de lançamentos não contém mundos, tokens de usuários nem a chave privada das atualizações. Os EXEs ainda não possuem certificado comercial Authenticode; a assinatura do catálogo é independente do SmartScreen. Não desative o antivírus.

Não afiliado à Mojang, Microsoft, CurseForge ou Google.
