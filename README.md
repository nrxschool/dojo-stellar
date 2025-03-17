# Dojo Stellar

## TLDR

### Números

| participants | teams | projects | challenger |
| - | - | - | - |
| 45 | 15 | 15 | 4 |

### DESAFIOS

**1: Construir um explorer**
- Subir um nó Stellar em algum Cloud
- Criar um Explorer que se conecte com o nó, ele deve:
- Buscar um bloco pelo número
- Buscar uma transação pelo hash
- Buscar o saldo pelo endereço

<img src="https://github.com/user-attachments/assets/3414bd2c-2da5-49cc-bcbb-84665d2492b8" alt="Blockchain Explorer" width="400"> 

**2: Criar uma wallet CLI**
- Criar uma Wallet CLI
- Fazer deploy da wallet em um package provider (Pypi, NPM ou Crate)
- Criar e armazenar vários par de chaves para o usuário (armazenar de forma segura com AES-128 padrão keystore é um Bônus)
- Buscar o saldo da carteira habilitada
- Enviar XML para outros endereços

<img src="https://github.com/user-attachments/assets/eab43826-6edd-4e3d-8927-241e7af77375" alt="Oracle Blockchain" width="400">

**3: Criar um Oráculo**
- Criar um Frontend que busque informações de preços diretamente na Blockchain
- Utilizar as transações do tipo `Manage Data` para salvar dados na Blockchain
- Os dados podem ser sobre preço, noticias ou outras informações que precisam de rastreabilidade de tempo

<img src="https://github.com/user-attachments/assets/6e6c447b-51de-4630-a0aa-ee7c0b82f93f" alt="Oracle Blockchain" width="400">


**4: Criar um CRUD usando Smartcontracts**
- Construir um smartcontract em Rust usando Stellar SDK
- O contrato deve ter as instruções de Creat, Read, Update e Delete

<img src="https://github.com/user-attachments/assets/8d85277a-445a-49db-b29e-0d36fede5f20" alt="CLI Wallet" width="400">


### Post/Articles of participants

1. https://www.linkedin.com/posts/emanoel-oliveira-br_nearx-stellar-dojostellar-activity-7291090329829609472-XuDB/?utm_source=share&utm_medium=member_desktop
2. https://www.linkedin.com/posts/emanoel-oliveira-br_create-your-local-stellar-node-a-step-by-step-activity-7291791286951374848-Omng/?utm_source=share&utm_medium=member_desktop
3. https://www.linkedin.com/posts/madureiradaniel_blockchain-stellar-web3-activity-7291994993659908097-ml3V/?utm_source=share&utm_medium=member_desktop
4. https://www.linkedin.com/feed/update/urn:li:activity:7291542293675692034/
5. https://www.linkedin.com/posts/conrado-niemeyer_blockchain-stellar-nearx-activity-7298691226516549633-2hGg?utm_source=share&utm_medium=member_desktop&rcm=ACoAACpOXLkBfne8vOaBrkrkLi4yRTXqYlN66Nk
6. https://www.linkedin.com/posts/dionathan-cordova-03a421134_blockchain-stellar-node-activity-7292878253340479490-ye-K?utm_source=share&utm_medium=member_desktop&rcm=ACoAACpOXLkBfne8vOaBrkrkLi4yRTXqYlN66Nk
7. https://www.linkedin.com/posts/marceloweb3_vite-react-activity-7293330784629760000-Y4h6?utm_source=share&utm_medium=member_desktop&rcm=ACoAACpOXLkBfne8vOaBrkrkLi4yRTXqYlN66Nk
8. https://www.linkedin.com/posts/kledenilson_stellar-dojoabrstellar-stellar-activity-7292543965931724802-bueF?utm_source=share&utm_medium=member_desktop&rcm=ACoAACpOXLkBfne8vOaBrkrkLi4yRTXqYlN66Nk
9. https://www.linkedin.com/posts/kelvintanita_stellarsenseis-blockchain-rust-activity-7293025611818663936-qXF_?utm_source=share&utm_medium=member_desktop&rcm=ACoAACpOXLkBfne8vOaBrkrkLi4yRTXqYlN66Nk
10. https://www.linkedin.com/posts/conrado-niemeyer_stellar-blockchain-opensource-activity-7292958218278887424-M4W_?utm_source=share&utm_medium=member_desktop&rcm=ACoAACpOXLkBfne8vOaBrkrkLi4yRTXqYlN66Nk
11. https://www.linkedin.com/posts/marceloweb3_we-held-our-first-meeting-on-dojo-stellar-activity-7291507168858591233-P14n?utm_source=share&utm_medium=member_desktop&rcm=ACoAACpOXLkBfne8vOaBrkrkLi4yRTXqYlN66Nk
12. https://www.linkedin.com/posts/madureiradaniel_blockchain-stellar-web3-activity-7291994993659908097-ml3V?utm_source=share&utm_medium=member_desktop&rcm=ACoAACpOXLkBfne8vOaBrkrkLi4yRTXqYlN66Nk
13. https://www.linkedin.com/posts/conrado-niemeyer_blockchain-stellar-xlm-activity-7295775532816736256-AAjs?utm_source=share&utm_medium=member_desktop&rcm=ACoAACpOXLkBfne8vOaBrkrkLi4yRTXqYlN66Nk


## Video de abertura: https://www.youtube.com/watch?v=l-VjAuM0B6g


## Links úteis:
- Dominando Stellar & Fullnode com Docker, Prometheus e SDK Python: https://www.youtube.com/watch?v=yj1sMVlatSM&t=4193s

- Maravilhoso artigo de como subir um node em um cloud FREE: https://medium.com/@pavusa/how-to-set-up-and-run-a-bitcoin-node-on-regtest-mode-using-linode-508c355bf1c3 (👏 parabéns mano @Rob DC)

- Outro Maravilhoso artigo de como subir um node em um cloud FREE: https://medium.com/@mauricio.doerr/bitcoin-regtest-node-with-always-free-oracle-cloud-compute-instance-e7412dd0f902 (👏 parabéns mano @Mauricio Doer)
 
