# $FreeBSD$

COMMENT=	Fonts and support for typesetting Greek
TEXMF_CATEG=	langgreek

TEXMF_DIRS=	\
	fonts/afm/public/gfsbaskerville/ fonts/afm/public/gfsporson/ \
	fonts/afm/public/ibygrk/ fonts/afm/public/kerkis/ \
	fonts/enc/dvips/cbfonts/ fonts/enc/dvips/gfsbaskerville/ \
	fonts/enc/dvips/gfsporson/ fonts/enc/dvips/ibygrk/ \
	fonts/enc/dvips/kerkis/ fonts/opentype/public/gfsbaskerville/ \
	fonts/opentype/public/gfsporson/ fonts/source/public/cbfonts/ \
	fonts/source/public/ibygrk/ fonts/source/public/levy/ \
	fonts/source/public/yannisgr/ \
	fonts/tfm/public/cbfonts/ fonts/tfm/public/gfsbaskerville/ \
	fonts/tfm/public/gfsporson/ fonts/tfm/public/ibygrk/ \
	fonts/tfm/public/kerkis/ fonts/tfm/public/levy/ \
	fonts/tfm/public/yannisgr/ fonts/type1/public/cbfonts/ \
	fonts/type1/public/gfsbaskerville/ fonts/type1/public/gfsporson/ \
	fonts/type1/public/ibygrk/ fonts/type1/public/kerkis/ \
	fonts/vf/public/gfsbaskerville/ \
	fonts/vf/public/gfsporson/ fonts/vf/public/kerkis/ \
	makeindex/mkgrkindex/ tex/generic/babel-greek/ tex/generic/ibygrk/ \
	tex/generic/levy/ tex/xelatex/xgreek/

TEXMF_DIRS_LATEX=	\
	begingreek betababel cbfonts-fd gfsbaskerville gfsporson \
	greek-fontenc greek-inputenc greekdates greektex greektonoi \
	ibycus-babel kerkis lgreek teubner

TEXMF_DOCDIRS_FONTS=	cbfonts-fd gfsbaskerville gfsporson greektex kerkis
TEXMF_DOCDIRS_LATEX_EXCLUDE=	${TEXMF_DOCDIRS_FONTS}

.include "${.CURDIR}/../texlive-texmf-all/bsd.texmf.mk"
