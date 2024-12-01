---
layout: default
title: Willkommen
---

# Willkommen zu unserer Hochzeit!

Wir freuen uns sehr, dass ihr unsere Hochzeitswebsite besucht. Hier findet ihr alle wichtigen Informationen zu unserem besonderen Tag:

- **Datum:** 25. Mai 2024  
- **Ort:** Schloss Glücksburg, Hamburg  
- **Zeit:** 14:00 Uhr  

## Wichtige Informationen:
1. **Anmeldung:** Bitte meldet euch über die Seite [Anmeldung](/anmeldung/) an.  
2. **Fahrgemeinschaften:** Ihr könnt uns mitteilen, ob ihr eine Fahrgemeinschaft oder einen Shuttle-Service benötigt.  
3. **Allergien:** Bitte informiert uns über mögliche Allergien, damit wir die Menüplanung entsprechend anpassen können.

---

### Countdown zu unserem großen Tag:
<div id="countdown"></div>
<script>
  const weddingDate = new Date("2024-05-25T14:00:00");
  setInterval(() => {
    const now = new Date();
    const diff = weddingDate - now;
    const days = Math.floor(diff / (1000 * 60 * 60 * 24));
    document.getElementById('countdown').innerText = `${days} Tage bis zu unserer Hochzeit!`;
  }, 1000);
</script>

Vielen Dank, dass ihr diesen besonderen Tag mit uns teilt. Wir freuen uns darauf, euch zu sehen!
