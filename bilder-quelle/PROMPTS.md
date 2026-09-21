# Vier Bilder fuer den Sofortbild-Stapel — Fassung 5

Gesucht: **dieselbe Familie, derselbe Strand, vier Jahre** (2023-2026).
Die Botschaft ist nicht "immer dasselbe Bild", sondern: **Menschen und Dinge
altern.** Kinder wachsen, Eltern veraendern sich, Gegenstaende nutzen sich ab.

Fest bleiben nur drei Sachen: **der Ort, der Abstand der Kamera und die
Tageszeit.** Alles andere bewegt sich — wer wo sitzt, wie sie sitzen, wo die
Sachen liegen.

## Was in Fassung 4 schiefging

"A family of four" reicht nicht. Ein Werkzeug hat daraus **eine Mutter mit
drei Kindern** gemacht — die Zahl stimmte, die Besetzung nicht. Deshalb steht
jetzt am Anfang eine **Besetzungsliste mit vier einzeln beschriebenen
Personen** und am Ende eine **Ausschlussliste**. Beide Bloecke gehoeren in
**jeden** der vier Aufrufe, unveraendert.

## Vorgehen

1. **Bild 2023 erzeugen**: Block A (Besetzung) + B (Ort) + C (Kamera) +
   D (Stil) + Jahresblock 2023 + E (Ausschluss).
2. Dieses Bild dem Werkzeug **als Referenz mitgeben**, dann 2024, 2025, 2026
   daraus ableiten — jedes Mal wieder mit den Bloecken A bis E.
   Geht bei Gemini/Nano Banana, GPT-Image und Midjourney (`--cref`).
3. Ablegen als `2023.png` ... `2026.png` (auch .jpg/.webp), hier im Ordner.
4. `bash Web/stapelbilder-einsetzen.sh`

**Technisch:** quadratisch (1:1), mindestens 1024 x 1024, kein Text, kein
Wasserzeichen. Die Bilder erscheinen auf der Seite nur **163 px** gross —
deshalb halbnah, nicht Ganzkoerper.

**Wenn das Werkzeug lange Prompts kuerzt:** Block A und E niemals kuerzen.
Eher die Stilzeilen aus D weglassen.

---

## Block A — Besetzung (unveraendert in jedem Aufruf)

    CAST — exactly four people in the picture, no more, no fewer:

    1. THE MOTHER — an adult woman, 33 years old in 2023. Mediterranean
       colouring, olive skin, oval face, dark brown almost black hair, warm
       brown eyes, a narrow straight nose, a small dark beauty spot on her
       left cheekbone, 1.68 m, slim build. She wears a plain gold wedding
       band on her left hand.

    2. THE FATHER — an adult man, 36 years old in 2023, clearly older than
       the children and the same age bracket as the mother. Lighter skin than
       hers, light brown hair, grey-green eyes, a broad square jaw, freckles
       on his forearms, 1.85 m, heavy-set, broad shoulders. He wears the
       matching plain gold wedding band. He is the children's father and the
       mother's husband; the two adults are a couple.

    3. THE DAUGHTER — a girl, 3 years old and 95 cm tall in 2023: a toddler,
       not a schoolgirl and not a teenager. Toddler body proportions — large
       head, round belly, short legs. She has her mother's dark hair but two
       shades lighter, brown eyes, round cheeks, a small gap between her
       front teeth.

    4. THE SON — a boy, 6 months old in 2023: an infant who cannot yet stand,
       carried in his mother's arms. Fine light hair, his father's grey-green
       eyes, a birthmark the size of a coin on his right thigh.

    These same four people, and only these four, appear in every image. The
    two adults are the parents; the two children are their small children.
    Ages and heights are given for every year below and must be followed —
    they are the whole point of the series.

## Block B — Ort (unveraendert in jedem Aufruf)

    SETTING — the same small stretch of Mediterranean beach every year, at
    the foot of the same weathered grey wooden staircase that leads down from
    the dunes: eight steps, a handrail worn smooth, dry grass on the dune
    behind it. Fine pale sand, calm sea, a pale flat horizon. Late afternoon,
    an hour before sunset.

## Block C — Kamera (unveraendert in jedem Aufruf)

    CAMERA — square 1:1 crop, phone camera, roughly 28 mm, held at the
    eye level of a standing adult, about four metres from the family, the
    staircase always on the right-hand third of the frame. Half-length
    composition: the family fills the frame from edge to edge, cropped just
    above the heads and just below the knees. The children are large in the
    frame.

    Low golden sun off the sea from the left, long soft shadows to the right,
    a little lens flare.

## Block D — Stil (unveraendert in jedem Aufruf)

    STYLE — a real family snapshot from a phone gallery, not a studio or
    stock photograph. Completely unposed: someone laughs with their eyes
    closed, one child looks at the other instead of at the camera, someone is
    half out of frame, nobody is arranged. Slightly soft focus, fine grain,
    warm faded colours, imperfect framing.

    Everyone is dressed for a day at the beach — t-shirts and shorts, a towel
    around someone's shoulders. Salt-damp hair, sand on knees and forearms,
    bare feet.

    Every year they sit somewhere else and do something else; their things
    are never where they were the year before. This is not a yearly ritual
    photograph — it is four ordinary afternoons that happen to be in the same
    place.

---

## Die vier Jahresblocke

### 2023

    THIS YEAR — the mother is 33, the father 36, the daughter 3 years old and
    95 cm tall, the son 6 months old. Both children are very small: the girl
    reaches just above her standing father's hip.

    The mother's hair is long, loose and windblown; a fresh sunburn across
    her shoulders; bare wrists apart from the wedding band. The father is
    clean-shaven with thick hair and a full hairline, the same scratched
    tortoiseshell sunglasses pushed up on his head. Both look young and a
    little worn out.

    They sit low on a brand-new blue-and-white striped picnic blanket spread
    flat on the sand at the foot of the stairs. The mother holds the baby boy
    against her chest, one tiny bare foot showing. The daughter stands at the
    left edge of the frame, her head just below her seated mother's shoulder,
    short wispy hair, a smear of melted ice cream on her cheek. A brand-new
    bright red plastic bucket stands upright in the sand in the foreground.

### 2024

    THIS YEAR — one year later. The mother is 34, the father 37, the daughter
    4 years old and 103 cm tall, the son 18 months old and 81 cm tall — a
    toddler who has just learned to walk.

    The mother has cut her hair short into a blunt bob and wears a thin gold
    necklace she did not have before. The father has grown a short beard and
    his nose is peeling from sunburn.

    They are sitting on the lower steps of the staircase this time, the
    blanket — already a shade paler — bundled up beside them. The daughter
    sits two steps above the others, visibly taller than last year, hair
    longer, a plaster on one knee and a fresh graze on the other shin. The
    son stands unsteadily in the sand in a sun hat and shorts, holding his
    father's hand, chubby legs dusted with sand. The red bucket lies on its
    side behind them, scratched, half full of shells.

### 2025

    THIS YEAR — two years later. The mother is 35, the father 38, the
    daughter 5 years old and 110 cm tall, the son 2 and a half and 92 cm
    tall — still a toddler, still round-faced.

    The mother's hair has grown back to her shoulders, one grey strand at her
    temple, more freckles across her nose, a small new tattoo on the inside
    of her left wrist. The father now has a full beard with the first grey at
    the chin and has put on a little weight.

    They have moved further right, close to the water line. The father lies
    half propped on one elbow in the sand; the faded blanket is rumpled and
    half covered in sand. The daughter crouches over something she found —
    slimmer face now, long hair in a salt-stiff braid, a missing front tooth,
    a small pale scar through her left eyebrow, sunburnt shoulders. The son
    sits on his father's stomach clutching a small stuffed rabbit, sand stuck
    to one wet cheek. The bucket, bleached to pale pink with a bent handle,
    is jammed upside down in the sand at the left edge.

### 2026

    THIS YEAR — three years later. The mother is 36, the father 39, the
    daughter 6 years old and 117 cm tall — school-age at last, a head taller
    than in 2023 — and the son 3 and a half and 100 cm tall, still a small
    child.

    The mother's hair is long again, tied up carelessly, laughter lines
    around her eyes, the sunburn replaced by an even tan. The father's beard
    is trimmed short and clearly grey at the sides, his hairline a little
    higher, reading glasses hooked into the neck of his t-shirt.

    Nobody sits on the blanket this year — it hangs over the handrail, pale
    and frayed at the edge. The daughter is caught mid-jump off the bottom
    step, clearly school-age now, a head taller than in 2023 and level with
    her seated father's eyes, long legs, scabbed knees, a frayed friendship
    bracelet on her wrist. The son stands on his own holding the same stuffed
    rabbit, now grey, worn and missing one ear. The parents sit in the sand
    watching her, leaning into each other. The old red bucket lies cracked
    and forgotten at the back right.

---

## Block E — Ausschluss (unveraendert in jedem Aufruf)

    DO NOT INCLUDE — no third child, no additional children of any age. No
    grandparents, no friends, no other adults, no other beachgoers, nobody in
    the background, no dogs, no boats. Not a single-parent family: both a
    mother and a father are present in every image. No text, no watermark, no
    logo, no date stamp, no border, no collage, no split screen, no
    before-and-after layout. Not a studio portrait, not stock photography, no
    perfect hair, no matching outfits, nobody looking into the camera and
    smiling on cue.

---

## Warum diese Details

Vier Dinge altern **neben** den Menschen mit und sind auf 163 px noch
erkennbar, wo ein Gesichtszug es nicht mehr ist:

| Gegenstand | 2023 | 2024 | 2025 | 2026 |
|---|---|---|---|---|
| Decke | neu, glatt ausgebreitet | blasser, zusammengeknuellt | zerknittert, sandig | ausgeblichen, ausgefranst, ueberm Gelaender |
| Eimer | leuchtend rot, aufrecht | zerkratzt, umgekippt | rosa ausgebleicht, Henkel krumm | gesprungen, vergessen |
| Stoffhase | — | — | neu, im Arm | grau, ein Ohr fehlt |
| Wo sie sind | auf der Decke | auf den Stufen | am Wassersaum | im Sprung von der Treppe |

Der **Massstab fuers Alter** ist jedes Mal derselbe: die Groesse des Kindes im
Verhaeltnis zu den sitzenden Eltern. 2023 unterhalb der Schulter der Mutter,
2026 auf Augenhoehe des Vaters. Daran liest man Jahre ab, am Gesicht nicht.

Bei den Eltern laeuft es mit: Haare lang - kurz - wieder lang; glatt rasiert -
Bart - grauer Bart - gestutzt; dazu Kette, Tattoo, Lesebrille, Lachfalten.
Nichts davon ist ein Ereignis. Genau das ist der Punkt.

## Kennzeichnung

Kuenstlich erzeugte Bilder, die echt wirken, sind seit dem 2. August 2026 nach
der EU-KI-Verordnung (Art. 50) zu kennzeichnen. Unter dem Stapel kommt deshalb
eine kleine Zeile "Beispielbilder, kuenstlich erzeugt", in allen drei Sprachen.
(Einschaetzung, keine Rechtsberatung.)

---

# Zwei Motive fuer die Werbebilder

Beide zeigen **dieselbe Familie** wie die Vierer-Reihe — das Bild **2023 als
Referenz mitgeben**. Sie liegen als ganzflaechiger Grund hinter dem Text,
deshalb **Hochformat** und viel ruhige Flaeche oben und unten.

Ablegen als `brief-schreiben.png` und `geschenk.png` in diesem Ordner.

## 1. "Ein Brief an spaeter" — story-03 (Hochformat 9:16)

    Create a portrait 9:16 photograph, at least 1024 x 1820 pixels.
    Same family as in the reference image, three years later.

    THE MOMENT — late evening, long after the children are asleep. The
    mother, now 36, sits alone at the kitchen table in the warm pool of a
    single lamp, writing on her phone with both thumbs. Her hair is tied up
    carelessly, she is in a worn t-shirt, bare feet on the chair rung. A cold
    cup of tea, a child's drawing held to the fridge behind her, one toy left
    on the floor at the edge of the frame. The rest of the room is dark.

    She is not smiling for anyone. She is concentrating, a little tired,
    somewhere between the day that just ended and something she wants to say
    later.

    COMPOSITION — she sits in the lower third, the dark room fills the upper
    half: room for a headline above her and a line of text below. Shot from
    across the table, slightly to the side, never straight on.

    STYLE — a real photo taken by someone else in the room, not a staged
    one. Warm lamplight, deep shadows, fine grain, slight motion blur in her
    hands. Not a stock photo, no perfect kitchen, no styled props.

    DO NOT INCLUDE — no other adults, no visible children, no text on the
    phone screen, no readable writing anywhere, no watermark, no logo, no
    date stamp, nobody looking into the camera.

## 2. "Das schoenste Geschenk fuer dein Kind?" — beitrag-02 (Hochformat 3:4)

    Create a portrait 3:4 photograph, at least 1024 x 1365 pixels.
    Same family as in the reference image, three years later.

    THE MOMENT — a child's bedroom at night, lit only by a small nightlight.
    The son, now 3 and a half, is asleep on his side, one arm around the same
    grey stuffed rabbit, now worn and missing an ear. His father sits on the
    edge of the bed in the half-dark, phone in one hand, the other hand
    resting on the blanket near the boy's back. The father's face is lit from
    below by the screen; his beard is trimmed short and grey at the sides.

    He is looking at the sleeping child, not at the phone.

    COMPOSITION — the bed runs across the lower two-thirds, dark wall above
    with room for a headline. The child in the foreground, the father behind
    and slightly out of focus.

    STYLE — a real photo from a phone gallery: high ISO, visible grain, warm
    orange nightlight, deep shadows, slightly soft. Not a stock photo, no
    designer nursery.

    DO NOT INCLUDE — no other children, no other adults, no text on the phone
    screen, no readable writing, no watermark, no logo, no date stamp, nobody
    looking into the camera, nothing cute or posed.
