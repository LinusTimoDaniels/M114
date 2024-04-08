# KW15 Arbeitsblatt

## Theorie: [D_KRYPTOGRAFIE_SYM](./D_KRYPTOGRAFIE_PGP.pdf)
## Aufgaben: [D_KRYPTOGRAFIE_SYM_ANNEX](./D_KRYPTOGRAFIE_PGP_ANNEX.pdf)

## Inhaltsverzeichnis
- [X] [Aufgabe 1](#Aufgabe-1---Public-Key-verifizieren)
- [X] [Aufgabe 2](#Aufgabe-2---ublic-Key-Infrastruktur)
- [X] [Aufgabe 3](#Aufgabe-3---Certification-Authority-und-Trust-CenterZertifikat)
- [X] [Aufgabe 4](#Aufgabe-4---Zertifikat-UBS)
- [X] [Aufgabe 5](#Aufgabe-5---Zertifikat-TBZ)
- [X] [Aufgabe 5](#Aufgabe-6---Zertifikat-Example)

- [X] [Reflexion](#Reflexion)

### Aufgabe 1 - Public-Key verifizieren

1. Wie kann ich einen Public-Key verifizieren? Die Public-Key-Verifizierung ist ein wichtiger Schritt, um sicherzustellen, dass ein öffentlicher Schlüssel tatsächlich zu einer bestimmten Person oder einem Gerät gehört. Hier sind die grundlegenden Schritte zur Verifizierung eines Public Keys:

Erhalten des öffentlichen Schlüssels: Zuerst benötigen Sie den öffentlichen Schlüssel, den Sie verifizieren möchten. Dieser kann von der betreffenden Person oder Organisation stammen.
Überprüfung der Quelle: Stellen Sie sicher, dass der öffentliche Schlüssel von einer vertrauenswürdigen Quelle stammt. Wenn Sie den Schlüssel von einer Website herunterladen, überprüfen Sie die URL und verwenden Sie eine sichere Verbindung (HTTPS).
Fingerabdruck überprüfen: Jeder öffentliche Schlüssel hat einen eindeutigen Fingerabdruck. Vergleichen Sie den Fingerabdruck des erhaltenen Schlüssels mit dem Fingerabdruck, der von der Quelle bereitgestellt wurde. Wenn sie übereinstimmen, ist der Schlüssel wahrscheinlich gültig.
Zertifikate verwenden: In einigen Fällen werden öffentliche Schlüssel in digitalen Zertifikaten verpackt. Diese Zertifikate werden von Certificate Authorities (CAs) ausgestellt und können die Authentizität des Schlüssels bestätigen.

### Aufgabe 2 - Public Key Infrastruktur

2. Was versteht man unter Public Key Infrastruktur (PKI)? Die Public Key Infrastruktur (PKI) ist ein Framework für Verschlüsselungsvorgänge, das digitale Kommunikation schützt und authentifiziert. Hier sind die Hauptbestandteile einer PKI:

Digitale Zertifikate: Diese verbinden einen öffentlichen Schlüssel mit der Identität eines Users oder Devices.
Certificate Authorities (CAs): Vertrauenswürdige Stellen, die digitale Zertifikate ausstellen und die Identität des Absenders verifizieren.
Öffentliche Schlüssel: Werden verwendet, um die Authentizität eines Users oder Devices zu gewährleisten.
Private Schlüssel: Werden zur Entschlüsselung von Nachrichten verwendet.
Die PKI schützt und authentifiziert die Kommunikation zwischen Servern und Usern, sowohl im Web als auch innerhalb von Unternehmen.

### Aufgabe 3 - Certification-Authority und Trust-CenterZertifikat

3. Was bedeutet Certification-Authority (CA) und was Trust-Center (TC)?

Eine Certification Authority (CA) ist eine vertrauenswürdige Einrichtung, die digitale Zertifikate ausstellt und 
die Identitäten von Diensten, Personen oder Organisationen validiert. Sie spielt eine Schlüsselrolle in der PKI.
Ein Trust-Center (TC) ist eine Organisationseinheit innerhalb einer PKI, die digitale Zertifikate ausstellt, 
verteilt und prüft. Es sorgt dafür, dass die Zertifikate vertrauenswürdig sind und die Identität des Absenders bestätigen.

### Aufgabe 4 - Zertifikat UBS

4. Wer hat das Zertifikat für die Bankwebseite www.ubs.com ausgestellt und wie lange ist es gültig?

Das Zertifikat für die Bankwebseite www.ubs.com wurde von der DigiCert Inc ausgestellt und ist 
bis zum Freitag, 13. Dezember 2024 um 00:59:59 gültig.

### Aufgabe 5 - Zertifikat TBZ

5. Wer hat das Zertifikat für die Schulwebseite www.tbz.ch ausgestellt und wie lange ist es gültig?

Das Zertifikat für die Schulwebseite www.tbz.ch wurde von Let's Encrypt ausgestellt und ist bis zum
Sonntag, 30. Juni 2024 um 19:35:24 gültig.

### Aufgabe 6 - Zertifikat Example

6. Wer hat das Zertifikat für die Webseite www.example.ch ausgestellt und wie lange ist es gültig? 

Die Website www.example.ch hat kein TLS-Zertifikat und verwendet nur HTTP und kein HTTPS.


### Reflexion
- Ich habe gelernt wie TLS-Zertifikate funktionieren