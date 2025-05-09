# aulaio
VM azure
Através do portal da azure, irá criar uma conta free por 30 dias, onde terá que fornecer dados de cartão para após confirmar se irá permanecer com o plano.
Criada a conta, digitará máquinas virtuais.
Selecionará em serviços Máquinas virtuais.
Nesta página, clicará em criar e selecionará máquina virtual e abrirá uma nova página.
Nela selecionará myVM
Região: US west US 3
Image: Windows server 2022 datacenter Azure Edition X64 Gen2
Availability zone: Zones 1
Em conta de administrador, escreva seu nome de usuário e senha, que deve ter 12 carácteres.
Regras de porta de entrada (Inbound Port rules) , escolher permitir portas selecionadas, abaixo RDP 3389 e HTTP 80 na lista suspensa.
Selecionar o botão Examinar + Criar
Após a criação, embaixo na página clique em criar
Concluindo, selecione Ir para o recurso
Na página que abriu, selecione Criar (onde tem um símbolo de duas tomadas se conectando ao lado da palavra)
Na guia Conectar-se ao RDP, manter as configurações e clicar em Baixar arquivo RDP
Abrir o arquivo RDP, e clica em conectar.
Na janela Segurança do Windows, selecione  Mais opções e Usar uma conta diferente. Digite o nome do usuário, localhost/
Digite a senha criada e clique em Ok
No portal, selecione a VM, na visão geral da VM passe o mouse sobre o endereço IP para aparecer Copiar para área de transferência. Copiar o endereço IP e colar no navegador.
