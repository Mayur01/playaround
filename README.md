
## SSH 
* https://www.digitalocean.com/community/tutorials/understanding-the-ssh-encryption-and-connection-procesow 
* How Does SSH Work: https://www.hostinger.com/tutorials/ssh-tutorial-how-does-ssh-work
* How To setup ssh-keys: https://www.digitalocean.com/community/tutorials/how-to-set-up-ssh-keys--2

## What happens when you type an URL in the browser and press enter?
* https://medium.com/@maneesha.wijesinghe1/what-happens-when-you-type-an-url-in-the-browser-and-press-enter-bb0aa2449c1a

## All About HTTP
* https://developer.mozilla.org/en-US/docs/Web/HTTP

## Ultimate guide for speech recognition using python
* https://realpython.com/python-speech-recognition/

## Docker format for Horizontal 
* For ZSH:
```
echo 'export FORMAT="ID\t{{.ID}}\nNAME\t{{.Names}}\nIMAGE\t{{.Image}}\nPORTS\t{{.Ports}}\nCOMMAND\t{{.Command}}\nCREATED\t{{.CreatedAt}}\nSTATUS\t{{.Status}}\n"' >> ~/.zshrc
source ~/.zshrc
```
* Usage: 
```
docker ps --format=$FORMAT
```
