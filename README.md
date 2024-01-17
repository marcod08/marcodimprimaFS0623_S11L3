### S11L3

## Spiegazione generica:

TS è un linguaggio di programmazione che estende JS introducendo il sistema di tipi, è un linguaggio interpretato e aggiunge un layer di tipizzazione statica che consente di dichiarare e definire i tipi delle variabili. Questo aiuta a prevenire molti errori durante la fase di progettazione e inoltre rende le operazioni di refactoring piu sicure 

## Il compilatore TypeScript:

Il compilatore converte il codice scritto in TS in un file JS, rendendolo eseguibile nei browser, infatti quest'ultimi non sarebbero in grado di interpretarlo altrimenti.
Inoltre il compilatore verifica la correttezza del codice gestisce le dichiarazioni dei tipi, e ottimizza il codice durante la compilazione

## Type Inference:

Il type inference permette al compilatore di dedurre automaticamente i tipi delle variabili sulla base del loro valore e del contesto in cui sono utilizzate. Questo consente di scrivere codice più conciso senza la necessità di dichiarare esplicitamente tutti i tipi

## Il tipo 'any':

Questo tipo permette di assegnare a una variabile un qualsiasi tipo di valore, ignorando la verifica del tipo da parte del compilatore.

## Il tipo Union:

Il tipo Union consente di definire una variabile con più di un tipo possibile.

## Il tipo Tuple:

Una Tuple è un tipo di dato che permette di definire un array con un numero fisso di elementi, ognuno con un tipo specifico.

## Le Interfaces in TS:

Le Interfaces sono utilizzate per dichiarare contratti che i tipi devono seguire. Le interfacce in TypeScript definiscono la forma di un oggetto, specificando i nomi e i tipi dei suoi membri. Gli oggetti che implementano un'interfaccia devono conformarsi a queste specifiche.

## Types vs Interfaces:

Entrambi i Types e le Interfacce possono essere utilizzati per dichiarare tipi in TypeScript, ma esistono alcune differenze. Le Interfacce sono principalmente utilizzate per dichiarare la forma di un contratto, mentre i Types possono essere più flessibili e usati per dichiarare tipi union, intersection, e altri tipi più avanzati.

## I Generics:

I Generics consentono la creazione di componenti riutilizzabili che possono lavorare con diversi tipi di dati senza sacrificare la sicurezza del tipo. Sono spesso utilizzati per scrivere funzioni e classi che possono operare su dati di tipo variabile.