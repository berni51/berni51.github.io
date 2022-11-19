
Meine persönliche Unix-Story

Erlebnisse mit einem Betriebssystem

        	
        Die Anfänge

        MINIX auf XT und AT

        XENIX 286 -- das erste echte OS

        XENIX 386 -- jetzt mit 32 Bit

        UNIX Emulation mit Mortic Kern's MKS

        UNIX für 68K - MINIX ST

        Coherent 2.0 auf dem Laptop

        Ein echter Profi -- SCO UNIX 3.2

        Interactive UNIX -- ein Klassiker

        Stop -- so geht das nicht weiter !

        Das freie Unix -- LinuX 0.9

        Es geht immer weiter .....

        Aktueller Stand

        Keine Stories - zurück
        	



Einleitung

Da sitze ich an einem Sonntag Abend im November vor einem etwas betagten PC 386/40 und arbeite mich gelangweilt durch das Betriebssystem, ein ebenfalls älteres Interactive 3.2. Dabei kommen und gehen so ein paar Gedanken.
Im Laufe der letzten Jahre hat man doch so einiges an UNIXen kennengelernt. Welche waren das eigentlich ? Und damit wächst eine Idee: das mit den UNIXen und der eigenen Entwicklung dabei, das müßte man doch mal in Worte fassen. Gedacht, getan.

Und so entstand diese kleine Geschichte. Sie beschreibt ganz einfach, was sich getan hat, seit ich UNIX als Betriebssystem für mich entdeckt habe - nicht mehr und nicht weniger. Wen's interessiert, der mag's lesen, wen nicht, der lege die Blätter zur Seite. Alles klar ?



Die Anfänge (Zurück zum Inhaltsverzeichnis)

Die Geschichte mit und um Computer und damit mit und um UNIX begann im Jahre 1987, am letzten Arbeitstag des Jahres, also so um den 20. Dezember herum. Bis zu diesem Zeitpunkt hatte ich mit der EDV nichts, aber auch wirklich gar nichts im Sinn. Genau genommen hätte man mich damals als einen Bilderstürmer, einen Computerhasser bezeichnen können. Was geschah also an diesem Tag? Kurz vor Feierabend, in eine leichte Festtagsstimmung hinein, kommt der Chef des Hauses. Er trägt 3 kleine kofferartige Gebilde mit sich. Jeder von uns drei Vertriebsleuten bekommt einen mit den Worten:
"Das sind Computer! Beschäftigt euch mal damit, damit kann man einiges machen. Nach den Feiertagen reden wir wieder drüber. Frohes Fest."

Frohes Fest, Chef. Was das nun wieder sollte! Keiner von uns kannte sich mit Computern aus. Naja, das Gerät gepackt und ab nach Hause.

Nun hatte ich wahrlich besseres zu tun, als mich während der Feiertage mit dem Computer zu befassen - dachte ich. Aber es kam anders. Mieses Wetter, grau und trüb, veranlaßten mich dann nach 2 Tagen doch, den Computer auszupacken. Es handelte sich um einen Zenith XT mit 4,77 MHz Taktfrequenz, 640 KB Arbeitsspeicher, 10 MB Festplatte und einer 3,5 Inch Floppy. Eingeschaltet und abgewartet. Seltsame Worte und Sätze, ähnlich den Merseburger Zaubersprüchen, zogen an den Augen vorbei, bis der Vorgang dann zum Stillstand kam und ein tabellenartiges Gebilde mit vielen undurchsichtigen Buchstaben und Zahlen zeigt. Später wußte ich, daß dies 1dirPlus war, der Renner unter den Oberflächen der damaligen Zeit.

Machen wirs kurz: nach weiteren zwei Tagen konnte ich so ein ganz kleines bißchen was tun mit dem Computer. Oh nein, nichts sinnvolles. Aber Programme aufrufen, dieselben durch Druck auf den Reset-Knopf wieder verlassen und manche Dateien konnte ich gar lesen. Wiederum zwei Tage später hatte ich es geschafft: der Rechner bootete nicht mehr: kein Kommandointerpreter. Oha!

Inzwischen waren die Feiertage vorbei. Der PC-Spezialist der Firma konnte den Zenith wieder zum Laufen bringen, wobei er sehr geheimnisvoll tat. Aber durch diese Sache war doch der Ehrgeiz erwacht. Als wenn ich mit Computern nicht klar käme - wollen doch mal sehen .....

So kam ich also zur Computerei, mit etwas Zwang und etwas Ehrgeiz. Nach einem halben Jahr, daß ich in Gesellschaft mit Larry Laffer verbrachte, einem kleinen Pixelmännchen aus Las Vegas, kaufte ich mir den ersten eigenen Computer. Auch einen XT, aber einen Turbo-XT. Und gleich am ersten Tag wurde der aufgerüstet mit CO-Prozessor, mehr Hauptspeicher, einer Filecard, einer Reset-Taste. Irgendwie war das der Anfang vom Ende - sagt meine Gattin Heidlinde zumindest.



MINIX auf XT und AT (Zurück zum Inhaltsverzeichnis)

Ist doch sonderbar: bereits nach wenigen Monaten, nach nichtmal ganz einem Jahr, begann MS-DOS mich zu langweilen. Als Späteinsteiger kam ich im hohen Alter von 35 Jahren zur EDV. Start natürlich mit DOS, Anfangs Version 3.2. Aber wie eingangs erwähnt: es beginnt schnell furchtbar langweilig zu werden. Sicher, die Anwendungen sind OK: Multiplan, WordPerfect, dBase usw. Aber der Forschungsdrang zum Betriebssystem selber ist bald befriedigt, nur zu bald.

Ich weiß gar nicht mehr, wann und wo der Begriff UNIX zum ersten mal auftaucht. Aber gut in Erinnerung ist der Hinweis eines Bekannten, der mir nebenbei Pascal beibringt. Er hätte da was: ein UNIX auf Disketten, 3 an der Zahl. Da im Format 360 KB, war es sogar für den XT geeignet. Damals arbeitete ich mit einem Schneider PC1512, 640 KB RAM, einer 20 MB Filecard und einem Coprozessor 8087. Naja, Disketten kopiert und dann zu Hause mal davon gebootet.

Booting the MINIX System .....

Booting the MINIX System war die erste Meldung. Danach wurde das Root Filesystem, ebenfalls von Diskette, gemountet. Und damit hatte ich in der Tat ein kleines UNIX auf dem PC. Nach einigen Tagen voller interessanter aber manchmal auch etwas frustriender Erlebnisse mit MINIX erst mal eine Bestellung beim örtlichen Buchhändler: "OPERATING SYSTEMS - Design and Implemantation" von Andrew Tanenbaum war von da an für die nächsten Wochen eine allabendliche Pfichtlektüre.

MINIX bot wirklich Raum für fantastische Experimente an Betriebssystemen! Der C-Compiler befähigte mich, kleine Programme zu erstellen oder gar vorhandene Dienstprogramme zu modifzieren. Habe jedenfalls eine Menge dabei gelernt. Sicher wäre ich schon damals komplett auf MINIX umgestiegen, wenn das System von der Festplatte aus startbar gewesen wäre. Leider habe ich das nie hingekriegt und habe auch nirgendwo Hinweise dazu gefunden. Das Internet oder Usenet war mir noch nicht bekannt, dort hätte ich womöglich Hilfe bekommen. So war die Diskettenbooterei eine bleibend lästige Sache. Daher blieb MINIX immer das Neben-Betriebsystem.



XENIX 286 - das erste echte OS (Zurück zum Inhaltsverzeichnis)

Der Pascal-Lehrer, im Hauptberuf Informatikstudent, hatte so seine Möglichkeiten! Jedenfalls war da eines Tages ein umfangreicher Diskettenpack mit der Bezeichnung XENIX 286. Gerade war der XT einem AT gewichen, die Festplatte hatte mit 40 MB auch mehr als genug Platz - also frisch gewagt.

So einfach war das allerdings beim ersten mal nicht! Festplatte partitionieren, zunächst wieder DOS installiert und das ganze lauffähig gemacht. Und dann die erste richtige Installation eines echten Operating-Systems! Netterweise hatte jemand die Installation auf einem kleinen Zettel dokumentiert und in winziger Handschrift auf etliche Hürden und Stolpersteine hingewiesen. Die obligatorischen Seriennummern der Pakete waren ebenfalls notiert. Gut gut, heute habe ich da ein Unrechtsbewusstsein entwickelt was Raubkopien betrifft, aber das war seinerzeit noch nicht sonderlich ausgeprägt.

The IBM Personal Computer
XENIX Version 2.0 (c)
Copyright IBM Corp. 1984, 1985 (c)
Copyright Microsoft Corp. 1983, 1984, 1985

Irgendwie hab ich das XENIX 286 zum Laufen bekommen. Und damit begann die Zeit der wirklichen Experimente und Erfahrungen. Ich lernte einen (etwas) besseren C-Compiler kennen, ein ordentliches manpage-System, Dual- Boot Optionen und die große Vielfalt der XENIX Dienstprogramme. Wir hatten eine Menge Spaß zusammen!
Aber natürlich auch eine Menge Frust. Bei Problemen konnte ich niemanden fragen. Auch die Cracks in der Firma schüttelten beim Wort UNIX nur den Kopf. Und dann die Sache mit dem Modem! Ich brauchte Wochen, um mittels cu eine Verbindung zu einem anderen Rechner zu bekommen. Ich weiß es noch wie heute: das war der Rechner veeble in Hannover, damals ein PS/2 von IBM. Wenn ich nur wüßte, woher ich die Telefonnummer hatte. Wie auch immer, auf der veeble lernte ich DAS NETZ kennen, the net. Plötzlich war ich per uucp verbunden mit der veeble, einer Maschine namens krefcom in Krefeld, einem Rechner an der Uni Gießen und verschiedenen Maschinen im Ruhrgebiet. Eine faszinierende Zeit!

Durch einen Umzug in eine sehr große Wohnung war da plötzlich Platz für ein ungewöhnlich großes Arbeitszimmer. Bald war der zweite Schreibtisch aufgestellt und ein verwegener Gedanke keimte auf: man könnte ja ein kleines UNIX-Netz aufbauen mit 2 AT's, auf beiden XENIX 286 installiert und beide mittels uucp seriell verbunden. Es dauerte nur 2-3 Wochen, dann entstand aus einem Original IBM-XT Gehäuse, einem gebrauchten 286/16er Motherboard und diversen Restteilen ein zweiter PC. Auf seinem klassischen Hercules-Grün-Monitor lief bald darauf tatsächlich auch das XENIX Login. Das war mein erster NUR-UNIX-Rechner.

Serielle Vernetzung mit 9600 Baud kann bei reinen ASCII Applikationen eine feine Sache sein. Durch den Einsatz von zig Schnittstellenkarten waren bullet und boerdix, so hießen die Rechner inzwischen, sowohl per uucp als auch per micnet verbunden und kommunizierten aufs feinste.

Über verschlungene Wege fanden 3 Festplatten aus DEC-Maschinen den Weg in mein Büro. Groß und schwer wie Häuser, aber MFM-Verfahren, also geeignet für meine UNIX Maschinen. Plötzlich hatte ich Kapazitäat frei. 70 und 140 MB waren für die damalige Zeit gewaltig viel!

Da in etwa begann auch mein ganz persönlicher Speicherwahn! Ein 286er mit seinem 1 MB bekam eine Speichererweiterungskarte, die voll mit 4 MB bestückt wurde, also lief er mit insgesamt 5 MB - gewaltig! Man bedenke, daß zu jener Zeit die SUN Workstations in unserer Firma auch nur mit 8 MB liefen, und das waren doch echte Maschinen. Bald war auch Rechner Nummer 2 aufgerüstet, der hatte sogar 6 MB Hauptspeicher. Ab und zu fand ich mich auf einem Rechner in den Staaten wieder, in good old Germany war ich auf etlichen hosts zuhause. Sehr gut erinnere ich mich an eine Telefonrechnung von fast 1000,- DM - das wirkte etwas ernüchternd, aber konnte mich nicht wirklich stoppen.
Quellcode bekam ich MB-weise, leider war davon nur ein geringer Teil auf meinen Systemen lauffähig. Der 286er C-Compiler von XENIX hatte da doch seine Grenzen. Aber etliche schöne Programme liefen und wurden intensiv eingesetzt. Das Kalkulations programm sc, eine prima Editor namens gnome, natürlich der emacs, news-reader, eine dBase-kompatible Datenbank, Terminalprogramme und sogar ein BTX-Decoder, also eigentlich alles, was man so brauchte. Für den engeren Freundes- und Bekanntenkreis wurde ein login-Zugang per Modem eingerichtet, über den wir uns gegenseitig Dateien und Nachrichten schickten. Alles lief prima! In der Firma ging bereits der Spruch vom Vogelsberger Rechenzentrum um.



XENIX 386 - jetzt mit 32 Bit (Zurück zum Inhaltsverzeichnis)

Von irgend jemandem meiner virtuellen Bekannten im Netz bekam ich dann ein 386er XENIX. Das zwang mich dazu, die Hardware entsprechend hochzurüsten. Ein 386er SX mit 20 Mhz und zunächst 8 MB Speicher schienen mir die rechte Umgebung zu sein. Dabei wurde auch gleichzeitig ein Tower-Gehäuse eingekauft, um die gewaltigen DEC-Festplatten verschwinden zu lassen. Und endlich kam auch der erste Farbbildschirm. Bei den 8 MB blieb es auch nicht sehr lange - inklusive einer prima BOCA Research Erweiterungskarte bootete mein System bald mit 16 MB. Und das alles mit DIL's bestückt! Kennt noch jemand die RAM-Preise der 80er Jahre ?

Leider zwang mich ein erneuter Umzug in ein deutlich beengteres Arbeitszimmer, sodaß ein Rechner abgegeben wurde - schlimm. So richtig glücklich war ich mit nur einer Maschine, es war boerdix, trotz 386er und Tower und viel Festplattenplatz nicht.
Naja, um ehrlich zu sein, das 386er XENIX war schon erheblich besser. Es war nun viel leichter, freien Quellcode durch den Compiler zu nüdeln. Sogar den GCC bekam ich hier endlich ans Laufen! Nur am X11 bin ich bis zum Schluss gescheitert, das gab Fehlermeldungen gleich seitenweise. Das war dann doch zuviel, und soo der C-Crack war und bin ich ja auch nicht.

XENIX386
login: berni
password: xxxxxxx

Insgesamt war Xenix 386 ein extrem robustes und zuverlässiges Betriebssystem. An Abstürze kann ich mich beim besten Willen nicht erinnern - es lief immer. Schlimmstenfall konnte mal ein Task kippen, aber bekanntlich macht das einem Multitasking-System nicht viel aus. So ein ganz kleiner Wermutstropfen war die Tatsache, daß SCO anscheinend immer etwas anders sein muß als andere. Manchen Quellcode bekam ich nie zum Laufen, während die Netzbekanntschaften mit Interactive, Ma Bells Unix oder ihren Workstation-Unixen damit sehr viel weniger Schwierigkeiten hatten. Trotzdem, auf SCO und Xenix lasse ich auch heute noch nichts kommen. Noch heute arbeite ich u.a. auf SCO-Betriebssystemen.



UNIX Emulation mit Mortic Kern's MKS (Zurück zum Inhaltsverzeichnis)

Wenn schon keine 2 UNIX-Maschinen möglich waren, dann wollte ich wenigstens auf einer Maschine 2 Unixe haben. Von einem netten IBM-ler bekam ich eine Version des Unix-Emulators von Mortice Kern, also ein MKS-Unix. Es handelte sich dabei um einen Aufsatz für DOS. Er konnte aber doch so realistisch konfguriert werden, daß ein Außenstehender den faulen Trick nicht so schnell bemerkte. Anstelle von command.com wurde gleich sh.exe als Kommandointerpreter geladen. Mithilfe der vielen mitgelieferten Unix-Kommandos und etlichen selbstgeschriebenen Shellscripten war eine sehr Unix--ähnliche Umgebung geschaffen, sogar mit Passwortabfrage, login und einem cc nachempfundenen Entwicklungssystem.

Natürlich war dabei von Multitasking oder Multiuser keine Spur. Aber man konnte doch einiges dabei lernen, vor allem über die Kornshell- und Shellprogrammierung.
Mit ein paar Büchern aus dem Hanser-Verlag und vielen durchwachten Nächten kamen da ganz passable Ergebnisse heraus. Allerdings konnte MKS die DOS-typischen Speicherprobleme und Beschränkungen auch nicht umgehen. Das führte immer wieder zu Engpässen und zu der Einsicht, daß auch das beste Sourogat eben nur ein Sourogat ist.



UNIX für 68K - MINIX ST (Zurück zum Inhaltsverzeichnis)

Erneuter Umzug, diesmal wieder aufs Land, in ein kleines Häuschen mit Riesengarten und vor allem mit vernünftigem Arbeitszimmer. Der Umzug erfolgte etappenweise, und gleich bei der ersten Fahrt kam der Computer mit. Nach dem provisorischen Einzug war ich zunächst mal ein paar Wochen so eine Art Strohwitwer: zur Gattin gings nur am Wochenende, um den endgültigen Umzug vorzubereiten. Einsame Abende verbringt man am besten wo? Genau, am Computer.

Mein Bruder machte schon seit längerer Zeit Musik mit Computerhilfe. Die Maschinen dabei waren von Atari. Von ihm bekam ich einen MEGA 2 vermittelt. Meine Absichten waren klar: keine Atari-Anwendungen, keine Musik, nein, auf dem Atari sollte ein Unix laufen. Das erste Betriebssystem wurde gekauft - es war wieder ein MINIX von Andy Tanenbaum, aber eben für den Atari.

Nach abenteuerlicher Installation war es soweit: der Atari bootete MINIX von der Festplatte. Schnell war erkannt, daß hier erstmal mehr Speicher hermußte. Schonmal einen Atari aufgemacht und aufgerüstet? Naja, da lob ich mir doch die PC's. Nichts paßte so richtig, sogar der Lötkolben mußte angeworfen werden. Und ein TTL-Grab ohnegleichen! Aber letzendlich war es doch geschafft, der Rechner hatte 4 MB, einen CO-Prozessor und sein Unix.

Booting MINIX 1.1 ..........

Gut, MINIX steht ja für Mini-Unix, also darf man nicht zuviel erwarten. Der Compiler ist doch eher mäßig, das Filesystem auch nicht das allerschnellste. Aber es war ein Unix, etwa auf dem Stand von System 7.
Unix, jedes Unix, sollte jedoch kommunizieren können mit anderen Systemen, und das konnte auch Minix. Gegenseitiges Einloggem über die seriellen Schnittstellen zwischen Minix und Xenix war schnell installiert. Mail Transport und uucp dauerten schon etwas länger. Das Minix uucp war ein wenig rudimentär, aber doch einsetzbar.

So nach und nach entstand aber auch wieder ein zweiter PC, ein echter 386er. Der bekam ebenfalls ein Xenix auf die Platte. Und nahezu gleichzeitig brachte mir ein alter Bekannter eine Kombiladung.
" Hier haste 3 Computer, sind bei uns in der Firma ausgemustert worden. Kosten nichts"
Nun, es waren keine Computer, sondern 3 ASCII-Terminals. 2 davon uralte von Data General, rund und groß wie vom Raumschiff Enterprise. Das dritte war ein recht modernes Ampex. Ein Data General und das Ampex bekam ich tatsächlich zum Laufen ... von einem alten Elektriker kann man das ja auch erwarten. Eines wurde an den Atari gehängt, das andere an boerdix, den Xenix-Rechner. Sah toll aus! 2 PC's, ein Atari und 2 Terminals, auf allen prangte der Prompt - das Dollarzeichen . Und alles war irgendwie seriell verbunden. Wir konnten mit 5 Leuten zusammensitzen und prima arbeiten, wobei der Atari vielleicht nicht ganzso überzeugend fott war. Am besten war es, wenn man den Atari als Terminal benutzte .....

Böse Zungen sprachen schon wieder vom Oberhessischen Gebietsrechenzentrum im Grünen. 2 Modeme stellten den Kontakt mit der Außenwelt sicher, eines zum Einwählen, das andere holte sich regelmäßig mail und news aus der Gegend von Mannheim und verteilte alles auf die Rechner. Da war sie wieder, diese heterogene Unix-Umgebung, und sie lief nach ein wenig Anpassung wunderbar stabil und rund.



Coherent 2.0 auf dem Laptop (Zurück zum Inhaltsverzeichnis)

Sicher, zuwenige Maschinen hatte ich nicht. Trotzdem konnte ich nicht nein sagen, als mir ein 286er Amstrad Laptop angeboten wurde. Der Preis ließ keine Absage zu. Mit 4 MB RAM und 40 MB Festplatte schien er mir wie vorbestimmt für eine portable Unix-Maschine. Am Arbeitsplatz hatte ich kurz vorher eine Vorführung gesehen. Dabei wurde eine Bürosoftware auf einem Toshiba Laptop unter SCO Unix gezeigt - war wirklich super.

Mein Amstrad sollte ein Coherent 286 bekommen. Braucht wenig an Ressourcen und war mal wieder was neues zum dazulernen. Gesagt, bestellt. Installation für ein Unix sehr einfach und sauber. Daß man mir die falsche Seriennummer dazu mitgeteilt hatte war weniger schön. Aber ein Anruf nach dem Wochenende, und das Problem war vom Tisch.

Das allerwichtigste war und ist mir immer der Anschluß neuer Maschinen ans eigene Unix Netz. Auch das mit Coherent kein Problem. Nur schnell ein Loch in die Decke gebohrt, das serielle Kabel vom Arbeitszimmer im Keller ins Wohnzimmer gezogen und schon konnte ich auch im Kreise der Lieben mit meinen Rechnern kommunizieren.

Neben dem Betriebssystem Coherent waren da noch etliche Disketten mit COHWare. Also Software, teils als Binaries, teils im Quellcode, für Coherent. Sogar Spiele und Norton-ähnliche Shells waren dabei. Einiges davon konnte sogar crosscompiliert unter Xenix zum Laufen gebracht werden. Insgesamt ein echter Gewinn, dieses Coherent.

Damals kam mir erstmals der Gedanke: da gibt es so wunderbare, preisgünstige und dennoch stabile Betriebssysteme. Damit geht Multiuser, Multitasking, Vernetzung ganz phantastisch, sogar in extrem heterogenen Unix-Umgebungen. Und trotzdem setzen die Firmen in den Büros, den Entwicklungslabors, im Außendienst und den Manageretagen DOS und Windows ein. Wieso eigentlich? Wissen sie es vielleicht nicht besser? Oder traut man den Systemen nicht? Oder weil etwas mehr an System-Administration notwendig ist? Wenn ich mir vorstelle, wie unser Büro mit einer Unix-Umgebung perfektioniert werden könnte - naja, lassen wirs gut sein, hat doch eh keinen Sinn.



Ein echter Profi - SCO UNIX 3.2 (Zurück zum Inhaltsverzeichnis)

Im Netz, meinem bevorzugten Aufenthaltsraum, bot jemand sehr günstig ein echtes Unix an, ein SCO Unix, damals das erste und einzige, daß auch den Namen Unix tragen durfte. Mit Entwicklungsumgebung und vor allem mit der gesamten Dokumentation.

Schnell war man sich handelseinig. Die Wartezeit wurde genutzt, um eine Maschine, bullet, prophylaktisch aufzurüsten. 16 MB Speicher, damals zu einem Tiefstpreis, und eine größere Platte waren schnell eingebaut. Und die Installation eines SCO-Produktes machte mir auch keine Schwierigkeiten mehr.

SCO UNIX System V/386 on i80486 Boot :

Der Unterschied zum Xenix 386 war zwar bei meinen Anwendungen nicht soo gewaltig, aber doch spürbar. Wenn hier mal alle Terminals aktiv waren und die User auch echt arbeiteten, statt nur chat und talk und write aufzurufen, war das auch keine Sache mehr, das SCO Unix ging kaum mal in die Knie. Und der Compiler war auch wieder etwas besser geworden. Um diese Zeit herum hörte ich übrigens im Netz erstmalig etwas von einem Projekt namens LINUX, einem freien UNIX-Derivat. Klang sehr interessant, aber reingehängt habe ich mich damals nicht in das Projekt.

Mit SCO Unix konnte ich erstmals völlig auf DOS verzichten. SCO enthielt einen DOS-Emulator namens VpiX, der sehr zuverlässig lief. Datenbankanwendungen unter Clipper entstanden nun in dieser Umgebung.


Interactive UNIX - ein Klassiker (Zurück zum Inhaltsverzeichnis)

Komischerweise hatte SCO im Usenet keinen so guten Ruf. Bei manchen war es nicht als echtes, richtiges Unix akzeptiert. Ich selbst konnte und kann diese Meinung nicht teilen. Sowohl auf die Xenixe als auch auf das SCO Unix lasse ich nichts kommen. Es sind sehr stabile, zuverlässige Systeme, die auch kommerziellen Ansprüchen bestens genügen. Vielleicht fehlt SCO so ein bißchen das Hacker-Image. Aber das ist doch wohl eher positiv, oder?

Jedenfalls bekam ich von einer Netzbekanntschaft ein Interactive Unix 3.2 geschickt, nur zum Probieren. Habs zunächst mal lange liegen lassen. Auf keinen Fall wollte ich meine zuverlässigen Xenix- und SCO Unix-Kisten umbauen. Man weiß ja: never change a running system.

Aber irgendwann begann ich aus Resten einen weiteren PC zusammenzubauen. Das ging schneller als gedacht - was sich so alles ansammelt...
Und das war die richtige Experimentalmaschine für das Interactive Unix. Nach den Erfahrungen der letzten Jahre waren Installation und Konfguration auch kein großes Problem. Zwar war etliches stark abweichend von den SCO Systemen, aber dafür entsprach es viel eher den Angaben in meiner Fachliteratur. Scheint also doch eher das klassische Unix zu sein. Und das Portieren von Software geht auch noch eine Idee einfacher. Als Zusatzpaket war das TCP/IP mit NFS von Lachman enthalten. Zum damaligen Zeitpunkt hatte ich zwar nirgendwo einen Netzwerkadapter installiert, aber dieses Zusatzpaket von Interactive brachte mich auf den Gedanken. Ein wenig reifen mußte er zwar noch, aber die Saat war gelegt.



Stop - so geht das nicht weiter ! (Zurück zum Inhaltsverzeichnis)

Schnitt, Pause! Was treibe ich da eigentlich? In einem winzigen Büro stehen eine Unmenge Rechner und Zubehör. Um das ganze am Laufen zu halten, habe ich quasi ueberhaupt keine Zeit mehr, mit den Maschinen zu arbeiten. Dabei ist da ein Programmier-Projekt, es sind etliche technische Dokumentationen zu erstellen und auch die Hardware fordert ihren Tribut. Schließlich sind doch jede Woche 1-2 Rechner zusammenzuschrauben oder zu reparieren. Irgendwas stimmt hier nicht, das steht fest.
Also: werden wirklich 4 Unixrechner, 2 Terminals und 3 Drucker gebraucht? Und dann für einen User? Das kann nicht sein!

Innerhalb von 2 Wochen ist bis auf zwei Maschinen (bullet und boerdix, die Urrechner) alles verkauft. Ja, das schafft Platz. Wußte garnicht mehr, wie groß das Arbeitszimmer sein kann. Und irgendwie, in dem ganzen abbauen, verkaufen, neu installieren und umkonfgurieren war da der Gedanke: jetzt muß was völlig neues her. Ende vom Lied war, daß die beiden verbliebenen Maschinen als Betriebssystem OS/2 erhielten, damals in der Betaversion von 2.1. Verbunden mit dem LANServer 3.0 ergab das ein tolles grafisches System mit verblüffender Stabilität. Die Anwendungen liefen prima und so wurde aus dem Selbstzweck-UNIX-Netz eine reine Arbeitsumgebung.

So blieb das bis Ende 1994. Allerdings: so der rechte Spaß wie unter UNIX wollte sich mit OS/2 nicht einstellen. Es war eher wie ganz am Anfang mit DOS - alles funktionierte, war aber etwas langweilig. Naja. Arbeitstiere eben, ohne eigene Seele.

Ende 1994 gab es so ein bißchen Luft, der Druck der Arbeit ließ ein wenig nach, sodaß immer öfter der Gedanke an UNIX zurückkam. Und dann, im November, war es mal wieder so weit.


Das freie Unix - LinuX 0.9 (Zurück zum Inhaltsverzeichnis)

Seltsam, daß man ein Betriebssystem sogar irgendwie liebgewinnen kann! Nicht jedes, natürlich nicht. DOS sicher nicht, und auch OS/2 nicht wirklich. Aber alle meine Unixe, selbst die wahrlich nicht perfekten 286er Portierungen und sogar das gute alte MINIX fuer den Atari.
Na, wie auch immer, im Spätherbst 1994 bestellte ich mir eine CD. Sie enthielt die LST 1.8 Distribution mit LinuX 0.9. Zwischenzeitlich war aus LinuX ja etwas wirklich tolles geworden. Ein fertiges und stabiles Betriebssystem , daß zudem noch frei zu bekommen war. Ein Heer von Aktiven im Netz steuerte immer wieder etwas dazu bei. Und dann gabs sogar Anwendungen dafür, und, zum Teil zumindest, was für Anwendungen!

Endlich hatte ich mein Unix wieder. Innerhalb weniger Tage wurden bullet und devox, wie die Maschinen mittlerweile hieien, so umpartitioniert, daß neben OS/2 auch LINUX gebootet werden konnte. Bullet und devox waren immer so ein wenig dem Stand der Technik gefolgt. Beide hatten als Herzstück einen 486/66 Prozessor, 32 MB RAM und mehr als 1 GB Festplattenkapazitaet.

Mit bullet wurde die Anbindung per Modem an einen Internet-Provider realisiert. Ohne netnews und mail ist so ein Unix-System doch nur die Hälfte wert. Rechnerdevox wurde das X11-Arbeitstier. TCP/IP-Vernetzung war selbstverständlich. Eine Maschine stellte 1,2 GB Festplattenkapazität per NFS zur Verfügung. Das Netz daheim stellte inzwischen die SUN-Anlage am Arbeitsplatz in den Schatten - auf jeden Fall hinsichtlich des Preis/Leistungsverhältnisses. Mit Linux wird das Leben nicht langweilig. Versionswechsel, Patches, neue Anwendungen halten den Heimadministrator aktiv.



Es geht immer weiter ..... (Zurück zum Inhaltsverzeichnis)

Und weiter ? Und damit hatte ich es wieder, das gute alte Unix. So ganz nebenbei wurde ein dritter Rechner, mal wieder aus Resten, zusammengebaut. Der sollte als Gateway für die Linux-Kisten dienen. Zunächst bekam er das alte Interactive installiert, daß dann aber irgendwie nicht mehr so recht zufriedenstellen konnte. Also ein SCO Unix drauf. Das lief doch gleich etwas stabiler, was den TCP-stack betraf.

Linux zeigte mir, wie man sehr schnell und einfach ein UNIX-Netzwerk auf der Basis von TCP/IP aufbauen kann. Das hieß also auch bei mir zuhause: Ende der seriellen Vernetzungen.
Die Linux-Maschinen waren wirklich sehr sehr gute Arbeitstiere und brachten dabei auch jede Menge Vergnügen. Trotzdem sieht man mich erstaunlich häufig vor dem SCO Rechner. Mit seinem Pizza-Gehäuse und dem Monochrom-Bildschirm wirkt er aber auch zu putzig. Und es gelingt sogar, die Programme aus alten Zeiten wieder zu beschaffen und zu portieren:

    GNOME, ein prima emacs-like Editor
    TEX, das wunderbare Satz-Programm von Donald Knuth
    SC6.8, die einfache und mächtige Tabellenkalkulation
    FoxPlus, eine Datenbank, die dBase kompatibel ist
    less, mein Lieblings-Viewer
    gcc 2.4.5, DER C-Compiler
    perl 4, ein Interpreter für alle Fälle
    und SCO BackGammon ist sowieso schon dabei
    OK, auch Tetrix....


Da frage ich euch: was braucht der Mensch mehr zum alltäglichen Arbeiten. Ich meine, wenn er auf Grafiken verzichten kann. Das alte 486sx/33 Board läuft doch prächtig mit diesen Programmen. Und 8 MB RAM sind schon fast zuviel......., naja, etwas mehr werden wir vielleicht doch installieren. Für meine Beruf als technischer Redakteur jedenfalls brauche ich nicht mehr. Mit TeX gelingen meiner Meinung nach ohnehin bessere Ergebnisse als mit den graphischenPendants { OK, ist natürlich Geschmacksache.

Natürlich geht die Geschichte weiter. FreeBSD 2.0.5 ist gerade auf Maschine Nr. 4 installiert. Nach einigen Flops mit NetBSD 1.0 ist das mal wieder eine sehr interessante und spannende Sache. Der Kernel müßte mal neu durch den Compiler genüdelt werden, und X11R6 werde ich doch wohl auch zum Laufen bekommen. Und dann kündigt sich die Möglichkeit an, eine echte Workstation zum Gebraucht-PC-Preis zu erstehen. Es ist eine RS6000 von IBM mit AIX, dem etwas anderen Unix. Da werde ich wohl nicht nein sagen können. Oder ein Notebook, so als eine Art Reiseschreibmaschine. Da könnte man dann auf Reisen in der vertrauten LinuX-Umgebung weiterarbeiten. TeX müßte drauf, der emacs, eventuell sogar X11 und xdvi .... mal sehen. Naja, erstmal eine kleine Pause. Die könnte ich doch gut nutzen, mal einen Sprung ins Netz zu machen. OK, tippen wir cu troia ......



Aktueller Stand (Zurück zum Inhaltsverzeichnis)

Jetzt, beim Schreiben dieser Zeilen, sehe ich mich in einem engen Büro um. Was sehe ich:

    Pentium 133 mit 128 MB RAM und FreeBSD 2.2
    Pentium 133 mit 80 MB RAM und SCO OpenServer 5
    Pentium 150 mit 128 MB und Debian-Linux
    Pentium 60 mit 32 MB RAM und FreeBSD 2.2 in einem portablen Gehäuse für Unterwegs(Schlepptop)
    486/80 mit 24 MB RAM und RedHat Linux als Router vom lokalen Netz via ISDN ins Internet
    486/120 mit 64 MB RAM und SCO UnixWare
    286/16 mit 8 MB und Minix


Übertrieben ? Finde ich auch, aber ich kann mich nicht entschließen, auch nur eine Maschine abzugeben.
Naja, das war so bis zum Jahre 1997. Dann fing ich aber langsam an, mich etwas zu beschränken. War ein schwieriger und langer Prozess für mich, aber heute, im Jahre 2006, sitze ich vor einem Mac mini mit dem wunderbaren Mac OS 10 (Ein Unix!) und daneben steht noch ein Averatec Notebook mit Windows. So weit ist es gekommen .....

Heute, im Jahre 2022, muss ich allerdings konstatieren, dass ich wie ein Junkie mehrfach rückfällig geworden bin. Momentan sind in zwei Räumen fast 20 Computer verteilt, dazu offene Mainboards, Minicomputer wie RaspberryPi und BananaPi, Experimentalaufbauten, Ersatzteile - ein Rückfall in schlimmste Zeiten. Aber ich fühle mich gut dabei, so what.
