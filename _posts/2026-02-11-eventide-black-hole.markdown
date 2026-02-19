---
layout: post
title: " replicate the Eventide Black Hole with Valhalla Shimmer"
subtitle: "Designing Infinite Space"
date: 2026-02-11 10:00:00 -0000
category: studio
studio_group: spatial
img: img/studio/eventide.png
abstract: "A look into the algorithmic reverb that provides the sense of immense, cold vacuum essential for cosmic ambient music."
---

### Creating the Void
To Simon and Garfunkel, the sound of silence was a metaphor for an existential paradox that resulted in a famous commercial moneymaker decrying commercial fame and money-making. And just as Paul Simon may have been affecting the protective cynical shell of post-beatnik poetry, I am also not the cynic in this case. I think it's a terrific song and it deserves its popularity. If popular music were a star, space music would float out in its Kuiper Belt. 

Similar to classical music, in space music, silence is just as important as sound. The space between sounds is a psychoacoustic cue. If the silence is literally silent, listeners perceive a lack of space. Ironically, to convey vast nothingness, we need to fill that space with something.

Eventide’s Blackhole is an iconic, "otherworldly" reverb that originated as a algorithm in the DSP4000 Ultra-Harmonizer rack unit in 1994. Today's familiar pedal and stompbox version is a modern version of that original rack processor preset. 

 To make silence feel "large," you need a specific type of spatial processing. 

#### The Geometry of Reverb

Unlike a "Room" or "Hall" reverb which tries to emulate a physical space on Earth, the Black Hole is designed to sound unnatural and vast. 

{% include player.html file="mp3/test-01.mp3" title="Test of embedded audio player" %}

Another take on the same motif:

{% include player.html file="mp3/test-02.mp3" title="Will this break?" %}

* **Gravity & Resonance:** By manipulating the feedback loops, I can create a "shimmer" that sounds like light reflecting off an icy nebula.
* **Modulation:** Adding slight pitch-shifting to the reverb trails helps prevent the sound from becoming static, giving it an "organic" drift.

### The Eventide Blackhole algorithm is not a shimmer reverb!

The Eventide Blackhole is primarily a massive, diffused feedback delay network (FDN), but it is not a “shimmer” reverb in the traditional sense.

While it lacks the octave-up pitch-shifting characteristic of shimmer reverbs, it uses internal modulation (subtle pitch variations) to create its signature “liquid” movement.

Unlike a shimmer reverb, the black hole does not feed audio through a pitch-shifter within the feedback loop. 

At its core, Blackhole uses a series of interconnected delays and diffusers (Diffused Delay Networks). When you increase the “Size,” you aren’t just lengthening a decay; you are expanding the physical “volume” of the virtual space, which changes how the echoes interact.

### Blackhole modulation

What we could consider the “Modulation section” controls the pitch element. The Blackhole Depth and Rate control modulate the delay lines. This causes very slight pitch drifting (chorusing), which prevents the long decay from sounding static or metallic.

The “Gravity” Control is the secret sauce. It allows you to change the decay shape. Positive Gravity gives you normal, expansive decay.

Negative Gravity is where it gets weird. An inverse, “sucking” decay where the reverb builds up before disappearing.

### Valhalla Shimmer

Valhalla Shimmer is compared to Blackhole, but they share little in common. Valhalla Shimmer is a feedback reverb network (similar to Hall/Plate approaches) with built-in pitch shifters plus lush diffusion. 

Shimmer provides a very distinctive effect, and you need to be judicious in its application. The "angelic shimmer cliché" happens because the high frequency pitch shifted wash on one recording tends to sound like the same high frequency pitch shifted wash on anyone else’s recording. Independent of what instrument you are running through it, you always get a fluttering string section effect. Blame guitarists for its overuse in the form of the Strymon BigSky pedal. Some guitarists will do anything to change their sound. between you and me, I don't think they even like the guitar.

Can Valhalla Shimmer Sound Like Blackhole? Partially yes. Especially for the more ambient, evolving tail textures. But Shimmer’s pitch shifting is fixed to large preset intervals and isn’t intended to be easily modulated (although you can automate that). Blackhole’s architecture is more about algorithmic space than shimmer itself.

So Valhalla Shimmer can approximate Blackhole’s vibe, especially for ambient pads and washes, but of course it isn’t a perfect algorithmic match.

### General Tips for Approximating Blackhole with Valhalla Shimmer

- Use long decay and high feedback.
- Pitch shift up a few octaves for lush overtones.
- Increase modulation depth/speed for slight movement.
- Use pre-delay for dramatic entrance before tail.



### Supermassive. Another Valhalla solution that cheapskates will like

A Better Valhalla Plugin for Blackhole-Style Sounds might be Valhalla Supermassive, the free plugin that I can almost hear people screaming when they clicked on this article. Supermassive is designed specifically for huge, evolving, lush reverbs and delays. Supermassive has modes like Nebulae, Cosmology that generate enormous tail lengths and dense feedback. Supermassive’s interactive feedback network makes it closer to Blackhole’s non-physical, other-worldly behavior.

### General Tips for Approximating Blackhole with Supermassive

- Set to modes with wide diffusion & long feedback.
- Experiment with “Multiply” feedback for density.
- Crank decay to maximum and auto-freeze if needed.
- Use wide stereo spread and mellow pitch shifts.

### FutureVerb. The Better-than-Blackhole Valhalla option

As of this writing, FutureVerb is the newest Valhalla reverb. FutureVerb  uses new algorithmic reverb topologies that Valhalla says are their cleanest/most transparent yet. Its echo/delay section is built-in and dynamic, meaning you get reverb plus  pitch/delay in one box, which admittedly isn’t the big draw for me that it seems to be for other people. 

On the plus side, FutureVerb  is more modular and has more flexible routing than either Supermassive or Shimmer. FutureVerb has real room/hall/plate style modes as well as ambient/nonlinear modes.

### FutureVerb Can Be Better for Blackhole-Style Sound

If your goal is to get in the ballpark of the Eventide Blackhole vibe, FutureVerb echo and reverb routing allow you to place delay echoes (including reversed or pitch-shifted ones) before the reverb. This is closer to how Blackhole’s engine combines feedback, pitch, and space.

FutureVerb ‘s Nonlinear & Ambient Modes go beyond traditional rooms. Several reverb modes are designed for huge spaces and abstract textures that can rival Blackhole’s “unreal” tails.

FutureVerb ‘s Integrated Manipulation Tools, such as “Color” modes and filters, give you additional timbral shaping without needing external EQ or inserts.

For Supermassive fans out there, sorry. Supermassive is great, but FutureVerb  is just more versatile. Supermassive is amazing for a free tool, but FutureVerb takes those concepts and embeds them in a reverb framework that give you more control, better sound, and better ways to shape the sound.

For a Blackhole emulation, FutureVerb provides much better control over creative echoes, pitch-manipulated tails, and reverb shape within one plugin. This is something neither Shimmer nor Supermassive alone fully accomplishes.

### Replicating Blackhole with Valhalla 

We are chasing the sound of the Eventide Blackhole, a non-physical, pitch-evolving, enormous feedback space with modulated diffusion and “infinite gravity” tails.

We will approximate that using  Valhalla Shimmer, Valhalla Supermassive, and Valhalla FutureVerb. Since Supermassive is free, you might as well download it and see what you think.

<div class="post-info-box" markdown="1">

BLACKHOLE IN VALHALLA SHIMMER

“Octave Gravity Well”

Concept: Use pitch-shifted feedback as spectral propulsion. Blackhole lowers pitch in feedback; Shimmer rises. We’ll tame the ascent and slow the bloom.

Algorithm
- Mode: Dual
- Size: 0.90
- Decay: 18–25 seconds
- Feedback: 0.85

Pitch
- Pitch A: +12 semitones
- Pitch B: 0 semitones
- Pitch Mix: 35%

(Reducing pitch mix prevents angelic shimmer cliché and moves toward Blackhole density.)

Diffusion
- Diffusion: 0.75
- Mod Depth: 0.30
- Mod Rate: 0.15 Hz

Tone
- Low Cut: 120 Hz
- High Cut: 7 kHz

Mix
- 40–50% wet (insert)
- 100% wet (aux bus)

Result: Expansive, harmonic bloom. Not identical to Blackhole’s downward cascade, but achieves evolving harmonic mass.

</div>

---

<div class="post-info-box" markdown="1">

VALHALLA SUPERMASSIVE

“Event Horizon Mode”

Concept: Blackhole is closer to a massive feedback delay network than a classical hall. Supermassive excels here.

Mode
- Cosmos or Lyra

(Cosmos = smoother; Lyra = darker and more unstable)

Core Settings
- Delay: 0.80
- Warp: 0.65
- Feedback: 0.92
- Density: 0.85

Modulation
- Mod Rate: 0.10 Hz
- Mod Depth: 0.40

EQ
- Low Cut: 150 Hz
- High Cut: 6 kHz

Optional Trick

Automate Feedback between 0.88 → 0.95 for swelling gravity effects.

Result: Vast, non-linear, evolving space. This is the closest structural match to Blackhole’s “unreal geometry.”

</div>

---

<div class="post-info-box" markdown="1">

VALHALLA FUTUREVERB

“Controlled Singularity”

FutureVerb’s architecture (reverb + echo routing) allows closer structural mimicry of Blackhole’s feedback complexity.

Reverb Section

Algorithm:
- Cathedral (for density)

OR

- Chamber / Ambient variant (if available)

Size: 0.95

Decay: 22–30 seconds

Mod Depth: 0.35

Mod Rate: 0.12 Hz

Low Cut: 120 Hz

High Cut: 6–8 kHz


Echo Section

Mode:
- Pitch Echo (if available)

OR

- Reverse Echo (for rising swell effect)

Delay Time:
- 600–900 ms

Feedback:
- 0.75

Pitch Shift:
- +7 or +12 semitones

(Lower intervals feel more “Blackhole” than full octave shimmer.)

Routing:
- Echo BEFORE Reverb

This is critical. It feeds pitch-shifted material into the reverb tank, approximating Blackhole’s internal feedback manipulation.

</div>

---

<div class="post-info-box" markdown="1">

Mix Strategy (may not match your workflow, follow as you see fit)
- Put it on a bus. Aux send at 100% wet
- Automate send level instead of decay
- Use stereo widening post-plugin if needed (either on the reverb or on the mixed track, whichever makes sense)

</div>

---

### Reverb Review and Technical Setup

The interesting thing is that none of these efforts exactly nail the Blackhole sound (although one of them is uncannily close). More valuable to my mind is that I have just provided you with 3 new cosmic reverbs that take you deep spaces which are very similar, but not the same as the Eventide Blackhole. And in each case they are spaces you would not be able to easily approximate with the Blackhole itself.  Listen for these spaces in my music. I use Reaper’s pin matrix routing method with multiple instances of these plugins to create surround sound in the rear channels, which I then fold back into the stereo signal using an LtRt matrix encoding tool. I don’t think my versions of “deep space” sound like any others.

For specific instruments, (e.g. a mono Moog voice or similar, I typically double the voice with 2 units to create a “stereo Moog” (c.f. “the magic of buying two of them”). I run the signal through a stereo chain into the Eventide processors or a pin matrixed Valhalla bus. By keeping the mix at approximately 45% wet, the original analog transient remains sharp while the tail fades into a seemingly infinite horizon.

This specific combination is what creates the “Planetarium” vibe—dry, intimate hardware sounds floating in a massive, algorithmic void. 

Some people have speculated that the universe may be mathematical in nature. 

If so, creating space from numbers, these cosmic soundscapes may not be unnatural. They may hint at the very substance of the universe. 
