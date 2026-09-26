# Thomas Semrad

AI systems builder and evaluator based in Waukesha, WI.

Anyone can vibe code something that runs now. You describe it, the AI builds it, and it looks like it works. The hard
part is knowing if it actually does, and that's the part I care about most.

I build with AI, and I test what gets built. The pass line gets written down before anything runs, every test gets a
control that's supposed to fail, and when the answer is "this doesn't work" it stays on the record. The way I think
about it: I'm the direction and the AI is the amplifier, but there always has to be an outside observer or the system
implodes on itself.

## About me

I came to this sideways: food service, retail, electrical work, and social work, with a B.S. in Criminology and a
Psychology minor. That mix taught me to read people, to understand how systems behave, and to ask what something is
really doing before I trust what it says it's doing. I finished the TripleTen Data Science program in 2026, and
alongside it I've been building real AI systems, not course exercises.

## Featured eval

**[aioos-retrieval-eval](https://github.com/DonMerlin77/aioos-retrieval-eval)**: does a game NPC's memory search pull
up the right memory? 127 real queries, labels checked by hand, and traps built to catch shortcuts (an old memory that
sounds right, a word that matches but means something else).

Why it matters: an engine developer ran it in his release gate before shipping his embedder. An eval is only useful
if someone trusts it enough to make a decision with it.

## Other evals

- **[aioos-channel-routing](https://github.com/DonMerlin77/aioos-channel-routing)**: embeddings beat keyword rules at
  routing what an NPC notices (+0.35 on 116 situations, including traps where the obvious keyword points the wrong way).
- **An NPC belief system, proven inside Unreal Engine 5.3**: the in-engine run matched my Python prediction within
  about a second, and the stress test found (and documented) exactly where it hits its limit.
- **The fine-tuned model I didn't ship**: it scored well on the metric it was trained against, but made real decisions
  worse, so I rebuilt the metric instead of shipping it.
- **My own tests**: I've caught tests of mine passing without testing anything. Every result I quote traces back to a
  script that reproduces it, failures included.

## Projects

- **Hearsay** *(private, available on request)*: game NPCs that believe things based on who told them, where the
  story started, and whether that source held up. Built to plug into Unreal Engine. It's also turning into
  provenance-aware memory for AI agents.
- **[Continuum Goods AI stack](https://github.com/DonMerlin77/continuum-agents)**: a multi-agent system that runs a
  live Shopify store (pricing, inventory, fulfillment, research, listings, marketing), with agent behavior tuned by
  editing plain-text "brain" files. The link is a public slice of it.
- **Orlog** ([orlog.fyi](https://orlog.fyi)): a live AI decision tool with subscriptions that routes a question
  through several models. When I tested it honestly it tied a well-written single prompt, so I describe its value as
  making a good prompt easy, not as being smarter.
- **[PersonaVid](https://github.com/DonMerlin77/personavid)**: an AI video personalization pipeline, from footage
  cataloging and shot direction to GPU generation on Modal, compositing, and publishing.

## Tools I work with

Python · SQL · pandas · NumPy · scikit-learn · PyTorch · Hugging Face · Modal (serverless GPU) · Unreal Engine 5 ·
Claude Code · Git / GitHub · Streamlit

## Data science projects

- **[data-science-projects](https://github.com/DonMerlin77/data-science-projects)**: classification, regression,
  statistical analysis, EDA, and SQL from the TripleTen program.
- **[gold-ore-purification-ml](https://github.com/DonMerlin77/gold-ore-purification-ml)**: models predicting gold
  recovery efficiency across industrial processing stages.
- **[chicago-taxi-sql-analysis](https://github.com/DonMerlin77/chicago-taxi-sql-analysis)**: SQL analysis of Chicago
  ride data.
- **[Used Car Price Explorer](https://tripleten-project-sprint-4.onrender.com)**: a live Streamlit app on US vehicle
  listings and what drives price.

## Connect

[LinkedIn](https://linkedin.com/in/thomas-semrad)
