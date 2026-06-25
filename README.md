# hkc-signature
This Repo contains the email signature related files of the Harsewinkler Karnevals Club (HKC)

## Signatur
Für die Nutzung den folgenden Codeblock bitte im Mailprogramm hinerlegen oder alternativ die [Quelle](https://example.com) verlinken.

```html
<!-- =====================================================
 HKC E-Mail-Signatur
 Nur die Werte in diesem Block anpassen:

 NAME=Leon Kampwerth
 POSITION=Kassierer
 MAIL_BENUTZER=leon
 TELEFON=+49 XXX XXXXXXX
 LOGO_URL=https://sgtmate.github.io/hkc-signature/HKC_logo_Mail.jpg

 Danach ersetzen:
 {{NAME}}
 {{POSITION}}
 {{MAIL_BENUTZER}}
 {{TELEFON}}
 {{LOGO_URL}}
===================================================== -->

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
