   _____
  / ____|
 | (___    _ __     ___   _ __   _ __   _   _
  \___ \  | '_ \   / _ \ | '__| | '__| | | | |
  ____) | | |_) | |  __/ | |    | |    | |_| |
 |_____/  | .__/   \___| |_|    |_|     \__, |
          | |                            __/ |
          |_|                           |___/

  _______                                 _                   _
 |__   __|                               | |                 (_)
    | |      ___    ___   _ __     ___   | |   ___     __ _   _    __ _
    | |     / _ \  / __| | '_ \   / _ \  | |  / _ \   / _` | | |  / _` |
    | |    |  __/ | (__  | | | | | (_) | | | | (_) | | (_| | | | | (_| |
    |_|     \___|  \___| |_| |_|  \___/  |_|  \___/   \__, | |_|  \__,_|
                                                       __/ |
                                                      |___/


Fazendo o download do script de instalação e iniciando a instalação. (Usar somente na primeira instalação):

```bash
sudo apt install -y git && git clone https://github.com/SperryTecnologia/tickets-main.git && sudo chmod -R 777 tickets-main && cd tickets-main && sudo ./install_primaria
```

Acessando o diretório do script de instalação e instalando novas instalações. (Usar somente depois da primieira instalação para novos sistemas):
```bash
cd ./tickets-main && sudo ./install_instancia
```

Utilizar apenas o repositório privado oficial de instalação:   
__________________________________________________ 
| https://github.com/sperrytecnologia/tickets.git |
| Usuário:                                        |
| Senha:                                          |
| ________________________________________________|
