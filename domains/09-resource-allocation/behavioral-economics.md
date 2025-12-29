# Behavioral Economics: Reasoning About Systematic Deviations

The mental operations for understanding how people actually behave - where they deviate from rationality, why, and how to design around it.

---

## Why Behavioral Economics Generates Useful Thinking Tools

Standard economic tools assume rational agents maximizing well-defined objectives with consistent preferences. Real people don't work this way. They're loss averse, present-biased, anchored by irrelevant numbers, susceptible to framing, and prone to treating sunk costs as relevant. This isn't a minor footnote - it changes everything.

Behavioral economics started as a catalog of deviations from rationality. But the real insight is that the deviations are systematic. People don't fail randomly - they fail in predictable, exploitable, and correctable ways. Loss aversion isn't noise; it's a consistent pattern with measurable magnitude (losses hurt about 2x as much as equivalent gains please).

The extraction principle: these aren't just biases to avoid but tools to apply. Loss aversion isn't just something to watch out for in yourself - it's something to design for in systems you build. Status quo bias isn't just a mistake - it's a lever for influencing behavior. The tools work descriptively (predicting what people will do) and prescriptively (designing better choices).

These tools are humbling. They reveal how far human behavior strays from textbook rationality. But they're also empowering. Once you understand the systematic errors, you can correct for them in yourself and design around them in systems.

---

## Tier 1: Reference-Dependent Preferences

People evaluate outcomes relative to reference points, not in absolute terms.

---

### Loss Aversion and Reference Dependence

**What**: Losses loom larger than equivalent gains. Evaluation is relative to a reference point, not absolute. The same outcome feels different depending on whether it's framed as a gain or loss relative to expectations.

**Why it matters**: This explains risk-seeking in the domain of losses, the endowment effect (valuing what you have more than identical things you don't have), and why framing matters so much. People will take risks to avoid a loss that they would never take to achieve an equivalent gain.

**The key move**: Identify the reference point. Outcomes above it are coded as gains, below as losses. Losses hurt roughly twice as much as equivalent gains please. Then ask: how does behavior change if we shift the reference point? The same objective outcome can produce different behavior with different framing.

**Classic application**: Investment behavior. Investors hold losing stocks too long (hoping to avoid realizing the loss) and sell winners too early (locking in the gain). The disposition effect is driven by loss aversion - realizing a loss feels worse than the equivalent failure to realize a gain.

**Surprising application**: Labor supply. Taxi drivers work longer on slow days (still in the "loss" domain relative to their daily earnings target) and quit early on busy days (already in the "gain" domain). This is backwards from rational income smoothing - they should work more when the hourly wage is high.

**Failure modes**:
- Assuming the reference point is obvious - it can be manipulated and is often path-dependent
- Treating loss aversion as universal - magnitude varies across people and domains
- Ignoring that reference points adapt - what feels like a loss today may feel like the status quo tomorrow
- Using loss aversion as an excuse for all risk aversion - not all risk aversion is loss aversion
- Missing that loss aversion can be overcome with experience and stakes

**Go deeper**: Kahneman and Tversky's prospect theory papers. Thaler's work on the endowment effect. Camerer et al. on labor supply.

---

### Framing Effects

**What**: How choices are described affects decisions, even when the underlying options are identical. Logically equivalent framings can produce opposite choices. This isn't a minor effect - it's large and robust.

**Why it matters**: Presentation matters as much as substance. The same policy, product, or choice can produce different decisions based solely on framing. Anyone who presents choices has power to influence outcomes through framing.

**The key move**: Ask: how is this choice being framed? What would happen with a different but logically equivalent frame? Test whether the framing is driving the preference. If changing the frame changes the choice, the choice isn't based on the underlying options.

**Classic application**: The "Asian disease problem." Same outcomes - 200 saved out of 600, or 400 die out of 600 - produce opposite risk preferences depending on whether the frame emphasizes lives saved (risk aversion) or lives lost (risk seeking). Same objective outcomes, opposite choices.

**Surprising application**: Goal framing. Framing a goal as "not losing" versus "winning" produces different motivation and persistence. Prevention focus (avoiding loss) versus promotion focus (seeking gain) leads to different strategies, risk preferences, and emotional responses.

**Failure modes**:
- Assuming your framing is neutral - all frames emphasize something
- Over-attributing choices to preferences when they're driven by framing
- Ignoring that sophisticated choosers can sometimes see through frames
- Using framing effects to manipulate without ethical reflection
- Missing that some framing effects diminish with stakes and experience

**Go deeper**: Kahneman and Tversky's original framing papers. Levin et al. on types of framing effects.

---

### Mental Accounting

**What**: People maintain separate mental accounts that violate fungibility. Money in different accounts is treated differently even though money is money. Winning $100 on a bet and losing $100 at a restaurant on the same night doesn't net to zero psychologically.

**Why it matters**: Fungibility - the principle that money is interchangeable - is violated constantly. People spend windfall income differently than regular income. They refuse to reallocate between mental accounts even when it would benefit them. This explains saving behavior, consumer spending patterns, and investment decisions.

**The key move**: Identify the mental accounts at play. Ask: how would behavior change if accounts were merged or separated differently? Are artificial boundaries between accounts constraining choice in ways that don't serve the person's actual objectives?

**Classic application**: Household budgets. People maintain separate accounts for "food," "entertainment," "emergencies" and resist transferring between them even when it would be beneficial. A family might finance a car at high interest rather than draw from "savings" even though the savings earn less than the loan costs.

**Surprising application**: Sunk cost effects. People continue investing in failing projects because they've mentally "opened an account" for that project and closing it at a loss feels bad. The sunk cost feels relevant because it's in the project's mental account, even though rationally it's irrelevant.

**Failure modes**:
- Treating mental accounting as always irrational - some mental accounts serve as useful commitment devices
- Missing that mental accounting can be helpful for self-control - separate accounts can prevent overspending
- Over-merging accounts and losing track of goals
- Ignoring that mental accounts differ across cultures and contexts
- Assuming mental accounts are fixed - they can be reshaped with framing

**Go deeper**: Thaler's work on mental accounting. Shefrin and Thaler on self-control and mental accounts.

---

### Anchoring

**What**: Numerical judgments are pulled toward arbitrary starting points, even irrelevant ones. First numbers matter disproportionately. Estimates are systematically biased by whatever number was recently encountered - even if it's obviously unrelated.

**Why it matters**: First numbers in a negotiation matter disproportionately. Estimates are biased by whatever arbitrary number was recently encountered. This isn't just about initial offers - any number can serve as an anchor.

**The key move**: Ask: what anchors are present? How might they be biasing the judgment? In negotiations: move first if you have information to anchor favorably; be aware of their anchor and adjust away from it if they move first.

**Classic application**: Real estate negotiation. Listing prices serve as anchors. Buyers estimate value relative to the listing, even when they know the listing is inflated. A $500,000 listing makes $450,000 feel like a good deal; a $400,000 listing makes $425,000 feel expensive. Same house.

**Surprising application**: Sentencing decisions. Judges' sentencing recommendations are anchored by prosecutor demands, even when those demands are extreme. Arbitrary numbers - even from dice rolls in experiments - anchor subsequent judgments about appropriate sentences.

**Failure modes**:
- Thinking you're immune to anchoring - everyone is affected, including experts
- Over-correcting and ignoring genuinely informative reference points
- Confusing anchoring with learning - sometimes initial information is actually relevant
- Missing that anchors can be manipulated strategically
- Ignoring that adjustment away from anchors is typically insufficient

**Go deeper**: Kahneman's "Thinking, Fast and Slow" for accessible treatment. Tversky and Kahneman's original research.

---

### Status Quo Bias and Default Effects

**What**: The current state is privileged. Changing requires justification; maintaining doesn't. Default options have enormous influence over outcomes - what happens if you do nothing matters more than what you could do.

**Why it matters**: Defaults are powerful. Opt-out beats opt-in by large margins. This explains inertia in everything from retirement savings to organ donation to software settings. Whoever sets the default has enormous influence.

**The key move**: Ask: what's the default? How would behavior change with a different default? When designing systems, choose defaults that match desired outcomes. When making choices, don't treat the status quo as neutral.

**Classic application**: Retirement savings. Automatic enrollment (default in, must opt out to leave) produces far higher participation than requiring active enrollment (default out, must opt in to join). Same options, different defaults, dramatically different outcomes.

**Surprising application**: Organ donation. Countries with presumed consent (default is donor, must opt out) have dramatically higher donation rates than countries requiring active opt-in. The "choice" to donate is largely determined by the default.

**Failure modes**:
- Treating defaults as neutral - they're not; defaults are choices made by system designers
- Ignoring that status quo bias can protect against manipulation - inertia sometimes prevents bad changes
- Assuming defaults only work on unsophisticated choosers - even informed people are affected
- Over-relying on defaults without providing good options - nudges don't substitute for good choices
- Missing that defaults interact with other choice architecture

**Go deeper**: Thaler and Sunstein's "Nudge." Samuelson and Zeckhauser on status quo bias.

---

## Tier 2: Time and Self-Control

People struggle with intertemporal choice and self-control.

---

### Time Discounting and Present Bias

**What**: Future costs and benefits are weighted less than present ones. This is normal (time discounting) but the discounting is often excessive and inconsistent (present bias). People discount the near future much more steeply than the far future.

**Why it matters**: Present bias explains why people make plans they don't follow, why they know what they should do but don't do it, and why commitment devices work. The same person who plans to save more "next month" never actually does it - because next month becomes this month.

**The key move**: Ask: how much is a future outcome discounted relative to the same outcome now? Is the discounting consistent over time (exponential) or does it shift (hyperbolic)? If hyperbolic, expect self-control problems and value for commitment devices.

**Classic application**: Saving behavior. Exponential discounters have consistent plans. Hyperbolic discounters always plan to save "starting next month" - and next month never comes because it becomes the present, and present costs loom large.

**Surprising application**: Addiction and health behavior. Present bias makes immediate rewards overwhelming relative to future costs. The smoker knows long-term costs but discounts them heavily. This isn't irrationality - it's a predictable consequence of hyperbolic discounting. Commitment devices (not buying cigarettes) work better than willpower.

**Failure modes**:
- Assuming exponential discounting when hyperbolic applies
- Ignoring that discount rates differ across domains - people discount health differently than money
- Treating all future-discounting as bias to be corrected - some discounting is appropriate
- Relying on willpower instead of commitment devices
- Missing that present bias can sometimes be adaptive

**Go deeper**: Ainslie's "Picoeconomics." Laibson's work on hyperbolic discounting. Thaler on self-control.

---

### Sunk Cost Fallacy

**What**: Resources already spent should be irrelevant to future decisions - they're gone regardless. But people continue investing in failing projects, sit through bad movies, and honor useless commitments because they've already invested. The sunk cost feels like a reason to continue.

**Why it matters**: Sunk cost reasoning is everywhere and costly. Organizations throw good money after bad. Individuals stay in bad relationships, careers, and projects because of prior investment. Recognizing sunk costs as irrelevant is difficult but essential.

**The key move**: For any continuing commitment, ask: would I make this choice if I hadn't already invested? Ignore prior investment; evaluate only future costs and benefits. If you wouldn't start this project today, you should quit it.

**Classic application**: Concorde fallacy. Britain and France continued funding the Concorde supersonic jet long after it was clear the project was economically unviable - because they'd already invested so much. The prior investment was a reason to continue, not to stop.

**Surprising application**: Relationship persistence. People stay in bad relationships partly because they've invested years. "I've already given this so much" becomes a reason to give more, even when the relationship has no future. The sunk cost keeps them stuck.

**Failure modes**:
- Treating all persistence as sunk cost fallacy - sometimes continuation is genuinely optimal
- Ignoring that quitting has costs (reputation, switching costs) beyond the psychology
- Missing that sunk cost reasoning can serve as a commitment device - it's not always irrational
- Over-quitting because you've learned about sunk costs - don't abandon good projects
- Ignoring emotional and identity investments that make "sunk costs" more complex

**Go deeper**: Thaler's early work on mental accounting and sunk costs. Arkes and Blumer on sunk cost experiments.

---

## Tier 3: Beliefs and Reality

How beliefs interact with outcomes in self-reinforcing ways.

---

### Revealed Preference

**What**: What people actually choose reveals their true preferences better than what they say they prefer. Talk is cheap; choices are costly. Behavior is the ground truth about preferences, not stated preferences.

**Why it matters**: People often say one thing and do another. They claim to value savings but don't save. They claim to want exercise but don't exercise. Revealed preference cuts through stated preference to what people actually want - as demonstrated by what they sacrifice to get.

**The key move**: When someone claims a preference, check behavior. What do they actually choose when facing trade-offs? What do they sacrifice to get what they supposedly want? If behavior contradicts statements, trust behavior.

**Classic application**: Consumer behavior. Market research asking "would you buy X?" overestimates actual purchase behavior. What people say they'll buy isn't what they actually buy. Revealed preference (actual purchases) beats stated preference (survey responses).

**Surprising application**: Self-knowledge. You may not know your own preferences. If you say you value family time but consistently work late, your revealed preference is for work (or money, or status). This isn't hypocrisy - it's information. Your behavior tells you about your actual values.

**Failure modes**:
- Ignoring constraints - behavior reveals constrained preferences, not unconstrained preferences
- Missing that revealed preferences can reflect mistakes, addiction, or weakness of will
- Treating all behavior as preference-revealing - some behavior is habitual or pressured
- Ignoring that preferences are constructed by choice situations, not just revealed
- Using revealed preference to dismiss stated preferences entirely - both contain information

**Go deeper**: Samuelson's revealed preference theory. Sen's critiques and expansions.

---

### Reflexivity

**What**: When beliefs affect reality, and reality affects beliefs, you get feedback loops where cause and effect become circular. Predictions about social systems can change the systems they predict.

**Why it matters**: Financial markets are reflexive. Self-fulfilling prophecies are real. Prediction and outcome aren't separable. Standard equilibrium thinking must be modified when the act of predicting changes what's predicted.

**The key move**: Ask: does believing X make X more likely to be true? If yes, the system is reflexive. A bank that's believed to be insolvent becomes insolvent as depositors flee. A stock believed to be valuable becomes valuable as investors pile in.

**Classic application**: Bank runs. If depositors believe a bank will fail, they withdraw. Withdrawals cause failure. The belief was self-fulfilling. A solvent bank becomes insolvent purely through the dynamics of belief.

**Surprising application**: Economic forecasting. If the central bank forecasts recession, that forecast changes behavior - businesses cut investment, consumers save more - which changes whether recession happens. The forecast interacts with its object. The economy the Fed predicts isn't the economy that will exist after the prediction.

**Failure modes**:
- Treating social systems like natural systems - ignoring that participants react to models
- Overweighting reflexivity - not everything is reflexive
- Mistaking correlation for reflexive causation
- Assuming reflexivity only works in one direction - negative reflexivity exists (successful prediction triggers prevention)
- Missing that reflexivity can create multiple equilibria - beliefs can coordinate on different outcomes

**Go deeper**: Soros's "Alchemy of Finance." Merton on self-fulfilling prophecies.

---

### Network Effects and Tipping Points

**What**: When the value of something depends on how many others use it, you get feedback loops, winner-take-all dynamics, and tipping points. Small initial advantages compound into dominant positions.

**Why it matters**: Platforms, standards, social networks, and social norms don't follow supply-and-demand intuitions. Path dependency matters. What wins isn't necessarily best - it's what got ahead first and built network advantage.

**The key move**: Ask: does the value to each user increase with total users? If yes, expect multiple equilibria (dominant standard or none), tipping points, and lock-in. The question isn't "is this good?" but "is this likely to reach critical mass?"

**Classic application**: Phone networks. A phone is useless if no one else has one. As adoption grows, value per user grows. This creates S-curve adoption and winner-take-all dynamics. The first network to critical mass tends to dominate.

**Surprising application**: Social norms. The value of following a norm depends on others following it. Wearing professional clothing has value only because others do. This is why norms are stable until they tip, then change rapidly - and why norm entrepreneurs focus on coordination, not persuasion.

**Failure modes**:
- Assuming the best technology wins - path dependency can lock in inferior standards
- Ignoring that network effects can reverse - networks can collapse as fast as they grew
- Treating all increasing returns as network effects - other mechanisms exist
- Missing multi-homing - when users can participate in multiple networks, dynamics differ
- Ignoring that network effects vary by segment - not all users value the network equally

**Go deeper**: Shapiro and Varian's "Information Rules." Arthur's work on increasing returns and lock-in.

---

### Evolution and Selection

**What**: When entities vary, face selection pressure, and propagate differentially based on fitness, evolutionary dynamics emerge. This applies beyond biology - to firms, ideas, institutions, and behaviors. What survives isn't necessarily best; it's what the selection environment favors.

**Why it matters**: Markets, ideas, and institutions evolve. Understanding selection pressure reveals what survives and why. Evolution doesn't optimize for what you care about - it optimizes for survival in the selection environment.

**The key move**: Ask: what is the selection environment? What is being selected for? What survives differential reproduction? Don't confuse what's "good" (by your values) with what's selected for (by the environment).

**Classic application**: Firm survival. Profit-maximizing firms survive; others don't. Even if no manager explicitly maximizes profit, the market selects as if they do. The economy evolves toward profit maximization through selection, not intention.

**Surprising application**: Memes and ideas. Ideas that spread aren't necessarily true - they're ideas with features that make them spread (emotional resonance, simplicity, tribal identity, memetic hooks). Truth is one selection criterion among many, and often not the dominant one.

**Failure modes**:
- Assuming evolution optimizes for what you care about - it optimizes for survival in the selection environment
- Ignoring that selection environments change - what was adaptive becomes maladaptive
- Treating survival as proof of optimality - many suboptimal things survive through luck or lock-in
- Missing multi-level selection - groups, organizations, and societies also face selection
- Confusing selection for with selection of - selection is for fitness-enhancing traits, selection of is everything that comes along with them

**Go deeper**: Alchian's "Uncertainty, Evolution, and Economic Theory." Dawkins' "Selfish Gene" for gene-centered view. Boyd and Richerson on cultural evolution.

---

## Quick Reference

### Decision Type -> Tool

| You're asking... | Start with... |
|------------------|---------------|
| Why won't they accept this fair deal? | Loss Aversion |
| Why does presentation change choices? | Framing Effects |
| Why won't they reallocate resources? | Mental Accounting |
| Why is this number influencing them? | Anchoring |
| Why won't they change from the current option? | Status Quo Bias |
| Why can't they stick to their plan? | Time Discounting |
| Why do they keep investing in failure? | Sunk Cost Fallacy |
| What do they really want? | Revealed Preference |
| Why did the prediction cause itself? | Reflexivity |
| Why did this become dominant? | Network Effects |
| Why does this bad pattern persist? | Evolution and Selection |

---

## Reading Path

**Foundations (start here)**:
- Kahneman, "Thinking, Fast and Slow"
- Thaler and Sunstein, "Nudge"

**Going deeper**:
- Ariely, "Predictably Irrational"
- Thaler, "Misbehaving"

**Advanced**:
- Kahneman and Tversky, "Choices, Values, and Frames" (collected papers)
- Ainslie, "Picoeconomics"

---

## Usage Notes

These tools describe systematic patterns in human behavior. They're probabilistic, not deterministic.

**Domain of applicability**: Strong where people face unfamiliar decisions with complex trade-offs. Weaker where people have extensive experience and feedback - experts in their domain show fewer biases for decisions within their expertise.

**Limitations**: Not everyone shows every bias. Biases can be reduced with training, experience, and well-designed choice architecture. Calling something a "bias" doesn't mean the behavior is always wrong - sometimes biases are adaptive.

**Composition**: Loss aversion and framing combine - framing a choice as gain vs loss invokes loss aversion. Anchoring and adjustment connects to mental accounting - anchors stick partly because they're assigned to mental accounts. Status quo bias and sunk cost interact - the status quo is partly favored because changing feels like "wasting" prior investment.

**Integration**: Behavioral tools complement core economics (they explain where rational-agent models fail) and information economics (how do people actually process information?). Use them together: what would a rational agent do (core), what information problems exist (information), and how will actual people deviate from this (behavioral)?
