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
    - few physical buttons
    - usability preference varies

## Mobile Design Guidelines

- size appropriately

- main functions apparent

- enable repeat actions

- allow offline use

- error prevention

- multi-sensory output

- speed and efficiency

## Air Gestures

- kinect

- applications

- challenges

- NUIs

- UI feels like an extension of body












# Wearables and Eye Tracking

## Eye Tracking and Measures

## Eye Tracking Uses

## Midas Gaze Problem

## Gaze Selection Techniques

## What Is Wearable Computing

## Design Issues With Wearables

- micro-interactions (no more than 4 seconds)

- interruptions

- social acceptance

- privacy/ethical concerns













# Accessibility
