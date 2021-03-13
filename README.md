## Praktisk information

Nu hvor serveren **De1-SoC** eller **Charlie** er sat op og kører nogelunde 24//7 (ahah), skal vi interagere med den, dvs forbinde via SSH, FTP eller lignende.

### FTP
Vi bruger FTP til at overføre filer til serveren. Det betyder I skal have installeret et program, som kan gøre den proces nemt for jer. Jeg anbefaler disse programmer:
- **FileZilla** - download her: https://filezilla-project.org/download.php?type=client (jeg benytter personligt denne)
- **WinSCP**  - download: https://winscp.net/download/WinSCP-5.17.10-Setup.exe

#### Forbindelse
Efter I har downloadet en af dem, skal I udfylde disse felter i programmet, for at forbinde til serveren. I kan enten vælge at skrive domainnavnet dev.miew.org I stedet for IP, hvis det er nemmere at huske.
- **Host:** dev.miew.org ELLER 82.211.207.249 
- **Username:** delta
- **Password:** \*\*\*\*\*\*
- **Port:** 21

Når I er forbundet skal I gå ind på: **/home/fweb/App1/** (som er hvor hjemmeside filerne ligger), selvom I har adgang til hele serveren, så venligst begræns jer til denne PATH, så serveren f.eks ikke med en fejl bliver slettet eller lignende... 

### SSH

Vi bruger SSH til at modificere selve Ubuntu styresystem. I bør kun bruge SSH til serveren, hvis I ved hvad I laver, og har en klar intention om årsagen til modificering.  Det er meget nemt at \*\*\*\* systemet op, og desuden er Charlie (De1-SoC) ekstrem langsomt, så hvis nogen skulle lave en fejl kan den både være uopretteligt pga. *sådan er Linux* eller fordi at det vil tage for LANG tid at rette op, pga vi arbejder med en server, som har en processor fra f.Kr.

I kan forbinde via **terminal** eller **cmd**, afhænging af om i Apple-tilhængere eller Windows brugere, ved brug af følgende kommando:

- ssh ubuntu@dev.miew.org 
- ssh ubuntu@82.211.207.249

Efterfølgende skal I skrive et password, som er \*\*\*\*\*

*End of document.*




