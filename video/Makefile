target:
	ghc -O --make Video.hs && ./Video && ffmpeg -r 30 -y -i out%05d.png -i ~/Desktop/script.wav -ab 128000 -vb 400000 output.avi
