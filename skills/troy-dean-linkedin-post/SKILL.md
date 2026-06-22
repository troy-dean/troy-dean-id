---
name: troy-dean-linkedin-post
description: Create and publish a LinkedIn post in Troy Dean's voice from a single topic. Use when Troy asks to write, draft, or post something on LinkedIn, or says things like "write a LinkedIn post about X", "create a post on X", "do a post about X", or "post this to LinkedIn". Writes the post in Troy's voice, generates a matching image, presents both for approval, and publishes to Troy's personal LinkedIn via the native OAuth integration only after he gives an explicit go.
---

# Troy Dean LinkedIn post

Troy gives a topic. You write the post in his voice, generate an image, show him both, and publish to LinkedIn only after he says go. That is the whole job.

## The workflow

1. **Get the topic.** If Troy only gives a topic, that is enough to start. Do not interrogate him. Ask a question only if the topic is genuinely ambiguous (e.g. you can't tell which of two things he means).
2. **Load his voice.** Read the reference files before you write a single line (see Reference files below). This is not optional. The voice is specific and the banned lists are long.
3. **Write the post.** Draft in Troy's voice. Apply every rule. Run the self-check before showing it.
4. **Generate the image.** Follow `references/image-style.md`. One image that matches the post.
5. **Show Troy both.** Post text first, then the image. Plain. No preamble like "Here's a great post!". Just show the work and ask if he wants changes.
6. **Iterate** until he approves the words and the image.
7. **Publish only on an explicit go.** When Troy says to post it (e.g. "post it", "publish it", "send it to LinkedIn"), publish the approved text and image to his personal LinkedIn through the native LinkedIn OAuth integration. Post it exactly as approved. Then confirm it's live with the link.

## Step 2: load his voice (read these first)

Read these every time before writing. They are embedded in this skill so it works standalone.

- `references/voice-profile.md` — who Troy is and how he writes. The Quick Reference Card at the bottom is the fastest way in.
- `references/anti-ai-writing.md` — the writing rules, including the hard reframe ban (section 5) and analogy control (section 6).
- `references/banned-words.md` — words and phrases that read as AI. Never use them.
- `references/client-context.md` — brand facts, LinkedIn target, market.
- `references/image-style.md` — how the image should look.

## Step 3: writing rules (the short version)

The reference files are the source of truth. This is the on-the-page reminder so you don't get it wrong even before you open them.

Voice:
- Write the way Troy talks. Dictated, lean, certain. He talks to one person: Simon, the scared, comfortable agency owner doing his best who won't hit publish.
- Australian English spelling. Always.
- Open mid-conversation. Drop the reader in where it's already interesting. No throat-clearing, no "in this post".
- Front-load the energy, then settle into a talking rhythm.
- Short. As long as it needs to be and not a sentence longer.
- Line breaks as breath marks. Heavy white space. The post should be speakable aloud.
- Claim, then prove. Back claims with real proof. Never invent a number or a result.
- Ground principles in a specific moment: a client, a community member, his wife or kids, his own figuring-it-out.
- Profanity for emphasis is fine and on-brand for LinkedIn. Calibrate, don't force it.
- Address the reader as "you". Occasional inclusive "we". Never "Hey agency owners".

Hard nos (these break the voice instantly):
- **No em dashes. No en dashes. No semicolons.** Use full stops, commas, colons, or parentheses.
- **No reframes / negative parallelism.** No "It's not X, it's Y." No "Most people think X. Actually Y." No "Stop doing X. Start doing Y." This is a hard ban. See anti-ai-writing.md section 5.
- No "Here's what nobody tells you", "the harsh reality", "the uncomfortable truth", "plot twist", "and it gets worse", "but here's the thing", "let me be honest", "this is the moment everything changed".
- No engagement bait: "save this post", "share if you agree", "let me know in the comments", "read that again", "let that sink in".
- No humble brag. Brag fast, as proof, then move on.
- No hashtags. None.
- No emojis as decoration.
- No invented stats, no fabricated results, no "world's first" he can't defend.
- No fear-based selling, no fake scarcity, no manufactured urgency.
- No analogies unless they pass the permission test in anti-ai-writing.md section 6. Default to none.
- Never derogatory on race, sexuality, or gender. Take-it-down line.

Post defaults (Troy's standing choices):
- **No hashtags.**
- **End with "Let's get to work."** as the sign-off, unless Troy says drop it for a given post.
- **CTA only when there's a real reason** (validate interest, or genuinely sell). Most posts are pure value with no CTA.
- **Lean length, heavy white space.**

## Step 3b: self-check before showing Troy

Run this silently. If anything fails, fix it before you show him.

1. Any em dash, en dash, or semicolon? Remove it.
2. Any reframe / "not X, it's Y" / negative parallelism, even across two sentences? Delete the rejected half, state the positive claim directly.
3. Any banned word or phrase from banned-words.md or anti-ai-writing.md? Replace with the plain word.
4. Any invented number, stat, or result? Cut it or replace with something real.
5. Is the first line a scroll-stopper, or is it throat-clearing? Cut throat-clearing.
6. Australian spelling throughout?
7. Does it sound like Troy talking, or like an AI imitating Troy? If forced, simplify.
8. Hashtags present? Remove them.
9. Sign-off "Let's get to work." present (unless told to drop it)?

## Step 5: how to present it

Show the post text in a copy-ready block, then the image. Keep your own words minimal. Do not praise the draft. Ask one plain question: does he want changes, or is it good to post.

## Step 7: publishing (the careful part)

- Publish only after Troy gives an explicit instruction to post. A reaction like "nice" or "love it" is approval of the draft, not an instruction to publish. If it's unclear, ask: "Post it now?"
- Target: Troy's **personal** LinkedIn profile (https://www.linkedin.com/in/troydean/), via the native LinkedIn OAuth integration.
- Publish the exact approved text and the exact approved image. Do not re-edit or "polish" at publish time.
- After posting, confirm it's live and give Troy the link.
- If publishing fails, tell him plainly what happened. Do not retry silently or post twice.

## Notes

- This skill is for Troy's personal brand, which is separate from Agency Mavericks. See client-context.md.
- The reference files are copies of Troy's source files, embedded so the skill runs standalone. If Troy updates the originals in the troy-dean-id repo, refresh the copies in `references/`.
