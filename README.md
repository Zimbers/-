#блок Эла
define z = Character(_('Девушка'), color='#0bbfc5')
define s = Character(_('Ela'), color='#0bbfc5')
# хз потом новые будут (наверное)
define m = Character(_('Me'), color='#00ff4c')
define n = Character(None, kind=nvl)
#звуки (под вопросом) 
define audio.sound_vstal = 'sound/bed-sheet-movement_mjjnbdvo.mp3'
define audio.sound_krovat = 'sound/390236-phone-retro_corded-lift-02.mp3'
define audio.sound_zvonok = 'sound/z_uko_ye-effekty-z_onok-telefona.mp3'
define audio.sound_helcok = 'sound/helcok.mp3'
define audio.sound_voda = 'sound/water-faucet.mp3'
#музыка новая (без ап)
define audio.mus_poezdka = 'music/AcousticGuitar1.mp3'
define audio.mus_slow = 'music/CryinInMyBeer.mp3'
define audio.mus_haip = 'music/veselaya muzika na fon.mp3'
define audio.mus_magazin = 'music/dxnzxl-essence.mp3'
define audio.mus_musli = 'music/без ап — Спокойная музыка раскаяние (www.lightaudio.ru).mp3'
define audio.mus_konzert = 'music/YouTube - Музыка без авторских прав.mp3'
#спрайты с анимацией ( на будущее :з )
 
#спрайты Ela устаревшие 
image logo = 'renpy logo.png'
image Ela sad = 'images/codel/codel Ela sad.png.'
image Ela smile = 'images/codel/codel Ela smile.png.'
image Ela smoh = 'images/codel/codel Ela smoh.png.'
image Ela surp = 'images/codel/codel Ela surp.png.'
image Ela upset = 'images/codel/codel Ela upset.png.'
image Ela winter = 'images/codel/codel Ela winter.png.'

#игра
label start:
    scene bg uni
    with dissolve
    show Ela smoh:
        xalign 0.75
        yalign 1.0
    n ""
    m ""
 
return
