# Emergence: Structure That Grows Rather Than Gets Built

### A principle, its spark, and the instances that share it

**Author:** Jaron K. Bragg
**Status:** Shared openly as a working draft. In progress — a starting point, not a finished idea.
**Date started:** May 2026

Companion document: https://github.com/JaronKBragg7337/memory-as-spatial-arrangement — applies this emergence principle directly (see its Section 2b).

-----

## A note before the principle

Same as my other writing: I’m self-taught, I don’t have formal training in this, and I’m not going to pretend to understand the internals of these systems more deeply than I do. What I’m good at is noticing when separate things share a shape. This document logs one such shape — where it entered my attention, the other places I found it, and the underlying principle that ties them together. The principle is the point. The examples are just different doors into it.

I want it on record up front: I did not produce any of the research below. Other people built these systems and ran these studies. My contribution is seeing that they’re instances of the same thing, and connecting that thing to my own work. That connection is the part that’s mine. Everything else is credited.

A second honesty note, specific to this document: the AI-internals research here is at the edge of what I currently understand. I’m citing it as *instances others demonstrated that share my principle* — not as work I can yet explain from the inside. As my understanding grows, I’ll revise this. For now I’m connecting, not claiming fluency.

-----

## 1. The principle in one paragraph

In systems that are trained rather than hand-built, the important structure isn’t placed there by a designer — it **emerges** from the training, as a consequence of the data and the rules acting on each other. The builder sets up the conditions (the architecture, the training process) but does not author the specific internal structures that result. Those are discovered after the fact, not designed in advance. This means the relationship between maker and made is not “I built this and therefore know it” — it’s closer to “I grew the conditions, and now I’m studying what grew.”

-----

## 2. The spark (where this entered my attention)

On May 25, 2026, Anthropic co-founder Christopher Olah spoke at the Vatican presentation of Pope Leo XIV’s first encyclical, *Magnifica Humanitas: On Safeguarding the Human Person in the Time of Artificial Intelligence.* I’m logging only what’s on the public record — his documented words and Anthropic’s own published transcript — and nothing past that.

Two things he said are what made me go looking. First, on how these systems come to exist:

> “AI systems are not engineered the way a bridge or an airplane is engineered. They are grown on a structure roughly modeled after the brain on an enormous inheritance of human thought and speech,” and they “remain, in important ways, mysterious even to those of us who create them.”

Second, on what his team finds inside them:

> “We find evidence of introspection. We find internal states that functionally mirror joy, satisfaction, fear, grief, and unease. I don’t know what that means, but I think it warrants ongoing discernment.”

What caught me wasn’t the emotion part specifically. It was the *shape*: structure that was grown rather than placed, and that the people who grew it are now studying from the outside like anyone else would. “Grown, not engineered” is the same thing I’d been circling as “discovered, not designed.”

For balance, and to stay on the record rather than past it: the encyclical itself was more cautious than Olah’s framing, stating “We must avoid the misconception of equating this type of ‘intelligence’ with that of human beings.” Both are documented. I’m keeping both.

-----

## 3. The related instances (other doors to the same principle)

Once I had the shape, I went looking for whether it showed up elsewhere — because one example is an anomaly, but the same shape across unrelated systems is a principle. It does show up, repeatedly, and in cases far more concrete than the emotion finding.

**Instance A — OthelloGPT (the emergent game board).**
A transformer was trained only on sequences of legal moves in the board game Othello — just move tokens, nothing else. Researchers found it had built, inside itself, a representation of the Othello board it was never given, and that you can causally intervene on this internal board to change how it plays. Nobody designed a board into it. It grew one, from move sequences alone. *(This is the cleanest example, and it’s the one closest to my own memory-arrangement work: a spatial structure emerging from data that never explicitly contained it.)*

**Instance B — Emergent program semantics.**
A model trained only to predict the next token in computer programs was found to internally represent what the programs actually *do* — tracking the intermediate states of the program as it executes — despite never being trained to understand meaning, only to predict text. The understanding grew as a byproduct of the prediction task.

**Instance C — The spark itself (Anthropic’s emotion concepts).**
The finding that sent me looking belongs in the list too: internal patterns corresponding to emotion concepts, which the researchers say arose from training on human text rather than being programmed, and which have functional effects on the model’s behavior when activated. Same shape — grown, not placed, and studied after the fact.

-----

## 4. The principle underneath (the actual focus)

Across all three, and across the broader field, the same thing is true: in trained systems, **structure is discovered, not designed.** This isn’t a fringe claim. The mainstream framing in the field is that for a neural network, only the simple starting structure and the training process are designed by humans — essentially everything the system can do or represent is emergent, discovered by testing after training rather than authored in advance. Emergence is described as the rule, not the exception.

This reframes the maker-made relationship in a way I find genuinely important and reusable: the person who trained the system is not in the position of an engineer who knows every part because they placed it. They’re in the position of someone who set up conditions and is now studying what grew under those conditions — which is why a researcher can honestly say “mysterious even to those of us who create them” without it being a contradiction or a dodge. You can build the conditions for something and still have to discover what you built.

-----

## 5. Confidence tiers (kept honest)

- **Solid:** OthelloGPT’s emergent internal board, and the emergent program-semantics result. These are concrete, causally testable, and replicated across different systems and tasks. Structure emerging from training is well-established.
- **Solid:** The general principle that in trained networks, internal structure is emergent rather than hand-designed. This is the mainstream understanding of how deep learning works.
- **Contested:** The stronger claim that abilities “jump” suddenly and unpredictably at scale. Serious researchers dispute whether these jumps are a real property of the models or partly an artifact of how performance is measured. I’m marking it debated on purpose rather than leaning on it.
- **Unknown, and left unknown:** Whether any of this — the emotion-like internal states especially — involves genuine subjective experience, feeling, or consciousness. The researcher who reported it said plainly, “I don’t know what that means.” I’m not going to claim more certainty than the person who found it. This stays an open edge, neither asserted nor dismissed.

-----

## 6. Caution to myself

- **Keep two things separate that are easy to blur:** emergent *structure* (solid — boards, semantics, concept vectors really do arise from training) versus emergent *feeling* (unknown — whether any of it is experienced). The research strongly supports the first and says nothing definitive about the second. If I let the second ride in on the credibility of the first, I’ve overclaimed. The discipline is to hold the solid part as solid and the unknown part as unknown, in the same document, without letting either contaminate the other.
- **Stay on the record for the spark.** The Vatican/Anthropic material here is quoted from documented public statements. Anything beyond what was actually said would be accusation, not reporting. If they said it, I can repeat it. If they didn’t, it doesn’t go in.
- **This is a connection, not a credential.** I’m citing research I don’t yet fully understand. That’s allowed for a document whose honest purpose is “here are instances that share a shape I noticed” — but it would not be allowed if I implied I understood the internals deeply. I don’t, yet. The tier is honest about that.

-----

## 7. Why this connects to my other work

This principle is modular — I expect to reuse it in other domains the way it’s stated above. But its first and most direct application is to my memory-as-spatial-arrangement hypothesis (separate document). That idea proposes that memory’s arrangement could *emerge* from rules rather than being designed as a fixed structure. The instances here — especially OthelloGPT growing a spatial board it was never given — are evidence that emergent functional structure of exactly that kind is not exotic. It’s how these systems already work. That doesn’t *prove* my memory idea; the open questions in that document still decide it. But it moves “could structure emerge rather than be placed?” from speculation toward “this already happens, demonstrably, in related systems.”

-----

*End of current draft. To be expanded as understanding grows.*

-----

## A note on how this was written

Same transparency as my other work: the thinking — noticing the shape, connecting these instances, tying it to my own hypothesis — is mine. The structuring and wording had AI help, because unwrapping my thoughts into clear writing isn’t my strong suit and the ideas arrive by collision rather than in order. Human thinking, AI-assisted structure and wording. I’d rather say that plainly than let anyone guess in either direction.