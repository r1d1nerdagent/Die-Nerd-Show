# Kommende Episode

## Offene Themen

Dieses Dokument ist der Arbeitsentwurf fuer die naechste Folge. Links sollten nach Thema oder Unternehmen gruppiert und fuer einen sinnvollen Sendungsfluss sortiert werden, nicht nach Eingang.

### Eingang

Neue Links nur hier ablegen, wenn die passende Themen-Gruppe unklar ist. Sobald die Struktur klarer ist, in einen besseren Abschnitt verschieben.

### AI-Infrastruktur und Chips

- [OpenAI und Broadcom stellen den LLM-Inferenzchip Jalapeno vor](https://openai.com/index/openai-broadcom-jalapeno-inference-chip/) - **Geteilt von:** Manuel. OpenAI und Broadcom zeigen mit Jalapeno OpenAIs ersten eigenen "Intelligence Processor": ein speziell fuer LLM-Inferenz gebauter Beschleuniger, der in neun Monaten bis zum Tape-out kam und ab Ende 2026 in einer mehrjaehrigen Plattform mit Partnern wie Broadcom, Celestica, Microsoft und weiteren Rechenzentrumspartnern im Gigawatt-Massstab ausgerollt werden soll. Erste Tests versprechen deutlich bessere Performance pro Watt als aktuelle Spitzenhardware; Details sollen spaeter folgen.
  **Diskussionswinkel:** OpenAI geht weiter in Richtung vertikal integrierter AI-Fabrik: Modelle, Produkte, Serving-Software, Netzwerke und nun eigene Chips. Spannend ist weniger nur der Chip selbst, sondern die Machtverschiebung in der Infrastruktur: Wer Inferenzkosten, Latenz und Verfuegbarkeit kontrolliert, kontrolliert auch, welche Agenten- und API-Produkte wirtschaftlich skalieren.

### Agenten-Frameworks und Developer Tools

- [OpenAIs Codex kann Arbeitsablaeufe aufzeichnen und als wiederverwendbare Skills wiederholen](https://the-decoder.de/openais-codex-kann-jetzt-arbeitsablaeufe-aufzeichnen-und-als-wiederverwendbare-skills-selbststaendig-wiederholen/) - **Geteilt von:** Carlo M. OpenAI bringt fuer die Codex-App auf macOS `Record & Replay`: Nutzer koennen einen Workflow einmal vormachen, etwa einen Upload mit Metadaten, Thumbnail und Untertiteln, und Codex wandelt ihn in einen wiederverwendbaren Skill um. Die Funktion braucht Computer Use und ist zunaechst nicht in EU, UK und Schweiz verfuegbar; parallel kommen Massenaktionen fuer die Automations-Historie und Thread-Uebergaben zwischen lokalem und entferntem Host.
  **Diskussionswinkel:** Spannend ist der Sprung von Prompt-Automation zu vormachbaren, wiederholbaren Arbeitsablaeufen. Wenn Agenten Skills aus menschlichen Demos bauen, wird Automatisierung fuer Nicht-Programmierer greifbarer, aber auch abhaengiger von Plattform, UI-Stabilitaet, Rechten und der Frage, wie gut man solche aufgezeichneten Skills pruefen, versionieren und begrenzen kann.

### AI-Security und Technologiesouveraenitaet

- [Shashank Joshi relativiert die kursierende Mythos-NSA-Behauptung](https://x.com/shashj/status/2068704535124508717?s=20) ([Economist-Artikel](https://www.economist.com/briefing/2026/06/14/donald-trumps-blocking-of-anthropic-is-capricious-and-chaotic)) - **Geteilt von:** Manuel. Joshi erklaert, dass die viel geteilte Aussage zu Anthropics Mythos aus seinem Economist-Text stammt: Er habe Mark Warner korrekt zitiert, wonach der NSA-Chef gesagt habe, Mythos sei in "almost all" klassifizierte Systeme in Stunden eingedrungen. Zugleich warnt Joshi nun davor, diese Formulierung woertlich zu lesen; vermutlich habe Mythos unter sehr speziellen Bedingungen zusammen mit anderen Tools gearbeitet. Sein Fazit: Das Zitat sollte die Potenz des Systems illustrieren, haette aber mehr Einschraenkungen gebraucht.
  **Diskussionswinkel:** Gute Korrektur gegen AI-Sicherheits-Folklore in Echtzeit. Ein spektakulaeres Zitat kann Exportkontrolle, Modellabschaltung und geopolitische Debatten antreiben, obwohl die operative Bedeutung unklar bleibt. Spannend ist, wie Labs, Medien und Politik ueber Cyberfaehigkeiten von Frontier-Modellen sprechen koennen, ohne entweder Risiken kleinzureden oder aus unvollstaendigen Anekdoten Mythos um Mythos zu bauen.

### Krypto und Post-Quantum-Security

- [Coinbase-Bericht: Sieben Millionen Bitcoin durch Quantencomputer gefaehrdet](https://www.finanzen.net/nachricht/devisen/blockchain-coinbase-bericht-sieben-millionen-bitcoin-durch-quantencomputer-gefaehrdet-15757061) - **Geteilt von:** Sebastian. Finanzen.net greift einen Bericht des Coinbase Quantum Advisory Council auf: Rund 7 Mio. BTC gelten langfristig als quantum-vulnerable, weil Public Keys bei alten P2PK-Adressen oder durch Adress-Wiederverwendung bereits sichtbar sind. Besonders heikel sind etwa 1,7 Mio. BTC in sehr alten P2PK-Adressen, darunter mutmasslich Satoshi-Coins und verlorene Wallets. Es geht nicht um eine akute Attacke morgen, sondern um die Vorbereitung auf post-quantenfaehige Signaturen und die Frage, was mit nicht migrierten oder aufgegebenen Coins passiert.
  **Diskussionswinkel:** Der technische Teil ist loesbar, der soziale nicht: Bitcoin muesste migrieren, ohne zentrale Instanz, ohne klare Eigentuemer vieler alter Coins und ohne Konsens, ob gefaehrdete Coins eingefroren, verbrannt, begrenzt bewegbar oder einfach dem Risiko ueberlassen werden. Das ist ein guter Aufhaenger fuer "Code is law" gegen Realitaet, Governance und Marktvertrauen.

### AgTech und IoT

- [Halter: KI-Halsbaender als virtuelle Zaeune und Fitness-Tracker fuer Kuehe](https://x.com/itsolelehmann/status/2062909345537634686) - **Geteilt von:** Oliver Thylmann. Halters solarbetriebene GPS-Halsbaender lassen Farmer virtuelle Weidegrenzen per App zeichnen, Herden mit Ton- und Vibrationssignalen bewegen und Gesundheit sowie Fortpflanzung einzelner Tiere ueberwachen. Das Unternehmen bestaetigt eine Series E ueber 220 Mio. Dollar bei 2 Mrd. Dollar Bewertung und eine Million verkaufte Halsbaender; neuere Modelle kommunizieren direkt per Satellit.
  **Diskussionswinkel:** Ein starkes Beispiel dafuer, wie AI, Sensorik und SaaS physische Arbeit veraendern: weniger Zaunbau und Kontrollfahrten, dafuer laufende Abos, datenbasierte Tierhaltung und die Frage, wo Automatisierung in Tiersteuerung und Tierwohl kippt.
