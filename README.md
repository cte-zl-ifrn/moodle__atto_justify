# moodle_atto_justify

Módulo para adicionar função de justificar texto no editor Atto para o Moodle.

As etapas a seguir devem ajudá-lo a começar a instalação do módulo:
 
 * Descompacte o arquivo moodle_atto_justify e leia atentamente este arquivo;
 * Coloque a pasta do plugin em /lib/editor/atto/plugins do diretório do moodle;
 * Modifique version.php e configure a versão inicial do seu módulo;
 * Na sua página do Moodle em  Configurações > Administração do Site > Notificações, o Moodle irar guiá-lo na instalação;
 * Vá para Administração do Site > Plug-ins > Editores de Texto > Configurações da Barra de Ferramentas Atto e você deve visualizar o plugin Justify align, adicionado à lista de módulos instalados;

**IMPORTANTE:**
Agora é necessário adicionar o nome da configuração do seu plugin, à estrutura do menu, na parte inferior da página em: Configuração da barra de ferramentas.
* Onde encontra-se: align = align.
  Mudar para: align = align, justify. (onde justify é o nome da configuração plugin)
* Depois de ter tudo configurado, é necessario que você execute o "shifter" 
  Veja como fazer a instalação: http://docs.moodle.org/dev/YUI/Shifter
* Feita a instalação, execute "sudo shifter" dentro do diretorio: yui/src/button
* Por fim, verifique se o ícone Justificar texto encontra-se na barra de ferramentas de edição do atto.
  
