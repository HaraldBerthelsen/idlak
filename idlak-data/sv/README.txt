A first shot at making Swedish language files for Idlak.

The accent dir is called "rs" for "riks-svenska", "standard Swedish"

Files in this dir:

nrules-default.xml Modified for Swedish
posset-default.xml Find similar examples for Swedish (from tagged corpus? or from synthesis manuscript?)
pbreak-default.xml No changes needed for Swedish, I think
postags-default.xml Is it handwritten, or trained on some data? How? Needs to be modified for Swedish.

Files in rs:
ccart-default.xml Cart tree for LTS. How is it trained?
config.xml Probably no change needed
lexicon-default.xml - link to lexicon-cmu0.7a.xml
cex-default.xml Phones and postags need to be updated for Swedish
fex-default.xml Phones need to be updated for Swedish
qset-default.xml Phones and some features need to be updated for Swedish
cex-hts.xml Phones, kaldiphones, and postags need to be updated for Swedish. What are kaldiphones?
lexicon-cmu0.7a.xml Format the nst lexicon like this
sylmax-default.xml Phones need to be updated for Swedish


TODO
phoneset nst
kaldiphones?
update xml files

format lexicon sv_lex_dump_160323.xml
train lts sv_lts.xml

tagset nst
tagged words examples
postags default - train or write?
