# Sistema de Streaming de Música

Um sistema de streaming de música simplificado (estilo Spotify), feito em Java com foco em praticar Programação Orientada a Objetos.

# Sobre o projeto

Este projeto simula o funcionamento básico de uma plataforma de streaming: usuários criam playlists, seguem artistas, "tocam" músicas, podcasts e audiolivros, e o sistema acompanha histórico de reprodução e estatísticas simples. O objetivo principal não é reproduzir áudio de verdade, e sim aplicar na prática os pilares da POO em um domínio do dia a dia.

# Estrutura de classes

```
Usuario (abstrata)
├── UsuarioGratuito
└── UsuarioPremium

Conteudo (abstrata) implements Reproduzivel, Avaliavel
├── Musica
├── Podcast
└── AudioLivro

Artista
Album
Playlist
HistoricoDeReproducao
SistemaStreaming
Main
```

# Funcionalidades

- [x] Cadastro de usuário, artista, álbum e música
- [x] Criação de playlists (adicionar/remover músicas)
- [x] Reprodução de conteúdo (atualiza contador e histórico)
- [x] Diferenciação entre usuário gratuito e premium
- [ ] Sistema de avaliação/curtidas
- [ ] Ranking de músicas mais tocadas
- [ ] Persistência de dados em arquivo
- [ ] Integração com a API do Spotify

# Licença
Este projeto é livre para fins de estudo.
