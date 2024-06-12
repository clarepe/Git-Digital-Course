- **Configuração por comandos de redes**
+ **ipconfig**: Exibe informações sobre a configuração de rede do sistema.
+ **ipconfig /release**: Libera a configuração de rede atual.
+ **ipconfig /renew**: Renova a configuração de rede atual.
+ **ipconfig /flushdns**: Limpa o cache de DNS do sistema.
+ **ipconfig /displaydns**: Exibe o conteúdo do cache de DNS do sistema.
+ **netsh**: Utilitário de linha de comando para gerenciar e configurar redes
+ **netsh interface ip show config**: Exibe a configuração de rede do sistema.
+ **netsh interface ip set address**: Configura o endereço IP do sistema.
+ **netsh interface ip set dns**: Configura o servidor DNS do sistema.
- **Configuração por comandos de sistema**
+ **systeminfo**: Exibe informações sobre o sistema.
+ **systeminfo /s**: Exibe informações sobre o sistema, incluindo a configuração
+ **msinfo32**: Abre a janela de informações do sistema.
- **Configuração por comandos de segurança**
+ **net localgroup**: Gerencia grupos locais do sistema.
+ **net user**: Gerencia usuários locais do sistema.
+ **netsh advfirewall**: Gerencia o firewall do sistema.
+ **netsh advfirewall set allprofiles state off**: Desativa o firewall em todos os
perfis.
+ **netsh advfirewall set allprofiles state on**: Ativa o firewall em todos os
perfis.
- **Configuração por comandos de arquivos e pastas**
+ **dir**: Exibe a lista de arquivos e pastas do diretório atual.
+ **cd**: Altera o diretório atual.
+ **mkdir**: Cria uma nova pasta.
+ **rmdir**: Exclui uma pasta.
+ **copy**: Copia arquivos.
+ **move**: Move ou renomeia arquivos.
+ **del**: Exclui arquivos.
+ **ren**: Renomeia arquivos.
- **Configuração por comandos de processos e serviços**
+ **tasklist**: Exibe a lista de processos em execução.
+ **taskkill**: Mata um processo em execução.
+ **net start**: Inicia um serviço.
+ **net stop**: Para um serviço.
+ **net pause**: Pausa um serviço.
+ **net continue**: Continua um serviço pausado.
+ **sc**: Gerencia serviços do sistema.
- **Configuração por comandos de backup e restauração**
+ **wbadmin**: Gerencia backups do sistema.
+ **wbadmin start backup**: Inicia um backup do sistema.
+ **wbadmin stop job**: Para um backup em andamento.
+ **wbadmin get versions**: Exibe as versões de backup disponíveis.
+ **wbadmin restore**: Restaura um backup do sistema.
- **Configuração por comandos de sistema de arquivos**
+ **chkdsk**: Verifica e corrige erros no sistema de arquivos.
+ **chkdsk /f**: Verifica e corrige erros no sistema de arquivos
+ **chkdsk /r**: Verifica e corrige erros no sistema de arquivos
+ **chkdsk /x**: Verifica e corrige erros no sistema de arquivos
+ **fsutil**: Gerencia o sistema de arquivos.
+ **fsutil fsinfo**: Exibe informações sobre o sistema de arquivos.


# Comando `ipconfig /flushdns`

O comando `ipconfig /flushdns` é utilizado no Windows para limpar (ou "descarregar") o cache do resolvedor DNS do sistema. Aqui está uma explicação detalhada sobre o que ele faz e quando você pode precisar usá-lo:

## O Que é o Cache DNS?

O cache DNS é um banco de dados temporário mantido pelo sistema operacional que armazena registros de DNS recentes. DNS (Domain Name System) é o sistema que traduz nomes de domínio legíveis, como www.exemplo.com, em endereços IP numéricos que os computadores usam para se comunicar.

## O Que o Comando `ipconfig /flushdns` Faz?

Quando você executa `ipconfig /flushdns`, ele limpa todos os registros armazenados no cache DNS do seu computador. Isso significa que, após executar esse comando, seu sistema terá que consultar novamente o servidor DNS para obter os endereços IP associados aos nomes de domínio que você visitar.

## Quando Usar `ipconfig /flushdns`?

1. **Problemas de Conectividade:**
   - Se você está tendo problemas para acessar determinados sites ou serviços, pode ser útil limpar o cache DNS para garantir que você está obtendo os endereços IP mais recentes.

2. **Alterações de DNS:**
   - Se você fez alterações no servidor DNS (por exemplo, alterando os registros de um domínio) e está vendo resultados antigos, limpar o cache DNS pode forçar seu sistema a pegar as novas informações.

3. **Ataques de DNS Spoofing:**
   - Em casos de segurança, onde o cache DNS pode ter sido comprometido (DNS spoofing), limpar o cache pode ajudar a garantir que seu sistema use registros DNS corretos e confiáveis.

## Como Executar `ipconfig /flushdns`

1. **Abrir o Prompt de Comando:**
   - Pressione `Win + R`, digite `cmd` e pressione Enter, ou procure por "cmd" no menu Iniciar e selecione "Prompt de Comando".

2. **Executar o Comando:**
   - No Prompt de Comando, digite `ipconfig /flushdns` e pressione Enter.

3. **Mensagem de Confirmação:**
   - Você verá uma mensagem confirmando que o cache do resolvedor DNS foi limpo: "Successfully flushed the DNS Resolver Cache".

## Exemplo Prático

Aqui está um exemplo de como executar o comando:

```sh
C:\> ipconfig /flushdns

Configurando DNS do Windows

A cache de resolução DNS foi liberada com sucesso.


Frequência de Uso: Este comando pode ser usado sempre que necessário, mas normalmente não precisa ser executado com frequência.
Impacto: Limpar o cache DNS pode causar um ligeiro atraso na primeira vez que você acessa um domínio, pois o sistema terá que consultar o servidor DNS novamente.

 


