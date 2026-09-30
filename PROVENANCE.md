# འབྱུང་ཁུངས — ཡིག་སྒྱུར་འདི་ཇི་ལྟར་བྱུང་བ།

ཡིག་སྒྱུར་འདི་འཕྲུལ་ཆས་ཀྱིས་བྱས། ཚིག་རྐང་རེ་རེ་དེའི་ཧེ་བྷྲུ་ལས་བསྒྱུར། སྒྲིག་གཞི་བྲིས་པ་ཞིག་ལྟར་བྱས།
ཧེ་བྷྲུའི་ཚིག་ནི་གཞི་ཡིན། མཚན་ནི་མཚན་དུ་གནས། རྗེས་མའི་ཚིག་རྐང་སྔ་མས་མི་ཤེས། ཏ་ན་ཁ་ཁོ་ན།

ཚིག་རྐང་རེ་རེ་ལ་ངོས་གཉིས་ཡོད། ཧེ་བྷྲུའི་ཚིག་རེ་རེའི་ཚིག་འགྲེལ་དང་། བོད་སྐད་ཀྱི་ཚིག་གྲུབ། གཉིས་ཀ་ཉར།
གང་ཡིན་ཞེ་ན། གཉིས་མི་མཐུན་ན་ནོར་འཁྲུལ་ཞིག་ཡོད།

ཤེས་ཟིན་པའི་ནོར་འཁྲུལ་ `NOTES.md` ནང་ཡོད།

---

## English — how this rendering came to be

*Tibetan (བོད་ཡིག). Floor 23,213 verses. First pass 2026-09-30.*

This is the record of how the text in this repository was produced and what is known
to be wrong in it. A machine-assisted rendering has no standing unless you can see
how it was made, so this file says both.

### The approach

Every verse is rendered from the Hebrew of that verse, under a written discipline —
`docs/methodology/translation-discipline/bo.md` in the Selah project. The rules: the
Hebrew token is the unit; the Name stays the Name; no foreknowledge, so Genesis 22:1
does not know Genesis 22:13; add nothing the text does not say and remove nothing it
does say (the plural of Genesis 1:26 stays plural); the Tanakh only, with no New
Testament vocabulary reaching back into it; no translator's notes.

Each verse produces two surfaces: a **gloss per Hebrew token**, and a **flow** — the
verse as a Tibetan sentence. Both are kept, because they can disagree, and where they
disagree something is wrong.

### The register — transliterate

Tibetan poses a question no earlier chair of this project posed so sharply: nearly
all of its religious vocabulary was coined to render Sanskrit Buddhist terms, so the
nearest Tibetan word for *law*, *holy*, *covenant* or *prophet* arrives carrying a
Buddhist meaning. The ruling for this chair, and for every chair after it, was:
**"Expose what is hidden, reveal the name of God, transliterate."** So the Name is
`ཡ་ཧ་ཝེ`, and the load-bearing words are carried in Tibetan script in their Hebrew
sound (`ཏོ་ར` · `ཀོ་དེ་ཤ` · `བེ་རིད` · `རུ་ཨ་ཁ` · `ཧེ་སེད` and the rest — see
`README.md`). The test is not *does a Tibetan word exist* but *what does it bring
with it*.

### What held

**The Name.** `ཡ་ཧ་ཝེ` stands in the Name's seat throughout, in the honorific
register, and **no title** — `དཀོན་མཆོག`, `གཙོ་བོ` — ever stands in its place. The
exceptions are a handful of verses where `ཨེ་ལོ་ཧིམ` was written where the Hebrew has
`יהוה`; they are listed in `NOTES.md`.

**`ཧེ་སེད` in every seat of `חסד`**, including every line of Psalm 136. **`ཏོ་ར`
in every seat of `תורה`.** **Genesis 1:26 keeps its plural** — `རང་རེའི`, *our*,
inclusive, twice.

**Passages worth naming.** Proverbs 25:2 kept its chiasm: the same `གཟི་བརྗིད` for
both occurrences of `כבד` and the same `དོན་གཅིག` for both of `דבר`, so the mirror
survives into Tibetan. Isaiah 30:15 carries `ཨ་དོ་ནའི་ཡ་ཧ་ཝེ་ཡི་སི་ར་ཨེལ་གྱི་ཀོ་དེ་ཤ`
— *Adonai Yahweh, the Holy One of Israel* — every ruled form in one line. Where a
creature had no Tibetan name, the text often carried it in Hebrew sound rather than
guess: Leviticus 11:19's stork, heron, hoopoe and bat are `ཧ་སི་ད` · `ཨ་ན་ཕ` ·
`དུ་ཁི་ཕཏ` · `ཨ་ཏ་ལཕ`.

### What had to be pinned

Several terms were fixed in the discipline document while the first pass was under
way, each because a verse showed the need:

- the Sabbath to one spelling, `ཤ་བད`, after it had come back in four — and once as
  `བདེ་ཆེན`, tantric bliss (Exodus 20:8);
- `מנחה` as `མིན་ཧ`, after the offering of Leviticus 2 had become a *torma*;
- `לאמר` *saying* as `ཞེས`, after Exodus 20:1 had used the buddha-prophecy `ལུང་བསྟན`;
- `מול` *circumcise* as `གཅོད`, `ירש` *possess* as `དབང་དུ་བྱེད`, `גוים` *the
  nations* as `མི་རིགས`, after all three had come back as words built on `ཆོས`;
- the verb `נבא` *prophesy* as `ན་བིའི་ཚིག་སྨྲ` (1 Samuel 19:20);
- `משפט` as `ཁྲིམས`, or `ལུགས་སྲོལ` where it means *custom* (2 Kings 11:14, 17:33);
- `צבאות` as `ཙེ་བ་ཨོད` beside the Name with nothing between, after Micah 4:4 had
  added a *lord of the armies* the Hebrew does not have;
- one spelling for every frequent name, from the text's own majority form, after
  Israel had come back in a dozen;
- `ཡེ་ཤེས` (*jñāna*) forbidden for `חכמה`.

Verses rendered before a pin keep the older form until they are rendered again;
they are the first entries in `NOTES.md`.

### What is known to be wrong

See `NOTES.md` — every verse found at fault, with the fault named. In brief: a few
verses whose flow came back in English or as broken fragments; English words inside
`⟨…⟩` brackets; Buddhist terms of art in verses rendered before their pin; one
reversal (Ecclesiastes 4:1, *the oppressed* read as *the oppressors*); one added
clause (Psalm 107:28); and the vocabulary of wild animals, which is the weakest part.

### The ear

No reader of Tibetan has yet read this text. Its checks are the canonical forms in
the discipline document and a gate that searches every verse for the forbidden words.
**Any Tibetan reader who comes outranks all of it.**

### Where the Hebrew came from

The consonantal text with its pointing, token by token, from the open editions of the
Hebrew Bible — **UXLC 2.5 as the primary witness.**
