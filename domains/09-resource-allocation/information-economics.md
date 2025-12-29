# Information Economics: Reasoning Under Asymmetry and Uncertainty

The mental operations for navigating situations where information is incomplete, unequally distributed, or costly to obtain.

---

## Why Information Economics Generates Useful Thinking Tools

Classical economics assumed everyone knows everything - prices, quality, intentions. Reality is different. Buyers don't know product quality. Employers don't know worker effort. Insurers don't know who will file claims. This asymmetry isn't a footnote; it's the main story.

Information economics emerged from taking this seriously. The tools that resulted - adverse selection, moral hazard, signaling, screening - turn out to be reasoning primitives that apply far beyond markets. Anytime one party knows something another doesn't, these patterns emerge. Job interviews, romantic relationships, diplomatic negotiations, and medical diagnosis all involve the same structures.

The extraction principle: these tools work because they describe information geometries, not economic assumptions. Adverse selection occurs whenever private information exists before a transaction. Moral hazard occurs whenever actions are hidden. Signaling occurs whenever costly actions can reveal type. The patterns are general; economics merely formalized them.

What makes these tools powerful is that they're diagnostic. When you see a market unraveling, check for adverse selection. When you see behavior change after a contract, check for moral hazard. When you see costly, seemingly wasteful actions, check if they're signals. The tools tell you where to look.

---

## Tier 1: Information Asymmetry

Tools for situations where one party knows more than another.

---

### Adverse Selection

**What**: When one party has private information about quality before a transaction, the uninformed party can't distinguish good from bad. This can collapse markets. High-quality sellers exit because they can't get fair prices; only low-quality remains - the "lemons."

**Why it matters**: Markets for used cars, insurance, credit, and talent all suffer from this. Knowing the structure of the problem points to the structure of solutions. When you see a market that should exist but doesn't, or prices that seem systematically wrong, adverse selection is often the explanation.

**The key move**: Identify pre-transaction information asymmetry. Ask: if the uninformed party can't distinguish quality, what average quality will be offered? If that average drives out high quality, the market unravels. The lemons drive out the peaches.

**Classic application**: Akerlof's "Market for Lemons." If buyers can't verify used car quality, they pay average-quality prices. Owners of good cars won't sell at those prices - they'd rather keep the car. Only owners of bad cars sell. Market is left with lemons. The asymmetry destroys mutually beneficial trade.

**Surprising application**: Health insurance without mandates. Healthy people know they're healthy. They find insurance overpriced. Only sick people buy, driving up premiums, driving out more healthy people, death spiral. The individual mandate was designed to break this dynamic by forcing healthy people into the pool.

**Failure modes**:
- Treating all information problems as adverse selection - confusing with moral hazard (hidden action vs hidden type)
- Ignoring that signals and screens are costly - solutions have costs
- Assuming adverse selection is always present - sometimes information asymmetry is minimal
- Missing that adverse selection can be overcome with reputation, warranties, or certification
- Confusing adverse selection with selection effects generally

**Go deeper**: Akerlof's original "Market for Lemons" paper. Rothschild-Stiglitz on insurance markets. Spence on labor market signaling as a response.

---

### Moral Hazard

**What**: When one party's actions affect outcomes but can't be observed, they have incentive to act differently than they would under observation. Hidden action creates divergence between interests.

**Why it matters**: Insurance changes behavior. Bailouts change behavior. Any risk-sharing arrangement confronts this problem. The structure is: I take actions, you bear consequences, and you can't see what I do.

**The key move**: Identify post-transaction hidden action. Ask: how does the party's behavior change when they don't bear full consequences of their actions? What would they do differently if they bore the full cost or had to act in public?

**Classic application**: Insurance. Insured drivers drive less carefully. Insured homeowners invest less in fire prevention. The problem isn't that bad drivers buy insurance (that's adverse selection) - it's that insurance makes drivers worse. Coverage changes behavior.

**Surprising application**: Corporate limited liability. When downside is capped but upside isn't, excessive risk-taking is rational. Heads I win big, tails the company goes bankrupt but my personal loss is limited. This explains some financial crisis dynamics - bankers had moral hazard.

**Failure modes**:
- Confusing moral hazard with adverse selection - hidden action (moral hazard) vs hidden type (adverse selection)
- Over-relying on monitoring - it's costly and often incomplete
- Ignoring that incentive pay creates its own distortions - it can induce gaming and risk-taking
- Treating all behavioral changes as moral hazard - some are legitimate responses to changed circumstances
- Assuming moral hazard is always bad - some risk-sharing despite moral hazard is still beneficial

**Go deeper**: Holmstrom's papers on moral hazard and optimal contracts. Arrow's work on medical care and moral hazard.

---

### Signaling

**What**: When you have private information others care about, you can take costly actions to credibly reveal it - but only if the cost differs by type. The signal works precisely because it's costly, and differentially costly.

**Why it matters**: Signals are everywhere - education, luxury goods, corporate dividends, peacock tails. Understanding the structure reveals when signals are informative and when they're pure waste. Many costly activities that seem irrational are actually rational signaling.

**The key move**: For any costly action that seems to convey information, ask: is the cost lower for the type being signaled? If yes, it can be a separating signal - high types take the action, low types don't. If the cost is the same for all types, the signal is uninformative.

**Classic application**: Spence's job market signaling. Education might not build skills but signals ability. The signal works because education is less costly (in effort, psychic cost) for high-ability individuals. A degree says "I could do this" even if the content is useless.

**Surprising application**: Handicapping in biology. The peacock's tail signals fitness precisely because it's costly. Only genuinely fit peacocks can afford the handicap - it's a credible signal because weak peacocks couldn't survive the cost. Zahavi's handicap principle applies to any biological signal.

**Failure modes**:
- Treating all costly actions as signals - some costs are just costs
- Ignoring that signaling is often socially wasteful even when privately rational - arms races destroy value
- Missing that signals can become uninformative as everyone acquires them - credential inflation
- Confusing signals with indices - indices are unfakeable (height), signals can be faked at a cost
- Treating signaling equilibria as unique - there may be pooling, separating, or semi-separating equilibria

**Go deeper**: Spence's original signaling paper. Zahavi's handicap principle for biology. Feltovich, Harbaugh & To on countersignaling.

---

### Screening

**What**: When you're the uninformed party, you can design tests, filters, or menus that cause the informed party to reveal their type through their choices. Screening is the mirror of signaling - the uninformed party moves first.

**Why it matters**: Job interviews, insurance menus, product lines, scholarship criteria - all are screening mechanisms. Rather than passively receiving signals, you design the game to extract information. Good screening mechanisms are incentive-compatible: people reveal their true type because it's in their interest.

**The key move**: Design a choice where different types prefer different options. High types self-select into one option, low types into another. The screen works when no type wants to mimic another - the options are designed so that misrepresentation isn't worth it.

**Classic application**: Insurance menus. Offer a high-premium, low-deductible plan and a low-premium, high-deductible plan. High-risk people (who know they're high-risk) choose the first. Low-risk people choose the second. Self-selection reveals type.

**Surprising application**: Job interviews as ordeal. Why do interviews involve stressful questions and long hours? Partly to screen for ability to handle pressure. But also: the very unpleasantness screens out people who aren't serious. Only those who really want the job submit to the ordeal.

**Failure modes**:
- Designing screens where types don't separate - if both types prefer the same option, you learn nothing
- Ignoring that screening is costly - you may reject good candidates or accept bad ones
- Missing that people can game screens - if the test is known, preparation substitutes for underlying quality
- Treating screens as fixed - good candidates learn which screens exist and how to pass them
- Confusing screening for quality with screening for fit - different objectives require different screens

**Go deeper**: Rothschild-Stiglitz on insurance markets. Standard personnel economics texts on job market screening.

---

### Principal-Agent Problems

**What**: When one party (agent) acts on behalf of another (principal), their interests may diverge. The agent has information or actions the principal can't observe. This structure is everywhere delegation exists.

**Why it matters**: Employment, management, democracy, finance, healthcare - all involve principals delegating to agents with divergent interests. The framing reveals where interests diverge and what structures address it. Most organizational problems have principal-agent structure.

**The key move**: Identify the principal and agent. Ask: where do their interests diverge? What can the agent do or know that the principal can't observe? Then evaluate how the relationship structure addresses (or fails to address) this gap.

**Classic application**: Employment. Employers (principal) want effort. Employees (agent) want compensation with minimal effort. The agent has private information about their effort and ability. Monitoring, incentive pay, and career concerns address the gap imperfectly.

**Surprising application**: Democracy. Citizens (principal) delegate to politicians (agent) with divergent interests and private information about their actions and abilities. Elections are an imperfect monitoring mechanism. Politicians have short horizons and concentrated interests; citizens have long horizons and diffuse interests.

**Failure modes**:
- Assuming aligned interests when they diverge - "we're all on the same team" often isn't true
- Over-relying on monitoring - costly and incomplete
- Ignoring multi-principal problems - agents often serve multiple masters with conflicting demands
- Treating agents as having fixed types - effort and honesty respond to incentives
- Confusing the level of analysis - who is principal and who is agent depends on the frame

**Go deeper**: Jensen and Meckling's foundational paper on agency costs. Milgrom and Roberts' "Economics, Organization and Management."

---

### Mechanism Design

**What**: If you can design the rules, you can shape outcomes. Work backward from desired behavior to incentive structures that produce it. Instead of predicting behavior in a given game, design the game to produce behavior you want.

**Why it matters**: Auctions, voting systems, matching markets, compensation schemes - all are designed mechanisms. Mechanism design is economics as engineering. The revelation principle shows that any outcome achievable by any mechanism can be achieved by one where people truthfully reveal their information.

**The key move**: Specify the outcome you want. Identify agents' private information and incentives. Design rules that make honest revelation and desired behavior individually rational. The mechanism should be incentive-compatible (people want to reveal truth) and individually rational (people want to participate).

**Classic application**: Auction design. Different auction formats (sealed-bid, ascending, Vickrey) produce different bidding behavior and revenue. In a Vickrey (second-price sealed-bid) auction, bidding your true value is dominant strategy - the mechanism makes honesty optimal.

**Surprising application**: Matching markets (medical residencies, school choice, kidney exchange). The algorithm isn't just implementing preferences - it's designed to make truthful preference revelation optimal. The Gale-Shapley algorithm for stable matching is a mechanism design achievement.

**Failure modes**:
- Designing mechanisms that aren't incentive-compatible - people will game them
- Ignoring implementation costs and gaming possibilities - theory and practice differ
- Forgetting that mechanism design requires authority to set rules - you need enforcement power
- Treating the revelation principle as a how-to guide - it's a theoretical result, not a practical method
- Ignoring participation constraints - people must want to play your game

**Go deeper**: Roth's "Who Gets What and Why" for accessible treatment. Myerson's work for theory. Milgrom's "Putting Auction Theory to Work."

---

## Tier 2: Reasoning Under Uncertainty

Tools for situations where the future is unknown.

---

### Risk vs Uncertainty

**What**: Risk is quantifiable - you know the probability distribution. Uncertainty is not - you don't even know the distribution. They require different reasoning. Most real situations involve both, but treating Knightian uncertainty as if it were quantifiable risk leads to false precision.

**Why it matters**: Insurance works for quantifiable risks (actuarial tables exist). It fails for novel events where the distribution is unknown. Financial models that treat uncertainty as risk blow up spectacularly when unprecedented events occur.

**The key move**: Ask: do I know the probability distribution? If yes, expected value/utility calculations apply. If no, you need different tools - robustness, optionality, scenario planning, heuristics. Don't pretend to know distributions you don't know.

**Classic application**: Insurance pricing. Actuarial tables work for quantifiable risks - car accidents have stable statistical properties. They fail for unprecedented events (9/11, COVID) where there's no historical distribution to reference.

**Surprising application**: Career planning. Some career domains have quantifiable risk - sales has a known distribution of outcomes. Others have Knightian uncertainty - founding a company in a new market has no reference class. The appropriate planning strategies differ fundamentally.

**Failure modes**:
- Pretending uncertainty is risk - assigning fake probabilities to unknowable events
- Paralysis when facing uncertainty - inaction is also a choice
- Confusing risk aversion with uncertainty aversion - they're different
- Treating all uncertainty as equal - some unknowns are more unknown than others
- Using expected value when you should use robustness

**Go deeper**: Knight's "Risk, Uncertainty, and Profit" for the foundational distinction. Taleb's "Antifragile" and "Black Swan" for practical implications.

---

### Option Value

**What**: The ability to choose later, after learning more, has value independent of which choice you'll make. Optionality is an asset. Flexibility to respond to information is worth preserving.

**Why it matters**: Irreversible commitments destroy option value. Premature optimization can be costly. Sometimes the right move is to preserve flexibility. The value of waiting depends on how much you'll learn by waiting.

**The key move**: Ask: what's the value of being able to decide later with more information? Compare this to the cost of delaying. Option value is high when: uncertainty is high, learning is likely, and commitment is irreversible.

**Classic application**: Real options in capital budgeting. A factory that can switch between products is worth more than one locked into a single product, even if the expected output is the same. Flexibility has value.

**Surprising application**: Career decisions. A generalist early career preserves options. Specializing is valuable but destroys optionality. The question is when to exercise the option - when the value of commitment exceeds the value of waiting to learn more.

**Failure modes**:
- Ignoring option value - committing prematurely when waiting would be valuable
- Overweighting option value - never committing, analysis paralysis
- Treating optionality as free - there's often a cost to keeping options open
- Ignoring that options expire - waiting too long loses the option entirely
- Confusing option value with risk aversion - they're related but distinct

**Go deeper**: Dixit and Pindyck's "Investment Under Uncertainty." Real options literature in finance.

---

### Expected Value vs Expected Utility

**What**: Rational choice under risk isn't about maximizing expected value - it's about maximizing expected utility. And utility isn't linear in wealth. Most people are risk-averse: a guaranteed $50 is worth more than a 50% chance of $100, even though expected values are equal.

**Why it matters**: Risk aversion is rational when utility is concave. Turning down positive expected value bets can be sensible. Kelly betting, insurance, and portfolio theory all depend on this distinction.

**The key move**: Don't just multiply probability by payoff. Ask: what's the utility of each outcome? People are typically risk-averse (diminishing marginal utility of wealth), which means equivalent expected values don't mean equivalent desirability.

**Classic application**: The St. Petersburg paradox. A game with infinite expected value isn't worth infinite price because the utility of infinite wealth isn't infinite (and you might lose everything getting there). Expected utility resolves the paradox.

**Surprising application**: Why rich people take more risks. Diminishing marginal utility means the next dollar matters less to a billionaire. At higher wealth, expected value approximates expected utility better. This makes expected-value-maximizing behavior more rational at higher wealth levels.

**Failure modes**:
- Using expected value when expected utility applies - ignoring risk preferences
- Assuming universal risk aversion - some domains show risk-seeking (gambling on longshots when behind)
- Ignoring that utility functions differ across people and contexts
- Treating utility as cardinal when it's ordinal - you can compare but not add utilities
- Confusing risk aversion with loss aversion - they have different implications

**Go deeper**: Von Neumann-Morgenstern utility theory. Kahneman and Tversky's prospect theory for modifications based on observed behavior.

---

### Bayesian Updating

**What**: When you get new information, update your beliefs proportionally to how much that information should surprise you under each hypothesis. New evidence that's more likely under hypothesis A than B should increase your belief in A relative to B.

**Why it matters**: Structured belief updating avoids both under-reaction (ignoring new evidence) and over-reaction (overweighting recent evidence). It's a discipline for incorporating information consistently.

**The key move**: Start with prior beliefs. When new evidence arrives, ask: how likely is this evidence if hypothesis A is true? How likely if hypothesis B is true? Update proportionally to this likelihood ratio. The posterior equals the prior times the likelihood ratio (normalized).

**Classic application**: Medical diagnosis. A positive test result should update your belief based on the test's accuracy (sensitivity, specificity) and the base rate of the disease. False positives are common when testing for rare diseases.

**Surprising application**: Evaluating expertise. When an expert makes a prediction that comes true, update based on: would they have made that prediction if they were just guessing? If the prediction was unusual and came true, update a lot (strong evidence of skill). If it was obvious, update little.

**Failure modes**:
- Ignoring base rates - the prior matters; rare events stay rare even with positive tests
- Updating on evidence you would have seen regardless - selection effects contaminate inference
- Treating absence of evidence as evidence of absence - sometimes you just didn't look
- Over-updating on vivid evidence - memorable events aren't necessarily diagnostic
- Under-updating on statistical evidence - representative samples beat anecdotes

**Go deeper**: Any Bayesian statistics text. Jaynes' "Probability Theory: The Logic of Science" for foundations.

---

### Price as Information

**What**: Prices aggregate dispersed information. No single person knows everything, but prices can reflect the collective knowledge of all market participants. This makes prices informative signals about value, scarcity, and expectations.

**Why it matters**: This is Hayek's fundamental insight. Central planners can't know what prices know - the distributed knowledge of millions of people making decisions. Prices coordinate without coordination. But this also means prices can be wrong when the information they aggregate is wrong.

**The key move**: When you see a price, ask: what information is this aggregating? Whose knowledge is reflected? A high price for a stock reflects the aggregate judgment of all traders. A rising price reflects changing information or expectations.

**Classic application**: The efficient market hypothesis. Stock prices reflect all available information (in its strong form). You can't beat the market because the market already knows what you know. Prices are sufficient statistics for value.

**Surprising application**: Prediction markets. Markets can aggregate dispersed information about future events. Betting odds often outperform expert forecasts because they aggregate many experts (and non-experts with local knowledge).

**Failure modes**:
- Treating prices as infallible - they aggregate available information, which may be wrong
- Ignoring that some information isn't reflected - private information, manipulation
- Assuming all markets are equally informative - thin markets with few traders are noisy
- Confusing price with value - prices reflect beliefs, which can be systematically biased
- Missing reflexivity - in some markets, prices affect the underlying value they're supposed to measure

**Go deeper**: Hayek's "The Use of Knowledge in Society." Fama on efficient markets (and the debate over its limits).

---

### Winner's Curse

**What**: In competitive bidding for uncertain-value items, the winner tends to have overestimated value. You win by bidding most, which means you're the one who made the biggest positive error. Winning is evidence you overbid.

**Why it matters**: This applies to any auction-like competition with uncertain values - bidding for companies, hiring negotiations, competing for contracts. The structure of competition can cause systematic overpayment even by rational bidders who don't account for selection.

**The key move**: When competing for something of uncertain value, recognize that winning is information. Ask: if I win, what does that tell me about whether I bid too high? Adjust your bid downward to account for the winner's curse.

**Classic application**: Oil tract auctions. Companies bidding for drilling rights estimate the oil reserves. The company with the highest estimate wins. But if estimates are unbiased on average, the highest estimate is probably too high. Winners systematically overpay.

**Surprising application**: Hiring. When you beat other employers to hire someone, ask why. Maybe you correctly recognized value others missed. But maybe you overestimated - you're the one who made the biggest positive error about this candidate's worth. Winning a bidding war is cause for concern, not celebration.

**Failure modes**:
- Ignoring the selection effect of winning - treating your estimate as unbiased
- Over-correcting into never bidding - some risk of winner's curse doesn't mean never compete
- Applying winner's curse logic to common-value settings when values are private - the curse only applies when there's a "true" value everyone is estimating
- Missing that sophisticated bidders shade their bids, changing the equilibrium
- Confusing winner's curse with paying too much for other reasons

**Go deeper**: Thaler's "The Winner's Curse" for accessible treatment. Kagel and Levin for experimental evidence. Oil auction empirical literature.

---

## Quick Reference

### Decision Type -> Tool

| You're asking... | Start with... |
|------------------|---------------|
| Why does this market fail? | Adverse Selection or Moral Hazard |
| What does this costly action reveal? | Signaling |
| How do I extract information? | Screening |
| Why isn't delegation working? | Principal-Agent |
| How should I design the rules? | Mechanism Design |
| Can I quantify this uncertainty? | Risk vs Uncertainty |
| What's flexibility worth? | Option Value |
| How do I value risky outcomes? | Expected Utility |
| How should I update beliefs? | Bayesian Updating |
| What does this price tell me? | Price as Information |
| Why do I keep overpaying? | Winner's Curse |

---

## Reading Path

**Foundations (start here)**:
- Akerlof, Spence, Stiglitz Nobel lectures (all accessible)
- Dixit and Nalebuff, "Thinking Strategically"

**Going deeper**:
- Milgrom and Roberts, "Economics, Organization and Management"
- Knight, "Risk, Uncertainty, and Profit"

**Advanced**:
- Roth, "Who Gets What and Why"
- Myerson's mechanism design papers

---

## Usage Notes

These tools work best when information asymmetry is the central feature. Not every market problem is an information problem.

**Domain of applicability**: Strong where information is costly, private, or asymmetrically distributed. Weaker where information is cheap and public, or where non-informational factors dominate.

**Limitations**: Information economics can over-explain. Not every market failure is adverse selection. Not every insurance problem is moral hazard. These are hypotheses to test, not conclusions to assume.

**Composition**: Adverse selection and signaling/screening are solutions to each other - signaling resolves adverse selection. Moral hazard and mechanism design connect - design mechanisms to mitigate hidden action. Bayesian updating and screening combine - screens provide information that gets incorporated via updating.

**Integration**: Information tools complement core economics (they explain why simple market models fail) and behavioral economics (boundedly rational agents handle information differently than optimal Bayesians).
