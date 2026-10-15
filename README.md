# HKC E-Mail-Signatur

Hier findest du die E-Mail-Signatur des Harsewinkler Karnevals Clubs (HKC).

Eine Vorschau der Signatur gibt es hier: [signature.html](https://sgtmate.github.io/hkc-signature/signature.html).

## So nutzt du die Signatur

1. Öffne den folgenden HTML-Code.
2. Ersetze die Platzhalter mit deinen Daten.
3. Kopiere den fertigen Code in deine E-Mail-Signatur im Mailprogramm.

### Was du anpassen musst

- `{{NAME}}` durch deinen Namen ersetzen
- `{{POSITION}}` durch deine Funktion ersetzen
- `{{MAIL_BENUTZER}}` durch deinen HKC-Mailnamen ersetzen
- `{{TELEFON}}` durch deine Telefonnummer ersetzen

Beispiel: Wenn dein Mailname `leon` ist, wird daraus `leon@hkc-harsewinkel.de`.

```html
<table cellpadding="0" cellspacing="0" border="0"
       style="font-family: Arial, Helvetica, sans-serif; font-size: 14px; color: #333333;">
    <tr>
        <td style="vertical-align: top; padding-right: 20px;">

            <p style="margin: 0 0 12px 0;">
                Mit freundlichen Grüßen
            </p>

            <p style="margin: 0;">
                <strong style="font-size: 16px;">{{NAME}}</strong><br>
                <span style="color: #666666;">{{POSITION}}</span>
            </p>

            <p style="margin: 12px 0;">
                <strong>Harsewinkler-Karnevals-Club (HKC) von 2015 e.V.</strong>
            </p>

            <p style="margin: 0; line-height: 1.8;">
                📍 Anton-Linzen-Str. 6 · 33428 Harsewinkel-Marienfeld<br>
                📧 <a href="mailto:{{MAIL_BENUTZER}}@hkc-harsewinkel.de"
                      style="color: #333333; text-decoration: none;">
                      {{MAIL_BENUTZER}}@hkc-harsewinkel.de
                    </a><br>
                📞 {{TELEFON}}<br>
                📸 <a href="https://www.instagram.com/hkc_hsw/"
                      style="color: #333333; text-decoration: none;">
                      @hkc_hsw
                    </a>
            </p>

        </td>

        <td style="vertical-align: top;">
            <br><br>
            <img src="https://sgtmate.github.io/hkc-signature/HKC_logo_Mail.jpg"
                 alt="HKC Logo"
                 width="140"
                 style="display: block; border: 0;">
        </td>
    </tr>
</table>
```

## Für den Vorstand

Für die Vorstandsmitglieder gibt es bereits fertig ausgefüllte Vorlagen im Ordner [vorstand](vorstand).

> Wichtig für Outlook: Bitte nicht den HTML-Code direkt einfügen, sondern die Signatur im Browser öffnen und die formatierte Ansicht daraus kopieren.

Die fertigen Signaturen sind hier direkt im Browser erreichbar:

- [1. Vorsitzender](https://sgtmate.github.io/hkc-signature/vorstand/1-vorsitzender.html)
- [2. Vorsitzender](https://sgtmate.github.io/hkc-signature/vorstand/2-vorsitzender.html)
- [2. Beisitzerin](https://sgtmate.github.io/hkc-signature/vorstand/2-beisitzerin.html)
- [Kassierer](https://sgtmate.github.io/hkc-signature/vorstand/kassierer.html)
- [Schriftführerin](https://sgtmate.github.io/hkc-signature/vorstand/schriftfuehrerin.html)
- [Geschäftsführer](https://sgtmate.github.io/hkc-signature/vorstand/geschaeftsfuehrer.html)
