# Curated_news_feed
Create	a	curated	news	feed
You	are	building an	AI	curated news	feed for	customers	which	shows	only	the	new	articles	that	
are	relevant	to	the	customer	based	on	the	stocks	he	has	invested	in.
Let’s	assume	a	customer	has	invested	in	Facebook,	Amazon,	Apple,	Netflix,	Tesla,	Cisco,	Google,
Baidu,	Alibaba	and	Tencent.	
We	want	you	to	come	up	with	a	program	in	Python	or	R	which	will	get	data	from	leading	news	
publication	and	show	only	the	news	articles	which	are	related	to	the	above	set	of	stocks:
You	need	to	start	with	the	following	2	data	sources:
- https://www.marketwatch.com/rss/
- https://www.nasdaq.com/services/rss.aspx
But	welcome	to	use	additional	data	sources	like	Twitter,	Wall	Street	journal,	etc.
1. Output	should	be	a	feed	of	news	article	with	following	details	for	each	article:
a. Headline
b. News	URL
c. Summary
d. Labels
e. Theme
f. Relevance
g. Any	additional	metrics	you	can	give	like	sentiment,	etc
2. Ensure	these	are	financial	news	and	not	generic	marketing	/	product	launches	for	these	
stocks
3. Remove	duplicates	and	similar	articles	from	different	sources.
4. Label	each	news	article	with	its	stock	symbol	so	that	these	can	be	easily	filtered	in	the	
system.	
a. For	ex:	All	news	on	Apple	need	to	have	a	label	– AAPL	(which	is	its	stock	symbol)
b. A	news	article	on	multiple	companies	need	to	be	labeled	
c. Stock	symbols	of	each	can	be	found	on	Google
5. Identify	key	theme	for	every	article	so	that	this	can	be	highlighted as	well
6. Track	relevance	of	the	article	for	the	stock	(on	a	scale	of	0	to	100%)
Note:	
1. You	will	need	to	use	various	text	analytics	algorithms	to	ensure	feed	is	curated	and	
usable.
2. Feel	free	to	use	any	ML	models	and	solutions	available	publicly
