---
layout: base
title:  'Statistics of ccomp in UD_Komi_Zyrian-IKDP'
udver: '2'
---

## Treebank Statistics: UD_Komi_Zyrian-IKDP: Relations: `ccomp`

This relation is universal.

4 nodes (0%) are attached to their parents as `ccomp`.

4 instances of `ccomp` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.

The following 2 pairs of parts of speech are connected with `ccomp`: <tt><a href="kpv_ikdp-pos-VERB.html">VERB</a></tt>-<tt><a href="kpv_ikdp-pos-VERB.html">VERB</a></tt> (3; 75% instances), <tt><a href="kpv_ikdp-pos-NOUN.html">NOUN</a></tt>-<tt><a href="kpv_ikdp-pos-VERB.html">VERB</a></tt> (1; 25% instances).


~~~ conllu
# visual-style 21	bgColor:blue
# visual-style 21	fgColor:white
# visual-style 16	bgColor:blue
# visual-style 16	fgColor:white
# visual-style 16 21 ccomp	color:blue
1	Ас	ас	ADJ	A	Case=Nom|Number=Sing	6	reparandum	_	SpaceAfter=No
2	,	,	PUNCT	CLB	_	1	punct	_	_
3	мыйке	мыйке	PRON	Pron	_	1	discourse	_	SpaceAfter=No
4	,	,	PUNCT	CLB	_	5	punct	_	_
5	ас	ас	ADJ	A	Case=Nom|Number=Sing	6	amod	_	_
6	муас	му	NOUN	N	Case=Ill|Number=Sing|Number[psor]=Sing|Person[psor]=3	7	obl	_	_
7	рӧдиттьыны	рӧдиттьыны	VERB	V	VerbForm=Inf	8	xcomp	_	Lang=Mixed
8	мӧдэма	мӧдны	VERB	V	Evident=Nfh|Mood=Ind|Person=1|Tense=Past|VerbForm=Fin	0	root	_	SpaceAfter=No
9	,	,	PUNCT	CLB	_	10	punct	_	_
10	абу	абу	PART	Pcle	Polarity=Neg	11	aux	_	_
11	мӧдэма	мӧдны	VERB	V	Evident=Nfh|Mood=Ind|Person=3|Tense=Past|VerbForm=Fin	8	conj	_	SpaceAfter=No
12	,	,	PUNCT	CLB	_	13	punct	_	_
13	оз	оз	VERB	V	Mood=Ind|Person=3|Polarity=Neg|Tense=Pres|VerbForm=Fin	16	reparandum	_	SpaceAfter=No
14	,	,	PUNCT	CLB	_	15	punct	_	_
15	абу	абу	PART	Pcle	Polarity=Neg	16	aux	_	_
16	мӧдэма	мӧдны	VERB	V	Evident=Nfh|Mood=Ind|Person=3|Tense=Past|VerbForm=Fin	8	conj	_	_
17	тытэн	тытэн	ADV	Adv	_	16	obl	_	SpaceAfter=No
18	,	,	PUNCT	CLB	_	19	punct	_	_
19	Из	из	PROPN	N	Case=Nom	21	obl	_	_
20	сайын	сайын	ADP	Po	Case=Ine|Number=Sing	19	case	_	_
21	рӧдиттьынысэ	рӧдиттьыны	VERB	V	VerbForm=Inf	16	ccomp	_	Lang=Mixed|SpaceAfter=No
22	.	.	PUNCT	CLB	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 10 ccomp	color:blue
1	Супругаа	супруга	NOUN	N	Case=Nom|Number=Sing|Number[psor]=Sing|Person[psor]=1	7	nsubj	_	Lang=Mixed|SpaceAfter=No
2	,	,	PUNCT	CLB	_	3	punct	_	_
3	кудз	кудз	ADV	Adv	_	4	advmod	_	_
4	висьтооны	висьтооны	VERB	V	VerbForm=Inf	7	parataxis	_	SpaceAfter=No
5	,	,	PUNCT	CLB	_	6	punct	_	_
6	абу	абу	PART	Pcle	Polarity=Neg	7	aux	_	_
7	оленевод	оленевод	NOUN	N	Case=Nom|Number=Sing	0	root	_	Lang=Mixed
8	да	да	PART	Pcle	_	7	discourse	_	Lang=Mixed|SpaceAfter=No
9	,	,	PUNCT	CLB	_	10	punct	_	_
10	приведитчис	приведитчыны	VERB	V	Mood=Ind|Person=3|Tense=Past|VerbForm=Fin	7	ccomp	_	Lang=Mixed
11	кольччыны	кольччыны	VERB	V	VerbForm=Inf	10	xcomp	_	SpaceAfter=No
12	.	.	PUNCT	CLB	_	7	punct	_	_

~~~


