# Pràctica 2: Anàlisi Adult Income Dataset

## 1. Integrants del grup  
Víctor Olivera Begue  
Guillem Romeu Graells

## 2. Arxius del repositori  
Aquest repositori conté els fitxers i carpetes següents:
```
PAC2_AdultIncome/
├── dades/
│   ├── adult.csv                # Dataset original (UCI)
│   └── adult_net_final.csv      # Dataset final netejat i imputat
├── codi/
│   └── PR2.Rmd                  # Fitxer R Markdown amb tot el codi i anàlisi
├── informe/
│   └── PR2_final.pdf            # Informe knit a PDF
├── README.md                    # Aquest document
└── LICENSE                      # Llicència del contingut
```
## 3. Ús del codi  
Per executar el codi de la pràctica:

Assegura’t que tens instal·lat R 4.2 o superior i RStudio.  
Instal·la les llibreries necessàries amb:

```r
install.packages(c("tidyverse", "naniar", "VIM", "caret", "pROC", "cluster", "factoextra", "rstatix"))
```

Obre `codi/PR2.Rmd` amb RStudio i prem **"Knit to PDF"** per generar l’informe.

El codi:

- Neteja i transforma les dades amb `tidyverse` i `VIM`
- Imputa valors perduts amb `kNN`
- Detecta outliers amb Cook’s Distance i boxplots
- Aplica models predictius (regressió logística) i clustering (PAM)
- Realitza proves d’hipòtesi (Shapiro, Levene, Wilcoxon)
- Representa gràficament els resultats

## 4. Enllaç al vídeo  
https://drive.google.com/drive/folders/1uxO3c8djVWcA67RFlMv0UHM9rHlYm2yr

## 5. Descripció del projecte  
Aquest projecte correspon a la Pràctica 2 de l’assignatura _Tipologia i cicle de vida de les dades_ del Màster en Ciència de Dades (UOC).  
L’objectiu és dur a terme una anàlisi completa de dades reals, aplicant tècniques de neteja, transformació, validació i modelatge per extreure conclusions útils sobre els factors que influeixen en els ingressos personals.

## 6. Requisits  
Llibreries necessàries (R):  
- tidyverse  
- naniar  
- VIM  
- caret  
- pROC  
- cluster  
- factoextra  
- rstatix

Pots instal·lar-les amb:

```r
install.packages(c("tidyverse", "naniar", "VIM", "caret", "pROC", "cluster", "factoextra", "rstatix"))
```

## 7. Llicència  
Aquest projecte s’ha elaborat en el marc d’una assignatura universitària.  
L’ús del contingut està subjecte a propòsits educatius i acadèmics.  
Consulta el fitxer `LICENSE` per a més informació.

