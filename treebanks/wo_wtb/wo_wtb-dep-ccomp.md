---
layout: base
title:  'Statistics of ccomp in UD_Wolof-WTB'
udver: '2'
---

## Treebank Statistics: UD_Wolof-WTB: Relations: `ccomp`

This relation is universal.

733 nodes (2%) are attached to their parents as `ccomp`.

727 instances of `ccomp` (99%) are left-to-right (parent precedes child).
Average distance between parent and child is 6.04365620736699.

The following 7 pairs of parts of speech are connected with `ccomp`: <tt><a href="wo_wtb-pos-VERB.html">VERB</a></tt>-<tt><a href="wo_wtb-pos-VERB.html">VERB</a></tt> (637; 87% instances), <tt><a href="wo_wtb-pos-VERB.html">VERB</a></tt>-<tt><a href="wo_wtb-pos-NOUN.html">NOUN</a></tt> (59; 8% instances), <tt><a href="wo_wtb-pos-VERB.html">VERB</a></tt>-<tt><a href="wo_wtb-pos-PRON.html">PRON</a></tt> (23; 3% instances), <tt><a href="wo_wtb-pos-VERB.html">VERB</a></tt>-<tt><a href="wo_wtb-pos-PROPN.html">PROPN</a></tt> (5; 1% instances), <tt><a href="wo_wtb-pos-VERB.html">VERB</a></tt>-<tt><a href="wo_wtb-pos-NUM.html">NUM</a></tt> (4; 1% instances), <tt><a href="wo_wtb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="wo_wtb-pos-VERB.html">VERB</a></tt> (3; 0% instances), <tt><a href="wo_wtb-pos-VERB.html">VERB</a></tt>-<tt><a href="wo_wtb-pos-ADV.html">ADV</a></tt> (2; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 7 ccomp	color:blue
1	Mu	mu	PRON	PRON	Case=Nom|Number=Sing|Person=3|PronType=Prs	2	nsubj	2:nsubj	_
2	nangu	nangu	VERB	VERB	Mood=Ind|VerbForm=Fin	0	root	0:root	_
3	te	te	CCONJ	CONJ	_	4	cc	4:cc	_
4	seere	seere	VERB	VERB	Mood=Ind|VerbForm=Fin	2	conj	2:conj	_
5	ni	ni	SCONJ	COMP	_	7	mark	7:mark	SpaceAfter=No
6	:	:	PUNCT	COLON	_	7	punct	7:punct	_
7	Amul	am	VERB	VERB	Mood=Ind|Number=Sing|Person=3|Polarity=Neg|VerbForm=Fin	4	ccomp	4:ccomp	_
8	jenn	benn	DET	DET	Definite=Ind|NounClass=Wol4|Number=Sing|PronType=Art	9	det	9:det	_
9	Yàlla	Yàlla	PROPN	NAME	_	7	obj	7:obj	_
10	ju	bu	PRON	PRON	NounClass=Wol4|Number=Sing|Person=3|PronType=Rel	12	nsubj	12:nsubj	_
11	dul	di	AUX	COP	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Neg|Tense=Pres|VerbForm=Fin	12	cop	12:cop	_
12	Allaa	Allaa	PROPN	NAME	_	9	acl:relcl	9:acl:relcl	SpaceAfter=No
13	.	.	PUNCT	PERIOD	_	2	punct	2:punct	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 6 ccomp	color:blue
1	Loolu	boobu	PRON	PRON	Deixis=Prox|DeixisRef=2|NounClass=Wol7|Number=Sing|PronType=Dem	3	nsubj	3:nsubj	_
2	a	a	AUX	INFL	FocusType=Subj|Mood=Ind	3	aux	3:aux	_
3	taxoon	tax	VERB	VERB	Mood=Ind|Tense=Past|VerbForm=Fin	0	root	0:root	_
4	ñu	mu	PRON	PRON	Case=Nom|Number=Plur|Person=3|PronType=Prs	6	nsubj	6:nsubj	_
5	di	di	AUX	COP	Aspect=Imp|Mood=Ind|Tense=Pres|VerbForm=Fin	6	cop	6:cop	_
6	réew	réew	NOUN	NOUN	_	3	ccomp	3:ccomp	_
7	yu	bu	PRON	PRON	NounClass=Wol8|Number=Plur|Person=3|PronType=Rel	8	nsubj	8:nsubj	_
8	naat	naat	VERB	VERB	Mood=Ind|VerbForm=Fin	6	acl:relcl	6:acl:relcl	SpaceAfter=No
9	.	.	PUNCT	PERIOD	_	3	punct	3:punct	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 8 ccomp	color:blue
1	Nu	mu	PRON	PRON	Case=Nom|Number=Plur|Person=1|PronType=Prs	2	nsubj	2:nsubj	_
2	naan	naan	VERB	VERB	Mood=Ind|VerbForm=Fin	0	root	0:root	_
3	lu	bu	PRON	PRON	NounClass=Wol7|Number=Sing|Person=3|PronType=Rel	8	nsubj	8:nsubj	_
4	fi	fi	ADV	ADV	Deixis=Prox|NounClass=Wol11|PronType=Dem	6	advmod	6:advmod	_
5	di	di	AUX	COP	Aspect=Imp|Mood=Ind|Tense=Pres|VerbForm=Fin	6	cop	6:cop	_
6	lu	bu	PRON	PRON	NounClass=Wol7|Number=Sing|Person=3|PronType=Rel	3	acl:relcl	3:acl:relcl	_
7	baax	baax	VERB	VERB	Mood=Ind|VerbForm=Fin	6	acl:relcl	6:acl:relcl	_
8	moom	moom	PRON	PRON	Number=Sing|Person=3|PronType=Prs	2	ccomp	2:ccomp	_
9	la	la	AUX	COP	Mood=Ind|Number=Sing|Person=3|VerbForm=Fin	8	cop	8:cop	SpaceAfter=No
10	,	,	PUNCT	COMMA	_	12	punct	12:punct	_
11	du	di	AUX	COP	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Neg|Tense=Pres|VerbForm=Fin	12	cop	12:cop	_
12	keneen	beneen	PRON	PRON	NounClass=Wol1|Number=Sing|PronType=Ind	8	parataxis	8:parataxis	SpaceAfter=No
13	,	,	PUNCT	COMMA	_	15	punct	15:punct	_
14	du	di	AUX	COP	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Neg|Tense=Pres|VerbForm=Fin	15	cop	15:cop	_
15	feneen	feneen	ADV	ADV	NounClass=Wol11|PronType=Ind	8	parataxis	8:parataxis	SpaceAfter=No
16	.	.	PUNCT	PERIOD	_	2	punct	2:punct	_

~~~


