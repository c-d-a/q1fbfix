    == About ==

The included .pak files act as patches for Quake content. Their main purpose is to fix erroneous fullbright pixels in the art assets.

Quake palette contains some colors that are supposed to be unaffected by lighting. Largely due to GLQuake's lack of support for such "fullbrights", a number of incorrectly converted textures made their way into user maps and mods. Though not apparent to their authors at the time of release, with modern source ports these flaws become obvious.

While it's usually possible to disable fullbrights completely (e.g. gl_fullbrights 0) - thus fully preserving "artistic intent" - it comes at a cost of dull unlit flames and projectiles, as well as some other unfortunate side effects. Instead, overriding only the offending assets allows for the best of both worlds.


    == Requirements ==

The patches work by overriding models and textures, of which the latter requires an engine with external texture support. Most source ports this side of Y2K have it.


    == Installation ==

Put the provided .pak files in the respective mods' folders. That's about it.

The files are named so as to minimize conflicts, but in case a .pak file with the same name already exists, rename the new one as next sequentially. There should be no gaps in numbering and higher number means higher priority.

If you just dump maps into id1 folder whenever possible, this way of overriding assets isn't too great, since there could be name conflicts between unrelated textures. Still, you could try putting different patches together in the same folder, but don't be surprised if eventually something won't look right.


    == Contents ==

1000cuts    "One Thousand Cuts" by sock
ac          "Adamantine Cruelty" by Vondur
ad          "Arcane Dimensions" by sock et al. (v1.70p1)
admaps      custom AD-based maps
    pak0 contains fixed-up skins for ADv1.70p1 but no map texture overrides
    pak1 contains overrides for:
        37_hcm1             "37th Relic Retrieval" by Mazu
        ad_e3m2             "The Faults Within" by mfx
        ad_paradise         "Paradise Sickness" by Redfield
        ad_shadesRefinery   "The Refinery" by Shadesmaster
        ad_shamsp4          "Annihilith of Abhorration" by Shambler
        ad_shamsp5          "Symphony of Steel" by Shambler
alk12       "Fearcraft" by Kona
apsp3       "Subterranean Library" by than
arcextra    "Arcanum Bonus Maps" by Tronyn & PM
arwop       "A Roman Wilderness of Pain" by Tronyn & PM
backstein   "Backsteingotik" by sock
bbelief     "Beyond Belief" by Matthias Worch
    note: expects bbelief6_fix as pak1
cda         "Castle of the Dark Ages" by JPL
chapters    "Contract Revoked: The Lost Chapters" by Kell et al.
coagpack1   "Coagula Contest 1"
coagpack2   "Coagula Contest 2"
coagpack3   "Coagula Mappack 3"
coagula     "Coagula 1-3" by Tim Elek
contract    "Contract Revoked" by Kell
copper      "Copper Quake" mod by Lunaran
czg07       "Insomnia" by CZG
dis_sp6     "Ruined Nation" by distrans
dm4jam      "DM4 Jam"
drake       pak3:   drake290111 "Drake" mod by PM
            pak4:   arcanum     "Arcanum" by Tronyn et al.
            pak5:   drysorrow   "Drysorrow" by Tronyn
            pak6:   sludge      "Sludge Factory" by Tronyn
drakebeta   "Drake" mod by PM
    beta is more recent than 290111 release, but isn't 100% backward compatible
    unlike 290111, no maps explicitly target drakebeta
e1m5quotha  "Gloomier Keep" by Kell
e2m5rmx     "The Lizard's Trance" by rj
egypt       "Egyptian Rhapsody!" by Drew & Hrimfaxi
fallen      "Fallen from Grace" by sock
flesh       "Carved in Flesh" by Kona
fmb_bdg2    "Binn, Dunne, Gorne" by Mike Woodham
gmsp3       "Day of the Lords" by GlassMan
gth         "Gate to Hell" by JPL
guncotton   "Guncotton" by Kona
haunting    "Autumn Haunting" by Kona
heresp5     "Dismal Signal" by Heresy
hipnotic    "Scourge of Armagon" by Hipnotic Interactive
hrim_sp3    "Breakfast at Twilight" by Hrimfaxi
hrim_sp4    "For Love of Evil" by Hrimfaxi
hwjam2018   "Halloween Jam"
hwjam2019   "Halloween Jam 2"
id1         "Quake" by id Software
ikspq5      "The Secret Installation" by Iikka Keränen
jam1        "Honey Jam"
jam2        "ikblue/ikwhite Jam"
jam3        "Zerstörer Jam"
jam5        "Qonquer Jam"
jam6        "Fire and Brimstone Jam"
jam7        "Back to Base Jam"
jam8        "Film Noir Jam"
jam9        "Contract Revoked Jam"
jamx        "Insomnia Jam"
jumpjam     "January Jump Jam"
jumpmod     "Jump Boots" mod and "Triune Discovery" by JCR
kaahoo      "Castle Kaahoo" by sock
koohoo      "The Castle of Koohoo" by Vondur
lunsp1      "Concentric Devastation" by Lunaran
marcher     "The Marcher Fortress" by Kinn
marine      "Ultramarine" by Kona
masque      "The Masque of Red Death" by Tronyn
mfxsp17     "Mainframe Mayhem" by mfx
movplan2    "Shifting Planes of Existence" by Spipper
nastrond    "Nastrond" by Vondur
ne_lend     "The Living End / Elder World Waystation" by necros
ne_ruins    "The Altar of Storms" by necros
ne_sp06     "Once Upon Atrocity" by necros
ne_sp09     "Dawn of Eternity" by necros
ne_tower    "Moldy Tower" by necros
nehahra     pak5:   "Nehahra" by Mindcrime et al.
            pak6:   "The Tides of War" by Tim Elek
nehmovie    "The Seal of Nehahra" by Mindcrime et al.
nihilore    "Nihilore" by Kona
nsoe        "Soul of Evil: Indian Summer" by Tronyn et al.
oms3        "Cataractnacon / Zeangala" by Orl
oum         "Operation: Urth Majik" by Fat Controller et al.
quoth       "Quoth" mod by Preach, necros & Kell (v2.2)
rapture     "Rapture" by Tronyn & Kona
red777      "Red 777" by Kell
retrojam1   "Medieval RetroJam"
retrojam2   "Fantasy Brick Cities in the Skies RetroJam"
retrojam4   "Elder World Retro Jam"
retrojam6   "Egyptian Retro Jam"
ritualsp    "Dark Ritual" by Tyrann & negke
rmx-pack    "Remix Map Pack 2008"
rogue       "Dissolution of Eternity" by Rogue Entertainment
rrp         "Rubicon Rumble Pack" by Hrimfaxi, ijed & mfx
sksp2       "Conference of the Shamblers" by skacky
slave       "Slave to a Machine" by RickyT23
soe         "Soul of Evil" by Tronyn et al.
smej        "Menetettyjen Valtakunta" (Realm of the Lost)
swjam       "Sewer Jam"
ter_shib    "Ter Shibboleth" by Orl
thehand     "(Don't Bite) The Hand That Feeds You" by RickyT23
travail     "Travail" by distrans et al.
unf         "Unforgiven" by Tronyn & PM
uwjam       "Underwater Jam"
warp        "Warp Spasm" by ijed
    pak3 contains all necessary skins and texture overrides (and an empty sound)
    pak4 contains optional darker reskins
wicked      pak5:   "Something Wicked This Way Comes" by Tronyn
            pak6:   "Nyarlathotep" by Tronyn
            pak7:   "Ter Shibboleth, Part 2" by Orl
xmas2017    pak0:   skins for ADv1.70p1
            pak1:   "Christmas Jam 2017"
xmas2018    pak0:   skins for ADv1.70p1
            pak1:   "Christmas Jam 2018"
xmas2019    "Christmas Jam 2019"
zendar      "The Horde of Zendar" by sock
zer         "Zerstörer" by Nihilism Unlimited
    note: expects zerend_fix as pak1


    == Notes ==

The patches are set up for additive luma (rather than masked). This means better compatibility, but also means some textures won't look good with fullbrights turned off. Don't turn them off (duh).

The following releases have been checked and do not require a patch:

5rivers, actaltrz, ad_dwoffice, ad_grendel, ad_scastle, ant, apsp1, apsp2, base_debris, barzai, bastion, binding, coag3_negke, cogs, could, czg00-04, damaul3, damaul6, digs05, dm6rmx, dm7rmx, dopa, februus, ghspch01, gmsp1, grim, honey, ikspq1-4, jam4, kellmet, mappi1, mappi2, menk, metmon, mexx1-10, mfxsp10, middle, mjb_horse, moonlite, mstalk, oblivion, oms2, retrojam3, retrojam5, rpgsp1, rubicon, rubicon2, rw3, scampsp1, sewage, simplex, solarfall, teacups, terra, tofaz, udob, xplore


    == Legal ==

These are patches to be installed next to the original files, which are not included. The contained override assets are based on these files and as such are the property of their original creators.

Most of the texture assets come completely unmodified, while models and certain select textures have been slightly modified with respect to the original artistic intent. No express permission to modify or distribute these assets was sought. Contact me if you are the author and would like me to change or exclude your assets from the package.

You are free to distribute and/or modify this package in accordance with licenses already associated with the assets.


    == Links ==

Download: https://github.com/c-d-a/q1fbfix
Discussion: http://celephais.net/board/view_thread.php?id=61775
