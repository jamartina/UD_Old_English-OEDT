This annotation is part of a long-term research project in Old English linguistics and lexicography characterised by the use of lexical databases, which are compiled and annotated with manual techniques as well as computational procedures and resources. In its present state, the Nerthus Project is annotating Old English with Universal Dependencies.
Against this background, this treebank contains 38,140 lines that annotate around 25,000 Old English words. 
The texts have been retrieved from Martín Arista, Javier (ed.), Sara Domínguez Barragán, Luisa Fidalgo Allo, Laura García Fernández, Yosra Hamdoun Bghiyel, Miguel Lacalle Palacios, Raquel Mateo Mendaza, Carmen Novo Urraca, Ana Elvira Ojanguren López, Esaúl Ruíz Narbona, Roberto Torre Alonso & Raquel Vea Escarza. 2023. ParCorOEv3. An open access annotated parallel corpus Old English-English. Nerthus Project, Universidad de La Rioja, www.nerthusproject.com. 
The choice of texts, which includes both vernacular prose (chronicles, homilies, religious and legal texts) and Latin translations (the Gospel) include Orosius (OROS), St. Mark’s Gospel (MARK), Ælfric ́s Catholic Homilies I (ÆHOM1), The Anglo-Saxon Chronicle A (ASCA), and the Laws (LAWS). 
The treebank is a revised version of the manual annotation carried our for assessing the performance of a computational model based on a Natural Langauge Processing library, which was the main aim of Domínguez Barragán, S. 2024. Universal Dependencies of Old English. Automatic Parsing with a Computational Model of Language. PhD Dissertation, Department of Modern Languages, University of La Rioja. Supervised by J. Martín Arista and A. E. Ojanguren López. 
Apart from addressing some local issues, the revised treebank does not consider multi-word tokens. Contrations with the negative word ne attached to pronouns, verbs and adverbs are dealt with by means of Polarity=Neg, marked in the FEATS column. 
The lemma list is based on Martín Arista, J. et al. 2011. Nerthus. A lexical database of Old English. The initial headword list 2007-2009. Working Papers in Early English Lexicology and Lexicography 1. Nerthus Project. Universidad de La Rioja.
Comment lines include a translation into Present-Day English, as can be seen in the example.

# global.columns ID FORM LEMMA UPOSTAG XPOSTAG FEATS HEAD DEPREL DEPS MISC
	# sent_id = LAWSAF.001.11(5).001.
		# text = Gif borenran wifmen ðis gelimpe, weaxe sio bot be ðam were.
			# text_en = If this outrage is done to a woman of higher birth, the compensation to be paid shall increase according to the wergeld.
				1	Gif	gif (CONJ)	SCONJ	subordinating conjunction	Uninflected=Yes	5	mark	_	_
				2	borenran	beran(ge)	ADJ	adjective	Tense=Past|Uninflected=Yes|VerbForm=Part|Case=Dat|Gender=Masc|Number=Sing	3	amod	_	_
				3	wifmen	wīfmann	NOUN	common noun	Case=Dat|Gender=Masc|Number=Sing	5	orphan	_	_
				4	ðis	ðes-ðēos-ðis (DEM)	DET	demonstrative	Case=Nom|Gender=Neut|Number=Sing|PronType=Dem	5	det	_	_
				5	gelimpe	gelimp 	NOUN	common noun	Case=Nom|Gender=Neut|Number=Sing	7	advcl	_	SpaceAfter=No
				6	,	,	PUNCT	punctuation	Uninflected=Yes	5	punct	_	_
				7	weaxe	weaxan(ge)	VERB	main verb	Mood=Sub|Number=Sing|Tense=Pres|VerbForm=Fin	0	root	_	_
				8	sio	se-sēo-ðæt (DEM)	DET	demonstrative-article	Case=Nom|Gender=Fem|Number=Sing|PronType=DemArt	9	det	_	_
				9	bot	bōt 	NOUN	common noun	Case=Nom|Gender=Fem|Number=Sing	7	nsubj	_	_
				10	be	be (PREP)	ADP	adposition	Uninflected=Yes	12	case	_	_
				11	ðam	se-sēo-ðæt (DEM)	DET	demonstrative-article	Case=Dat|Gender=Masc|Number=Sing|PronType=DemArt	12	det	_	_
				12	were	wer ‘the legal money-equivalent of a person’s life, a man’s legal value’	NOUN	common noun	Case=Dat|Gender=Masc|Number=Sing	7	obl	_	SpaceAfter=No
				13	.	.	PUNCT	punctuation	Uninflected=Yes	7	punct	_	_
				
						
The team and the funding of the project can be found at https://www.nerthusproject.com/about-us.

You may also be interested in the new version of the Nerthus database, an interface of textual, lexicographical and secondary sources of Old English: Martín Arista, Javier (ed.), Sara Domínguez Barragán, Luisa Fidalgo Allo, Laura García Fernández, Yosra Hamdoun Bghiyel, Miguel Lacalle Palacios, Raquel Mateo Mendaza, Carmen Novo Urraca, Ana Elvira Ojanguren López, Esaúl Ruíz Narbona, Roberto Torre Alonso, Marta Tío Sáenz & Raquel Vea Escarza. 2024. Nerthusv5. Interface of textual, lexicographical and secondary sources of Old English. Nerthus Project, Universidad de La Rioja, www.nerthusproject.com. 