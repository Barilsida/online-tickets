
# Skenari 2: Kontrollimi i biletave

## Rrjedha normale e ngjarjeve

Klajdi ka blerë një biletë për 2 persona për në teatër (për vete dhe
për Klementin). Këtë biletë e ka ruajtur në celularin e tij në format
PDF.

Te dera e teatrit është Adriani i cili bën kontrollin e biletave.
Adriani ka një telefon ku ka instaluar aplikacionin e kontrollit të
biletave. Pasi Adriani zgjedh aktivitetin për të cilin do bëjë
kontrollin e biletave (shfaqjen e teatrit), aplikacioni aktivizon
kamerën dhe kalon në gjëndje skanimi.

Klajdi shfaq në telefonin e tij biletën, e cila ka edhe kodin 2D, dhe
Adriani e skanon me telefonin e tij. Aplikacioni lexon kodin 2D, e
deshifron, verifikon që bileta është e saktë, dhe nxjerr një mesazh
konfirmimi që kjo është një biletë e vlefshme për 2 persona. Adriani e
lejon Klajdin dhe Klementin të futen në teatër.

Ndërkohë, aplikacioni e ka shënuar si të përdorur biletën që sapo
verifikoi, në mënyrë që mos të përdoret më për herë të dytë.

## Rrjedhat alternative

### Bileta nuk është e vlefshme

Në rast se bileta e paraqitur është për një datë ose për një aktivitet
tjetër, aplikacioni nxjerr një mesazh me të kuqe që thotë se bileta
nuk është e vlefshme.  Po ashtu edhe nëse bileta është e ripërdorur
ose e fallsifikuar.

Në të gjitha rastet e pavlefshme, aplikacioni njofton edhe arsyen se
pse bileta është e pavlefshme (p.sh. data/ora e gabuar, aktiviteti i
gabuar, biletë e ripërdorur, biletë e panjohur/fallsifikuar, etj.)
