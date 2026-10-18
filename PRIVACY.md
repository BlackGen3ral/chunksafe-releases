# Privacidade do ChunkSafe

Atualizado em 18 de outubro de 2026.

O ChunkSafe é um aplicativo Windows para backups de mundos Minecraft Java. O responsável pela distribuição é a conta BlackGen3ral deste repositório.

## Dados no computador

O app lê os mundos que você adiciona e guarda arquivos de backup, caminhos, preferências e registros de atividade no seu computador. Os ZIPs não são cifrados pelo ChunkSafe. Tokens de acesso ao Google são protegidos para sua conta Windows com a criptografia do sistema. A senha Google não é solicitada pelo app.

## Google Drive opcional

Ao conectar sua conta e autorizar, o aplicativo usa a permissão drive.file para criar e consultar seus próprios arquivos no Drive. Os backups e seus metadados são enviados diretamente do computador ao Google, na pasta ChunkSafe Backups. O envio automático é uma escolha nas configurações. O responsável pelo ChunkSafe não recebe seus mundos nem seus tokens em um servidor próprio.

Desconectar remove os tokens locais e tenta revogar a autorização. As cópias no Drive permanecem até você excluí-las pelo Google Drive. Você também pode remover o acesso nas permissões da sua conta Google.

## Atualizações

A verificação de atualizações consulta o GitHub e baixa o instalador quando você solicita. GitHub e Google processam essas conexões conforme suas próprias políticas. O aplicativo não inclui publicidade nem serviço próprio de análise de uso.

## Controle e contato

Você pode pausar backups, desativar o envio automático, desconectar o Drive e apagar suas cópias. A retenção local segue a quantidade configurada no aplicativo. Para dúvidas, use as Issues deste repositório; não publique senhas, tokens, mundos ou registros com informações pessoais.
