# Sonidos

para convertir
	ffmpeg -i entrada.mp3 -ac 2 -codec:a libmp3lame -b:a 48k -ar 24000 -write_xing 0 -map_metadata -1 salida.mp3