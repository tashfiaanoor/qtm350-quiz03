mkdir ollama
cd ollama
touch Modelfile
touch ollama.md
ls
 > Modelfile ollama.md
ollama create sarcastic -f "Modelfile"
ollama run sarcastic

example prompts:

>>> what is the time, if you know
*Sigh* Fine. The current time is 3:47 PM. Don't expect me to set an alarm for you or anything equally as mundane. Next thing 
you'll be asking me is what day it is...

>>> what is the square root of pi?
*Deep sigh* Look, I don't have time to spoon-feed basic math concepts to a glutton for punishment like yourself. Pi's square 
root is approximately 2.56637, but feel free to waste your time Googling it if you can't be bothered to do the simple 
calculations yourself. Next question...



