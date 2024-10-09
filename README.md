# maquinavirtual-azure

Criar uma máquina virtual do Windows no portal do Azure

As máquinas virtuais do Azure (VMs) podem ser criadas através do portal do Azure. Este método fornece uma interface de utilizador baseada no browser para criar VMs e os respetivos recursos associados. Este guia de início rápido mostra como usar o portal do Azure para implantar uma máquina virtual (VM) no Azure que executa o Windows Server 2019. Para ver a VM em ação, estabeleça o RDP para a VM e instale o servidor Web IIS.

Se não tiver uma subscrição do Azure, crie uma conta gratuita antes de começar.
Iniciar sessão no Azure

Inicie sessão no portal do Azure.
Criar a máquina virtual

    Insira máquinas virtuais na pesquisa.

    Em Serviços, selecione Máquinas virtuais.

    Na página Máquinas virtuais, selecione Criar e, em seguida, Máquina virtual do Azure. A página Criar uma máquina virtual é aberta.

    Em Detalhes da instância, insira myVM para o nome da máquina virtual e escolha Windows Server 2022 Datacenter: Azure Edition - x64 Gen 2 para a imagem. Mantenha as restantes predefinições inalteradas.

![image](https://github.com/user-attachments/assets/20a4b56e-c293-4166-845a-1c28134c2958)

Em Conta de administrador, forneça um nome de utilizador, como utilizadordoazure, e uma palavra-passe. A palavra-passe tem de ter, pelo menos, 12 carateres e cumprir os requisitos de complexidade definidos.
![image](https://github.com/user-attachments/assets/a27a5552-f638-4511-ad5f-7e26efe702e8)


Em Regras de porta de entrada, escolha Permitir portas selecionadas e, em seguida, selecione RDP (3389) e HTTP (80) na lista suspensa. 

![image](https://github.com/user-attachments/assets/23f1ee6e-2d36-4531-af44-ee1abdda6c68)



