# prompts-cmd-powershell


**CMD - [ arp - a ]** O comando irá exibir a tabela ARP do seu computador, que contém os endereços IP e MAC dos dispositivos que estão conectados à rede local.

  ![](https://github.com/Fabx01/prompts-cmd-powershell/blob/main/cmd%20(arp%20-a).png)
  
  -------------------------------------------------------------------------
  
 **CMD - [ ipconfig ]** comando usado para exibir informações de configuração de rede do computador local. Ele permite que os usuários visualizem informações como endereço IP, máscara de sub-rede, gateway padrão e outros detalhes de rede.  
 
 Ao executar o comando "ipconfig" sem nenhum argumento adicional, ele exibe as informações de configuração de todos os adaptadores de rede disponíveis no computador. Alguns dos argumentos mais comuns usados com o comando "ipconfig" incluem:

* **/all:** exibe informações detalhadas sobre todos os adaptadores de rede, incluindo os que estão desativados.
* **/release:** libera o endereço IP atualmente atribuído ao adaptador de rede.
* **/renew:** solicita um novo endereço IP ao servidor DHCP (Dynamic Host Configuration Protocol).
* **/flushdns:** limpa o cache do DNS (Domain Name System) do computador.

Em geral, o comando "ipconfig" é uma ferramenta útil para solucionar problemas de rede, como problemas de conectividade, endereços IP conflitantes ou problemas de DNS.
  
 ![](https://github.com/Fabx01/prompts-cmd-powershell/blob/main/IPCONFIG.png)
 
 ------------------------------------------------------------------

 **POWER SHELL - Adicionar variavel de ambiente temporaria**
 
 * adicionar
 ```javascript
 $env:Path += ";E:\partables\node"
```
* visualizar
```javascript
echo $env:Path

```
-------------------------------------------------------------------------

**CMD - [ set ] criar uma usuario temporario 

* definir uma nova localização para o perfil do usuário temporario (o sistema operacional usará o caminho especificado para armazenar e recuperar configurações de usuário e arquivos relacionados ao perfil do usuário.

```
 C:\usuario>set userprofile=c:\novoprofile
```
* a variável de ambiente "homepath" será atualizada para o novo caminho "\novoprofile"
```
 C:\usuario>set homepath=\novoprofile
```
* Para adicionar um novo caminho à variável "path" (de ambiente) (  "path", é usada pelo sistema operacional para localizar arquivos executáveis)
```
 set path=%path%;C:\novo\caminho set path
 
 set path=%path%;E:\partables\node ( adicionar a variavel do node que esta no pendrive )
```
* Exibe os caminhos da variável "path" (de ambiente)
```
  set path
```

--------------------------------------------------------------------

**CMD [ dir ] listar os arquivos e pastas dentro do diretorio**

```
 C:\>dir
 O volume na unidade C é Windows
 O Número de Série do Volume é 83BC-C380

 Pasta de C:\

11/04/2023  11:42    <DIR>          Intel
07/12/2019  06:14    <DIR>          PerfLogs
23/02/2023  16:22    <DIR>          Program Files
13/01/2022  18:37    <DIR>          Program Files (x86)
02/05/2023  16:06    <DIR>          teste
11/04/2023  11:42    <DIR>          Users
01/02/2023  17:01    <DIR>          Windows
               0 arquivo(s)              0 bytes
               7 pasta(s)   176.297.418.752 bytes disponíveis

```







