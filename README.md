# Autoexec
CSGO Autoexec !

// Viewmodel

viewmodel_fov "68"
viewmodel_offset_x "2.500000"
viewmodel_offset_y "0"
viewmodel_offset_z "-1.500000"
viewmodel_presetpos "3"
cl_bob_lower_amt "0"
cl_bobamt_lat "0"
cl_bobamt_vert "0"
cl_bobcycle "0.98"
cl_viewmodel_shift_left_amt "0"
cl_viewmodel_shift_right_amt "0"
bind "RIGHTARROW" "toggle cl_righthand 0 1"

// Maussettings

m_rawinput "1"
m_mouseaccel2 "0"
m_mouseaccel1 "0"
m_customaccel "0"
m_mousespeed "0"

// Radar

cl_radar_scale "0.55"
cl_radar_rotate "1"
cl_radar_always_centered "0"
cl_radar_square_with_scoreboard "1"
cl_radar_icon_scale_min "1"
r_drawtracers_firstperson "0"

// HUD 

gameinstructor_enable "0"
cl_showhelp "0"
cl_autohelp "0"
cl_disablefreezecam "1"
cl_teammate_colors_show 2
cl_hud_bomb_under_radar "1"
cl_showloadout "1"
cl_teamid_overhead_always 1

// Buyscript

bind "DOWNARROW" "buy vesthelm"
bind "LEFTARROW" "buy defuser"
bind "UPARROW" "buy vest"
 
bind "KP_INS" "buy molotov; buy incgrenade"
bind "KP_END" "buy hegrenade"
bind "KP_DOWNARROW" "buy flashbang"
bind "KP_PGDN" "buy smokegrenade"
bind "KP_LEFTARROW" "buy ak47; buy m4a1"
bind "KP_5" "buy awp"
bind "KP_RIGHTARROW" "buy famas; buy galilar"
bind "KP_HOME" "buy tec9; buy fiveseven"
bind "KP_UPARROW" "buy p250"
bind "KP_PGUP" "buy deagle"
bind "HOME" "toggleconsole"
bind "KP_PLUS" "buy p90"
bind "KP_ENTER" "buy ump45"
bind "KP_DEL" "buy decoy"

bind "MOUSE4" "use weapon_molotov; use weapon_incgrenade"
bind "MWHEELUP" "use weapon_flashbang"
bind "MWHEELDOWN" "use weapon_smokegrenade"

// Crosshair

cl_crosshair_drawoutline "1"
cl_crosshair_dynamic_maxdist_splitratio "0.35"
cl_crosshair_dynamic_splitalpha_innermod "1"
cl_crosshair_dynamic_splitalpha_outermod "0.5"
cl_crosshair_dynamic_splitdist "7"
cl_crosshair_outlinethickness "1"
cl_crosshair_sniper_show_normal_inaccuracy "0"
cl_crosshair_sniper_width "1"
cl_crosshairalpha "230"
cl_crosshaircolor "5"
cl_crosshaircolor_b "000"
cl_crosshaircolor_g "000"
cl_crosshaircolor_r "255"
cl_crosshairdot "0"
cl_crosshairgap "-1"
cl_crosshairgap_useweaponvalue "0"
cl_crosshairscale "1000"
cl_crosshairsize "1"
cl_crosshairstyle "4"
cl_crosshairthickness "0.5"
cl_crosshairusealpha "1"
cl_fixedcrosshairgap "-2"

// Netsettings

rate "786432"
cl_cmdrate "128"
cl_updaterate "128"
cl_interp_ratio "1"
cl_interp "0"
cl_lagcompensation "1"
cl_predict "1"
cl_predictweapons "1"

// Sound

volume 0.16
snd_mixahead "0.05"
snd_musicvolume "0"
voice_enable "1"
voice_scale "0.6"
lobby_voice_chat_enabled "0"

// Custom Settings

mm_dedicated_search_maxping "50"
cl_autowepswitch 0
func_break_max_pieces 0

net_graph "1"
net_graphheight "9999"
alias "+scorenet" "+showscores; net_graphheight 0"
alias "-scorenet" "-showscores; net_graphheight 9999"
bind "TAB" "+scorenet"

alias displaydamage "displaydamage_on"
alias displaydamage_on "con_filter_text Damage Given To; con_filter_text_out Player:; con_filter_enable 2; developer 1; playvol buttons\blip1 0.5; alias displaydamage "displaydamage_off""
alias displaydamage_off "con_filter_enable 0; developer 0; playvol buttons\blip2 0.5; alias displaydamage "displaydamage_on""
bind "f5" "displaydamage"

fps_max "165"

// Startoptionen
// -exec autoexec.cfg -novid -language bananagaming -high -threads 4 -freq 75 -refresh 75 -tickrate 128

host_writeconfig
