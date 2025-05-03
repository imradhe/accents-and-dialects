# Accent–Language Taxonomy

This taxonomy classifies speech data based on two core dimensions:

1. Type of Accent — how a speaker sounds when speaking a language


2. Type of Language Set — the speaker’s relationship to that language (native, fluent, or learning)



These two dimensions combine to form a structured and expressive system for understanding accent evolution, speaker identity, and linguistic diversity.


---

I. Accent Classification

1. Intralingual Accents

> Accents that occur within a single native language due to regional, social, or contextual variation.



Key Features:

The language remains the same, but the pronunciation, prosody, and vocabulary vary.

Intralingual variation is shaped by:

Region (e.g., Telangana vs. Coastal Andhra Telugu)

Caste or community (e.g., Brahmin Tamil vs. colloquial Chennai Tamil)

Formality and register (e.g., Sanskritized Kannada vs. street Kannada)


Speaker is fluent and unconsciously uses these accents based on identity and context.


Use in Asynth:

Forms the A₁, A₂...Aₙ axes within the A Set.

Models fine-grained speaker identity, social context, and realism in native-language TTS.



---

2. Inherited Interlingual Accents

> Accents that develop when a speaker becomes fluent in a non-native language, retaining elements of their native phonology.



Key Features:

Accents are stable, formed over time.

Phonetic influence of L1 is evident in the speaker’s articulation of L2 or L3.

Examples:

A Telugu speaker’s Indian English.

A Marathi speaker’s Hindi with distinctive phonetic patterns.

A Bengali speaker’s Tamil, shaped by Bengali phonotactics.



Sociolinguistic Insight:

These accents reflect linguistic identity across boundaries.

They are not considered “imperfect,” but rather culturally grounded fluency.


Use in Asynth:

Forms the B₁, B₂...Bₙ set of fluent non-native languages.

Models stable cross-lingual voice consistency in multilingual TTS.



---

3. Emergent Interlingual Accents

> Accents that emerge as a speaker attempts to learn a new language, typically with low fluency and high phonetic interference.



Key Features:

Accent is unstable, shifting, and highly influenced by L1 phonology.

Captures the natural trajectory of how humans learn to pronounce new languages.

Collected in three stages (Entropic Learning paradigm):

Take 1: Cold attempt — raw, heavy accent (high entropy)

Take 2: After hearing a reference audio — mimetic improvement

Take 3: After receiving expert feedback — refined articulation



Use in Asynth:

Forms the C₁, C₂...Cₙ set of unfamiliar languages.

Enables TTS systems to model learning, imperfection, and accent progression, just like real humans do.



---

II. Language Set Classification

These sets categorize each speaker’s language profile, which informs the type of accent expected in their speech.

A Set – Native Language + Intralingual Variation

> The speaker’s first language (L1), spoken natively across different dialects and accents.



A₁, A₂...Aₙ refer to dialectal or sociolectal variants within the native language.

Speech in A set is fluent, confident, and identity-anchored.

Data from A set is used to:

Establish the speaker’s core voice model

Capture intralingual richness



Example:

A speaker’s A Set = Telugu

A₁: Coastal Andhra

A₂: Telangana

A₃: Brahminical Telugu




---

B Set – Fluent Non-Native Languages

> Languages that the speaker speaks with fluency, but which are not native.



Each B₁, B₂, Bₙ is a language acquired over time, often through schooling or societal immersion.

Fluency is stable, but accent is inherited from L1.

Speaker can express complex ideas, but pronunciation retains features of their native language.


Example:

A Telugu speaker:

B₁: English with a Telugu accent

B₂: Hindi with a Telugu rhythm




---

C Set – Learning Languages

> Languages that the speaker is currently learning, and has no strong fluency in yet.



Speech in C Set is collected in progressive accent stages:

Take 1 = cold attempt

Take 2 = after reference audio

Take 3 = after expert correction


This set embodies the entropic learning curve of accent formation.

It is not just data — it is a signal of transformation.


Example:

A Telugu speaker:

C₁: Reading Bengali either in Telugu script or Bengali. 

C₂: Repeating Tamil dialogues as is by a reference audio or a language expert.

C₃: Singing a song in Odia after listening to it.




---

📊 Combined Accent–Language Table

Set	Type of Language	Fluency	Accent Type	Variation Type	Role in Asynth

A	Native (L1)	Full	Intralingual	A₁...Aₙ	Speaker anchoring, native realism
B	Fluent L2/L3	High	Inherited Interlingual	B₁...Bₙ	Cross-lingual stability, speaker identity
C	Learning L3/L4	Low → Improving	Emergent Interlingual	C₁...Cₙ (3 takes)	Accent emergence, entropic learning path



---

