# Competitive Game Theory: Transferable Reasoning Tools

## Why Competitive Game Theory Generates Useful Thinking Tools

Game theory's epistemic status is complex: it excels at revealing strategic structure in conflict situations but often fails at precise prediction. Most real-world "games" violate its core assumptions (perfect rationality, common knowledge, known payoffs), yet the framework remains invaluable because it exposes hidden interdependencies that intuition misses.

The case for extracting from game theory despite these limitations: humans systematically fail at strategic reasoning. We treat competitive situations as independent optimization problems, ignoring how others' responses reshape our options. We confuse "doing better" with "winning." We fail to recognize when cooperation becomes impossible or when competition is wasteful. Game theory doesn't fix human irrationality, but it provides tools for seeing strategic structure that remains invisible to direct intuition.

The core insight: competitive situations have exploitable patterns. When your outcome depends on others' choices AND they're reasoning about your choices, specific structural regularities emerge. These patterns recur across domains - from geopolitics to product pricing to evolutionary biology - because the underlying strategic logic is identical.

Extraction principle: what survives even when the math fails? The mental operations for mapping strategic interdependencies, identifying stable outcomes, recognizing when first-mover or last-mover advantage applies, spotting situations where individual rationality produces collective disaster. These reasoning moves remain useful even when we can't calculate precise equilibria or when real humans violate rational actor assumptions. We're extracting the conceptual scaffolding, not the computational machinery.

---

## Tier 1: Foundational Strategic Primitives

*These tools reveal the basic structure of strategic interdependence - applicable across almost any competitive situation.*

### Payoff Matrix Construction

**What:** A systematic method for mapping the strategic structure of any interaction by identifying: (1) the players, (2) their available actions, (3) the outcome for each combination of actions, and (4) each player's preferences over outcomes. This creates a complete representation of strategic interdependence.

**Why it matters:** Humans instinctively optimize as if their choices determine outcomes directly. In strategic situations, your outcome depends on both your choice AND others' choices, but we fail to mentally represent this cross-dependency. Payoff matrices force explicit mapping of how others' actions affect your outcomes and vice versa. This reveals hidden structure: dominant strategies, coordination problems, incentive misalignments, and situations where "better for me" doesn't equal "better outcome."

**The key move:** For any competitive or cooperative situation: (1) List all decision-makers whose choices affect outcomes. (2) For each, enumerate their meaningful action options (collapse irrelevant distinctions). (3) Create a grid where rows are one player's actions, columns are another's. (4) In each cell, write the outcome for both players when those actions combine. (5) Check: does changing your action change your outcome differently depending on what they do? If yes, you've captured strategic interdependence.

**Classic application:** The Prisoner's Dilemma reveals why individually rational choices produce collectively terrible outcomes. Two suspects can't communicate. Each can defect (testify) or cooperate (stay silent). If both cooperate: light sentences. If both defect: heavy sentences. If one defects while the other cooperates: the defector goes free while the cooperator gets maximum sentence. Payoff matrix reveals: defecting is individually optimal regardless of what the other does (dominant strategy), yet mutual defection is worse than mutual cooperation. This structure recurs constantly.

**Surprising application:** Coffee shop laptop usage norms. Each customer chooses whether to occupy a seat with just a coffee (low-value use) or give up the seat when crowded. Payoff matrix: If I camp AND others camp, café is unusable for everyone (mutual defection). If I camp but others don't, I get great workspace (exploitation). If I yield but others camp, I can't find seats (being exploited). If all yield when crowded, seats available for high-value work (cooperation). This reveals why social pressure evolved: the uncoordinated equilibrium is everyone camping, making the café worthless to all. Non-obvious because it seems like pure individual choice, but it's strategic interdependence.

**Failure modes:** Over-simplification - real situations often have continuous action spaces or many players, not the clean 2x2 structure. Treating preferences as objective - players may value things differently than you assume (assuming money-maximization when reputation matters more). Static analysis - payoff matrices don't capture learning, reputation, or repeated play where credible threats emerge. Ignoring mixed strategies - sometimes the equilibrium involves randomization, not pure action choices.

**Go deeper:** Dixit & Nalebuff, *The Art of Strategy*, Chapter 2; Osborne & Rubinstein, *A Course in Game Theory*, Chapter 1.2

### Dominant Strategy Identification

**What:** For any player in a strategic interaction, a dominant strategy is an action that produces better outcomes than all alternative actions regardless of what other players choose. If you have a dominant strategy, you should choose it; if your opponent has one, you should expect them to choose it.

**Why it matters:** Strategic analysis can spiral into infinite regress: "If I think he thinks I think..." Dominant strategies cut through this: they're optimal without needing to predict others' choices. Identifying your opponent's dominant strategy tells you what they'll do regardless of your actions, simplifying your own decision. Many important situations (voting, public goods contribution, competitive markets) have dominant strategy structures that explain seemingly irrational behavior.

**The key move:** For each player and each of their possible actions: (1) Hold one of your opponent's actions fixed. (2) Compare your outcomes for each of your actions. (3) Note which of your actions is best. (4) Repeat for every opponent action. (5) If the same action of yours is best in all cases, that's your dominant strategy - choose it without further analysis. (6) Repeat this process from your opponent's perspective to predict their choice.

**Classic application:** Arms races between nations. Each nation chooses "arm" or "disarm." Payoff structure: If opponent disarms and you arm, you gain strategic advantage (best outcome). If both arm, you're secure but waste resources on weapons (mediocre outcome). If both disarm, you save resources but remain secure (good outcome). If you disarm and opponent arms, you're vulnerable (worst outcome). Matrix analysis: "arm" dominates "disarm" - it's better whether opponent arms OR disarms. Both nations arm despite both being better off if both disarmed. The dominant strategy analysis explains why disarmament treaties are hard: even if you believe the other side wants peace, arming is still your best choice.

**Surprising application:** Email inbox management strategies. Each person choosing between "respond quickly to all messages" versus "batch process during designated times." If you respond quickly: you're available when others need you (relationship benefit) but suffer constant interruption (productivity cost). If you batch: you protect focus time but may miss urgent issues. The strategic interdependence: if most people respond quickly, batching makes you seem unresponsive (coordination pressure). If most batch, quick response gives you an edge but wastes your responsiveness on others who won't reciprocate. Many people discover that "respond quickly" weakly dominates in competitive environments - better whether others batch or respond quickly - even though everyone would be more productive if all batched. Non-obvious because it seems like pure personal productivity choice.

**Failure modes:** Assuming dominance without checking all alternatives - need to verify the strategy is best against every opponent action, not just most. Confusing "usually better" with "always better" - near-dominant strategies that fail in edge cases. Ignoring mixed strategies - sometimes no pure dominant strategy exists but a randomized strategy dominates. Not checking opponent's payoffs - you might have a dominant strategy but if they do too, you end up in mutual defection. Applying to cooperative games - dominant strategy logic assumes players can't make binding commitments.

**Go deeper:** Hardin, "The Tragedy of the Commons," *Science* 162(3859), 1968; Axelrod, *The Evolution of Cooperation*, Chapter 1

### Nash Equilibrium Identification

**What:** A Nash equilibrium is a combination of strategies (one for each player) where no player can improve their outcome by unilaterally changing their strategy. It represents a stable outcome: if you're at Nash equilibrium, no one has an incentive to deviate given what others are doing.

**Why it matters:** Not all games have dominant strategies, but strategic interactions still settle into predictable patterns. Nash equilibrium explains where interactions stabilize even without coordination or enforcement. It identifies self-reinforcing outcomes: situations where everyone's choice is the best response to everyone else's choice. This tool reveals why certain bad outcomes persist (stable equilibria), why certain good outcomes are reachable (equilibrium), and why some desirable states are unstable (not equilibrium). It also shows that multiple equilibria can coexist, explaining coordination problems.

**The key move:** Given a payoff structure: (1) For each possible combination of actions (each cell in a payoff matrix), check each player's incentive to deviate. (2) Hold other players' actions fixed. (3) Ask: could this player improve their outcome by switching to a different action? (4) If yes, this isn't an equilibrium. (5) If no player can improve by deviating, you've found a Nash equilibrium. (6) Check all possible combinations - there may be multiple equilibria. (7) If players are at an equilibrium, predict they'll stay there; if not at equilibrium, predict movement toward one.

**Classic application:** Traffic route choice. Many drivers choosing between two routes to the same destination. As more drivers choose route A, congestion increases, making route A slower. Nash equilibrium: drivers distribute themselves between routes until travel times equalize. If route A is faster, drivers switch from B to A until congestion makes them equal. No driver can improve their commute time by switching routes - that's the equilibrium condition. This explains why adding roads can paradoxically increase congestion (Braess's paradox): the new equilibrium may be worse for everyone than the old one.

**Surprising application:** Social media posting frequency. Each person chooses how often to post. If you post more frequently while others post rarely, you capture attention (high payoff). If everyone posts constantly, each post gets less attention due to feed saturation (low payoff). Nash equilibrium: posting frequency where no one benefits from posting more (would get lost in noise) or less (would lose visibility). This explains the "posting arms race" on platforms: the equilibrium posting frequency rises over time as more users join, making everyone post more frequently while each post gets less engagement. Non-obvious because it feels like individual choice about self-expression, but it's actually a strategic equilibrium driven by attention competition.

**Failure modes:** Multiple equilibria without selection mechanism - Nash equilibrium tells you where things can stabilize, not which equilibrium will be reached. Ignoring mixed strategy equilibria - sometimes the equilibrium involves randomization (like penalty kicks in soccer), not pure strategies. Assuming players can calculate equilibria - real humans often can't find equilibria in complex games. Treating equilibrium as normative - Nash equilibrium describes stability, not optimality; many equilibria are terrible for everyone. Not checking for strict versus weak equilibria - in weak equilibria, players are indifferent to deviating, so stability is questionable.

**Go deeper:** Osborne & Rubinstein, *A Course in Game Theory*, Chapter 2; Dixit & Skeath, *Games of Strategy*, Chapter 4

### Best Response Mapping

**What:** For any action your opponent might take, your best response is the action that maximizes your payoff given that opponent action. Best response mapping means systematically identifying your optimal action for each possible opponent choice, revealing how your strategy should adapt to theirs.

**Why it matters:** Strategic thinking isn't about finding one "best" action - it's about conditional planning. Your optimal choice depends on what you expect others to do. Best response mapping forces explicit conditional reasoning: "if they do X, I should do Y; if they do Z, I should do W." This reveals strategic complements (doing more when they do more), strategic substitutes (doing less when they do more), and situations where your best response doesn't vary (dominant strategies). It's also the foundation for finding equilibria: equilibrium is where everyone is playing best responses simultaneously.

**The key move:** For each possible action your opponent might choose: (1) Assume they've chosen it. (2) Compare your payoffs across all your available actions under that assumption. (3) Identify which of your actions gives the best outcome. (4) Record this as your best response to that opponent action. (5) Repeat for every opponent action. (6) Map the relationship: does your best response increase when their action increases (complements), decrease (substitutes), or stay constant (dominance)? (7) Do the same from their perspective to predict their best responses to your actions.

**Classic application:** Price competition between duopolists (Bertrand model). Each firm chooses a price. Best response: if competitor prices high, you price slightly lower to capture all customers. If competitor prices low, you either match (split market) or price even lower (capture market but reduce margin). Best response function: your optimal price decreases as competitor's price decreases. This reveals why price competition drives prices toward marginal cost - each firm's best response to any above-cost price is to undercut, creating a race to the bottom until neither can profitably undercut further.

**Surprising application:** Workout intensity at the gym. If you're exercising near others, each person chooses their intensity level. If others are working hard, your best response might be to work harder (motivational complement - you push yourself to match) or to slack off (substitutional - their intensity makes your relative effort seem okay). Which relationship dominates varies by person and context. This explains why some people thrive in group fitness classes (complements) while others perform better alone (substitutes), and why competitive environments can either elevate everyone's performance or create free-riding. Non-obvious because it reveals exercise intensity as strategic interaction, not pure individual willpower.

**Failure modes:** Assuming continuity - best responses can jump discontinuously at thresholds. Ignoring capacity constraints - your best response might require resources you don't have. Not checking for dominant responses - if your best response doesn't vary across opponent actions, you've found a dominant strategy. Confusing best response with equilibrium - knowing your best response to each opponent action doesn't tell you which opponent action to expect. Over-applying in non-competitive contexts - best response logic assumes you're optimizing against others, not cooperating with them.

**Go deeper:** Varian, *Intermediate Microeconomics*, Chapter 27; Gibbons, *Game Theory for Applied Economists*, Chapter 1.2.A

---

## Tier 2: Strategic Structure Recognition

*These tools identify types of games with characteristic strategic patterns - applicable when you need to diagnose what kind of interaction you're in.*

### Coordination vs. Anti-Coordination Distinction

**What:** Coordination games are situations where players benefit from matching strategies (both choosing the same action), while anti-coordination games are situations where players benefit from choosing different strategies. This distinction determines whether alignment or differentiation drives the strategic interaction.

**Why it matters:** Both types involve strategic interdependence, but they require opposite reasoning. In coordination games, the challenge is selecting which mutually beneficial equilibrium (driving on left vs. right side of road). In anti-coordination games, the challenge is achieving differentiation without communication (who goes first at a stop sign). Misidentifying which type you're in leads to wrong strategies: trying to differentiate when you should match, or trying to match when you should differentiate. Many real-world failures stem from treating coordination problems as competition or vice versa.

**The key move:** For any strategic situation: (1) Identify what happens when both players choose the same action - do they both benefit (coordination) or does this create conflict (anti-coordination)? (2) Check what happens when players choose different actions - does this create problems (coordination) or mutual benefit (anti-coordination)? (3) Look for diagonal payoffs: in coordination games, high payoffs are on the diagonal (matching strategies); in anti-coordination games, high payoffs are off-diagonal (different strategies). (4) Once identified, apply appropriate solution concept: coordination games need focal points or communication; anti-coordination games need randomization or turn-taking.

**Classic application:** Technology standard adoption (VHS vs. Betamax, Blu-ray vs. HD-DVD). Each company choosing which standard to develop. Payoffs: if both develop the same standard, it becomes dominant and both profit from compatibility (coordination benefit). If each develops different standards, market fragmentizes and both suffer reduced network effects (coordination failure). This is pure coordination - matching is good, mismatching is bad. The challenge isn't incentive alignment (both want to coordinate) but equilibrium selection (which standard). First-mover advantage and installed base become decisive.

**Surprising application:** Couple deciding on weekend plans. Each person proposes an activity. Payoffs: both enjoy spending time together regardless of activity (weak coordination preference), but each prefers their suggested activity and loses face if they always defer to the other (anti-coordination element on who decides). This mixed structure explains relationship friction: it's partially a coordination game (being together matters most) and partially anti-coordination (maintaining agency matters). Pure coordination logic says "just pick something," but ignoring the anti-coordination component (whose preference prevails) creates resentment. Non-obvious because it looks like preference disagreement but it's actually about decision-making power distribution.

**Failure modes:** Missing mixed games - many situations combine coordination and anti-coordination elements. Treating all cooperation as coordination - cooperation can also occur in anti-coordination games through turn-taking. Ignoring payoff asymmetries - players might not value coordination equally. Assuming focal points are obvious - what seems like a natural focal point to you may not be to others. Not recognizing sequential play advantages - in anti-coordination games, moving first or second can be decisive.

**Go deeper:** Schelling, *The Strategy of Conflict*, Chapter 3; Skyrms, *The Stag Hunt and the Evolution of Social Structure*, Chapter 1

### Zero-Sum vs. Positive-Sum Recognition

**What:** Zero-sum games are situations where one player's gain exactly equals the other's loss - the total payoff is constant regardless of actions chosen. Positive-sum games allow for mutual gains or mutual losses - the total payoff varies with the actions chosen. Variable-sum games include both positive and negative possibilities.

**Why it matters:** This distinction fundamentally changes strategic reasoning. In zero-sum games, your opponent's optimal strategy is your worst-case scenario - perfect opposition of interests. No cooperation is possible; what helps them hurts you. In positive-sum games, cooperative strategies may exist where both benefit, but so do exploitative strategies. Misidentifying the sum structure leads to tragic errors: treating positive-sum situations as zero-sum destroys mutual gain opportunities (false competition), while treating zero-sum situations as positive-sum enables exploitation (false cooperation).

**The key move:** For any strategic situation: (1) Choose one cell in the payoff matrix (one combination of actions). (2) Add up the total payoffs to all players. (3) Choose a different cell and add up those payoffs. (4) If the totals are always equal regardless of actions chosen, it's zero-sum. (5) If some action combinations produce higher totals than others, it's positive/variable-sum. (6) In zero-sum games, expect pure competition; in positive-sum games, look for cooperative opportunities that increase the total before dividing it. (7) Check whether changing your strategy can increase or decrease the total payoff - if yes, not zero-sum.

**Classic application:** Poker (with fixed pot, excluding house rake) is zero-sum: money won by winners exactly equals money lost by losers. Your optimal strategy is purely adversarial - making your opponents worse off is identical to making yourself better off. This explains why poker strategy focuses on deception and exploitation: there are no mutual gains, only redistribution. Every chip your opponent wins comes from you.

**Surprising application:** Academic citation networks. Each researcher chooses which papers to cite. Naive view: citations are zero-sum (limited attention, citing others takes space from self-citation). Reality: positive-sum with strong network effects. When you cite high-quality related work, it (1) positions your work within established literature, increasing credibility, (2) encourages reciprocal citation, and (3) builds research communities that elevate everyone's visibility. Total citation impact grows for all participants. Treating it as zero-sum (hiding related work, over-emphasizing novelty) actually reduces your citations by isolating your work. Non-obvious because citations feel like a fixed resource, but the network effects create value.

**Failure modes:** Assuming competition implies zero-sum - most competitive situations are variable-sum (you can both do poorly). Ignoring distribution after value creation - positive-sum in creation doesn't mean equal distribution. Missing negative-sum games - mutual destruction is possible (war, price wars). Treating negotiation as zero-sum - most negotiations have integrative potential even when they feel adversarial. Not recognizing that sum can change with repetition - one-shot zero-sum games can become positive-sum when repeated with reputation effects.

**Go deeper:** Von Neumann & Morgenstern, *Theory of Games and Economic Behavior*, Chapter 3; Axelrod, *The Evolution of Cooperation*, Chapter 6

### Sequential vs. Simultaneous Move Recognition

**What:** In simultaneous move games, players choose actions without knowing others' choices (decisions made in ignorance of opponents). In sequential games, players observe previous choices before making their own (decisions made with information about opponent actions). The timing structure determines whether backward induction or equilibrium analysis applies.

**Why it matters:** The same payoff structure produces completely different outcomes depending on move timing. Sequential play enables commitment (first-mover locks in a strategy that constrains others), incredible threats become incredible (you can observe whether threats will actually be executed), and backward induction allows solving by working backward from end states. Simultaneous play requires predicting opponent actions without observation, making commitment impossible and requiring equilibrium thinking. Misidentifying timing structure leads to wrong predictions and wrong strategies.

**The key move:** For any strategic interaction: (1) Ask: when you choose your action, do you know what action(s) the other player(s) have chosen? (2) If yes to any, it's sequential (at least partially). (3) If no to all, it's simultaneous. (4) For sequential games, map the decision tree showing who moves when. (5) Apply backward induction: start from the final decision nodes, determine optimal choices, work backward to find the optimal strategy at each stage. (6) For simultaneous games, use equilibrium analysis: find action combinations where no one wants to deviate. (7) Check whether converting between simultaneous and sequential changes the outcome - if yes, timing structure is strategically important.

**Classic application:** Entry deterrence in markets. Incumbent firm chooses capacity expansion before entrant decides whether to enter. If simultaneous: both firms would choose actions based on predicted responses, likely resulting in entry. If sequential (reality): incumbent expands capacity first, raising entrant's expected losses from entry. Entrant observes expansion and chooses not to enter. The key: expansion is a credible commitment (already built, sunk cost) that changes the entrant's optimization problem. Incumbent's first-mover advantage makes entry deterrence possible.

**Surprising application:** Conflict resolution in relationships. Simultaneous structure: both partners simultaneously decide whether to escalate or de-escalate during an argument. Each fears that de-escalating while the other escalates means losing face, so both escalate (defection equilibrium). Sequential structure: one person explicitly de-escalates first, creating observable commitment. The other can then respond to observed de-escalation rather than predicted behavior. This explains why "I'll go first" statements work - they convert simultaneous (unstable, both escalate) to sequential (stable, both de-escalate) by introducing observation and commitment. Non-obvious because conversations feel simultaneous but sequential framing enables coordination.

**Failure modes:** Ignoring information structure - just because moves happen at different times doesn't mean it's sequential (if later mover doesn't observe earlier move, it's effectively simultaneous). Assuming commitment is automatic - sequential advantage requires credible commitment (sunk costs, binding contracts). Backward induction with irrational players - assumes perfect rationality at every stage. Missing simultaneous components in sequential games - many games have both elements. Not checking for subgame perfection - equilibria in sequential games must be optimal at every decision node, not just overall.

**Go deeper:** Dixit & Nalebuff, *The Art of Strategy*, Chapter 3; Gibbons, *Game Theory for Applied Economists*, Chapter 2.1

### Complete vs. Incomplete Information Distinction

**What:** Complete information games are situations where all players know the payoff structure - everyone knows everyone's preferences over outcomes. Incomplete information games involve uncertainty about payoffs - players don't know others' valuations, costs, or preferences. This distinction determines whether signaling, screening, and belief-updating become strategically relevant.

**Why it matters:** When information is complete, strategic analysis focuses on equilibrium given known payoffs. When incomplete, a new dimension emerges: players use actions to signal their private information (signaling) or design mechanisms to elicit it (screening), and they update beliefs about opponents based on observed actions. Many real-world strategic failures stem from assuming complete information when uncertainty exists (leading to adverse selection, signaling failures) or over-complicating complete information situations by modeling unnecessary uncertainty.

**The key move:** For any strategic situation: (1) Ask: do all players know each other's payoffs/preferences/costs? (2) If yes, it's complete information - focus on equilibrium analysis with known payoffs. (3) If no, identify what's unknown: preferences, costs, capabilities, alternatives? (4) Model as incomplete information game where actions reveal information. (5) Check whether players have incentives to misrepresent (separate signaling equilibria from pooling equilibria). (6) Look for screening mechanisms that elicit private information. (7) Apply Bayes' rule: update beliefs about opponent types based on their observed actions.

**Classic application:** Job market signaling (Spence model). Employers have incomplete information about worker productivity. Workers know their own ability but can't directly communicate it (cheap talk isn't credible). Costly signal: education. High-ability workers can acquire education more easily (lower cost) than low-ability workers. Employers observe education and infer productivity. Separating equilibrium: high-ability workers get education, low-ability workers don't, because the cost-benefit ratio differs by type. Education's value is in signaling ability, not necessarily increasing it - this explains why firms value degrees even when job doesn't use specific knowledge.

**Surprising application:** Restaurant pricing and quality uncertainty. Customers have incomplete information about food quality before ordering. Restaurants know their own quality. Signaling mechanism: high prices. High-quality restaurants can sustain high prices (repeat customers, word-of-mouth) while low-quality restaurants can't (customers don't return). Price becomes a quality signal in equilibrium - expensive restaurants are more likely to be good because low-quality restaurants can't profitably mimic the price. This explains why artificially lowering prices can backfire (sends low-quality signal) and why new restaurants often price high initially (establishing quality signal). Non-obvious because we think of price as cost-based, but it's also an information-revelation mechanism.

**Failure modes:** Assuming incomplete information when it's actually complete - over-complicating situations where preferences are known. Not identifying the private information dimension - what specifically is unknown? Ignoring pooling equilibria - sometimes all types choose the same action, so no information is revealed. Treating signals as costless - effective signals must be differentially costly across types. Missing adverse selection - when one side has private information, the informed side's participation decision reveals information about the distribution of types.

**Go deeper:** Spence, "Job Market Signaling," *Quarterly Journal of Economics* 87(3), 1973; Gibbons, *Game Theory for Applied Economists*, Chapter 3

---

## Tier 3: Dynamic and Evolutionary Tools

*These tools reason about how strategic interactions evolve over time and through repetition.*

### Backward Induction

**What:** A reasoning method for sequential games where you solve for optimal strategies by starting at the end (final decision nodes) and working backward to the beginning. At each stage, you assume optimal play in all subsequent stages and determine what's best given that assumption.

**Why it matters:** In sequential games, naive analysis focuses on immediate payoffs, ignoring how current choices constrain future options. Backward induction forces consideration of the full game tree: your current best move depends on what optimal play looks like after every possible action you might take. This reveals counter-intuitive strategies (sacrificing immediate gain for better position), exposes incredible threats (threats you wouldn't actually execute when the time comes), and enables optimal planning in multi-stage situations. Without backward induction, sequential reasoning devolves into myopic optimization.

**The key move:** (1) Map the sequential game as a decision tree with decision nodes (who chooses) and terminal nodes (outcomes). (2) Start at the terminal nodes (end states) and note the payoffs. (3) Move to the last decision nodes - the final choices before outcomes. (4) For each player at these nodes, identify which action maximizes their payoff given the terminal payoffs. (5) Replace those decision nodes with the payoff resulting from optimal choice. (6) Move backward to the second-to-last decision nodes, repeat the optimization assuming optimal play afterward. (7) Continue backward until reaching the initial node. (8) The backward induction solution is the path of optimal choices from start to finish.

**Classic application:** Centipede game. Two players alternate choosing "continue" or "stop." Pool of money grows each round. When you stop, you take slightly more than half, leaving the rest to the other player. Backward induction: at the final decision node, the last mover takes the full pot (stopping is optimal). Knowing this, the second-to-last mover should stop (since continuing gives the last mover the opportunity to take everything). Working backward, this logic unravels to the first decision: the first mover should stop immediately. Prediction: immediate stopping. Reality: humans often cooperate for several rounds, suggesting limits of pure backward induction with real players.

**Surprising application:** Negotiation deadlines and timing. Two parties negotiating over a deal with a known deadline. Backward induction: work backward from the deadline. At the deadline moment, whoever needs the deal more has zero leverage (their alternative is no deal). Knowing this, the other party can extract maximum concession at the deadline. Knowing this, concessions should happen earlier to preserve some leverage. But working further backward, this logic suggests concessions should happen immediately. This explains why many negotiations have "deadline rush" - both parties avoid early concession (preserving leverage) but know that waiting until the deadline means capitulation. Non-obvious because it reveals how known endpoints propagate backward to affect early-stage behavior.

**Failure modes:** Assuming perfect rationality throughout - backward induction requires all players to be perfectly rational at every stage, which humans aren't. Ignoring incredible threats - backward induction reveals that many threats won't be executed when the time comes, but humans sometimes irrationally follow through. Missing subgame imperfection - some equilibria involve non-credible strategies that backward induction eliminates. Not checking for multiple equilibria - some sequential games have multiple backward induction solutions. Applying to simultaneous games - backward induction requires sequential structure with observation.

**Go deeper:** Osborne & Rubinstein, *A Course in Game Theory*, Chapter 6; Dixit & Skeath, *Games of Strategy*, Chapter 3

### Repeated Game Recognition and Grim Trigger Analysis

**What:** Repeated games are strategic interactions played multiple times between the same players, where past actions are observable and future interactions matter. Grim trigger strategies are commitment rules: cooperate until opponent defects, then defect forever after. These strategies can sustain cooperation in repeated settings even when one-shot analysis predicts defection.

**Why it matters:** One-shot game analysis often predicts non-cooperation (Prisoner's Dilemma defection, public goods free-riding), yet we observe extensive cooperation in reality. Repetition fundamentally changes incentives: the threat of future punishment can deter present defection. Grim trigger analysis shows how cooperation can be an equilibrium: the short-term gain from defection is outweighed by the long-term loss from permanent punishment. This explains how cooperation emerges without central enforcement: reputational incentives in ongoing relationships create self-enforcing agreements.

**The key move:** (1) Check if the interaction repeats: same players, observable actions, future matters. (2) Calculate the one-shot payoffs: what do players gain from mutual cooperation (C,C), mutual defection (D,D), and exploitation (D,C)? (3) Apply grim trigger logic: "I cooperate until you defect; after any defection, I defect forever." (4) Calculate defection temptation: immediate gain from defecting while opponent cooperates. (5) Calculate punishment cost: loss from eternal mutual defection versus cooperation. (6) Check if future matters enough: if (present value of future cooperation losses) > (immediate defection gain), cooperation is sustainable. (7) This requires discount factor (how much you value future payoffs) to be sufficiently high.

**Classic application:** Maintaining cooperation in repeated Prisoner's Dilemma. One-shot: both defect (dominant strategy). Repeated: grim trigger makes cooperation an equilibrium if players value future enough. Cooperate yields payoff R per round forever (total = R/(1-δ) where δ = discount factor). Defect once yields temptation payoff T, then punishment D forever (total = T + δD/(1-δ)). Cooperation is sustainable when R/(1-δ) > T + δD/(1-δ), which simplifies to δ > (T-R)/(T-D). This inequality shows when repetition enables cooperation: must value future sufficiently and punishment must be costly enough.

**Surprising application:** Open-source software contribution. One-shot analysis: free-riding dominates (why contribute when you can use others' code?). Repeated game reality: developers interact repeatedly on platforms like GitHub. Grim trigger equivalent: community members cooperate (contribute code, review, answer questions) with those who've cooperated, but stop helping free-riders (ignore their issues, don't review their PRs). This sustains contribution equilibrium: the immediate cost of contributing is outweighed by long-term benefit of community support. Developers with long-term presence contribute more because they value future cooperation (high discount factor). Non-obvious because there's no formal contract, but reputational repeated game structure creates self-enforcement.

**Failure modes:** Assuming infinite repetition - cooperation requires sufficiently long horizon, but most real interactions have uncertain endpoints. Ignoring noise and mistakes - in real settings, you might defect accidentally, triggering permanent punishment. Missing renegotiation - "grim forever" isn't credible when players can restart cooperation. Not checking for discount factor - cooperation requires valuing future enough; short-sighted players still defect. Treating all punishment as grim - many effective strategies use limited punishment (tit-for-tat) rather than permanent defection.

**Go deeper:** Axelrod, *The Evolution of Cooperation*, Chapter 2; Fudenberg & Maskin, "The Folk Theorem in Repeated Games with Discounting," *Econometrica* 54(3), 1986

### Evolutionary Stability Checking

**What:** An evolutionarily stable strategy (ESS) is a strategy that, if adopted by a population, cannot be invaded by a mutant strategy. When a strategy is evolutionarily stable, small deviations get selected against, returning the population to the original strategy. This concept originated in biology but applies wherever strategies compete through differential success.

**Why it matters:** Nash equilibrium identifies stable outcomes in games between rational players, but it doesn't explain which equilibrium will be selected or whether equilibria are stable against invasion. Evolutionary stability adds a dynamic selection criterion: strategies that reproduce more successfully spread through populations. This explains which equilibria we should expect to see in the long run and which cooperative arrangements resist free-rider invasion. It's particularly powerful for analyzing situations where "rationality" is implausible but selection pressure exists (animal behavior, cultural evolution, market competition).

**The key move:** (1) Identify a candidate strategy S used by most of the population. (2) Introduce a small proportion of mutants using alternative strategy M. (3) Calculate payoffs: S vs. S (population members playing each other), S vs. M (population vs. mutants), and M vs. M (mutants playing each other). (4) Check ESS condition: either (a) S vs. S gives higher payoff than M vs. S (S is better against itself than M is against S), or (b) if payoffs are equal, then S vs. M must exceed M vs. M (S does better against mutants than mutants do against each other). (5) If both conditions fail, S is invadable - mutant strategy can spread. (6) If ESS condition holds, small proportions of M will be selected against.

**Classic application:** Hawk-Dove game in animal conflict. Animals compete for resources. Hawk strategy: escalate, fight if opposed. Dove strategy: display, flee if opponent escalates. Payoffs: Hawk vs. Dove (Hawk wins), Dove vs. Dove (split resource peacefully), Hawk vs. Hawk (both injured, net negative). Is "always Hawk" evolutionarily stable? No - in a Hawk population, being Dove avoids costly fights when meeting Hawks. Is "always Dove" stable? No - in a Dove population, a single Hawk takes all resources. ESS: mixed strategy (probabilistic Hawk/Dove) or conditional strategy (Hawk if opponent is Dove, Dove if opponent is Hawk). This explains observed behavioral polymorphism in nature.

**Surprising application:** Workplace norm persistence. Consider "work-life balance culture" versus "overwork culture" in organizations. If most employees work reasonable hours (balance strategy), is this invadable? A few workaholics (overwork mutants) might gain visibility/promotions (overwork vs. balance favors overwork). But if many switch to overwork, competition intensifies and everyone is worse off (overwork vs. overwork is worse than balance vs. balance). ESS analysis: balance is stable only if rewards don't disproportionately favor overwork, or if overwork becomes self-defeating when common (burnout, errors). This explains why some company cultures sustain healthy norms while others spiral into overwork equilibria - depends on the payoff structure and whether the culture has ESS properties. Non-obvious because it treats culture as evolved strategy rather than chosen policy.

**Failure modes:** Assuming single ESS - many games have multiple evolutionarily stable strategies or none. Ignoring frequency-dependence - ESS analysis assumes payoffs depend on strategy frequencies, but this isn't always modeled correctly. Not checking for neutral stability - sometimes mutants neither grow nor shrink (drift). Applying to non-replicating populations - ESS requires differential reproduction/success, doesn't apply when strategies don't spread. Missing environmental changes - ESS is relative to fixed payoff structure, but real environments shift.

**Go deeper:** Maynard Smith, *Evolution and the Theory of Games*, Chapter 1; Weibull, *Evolutionary Game Theory*, Chapter 2

### Subgame Perfect Equilibrium Identification

**What:** In sequential games, a subgame perfect equilibrium (SPE) is a strategy profile that constitutes a Nash equilibrium in every subgame - every decision node and all subsequent play. It's a refinement of Nash equilibrium that eliminates non-credible threats: strategies that involve actions you wouldn't actually take when the time comes.

**Why it matters:** Standard Nash equilibrium in sequential games can include incredible threats - commitments to actions that aren't optimal when you'd actually have to execute them. Opponents who predict your future actions correctly won't be deterred by incredible threats. SPE forces consistency: your strategy must be optimal not just at the start but at every point where you might have to act. This eliminates bluffing equilibria where threats lack commitment, reveals which first-mover advantages are real versus illusory, and identifies credible bargaining positions.

**The key move:** (1) Map the sequential game as a tree with decision nodes and subgames (subtrees starting from each node). (2) Find all Nash equilibria using standard methods. (3) For each Nash equilibrium, check every decision node: if play reaches this node, would the player whose turn it is actually want to take the action specified by the strategy? (4) Check by applying backward induction from that node forward - what's optimal in the subgame starting from here? (5) If the strategy specifies an action that isn't optimal in any subgame, eliminate that Nash equilibrium - it's not subgame perfect. (6) Only strategies that are optimal at every node (including off-equilibrium nodes) are SPE.

**Classic application:** Chain store paradox (Selten). Incumbent chain faces potential entry in 20 cities sequentially. In each city, if entrant enters, incumbent chooses "fight" (price war, both lose money) or "accommodate" (share market, both profit modestly). Entrant chooses "enter" or "stay out." Backward induction: in city 20 (last city), incumbent won't fight (no future cities to deter entry, fighting is costly). Knowing this, entrant enters city 20. But then in city 19, same logic applies - no benefit to fighting in 19 since entry in 20 is inevitable. Unraveling backward, entrant should enter all cities and incumbent should accommodate all. The "fight to build reputation" strategy isn't subgame perfect - when you reach the decision to fight, it's not optimal.

**Surprising application:** Parenting and discipline threats. Parent threatens punishment if child misbehaves. Nash equilibrium could include: "If child misbehaves, parent imposes severe punishment." But when misbehavior actually occurs, is severe punishment optimal for the parent? If punishment is costly to enforce (parent suffers from child's distress, creates relationship damage), the parent won't want to follow through. Child predicts this, making the threat non-credible. SPE analysis: only punishment levels the parent will actually enforce are credible. This explains why consistent moderate consequences work better than threatened severe consequences - moderate punishment is subgame perfect (parent will actually do it), making it credible and therefore deterring. Severe threats aren't SPE and get ignored. Non-obvious because it distinguishes stated strategy from credible strategy.

**Failure modes:** Computational complexity - finding all subgames and checking equilibrium in each can be intractable in complex games. Assuming common knowledge of rationality - SPE requires all players to predict all future optimal play, which requires strong rationality assumptions. Missing trembles and mistakes - perfect equilibrium further refines SPE by considering small probability mistakes. Not identifying all subgames - off-equilibrium nodes still define subgames that must be checked. Applying to simultaneous games - SPE is specifically for sequential games with proper subgames.

**Go deeper:** Selten, "The Chain Store Paradox," *Theory and Decision* 9(2), 1978; Fudenberg & Tirole, *Game Theory*, Chapter 3

---

## Tier 4: Applied Strategic Tools

*These tools guide decision-making and intervention in competitive situations.*

### Commitment Device Design

**What:** A commitment device is a mechanism that constrains your future choices, making certain actions impossible or prohibitively costly. In strategic settings, limiting your own options can improve your outcomes by credibly committing to a strategy that wouldn't be optimal in the moment but changes opponents' expectations and behavior.

**Why it matters:** Many strategic advantages require commitment - convincing opponents you'll take actions that won't be optimal when the time comes. Without commitment, your threats aren't credible (opponent predicts you won't follow through) and your promises aren't believed (opponent predicts you'll renege). Commitment devices solve this by making deviation costly or impossible. This enables first-mover advantages (commit first, force opponent to respond), bargaining power (eliminate your own flexibility to extract concessions), and cooperation enforcement (mutual commitment prevents defection).

**The key move:** (1) Identify an action you want to threaten/promise but that won't be optimal when the moment arrives. (2) Find a mechanism that makes the action automatic, removes your ability to change course, or imposes high costs on deviation. (3) Make the commitment observable to opponents (they must see that you've constrained yourself). (4) Check credibility: would you actually follow through now that you've committed? If yes, the commitment works. (5) Verify that changing your opponent's expectations (based on your commitment) actually improves your outcome. (6) Common commitment devices: contracts with penalties, reputation stakes, delegation to agents with different incentives, burning bridges.

**Classic application:** Cortés burning his ships upon arrival in Mexico. Soldiers faced a choice: fight the Aztecs (risky) or retreat to ships (safe). Without commitment, soldiers would retreat when faced with battle. Burning ships eliminated the retreat option - fight became the only choice. This commitment made soldiers more formidable (no half-hearted fighting), deterred Aztec confidence in Spanish retreat, and actually improved Spanish survival odds by forcing full commitment. The commitment device was costly (eliminated valuable option) but strategically valuable (changed equilibrium).

**Surprising application:** Self-imposed deadlines for creative work. Without deadline, optimal strategy is "wait for inspiration" (low immediate cost, preserves option value). But this leads to procrastination equilibrium - never starting because starting is always suboptimal compared to waiting. Commitment device: public announcement of deadline, accountability partner, contractual delivery date. Makes "wait for inspiration" costly (reputational damage, breach of contract), forcing work to begin even when uninspired. This commitment improves outcomes by changing the game from "work when optimal" (never) to "work or face consequences" (actually produces output). Non-obvious because it makes you worse off in the moment (forced to work when you don't feel like it) but better off in equilibrium (projects actually complete).

**Failure modes:** Over-commitment - eliminating too much flexibility can be disastrous when circumstances change. Making non-credible commitments - if you can secretly undo the commitment, it doesn't work. Commitment without observability - opponents must see your commitment or it doesn't change their behavior. Ignoring opponent counter-commitments - they can also commit, leading to escalation. Not checking if commitment actually improves equilibrium - sometimes constraining yourself just makes you worse off without changing opponent behavior.

**Go deeper:** Schelling, *The Strategy of Conflict*, Chapter 2; Dixit & Nalebuff, *The Art of Strategy*, Chapter 6

### Mixed Strategy Equilibrium Finding

**What:** Mixed strategies involve randomizing over pure actions according to specific probabilities. A mixed strategy equilibrium is a set of randomization probabilities (one for each player) where each player's mixture is optimal given opponents' mixtures - making the opponent indifferent between their pure strategies.

**Why it matters:** Many games have no pure strategy Nash equilibrium - no combination of deterministic actions is stable. Yet players must choose something, and outcomes display statistical regularities. Mixed strategy equilibrium explains these patterns: players randomize in specific proportions that make opponents indifferent, so no pure strategy dominates. This is crucial for situations involving inspection (tax audits, drug testing), competition with unpredictability value (penalty kicks, poker), and hide-and-seek scenarios (patrol routes, ad timing). Without mixed strategy analysis, these situations appear chaotic but are actually structured probabilistically.

**The key move:** (1) Check if pure strategy Nash equilibrium exists - if yes, no need for mixing. (2) If no pure equilibrium, assume players randomize. (3) Let p = probability player 1 chooses action A (versus 1-p for action B). Let q = probability player 2 chooses action C (versus 1-q for action D). (4) For player 1's mixture to be optimal, player 2 must be indifferent between C and D. Calculate: player 2's expected payoff from C equals expected payoff from D, which gives an equation in terms of p. (5) Solve for p. (6) Repeat for player 1: set their expected payoffs from A and B equal, solve for q. (7) The mixed strategy equilibrium is (p, 1-p) for player 1 and (q, 1-q) for player 2.

**Classic application:** Penalty kicks in soccer. Kicker chooses left or right. Goalie chooses which direction to dive. If kicker goes where goalie dives, usually saved. If different directions, usually goal. No pure strategy equilibrium - if kicker always goes left, goalie dives left; but then kicker wants to switch to right. Mixed strategy equilibrium: kicker randomizes with probabilities that make goalie indifferent (expected payoff from diving left = expected payoff from diving right), and vice versa. Empirical studies show professional players approximate these equilibrium probabilities - not through calculation but through learning.

**Surprising application:** Bluffing frequency in poker. You hold weak hands sometimes and must choose: fold (certain small loss) or bluff (risk big loss if called, but win if opponent folds). Pure strategy "never bluff" is exploitable - opponent always folds to your bets, so you win only tiny pots. Pure strategy "always bluff" is exploitable - opponent always calls, you lose big. Mixed strategy equilibrium: bluff with probability that makes opponent indifferent between calling and folding. This depends on pot odds. Math shows optimal bluffing frequency increases with pot size. Explains why good poker players bluff more in big pots - not psychology but equilibrium mixing probability. Non-obvious because bluffing seems like psychological deception but it's actually mathematical randomization.

**Failure modes:** Assuming players consciously randomize - humans often approximate mixed strategies through intuition or learning, not deliberate calculation. Not checking for multiple equilibria - some games have multiple mixed equilibria. Ignoring dominated strategies - must eliminate dominated strategies before calculating mixtures. Treating all randomization as equilibrium - sometimes observed randomness is just noise, not strategic mixing. Over-applying - many situations with apparent randomness don't have strategic structure requiring mixed equilibrium.

**Go deeper:** Gibbons, *Game Theory for Applied Economists*, Chapter 1.3.B; Walker & Wooders, "Minimax Play at Wimbledon," *American Economic Review* 97(5), 2001

### Mechanism Design Inversion

**What:** Mechanism design inverts traditional game theory: instead of analyzing equilibria in a given game, you design the game rules (payoff structure, information flow, action spaces) to achieve desired equilibrium outcomes. You work backward from the outcome you want to the incentive structure that produces it.

**Why it matters:** In many situations, you can't change players' underlying preferences but you can change the strategic environment they face. Mechanism design asks: what rules create a game where self-interested behavior produces socially desirable outcomes? This is crucial for institution design (voting systems, auction formats, organizational incentives), platform design (eBay feedback, Wikipedia editing), and policy (pollution permits, organ donation systems). Without mechanism design thinking, you rely on appealing to altruism or imposing mandates; with it, you align selfish incentives with desired outcomes.

**The key move:** (1) Specify the desired outcome clearly - what behavior or allocation do you want? (2) Identify players' private information and preferences - what do they know/want that you don't? (3) Work backward: what payoff structure would make the desired outcome a Nash equilibrium? (4) Design rules, payment schemes, information revelation mechanisms that create that payoff structure. (5) Check incentive compatibility: is truthfully revealing information/choosing desired action actually optimal for players? (6) Check participation constraints: will players choose to participate in this mechanism? (7) Iterate if constraints aren't satisfied.

**Classic application:** Vickrey second-price auction for selling an item. Goal: allocate item to highest-valuation bidder, elicit true valuations. Mechanism: sealed bids, highest bidder wins but pays second-highest bid (not their own bid). Why this works: bidding your true valuation is a dominant strategy. If you bid higher than your value and win, you might pay more than it's worth. If you bid lower and lose, you might miss out on profitable purchase. Bidding truth is optimal regardless of others' bids. This mechanism elicits truthful information and allocates efficiently.

**Surprising application:** Wikipedia edit wars and protection levels. Goal: allow good-faith editors to improve articles while preventing vandalism. Mechanism design: different protection levels create different games. Unprotected: anyone can edit (equilibrium: vandalism dominates on controversial topics). Semi-protected: only established accounts can edit (equilibrium: vandals must build reputation first, making vandalism costly). Full protection: only admins edit (equilibrium: no vandalism but also slow improvement). Wikipedia's mechanism: dynamically adjust protection based on edit war detection, creating a multi-level game where vandalism is unprofitable (cost of building reputation exceeds benefit) but legitimate editing remains accessible. Non-obvious because it's not about appealing to altruism - it's about designing a game where vandalism doesn't pay.

**Failure modes:** Ignoring participation constraints - mechanism only works if players opt in. Not accounting for collusion - players might coordinate to exploit mechanism. Assuming players understand the mechanism - complexity can prevent optimal play. Missing unintended equilibria - mechanism might have other equilibria besides the intended one. Infinite regress - if players can redesign the mechanism, your design game becomes nested. Not testing incentive compatibility rigorously - subtle ways to profit from misrepresentation may exist.

**Go deeper:** Hurwicz, "The Design of Mechanisms for Resource Allocation," *American Economic Review* 63(2), 1973; Roth, "The Economist as Engineer," *Econometrica* 70(4), 2002

---

## Quick Reference

### Decision Type -> Tool Mapping

| When you need to... | Use these tools |
|---------------------|-----------------|
| Map strategic interdependence in competitive situations | Payoff Matrix Construction, Best Response Mapping |
| Identify stable outcomes where no one wants to deviate | Nash Equilibrium Identification, Dominant Strategy Identification |
| Determine if cooperation is possible or pure competition applies | Zero-Sum vs. Positive-Sum Recognition, Coordination vs. Anti-Coordination Distinction |
| Solve sequential games with multiple stages | Backward Induction, Subgame Perfect Equilibrium Identification |
| Understand why cooperation persists despite incentives to defect | Repeated Game Recognition, Evolutionary Stability Checking |
| Design incentives to achieve desired outcomes | Mechanism Design Inversion, Commitment Device Design |
| Analyze situations with incomplete information about opponents | Complete vs. Incomplete Information Distinction |
| Recognize when timing of moves matters strategically | Sequential vs. Simultaneous Move Recognition |
| Find equilibria in games without pure strategy solutions | Mixed Strategy Equilibrium Finding |

### Suggested Reading Path

1. **Entry point (accessible, foundational):**
   - Dixit & Nalebuff, *The Art of Strategy* (2008) - Highly readable introduction covering most core concepts with business and everyday examples.
   - Harford, *The Logic of Life* (2008) - Applies game theoretic reasoning to everyday situations, demonstrating transfer beyond economics.

2. **Deepening understanding (more technical/comprehensive):**
   - Gibbons, *Game Theory for Applied Economists* (1992) - Rigorous but approachable treatment of fundamental concepts with economic applications.
   - Dixit, Skeath & Reiley, *Games of Strategy* (4th ed., 2014) - Comprehensive textbook balancing theory with applications across multiple domains.

3. **Advanced/specialized (for serious students):**
   - Osborne & Rubinstein, *A Course in Game Theory* (1994) - Mathematical foundations, proofs, and deep theoretical treatment.
   - Fudenberg & Tirole, *Game Theory* (1991) - Graduate-level comprehensive reference covering advanced topics (repeated games, incomplete information, mechanism design).

4. **Applications and extensions:**
   - Axelrod, *The Evolution of Cooperation* (1984) - Repeated games, evolutionary stability, and emergence of cooperation.
   - Schelling, *The Strategy of Conflict* (1960) - Classic work on commitment, coordination, and tacit bargaining; many concepts originated here.

---

## Usage Notes

### Domain of Applicability

These tools work well in situations with:
- **Clear strategic interdependence**: Your outcome depends on others' choices and vice versa.
- **Identifiable players and actions**: You can specify who decides and what options they have.
- **Consequential choices**: Actions have meaningful payoff differences that motivate careful choice.
- **Some stability**: Repeated interactions or long-enough time horizons for equilibrium thinking to apply.

They work poorly when:
- **True preferences are unknowable**: Not just incomplete information (which game theory handles) but fundamental preference uncertainty.
- **Actions are continuous and high-dimensional**: Game theory can handle these but analysis becomes intractable without computational tools.
- **Radical innovation**: Game theory assumes fixed game structure, but transformative innovation changes the game itself.
- **Players are fundamentally irrational**: Behavioral economics shows systematic deviations from game-theoretic predictions.

### Limitations

What these tools CANNOT do:
- **Predict behavior precisely**: Game theory identifies equilibria but doesn't guarantee players reach them, especially in one-shot games.
- **Handle genuine cooperation**: Game theory models cooperation as sustained by incentives, not intrinsic motivation or solidarity.
- **Resolve fundamental value conflicts**: Game theory takes preferences as given; it doesn't adjudicate whose preferences should prevail.
- **Replace domain expertise**: Strategic structure matters, but so does domain-specific knowledge about payoffs, constraints, and feasible actions.
- **Account for bounded rationality fully**: Real humans satisfice, use heuristics, and can't compute complex equilibria.

### Composition

**Tools that work well together:**
- Payoff Matrix Construction + Best Response Mapping → systematic way to find Nash equilibria
- Backward Induction + Subgame Perfect Equilibrium → solving sequential games credibly
- Repeated Game Recognition + Evolutionary Stability → understanding when cooperation persists
- Commitment Device Design + Sequential Move Recognition → creating first-mover advantages

**Tools that are substitutes:**
- Nash Equilibrium vs. Dominant Strategy (dominant strategy is simpler when it exists)
- Mixed Strategy vs. Pure Strategy equilibrium (different solution concepts for different game structures)
- Backward Induction vs. Nash Equilibrium (sequential games use backward induction instead of simultaneous Nash)

**Common tool sequences:**
1. Map situation → Payoff Matrix Construction
2. Classify game type → Zero-Sum/Positive-Sum, Coordination/Anti-Coordination, Sequential/Simultaneous
3. Apply appropriate solution → Dominant Strategy, Nash Equilibrium, Backward Induction, or Mixed Strategy
4. If repeated → check for Repeated Game structure and Evolutionary Stability
5. If designing system → use Mechanism Design Inversion

### Integration with Other Domains

**Complements to these game theory tools:**
- **Decision theory under uncertainty**: Game theory assumes strategic opponents; decision theory handles non-strategic uncertainty (nature, randomness). Use both when facing mixed strategic and non-strategic uncertainty.
- **Behavioral economics**: Game theory assumes rationality; behavioral economics documents systematic deviations. Combine to predict when game-theoretic reasoning applies and when behavioral patterns dominate.
- **System dynamics**: Game theory is static or comparative static; system dynamics models how equilibria shift over time with changing parameters.
- **Probability and statistics**: Many game theory applications require calculating expected values, updating beliefs (Bayesian updating in incomplete information games).

**Conflicts to watch for:**
- **Optimization vs. equilibrium**: Individual optimization (choose best action) differs from equilibrium analysis (best response to others' best responses). Game theory requires equilibrium thinking, not just personal optimization.
- **Normative vs. positive**: Game theory is descriptive (what equilibria exist) not normative (what should happen). Don't confuse Nash equilibrium with optimal or fair outcomes.
- **Transfer limitations**: Game theory tools transfer across strategic situations, but specific equilibria don't transfer - you must recalculate for new payoff structures.

