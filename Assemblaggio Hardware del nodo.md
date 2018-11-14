## 5.Assemblaggio Hardware del nodo. ##


A questo punto possiamo procedere ad assemblare il nodo, il Raspberry è funzionante, quindi possiamo mettere assieme l'hardware del nodo.
Il setup sotto riportato è quello che minimizza l’hardware richiesto assicurando un funzionamento corretto e stabile.


Per prima cosa dovremo assemblare il Raspberry. Se avete acquistato un case simile al mio non dovrebbe essere un problema attaccare i dissipatori ai chip seguendo le immagini dimostrative, avvitare la scheda madre al case usando le apposite viti con il cacciavite in dotazione e per ultimo chiudere il case e montare i piedini di gomma. Come vedete vi è una lunga apertura del case in corrispondenza della porta  GPIO (General Purpose Input/Output port, quella lunga con tutti quei pin, insomma) del Raspberry: visto che non sarà utile nel nostro caso, si può pensare di chiuderla con del nastro adesivo, uno sticker o qualche altra decorazione: il raffreddamento del case non ne soffrirà, ed in compenso limiteremo l’accesso alla polvere: quella è sicuramente dannosa.


A questo punto potremo inserire la scheda Micro SD nello slot del Raspberry.


Colleghiamo alla presa micro usb di alimentazione del Raspberry uno dei due cavi di alimentazioni dell’alimentatore. L’altro invece andrà ad alimentare l’HUB, che a sua volta collegheremo ad una delle 4 prese USB del Raspberry stesso. A questo punto sia il Raspberry che l’HUB sono correttamente alimentati e collegati, possiamo quindi collegare l’Hard Disk all’HUB: sarà quindi solo l’HUB ad alimentare l’Hard disk, che pertanto non andrà a sottrarre amperaggio al funzionamento del Raspberry.
Credo che sia stato tutto abbastanza facile, alla fine dovremmo avere ottenuto un setup simile al seguente: 



![Non è stato difficile alla fine](/images/003.20MinutesLater.JPG)
###### Figura 3. That was easy #######

L'unico cavo qui non rappresentato è il cavo ethernet che dovrà essere ovviamente inserito nel Raspberry. Come abiamo visto nella sezione precedente il Raspberry Pi potrebbe funzionare anche con una connessione Wi-Fi, ma ancora una volta lo sconsiglio.

Quindi collegate la presa nella corrente ed il Cavo Ethernet ad una porta libera del Router. 

Non dovrebbe essere stato difficile, ma non riposiamo sugli allori ed andiamo oltre verso parti ben più ostiche. 
