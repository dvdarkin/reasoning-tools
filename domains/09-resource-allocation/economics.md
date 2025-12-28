# Economic Reasoning: A Map of the Territory

A crash course in thinking tools extracted from economics. Not models, not theory - the underlying reasoning primitives that transfer across domains.

---

## How to Use This Map

This document is structured as a taxonomy of reasoning tools. Each tool follows the same format:

- **What**: The core concept in one or two sentences
- **Why it matters**: What problem it solves, what it lets you see
- **The key move**: The mental operation you perform
- **Classic application**: Where this originated or is most clearly illustrated
- **Surprising application**: Where the same reasoning transfers unexpectedly
- **Failure modes**: How this tool misleads when misapplied
- **Go deeper**: Pointers to serious treatment

The tools are organized into four tiers:
1. **Foundations** - Primitives that underlie everything else
2. **Strategic Interaction** - Tools for multi-agent reasoning
3. **Information and Uncertainty** - Tools for reasoning under incomplete knowledge
4. **Dynamics and Emergence** - Tools for systems that evolve over time

---

# Tier 1: Foundations

These are the atomic reasoning moves. Everything else builds on them.

---

## Opportunity Cost

**What**: The true cost of any choice is the value of the best alternative you gave up. Not what you paid - what you forwent.

**Why it matters**: Sticker prices lie. Time is unpriced. Most decisions look different when you ask "compared to what?"

**The key move**: For any choice, identify the realistic next-best use of the same resources. That's your benchmark, not zero.

**Classic application**: Career decisions. The cost of a PhD isn't tuition - it's five years of foregone salary and career progression.

**Surprising application**: Attention allocation. Every article you read costs every other article you could have read. Every meeting costs every other use of that hour.

**Failure modes**: 
- Comparing to "doing nothing" when that's not a real option
- Treating sunk costs as relevant (they're not - opportunity cost is forward-looking)
- Ignoring optionality value in alternatives

**Go deeper**: Buchanan's "Cost and Choice" for the philosophical foundations. Bastiat's "What is Seen and What is Not Seen" for the original articulation.

---

## Marginal Thinking

**What**: Decisions happen at the margin. Not "is X good" but "is one more unit of X worth the cost of one more unit, given current levels."

**Why it matters**: Almost nothing is binary. The interesting question is usually "how much" not "whether." And the answer changes based on where you already are.

**The key move**: Ask what changes with one more unit. Benefits typically diminish (the tenth cookie is less valuable than the first). Costs often increase (the tenth hour of work is harder than the first). Optimization is where these cross.

**Classic application**: Production decisions. Firms don't ask "should we make widgets?" They ask "should we make one more widget given what we're already producing?"

**Surprising application**: Relationships. Not "is this friendship good" but "is the next hour invested in this friendship worth more than the next hour invested elsewhere, given current investment levels."

**Failure modes**:
- Using averages when you need marginals
- Ignoring that margins shift as quantities change
- Treating discrete decisions as if they were continuous (sometimes choices really are binary)

**Go deeper**: Any intermediate microeconomics text covers this formally. Marshall's "Principles of Economics" for the historical development.

---

## Trade-offs and Constraints

**What**: Scarcity forces choice. You can't have everything. Every system operates within constraints - budgets, time, physics, attention, political capital.

**Why it matters**: Wishful thinking ignores constraints. Effective reasoning identifies the binding constraint and works within or around it.

**The key move**: For any objective, ask: what limits progress? Is it money, time, information, coordination, legitimacy, attention? The binding constraint is where additional resources would actually help. Loosening non-binding constraints is waste.

**Classic application**: Budget constraints in consumer choice. You maximize utility subject to your budget, not in the abstract.

**Surprising application**: Organizational strategy. Most organizations are bottlenecked by one or two binding constraints (often attention of key decision-makers). Everything else is slack.

**Failure modes**:
- Optimizing against non-binding constraints
- Treating all constraints as fixed when some are negotiable
- Ignoring that relieving one constraint often reveals another

**Go deeper**: Goldratt's "Theory of Constraints" for the operations angle. Linear programming literature for the formal treatment.

---

## Comparative Advantage

**What**: Efficient allocation depends on relative productivity, not absolute. You should specialize in tasks where your opportunity cost is lowest relative to others - even if you're not the best in absolute terms.

**Why it matters**: Absolute thinking leads to bad allocation. The best programmer shouldn't debug if their comparative advantage is architecture, even if they're also the best debugger.

**The key move**: Don't ask "who's best at X." Ask "who gives up least to do X." Convert absolute productivity into opportunity cost terms.

**Classic application**: International trade. A country that's worse at everything still has comparative advantage in something. Trade benefits both parties.

**Surprising application**: Team composition. A founder who can do everything should still delegate based on comparative advantage. The question isn't what they can do, but what costs them least relative to others.

**Failure modes**:
- Assigning tasks to whoever is "best" (absolute advantage thinking)
- Ignoring transaction costs of coordination and trade
- Forgetting that comparative advantage can shift with investment

**Go deeper**: Ricardo's original treatment. Deardorff's work on the theory of comparative advantage.

---

## Equilibrium as Analytical Tool

**What**: A situation is in equilibrium when no agent has incentive to unilaterally change their behavior. Not a prediction that systems reach equilibrium - a consistency check on your reasoning.

**Why it matters**: If your model of a situation has someone leaving money on the table indefinitely, you're missing something. Equilibrium analysis finds where behavior is mutually consistent.

**The key move**: For any proposed outcome, ask: given what everyone else is doing, does anyone want to deviate? If yes, trace where deviations lead. If no, you've found a stable configuration.

**Classic application**: Market clearing. Price adjusts until quantity supplied equals quantity demanded. At that point, no buyer or seller wants to change behavior.

**Surprising application**: Social norms. A norm persists when everyone following it is individually rational given that others follow it. Norm change requires coordinated deviation.

**Failure modes**:
- Assuming systems reach equilibrium (they often don't)
- Ignoring multiple equilibria (different stable configurations are possible)
- Confusing equilibrium with optimality (stable doesn't mean good)

**Go deeper**: Nash's original papers. Schelling's "Strategy of Conflict" for intuitive treatment.

---

# Tier 2: Strategic Interaction

These tools apply when your outcomes depend on what others do - and they're reasoning about you too.

---

## Incentive Mapping

**What**: Agents respond to actual incentives, not intended ones. The behavior a system produces is the behavior it rewards.

**Why it matters**: Systems routinely produce outcomes their designers didn't want because the incentive structure rewards something else. Diagnosing this requires mapping incentives as they are, not as hoped.

**The key move**: For any system, identify what actions are rewarded, what's punished, who monitors, and what the monitors' incentives are. Then predict behavior that maximizes reward within those rules.

**Classic application**: Compensation design. Salespeople paid on revenue maximize revenue, not profit. Employees measured on lines of code write verbose code.

**Surprising application**: Content recommendation. Algorithms optimizing for engagement produce outrage because outrage engages. The system is working exactly as designed, just not as intended.

**Failure modes**:
- Assuming agents share your objectives
- Ignoring that measurement itself shapes behavior (Goodhart's law)
- Forgetting that monitors need incentives too

**Go deeper**: Kerr's "On the Folly of Rewarding A While Hoping for B." Principal-agent literature generally.

---

## Game Structures

**What**: Strategic situations have structure - who moves when, who knows what, how payoffs relate. Recognizing the structure points to likely dynamics.

**Why it matters**: A negotiation is different from an auction is different from a war of attrition. Each structure has characteristic dynamics. Pattern-matching helps.

**The key move**: Identify the game structure. Sequential vs simultaneous moves? Complete vs incomplete information? One-shot vs repeated? Zero-sum vs positive-sum? Each combination has known dynamics.

**Key structures to recognize**:

*Prisoner's Dilemma*: Individual rationality leads to collective disaster. Both parties would benefit from cooperation but have individual incentive to defect.

*Coordination Game*: Multiple equilibria exist. The problem isn't incentive alignment - it's agreeing which equilibrium to coordinate on.

*Chicken/Brinkmanship*: Mutual destruction is worst. Each party wants to hold out while the other swerves. Commitment devices matter.

*Assurance/Stag Hunt*: Cooperation is better but risky. You cooperate if you trust others will. Confidence in others is the key variable.

*Battle of the Sexes*: Both want to coordinate but prefer different equilibria. The question is who accommodates whom.

**Classic application**: Arms races (Prisoner's Dilemma). Technical standards adoption (Coordination). Price wars (Chicken).

**Surprising application**: Academic citation (Coordination - everyone cites what everyone else cites). Diet and exercise commitments (single-player Prisoner's Dilemma against your future self).

**Failure modes**:
- Treating all strategic interactions as zero-sum
- Missing that repeated games differ fundamentally from one-shot games
- Assuming the structure when you should be diagnosing it

**Go deeper**: Dixit and Nalebuff's "Thinking Strategically." Schelling's "Strategy of Conflict."

---

## Commitment and Credibility

**What**: Sometimes you benefit from limiting your own options. A credible commitment to a future action changes what others do now.

**Why it matters**: Flexibility is usually valuable, but in strategic situations, the ability to commit can be more valuable. Burning bridges can help.

**The key move**: Ask whether you'd benefit if you could credibly commit to a future action. If yes, find a way to make that commitment credible - by making defection costly, visible, or impossible.

**Classic application**: Nuclear deterrence. The commitment to retaliate must be credible, even though retaliation after being destroyed serves no purpose. Hence automated systems, decentralized authority, public doctrine.

**Surprising application**: Ulysses and the Sirens. Binding yourself to the mast (removing future options) is rational when you know your future self will be compromised.

**Failure modes**:
- Making commitments that aren't credible
- Committing when flexibility would serve better
- Forgetting that others assess your commitment credibility

**Go deeper**: Schelling's "Strategy of Conflict." Elster's "Ulysses and the Sirens" for self-commitment.

---

## Repeated Games and Reputation

**What**: When interactions repeat, the future casts a shadow on the present. Reputation becomes an asset. Cooperation can emerge even among self-interested agents.

**Why it matters**: One-shot logic often fails. Agents sacrifice short-term gains to preserve reputation and future cooperation possibilities.

**The key move**: Ask: is this one-shot or repeated? If repeated, how does future value compare to present temptation? Cooperation is sustainable when the future matters enough.

**Key insight**: Cooperation in repeated games isn't altruism - it's self-interest that accounts for future interactions. Defection becomes irrational when it costs more in future reputation than it gains now.

**Classic application**: Business relationships. Short-term cheating is possible but destroys future deals. Reputation is capital.

**Surprising application**: End-game effects. Cooperation unravels when the end is known (finite game) but sustains when it's uncertain (indefinite game). This explains retirement-phase defection.

**Failure modes**:
- Applying repeated-game logic to one-shot situations
- Underweighting reputation in long-term relationships
- Missing end-game dynamics

**Go deeper**: Axelrod's "Evolution of Cooperation." Folk theorem literature for formal treatment.

---

## Mechanism Design

**What**: If you can design the rules, you can shape outcomes. Work backward from desired behavior to incentive structures that produce it.

**Why it matters**: Instead of predicting behavior in a given game, you design the game to produce behavior you want. This is economics as engineering.

**The key move**: Specify the outcome you want. Identify agents' private information and incentives. Design rules that make honest revelation and desired behavior individually rational.

**Classic application**: Auction design. Different auction formats (sealed-bid, ascending, Vickrey) produce different bidding behavior and revenue. Choose the format that achieves your goal.

**Surprising application**: Matching markets (medical residencies, school choice, kidney exchange). The algorithm isn't just implementing preferences - it's shaping what preferences people reveal.

**Failure modes**:
- Designing mechanisms that aren't incentive-compatible
- Ignoring implementation costs and gaming possibilities
- Forgetting that mechanism design requires authority to set rules

**Go deeper**: Roth's "Who Gets What and Why" for accessible treatment. Myerson's work for theory.

---

## Principal-Agent Problems

**What**: When one party (agent) acts on behalf of another (principal), their interests may diverge. The agent has information or actions the principal can't observe.

**Why it matters**: Delegation is ubiquitous - employment, management, democracy, finance. Principal-agent framing reveals where interests diverge and what structures address it.

**The key move**: Identify the principal and agent. Ask: where do their interests diverge? What can the agent do or know that the principal can't observe? Then evaluate how the relationship structure addresses (or fails to address) this gap.

**Classic application**: Employment. Employers (principal) want effort. Employees (agent) want compensation for minimal effort. Monitoring, incentive pay, and career concerns address the gap imperfectly.

**Surprising application**: Democracy. Citizens (principal) delegate to politicians (agent) with divergent interests and private information. Elections are an imperfect monitoring mechanism.

**Failure modes**:
- Assuming aligned interests when they diverge
- Over-relying on monitoring (costly and incomplete)
- Ignoring multi-principal problems (agents serving multiple masters)

**Go deeper**: Jensen and Meckling's original paper. Milgrom and Roberts' "Economics, Organization and Management."

---

# Tier 3: Information and Uncertainty

These tools apply when you don't know everything - and neither does anyone else.

---

## Adverse Selection

**What**: When one party has private information about quality before a transaction, the uninformed party can't distinguish good from bad. This can collapse markets.

**Why it matters**: Markets for used cars, insurance, credit, and talent all suffer from this. The structure of the problem points to the structure of solutions.

**The key move**: Identify the pre-transaction information asymmetry. Ask: if the uninformed party can't distinguish quality, what average quality will be offered? If that average drives out high quality, the market unravels.

**Classic application**: Akerlof's "Market for Lemons." If buyers can't verify car quality, they pay average-quality prices. Owners of good cars won't sell at those prices. Market is left with lemons.

**Surprising application**: Hiring. Employers can't perfectly assess candidate quality. This drives credential inflation (everyone gets the signal, so signal becomes meaningless) and excessive interviewing.

**Remedies**: 
- Signaling (informed party takes costly action to reveal type)
- Screening (uninformed party designs filter to separate types)
- Certification (third party verifies quality)
- Warranties (quality guarantee shifts risk back to informed party)

**Failure modes**:
- Treating all information problems as adverse selection (confusing with moral hazard)
- Ignoring that signals and screens are costly
- Assuming adverse selection is always present (sometimes information asymmetry is minimal)

**Go deeper**: Akerlof's original paper. Spence on signaling. Rothschild-Stiglitz on insurance markets.

---

## Moral Hazard

**What**: When one party's actions affect outcomes but can't be observed, they have incentive to act differently than they would under observation.

**Why it matters**: Insurance changes behavior. Bailouts change behavior. Any risk-sharing arrangement confronts this problem.

**The key move**: Identify post-transaction hidden action. Ask: how does the party's behavior change when they don't bear full consequences of their actions?

**Classic application**: Insurance. Insured drivers drive less carefully. The problem isn't that bad drivers buy insurance (that's adverse selection) - it's that insurance makes drivers worse.

**Surprising application**: Corporate limited liability. When downside is capped but upside isn't, excessive risk-taking is rational. This explains some financial crisis dynamics.

**Remedies**:
- Monitoring (observe actions directly - costly)
- Incentive alignment (make agent bear some consequences)
- Deductibles and co-pays (keep some skin in the game)
- Bonding (agent posts collateral they lose if they shirk)

**Failure modes**:
- Confusing moral hazard with adverse selection (hidden action vs hidden type)
- Over-relying on monitoring
- Ignoring that incentive pay creates its own distortions

**Go deeper**: Holmstrom's papers on moral hazard. Insurance economics literature.

---

## Signaling

**What**: When you have private information others care about, you can take costly actions to credibly reveal it - but only if the cost differs by type.

**Why it matters**: Signals are everywhere - education, luxury goods, corporate dividends, peacock tails. Understanding the structure reveals when signals are informative and when they're pure waste.

**The key move**: For any costly action that seems to convey information, ask: is the cost lower for the type being signaled? If yes, it can be a separating signal. If no, it's noise or pooling.

**Classic application**: Spence's job market signaling. Education might not build skills but signals ability. The signal works because education is easier (less costly) for high-ability individuals.

**Surprising application**: Handicapping in biology. The peacock's tail signals fitness precisely because it's costly. Only genuinely fit peacocks can afford the handicap.

**Key distinctions**:
- Separating equilibrium: different types take different actions, signal is informative
- Pooling equilibrium: all types take same action, signal is uninformative
- Wasteful signaling: the signal is informative but resources spent on it are pure cost

**Failure modes**:
- Treating all costly actions as signals
- Ignoring that signaling is often socially wasteful even when privately rational
- Missing that signals can become uninformative as everyone acquires them

**Go deeper**: Spence's original paper. Zahavi's handicap principle for biology. Feltovich, Harbaugh, To on countersignaling.

---

## Risk vs Uncertainty

**What**: Risk is quantifiable - you know the probability distribution. Uncertainty is not - you don't even know the distribution. They require different reasoning.

**Why it matters**: Most decisions under "uncertainty" involve both. Treating Knightian uncertainty as if it were quantifiable risk leads to false precision.

**The key move**: Ask: do I know the probability distribution? If yes, expected value/utility calculations apply. If no, you need different tools - robustness, optionality, scenario planning.

**Classic application**: Insurance pricing works for quantifiable risks (actuarial tables). It fails for novel events where the distribution is unknown (emerging technology liability).

**Surprising application**: Career planning. Some career domains have quantifiable risk (sales - you know the distribution of outcomes). Others have Knightian uncertainty (founding a company in a new market - no distribution to reference).

**Responses to uncertainty (not risk)**:
- Robustness: choose options that perform tolerably across many scenarios
- Optionality: preserve ability to adapt when you learn more
- Diversification: spread across uncorrelated bets
- Heuristics: simple rules that work well on average without requiring probability estimates

**Failure modes**:
- Pretending uncertainty is risk (false precision)
- Paralysis when facing uncertainty
- Confusing risk aversion with uncertainty aversion

**Go deeper**: Knight's "Risk, Uncertainty, and Profit." Taleb's "Antifragile" for practical implications.

---

## Option Value

**What**: The ability to choose later, after learning more, has value independent of which choice you'll make. Optionality is an asset.

**Why it matters**: Irreversible commitments destroy option value. Premature optimization can be costly. Sometimes the right move is to preserve flexibility.

**The key move**: Ask: what's the value of being able to decide later with more information? Compare this to the cost of delaying. Option value is high when: uncertainty is high, learning is likely, commitment is irreversible.

**Classic application**: Real options in capital budgeting. A factory that can switch between products is worth more than one locked into a single product, even if the expected output is the same.

**Surprising application**: Career decisions. A generalist early career preserves options. Specializing is valuable but destroys optionality. The question is when to exercise the option.

**Key factors**:
- Volatility: higher uncertainty means higher option value
- Time to expiry: longer timeframe means higher option value
- Reversibility: more irreversible commitment means option value matters more

**Failure modes**:
- Ignoring option value (committing prematurely)
- Overweighting option value (never committing, analysis paralysis)
- Treating optionality as free (there's often a cost to keeping options open)

**Go deeper**: Dixit and Pindyck's "Investment Under Uncertainty." Real options literature.

---

## Expected Value vs Expected Utility

**What**: Rational choice under risk isn't about maximizing expected value - it's about maximizing expected utility. And utility isn't linear in wealth.

**Why it matters**: Risk aversion is rational. Turning down positive expected value bets can be sensible. Kelly betting, insurance, and portfolio theory all depend on this distinction.

**The key move**: Don't just multiply probability by payoff. Ask: what's the utility of each outcome? People are typically risk-averse (diminishing marginal utility of wealth), which means equivalent expected values don't mean equivalent desirability.

**Classic application**: The St. Petersburg paradox. A game with infinite expected value isn't worth infinite price because utility of infinite wealth isn't infinite (and you might lose everything getting there).

**Surprising application**: Why rich people take more risks. Diminishing marginal utility means the next dollar matters less to a billionaire. This makes expected-value-maximizing behavior more rational at higher wealth.

**Key concepts**:
- Diminishing marginal utility: each additional unit of wealth is worth less
- Certainty equivalent: the guaranteed amount you'd accept instead of a gamble
- Risk premium: the expected value you'll sacrifice for certainty

**Failure modes**:
- Using expected value when expected utility applies
- Assuming universal risk aversion (some domains show risk-seeking behavior)
- Ignoring that utility functions differ across people and contexts

**Go deeper**: Von Neumann-Morgenstern utility theory. Kahneman and Tversky for prospect theory modifications.

---

## Bayesian Updating

**What**: When you get new information, update your beliefs proportionally to how much that information should surprise you under each hypothesis.

**Why it matters**: Structured belief updating avoids both under-reaction (ignoring new evidence) and over-reaction (overweighting recent evidence).

**The key move**: Start with prior beliefs. When new evidence arrives, ask: how likely is this evidence if hypothesis A is true? How likely if hypothesis B is true? Update proportionally to this likelihood ratio.

**Classic application**: Medical diagnosis. A positive test result should update your belief based on the test's accuracy and the base rate of the disease.

**Surprising application**: Evaluating expertise. When an expert makes a prediction that comes true, update based on: would they have made that prediction if they were just guessing? (If the prediction was unusual and came true, update a lot. If it was obvious, update little.)

**Key concepts**:
- Prior: your belief before new evidence
- Likelihood: probability of seeing this evidence if the hypothesis is true
- Posterior: your belief after updating

**Failure modes**:
- Ignoring base rates (base rate neglect)
- Updating on evidence you would have seen regardless of the hypothesis (selection effects)
- Treating absence of evidence as evidence of absence (sometimes you just didn't look)

**Go deeper**: Any Bayesian statistics text. Jaynes' "Probability Theory" for foundations.

---

# Tier 4: Dynamics and Emergence

These tools apply to systems that change over time and produce aggregate patterns.

---

## Externalities

**What**: When an action imposes costs or benefits on parties not involved in the decision, private optimization diverges from social optimum.

**Why it matters**: Externalities are everywhere - pollution, noise, network effects, herd immunity. Recognizing them identifies where uncoordinated action fails and where intervention might help.

**The key move**: For any activity, ask: who bears costs or receives benefits outside the decision-maker? The gap between private and social cost/benefit indicates over- or under-production.

**Classic application**: Pollution. Factory owners don't pay for the air quality damage they impose. Result: too much pollution relative to social optimum.

**Surprising application**: Positive externalities in knowledge production. Inventors can't capture all value from their inventions (others learn and build). Result: underinvestment in research relative to social optimum.

**Remedies**:
- Pigovian pricing: tax negative externalities, subsidize positive
- Property rights (Coase): if defined and tradeable, parties can bargain to efficient outcome
- Regulation: quantity limits
- Public provision: for extreme cases (public goods)

**Failure modes**:
- Treating all third-party effects as externalities (pecuniary vs technological distinction)
- Assuming externalities require intervention (Coase theorem conditions sometimes hold)
- Ignoring that remedies have costs and create their own distortions

**Go deeper**: Pigou's original treatment. Coase's "Problem of Social Cost."

---

## Public Goods and Collective Action

**What**: When goods are non-excludable (can't prevent non-payers from enjoying) and non-rival (one person's use doesn't reduce another's), private provision fails.

**Why it matters**: Defense, basic research, clean air, open-source software - these are underprovided by markets. Understanding why points to what institutional structures can help.

**The key move**: For any good, ask: can non-payers be excluded? Does use reduce availability? If neither, it's a public good. Expect underprovision through voluntary action.

**Classic application**: National defense. Your protection doesn't reduce your neighbor's. You can't exclude non-payers within the territory. Free-riding is rational. Private provision fails.

**Surprising application**: Social movements and protests. Participation has private costs. Benefits are non-excludable (everyone gets the policy change). Free-riding is rational. Yet protests happen - explained by selective incentives, identity, expressive value.

**Key distinction**:
- Pure public good: non-excludable AND non-rival (rare)
- Club goods: excludable but non-rival (gyms, streaming services)
- Common pool resources: non-excludable but rival (fisheries, atmosphere)

**Failure modes**:
- Treating all shared resources as public goods
- Ignoring that some collective action problems get solved (Ostrom's work on commons governance)
- Assuming government provision is always the answer

**Go deeper**: Olson's "Logic of Collective Action." Ostrom's "Governing the Commons."

---

## Network Effects and Tipping Points

**What**: When the value of something depends on how many others use it, you get feedback loops, winner-take-all dynamics, and tipping points.

**Why it matters**: Platforms, standards, social networks, technologies - these don't follow supply-and-demand intuitions. Path dependency matters.

**The key move**: Ask: does the value to each user increase with total users? If yes, expect multiple equilibria (dominant standard or none), tipping points, and lock-in.

**Classic application**: Phone networks. A phone is useless if no one else has one. As adoption grows, value per user grows. This creates S-curve adoption and winner-take-all dynamics.

**Surprising application**: Social norms. The value of following a norm depends on others following it. This is why norms are stable until they tip, then change rapidly.

**Key dynamics**:
- Critical mass: the point at which network effects become self-sustaining
- Lock-in: once a standard wins, switching costs make it durable even if inferior
- Multi-homing: when users can participate in multiple networks, winner-take-all is less strong

**Failure modes**:
- Assuming the best technology wins (path dependency can lock in inferior standards)
- Ignoring that network effects can reverse (networks can collapse as fast as they grew)
- Treating all increasing returns as network effects (other mechanisms exist)

**Go deeper**: Shapiro and Varian's "Information Rules." Arthur's work on increasing returns.

---

## Reflexivity

**What**: When beliefs affect reality, and reality affects beliefs, you get feedback loops where cause and effect become circular.

**Why it matters**: Financial markets are reflexive. Self-fulfilling prophecies are real. Prediction and outcome aren't separable.

**The key move**: Ask: does believing X make X more likely to be true? If yes, the system is reflexive. Standard equilibrium thinking must be modified.

**Classic application**: Bank runs. If depositors believe a bank will fail, they withdraw. Withdrawals cause failure. The belief was self-fulfilling.

**Surprising application**: Economic forecasting. If the central bank forecasts recession, that forecast changes behavior, which changes whether recession happens. The forecast interacts with its object.

**Key distinction**:
- Positive reflexivity: belief in X makes X more likely (bubbles)
- Negative reflexivity: belief in X makes X less likely (successful prediction triggers prevention)

**Failure modes**:
- Treating social systems like natural systems (ignoring that participants react to models)
- Overweighting reflexivity (not everything is reflexive)
- Mistaking correlation for reflexive causation

**Go deeper**: Soros's "Alchemy of Finance." Merton on self-fulfilling prophecies.

---

## Time Discounting and Intertemporal Choice

**What**: Future costs and benefits are weighted differently than present ones. How agents trade off now versus later determines saving, investment, and long-term behavior.

**Why it matters**: Most important decisions involve intertemporal trade-offs. Understanding discounting reveals why people underinvest in the future and how to design better commitment structures.

**The key move**: Ask: how much is a future outcome discounted relative to the same outcome now? Is the discounting consistent over time (exponential) or does it shift (hyperbolic)? Inconsistent discounting creates self-control problems.

**Classic application**: Saving behavior. Exponential discounters have consistent plans. Hyperbolic discounters always plan to save "starting next month" - and next month never comes.

**Surprising application**: Addiction and habit. Present bias makes immediate reward overwhelming relative to future costs. This isn't irrationality - it's a predictable consequence of hyperbolic discounting.

**Key distinction**:
- Exponential discounting: constant discount rate, time-consistent preferences
- Hyperbolic discounting: present bias, time-inconsistent preferences, self-control problems

**Failure modes**:
- Assuming exponential discounting when hyperbolic applies
- Ignoring that discount rates differ across domains (health vs money vs relationships)
- Treating all future-discounting as bias to be corrected

**Go deeper**: Ainslie's "Picoeconomics." Laibson's work on hyperbolic discounting.

---

## Evolution and Selection

**What**: When entities vary, face selection pressure, and propagate differentially based on fitness, evolutionary dynamics emerge. This applies beyond biology.

**Why it matters**: Markets, ideas, institutions, and strategies evolve. Understanding selection pressure reveals what survives and why.

**The key move**: Ask: what is the selection environment? What is being selected for? What survives differential reproduction? Don't confuse what's "good" with what's selected for.

**Classic application**: Firm survival. Profit-maximizing firms survive; others don't. Even if no manager explicitly maximizes profit, the market selects as if they do.

**Surprising application**: Memes and ideas. Ideas that spread aren't necessarily true - they're ideas that have features making them spread (emotional resonance, simplicity, tribal identity).

**Key distinction**:
- Selection for vs selection of: selection is for the features that cause differential survival, selection of is the side effects that come along
- Fitness landscapes: the shape of the landscape (smooth vs rugged) determines whether selection finds global optima or gets stuck

**Failure modes**:
- Assuming evolution optimizes for what you care about
- Ignoring that selection environments change
- Treating survival as proof of optimality

**Go deeper**: Alchian's "Uncertainty, Evolution, and Economic Theory." Dawkins' "Selfish Gene" for gene-centered view.

---

# Tier 5: Behavioral Realism

Standard tools assume agents are rational optimizers. These tools model systematic deviations.

---

## Loss Aversion and Reference Dependence

**What**: Losses loom larger than equivalent gains. Evaluation is relative to a reference point, not absolute.

**Why it matters**: This explains risk-seeking in the domain of losses, the endowment effect, and why framing matters.

**The key move**: Identify the reference point. Outcomes above it are coded as gains, below as losses. Losses hurt roughly twice as much as equivalent gains please.

**Classic application**: Investment behavior. Investors hold losing stocks too long (hoping to avoid realizing the loss) and sell winners too early (locking in the gain).

**Surprising application**: Negotiations. Making a concession feel like avoiding a loss rather than forgoing a gain changes behavior dramatically.

**Go deeper**: Kahneman and Tversky's prospect theory papers.

---

## Framing and Mental Accounting

**What**: How choices are described affects decisions, even when the underlying options are identical. People maintain separate mental accounts that violate fungibility.

**Why it matters**: Presentation matters. The same objective choice can produce different decisions based on framing.

**The key move**: Ask: how is this choice being framed? What would happen with a different but logically equivalent frame? Are there mental accounts being treated as non-fungible when they shouldn't be?

**Classic application**: The "Asian disease problem." Same outcomes framed as lives saved vs lives lost produce opposite risk preferences.

**Go deeper**: Thaler's work on mental accounting.

---

## Anchoring

**What**: Numerical judgments are pulled toward arbitrary starting points, even irrelevant ones.

**Why it matters**: First numbers in a negotiation matter disproportionately. Estimates are biased by whatever number was recently encountered.

**The key move**: Ask: what anchors are present? How might they be biasing the judgment? In negotiations: move first if you have information; let them anchor if you don't.

**Go deeper**: Kahneman's "Thinking, Fast and Slow."

---

## Status Quo Bias and Default Effects

**What**: The current state is privileged. Changing requires justification; maintaining doesn't.

**Why it matters**: Default options are powerful. Opt-out beats opt-in. This explains inertia in everything from retirement plans to software settings.

**The key move**: Ask: what's the default? How would behavior change with a different default? Design defaults to match desired outcomes.

**Go deeper**: Thaler and Sunstein's "Nudge."

---

# Appendix: Quick Reference

## Decision Type -> Primary Tool

| You're asking... | Start with... |
|------------------|---------------|
| Should I do X? | Opportunity Cost |
| How much of X? | Marginal Analysis |
| Why does this persist? | Equilibrium Analysis |
| Why isn't this working? | Incentive Mapping |
| Who should do what? | Comparative Advantage |
| Why can't we coordinate? | Collective Action / Game Structure |
| Why does this market fail? | Information Asymmetry (Adverse Selection / Moral Hazard) |
| What's this signal mean? | Signaling |
| How should I bet? | Expected Utility + Risk vs Uncertainty |
| What's the value of waiting? | Option Value |
| Why the gap between private and social outcomes? | Externalities |
| Why winner-take-all? | Network Effects |
| Why is prediction so hard here? | Reflexivity |
| Why can't I stick to my plan? | Time Discounting |
| Why the irrational behavior? | Behavioral tools (loss aversion, framing, etc.) |

---

## Reading Path

**Foundations (start here)**:
- Schelling, "Micromotives and Macrobehavior"
- Dixit and Nalebuff, "Thinking Strategically"

**Strategic Interaction**:
- Schelling, "Strategy of Conflict"
- Axelrod, "Evolution of Cooperation"
- Roth, "Who Gets What and Why"

**Information**:
- Akerlof, Spence, Stiglitz (Nobel lectures are accessible)
- Taleb, "Antifragile"

**Dynamics**:
- Olson, "Logic of Collective Action"
- Ostrom, "Governing the Commons"
- Shapiro and Varian, "Information Rules"

**Behavioral**:
- Kahneman, "Thinking, Fast and Slow"
- Thaler and Sunstein, "Nudge"

---

## Usage Notes

These tools are lenses, not laws. They structure thinking but don't guarantee correct conclusions.

Every tool has a domain of applicability. Marginal thinking doesn't apply to genuinely binary choices. Equilibrium analysis doesn't apply to genuinely novel situations. Game theory doesn't apply to one-player optimization.

Multiple tools often apply. The skill is selecting the right lens for the situation - and knowing when to switch.

The tools generate hypotheses, not conclusions. "Incentive mapping suggests X" is different from "X is true." Always check conclusions against reality.
