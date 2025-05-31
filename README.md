YouTube Downloader
Este projeto contém dois scripts em Python para download de conteúdos do YouTube:
  Baixar uma playlist completa.
  Baixar um vídeo individual.

🚀 Funcionalidades
✅ Download de playlists completas, com controle de vídeos indisponíveis ou já baixados.
✅ Download de vídeos individuais.
✅ Organização automática dos arquivos, nomeando com título e/ou ID para evitar duplicatas.
✅ Compatível com qualquer sistema operacional que suporte yt-dlp e Python.

🛠️ Requisitos
Python 3.x

yt-dlp instalado e configurado no PATH.

📥 Instalando o yt-dlp
![image](https://github.com/user-attachments/assets/83682e62-c603-4866-8f28-f845afa63f0b)

📁 Estrutura do Projeto
bash
Copiar
Editar
youtube_downloader/
├── download_playlist.py   # Script para baixar playlists
└── download_video.py      # Script para baixar vídeos individuais
🎯 Como Usar
✅ 1. Baixar uma Playlist
Arquivo: download_playlist.py

📌 Passos:
1.Execute o script:
![image](https://github.com/user-attachments/assets/93b035ae-8d69-43d8-a7dd-5900a4b7a9bd)

2.Informe a URL da playlist do YouTube.
3.Informe o diretório onde deseja salvar os vídeos (por exemplo: C:/Videos ou ~/Videos).

✅ O script irá:
  Listar todos os vídeos, incluindo os indisponíveis.
  Identificar automaticamente os vídeos já baixados.
  Fazer download apenas dos vídeos faltantes.
  Exibir um resumo no final.

✅ 2. Baixar um Vídeo Individual
Arquivo: download_video.py

📌 Passos:
Execute o script:
![image](https://github.com/user-attachments/assets/4eabe54c-bff3-4ad7-84cd-dc8aec3dc1d0)

2.Informe a URL do vídeo do YouTube.
3.Informe o diretório onde deseja salvar o vídeo.
✅ O script irá:
  Baixar o vídeo informado.
  Salvar com o título original do YouTube.

💡 Observações Importantes
    O nome dos arquivos pode conter caracteres incompatíveis com alguns sistemas de arquivos. Ajuste o parâmetro -o conforme necessário.
    O yt-dlp é uma ferramenta poderosa e suporta diversos formatos e parâmetros extras. Consulte a documentação oficial para mais opções.
    O script de playlist trata vídeos indisponíveis ou deletados, evitando erros e interrupções no download.

OBS: 
Deixei uma pasta chamada "Imagens Tutoriais de como usar os dois Códigos", com capturas de tela que mostram passo a passo 
como copiar os links da playlist do YouTube e como executar corretamente cada um dos scripts para baixar vídeos ou playlists.

📝 Licença
Este projeto está sob a licença MIT.



