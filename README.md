# MFA LinOTP  Javascript HD

Das vorliegende Skript ist eine Erweiterung des "Pure JavaScript TOTP Code generator" (https://cable.ayra.ch/totp/) von Kevin Gut, das mit freundlicher Genehmigung in der modifizierten Form bei github bereitgestellt werden darf.

TOTP steht für Time-based one-time password und hierbei wird durch ein vereinbartes Geheimnis (secret) und der Uhrzeit ein Hash-code ereugt, der als zweiter Faktor bei einem Login herangezogen wird. 

Das Skript sollte lokal auf der Festplatte gespeichert werden und erzeugt im Web-Browser gültige MFA-Tokens für die LinOTP  Plattform, nachdem man das Secret übertragen hat. Die LinOTP  Plattform wird mitunter zum Absichern von VPN und anderen Diensten durch einen zweiten Faktor verwendet. Einige Universitäten nutzen inzwischen diese Form des sicheren Logins mit einem zweiten Faktor. 

![ScreenShotSecret](https://github.com/bohnelang/MFA_LinOTP_Javascript_HD/blob/main/secret.jpg)

Das Skript speichert man lokal und beim ersten Öffnen überträgt man das Secret auf dem LinOTP  und anschließend bookmarkt man diese lokal geöffnete Seite. 

Wer das Skript in Betrieb verteilen möchte, kann auch den JavaScript-Code durch einen Verschleierer (Obfuscator) https://www.lddgo.net/en/encrypt/js für Menschen unleserliche machen.

