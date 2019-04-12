---

# Usable Security

## Why Usability Affects Security

- secondary task
    - users focus on their primary task
    - ignore security, or actively sabotage it

- weakest link property
    - the user is the weakest link
    - only takes one hole for a breach

- active adversaries

- barn door property
    - if an attacker gets in, it's GG

## Guidelines for Good Security UI

1. aware of tasks
1. how to perform tasks
1. no dangerous errors
1. comfortable
1. can tell task complete
1. can determine systems state

## Three Types of Authentication Mechanisms

1. Something you have -> 2FA
1. Something you know -> password
1. Something you are  -> fingerprint

## Password Space

- amount of possible unique passwords for a password scheme
- alphabet^length

## Why Does Phishing Still Work?

- people are dumb

## Usable Policies

- easy to remember -> easy to guess
- hard to remember -> hard to guess
- usability vs security trade-off












# Memory and Graphical Passwords

## Memory

- sensory memory
    - buffers (iconic, echoic, haptic)
    - filtering into short term memory by attention
- working memory
    - 70ms access, 200ms decay
    - 7 +/- 2 things at once
    - chunking can help with this
- long term memory
    - 100ms access, little decay
    - very large

- 7 +/- 2 rule for working memory

- expertise and context

- recognition > recall

- primacy and recency
    - first and last things are easier to remember

- best practice?
    - don't overload user memory (7 +/- 2)
    - recognition over recall
    - multiple ways of encoding info (like colored piano keys)

## Graphical Passwords

<!-- doesn't seem to be important -->
<!-- sana said it's better to know big picture stuff for this? follow up on that -->

- how was it designed?

- how data is analyzed and presented













# Quantitative Data and Analysis

## What to Collect?

- time to complete a task
- time to complete a task after specified time away
- number and type of error
- number of errors per unit of time
- number of navigations to help
- number of users who make an error
- number of users who complete task
- perception questionnaires

## Messy Data Collection

- solution: pre-processing
- be careful and include sanity checks
- check data manually as well

## Descriptive Statistics

- mean
- SD
- quartiles and whiskers
    - min
    - max
    - lower
    - middle
    - upper

## Why Do We Need Stats?

- describe data
- make generalizations based on a sample

## Type I and Type II Errors

- boy who cried wolf
- type  I: think effect exists when it doesn't
- type II: think effect does not exist when it does
- 95% CI is good (5% chance for type I or II error, p-value < 0.05)

## Independent vs Dependent Variables

- independent
    - what affects the dependent
- dependent
    - what we are measuring

## P-Value

- percent chance of making a type I error if you assume H0 is true
- ideally < 1 - CI

## Hypotheses

- H0 (null)
    - opposite of HA
    - we accept or reject this
- HA (alternative)
    - opposite of H0
    - we can only accept or reject H0
- for t-tests:
    - accept H0 if p-value > 1 - CI
    - reject H0 if p-value <= 1 - CI
- can be one-tailed or two-tailed
    - one-tailed: HA would be A <= B or A >= B
    - two-tailed: HA would be A != B or A == B

## Overall Process of Analyzing Data

- pre-process
    - parse it
    - clean it
- descriptive statistics
    - mean
    - SD
    - lower quartile
    - middle quartile
    - upper quartile
    - whiskers (min, max)
- graphs and plots
- tests
    - t-test
    - wilcoxon
    - etc.












# Statistics

## Skewness

- positive
    - large right tail
- negative
    - large left tail

## Kurtosis

- platykurtic
    - flat
    - thin tails
    - kurt < 0
- mesokurtic
    - normal distribution shape
    - kurt = 0
- letdokurtic
    - tall and thin
    - short but thicker tails
    - kurt < 0

## Hypothesis Testing

- H0, HA
- accept H0 if p-value > 0.05
- reject H0 if p-value <= 0.05

## Type I Error

- assume there is an effect when there isn't

## Type II Error

- assume there isn't an effect when there is

## Examples of Running Descriptive Statistics

<!-- come back to this -->
<!-- scuba example     -->

## Interpreting Results From Statistical Analysis

- measure effect size
- look at numbers
- figure out if data is meaningful

## Fishing vs post-Hoc Exploration

- fishing
    - bad
    - looking for something significant when there might not be
- post-hoc exploration
    - good
    - use unexpected results to inform later experiments

## Password Space
- repetition, order -> log2(alphabet^length)
- no rep, no order  -> log2(alphabet C length)
- no rep, order     -> log2(alphabet! / (alphabet - length)!) AKA log2(alphabet P length)











# Emotional Interaction

## Benefits of Incorporating Emotion Into Design

- people tend to treat computers as real people
- computers should emulate human etiquette
- make users feel at ease, comfortable

## Guidelines for Incorporating Emotion

<!-- come back to this -->

## Russell's Circumplex Model

- 2d circle mapped to emotions
- clockwise
    - activation
    - pleasant
    - deactivation
    - unpleasant

## PAD

- pleasure
- arousal
- dominance

## Flow Model

- state of concentration or complete absorption

## Theory of Media Equation

- people treat computers and other media as if they were real people

## Fogg's Principles of Persuasive Technology

- RATTSRC

1. reduction
    - simplify user tasks
1. tunnelings
    - lead to progressively more critical steps
1. tailoring
    - customize interaction to user
1. suggestion
    - present better alternative actions
1. conditioning
    - reinforcement
1. reciprocity
    - reward user
1. authority
    - mentor user

## Anthropomorphism

- advantages
    - flattering and praising users = good

- disadvantages
    - people don't like waving
    - makes people feel anxious, inferior, stupid
    - personalized feedback less honest, makes users feel less responsible













# Social Interaction

## Groupware Matrix

- synchronous/asynchronous
    - same time
    - different time

- co-located/remote
    - same place
    - different place

## Remote Conversations

- some mimic existing ways of conversing
- some move beyond

## Conversational Rules

1. Speaker chooses next speaker.
1. Another person decides to start speaking.
1. Current speaker keeps talking.

- turn taking
- back channeling (feedback like mhm, uh-huh)
- farewell rituals
- misunderstandings
    - huh?
    - speaker repeats with emphasis

## Coordination

- verbal/non-verbal communication
- schedules, rules, conventions
- shared external representations

## Awareness

- knowing who is around
- what is happening
- who is talking with whom

## Peripheral Awareness

- overhearing/overseeing
- keep track without explicit cues

## Multi-Touch Displays

- IR
    - detect disruption in LED beams

- Resistive
    - two thin layers
    - press on top and detect where they touch

- Capacitive
    - one side of surface is conductive
    - detect where capacitance increases













# Mobile Interaction

## Challenges/Features of Mobile Design

- use while on the move
- increasingly used in all aspects of life

- challenges?
    - smaller screens
    - fat fingers
    - few physical buttons
    - usability preference varies

## Mobile Design Guidelines

- size appropriately

- main functions apparent

- avoid forms
    - auto fill when possible

- enable repeat actions

- allow offline use

- error prevention

- multi-sensory output

- speed and efficiency

## Air Gestures

- kinect

- applications
    - gaming
    - sign language
    - video conferencing
    - touch-free situations
        - driving
        - sterile environments

- challenges
    - how to recognize specific gestures
    - how to separate one gesture from the next
    - may feel awkward or weird

- NUIs
    - natural user interface
    - feels like an extension of the body
    - should be comfortable (resting position most of the time)
    - easy gestures
    - avoid everyday gestures (unintentional interaction)












# Wearables and Eye Tracking

## Eye Tracking Tech and Measures

- measures eye movement
    - where you're looking
    - where your gaze shifts

- accurate to 0.5-1 degree
- how does it work?
    - infrared light and sensor
    - track corneal reflection using trig

Measures:

- fixations
    - when eyes are stationary
- saccades
    - quick eye movements between fixations
- scanpath
    - saccade-fixate-saccade path
- dwell time
    - prolonged gaze
    - longer than fixation

Less reliable:

- blink rate
    - low -> high workload
    - high -> fatigue
- large pupils
    - more cognitive effort

## Eye Tracking Uses

- indicator of visual focus and attention
- control signal for input

Domains:

- research
- medical

## Midas Gaze Problem

- everywhere you look could be interpreted as input
- how to separate real input from casual gazing

## Gaze Selection Techniques

- gaze pointing plus another method for selecting
    - like a button or a gesture
- adjustable dwell time
- pause/resume input
- make on-screen object bigger to address accuracy

## What Is Wearable Computing

- computer that you wear
- to be used during other daily activities
- expect interruptions

## Design Issues With Wearables

- micro-interactions (no more than 4 seconds)
    - split attention with real world
    - one task per interaction
    - one input per interaction
    - no more than 4 seconds per step

- interruptions
    - assume user is engaged in a real world task
    - "is this really necessary now?"
    - interrupt in a way that requires low attention
    - dismiss/ignore with minimal effort

- social acceptance
    - should be socially acceptable to those around
    - should be fashionable

- privacy/ethical concerns
    - can record private info
    - sensitive medical info
    - other people's privacy













# Accessibility

## Assistive Technologies

- promote independence for disabled people
- accomplish otherwise difficult tasks
- modified methods for interacting

## Principles of Universal Design

- make things accessible by default
- avoid need for post adaptations

1. Equitable use
    - identical for all users when possible
    - equivalent when not
2. Flexibility
    - offer choice of methods
3. Simple and intuitive
4. Perceptible information
    - redundant modes of presentation
    - contrast
5. Tolerance for error
    - minimize hazards
    - failsafe features

## Web Accessibility

Problems:

- images without alternate text
- misleading use of structural elements
- uncaptioned audio / undescribed video
- etc.

WCAG Standards (POUR):

1. Perceivable
1. Operable
1. Understandable
1. Robust

## How To Incorporate Accessibility Into Design

- design without user interface
    - MVC
