# Tabela Periódica Interativa da UFJF — pacotes

Pacotes `.deb` (Raspberry Pi OS 64-bit, arm64) da Tabela Periódica Interativa
do Centro de Ciências da UFJF. Este repositório contém **apenas os pacotes
compilados**, gerados automaticamente; o código-fonte é privado.

- `latest.json` — versão mais recente, nome do arquivo e SHA-256.
- `pacotes/` — todas as versões publicadas.

## Atualizar um Pi que já tem a tabela instalada

```sh
sudo tabela-periodica-atualizar
```

## Primeira instalação

```sh
curl -fLO https://raw.githubusercontent.com/GuiOliveiraRamos/tabela-periodica-releases/main/pacotes/<arquivo-do-latest.json>
sudo apt install ./<arquivo>
sudo tabela-periodica-setup
sudo reboot
```
