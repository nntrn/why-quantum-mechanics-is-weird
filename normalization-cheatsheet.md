# Quantum Drift Cheatsheet

> [!NOTE]
> In this project, 
> * Biology is used to mean **identity-first**
> * Psychology is used to mean **motion-first**
>
> ... and vice versa 

---

## IDENTITY-FIRST (Biology Structure)

### Core Logic

```
What something IS → What it DOES
(1:m mapping - one identity, many possible behaviors)
```

### Semantic Equations (POS)

```
NOUN → VERB
"Tiger" → "runs fast"
"Tiger" → "hunts prey"  
"Tiger" → "sleeps"
[One subject → many possible predicates]

ADJECTIVE NOUN → VERB PHRASE
"Sore loser" → "might yell"
"Sore loser" → "might flip table"
"Sore loser" → "might challenge again"
[Property-bearing entity → multiple possible actions]

IDENTITY STATEMENT → BEHAVIOR PREDICTION
"This is a tiger" → "can run 40mph"
"This is water" → "flows downward"
"This is copper" → "conducts electricity"
```

### Mathematical Equations/Expressions

Classical Mechanics:

```
F = ma
[mass (identity property) → acceleration (behavior)]

x(t) = x₀ + v₀t + ½at²
[initial conditions (identity) → trajectory (behavior)]
```

Thermodynamics:

```
PV = nRT
[gas properties (identity) → relations between them]

dU = TdS - PdV
[state properties (identity) → energy change (behavior)]
```

Classical Hamiltonian:

```
H(q,p) = T(p) + V(q)
[phase space point (identity) → energy value]

dq/dt = ∂H/∂p, dp/dt = -∂H/∂q
[state (identity) → evolution (behavior)]
```

General Form:

```
S(t₀) → S(t) for all t > t₀
[identity at moment → behavior over time]

No measurement operators
No observation dependence
No probabilistic outcomes (unless epistemic uncertainty)
```

### Question Types (Classification)

"What is X?" (Seeks identity)
```
* What is a tiger?
* What is temperature?
* What is this object?
```

"What properties does X have?" (Identity properties)
```
* What is its mass?
* What is its charge?
* What are its dimensions?
```

"What will X do?" (Prediction from identity)
```
* What will the ball do if I drop it?
* How fast can a tiger run?
* Where will the planet be in 10 years?
```

Valid reasoning:

```
IF identity confirmed (tiger) 
THEN predict behavior (can run fast, hunt, etc.)
```

Invalid reasoning:

```
IF behavior observed (runs fast)
THEN identity certain (must be tiger)

[Wrong because: could be cheetah, horse, dog...]
```

## MOTION-FIRST (Psychology Structure)

Core Logic

```
What something DOES → Infer what it IS

(m:1 mapping - many behaviors, one/zero/many possible identities)
```

Semantic Equations (POS)

```
VERB → NOUN (inference)
"Runs fast" → "might be tiger"
"Runs fast" → "might be cheetah"
"Runs fast" → "might be athlete"
[Action observed → multiple possible subjects inferred]

VERB PHRASE → ADJECTIVE NOUN (inference)
"Flips table" → "probably angry drunk"
"Flips table" → "probably clumsy person"
"Flips table" → "probably sorr loser"
[Behavior → multiple possible property-identities]
```

## BEHAVIORAL OBSERVATION → IDENTITY INFERENCE

```
"Appears here when measured" → "was probably in superposition"
"Test positive" → "probably has disease"
"Company growing fast" → "probably well-managed"
```

### Mathematical Equations/Expressions

Quantum Mechanics:
```
iℏ ∂ψ/∂t = Ĥψ
[constraints (Ĥ) + inference model (ψ) → how inference evolves]
[∂/∂t = change/motion required]

P(outcome) = |⟨outcome|ψ⟩|²
[measurement (motion/event) → probability of classification]
```

Heisenberg Equation:
```
d⟨A⟩/dt = (i/ℏ)⟨[Ĥ,A]⟩

[observable change (motion) → rate of change]
[Only describes transitions, not static identity]
```

Bayesian Inference:
```
P(identity|behavior) = P(behavior|identity)·P(identity) / P(behavior)

[behavior observed → probability of identity]
[Posterior depends on observation (motion)]
```

State Space Evolution:
```
ψ(t+dt) = U(dt)·ψ(t)  [deterministic constraint evolution]
Measurement → ψ_after = |i⟩ with P = |⟨i|ψ⟩|²  [probabilistic classification]
```

General Form:
```
Observation(t) → Update_inference_model
[behavior/motion → identity inference]

Requires measurement operators
Observation-dependent outcomes
Probabilistic classification
Context-sensitive (measurement basis matters)
```

### Question Types (Classification)

"What did X do?" (Behavior observation)
```
* What was measured?
* What outcome occurred?
* What behavior was exhibited?
```

"What can we infer about X?" (Identity from behavior)
```
* Given this measurement, what was the state?
* Given this behavior, what is likely identity?
* What possibilities are consistent with observations?
```

"How will observation change inference?" (Update from motion)
```
* If we measure position, what can we know about momentum?
* If we observe this, what must we update?
* What does this outcome tell us?
```

Valid reasoning:

```
IF behavior observed (flips table)
THEN infer identity possibilities (bad drunk, sore loser, etc.)
AND acknowledge ambiguity (m:1 = multiple possible identities)
```

Invalid reasoning:

```
IF behavior observed (particle appears here)
THEN identity certain (particle WAS here before measurement) ✗

[Invalid Because: measurement forces classification, doesn't reveal pre-existing location]
```

## SIDE-BY-SIDE COMPARISON

### Structural Properties

Property | Identity-First (Biology) | Motion-First (Psychology)
:--- | :--- | :---
Mapping | 1:m (one identity → many behaviors) | m:1 (many behaviors → one/zero/many identities)
Time dependence | Time-independent properties | Requires temporal process (observation)
Determinism | Behavior determined by identity | Classification probabilistic from behavior
Observation role | Reveals pre-existing properties | Forces classification/resolution
Uncertainty | Epistemic (lack of knowledge) | Structural (incompatible classifications)
Context dependence | Properties independent of measurement | Properties depend on measurement type

### Language Markers

Aspect | Identity-First | Motion-First
:--- | :--- | :---
Subject | System IS ψ | ψ tracks inference about system
Properties | Has definite values | Values emerge from measurement
Superposition | Impossible ("both at once") | Normal (unresolved inference)
Collapse | Mysterious physical process | Classification from observation
Measurement | Reveals what's there | Forces resolution

### Mathematical Signatures

Feature | Identity-First Math | Motion-First Math
:--- | :--- | :---
Operators | Commute: [A,B] = 0 | Don't commute: [x̂,p̂] ≠ 0
States | Definite: ψ = \|i⟩ | Superposed: ψ = Σαᵢ\|i⟩
Evolution | S(t₀) → S(t) deterministic | ψ(t) + measurement → probabilistic
Measurement | Not in formalism | Central to formalism
Phase space | Points are states | Hilbert space is inference space

## EXAMPLE TRANSLATIONS

### Example 1: Position

Identity-First (Classical):

```
Statement: "The ball is at x=5m"
Math: x = 5
Meaning: Ball HAS position 5m (property)
Prediction: Will be at x=5m if you look
Question: "Where is the ball?"
```

Motion-First (Quantum):

```
"The particle was measured at x=5m"

Math: ⟨x|ψ⟩ gave eigenvalue 5m

Meaning: 
Observation classified particle at 5m

Prediction: 
IF we measure position, THEN probability distribution |ψ(x)|²

Question: 
"Where did it appear when measured?"
```

### Example 2: Energy

Identity-First (Classical):

```
"The system has energy E = 10J"

Math: H(q,p) = 10J

Meaning: Energy IS property of system
Prediction: Energy will be 10J (conservation)
Question: "What is the system's energy?"
```

Motion-First (Quantum):

```
"Energy measurement gave 10J"

Math: 
Ĥ|ψ⟩ → eigenvalue E₃ = 10J, collapse to |3⟩

Meaning: 
Measurement classified system in energy level 3

Prediction: 
IF measure energy, THEN ⟨Ĥ⟩ expected value

Question: 
"What energy did it show when measured?"
```

### Example 3: Tiger

Identity-First:

```
"This is a tiger"

Logic: 
Tiger → can run fast, hunt, roar (1:m)

Math equivalent: 
Identity(tiger) → Behavior_set{run, hunt, roar}

Valid: 
Predicting possible behaviors from identity

Invalid: 
Assuming single definite behavior
```

Motion-First:

```
"This thing runs fast"

Logic: 
Runs fast → might be tiger, cheetah, horse (m:1)

Math equivalent: 
Observation(runs_fast) → Identity_set{tiger, cheetah, horse}

Valid: Inferring possible identities from behavior

Invalid: Claiming certain identity from single behavior
```

## QUANTUM MECHANICS CONFUSION DIAGNOSTIC

### When Textbook Says:

Statement | Hidden Structure | Should Say
:--- | :--- | :---
"System is in state ψ" | Identity-first language | "ψ tracks our inference about system"
"Particle has wave-like properties" | Identity-first | "Measurements show interference patterns"
"Superposition of states" | Identity-first (impossible) | "Multiple unresolved classifications"
"Measurement collapses wavefunction" | Identity-first (mysterious) | "Observation forces classification"
"Wavefunction is reality" | Identity-first | "Wavefunction is inference model"

### Quick Test: Which Structure?

Ask: "Can I calculate outcomes without reference to observation/measurement?"

```
* YES → Identity-first (classical mechanics, thermodynamics)
* NO → Motion-first (quantum mechanics, Bayesian inference)
```

Ask: "Do different measurement types give incompatible results?"

```
* NO → Identity-first (measurements reveal same underlying properties)
* YES → Motion-first (measurement type determines classification scheme)
```

Ask: "Can properties be specified completely and simultaneously?"

```
* YES → Identity-first (complete state specification possible)
* NO → Motion-first (uncertainty/complementarity)
```

## THE KEY INSIGHT

Why QM is confusing:

```
QM MATH = Motion-first (psychology structure)
QM LANGUAGE = Identity-first (biology language)
```

Motion-first math + Identity-first language = Contradiction

```
→ "Measurement problem"
→ "Interpretation debates"  
→ "Quantum weirdness"
```

The cheat sheet rule:

```
IF your equations require measurement/observation operators
THEN use motion-first language (psychology)

IF your equations work without measurement operators
THEN use identity-first language (biology)

NEVER mix: motion-first math + identity-first language
```

---

Source: 
github.com/nntrn/why-quantum-mechanics-is-weird
