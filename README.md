# RobberiesDataProcessing
End-to-end data pipeline using Azure services for processing robberies data for EU countries and interactive reporting with Power BI.

This project showcases a complete cloud-based data pipeline and reporting solution using Microsoft Azure and Power BI. The dataset used involves robbery statistics sourced directly from the official Eurostat website.

The main goal of this project is to demonstrate how data can be collected, processed, stored, analyzed, and visualized using Azure’s powerful data tools — all without any local infrastructure.


---

Data Pipeline Steps

1. Data Ingestion
A CSV file containing robbery statistics was downloaded from Eurostat's official open data portal and uploaded to Azure Blob Storage.


2. Data Transformation
The raw CSV file was processed using Azure Data Factory Data Flow, where cleaning and transformations were applied. The cleaned dataset was then saved back to a different container in Blob Storage via a pipeline.


3. Querying and Analysis
The transformed data was queried using Azure Synapse Analytics through the Serverless SQL Pool. This allowed for on-demand analysis directly from the data lake without provisioning any dedicated SQL resources.


4. Reporting and Visualization
Using Power BI, a fully interactive report was created, including:

A standard column chart

A horizontal bar chart

A geographical map visualizing robbery rates

---

Technologies Used

-Azure Blob Storage

-Azure Data Factory (Data Flow & Pipelines)

-Azure Synapse Analytics (Serverless SQL Pool)

-Power BI (Visualization & Reporting)


---

Αυτό το project παρουσιάζει ένα πλήρες cloud-based data pipeline και σύστημα αναφορών χρησιμοποιώντας το Microsoft Azure και το Power BI. Τα δεδομένα που χρησιμοποιήθηκαν αφορούν στατιστικά για ληστείες, και προέρχονται απευθείας από τον επίσημο ιστότοπο της Eurostat.

Στόχος του project είναι να δείξει πώς μπορούμε να συλλέξουμε, να επεξεργαστούμε, να αποθηκεύσουμε, να αναλύσουμε και να οπτικοποιήσουμε δεδομένα αξιοποιώντας τις cloud υπηρεσίες της Azure — χωρίς να απαιτείται τοπική υποδομή.


---

Βήματα του Data Pipeline

1. Ανέβασμα των Δεδομένων
Ένα αρχείο CSV με στατιστικά ληστειών κατεβάστηκε από την επίσημη πύλη της Eurostat και ανέβηκε στο Azure Blob Storage.


2. Καθαρισμός και Μετασχηματισμός
Το αρχείο CSV πέρασε από Data Flow στο Azure Data Factory, όπου έγινε καθαρισμός και μετασχηματισμός των δεδομένων. Το τελικό καθαρό dataset αποθηκεύτηκε ξανά σε ξεχωριστό container στο Blob Storage μέσω pipeline.


3. Ανάλυση με SQL
Τα καθαρισμένα δεδομένα αναλύθηκαν μέσω Azure Synapse Analytics με χρήση του Serverless SQL Pool. Έγινε εκτέλεση ερωτημάτων απευθείας πάνω στο αρχείο, χωρίς να χρειάζεται SQL server ή άλλη υποδομή.


4. Δημιουργία Report
Στο Power BI δημιουργήθηκε ένα διαδραστικό report που περιλαμβάνει:

Ένα απλό column chart

Ένα οριζόντιο column chart

Ένα γεωγραφικό χάρτη με τα ποσοστά ληστειών ανά περιοχή





---

Τεχνολογίες που Χρησιμοποιήθηκαν

Azure Blob Storage

Azure Data Factory (Data Flows & Pipelines)

Azure Synapse Analytics (Serverless SQL Pool)

Power BI (Δημιουργία Reports & Οπτικοποίηση Δεδομένων)



---
