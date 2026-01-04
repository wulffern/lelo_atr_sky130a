
#- Core makefile provides the following commands:
# -----------------------------------------------------------
# gds: generate gds/<CELL>.gds
# cdl: generate cdl/<CELL>.cdl
# xsch: generate xsch/<CELL>.spice
# lvs: Check cdl/<CELL>.cdl versus ../design/<LIB>/<CELL>.mag
# lpe: Extract parasitics lpe/<CELL>.spi
# drc: Run design rule checks on ../design/<LIB>/<CELL>.mag
# -----------------------------------------------------------

PREFIX=LELOATR_
LIB=LELO_ATR_SKY130A
CELL=LELO_ATR

#- Provide cells you want to check for the lvsall drcall commands
CELLS = LELO_ATR

#- Which libraries to make SVG files for
SVGLIBS=LELO_ATR_SKY130A

#- Provide cells you want to check for the lvsall drcall commands
CELLS= PCH_2CTOP PCH_4CTOP PCH_8CTOP PCH_12CTOP NCH_2CTOP NCH_4CTOP NCH_8CTOP NCH_12CTOP

include ../tech/make/core.make
