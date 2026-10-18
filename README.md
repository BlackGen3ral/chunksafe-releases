# SaveBlock — versões para Windows

Anteriormente chamado ChunkSafe. Backups automáticos e restauração segura de mundos Minecraft Java do CurseForge, launcher oficial e pastas personalizadas.

## Instalação e atualização

Baixe o instalador Windows x64 em [Releases](https://github.com/BlackGen3ral/chunksafe-releases/releases/latest). Se já usa a versão 1.1.1 ou posterior, abra **Atualizações → Verificar atualizações** no aplicativo. A atualização é instalada após sua confirmação e espera operações em andamento terminarem.

O canal público é `https://github.com/BlackGen3ral/chunksafe-releases/releases/latest/download/`. O app verifica a assinatura do catálogo e o SHA-512 do instalador.

## Novidades da versão 1.7

- Novo nome SaveBlock no aplicativo, instalador e atalhos.
- Google Drive organizado em **SaveBlock**, com uma pasta para cada mundo e cópias identificadas pela data.
- Backups antigos do app são organizados na próxima sincronização, sem reenviar os ZIPs.
- Atualização aproveita o perfil, os backups e a conexão Google existentes.

Para organizar suas cópias após atualizar, abra **Google Drive → Enviar backups agora**.

O histórico completo das versões está no cartão **Novidades desta versão** do aplicativo, inclusive sem internet.

## Backup e Google Drive

Os backups locais funcionam sem conta e sem internet. Para uma cópia extra, abra **Google Drive → Conectar com Google** e escolha sua conta no navegador. O acesso usa somente arquivos criados pelo SaveBlock (escopo `drive.file`). O consentimento Google está em produção, separado da verificação de marca.

Salve e feche o Minecraft antes de copiar ou restaurar. Na restauração, o SaveBlock verifica a cópia, salva o estado atual e preserva a pasta anterior. Os ZIPs dos mundos não são cifrados.

Leia a [Política de Privacidade](PRIVACY.md). O repositório de lançamentos não contém mundos, tokens de usuários nem a chave privada das atualizações. Os EXEs ainda não possuem certificado comercial Authenticode; a assinatura do catálogo é independente do SmartScreen. Não desative o antivírus.

Não afiliado à Mojang, Microsoft, CurseForge ou Google.
