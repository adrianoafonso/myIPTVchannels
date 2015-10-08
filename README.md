# myIPTVchannels
Just a public collection of IPTV links collected over the web!
Open to all the IPTV community.

Atenção: <b>Todas as ligações de streams disponibilizados nas listas foram retiradas da internet. A comunidade apenas as organiza, disponibiliza e partilha. Não detemos qualquer servidor e/ou trasmitimos ou re-emitimos qualquer tipo de sinal</b>.

##URLs myIPTVChannels (Kodi/VLC, etc)
Portugal PT Channels: pt.m3u = http://tinyurl.com/myiptvportugal

Sports Channels: sports.m3u = http://tinyurl.com/myiptvsports

Movies: movies.m3u = http://tinyurl.com/myiptvmovies

Music Channels: music.m3u = http://tinyurl.com/myiptvmusic

United Kingdom UK Channels : uk.m3u = http://tinyurl.com/myiptvuk

Russia RU Channels: ru.m3u = http://tinyurl.com/myiptvru

Indian IN Channels: hindi.m3u = http://tinyurl.com/myiptvhindi

NASA Space Channels: nasa.m3u = http://tinyurl.com/myiptvnasa

SMART TV (LG, Samsung, Philips): smart-tv.m3u = http://tinyurl.com/myiptvsmarttv

Adult Channels: adult.m3u = http://tinyurl.com/myiptvadult

Webcams World / Beaches : webcamsmundoepraias.m3u = http://tinyurl.com/myiptvpraias


##Rules
1) KISS = Keep it simple, stupid (as possible)!

1.1) Nome do canal com um espaço " " antes, a seguir à virgula (optimização para dispositivos pequenos, como tablets).

1.2) Se existir mais que um canal/ligação, diferenciar através da qualidade do canal a seguir ao nome do mesmo, com FHD (para 1080p) HD (para 720p), FSD (entre 480i e 576i) e SD (Menos de 480i), ou então um número sequencial entre parentisis. Ex: RTP FHD / RTP (2). Resoluções abaixo de 720p porém acima de 576i deverão ser consideradas "FSD" (para avaliar a resolução de uma stream, poderão usar o VLC).

1.3) Nomes dos canais sem referências, créditos e cores.

1.4) Respeitar a estrutura previamente adoptada.

1.5) Verificar se a categoria já existe, e adicionar respeitando a mesma se já existir. Podem ser usadas cores para as diferênciar.

1.6) Tentar organizar por ordem alfabética dos nomes dos canais, dentro de cada categoria.


2) Template:
EXTINF:0 tvg-name="rtp1.pt" audio-track="pt" tvg-logo="http://mylogos.domain/Sporttv1.png" group-title="TDT", RTP 1
http://server.name/stream/to/video2

2.1) group-title= Sugiro categorias clean para a organização dos canais.Evitar a criação de novas categorias

2.2) tvg name pode consultar-se o xml do epg.kodiportugal.com

2.3) tvg-id is value of channel id in EPG xml file. If the tag is absent then addon will use tvg-name for map channel to EPG;

2.4) tvg-name is value of display-name in EPG there all space chars replaced to _ (underscore char) if this value is not found in xml then addon will use the channel name to find correct EPG.

2.5) tvg-shift is value in hours to shift EPG time. This tag can be used in #EXTM3U for apply shift to all channels or in #EXTINF for apply shift only to current channel.

2.6) group-name is channels group name. If the tag is absent then addon will use group name from the previous channel.
radio is flag that indicate what group or cahnnel is radio. If the tag is absent then addon will use value from current group (if exists).

2.7) tvg-logo - Display name or logo of this channel
audio-track - Audio track definition of this channel, if it's supported by stream. Write language codes in ISO 639-2 standard, you may use several codes separated by comma (e.g.: "eng, rus, deu"). The first item in the list will be defined as default.

##Help/Ajuda

Como usar várias listas ao mesmo tempo no KODI - http://kodiportugal.com/PlayList.pdf

##Channels Sources

###Portugal
http://kodiportugal.com/iptv.html
Based on Kitina, by Magellan

###Russia Channels
http://fixzen.3dn.ru/load/video/iptv_playlist/7-1-0-36

http://dump-sat.blogspot.pt/

http://retranslyator.blogspot.com/p/iptv-playlist.html

###Husham
http://www.husham.com/iptv-links/

https://github.com/hmemar/husham.com/tree/master/Lists

###Indian Channels (Husham)
https://github.com/hmemar/husham.com/blob/master/Lists/hindi.m3u

##Utilities
http://git.io/
