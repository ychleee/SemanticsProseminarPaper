---
type: readingNote
tags: ["#reading" ]
author: 
aliases: ["Lim (2012)"]
publish: 
---
> Author: [[Dongsik Lim]]
---
# Content Summary
## 1. Introduction
Korean verbal ending -te- introduces different presuppositions depending on whether it appears with a tense marker (such as the past tense marker -ass/ess- or the future tense marker -keyss-) or not. When it appears without any tense marker, it introduces the presupposition1 that the speaker has direct perceptive evidence relative to the ‘prejacent’2 (hereafter direct evidential presupposition), as in (1):

Data:: 1. 어제 비가 오더라.

Note that (1) is interpreted as past, though there is no overt tense marker. That is, the eventuality denoted by the prejacent occurred before the utterance time t*. This becomes clearer when we compare (1) with (2), where -te- is replaced by the past tense marker -ass-. (2) has the same interpretation as (1), except that in (2) we do not have any presupposition regarding evidentiality of the speaker at all.

Data:: 2. 어제 비가 왔다.

The puzzling fact is that, when used with an overt tense marker, -te- seems to introduce a different presupposition. This is illustrated in (3). With the past tense marker -ass- or the future tense marker - keyss-, -te- introduces the presupposition that the speaker asserts the prejacent based on her inference (hereafter inferential evidential presupposition).

Data:: 3. 어제 비가 왔더라.
Data:: 4. 내일 비가 오겠더라.

Examples in (1)-(3) show the ‘mixed nature’ of -te-. It is not a run-of-the-mill past tense marker, since it introduces the evidential presupposition, and it can appear with a past tense marker -ass-.
However, apparently it is not a run-of-the-mill evidential, either, because the prejacent of -te- may denote the evidentiality occurring before t* (when used without any overt tense), and the presupposition it introduces vary depending on whether a tense marker is overtly present or not.
Many previous studies, including Chung (2007) and Lee (2010), analyze -te- with the (at least implicit) assumption that the generalization made in (1)-(3) always holds when -te- is used. However, in Section 2, while introducing more data some of which were overlooked before, I will show that there are some crucial exceptions of this generalization (that is, -te- does not always refer to the past when used without overt tense markers, and -te- does not always introduce the direct evidential presupposition when used without overt tense markers).

> I will propose that -te- is an evidential marker which introduces the presupposition that the speaker asserts the prejacent based on the inference from her direct perceptive evidence, and illustrate how this proposal can account for the pattern in (1) and (3), as well as the exceptions in Section 2.
## 2. More data on -te-
### 2.1 -te- always requires direct perceptive evidence
- wrong
data: 4. # 어제 비가 왔더라. 
- 맥락: (Scenario: John is sick, so he has stayed in his bed since yesterday and has not been outside at all. John’s room does not have any window, so he could not see outside, either. Today he heard from his roommate that the ground is wet. John says to his friend on the phone...)
- -te- with an overt tense is not compatible with any kind of inference, but it is felicitous only when the speaker’s inference should be based on direct perceptive evidence.
### 2.2 -te- may introduce inferential evidential presupposition without any overt tense.
> many of the previous studies simply take it for granted that, when -te- is used without any overt tense marker, it always introduces the direct evidential presupposition, and its prejacent always denotes the eventuality in the past.
> > However, this faces problem in expaining data like 5.

Data:: 5. 오늘 밖에 비가 오더라.
- 맥락: (Scenario: Mary was sick, so she stayed in her bed all day long. Her room does not have any window, so she could not see outside at all. Now she saw that her roommate came home with a wet umbrella and a wet raincoat. She says to her friend on the phone...)
C:: 정에 대한 반박?
### 2.3 The prejacent of -te- may denote future eventuality without any overt tense

Data:: 6. 존이 WWCFL에서 논문을 발표하더라.

(6) is ambiguous with respect to its temporal interpretation (as well as their evidential presupposition). First consider the scenario, where Mary went to the WCCFL meeting last week, and saw John present his paper. Under this scenario, Mary felicitously utter (6), with the interpretation of (7a) and the presupposition of (7b). In this case, the prejacent of (6) refers to the eventuality in the past, and (6) carries the direct evidential presupposition, as commonly assumed:

Data:: 7. Interpretation(a): John presented a paper in WCCFL
- Presupposition: the speaker directly saw that John presented a paper in WCCFL

Data:: 8. Interpretation(b): John is going to present a paper in WCCFL
- Presupposition: the speaker infers that John is going to present a paper in WCCFL from her direct evidence that John’s name is on the schedule.

We can see that, under the second scenario, the presupposition of (6), (8b), is an inferential evidential presupposition, which further confirms the observation made in Section 2.2. More importantly, we can also see that the prejacent of (6) now refers to the eventuality in the future, unlike the previous generalization made in Section 1. Note further that, without a tense marker, the prejacent of -te- can only refer to the eventuality in the near future. For example, suppose that Mary saw John’s name on the schedule of WCCFL for the next year. In this case, (6) becomes more unacceptable.
## 3. Proposal
> 1. -te- is an inferential evidential which requires direct evidence.
> 2. -te- is a function from propositions to characters, introducing a variable over contexts bound by lambda operator. 

### Lexical Entry for -te-:
- Given the facts in Section 1 and 2, I propose the following lexical entry for -te-:

Data:: 9. For any utterence context c*, : $[[-te-]]^{c*} =$ $\lambda p_{st}.\lambda_c$: there is a time interval t sailent in c such that t < t*, and that t, the speaker s  in c ($s^c$) acquires direct perceptive evidence, from which she infers p. p(where c* is the triple of the utterance speaker, the utterance time, and the utterance world, <s*,t*,w*>, and c is a variable over contexts: see Kaplan 1989)
- According to 9, -te- is a function from propositions to characters (function  from contexts to propositions of type <c,st>), with the definedness condition that ther is a salient time interval t before the utterance time t, and at that t, $s^c$ acquires direct perceptive evidence, from which $s^c$ infers the prajacent p. 
### 3.1 -te- without any overt tense

Data:: 10. 비가 오더라.
- when there is no overt tense, a covert anaphoric tense $t_{pro}$ is used (cf. Parte 1984). Given this, the LF(Logical Form) of 10 is 11:

Data:: 11.   $[-te-$      $[t_{pro}$       $\lambda w.$ it rains in $w  $]$   $]$
- $t_{pro}$ is a free variable, and it receives its value from the preceding salient time interval.
- Now there are two salient time intervals in (11): 
	- the one is t in the definedness condition on c in the lexical entry (9), which is the time when sc acquires direct perceptive evidence; 
	- the other is t* in c* (the utterance time).
- In general, tpro receives its value from t, since it is the closest time interval in the LF. In this case, since t is before t*, the prejacent is interpreted as past. However, as a free variable, $t_{pro}$ may also receive its value from t* in c*.
- This is because: 
	- the prejacent is interpreted as referring to the eventuality in the near future, as (8): when receiving its value from t*, it is interpreted as the present, which may further be interpreted as near future, just like present tense in English (like I am going to school now).
- Then how can the lexical entry for -te- in (9) introduce the direct evidential presupposition? Suppose that a speaker directly perceives the eventuality which can be denoted by a proposition p. From this direct perceptive evidence, the speaker may still ‘infer’ p (that is, the speaker makes a tautological inference p → p), which makes the inferential evidential presupposition ‘look like’ the direct evidential presupposition.
-  In the lexical entry in (9) above nothing prevents this inference. 
> [!note] Therefore, 
> I propose that the direct evidential presupposition of -te- is simply a ==special case of the inferential evidential presupposition== involving tautological inference in the form of p → p. This analysis allows us to explain the evidential presupposition in a unified way.
### 3.2 -te- with the past tense -ass-

Data:: 12. 비가 왔더라
- $t_{pro}$ is replaced by the past tense marker -ass-:

Data:: 13.   $[-te-$     $[$ $-ass-$       $\lambda w.$ it rains in $w  $]$   $]$

Since the tense is overt, the prejacent obligatorily refers to the eventuality in the past. Furthermore, since the eventuality denoted by the prejacent has already occurred in the past, in general, the speaker does not directly observe it. This means that -te- with the past tense marker can only introduces the inferential evidential presupposition.

### 3.3 -te- with the future tense -keyss-

Data:: 14. 비가 오겠더라.

Data:: 15.   $[-te-$     $[$ $-keyss-$       $\lambda w.$ it rains in $w  $]$   $]$

Like (12) (and 13), the prejacent obligatorily refers to the eventuality in the future. Since this eventuality does not occur yet, the speaker cannot directly perceive it. This means that -te- with the future tense marker can only introduces the inferential evidential presupposition.

>[!note] Summary
>1. -te- is a function from propositions to characters, 
>>- introducing a variable over contexts c bound by lambda operator, 
>>	- with the definedness condition that the speaker in c acquires direct perceptive evidence at time t before t*, 
>>	- and from that direct perceptive evidence the speaker infers the prejacent p. 
>2. With this definedness condition, two apparently different presuppositions of -te- can be explained in a unified way. 
>> I also accounted for the ambiguity of the temporal reading of the prejacent with -te- in a tenseless sentence such as (6) (also 1 and 10) by assuming a anaphoric tense, which can be bound either to t in c or $t^*$ in $c^*$.
[[Callouts Obsidian]]
## 4. Previous analyses
### 4.1 -te- as spatiotemporal diectic tense: [[Spatial deictic tense and evidentials in Korean|Chung (2007)]]
>[!info]- Chung (2007)
> >-te- is not an evidential marker by itself, but is a spatial deictic past tense in the sense of Faller (2004). According to her, -te- “not only denotes a temporally deictic past time but also the speaker’s spatial deictic vantage point at the reference time” (Chung 2007: 189). 
> >>In other words, informally speaking, it ‘locates’ the speaker in a certain spatial position and in a certain past time, where the speaker acquires a certain type of evidence relative to the prejacent.

Data:: 16. Spatial deictic past tense -te- (Chung 2007: 204):  $[[-te-]]^c$ is only defined if c provides a unique salient spatiotemporal location $L_c$ such that $\tau(L_c) < t_c \land L_c \subseteq P-trace(s_c)$. If defined, then $[[-te-]]^c$  = $L_c$ (where $t_c$ is the speech time, and $s_c$ is the speaker of the context c, and P-trace($s_c$) is the speaker $s_c$'s perceptual trace.)

> Question: Where does the evidential meaning come from?
> > Chung(2007): when used with -te-, -ass- and -keyss- are used as inferential evidential markers.

Data:: 17. (With $-te-$  )   | $-ass-$: inference based on result states | $-keyss-$: inference based on reasoning | ø: Direct evidential. |

Data:: 18. (Without $-te-$  )   | $-ass-$: perfective(anterior) tense | $-keyss-$: regular mood marker |

>[!note] Obviously, Chung’s (2007) analysis has several problems. 
>1. First of all, it is unclear why -ass- and - keyss- are used as evidential markers only when they appear with -te-, and why a covert direct evidential marker is used only when -te- is used. 
>2. Furthermore, it predicts that the sentence where -te- is used without a tense marker should carry the direct evidential presupposition (due to the covert direct evidential marker), 
>	- contrary to what we saw in Section 2.2 and 2.3: ==-te- may also introduce the inferential evidential presupposition, even without any tense.==

### 4.2 -te- as epistemic modal (2010)
>[!note] Lee(2010) shows that the semantic behavior of -te- is similar to that of epistemic moals. 

1. First, the negation of the prejacent in the immediately following sentence is infelicitous (Lee 2010: 296):

Data:: 19. a) It must have been raining / # It did not rain  |    b) 비가 오더라 / # 비가 안왔어 ^c87183

2. Neither of them is compatible with the first-person subject (Lee 2010: 297)

Data:: 20. a) Mary/ # I must be going to school   |   b) 메리가 / # 내가  학교에 가더라.  ^891911

3. Finally, both show modal subordination (Robers 1989) as in (21) (Lee 2010:299):

Data: 21. a) A theif might break into the house. He # will/ would take the silver. | b) 도둑이 들었더라. 그는 키가 # 작다  ^36e646
- A thief broke in (with inferential evidentiality) # He is short / he must be short.

> [!note] Lee(2010): -te- is an epistemic necessity modal (cf. Kratzer 1991)
 -te- is an epistemic necessity modal with the semantic components regarding 
>> - its direct evidentiality and 
>> - its temporal interpretation (indicating that the speaker acquires direct perceptive evidence before the utterance time). 

Data: 22. $[[-te]] = \lambda P_{<s,<i,t>>}.\lambda w.\lambda t. \exists t''[t''<t \land \forall w'[w' \in BEST(SO,ST/DX, w, t'') \rightarrow P(w')(t''))]]$ (where $BEST$ is the function which maps world-time pairs(w, t) to sets of worlds which are the most highly ranked with respect to the stereotypical/doxastic ordering source $ST/DX(w,t)$ in the sensory observation modal base $SO(w,t)$ )

##### two different evidential presuppositions introduced by -te- in terms of the interaction between -te- and tense markers. 
- Direct evidential presupposition: Overlap
	- Suppose the evidence acquisition time and the time of the eventuality denoted by the prejacent overlap. Then since the speaker may directly observe the eventuality, -te- introduces the direct evidential presupposition.
- Indirect: non-overlap
	- However, if they do not overlap, then the speaker cannot directly observe the eventuality, and therefore she can only infer what happened (or what will happen) at the time of eventuality from her direct perceptive evidence.
> [!note] Problems in Lee's account

- Most of all, her examples above are not strong enough to support her claim that -te- is an epistemic necessity modal. 
	- With my lexical entry for -te-, each example can also be accounted for as follows. 
		- The infelicity of ([[#^c87183|19b]]) is just because it is unnatural to deny what has just been asserted (remember that my lexical entry for -te- in 9 takes a proposition and returns a character with a definedness condition: if a context which the character takes as its argument satisfies the definedness condition, it returns the original proposition itself). 
		- The infelicity of ([[#^891911|20b]]) is because it is unnatural to make inference about the speaker’s own experience. 
		- Finally, the infelicity of ([[#^36e646|21b]]) is also explained in a pragmatic way. An assertion without any evidential marker normally carries the implication that it is based on the speaker’s strongest available evidence. However, -te- indicates that the speaker’s assertion is based on weaker (inferential) evidence. Therefore it is unnatural for the assertion without -te- directly follows the assertion with -te-. 
- It is unclear how to explain the examples we saw in [[#2.2 -te- may introduce inferential evidential presupposition without any overt tense.|2.2]] and [[#2.3 The prejacent of -te- may denote future eventuality without any overt tense|2.3]], where -te- without any tense introduces the inferential evidential presupposition, and the prejacent of -te- without any tense is interpreted as referring to the eventuality in the near future.
## 5. Conclusion and further implications
>[!note] 1. When a speaker adopts -te-, it introduces 
> - The definedness condition on the context that the speaker acquired direct perceptive evidence at some time interval before the utterance time, 
>> and from that evidence ==she makes inference== where her assertion is based on. 

With this proposal, I explained 
- the temporal interpretation of the prejacent of -te-, with an additional assumption that when there is no overt tense a covert anaphoric tense is used. 

>[!note] 2. The direct perceptive evidential presupposition introduced by -te- is a special case of the inferential evidential presupposition: 
> - the speaker makes ==tautological inference== from her direct perceptive evidence. 

### 5.1 Unexpectedness implication triggered by -te-
#### Redunduncy of  p→p
According to my analysis, the direct evidential presupposition of -te- is due to the tautological inference of the form p→p from the direct perception of the eventuality denoted by the prejacent p. 
However, this inference is obviously redundant. In [[#4.2|Section 4.3]]??[C:: There is no 4.3], a sentence without any evidential marker is in general interpreted as based on the best possible evidence, which is direct perceptive evidence. Then there seems no need to use -te- to specify direct perceptive evidence, even with a redundant inference.
- C:: Best possible evidence account is wrong. [[MVP-Evidentiality as Perspectiveness- Analysis of Korean morpheme '-te-'#|See]]

This redundancy leads us to another interesting prediction: if a speaker adopts -te- to indicate that her assertion of the prejacent p is based on direct perception of the eventuality denoted by p, since the speaker asserts p in a more complicated and redundant manner than usual, ==the sentence with -te- may carry the additional implication== (I use this term to remain neutral to the nature of this extra meaning component) that it is unusual, ==unexpected and/or surprising for the eventuality denoted by p to happen== (cf. the conversational maxim of manner in Grice 1975 or the notion of M implicature in Levinson 2000).
It is hard to test whether a sentence ==actually carries the unexpectedness/surprise implication== (since ==every assertion is ‘unexpected’, in some sense,== as far as it introduces new information which is not shared between conversational participants to the common ground). Nevertheless, at least some Korean speakers have the intuition that -te- without any overt tense marker actually triggers this implication. They also agree that -te- without a tense may carry a specific type of ==intonation==, such as raising tone on -te-, which is commonly adopted in Korean to express the unexpectedness or surprise. This may be tested by some experiment, but I will leave this for the topic of future research.

### 5.2 Exceptional de se reading triggered by -te-
#### Caki (self)
A more interesting implication of my proposal comes from the interaction of -te- with the anaphor caki, which is usually translated as ‘self’.  

Data:: 23. a) Pavarotti is listening to himself singing La donna e mobile and is impressed by his own skill. He thinks, “I have to admit it: I really am a genius!” | b) Pavarotti is listening to a performer singing La donna e mobile, and is impressed by his artistry. He thinks, “This performer is a genius! I could learn a lot from him.” Unbeknownst to him, he is the performer he is listening to.

Data :: 24 파바로티는 자기가 천재라고 생각했다.  (fine under 23a but unacceptable under 23b)

> Note that, (24), where caki appears in the embedded proposition under sayngkakha- ‘think’, is acceptable only under (23a). 
> >This means that caki is a de se anaphor when used as a long distance anaphor (two scenarios in 23 are from Anand 2006: 9, which is originated from Chierchia 1989).

#### Bill's son

Data:: 25. Bill and John are close friends to each other. They know each other’s children well, and their children go to the same school. Once Bill and John were invited to the school. In the school, when both Bill and John were looking at a class in a distance, they saw one kid making troubles during a class: walking around, yelling at classmates, etc. After that class, worrying that his own son might not take the class well due to that troublesome kid, Bill came to Tom, the teacher of that class, and told him to scold the kid who was making troubles in the class. However, John also found that, unbeknownst to Bill, the kid was actually Bill’s son.

Data:: 26. a) # 빌이 톰에게 자기의 아들을 혼내라고 말했다. | b) ==빌이 톰에게 자기의 아들을 혼내라고 말하더라.==

- the attitude holder Bill does not have the appropriate de se ascriptions,
	- therefore it is expected that caki cannot refer to Bill, as in (26a). 
- However, when -te- is used, as we see in (26b), ==caki can still be anchored to the attitude holder.== This means that the speaker’s state of knowledge, which is indicated by -te-, can also license the long-distance anaphoric use of caki. 
- In this sense, the de se reading involving caki and -te- is different from the commonly discussed de se reading involves PRO or other logophoric pronouns (c.f. Chierchia 1989, Anand 2006, among others). 
- Furthermore, since caki shows the similar behavior to other de se pronouns when the attitude holder has appropriate de se ascriptions, as shown in (23) and (24), it is actually the semantic of -te- which is responsible for this exceptional de se reading.

I do not think the lexical entries for -te- proposed by Chung (2007) or Lee (2010) can explain this exceptional de se reading triggered by -te-, but it is unclear how my proposal can explain this, either. One possible analysis of the exceptional de se reading with my lexical entry for -te- may go as follows. Many authors, including Anand (2006), try to analyze de se reading of certain pronouns in terms of Kaplan’s (1969) acquaintance relation: a pronoun can be read as de se only when the attitude holder has some acquaintance relation with the pronoun. Now, we may further speculate that the context variable c in -te- introduces some acquaintance relation (in terms of the definedness condition, for example), which further specifies that caki is anchored to the attitude holder. At the moment I do not have any answer how to formalize this speculation, or how to revise my lexical entry for -te- accordingly, and therefore I also leave this for future research. However, as far as I can see, my lexical entry for -te- seems to give us a more correct answer to the puzzle of exceptional de se reading in (25) and (26).
# Reviews and Comments
### DATA
```dataview 
TABLE WITHOUT ID Data 
FROM "ideaBlocks/Semantics Proseminar Term Paper/Korean Evidential -te- Inference from Direct Evidence"
WHERE Data != null
FLATTEN Data
```
#### Cs
```dataview 
TABLE WITHOUT ID C
FROM "ideaBlocks/Korean Evidential -te- Inefernce from Direct Evidence"
FLATTEN C
```
### Response 
### Meta Informations
Journal:: 
Published:: 
related:: 
Cited:: 
Field:: 
author:: 


