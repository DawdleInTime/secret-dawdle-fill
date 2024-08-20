<body style="background-color: #e4e4e4;">

<div id="db_invite" class="fc h100 dialog w100 p20" style="display:none;position:absolute;z-index:999;">
  <div class="fr w100 fig">
    <div class="fcm w100 p10" style="margin-top:auto;margin-bottom:auto;">
      <div class="fc p20 br sha" style="width: 800px;background-color: #ffffff;display: flex;flex-direction: column;justify-content: flex-end;align-items: flex-end;">
        <div class="frm w100 pb20 pt10">
          <img src="https://edusp-static.ip.tv/webinar/edusp/main_logo.png">
        </div>
        <div class="i18n-you-were-invited frm w100 sxl b toj pb20">Você foi convidado para participar desta sala de conferência</div>
        <div id="invite_panel" class="frm w100">
          <div class="frm w100">
            <div class="fc" style="width:370px;">
              <div class="fic sn pb10 sxl b toj">
                Login
              </div>
              <div class="fic fc w100">
                <div class="fic sn" style="width:300px">
                    <label for="db_invite_username ss" class="i18n-username" style="display:block;">Usuário</label>
                    <div class="bor br p5"><input class="ss pl5" id="db_invite_username" name="username" type="text" style="text-align:left;width:250px;height:30px;"></div>
                </div>
                <div class="fic sn bp5 pb5 style=" width:300px;"="">
                    <label for="db_invite_password" class="i18n-password pt5 ss" style="display:block;">Senha</label>
                    <div class="bor br p5">
                    <input class="ss pl5" id="db_invite_password" type="password" name="password" style="text-align:left;width:260px;height:30px;">
                    <span id="db_invite_showpassword" class="material-icons" style="font-size:15px;width:15px"></span>
                    </div>
                </div>
                <div id="db_inv_alert" class="alert fic sxs b tr pl10 pr10" style="min-height:16px;text-align:center;"></div>
                <div class="fic pb10">
                    <div class="fic sxs pt10 pb5">
                    <div id="db_inv_btn_login" class="i18n-enter fic bt cb tw sn" style="width:300px;height:45px;border:0px;background-color:#325794;">Entrar</div>
                    </div>
                </div>
              </div>
            </div>
            <div id="guest_panel" style="display: flex;">
              <div class="fc" style="height:220px;">
                <div class="fig bor" style="width:1px;margin-left:auto;margin-right:auto;border-color:#EEEEEE;"></div>
                <div>ou</div>
                <div class="fig bor" style="width:1px;margin-left:auto;margin-right:auto;border-color:#EEEEEE;"></div>
              </div>
              <div class="fc pb10" style="width:370px;">
                <div class="i18n-guest-login sxl b toj fic pb20">Entrar como convidado</div>
                <div id="db_inv_input_area" class="fic fc w100 pt5" style="width:300px;">
                  <div class="i18n-name ss">Nome</div>
                  <div class="bor p5 br">
                    <input id="db_invite_name" class="ss p5" type="text" style="width:300px;">
                  </div>
                </div>
                <div class="frm w100 pb5" style="min-height:31px;">
                  <div id="db_invite-alert" class="fic ss tr" style="display:none"></div>
                </div>
                <div id="db_inv_button" class="i18n-enter fic bt cb tw sn" style="width:300px;height:45px;border:0px;background-color:#325794;">Entrar</div>
              </div>
            </div>
          </div>
        </div>
        <div id="inv_panel_close_btn" class="i18n-close bt" style="right:0; display:none">Fechar</div>
      </div>
    </div>
  </div>
</div>

<div id="db_invite_logout" class="frm h100 dialog w100" style="display:none;position:absolute;z-index:999;">
  <div class="fig h100"></div>
  <div>
    <div class="fr">
      <div class="fic fc db bor p20" style="width:420px;">
        <div class="w100 tdg fc h100 p10">
          <div class="fic pt10 pl5 pr10 pb5"><img src="https://edusp-static.ip.tv/edusp/main_logo.png"></div>
          <div id="db_inv_msg" class="fic sn" style="text-align:center"></div>
        </div>
      </div>
    </div>
  </div>
  <div class="fig h100"></div>
</div>

<div id="block" style="display:none;"></div>

<div id="dialog" class="dialog" style="display: none;">
    <div id="db-connection-failure" class="frm h100 dialog" style="display: none;"><div class="fig h100"></div><div><div class="fc"><div class="fig w100" style="height:2.5%"></div><div class="fc db" style="min-width:360px;max-width:360px;">
        <div id="dbcfh" class="fc w100 pb20">
            <div class="fic material-icons pt20" style="cursor:auto;font-size:60px;color:#efce2a;">warning</div>
            <div class="i18n-attention fic n toj pt5 pb10" style="font-size:28px;">Atenção!</div>
            <div class="fic p5" style="border-bottom:1px;border-color:rgba(0,0,0,.2);border-bottom-style:solid;width:280px;height: 1px;"></div>
        </div>
        <div id="dbfb" class="fc fig" style="height:200px;max-height:200px;">
            <div class="fc fic pt" style="width:220px;">
                <div id="dbcfb-lbl" class="fic" style="text-align:center;font-size:20px;">Conexão perdida, tente novamente</div>
                <div id="dbcfb-ok" class="bt ss fic tw pt bgbl" style="margin:15px;width:159px;">OK</div>
            </div>
        </div>
    </div>
    <div class="fig w100" style="height:2.5%"></div>
    </div></div><div class="fig h100"></div></div>

  <div id="dbclosedcaption" class="frm h100 dialog" style="display: none;"><div class="fig h100 dx"></div><div><div class="fc"><div class="fig w100 dx" style="height:2.5%"></div>
  <div class="fc db" style="min-width:330px;max-width:330px;">
    <div id="dbclosedcaptionh" class="w100 tdg">
      <div class="fr pt10 pl10 pr10">
        <div class="i18n-closed-caption fig sl toj pl5">Legendas</div>
      </div>
    </div>
    <div id="dbclosedcaptionb" class="fig w100" style="padding:15px;height:260px;max-height:260px">
    <div class="ss i18n-select-the-language-to-be-spoken">Selecione o idioma que será falado.</div>
    <div class="pt5"><select id="cc-language-capture" class="p5 ss" style="width:295px;"></select></div>
    <div style="border-bottom: 1px solid #ccc;margin-bottom:15px;" class="p10"></div>
    <div class="ss i18n-select-which-language-will-be-translated-to">Selecione para qual idioma será traduzido.</div>
    <div class="ss i18n-subtitles-appeared-in-the-chosen-language">As legendas aparecerão no idioma escolhido.</div>
    <div class="pt5 pb10"><select id="cc-language-translate" class="p5 ss" style="width:295px;"></select></div>
    <div class="frm pt20">
        <div id="cc-cancel" class="i18n-cancel bt p10 pt tw bgbl ss">Cancelar</div>
        <div id="cc-activate" class="i18n-activate bt p10 pt tw bgbl ss" style="margin-left:10px;">Ativar</div>
        <div id="cc-deactivate" class="i18n-deactivate bt p10 pt tw bgbl ss" style="margin-left:10px;">Desativar</div>
    </div>
  </div>
  </div>
  <div class="fig w100 dx" style="height:2.5%"></div>
  </div></div><div class="fig h100 dx"></div></div>

  <div id="dbm" class="frm h100 dialog" style="display: none;"><div class="fig h100 dx"></div><div><div class="fc"><div class="fig w100 dx" style="height:2.5%"></div><div class="fc db" style="min-width:400px;width:400px;min-height:415px;height:415px;">
    <div id="dbmh" class="w100 tdg">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          <div class="material-icons tb pb10 nopt"></div>
          <div class="i18n-device-config fig sl pl10 toj">Configuração de Dispositivos</div>
          <div class="sxl tg dx pt">X</div>
        </div>
      </div>
    </div>
    <div id="dbmb" class="fig w100 p10" style="">
      <!-- Modal content -->
      <div id="input_devices_popup" class="modal">
        <div class="modal-content">
          <!-- span class="close">&times;</span -->
          <div id="select_source" class="hidden pb10">
            <div class="source">
              <span class="sl material-icons" style="vertical-align:middle;"></span>
              <label for="audio_src" class="i18n-audio-cam ss">Áudio:</label>
              <select id="audio_src" style="max-width:310px;"></select>
            </div>
            <div class="source">
              <span class="sl material-icons" style="vertical-align:middle;"></span>
              <label for="video_src" class="i18n-video-cam ss">Captura de Vídeo</label>
              <select id="video_src"></select>
            </div>
          </div>
          <video id="video_preview" autoplay="" muted="" style="min-height:220px;max-height:220px;max-width:380px" class="br w100"></video>
          <span class="dbm_confirm fcm p10" style="display:none;">
            <span id="dbm_cancel" class="i18n-cancel bt ss fic tw pt" style="background-color:CCCCCC;margin:5px;">Cancelar</span>
            <span id="dbm_confirm" class="i18n-confirm bt ss fic tw pt bgbl" style="margin:5px;">Confirmar</span>
          </span>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100 dx" style="height:2.5%"></div>
  </div></div><div class="fig h100 dx"></div></div>

  <div id="dbdev" class="frm h100 dialog" style="display: none;"><div class="fig h100 "></div><div><div class="fc"><div class="fig w100 " style="height:2.5%"></div><div class="fc db" style="min-width:480px;width:480px;">
    <div id="dbdevh" class="w100 tdg">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          <div class="material-icons tb pb10 nopt">video_camera_front</div>
          <div class="i18n-transmission-start fig sl pl10 toj">Transmissão</div>
          <!--div class="sxl tg dx pt">X</div -->
        </div>
      </div>
    </div>
    <div id="dbdevb" class="fig w100 p10">
      <div id="input_devices_popup" class="modal">
        <div class="modal-content">
          <div id="select_source" class="fc hidden pb10">
            <div class="source fic fcm" style="width:450px;">
              <span id="dbdev-audio-input-toggle" class="material-icons tb" style="vertical-align:middle;font-size:4rem;">toggle_on</span>
              <label for="audio_select" class="i18n-audio-input ss" style="width:110px">Entrada de Áudio</label>
              <div style="max-width:290px;min-width:290px;">
                <select id="audio_input_select" style="max-width:285px;min-width:285px;border-color:#dddddd;"></select>
              </div>
            </div>
            <div class="source fic fcm" style="width:450px;">
                <span id="dbdev-audio-output-toggle" class="material-icons tb" style="vertical-align:middle;font-size:4rem;">toggle_on</span>
                <label for="audio_output_select" class="i18n-audio-output ss" style="width:110px;min-width: 110px;">Saída de Áudio</label>
                <div style="max-width:290px;min-width:290px;">
                    <select id="audio_output_select" style="max-width:285px;min-width:285px;border-color:#dddddd;"></select>
                </div>
              </div>
            <div class="source fic fcm" style="width:450px;">
              <span id="dbdev-video-toggle" class="material-icons tb" style="vertical-align:middle;font-size:4rem;">toggle_on</span>
              <label for="video_select" class="i18n-video-cam ss" style="width:110px">Captura de Vídeo</label>
              <div style="max-width:290px;min-width:290px;">
                  <select id="video_select" style="max-width:285px;min-width:285px;border-color:#dddddd;"></select>
              </div>
            </div>
          </div>
          <div class="fc">
            <video id="webcam_preview" autoplay="" muted="" style="min-height:220px;max-height:220px;max-width:380px" class="fic bgb br w100"></video>
          </div>
          <div id="banuba-area" class="pt10 frm" style="display:none;">
            <div class="i18n-banuba-effect">Efeito:</div>
            <select id="banuba_effect"><option value="none">none</option><option value="0003_cu_Spider1_v3_b1">0003_cu_Spider1_v3_b1</option><option value="ActionunitsGrout">ActionunitsGrout</option><option value="Afro">Afro</option><option value="Background_doc">Background</option><option value="BackgroundPicture">Home Office</option><option value="BigPinkGlasses">BigPinkGlasses</option><option value="blur_bg">Background Blur</option><option value="blur_bg_2">blur_bg_2</option><option value="bokeh">bokeh</option><option value="BulldogHarlamov">BulldogHarlamov</option><option value="BurningMan2018">BurningMan2018</option><option value="CartoonOctopus">CartoonOctopus</option><option value="CubemapEverest">CubemapEverest</option><option value="Glasses">Glasses</option><option value="glasses_Banuba">glasses_Banuba</option><option value="Hipster3">Hipster3</option><option value="MonsterFactory">MonsterFactory</option><option value="PineappleGlasses">PineappleGlasses</option><option value="PoliceMan">PoliceMan</option><option value="Rorschach">Rorschach</option><option value="scene_4_faces">scene_4_faces</option><option value="Skydiver">Skydiver</option><option value="80s">Home 80s</option><option value="Apartment">Apartament</option><option value="Beauty_4">Beauty_4</option><option value="BG_Cafe_City">Cafe City</option><option value="BG_Home_Day_02">Home Day</option><option value="MorphHooligan">MorphHooligan</option><option value="MorphNeandertalLow">MorphNeandertalLow</option><option value="ScoobyDoo">ScoobyDoo</option><option value="SpaceShip">SpaceShip</option><option value="UnluckyWitch">UnluckyWitch</option><option value="Lut_Alice">Lut_Alice</option><option value="Lut_AutumnColors2">Lut_AutumnColors2</option><option value="Lut_Badgirl">Lut_Badgirl</option><option value="Lut_battona">Lut_battona</option><option value="Lut_BerlinSky">Lut_BerlinSky</option><option value="Lut_Brightsnow">Lut_Brightsnow</option><option value="Lut_BWC">Lut_BWC</option><option value="Lut_California1">Lut_California1</option><option value="Lut_Canada">Lut_Canada</option><option value="Lut_CinematicLook1">Lut_CinematicLook1</option><option value="Lut_CinematicLook2">Lut_CinematicLook2</option><option value="Lut_columbia">Lut_columbia</option><option value="Lut_England">Lut_England</option><option value="Lut_FilmLook1">Lut_FilmLook1</option><option value="Lut_Gold">Lut_Gold</option><option value="Lut_Japan">Lut_Japan</option><option value="Lut_LUX">Lut_LUX</option><option value="Lut_Paladin">Lut_Paladin</option><option value="Lut_pirate">Lut_pirate</option><option value="Lut_Polaroid690">Lut_Polaroid690</option><option value="Lut_PurpleDreams">Lut_PurpleDreams</option><option value="Lut_shine">Lut_shine</option><option value="Lut_soap">Lut_soap</option><option value="Lut_spring">Lut_spring</option><option value="Lut_Yearning">Lut_Yearning</option></select>
          </div>
          <span class="dbdev_confirm fcm pt10" style="display:none;">
            <span id="dbdev_cancel" class="i18n-cancel bt ss fic tw pt" style="background-color:CCCCCC;margin:5px;display:none;">Cancelar</span>
            <span id="dbdev_quit" class="i18n-quit-channel bt ss fic tw pt" style="background-color:CCCCCC;margin:5px;display:none;">Sair do Canal</span>
            <span id="dbdev_confirm" class="i18n-confirm bt ss fic tw pt bgbl" style="margin:5px;">Confirmar</span>
          </span>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100 " style="height:2.5%"></div>
  </div></div><div class="fig h100 "></div></div>

  <div id="dbninv" class="frm h100 dialog" style="display: none;"><div class="fig h100"></div><div><div class="fc"><div class="fig w100" style="height:2.5%"></div><div class="fc db" style="min-width:700px;width:700px;min-height:380px;height:380px;">
    <div id="dbninvh" class="w100 tdg">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          <div class="material-icons tb pb10 nopt">link</div>
          <div class="i18n-invite fig sl pl10 toj">Convite</div>
        </div>
      </div>
    </div>
    <div id="dbninvb" class="fig w100 p10">
      <div class="modal w100">
        <div class="modal-content w100 p10">
          <div class="pb10 pl10"><span id="dbninv_share_link" class="i18n-invite-share-link toj sn">Compartilhe o link a seguir com quem você deseja que participe desta Sala de Conferência</span>:</div>
          <div class="frm bor br p10 w100" style="margin-top:10px;">
              <div id="dbninv_token" class="ss fig" style="height:160px;word-wrap:break-word;max-width:600px;"></div>
              <div id="dbninv_token_copy" class="material-icons tg pl10 fic">content_copy</div>
          </div>
          <div class="frm sn w100" style="min-height:30px;height:30px;">
              <span id="dbninv_alert" class="fic ss"></span>
          </div>
          <span class="dbninv_confirm fcm">
            <span id="dbninv_confirm" class="i18n-ok bt ss fic tw pt bgbl" style="margin:5px;">OK</span>
          </span>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100" style="height:2.5%"></div>
  </div></div><div class="fig h100"></div></div>

  <div id="dbcinv" class="frm h100 dialog" style="display: none;"><div class="fig h100"></div><div><div class="fc"><div class="fig w100" style="height:2.5%"></div><div class="fc db" style="min-width:450px;width:450px;">
    <div id="dbcinvh" class="w100 tdg">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          <div class="material-icons tb pb10 nopt">link</div>
          <div class="i18n-invite fig sl pl10 toj">Convite</div>
        </div>
      </div>
    </div>
    <div id="dbcinvb" class="fig w100 p10">
      <div class="modal w100" style="position:relative;">
        <div id="cinv-options-menu" class="bgw fc bor br p10" style="position:absolute;">
          <div id="cinv-option-copy" class="i18n-copy p5 pt">Copiar</div>
          <div id="cinv-option-edit" class="i18n-edit p5 pt">Editar</div>
          <div id="cinv-option-delete" class="i18n-delete p5 pt">Apagar</div>
        </div>
        <div class="modal-content w100 pt10 pl10 pr10">
          <div id="cinv-public-area" class="fc" style="border-bottom: 1px solid #eee;">
            <div class="frm pb10 w100">
              <div class="fig fc"><div class="toj sn b i18n-invite-public">Público</div><div class="tdg ss i18n-invite-anyone">Qualquer um com o link</div></div>
              <div id="cinv-public-add" class="material-icons tdg sxxl">add</div>
            </div>
            <div id="cinv-public-list-area" class="fcm w100" style="margin-bottom:10px;">
                <div class="fic fig"><textarea id="cinv-public-link-value" class="bglg br p5 w100 sxs" style="border:none;height:80px;resize:none;"></textarea></div>
                <div id="cinv-public-link-copy" class="pl10 pt10 pb10 material-icons sxl pt">content_copy</div>
                <div id="cinv-public-options" class="pl10 pt10 pb10 material-icons sxl pt">more_vert</div>
            </div>
            <div id="cinv-public-edit" class="fc w100" style="display:none;">
                <div class="fic i18n-invite-valid-since">Válido a partir de:</div>
                <div class="fr fic">
                    <div class="p5"><input id="cinv-public-from" class="bglg p10" type="datetime-local" style="font-family:'Roboto',sans-serif;"></div>
                </div>
                <div class="fic i18n-invite-to">Até</div>
                <div class="fr fic">
                    <div class="p5"><input id="cinv-public-to" class="bglg p10" type="datetime-local" style="font-family:'Roboto',sans-serif;"></div>
                </div>
                <div class="frm pl5 pr5 pb10 w100" style="justify-content:space-between;">
                    <div id="cinv-public-edit-cancel" class="i18n-cancel ss p5 pt" style="margin-right:20px;">Cancelar</div>
                    <div id="cinv-public-edit-link" class="i18n-invite-create ss p10 toj pt b">Criar convite</div>
                </div>
            </div>
          </div>
          <div id="cinv-private-area" class="fc" style="border-bottom: 1px solid #eee;margin-top:20px;">
            <div class="frm pb10 w100">
              <div class="fig fc"><div class="toj sn b i18n-invite-private">Privado</div><div class="tdg ss i18n-invite-only-members">Apenas para membros</div></div>
              <div id="cinv-private-add" class="material-icons tdg sxxl">add</div>
            </div>
            <div id="cinv-private-list-area" class="fcm w100" style="margin-bottom:10px;">
                <div class="fic fig"><textarea id="cinv-private-link-value" class="bglg br p5 w100 sxs" style="border:none;height:80px;resize:none;"></textarea></div>
                <div id="cinv-private-link-copy" class="pl10 pt10 pb10 material-icons sxl pt">content_copy</div>
                <div id="cinv-private-options" class="pl10 pt10 pb10 material-icons sxl pt">more_vert</div>
            </div>
            <div id="cinv-private-edit" class="fc w100" style="display:none;">
                <div class="fic i18n-invite-valid-since">Válido a partir de:</div>
                <div class="fr fic">
                    <div class="p5"><input id="cinv-private-from" class="bglg p10" type="datetime-local" style="font-family:'Roboto',sans-serif;"></div>
                </div>
                <div class="fic i18n-invite-to">Até</div>
                <div class="fr fic">
                    <div class="p5"><input id="cinv-private-to" class="bglg p10" type="datetime-local" style="font-family:'Roboto',sans-serif;"></div>
                </div>
                <div class="frm pl5 pr5 pb10 w100" style="justify-content:space-between;">
                    <div id="cinv-private-edit-cancel" class="i18n-cancel ss p5 pt" style="margin-right:20px;">Cancelar</div>
                    <div id="cinv-private-edit-link" class="i18n-invite-create ss p10 toj pt b">Criar convite</div>
                </div>
            </div>
          </div>
          <!--div class="fc" style="border-bottom: 1px solid #eee;">
            <div class="frm pb10 pt10 w100">
              <div class="fig fc"><div class="toj sn b">Privado</div><div class="tdg ss i18n-invite-only-members">Apenas para membros</div></div>
              <div class="material-icons tdg sxxl">add</div>
            </div>
          </div -->

          <div class="frm sn w100" style="min-height:30px;height:30px;">
              <span id="dbcinv_alert" class="fic ss"></span>
          </div>
          <span class="dbcinv_confirm fcm">
            <span id="dbcinv_confirm" class="i18n-ok bt ss fic tw pt bgbl" style="margin-top:5px;">OK</span>
          </span>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100" style="height:2.5%"></div>
  </div></div><div class="fig h100"></div></div>

  <div id="db-metaverse-idle" class="frm h100 dialog" style="display: none;"><div class="fig h100"></div><div><div class="fc"><div class="fig w100" style="height:2.5%"></div><div class="fc db" style="min-width:350px;width:350px;min-height:125px;height:125px;">
    <div id="db-metaverse-idleb" class="fig w100 p10">
      <div class="modal w100">
        <div class="modal-content w100 p10">
          <div class="pb10 pl10">
            <span class="i18n-metaverse-idle-msg toj sn">Deseja continuar no Metaverso?</span>&nbsp;(<span id="db-metaverse-idle-countdown">10</span>s)
          </div>
          <span class="fcm pt10">
            <span id="db-metaverse-idle-quit" class="i18n-metaverse-idle-quit bt ss fic tw pt" style="margin:5px;background-color:#CCCCCC">SAIR</span>
            <span id="db-metaverse-idle-continue" class="i18n-metaverse-idle-continue bt ss fic tw pt bgbl" style="margin:5px;">SIM, CONTINUAR</span>
          </span>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100" style="height:2.5%"></div>
</div></div><div class="fig h100"></div></div>

  <div id="dbadv" class="frm h100 dialog" style="display: none;"><div class="fig h100 dx"></div><div><div class="fc"><div class="fig w100 dx" style="height:2.5%"></div><div class="fc db" style="min-width:700px;width:700px;min-height:220px;height:220px;">
    <div id="dbadvh" class="w100 tdg">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          <div class="material-icons tb pb10 nopt">settings</div>
          <div class="i18n-advanced-settings fig sl pl10 toj">Configurações avançadas</div>
          <div class="sxl tg dx pt">X</div>
        </div>
      </div>
    </div>
    <div id="dbadvb" class="fig w100 p10">
      <div class="modal w100">
        <div class="modal-content w100 p10">
          <div class="pb10 pl10">
            <span class="i18n-webcam-bitrate toj sn">Taxa de transferência de câmera de vídeo:</span>&nbsp;
            <select id="webcam-bitrate" class="sn"></select>
          </div>
          <div class="pb10 pl10">
            <span class="i18n-screen-bitrate toj sn">Taxa de transferência de compartilhamento de tela:</span>&nbsp;
            <select id="screen-bitrate" class="sn"></select>
          </div>
          <div class="pb10 pl10" style="display: none;">
            <span class="i18n-screen-framerate toj sn">Taxa de quadros por segundo de compartilhamento de tela:</span>&nbsp;
            <select id="screen-framerate" class="sn"></select>
          </div>
          <span class="dbadv_confirm fcm pt10">
            <span id="dbadv_cancel" class="i18n-cancel bt ss fic tw pt" style="margin:5px;background-color:#CCCCCC">Cancelar</span>
            <span id="dbadv_confirm" class="i18n-confirm bt ss fic tw pt bgbl" style="margin:5px;">Confirmar</span>
          </span>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100 dx" style="height:2.5%"></div>
  </div></div><div class="fig h100 dx"></div></div>

  <div id="dbyt" class="frm h100 dialog" style="display: none;"><div class="fig h100 dx"></div><div><div class="fc"><div class="fig w100 dx" style="height:2.5%"></div><div class="fc db" style="min-width:710px;width:710px;min-height:550px;height:550px;">
    <div id="dbyth" class="w100 tdg">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          <div class="material-icons tb pb10 nopt"></div>
          <div class="i18n-youtube-playlist fig sl pl10 toj">Playlist Youtube</div>
          <div class="sxl tg dx pt">X</div>
        </div>
      </div>
    </div>
    <div id="dbytb" class="fig w100 p10">
      <!-- Modal content -->
      <div class="modal fr h100">
        <div class="fc bgw pt5" style="width:120px;">
          <div id="yt-new" class="i18n-new-video item w100 p5 pt">Novo vídeo</div>
          <div id="yt-playlist" class="i18n-playlist item w100 bgw p5 pt">Playlist</div>
          <div id="yt-config" class="i18n-settings item w100 bgw p5 pt">Configurações</div>
        </div>
        <div class="fc fig p10 pl20">
          <div id="yt-new-board" class="w100" style="height:410px;">
            <div class="fc fig h100">
              <div class="i18n-youtube-video-url">URL do vídeo do youtube</div>
              <div class="fr">
                <div>
                  <input type="text" class="sn bor br p10" id="yt-input" style="width:400px;">
                </div>
                <div class="fig">
                  <div id="yt-new-search" class="i18n-search ss tw bgbl bt" style="margin-left:10px;">Buscar</div>
                </div>
              </div>
              <div class="frm w100">
                <div id="yt-load-error" class="fic p20 tr ss"></div>
              </div>
              <div id="yt-preview-content" class="w100">
                <div class="i18n-video-title pt10">Tópico do Vídeo</div>
                <input type="text" class="ss bor br p10" id="yt-title-input" style="width:490px;" maxlength="70">
                <div class="i18n-preview pt10">Preview</div>
                <div class="bor br" style="width:400px;height:225px;overflow:hidden;">
                  <div id="yt-preview"></div>
                </div>
                <div class="frm w100" style="margin-top:20px;">
                  <div class="i18n-cancel yt-cancel bt tw ss" style="margin-right:10px;background-color:#CCCCCC">Cancelar</div>
                  <div id="yt-new-save" class="i18n-save bt bgbl tw ss" style="margin-left:10px;">Salvar</div>
                </div>
              </div>
              <div id="yt-preview-no-content" class="frm w100 h100" style="color:#EEEEEE;">
                <div class="fic fcm w100 h100">
                  <div class="fic">
                    <div class="material-icons" style="font-size: 200px;"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div id="yt-new-update" class="w100" style="height:400px;display:none;">
            <div class="fc h100">
              <div class="fig"></div>
              <div class="fic frm w100"><div class="i18n-video-sucessfuly-added-to-playlist fic sl p10">Vídeo adicionado com sucesso a playlist!</div></div>
              <div class="fic frm p10">
                <div id="yt-new-again" class="i18n-add-new-video fic bgbl tw sn p5 pl20 pr20 br pt">Adicionar novo vídeo</div>
              </div>
              <div class="fig"></div>
            </div>
          </div>
          <div id="yt-playlist-board" class="w100" style="height:470px;display:none;">
            <div id="yt-playlist-body" class="w100" style="height:410px;overflow:auto;">
              <div class="yt-playlist-item fcm w100" style="border-bottom:1px solid #f1f1f1" index="0">
                <div class="fic frm w100">
                  <div class="material-icons sxl p10"></div>
                  <div class="fig ss toj"></div>
                  <div class="sxs"></div>
                  <div class="material-icons sxl"></div>
                </div>
              </div>
            </div>
            <div id="yt-playlist-buttons" class="w100 frm" style="height:60px;">
              <div class="pr10">
                <div class="i18n-cancel yt-update-cancel p5 pl20 pr20 bgdg br tw pt">Cancelar</div>
              </div>
              <div class="pl10">
                <div id="yt-playlist-publish" class="i18n-update yt-playlist-publish p5 pl20 pr20 bgbl br tw pt">Atualizar</div>
              </div>
            </div>
          </div>
          <div id="yt-config-board" class="w100" style="height:470px;display:none;">
            <div id="yt-config-body" class="w100" style="height:410px;overflow:auto;">
              <div class="yt-config-item fcm w100" style="border-bottom:1px solid #f1f1f1" index="1">
                <div class="fic frm w100">
                  <div class="i18n-auto-play fig sn toj pt10 pb10">Auto play</div>
                  <div class="sxs"><input id="yt-checkbox1" type="checkbox"></div>
                </div>
              </div>
              <div class="yt-config-item fcm w100" style="border-bottom:1px solid #f1f1f1" index="2">
                <div class="fic frm w100">
                  <div class="i18n-show-control fig sn toj pt10 pb10">Exibir controle</div>
                  <div class="sxs"><input id="yt-checkbox2" type="checkbox"></div>
                </div>
              </div>
              <div class="yt-config-item fcm w100" style="border-bottom:1px solid #f1f1f1" index="0">
                <div class="fic frm w100">
                  <div class="i18n-loop fig sn toj pt10 pb10">loop</div>
                  <div class="sxs"><input id="yt-checkbox0" type="checkbox"></div>
                </div>
              </div>
              <div class="yt-config-item fcm w100" style="border-bottom:1px solid #f1f1f1" index="3">
                <div class="fic frm w100">
                  <div class="i18n-tv-mode fig sn toj pt10 pb10">Modo TV</div>
                  <div class="sxs"><input id="yt-checkbox3" type="checkbox"></div>
                </div>
              </div>
            </div>
            <div id="yt-config-buttons" class="w100 frm" style="height:60px;">
              <div class="pr10">
                <div class="i18n-cancel yt-update-cancel p5 pl20 pr20 bgdg br tw pt">Cancelar</div>
              </div>
              <div class="pl10">
                <div class="i18n-update yt-playlist-publish p5 pl20 pr20 bgbl br tw pt">Atualizar</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100 dx" style="height:2.5%"></div>
  </div></div><div class="fig h100"></div></div>

  <div id="dbcsmstart" class="frm h100 dialog" style="display: none;"><div class="fig h100"></div><div><div class="fc"><div class="fig w100" style="height:2.5%"></div><div class="fc db" style="min-width:570px;width:570px;min-height:600px;height:600px;">
    <div id="dbcsmstarth" class="w100 tdg">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          <div class="i18n-session-start sl pl10" style="color:#000;">Iniciar Aula</div>
          <div class="fig"></div>
          <div id="dbcsm-session-new" class="i18n-session-new ss tg pt dbcsmoption" style="position:relative;bottom:-3px;margin-right:40px;border-bottom:0px solid;border-color:#002d70;">Nova Aula</div>
          <div id="dbcsm-session-rerecord" class="i18n-rerecord-session ss tg pt dbcsmoption" style="position:relative;bottom:-3px;margin-right:20px;border-bottom:0px solid;border-color:#002d70;">Substituir Aula</div>
        </div>
      </div>
    </div>
    <div id="dbcsmstartb" class="fig w100 p5">
        <div id="dbcsm-startb" class="modal fr h100 dbcsmstartb-area" style="display:none;">
            <div class="fc fig p10" style="padding-top:0px;">
                <div class="w100 ss pt10 pb10">Insira os dados obrigatórios abaixo.</div>
                <div class="fc fig h100 w100">
                    <div><span class="ss i18n-title">Título</span>*</div>
                    <div class="fr w100">
                        <div class="fig w100">
                            <input type="text" class="i18n-session-insert-title sn p5 pt5" id="dbcsm-session-input-title" placeholder="Insira um título..." style="width:100%;border-bottom:solid;border-width:1px;">
                        </div>
                    </div>
                    <div class="fr w100 pt5 pb5" style="min-height:20px;">
                        <div id="dbcsm-session-date-area" class="fig w100">
                            <span class="ss i18n-session-date-reference">Data da aula</span>
                            <select id="dbcsm-session-spare" class="p5 bor br" style="margin-left:5px;font-family:'Roboto',sans-serif;"><option value="" class="i18n-session-spare-select-here" disabled="" selected="" hidden="">Selecione aqui</option><option value="spare" class="i18n-session-spare-spare">Reposição</option><option value="today" class="i18n-session-spare-today">Hoje</option></select>
                            <span id="dbcsm-session-date-area-select" style="display:none;">
                                <input id="dbcsm-session-date-reference" type="date" value="" class="ss p5 bor br" style="margin-left:5px;font-family:'Roboto',sans-serif;">
                                <span class="ss i18n-session-date-time pl10">Horário:</span>
                                <select class="p5 bor br" id="dbcsm-session-date-hour"></select>&nbsp;:
                                <select class="p5 bor br" id="dbcsm-session-date-minutes"></select>
                            </span>
                        </div>
                    </div>
                    <div id="dbcsm-categories-area" class="fc w100 p5 bor br" style="height:335px;min-height:335px;overflow-y:auto;overflow-x:hidden;max-width:540px;">
                    </div>
                    <div class="pl5 " style="height:23px;margin-top:0px;">
                        <div id="dbcsm-add-category" class="fig w100 fr" style="height:23px;display:none;">
                            <div class="material-icons pr5 sl toj fic">control_point</div>
                            <div class="i18n-session-insert-category toj pt ss fic" style="vertical-align:middle;">Adicionar Categoria</div>
                        </div>
                    </div>
                    <div class="frm w100" style="min-height:25px;position:relative;top:-10px;">
                        <div id="dbcsm-session-label-start-error" class="fic ss tr" style="display:none;"></div>
                    </div>
                    <div class="w100" style="position:relative;top:-10px;">
                        <div class="frm w100" style="">
                            <div class="i18n-cancel session-cancel bt tw ss" style="margin-right:10px;background-color:#CCCCCC">Cancelar</div>
                            <div id="dbcsm-session-start" class="i18n-start bt bgbl tw ss" style="margin-left:10px;">Iniciar</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
      <div id="dbcsm-rerecordb" class="modal fr h100 dbcsmstartb-area" style="display:none;">
        <div id="dbcsm-session-rerecord-area" class="fc fig p10" style="padding-top:0px;position:relative;">
            <div class="w100 p10 ss" style="margin-left:10px;">Selecione a aula que deseja substituir</div>
            <div class="fc fig h100 w100" style="align-items:center;">
                <div class="fc w100 bor br" style="height:440px;min-height:440px;width:500px;border-color:#CCCCCC;">
                    <div class="w100 fr" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
                        <div class="p5 ss" style="width:120px;text-align:center">ID</div>
                        <div class="fig">&nbsp;</div>
                        <div class="p5 ss fig" style="width:200px;max-width:200px;text-align:center;">Data/Hora de Referência</div>
                    </div>
                    <div id="dbcsm-sessions-availiable-area" class="fig fc w100 p5" style="overflow-y:auto;overflow-x:hidden;">
                    </div>
                </div>
                <div class="frm w100" style="min-height:25px;">
                    <div id="dbcsm-session-start-label-error" class="fic ss tr" style="display:none;"></div>
                </div>
                <div class="w100">
                    <div class="frm w100" style="">
                        <div class="i18n-cancel session-cancel bt tw ss" style="margin-right:10px;background-color:#CCCCCC">Cancelar</div>
                        <div id="dbcsm-session-continue" class="i18n-continue bt bgbl tw ss" style="margin-left:10px;">Continuar</div>
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100" style="height:2.5%"></div>
  </div></div><div class="fig h100"></div></div>

  <div id="dbsessionstart" class="frm h100 dialog" style="display: none;"><div class="fig h100 dx"></div><div><div class="fc"><div class="fig w100 dx" style="height:2.5%"></div><div class="fc db" style="min-width:570px;width:570px;min-height:520px;height:520px;">
    <div id="dbsessionstarth" class="w100 tdg">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          <div class="i18n-session-start sl pl10 toj">Iniciar Aula</div>
          <div class="fig"></div>
          <div class="sxl tg dx pt">X</div>
        </div>
      </div>
    </div>
    <div id="dbsessionstartb" class="fig w100 p5">
      <div class="modal fr h100">
        <div class="fc fig p10" style="padding-top:0px;position:relative;">
            <div id="new-session" class="i18n-session-new bt bgbl tw ss" style="position:absolute;right:10px;background-color:#002d70;padding:3px 20px;">Nova Aula</div>
            <div class="fc fig h100 w100" style="align-items:center;">
                <div class="fr w100 pt5 pb0" style="border:0px;border-bottom:1px;border-style: solid;border-color:#EEEEEE;margin-bottom:10px;">
                    <div id="session-record-session" class="i18n-record-session fic p5 pt" style="display: none; border-width: 0px 0px 2px; border-style: solid; border-color: rgb(50, 87, 148); border-image: initial;">Aulas Agendadas</div>
                    <div id="session-rerecord-session" class="i18n-rerecord-session fic p5 pt" style="margin-left: 10px; display: none; border: 0px;">Substituir Aula</div>
                    <div class="fig"></div>
                </div>
                <div class="fc w100 bor br" style="height:345px;min-height:345px;width:500px;border-color:#CCCCCC;">
                    <div class="w100 fr" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
                        <div class="p5 ss" style="width:120px;text-align:center">ID</div>
                        <div class="fig">&nbsp;</div>
                        <div class="p5 ss fig" style="width:200px;max-width:200px;text-align:center;">Data/Hora de Referência</div>
                    </div>
                    <div id="sessions-availiable-area" class="fig fc w100 p5" style="overflow-y:auto;overflow-x:hidden;">
                    </div>
                </div>
                <div class="frm w100" style="min-height:25px;">
                    <div id="session-start-label-error" class="fic ss tr" style="display:none;"></div>
                </div>
                <div class="w100">
                    <div class="frm w100" style="">
                        <div class="i18n-cancel session-cancel bt tw ss" style="margin-right:10px;background-color:#CCCCCC">Cancelar</div>
                        <div id="session-continue" class="i18n-continue bt bgbl tw ss" style="margin-left:10px;">Continuar</div>
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100 dx" style="height:2.5%"></div>
  </div></div><div class="fig h100 dx"></div></div>

  <div id="dbsessionrecord" class="frm h100 dialog" style="display: none;"><div class="fig h100 dx"></div><div><div class="fc"><div class="fig w100 dx" style="height:2.5%"></div><div class="fc db" style="min-width:570px;width:570px;min-height:600px;height:600px;">
    <div id="dbsessionrecordh" class="w100 tdg">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          <div id="dbsession-title" class="i18n-session-start sl pl10 toj">Iniciar Aula</div>
          <div class="fig"></div>
          <div class="sxl tg dx pt">X</div>
        </div>
      </div>
    </div>
    <div id="dbsessionrecordb" class="fig w100 p10">
      <div class="modal fr h100">
        <div class="fc fig p10" style="padding-top:0px;">
            <div class="fc fig h100 w100">
                <div class="w100 ss pt10 pb10">Insira os dados obrigatórios abaixo.</div>
                <div><span class="ss i18n-title">Título</span>*</div>
                <div class="fr w100">
                    <div class="fig w100">
                        <input type="text" class="i18n-session-insert-title sn p5 pt5" id="dbsession-input-title" placeholder="Insira um título..." style="width:100%;border-bottom:solid;border-width:1px;">
                    </div>
                </div>
                <div class="fr w100 sn p10" style="justify-content:space-between;">
                    <div class="pr20">ID: <span id="dbsessionid"></span></div>
                    <div>
                        <span>Data/Hora de referência:</span>
                        <span id="dbsessionrefdate"></span>
                    </div>
                </div>
                <div id="dbsessionselectedcategories" class="fr w100 pl5 pr5 pb5"></div>
                <div class="fc w100 p5 bor br" style="height:270px;min-height:270px">
                    <div id="dbsession-categories-area" class="fig fc w100 p5" style="overflow-y:auto;overflow-x:hidden;">
                    </div>
                </div>
                <div class="pl5 " style="height:23px;">
                    <div id="dbsessionadd-category" class="fig w100 fr" style="height:23px;">
                        <div class="material-icons pr5 sl toj fic">control_point</div>
                        <div class="i18n-session-insert-category toj pt ss fic" style="vertical-align:middle;">Adicionar Categoria</div>
                    </div>
                </div>
                <div class="frm w100" style="min-height:25px;">
                    <div id="dbsession-start-label-error" class="fic ss tr" style="display:none;"></div>
                </div>
                <div class="w100">
                    <div class="frm w100" style="justify-content:space-between;">
                        <div id="dbsessionrecord-back" class="i18n-back bt tw ss" style="margin-right:10px;background-color:#CCCCCC">Voltar</div>
                        <div>
                            <div class="i18n-cancel session-cancel bt tw ss" style="margin-right:10px;background-color:#CCCCCC">Cancelar</div>
                            <div id="dbsession-start" class="i18n-start bt bgbl tw ss" style="margin-left:10px;">Iniciar</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100 dx" style="height:2.5%"></div>
  </div></div><div class="fig h100 dx"></div></div>

  <div id="dbsession" class="frm h100 dialog" style="display: none;"><div class="fig h100 dx"></div><div><div class="fc"><div class="fig w100 dx" style="height:2.5%"></div><div class="fc db" style="min-width:800px;width:1024px;min-height:560px;height:560px;">
    <div id="dbsessionh" class="w100 tdg">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          <div class="i18n-session-new sl pl10 toj">Nova Aula</div>
          <div class="fig"></div>
          <div class="sxl tg dx pt">X</div>
        </div>
      </div>
    </div>
    <div id="dbsessionb" class="fig w100 p10">
      <div class="modal fr h100">
        <div class="fc fig p10" style="padding-top:0px;">
            <div class="fc fig h100 w100">
                <div><span class="ss i18n-title">Título</span>*</div>
                <div class="fr w100">
                    <div class="fig w100">
                        <input type="text" class="i18n-session-insert-title sn p5 pt5" id="session-input-title" placeholder="Insira um título..." style="width:100%;border-bottom:solid;border-width:1px;">
                    </div>
                </div>
                <div class="fr w100 pt5 pb5">
                    <div class="fig w100">
                        <span class="ss i18n-session-date-reference">Data da aula</span>
                        <select id="session-spare" class="p5 bor br" style="margin-left:5px;font-family:'Roboto',sans-serif;"><option value="" class="i18n-session-spare-select-here" disabled="" selected="" hidden="">Selecione aqui</option><option value="spare" class="i18n-session-spare-spare">Reposição</option><option value="today" class="i18n-session-spare-today">Hoje</option></select>
                        <span id="session-date-area" style="display:none;">
                            <input id="session-date-reference" type="date" value="" class="ss p5 bor br" style="margin-left:5px;font-family:'Roboto',sans-serif;">
                            <span class="ss i18n-session-date-time pl10">Horário:</span>
                            <select class="p5 bor br" id="session-date-hour"></select>&nbsp;:
                            <select class="p5 bor br" id="session-date-minutes"></select>
                        </span>
                    </div>
                </div>
                <div id="categories-area" class="fc w100 p5 bor br" style="height:335px;min-height:335px;overflow-y:auto;overflow-x:hidden;">
                </div>
                <div class="frm w100" style="min-height:25px;">
                    <div id="session-label-start-error" class="fic ss tr" style="display:none;"></div>
                </div>
                <div class="pl5 " style="height:23px;margin-top:-20px;">
                    <div id="add-category" class="fig w100 fr" style="height:23px;display:none;">
                        <div class="material-icons pr5 sl toj fic">control_point</div>
                        <div class="i18n-session-insert-category toj pt ss fic" style="vertical-align:middle;">Adicionar Categoria</div>
                    </div>
                </div>
                <div class="w100">
                    <div class="frm w100" style="">
                        <div class="i18n-cancel session-cancel bt tw ss" style="margin-right:10px;background-color:#CCCCCC">Cancelar</div>
                        <div id="session-start" class="i18n-start bt bgbl tw ss" style="margin-left:10px;">Iniciar</div>
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100 dx" style="height:2.5%"></div>
  </div></div><div class="fig h100 dx"></div></div>

  <div id="dbsession-finish" class="frm h100 dialog" style="display: none;"><div class="fig h100 dx"></div><div><div class="fc"><div class="fig w100 dx" style="height:2.5%"></div><div class="fc db" style="position:relative;min-width:420px;width:420px;min-height:510px;height:510px;border-bottom-left-radius:0px;border-bottom-right-radius:0px;">
    <div id="dbsessionh-finish" class="w100 tdg" style="position:absolute;">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100">
          <div class="fig"></div>
          <div id="session-ok" class="sxl tg pt">X</div>
        </div>
      </div>
    </div>
    <div id="dbsession-finishb" class="fig w100 p10">
      <div class="modal fr h100 w100">
        <div class="fc fig p5 w100">
            <div class="fc fig h100 w100">
                <div class="w100">
                    <div class="frm w100 p10">
                        <div class="material-icons sl" style="font-size:50px;color:#18B537;cursor:auto;">check_circle_outline</div>
                    </div>
                </div>
                <div class="w100">
                    <div class="frm w100 pt0 pb10">
                        <div class="i18n-session-finished b sn">Aula Finalizada!</div>
                    </div>
                </div>
                <div class="w100 frm">
                    <div class="frm p0" style="width:300px;border-bottom:solid;border-width:1px;border-color:#707070;">
                    </div>
                </div>
                <div class="w100">
                    <div class="frm w100 p10">
                        <div class="i18n-session-report sn pt10">Resumo da aula</div>
                    </div>
                </div>
                <div class="w100 bor br" style="border-color:#707070;height:320px;min-height:320px;">
                    <div class="frm w100 p5 pl10 pr10" style="border-bottom:solid;border-width:1px;">
                        <div class="sxs fig">Usuário</div>
                        <div class="sxs" style="width:100px;">Tempo em aula</div>
                    </div>
                    <div id="session-userlist" class="w100" style="padding:2px;overflow-y:auto;height:280px;max-height:280px;">
                    </div>
                </div>

                <!-- div class="w100">
                    <div class="frm w100" style="margin-top:20px;">
                        <div id="session-download" class="i18n-download bt tdg ss bor" style="margin-right:10px;background-color:#FFFFFF">Download</div>
                        <div id="session-email" class="i18n-send-email bt tdg ss bor" style="margin-right:10px;background-color:#FFFFFF;display:flex;"><span class="i18n-send-email pr5">Enviar por e-mail</span><span class="material-icons sl">mail_outline</span></div>
                        <div id="session-ok" class="i18n-ok bt bgbl tw ss" style="margin-left:10px;">OK</div>
                    </div>
                </!-->
            </div>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100" style="height:130px;background-color:#01327e;border-bottom-left-radius:7.5px;border-bottom-right-radius:7.5px;">
    <div class="fc w100 p10">
        <div class="fic tw">Para detalhamento da aula faça</div>
        <div class="fic tw">o download dos arquivos.</div>
        <div class="frm fic w100" style="margin-top:10px;">
            <div id="session-download" class="bt tdg ss bor" style="margin-right:10px;background-color:#FFFFFF">
                <div class="fr">
                    <div class="i18n-download">Download</div>
                    <div>&nbsp;&nbsp;</div>
                    <div class="material-icons sl">file_download</div>
                </div>
            </div>
        </div>
    </div>
  </div>
  </div></div><div class="fig h100 dx"></div></div>

  <div id="dbdisplay" class="frm h100 dialog" style="display: none;">
    <div class="frm w100 h100">
      <div class="fic fcm h100 w100">
        <div id="dbdisplay_size" class="fc db p10">
          <div class="w100 tdg">
            <div class="fr pt5 pl5 pr10 pb5 w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
              <div id="dbdisplay_icon" class="tb material-icons dx pl5"></div>
              <div id="dbdisplay_title" class="tc toj fig sl pl5"></div>
              <div class="pt dx">X</div>
            </div>
          </div>
          <div class="fig w100">
            <div class="fc w100">
              <div class="fc fig pt10 pb10 w100">
                <span id="dbdisplay_text" class="ss n fig pl5 w100" style="text-align:justify"></span>
              </div>
              <div class="frm w100">
                <span id="dbdisplay_ok" class="dbdisplay_ok bt ss fic tw pt" style="background-color:CCCCCC;display:none;">OK</span>
                <span class="dbdisplay_confirm" style="display:none;">
                  <span id="dbdisplay_cancel" class="i18n-cancel bt ss fic tw pt" style="background-color:CCCCCC">Cancelar</span>
                  <span id="dbdisplay_confirm" class="i18n-confirm bt ss fic tw pt bgbl">Confirmar</span>
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div id="dbdisplay-layout" class="frm h100 dialog" style="display: none;"><div class="fig h100 dx"></div><div><div class="fc"><div class="fig w100 dx" style="height:2.5%"></div><div class="fc db" style="position:relative;min-width:400px;width:400px;min-height:350px;">
    <div id="dbdisplay-layout-finish" class="w100 tdg" style="position:absolute;">
      <div class="fr pt10 pl10 pr10">
        <div class="fr w100">
          <div class="fig"></div>
          <div class="sxl tg dx pt">X</div>
        </div>
      </div>
    </div>
    <div id="dbdisplay-layoutb" class="fig w100 p10">
      <div class="modal fr h100 w100">
        <div class="fc fig p5 w100">
            <div class="fc fig h100 w100">
                <div class="w100">
                    <div class="frm w100 pt0 pb10">
                        <div class="sn">Alterar Layout de Gravação</div>
                    </div>
                </div>
                <div class="w100 frm">
                    <div class="frm p0" style="width:300px;border-bottom:solid;border-width:1px;border-color:#707070;">
                    </div>
                </div>
                <div class="w100">
                    <div class="frm w100 p10">
                        <div class="fic p5">
                            <input id="display-main" type="radio" name="display-layout" value="main">
                        </div>
                        <label for="display-main" class="fic p5">
                            <div style="width:31px;height:22px;border-radius:4px;background-color:#AEAEAE"></div>
                        </label>
                        <label for="display-main" class="fic p5">
                            Destaque
                        </label>
                        <div class="fig"></div>
                    </div>
                    <div class="frm w100 p10">
                        <div class="fic p5">
                            <input id="display-lateral" type="radio" name="display-layout" value="lateral">
                        </div>
                        <label for="display-lateral" class="fic p5">
                            <div class="frm" style="width:31px;height:21px;border-radius:2px">
                                <div style="width:21px;min-width:21px;height:100%;background-color:#AEAEAE"></div>
                                <div style="width:4px;min-width:3px;height:100%;background-color:#FFFFFF"></div>
                                <div class="fc fig w100 h100 bgw" style="max-height:21px;justify-content:space-between;">
                                    <div class="fic w100" style="height:6px;background-color:#AEAEAE"></div>
                                    <div class="fic w100" style="height:6px;background-color:#AEAEAE"></div>
                                    <div class="fic w100" style="height:6px;background-color:#AEAEAE"></div>
                                </div>
                            </div>
                        </label>
                        <label for="display-lateral" class="fic p5">
                            Barra Lateral
                        </label>
                        <div class="fig"></div>
                    </div>
                    <div id="display-grid-area" class="frm w100 p10" style="display:none;">
                        <div class="fic p5">
                            <input id="display-grid" type="radio" name="display-layout" value="grid">
                        </div>
                        <label for="display-grid" class="fic p5">
                            <div class="frm bgw" style="width:35px;max-width:35px;height:21px;max-height:21px;border-radius:2px;flex-wrap:wrap;">
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                                <div style="width:6px;height:6px;margin:1px;background-color:#AEAEAE"></div>
                            </div>
                        </label>
                        <label for="display-grid" class="fic p5">
                            Grade
                        </label>
                        <div class="fig"></div>
                    </div>
                    <div class="frm w100 p10 ss">
                        <div>Observação: Será possível visualizar o layout escolhido apenas no vídeo gerado após finalizar a aula.</div>
                    </div>
                    <div id="rec-options" class="w100 fc p10" style="display:none;">
                        <div class="fic frm p0" style="width:300px;border-bottom:solid;border-width:1px;border-color:#707070;">
                        </div>
                        <div class="sn p10">Opções de Gravação</div>
                        <div class="ss p5"><input id="record_cc_checkbox" name="record_cc_checkbox" type="checkbox"><label for="record_cc_checkbox">Gravar com Legenda ativada.</label></div>
                        <div class="ss p5"><input id="record_chat_checkbox" name="record_chat_checkbox" type="checkbox"><label for="record_chat_checkbox">Gravar o chat da aula.</label></div>
                        <div class="ss p5"><input id="record_inout_checkbox" name="record_inout_checkbox" type="checkbox"><label for="record_inout_checkbox">Gravar controle de saída e entrada de usuário.</label></div>
                    </div>
                </div>

                <div class="w100">
                    <div class="frm w100" style="margin-top:10px;">
                        <div id="display-layout-cancel" class="i18n-cancel bt tdg ss bor" style="margin-right:10px;background-color:#FFFFFF">Cancelar</div>
                        <div id="display-layout-apply" class="i18n-apply bt bgbl tw ss" style="margin-left:10px;">Aplicar</div>
                    </div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100 dx" style="height:2.5%"></div>
  </div></div><div class="fig h100 dx"></div></div>

  <div id="dbgroupinfo" class="frm h100 dialog" style="display: none;">
    <div class="frm w100 h100">
      <div class="fic fcm h100 w100">
        <div class="fc db" style="min-width: 300px;">
          <div class="fr w100 tdg">
            <div class="i18n-group-data sn toj pl10 pt5">Dados do Grupo</div>
            <div class="fig"></div>
            <div class="pt dx pr10 pt5">X</div>
          </div>
          <div class="frm w100 pb10">
            <img id="dbgroupinfo_avatar" src="https://edusp-static.ip.tv/webinar/common/img/avatarGroup.png" style="width:100px;height:100px;" class="cp" onerror="loadDefaultAvatar(this);">
          </div>
          <div id="dbgroupinfo_name" class="toj frm w100 sn pb10">Group Name</div>
          <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          </div>
          <div id="dbgroupinfo_silence" class="tdg fr frm w100 ss p5">
            <div class="sxl material-icons"></div>
            <div class="i18n-silence-notifications ss">Silenciar Notificações</div>
            <div class="fig"></div>
            <div><input id="dbgroupsilencecb" type="checkbox"></div>
          </div>
          <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          </div>
          <div class="tdg fr w100 sxs">
            <span class="i18n-participants ss tdg p5 pl10">Participantes</span>:
            <span id="dbgroupinfo_membercount" class="ss tdg p5">83</span>
          </div>
          <div class="fr w100" style="border:0px;border-bottom:1px;border-style: solid;border-color:#CCCCCC;">
          </div>
          <div class="fc w100 p10" style="max-height:200px;overflow:auto">
            <div id="dbgroupowner" class="fr frm w100 pb5"></div>
            <div id="dbgroupadmin" class="fc w100"></div>
            <div id="dbgroupmembers" class="fc w100"></div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div id="dbroomdetail" class="frm h100 dialog" style="display: none;"><div class="fig h100"></div><div><div class="fc"><div class="fig w100" style="height:fit-content"></div><div class="fc db" style="width:550px; height:fit-content">
    <div id="dbroomdetailh" class="w100 tdg">
      <div class="frm pt10 pl5 pr10 pb5">
        <div class="i18n-detail fic sxl pl10 toj b">Detalhes</div>
      </div>
    </div>
    <div class="fic" style="border-bottom: 1px solid #ccc;width:90%;"></div>
    <div id="room-detail-name" class="fic p10 sxl"></div>
    <div id="dbroomdetailb" class="fig w100 p10" style="width: 550px;">
      <div id="room-detail-categories" class="tc">
      </div>
      <div class="tc pt10 w100 fr">
        <div class="fig"></div>
        <div>
          <span id="dbroomdetail_close" class=""><div class="tb sxl pt pr20"><span class="i18n-close">Fechar</span></div></span>
        </div>
      </div>
    </div>
  </div>
  <div class="fig w100" style="height:2.5%"></div>
  </div></div><div class="fig h100"></div></div>

  <div id="dbconf" class="frm h100 dialog" style="display: none;"><div class="fig h100 dx"></div><div><div class="fc"><div class="fig w100 dx" style="height:2.5%"></div><div class="fc db" style="height:150px;">
    <div id="dbconfh" class="w100 tdg">
      <div class="fr pt10 pl5 pr10 pb5">
        <div class="material-icons dx pl5"></div>
        <div class="i18n-settings fig sl pl5">Configurações</div>
      </div>
    </div>
    <div id="dbconfb" class="fig w100">
      <span id="dbconfbs">
        <div class="fr pt">
          <div class="fc fig pl5 pt10 pr10">
            <div class="fr w100">
              <span class="i18n-sound-alert sn n fig pl5">Alerta sonoro de novas Mensagens</span>
              <div style="position:relative;width:30px;height:30px">
                <input id="dbconfnm" name="" type="checkbox" class="sn fig fic">
              </div>
            </div>
            <div class="frm w100 pt5 dx">
              <span class="i18n-ok bt ss fic cb tw">OK</span>
            </div>
          </div>
        </div>
      </span>
      </div>
    </div>
    <div class="fig w100 dx" style="height:2.5%"></div>
  </div></div><div class="fig h100 dx"></div></div></div>





<div id="popup" class="bgw bor br ss pt5 pb5 fr" style="position:absolute;min-width:200px;z-index:19;display:none;">
  <div id="popupItens" class="fic w100">
    <div id="popupItemComment" class="i18n-reply pt5 pb5 popupItem" t="comment">Responder</div>
    <div id="popupItemForward" class="i18n-forward pt5 pb5 popupItem" t="forward">Encaminhar</div>
    <div id="popupItemDelete" class="i18n-delete pt5 pb5 popupItem" t="delete">Apagar</div>
  </div>
</div>

<div id="channelUserPopup" class="bgw bor br ss pt5 pb5 fr" style="position:absolute;min-width:200px;z-index:19;display:none;">
  <div id="popupItens" class="fic w100">
    <div id="popupItemSendMsg" class="pt5 pb5 popupItem" t="sendMsg"><span class="i18n-private-message pl10 pr10">Mensagem Privada</span></div>
    <div id="popupAddVoice" class="pt5 pb5 popupItem" t="addVoice"><span class="i18n-give-collaboration pl10 pr10">Dar Colaboração</span></div>
    <div id="popupDelVoice" class="pt5 pb5 popupItem" t="delVoice"><span class="i18n-remove-collaboration pl10 pr10">Retirar Colaboração</span></div>
    <div id="popupAddModerator" class="pt5 pb5 popupItem" t="addModerator"><span class="i18n-give-moderation pl10 pr10">Dar Moderação</span></div>
    <div id="popupDelModerator" class="pt5 pb5 popupItem" t="delModerator"><span class="i18n-remove-moderation pl10 pr10">Retirar Moderação</span></div>
    <div id="popupMuteMic" class="pt5 pb5 popupItem" t="muteMic"><span class="i18n-mute-mic pl10 pr10">Desativar Microfone</span></div>
    <div id="popupMuteCam" class="pt5 pb5 popupItem" t="muteCam"><span class="i18n-mute-cam pl10 pr10">Desativar Câmera</span></div>
    <div id="popupItemKick" class="pt5 pb5 popupItem" t="kick"><span class="i18n-kick pl10 pr10">Expulsar</span></div>
    <div id="popupItemAddMute" class="pt5 pb5 popupItem" t="addMute"><span class="i18n-silence pl10 pr10">Silenciar</span></div>
    <div id="popupItemDelMute" class="pt5 pb5 popupItem" t="delMute"><span class="i18n-remove-silence pl10 pr10">Retirar Silenciar</span></div>
    <div id="popupItemAddBan" class="pt5 pb5 popupItem" t="addBan"><span class="i18n-ban pl10 pr10">Banir</span></div>
    <div id="popupItemDelMsg" class="pt5 pb5 popupItem" t="delMsg"><span class="i18n-delete-message pl10 pr10">Apagar Mensagem</span></div>
  </div>
</div>


<div id="app" style="display:block">
  <div class="fc h100 w100" style="position:absolute;">
    <div id="top_menu" class="bgw p10 w100 fcm" style="min-height: 66px; border-bottom: 1px solid rgb(238, 238, 238);">
      <div class="fr w100" style="max-width:1400px;">
        <div class="pr10 pt5">
          <img id="alo" src="https://i.imgur.com/0iLry2i.png" style="height: 41px;width: 450px;">
        </div>
        <div class="fig fic tc pl10 pr10">
          <div id="finder" class="br bgw p5 bor fr" style="display:none;">
            <div class="sxxl tg material-icons"></div>
            <div class="fig fic">
              <input id="fit" class="sl w100 tdg" type="text" placeholder="Buscar">
            </div>
            <div id="fitc" class="sxxl tg material-icons"></div>
          </div>
        </div>
        <div class="fig"></div>
        <div class="fic tc fr">
          <div id="ncr" class="fig lpi pl5" style="display:none;">
            <div class="material-icons"></div>
            <div class="i18n-new-conference-room sxs">Nova sala de conferência</div>
          </div>
          <div id="chni" class="fig lpi pl5 __web-inspector-hide-shortcut__" style="">
            <div class="material-icons" style="margin-top:-3px;"></div>
            <div class="i18n-channels sxs" style="margin-top:3px;">Canais</div>
          </div>
          <div id="chng" class="fig lpi pl5 lpis" style="">
            <div id="groups-icon1" class="material-icons ic_group ic_group_ON __web-inspector-hide-shortcut__" style="width:30px;height:30px;" selected="selected"></div>
            <div id="groups-icon2" class="material-icons" style="display:none;">groups</div>
            <div id="groups-icon-text" class="i18n-groups sxs __web-inspector-hide-shortcut__" style="">Turmas</div>
            <div id="groups-icon2-text" class="i18n-rooms sxs" style="display:none;">Salas</div>
          </div>
          <div id="chi" class="fig lpi pl5" style="position:relative;display:none;">
            <div id="chinotread" class="bor bgr br sxxs tw" style="position:absolute;top:0px;right:5px;min-width:20px;display:none"></div>
            <div class="sxxl material-icons" style="padding-top:2px;"></div>
            <div class="i18n-chats sxs">Conversas</div>
          </div>
          <div id="pei" class="fig lpi pl5" style="display:none;">
            <div class="material-icons"></div>
            <div class="i18n-people sxs">Pessoas</div>
          </div>
          <div id="oti" class="fig lpi pl5" style="">
            <div class="material-icons __web-inspector-hide-shortcut__"></div>
            <div class="i18n-others sxs __web-inspector-hide-shortcut__">Outros</div>
          </div>
          <div id="lms" class="fig lpi pl5" style="display:none;">
            <div class="material-icons"></div>
            <div class="i18n-lms sxs">LMS</div>
          </div>
          <div id="gci" class="fig lpi pl5" style="">
            <div class="material-icons __web-inspector-hide-shortcut__"></div>
            <div class="i18n-google-classroom sxs __web-inspector-hide-shortcut__">Google Classroom</div>
          </div>
          <div id="coi" class="fig lpi pl5" style="display:none;">
            <div class="material-icons"></div>
            <div class="i18n-settings sxs">Configurações</div>
          </div>
          <div class="fig fic lpi pl5" style="position:relative;margin-left:20px;min-width:250px;">
            <div id="main-user-hello" style="display:flex;align-items:center;"><div class="material-icons">account_circle</div><div class="pt" style="margin-left:10px;"><span class="i18n-hello tg">Olá</span><span class="tg">,&nbsp;</span><span class="fullname tg" style="font-weight:bold;">GABRIEL BELO POMPEO</span></div></div>
            <div id="main-user-hello-display" class="bor br p0 sha bgw" style="position: absolute; top: 40px; z-index: 9; width: 100%; display: none;">
                <div class="p10" style="display:flex;flex-direction:column;align-items:flex-start;width:100%;">
                    <div class="w100" style="text-align:left;overflow:hidden;white-space:nowrap;text-overflow:ellipsis;"><span class="fullname sxl toj">GABRIEL BELO POMPEO</span></div>
                    <div class="nick ss tg">gabrielbelocagao92983824-waldmr</div>
                </div>
                <div style="border-bottom:1px solid;border-color:#CCCCCC;margin-top:10px;"></div>
                <div class="p20">
                    <div id="logout" class="pt frm btn br pt5 pb5 pl10 pr10" style="border:1px solid;border-color:#002d70">
                        <div class="material-icons" style="color:#002d70"></div>
                        <div class="i18n-quit sxl pl10" style="color:#002d70">Sair</div>
                    </div>
                </div>
            </div>
            <!-- div class="material-icons">&#xE9BA;</!-->
            <!-- div class="i18n-quit sxs">Sair</!-->
          </div>
        </div>

      </div>
    </div>
    <div id="chnCategoriesMenu" class="fic bgw w100" style="z-index: 1;">
      <div id="lpchcb" class="fcm fic sha w100">
        <div class="fc tw fic">
          <div id="channelCategories" class="fic fr p5 " style="display: none;"></div>
        </div>
      </div>
    </div>

    <div id="channelArea" class="fc fig w100" style="position: relative; background-image: url(&quot;https://edusp-static.ip.tv/edusp/background.png&quot;); background-repeat: repeat; overflow: auto;">
      <div id="channelList" class="fr fic w100" style="flex-wrap: wrap; max-width: 1400px; padding-top: 20px; display: none;"></div>
      <div id="roomList" class="frm w100 p20" style="min-height: 100%; background: rgb(243, 243, 243); flex-wrap: wrap; display: none;">
        <div id="roomListDetailMenu" class="br bor p10 fc bgw" style="position: absolute; display: none;"><div id="room-list-menu-tasks" class="room-list-menu-item pt p5 i18n-tasks"><span style="font-size:16px;">Provas<br>Atividades</span></div><div id="room-list-menu-recordings" class="room-list-menu-item pt p5 i18n-recordings">Gravações</div><div id="room-list-menu-mural" class="room-list-menu-item pt p5 i18n-mural">Mural</div><div id="room-list-menu-detail" class="room-list-menu-item pt p5 i18n-details">Detalhes</div></div>
        <div id="roomListFilterArea" class="fc h100" style="min-height:100%;width:300px;border-right: 1px solid #ccc;"><div class="i18n-filters">Filtros:</div><div id="roomListFilterOptions" class="p10" style="overflow-y:auto;"><div class="fc"><div class="p10"><input id="room-filter--1" class="room-filter pt" type="radio" value="-1" name="room-filter" checked=""><label for="room-filter--1" class="pl10 pt">TODOS</label></div><div class="p10"><input id="room-filter-13725" class="room-filter pt" type="radio" value="13725" name="room-filter"><label for="room-filter-13725" class="pl10 pt">  PROVA PAULISTA</label></div><div class="p10"><input id="room-filter-14287" class="room-filter pt" type="radio" value="14287" name="room-filter"><label for="room-filter-14287" class="pl10 pt"> OLIMPÍADA DE REDAÇÃO SÃO PAULO (REDASP)</label></div><div class="p10"><input id="room-filter-14288" class="room-filter pt" type="radio" value="14288" name="room-filter"><label for="room-filter-14288" class="pl10 pt"> PROVA DE RECUPERAÇÃO</label></div><div class="p10"><input id="room-filter-466" class="room-filter pt" type="radio" value="466" name="room-filter"><label for="room-filter-466" class="pl10 pt">ENSINO FUNDAMENTAL DE 9 ANOS</label></div></div></div></div>
        <div id="roomListArea" class="fc fig h100" style="overflow-y:auto;"><div class="fic p0" style="width:70%;margin-left:1.7%;margin-top:1.7%;"><div class="pl10 ss tw" style="background:#979797;width:50%;">  PROVA PAULISTA</div></div><div class="sha bgw fic" style="width:70%;margin-left:1.7%;margin-bottom:1.2%;"><div id="lproom_rd2ea544cc48ac2ab2-l" class="lproom_rd2ea544cc48ac2ab2-l frm w100 p10 pt " room="rd2ea544cc48ac2ab2-l" name="6º B EF " imgsrc="https://edusp-static.ip.tv/webinar/edusp/room_avatar.png"><div><img id="lproom_img_rd2ea544cc48ac2ab2-l" src="https://edusp-static.ip.tv/webinar/edusp/room_avatar.png" class="cp lpchi room" room="rd2ea544cc48ac2ab2-l" name="6º B EF "></div><div class="fc fig pl5 fig "><div class="fr w100 room" room="rd2ea544cc48ac2ab2-l" name="6º B EF "><span class="lpcn sn toj fic">6º B EF </span><span class="fig"></span></div></div><div class="material-icons room-list-menu-tasks tdg" room="rd2ea544cc48ac2ab2-l">assignment</div></div></div><div class="fic p0" style="width:70%;margin-left:1.7%;margin-top:1.7%;"><div class="pl10 ss tw" style="background:#979797;width:50%;"> OLIMPÍADA DE REDAÇÃO SÃO PAULO (REDASP)</div></div><div class="sha bgw fic" style="width:70%;margin-left:1.7%;margin-bottom:1.2%;"><div id="lproom_rd2ea544cc48ac2ab2-l" class="lproom_rd2ea544cc48ac2ab2-l frm w100 p10 pt " room="rd2ea544cc48ac2ab2-l" name="6º B EF " imgsrc="https://edusp-static.ip.tv/webinar/edusp/room_avatar.png"><div><img id="lproom_img_rd2ea544cc48ac2ab2-l" src="https://edusp-static.ip.tv/webinar/edusp/room_avatar.png" class="cp lpchi room" room="rd2ea544cc48ac2ab2-l" name="6º B EF "></div><div class="fc fig pl5 fig "><div class="fr w100 room" room="rd2ea544cc48ac2ab2-l" name="6º B EF "><span class="lpcn sn toj fic">6º B EF </span><span class="fig"></span></div></div><div class="material-icons room-list-menu-tasks tdg" room="rd2ea544cc48ac2ab2-l">assignment</div></div></div><div class="fic p0" style="width:70%;margin-left:1.7%;margin-top:1.7%;"><div class="pl10 ss tw" style="background:#979797;width:50%;"> PROVA DE RECUPERAÇÃO</div></div><div class="sha bgw fic" style="width:70%;margin-left:1.7%;margin-bottom:1.2%;"><div id="lproom_rd2ea544cc48ac2ab2-l" class="lproom_rd2ea544cc48ac2ab2-l frm w100 p10 pt " room="rd2ea544cc48ac2ab2-l" name="6º B EF " imgsrc="https://edusp-static.ip.tv/webinar/edusp/room_avatar.png"><div><img id="lproom_img_rd2ea544cc48ac2ab2-l" src="https://edusp-static.ip.tv/webinar/edusp/room_avatar.png" class="cp lpchi room" room="rd2ea544cc48ac2ab2-l" name="6º B EF "></div><div class="fc fig pl5 fig "><div class="fr w100 room" room="rd2ea544cc48ac2ab2-l" name="6º B EF "><span class="lpcn sn toj fic">6º B EF </span><span class="fig"></span></div></div><div class="material-icons room-list-menu-tasks tdg" room="rd2ea544cc48ac2ab2-l">assignment</div></div></div><div class="fic p0" style="width:70%;margin-left:1.7%;margin-top:1.7%;"><div class="pl10 ss tw" style="background:#979797;width:50%;">JARDIM PAINEIRAS_581124</div></div><div class="sha bgw fic" style="width:70%;margin-left:1.7%;margin-bottom:1.2%;"><div id="lproom_rd2ea544cc48ac2ab2-l" class="lproom_rd2ea544cc48ac2ab2-l frm w100 p10 pt " room="rd2ea544cc48ac2ab2-l" name="6º B EF " imgsrc="https://edusp-static.ip.tv/webinar/edusp/room_avatar.png"><div><img id="lproom_img_rd2ea544cc48ac2ab2-l" src="https://edusp-static.ip.tv/webinar/edusp/room_avatar.png" class="cp lpchi room" room="rd2ea544cc48ac2ab2-l" name="6º B EF "></div><div class="fc fig pl5 fig "><div class="fr w100 room" room="rd2ea544cc48ac2ab2-l" name="6º B EF "><span class="lpcn sn toj fic">6º B EF </span><span class="fig"></span></div></div><div class="material-icons room-list-menu-tasks tdg" room="rd2ea544cc48ac2ab2-l">assignment</div></div></div><div id="listRoomsBtn" style="cursor: pointer; display: flex; justify-content: space-evenly; align-items: center; margin: 0px auto; background-color: rgb(26, 57, 117); min-width: 250px; height: 56px; border-radius: 10px; padding: 16px 24px; position: absolute; bottom: 25px; right: 20px;"><div>
        <svg width="25" height="24" viewBox="0 0 25 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <mask id="mask0_1337_336" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="25" height="24">
                <rect x="0.5" width="24" height="24" fill="#D9D9D9"></rect>
            </mask>
            <g mask="url(#mask0_1337_336)">
                <path d="M12.5 20C10.2667 20 8.375 19.225 6.825 17.675C5.275 16.125 4.5 14.2333 4.5 12C4.5 9.76667 5.275 7.875 6.825 6.325C8.375 4.775 10.2667 4 12.5 4C13.65 4 14.75 4.2375 15.8 4.7125C16.85 5.1875 17.75 5.86667 18.5 6.75V5C18.5 4.71667 18.5958 4.47917 18.7875 4.2875C18.9792 4.09583 19.2167 4 19.5 4C19.7833 4 20.0208 4.09583 20.2125 4.2875C20.4042 4.47917 20.5 4.71667 20.5 5V10C20.5 10.2833 20.4042 10.5208 20.2125 10.7125C20.0208 10.9042 19.7833 11 19.5 11H14.5C14.2167 11 13.9792 10.9042 13.7875 10.7125C13.5958 10.5208 13.5 10.2833 13.5 10C13.5 9.71667 13.5958 9.47917 13.7875 9.2875C13.9792 9.09583 14.2167 9 14.5 9H17.7C17.1667 8.06667 16.4375 7.33333 15.5125 6.8C14.5875 6.26667 13.5833 6 12.5 6C10.8333 6 9.41667 6.58333 8.25 7.75C7.08333 8.91667 6.5 10.3333 6.5 12C6.5 13.6667 7.08333 15.0833 8.25 16.25C9.41667 17.4167 10.8333 18 12.5 18C13.6333 18 14.6708 17.7125 15.6125 17.1375C16.5542 16.5625 17.2833 15.7917 17.8 14.825C17.9333 14.5917 18.1208 14.4292 18.3625 14.3375C18.6042 14.2458 18.85 14.2417 19.1 14.325C19.3667 14.4083 19.5583 14.5833 19.675 14.85C19.7917 15.1167 19.7833 15.3667 19.65 15.6C18.9667 16.9333 17.9917 18 16.725 18.8C15.4583 19.6 14.05 20 12.5 20Z" fill="#FEFEFE"></path>
            </g>
        </svg></div><span id="contentListRoomsBtn" style="color: rgb(255, 255, 255); font-weight: 600; letter-spacing: 0.5px; font-family: roboto, sans-serif; font-size: 16px;">Atualizar lista de turmas</span></div></div>
      </div>
      <div id="roomDetailArea" class="fc w100 h100 pr20 pb20" style="min-height: 100%;background: rgb(74 90 119);flex-wrap: wrap;" room="rd2ea544cc48ac2ab2-l" name="6º B EF ">
        <div id="roomDetailH" class="frm fig w100" style="border-bottom: solid 1px #ccc; margin-bottom: 10px;max-height:60px;">
            <div id="roomDetailClose" class="sxl tg pt p10">X</div>
            <div id="roomDetailChannel" class="fig p10 sl toj b">4º Ano 3 </div>
            <div id="roomDetailInfo" class="sxxl p10 tg material-icons">info_outline</div>
        </div>
        <div id="roomDetailB" class="w100 fig fr" style="justify-content: center;flex-wrap: wrap;position:absolute;margin-top:80px;background: rgb(161 167 201);"><div id="roomDetailTest" class="bor br sha fc pt p10 hovbgw __web-inspector-hide-shortcut__" style="width: 180px;height:180px;margin:5px;"><div class="fic" style="margin:10px;"><img id="roomDetailTestImg" src="https://assets.ip.tv/webchat/edusp/prova_paulista.png" style="width:100px;"></div><div class="fic sl toj b i18n-tests">Prova Paulista</div></div><div id="roomDetailEssay" class="bor br sha fc pt p10 hovbgw __web-inspector-hide-shortcut__" style="width: 180px;height:180px;margin:5px;"><div class="fic" style="margin:10px;"><img id="roomDetailEssayImg" src="https://assets.ip.tv/webchat/edusp/redacao_paulista.png" style="width:100px;"></div><div class="fic sl toj b i18n-essay">Redação Paulista</div></div><div id="roomDetailTms" class="bor br sha fc pt p10 hovbgw __web-inspector-hide-shortcut__" style="width: 180px;height:180px;margin:5px;"><div class="fcm fic" style="margin:10px;width:100px;height:100px"><div class="sxxl p10 toj material-icons" style="font-size:50px;">assignment</div></div><div class="fic sl toj b i18n-tasks"><span style="font-size:16px;">Provas<br>Atividades</span></div></div><div id="roomDetailConference" class="bor br sha fc pt p10 hovbgw __web-inspector-hide-shortcut__" style="width: 180px;height:180px;margin:5px;"><div class="fcm fic" style="margin:10px;width:100px;height:100px"><div class="sxxl p10 toj material-icons" style="font-size:50px;">videocam</div></div><div class="fic sl toj b i18n-conference">Sala de Aula Virtual</div></div><div id="roomDetailMural" class="bor br sha fc pt p10 hovbgw __web-inspector-hide-shortcut__" style="width: 180px;height:180px;margin:5px;"><div class="fcm fic" style="margin:10px;width:100px;height:100px"><div class="sxxl p10 toj material-icons" style="font-size:50px;">campaign</div></div><div class="fic sl toj b i18n-mural">Mural</div></div><div class="room-card bor br sha fc pt p10 hovbgw __web-inspector-hide-shortcut__" style="width: 180px;height:180px;margin:5px;" type="link" url="https://repositorio.educacao.sp.gov.br/Autenticacao?t={{seducsp_token}}" label="Material Digital" embeddable="false" name="rd2ea544cc48ac2ab2-l" topic="6º B EF " url_placeholders="[&quot;seducsp_token&quot;]"><div class="fcm fic" style="margin:10px;width:100px;height:100px"><div class="p10"><img src="https://s3.sa-east-1.amazonaws.com/edusp-static.ip.tv/room/cards/edusp/elianemararod3272389-sp/Yo942kdkKE76Er4MVg2PwsXexmAUEk.png" style="max-width:100px;max-height:100px;"></div></div><div class="fic sl toj b" style="text-align:center;">Material Digital</div></div><div class="room-card bor br sha fc pt p10 hovbgw __web-inspector-hide-shortcut__" style="width: 280px;height:180px;margin:5px;" type="link" url="https://www.matific.com/api/v2/integrations/login?vendor_id=25&amp;vendor_token={{seducsp_token}}" label="Matific" embeddable="false" name="rd2ea544cc48ac2ab2-l" topic="6º B EF " url_placeholders="[&quot;seducsp_token&quot;]"><div class="fcm fic" style="margin:10px;width:100px;height:100px"><div class="p10"><img src="https://s3.sa-east-1.amazonaws.com/edusp-static.ip.tv/room/cards/edusp/julianasanche3225895-sp/VDJKB7A43QWgudrnkkxj81OZMa6SkG.jpg" style="max-width:100px;max-height:100px;"></div></div><div class="fic sl toj b" style="text-align:center;">Matific</div></div><div class="room-card bor br sha fc pt p10 hovbgw" style="width: 280px;height:180px;margin:5px;" type="link" url="https://blog.elefanteletrado.com.br/" label="Leia SP" embeddable="false" name="rd2ea544cc48ac2ab2-l" topic="6º B EF " url_placeholders="[&quot;seducsp_token&quot;]"><div class="fcm fic" style="margin:10px;width:100px;height:100px"><div class="p10"><img src="https://play-lh.googleusercontent.com/rop_zQ7l_IdrR0V4FDvGViWmjGcRkGPHYe0cmMLoWPZ3ZkFdM7IVrZDpT2PM66tdMzg" style="max-width:100px;max-height:100px;"></div></div><div class="fic sl toj b" style="text-align:center;">Elefante Letrado</div></div><div class="room-card bor br sha fc pt p10 hovbgw" style="width: 280px;height:180px;margin:5px;" type="link" url="https://www.limeira.sp.gov.br" label="REDASP" embeddable="true" name="rd2ea544cc48ac2ab2-l" topic="6º B EF " url_placeholders="[&quot;auth_token&quot;,&quot;room_name&quot;]"><div class="fcm fic" style="margin:10px;width:100px;height:100px"><div class="p10"><img src="https://www.limeira.sp.gov.br/Arquitetura/Imagens/prefeitura/brasao.png" style="max-width:100px;max-height:100px;"></div></div><div class="fic sl toj b" style="text-align:center;">SMDE</div></div><div class="room-card bor br sha fc pt p10 hovbgw" style="width: 280px;height:180px;margin:5px;" type="link" url="https://rachacuca.com.br/" label="Alura" embeddable="false" name="rd2ea544cc48ac2ab2-l" topic="6º B EF " url_placeholders="[&quot;seducsp_token&quot;]"><div class="fcm fic" style="margin:10px;width:100px;height:100px"><div class="p10"><img src="https://rachacuca.com.br/static/images/rachacuca-logo-menu.png" style="max-width:100px;max-height:100px;"></div></div><div class="fic sl toj b" style="text-align:center;">Racha Cuca</div></div><div class="room-card bor br sha fc pt p10 hovbgw" style="width: 280px;height:180px;margin:5px;" type="link" url="https://sme.limeira.sp.gov.br/index_v2.php" label="Tarefa SP" embeddable="true" name="rd2ea544cc48ac2ab2-l" topic="6º B EF " url_placeholders="[&quot;room_name&quot;,&quot;auth_token&quot;]"><div class="fcm fic" style="margin:10px;width:100px;height:100px"><div class="p10"><img src="https://i.imgur.com/I0B4xlq.png" style="max-width:100px;max-height:100px;"></div></div><div class="fic sl toj b" style="text-align:center;">Tarefas</div></div><div class="room-card bor br sha fc pt p10 hovbgw" style="width: 280px;height:180px;margin:5px;" type="link" url="https://sme.limeira.sp.gov.br/avaliaonline/avaliacao_redir.php?tipo=AVA" label="Prova de Recuperação" embeddable="true" name="rd2ea544cc48ac2ab2-l" topic="6º B EF " url_placeholders="[&quot;auth_token&quot;,&quot;room_name&quot;]"><div class="fcm fic" style="margin:10px;width:100px;height:100px"><div class="p10"><img src="https://sme.limeira.sp.gov.br/2020_imagens/menu/online1.png" style="max-width:100px;max-height:100px;"></div></div><div class="fic sl toj b" style="text-align:center;">Avaliação online</div></div></div>
      </div>
      <div id="channelBody" class="w100 h100 fr" style="position:absolute;display:none;">
        <div id="channel_lp" class="h100 bgb" style="width:70%;min-width: 50%;max-width:70%;z-index: 1;">
          <div id="rpchn" class="ch fc z10 sha" style="display: none;">
            <div id="session-recording" class="fcm bgr tw p10 ss" style="display:none;position:absolute;left:10px;top:70px;z-index:99;border-radius:17px;">
                <span class="material-icons sn">radio_button_checked</span><span class="pl5 i18n-session-recording">Gravando</span>
            </div>
            <div id="session-timer" class="fcm bgbl tw p10 ss" style="display:none;position:absolute;right:10px;top:70px;z-index:99;border-radius:17px;">
                <span id="session-timer-icon" class="material-icons sxl pl10">access_time</span><span id="session-timer-value" class="pl5 pr10"></span>
            </div>
            <div id="alert-display" class="fcm bgw tr p10 ss" style="display:none;position:absolute;left:0px;top:70px;z-index:99;">
                <span id="alert-display-icon" class="material-icons sxl"></span><span id="alert-display-message" class="pl10 pl5 pr5"></span>
            </div>
            <div id="alert-time-remaining" class="fcm bgw tr p5 ss" style="display:none;position:absolute;right:10px;top:125px;z-index:99;">
                <span class="material-icons sxl">alarm_on</span><span class="pl5 i18n-session-time-remaining pl5 pr5">Faltam 2 minutos para o fim da aula</span>
            </div>
            <div id="alert-session-do-not-leave" class="fcm bgw tr p5 ss" style="display:none;position:absolute;right:10px;top:125px;z-index:99;">
                <span class="material-icons sxl">highlight_off</span><span class="pl5 i18n-session-do-not-leave pl5 pr5">Para sair da turma é preciso primeiro finalizar a aula. Clique no botão "Finalizar aula"</span>
            </div>
            <div id="alert-transmission-safari" class="fcm bgw tr p5 ss" style="display:none;position:absolute;right:5px;top:65px;z-index:99;">
                <span class="material-icons">highlight_off</span><span class="pl5 i18n-session-safari-not-supported">O navegador utilizado ainda não suporta o recurso de iniciar aula. Tente novamente em outro navegador!</span>
            </div>
            <div id="alert-transmission-firefox" class="fcm bgw tr p5 ss" style="display:none;position:absolute;right:5px;top:65px;z-index:99;">
                <span class="material-icons">highlight_off</span><span class="pl5 i18n-session-firefox-not-supported">O navegador utilizado ainda não suporta o recurso de iniciar aula. Tente novamente em outro navegador!</span>
            </div>
            <div id="alert-transmission" class="fcm bgw toj p5 ss" style="display:none;position:absolute;right:5px;top:65px;z-index:99;">
                <span class="material-icons">highlight_off</span><span class="pl5 i18n-session-need-for-transmission">Para transmitir primeiro inicie a aula!</span>
            </div>
            <div id="alert-closed-caption-chrome" class="fcm bgw tr p5 ss" style="display:none;position:absolute;right:5px;top:65px;z-index:99;">
                <span class="material-icons">highlight_off</span><span class="pl5 i18n-closed-caption-chrome-only">Legendas apenas suportado pelo navegador Chrome</span>
            </div>
            <div class="bglg w100 fr tg chnmax" style="height:60px;min-height:60px;">
              <div class="fr fic pl10">
                <img id="rpchni" src="https://edusp-static.ip.tv/webinar/common/img/avatarChannel.png" class="cp rphi" onerror="loadDefaultAvatar(this);">
                <div class="pl10 fc fig fic">
                  <div id="rpchnc" class="sn toj rphn"></div>
                  <div id="rpchnn" class="sxs l"></div>
                </div>
              </div>
              <div class="fig"></div>
              <div class="fic fc">
                <div class="fir">
                  <div id="rpchnctrl" class="fic fr" style="height:30px">
                    <div id="chn-session-is-active-btn" class="i18n-session-is-active fic tw bgbl ss bt" style="display:none;margin-right:20px;background-color:#707070;padding-right:30px;padding-left:30px;padding-top:5px;padding-bottom:5px;">Aula em andamento</div>
                    <div id="chn-session-stop-btn" class="i18n-session-stop fic tw ss bt pt" style="display:none;margin-right:20px;background-color:#FF8A30;padding-right:30px;padding-left:30px;padding-top:5px;padding-bottom:5px;">Finalizar Aula</div>
                    <div id="chn-session-continue-btn" class="i18n-session-continue fic tw bgbl ss bt pt" style="display:none;margin-right:20px;background-color:#61C428;padding-right:30px;padding-left:30px;padding-top:5px;padding-bottom:5px;">Continuar Aula</div>
                    <div id="chn-session-start-btn" class="i18n-session-start fic tw bgbl ss bt pt" style="display:none;background-color:#61C428;padding-right:30px;padding-left:30px;padding-top:5px;padding-bottom:5px;">Iniciar Aula</div>
                    <div id="selfMediaControl" class="frm" style="margin-right:20px;width:250px;height:28px;display:none;">
                      <div id="mediaAudio" class="p10 tw pt" style="width:120px;">
                        <div id="audioOff" class="fcm">
                          <div class="p5 sxxl tg material-icons"></div>
                          <div class="i18n-enable-microphone p5 sxs tg">Ativar Microfone</div>
                        </div>
                        <div id="audioOn" class="fcm">
                          <div class="p5 sxxl tr material-icons"></div>
                          <div class="i18n-disable-microphone p5 sxs tg">Desativar Microfone</div>
                        </div>
                      </div>
                      <div id="mediaVideo" class="p10 tw pt" style="width:120px;">
                        <div id="videoOff" class="fcm">
                          <div class="p5 sxxl tg material-icons"></div>
                          <div class="i18n-enable-camera p5 sxs tg">Ativar Câmera</div>
                        </div>
                        <div id="videoOn" class="fcm">
                          <div class="p5 sxxl tr material-icons"></div>
                          <div class="i18n-disable-camera p5 sxs tg">Desativar Câmera</div>
                        </div>
                      </div>
                    </div>
                    <div id="rpchnhi" class="fic sl tg material-icons ic_collaborate" style="margin-right:20px;"></div>
                    <div id="medias-view-config" class="fic" style="margin-right:20px;position:relative;">
                      <div id="medias-view-config-btn" class="frm pt" style="width:28px;display:none;">
                          <div id="medias-view-config-grid" class="medias-view-config-icon tg fr" style="width:24px;height:24px;flex-wrap:wrap;">
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;margin-right:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;margin-right:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;margin-right:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;margin-right:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;margin-right:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;margin-right:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;border-radius:2px;"></div>
                          </div>
                          <div id="medias-view-config-bottom" class="medias-view-config-icon tg fr" style="width:24px;height:24px;flex-wrap:wrap;display:none;">
                              <div class="bgdg" style="width:7px;height:7px;margin-right:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-right:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-right:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:23px;height:16px;margin-top:1px;border-radius:2px;"></div>
                          </div>
                          <div id="medias-view-config-left" class="medias-view-config-icon tg fc" style="width:24px;height:24px;flex-wrap:wrap;display:none;">
                              <div class="bgdg" style="width:16px;height:23px;margin-top:1px;margin-right:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;border-radius:2px;"></div>
                              <div class="bgdg" style="width:7px;height:7px;margin-top:1px;border-radius:2px;"></div>
                          </div>
                      </div>
                      <div id="medias-view-options" class="fc bgw bor br p5 ss" style="position:absolute;right:5px;z-index:999;width:250px;display:none;">
                          <div id="medias-view-option-grid" class="p5 fr w100 pt">
                              <div id="medias-view-grid-selected" class="medias-view-selected sn material-icons" style="margin-top:2px;min-width:21px;">check</div>
                              <div class="i18n-default fig">Padrão</div>
                              <div class="tg fr" style="width:18px;height:18px;flex-wrap:wrap;">
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;margin-right:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;margin-right:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;margin-right:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;margin-right:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;margin-right:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;margin-right:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;"></div>
                              </div>
                          </div>
                          <div id="medias-view-option-bottom" class="p5 fr w100 pt">
                              <div id="medias-view-bottom-selected" class="medias-view-selected sn material-icons" style="margin-top:2px;min-width:21px;"></div>
                              <div class="i18n-screen-bottom fig">Tela para baixo</div>
                              <div class="tg fr" style="width:18px;height:18px;flex-wrap:wrap;">
                                  <div class="bgdg" style="width:5px;height:5px;margin-right:1px;border-radius:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-right:1px;border-radius:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-right:1px;border-radius:1px;"></div>
                                  <div class="bgdg" style="width:17px;height:12px;margin-top:1px;border-radius:1px;"></div>
                              </div>
                          </div>
                          <div id="medias-view-option-left" class="p5 fr w100 pt">
                              <div id="medias-view-left-selected" class="medias-view-selected sn material-icons" style="margin-top:2px;min-width:21px;"></div>
                              <div class="i18n-screen-left fig">Tela para a esquerda</div>
                              <div id="medias-view-screen-left" class="tg fc" style="width:18px;height:18px;flex-wrap:wrap;">
                                  <div class="bgdg" style="width:12px;height:17px;margin-top:1px;margin-right:1px;border-radius:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;border-radius:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;border-radius:1px;"></div>
                                  <div class="bgdg" style="width:5px;height:5px;margin-top:1px;border-radius:1px;"></div>
                              </div>
                          </div>
                      </div>
                    </div>
                    <div id="breakoutroom-options" class="fic" style="position:relative;">
                      <div id="breakoutroom-options-btn" class="frm pt sxxl p10 tg material-icons-round" style="margin-right:20px;width:28px;">
                       grid_view
                      </div>
                      <div id="breakoutroom-options-area" class="fc bgw bor br p5 ss" style="position:absolute;right:5px;z-index:999;width:250px;max-height:400px;overflow:auto;">
                      </div>
                    </div>
                    <div id="rpchnpi" class="fic pr5 sxxl tg material-icons rd"></div>
                    <div id="rpchnp" class="fic sxs tg lpchu pr5" style="padding-right:20px;">0</div>
                    <div id="rpchnui" class="fic pr5 sxxl tg material-icons rd" style="display:none;"></div>
                    <div id="rpchnu" class="fic sxs tg lpchu pr10" style="padding-right:20px;display:none;">0</div>
                    <div id="channel_max_icon" class="fic sxl material-icons pr5 rd" zoom="0" style="display:none;"></div>
                    <div id="channel_invite_icon" class="fic sxxl material-icons pr5 rd" zoom="0" style="display:none;margin-right:20px;">link</div>
                    <div id="channel_close" class="fic pr5 sxxl material-icons ic_exit rd" style="margin-right:20px;"></div>
                    <div id="channelChatHide" class="channelChat fic pr10 sxxl tg material-icons rd"></div>
                    <div id="channelChatShow" class="channelChat fic pr10 sxxl tg material-icons" style="display:none;"></div>
                  </div>
                </div>
              </div>
            </div>
            <div id="boxesArea" class="fr fig h100 w100 " style="position: relative; height: 0px;">
              <div id="pollArea" class="fic h100 w100 fcm" style="position:absolute;z-index:99;display:none;">
                <div class="fic bgw sha fc" style="min-width:300px;max-width:70%;border-radius: 20px;">
                  <div id="pollRewardResult" class="fc p20 w100" style="display:none;">
                    <div id="pollRewardTopLabel" class="i18n-congratulations-you-won fic bgdgr tw pl20 pr20 pt10 pb10 br" style="margin-top:15px;">Parabéns você venceu!</div>
                    <div id="pollTrophyWinner" class="pollTrophyWinner fic" style="display:block;margin-top:15px;"><img class="pollTrophyWinnerImg" src="" style="width:150px;height:150px;"></div>
                    <div id="pollTrophyLooser" class="pollTrophyLooser fic" style="display:none;margin-top:15px;"><img class="poolTropyLooserImg" src="" style="width:150px;height:150px;"></div>
                    <div id="pollRewardPoints" class="fic bor sha sxs pt5 pb5 pl20 pr20 bglg" style="border-radius:30px;margin-top:15px;margin-bottom:15px;"><span id="pollRewardPointsValue">99</span></div>
                    <div class="fic frm p10 bor" style="margin:20px;border-left:0px;border-right:0px;border-top-width:2px;border-bottom-width:2px;">
                        <div class="pollTrophyWinner"><img class="pollTrophyWinnerImg" src="" style="width:40px;height:40px;"></div>
                        <div class="pollTrophyLooser"><img class="poolTropyLooserImg" src="" style="width:40px;height:40px;"></div>
                        <div id="pollTrophyMessage" class="p10 ss toj" style="text-align:center;">Você e mais XX participantes<br>foram vencedores</div>
                    </div>
                    <div id="pollRewardButton" class="i18n-close fic br bgdbl tw p10 pt" style="border-radius:30px;padding-left:50px;padding-right:50px;margin-bottom:15px;">Fechar</div>
                  </div>

                  <div id="pollTopBar" class="tdg frm w100" style="padding-top:15px;padding-left:15px;padding-right:15px;padding-bottom:0px;">
                    <div id="pollSeq" class="pl5 bgw" style="text-align:center;border:1px solid #666;border-radius:50%;display:block;width:auto;height:auto;padding:5px;min-width:35px;">99</div>
                    <div class="fig"></div>
                    <div id="pollPlayers" class="frm pr10 ss"><span class="material-icons sxl tdg"></span><span id="pollPlayersValue">999</span></div>
                    <div id="pollLifes" class="frm pr5 ss"><span class="material-icons sxl tr"></span><span id="pollLifesValue">9</span></div>
                  </div>

                  <div id="pollTimeArea" class="fcm w100 p10 sn bgw b tg" style="border-radius:20px;">
                    <div style="position:relative;height:100px;width:100px;margin-top:25px;">
                        <svg viewBox="0 0 100 100" style="transform:scaleX(-1);">
                            <g style="fill:none;stroke:none;">
                                <circle cx="50" cy="50" r="45" style="stroke-width:7px; stroke:grey;"></circle>
                                <path id="pollTimeRemaining" stroke-dasharray="283 283" d="M 50, 50 m -45, 0 a 45,45 0 1,0 90,0 a 45,45 0 1,0 -90,0" style="stroke-width:7px;stroke-linecap:round;transform:rotate(90deg);transform-origin:center;transition: 1s linear all;stroke: #1BC37B;"></path>
                            </g>
                        </svg>
                        <span id="pollTime" style="position:absolute;width:100px;height:100px;top:0;display:flex;align-items:center;justify-content:center;font-size:28px;"></span>
                    </div>
                  </div>
                  <div class="pollResultLabel frm w100" style="margin-top:25px;">
                    <div id="pollResultLabel" class="pollResultLabel fic p10 ss bgdgr tw" style="text-align:center;padding-left:40px;padding-right:40px;border-radius:20px;">Resultado</div>
                  </div>
                  <div id="pollEliminatedArea" class="fc bg p10 w100">
                    <div class="pollUseLife fc fic bgg br p10">
                        <div class="fic material-icons tr p10" style="font-size:5rem;"></div>
                        <div class="fic p10"><span class="i18n-use-your-extra-life-and-keep-playing">Utilize a sua vida extra e continue <br>jogando</span></div>
                        <div id="pollUseLife" class="i18n-use-extra-life pollUseLife fic bgdbl tw pl20 pr20 pt5 pb5 ss pt br">Utilizar vida extra</div>
                    </div>
                    <div id="pollEliminatedContinue" class="i18n-keep-watching fic bgw tdg bor br pt p10" style="margin:20px;">Continuar assistindo</div>
                  </div>
                  <div id="pollTitle" class="w100 p10 sn tg b br" style="text-align:center;margin-top:15px;"></div>
                  <div class="fr w100 h100 pollOptionArea" style="margin-top:15px;padding-left:15px;padding-right:15px;">
                    <div id="pollOption0" class="pollOption p0 sl bgw br fig w100 h100" option="0" style="position:relative;margin-bottom:15px;">
                      <div id="pollBackground0" class="p10 bgdlg h100" style="position:absolute;border-radius: 20px;width: 100%;"></div>
                      <div id="pollResult0" class="p10 bgdgr h100" style="position:absolute;border-radius: 20px;width: 50%;"></div>
                      <div class="p10 br w100 h100 fr" style="position:relative">
                        <div id="pollOptionText0" class="fig tw ss pl10 pr10" style="max-width:90%"></div>
                        <div id="pollValue0" class="pollValue tk ss" style="display:none;min-width:50px;text-align:right;"></div>
                      </div>
                    </div>
                  </div>
                  <div class="fr w100 h100 pollOptionArea" style="padding-left:15px;padding-right:15px;">
                    <div id="pollOption1" class="pollOption p0 sl bgw br fig w100 h100" option="1" style="position:relative;margin-bottom:15px;">
                      <div id="pollBackground1" class="p10 bgdlg h100" style="position:absolute;border-radius: 20px;width: 100%;"></div>
                      <div id="pollResult1" class="p10 bgdgr h100" style="position:absolute;border-radius: 20px;width: 50%;"></div>
                      <div class="p10 br w100 h100 fr" style="position:relative">
                        <div id="pollOptionText1" class="fig tw ss pl10 pr10" style="max-width:90%"></div>
                        <div id="pollValue1" class="pollValue tk ss" style="display:none;min-width:50px;text-align:right;"></div>
                      </div>
                    </div>
                  </div>
                  <div class="fr w100 h100 pollOptionArea" style="margin-bottom:10px;padding-left:15px;padding-right:15px;">
                    <div id="pollOption2" class="pollOption p0 sl bgw br fig w100 h100" option="2" style="position:relative;margin-bottom:15px;">
                      <div id="pollBackground2" class="p10 bgdlg h100" style="position:absolute;border-radius: 20px;width: 100%;"></div>
                      <div id="pollResult2" class="p10 bgdgr h100" style="position:absolute;border-radius: 20px;width: 50%;"></div>
                      <div class="p10 br w100 h100 fr" style="position:relative">
                        <div id="pollOptionText2" class="fig tw ss pl10 pr10" style="max-width:90%"></div>
                        <div id="pollValue2" class="pollValue tk ss" style="display:none;min-width:50px;text-align:right;"></div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div id="featuredImg" class="fcm fic w100 bgb" style="position:absolute;z-index:9;display:none;">
                <img src="" class="w100">
              </div>
              <div id="metaverse-area" class="w100 h100 frm fic" style="position:relative;flex-wrap:wrap;max-height:inherit;display:none;"></div>
              <div id="medias" class="w100 frm fic" style="position:relative;flex-wrap:wrap;height:inherit;max-height:inherit;display:none;"></div>
              <div id="dbint" class="frm h100 w100" style="display:none;position:absolute;z-index:999;">
                <div class="fcm fic h100 w100">
                    <div class="fic db" style="min-width:400px;width:400px;min-height:240px;height:240px;">
                        <div class="fc modal-content w100 p10">
                            <div class="i18n-session-interrupted pb10 pl10 toj sxl" style="text-align:center;">A aula foi interrompida inesperadamente e poderá ser retomada pelo professor em até:</div>
                            <div class="bor w100" style="height:1px;"></div>
                            <div id="dbint_counter" class="fic tb p10" style="font-size:73px;"></div>
                          </div>
                    </div>
                </div>
              </div>
            </div>
            <div id="media-cc" class="media-cc fr w100 pl20 pr20 sn" style="position:relative;height:100px;min-height:20px;display:none;">
                <div id="media-cc-interim" class="fic tw"></div>
                <div id="media-cc-body-area" class="fr w100" style="height:100%;overflow:auto;z-index:10;"><div id="media-cc-body" class="fc fic tw w100"></div></div>
            </div>

            <div id="user-media-cc" class="material-icons sxxl tw pl20" style="position:absolute;right:20px;top:80px;z-index:98;display:none;">subtitles</div>

            <div id="user-media-control" class="frm w100" style="height:64px;min-height:50px;position:relative;background-color:#222222;display:none;">
                <div class="fig"></div>
                <div id="user-media-mic" class="material-icons sxxl tw bor brr" style="padding:5px;border-color:#707070;background-color:#707070;"></div>
                <div style="width:16px;"></div>
                <div id="user-media-cam" class="material-icons sxxl tw bor brr" style="padding:5px;border-color:#707070;background-color:#707070;"></div>
                <div style="width:16px;"></div>
                <div id="control-screensharing-area" style="position:relative;">
                    <div id="control-screensharing-stop" class="bgw br" style="top:-53px;left:0px;position: absolute;height:40px;min-height:40px;width:204px;z-index:11;display:none;border-radius:4px;">
                        <div class="p5 frm w100 pt">
                          <div class="fic material-icons sxl tbl p5 pl10 pr10"></div>
                          <div class="i18n-stop-presentation fic ss tbl" style="text-align:center;">Parar Apresentação</div>
                          <div class="fig"></div>
                        </div>
                      </div>
                    <div id="control-screensharing" class="material-icons sxxl tw bor brr" style="padding:5px;border-color:#707070;background-color:#707070;" "="">present_to_all</div>
                </div>
                <div style="width:16px;"></div>
                <div style="position:relative;">
                    <div id="control-more-area" class="p5 bgw br" style="top:-111px;left:0px;position: absolute;width:180px;z-index:11;display:none;border-radius:4px;">
                        <div id="record-option" class="p5 frm w100 pt" style="display:none;">
                            <div id="record-option-icon" class="fic material-icons sxl tbl p5 pl10 pr10">radio_button_checked</div>
                            <div id="record-option-start" class="i18n-record-start fic ss tbl" style="text-align:center;display:none;">Iniciar Gravação</div>
                            <div id="record-option-stop" class="i18n-record-stop fic ss tbl" style="text-align:center;display:none;">Parar Gravação</div>
                            <div class="fig"></div>
                          </div>
                        <div id="display-define-layout" class="p5 frm w100 pt">
                          <div class="display-define-layout fic material-icons sxl tbl p5 pl10 pr10">dashboard</div>
                          <div class="display-define-layout i18n-display-define-layout fic ss tbl" style="text-align:center;">Definir Layout</div>
                          <div class="fig"></div>
                        </div>
                        <div id="cc-select" class="p5 frm w100 pt" style="display:none;">
                            <div class="fic material-icons sxl tbl p5 pl10 pr10">closed_caption</div>
                            <div class="fic fc">
                                <div class="i18n-closed-caption fic ss tbl" style="text-align:center;">Legendas</div>
                                <div id="cc-status" class="fic sxs tg" style="text-align:center;">Desativado</div>
                            </div>
                            <div class="fig"></div>
                        </div>
                    </div>
                    <div id="control-display" class="material-icons sxxl tw bor brr" style="padding:5px;border-color:#707070;background-color:#707070;display:none;" "="">more_vert</div>
                </div>
                <div class="fig"></div>
            </div>

            <div class="fig w100 bgw " style="overflow:auto; display:none">
            </div>
            <div class="chnprivchatsarea ss w100 frr" style="position:absolute;bottom:0px;height:0px;width:360px;">
            <div id="chnprivchatsarea" class="frr" style="z-index:11;width:300px;"></div>
            <div style="width:50px;z-index:11;">
                <div id="chnprivchats" class="fr bor brtl brtr bglg sha pl5 pr5" style="width: 40px; height: 60px; text-align: center; margin-right: 10px; position: relative; z-index: 10; display: none;">
                  <div id="chnprivchatslist" class="bgw bor br p5 fc z9" style="position:absolute;left:30px;bottom:50px;display:none;width:max-content;"></div>
                  <div id="chnopenprivchats" class="chnprivchats pt bor tw bgr br pl5 pr5 sxxs" style="position:absolute;right:0px;top:10px;display:none;"></div>
                  <div class="fic sxxl tg material-icons chnprivchats pt"></div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div id="channel_mp" style="width:15px;cursor:ew-resize;background-color:transparent;z-index:2;margin-left:-5px">
          <div id="channel_mp_handle" class="h100" style="width:5px;background-color:transparent;z-index:3;margin-left:5px;"></div>
        </div>
        <div id="channel_rp" class="h100 fc chnmax" style="width:30%;position:relative;flex:1;z-index:1;margin-left:-10px;">
          <div id="channelEmoticon" class="w100" style="display: none; z-index: 19;" t="__Channel__">
            <div id="channelEmoticonHeader" class="fr w100"><span id="emoticonMenu_recent" class="emoticonMenu emoticonMenu_recent material-icons material-icons tg" type="recent"></span><span id="emoticonMenu_smiles_people" class="emoticonMenu emoticonMenu_smiles_people material-icons material-icons tg" type="smiles_people"></span><span id="emoticonMenu_animals_nature" class="emoticonMenu emoticonMenu_animals_nature material-icons material-icons tg" type="animals_nature"></span><span id="emoticonMenu_food_drink" class="emoticonMenu emoticonMenu_food_drink material-icons material-icons tg" type="food_drink"></span><span id="emoticonMenu_activity" class="emoticonMenu emoticonMenu_activity material-icons material-icons tg" type="activity"></span><span id="emoticonMenu_travel_places" class="emoticonMenu emoticonMenu_travel_places material-icons material-icons tg" type="travel_places"></span><span id="emoticonMenu_objects" class="emoticonMenu emoticonMenu_objects material-icons material-icons tg" type="objects"></span><span id="emoticonMenu_simbols" class="emoticonMenu emoticonMenu_simbols material-icons material-icons tg" type="simbols"></span><span id="emoticonMenu_flags" class="emoticonMenu emoticonMenu_flags material-icons material-icons tg" type="flags"></span><div class="fig"></div><div class="emoticons_close pt" t="undefined">X</div></div>
            <div id="channelEmoticonBody"><div id="emoticon_smiles_people" class="emoticon emoticon_smiles_people toj" type="smiles_people">Emojis &amp; Pessoas</div><div class="emoticonItem" type="smiles_people">😀</div><div class="emoticonItem" type="smiles_people">😃</div><div class="emoticonItem" type="smiles_people">😄</div><div class="emoticonItem" type="smiles_people">😁</div><div class="emoticonItem" type="smiles_people">😆</div><div class="emoticonItem" type="smiles_people">😅</div><div class="emoticonItem" type="smiles_people">😂</div><div class="emoticonItem" type="smiles_people">🤣</div><div class="emoticonItem" type="smiles_people">😊</div><div class="emoticonItem" type="smiles_people">☺️</div><div class="emoticonItem" type="smiles_people">😇</div><div class="emoticonItem" type="smiles_people">🙂</div><div class="emoticonItem" type="smiles_people">🙃</div><div class="emoticonItem" type="smiles_people">😉</div><div class="emoticonItem" type="smiles_people">😌</div><div class="emoticonItem" type="smiles_people">😍</div><div class="emoticonItem" type="smiles_people">😘</div><div class="emoticonItem" type="smiles_people">😗</div><div class="emoticonItem" type="smiles_people">😙</div><div class="emoticonItem" type="smiles_people">😚</div><div class="emoticonItem" type="smiles_people">😋</div><div class="emoticonItem" type="smiles_people">😛</div><div class="emoticonItem" type="smiles_people">😝</div><div class="emoticonItem" type="smiles_people">😜</div><div class="emoticonItem" type="smiles_people">🤓</div><div class="emoticonItem" type="smiles_people">😎</div><div class="emoticonItem" type="smiles_people">😏</div><div class="emoticonItem" type="smiles_people">😒</div><div class="emoticonItem" type="smiles_people">😞</div><div class="emoticonItem" type="smiles_people">😔</div><div class="emoticonItem" type="smiles_people">😟</div><div class="emoticonItem" type="smiles_people">😕</div><div class="emoticonItem" type="smiles_people">🙁</div><div class="emoticonItem" type="smiles_people">☹️</div><div class="emoticonItem" type="smiles_people">😣</div><div class="emoticonItem" type="smiles_people">😖</div><div class="emoticonItem" type="smiles_people">😫</div><div class="emoticonItem" type="smiles_people">😩</div><div class="emoticonItem" type="smiles_people">😢</div><div class="emoticonItem" type="smiles_people">😭</div><div class="emoticonItem" type="smiles_people">😤</div><div class="emoticonItem" type="smiles_people">😠</div><div class="emoticonItem" type="smiles_people">😡</div><div class="emoticonItem" type="smiles_people">😳</div><div class="emoticonItem" type="smiles_people">😱</div><div class="emoticonItem" type="smiles_people">😨</div><div class="emoticonItem" type="smiles_people">😰</div><div class="emoticonItem" type="smiles_people">😥</div><div class="emoticonItem" type="smiles_people">😓</div><div class="emoticonItem" type="smiles_people">🤗</div><div class="emoticonItem" type="smiles_people">🤔</div><div class="emoticonItem" type="smiles_people">🤥</div><div class="emoticonItem" type="smiles_people">😶</div><div class="emoticonItem" type="smiles_people">😐</div><div class="emoticonItem" type="smiles_people">😑</div><div class="emoticonItem" type="smiles_people">😬</div><div class="emoticonItem" type="smiles_people">🙄</div><div class="emoticonItem" type="smiles_people">😯</div><div class="emoticonItem" type="smiles_people">😦</div><div class="emoticonItem" type="smiles_people">😧</div><div class="emoticonItem" type="smiles_people">😮</div><div class="emoticonItem" type="smiles_people">😲</div><div class="emoticonItem" type="smiles_people">😴</div><div class="emoticonItem" type="smiles_people">🤤</div><div class="emoticonItem" type="smiles_people">😪</div><div class="emoticonItem" type="smiles_people">😵</div><div class="emoticonItem" type="smiles_people">🤐</div><div class="emoticonItem" type="smiles_people">🤢</div><div class="emoticonItem" type="smiles_people">🤧</div><div class="emoticonItem" type="smiles_people">😷</div><div class="emoticonItem" type="smiles_people">🤒</div><div class="emoticonItem" type="smiles_people">🤕</div><div class="emoticonItem" type="smiles_people">🤑</div><div class="emoticonItem" type="smiles_people">🤠</div><div class="emoticonItem" type="smiles_people">😈</div><div class="emoticonItem" type="smiles_people">👿</div><div class="emoticonItem" type="smiles_people">👹</div><div class="emoticonItem" type="smiles_people">👺</div><div class="emoticonItem" type="smiles_people">🤡</div><div class="emoticonItem" type="smiles_people">💩</div><div class="emoticonItem" type="smiles_people">👻</div><div class="emoticonItem" type="smiles_people">💀</div><div class="emoticonItem" type="smiles_people">👽</div><div class="emoticonItem" type="smiles_people">👾</div><div class="emoticonItem" type="smiles_people">🤖</div><div class="emoticonItem" type="smiles_people">🎃</div><div class="emoticonItem" type="smiles_people">😺</div><div class="emoticonItem" type="smiles_people">😸</div><div class="emoticonItem" type="smiles_people">😹</div><div class="emoticonItem" type="smiles_people">😻</div><div class="emoticonItem" type="smiles_people">😼</div><div class="emoticonItem" type="smiles_people">😽</div><div class="emoticonItem" type="smiles_people">🙀</div><div class="emoticonItem" type="smiles_people">😿</div><div class="emoticonItem" type="smiles_people">😾</div><div class="emoticonItem" type="smiles_people">👐</div><div class="emoticonItem" type="smiles_people">🙌</div><div class="emoticonItem" type="smiles_people">👏</div><div class="emoticonItem" type="smiles_people">🤝</div><div class="emoticonItem" type="smiles_people">👍</div><div class="emoticonItem" type="smiles_people">👎</div><div class="emoticonItem" type="smiles_people">👊</div><div class="emoticonItem" type="smiles_people">✊</div><div class="emoticonItem" type="smiles_people">🤛</div><div class="emoticonItem" type="smiles_people">🤜</div><div class="emoticonItem" type="smiles_people">🤞</div><div class="emoticonItem" type="smiles_people">🤘</div><div class="emoticonItem" type="smiles_people">👌</div><div class="emoticonItem" type="smiles_people">👈</div><div class="emoticonItem" type="smiles_people">👉</div><div class="emoticonItem" type="smiles_people">👆</div><div class="emoticonItem" type="smiles_people">👇</div><div class="emoticonItem" type="smiles_people">✋</div><div class="emoticonItem" type="smiles_people">🤚</div><div class="emoticonItem" type="smiles_people">🖐</div><div class="emoticonItem" type="smiles_people">🖖</div><div class="emoticonItem" type="smiles_people">👋</div><div class="emoticonItem" type="smiles_people">🤙</div><div class="emoticonItem" type="smiles_people">💪</div><div class="emoticonItem" type="smiles_people">🖕</div><div class="emoticonItem" type="smiles_people">✍️</div><div class="emoticonItem" type="smiles_people">🙏</div><div class="emoticonItem" type="smiles_people">💍</div><div class="emoticonItem" type="smiles_people">💄</div><div class="emoticonItem" type="smiles_people">💋</div><div class="emoticonItem" type="smiles_people">👄</div><div class="emoticonItem" type="smiles_people">👅</div><div class="emoticonItem" type="smiles_people">👂</div><div class="emoticonItem" type="smiles_people">👃</div><div class="emoticonItem" type="smiles_people">👣</div><div class="emoticonItem" type="smiles_people">👁</div><div class="emoticonItem" type="smiles_people">👀</div><div class="emoticonItem" type="smiles_people">🗣</div><div class="emoticonItem" type="smiles_people">👤</div><div class="emoticonItem" type="smiles_people">👥</div><div class="emoticonItem" type="smiles_people">👶</div><div class="emoticonItem" type="smiles_people">👧</div><div class="emoticonItem" type="smiles_people">👦</div><div class="emoticonItem" type="smiles_people">👩</div><div class="emoticonItem" type="smiles_people">👨</div><div class="emoticonItem" type="smiles_people">👱&zwj;♀</div><div class="emoticonItem" type="smiles_people">👱&zwj;♂</div><div class="emoticonItem" type="smiles_people">👵</div><div class="emoticonItem" type="smiles_people">👴</div><div class="emoticonItem" type="smiles_people">👲</div><div class="emoticonItem" type="smiles_people">👳&zwj;♀</div><div class="emoticonItem" type="smiles_people">👳&zwj;♂</div><div class="emoticonItem" type="smiles_people">👮&zwj;♀</div><div class="emoticonItem" type="smiles_people">👮&zwj;♂</div><div class="emoticonItem" type="smiles_people">👷&zwj;♀</div><div class="emoticonItem" type="smiles_people">👷&zwj;♂</div><div class="emoticonItem" type="smiles_people">💂&zwj;♀</div><div class="emoticonItem" type="smiles_people">💂&zwj;♂</div><div class="emoticonItem" type="smiles_people">🕵&zwj;♀</div><div class="emoticonItem" type="smiles_people">🕵&zwj;♂</div><div class="emoticonItem" type="smiles_people">👩&zwj;⚕</div><div class="emoticonItem" type="smiles_people">👨&zwj;⚕</div><div class="emoticonItem" type="smiles_people">👩&zwj;🌾</div><div class="emoticonItem" type="smiles_people">👨&zwj;🌾</div><div class="emoticonItem" type="smiles_people">👩&zwj;🍳</div><div class="emoticonItem" type="smiles_people">👨&zwj;🍳</div><div class="emoticonItem" type="smiles_people">👩&zwj;🎓</div><div class="emoticonItem" type="smiles_people">👨&zwj;🎓</div><div class="emoticonItem" type="smiles_people">👩&zwj;🎤</div><div class="emoticonItem" type="smiles_people">👨&zwj;🎤</div><div class="emoticonItem" type="smiles_people">👩&zwj;🏫</div><div class="emoticonItem" type="smiles_people">👨&zwj;🏫</div><div class="emoticonItem" type="smiles_people">👩&zwj;🏭</div><div class="emoticonItem" type="smiles_people">👨&zwj;🏭</div><div class="emoticonItem" type="smiles_people">👩&zwj;💻</div><div class="emoticonItem" type="smiles_people">👨&zwj;💻</div><div class="emoticonItem" type="smiles_people">👩&zwj;💼</div><div class="emoticonItem" type="smiles_people">👨&zwj;💼</div><div class="emoticonItem" type="smiles_people">👩&zwj;🔧</div><div class="emoticonItem" type="smiles_people">👨&zwj;🔧</div><div class="emoticonItem" type="smiles_people">👩&zwj;🔬</div><div class="emoticonItem" type="smiles_people">👨&zwj;🔬</div><div class="emoticonItem" type="smiles_people">👩&zwj;🎨</div><div class="emoticonItem" type="smiles_people">👨&zwj;🎨</div><div class="emoticonItem" type="smiles_people">👩&zwj;🚒</div><div class="emoticonItem" type="smiles_people">👨&zwj;🚒</div><div class="emoticonItem" type="smiles_people">👩&zwj;✈</div><div class="emoticonItem" type="smiles_people">👨&zwj;✈</div><div class="emoticonItem" type="smiles_people">👩&zwj;🚀</div><div class="emoticonItem" type="smiles_people">👨&zwj;🚀</div><div class="emoticonItem" type="smiles_people">👩&zwj;⚖</div><div class="emoticonItem" type="smiles_people">👨&zwj;⚖</div><div class="emoticonItem" type="smiles_people">👰</div><div class="emoticonItem" type="smiles_people">🤵</div><div class="emoticonItem" type="smiles_people">👸</div><div class="emoticonItem" type="smiles_people">🤴</div><div class="emoticonItem" type="smiles_people">🤶</div><div class="emoticonItem" type="smiles_people">🎅</div><div class="emoticonItem" type="smiles_people">👼</div><div class="emoticonItem" type="smiles_people">🤰</div><div class="emoticonItem" type="smiles_people">🙇&zwj;♀</div><div class="emoticonItem" type="smiles_people">🙇&zwj;♂</div><div class="emoticonItem" type="smiles_people">💁&zwj;♀</div><div class="emoticonItem" type="smiles_people">💁&zwj;♂</div><div class="emoticonItem" type="smiles_people">🙅&zwj;♀</div><div class="emoticonItem" type="smiles_people">🙅&zwj;♂</div><div class="emoticonItem" type="smiles_people">🙆&zwj;♀</div><div class="emoticonItem" type="smiles_people">🙆&zwj;♂</div><div class="emoticonItem" type="smiles_people">🙋&zwj;♀</div><div class="emoticonItem" type="smiles_people">🙋&zwj;♂</div><div class="emoticonItem" type="smiles_people">🤦&zwj;♀</div><div class="emoticonItem" type="smiles_people">🤦&zwj;♂</div><div class="emoticonItem" type="smiles_people">🤷&zwj;♀</div><div class="emoticonItem" type="smiles_people">🤷&zwj;♂</div><div class="emoticonItem" type="smiles_people">🙎&zwj;♀</div><div class="emoticonItem" type="smiles_people">🙎&zwj;♂</div><div class="emoticonItem" type="smiles_people">🙍&zwj;♀</div><div class="emoticonItem" type="smiles_people">🙍&zwj;♂</div><div class="emoticonItem" type="smiles_people">💇&zwj;♀</div><div class="emoticonItem" type="smiles_people">💇&zwj;♂</div><div class="emoticonItem" type="smiles_people">💆&zwj;♀</div><div class="emoticonItem" type="smiles_people">💆&zwj;♂</div><div class="emoticonItem" type="smiles_people">💅</div><div class="emoticonItem" type="smiles_people">🤳</div><div class="emoticonItem" type="smiles_people">💃</div><div class="emoticonItem" type="smiles_people">🕺</div><div class="emoticonItem" type="smiles_people">👯&zwj;♀</div><div class="emoticonItem" type="smiles_people">👯&zwj;♂</div><div class="emoticonItem" type="smiles_people">🕴</div><div class="emoticonItem" type="smiles_people">🚶&zwj;♀</div><div class="emoticonItem" type="smiles_people">🚶&zwj;♂</div><div class="emoticonItem" type="smiles_people">🏃&zwj;♀</div><div class="emoticonItem" type="smiles_people">🏃&zwj;♂</div><div class="emoticonItem" type="smiles_people">👫</div><div class="emoticonItem" type="smiles_people">👭</div><div class="emoticonItem" type="smiles_people">👬</div><div class="emoticonItem" type="smiles_people">💑</div><div class="emoticonItem" type="smiles_people">👩&zwj;❤&zwj;👩</div><div class="emoticonItem" type="smiles_people">👨&zwj;❤&zwj;👨</div><div class="emoticonItem" type="smiles_people">💏</div><div class="emoticonItem" type="smiles_people">👩&zwj;❤&zwj;💋&zwj;👩</div><div class="emoticonItem" type="smiles_people">👨&zwj;❤&zwj;💋&zwj;👨</div><div class="emoticonItem" type="smiles_people">👪</div><div class="emoticonItem" type="smiles_people">👨&zwj;👩&zwj;👧</div><div class="emoticonItem" type="smiles_people">👨&zwj;👩&zwj;👧&zwj;👦</div><div class="emoticonItem" type="smiles_people">👨&zwj;👩&zwj;👦&zwj;👦</div><div class="emoticonItem" type="smiles_people">👨&zwj;👩&zwj;👧&zwj;👧</div><div class="emoticonItem" type="smiles_people">👩&zwj;👩&zwj;👦</div><div class="emoticonItem" type="smiles_people">👩&zwj;👩&zwj;👧</div><div class="emoticonItem" type="smiles_people">👩&zwj;👩&zwj;👧&zwj;👦</div><div class="emoticonItem" type="smiles_people">👩&zwj;👩&zwj;👦&zwj;👦</div><div class="emoticonItem" type="smiles_people">👩&zwj;👩&zwj;👧&zwj;👧</div><div class="emoticonItem" type="smiles_people">👨&zwj;👨&zwj;👦</div><div class="emoticonItem" type="smiles_people">👨&zwj;👨&zwj;👧</div><div class="emoticonItem" type="smiles_people">👨&zwj;👨&zwj;👧&zwj;👦</div><div class="emoticonItem" type="smiles_people">👨&zwj;👨&zwj;👦&zwj;👦</div><div class="emoticonItem" type="smiles_people">👨&zwj;👨&zwj;👧&zwj;👧</div><div class="emoticonItem" type="smiles_people">👩&zwj;👦</div><div class="emoticonItem" type="smiles_people">👩&zwj;👧</div><div class="emoticonItem" type="smiles_people">👩&zwj;👧&zwj;👦</div><div class="emoticonItem" type="smiles_people">👩&zwj;👦&zwj;👦</div><div class="emoticonItem" type="smiles_people">👩&zwj;👧&zwj;👧</div><div class="emoticonItem" type="smiles_people">👨&zwj;👦</div><div class="emoticonItem" type="smiles_people">👨&zwj;👧</div><div class="emoticonItem" type="smiles_people">👨&zwj;👧&zwj;👦</div><div class="emoticonItem" type="smiles_people">👨&zwj;👦&zwj;👦</div><div class="emoticonItem" type="smiles_people">👨&zwj;👧&zwj;👧</div><div class="emoticonItem" type="smiles_people">👚</div><div class="emoticonItem" type="smiles_people">👕</div><div class="emoticonItem" type="smiles_people">👖</div><div class="emoticonItem" type="smiles_people">👔</div><div class="emoticonItem" type="smiles_people">👗</div><div class="emoticonItem" type="smiles_people">👙</div><div class="emoticonItem" type="smiles_people">👘</div><div class="emoticonItem" type="smiles_people">👠</div><div class="emoticonItem" type="smiles_people">👡</div><div class="emoticonItem" type="smiles_people">👢</div><div class="emoticonItem" type="smiles_people">👞</div><div class="emoticonItem" type="smiles_people">👟</div><div class="emoticonItem" type="smiles_people">🎩</div><div class="emoticonItem" type="smiles_people">👒</div><div class="emoticonItem" type="smiles_people">🎓</div><div class="emoticonItem" type="smiles_people">⛑</div><div class="emoticonItem" type="smiles_people">👑</div><div class="emoticonItem" type="smiles_people">👝</div><div class="emoticonItem" type="smiles_people">👛</div><div class="emoticonItem" type="smiles_people">👜</div><div class="emoticonItem" type="smiles_people">💼</div><div class="emoticonItem" type="smiles_people">🎒</div><div class="emoticonItem" type="smiles_people">👓</div><div class="emoticonItem" type="smiles_people">🕶</div><div class="emoticonItem" type="smiles_people">🌂</div><div id="emoticon_animals_nature" class="emoticon emoticon_animals_nature toj" type="animals_nature">Animais &amp; Natureza</div><div class="emoticonItem" type="animals_nature">🐶</div><div class="emoticonItem" type="animals_nature">🐱</div><div class="emoticonItem" type="animals_nature">🐭</div><div class="emoticonItem" type="animals_nature">🐹</div><div class="emoticonItem" type="animals_nature">🐰</div><div class="emoticonItem" type="animals_nature">🦊</div><div class="emoticonItem" type="animals_nature">🐻</div><div class="emoticonItem" type="animals_nature">🐼</div><div class="emoticonItem" type="animals_nature">🐨</div><div class="emoticonItem" type="animals_nature">🐯</div><div class="emoticonItem" type="animals_nature">🦁</div><div class="emoticonItem" type="animals_nature">🐮</div><div class="emoticonItem" type="animals_nature">🐷</div><div class="emoticonItem" type="animals_nature">🐽</div><div class="emoticonItem" type="animals_nature">🐸</div><div class="emoticonItem" type="animals_nature">🐵</div><div class="emoticonItem" type="animals_nature">🙈</div><div class="emoticonItem" type="animals_nature">🙉</div><div class="emoticonItem" type="animals_nature">🙊</div><div class="emoticonItem" type="animals_nature">🐒</div><div class="emoticonItem" type="animals_nature">🐔</div><div class="emoticonItem" type="animals_nature">🐧</div><div class="emoticonItem" type="animals_nature">🐦</div><div class="emoticonItem" type="animals_nature">🐤</div><div class="emoticonItem" type="animals_nature">🐣</div><div class="emoticonItem" type="animals_nature">🐥</div><div class="emoticonItem" type="animals_nature">🦆</div><div class="emoticonItem" type="animals_nature">🦅</div><div class="emoticonItem" type="animals_nature">🦉</div><div class="emoticonItem" type="animals_nature">🦇</div><div class="emoticonItem" type="animals_nature">🐺</div><div class="emoticonItem" type="animals_nature">🐗</div><div class="emoticonItem" type="animals_nature">🐴</div><div class="emoticonItem" type="animals_nature">🦄</div><div class="emoticonItem" type="animals_nature">🐝</div><div class="emoticonItem" type="animals_nature">🐛</div><div class="emoticonItem" type="animals_nature">🦋</div><div class="emoticonItem" type="animals_nature">🐌</div><div class="emoticonItem" type="animals_nature">🐚</div><div class="emoticonItem" type="animals_nature">🐞</div><div class="emoticonItem" type="animals_nature">🐜</div><div class="emoticonItem" type="animals_nature">🕷</div><div class="emoticonItem" type="animals_nature">🕸</div><div class="emoticonItem" type="animals_nature">🦂</div><div class="emoticonItem" type="animals_nature">🐢</div><div class="emoticonItem" type="animals_nature">🐍</div><div class="emoticonItem" type="animals_nature">🦎</div><div class="emoticonItem" type="animals_nature">🐙</div><div class="emoticonItem" type="animals_nature">🦑</div><div class="emoticonItem" type="animals_nature">🦐</div><div class="emoticonItem" type="animals_nature">🦀</div><div class="emoticonItem" type="animals_nature">🐡</div><div class="emoticonItem" type="animals_nature">🐠</div><div class="emoticonItem" type="animals_nature">🐟</div><div class="emoticonItem" type="animals_nature">🐬</div><div class="emoticonItem" type="animals_nature">🐳</div><div class="emoticonItem" type="animals_nature">🐋</div><div class="emoticonItem" type="animals_nature">🦈</div><div class="emoticonItem" type="animals_nature">🐊</div><div class="emoticonItem" type="animals_nature">🐅</div><div class="emoticonItem" type="animals_nature">🐆</div><div class="emoticonItem" type="animals_nature">🦍</div><div class="emoticonItem" type="animals_nature">🐘</div><div class="emoticonItem" type="animals_nature">🦏</div><div class="emoticonItem" type="animals_nature">🐪</div><div class="emoticonItem" type="animals_nature">🐫</div><div class="emoticonItem" type="animals_nature">🐃</div><div class="emoticonItem" type="animals_nature">🐂</div><div class="emoticonItem" type="animals_nature">🐄</div><div class="emoticonItem" type="animals_nature">🐎</div><div class="emoticonItem" type="animals_nature">🐖</div><div class="emoticonItem" type="animals_nature">🐏</div><div class="emoticonItem" type="animals_nature">🐑</div><div class="emoticonItem" type="animals_nature">🐐</div><div class="emoticonItem" type="animals_nature">🦌</div><div class="emoticonItem" type="animals_nature">🐕</div><div class="emoticonItem" type="animals_nature">🐩</div><div class="emoticonItem" type="animals_nature">🐈</div><div class="emoticonItem" type="animals_nature">🐓</div><div class="emoticonItem" type="animals_nature">🦃</div><div class="emoticonItem" type="animals_nature">🕊</div><div class="emoticonItem" type="animals_nature">🐇</div><div class="emoticonItem" type="animals_nature">🐁</div><div class="emoticonItem" type="animals_nature">🐀</div><div class="emoticonItem" type="animals_nature">🐿</div><div class="emoticonItem" type="animals_nature">🐾</div><div class="emoticonItem" type="animals_nature">🐉</div><div class="emoticonItem" type="animals_nature">🐲</div><div class="emoticonItem" type="animals_nature">🌵</div><div class="emoticonItem" type="animals_nature">🎄</div><div class="emoticonItem" type="animals_nature">🌲</div><div class="emoticonItem" type="animals_nature">🌳</div><div class="emoticonItem" type="animals_nature">🌴</div><div class="emoticonItem" type="animals_nature">🌱</div><div class="emoticonItem" type="animals_nature">🌿</div><div class="emoticonItem" type="animals_nature">☘️</div><div class="emoticonItem" type="animals_nature">🍀</div><div class="emoticonItem" type="animals_nature">🎍</div><div class="emoticonItem" type="animals_nature">🎋</div><div class="emoticonItem" type="animals_nature">🍃</div><div class="emoticonItem" type="animals_nature">🍂</div><div class="emoticonItem" type="animals_nature">🍁</div><div class="emoticonItem" type="animals_nature">🍄</div><div class="emoticonItem" type="animals_nature">🌾</div><div class="emoticonItem" type="animals_nature">💐</div><div class="emoticonItem" type="animals_nature">🌷</div><div class="emoticonItem" type="animals_nature">🌹</div><div class="emoticonItem" type="animals_nature">🥀</div><div class="emoticonItem" type="animals_nature">🌺</div><div class="emoticonItem" type="animals_nature">🌸</div><div class="emoticonItem" type="animals_nature">🌼</div><div class="emoticonItem" type="animals_nature">🌻</div><div class="emoticonItem" type="animals_nature">🌞</div><div class="emoticonItem" type="animals_nature">🌝</div><div class="emoticonItem" type="animals_nature">🌛</div><div class="emoticonItem" type="animals_nature">🌜</div><div class="emoticonItem" type="animals_nature">🌚</div><div class="emoticonItem" type="animals_nature">🌕</div><div class="emoticonItem" type="animals_nature">🌖</div><div class="emoticonItem" type="animals_nature">🌗</div><div class="emoticonItem" type="animals_nature">🌘</div><div class="emoticonItem" type="animals_nature">🌑</div><div class="emoticonItem" type="animals_nature">🌒</div><div class="emoticonItem" type="animals_nature">🌓</div><div class="emoticonItem" type="animals_nature">🌔</div><div class="emoticonItem" type="animals_nature">🌙</div><div class="emoticonItem" type="animals_nature">🌎</div><div class="emoticonItem" type="animals_nature">🌍</div><div class="emoticonItem" type="animals_nature">🌏</div><div class="emoticonItem" type="animals_nature">💫</div><div class="emoticonItem" type="animals_nature">⭐</div><div class="emoticonItem" type="animals_nature">🌟</div><div class="emoticonItem" type="animals_nature">✨</div><div class="emoticonItem" type="animals_nature">⚡️</div><div class="emoticonItem" type="animals_nature">☄️</div><div class="emoticonItem" type="animals_nature">💥</div><div class="emoticonItem" type="animals_nature">🔥</div><div class="emoticonItem" type="animals_nature">🌪</div><div class="emoticonItem" type="animals_nature">🌈</div><div class="emoticonItem" type="animals_nature">☀</div><div class="emoticonItem" type="animals_nature">🌤</div><div class="emoticonItem" type="animals_nature">⛅</div><div class="emoticonItem" type="animals_nature">🌥</div><div class="emoticonItem" type="animals_nature">🌦</div><div class="emoticonItem" type="animals_nature">🌧</div><div class="emoticonItem" type="animals_nature">⛈</div><div class="emoticonItem" type="animals_nature">🌩</div><div class="emoticonItem" type="animals_nature">🌨</div><div class="emoticonItem" type="animals_nature">❄️</div><div class="emoticonItem" type="animals_nature">☃️</div><div class="emoticonItem" type="animals_nature">⛄</div><div class="emoticonItem" type="animals_nature">🌬</div><div class="emoticonItem" type="animals_nature">💨</div><div class="emoticonItem" type="animals_nature">💧</div><div class="emoticonItem" type="animals_nature">💦</div><div class="emoticonItem" type="animals_nature">☔️</div><div class="emoticonItem" type="animals_nature">☂️</div><div class="emoticonItem" type="animals_nature">🌊</div><div class="emoticonItem" type="animals_nature">🌫</div><div id="emoticon_food_drink" class="emoticon emoticon_food_drink toj" type="food_drink">Comida &amp; Bebida</div><div class="emoticonItem" type="food_drink">🍏</div><div class="emoticonItem" type="food_drink">🍎</div><div class="emoticonItem" type="food_drink">🍐</div><div class="emoticonItem" type="food_drink">🍊</div><div class="emoticonItem" type="food_drink">🍋</div><div class="emoticonItem" type="food_drink">🍌</div><div class="emoticonItem" type="food_drink">🍉</div><div class="emoticonItem" type="food_drink">🍇</div><div class="emoticonItem" type="food_drink">🍓</div><div class="emoticonItem" type="food_drink">🍈</div><div class="emoticonItem" type="food_drink">🍒</div><div class="emoticonItem" type="food_drink">🍑</div><div class="emoticonItem" type="food_drink">🍍</div><div class="emoticonItem" type="food_drink">🥝</div><div class="emoticonItem" type="food_drink">🍅</div><div class="emoticonItem" type="food_drink">🍆</div><div class="emoticonItem" type="food_drink">🥑</div><div class="emoticonItem" type="food_drink">🥒</div><div class="emoticonItem" type="food_drink">🌶</div><div class="emoticonItem" type="food_drink">🌽</div><div class="emoticonItem" type="food_drink">🥕</div><div class="emoticonItem" type="food_drink">🥔</div><div class="emoticonItem" type="food_drink">🍠</div><div class="emoticonItem" type="food_drink">🥐</div><div class="emoticonItem" type="food_drink">🍞</div><div class="emoticonItem" type="food_drink">🥖</div><div class="emoticonItem" type="food_drink">🧀</div><div class="emoticonItem" type="food_drink">🥚</div><div class="emoticonItem" type="food_drink">🍳</div><div class="emoticonItem" type="food_drink">🥞</div><div class="emoticonItem" type="food_drink">🥓</div><div class="emoticonItem" type="food_drink">🍗</div><div class="emoticonItem" type="food_drink">🍖</div><div class="emoticonItem" type="food_drink">🌭</div><div class="emoticonItem" type="food_drink">🍔</div><div class="emoticonItem" type="food_drink">🍟</div><div class="emoticonItem" type="food_drink">🍕</div><div class="emoticonItem" type="food_drink">🥙</div><div class="emoticonItem" type="food_drink">🌮</div><div class="emoticonItem" type="food_drink">🌯</div><div class="emoticonItem" type="food_drink">🥗</div><div class="emoticonItem" type="food_drink">🥘</div><div class="emoticonItem" type="food_drink">🍝</div><div class="emoticonItem" type="food_drink">🍜</div><div class="emoticonItem" type="food_drink">🍲</div><div class="emoticonItem" type="food_drink">🍛</div><div class="emoticonItem" type="food_drink">🍣</div><div class="emoticonItem" type="food_drink">🍱</div><div class="emoticonItem" type="food_drink">🍤</div><div class="emoticonItem" type="food_drink">🍙</div><div class="emoticonItem" type="food_drink">🍚</div><div class="emoticonItem" type="food_drink">🍘</div><div class="emoticonItem" type="food_drink">🍥</div><div class="emoticonItem" type="food_drink">🍢</div><div class="emoticonItem" type="food_drink">🍡</div><div class="emoticonItem" type="food_drink">🍧</div><div class="emoticonItem" type="food_drink">🍨</div><div class="emoticonItem" type="food_drink">🍦</div><div class="emoticonItem" type="food_drink">🍰</div><div class="emoticonItem" type="food_drink">🎂</div><div class="emoticonItem" type="food_drink">🍮</div><div class="emoticonItem" type="food_drink">🍭</div><div class="emoticonItem" type="food_drink">🍬</div><div class="emoticonItem" type="food_drink">🍫</div><div class="emoticonItem" type="food_drink">🍿</div><div class="emoticonItem" type="food_drink">🍩</div><div class="emoticonItem" type="food_drink">🍪</div><div class="emoticonItem" type="food_drink">🌰</div><div class="emoticonItem" type="food_drink">🥜</div><div class="emoticonItem" type="food_drink">🍯</div><div class="emoticonItem" type="food_drink">🥛</div><div class="emoticonItem" type="food_drink">🍼</div><div class="emoticonItem" type="food_drink">🍵</div><div class="emoticonItem" type="food_drink">🍶</div><div class="emoticonItem" type="food_drink">🍺</div><div class="emoticonItem" type="food_drink">🍻</div><div class="emoticonItem" type="food_drink">🥂</div><div class="emoticonItem" type="food_drink">🍷</div><div class="emoticonItem" type="food_drink">🥃</div><div class="emoticonItem" type="food_drink">🍸</div><div class="emoticonItem" type="food_drink">🍹</div><div class="emoticonItem" type="food_drink">🍾</div><div class="emoticonItem" type="food_drink">🥄</div><div class="emoticonItem" type="food_drink">🍴</div><div class="emoticonItem" type="food_drink">🍽</div><div id="emoticon_activity" class="emoticon emoticon_activity toj" type="activity">Atividade</div><div class="emoticonItem" type="activity">⚽</div><div class="emoticonItem" type="activity">🏀</div><div class="emoticonItem" type="activity">🏈</div><div class="emoticonItem" type="activity">⚾</div><div class="emoticonItem" type="activity">🎾</div><div class="emoticonItem" type="activity">🏐</div><div class="emoticonItem" type="activity">🏉</div><div class="emoticonItem" type="activity">🎱</div><div class="emoticonItem" type="activity">🏓</div><div class="emoticonItem" type="activity">🏸</div><div class="emoticonItem" type="activity">🥅</div><div class="emoticonItem" type="activity">🏒</div><div class="emoticonItem" type="activity">🏑</div><div class="emoticonItem" type="activity">🏏</div><div class="emoticonItem" type="activity">⛳</div><div class="emoticonItem" type="activity">🏹</div><div class="emoticonItem" type="activity">🎣</div><div class="emoticonItem" type="activity">🥊</div><div class="emoticonItem" type="activity">🥋</div><div class="emoticonItem" type="activity">🎽</div><div class="emoticonItem" type="activity">⛸</div><div class="emoticonItem" type="activity">🎿</div><div class="emoticonItem" type="activity">⛷</div><div class="emoticonItem" type="activity">🏂</div><div class="emoticonItem" type="activity">🏋&zwj;♀</div><div class="emoticonItem" type="activity">🏋&zwj;♂</div><div class="emoticonItem" type="activity">🤼&zwj;♀</div><div class="emoticonItem" type="activity">🤼&zwj;♂</div><div class="emoticonItem" type="activity">🤸&zwj;♀</div><div class="emoticonItem" type="activity">🤸&zwj;♂</div><div class="emoticonItem" type="activity">⛹&zwj;♀</div><div class="emoticonItem" type="activity">⛹&zwj;♂</div><div class="emoticonItem" type="activity">🤺</div><div class="emoticonItem" type="activity">🤾&zwj;♀</div><div class="emoticonItem" type="activity">🤾&zwj;♂</div><div class="emoticonItem" type="activity">🏌&zwj;♀</div><div class="emoticonItem" type="activity">🏌&zwj;♂</div><div class="emoticonItem" type="activity">🏇</div><div class="emoticonItem" type="activity">🏄&zwj;♀</div><div class="emoticonItem" type="activity">🏄&zwj;♂</div><div class="emoticonItem" type="activity">🏊&zwj;♀</div><div class="emoticonItem" type="activity">🏊&zwj;♂</div><div class="emoticonItem" type="activity">🤽&zwj;♀</div><div class="emoticonItem" type="activity">🤽&zwj;♂</div><div class="emoticonItem" type="activity">🚣&zwj;♀</div><div class="emoticonItem" type="activity">🚣&zwj;♂</div><div class="emoticonItem" type="activity">🚵&zwj;♀</div><div class="emoticonItem" type="activity">🚵&zwj;♂</div><div class="emoticonItem" type="activity">🚴&zwj;♀</div><div class="emoticonItem" type="activity">🚴&zwj;♂</div><div class="emoticonItem" type="activity">🏆</div><div class="emoticonItem" type="activity">🥇</div><div class="emoticonItem" type="activity">🥈</div><div class="emoticonItem" type="activity">🥉</div><div class="emoticonItem" type="activity">🏅</div><div class="emoticonItem" type="activity">🎖</div><div class="emoticonItem" type="activity">🏵</div><div class="emoticonItem" type="activity">🎗</div><div class="emoticonItem" type="activity">🎫</div><div class="emoticonItem" type="activity">🎟</div><div class="emoticonItem" type="activity">🎪</div><div class="emoticonItem" type="activity">🤹&zwj;♀</div><div class="emoticonItem" type="activity">🤹&zwj;♂</div><div class="emoticonItem" type="activity">🎭</div><div class="emoticonItem" type="activity">🎨</div><div class="emoticonItem" type="activity">🎬</div><div class="emoticonItem" type="activity">🎤</div><div class="emoticonItem" type="activity">🎧</div><div class="emoticonItem" type="activity">🎼</div><div class="emoticonItem" type="activity">🎹</div><div class="emoticonItem" type="activity">🥁</div><div class="emoticonItem" type="activity">🎷</div><div class="emoticonItem" type="activity">🎺</div><div class="emoticonItem" type="activity">🎸</div><div class="emoticonItem" type="activity">🎻</div><div class="emoticonItem" type="activity">🎲</div><div class="emoticonItem" type="activity">🎯</div><div class="emoticonItem" type="activity">🎳</div><div class="emoticonItem" type="activity">🎮</div><div class="emoticonItem" type="activity">🎰</div><div id="emoticon_travel_places" class="emoticon emoticon_travel_places toj" type="travel_places">Viagens &amp; Locais</div><div class="emoticonItem" type="travel_places">🚗</div><div class="emoticonItem" type="travel_places">🚕</div><div class="emoticonItem" type="travel_places">🚙</div><div class="emoticonItem" type="travel_places">🚌</div><div class="emoticonItem" type="travel_places">🚎</div><div class="emoticonItem" type="travel_places">🏎</div><div class="emoticonItem" type="travel_places">🚓</div><div class="emoticonItem" type="travel_places">🚑</div><div class="emoticonItem" type="travel_places">🚒</div><div class="emoticonItem" type="travel_places">🚐</div><div class="emoticonItem" type="travel_places">🚚</div><div class="emoticonItem" type="travel_places">🚛</div><div class="emoticonItem" type="travel_places">🚜</div><div class="emoticonItem" type="travel_places">🛴</div><div class="emoticonItem" type="travel_places">🚲</div><div class="emoticonItem" type="travel_places">🛵</div><div class="emoticonItem" type="travel_places">🏍</div><div class="emoticonItem" type="travel_places">🚨</div><div class="emoticonItem" type="travel_places">🚔</div><div class="emoticonItem" type="travel_places">🚍</div><div class="emoticonItem" type="travel_places">🚘</div><div class="emoticonItem" type="travel_places">🚖</div><div class="emoticonItem" type="travel_places">🚡</div><div class="emoticonItem" type="travel_places">🚠</div><div class="emoticonItem" type="travel_places">🚟</div><div class="emoticonItem" type="travel_places">🚃</div><div class="emoticonItem" type="travel_places">🚋</div><div class="emoticonItem" type="travel_places">🚞</div><div class="emoticonItem" type="travel_places">🚝</div><div class="emoticonItem" type="travel_places">🚄</div><div class="emoticonItem" type="travel_places">🚅</div><div class="emoticonItem" type="travel_places">🚈</div><div class="emoticonItem" type="travel_places">🚂</div><div class="emoticonItem" type="travel_places">🚆</div><div class="emoticonItem" type="travel_places">🚇</div><div class="emoticonItem" type="travel_places">🚊</div><div class="emoticonItem" type="travel_places">🚉</div><div class="emoticonItem" type="travel_places">✈️</div><div class="emoticonItem" type="travel_places">🛫</div><div class="emoticonItem" type="travel_places">🛬</div><div class="emoticonItem" type="travel_places">🛩</div><div class="emoticonItem" type="travel_places">💺</div><div class="emoticonItem" type="travel_places">🛰</div><div class="emoticonItem" type="travel_places">🚀</div><div class="emoticonItem" type="travel_places">🚁</div><div class="emoticonItem" type="travel_places">🛶</div><div class="emoticonItem" type="travel_places">⛵</div><div class="emoticonItem" type="travel_places">🚤</div><div class="emoticonItem" type="travel_places">🛥</div><div class="emoticonItem" type="travel_places">🛳</div><div class="emoticonItem" type="travel_places">⛴</div><div class="emoticonItem" type="travel_places">🚢</div><div class="emoticonItem" type="travel_places">⚓️</div><div class="emoticonItem" type="travel_places">⛽</div><div class="emoticonItem" type="travel_places">🚧</div><div class="emoticonItem" type="travel_places">🚦</div><div class="emoticonItem" type="travel_places">🚥</div><div class="emoticonItem" type="travel_places">🚏</div><div class="emoticonItem" type="travel_places">🗺</div><div class="emoticonItem" type="travel_places">🗿</div><div class="emoticonItem" type="travel_places">🗽</div><div class="emoticonItem" type="travel_places">🗼</div><div class="emoticonItem" type="travel_places">🏰</div><div class="emoticonItem" type="travel_places">🏯</div><div class="emoticonItem" type="travel_places">🏟</div><div class="emoticonItem" type="travel_places">🎡</div><div class="emoticonItem" type="travel_places">🎢</div><div class="emoticonItem" type="travel_places">🎠</div><div class="emoticonItem" type="travel_places">⛲</div><div class="emoticonItem" type="travel_places">⛱</div><div class="emoticonItem" type="travel_places">🏖</div><div class="emoticonItem" type="travel_places">🏝</div><div class="emoticonItem" type="travel_places">🏜</div><div class="emoticonItem" type="travel_places">🌋</div><div class="emoticonItem" type="travel_places">⛰</div><div class="emoticonItem" type="travel_places">🏔</div><div class="emoticonItem" type="travel_places">🗻</div><div class="emoticonItem" type="travel_places">🏕</div><div class="emoticonItem" type="travel_places">⛺</div><div class="emoticonItem" type="travel_places">🏠</div><div class="emoticonItem" type="travel_places">🏡</div><div class="emoticonItem" type="travel_places">🏘</div><div class="emoticonItem" type="travel_places">🏚</div><div class="emoticonItem" type="travel_places">🏗</div><div class="emoticonItem" type="travel_places">🏭</div><div class="emoticonItem" type="travel_places">🏢</div><div class="emoticonItem" type="travel_places">🏬</div><div class="emoticonItem" type="travel_places">🏣</div><div class="emoticonItem" type="travel_places">🏤</div><div class="emoticonItem" type="travel_places">🏥</div><div class="emoticonItem" type="travel_places">🏦</div><div class="emoticonItem" type="travel_places">🏨</div><div class="emoticonItem" type="travel_places">🏪</div><div class="emoticonItem" type="travel_places">🏫</div><div class="emoticonItem" type="travel_places">🏩</div><div class="emoticonItem" type="travel_places">💒</div><div class="emoticonItem" type="travel_places">🏛</div><div class="emoticonItem" type="travel_places">⛪</div><div class="emoticonItem" type="travel_places">🕌</div><div class="emoticonItem" type="travel_places">🕍</div><div class="emoticonItem" type="travel_places">🕋</div><div class="emoticonItem" type="travel_places">⛩</div><div class="emoticonItem" type="travel_places">🛤</div><div class="emoticonItem" type="travel_places">🛣</div><div class="emoticonItem" type="travel_places">🗾</div><div class="emoticonItem" type="travel_places">🎑</div><div class="emoticonItem" type="travel_places">🏞</div><div class="emoticonItem" type="travel_places">🌅</div><div class="emoticonItem" type="travel_places">🌄</div><div class="emoticonItem" type="travel_places">🌠</div><div class="emoticonItem" type="travel_places">🎇</div><div class="emoticonItem" type="travel_places">🎆</div><div class="emoticonItem" type="travel_places">🌇</div><div class="emoticonItem" type="travel_places">🌆</div><div class="emoticonItem" type="travel_places">🏙</div><div class="emoticonItem" type="travel_places">🌃</div><div class="emoticonItem" type="travel_places">🌌</div><div class="emoticonItem" type="travel_places">🌉</div><div class="emoticonItem" type="travel_places">🌁</div><div id="emoticon_objects" class="emoticon emoticon_objects toj" type="objects">Objetos</div><div class="emoticonItem" type="objects">⌚</div><div class="emoticonItem" type="objects">📱</div><div class="emoticonItem" type="objects">📲</div><div class="emoticonItem" type="objects">💻</div><div class="emoticonItem" type="objects">⌨️</div><div class="emoticonItem" type="objects">🖥</div><div class="emoticonItem" type="objects">🖨</div><div class="emoticonItem" type="objects">🖱</div><div class="emoticonItem" type="objects">🖲</div><div class="emoticonItem" type="objects">🕹</div><div class="emoticonItem" type="objects">🗜</div><div class="emoticonItem" type="objects">💽</div><div class="emoticonItem" type="objects">💾</div><div class="emoticonItem" type="objects">💿</div><div class="emoticonItem" type="objects">📀</div><div class="emoticonItem" type="objects">📼</div><div class="emoticonItem" type="objects">📷</div><div class="emoticonItem" type="objects">📸</div><div class="emoticonItem" type="objects">📹</div><div class="emoticonItem" type="objects">🎥</div><div class="emoticonItem" type="objects">📽</div><div class="emoticonItem" type="objects">🎞</div><div class="emoticonItem" type="objects">📞</div><div class="emoticonItem" type="objects">☎️</div><div class="emoticonItem" type="objects">📟</div><div class="emoticonItem" type="objects">📠</div><div class="emoticonItem" type="objects">📺</div><div class="emoticonItem" type="objects">📻</div><div class="emoticonItem" type="objects">🎙</div><div class="emoticonItem" type="objects">🎚</div><div class="emoticonItem" type="objects">🎛</div><div class="emoticonItem" type="objects">⏱</div><div class="emoticonItem" type="objects">⏲</div><div class="emoticonItem" type="objects">⏰</div><div class="emoticonItem" type="objects">🕰</div><div class="emoticonItem" type="objects">⌛</div><div class="emoticonItem" type="objects">⏳</div><div class="emoticonItem" type="objects">📡</div><div class="emoticonItem" type="objects">🔋</div><div class="emoticonItem" type="objects">🔌</div><div class="emoticonItem" type="objects">💡</div><div class="emoticonItem" type="objects">🔦</div><div class="emoticonItem" type="objects">🕯</div><div class="emoticonItem" type="objects">🗑</div><div class="emoticonItem" type="objects">🛢</div><div class="emoticonItem" type="objects">💸</div><div class="emoticonItem" type="objects">💵</div><div class="emoticonItem" type="objects">💴</div><div class="emoticonItem" type="objects">💶</div><div class="emoticonItem" type="objects">💷</div><div class="emoticonItem" type="objects">💰</div><div class="emoticonItem" type="objects">💳</div><div class="emoticonItem" type="objects">💎</div><div class="emoticonItem" type="objects">🔧</div><div class="emoticonItem" type="objects">🔨</div><div class="emoticonItem" type="objects">⚒</div><div class="emoticonItem" type="objects">🛠</div><div class="emoticonItem" type="objects">⛏</div><div class="emoticonItem" type="objects">🔩</div><div class="emoticonItem" type="objects">⚙️</div><div class="emoticonItem" type="objects">⛓</div><div class="emoticonItem" type="objects">🔫</div><div class="emoticonItem" type="objects">💣</div><div class="emoticonItem" type="objects">🔪</div><div class="emoticonItem" type="objects">🗡</div><div class="emoticonItem" type="objects">⚔️</div><div class="emoticonItem" type="objects">🛡</div><div class="emoticonItem" type="objects">🚬</div><div class="emoticonItem" type="objects">⚰️</div><div class="emoticonItem" type="objects">⚱️</div><div class="emoticonItem" type="objects">🏺</div><div class="emoticonItem" type="objects">🔮</div><div class="emoticonItem" type="objects">📿</div><div class="emoticonItem" type="objects">💈</div><div class="emoticonItem" type="objects">⚗️</div><div class="emoticonItem" type="objects">🔭</div><div class="emoticonItem" type="objects">🔬</div><div class="emoticonItem" type="objects">🕳</div><div class="emoticonItem" type="objects">💊</div><div class="emoticonItem" type="objects">💉</div><div class="emoticonItem" type="objects">🌡</div><div class="emoticonItem" type="objects">🚽</div><div class="emoticonItem" type="objects">🚰</div><div class="emoticonItem" type="objects">🚿</div><div class="emoticonItem" type="objects">🛁</div><div class="emoticonItem" type="objects">🛀</div><div class="emoticonItem" type="objects">🛎</div><div class="emoticonItem" type="objects">🔑</div><div class="emoticonItem" type="objects">🗝</div><div class="emoticonItem" type="objects">🚪</div><div class="emoticonItem" type="objects">🛋</div><div class="emoticonItem" type="objects">🛏</div><div class="emoticonItem" type="objects">🛌</div><div class="emoticonItem" type="objects">🖼</div><div class="emoticonItem" type="objects">🛍</div><div class="emoticonItem" type="objects">🛒</div><div class="emoticonItem" type="objects">🎁</div><div class="emoticonItem" type="objects">🎈</div><div class="emoticonItem" type="objects">🎏</div><div class="emoticonItem" type="objects">🎀</div><div class="emoticonItem" type="objects">🎊</div><div class="emoticonItem" type="objects">🎉</div><div class="emoticonItem" type="objects">🎎</div><div class="emoticonItem" type="objects">🏮</div><div class="emoticonItem" type="objects">🎐</div><div class="emoticonItem" type="objects">📩</div><div class="emoticonItem" type="objects">📨</div><div class="emoticonItem" type="objects">📧</div><div class="emoticonItem" type="objects">💌</div><div class="emoticonItem" type="objects">📥</div><div class="emoticonItem" type="objects">📤</div><div class="emoticonItem" type="objects">📦</div><div class="emoticonItem" type="objects">🏷</div><div class="emoticonItem" type="objects">📪</div><div class="emoticonItem" type="objects">📫</div><div class="emoticonItem" type="objects">📬</div><div class="emoticonItem" type="objects">📭</div><div class="emoticonItem" type="objects">📮</div><div class="emoticonItem" type="objects">📯</div><div class="emoticonItem" type="objects">📜</div><div class="emoticonItem" type="objects">📃</div><div class="emoticonItem" type="objects">📄</div><div class="emoticonItem" type="objects">📑</div><div class="emoticonItem" type="objects">📊</div><div class="emoticonItem" type="objects">📈</div><div class="emoticonItem" type="objects">📉</div><div class="emoticonItem" type="objects">🗒</div><div class="emoticonItem" type="objects">🗓</div><div class="emoticonItem" type="objects">📆</div><div class="emoticonItem" type="objects">📅</div><div class="emoticonItem" type="objects">📇</div><div class="emoticonItem" type="objects">🗃</div><div class="emoticonItem" type="objects">🗳</div><div class="emoticonItem" type="objects">🗄</div><div class="emoticonItem" type="objects">📋</div><div class="emoticonItem" type="objects">📁</div><div class="emoticonItem" type="objects">📂</div><div class="emoticonItem" type="objects">🗂</div><div class="emoticonItem" type="objects">🗞</div><div class="emoticonItem" type="objects">📰</div><div class="emoticonItem" type="objects">📓</div><div class="emoticonItem" type="objects">📔</div><div class="emoticonItem" type="objects">📒</div><div class="emoticonItem" type="objects">📕</div><div class="emoticonItem" type="objects">📗</div><div class="emoticonItem" type="objects">📘</div><div class="emoticonItem" type="objects">📙</div><div class="emoticonItem" type="objects">📚</div><div class="emoticonItem" type="objects">📖</div><div class="emoticonItem" type="objects">🔖</div><div class="emoticonItem" type="objects">🔗</div><div class="emoticonItem" type="objects">📎</div><div class="emoticonItem" type="objects">🖇</div><div class="emoticonItem" type="objects">📐</div><div class="emoticonItem" type="objects">📏</div><div class="emoticonItem" type="objects">📌</div><div class="emoticonItem" type="objects">📍</div><div class="emoticonItem" type="objects">🖊</div><div class="emoticonItem" type="objects">🖋</div><div class="emoticonItem" type="objects">✒️</div><div class="emoticonItem" type="objects">🖌</div><div class="emoticonItem" type="objects">🖍</div><div class="emoticonItem" type="objects">📝</div><div class="emoticonItem" type="objects">✏️</div><div class="emoticonItem" type="objects">🔍</div><div class="emoticonItem" type="objects">🔎</div><div class="emoticonItem" type="objects">🔏</div><div class="emoticonItem" type="objects">🔐</div><div class="emoticonItem" type="objects">🔒</div><div class="emoticonItem" type="objects">🔓</div><div id="emoticon_simbols" class="emoticon emoticon_simbols toj" type="simbols">Símbolos</div><div class="emoticonItem" type="simbols">❤️</div><div class="emoticonItem" type="simbols">💛</div><div class="emoticonItem" type="simbols">💚</div><div class="emoticonItem" type="simbols">💙</div><div class="emoticonItem" type="simbols">💜</div><div class="emoticonItem" type="simbols">🖤</div><div class="emoticonItem" type="simbols">💔</div><div class="emoticonItem" type="simbols">❣️</div><div class="emoticonItem" type="simbols">💕</div><div class="emoticonItem" type="simbols">💞</div><div class="emoticonItem" type="simbols">💓</div><div class="emoticonItem" type="simbols">💗</div><div class="emoticonItem" type="simbols">💖</div><div class="emoticonItem" type="simbols">💘</div><div class="emoticonItem" type="simbols">💝</div><div class="emoticonItem" type="simbols">💟</div><div class="emoticonItem" type="simbols">☮️</div><div class="emoticonItem" type="simbols">✝️</div><div class="emoticonItem" type="simbols">☪️</div><div class="emoticonItem" type="simbols">🕉</div><div class="emoticonItem" type="simbols">☸️</div><div class="emoticonItem" type="simbols">✡️</div><div class="emoticonItem" type="simbols">🔯</div><div class="emoticonItem" type="simbols">🕎</div><div class="emoticonItem" type="simbols">☯️</div><div class="emoticonItem" type="simbols">☦️</div><div class="emoticonItem" type="simbols">🛐</div><div class="emoticonItem" type="simbols">⛎</div><div class="emoticonItem" type="simbols">♈️</div><div class="emoticonItem" type="simbols">♉️</div><div class="emoticonItem" type="simbols">♊️</div><div class="emoticonItem" type="simbols">♋️</div><div class="emoticonItem" type="simbols">♌️</div><div class="emoticonItem" type="simbols">♍️</div><div class="emoticonItem" type="simbols">♎️</div><div class="emoticonItem" type="simbols">♏️</div><div class="emoticonItem" type="simbols">♐️</div><div class="emoticonItem" type="simbols">♑️</div><div class="emoticonItem" type="simbols">♒️</div><div class="emoticonItem" type="simbols">♓️</div><div class="emoticonItem" type="simbols">🆔</div><div class="emoticonItem" type="simbols">⚛️</div><div class="emoticonItem" type="simbols">🉑</div><div class="emoticonItem" type="simbols">☢️</div><div class="emoticonItem" type="simbols">☣️</div><div class="emoticonItem" type="simbols">📴</div><div class="emoticonItem" type="simbols">📳</div><div class="emoticonItem" type="simbols">🈶</div><div class="emoticonItem" type="simbols">🈚</div><div class="emoticonItem" type="simbols">🈸</div><div class="emoticonItem" type="simbols">🈺</div><div class="emoticonItem" type="simbols">🈷️</div><div class="emoticonItem" type="simbols">✴️</div><div class="emoticonItem" type="simbols">🆚</div><div class="emoticonItem" type="simbols">💮</div><div class="emoticonItem" type="simbols">🉐</div><div class="emoticonItem" type="simbols">㊙️</div><div class="emoticonItem" type="simbols">㊗️</div><div class="emoticonItem" type="simbols">🈴</div><div class="emoticonItem" type="simbols">🈵</div><div class="emoticonItem" type="simbols">🈹</div><div class="emoticonItem" type="simbols">🈲</div><div class="emoticonItem" type="simbols">🅰️</div><div class="emoticonItem" type="simbols">🅱️</div><div class="emoticonItem" type="simbols">🆎</div><div class="emoticonItem" type="simbols">🆑</div><div class="emoticonItem" type="simbols">🅾️</div><div class="emoticonItem" type="simbols">🆘</div><div class="emoticonItem" type="simbols">❌</div><div class="emoticonItem" type="simbols">⭕</div><div class="emoticonItem" type="simbols">🛑</div><div class="emoticonItem" type="simbols">⛔</div><div class="emoticonItem" type="simbols">📛</div><div class="emoticonItem" type="simbols">🚫</div><div class="emoticonItem" type="simbols">💯</div><div class="emoticonItem" type="simbols">💢</div><div class="emoticonItem" type="simbols">♨️</div><div class="emoticonItem" type="simbols">🚷</div><div class="emoticonItem" type="simbols">🚯</div><div class="emoticonItem" type="simbols">🚳</div><div class="emoticonItem" type="simbols">🚱</div><div class="emoticonItem" type="simbols">🔞</div><div class="emoticonItem" type="simbols">📵</div><div class="emoticonItem" type="simbols">🚭</div><div class="emoticonItem" type="simbols">❗</div><div class="emoticonItem" type="simbols">❕</div><div class="emoticonItem" type="simbols">❓</div><div class="emoticonItem" type="simbols">❔</div><div class="emoticonItem" type="simbols">‼️</div><div class="emoticonItem" type="simbols">⁉️</div><div class="emoticonItem" type="simbols">🔅</div><div class="emoticonItem" type="simbols">🔆</div><div class="emoticonItem" type="simbols">〽️</div><div class="emoticonItem" type="simbols">⚠️</div><div class="emoticonItem" type="simbols">🚸</div><div class="emoticonItem" type="simbols">🔱</div><div class="emoticonItem" type="simbols">⚜️</div><div class="emoticonItem" type="simbols">🔰</div><div class="emoticonItem" type="simbols">♻️</div><div class="emoticonItem" type="simbols">✅</div><div class="emoticonItem" type="simbols">🈯</div><div class="emoticonItem" type="simbols">💹</div><div class="emoticonItem" type="simbols">❇️</div><div class="emoticonItem" type="simbols">✳️</div><div class="emoticonItem" type="simbols">❎</div><div class="emoticonItem" type="simbols">🌐</div><div class="emoticonItem" type="simbols">💠</div><div class="emoticonItem" type="simbols">Ⓜ️</div><div class="emoticonItem" type="simbols">🌀</div><div class="emoticonItem" type="simbols">💤</div><div class="emoticonItem" type="simbols">🏧</div><div class="emoticonItem" type="simbols">🚾</div><div class="emoticonItem" type="simbols">♿️</div><div class="emoticonItem" type="simbols">🅿️</div><div class="emoticonItem" type="simbols">🈳</div><div class="emoticonItem" type="simbols">🈂️</div><div class="emoticonItem" type="simbols">🛂</div><div class="emoticonItem" type="simbols">🛃</div><div class="emoticonItem" type="simbols">🛄</div><div class="emoticonItem" type="simbols">🛅</div><div class="emoticonItem" type="simbols">🚹</div><div class="emoticonItem" type="simbols">🚺</div><div class="emoticonItem" type="simbols">🚼</div><div class="emoticonItem" type="simbols">🚻</div><div class="emoticonItem" type="simbols">🚮</div><div class="emoticonItem" type="simbols">🎦</div><div class="emoticonItem" type="simbols">📶</div><div class="emoticonItem" type="simbols">🈁</div><div class="emoticonItem" type="simbols">🔣</div><div class="emoticonItem" type="simbols">ℹ️</div><div class="emoticonItem" type="simbols">🔤</div><div class="emoticonItem" type="simbols">🔡</div><div class="emoticonItem" type="simbols">🔠</div><div class="emoticonItem" type="simbols">🆖</div><div class="emoticonItem" type="simbols">🆗</div><div class="emoticonItem" type="simbols">🆙</div><div class="emoticonItem" type="simbols">🆒</div><div class="emoticonItem" type="simbols">🆕</div><div class="emoticonItem" type="simbols">🆓</div><div class="emoticonItem" type="simbols">0️⃣</div><div class="emoticonItem" type="simbols">1️⃣</div><div class="emoticonItem" type="simbols">2️⃣</div><div class="emoticonItem" type="simbols">3️⃣</div><div class="emoticonItem" type="simbols">4️⃣</div><div class="emoticonItem" type="simbols">5️⃣</div><div class="emoticonItem" type="simbols">6️⃣</div><div class="emoticonItem" type="simbols">7️⃣</div><div class="emoticonItem" type="simbols">8️⃣</div><div class="emoticonItem" type="simbols">9️⃣</div><div class="emoticonItem" type="simbols">🔟</div><div class="emoticonItem" type="simbols">🔢</div><div class="emoticonItem" type="simbols">#️⃣</div><div class="emoticonItem" type="simbols">*️⃣</div><div class="emoticonItem" type="simbols">▶️</div><div class="emoticonItem" type="simbols">⏸</div><div class="emoticonItem" type="simbols">⏯</div><div class="emoticonItem" type="simbols">⏹</div><div class="emoticonItem" type="simbols">⏺</div><div class="emoticonItem" type="simbols">⏭</div><div class="emoticonItem" type="simbols">⏮</div><div class="emoticonItem" type="simbols">⏩</div><div class="emoticonItem" type="simbols">⏪</div><div class="emoticonItem" type="simbols">⏫</div><div class="emoticonItem" type="simbols">⏬</div><div class="emoticonItem" type="simbols">◀️</div><div class="emoticonItem" type="simbols">🔼</div><div class="emoticonItem" type="simbols">🔽</div><div class="emoticonItem" type="simbols">➡️</div><div class="emoticonItem" type="simbols">⬅️</div><div class="emoticonItem" type="simbols">⬆️</div><div class="emoticonItem" type="simbols">⬇️</div><div class="emoticonItem" type="simbols">↗️</div><div class="emoticonItem" type="simbols">↘️</div><div class="emoticonItem" type="simbols">↙️</div><div class="emoticonItem" type="simbols">↖️</div><div class="emoticonItem" type="simbols">↕️</div><div class="emoticonItem" type="simbols">↔️</div><div class="emoticonItem" type="simbols">↪️</div><div class="emoticonItem" type="simbols">↩️</div><div class="emoticonItem" type="simbols">⤴️</div><div class="emoticonItem" type="simbols">⤵️</div><div class="emoticonItem" type="simbols">🔀</div><div class="emoticonItem" type="simbols">🔁</div><div class="emoticonItem" type="simbols">🔂</div><div class="emoticonItem" type="simbols">🔄</div><div class="emoticonItem" type="simbols">🔃</div><div class="emoticonItem" type="simbols">🎵</div><div class="emoticonItem" type="simbols">🎶</div><div class="emoticonItem" type="simbols">➕</div><div class="emoticonItem" type="simbols">➖</div><div class="emoticonItem" type="simbols">➗</div><div class="emoticonItem" type="simbols">✖️</div><div class="emoticonItem" type="simbols">💲</div><div class="emoticonItem" type="simbols">💱</div><div class="emoticonItem" type="simbols">™️</div><div class="emoticonItem" type="simbols">©️</div><div class="emoticonItem" type="simbols">®️</div><div class="emoticonItem" type="simbols">〰️</div><div class="emoticonItem" type="simbols">➰</div><div class="emoticonItem" type="simbols">➿</div><div class="emoticonItem" type="simbols">🔚</div><div class="emoticonItem" type="simbols">🔙</div><div class="emoticonItem" type="simbols">🔛</div><div class="emoticonItem" type="simbols">🔝</div><div class="emoticonItem" type="simbols">🔜</div><div class="emoticonItem" type="simbols">✔️</div><div class="emoticonItem" type="simbols">☑️</div><div class="emoticonItem" type="simbols">🔘</div><div class="emoticonItem" type="simbols">⚪</div><div class="emoticonItem" type="simbols">⚫</div><div class="emoticonItem" type="simbols">🔴</div><div class="emoticonItem" type="simbols">🔵</div><div class="emoticonItem" type="simbols">🔺</div><div class="emoticonItem" type="simbols">🔻</div><div class="emoticonItem" type="simbols">🔸</div><div class="emoticonItem" type="simbols">🔹</div><div class="emoticonItem" type="simbols">🔶</div><div class="emoticonItem" type="simbols">🔷</div><div class="emoticonItem" type="simbols">🔳</div><div class="emoticonItem" type="simbols">🔲</div><div class="emoticonItem" type="simbols">▪️</div><div class="emoticonItem" type="simbols">▫️</div><div class="emoticonItem" type="simbols">◾️</div><div class="emoticonItem" type="simbols">◽️</div><div class="emoticonItem" type="simbols">◼️</div><div class="emoticonItem" type="simbols">◻️</div><div class="emoticonItem" type="simbols">⬛</div><div class="emoticonItem" type="simbols">⬜️</div><div class="emoticonItem" type="simbols">🔈</div><div class="emoticonItem" type="simbols">🔇</div><div class="emoticonItem" type="simbols">🔉</div><div class="emoticonItem" type="simbols">🔊</div><div class="emoticonItem" type="simbols">🔔</div><div class="emoticonItem" type="simbols">🔕</div><div class="emoticonItem" type="simbols">📣</div><div class="emoticonItem" type="simbols">📢</div><div class="emoticonItem" type="simbols">👁&zwj;🗨</div><div class="emoticonItem" type="simbols">💬</div><div class="emoticonItem" type="simbols">💭</div><div class="emoticonItem" type="simbols">🗯</div><div class="emoticonItem" type="simbols">♠️</div><div class="emoticonItem" type="simbols">♣️</div><div class="emoticonItem" type="simbols">♥️</div><div class="emoticonItem" type="simbols">♦️</div><div class="emoticonItem" type="simbols">🃏</div><div class="emoticonItem" type="simbols">🎴</div><div class="emoticonItem" type="simbols">🀄</div><div class="emoticonItem" type="simbols">🕐</div><div class="emoticonItem" type="simbols">🕑</div><div class="emoticonItem" type="simbols">🕒</div><div class="emoticonItem" type="simbols">🕓</div><div class="emoticonItem" type="simbols">🕔</div><div class="emoticonItem" type="simbols">🕕</div><div class="emoticonItem" type="simbols">🕖</div><div class="emoticonItem" type="simbols">🕗</div><div class="emoticonItem" type="simbols">🕘</div><div class="emoticonItem" type="simbols">🕙</div><div class="emoticonItem" type="simbols">🕚</div><div class="emoticonItem" type="simbols">🕛</div><div class="emoticonItem" type="simbols">🕜</div><div class="emoticonItem" type="simbols">🕝</div><div class="emoticonItem" type="simbols">🕞</div><div class="emoticonItem" type="simbols">🕟</div><div class="emoticonItem" type="simbols">🕠</div><div class="emoticonItem" type="simbols">🕡</div><div class="emoticonItem" type="simbols">🕢</div><div class="emoticonItem" type="simbols">🕣</div><div class="emoticonItem" type="simbols">🕤</div><div class="emoticonItem" type="simbols">🕥</div><div class="emoticonItem" type="simbols">🕦</div><div class="emoticonItem" type="simbols">🕧</div><div id="emoticon_flags" class="emoticon emoticon_flags toj" type="flags">Bandeiras</div><div class="emoticonItem" type="flags">🏳</div><div class="emoticonItem" type="flags">🏴</div><div class="emoticonItem" type="flags">🏁</div><div class="emoticonItem" type="flags">🚩</div><div class="emoticonItem" type="flags">🏳&zwj;🌈</div><div class="emoticonItem" type="flags">🇦🇫</div><div class="emoticonItem" type="flags">🇦🇽</div><div class="emoticonItem" type="flags">🇦🇱</div><div class="emoticonItem" type="flags">🇩🇿</div><div class="emoticonItem" type="flags">🇦🇸</div><div class="emoticonItem" type="flags">🇦🇩</div><div class="emoticonItem" type="flags">🇦🇴</div><div class="emoticonItem" type="flags">🇦🇮</div><div class="emoticonItem" type="flags">🇦🇶</div><div class="emoticonItem" type="flags">🇦🇬</div><div class="emoticonItem" type="flags">🇦🇷</div><div class="emoticonItem" type="flags">🇦🇲</div><div class="emoticonItem" type="flags">🇦🇼</div><div class="emoticonItem" type="flags">🇦🇺</div><div class="emoticonItem" type="flags">🇦🇹</div><div class="emoticonItem" type="flags">🇦🇿</div><div class="emoticonItem" type="flags">🇧🇸</div><div class="emoticonItem" type="flags">🇧🇭</div><div class="emoticonItem" type="flags">🇧🇩</div><div class="emoticonItem" type="flags">🇧🇧</div><div class="emoticonItem" type="flags">🇧🇾</div><div class="emoticonItem" type="flags">🇧🇪</div><div class="emoticonItem" type="flags">🇧🇿</div><div class="emoticonItem" type="flags">🇧🇯</div><div class="emoticonItem" type="flags">🇧🇲</div><div class="emoticonItem" type="flags">🇧🇹</div><div class="emoticonItem" type="flags">🇧🇴</div><div class="emoticonItem" type="flags">🇧🇦</div><div class="emoticonItem" type="flags">🇧🇼</div><div class="emoticonItem" type="flags">🇧🇷</div><div class="emoticonItem" type="flags">🇮🇴</div><div class="emoticonItem" type="flags">🇻🇬</div><div class="emoticonItem" type="flags">🇧🇳</div><div class="emoticonItem" type="flags">🇧🇬</div><div class="emoticonItem" type="flags">🇧🇫</div><div class="emoticonItem" type="flags">🇧🇮</div><div class="emoticonItem" type="flags">🇰🇭</div><div class="emoticonItem" type="flags">🇨🇲</div><div class="emoticonItem" type="flags">🇨🇦</div><div class="emoticonItem" type="flags">🇮🇨</div><div class="emoticonItem" type="flags">🇨🇻</div><div class="emoticonItem" type="flags">🇧🇶</div><div class="emoticonItem" type="flags">🇰🇾</div><div class="emoticonItem" type="flags">🇨🇫</div><div class="emoticonItem" type="flags">🇹🇩</div><div class="emoticonItem" type="flags">🇨🇱</div><div class="emoticonItem" type="flags">🇨🇳</div><div class="emoticonItem" type="flags">🇨🇽</div><div class="emoticonItem" type="flags">🇨🇨</div><div class="emoticonItem" type="flags">🇨🇴</div><div class="emoticonItem" type="flags">🇰🇲</div><div class="emoticonItem" type="flags">🇨🇬</div><div class="emoticonItem" type="flags">🇨🇩</div><div class="emoticonItem" type="flags">🇨🇰</div><div class="emoticonItem" type="flags">🇨🇷</div><div class="emoticonItem" type="flags">🇨🇮</div><div class="emoticonItem" type="flags">🇭🇷</div><div class="emoticonItem" type="flags">🇨🇺</div><div class="emoticonItem" type="flags">🇨🇼</div><div class="emoticonItem" type="flags">🇨🇾</div><div class="emoticonItem" type="flags">🇨🇿</div><div class="emoticonItem" type="flags">🇩🇰</div><div class="emoticonItem" type="flags">🇩🇯</div><div class="emoticonItem" type="flags">🇩🇲</div><div class="emoticonItem" type="flags">🇩🇴</div><div class="emoticonItem" type="flags">🇪🇨</div><div class="emoticonItem" type="flags">🇪🇬</div><div class="emoticonItem" type="flags">🇸🇻</div><div class="emoticonItem" type="flags">🇬🇶</div><div class="emoticonItem" type="flags">🇪🇷</div><div class="emoticonItem" type="flags">🇪🇪</div><div class="emoticonItem" type="flags">🇪🇹</div><div class="emoticonItem" type="flags">🇪🇺</div><div class="emoticonItem" type="flags">🇫🇰</div><div class="emoticonItem" type="flags">🇫🇴</div><div class="emoticonItem" type="flags">🇫🇯</div><div class="emoticonItem" type="flags">🇫🇮</div><div class="emoticonItem" type="flags">🇫🇷</div><div class="emoticonItem" type="flags">🇬🇫</div><div class="emoticonItem" type="flags">🇵🇫</div><div class="emoticonItem" type="flags">🇹🇫</div><div class="emoticonItem" type="flags">🇬🇦</div><div class="emoticonItem" type="flags">🇬🇲</div><div class="emoticonItem" type="flags">🇬🇪</div><div class="emoticonItem" type="flags">🇩🇪</div><div class="emoticonItem" type="flags">🇬🇭</div><div class="emoticonItem" type="flags">🇬🇮</div><div class="emoticonItem" type="flags">🇬🇷</div><div class="emoticonItem" type="flags">🇬🇱</div><div class="emoticonItem" type="flags">🇬🇩</div><div class="emoticonItem" type="flags">🇬🇵</div><div class="emoticonItem" type="flags">🇬🇺</div><div class="emoticonItem" type="flags">🇬🇹</div><div class="emoticonItem" type="flags">🇬🇬</div><div class="emoticonItem" type="flags">🇬🇳</div><div class="emoticonItem" type="flags">🇬🇼</div><div class="emoticonItem" type="flags">🇬🇾</div><div class="emoticonItem" type="flags">🇭🇹</div><div class="emoticonItem" type="flags">🇭🇳</div><div class="emoticonItem" type="flags">🇭🇰</div><div class="emoticonItem" type="flags">🇭🇺</div><div class="emoticonItem" type="flags">🇮🇸</div><div class="emoticonItem" type="flags">🇮🇳</div><div class="emoticonItem" type="flags">🇮🇩</div><div class="emoticonItem" type="flags">🇮🇷</div><div class="emoticonItem" type="flags">🇮🇶</div><div class="emoticonItem" type="flags">🇮🇪</div><div class="emoticonItem" type="flags">🇮🇲</div><div class="emoticonItem" type="flags">🇮🇱</div><div class="emoticonItem" type="flags">🇮🇹</div><div class="emoticonItem" type="flags">🇯🇲</div><div class="emoticonItem" type="flags">🇯🇵</div><div class="emoticonItem" type="flags">🎌</div><div class="emoticonItem" type="flags">🇯🇪</div><div class="emoticonItem" type="flags">🇯🇴</div><div class="emoticonItem" type="flags">🇰🇿</div><div class="emoticonItem" type="flags">🇰🇪</div><div class="emoticonItem" type="flags">🇰🇮</div><div class="emoticonItem" type="flags">🇽🇰</div><div class="emoticonItem" type="flags">🇰🇼</div><div class="emoticonItem" type="flags">🇰🇬</div><div class="emoticonItem" type="flags">🇱🇦</div><div class="emoticonItem" type="flags">🇱🇻</div><div class="emoticonItem" type="flags">🇱🇧</div><div class="emoticonItem" type="flags">🇱🇸</div><div class="emoticonItem" type="flags">🇱🇷</div><div class="emoticonItem" type="flags">🇱🇾</div><div class="emoticonItem" type="flags">🇱🇮</div><div class="emoticonItem" type="flags">🇱🇹</div><div class="emoticonItem" type="flags">🇱🇺</div><div class="emoticonItem" type="flags">🇲🇴</div><div class="emoticonItem" type="flags">🇲🇰</div><div class="emoticonItem" type="flags">🇲🇬</div><div class="emoticonItem" type="flags">🇲🇼</div><div class="emoticonItem" type="flags">🇲🇾</div><div class="emoticonItem" type="flags">🇲🇻</div><div class="emoticonItem" type="flags">🇲🇱</div><div class="emoticonItem" type="flags">🇲🇹</div><div class="emoticonItem" type="flags">🇲🇭</div><div class="emoticonItem" type="flags">🇲🇶</div><div class="emoticonItem" type="flags">🇲🇷</div><div class="emoticonItem" type="flags">🇲🇺</div><div class="emoticonItem" type="flags">🇾🇹</div><div class="emoticonItem" type="flags">🇲🇽</div><div class="emoticonItem" type="flags">🇫🇲</div><div class="emoticonItem" type="flags">🇲🇩</div><div class="emoticonItem" type="flags">🇲🇨</div><div class="emoticonItem" type="flags">🇲🇳</div><div class="emoticonItem" type="flags">🇲🇪</div><div class="emoticonItem" type="flags">🇲🇸</div><div class="emoticonItem" type="flags">🇲🇦</div><div class="emoticonItem" type="flags">🇲🇿</div><div class="emoticonItem" type="flags">🇲🇲</div><div class="emoticonItem" type="flags">🇳🇦</div><div class="emoticonItem" type="flags">🇳🇷</div><div class="emoticonItem" type="flags">🇳🇵</div><div class="emoticonItem" type="flags">🇳🇱</div><div class="emoticonItem" type="flags">🇳🇨</div><div class="emoticonItem" type="flags">🇳🇿</div><div class="emoticonItem" type="flags">🇳🇮</div><div class="emoticonItem" type="flags">🇳🇪</div><div class="emoticonItem" type="flags">🇳🇬</div><div class="emoticonItem" type="flags">🇳🇺</div><div class="emoticonItem" type="flags">🇳🇫</div><div class="emoticonItem" type="flags">🇰🇵</div><div class="emoticonItem" type="flags">🇲🇵</div><div class="emoticonItem" type="flags">🇳🇴</div><div class="emoticonItem" type="flags">🇴🇲</div><div class="emoticonItem" type="flags">🇵🇰</div><div class="emoticonItem" type="flags">🇵🇼</div><div class="emoticonItem" type="flags">🇵🇸</div><div class="emoticonItem" type="flags">🇵🇦</div><div class="emoticonItem" type="flags">🇵🇬</div><div class="emoticonItem" type="flags">🇵🇾</div><div class="emoticonItem" type="flags">🇵🇪</div><div class="emoticonItem" type="flags">🇵🇭</div><div class="emoticonItem" type="flags">🇵🇳</div><div class="emoticonItem" type="flags">🇵🇱</div><div class="emoticonItem" type="flags">🇵🇹</div><div class="emoticonItem" type="flags">🇵🇷</div><div class="emoticonItem" type="flags">🇶🇦</div><div class="emoticonItem" type="flags">🇷🇪</div><div class="emoticonItem" type="flags">🇷🇴</div><div class="emoticonItem" type="flags">🇷🇺</div><div class="emoticonItem" type="flags">🇷🇼</div><div class="emoticonItem" type="flags">🇼🇸</div><div class="emoticonItem" type="flags">🇸🇲</div><div class="emoticonItem" type="flags">🇸🇹</div><div class="emoticonItem" type="flags">🇸🇦</div><div class="emoticonItem" type="flags">🇸🇳</div><div class="emoticonItem" type="flags">🇷🇸</div><div class="emoticonItem" type="flags">🇸🇨</div><div class="emoticonItem" type="flags">🇸🇱</div><div class="emoticonItem" type="flags">🇸🇬</div><div class="emoticonItem" type="flags">🇸🇽</div><div class="emoticonItem" type="flags">🇸🇰</div><div class="emoticonItem" type="flags">🇸🇮</div><div class="emoticonItem" type="flags">🇬🇸</div><div class="emoticonItem" type="flags">🇸🇧</div><div class="emoticonItem" type="flags">🇸🇴</div><div class="emoticonItem" type="flags">🇿🇦</div><div class="emoticonItem" type="flags">🇰🇷</div><div class="emoticonItem" type="flags">🇸🇸</div><div class="emoticonItem" type="flags">🇪🇸</div><div class="emoticonItem" type="flags">🇱🇰</div><div class="emoticonItem" type="flags">🇧🇱</div><div class="emoticonItem" type="flags">🇸🇭</div><div class="emoticonItem" type="flags">🇰🇳</div><div class="emoticonItem" type="flags">🇱🇨</div><div class="emoticonItem" type="flags">🇵🇲</div><div class="emoticonItem" type="flags">🇻🇨</div><div class="emoticonItem" type="flags">🇸🇩</div><div class="emoticonItem" type="flags">🇸🇷</div><div class="emoticonItem" type="flags">🇸🇿</div><div class="emoticonItem" type="flags">🇸🇪</div><div class="emoticonItem" type="flags">🇨🇭</div><div class="emoticonItem" type="flags">🇸🇾</div><div class="emoticonItem" type="flags">🇹🇼</div><div class="emoticonItem" type="flags">🇹🇯</div><div class="emoticonItem" type="flags">🇹🇿</div><div class="emoticonItem" type="flags">🇹🇭</div><div class="emoticonItem" type="flags">🇹🇱</div><div class="emoticonItem" type="flags">🇹🇬</div><div class="emoticonItem" type="flags">🇹🇰</div><div class="emoticonItem" type="flags">🇹🇴</div><div class="emoticonItem" type="flags">🇹🇹</div><div class="emoticonItem" type="flags">🇹🇳</div><div class="emoticonItem" type="flags">🇹🇷</div><div class="emoticonItem" type="flags">🇹🇲</div><div class="emoticonItem" type="flags">🇹🇨</div><div class="emoticonItem" type="flags">🇹🇻</div><div class="emoticonItem" type="flags">🇻🇮</div><div class="emoticonItem" type="flags">🇺🇬</div><div class="emoticonItem" type="flags">🇺🇦</div><div class="emoticonItem" type="flags">🇦🇪</div><div class="emoticonItem" type="flags">🇬🇧</div><div class="emoticonItem" type="flags">󠁧󠁢󠁷󠁬󠁳󠁿🇺🇸</div><div class="emoticonItem" type="flags">🇺🇾</div><div class="emoticonItem" type="flags">🇺🇿</div><div class="emoticonItem" type="flags">🇻🇺</div><div class="emoticonItem" type="flags">🇻🇦</div><div class="emoticonItem" type="flags">🇻🇪</div><div class="emoticonItem" type="flags">🇻🇳</div><div class="emoticonItem" type="flags">🇼🇫</div><div class="emoticonItem" type="flags">🇪🇭</div><div class="emoticonItem" type="flags">🇾🇪</div><div class="emoticonItem" type="flags">🇿🇲</div><div class="emoticonItem" type="flags">🇿🇼</div></div>
          </div>
          <div class="rpchnh rph frm p5 tdg sha" style="z-index:1">
            <div id="channelExpandRP" class="channelExpandRP sxxl tg material-icons rd" style="">navigate_before</div>
            <div class="channelExpandRP fig"></div>
            <div id="channelAdmChat" class="channelAdmChat ic_channel_chat rd" style="background-repeat:no-repeat;display:none;"></div>
            <div class="channelAdmChat fig"></div>
            <div id="channelAdmGroup" class="channelAdmGroup sxxl tg material-icons ic_group rd ic_group_ON" style="display:block;background-repeat:no-repeat;" selected="selected"></div>
            <div class="channelAdmGroup fig"></div>
            <!--div id="channelAdmUserList" class="channelAdmUserList sxxl tg material-icons" style="display:none;">&#xE7FB;</div -->
            <div id="channelAdmUserList" class="channelAdmUserList tg" style="display:none;position:relative;"><div class="material-icons sxxl rd"></div>
              <div id="channelRequestVoiceMark" class="sxxs material-icons tb" style="position:absolute;top:-2px;left:25px;display:none;">circle</div>
              <div id="channelAdmUserListCount" class="sxs" style="position:absolute;bottom:-2px;left:30px;"></div>
            </div>
            <div class="fig channelAdmUserList"></div>
            <div id="channelTaskList" class="channelTaskList sxxl tg material-icons rd " style="display:none;"></div>
            <div class="fig channelTaskList"></div>
            <div id="channelCsmVideosIcon" class="channelCsmVideosIcon sxxl tg material-icons rd" style="display:none;">video_library</div>
            <div class="fig channelCsmVideosIcon" style="display:none;"></div>
            <div id="channelFeedIcon" class="channelFeedIcon sxxl tg material-icons rd" style="display:none;">campaign</div>
            <div class="fig channelFeedIcon" style="display:none;"></div>
            <div id="channelModList" class="channelModList sxxl tg material-icons rd" style="display:none;"></div>
            <div class="fig channelModList"></div>
            <div id="channelOtherIcon" class="channelOtherIcon sxxl tg material-icons rd" style=""></div>
            <div class="fig channelOtherIcon" style=""></div>
            <div id="channelLmsIcon" class="channelLmsIcon sxxl tg material-icons rd" style="display:none;"></div>
            <div class="fig channelLmsIcon" style="display:none;"></div>

            <div class="frm" style="position:relative;">
              <div id="rpchnconficon" class="sxxl tg material-icons rd"></div>
              <div id="rpchnconfshow" class="sxxl tg material-icons rd "></div>
              <div id="rpchnconfhide" class="sxxl tg material-icons rd" style="display:none;"></div>
            </div>
          </div>
          <div id="rpchnbox" class=" frm w100 p5 pr10 bgdbl chnmax z9" style="height: 60px; min-height: 60px; z-index: 999; background-color: rgb(50, 87, 148); display: none;">
            <div>
              <a href="" target="_blank" class="rpchnboxlink">
                <span class="material-icons material-icons tw pt"></span>
              </a>
            </div>
            <div class="fig" style="text-overflow:ellipsis;white-space:nowrap;overflow:hidden;">
              <a id="rpchnboxtext" href="" target="_blank" class="ss pt tw rpchnboxlink"></a>
            </div>
            <div id="rpchnboxclose" class="ss pt tw">X</div>
          </div>
          <div id="rpchnconf" class="bgw w100 fc p0 tdg sha" style="display:none;z-index:1">
            <div id="rpchnmetaverse" class="rpchnmetaverse frm pl10 w100 pt" style="display:none;">
                <div id="rpchnmetaverseicon" class="sxxl p10 tg material-icons">view_in_ar</div>
                <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-bottom-width:1px;border-style:solid;">
                  <div id="rpchnmetaverselabel" class="rpchnmetaverse" style="max-width:370px;text-overflow:ellipsis;white-space:nowrap;overflow:hidden;">
                    <div class="i18n-metaverse ss">Metaverso</div><div id="metaverse-status" class="sxs" style="min-height:16.5px;"></div>
                  </div>
                  <div class="fig"></div>
                </div>
            </div>
            <div id="rpchnscreensaving" class="rpchnscreensaving frm pl10 w100 pt" style="display:none;">
                <div id="rpchnscreensavingicon" class="sxxl p10 tg material-icons">monitor</div>
                <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-bottom-width:1px;border-style:solid;">
                  <div id="rpchnscreensavinglabel" class="rpchnscreensaving" style="max-width:370px;text-overflow:ellipsis;white-space:nowrap;overflow:hidden;">
                    <div class="i18n-screen-saving ss">Gravar Metaverso</div><div id="screen-saving-status" class="sxs" style="min-height:16.5px;"></div>
                  </div>
                  <div class="fig"></div>
                </div>
            </div>
            <div id="rpchninvite" class="rpchninvite frm pl10 w100 pt" style="display:none;">
              <div id="rpchninviteicon" class="sxxl p10 tg material-icons">link</div>
              <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-bottom-width:1px;border-style:solid;">
                <div id="rpchninvitelabel" class="i18n-invite-generate-invite rpchninvite" style="max-width:370px;text-overflow:ellipsis;white-space:nowrap;overflow:hidden;">Convites</div>
                <div class="fig"></div>
              </div>
            </div>
            <div id="rpchnmoderate" class="rpchnmoderate frm pl10 w100 pt" style="display:none;">
              <div id="rpchnmoderateicon" class="sxxl p10 tg material-icons"></div>
              <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-bottom-width:1px;border-style:solid;">
                <div id="rpchnmoderatelabel" class="i18n-block-chat rpchnmoderate fig">Bloquear Chat</div>
              </div>
            </div>
            <div id="rpchnnotification" class="rpchnnotification frm pl10 w100 pt" style="display:none;">
              <div id="rpchnnotificationicon" class="sxxl p10 tg material-icons"></div>
              <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-bottom-width:1px;border-style:solid;">
                <div id="rpchnnotificationlabel" class="i18n-send-notification rpchnnotification fig">Enviar Notificação</div>
              </div>
            </div>
            <div id="channelAdmShareScreen" class="frm pl10 w100 pt">
              <div id="channelShareScreenIcon" class="channelShareScreen sxxl p10 tg material-icons"></div>
              <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-bottom-width:1px;border-style:solid;">
                <div class="i18n-share-screen channelShareScreen fig">Compartilhar Tela</div>
                <div id="rpchnshareinfo" class="sxxl tg material-icons pr10"></div>
              </div>
            </div>
            <div id="rpchnyt" class="rpchnyt frm pl10 w100 pt" style="display:none;">
              <div id="rpchnytIcon" class="rpchnyt sxxl p10 tg material-icons"></div>
              <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-bottom-width:1px;border-style:solid;">
                <div class="i18n-youtube-playlist rpchnyt fig">Playlist Youtube</div>
              </div>
            </div>
            <div id="rpchn-silenced" class="rpchn-silenced frm pl10 w100 pt" style="display:none;">
                <div id="rpch-silenced-icon" class="rpchn-silenced sxxl p10 tg material-icons" style="width:48px;height:48px;">speaker_notes_off</div>
                <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-bottom-width:1px;border-style:solid;">
                    <div class="i18n-list-silenced rpch-silenced fig">Listar Silenciados</div>
                </div>
            </div>
            <div id="rpchn-breakout-rooms" class="rpchn-breakout-rooms frm pl10 w100 pt" style="display:none;">
                <div id="rpchn-breakout-rooms-icon" class="rpchn-breakout-rooms sxxl p10 tg material-icons-round" style="width:48px;height:48px;">grid_view</div>
                <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-bottom-width:1px;border-style:solid;">
                    <div id="rpchn-breakout-room-label" class="rpch-breakout-rooms fig"></div>
                </div>
            </div>

            <div id="rpchn-banned" class="rpchn-banned frm pl10 w100 pt" style="display:none;">
                <div id="rpch-banned-icon" class="rpchn-banned sxxl p10 tg material-icons" style="width:48px;height:48px;">do_disturb_off</div>
                <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-bottom-width:1px;border-style:solid;">
                    <div class="i18n-list-banned rpchn-banned fig">Listar Banidos</div>
                </div>
            </div>
            <div id="rpchncl" class="frm pl10 w100 pt" style="display:none;">
                <div class="sxxl p10 tg material-icons" style="width:48px;height:48px;">link</div>
                <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-bottom-width:1px;border-style:solid;">
                    <div class="i18n-channel-link-copy fig">Copiar Link</div>
                </div>
            </div>
            <div id="rpchnmi" class="frm pl10 w100 pt">
              <div class="sxxl p10 tg material-icons"></div>
              <div class="i18n-device-config fig pt10 pb10 ss tg">Configuração de Dispositivos</div>
            </div>
            <div id="rpchnad" class="frm pl10 w100 pt" style="display:none;">
                <div class="sxxl p10 tg material-icons">settings</div>
                <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-top-width:1px;border-style:solid;">
                    <div class="i18n-advanced-settings fig pt10 pb10 ss tg">Configurações avançadas</div>
                </div>
            </div>
            <div id="rpchntut" class="frm pl10 w100 pt" style="display:none;">
                <div class="sxxl p10 tg material-icons">info_outline</div>
                <div class="frm fig pt10 pb10 ss tg" style="border:0px;border-color:#CCCCCC;border-top-width:1px;border-style:solid;">
                    <div class="i18n-room-tutorial fig pt10 pb10 ss tg">Exibir tutorial</div>
                </div>
            </div>
          </div>

          <div id="hp__Channel__" class="rpb fig " target="__Channel__" channel="" style="flex-basis:0"></div>

          <div id="rpchnmetaverselist" class="fc rpb bgw fig" style="flex-basis:0;display:none;background-color:#FFF">
          </div>

          <div id="rpchntasklist" class="rpb fig" style="flex-basis:0;display:none;background-color:#FFF">
            <div class="fr bgw p0 lsha pt5" style="width:100%;border-bottom: 1px solid #F9F9F9;">
              <div id="rpchntasks" class="i18n-my-tasks p10 ss toj b pt" style="width:50%;text-align:center;">Minhas Tarefas</div>
              <div id="rpchntasksdone" class="i18n-tasks-delivered p10 ss pt" style="width:50%;text-align:center;">Tarefas Entregues</div>
            </div>
            <div id="rpchntasksarea" class="rpb fig" style="flex-basis:0;"></div>
          </div>

          <div id="rpchncsmlist" class="rpb fig" style="flex-basis:0;display:none;background-color:#FFF">
            <div id="rpchncsmarea" class="rpb fig" style="flex-basis:0;"></div>
          </div>

          <div id="rpchnfeedlist" class="rpb fig" style="flex-basis:0;display:none;background-color:#FFF">
            <div id="rpchnfeedarea" class="rpb fig" style="flex-basis:0;"></div>
          </div>

          <div id="rpchnmodlist" class="rpb fig" style="flex-basis:0;display:none;background-color:#FFF"></div>

          <div id="rpchngrouplist" class="rpb fig" style="flex-basis:0;display:none;background-color:#FFF"><div class="choose-the-chat-you-want-to-access bglg p10" style="width:100%;border-bottom: 1px solid #F0F0F0;"><div class="p5 sl">Escolha o chat que deseja acessar</div></div></div>

          <div id="rpchncloudlist" class="rpb fig" style="flex-basis:0;display:none;background-color:#FFF"></div>

          <div id="rpchngroupchat" class="fc rpb fig" style="flex-basis:0;padding-bottom:0px;display:none;">
            <div class="fr bglg p10" style="width:100%;border-bottom: 1px solid #F0F0F0;">
              <div id="rpchngroupchatback" class="p5 sxxl tg material-icons" style=""></div>
              <div id="rpchngroupchaticon" class="p5 sl"><img id="rpchngroupiconimg" src="https://edusp-static.ip.tv/webinar/edusp/room_avatar.png" class="cp" style="width:30px;height:30px;"></div>
              <div id="rpchngroupchatname" class="p5 sl"></div>
            </div>
            <div id="hp__Group__" class="rpb fig" style="flex-basis:0;"></div>
            <div id="og___Group__" display="hidden" style="display:none;background-color:#FFFFFF;height:105px;min-height:120px;width:100%" class="fr p10">
              <div style="height:100%" class="fig br">
                <div class="fr" style="background-color:#F9F9F9;">
                  <div class="fic og_Image" style="width:105px;min-width:105px;height:105px"></div>
                  <div class="fig fc ss pl10 pr5" style="height:105px">
                    <div class="fc" style="height:100%">
                      <div class="og_Title b"></div>
                      <div class="og_Description fig sxs" style="overflow:hidden;text-overflow:ellipsis;text-align:justify;"></div>
                      <div class="og_Name fig sxs pt5 pb5 tb"></div>
                    </div>
                  </div>
                </div>
              </div>
              <div style="background-color:#FFFFFF;height:100%;width:30px;min-width:30px" class="fic fcm">
                <span class="'+mb+'material-icons material-icons tb og_close" t="__Group__"></span>
              </div>
            </div>
            <div id="channelGroupInputArea" class="__Group__ rpm fr pr10 pl10 bglg" style="display:none;">
              <div id="__Group__" class="fic fig rmc rpm fr pr10">
                <span class="rpmap tdg" t="__Group__" group="">
                  <div class="rpmaiiv">
                    <span class="'+mb+'material-icons material-icons tb rpma"></span>
                    <span class="i18n-photos-and-videos tl">Fotos e Vídeos</span>
                  </div>
                  <div class="rpmaid">
                    <span class="'+mb+'material-icons material-icons tb rpma"></span>
                    <span class="i18n-share-document tl">Compartilhar Documento</span>
                  </div>
                  <div class="rpmaia">
                    <span class="'+mb+'material-icons material-icons tb rpma"></span>
                    <span class="i18n-share-audio tl">Compartilhar Áudio</span>
                  </div>
                  <div class="rpmaic" style="display: none;">
                    <span class="'+mb+'material-icons material-icons tb rpma"></span>
                    <span class="i18n-share-contact tl">Compartilhar Contato</span>
                  </div>
                </span>
                <div class="fic">
                  <span class="'+mb+'material-icons material-icons tg rpme" t="__Group__"></span>
                </div>
                <div id="chnat" class="chnat fic">
                  <span class="'+mb+'material-icons material-icons tb rpma rpmat" t="__Group__" privchat="channel"></span>
                </div>
                <div class="fic fig rmc">
                  <textarea id="rpchngrouptx" class="sn rm fig fic" t="" type="groupinchannel" onkeyup="inputKeyUp(event, this);" oninput="inputChange(event, this);"></textarea>
                </div>
              </div>
            </div>

          </div>

          <div id="rpchnuserlist" class="rpb fig" style="display: flex; flex-direction: column; height: 100vh; padding: 0; background-color:#FFF">
            <div style="flex: 1; overflow-y: auto;">
              <div class="user-transmitting w100" style="display:none;">
                <div class="fr w100 bgg">
                    <div id="user-transmitting-arrow" class="user-transmitting-label material-icons pl20 tg">arrow_drop_down</div>
                    <div id="user-transmitting-label" class="i18n-transmitting user-transmitting-label w100 pl5 pr10 pt5 pb5 bgg ss pt">Transmitindo</div>
                </div>
                <div id="user-transmitting" class="fc w100"></div>
            </div>
            <div class="user-request w100" style="display:none;">
                <div class="fr w100 bgg">
                    <div id="user-request-arrow" class="user-request-label material-icons pl20 tg">arrow_drop_down</div>
                    <div id="user-request-label" class="i18n-collaboration-request user-request-label w100 pl5 pr10 pt5 pb5 bgg ss pt">Pedido de colaboração</div>
                </div>
                <div>
                  <div id="user-request" class="fc w100"></div>
                </div>
                <div id="remove-all-request" style="display: flex; height: 48px; border-top: solid 1px #1A3975; border-bottom: solid 1px #1A3975; gap: 8px; padding: 12px 16px 12px 16px; align-items: center; cursor:pointer; justify-content: center;">
                  <div class="material-icons" style="width: 24px;"><span style="color:#1A3975;">delete_outlined</span></div>
                  <div><span style="font-weight: 400; color: #1A3975; font-size: 16px;">Remover todos os pedidos de colaboração</span></div>
                </div>
            </div>
            <div class="user-list w100" style="display:none;">
                <div class="fr w100 bgg">
                    <div id="user-list-arrow" class="user-list-label material-icons pl20 tg">arrow_drop_down</div>
                    <div id="user-list-label" class="i18n-list-of-users-in-session user-list-label w100 pl20 pr10 pt5 pb5 bgg ss">Lista de usuários em aula</div>
                </div>
                <div id="user-list" class="fc w100"></div>
            </div>
          </div>
        <div id="rpchn-MuteAll" style="margin-top: auto; width: 100%; background-color: #FEFEFE; box-shadow: 0px -2px 4px 0px rgb(0 0 0 / 15%); border: 0; height: 80px; align-items: center; display: flex; justify-content: flex-end; padding: 12px 16px;">
          <div id="btn-MuteAll" class="frm pl10 w100 pt" style="display: flex; border: solid #1A3975 1px;
          border-radius: 10px; width: 258px; justify-content: center; height: 48px; gap: 8px; padding: 0; cursor: pointer;" t="muteMicAll">  
                  <div><span class="material-icons" style="color: #1A3975; font-size: 24px;"></span></div>
                  <div><span style="color: #1A3975; font-weight: 400; font-size: 16;">Desativar o som de todos</span></div>
          </div>
      </div>
        </div>

          <div id="rpchnusermutelist" class="rpb fig" style="flex-basis:0;display:none;background-color:#FFF"></div>

          <div id="rpchnuserbanlist" class="rpb fig" style="flex-basis:0;display:none;background-color:#FFF"></div>

          <!-- div id="rpchnrequestvoicelist" class="rpb fig" style="flex-basis:0;display:none;background-color:#FFF"></div -->


          <div id="og___Channel__" display="hidden" style="display:none;background-color:#FFFFFF;height:105px;min-height:120px;width:100%" class="fr p10">
            <div style="height:100%" class="fig br">
              <div class="fr" style="background-color:#F9F9F9;">
                <div class="fic og_Image" style="width:105px;min-width:105px;height:105px"></div>
                <div class="fig fc ss pl10 pr5" style="height:105px">
                  <div class="fc" style="height:100%">
                    <div class="og_Title b"></div>
                    <div class="og_Description fig sxs" style="overflow:hidden;text-overflow:ellipsis;text-align:justify;"></div>
                    <div class="og_Name fig sxs pt5 pb5 tb"></div>
                  </div>
                </div>
              </div>
            </div>
            <div style="background-color:#FFFFFF;height:100%;width:30px;min-width:30px" class="fic fcm">
              <span class="'+mb+'material-icons material-icons tb og_close" t="__Channel__"></span>
            </div>
          </div>
          <div id="channelNoMoreMsg" class="fr p10 bgdg frm w100" style="display:none;">
            <span class="i18n-maximum-number-of-messages-reached ss br bglb tw" style="text-align:center;">Número máximo de mensagens atingido. Amanhã você poderá enviar mais mensagens.</span>
          </div>
          <div id="channelMsgAlert" class="fr p10 bgdg frm w100" style="display:none;">
            <span class="i18n-chat-blocked-by-administrator ss br bglb tw">Chat bloqueado pelo administrador</span>
          </div>
          <div id="channelMsgCounter" class="fr p10 bglg frm w100 pt" style="display:none;">
            <span class="fic">
              <div class="btn br bgbl tw ss p5" style="width:250px;text-align:center;">
                <span class="i18n-send-message">Enviar Mensagem</span> (<span id="channelMsgCredit"></span>/<span id="channelMsgCounterLimit"></span>)
              </div>
            </span>
          </div>
          <div id="channelInputArea" class="__Channel__ rpm fr pr10 pl10 bglg" style="display:none;">
            <div id="__Channel__" class="fir fig rmc rpm fr pr10">
              <span class="rpmap tdg" t="__Channel__" group="">
                <div class="rpmaiiv">
                  <span class="'+mb+'material-icons material-icons tb rpma"></span>
                  <span class="i18n-photos-and-videos tl">Fotos e Vídeos</span>
                </div>
                <div class="rpmaid">
                  <span class="'+mb+'material-icons material-icons tb rpma"></span>
                  <span class="i18n-share-document tl">Compartilhar Documento</span>
                </div>
                <div class="rpmaia">
                  <span class="'+mb+'material-icons material-icons tb rpma"></span>
                  <span class="i18n-share-audio tl">Compartilhar Áudio</span>
                </div>
                <div class="rpmaic" style="display: none;">
                  <span class="'+mb+'material-icons material-icons tb rpma"></span>
                  <span class="i18n-share-contact tl">Compartilhar Contato</span>
                </div>
              </span>
              <div class="fir">
                <span class="'+mb+'material-icons material-icons tg rpme" t="__Channel__"></span>
              </div>
              <div id="chnat" class="chnat fir">
                <span class="'+mb+'material-icons material-icons tb rpma rpmat" t="__Channel__" privchat="channel"></span>
              </div>
              <div class="fir fig rmc">
                <textarea id="rpchntx" class="sn rm fig fic" style="bottom:10px" t="" type="channel" onkeyup="inputKeyUp(event, this);" oninput="inputChange(event, this);"></textarea>
              </div>
            </div>
          </div>
        </div>
        <div id="channelChatTab" style="width:210px;min-width:210px;z-index:1;display:none;" class="fc bgw h100 sha">
          <div class="chnchh fcm pt5 pb5 pl10 pr10 tdg sha w100" style="background-color:#F9F9F9;min-height:60px;z-index:1">
            <div id="chnchhtabtitle" class="frm w100 pt">
              <div class="material-icons sxl pr5 tb"></div>
              <div class="toj" style="">Conversas</div>
              <div class="fig">&nbsp;</div>
            </div>
          </div>
          <div id="lpcb_noWakeUp" class="lpcb_noWakeUp fc" style="background-color:#FED24F;display:none;">
            <div class="fr w100 p10">
              <span class="cp" style="width:30px;height:30px;">
                <span class="sn material-icons lpcb_icon" style="padding:5px;"></span>
              </span>
              <div class="fc fig pl5">
                <div class="fr w100">
                  <span class="i18n-no-response-from-the-app ss n">Sem resposta do aplicativo!</span>
                  <span class="fig"></span>
                </div>
                <div class="fr w100">
                  <span class="i18n-check-your-connection sxs l">Verifique a sua conexão e se o seu dispositivo está com o aplicativo aberto!</span>
                  <span class="fig"></span>
                </div>
              </div>
            </div>
          </div>
          <div id="channelChatTabList" class="fc fig w100 h100" style="overflow-y:auto;overflow-x:hidden;background-color:#FFF;">
            <div class="lpcb_loading fc">
              <div class="fr w100 p10">
                <span class="frm">
                  <span class="loader"></span>
                </span>
                <div class="fc fig pl5">
                  <div class="fr w100">
                    <span class="i18n-getting-data sxs n">Obtendo dados...</span>
                    <span class="fig"></span>
                  </div>
                  <div class="fr w100">
                    <span class="i18n-keep-your-app-connected sxxs l">Mantenha seu aplicativo conectado à internet</span>
                    <span class="fig"></span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>
      <div id="lpchb" class="fc">
        <div id="lpcht" style="display:none;"></div>
        <div id="lpchm"></div>
      </div>
    </div>

    <div id="embedArea" class="fc fig w100 h100" style="position: relative; display: none;" room="rd2ea544cc48ac2ab2-l">
      <div id="embed-area-top" class="bgw p10 w100 fcm" style="min-height:66px;max-height:66px;border-bottom: 1px solid #eee">
          <div id="embed-area-channel-icon"><img src="https://edusp-static.ip.tv/webinar/edusp/room_avatar.png" style="width:50px;height:50px; "></div>
          <div id="embed-area-channel-topic" class="fig pl10"></div>
          <div id="embed-area-channel-close" class="material-icons pt ic_exit"></div>
      </div>
      <div id="embed-area-body" class="w100 fig"></div>
    </div>

    <div id="tmsArea" class="fc fig w100 h100" style="position:relative;display:none;">
        <div id="tms-area-top" class="bgw p10 w100 fcm" style="min-height:66px;max-height:66px;border-bottom: 1px solid #eee">
            <div id="tms-area-channel-icon"></div>
            <div id="tms-area-channel-topic" class="fig pl10"></div>
            <div id="tms-area-channel-close" class="material-icons pt ic_exit"></div>
        </div>
        <div id="tms-area-body" class="w100 fig"></div>
    </div>

    <div id="recordingsArea" class="fc fig w100 h100" style="position:relative;display:none;">
        <div id="recordings-area-top" class="bgw p10 w100 fcm" style="min-height:66px;max-height:66px;border-bottom: 1px solid #eee">
            <div id="recordings-area-channel-icon"></div>
            <div id="recordings-area-channel-topic" class="fig pl10"></div>
            <div id="recordings-area-channel-close" class="material-icons pt ic_exit"></div>
        </div>
        <div id="recordings-area-body" class="w100 fig"></div>
    </div>

    <div id="muralArea" class="fc fig w100 h100" style="position:relative;display:none;">
        <div id="mural-area-top" class="bgw p10 w100 fcm" style="min-height:66px;max-height:66px;border-bottom: 1px solid #eee">
            <div id="mural-area-channel-icon"></div>
            <div id="mural-area-channel-topic" class="fig pl10"></div>
            <div id="mural-area-channel-close" class="material-icons pt ic_exit"></div>
        </div>
        <div id="mural-area-body" class="w100 fig"></div>
    </div>

    <div id="otherArea" class="fcm fig w100" style="position:relative;display:none;">
    </div>

  </div>

  <span id="record_main_btn" style="display:none;"></span>
  <span id="record_main_sidebar_btn" style="display:none;"></span>
  <input type="checkbox" id="record_main_sidebar_mockup_checkbox" name="record_main_sidebar_mockup_checkbox" style="display:none;">
  <select name="record_main_sidebar_mockup_total_wnds_combo" id="record_main_sidebar_mockup_total_wnds_combo" disabled="" style="display:none;"><option value="1" selected="selected">1</option><option value="2">2</option><option value="3">3</option><option value="4">4</option></select>
  <select name="record_main_sidebar_slots_combo" id="record_main_sidebar_slots_combo" style="display:none;"><option value="3" selected="selected">3</option><option value="4">4</option><option value="5">5</option><option value="6">6</option><option value="7">7</option><option value="8">8</option></select>
  <span id="record_grid_btn" style="display:none;"></span>
  <input type="checkbox" id="record_grid_mockup_checkbox" name="record_grid_mockup_checkbox" style="display:none;">
  <select name="record_grid_mockup_total_wnds_combo" id="record_grid_mockup_total_wnds_combo" disabled="" style="display:none;"><option value="1">1</option><option value="2">2</option><option value="3">3</option><option value="4">4</option><option value="5">5</option><option value="6">6</option><option value="7">7</option><option value="8">8</option><option value="9">9</option><option value="10">10</option><option value="11">11</option><option value="12">12</option><option value="13">13</option><option value="14">14</option><option value="15">15</option><option value="16">16</option><option value="17">17</option><option value="18">18</option><option value="19">19</option><option value="20">20</option><option value="21">21</option><option value="22">22</option><option value="23">23</option><option value="24">24</option><option value="25">25</option><option value="26">26</option><option value="27">27</option><option value="28">28</option><option value="29">29</option><option value="30">30</option><option value="31">31</option><option value="32">32</option><option value="33">33</option><option value="34">34</option><option value="35">35</option><option value="36">36</option><option value="37">37</option><option value="38">38</option><option value="39">39</option><option value="40">40</option><option value="41">41</option><option value="42">42</option><option value="43">43</option><option value="44">44</option><option value="45">45</option><option value="46">46</option><option value="47">47</option><option value="48">48</option><option value="49">49</option><option value="50">50</option><option value="51">51</option><option value="52">52</option><option value="53">53</option><option value="54">54</option><option value="55">55</option><option value="56">56</option><option value="57">57</option><option value="58">58</option><option value="59">59</option><option value="60">60</option><option value="61">61</option><option value="62">62</option><option value="63">63</option><option value="64">64</option><option value="65">65</option><option value="66">66</option><option value="67">67</option><option value="68">68</option><option value="69">69</option><option value="70">70</option><option value="71">71</option><option value="72">72</option><option value="73">73</option><option value="74">74</option><option value="75">75</option><option value="76">76</option><option value="77">77</option><option value="78">78</option><option value="79">79</option><option value="80">80</option><option value="81">81</option><option value="1">1</option><option value="2">2</option><option value="3">3</option><option value="4">4</option><option value="5">5</option><option value="6">6</option><option value="7">7</option><option value="8">8</option><option value="9">9</option><option value="10">10</option><option value="11">11</option><option value="12">12</option><option value="13">13</option><option value="14">14</option><option value="15">15</option><option value="16">16</option><option value="17">17</option><option value="18">18</option><option value="19">19</option><option value="20">20</option><option value="21">21</option><option value="22">22</option><option value="23">23</option><option value="24">24</option><option value="25">25</option><option value="26">26</option><option value="27">27</option><option value="28">28</option><option value="29">29</option><option value="30">30</option><option value="31">31</option><option value="32">32</option><option value="33">33</option><option value="34">34</option><option value="35">35</option><option value="36">36</option><option value="37">37</option><option value="38">38</option><option value="39">39</option><option value="40">40</option><option value="41">41</option><option value="42">42</option><option value="43">43</option><option value="44">44</option><option value="45">45</option><option value="46">46</option><option value="47">47</option><option value="48">48</option><option value="49">49</option><option value="50">50</option><option value="51">51</option><option value="52">52</option><option value="53">53</option><option value="54">54</option><option value="55">55</option><option value="56">56</option><option value="57">57</option><option value="58">58</option><option value="59">59</option><option value="60">60</option><option value="61">61</option><option value="62">62</option><option value="63">63</option><option value="64">64</option><option value="65">65</option><option value="66">66</option><option value="67">67</option><option value="68">68</option><option value="69">69</option><option value="70">70</option><option value="71">71</option><option value="72">72</option><option value="73">73</option><option value="74">74</option><option value="75">75</option><option value="76">76</option><option value="77">77</option><option value="78">78</option><option value="79">79</option><option value="80">80</option><option value="81">81</option></select>
  <select name="record_resolution" id="record_resolution_combo" style="display:none;">
    <option value="1920x1080">1920x1080</option>
    <option value="1600x900">1600x900</option>
    <option value="1280x720" selected="selected">1280x720</option>
    <option value="960x540">960x540</option>
    <option value="800x600">800x600</option>
    <option value="800x450">800x450</option>
    <option value="640x480">640x480</option>
    <option value="640x360">640x360</option>
  </select>
  <select name="record_fps" id="record_fps_combo" style="display:none;">
    <option value="5">5</option>
    <option value="10">10</option>
    <option value="15">15</option>
    <option value="20">20</option>
    <option value="25">25</option>
    <option value="30" selected="selected">30</option>
  </select>
  <select name="record_bitrate_kbps" id="record_bitrate_kbps_combo" style="display:none;">
    <option value="256" selected="selected">256</option>
    <option value="512">512</option>
    <option value="768">768</option>
    <option value="1024">1024</option>
    <option value="2048">2048</option>
  </select>
  <select name="rec_mime_type" id="record_mime_type_combo" style="display:none;" disabled="">
    <option value="video/webm;codecs=h264,opus">video/webm;codecs=h264,opus</option>
    <option value="video/webm;codecs=h264,pcm">video/webm;codecs=h264,pcm</option>
    <option value="video/webm;codecs=h264,wav">video/webm;codecs=h264,wav</option>
    <option value="video/webm;codecs=h264,mp3">video/webm;codecs=h264,mp3</option>
    <option value="video/webm;codecs=h264,aac">video/webm;codecs=h264,aac</option>
    <option value="video/webm;codecs=vp9,opus">video/webm;codecs=vp9,opus</option>
    <option value="video/webm;codecs=vp8,opus">video/webm;codecs=vp8,opus</option>
    <option value="video/webm">video/webm</option>
    <option value="video/mp4">video/mp4</option>
    <option value="video/mp4;codecs='avc1.424028, mp4a.40.2'">video/mp4;codecs=avc1.424028, mp4a.40.2</option>
  </select>
  <input id="filesend" type="file" class="file" name="file" t="" group="" style="display:none">
</div>
<div id="hint" class="bor bgw tdg p5 br sxs" style="z-index:999;position:absolute;display:none;max-width:300px;"></div>
<div id="input_devices" style="display:none;"></div>
<video id="local_screen_video" autoplay="" muted="" style="position:absolute;"></video>
<div id="local_screen_btn" style="display:none;"></div>

<script type="text/javascript" id="www-widgetapi-script" src="https://www.youtube.com/s/player/43bc9526/www-widgetapi.vflset/www-widgetapi.js" async=""></script><script src="https://www.youtube.com/iframe_api"></script>
<script src="https://edusp-static.ip.tv/webinar/common/streamer-worker-script.js"></script>
<script src="https://edusp-static.ip.tv/webinar/common/timer-worker-script.js"></script>
<script src="https://edusp-static.ip.tv/webinar/common/js.js?ts=1724108219210"></script>
<script src="https://apis.google.com/js/api.js"></script>


</body>
