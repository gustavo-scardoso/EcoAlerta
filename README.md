# EcoAlerta — versão demonstrativa

Aplicação acadêmica desktop feita em Python + Tkinter. Nesta versão, os dados são persistidos localmente em arquivos JSON e as imagens ficam na pasta `ecoalerta_dados/evidencias`.

## Requisitos

- Python 3.10 ou superior
- Visual Studio Code (opcional, recomendado para editar o código)
- Bibliotecas:

```bash
python -m pip install Pillow cryptography
```

O Tkinter normalmente já acompanha a instalação oficial do Python para Windows.

## Executar

1. Baixe `ecoalerta.py`.
2. Abra a pasta do arquivo no VS Code.
3. Abra **Terminal > Novo Terminal**.
4. Execute `python -m pip install Pillow cryptography`.
5. Execute `python ecoalerta.py`.

Na primeira execução, o programa cria a pasta `ecoalerta_dados`, o arquivo `ecoalerta_dados.json` e imagens demonstrativas.

## Contas demonstrativas

- Coordenador: `coordenador@ecoalerta.local` — senha `EcoAlerta@123`
- Técnico: `tecnico@ecoalerta.local` — senha `Tecnico@123`

Troque as senhas se o programa for utilizado fora de uma demonstração acadêmica.

## Como os dados funcionam

- Cada computador mantém seus próprios dados em `ecoalerta_dados/ecoalerta_dados.json`.
- O GitHub compartilha o código-fonte, mas não sincroniza cadastros em tempo real.
- Para levar os dados alterados de um computador para outro, entre como coordenador, abra **Importação e exportação**, gere um pacote ZIP e importe esse ZIP no outro computador.
- A opção **Restaurar dados demonstrativos** apaga as alterações locais e retorna aos registros iniciais. Use somente se quiser descartar os dados feitos durante os testes.
- Mantenha a pasta `ecoalerta_dados` junto do arquivo Python. Ela contém os registros, as imagens e, quando aplicável, a chave necessária para abrir evidências criptografadas.

## GitHub e privacidade

Para que todos comecem com os exemplos, cada integrante pode baixar o mesmo código e deixar o programa criar os dados demonstrativos na primeira execução. Não enviem para um repositório público dados pessoais, imagens reais de moradores, senhas ou informações sensíveis. Para compartilhar alterações de demonstração, prefiram o pacote ZIP de exportação.

## Observação acadêmica

Este é um protótipo local para fins de estudo e apresentação. Não oferece sincronização simultânea entre computadores nem deve ser usado como sistema de produção.
