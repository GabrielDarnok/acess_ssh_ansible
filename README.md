# Descrição

- Este é um script para realizar um acesso ssh e fazer um ping no servidor remoto e printar o resulado no terminal do interpretador.

# Arquivos

- hosts: Arquivo onde estão armazenados as configurações de acesso.

# Requisitos
- ansible [core 2.16.7]

# Uso
1. Certifique-se de ter o Python instalado em sua máquina.
2. Instale a biblioteca necessária executando o seguinte comando:

- | pip install ansible | 

3. Edite o arquivo hosts com as informações necessárias.

4. Execute o codigo pelo terminal com o seguinte comando:

- | ansible-playbook -i hosts teste.yml | 

# Estrutura do Projeto
- teste.yml: Script principal que coordena a execução.
- hosts: Arquivo de configuração com informações de conexão SSH de uma maquina externa, chave id_rsa, e algumas configurações necessárias.

# Autores
Gabriel Henrique
