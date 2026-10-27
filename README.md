# DJ Zelin | Link in Bio

Página de links do DJ Zelin, centralizando playlists, vídeos, redes sociais e contatos em um único endereço.

## Links

- Playlist Mundo Eletrônico — Spotify
- Mundo Eletrônico Club Radio (DJ Set) — YouTube
- Instagram e TikTok
- Contato para bookings e publicidade via WhatsApp

## Tecnologias

- HTML5 e CSS3
- Google Fonts (Bricolage Grotesque + Orbitron)
- Bootstrap Icons

## Estrutura

```
/
├── index.html
├── style.css
```

## Como rodar

Abra o `index.html` no navegador. Não há dependências para instalar — fontes e ícones são carregados via CDN.

## Adicionar novos links

Basta inserir um novo `<li>` dentro da `<ul class="list">` no `index.html`:

```html
<li class="list-item">
  <a class="link" target="_blank" href="URL">
    Nome da plataforma
    <i class="bi bi-nome-do-icone"></i>
  </a>
</li>
```

Ícones disponíveis em [icons.getbootstrap.com](https://icons.getbootstrap.com/).

---

Desenvolvido por Guilherme D'antoni.
