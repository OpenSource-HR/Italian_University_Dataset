# Dataset delle Università Italiane - Repository

Benvenuto nel **Dataset delle Università Italiane - Repository**! 🎉 Questo repository è dedicato alla fornitura di un dataset strutturato derivato da AlmaLaurea, un'entità specializzata nella raccolta di dati dagli studenti universitari italiani.

- Puoi scaricare i nostri ultimi dataset leggendo la *sezione ["🛠️ Come Utilizzare"](#%EF%B8%8F-come-utilizzare) in basso in questo Readme*.

## 🌟 Informazioni su Questo Repository

Lo scopo di questo repository è rendere accessibile e semplice l'analisi dei dati sulle università italiane. Il dataset è presentato in formato tabellare per facilitare l'analisi non commerciale da parte di:

- **Aziende**: Per costruire relazioni informate con il panorama universitario italiano.
- **Candidati**: Per prendere decisioni migliori nella valutazione delle università.

Questa iniziativa si allinea ai termini di AlmaLaurea per l'uso non commerciale, garantendo che i dati siano utilizzati in modo etico ed efficace. 🌍

---

## 🎯 Obiettivi

1. **Supportare Decisioni Informate**: Permettere ai candidati di valutare le università e alle aziende di migliorare strategie di employer branding e recruiting.
2. **Semplificare l'Accesso ai Dati**: Offrire un dataset pulito e strutturato, pronto per l'analisi.
3. **Promuovere la Trasparenza**: Fornire una risorsa aperta per usi non commerciali.

---

## 📁 Struttura del Repository

### 📂 Stato Attuale (Versione 0.1)

- **Dati**: Il repository attualmente contiene dati del 2023 di tutte le università italiane in formato `.csv`. Le categorie rispecchiano quelle utilizzate da AlmaLaurea, e sono stati fatti sforzi per mantenere l'integrità dei dati, aggiungendo alcune macro-categorie dove necessario. La struttura dei dati è derivata dai raggruppamenti di AlmaLaurea per aree disciplinari e campi, con il numero di studenti aggregato per università. Gli utenti possono replicare questi risultati utilizzando i filtri direttamente sul sito di AlmaLaurea, collegato nella sezione "Avviso Importante" di questo README. Tuttavia, il dataset necessita ancora di una pulizia.
  - **Work in Progress**: Stiamo implementando una colonna per distinguere tra numeri assoluti e percentuali, oltre a separare i dati aggregati dai record individuali. La Categoria 5 è attualmente la più impattata da questi aggiornamenti.
  - **Nota Metodologica**: I dati originali raccolti da AlmaLaurea utilizzavano "-" per indicare l'assenza di rispondenti nel campione, e "*" per indicare che cinque o meno rispondenti avevano risposto in quel campione, escludendoli dall'analisi. Per mantenere questa struttura e migliorarne l'usabilità, "-" è stato sostituito dal valore numerico `0` e "*" con `-1` nel dataset. Queste sostituzioni mantengono lo stesso significato della metodologia originale di AlmaLaurea. Consulta la sezione "Avviso Importante" di questo README per i link alle pagine ufficiali di AlmaLaurea sulla metodologia dei dati.

### 🔜 Piani Futuri

- **Maggiore Usabilità**: Pulire e riorganizzare ulteriormente il dataset per renderlo ancora più user-friendly.
- **Dati Storici**: Includere dati degli anni precedenti, dividendo i file `.csv` per anno.
- **Formato SQL**: Introdurre una versione del database in SQL per migliorare la compatibilità e la scalabilità con diversi strumenti di analisi HR.
- **Implementazione di una Dashboard**: Considerare l'aggiunta di una dashboard a questo progetto, rendendo il dataset più accessibile a un pubblico più ampio. Sebbene *non sia attualmente nella roadmap*, questa funzione sarebbe in linea con la mission del repository, semplificando l'interpretazione dei dati per più utenti.

---

## 🛠️ Come Utilizzare

1. Scarica il file `.csv` per l'anno di interesse direttamente dalla sezione delle release.
   - ➡️ **Ecco il [LINK](https://github.com/OpenSource-HR/Italian_University_Dataset/releases/download/v0.1/Italian_University_Dataset_2023.csv) per il** `Italian_University_Dataset_2023.csv`. Al momento è l'unico disponibile ⬅️
   - Puoi trovare le versioni attuali e future nella sezione [Releases](https://github.com/OpenSource-HR/Italian_University_Dataset/releases), con tutti i relativi asset e una descrizione dettagliata.
2. Apri il file utilizzando il tuo strumento di analisi dati preferito, come Tableau o Power BI.
3. Inizia a esplorare e analizzare i dati per soddisfare le tue esigenze.

---

## 📬 Contattaci

Per domande, suggerimenti o collaborazioni, sentiti libero di aprire un issue o contattarci:

- **Email**: OpenHRProject@gmail.com 📨
- **LinkedIn**:  
  👥 [OpenSource HR Project](https://linkedin.com/company/opensource-hr-project)  
    ➞ [Riccardo Spedito](https://linkedin.com/in/riccardo-spedito)  
    ➞ [Federica Dolcemascolo](https://linkedin.com/in/federica-dolcemascolo)  

---

## 🌱 Contributi

Accogliamo con piacere contributi per migliorare questo progetto! Scrivici per entrare in contatto. Insieme, possiamo migliorare l'accessibilità e l'usabilità dei dati HR. 🤝

Ringraziamo inoltre il [repository Gibberlink3](https://github.com/Gibberlings3), da cui abbiamo preso il [modello di licenza](https://github.com/Gibberlings3/GitHub-Templates/blob/master/License-Templates/CC-BY-NC-4.0/LICENSE-CC-BY-NC-4.0.md).

---

## 📜 Licenza e Attribuzione

Questo repository opera sotto una licenza **Creative Commons Attribution-NonCommercial (CC BY-NC)**. Ciò significa:

- **Solo Uso Non Commerciale**: i dati e le risorse fornite qui sono esclusivamente per scopi non commerciali, in conformità con i requisiti di AlmaLaurea.
- **Attribuzione**: ogni utilizzo dei dati deve citare OpenSource HR Project e AlmaLaurea come fonti originali, per garantire trasparenza e tracciabilità della storia dei dati.
- **Leggi la licenza**: per ulteriori dettagli, consulta il file [LICENSE](LICENSE.md) del repository.

---

## ❗️ Avviso Importante

Questo progetto **non è affiliato con AlmaLaurea**. Ripropone dati raccolti da AlmaLaurea in conformità con la loro politica per l'uso non commerciale. Per metodologie dettagliate, analisi e criteri dei dati, consulta direttamente le pagine ufficiali di AlmaLaurea:

- [Tutti i dati disponibili dalle indagini AlmaLaurea](https://www.almalaurea.it/i-dati/tutti-i-dati)
- [Raccolta dati dalle indagini AlmaLaurea](https://www.almalaurea.it/i-dati/le-nostre-indagini)
- [Contatti e Approfondimenti](https://www.almalaurea.it/i-dati/approfondimenti)
- [Dove ottenere i dati utilizzati in questo progetto - Laureati (Laurea Triennale, Magistrale) per Università](https://www.almalaurea.it/i-dati/tutti-i-dati)
- [Note metodologiche di AlmaLaurea](https://www2.almalaurea.it/cgi-php/universita/statistiche/note-metodologiche.php?lang=it&config=profilo&anno=2023)
- [Informativa sulla privacy di AlmaLaurea](https://www.almalaurea.it/info/condizioni/privacy)

---

