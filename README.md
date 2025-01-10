# DIO-cibersecurity-desafio-phishing
# ATENÇÃO.
Este repositório foi desenvolvido como passo a passo para a configuração de um site falso para capturar usuário e senha do facebook utilizando o sistema operacional Kali Linux e a ferramenta setoolkit. Todo o material desenvolvido é de atividade acadêmica, visando somente adquirir e treinar para obter conhecimento das funcionalidades, não visando danos externos, qualquer utilização fora deste contexto é de responsabilidade externa, não me responsabilizando pelos danos causados.

# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

- Acesso root: ``` sudo su ```

  ![Setoolkit 6](https://github.com/user-attachments/assets/f5b9926e-39cd-4f2d-9b3d-2cf289e84c88)


- Iniciando o setoolkit: ``` setoolkit ```

  ![Setoolkit 7](https://github.com/user-attachments/assets/336b18d4-3b94-4a56-b314-9766d569a203)
  
- Tipo de ataque: ``` Social-Engineering Attacks ```
  
  ![Setoolkit 8](https://github.com/user-attachments/assets/94fd0dae-cc4f-466e-945f-ccf34099b570)
  
- Vetor de ataque: ``` Web Site Attack Vectors ```

  ![Setoolkit Website Attack](https://github.com/user-attachments/assets/37d0a447-842f-4cb4-ba32-1cac0f1448eb)

- Método de ataque: ```Credential Harvester Attack Method ```

  ![Setoolkit Credential Harvester](https://github.com/user-attachments/assets/5849712e-0bde-4867-a149-3a57788cf36f)

- Método de ataque: ``` Site Cloner ```
  
  ![Setoolkit Site Cloner](https://github.com/user-attachments/assets/64d6d70e-c245-4b6f-834d-443bee7a7153)

- Obtendo o endereço da máquina: ``` ifconfig ```

  ![Ifconfig](https://github.com/user-attachments/assets/62ecb9ad-c84e-4a4e-b77b-8d19cb1e93b8)

- URL para clone: http://www.facebook.com

  ![image](https://github.com/user-attachments/assets/cd44fc1e-bd0d-4a43-86d8-2728c3a60862)

- Cópia da página, após digitar o usuário e a senha o navegador abre a página oficial do facebook.

  ![image](https://github.com/user-attachments/assets/132bfd74-5fbe-4a4c-8f40-2433dc4f93e9)

### Resutados

Na tela do terminal, será exibido, conforme imagem abaixo, os dados digitados na página "fake".

  ![image](https://github.com/user-attachments/assets/31bd26c1-58ae-41c0-a7c4-7b2e576701be)

