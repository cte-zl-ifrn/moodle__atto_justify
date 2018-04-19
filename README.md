# moodle_atto_justify

Módulo para adicionar função de justificar texto no editor Atto para o Moodle.

## Instalação

 ```
 git clone https://github.com/CoticEaDIFRN/moodle_atto_justify.git

 - Coloque a pasta do plugin em /lib/editor/atto/plugins do diretório do moodle;
 ```
  **ou**
  ```
  - Baixar diretamente o arquivo moodle_atto_justify.zip
  - O Moodle irar guiá-lo na instalação;
  ```
 - Vá para `Administração do Site `> `Plug-ins `> `Editores de Texto` > `Configurações da Barra de Ferramentas Atto` e você deve visualizar o módulo Justify align, adicionado à sua lista de módulos instalados;

- Agora é necessário adicionar o nome da configuração do módulo justify, à estrutura do menu, na parte inferior da página em: `Configuração da barra de ferramentas.`

**Onde encontra-se:**

 ```align = align. ```

 **Mudar para:**

 ```align = align, justify. (onde justify é o nome da configuração módulo)```

- Por fim, verifique se o ícone Justificar texto encontra-se na barra de ferramentas de edição do atto.

## Desenvolvimento

- Para acrescentar novas funções ao modulo é necessário adiciona-las no arquivo `button.js` que se encontra em:  `/lib/editor/atto/plugins/justify/yui/src/button/js`

- Depois de ter feito as alterações, é necessário que você execute o `shifter` para atualizar o atto


- Veja como fazer a instalação do [shifter](http://docs.moodle.org/dev/YUI/Shifter).

- Feita a instalação, execute "sudo shifter" dentro do diretorio: yui/src/button

Verifique se o novo ícone encontra-se na barra de ferramentas de edição do atto.
