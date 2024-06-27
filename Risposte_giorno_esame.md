## Risposte Minardi
### Esperimento 1 - Teletrasporto quantistico
2) L'esperimento di Vienna era un esperimento di teletrasporto quantistico. Lo scopo ultimo era quindi quello di passare uno stato di un fotone ad un altro fotone, senza che i due fotoni si siano mai incontrati. Questo è possibile grazie al fenomeno di entanglement quantistico. 
In particolare per questo esperimtno si crea una coppia di fotoni entangled $q_2$ e $q_3$ e si invia il fotone $q_2$ ad Alice e il fotone $q_3$ a Bob. Alice ha a disposizione un fotone $q_1$ che vuole teletrasportare.
Alice effettua una misura di Bell sulla coppia di fotoni in suo possesso.
La misura di bell viene effettuata tramite dei proiettori che proiettano direttamente nello stato di Bell, per semplificare nell'esperimento di Vienna si è scelto di proiettare sempre nello stato $\ket{\Phi^-}$.
Alice successivamente descrive l'esito della misura a Bob, che a sua volta effettua una trasformazione unitaria sul suo fotone $q_3$ in base all'informazione ricevuta da Alice.
La creazione della coppia di fotoni entangled avviene tramite il fenomeno di Parametric Down Conversion, in cui si spara un raggio di fotoni, che è un onda straordinaria, attraverso un cristallo non lineare, creando una coppia di fotoni entangled, uno ordinario e uno straordinario.
La Misura di Bell è effettuata attraverso un beam splitter, con polarizzazione a 45°, e due rivelatori, uno per il fotone ordinario e uno per lo straordinario.
Si calcolano le triple coincidenze tra i due rivelatori e il beam splitter, e si ottiene la funzione di correlazione di Bell.


### Esperimento 2 - Misura di Bell e indistinguibilità dei fotoni
1) La misura di Bell è una misura che permette di verificare la non località della meccanica quantistica. In particolare si vuole verificare se la meccanica quantistica è una teoria locale o no.
La misura di Bell si basa sulla disuguaglianza di Bell, che afferma che se si ha una teoria locale, allora la disuguaglianza di Bell è rispettata, altrimenti no.
Ci fu una serie di esperimenti a riguardo partendo da quelli di Freedman e Clauser.
Freedman e Clauser misurano le polarizzazioni di due fotoni, e verificano che la disuguaglianza di Bell non è rispettata.
Preparano la coppia di fotoni entagled partendo da un atomo di calcio 40, eccitandolo con della luce UV, e misurando le polarizzazioni dei fotoni emessi.
La disuguaglianza di Bell è data da $|E(a,b) - E(a,b') + E(a',b) + E(a',b')| \leq 2$, dove $E(a,b)$ è la correlazione tra le polarizzazioni dei due fotoni.
Aspect eseguirà 3 esperimenti.
Nel primo esperimento di Aspect ripropone l'esperimento di Clauser ma cambiando il metodo di generazione della coppia di fotoni entangled per aumentare i rate di coincidenze.
Li crea utilizzando due laser, uno per ogni fotone. Questo aumenta il rate di conicidenze di 3 ordini di grandezza.
Nel secondo esperimento Aspect aggiungerà un secondo rivelatore per ogni fotone, in modo da poter misurare anche i fotoni riflessi dal beam splitter.
Nel terzo esperimento Aspect utilizzerà una tecnologia a cristalli liquidi per variare l'angolo di polarizzazione mentre i fotoni sono in volo, per eliminare il loophole relativo alla comunicazione tra i due fotoni.
Altri loophole sono il fair sampling(che si è risolto chiamando 100000 persone per scegliere una sequenza di bit) e il detection loophole(che si è risolto aumentando il rate di coincidenze).

### Esperimento 3 - Criptografia quantistica
1) La criptografia quantistica è un metodo di crittografia che sfrutta le leggi della meccanica quantistica per garantire la sicurezza delle comunicazioni.
In particolare Naik et al. nel 2000 hanno dimostrato la sicurezza della criptografia quantistica.
Il protocollo di Naik et al. si basa sul protocollo di Ekert, dove creata una coppia di fotoni entangled attraverso un cristallo non lineare, si inviano i fotoni ai due utenti, Alice e Bob.
Alice e Bob misurano le polarizzazioni dei fotoni su angoli diversi, e confrontano le misure.
Utilizzano l'insieme delle misure complementare a quelle utilizzate per la chiave segreta per verificare che non ci siano interferenze esterne.
Calcolano la combinazione lineare delle misure che violerà la disuguaglianza CHSH. Nel momento in cui c'è un Eve che intercetta i fotoni, la disuguaglianza CHSH non è più violata dato che lei deve effettuare misure e rinviare i fotoni, e quindi la combinazione lineare delle misure non violerà la disuguaglianza CHSH.
Due parole sulla distribuzioni di chiave tramite satellite: si inviano i fotoni entangled utilizzando il protocollo BB84 per utilizzare non singoli fotoni ma sequenze di fotoni, e si inviano i fotoni tramite un satellite che è più veloce di un canale di comunicazione terrestre.
Il satellite pubblica lo xor delle due chiavi così ognuno ottiene la chiave dell'altro.

### Esperimento 4 - Atomi di Rydberg
1) Gli atomi di Rydberg sono atomi in cui un elettrone è stato eccitato ad un livello energetico molto alto.
Avendo un numero quantico n molto alto, l'elettrone si trova molto lontano dal nucleo, e quindi l'atomo diventa molto grande. Questi stati con n molto alto hanno una vita media molto lunga, di qualche nanosecondo, quindi possono essere studiati con facilità.
Il registro quantistico che conterrà questi atomi viene realizzato tramite un array di pinzette ottiche e poi vengono raffreddati a temperature molto basse, dell'ordine di qualche microkelvin utilizzando trappole magneto ottiche.
Essendo che gli atomi di Rydberg posseggono elemnti di matrice del dipolo che scalano come $n^2$, le interazioni dipolo-dipolo tra gli atomi di Rydberg sono molto forti e aumentano all'aumentare di n.
Sono facilmente maneggevoli in quanto è facile disattivare l'interazione tra gli atomi di Rydberg riportando l'elettrone al suo stato fondamentale.
Gli atomi di Rydberd inoltre fomrano blocchi di Rydberg, che sono blocchi di due atomi di Rydberg dove solo uno dei due è eccitato, e che possono essere utilizzati per realizzare porte logiche quantistiche, poichè l'atomo di Rydberg eccitato sposta i livelli energetici dell'altro atomo di Rydberg fuori risonanza.
E' stata ideata una porta logica C-Z utilizzando due atomi di Rydberg, uno di controllo e uno di target. Si dà un impulso di Rabie al controllo, che se è nello stato $\ket{1}$ sposta il target fuori risonanza, e se è nello stato $\ket{0}$ non succede nulla. Questo aggiunge una fase di $\pi$ allo stato $\ket{11}$ e non fa nulla allo stato $\ket{10}$.

## Domande Calarco
4. Circuito di copia quantistica e teorema di non clonazione.(con esempi di calcolo) 

4) Il circuito di copia quantistica è un circuito che permette di copiare uno stato quantistico utilizzando un gate CNOT.
Si vuole mandare uno stato $\ket{\psi} = \alpha\ket{0} + \beta\ket{1}$ in un target qubit $\ket{0}$.
Il problema è che se lo stato non è ortogonale a $\ket{0}$, non si può copiare.
In quanto viene come risultato dopo la CNOT $\alpha\ket{00} + \beta\ket{11}$ che non è uguale a $\ket{\psi}\ket{\psi} = \alpha^2\ket{00} + \alpha\beta\ket{01} + \alpha\beta\ket{10} + \beta^2\ket{11}$.

7. Spiegami l'algoritmo di Deutsch.

7) L'algoritmo di Deutsch è un algoritmo quantistico che permette di risolvere un problema di decisione in un solo passaggio.
Il problema di decisione è il seguente: si ha una funzione $f: \{0,1\} \rightarrow \{0,1\}$, e si vuole sapere se è costante o bilanciata.
La funzione è costante se $f(0) = f(1)$, e bilanciata altrimenti.
Questa volta si parte da uno stato $\ket{01}$, si applica un'Hadamard e si applica una trasformazione unitaria $U_f$ che agisce su due qubit, e che mappa $\ket{x}\ket{y}$ in $\ket{x}\ket{y \oplus f(x)}$.
infine si applica un altro Hadamard sull'input.
Se la misura finale è uguale a 0, allora la funzione è costante, altrimenti è bilanciata.

13. Protoccolo Error Correction e BB84, spiegali.

## Domande Ercolessi
5. Paradosso EPR e ineguaglianza di Bell, spiegali.

5) Il paradosso EPR è un paradosso che mette in discussione la completezza della meccanica quantistica.
Una teoria per essere completa deve rispettare:
- località: oltre una certa distanza non ci deve essere correlazione tra i due sistemi
- realismo: i sistemi devono avere delle proprietà ben definite anche se non misurate
- completezza: la teoria deve essere in grado di spiegare tutti i fenomeni
Il paradosso EPR mette in discussione la località della meccanica quantistica.
Si calcola quindi la disuguaglianza di Bell, che afferma che se la meccanica quantistica è locale, allora la disuguaglianza è rispettata, altrimenti no, utilizzando la correlazione tra i fotoni.
Come misura si utilizza la correlazione tra le polarizzazioni dei fotoni seguendo la disuguaglianza di Bell $|E(a,b) - E(a,b') + E(a',b) + E(a',b')| \leq 2$.

7. Stati puri e misti, e matrice densità, spiegali.

Gli stati puri sono stati che possono essere descritti da una matrice densità che è il prodotto esterno dello stato puro con se stesso.
La matrice densità deve avere le seguenti proprietà:
- $P_{\psi}$ è bounded, in particolare $||{P_{\psi}} = 1||$.
- $P_{\psi} = P_{\psi}^{\dagger}$
- $P_{\psi}^2 = P_{\psi}$
- $Tr(P_{\psi}) = 1$
- $P_{\psi}$ è positiva, ovvero $\braket{\phi|P_{\psi}|\phi} \geq 0$ per ogni $\phi$.

Gli stati misti sono stati che vengono descritti da una matrice densità che è una somma pesata in base alle probabilità di avere uno stato puro.
La matrice densità deve avere le seguenti proprietà:
- $P_{\rho}$ è bounded, in particolare $||{P_{\rho}} = 1||$.
- $P_{\rho} = P_{\rho}^{\dagger}$
- $P_{\rho}^2 \neq P_{\rho}$
- $Tr(P_{\rho}) = 1$
- $P_{\rho}$ è positiva, ovvero $\braket{\phi|P_{\rho}|\phi} \geq 0$ per ogni $\phi$.

9. Quantum Operators, quantum operations, spiegali.

Gli operatori quantistici sono operatori che agiscono su uno spazio di Hilbert, hanno autovalori reali e sono hermitiani.
Le operazioni quantistiche sono operatori che agiscono su stati quantistici, e sono operatori completamente positivi e traccia-preservanti.
Possono essere visti come dei canali quantistici, che descrivono la trasformazione di uno stato quantistico in base all'ambientazione in cui si trova.
- Depolarizing channel: è un canale secondo il quale un qubit con probabilità $1-p$ rimane invariato, e con probabilità $p$ viene trasformato in uno stato casuale. Tre tipi di errori possono avvenire: errore di bit flip, errore di fase flip, errore di bit e fase flip. Il canale di depolarizzaizone può essere descritto attraverso la trasformazione di Kraus $\mathcal{E}(\rho) = (1-p)\rho + p X\rho X + pY\rho Y + pZ\rho Z$.
- dephasing channel: è un canale che introduce un errore di fase, e può essere descritto attraverso la trasformazione di Kraus $\mathcal{E}(\rho) = (1- 1/2p)\rho + 1/2pZ\rho Z$.
- Amplitude damping channel: è un canale che introduce un errore di damping, ossia che un atomo eccitato può decadere in uno stato di energia inferiore rilasciando fotonio. Può essere descritto attraverso la trasformazione di Kraus $\mathcal{E}(\rho) = E_0\rho E_0^{\dagger} + E_1\rho E_1^{\dagger}$, dove $E_0 = \begin{bmatrix} 1 & 0 \\ 0 & \sqrt{1-p} \end{bmatrix}$ e $E_1 = \begin{bmatrix} 0 & \sqrt{p} \\ 0 & 0 \end{bmatrix}$.