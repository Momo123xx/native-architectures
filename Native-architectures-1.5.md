# Three-Architecture Neurodiversity Theory — v1.5

**Conflict of interest — read first**: The theorist is self-identified as scout-dominant AuDHD. The thing being theorized about is the theorist's own neurotype. Confirmation bias risk is accordingly high. This is disclosed in detail in §8, and safeguards are described in the Document Structure section below.

## Changelog

### v1.5 (from v1.4)

- **New theoretical content**: Two new derived mechanism sections added — architecture-native engagement modes (§4.11) and cross-architecture growth trajectories (§4.12). One new prediction added (§5.9). These are extensions of existing mechanisms (emulation fatigue, plasticity, stress-polarization), not revisions of prior claims.
- **PP literature positioning**: New section (§1.2) positions the framework within the existing predictive processing literature, engaging with Friston (2005, 2010) FEP, Pellicano & Burr (2012), Van de Cruys et al. (2014), Lawson, Rees & Friston (2014), emerging ADHD-PP accounts, Sinha et al. (2014) predictive impairment, Constant et al. (2020) HIPPEA-social extension, and Palmer et al. (2017) volatility estimation. New section (§1.1) positions the framework relative to non-PP research programs (Baron-Cohen E-S, Murray et al. monotropism, Hull et al. masking, Markram & Markram Intense World Theory, Chevallier et al. Social Motivation Theory, Barkley executive function, polyvagal theory).
- **Qualitative-not-formal acknowledgment**: Explicit statement that PP terminology is used conceptually and qualitatively, not as a claim of formal mathematical equivalence with existing computational models.
- **Architecture descriptions augmented**: Each architecture now includes a functional characterization alongside the existing PP-grounded technical description, ensuring equal representational depth and dignity across all three profiles.
- **Evolutionary argument scoped out**: The evolutionary mechanism is explicitly decoupled from the core PP framework as a separate development track.
- **"Why three" reframed**: The three-architecture claim is reframed as a first-order approximation identifying dominant attractor basins, not a claim about the complete precision-weighting space.
- **Confirmation bias transparency**: Explicit acknowledgment of motivated reasoning risk added to the document structure section.
- **AuDHD hierarchical precision split**: The AuDHD mechanism (§4.5) is revised to resolve the tension between scout PE salience (consequence of low priors) and systemizer structural priors (high). The resolution: precision policies operate at different hierarchical levels — high within-model (systemizer), low on-model-validity (scout). Hierarchical note added to §2.2.
- **New observational evidence**: Two new Layer 2 entries added — cross-architecture communication parsing (§9.10) and high-prior precision error pattern (§9.11).

### v1.4 (from v1.3)

- **Structural reorganization**: Document split into two explicit layers — theoretical framework (Layer 1) and observational evidence (Layer 2). All claims now traceable to their evidential basis or lack thereof.
- **Epistemic hygiene**: Observational material relabeled as illustrative, not confirmatory. No observational claims removed — all preserved with explicit status markers.
- **Predictions consolidated**: All testable predictions extracted from inline discussion and collected into a dedicated section within the theoretical layer.
- **No theoretical content added or modified**: All framework claims, PP mappings, and mechanism specifications were carried unchanged from v1.3. v1.4 was a reorganization, not a revision.

---

## Document Structure

This document is organized into two separable layers:

**Layer 1 — Theoretical Framework** contains the formal model: definitions, mechanisms, structural claims, and predictions. It is intended to stand alone without reference to any specific individual's experience. Every claim in Layer 1 is either a formal consequence of the Bayesian Predictive Processing mapping or a structural argument about the relationships between components. Where a claim lacks formal grounding, this is flagged.

**Layer 2 — Observational Evidence** contains all case material, self-report data, and illustrative examples. Every item in Layer 2 is explicitly labeled as illustrative (consistent with the model but not confirmatory) or motivating (the observation that generated the claim, subject to post-hoc interpretation bias). Layer 2 depends on Layer 1 for its interpretive frame. Layer 1 does not depend on Layer 2 for its logical structure.

This separation serves a specific purpose: it allows a reader to evaluate the theoretical architecture on its own terms — internal consistency, predictive specificity, falsifiability — before deciding how much weight to assign the observational base. It also makes the theory's current empirical weakness maximally visible rather than dispersed across inline anecdotes.

**Operationalization status**: The framework currently generates predictions that are testable in principle but not yet operationalized for independent empirical testing. The core constructs — architecture identification, precision weighting, emulation quality — lack operational definitions sufficient for a researcher to apply them without the framework's own interpretive lens. This is acknowledged as a high-severity open problem (§6.1).

**Conflict of interest disclosure**: The theorist is self-identified as scout-dominant AuDHD (see §8). This means the theory was developed by someone whose own neurotype is reframed by the framework — the confirmation bias risk is accordingly high. Two safeguards have been applied: first, all three architecture descriptions have been tested against the criterion "would a self-identified member of this architecture read their own description and feel accurately characterized, not merely categorized?" Second, external critique from individuals across all three proposed architectures is actively sought. The theory predicts that critics from different architectures should object to different aspects of the framework — systematic testing of this prediction would itself constitute partial evidence.

---

## Intended Use

This framework is a structural model of cognitive architecture diversity. It is not a personality typology, a diagnostic instrument, or a tool for categorizing individuals. The architectures described are attractor states in a continuous space — not discrete boxes.

The intended function is explanatory, not prescriptive: to provide a mechanistic account of why different cognitive architectures exist, what each contributes, and why the sequential dependency between them (§3.2) produces outcomes that no single architecture can achieve alone.

The framework reframes the traditional deficit model. It does not claim the deficit model is wrong — deficit framing was an honest attempt to account for observable impairment. The claim is that it is incomplete: what presents as deficit is often an architecture-environment mismatch (§5.3) or the accumulated cost of sustained emulation (§4.2), not a failure of the architecture itself. All three architectures carry intrinsic costs (§2.1–2.3) independent of environmental mismatch. No architecture is superior; each is a different optimization with different trade-offs. Connection is a universal human drive across all three — what varies is the channel and cost of connection, not the motivation.

Self-recognition is the entry point, not the endpoint. The framework's applied value lies in identifying one's native architecture, understanding its costs and ceilings, and — where the individual chooses — developing cross-architecture capacity through the mechanisms described in §4.12.

---

# LAYER 1 — THEORETICAL FRAMEWORK

---

## 1. Core Framework: Bayesian Predictive Processing

**Terminological note**: The predictive processing mapping in this document is conceptual and qualitative, not formal or mathematical. PP terminology — precision, prediction error, gain control — is used to generate testable predictions and to unify the three architectures under a common mechanistic language. In the PP literature, "precision" has a specific mathematical definition (the inverse variance of a probability distribution); this document uses it as a qualitative descriptor of gain-control tuning. This is not a claim of formal equivalence with existing computational models such as the Hierarchical Gaussian Filter or active inference simulations. Formalization — specifying the generative model, deriving predictions analytically, running simulations — requires collaboration with computational neuroscience specialists and is identified as a priority for future development (see Appendix B).

The brain operates as a hierarchical prediction engine. It continuously generates top-down predictions about incoming sensory data. When predictions fail, the residual — prediction error (PE) — propagates upward, forcing model revision.

Precision weighting is the gain-control mechanism that determines how much any given prediction error matters: high precision on a PE means "trust this signal, update the model"; low precision means "this is noise, suppress it."

The three architectures are unified under this framework as **three distinct default precision weighting policies** operating on the same underlying predictive processing machinery. Same engine, different tuning.

**Literature engagement note**: This document engages with the research programs listed in §1.1 and §1.2 at the level of their theoretical claims and published positions, not as a comprehensive review of primary sources. The theorist's familiarity with these frameworks is conceptual — sufficient to identify points of agreement, disagreement, and extension, but not equivalent to a systematic literature review. Full primary source review, conducted in collaboration with domain specialists, is identified as a development priority (see Appendix B).

**Dependency note**: The behavioral-level claims (the three architectures, the loop, the sequential dependency, the predictions) were developed independently of PP and would survive a substantial revision of the PP framework. The mechanistic layer (why emulation fatigues, why stress polarizes, why the architectures are discrete) depends on PP. If PP is supplanted, the mechanistic layer requires rebuilding; the structural layer does not.

### 1.1 Related Frameworks Not Grounded in PP

This framework intersects with several research programs beyond the PP literature. Full engagement with each is a development priority; the key differentiations are stated here to locate the boundaries.

**Baron-Cohen (2002, 2009) — Empathizing-Systemizing (E-S) theory.** The "systemizer" label in this framework echoes Baron-Cohen's systemizing construct. The distinction: E-S theory defines systemizing as a cognitive style measured by self-report questionnaire (SQ). This framework defines the systemizer as a precision-weighting architecture — a gain-control configuration, not a behavioral preference. The E-S systemizer is what the person does; the PP systemizer is how the system is tuned. The two may correlate empirically but are defined at different levels of description.

This framework also disagrees with the E-S model's implied inverse relationship between empathizing and systemizing. Baron-Cohen's model associates the autism profile with high systemizing and low empathizing, treating empathizing capacity as inversely related to systemizing drive. This framework proposes a different account: empathy is not absent in the systemizer architecture, it is *costly*. The systemizer processes empathic content through the same high-precision machinery it applies to everything else — modeling another person's internal state is a systemizing task when the systemizer does it. The cost is not inability but emulation overhead: the systemizer must build a model of the other person's precision-weighting policy and run it top-down, which requires the same effortful override described in §4.2. A systemizer who has built that model can be deeply empathic — but the path to empathy runs through system-building, not through the social-channel intuition the socialite uses natively. The E-S model mistakes the higher cost of empathizing in the systemizer architecture for an inability to empathize. The prediction: systemizers who have developed empathic capacity should show high empathizing *and* high systemizing simultaneously — a region the E-S model treats as empty.

**Murray, Lesser & Lawson (2005) — Monotropism theory.** §4.6 recharacterizes monotropism as a universal attentional parameter varying across architectures. The original monotropism theory proposes a monotropic attention style as the central feature of autism. This framework agrees that monotropism is central to the autistic experience but disagrees that it is autism-specific — it proposes monotropism as a precision-budget concentration mechanism expressed differently across all three architectures. The recharacterization extends Murray et al., it does not replace them.

**Hull et al. (2017, 2019) — Autistic camouflaging/masking.** The emulation fatigue mechanism (§4.2) maps directly onto the published camouflaging literature. Hull et al.'s Camouflaging Autistic Traits Questionnaire (CAT-Q) operationalizes masking cost in ways that could empirically test the emulation fatigue predictions. This is the closest existing empirical literature to the document's masking/emulation claims and represents a potential bridge to operationalization.

**Markram & Markram (2010) — Intense World Theory.** The Intense World Theory proposes that autism results from hyper-functional neural circuitry — excessive neuronal processing, hyper-reactivity, and hyper-plasticity — producing a world experienced as overwhelmingly intense. This framework partially agrees: the systemizer's high sensory PE precision and high structural prior precision produce an "un-damped" processing style where incoming data is weighted heavily against rigorous internal models. The behavioral consequences the Intense World Theory describes — social withdrawal (isolating entropic variables to reduce unpredictable input), resistance to change (routine-seeking that calibrates body and mind to a predictable rhythm), and intense focal interests — are consistent with this framework's systemizer profile. However, this framework treats these as downstream effects of the precision-weighting architecture, not as defining features, and proposes they can be overcome through deliberate cross-architecture development (§4.12). The Intense World Theory's claim of "hyper-functional" processing may also conflate architecture with capacity — the intensity of signal processing may interact with cognitive capacity (§7.1) rather than being a fixed property of the architecture itself. Additionally, "un-damped" signal processing is not unique to the systemizer — the scout architecture also processes signals without strong prior dampening, through a different mechanism (low prior precision rather than high dual-channel precision). The Intense World Theory captures one architecture's phenomenology but does not extend to the full triadic space.

**Chevallier et al. (2012) — Social Motivation Theory of Autism.** The Social Motivation Theory proposes that autism involves diminished social motivation — reduced orienting to social stimuli, reduced social reward seeking, and reduced social maintaining. This framework disagrees with the core claim. Social motivation is not diminished in the systemizer or scout architecture — connection is a fundamental human drive across all architectures (see Intended Use). What differs is cost, not desire. The systemizer's high-precision processing makes the socialite-systemizer interface inherently expensive: the socialite's native mode of connection operates through social-channel protocols that the systemizer must emulate at high metabolic cost (§4.2), and the systemizer's native mode — direct, protocol-sparse, content-focused — can be experienced by socialites as socially aversive, creating bidirectional friction (§5.3). The accumulated cost of repeated failed connection across a lifetime produces withdrawal that mimics reduced social motivation but is mechanistically distinct from it. This framework predicts that when the social interface matches the architecture — shared-interest communities, technical subcultures, contexts where socialite-protocol emulation is not required — the connection cost drops and social engagement becomes visible. The Social Motivation Theory mistakes an architecture-interface mismatch for a motivational deficit.

**Barkley (1997) — Executive dysfunction model of ADHD.** The dominant cognitive model of ADHD in clinical psychology frames ADHD as impaired executive function — inhibition, working memory, planning. This framework implicitly disagrees: the scout profile is not an executive function deficit but a native precision-weighting configuration optimized for exploration. The two accounts make different predictions about ADHD under optimal conditions — executive dysfunction predicts persistent impairment across contexts, whereas the architecture model predicts context-dependent performance (high function in novelty-rich environments, low function in structure-demanding ones).

**Porges (1995) — Polyvagal theory.** The socialite's "social channel" and "protocol handshake" parallel the social engagement system described in polyvagal theory. Porges proposes a vagally-mediated system that supports social communication and calms physiological threat responses. The socialite's social-channel anchoring may have polyvagal underpinnings — this is a potential neurophysiological grounding for the socialite architecture that has not been explored. **Note**: Polyvagal theory has faced significant scientific criticism regarding its phylogenetic claims and empirical basis (e.g., Grossman & Taylor, 2007, who challenge the evolutionary assumptions underlying Porges' proposed vagal hierarchy); any connection to the socialite architecture remains speculative.

### 1.2 Positioning Within the PP Literature

This framework takes a specific position within an active and unresolved debate in the PP literature. The field has not converged on a single PP account of autism, let alone ADHD or neurotypicality. This theory does not claim to resolve that debate — it proposes that the debate may be more productively framed by treating precision-weighting profiles as cognitive architectures rather than deficit states, and by extending the framework to all three neurotypes rather than modeling only one against a presumed baseline.

The following positions are stated explicitly to locate this framework relative to existing accounts.

**Friston (2005, 2010) — Free Energy Principle.** The foundational predictive processing framework that this document's mechanistic layer rests on. The free energy principle proposes that biological systems minimize surprise by updating internal models or acting on the environment. This framework takes the FEP's precision-weighting machinery and proposes that stable individual differences in default precision allocation constitute cognitive architectures. The FEP does not itself predict stable individual differences in precision policy — this is an extension, not a derivation.

**a) Pellicano & Burr (2012) — "Hypo-priors" account.** Pellicano and Burr propose that autistic individuals form weaker or flatter priors, such that every encounter carries disproportionate surprise. This framework disagrees. If priors were weak, autistic individuals would not exhibit the rigid world models that produce visible frustration when violated. The observable pattern — incoming input conflicts with a strong internal model, producing a correction response — is evidence for high-confidence priors that resist updating, not for weak priors that fail to form (§9.11 provides an illustrative observation consistent with this claim). A high-prior-precision system encountering a prediction error it cannot suppress produces a qualitatively different response than a low-prior system encountering undifferentiated novelty.

**See also Sinha et al. (2014) — "Autism as a disorder of prediction."** Sinha et al. propose a broader version of the same claim: autism as a global predictive impairment — the system fails to form predictions across domains, producing a world experienced as "magical" where events occur without anticipation. This framework disagrees for the same reason it disagrees with hypo-priors: within domains where the autistic individual has built deep models, prediction is not impaired — it is exceptional. The systemizer who has spent years building a high-confidence model of their domain generates predictions that exceed what a shallow-prior system can produce. Predictive impairment accounts mistake domain-specificity for global inability. The systemizer does not fail to predict; the systemizer predicts deeply within the model and poorly outside it — which is precisely what high prior precision concentrated on specific channels would produce.

**b) Van de Cruys et al. (2014) — HIPPEA (High, Inflexible Precision of Prediction Errors in Autism).** HIPPEA is the closest existing account to this framework's systemizer profile. Both agree on inflexibly high precision on prediction errors in autism. The key difference is framing: HIPPEA treats inflexible precision as a deficit in meta-learning — the system fails to learn when to adjust precision. This framework reframes the same mechanism as a native architecture: a stable precision-weighting policy that is not broken but differently optimized. The inflexibility is the feature that enables deep, sustained model-building at the cost of adaptability. This is the most important distinction to make clear: deficit framing versus architecture framing applied to the same underlying mechanism.

**c) Lawson, Rees & Friston (2014) — Aberrant precision account.** Lawson et al. propose attenuated prior precision relative to sensory precision in autism — a "slavery to the senses." This partially aligns with the triadic model's claim of high sensory PE precision in the systemizer profile. The difference: Lawson et al. frame the imbalance as sensory precision being too high relative to priors. This framework proposes both are high — high sensory PE precision and high structural prior precision — which creates the characteristic tension between rigorous models and sensory flooding. The systemizer is not enslaved to the senses; the systemizer is running two high-gain channels simultaneously, one bottom-up and one top-down, and the tension between them is the defining feature.

**d) Emerging ADHD-PP work.** PP accounts of ADHD are less developed than autism accounts but are emerging. Dopamine is associated with encoding the precision of prediction errors by controlling neural gain, which supports the neurochemical unification claim in §2.2. Recent work on predictive coding and active inference within clinical neuroscience (Smith, Badcock & Friston, 2021) aligns with the scout profile described here. This framework goes further by proposing low prior precision as the defining feature of the scout architecture, not merely impaired gain modulation — the low priors are not a failure to form predictions but a native configuration optimized for exploration.

**e) Neurotypicality as novel contribution.** To the author's knowledge, no existing PP account defines neurotypicality as its own precision-weighting architecture. The literature universally treats NT as the baseline or control condition against which atypical profiles are measured. The proposal that neurotypicality is a social-channel-anchored flexible precision allocation strategy — a specialization in its own right, with its own costs and its own native strengths — is, as far as the author can determine, genuinely novel.

**f) Constant, Bervoets, Hens & Van de Cruys (2020) — HIPPEA extended to social cognition.** Constant et al. extend the HIPPEA framework into the social domain, arguing that social difficulties in autism arise from the same high inflexible PE precision applied to inherently noisy social signals — the system demands predictive precision that social interaction cannot deliver. This framework partially agrees: social interaction is an entropy generator — a signal source whose variance resists the kind of precision-weighting the systemizer applies natively to structured domains. Where this framework diverges: the socialite architecture processes social entropy natively through automatic gain control on the social channel — not by achieving precision on noisy signals, but by running a different kind of processing tuned to that noise. The systemizer's social difficulty is not merely that social signals are noisy, but that the systemizer lacks the native social-channel gain control the socialite runs automatically. The socialite's social processing is instinctive; the systemizer's must be derived from extensive observation and deliberate model-building (§4.2), and even then does not replicate the socialite's native operation.

**g) Palmer, Lawson & Hohwy (2017) — Volatility estimation account.** Palmer et al. propose that autistic individuals overestimate environmental volatility — treating stable contexts as unstable — which drives the characteristic need for sameness as a compensatory strategy. This framework disagrees. The autistic preference for stable environments is not evidence of broken volatility estimation; it is a consequence of the systemizer architecture's model-building requirements. The systemizer's sensors are not malfunctioning — the architecture requires building a sufficiently complete model before the environment becomes navigable. Unstable environments resist model-completion, which is why they are aversive. Stable environments are preferred not because the system incorrectly perceives them as volatile, but because stability permits the deep model-building the architecture requires. The two accounts make different predictions: Palmer et al. predict that genuinely volatile environments should reduce distress (because the volatility estimate now matches reality); this framework predicts genuinely volatile environments increase distress for systemizers (because model-building is continuously disrupted) but may be neutral or positive for scouts (whose low prior precision is natively suited to volatility).

---

## 2. Architecture Definitions

**Heterogeneity caveat**: The mappings below — systemizer to autism, scout to ADHD, socialite to neurotypicality — describe the proposed precision-weighting core of each category. Significant within-category heterogeneity exists and is expected. Not all autistic individuals are systemizer-dominant, and not all individuals with ADHD are scout-dominant. The claim is about the central tendency of the attractor basin, not about every individual within it. Individuals whose presentation does not match the described core may occupy different positions within the basin, sit between basins (see §4.5 on AuDHD), or represent heterogeneity that this first-order model does not yet capture.

### 2.1 Native Systemizer (Autism)

Systemizers build the structures that everyone depends on. Their monotropic focus is not a restriction — it is sustained attention driven by deep engagement with a subject. The healthcare systems, the chip architectures, the legal frameworks, the bridges — these exist because someone cared enough about the details to stay with them. When a systemizer is in their native mode, everything extraneous fades: sensory distraction, social noise, competing demands. What remains is presence with the subject. The cost — rigidity, sensory overwhelm — is intrinsic to the depth. You cannot build a cathedral with shallow attention.

**Precision profile**: High sensory PE precision + high structural prior precision + inflexible reallocation.

The system trusts incoming sensory detail (bottom-up PEs weighted high) and trusts its own built models (structural priors weighted high). This produces the characteristic tension: rigorous models AND sensory flooding. Monotropic expression — deep, narrow, persistent focus — is a consequence: concentrating precision on a single channel manages saturation, and high prior precision on the model being built resists channel-switching.

**Intrinsic cost** (rigidity): High prior precision on structural models means the threshold for PE-driven model revision is very high. The model resists updating because it has assigned high confidence to itself.

**Intrinsic cost** (sensory overwhelm): High sensory PE precision means the system cannot attenuate irrelevant detail.

**Active inference style**: Model-building. When PEs arise, the systemizer resolves them by refining the internal model — deepening structure, increasing precision on the current channel.

### 2.2 Native Scout (ADHD)

Scouts go first into unknown territory. Their drive toward novelty is not a failure to commit — it is an orientation toward what has not yet been found. They discover the new technology, the uncharted idea, the territory nobody else would enter because the map does not exist yet. There is often real loss — passions left behind, projects that were genuinely deep while they lasted. But the scout's deepest function in the loop is to find something worthy enough to hand off: territory worth mapping, signal worth structuring. The exploration has a telos — it feeds the sequential dependency (explore → structure → cohere). The cost — difficulty sustaining commitment, the accumulation of abandoned pursuits — is the price of being the architecture that finds the territory the systemizers will later map and the socialites will later settle.

The "scout" framing is preferred over Hartmann's (1993) "hunter" metaphor because it maps directly onto the PP mechanism: exploration of novel territory under low prior precision, rather than a predator-prey analogy that does not connect to the underlying computational architecture.

**Precision profile**: Low prior precision + rapid reallocation.

Existing models hold loosely. Prediction errors from novel or unexpected input get amplified disproportionately because the system lacks high-confidence priors to suppress them. Novelty is intrinsically salient because the prior is too weak to explain away the PE. High PE salience in the scout is a *consequence* of low prior precision, not a separate tuning parameter — when priors are weak, more prediction errors pass the significance threshold, making the world feel continuously novel. **Hierarchical note**: In the pure scout profile, low prior precision operates globally — across both within-model and meta-model levels of the hierarchy. This distinction becomes load-bearing in the AuDHD case (§4.5), where prior precision splits across hierarchical levels.

**Intrinsic cost** (commitment difficulty): Low prior precision means the system cannot maintain high confidence in its current model long enough to resist the next salient PE. The current engagement is always being outbid by incoming surprise. The same low prior precision that makes the scout brilliant at finding new territory makes it difficult to stay once it has been found.

**Active inference style**: World-updating. When PEs arise, the scout resolves them by moving — seeking new input, changing context, physically exploring. This is why ADHD presents as hyperactivity/impulsivity at the behavioral level.

**Neurochemical unification**: Dopaminergic salience gating is the neurochemical implementation of precision weighting on novelty and reward prediction errors. The scout profile is not a separate mechanism from the systemizer profile — it is the same precision-weighting architecture with different neurochemical tuning. This resolves the asymmetry where the systemizer vertex appeared to be a PP claim and the scout vertex appeared to be a neuropharmacology claim. They are the same framework at different levels of description.

**Neurochemical caveat**: The dopaminergic model is simplified. Norepinephrine, DMN dysregulation, cortical maturation delays, and cerebellar involvement are all part of the ADHD picture and are not yet integrated into this framework.

### 2.3 Native Socialite (NT)

Socialites are the architecture that holds groups together. They feel the fractures in a social structure before anyone else does, and they move to repair them. Their social-channel precision is not a limitation — it is their deepest functional strength. They read the room the way a systemizer reads a schematic: with precision, with care, with stakes. When a group survives a crisis, it is usually because someone held the center — maintained trust, absorbed conflict, kept people connected through the slow daily work that nobody notices until it stops. The cost — protocol dependency, reduced specialist depth — is intrinsic to the breadth. You cannot hold a group together with narrow attention.

**Precision profile**: Social-channel-anchored precision + flexible reallocation across non-social channels.

The system assigns high default precision to the social prediction channel — violations of expected social behavior, breaks in reciprocity, failures of group coordination are weighted more heavily than non-social PEs. The system treats social signals as its most reliable information source. Across all other channels, precision allocation is context-sensitive and flexible — the socialite can shift between prior-dominant and PE-dominant processing depending on situational demands.

**Intrinsic cost** (protocol dependency): Until the social channel is established ("handshake complete"), the system has not assigned precision to the connection. Data arriving without social framing arrives on a channel the system has assigned low precision to. The system literally processes it less — not because the data is invalid but because the connection carrying it is untrusted. This is the precision-gating mechanism made explicit.

**Active inference style**: Social action. When PEs arise, the socialite resolves them by seeking social contact — talking, checking in, reading the room, coordinating.

**Open mechanistic gap**: The nature and limits of the socialite's non-social flexibility are described but not decomposed. How flexible? Fully unconstrained, or secondarily biased? Does flexibility carry costs beyond protocol dependency? The anchor is specified; the flexibility is not.

**Contributor note**: The socialite architecture is the least developed of the three because the theorist is not one. The observational base is limited and filtered through a non-socialite perspective. This is the most important place for socialite contributors to enter the framework — the structural scaffolding exists, but the experiential depth and mechanistic decomposition require a native socialite's voice.

---

## 3. Structural Properties

### 3.1 Structural Asymmetry: Two States and One Strategy

The PP mapping reveals that the three architectures are not structurally identical types of entity:

The **systemizer and scout** profiles are fixed precision configurations — locked gain settings that produce extreme depth in specific channels at the cost of inflexibility.

The **socialite** profile is a flexible precision allocation strategy anchored by one fixed channel (social) — context-sensitive gain control that produces breadth at the cost of specialist depth.

All three share one structural feature: a non-negotiable precision commitment. For the systemizer, this is a high-precision ceiling — structural-prior and sensory-PE channels locked high. For the socialite, it is a high-precision anchor — the social channel is fixed high. For the scout, it is a low-precision floor — prior precision locked low, which makes novelty salient as a consequence (see §2.2), not as a separately assigned high-precision channel. They differ in what they do with the remaining precision budget. Systemizers lock it onto sensory detail. Scouts cannot prevent it from following the next unsuppressed PE. Socialites distribute it flexibly based on context.

The architectures are **functionally symmetric** (each is necessary, each has costs, each is a peer in the loop) but **structurally asymmetric** (two are states in the precision space, one is a strategy over the space). The socialite is not "better" — flexibility is a different optimization, not a superior one. The locked profiles access regions of the precision space that flexibility cannot reach by definition. Depth requires inflexibility.

This asymmetry explains the socialite's population dominance: flexible precision allocation is adaptive across the broadest range of social environments. But breadth without depth is as incomplete as depth without breadth — the loop requires all three.

**Open question**: Whether this asymmetry is a feature (accurately reflecting biological reality) or a problem (suggesting the socialite is a qualitatively different kind of entity) remains unresolved.

### 3.2 The Three-Phase Loop

The three architectures are not merely complementary but sequentially dependent:

**Explore → Structure → Cohere → Explore**

Each architecture's output is the next architecture's required input. Scouts generate signal from unknown territory. Systemizers extract structure from that signal. Socialites cohere groups around established structure. The cycle restarts when established structure encounters novel territory.

The loop is **dual-function**:

1. **Generative**: Each phase produces the input required by the next phase.
2. **Error-corrective**: Each architecture's native precision profile detects the specific precision pathology the other architectures are vulnerable to.

Error-correction mechanism: Each architecture's excess is a specific precision imbalance; each other architecture's native profile is optimally positioned to detect precisely that imbalance.

- Scout excess (too many unsuppressed PEs): Systemizer detects absence of structure. Socialite detects group fragmentation.
- Socialite excess (social precision drowning out non-social PEs): Scout detects ignored novel threats. Systemizer detects model-reality mismatch.
- Systemizer excess (prior precision so high PEs can't force revision): Scout detects environmental change being ignored. Socialite detects human cost of dead models.

### 3.3 The "Why Three" Problem

The three-architecture claim is presented as a first-order approximation: a hypothesis about the dominant attractor states in the precision-weighting space, not a claim about the complete space. Finer-grained architectures, subtypes, gradients (such as AuDHD, §4.5), and edge cases are expected within and between these basins.

Before the PP mapping, "three architectures" was a structural claim supported by functional closure. The PP mapping raises the bar: if the architectures are attractor states in a continuous precision-weighting space, the model must account for why these three basins of attraction are dominant and stable.

The two most relevant axes are prior precision and PE precision. The two locked architectures map to positions in this space: high-prior + high-PE (systemizer) and low-prior + high-PE-salience-as-consequence (scout). The socialite does not occupy a fixed point in this space — as §3.1 establishes, it is a strategy over the space, anchored by a channel-specific commitment (social) rather than by a global prior/PE setting. This means the 2D mapping captures two of the three architectures directly; the socialite is a qualitatively different kind of entity in this space. The fourth position — **low prior + low PE precision** — is unaccounted for.

**Candidate argument**: A system with low precision everywhere cannot maintain homeostasis and collapses into pathology rather than forming a stable architecture. This is plausible but unformalized.

**Status**: Open. This is the most pressing formalization problem. The current claim — that three dominant basins exist — is a first-order model. Whether the space contains additional stable configurations (at lower population frequency or narrower basin width) remains unexplored. The "why three" question does not threaten the existing architectural descriptions — it threatens the claim that three is complete. This framework claims three dominant basins exist, not that three is exhaustive. The theory is designed to be extended, not defended as complete.

**Categorical vs. dimensional status**: The framework is presented in categorical terms (discrete attractors) because the attractor-basin model generates different predictions than dimensional models — most critically in §5.1 (asymmetric stress degradation) and §5.8 (discrete behavioral clustering). However, the categorical vs. dimensional question is empirically open. All current observational evidence (Layer 2) is equally consistent with extreme positions on continuous dimensions. Until §5.8 or equivalent studies are conducted, categoricality is a modeling assumption that enables specific predictions, not an established finding.

---

## 4. Derived Mechanisms

### 4.1 Native vs. Learned Architecture

**Definition**: Native architecture operates pre-volitionally — it runs without being invoked, requires no conscious effort to initiate, and feels like a default mode. Learned/emulated architecture operates volitionally — it must be consciously executed each time and feels like deliberate work.

**PP mechanism**: Native architecture = the precision weighting policy implemented in automatic gain control (synaptic, neurochemical). Learned architecture = precision weighting imposed by top-down cognitive control overriding the native gain settings. The phenomenological discontinuity between native and learned operation is the difference between automatic gain control and effortful override.

### 4.2 Emulation Fatigue

Emulation is not merely "doing something hard." It is continuous top-down override of native gain control — manually suppressing one's automatic precision policy and imposing a non-native one, every inference cycle, without the automatic infrastructure that makes native operation effortless.

The energetic cost maps onto the literal metabolic cost of sustained prefrontal override of subcortical/default-mode tuning.

**Prediction**: The boundary between native and emulated operation should be phenomenologically discrete rather than graded — consistent with the qualitative difference between automatic gain control and effortful override.

### 4.3 Stress-Polarization

Under cognitive or emotional stress, native architecture amplifies while non-native architectures shed in reverse acquisition order. The system retreats to its native mode under load.

**PP mechanism**: Cognitive load depletes the top-down control resources that maintain non-native precision policies. The first thing to go is the effortful precision override (learned architecture). What remains is the native precision policy — the gain settings that don't require top-down maintenance. Stress-polarization is the system losing its ability to override its own default tuning.

### 4.4 Plasticity: Range Modification, Not Attractor Shift

Precision weighting policies are not fully fixed at birth. They are shaped by development, experience, and learning. However, plasticity operates around the native attractor state — it widens or narrows the operating range without shifting the set point.

**Implication**: The architectures are attractor states in a continuous precision-weighting space. Individuals can develop capacity at other points in the space, but the native attractor is where the system returns under resource depletion. This preserves the categorical structure (discrete attractors) while accommodating continuous variation (different orbit widths around each attractor).

### 4.5 AuDHD as Attractor Gradient

AuDHD is not "autism plus ADHD" as two discrete modules bolted together. It is a position in the precision-weighting space between the scout and systemizer attractors. Both profiles share the trait of inflexible precision allocation (unlike the socialite's flexibility), but they are inflexible in different directions. "Inflexible" here refers to the precision *policy* being fixed — the scout cannot stop exploring (locked low-prior), the systemizer cannot stop structuring (locked high-prior) — not to the behavioral output, which differs dramatically between the two.

**Hierarchical precision split**: The apparent contradiction — how can the AuDHD individual have both high structural priors (systemizer) and high PE salience from low priors (scout) simultaneously? — resolves when the precision policies are located at different levels of the predictive hierarchy. The systemizer component operates **within-model**: high prior precision on the structure being built, high confidence in the internal model's coherence. The scout component operates **on-model**: low prior precision on whether the model itself is valid, whether the entire enterprise should exist, whether the current direction is correct. These are not competing claims about the same channel — they are different precision policies at different hierarchical levels, running concurrently.

This produces AuDHD's characteristic signature: intense model-building (systemizer within-model priors driving depth and coherence) combined with catastrophic fragility (scout meta-level priors failing to suppress prediction errors about the model's validity). A minor external critique or internal inconsistency generates a PE at the meta level. Because the scout's low meta-prior cannot absorb it, the PE propagates. Because the systemizer has built a tightly-coupled model where structural coherence is high, a single meta-level crack threatens cascading collapse — the system cannot localize the damage because everything depends on everything. The phenomenological result is disproportionate to the trigger: a small signal produces a sense that the entire model is wrong and the entire effort was wasted.

This also explains the verification cost unique to AuDHD. To evaluate whether the model is actually wrong, the system must construct an alternative model at comparable precision and run both simultaneously — diffing two systemizer-grade simulations in parallel. This is computationally prohibitive, which is why the AuDHD individual's typical response to the meta-level PE is either abandonment (scout default: drop the model, move on) or outsourcing the comparison to an external system that can diff without the meta-level emotional loading.

**Contrast with pure profiles**: A pure systemizer has high priors at *both* levels — within-model and on-model-validity — so minor critiques bounce off the meta-prior. The model only collapses when accumulated external evidence overwhelms the high meta-prior, which takes substantial and sustained pressure. A pure scout has low priors at *both* levels — models are held loosely throughout, so there is no tightly-coupled structure to collapse and no catastrophic fragility. The AuDHD combination — high within-model, low on-model — is what produces the unique phenomenology: the flywheel (intense coherent building) and the crash (disproportionate collapse from minor signals).

Each AuDHD individual sits somewhere on the gradient between the two locked profiles, with a dominant pull toward one. The hierarchical split described above operates regardless of gradient position — what varies is the ratio of within-model depth to meta-level fragility.

### 4.6 Monotropism as Universal Axis

Monotropism — concentration of precision budget on a single channel — is a universal attentional parameter. All architectures can be monotropic. What differs across architectures is depth, duration, and what governs channel release.

- **Systemizer monotropism**: Deep, narrow, persistent. High prior precision on the model being built resists being outbid by competing PEs. Channel holds for years or a lifetime because switching means abandoning a high-confidence model, which the system experiences as structural damage.
- **Scout monotropism**: Deep, narrow, temporary. When engaged, intensity can match the systemizer's — but low prior precision means the channel holds only as long as the novelty-PE stream remains high. The moment the PE rate drops, a new channel outbids the current one.
- **AuDHD monotropism**: Deep, narrow, medium-duration. Systemizer component drives depth; scout component drives rotation. Position on the gradient determines the ratio.
- **Socialite monotropism**: Moderate depth, socially modulated. The social-channel anchor keeps reclaiming precision budget. Monotropic engagement should be most stable when socially embedded (book clubs over solo reading, team sports over solo practice). Predicts socialites rarely develop extreme specialist depth — not because they cannot focus but because their social anchor keeps pulling precision back.

### 4.7 Diagnostic Invisibility

Deficit-based diagnostic criteria are constructed by and for the socialite architecture. They measure deviation from socialite baseline. A high-capacity individual with non-socialite architecture who has successfully developed socialite emulation will not show deficits by these criteria — they will show costs (fatigue, effort, stress-reversion) that the diagnostic framework is not designed to detect.

### 4.8 Architectural Translator Function

A distinct functional role: an individual whose cross-architecture fluency allows them to repackage output from one precision profile into input that another profile can process without mismatch cost. The translator performs two simultaneous functions: (a) precision translation (reframing signal type) and (b) protocol management (absorbing relational/social risk so the receiving architecture can process without interference).

**Structural prediction**: Organizations with effective architectural translators should massively outperform those without, and the translator role should be predictable from cross-architecture fluency measures.

### 4.9 Protocol-Switching as Observable Precision Reallocation

Communication mode shifts between interlocutors of different architectures constitute directly observable precision reallocation. The effort gradient should track distance from the communicator's native precision profile — interaction with same-architecture individuals should require least effort; interaction with the most distant architecture should require most.

### 4.10 Architecture-Specific Leadership Failure Modes

Each failure mode is a specific precision weighting pathology. Each is optimally detected by the other architectures' native profiles:

- **Scout leaders**: Too many unsuppressed PEs → direction changes constantly. Systemizer correction: impose structure. Socialite correction: stabilize the group.
- **Socialite leaders**: Social precision drowns out non-social PEs → threats and model-reality mismatches go undetected. Scout correction: flag novel threats. Systemizer correction: flag model failure.
- **Systemizer leaders**: Prior precision so high PEs can't force revision → the world moves on while the model remains. Scout correction: signal environmental change. Socialite correction: surface human cost.

### 4.11 Architecture-Native Engagement Modes

Each architecture has a characteristic native engagement mode — an optimal state where the native precision-weighting profile runs at full capacity with minimal interference.

**Terminological note**: These states are referred to as native engagement modes, not flow states. They share features with Csikszentmihalyi's (1990) flow — absorption, intrinsic reward, altered time perception — but differ from formal flow theory in important ways. Flow as formally defined requires a specific challenge-skill balance, a sense of control, and clear feedback, and is treated as a universal state accessible to anyone when conditions align. The claim here is stronger and more specific: each architecture has a different kind of optimal experience, with different entry conditions, different phenomenology, and a different precision-weighting signature.

**Systemizer native engagement mode**: All available precision budget concentrated on the structural-prior channel and its associated sensory inputs. Competing channels suppressed to near-zero. The high prior precision on the model being built locks the channel in place; the high sensory PE precision on relevant detail creates total immersion in the subject. Entry condition: deep subject-alignment — the system must be engaging with a domain where it has built or is building a high-confidence model. This explains why systemizers can sustain intense focus for hours on their domain of engagement but cannot force the same state on an unrelated task — the prior precision is not present to anchor the channel. This state more closely resembles hyperfocus as described in the clinical literature — intense sustained attention with diminished perception of non-task stimuli — than formal flow. Research shows hyperfocus and flow are related but distinguishable: hyperfocus is associated with perceived loss of control and can override self-care, while flow involves a sense of effortless control (Hupfeld et al., 2019; Ashinoff & Abu-Akel, 2021).

**Scout native engagement mode**: The effective PE salience — a consequence of low prior precision (§2.2) — is continuously sustained because the unfolding activity itself generates a stream of novel prediction errors. Each moment of execution generates enough prediction error — micro-novelty, micro-discovery — to sustain engagement. The low prior precision means the scout is not locked onto a model but is riding the PE stream in real time. Process and exploration merge: the activity itself becomes the adventure. Entry condition: process-engagement where the activity generates continuous novelty. This explains why scouts enter this state during improvisation, real-time problem-solving, or action-oriented tasks, but struggle with repetitive execution where the PE stream dries up. The scout's engagement collapses when novelty drops, even if challenge-skill balance is maintained — which standard flow theory does not predict.

**Socialite native engagement mode**: Social-channel precision at maximum, with social prediction errors being resolved in real time through reciprocal exchange. The flexible non-social precision budget is freed because the social anchor is fully satisfied — the protocol handshake is not just complete but running at high bandwidth. This frees cognitive resources normally spent monitoring social status. Entry condition: genuine reciprocal social engagement — the social prediction channel must be receiving high-quality, high-bandwidth signal through authentic emotional exchange, not performative socializing. This explains why socialites can feel deeply connected in intimate conversation or collective crisis but drained by shallow networking — the former saturates the social channel, the latter generates unresolved social PEs. This state more closely resembles group flow or shared interactive flow (Sawyer, 2003; Hackert et al., 2023) — collective synchrony, self-other overlap, seamless coordination. The triadic model predicts socialites access this state with lower thresholds and higher frequency than other architectures.

**Cross-architecture engagement access**: The plasticity mechanism (§4.4) predicts that individuals can develop enough cross-architecture capacity to touch another architecture's native engagement mode. This access should show higher energy cost, faster depletion, and stress-reversion to the native mode — consistent with the emulation fatigue mechanism (§4.2). The engagement is real but it is not home.

**Testable prediction**: See §5.9.

### 4.12 Cross-Architecture Growth Trajectories

Each architecture's native strength eventually reveals its own ceiling. The feature that makes the architecture powerful is also the feature that eventually limits it. Growth occurs when the individual recognizes this ceiling and chooses to develop a non-native operation — deliberately running a non-native precision-weighting policy against the automatic gain control.

This development uses the same mechanism as masking: top-down override of the native precision-weighting policy, producing emulation fatigue (§4.2). The distinction is in motivation and outcome:

**Masking** runs a non-native precision policy because the environment demands it. The goal is concealment of native architecture. It produces depletion without expansion — the override does not build new capacity, it hides the native one.

**Deliberate cross-architecture development** runs a non-native precision policy because the individual has recognized the limit of their own architecture. The goal is expansion, not concealment. It still produces depletion (the mechanism is identical), but it also builds new orbits around the attractor over time (§4.4). The learned capacity persists under low-load conditions but sheds under stress, revealing the native attractor — consistent with the stress-polarization mechanism (§4.3).

The three growth trajectories:

**Systemizer → Scout development**: The systemizer's depth becomes limiting when the individual has been building deeply in territory that is no longer relevant, or has never explored beyond the current domain. The high prior precision that enabled mastery now prevents model-release and territory-seeking. Growth requires learning to lower prior precision voluntarily — to tolerate incomplete models, to release, to explore without a blueprint. The systemizer architecture experiences model-abandonment as structural damage, which is why this is the path of most resistance.

**Scout → Systemizer development**: The scout's exploration becomes limiting when the individual has found many worthy subjects but built none of them to depth. The low prior precision that enabled discovery now prevents sustained commitment. Growth requires learning to raise prior precision voluntarily — to stay with one thing, to build depth, to resist the next novel signal. The scout architecture experiences sustained commitment as confinement, which is why this is the path of most resistance.

**Non-socialite → Socialite development**: Both systemizer and scout architectures become limiting when the individual's output is not reaching others — no one uses what has been built or found because the connective tissue to bring others along was never developed. Growth requires learning to impose social-channel precision — to monitor social signals, to manage protocol, to translate technical output into terms others can receive. The non-social architectures experience sustained social-channel processing as energy drain, because the social channel is operating on manual override rather than automatic gain control.

**Socialite → Non-socialite development**: The socialite's flexibility becomes limiting when the individual is maintaining cohesion around structures they did not build and cannot evaluate, or maintaining stability when the group needs to move into unknown territory. Growth requires learning to either deepen (systemizer direction) or explore (scout direction) — to engage with non-social channels without the social anchor constantly reclaiming precision budget.

**Connection to the loop**: This growth model mirrors the sequential dependency (§3.2) at the individual level. Just as the group cycle follows explore → structure → cohere, an individual's development can move through the same sequence. An individual who develops cross-architecture capacity has internalized the loop — this is rare and costly, but the framework predicts it is possible (plasticity modifies range around the attractor) and that the native architecture remains dominant under stress regardless of the extent of cross-architecture development.

**Connection to HIPPEA reframe**: The HIPPEA account (§1.2b) frames inflexible precision as a deficit — something broken that prevents flexible adjustment. This growth model adds a layer: the inflexibility is a native feature that enables depth, but it can become a limitation when the individual's goals exceed what the native architecture can deliver. At that point, the individual can choose to develop flexibility — not because the architecture is broken, but because they have outgrown one mode. The inflexibility is not the deficit. The limitation appears only when the individual needs something their architecture does not natively provide.

---

## 5. Consolidated Predictions

All predictions extracted from the theoretical framework, collected for evaluation. Each is labeled with the competing model it differentiates against.

### 5.1 Stress-Polarization Signature

**Prediction**: Under cognitive or emotional stress, native architecture amplifies while non-native architectures shed in reverse acquisition order. Degradation is asymmetric and architecture-specific.

**Differentiating against**:
- Triadic model predicts: Asymmetric degradation — native functions hold or amplify, non-native functions collapse first.
- Dimensional model predicts: Uniform degradation across all traits under stress.
- Medical model predicts: No architecture-specific degradation pattern; just general impairment.

**Status**: Foundational empirical question. Should be tested first.

### 5.2 Emulation Fatigue Discontinuity

**Prediction**: The transition from emulated to native operation is phenomenologically discrete (step function), not smooth (gradient). There is a felt boundary between automatic and override operation.

**Internal tension note**: This prediction sits in tension with the plasticity mechanism (§4.4), which says the orbit around the native attractor widens with development. If the orbit widens, one might expect the boundary to become more graded, not less. The proposed resolution: the phenomenological discontinuity persists regardless of orbit width — the cliff between automatic and override operation is always there, but an individual with extensive cross-architecture development can stand further from home before reaching it. The range of emulated operation widens; the nature of the boundary does not change. This resolution is plausible but untested.

### 5.3 Bidirectional Mismatch

**Prediction**: Architectural mismatch produces costs regardless of which architecture is mismatched with its environment. Socialites in non-socialite-dominant environments should show mismatch costs comparable in kind (though perhaps not in social consequence) to non-socialites in socialite-dominant environments.

### 5.4 AuDHD Gradient Directionality

**Prediction**: Within AuDHD populations, scout-dominant individuals should present with more ADHD-characteristic symptoms and systemizer-dominant individuals with more ASD-characteristic symptoms. Both should show stress-polarization toward their dominant pole.

**Differentiating against**: The "two comorbid conditions" model, which predicts no systematic gradient-dependent directionality in stress responses.

### 5.5 Diagnostic Underdiagnosis

**Prediction**: Current deficit-based diagnostic criteria should systematically underdiagnose high-capacity individuals with developed emulation. The underdiagnosis rate should correlate with emulation quality, not with architecture absence.

### 5.6 Monotropism Across Architectures

**Prediction**: Monotropism is measurable across all architectures with architecture-specific expression patterns (persistence, duration, release-trigger). This is testable and differentiates against models that treat monotropism as autism-specific.

### 5.7 Translator Effect on Organizational Performance

**Prediction**: Organizations with effective architectural translators should massively outperform those without. The translator role should be predictable from cross-architecture fluency measures.

### 5.8 Children's Stress Response Clustering

**Prediction**: Young children placed in mild frustration scenarios should show stress responses clustering into three discrete behavioral patterns:
- Native scouts: physically move, explore the room, shift attention, seek novelty.
- Native systemizers: intensify focus, dig into current engagement, resist interruption harder.
- Native socialites: seek a person, initiate eye contact, vocalize, move toward caregiver or peer.

**Differentiating against**: Dimensional models, which predict smooth individual-variation gradients rather than discrete clustering.

### 5.9 Architecture-Native Engagement Entry Conditions

**Prediction**: The three architectures should show different entry conditions for their optimal engagement states. Systemizers enter through subject-alignment (prior precision anchoring), scouts through process-novelty (PE stream sustaining), socialites through social reciprocity (social-channel saturation). The observable intensity of absorption may be comparable across architectures; the triggers should be architecture-specific.

**Differentiating against**: Standard flow theory (Csikszentmihalyi, 1990), which predicts a single universal entry mechanism (challenge-skill balance) regardless of individual differences in cognitive architecture.

---

## 6. Open Problems

### 6.1 Severity: High

**Operationalization gap.** The core constructs — precision weighting, architecture identification, emulation quality, native vs. learned operation — lack operational definitions sufficient for independent empirical testing. Precision weighting is used qualitatively; architecture identification currently depends on the theorist applying the theory (circular). For the framework to generate empirical research programs, a researcher needs to know: what do I measure, and how do I determine someone's architecture independently of the framework's predictions? The children's study (§5.8, Appendix C) is the most promising path because it proposes behavioral observation of stress responses as an architecture identification method. For adults, the camouflaging literature (Hull et al., 2017; see §1.1) offers existing validated instruments (CAT-Q) that could operationalize emulation cost. Computational PP methods (Hierarchical Gaussian Filter, active inference modeling) could in principle estimate precision parameters from behavioral data, but this requires the formalization identified in §1 and Appendix B. Until operationalization is achieved, the framework generates predictions that are testable in principle but not yet in practice.

**Why three dominant attractors?** Reframed in §3.3 as a first-order approximation problem. The PP mapping requires a principled account of why these three basins of attraction are dominant and stable. The fourth quadrant (low-prior + low-PE) must be addressed — either as an unstable configuration (with argument for why) or as a potential additional architecture (with implications mapped). The current claim is that three dominant basins exist; the claim that three is complete remains open and under formal pressure.

**Unfalsifiability — partially addressed.** Three candidate falsification criteria exist. The boundary-absorption problem persists: what neurodevelopmental variations fall outside the three-phase framework? The PP mapping offers a partial path (conditions as perturbations of existing attractors vs. distinct attractor states) but this analysis has not been performed.

### 6.2 Severity: Moderate

**PP framework dependency.** The Bayesian brain / predictive processing account of autism is one of several competing models. The empathizing-systemizing theory, the intense world theory, the social motivation theory, and monotropism theory are partially overlapping but not fully reconciled. If PP is substantially revised, the formal layer requires rebuilding. The PP literature positioning (§1.2) makes this framework's specific commitments and disagreements explicit.

**Dopaminergic model simplified.** Norepinephrine, DMN dysregulation, cortical maturation delays, and cerebellar involvement are not yet integrated.

**Group selection problem — scoped out.** The evolutionary mechanism (group selection vs. frequency-dependent selection vs. inclusive fitness) is not resolved in this version. The PP framework stands independently of the evolutionary claim — the three architectures can be characterized as attractor states in precision-weighting space without requiring an evolutionary account of how they stabilized. The evolutionary argument will be developed separately and is not a structural dependency of the current theory. This decouples the core framework from its most vulnerable supporting argument.

**Population heterogeneity underaddressed.** Within-category variance remains enormous. The PP mapping provides a framework (basin position, basin depth, orbit width) but has not been applied.

**Sample bias.** The observational base is a single primary observer. See Layer 2.

### 6.3 Severity: Low-Moderate

**AuDHD interaction dynamics — partially superseded.** Original claims about antagonistic masking, resource competition, and paradoxical motivation were never formally downgraded. The gradient reconceptualization partially supersedes them.

**Structural asymmetry unresolved.** Whether the two-states-plus-one-strategy finding is a feature or a problem remains open.

**Socialite non-social flexibility unspecified.** The anchor is decomposed; the flexibility is described but not mechanized.

---

## 7. Parked Hypotheses

These hypotheses are grounded in the framework but blocked on prior validation. They are included for completeness, not as active claims.

### 7.1 IQ as Second-Order Resource Constraint

**Claim**: Cognitive capacity modulates how far an individual can operate from their native architecture.

**PP interpretation**: IQ maps roughly to the computational budget available for precision optimization — how many hierarchical levels can be simultaneously maintained, how fine-grained the precision allocation can be, how quickly the system can revise. Higher IQ = more capacity to run non-native precision policies because there is more top-down control resource available.

**Required prior validation**: Stress-polarization signature must be established first.

### 7.2 Architecture-Dependent IQ-Outcome Gradients

**Claim**: IQ should interact differently with each architecture.

**Status**: Derivative of IQ-as-resource hypothesis. Double-parked.

---

# LAYER 2 — OBSERVATIONAL EVIDENCE

---

## Evidential Status Conventions

Each observational item is labeled with one of the following:

- **[ILLUSTRATIVE]** — Consistent with the model but not confirmatory. The observation fits the theoretical prediction but could also be explained by other frameworks. Included because it demonstrates the kind of evidence the model would need, not because it constitutes that evidence.
- **[MOTIVATING]** — The observation that originally generated or shaped the theoretical claim. Subject to post-hoc interpretation bias by definition. Included for intellectual honesty about the theory's origins, not as independent support.
- **[STRUCTURAL]** — The observation has structural features (asymmetry, directionality, discreteness) that are difficult to account for without something like the proposed mechanism, even if the specific mechanism is uncertain.

**General caveat**: The primary observational base is a single theorist with proposed AuDHD architecture, reporting on their own experience and that of immediate family members. All observations are filtered through this single perspective. The theorist has demonstrated epistemic discipline (refusing to speculate beyond data, accepting corrections, flagging own biases) but single-observer data is inherently limited regardless of observer quality. Nothing in Layer 2 should be read as confirmation of Layer 1. It is the evidential material the theory was built from and must eventually move beyond.

---

## 8. Observer Position

The theorist is a proposed scout-dominant AuDHD individual who spent approximately 26 years running socialite emulation before recognizing the native architecture underneath. This creates specific strengths and limitations:

**Strengths**: Deep cross-architecture experiential data. First-person access to the emulation/native boundary. Ability to report phenomenological differences between automatic and override operation.

**Limitations**: All observations are filtered through a single cognitive architecture. The systemizer component may over-structure the framework. The scout component may under-value the socialite architecture's depth. The emulation history may bias the theorist toward seeing emulation everywhere.

**Methodology — LLM as cognitive prosthetic**: This document was produced with extensive use of large language models as a serialization and processing interface. The theorist's native architecture (scout-dominant AuDHD) makes sustained structured output of this depth and length prohibitively costly without assistive tooling — the serialization task requires running systemizer-mode precision policies on manual override, which the framework itself predicts to be energetically expensive (§4.2, §4.12). The LLM served as the interface between the theorist's internal models and structured text: the structural reasoning, theoretical positions, and predictions originated with the theorist; the serialization into coherent prose, the citation formatting, and the organizational scaffolding were LLM-assisted. Every claim in this document has been reviewed, contested, or approved by the theorist across multiple readings — new sections emerge when the theorist's engagement with the existing text generates new connections, disagreements, or structural gaps. The theorist orchestrates the LLM, not the reverse. This disclosure is made for the same reason as the conflict-of-interest statement — transparency about the process by which the document was produced allows readers to calibrate their trust appropriately. It also constitutes a minor instance of the framework demonstrating itself: the tool the theorist required is predicted by the architecture the theorist describes.

**Implication**: The theorist's observations are most reliable where they report on their own phenomenology (what native vs. emulated operation feels like) and least reliable where they attribute architecture to others (family members, colleagues, public figures).

---

## 9. Observational Evidence by Theoretical Claim

### 9.1 Stress-Polarization (supports §4.3)

**[STRUCTURAL]** Theorist self-report: Under argument stress, the theorist reports "uncontrollable" reversion to logic-tree construction (systemizer) despite having developed Pareto heuristics (scout-compatible behavior). The Pareto capacity is a learned orbit around the systemizer attractor; the attractor holds under load. The structural feature — asymmetric degradation with native amplification and non-native shedding — is the key datum, not the specific content.

**[ILLUSTRATIVE]** Theorist's partner (proposed native socialite): Under relational stress, intensified socializing while logical reasoning degraded. Consistent with social-channel-anchored precision holding while non-social processing sheds.

### 9.2 Emulation Fatigue (supports §4.2)

**[MOTIVATING]** Theorist's 26-year NT emulation history. Phenomenological report: native operation feels like release, emulated operation feels like continuous work, and the boundary between them is discrete rather than graded. This is the observation that generated the emulation fatigue mechanism — it is not independent evidence for it.

### 9.3 AuDHD Gradient (supports §4.5)

**[ILLUSTRATIVE]** Theorist (proposed scout-dominant AuDHD) and theorist's brother (proposed systemizer-dominant AuDHD, confirmed ASD diagnosis) show gradient-consistent differences in multiple domains:

- Communication: The theorist's associative leaps occasionally produce errors in the brother when they violate structural expectations. The theorist tolerates the brother's structural rigidity without equivalent error signals. Asymmetry is consistent with different dominant attractors.
- Game preferences: The theorist prefers action roguelikes (real-time novelty-processing, rapid adaptation — scout precision demands). The brother prefers roguelike deckbuilders (combinatorial optimization, system-building — systemizer precision demands). Same genre, different precision demands, different preference.

**[STRUCTURAL]** Bidirectional prediction errors between the theorist (scout-dominant AuDHD) and the brother (systemizer-dominant AuDHD): Despite deep resonance and shared AuDHD architecture, the two individuals generate prediction errors in each other when their dominant attractors conflict. The brother's systemizer-dominant models produce structural expectations that the theorist's scout-dominant associative leaps violate; conversely, the theorist's scout-dominant fluidity encounters friction against the brother's structural rigidity. Both directions produce disconnection. Neither direction is wrong — they are two positions on the same gradient, each generating prediction errors the other's dominant precision profile is not tuned to suppress. The bidirectionality is the key structural feature: relationship dynamics between architectures are always bidirectional, and none are wrong. Everyone is right from the precision profile they are running.

**Limitation**: Both architecture attributions made by the theorist. The brother's experience of the mismatch is not independently reported.

### 9.4 Bidirectional Mismatch (supports §5.3)

**[STRUCTURAL]** Theorist's mother (proposed native socialite) in a household with three proposed AuDHD/2e individuals (theorist, brother, father). Reported trajectory:

- Mismatch: Socialite architecture in systemizer/scout-dominant social environment. Father expressed care through systemizer channels (financial stability, practical problem-solving). Mother's high-precision social channel received insufficient signal — the emotional confirmation she required was not delivered in protocol-compliant form.
- Cost: Depression across approximately a decade.
- Resolution: Mother built a translation layer — learned to parse systemizer/scout communication without requiring the social handshake first.
- Current state: Reported as happy, now operating with cross-architecture reading capacity she would not have developed without the mismatch pressure.

The structural feature: mismatch costs follow the same pattern regardless of which architecture is mismatched. The directionality reversal (socialite mismatched in ND environment, rather than the usual ND mismatched in socialite environment) is the datum that is hard to explain without something like bidirectional mismatch.

**Limitation**: This is the theorist's interpretation of the mother's experience, not independently reported.

### 9.5 Protocol-Switching (supports §4.9)

**[MOTIVATING]** Theorist self-report of three distinct communication modes:

- With scouts: Direct, associative leaps. Lowest effort.
- With systemizers: Logic-based serialization. Moderate effort.
- With socialites: Social protocol management and feeling confirmation. Highest effort.

The effort gradient tracks distance from native precision profile. This observation motivated the protocol-switching mechanism — it is not independent evidence for it.

### 9.6 Architectural Translator (supports §4.8)

**[ILLUSTRATIVE]** Jeff Kaplan operating between Chris Metzen (proposed scout-systemizer) and implementation-level systemizers at Blizzard. Metzen's creative direction ("make this building THE highest in the realm") was scout-output — directional, non-monotropic. The systemizers receiving it interpreted it through monotropic precision — attempting pixel-level measurement. Kaplan recognized the instruction as directional, not dimensional, and translated accordingly. His statement ("if he gets upset I'll take the blame") simultaneously performed precision translation and socialite protocol management.

**Limitation**: Architecture attributions are post-hoc. The case is public record but interpreted through the triadic framework after the fact.

### 9.7 Diagnostic Invisibility (supports §4.7)

**[ILLUSTRATIVE]** The theorist's psychiatrist does not see ASD because the theorist's socialite emulation is performatively convincing. The theorist's mother (a psychiatrist) negated three separate signals across development because the theorist was performing adequately by socialite metrics. In both cases, the diagnostic system functioned as designed — and the design has a socialite architecture bias.

**Limitation**: Self-report of non-diagnosis is consistent with diagnostic invisibility but also consistent with actual architecture absence. This observation cannot distinguish between the two without independent architecture measurement.

### 9.8 Plasticity and Attractor Reversion (supports §4.4)

**[STRUCTURAL]** Theorist moved from rigid perfectionism to embracing Pareto heuristics through deliberate development. In PP terms: lowered prior precision on structural completeness. However, under argument stress, the theorist reports involuntary reversion to logic-tree construction and completionist analysis.

The structural feature: the learned capacity exists and functions under low-load conditions, but sheds under load to reveal the native profile. This is difficult to explain as smooth dimensional variation — it has the signature of a stable attractor with a modifiable orbit.

### 9.9 IQ as Resource Constraint (supports §7.1)

**[ILLUSTRATIVE]** Theorist's colleague (proposed native systemizer, lower cognitive capacity, age ~40): shows strong monotropic focus, limited scouting range, and a socializing ceiling despite genuine social motivation. Consistent with lower computational budget limiting the range of non-native operation.

**Limitation**: Single observation. Architecture and cognitive capacity both attributed by the theorist.

### 9.10 Cross-Architecture Communication Parsing (supports §4.9, §4.1)

**[ILLUSTRATIVE]** Theorist self-report: When asked "Do you want to pick me up?" by a socialite partner, the theorist's system involuntarily parses the literal semantic content, spawning parallel interpretation threads ("yes, I want to" vs. "no, because I am doing x") before the social-channel framing (a considerate request, not a literal question) can be processed. The socialite's phrasing routes through social protocol; the non-socialite's system assigns high precision to the literal content because that is where native gain is highest.

This pattern demonstrates: (a) the pre-volitional nature of native precision-weighting — the literal parsing occurs before conscious override can intervene; (b) the cross-architecture communication mismatch predicted by §4.9; and (c) the trainability of the response — the theorist reports decreasing annoyance over time, consistent with the plasticity-modifies-range claim (§4.4).

**Limitation**: Single-observer self-report. The parsing pattern is consistent with the model but also consistent with general literalism without architecture-specific precision-weighting.

### 9.11 High-Prior Precision Error Pattern (supports §1.2a, §2.1)

**[STRUCTURAL]** Observed pattern in a systemizer-architecture individual: Upon encountering a statement that conflicts with an established internal model (e.g., a joke parsed literally, a factual error, a category violation), the individual displays a brief visible frustration response (1–2 seconds), followed by a verbal correction stating the factual or structural expectation that was violated. The individual is often unaware that the frustration was externally visible.

This pattern has structural significance for the PP literature debate. If priors were weak (Pellicano & Burr, 2012), there would be no rigid model to violate — the system would encounter undifferentiated surprise, not a specific conflict. The observed pattern — specific prediction, specific violation, specific correction — is consistent with high-confidence priors that resist updating (this framework) and inconsistent with weak priors that fail to constrain (hypo-priors account). The micro-frustration is the phenomenological signature of a high-precision prediction error that the system cannot suppress.

**Limitation**: Post-hoc interpretation. The pattern is consistent with the high-prior-precision account but the observation was collected after the theoretical claim was formulated.

---

## 10. Observational Gap Analysis

The following theoretical predictions currently have **no observational evidence**, illustrative or otherwise:

- Children's stress response clustering (§5.8) — proposed methodology exists but has not been executed.
- Monotropism expression across all three architectures measured within a single study (§5.6).
- Translator effect on organizational performance (§5.7) — the Kaplan case is illustrative but no performance comparison exists.
- AuDHD gradient directionality in stress responses measured across a population (§5.4).
- Diagnostic underdiagnosis correlated with emulation quality (§5.5) — the theorist's case (§9.7) is illustrative but no correlation between emulation quality and underdiagnosis rate has been measured.
- Architecture-native engagement entry conditions measured across architectures (§5.9) — cross-architecture access is reported anecdotally in §4.11 but no systematic comparison exists.

These are the theory's most important empirical next steps. The children's study (§5.8) remains the most promising entry point because it strips the most confounding variables (decades of learned emulation, trauma responses, compensatory strategies).

---

# APPENDICES

---

## A. Epistemic Status Summary

| Claim | Status | Layer 1 Basis | Layer 2 Support | Change |
|---|---|---|---|---|
| PP usage is qualitative, not formal | Acknowledged | §1 | — | NEW v1.5 |
| Related frameworks differentiated | Stated | §1.1 | — | NEW v1.5 |
| Operationalization gap acknowledged | Open problem | §6.1 | — | NEW v1.5 |
| Within-diagnosis heterogeneity | Acknowledged | §2 | — | NEW v1.5 |
| Categorical vs. dimensional status empirically open | Acknowledged | §3.3 | — | NEW v1.5 |
| PP positioning: disagrees with hypo-priors | Explicit position | §1.2a | §9.11 [STRUCTURAL] | NEW v1.5 |
| PP positioning: reframes HIPPEA as architecture not deficit | Explicit position | §1.2b | — | NEW v1.5 |
| PP positioning: both priors and PEs high (vs. Lawson et al.) | Explicit position | §1.2c | — | NEW v1.5 |
| PP positioning: disagrees with predictive impairment (Sinha et al.) | Explicit position | §1.2a | — | NEW v1.5 |
| PP positioning: social entropy requires native gain control (vs. Constant et al.) | Explicit position | §1.2f | — | NEW v1.5 |
| PP positioning: disagrees with volatility overestimation (Palmer et al.) | Explicit position | §1.2g | — | NEW v1.5 |
| NT as own PP architecture is novel | Explicit claim | §1.2e | — | NEW v1.5 |
| Autism involves atypical precision weighting | Supported but contested model | PP literature | — | — |
| ADHD involves dopaminergic salience gating | Supported, simplified; unified with PP | Neurochemical unification argument | — | ↑ v1.3 |
| NT as specialization, not default | Novel reframe, logically sound | Structural argument (§3.1, §3.2) | §9.4 (bidirectional mismatch) | — |
| Three architectures form closed loop | Structurally elegant, with falsification criteria | Sequential dependency (§3.2) | — | ↑ v1.1 |
| Sequential dependency (explore → build → maintain) | Plausible, not demonstrated | §3.2 | — | — |
| Loop complete at three | Under formal pressure; reframed as first-order approximation | §3.3 (why-three problem) | — | ↓ v1.3, reframed v1.5 |
| Native = pre-volitional, learned = volitional | Mechanized via PP | §4.1 | §9.2 [MOTIVATING] | ↑ v1.3 |
| Stress-polarization: native amplifies, non-native sheds | Mechanized via PP | §4.3 | §9.1 [STRUCTURAL] | ↑ v1.3 |
| Emulation fatigue is discrete, not graded | Mechanized via PP | §4.2 | §9.2 [MOTIVATING] | ↑ v1.3 |
| Bidirectional mismatch | Structurally predicted | §5.3 | §9.4 [STRUCTURAL] | ↑ v1.3 |
| Architecture-specific leadership failure modes | PP-grounded | §4.10 | — | ↑ v1.3 |
| Architecture-intrinsic costs independent of mismatch | All three PP-grounded | §2.1, §2.2, §2.3 | — | ↑ v1.3 |
| Loop is dual-function: generative + error-corrective | PP-grounded | §3.2 | — | ↑ v1.3 |
| PP as unifying backbone | New v1.3 | §1 | — | NEW v1.3 |
| AuDHD as attractor gradient | Structurally sound | §4.5 | §9.3 [ILLUSTRATIVE] | NEW v1.3, revised v1.5 |
| AuDHD hierarchical precision split | PP-grounded, resolves internal tension | §4.5, §2.2 | §9.3 [ILLUSTRATIVE] | NEW v1.5 |
| Architectural translator function | Structurally predicted | §4.8 | §9.6 [ILLUSTRATIVE] | NEW v1.3 |
| Diagnostic invisibility as model prediction | Structurally predicted | §4.7 | §9.7 [ILLUSTRATIVE] | NEW v1.3 |
| Plasticity modifies range, not attractor | Confirmed by stress-reversion | §4.4 | §9.8 [STRUCTURAL] | NEW v1.3 |
| Protocol-switching as precision reallocation | Observable prediction | §4.9 | §9.5 [MOTIVATING] | NEW v1.3 |
| Monotropism as universal axis | Recharacterized | §4.6 | — | ↑ v1.3 |
| Architecture-native engagement modes | PP-grounded, novel | §4.11 | — | NEW v1.5 |
| Masking vs. deliberate cross-architecture development | Mechanistically grounded | §4.12 | §9.2 [MOTIVATING], §9.8 [STRUCTURAL] | NEW v1.5 |
| Cross-architecture growth trajectories | Derived from existing mechanisms | §4.12 | — | NEW v1.5 |
| IQ modulates architectural range | Parked | §7.1 | §9.9 [ILLUSTRATIVE] | ↑ v1.3 |
| Clinical labels reflect dominant-architecture bias | Supported by labeling theory | §4.7 | §9.7 [ILLUSTRATIVE] | — |
| Scout > Hunter as ADHD framing | Mechanistically tighter | §2.2 | — | — (Hartmann, 1993; PP-grounded justification added v1.5) |
| 300,000 years of operation | [SCOPED OUT — retained for version history only] | — | — | — (evolutionary argument scoped out of v1.5, see §6.2) |

## B. Recommendations for Development

### From prior versions — status:

1. **Decompose NT architecture mechanistically.** CLOSED v1.3. Remaining sub-gap: socialite non-social flexibility (§6.3).
2. **Define falsification criteria.** Partially addressed v1.1. Boundary-absorption problem remains.
3. **Engage with suffering that isn't environmental mismatch.** Closed v1.1–v1.2. Intrinsic costs specified.
4. **Reformulate evolutionary argument.** Scoped out of core framework (§6.2). Will be developed as a separate track, decoupled from the PP-grounded theory.
5. **Expand sample beyond n<10.** Still open. Children study design (§5.8) is most promising path.
6. **Publish or formalize.** Still open. v1.5 is the first version with PP literature positioning and epistemic transparency suitable for open-source sharing and external contribution.
7. **Test stress-polarization first.** Still the foundational empirical question (§5.1).
8. **Guard against architecture chauvinism.** Ongoing. Structural asymmetry acknowledged. Functional characterizations rewritten for equal representational depth (v1.5).
9. **Document observational instances systematically.** Still open. Layer 2 is a first step.
10. **Develop error-correction argument formally.** PP-grounded in §3.2.
11. **Test bidirectional mismatch in existing environments.** Longitudinal case in §9.4.
12. **Acknowledge observer position explicitly.** Done. §8. Confirmation bias disclosure added to document structure (v1.5).

### New from v1.5:

1. **Formalize engagement mode predictions empirically.** The architecture-specific entry conditions (§5.9) are the most accessible new prediction for experimental testing. Design a within-subjects study comparing engagement onset across different trigger types (subject-alignment, process-novelty, social-reciprocity) in individuals with identified architectures.
2. **Develop growth trajectory predictions with measurable outcomes.** The masking vs. deliberate development distinction (§4.12) predicts different long-term outcomes (depletion without expansion vs. depletion with orbit-widening). This should be measurable in longitudinal data.
3. **Seek external PP review.** The literature positioning (§1.2) enables targeted engagement with PP researchers. The specific disagreements with Pellicano & Burr, the reframing of HIPPEA, and the extension to ADHD and NT are now stated clearly enough to invite critique.
4. **Open-source publication.** v1.5 is the first version with sufficient epistemic scaffolding — literature positioning, qualitative acknowledgment, confirmation bias disclosure, layer separation — for external contributors to engage productively. Recommended for public release.

### Carried from v1.4:

1. **Maintain layer separation in all future versions.** New theoretical claims go in Layer 1 with formal basis identified. New observations go in Layer 2 with evidential status labels. No claim should exist in Layer 1 that can only be justified by pointing to Layer 2.
2. **Prioritize predictions that differentiate against competing models.** The theory's empirical value lies in §5.1 (stress-polarization), §5.4 (AuDHD gradient), §5.8 (children's clustering), and now §5.9 (engagement entry conditions) — these generate predictions that dimensional and medical models do not.
3. **Seek independent observers.** The single largest methodological improvement available is getting architecture attributions from someone other than the theorist.

### Carried from v1.3:

1. **Formalize the "why three attractors" argument** (§3.3). Now reframed as a first-order approximation problem, but formalization still needed.
2. **Specify neurochemical basis for all three profiles at comparable depth.** Dopaminergic unification (scout) is done. GABAergic/glutamatergic (systemizer) and oxytocinergic/serotonergic (socialite) mapping needed. Collaboration with a neuroscientist recommended.
3. **Develop AuDHD gradient model with explicit predictions** (§5.4).
4. **Formalize architectural translator concept in PP terms** (§4.8).
5. **Separate theorist's structural reasoning from PP literature.** Literature review mapping triadic PP claims against existing PP research needed before external presentation. Partially addressed by §1.1–§1.2; full review still needed. Collaboration recommended.

---

## C. Proposed Methodology: Children as Test Population

**Rationale**: Adult populations are contaminated by decades of learned emulation, social masking, trauma responses, and compensatory strategies. If native architectures exist as discrete categories, the signal should be cleaner in young children who haven't built those layers yet.

**Design**: Place children in mild, age-appropriate frustration scenarios and observe default behavioral responses.

**Predicted signatures** (from §5.8):
- Native scouts should physically move — explore the room, shift attention, seek novelty.
- Native systemizers should intensify focus — dig into current engagement, resist interruption harder.
- Native socialites should seek a person — initiate eye contact, vocalize, move toward caregiver or peer.

**What this tests**: Whether stress responses cluster into three discrete behavioral patterns (triadic prediction) or distribute along smooth individual-variation gradients (dimensional prediction).

**Ethical note**: Requires careful design — frustration must be mild and age-appropriate, with immediate resolution. Standard developmental psychology protocols exist for this type of study.

---

## D. References

Ashinoff, B. K., & Abu-Akel, A. (2021). Hyperfocus: The forgotten frontier of attention. *Psychological Research*, 85(1), 1–19. https://doi.org/10.1007/s00426-019-01245-8

Barkley, R. A. (1997). Behavioral inhibition, sustained attention, and executive functions: Constructing a unifying theory of ADHD. *Psychological Bulletin*, 121(1), 65–94. https://doi.org/10.1037/0033-2909.121.1.65

Baron-Cohen, S. (2002). The extreme male brain theory of autism. *Trends in Cognitive Sciences*, 6(6), 248–254. https://doi.org/10.1016/S1364-6613(02)01904-6

Baron-Cohen, S. (2009). Autism: The empathizing–systemizing (E-S) theory. *Annals of the New York Academy of Sciences*, 1156(1), 68–80. https://doi.org/10.1111/j.1749-6632.2009.04467.x

Chevallier, C., Kohls, G., Troiani, V., Brodkin, E. S., & Schultz, R. T. (2012). The social motivation theory of autism. *Trends in Cognitive Sciences*, 16(4), 231–239. https://doi.org/10.1016/j.tics.2012.02.007

Constant, A., Bervoets, J., Hens, K., & Van de Cruys, S. (2020). Precise worlds for certain minds: An ecological perspective on the relational self in autism. *Topoi*, 39(3), 611–622. https://doi.org/10.1007/s11245-018-9546-4

Csikszentmihalyi, M. (1990). *Flow: The psychology of optimal experience*. Harper & Row.

Friston, K. (2005). A theory of cortical responses. *Philosophical Transactions of the Royal Society B*, 360(1456), 815–836. https://doi.org/10.1098/rstb.2005.1622

Friston, K. (2010). The free-energy principle: A unified brain theory? *Nature Reviews Neuroscience*, 11(2), 127–138. https://doi.org/10.1038/nrn2787

Grossman, P., & Taylor, E. W. (2007). Toward understanding respiratory sinus arrhythmia: Relations to cardiac vagal tone, evolution and biobehavioral functions. *Biological Psychology*, 74(2), 263–285. https://doi.org/10.1016/j.biopsycho.2005.11.014

Hackert, B., Lumma, A.-L., Raettig, T., Berger, B., & Weger, U. (2023). Towards a re-conceptualization of flow in social contexts. *Journal for the Theory of Social Behaviour*, 53(1), 100–125. https://doi.org/10.1111/jtsb.12362

Hartmann, T. (1993). *Attention Deficit Disorder: A Different Perception*. Underwood Books.

Hull, L., Petrides, K. V., Allison, C., Smith, P., Baron-Cohen, S., Lai, M.-C., & Mandy, W. (2017). "Putting on my best normal": Social camouflaging in adults with autism spectrum conditions. *Journal of Autism and Developmental Disorders*, 47(8), 2519–2534. https://doi.org/10.1007/s10803-017-3166-5

Hull, L., Mandy, W., Lai, M.-C., Baron-Cohen, S., Allison, C., Smith, P., & Petrides, K. V. (2019). Development and validation of the Camouflaging Autistic Traits Questionnaire (CAT-Q). *Journal of Autism and Developmental Disorders*, 49(3), 819–833. https://doi.org/10.1007/s10803-018-3792-6

Hupfeld, K. E., Abagis, T. R., & Shah, P. (2019). Living "in the zone": Hyperfocus in adult ADHD. *ADHD Attention Deficit and Hyperactivity Disorders*, 11(2), 191–208. https://doi.org/10.1007/s12402-018-0272-y

Lawson, R. P., Rees, G., & Friston, K. J. (2014). An aberrant precision account of autism. *Frontiers in Human Neuroscience*, 8, 302. https://doi.org/10.3389/fnhum.2014.00302

Markram, K., & Markram, H. (2010). The intense world theory — A unifying theory of the neurobiology of autism. *Frontiers in Human Neuroscience*, 4, 224. https://doi.org/10.3389/fnhum.2010.00224

Murray, D., Lesser, M., & Lawson, W. (2005). Attention, monotropism and the diagnostic criteria for autism. *Autism*, 9(2), 139–156. https://doi.org/10.1177/1362361305051398

Palmer, C. J., Lawson, R. P., & Hohwy, J. (2017). Bayesian approaches to autism: Towards volatility, action, and behavior. *Psychological Bulletin*, 143(8), 801–829. https://doi.org/10.1037/bul0000097

Pellicano, E., & Burr, D. (2012). When the world becomes 'too real': A Bayesian explanation of autistic perception. *Trends in Cognitive Sciences*, 16(10), 504–510. https://doi.org/10.1016/j.tics.2012.08.009

Porges, S. W. (1995). Orienting in a defensive world: Mammalian modifications of our evolutionary heritage. A polyvagal theory. *Psychophysiology*, 32(4), 301–318. https://doi.org/10.1111/j.1469-8986.1995.tb01213.x

Sawyer, R. K. (2003). *Group creativity: Music, theater, collaboration*. Lawrence Erlbaum Associates.

Sinha, P., Kjelgaard, M. M., Gandhi, T. K., Tsourides, K., Cardinaux, A. L., Pantazis, D., Diamond, S. P., & Held, R. M. (2014). Autism as a disorder of prediction. *Proceedings of the National Academy of Sciences*, 111(42), 15220–15225. https://doi.org/10.1073/pnas.1416797111

Smith, R., Badcock, P., & Friston, K. J. (2021). Recent advances in the application of predictive coding and active inference models within clinical neuroscience. *Psychiatry and Clinical Neurosciences*, 75(1), 3–13. https://doi.org/10.1111/pcn.13138

Van de Cruys, S., Evers, K., Van der Hallen, R., Van den Noortgate, W., & Wagemans, J. (2014). Precise minds in uncertain worlds: Predictive coding in autism. *Psychological Review*, 121(4), 649–675. https://doi.org/10.1037/a0037665

---

## E. Personal Note

This document is a product of the loop it describes. It exists because scouts explored, systemizers built, and socialites held people together long enough for any of it to matter. The theorist is one node in a causal chain — the scientists, the traditions, the family, and the accumulated effort that made this synthesis possible.

Sharing the framework openly is a deliberate choice. The more a person understands their own architecture, the lower the cost of operating in the world and the more capacity they have available for contribution. The loop requires all three architectures. Making that structural dependency visible — so that each architecture is recognized for what it contributes rather than pathologized for what it costs — is the purpose of this document.

---

*v1.5 — New theoretical content (engagement modes, growth trajectories), PP literature positioning, qualitative acknowledgment, architecture descriptions augmented, evolutionary argument scoped out, "why three" reframed, confirmation bias disclosed. Layer separation maintained throughout.*
