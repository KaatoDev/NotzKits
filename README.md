<div align="center">
<img src="https://github.com/KaatoDev/NotzKits/assets/107152563/23bcda35-6d06-4a03-97cc-5e9fba4fad69" alt="" height="320" >

#
Plugin de kits personalizável com menu próprio e editável.

## Informações
### `Kits`
Possuem display próprio que, não somente é mostrado ao receber o item, como seta o displayname de itens sem customização para o mesmo.

### `Delay`
São salvos por DATE, então o tempo colocado no kit será a soma do delay do kit ao tempo atual. Por exemplo, se o delay for de 1 dia, o kit poderá ser resgatado exato 1 dia depois, independente do plugin ligado ou não.

</div>

## Dependências
- 

## Spoilers
- ### Loja

![Screenshot_213](https://github.com/KaatoDev/NotzShop/assets/107152563/2312a1bb-765c-4830-939f-30cec569212f)

## Permissões

- `notzkits.admin` - Acesso aos comandos e funções de admin.
- `notzkits.nodelay` - Ignora o tempo de delay do kit.
- `notzkits.kit.{kit}` - Permissão de pegar o kit.

## Commandos
 - `/kit` - Abre o menu de kits.
 - `/kits` - Recebe uma lista de quais kits tem permissão de resgatar.

## Comandos `Admin`
### `/nkit`
 - `addSubmenu` \<Name> - Adiciona um novo submenu.
 - `create` \<Name> \<Display> - Cria um kit novo.
 - `list` - Mostra os kits existentes.
 - `out` - Mostra os kits que não estão setados no menu.
 - `remove` \<Name> - Remove um kit.
 - `removeSubmenu` \<Name> - Remove um submenu existente.
 - `addSubmenu` \<Name> - Para ver as opções de comando dos kits.
 - `<kit>`
   - `get` - Recebe o kit.
   - `give` \<player> - Dá o kit à um player.
   - `set` - Seta o conteúdo do kit (Utiliza dos itens no inventário sem contar a hotbar).
   - `setDelay` \<0d0h0m0s> - Altera o tempo de delay do kit.
   - `setDisplay` \<display> - Altera o display do kit.
   - `setSlot` \<slot> - Altera o slot do kit no submenu.
   - `setSubmenu` \<submenu> - Altera o Submenu do kit.
   - `unsetSubmenu` - Remove o Submenu do kit.

### `Aliases`
- `/nkit`:
  - /nkits, /nk

###### | <> argumento obrigatório. | () argumento opcional. |
 
#
###### Versões testadas: 1.8
