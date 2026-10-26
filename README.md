# craftwise.com.br

Site institucional da Craftwise: uma página estática (HTML e CSS, sem PHP, sem banco, sem JavaScript), servida pelo Nginx no mesmo servidor dos sistemas.

```
public/
  index.html          a página
  og.png              imagem que aparece ao compartilhar o link (1200×630)
  favicon.svg/.ico    ícone
  apple-touch-icon.png
```

## Ver no computador

Abra `public/index.html` no navegador.

## Publicar

Push na `main` e, no servidor:

```
sudo craftwise-atualizar site
```

(O `sudo craftwise-atualizar` sem nada também atualiza o site, junto com os sistemas.)

## Instalar no servidor (uma vez)

Ver a seção "Site institucional" em `marcenaria/deploy/LEIA-ME.md`.

## Contato que aparece na página

- WhatsApp: (41) 99716-6329 (link `https://wa.me/5541997166329`)
- E-mail: contato@craftwise.com.br
