/———OPSİDE RESETLEME———-\

———-durdurma komutları v2———-
cd
cd testnet-auto-install-v2
opside-chain/stop-all.sh
———-durdurma komutları v3———-
cd
cd testnet-auto-install-v3
opside-chain/stop-all.sh
———- baslatma komutları v2———-
cd
testnet-auto-install-v2/opside-chain/start-geth.sh
testnet-auto-install-v2/opside-chain/start-beaconChain.sh
testnet-auto-install-v2/opside-chain/start-validator.sh
———- baslatma komutları v3———-
cd
testnet-auto-install-v3/opside-chain/start-geth.sh
testnet-auto-install-v3/opside-chain/start-beaconChain.sh
testnet-auto-install-v3/opside-chain/start-validator.sh
————Log Kontrol v2———
cd
cd testnet-auto-install-v2/

not: alttakiler sırayla girilip bakılacak

opside-chain/show-geth-log.sh
opside-chain/show-beaconChain-log.sh
opside-chain/show-validator-log.sh
————Log Kontrol v3———
cd
cd testnet-auto-install-v3/

not: alttakiler sırayla girilip bakılacak

opside-chain/show-geth-log.sh
opside-chain/show-beaconChain-log.sh
opside-chain/show-validator-log.sh

NOT: control panelinden yapanlar. önce stoplasın biraz beklesin sonra restart yapsın.  KODLARLA yapanlar durdurup biraz beklesin sonra baslatma kodlarını girsin. loglarıda kontrol ediniz bazen baslamayan oluyor adımları tekrarlarsınız
