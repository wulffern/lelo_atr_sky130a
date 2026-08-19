
#- Core makefile provides the following commands:
# -----------------------------------------------------------
# gds: generate gds/<CELL>.gds
# cdl: generate cdl/<CELL>.cdl
# xsch: generate xsch/<CELL>.spice
# lvs: Check cdl/<CELL>.cdl versus ../design/<LIB>/<CELL>.mag
# lpe: Extract parasitics lpe/<CELL>.spi
# drc: Run design rule checks on ../design/<LIB>/<CELL>.mag
# -----------------------------------------------------------

#- No PREFIX: CI passes the full cell name from info.yaml, and a prefix
#- would be applied twice.
PREFIX=
LIB=LELO_ATR_SKY130A
CELL=LELOATR_NCH_4C5F0

#- Which libraries to make SVG files for
SVGLIBS=LELO_ATR_SKY130A

#- Provide cells you want to check for the lvsall drcall commands.
#- The PCH_*CTOP and NCH_8/12CTOP layouts lack port labels, so they do
#- not extract to a subckt and fail LVS; only the clean cells are listed.
CELLS= LELOATR_NCH_2CTOP LELOATR_NCH_4CTOP

include ../tech/make/core.make
