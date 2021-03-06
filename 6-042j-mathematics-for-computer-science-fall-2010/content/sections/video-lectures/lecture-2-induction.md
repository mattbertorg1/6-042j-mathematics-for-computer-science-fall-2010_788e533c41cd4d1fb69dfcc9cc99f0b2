---
about_this_resource_text: <p><strong>Description:</strong> An introduction to proof
  techniques, covering proof by contradiction and induction, with an emphasis on the
  inductive techniques used in proof by induction.</p> <p><strong>Speaker:</strong>
  Tom Leighton</p>
course_id: 6-042j-mathematics-for-computer-science-fall-2010
embedded_media:
- id: Video-YouTube-Stream
  media_location: z8HKWUWS-lA
  parent_uid: 538a5a75a30978324d0ba06505eff624
  title: Video-YouTube-Stream
  type: Video
  uid: 9b35f9f498d0cbffce8f1218b80df7fd
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/z8HKWUWS-lA/default.jpg
  parent_uid: 538a5a75a30978324d0ba06505eff624
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 00f9c9319c7cfdc5d9f55114507766f2
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/itunes-u/lecture-2-induction/id503873536?i=110644980
  parent_uid: 538a5a75a30978324d0ba06505eff624
  title: Video-iTunes U-MP4
  type: Video
  uid: bd3eed1d0c078de3ab4f840cb50ef4bb
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.042JF10/MIT6_042JF10_lec02_300k.mp4
  parent_uid: 538a5a75a30978324d0ba06505eff624
  title: Video-Internet Archive-MP4
  type: Video
  uid: b1103c663d0e67a2e70a4572d5fc428e
- id: 3Play-3PlayYouTubeid-MP4
  media_location: z8HKWUWS-lA
  parent_uid: 538a5a75a30978324d0ba06505eff624
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 628109c0ba758c967f8da1ac993ff853
- id: z8HKWUWS-lA.srt
  parent_uid: 538a5a75a30978324d0ba06505eff624
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/lecture-2-induction/z8HKWUWS-lA.srt
  title: 3play caption file
  type: null
  uid: 4a05768d21b09745fe773fc8b36dd7f4
- id: z8HKWUWS-lA.pdf
  parent_uid: 538a5a75a30978324d0ba06505eff624
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/lecture-2-induction/z8HKWUWS-lA.pdf
  title: 3play pdf file
  type: null
  uid: 3e3c5ae1dd04aab8de88a9cf9f16544f
- id: Caption-3Play YouTube id-SRT
  parent_uid: 538a5a75a30978324d0ba06505eff624
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 65639c91f0e17279d546ca8e6187e6cd
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 538a5a75a30978324d0ba06505eff624
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 8d4bd92978b85ea70a3d6d49152ec97a
inline_embed_id: 42287028lecture2:induction54402581
layout: video
order_index: null
parent_uid: 7e5e792254d703550b60881541fa6160
related_resources_text: ''
short_url: lecture-2-induction
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/lecture-2-induction
template_type: Tabbed
title: 'Lecture 2: Induction'
transcript: '<p><span m=''560''>The</span> <span m=''680''>following</span> <span
  m=''1120''>content</span> <span m=''1710''>is</span> <span m=''1830''>provided</span>
  <span m=''2270''>under</span> <span m=''2550''>a</span> <span m=''2590''>Creative</span>
  <span m=''2990''>Commons</span> <span m=''3400''>license.</span> <span m=''4510''>Your</span>
  <span m=''4700''>support</span> <span m=''5200''>will</span> <span m=''5360''>help</span>
  <span m=''5600''>MIT</span> <span m=''6060''>OpenCourseWare</span> <span m=''6850''>continue</span>
  <span m=''7360''>to</span> <span m=''7440''>offer</span> <span m=''7850''>high</span>
  <span m=''8090''>quality</span> <span m=''8610''>educational</span> <span m=''9240''>resources</span>
  <span m=''9860''>for</span> <span m=''10010''>free.</span> <span m=''11220''>To</span>
  <span m=''11320''>make</span> <span m=''11430''>a</span> <span m=''11470''>donation,</span>
  <span m=''12160''>or</span> <span m=''12430''>view</span> <span m=''12870''>additional</span>
  <span m=''13290''>materials</span> <span m=''13820''>from</span> <span m=''13980''>hundreds</span>
  <span m=''14410''>of</span> <span m=''14520''>MIT</span> <span m=''14950''>courses,</span>
  <span m=''16059''>visit</span> <span m=''16280''>MIT</span> <span m=''16700''>OpenCourseWare</span>
  <span m=''17740''>at</span> <span m=''17910''>ocw.mit.edu.</span> </p><p><span m=''23730''>PROFESSOR:
  Last</span> <span m=''24070''>week</span> <span m=''24230''>we</span> <span m=''24350''>talked</span>
  <span m=''24670''>about</span> <span m=''24850''>the</span> <span m=''24950''>key</span>
  <span m=''25740''>components</span> <span m=''26310''>of</span> <span m=''26400''>a
  proof,</span> <span m=''27290''>propositions,</span> <span m=''28560''>axioms,</span>
  <span m=''29470''>and</span> <span m=''29630''>logical</span> <span m=''30030''>deductions,</span>
  <span m=''31380''>and</span> <span m=''31520''>as</span> <span m=''31590''>you</span>
  <span m=''31700''>probably</span> <span m=''32070''>talked</span> <span m=''32369''>about</span>
  <span m=''32619''>during</span> <span m=''32830''>recitation,</span> <span m=''34580''>we''re</span>
  <span m=''34790''>not</span> <span m=''35000''>going</span> <span m=''35100''>to</span>
  <span m=''35170''>worry</span> <span m=''35570''>too</span> <span m=''35830''>much</span>
  <span m=''36180''>about</span> <span m=''36600''>what</span> <span m=''36830''>axioms</span>
  <span m=''37690''>or</span> <span m=''37860''>logical</span> <span m=''38370''>deductions</span>
  <span m=''38930''>that</span> <span m=''39010''>you</span> <span m=''39120''>use.</span>
  <span m=''40360''>Anything</span> <span m=''41360''>that</span> <span m=''41480''>is</span>
  <span m=''41630''>reasonable,</span> <span m=''42170''>is</span> <span m=''42290''>fine</span>
  <span m=''42560''>by</span> <span m=''42760''>us.</span> <span m=''43490''>We''re</span>
  <span m=''43640''>not</span> <span m=''43830''>going</span> <span m=''43940''>to</span>
  <span m=''44020''>ask</span> <span m=''44380''>you</span> <span m=''44470''>to</span>
  <span m=''44570''>know</span> <span m=''44760''>what</span> <span m=''44910''>modus</span>
  <span m=''45280''>ponens</span> <span m=''45810''>is,</span> <span m=''46240''>or</span>
  <span m=''46340''>to</span> <span m=''46420''>label</span> <span m=''46920''>some</span>
  <span m=''47200''>law</span> <span m=''47580''>when</span> <span m=''47700''>you</span>
  <span m=''47790''>make</span> <span m=''48000''>a</span> <span m=''48050''>logical</span>
  <span m=''48470''>deduction.</span> <span m=''49420''>Just,</span> <span m=''49970''>you
  know,</span> <span m=''50280''>be</span> <span m=''50470''>reasonable.</span> <span
  m=''51360''>Any</span> <span m=''51680''>facts</span> <span m=''52070''>you</span>
  <span m=''52190''>knew</span> <span m=''52450''>coming</span> <span m=''52790''>into</span>
  <span m=''52930''>this</span> <span m=''53170''>course</span> <span m=''53500''>about</span>
  <span m=''53690''>mathematics,</span> <span m=''54860''>probably</span> <span m=''55170''>close</span>
  <span m=''55510''>enough</span> <span m=''55650''>to</span> <span m=''55740''>use</span>
  <span m=''56200''>as</span> <span m=''56380''>an</span> <span m=''56480''>axiom.</span>
  <span m=''57470''>Want</span> <span m=''57590''>to</span> <span m=''57630''>make</span>
  <span m=''57770''>sure</span> <span m=''57950''>your</span> <span m=''58080''>axioms</span>
  <span m=''58480''>are</span> <span m=''58550''>consistent,</span> <span m=''59990''>but</span>
  <span m=''60360''>that''s</span> <span m=''60600''>OK.</span> </p><p><span m=''61440''>Now</span>
  <span m=''61570''>the</span> <span m=''61700''>exception</span> <span m=''62240''>to</span>
  <span m=''62290''>this</span> <span m=''62500''>would</span> <span m=''62630''>be,</span>
  <span m=''63610''>is</span> <span m=''63760''>say</span> <span m=''63980''>we''re</span>
  <span m=''64129''>on</span> <span m=''64209''>an</span> <span m=''64280''>exam,</span>
  <span m=''65160''>and</span> <span m=''65459''>we</span> <span m=''65630''>ask</span>
  <span m=''65910''>you</span> <span m=''66010''>to</span> <span m=''66100''>prove</span>
  <span m=''66500''>some</span> <span m=''66930''>proposition,</span> <span m=''68080''>p.</span>
  <span m=''69080''>Well</span> <span m=''69340''>you</span> <span m=''69490''>can''t</span>
  <span m=''69820''>say,</span> <span m=''70220''>I</span> <span m=''70400''>already</span>
  <span m=''70620''>knew</span> <span m=''70850''>p,</span> <span m=''71420''>it''s</span>
  <span m=''71620''>an</span> <span m=''71700''>axiom,</span> <span m=''72970''>check.</span>
  <span m=''73730''>That''s</span> <span m=''74020''>not</span> <span m=''74210''>so</span>
  <span m=''74330''>good.</span> <span m=''74550''>We''re</span> <span m=''74700''>asking</span>
  <span m=''75100''>you</span> <span m=''75220''>to</span> <span m=''75610''>prove</span>
  <span m=''75890''>it</span> <span m=''76010''>from</span> <span m=''76230''>some</span>
  <span m=''76480''>more</span> <span m=''76710''>elementary</span> <span m=''77500''>facts.</span>
  <span m=''80060''>OK</span> <span m=''80460''>it''s</span> <span m=''80610''>also</span>
  <span m=''80980''>don''t</span> <span m=''81150''>want</span> <span m=''81290''>me</span>
  <span m=''81380''>making</span> <span m=''81660''>wild</span> <span m=''82060''>leaps</span>
  <span m=''82390''>of</span> <span m=''82500''>faith,</span> <span m=''82980''>or</span>
  <span m=''83170''>saying</span> <span m=''83590''>it''s</span> <span m=''83770''>obvious</span>
  <span m=''84330''>that,</span> <span m=''84590''>unless</span> <span m=''84820''>it</span>
  <span m=''84930''>really</span> <span m=''85470''>is</span> <span m=''85650''>obvious.</span>
  <span m=''86130''>That</span> <span m=''86300''>kind</span> <span m=''86460''>of</span>
  <span m=''86520''>stuff</span> <span m=''86770''>can get you in</span> <span m=''87180''>trouble.</span>
  <span m=''87920''>Much</span> <span m=''88170''>better</span> <span m=''88370''>to</span>
  <span m=''88590''>sort</span> <span m=''88760''>of</span> <span m=''88810''>explain</span>
  <span m=''89370''>the</span> <span m=''89480''>reasoning</span> <span m=''90360''>in</span>
  <span m=''90500''>the</span> <span m=''90590''>proof.</span> </p><p><span m=''92470''>Now</span>
  <span m=''92770''>the</span> <span m=''92900''>proofs</span> <span m=''93170''>that</span>
  <span m=''93290''>we</span> <span m=''93410''>covered</span> <span m=''94040''>last</span>
  <span m=''94390''>week</span> <span m=''94650''>in</span> <span m=''94730''>recitation,</span>
  <span m=''95480''>the</span> <span m=''95570''>problems</span> <span m=''96060''>set,</span>
  <span m=''96610''>were</span> <span m=''96780''>all</span> <span m=''97160''>examples</span>
  <span m=''97840''>of</span> <span m=''97940''>what</span> <span m=''98070''>are</span>
  <span m=''98140''>called</span> <span m=''98530''>direct</span> <span m=''99130''>proofs.</span>
  <span m=''100140''>You</span> <span m=''100240''>start</span> <span m=''100500''>with</span>
  <span m=''100580''>some</span> <span m=''100750''>axioms,</span> <span m=''101840''>you</span>
  <span m=''101980''>have</span> <span m=''102300''>some</span> <span m=''102450''>theorems</span>
  <span m=''102820''>you</span> <span m=''102910''>knew</span> <span m=''103050''>before</span>
  <span m=''103370''>or</span> <span m=''103690''>you</span> <span m=''103800''>proved</span>
  <span m=''104080''>along</span> <span m=''104340''>the</span> <span m=''104430''>way,</span>
  <span m=''105100''>and</span> <span m=''105250''>you</span> <span m=''105340''>make</span>
  <span m=''105620''>logical</span> <span m=''106040''>deductions</span> <span m=''106590''>until</span>
  <span m=''106800''>you</span> <span m=''106960''>get</span> <span m=''107300''>to</span>
  <span m=''107400''>where</span> <span m=''107550''>you</span> <span m=''107660''>want</span>
  <span m=''107860''>to</span> <span m=''107910''>go,</span> <span m=''108580''>the</span>
  <span m=''108680''>theorem.</span> <span m=''109960''>We''re</span> <span m=''110310''>going</span>
  <span m=''110420''>to</span> <span m=''110590''>start</span> <span m=''110910''>today</span>
  <span m=''111930''>with</span> <span m=''112580''>an</span> <span m=''112750''>indirect</span>
  <span m=''113360''>proof.</span> <span m=''113980''>For</span> <span m=''114050''>example,</span>
  <span m=''114470''>a</span> <span m=''114530''>proof</span> <span m=''114890''>by</span>
  <span m=''115020''>contradiction.</span> <span m=''116360''>And</span> <span m=''116490''>this</span>
  <span m=''116650''>is</span> <span m=''116740''>a</span> <span m=''116800''>little</span>
  <span m=''117060''>bit</span> <span m=''117270''>different.</span> <span m=''118320''>In</span>
  <span m=''118420''>a</span> <span m=''118520''>proof</span> <span m=''118740''>by</span>
  <span m=''118870''>contradiction,</span> <span m=''120860''>you</span> <span m=''121070''>assume</span>
  <span m=''121580''>the</span> <span m=''121900''>opposite</span> <span m=''122740''>of</span>
  <span m=''122880''>what</span> <span m=''123050''>you''re</span> <span m=''123170''>trying</span>
  <span m=''123540''>to</span> <span m=''123620''>prove.</span> <span m=''125350''>Then</span>
  <span m=''125550''>you</span> <span m=''125640''>just</span> <span m=''125950''>take</span>
  <span m=''126170''>steps</span> <span m=''126490''>for</span> <span m=''126750''>logical</span>
  <span m=''127120''>deductions</span> <span m=''127570''>forward</span> <span m=''127980''>until</span>
  <span m=''128340''>you</span> <span m=''128500''>arrive</span> <span m=''128960''>at</span>
  <span m=''129020''>a</span> <span m=''129080''>contradiction,</span> <span m=''130610''>something</span>
  <span m=''131160''>where</span> <span m=''131250''>you</span> <span m=''131400''>prove</span>
  <span m=''131720''>false</span> <span m=''132090''>equals</span> <span m=''132390''>true.</span>
  </p><p><span m=''133940''>Now</span> <span m=''134320''>if</span> <span m=''134470''>you</span>
  <span m=''134560''>can</span> <span m=''134670''>ever</span> <span m=''134850''>get</span>
  <span m=''135010''>to</span> <span m=''135070''>the</span> <span m=''135170''>point</span>
  <span m=''135420''>we</span> <span m=''135540''>approve</span> <span m=''136030''>something</span>
  <span m=''136350''>is</span> <span m=''136500''>false</span> <span m=''137510''>and</span>
  <span m=''137810''>true,</span> <span m=''138830''>that</span> <span m=''139040''>means</span>
  <span m=''139260''>what</span> <span m=''139390''>you</span> <span m=''139490''>assumed</span>
  <span m=''139810''>at</span> <span m=''139870''>the</span> <span m=''139970''>start</span>
  <span m=''140220''>had</span> <span m=''140370''>to</span> <span m=''140430''>be</span>
  <span m=''140540''>wrong.</span> <span m=''141750''>Namely,</span> <span m=''142640''>what</span>
  <span m=''143000''>you''re</span> <span m=''143100''>trying</span> <span m=''143310''>to</span>
  <span m=''143390''>prove</span> <span m=''144060''>has</span> <span m=''144310''>to</span>
  <span m=''144400''>be</span> <span m=''144510''>true.</span> <span m=''144920''>So</span>
  <span m=''145140''>let''s</span> <span m=''145320''>write</span> <span m=''145520''>that</span>
  <span m=''145720''>down,</span> <span m=''145940''>because</span> <span m=''146090''>it</span>
  <span m=''146180''>can</span> <span m=''146470''>be</span> <span m=''147350''>a</span>
  <span m=''147430''>little</span> <span m=''147620''>confusing</span> <span m=''148080''>the</span>
  <span m=''148160''>first</span> <span m=''148440''>time.</span> </p><p><span m=''160200''>So</span>
  <span m=''160640''>to</span> <span m=''160730''>prove</span> <span m=''162590''>a</span>
  <span m=''162650''>proposition</span> <span m=''163340''>p</span> <span m=''163860''>is</span>
  <span m=''163980''>true,</span> <span m=''169000''>you</span> <span m=''169120''>will</span>
  <span m=''169560''>assume</span> <span m=''173430''>that</span> <span m=''173600''>it''s</span>
  <span m=''173740''>false.</span> <span m=''179430''>In</span> <span m=''179580''>other</span>
  <span m=''179770''>words,</span> <span m=''180170''>that</span> <span m=''180340''>not</span>
  <span m=''180750''>p</span> <span m=''180960''>is</span> <span m=''181070''>true.</span>
  <span m=''190210''>And</span> <span m=''190440''>then</span> <span m=''193560''>you</span>
  <span m=''193760''>use</span> <span m=''194270''>that</span> <span m=''194480''>hypothesis,</span>
  <span m=''199060''>namely</span> <span m=''199340''>the</span> <span m=''199460''>p</span>
  <span m=''199630''>is</span> <span m=''199800''>false,</span> <span m=''202470''>to</span>
  <span m=''202640''>derive</span> <span m=''205310''>a</span> <span m=''205420''>falsehood.</span>
  <span m=''207040''>In other words,</span> <span m=''207300''>you</span> <span m=''207390''>prove</span>
  <span m=''207570''>a</span> <span m=''207630''>falsehood</span> <span m=''208120''>is</span>
  <span m=''208220''>true.</span> <span m=''209590''>And</span> <span m=''209740''>this</span>
  <span m=''209950''>is</span> <span m=''210950''>called</span> <span m=''211300''>deriving</span>
  <span m=''211830''>a</span> <span m=''211900''>contradiction.</span> </p><p><span
  m=''219350''>And</span> <span m=''219440''>so</span> <span m=''219570''>it</span>
  <span m=''219670''>must</span> <span m=''220010''>be</span> <span m=''220200''>that,</span>
  <span m=''220310''>in</span> <span m=''220430''>fact,</span> <span m=''220890''>p</span>
  <span m=''221000''>is</span> <span m=''221130''>not</span> <span m=''221360''>false,</span>
  <span m=''221720''>namely</span> <span m=''222000''>that</span> <span m=''222120''>it''s</span>
  <span m=''222320''>true.</span> <span m=''223980''>Now this works</span> <span m=''225070''>because</span>
  <span m=''225710''>if</span> <span m=''225840''>you</span> <span m=''226010''>can</span>
  <span m=''226160''>prove,</span> <span m=''228410''>if</span> <span m=''228600''>not</span>
  <span m=''228970''>p</span> <span m=''231490''>implies</span> <span m=''232090''>false</span>
  <span m=''233460''>is</span> <span m=''233620''>true,</span> <span m=''237290''>well</span>
  <span m=''237490''>from</span> <span m=''237650''>last</span> <span m=''237970''>time,</span>
  <span m=''239660''>the</span> <span m=''239830''>only</span> <span m=''240050''>way</span>
  <span m=''240290''>this</span> <span m=''240640''>is</span> <span m=''240750''>a</span>
  <span m=''240810''>true</span> <span m=''241060''>statement</span> <span m=''243440''>is</span>
  <span m=''243680''>if</span> <span m=''243820''>this</span> <span m=''244020''>is</span>
  <span m=''244170''>false,</span> <span m=''245530''>namely</span> <span m=''246380''>p</span>
  <span m=''246570''>is</span> <span m=''246700''>true.</span> <span m=''249020''>All</span>
  <span m=''249130''>right?</span> <span m=''249240''>So</span> <span m=''249350''>we</span>
  <span m=''249450''>can</span> <span m=''249590''>conclude</span> <span m=''250180''>that</span>
  <span m=''250290''>p</span> <span m=''250520''>is</span> <span m=''250650''>true,</span>
  <span m=''251520''>if</span> <span m=''251730''>we</span> <span m=''251830''>can</span>
  <span m=''251950''>show</span> <span m=''252230''>that</span> <span m=''252420''>not</span>
  <span m=''252750''>P</span> <span m=''252990''>implies</span> <span m=''254080''>a</span>
  <span m=''254150''>falsehood.</span> <span m=''256850''>Any</span> <span m=''257010''>questions</span>
  <span m=''258440''>about</span> <span m=''258640''>that?</span> <span m=''258779''>It''s</span>
  <span m=''258839''>sort</span> <span m=''259040''>of</span> <span m=''259130''>a</span>
  <span m=''259630''>lot</span> <span m=''259890''>of</span> <span m=''260170''>sort</span>
  <span m=''260339''>of</span> <span m=''260399''>notation,</span> <span m=''261860''>and</span>
  <span m=''262340''>until</span> <span m=''262460''>you''ve</span> <span m=''262610''>seen,</span>
  <span m=''262970''>it</span> <span m=''263060''>can</span> <span m=''263280''>be</span>
  <span m=''263390''>confusing.</span> </p><p><span m=''265300''>So maybe</span> <span
  m=''265420''>we</span> <span m=''265510''>should</span> <span m=''265720''>do</span>
  <span m=''266560''>an</span> <span m=''266640''>example.</span> <span m=''268970''>Let''s</span>
  <span m=''269180''>prove</span> <span m=''271440''>that</span> <span m=''271640''>square</span>
  <span m=''271990''>root</span> <span m=''272130''>of</span> <span m=''272210''>2</span>
  <span m=''272490''>is</span> <span m=''272590''>irrational.</span> <span m=''280330''>Is</span>
  <span m=''280440''>irrational.</span> <span m=''285540''>OK,</span> <span m=''285830''>everybody</span>
  <span m=''286110''>knows</span> <span m=''286320''>what</span> <span m=''286410''>an</span>
  <span m=''286480''>irrational</span> <span m=''287060''>number</span> <span m=''287410''>is?</span>
  <span m=''289290''>That''s</span> <span m=''289470''>something</span> <span m=''289770''>that</span>
  <span m=''290070''>can''t</span> <span m=''290480''>be</span> <span m=''290590''>expressed</span>
  <span m=''291090''>as</span> <span m=''291200''>the</span> <span m=''291320''>ratio</span>
  <span m=''291740''>of</span> <span m=''291830''>integers.</span> <span m=''293460''>OK,</span>
  <span m=''293630''>and</span> <span m=''293700''>probably</span> <span m=''293970''>most</span>
  <span m=''294270''>people</span> <span m=''294510''>already</span> <span m=''294820''>know</span>
  <span m=''295120''>that--</span> <span m=''295440''>how</span> <span m=''295620''>many</span>
  <span m=''295780''>people</span> <span m=''296210''>have</span> <span m=''296990''>not</span>
  <span m=''297300''>seen</span> <span m=''297460''>a proof</span> <span m=''297840''>that</span>
  <span m=''297940''>square</span> <span m=''298150''>root</span> <span m=''298240''>of</span>
  <span m=''298330''>2</span> <span m=''298690''>is</span> <span m=''298800''>a</span>
  <span m=''298870''>rational</span> <span m=''299300''>before?</span> <span m=''301780''>So</span>
  <span m=''301920''>most</span> <span m=''302220''>of</span> <span m=''302310''>you</span>
  <span m=''302450''>have</span> <span m=''302550''>seen</span> <span m=''302730''>a
  proof of</span> <span m=''303050''>that,</span> <span m=''303300''>good.</span>
  <span m=''303820''>You know, if</span> <span m=''304070''>you</span> <span m=''304150''>try</span>
  <span m=''304340''>to</span> <span m=''304420''>do</span> <span m=''304550''>a</span>
  <span m=''304610''>direct</span> <span m=''305060''>proof</span> <span m=''305240''>for</span>
  <span m=''305320''>this,</span> <span m=''305520''>it''s</span> <span m=''305640''>pretty</span>
  <span m=''305850''>hard.</span> <span m=''306840''>How</span> <span m=''307030''>do</span>
  <span m=''307100''>you</span> <span m=''307190''>show</span> <span m=''307530''>there''s</span>
  <span m=''307760''>no</span> <span m=''308060''>way</span> <span m=''308350''>to</span>
  <span m=''308460''>represent</span> <span m=''308900''>the</span> <span m=''308980''>square</span>
  <span m=''309160''>root</span> <span m=''309280''>of</span> <span m=''309390''>2</span>
  <span m=''309690''>is</span> <span m=''310560''>as</span> <span m=''310740''>integers</span>
  <span m=''311120''>a</span> <span m=''311260''>over</span> <span m=''311450''>b?</span>
  </p><p><span m=''312950''>But</span> <span m=''313070''>it''s</span> <span m=''313210''>very</span>
  <span m=''313510''>easy,</span> <span m=''314720''>if</span> <span m=''314900''>we</span>
  <span m=''314990''>do</span> <span m=''315150''>a</span> <span m=''315220''>proof</span>
  <span m=''315470''>by</span> <span m=''315590''>contradiction.</span> <span m=''317040''>Now</span>
  <span m=''317160''>when</span> <span m=''317240''>you''re</span> <span m=''317310''>doing</span>
  <span m=''317560''>a</span> <span m=''317620''>proof</span> <span m=''317840''>by</span>
  <span m=''317960''>contradiction,</span> <span m=''319010''>always</span> <span
  m=''319390''>start</span> <span m=''319670''>off</span> <span m=''319890''>by</span>
  <span m=''320348''>saying,</span> <span m=''322180''>by</span> <span m=''322640''>contradiction.</span>
  <span m=''323540''>Write</span> <span m=''323790''>that</span> <span m=''324000''>down.</span>
  <span m=''325910''>And</span> <span m=''326120''>then</span> <span m=''326280''>what</span>
  <span m=''326400''>you</span> <span m=''326700''>do</span> <span m=''326840''>next</span>
  <span m=''327380''>is</span> <span m=''327720''>you</span> <span m=''327830''>say,</span>
  <span m=''328140''>I''m</span> <span m=''328290''>going</span> <span m=''328480''>to</span>
  <span m=''328550''>assume,</span> <span m=''330780''>for</span> <span m=''330940''>the</span>
  <span m=''331060''>purpose</span> <span m=''331430''>of</span> <span m=''331520''>contradiction,</span>
  <span m=''341690''>that</span> <span m=''345250''>p</span> <span m=''345490''>is</span>
  <span m=''345660''>false</span> <span m=''345980''>and</span> <span m=''346080''>when</span>
  <span m=''346160''>not</span> <span m=''346430''>p</span> <span m=''346550''>is</span>
  <span m=''346690''>true.</span> <span m=''347350''>In</span> <span m=''347450''>this</span>
  <span m=''347530''>case,</span> <span m=''347870''>that</span> <span m=''347950''>would</span>
  <span m=''348070''>be</span> <span m=''349050''>square</span> <span m=''349260''>root</span>
  <span m=''349330''>of</span> <span m=''349420''>2</span> <span m=''349900''>is</span>
  <span m=''350090''>rational.</span> </p><p><span m=''356170''>So</span> <span m=''356340''>in</span>
  <span m=''356420''>this</span> <span m=''356660''>case,</span> <span m=''358350''>here''s</span>
  <span m=''358600''>what</span> <span m=''358670''>we''re</span> <span m=''358800''>trying</span>
  <span m=''359060''>to</span> <span m=''359130''>prove.</span> <span m=''359520''>That''s</span>
  <span m=''359790''>p.</span> <span m=''361730''>I''m</span> <span m=''361890''>going</span>
  <span m=''362140''>to</span> <span m=''362250''>assume</span> <span m=''363060''>not</span>
  <span m=''363380''>p,</span> <span m=''363590''>namely</span> <span m=''363930''>that</span>
  <span m=''364040''>square</span> <span m=''364320''>root</span> <span m=''364410''>of</span>
  <span m=''364490''>2</span> <span m=''364740''>is</span> <span m=''364880''>irrational</span>
  <span m=''365470''>number.</span> <span m=''366570''>Then</span> <span m=''366750''>I''m</span>
  <span m=''366830''>going</span> <span m=''366930''>to</span> <span m=''366990''>get</span>
  <span m=''367160''>a</span> <span m=''367220''>contradiction</span> <span m=''367870''>or</span>
  <span m=''367990''>falsehood,</span> <span m=''368830''>and</span> <span m=''368990''>then</span>
  <span m=''369110''>I''m</span> <span m=''369200''>going</span> <span m=''369320''>to</span>
  <span m=''369420''>know</span> <span m=''371020''>that</span> <span m=''371150''>p</span>
  <span m=''371390''>was</span> <span m=''371540''>true</span> <span m=''371790''>after</span>
  <span m=''372080''>all.</span> <span m=''374540''>All right, so</span> <span m=''374890''>let''s</span>
  <span m=''375050''>see</span> <span m=''375190''>where</span> <span m=''375290''>this</span>
  <span m=''375510''>leads</span> <span m=''375800''>us.</span> <span m=''378250''>Well,</span>
  <span m=''378600''>if</span> <span m=''378750''>square</span> <span m=''379000''>root</span>
  <span m=''379070''>of</span> <span m=''379160''>2</span> <span m=''379330''>is</span>
  <span m=''379440''>rational</span> <span m=''379980''>then</span> <span m=''380080''>we</span>
  <span m=''380180''>can</span> <span m=''380310''>express</span> <span m=''380800''>it</span>
  <span m=''380970''>as</span> <span m=''381330''>a</span> <span m=''381530''>over</span>
  <span m=''381740''>b,</span> <span m=''383070''>where</span> <span m=''383390''>a</span>
  <span m=''383570''>over</span> <span m=''383720''>b</span> <span m=''383850''>is</span>
  <span m=''383990''>a</span> <span m=''384050''>fraction</span> <span m=''384590''>in</span>
  <span m=''384690''>lowest</span> <span m=''385040''>terms.</span> <span m=''390520''>That</span>
  <span m=''390700''>means</span> <span m=''390990''>a and</span> <span m=''391240''>b</span>
  <span m=''391400''>have</span> <span m=''391570''>no</span> <span m=''391760''>common</span>
  <span m=''392060''>divisors.</span> <span m=''396140''>And</span> <span m=''396580''>then</span>
  <span m=''396740''>I</span> <span m=''396830''>can</span> <span m=''397020''>square</span>
  <span m=''397480''>both</span> <span m=''397710''>sides,</span> <span m=''399720''>and
  I</span> <span m=''399880''>get</span> <span m=''400090''>two</span> <span m=''400360''>is</span>
  <span m=''400480''>a</span> <span m=''400660''>squared</span> <span m=''401190''>over</span>
  <span m=''401400''>b</span> <span m=''401590''>squared.</span> <span m=''405370''>Then</span>
  <span m=''405470''>I</span> <span m=''405540''>multiply</span> <span m=''405980''>by</span>
  <span m=''406160''>b</span> <span m=''406380''>squared,</span> <span m=''406695''>and</span>
  <span m=''407010''>I</span> <span m=''407070''>get</span> <span m=''408100''>2b</span>
  <span m=''408570''>squared</span> <span m=''409080''>equals</span> <span m=''409470''>a</span>
  <span m=''409600''>squared.</span> </p><p><span m=''411900''>And</span> <span m=''411970''>what</span>
  <span m=''412120''>does</span> <span m=''412270''>that</span> <span m=''412650''>imply</span>
  <span m=''413010''>about</span> <span m=''413270''>a?</span> <span m=''415340''>What</span>
  <span m=''415480''>can</span> <span m=''415600''>you</span> <span m=''415690''>tell</span>
  <span m=''415900''>me</span> <span m=''416020''>about</span> <span m=''416360''>a
  if it</span> <span m=''416840''>equals--</span> <span m=''417710''>if</span> <span
  m=''417970''>a</span> <span m=''418070''>squared</span> <span m=''418340''>is</span>
  <span m=''418430''>2b</span> <span m=''418790''>squared?</span> <span m=''424840''>Anything</span>
  <span m=''425160''>special</span> <span m=''425540''>about</span> <span m=''425780''>a?</span>
  <span m=''425910''>Could</span> <span m=''426120''>a</span> <span m=''426330''>be</span>
  <span m=''426990''>anything?</span> <span m=''429990''>A</span> <span m=''430180''>squared</span>
  <span m=''430510''>is</span> <span m=''430670''>even,</span> <span m=''432040''>all
  right?</span> <span m=''432180''>Because 2b</span> <span m=''432480''>squared</span>
  <span m=''432760''>is</span> <span m=''432840''>an</span> <span m=''432920''>even</span>
  <span m=''433110''>number,</span> <span m=''433380''>so</span> <span m=''433570''>a</span>
  <span m=''433770''>squared</span> <span m=''434080''>is</span> <span m=''434190''>even,</span>
  <span m=''435360''>and</span> <span m=''435490''>what</span> <span m=''435600''>does</span>
  <span m=''435680''>that</span> <span m=''435810''>mean</span> <span m=''435960''>about</span>
  <span m=''436180''>a?</span> <span m=''438605''>A</span> <span m=''439090''>is</span>
  <span m=''439270''>even.</span> <span m=''440140''>B</span> <span m=''440320''>squared</span>
  <span m=''440720''>is</span> <span m=''441045''>even,</span> <span m=''441126''>then</span>
  <span m=''441207''>a</span> <span m=''441288''>is</span> <span m=''441370''>even.</span>
  <span m=''443570''>So</span> <span m=''443900''>a</span> <span m=''443970''>is</span>
  <span m=''444130''>even.</span> <span m=''446860''>So</span> <span m=''447260''>we</span>
  <span m=''447420''>could</span> <span m=''447540''>write</span> <span m=''447810''>that</span>
  <span m=''448240''>as</span> <span m=''448690''>two</span> <span m=''449110''>divides</span>
  <span m=''449730''>a.</span> <span m=''450080''>That''s</span> <span m=''450340''>the</span>
  <span m=''450440''>divide</span> <span m=''450890''>symbol.</span> <span m=''451250''>You''ll</span>
  <span m=''451360''>see</span> <span m=''451530''>a</span> <span m=''451600''>lot</span>
  <span m=''451860''>of</span> <span m=''451930''>that</span> <span m=''452300''>next</span>
  <span m=''452560''>week.</span> </p><p><span m=''454700''>All</span> <span m=''454800''>right</span>
  <span m=''454920''>if</span> <span m=''455060''>a</span> <span m=''455310''>is</span>
  <span m=''455440''>even,</span> <span m=''455800''>what</span> <span m=''455930''>do</span>
  <span m=''456010''>I</span> <span m=''456080''>know</span> <span m=''456270''>about</span>
  <span m=''456470''>a</span> <span m=''456600''>squared?</span> <span m=''457940''>I</span>
  <span m=''458030''>know</span> <span m=''458200''>more</span> <span m=''458450''>than</span>
  <span m=''458580''>just,</span> <span m=''458840''>it''s</span> <span m=''458960''>even.</span>
  <span m=''464020''>What</span> <span m=''464200''>is it?</span> <span m=''464510''>It''s</span>
  <span m=''464550''>multiple</span> <span m=''464990''>of</span> <span m=''465810''>4,</span>
  <span m=''466490''>yeah.</span> <span m=''467160''>So</span> <span m=''467330''>that</span>
  <span m=''467550''>means</span> <span m=''467870''>that</span> <span m=''469110''>four</span>
  <span m=''471070''>divides</span> <span m=''471550''>a</span> <span m=''471710''>squared.</span>
  <span m=''473030''>A</span> <span m=''473190''>squared</span> <span m=''473500''>is</span>
  <span m=''473790''>2b</span> <span m=''474230''>squared,</span> <span m=''474740''>so</span>
  <span m=''474840''>that</span> <span m=''474870''>means</span> <span m=''475150''>that</span>
  <span m=''475350''>four</span> <span m=''475830''>divides</span> <span m=''476370''>2b</span>
  <span m=''476840''>squared.</span> <span m=''477970''>Divide</span> <span m=''478300''>each</span>
  <span m=''478460''>side</span> <span m=''478710''>by</span> <span m=''478850''>2</span>
  <span m=''479250''>means</span> <span m=''479720''>2</span> <span m=''480140''>divides</span>
  <span m=''480730''>b</span> <span m=''480970''>squared.</span> <span m=''482780''>What</span>
  <span m=''483000''>does</span> <span m=''483100''>that</span> <span m=''483230''>imply</span>
  <span m=''483520''>about</span> <span m=''483940''>b?</span> <span m=''487764''>B
  is</span> <span m=''488250''>even.</span> <span m=''490870''>All right,</span> <span
  m=''491110''>b is</span> <span m=''491280''>even,</span> <span m=''492200''>good.</span>
  <span m=''493750''>Well,</span> <span m=''494830''>I''ve</span> <span m=''494960''>got</span>
  <span m=''495240''>a</span> <span m=''495500''>is</span> <span m=''495670''>even</span>
  <span m=''496030''>and</span> <span m=''496300''>b</span> <span m=''496600''>is</span>
  <span m=''496760''>even.</span> <span m=''499620''>I</span> <span m=''499730''>got</span>
  <span m=''499930''>a</span> <span m=''499980''>contradiction</span> <span m=''500610''>here,</span>
  <span m=''500930''>somewhere?</span> <span m=''504080''>Yeah</span> <span m=''504910''>a</span>
  <span m=''505390''>over</span> <span m=''505670''>b</span> <span m=''505920''>was</span>
  <span m=''506160''>not</span> <span m=''506700''>a</span> <span m=''506810''>fraction</span>
  <span m=''507320''>in</span> <span m=''507420''>lowest</span> <span m=''507790''>terms,</span>
  <span m=''508260''>because</span> <span m=''508710''>both</span> <span m=''509130''>and</span>
  <span m=''509500''>b</span> <span m=''509730''>are</span> <span m=''509840''>even.</span>
  <span m=''511410''>All</span> <span m=''511470''>right,</span> <span m=''511850''>so</span>
  <span m=''513080''>that</span> <span m=''513270''>implies</span> <span m=''516690''>a</span>
  <span m=''517030''>over</span> <span m=''517299''>b</span> <span m=''518600''>is</span>
  <span m=''518909''>not</span> <span m=''520760''>in</span> <span m=''520919''>lowest</span>
  <span m=''521280''>terms.</span> <span m=''526060''>And</span> <span m=''526400''>that</span>
  <span m=''528120''>is</span> <span m=''528390''>a</span> <span m=''528470''>contradiction.</span>
  </p><p><span m=''530500''>Now</span> <span m=''530840''>you''ll</span> <span m=''530990''>see</span>
  <span m=''531180''>that</span> <span m=''531400''>written</span> <span m=''531590''>lots</span>
  <span m=''531980''>of</span> <span m=''532060''>ways.</span> <span m=''532660''>One</span>
  <span m=''532780''>is,</span> <span m=''532900''>you</span> <span m=''533360''>can</span>
  <span m=''533520''>say a</span> <span m=''533780''>contradiction,</span> <span m=''534410''>sometimes</span>
  <span m=''534820''>you''ll</span> <span m=''534960''>see</span> <span m=''535310''>just</span>
  <span m=''535635''>this</span> <span m=''536280''>sharp</span> <span m=''536670''>symbol</span>
  <span m=''537040''>written,</span> <span m=''537880''>and</span> <span m=''537990''>that</span>
  <span m=''538150''>means</span> <span m=''538360''>you''ve</span> <span m=''538520''>got</span>
  <span m=''538740''>to</span> <span m=''538820''>a</span> <span m=''538880''>contradiction.</span>
  <span m=''539460''>Because</span> <span m=''540480''>here,</span> <span m=''540810''>we</span>
  <span m=''541490''>had</span> <span m=''541730''>it</span> <span m=''541820''>being</span>
  <span m=''542160''>in</span> <span m=''542240''>lowest</span> <span m=''542590''>terms,</span>
  <span m=''543510''>and</span> <span m=''543630''>here</span> <span m=''543870''>we</span>
  <span m=''543990''>have</span> <span m=''544250''>it</span> <span m=''544380''>not</span>
  <span m=''544590''>in</span> <span m=''544680''>lowest</span> <span m=''544980''>terms.</span>
  <span m=''545260''>You</span> <span m=''545350''>can''t</span> <span m=''545590''>have</span>
  <span m=''545780''>both</span> <span m=''546020''>at</span> <span m=''546100''>the</span>
  <span m=''546170''>same</span> <span m=''546440''>time,</span> <span m=''546700''>so</span>
  <span m=''546820''>you</span> <span m=''546860''>got</span> <span m=''546990''>a</span>
  <span m=''547040''>contradiction.</span> <span m=''548910''>And</span> <span m=''549160''>that</span>
  <span m=''549400''>means</span> <span m=''549700''>we''ve</span> <span m=''549890''>now</span>
  <span m=''550510''>proved</span> <span m=''551690''>that</span> <span m=''551850''>this</span>
  <span m=''552010''>assumption</span> <span m=''552500''>was</span> <span m=''552650''>wrong.</span>
  <span m=''554080''>Square</span> <span m=''554310''>root</span> <span m=''554430''>of</span>
  <span m=''554520''>2</span> <span m=''554730''>is</span> <span m=''556050''>not</span>
  <span m=''556240''>rational,</span> <span m=''556750''>so</span> <span m=''556850''>it</span>
  <span m=''556950''>must</span> <span m=''557000''>be</span> <span m=''557490''>irrational.</span>
  <span m=''564420''>and</span> <span m=''564550''>then</span> <span m=''564720''>we</span>
  <span m=''564830''>put</span> <span m=''565000''>a</span> <span m=''565050''>little</span>
  <span m=''565250''>box</span> <span m=''565710''>here</span> <span m=''565890''>at</span>
  <span m=''565970''>the</span> <span m=''566130''>end,</span> <span m=''566540''>or</span>
  <span m=''566620''>sometimes</span> <span m=''566990''>you''ll</span> <span m=''567110''>see</span>
  <span m=''567270''>a</span> <span m=''567340''>check,</span> <span m=''568120''>sometimes</span>
  <span m=''568510''>you''ll</span> <span m=''568620''>see</span> <span m=''568810''>QED,</span>
  <span m=''570000''>that</span> <span m=''570160''>says</span> <span m=''570650''>the</span>
  <span m=''570740''>proof''s</span> <span m=''571020''>done</span> <span m=''571230''>now.</span>
  <span m=''572910''>It''s</span> <span m=''573070''>over.</span> <span m=''574640''>Any</span>
  <span m=''574810''>questions</span> <span m=''577000''>about</span> <span m=''577220''>that</span>
  <span m=''577410''>proof?</span> </p><p><span m=''578790''>We''re</span> <span m=''578890''>going</span>
  <span m=''578970''>to</span> <span m=''579010''>do</span> <span m=''579110''>a</span>
  <span m=''579220''>lot</span> <span m=''579490''>of</span> <span m=''579570''>proofs</span>
  <span m=''579800''>by</span> <span m=''579920''>contradiction.</span> <span m=''581740''>Actually,</span>
  <span m=''582530''>there''s</span> <span m=''582730''>an</span> <span m=''582810''>interesting</span>
  <span m=''583190''>story</span> <span m=''583640''>behind</span> <span m=''584040''>this</span>
  <span m=''584220''>proof.</span> <span m=''585630''>As</span> <span m=''585830''>far</span>
  <span m=''586060''>as</span> <span m=''586150''>we</span> <span m=''586260''>know,</span>
  <span m=''586500''>it</span> <span m=''586590''>was</span> <span m=''586750''>first</span>
  <span m=''587080''>discovered</span> <span m=''587520''>by</span> <span m=''587650''>the</span>
  <span m=''587930''>Pythagoreans,</span> <span m=''589600''>way</span> <span m=''589930''>back</span>
  <span m=''590200''>when</span> <span m=''590470''>in</span> <span m=''590630''>ancient</span>
  <span m=''590990''>Greece.</span> <span m=''592270''>And</span> <span m=''592850''>the</span>
  <span m=''592970''>Pythagoreans</span> <span m=''593770''>were</span> <span m=''594070''>a</span>
  <span m=''594190''>religious</span> <span m=''594620''>society</span> <span m=''595330''>started</span>
  <span m=''595650''>by</span> <span m=''595820''>Pythagoras,</span> <span m=''596510''>of</span>
  <span m=''596980''>Pythagoras</span> <span m=''597550''>theorem</span> <span m=''597940''>frame.</span>
  <span m=''599350''>Now</span> <span m=''599600''>it</span> <span m=''599710''>sounds</span>
  <span m=''600060''>weird</span> <span m=''600430''>today,</span> <span m=''601260''>but</span>
  <span m=''601470''>back</span> <span m=''601750''>then,</span> <span m=''602840''>in</span>
  <span m=''602970''>ancient</span> <span m=''603240''>Greece,</span> <span m=''603850''>math</span>
  <span m=''604250''>was</span> <span m=''604430''>a</span> <span m=''604530''>religion,</span>
  <span m=''606020''>all</span> <span m=''606180''>right?</span> <span m=''607080''>Every</span>
  <span m=''607250''>once</span> <span m=''607480''>in</span> <span m=''607530''>while</span>
  <span m=''607650''>you''ll</span> <span m=''607770''>see</span> <span m=''607900''>somebody</span>
  <span m=''608300''>around</span> <span m=''608490''>MIT,</span> <span m=''608970''>and</span>
  <span m=''609210''>you''ll</span> <span m=''609350''>think</span> <span m=''609670''>he</span>
  <span m=''609820''>must</span> <span m=''610070''>think</span> <span m=''610230''>math</span>
  <span m=''610460''>is</span> <span m=''610580''>a</span> <span m=''610640''>religion,</span>
  <span m=''611920''>but</span> <span m=''612230''>back</span> <span m=''612490''>then</span>
  <span m=''612640''>it</span> <span m=''612720''>really</span> <span m=''612990''>was,</span>
  <span m=''613510''>and</span> <span m=''613670''>it</span> <span m=''613740''>was</span>
  <span m=''613870''>ruled</span> <span m=''614180''>by</span> <span m=''614300''>God,</span>
  <span m=''614860''>because</span> <span m=''615080''>this</span> <span m=''615250''>is</span>
  <span m=''615460''>ancient</span> <span m=''615800''>Greece.</span> </p><p><span
  m=''616620''>And</span> <span m=''616840''>there</span> <span m=''616940''>were</span>
  <span m=''617060''>two</span> <span m=''617280''>key</span> <span m=''617500''>gods</span>
  <span m=''618230''>in</span> <span m=''618340''>this</span> <span m=''618510''>religion,</span>
  <span m=''619770''>Apeiron</span> <span m=''620430''>and</span> <span m=''620610''>Peros.</span>
  <span m=''621790''>Now</span> <span m=''622040''>Apeiron</span> <span m=''622990''>was</span>
  <span m=''623280''>the</span> <span m=''623360''>bad</span> <span m=''623730''>god,</span>
  <span m=''624750''>and</span> <span m=''625140''>he</span> <span m=''625320''>was</span>
  <span m=''625480''>the</span> <span m=''625600''>god</span> <span m=''625910''>of</span>
  <span m=''626000''>infinity,</span> <span m=''626730''>because</span> <span m=''627020''>infinity</span>
  <span m=''627500''>was</span> <span m=''627660''>considered</span> <span m=''628070''>all</span>
  <span m=''628370''>that</span> <span m=''628480''>was</span> <span m=''628640''>bad.</span>
  <span m=''629700''>And</span> <span m=''630030''>I</span> <span m=''630180''>don''t</span>
  <span m=''630320''>think</span> <span m=''630470''>we''ll</span> <span m=''630590''>do</span>
  <span m=''630720''>a</span> <span m=''630790''>lot</span> <span m=''630940''>with</span>
  <span m=''631060''>infinity</span> <span m=''631540''>this</span> <span m=''631640''>term,</span>
  <span m=''632020''>but</span> <span m=''632120''>if</span> <span m=''632220''>we</span>
  <span m=''632230''>do</span> <span m=''632510''>you''ll</span> <span m=''632890''>appreciate</span>
  <span m=''633570''>why</span> <span m=''633860''>that''s</span> <span m=''634090''>the</span>
  <span m=''634170''>case.</span> <span m=''635270''>And</span> <span m=''636140''>Peros</span>
  <span m=''636700''>was</span> <span m=''636900''>a</span> <span m=''636970''>good</span>
  <span m=''637170''>god.</span> <span m=''637540''>He</span> <span m=''637780''>was</span>
  <span m=''637930''>the</span> <span m=''638040''>god</span> <span m=''638330''>of</span>
  <span m=''638390''>the</span> <span m=''638470''>finite</span> <span m=''638940''>world,</span>
  <span m=''639580''>and</span> <span m=''639780''>represented</span> <span m=''640350''>everything</span>
  <span m=''640750''>that</span> <span m=''640850''>was</span> <span m=''641020''>good</span>
  <span m=''641750''>to</span> <span m=''641900''>the</span> <span m=''642010''>ancient</span>
  <span m=''642290''>Greeks.</span> </p><p><span m=''643570''>Now</span> <span m=''643750''>one</span>
  <span m=''643930''>of</span> <span m=''644000''>their</span> <span m=''644140''>main</span>
  <span m=''644660''>axioms,</span> <span m=''645420''>or</span> <span m=''645570''>beliefs,</span>
  <span m=''646930''>was</span> <span m=''647310''>that</span> <span m=''647420''>there</span>
  <span m=''647530''>were</span> <span m=''647690''>no</span> <span m=''648340''>irrational</span>
  <span m=''649110''>numbers.</span> <span m=''650290''>They</span> <span m=''650420''>just</span>
  <span m=''650920''>didn''t</span> <span m=''651420''>exist.</span> <span m=''653070''>Now</span>
  <span m=''653380''>the</span> <span m=''653510''>reason</span> <span m=''653930''>is,</span>
  <span m=''654030''>they</span> <span m=''654130''>didn''t</span> <span m=''654480''>like</span>
  <span m=''654730''>irrational</span> <span m=''655210''>numbers.</span> <span m=''655570''>They</span>
  <span m=''655650''>were</span> <span m=''655790''>bad.</span> <span m=''656690''>Because,</span>
  <span m=''657660''>well</span> <span m=''657830''>they''re</span> <span m=''657970''>infinite.</span>
  <span m=''658420''>You</span> <span m=''658530''>can''t</span> <span m=''658910''>write</span>
  <span m=''659200''>them</span> <span m=''660060''>as</span> <span m=''660240''>a</span>
  <span m=''660330''>decimal</span> <span m=''661390''>without</span> <span m=''661690''>repeating</span>
  <span m=''662140''>forever,</span> <span m=''663190''>and</span> <span m=''663330''>you
  know,</span> <span m=''663640''>just</span> <span m=''664140''>an</span> <span m=''664300''>infinite</span>
  <span m=''664990''>sort</span> <span m=''665130''>of</span> <span m=''665220''>decimal</span>
  <span m=''665540''>representation.</span> <span m=''667160''>They</span> <span m=''667320''>liked</span>
  <span m=''668590''>rational</span> <span m=''669100''>numbers,</span> <span m=''669570''>you
  know, like</span> <span m=''669760''>one</span> <span m=''670000''>seventh?</span>
  <span m=''671530''>That''s</span> <span m=''671770''>a</span> <span m=''671840''>good</span>
  <span m=''672060''>number,</span> <span m=''672420''>because</span> <span m=''673010''>you</span>
  <span m=''673130''>can</span> <span m=''673250''>write</span> <span m=''673490''>it</span>
  <span m=''673540''>as</span> <span m=''673650''>0.142857</span> <span m=''677290''>repeating.</span>
  <span m=''679330''>So</span> <span m=''679420''>rational</span> <span m=''679910''>numbers</span>
  <span m=''680270''>are</span> <span m=''680450''>finite,</span> <span m=''681210''>in</span>
  <span m=''681290''>that</span> <span m=''681370''>you</span> <span m=''681470''>can</span>
  <span m=''681580''>always</span> <span m=''681870''>find</span> <span m=''682100''>a</span>
  <span m=''682140''>repeating</span> <span m=''682520''>pattern</span> <span m=''682950''>of</span>
  <span m=''683040''>finite</span> <span m=''683390''>length.</span> <span m=''684100''>Irrational</span>
  <span m=''684700''>numbers</span> <span m=''685140''>are</span> <span m=''685270''>not.</span>
  <span m=''685540''>They''re</span> <span m=''685700''>infinite</span> <span m=''686090''>in</span>
  <span m=''686180''>that</span> <span m=''686390''>sense</span> <span m=''686820''>of</span>
  <span m=''686930''>the</span> <span m=''687360''>ancient</span> <span m=''687620''>Greeks.</span>
  </p><p><span m=''689080''>So</span> <span m=''689240''>they</span> <span m=''689360''>said</span>
  <span m=''689550''>there</span> <span m=''689650''>were</span> <span m=''689890''>no</span>
  <span m=''690110''>irrational</span> <span m=''690530''>numbers.</span> <span m=''690840''>That</span>
  <span m=''690990''>was</span> <span m=''691360''>an</span> <span m=''691460''>early</span>
  <span m=''691710''>axiom.</span> <span m=''693380''>Now</span> <span m=''694690''>they</span>
  <span m=''694850''>also</span> <span m=''695090''>had</span> <span m=''695280''>an</span>
  <span m=''695370''>axiom</span> <span m=''696320''>that</span> <span m=''696480''>said</span>
  <span m=''696810''>that</span> <span m=''697040''>every</span> <span m=''698440''>length</span>
  <span m=''699170''>of</span> <span m=''699290''>a</span> <span m=''699360''>line</span>
  <span m=''701030''>was</span> <span m=''701340''>finite,</span> <span m=''702530''>therefore</span>
  <span m=''702930''>rational.</span> <span m=''704210''>All right,</span> <span m=''704380''>you
  know</span> <span m=''704520''>the</span> <span m=''704770''>ancient</span> <span
  m=''705080''>Greeks</span> <span m=''705300''>were</span> <span m=''705410''>good</span>
  <span m=''705650''>with</span> <span m=''705890''>a</span> <span m=''706960''>compass,</span>
  <span m=''707340''>and</span> <span m=''707510''>drawing</span> <span m=''707800''>lines</span>
  <span m=''708130''>with</span> <span m=''708230''>straight</span> <span m=''708480''>edges</span>
  <span m=''708740''>and</span> <span m=''708850''>stuff.</span> <span m=''709570''>So</span>
  <span m=''709690''>they</span> <span m=''709820''>said</span> <span m=''710020''>any</span>
  <span m=''710230''>line</span> <span m=''710510''>that you</span> <span m=''710730''>can</span>
  <span m=''710910''>construct</span> <span m=''712090''>has</span> <span m=''712470''>a</span>
  <span m=''712670''>finite</span> <span m=''713190''>length</span> <span m=''713530''>to</span>
  <span m=''713710''>it,</span> <span m=''713800''>so</span> <span m=''713920''>therefore
  it</span> <span m=''714270''>has</span> <span m=''714470''>a</span> <span m=''714540''>rational</span>
  <span m=''715130''>length.</span> </p><p><span m=''715390''>That</span> <span m=''715540''>was</span>
  <span m=''715790''>axiom</span> <span m=''716180''>number</span> <span m=''716450''>two.</span>
  <span m=''718740''>Now</span> <span m=''719420''>they</span> <span m=''719540''>were</span>
  <span m=''719660''>good</span> <span m=''719870''>geometers,</span> <span m=''720410''>so</span>
  <span m=''720570''>they</span> <span m=''720730''>knew,</span> <span m=''721420''>of</span>
  <span m=''721580''>course,</span> <span m=''721910''>they</span> <span m=''722010''>developed</span>
  <span m=''722380''>the</span> <span m=''722480''>Pythagorean</span> <span m=''723050''>theorem.</span>
  <span m=''724070''>But</span> <span m=''724190''>if</span> <span m=''724270''>you</span>
  <span m=''724360''>took</span> <span m=''724510''>a</span> <span m=''724580''>triangle,</span>
  <span m=''724890''>and you</span> <span m=''725200''>have</span> <span m=''725470''>side</span>
  <span m=''725760''>lengths</span> <span m=''726070''>one,</span> <span m=''727520''>the</span>
  <span m=''727630''>length</span> <span m=''727900''>of</span> <span m=''727980''>the</span>
  <span m=''728050''>hypotenuse</span> <span m=''729520''>was</span> <span m=''729590''>square</span>
  <span m=''729870''>root</span> <span m=''730010''>2.</span> <span m=''731410''>Therefore</span>
  <span m=''731750''>they</span> <span m=''731890''>had</span> <span m=''732010''>a</span>
  <span m=''732070''>theorem</span> <span m=''732450''>that</span> <span m=''732640''>said</span>
  <span m=''732760''>square</span> <span m=''733020''>root</span> <span m=''733180''>2</span>
  <span m=''733390''>was</span> <span m=''733560''>rational.</span> <span m=''734946''>Because</span>
  <span m=''735350''>you''ve</span> <span m=''735480''>got the</span> <span m=''735560''>2</span>
  <span m=''735990''>axioms there,</span> <span m=''736340''>right?</span> <span m=''738430''>Now</span>
  <span m=''739830''>eventually,</span> <span m=''741170''>they</span> <span m=''741310''>discovered</span>
  <span m=''742630''>a</span> <span m=''742710''>proof</span> <span m=''743020''>like</span>
  <span m=''743190''>that,</span> <span m=''743480''>that</span> <span m=''743580''>it</span>
  <span m=''743650''>wasn''t</span> <span m=''744160''>rational.</span> <span m=''744740''>It</span>
  <span m=''744800''>was</span> <span m=''744930''>irrational.</span> </p><p><span
  m=''746380''>This</span> <span m=''746640''>caused</span> <span m=''746970''>quite</span>
  <span m=''747260''>a</span> <span m=''747320''>stir.</span> <span m=''748010''>First</span>
  <span m=''748420''>it</span> <span m=''748530''>meant</span> <span m=''748840''>that</span>
  <span m=''749000''>their</span> <span m=''749120''>axioms</span> <span m=''749740''>were</span>
  <span m=''749920''>inconsistent.</span> <span m=''751180''>Every</span> <span m=''751500''>theorem</span>
  <span m=''751820''>they</span> <span m=''751980''>proved</span> <span m=''752590''>was</span>
  <span m=''752780''>now</span> <span m=''752950''>suspect,</span> <span m=''754590''>once</span>
  <span m=''754750''>you</span> <span m=''754860''>have</span> <span m=''755060''>inconsistent</span>
  <span m=''755630''>axioms.</span> <span m=''756600''>Even</span> <span m=''756930''>worse,</span>
  <span m=''758160''>the</span> <span m=''758310''>devil</span> <span m=''759940''>is</span>
  <span m=''760340''>in</span> <span m=''760480''>their</span> <span m=''760610''>midst.</span>
  <span m=''761800''>Square</span> <span m=''762240''>root</span> <span m=''762410''>2</span>
  <span m=''762590''>is</span> <span m=''762740''>infinite</span> <span m=''763070''>is</span>
  <span m=''763220''>the</span> <span m=''763320''>bad</span> <span m=''763860''>god,</span>
  <span m=''764300''>and</span> <span m=''764600''>this</span> <span m=''764760''>is</span>
  <span m=''764860''>the</span> <span m=''764930''>most</span> <span m=''765150''>basic</span>
  <span m=''765980''>length</span> <span m=''766320''>they</span> <span m=''766440''>had,</span>
  <span m=''766820''>besides</span> <span m=''767090''>one.</span> <span m=''768690''>So</span>
  <span m=''768840''>that''s</span> <span m=''769000''>a</span> <span m=''769040''>very</span>
  <span m=''769260''>bad</span> <span m=''769560''>thing.</span> <span m=''770300''>Sort
  of</span> <span m=''770430''>like, you know,</span> <span m=''770640''>today</span>
  <span m=''771210''>we</span> <span m=''771300''>were</span> <span m=''771390''>to</span>
  <span m=''771440''>wake</span> <span m=''771690''>up</span> <span m=''771820''>and</span>
  <span m=''771910''>discover</span> <span m=''772350''>that</span> <span m=''773320''>there
  were</span> <span m=''773500''>only</span> <span m=''773940''>nine</span> <span
  m=''774310''>commandments,</span> <span m=''775450''>and</span> <span m=''775680''>the</span>
  <span m=''775790''>10th</span> <span m=''776240''>was</span> <span m=''776450''>planted</span>
  <span m=''776940''>there</span> <span m=''777090''>by</span> <span m=''777250''>the</span>
  <span m=''777370''>devil.</span> <span m=''777950''>And</span> <span m=''778080''>you''re</span>
  <span m=''778150''>not</span> <span m=''778330''>sure</span> <span m=''778520''>which</span>
  <span m=''778710''>one,</span> <span m=''778930''>maybe.</span> <span m=''779710''>That</span>
  <span m=''780190''>would</span> <span m=''780310''>be</span> <span m=''780610''>a</span>
  <span m=''780670''>big</span> <span m=''780970''>mess,</span> <span m=''781400''>sacrilege.</span>
  </p><p><span m=''783280''>Well,</span> <span m=''783460''>so</span> <span m=''783580''>what</span>
  <span m=''783770''>were</span> <span m=''783860''>they</span> <span m=''784010''>to</span>
  <span m=''784100''>do?</span> <span m=''784520''>This</span> <span m=''784710''>is</span>
  <span m=''784950''>a</span> <span m=''785060''>disaster</span> <span m=''785690''>of</span>
  <span m=''786530''>major</span> <span m=''786850''>proportions.</span> <span m=''787370''>So</span>
  <span m=''788060''>they</span> <span m=''788180''>covered</span> <span m=''788510''>it</span>
  <span m=''788620''>up,</span> <span m=''789670''>and</span> <span m=''789870''>they</span>
  <span m=''789940''>denied</span> <span m=''790300''>the</span> <span m=''790420''>result.</span>
  <span m=''791490''>So</span> <span m=''791910''>they</span> <span m=''792270''>didn''t</span>
  <span m=''792550''>want</span> <span m=''792680''>to</span> <span m=''792730''>publish</span>
  <span m=''793050''>that</span> <span m=''793230''>proof.</span> <span m=''793570''>So
  they</span> <span m=''793620''>kept</span> <span m=''793880''>on</span> <span m=''794010''>saying</span>
  <span m=''794340''>square</span> <span m=''794590''>root</span> <span m=''794750''>2</span>
  <span m=''794900''>was</span> <span m=''795050''>rational.</span> <span m=''796760''>But</span>
  <span m=''796910''>then,</span> <span m=''797530''>according</span> <span m=''797900''>to</span>
  <span m=''798010''>legend</span> <span m=''798410''>there</span> <span m=''798500''>was</span>
  <span m=''798620''>a</span> <span m=''798700''>Deep</span> <span m=''798960''>Throat.</span>
  <span m=''800130''>Somebody</span> <span m=''800760''>who</span> <span m=''800960''>let</span>
  <span m=''801130''>out</span> <span m=''801330''>the</span> <span m=''801420''>word</span>
  <span m=''802230''>and</span> <span m=''802410''>the</span> <span m=''802480''>proof</span>
  <span m=''802750''>the</span> <span m=''802860''>square</span> <span m=''803120''>root</span>
  <span m=''803270''>2</span> <span m=''803450''>is</span> <span m=''803550''>irrational,</span>
  <span m=''804060''>because</span> <span m=''804180''>that</span> <span m=''804320''>would</span>
  <span m=''804400''>be</span> <span m=''804500''>very</span> <span m=''804770''>destabilizing</span>
  <span m=''805630''>for</span> <span m=''805730''>the</span> <span m=''805850''>society,</span>
  <span m=''807450''>and</span> <span m=''807590''>so</span> <span m=''807690''>they</span>
  <span m=''807800''>killed</span> <span m=''808030''>them.</span> </p><p><span m=''809810''>This</span>
  <span m=''810000''>is</span> <span m=''810110''>the</span> <span m=''810220''>legend.</span>
  <span m=''811320''>Now,</span> <span m=''811400''>hard</span> <span m=''811600''>to</span>
  <span m=''811680''>imagine</span> <span m=''812030''>getting</span> <span m=''812200''>killed</span>
  <span m=''812500''>over</span> <span m=''812640''>the</span> <span m=''812770''>irrationality</span>
  <span m=''813430''>of</span> <span m=''813510''>2.</span> <span m=''815990''>All</span>
  <span m=''816130''>right,</span> <span m=''816280''>we''re</span> <span m=''816380''>going</span>
  <span m=''816460''>to</span> <span m=''816500''>do</span> <span m=''816600''>a</span>
  <span m=''816660''>lot</span> <span m=''816860''>more</span> <span m=''817130''>of</span>
  <span m=''817460''>these</span> <span m=''817670''>kind</span> <span m=''817840''>of</span>
  <span m=''817910''>proofs</span> <span m=''818260''>in</span> <span m=''818610''>homework</span>
  <span m=''819080''>and</span> <span m=''819430''>throughout</span> <span m=''819730''>the</span>
  <span m=''819830''>term.</span> <span m=''820800''>The</span> <span m=''820890''>next</span>
  <span m=''821200''>proof</span> <span m=''821330''>I</span> <span m=''821390''>want</span>
  <span m=''821580''>to</span> <span m=''821630''>show</span> <span m=''821900''>you</span>
  <span m=''822750''>is</span> <span m=''823760''>one</span> <span m=''823920''>of</span>
  <span m=''823970''>my</span> <span m=''824080''>favorite</span> <span m=''824470''>proof</span>
  <span m=''824680''>techniques.</span> <span m=''825410''>One of</span> <span m=''825540''>my</span>
  <span m=''825650''>favorite</span> <span m=''825960''>proofs.</span> <span m=''826950''>And</span>
  <span m=''827240''>that</span> <span m=''827430''>is</span> <span m=''827720''>a</span>
  <span m=''827880''>false</span> <span m=''828260''>proof.</span> <span m=''829420''>And</span>
  <span m=''829570''>we''re</span> <span m=''829650''>going</span> <span m=''829730''>to</span>
  <span m=''829970''>see</span> <span m=''830150''>a</span> <span m=''830200''>lot</span>
  <span m=''830390''>of</span> <span m=''830440''>these</span> <span m=''830640''>during</span>
  <span m=''830830''>the</span> <span m=''830920''>term,</span> <span m=''831190''>too.</span>
  <span m=''831370''>And if</span> <span m=''831510''>we</span> <span m=''831600''>could</span>
  <span m=''831700''>bring</span> <span m=''831880''>the</span> <span m=''831970''>screens</span>
  <span m=''832340''>down.</span> <span m=''834030''>Somebody</span> <span m=''834270''>back</span>
  <span m=''834520''>there</span> <span m=''834660''>to--</span> <span m=''835260''>yeah.</span>
  <span m=''835420''>Great.</span> <span m=''835730''>Bring</span> <span m=''835870''>the</span>
  <span m=''835940''>screens</span> <span m=''836280''>down,</span> <span m=''836530''>I''m</span>
  <span m=''836670''>going to--</span> <span m=''836930''>and</span> <span m=''837050''>then</span>
  <span m=''837180''>turn</span> <span m=''837370''>this</span> <span m=''837560''>on</span>
  <span m=''838250''>for</span> <span m=''838600''>me.</span> <span m=''838750''>So</span>
  <span m=''839510''>I''m</span> <span m=''839730''>going</span> <span m=''839840''>to</span>
  <span m=''839910''>prove</span> <span m=''840390''>to</span> <span m=''840490''>you</span>
  <span m=''841720''>that</span> <span m=''841920''>90</span> <span m=''842520''>is</span>
  <span m=''842680''>bigger</span> <span m=''843000''>than</span> <span m=''843170''>92.</span>
  <span m=''845370''>All right?</span> <span m=''845660''>And</span> <span m=''845780''>that</span>
  <span m=''846980''>hopefully,</span> <span m=''847230''>is</span> <span m=''847310''>not</span>
  <span m=''847530''>really</span> <span m=''847820''>true.</span> <span m=''849360''>But,</span>
  <span m=''849790''>you know,</span> <span m=''849860''>watch</span> <span m=''850100''>this</span>
  <span m=''850280''>proof</span> <span m=''851210''>and</span> <span m=''851360''>see</span>
  <span m=''851600''>if</span> <span m=''853280''>there''s</span> <span m=''853470''>any</span>
  <span m=''853640''>problems</span> <span m=''854100''>with</span> <span m=''854250''>it.</span>
  </p><p><span m=''857480''>All right,</span> <span m=''857720''>the</span> <span
  m=''857820''>proof,</span> <span m=''858240''>by</span> <span m=''858420''>PowerPoint.</span>
  <span m=''859110''>Right</span> <span m=''859300''>away</span> <span m=''859570''>you</span>
  <span m=''859670''>should</span> <span m=''859850''>be</span> <span m=''860030''>suspicious.</span>
  <span m=''863300''>I''m</span> <span m=''863460''>going</span> <span m=''863560''>to</span>
  <span m=''863620''>take</span> <span m=''863860''>two</span> <span m=''864030''>triangles</span>
  <span m=''864770''>with</span> <span m=''864920''>total</span> <span m=''865310''>area</span>
  <span m=''865660''>90</span> <span m=''867050''>and</span> <span m=''867400''>put</span>
  <span m=''867560''>them</span> <span m=''867670''>together,</span> <span m=''868220''>and</span>
  <span m=''868320''>then</span> <span m=''868330''>divide</span> <span m=''868660''>them</span>
  <span m=''868790''>up</span> <span m=''868920''>into</span> <span m=''869080''>four</span>
  <span m=''869390''>triangles</span> <span m=''870540''>with</span> <span m=''870810''>area</span>
  <span m=''871190''>greater</span> <span m=''871720''>than</span> <span m=''871890''>92.</span>
  <span m=''874110''>And</span> <span m=''874390''>by</span> <span m=''874550''>the</span>
  <span m=''874660''>conservation</span> <span m=''875410''>of</span> <span m=''875490''>area</span>
  <span m=''875880''>axiom,</span> <span m=''876820''>which</span> <span m=''877020''>you</span>
  <span m=''877120''>want</span> <span m=''877310''>to</span> <span m=''877350''>be</span>
  <span m=''878050''>maybe</span> <span m=''878280''>thinking</span> <span m=''878570''>about,</span>
  <span m=''879230''>this</span> <span m=''879430''>will</span> <span m=''879550''>imply</span>
  <span m=''879910''>an</span> <span m=''880020''>area</span> <span m=''880310''>of</span>
  <span m=''880410''>90</span> <span m=''880830''>is</span> <span m=''880960''>larger</span>
  <span m=''881440''>than</span> <span m=''881540''>an</span> <span m=''881650''>area</span>
  <span m=''881900''>of</span> <span m=''881960''>92.</span> <span m=''883110''>And</span>
  <span m=''883240''>therefore</span> <span m=''883590''>that</span> <span m=''883770''>90</span>
  <span m=''884150''>is</span> <span m=''884300''>bigger</span> <span m=''884540''>than</span>
  <span m=''884700''>92.</span> </p><p><span m=''887460''>All</span> <span m=''887580''>right,</span>
  <span m=''887840''>those</span> <span m=''888130''>are</span> <span m=''888180''>my</span>
  <span m=''888340''>triangles.</span> <span m=''888900''>They</span> <span m=''889040''>are</span>
  <span m=''889240''>right</span> <span m=''889660''>triangles,</span> <span m=''890620''>9</span>
  <span m=''890880''>by</span> <span m=''891070''>10.</span> <span m=''893150''>If</span>
  <span m=''893310''>I</span> <span m=''893400''>put</span> <span m=''893610''>them</span>
  <span m=''893720''>together,</span> <span m=''894860''>I</span> <span m=''894970''>get</span>
  <span m=''895130''>a</span> <span m=''895200''>9</span> <span m=''895540''>by</span>
  <span m=''895830''>10</span> <span m=''896180''>rectangle.</span> <span m=''898510''>Of
  course</span> <span m=''898750''>it</span> <span m=''898820''>has</span> <span m=''899030''>area</span>
  <span m=''899300''>90,</span> <span m=''899710''>9</span> <span m=''900120''>times</span>
  <span m=''900380''>10.</span> <span m=''903140''>Now</span> <span m=''903340''>I''m</span>
  <span m=''903470''>going</span> <span m=''903580''>to</span> <span m=''903650''>slide</span>
  <span m=''904520''>these</span> <span m=''904730''>triangles</span> <span m=''906370''>across</span>
  <span m=''906950''>their</span> <span m=''908870''>diagonal</span> <span m=''910170''>so</span>
  <span m=''910440''>that</span> <span m=''910610''>I</span> <span m=''910730''>get,</span>
  <span m=''911150''>instead</span> <span m=''911450''>of</span> <span m=''911500''>having</span>
  <span m=''911790''>10</span> <span m=''912060''>on</span> <span m=''912140''>the</span>
  <span m=''912230''>side,</span> <span m=''912620''>I''m</span> <span m=''912690''>going</span>
  <span m=''912780''>to</span> <span m=''912830''>slide</span> <span m=''913210''>it</span>
  <span m=''913310''>so</span> <span m=''913400''>I</span> <span m=''913460''>get</span>
  <span m=''913610''>a</span> <span m=''913720''>2</span> <span m=''913940''>and</span>
  <span m=''914010''>an 8.</span> <span m=''915030''>OK</span> <span m=''915900''>I</span>
  <span m=''916030''>had</span> <span m=''916190''>10</span> <span m=''916380''>there
  before,</span> <span m=''916770''>now</span> <span m=''916970''>it''s</span> <span
  m=''917100''>2</span> <span m=''917270''>and</span> <span m=''917360''>8.</span>
  <span m=''917910''>And</span> <span m=''918130''>then</span> <span m=''918320''>you</span>
  <span m=''918420''>see</span> <span m=''918580''>I''ve</span> <span m=''918680''>got</span>
  <span m=''918820''>this--</span> <span m=''918990''>I''m</span> <span m=''919060''>going</span>
  <span m=''919220''>to</span> <span m=''919340''>cut</span> <span m=''919610''>off</span>
  <span m=''919850''>along</span> <span m=''920110''>the</span> <span m=''920170''>dotted</span>
  <span m=''920490''>line,</span> <span m=''920940''>and</span> <span m=''921260''>as</span>
  <span m=''921440''>you</span> <span m=''921560''>can</span> <span m=''921710''>see</span>
  <span m=''921940''>that</span> <span m=''922170''>dotted</span> <span m=''922460''>line,</span>
  <span m=''923220''>yeah but</span> <span m=''923490''>won''t</span> <span m=''923620''>compute
  it</span> <span m=''923940''>exactly,</span> <span m=''924380''>but</span> <span
  m=''924480''>it''s</span> <span m=''924560''>a</span> <span m=''924610''>little</span>
  <span m=''924880''>bit</span> <span m=''925030''>bigger</span> <span m=''925340''>than</span>
  <span m=''925520''>2.</span> <span m=''926425''>All right?</span> <span m=''926870''>It''s</span>
  <span m=''927080''>a</span> <span m=''927120''>little</span> <span m=''927330''>bit</span>
  <span m=''927460''>longer</span> <span m=''927810''>than</span> <span m=''927970''>that</span>
  <span m=''928250''>2</span> <span m=''928490''>there,</span> <span m=''928670''>you
  could</span> <span m=''928920''>see</span> <span m=''929150''>that.</span> <span
  m=''931090''>All</span> <span m=''931220''>right,</span> <span m=''931510''>so I''ll
  call it</span> <span m=''932040''>2</span> <span m=''932180''>plus,</span> <span
  m=''932530''>bigger</span> <span m=''932710''>than</span> <span m=''932850''>2.</span>
  </p><p><span m=''933390''>Now</span> <span m=''933560''>I</span> <span m=''933660''>slice</span>
  <span m=''934230''>off</span> <span m=''934430''>along</span> <span m=''934690''>the</span>
  <span m=''934780''>dotted</span> <span m=''935100''>line,</span> <span m=''936970''>and</span>
  <span m=''937130''>now</span> <span m=''937310''>I''m</span> <span m=''937440''>going</span>
  <span m=''937540''>to</span> <span m=''937610''>put</span> <span m=''937980''>those</span>
  <span m=''938890''>two</span> <span m=''939110''>triangles</span> <span m=''939580''>together,</span>
  <span m=''940040''>and</span> <span m=''940120''>I</span> <span m=''940190''>create</span>
  <span m=''940440''>a</span> <span m=''940500''>rectangle.</span> <span m=''942560''>Two</span>
  <span m=''942770''>by</span> <span m=''942930''>two--</span> <span m=''943300''>little</span>
  <span m=''943450''>more</span> <span m=''943600''>than</span> <span m=''943740''>two.</span>
  <span m=''945010''>Now</span> <span m=''945140''>the</span> <span m=''945320''>area</span>
  <span m=''945580''>of</span> <span m=''945630''>the</span> <span m=''945710''>little</span>
  <span m=''945940''>rectangle is</span> <span m=''946560''>bigger</span> <span m=''946820''>than</span>
  <span m=''946970''>4,</span> <span m=''947420''>cause</span> <span m=''947550''>I</span>
  <span m=''947600''>got</span> <span m=''947870''>2</span> <span m=''948120''>times</span>
  <span m=''948400''>something</span> <span m=''948630''>bigger</span> <span m=''948810''>than</span>
  <span m=''948960''>2,</span> <span m=''949850''>and</span> <span m=''950160''>you</span>
  <span m=''950250''>can</span> <span m=''950380''>see</span> <span m=''950650''>here</span>
  <span m=''950980''>I</span> <span m=''951090''>have</span> <span m=''951570''>the</span>
  <span m=''951690''>8</span> <span m=''951860''>left</span> <span m=''952090''>over,</span>
  <span m=''952740''>and</span> <span m=''952920''>I</span> <span m=''952940''>have</span>
  <span m=''953060''>9</span> <span m=''953570''>plus</span> <span m=''953910''>2</span>
  <span m=''954050''>plus,</span> <span m=''954480''>means</span> <span m=''954740''>it''s</span>
  <span m=''955390''>a</span> <span m=''955460''>little</span> <span m=''955670''>bit</span>
  <span m=''955820''>bigger</span> <span m=''956020''>than</span> <span m=''956140''>11</span>
  <span m=''956500''>by</span> <span m=''956680''>8.</span> <span m=''958120''>I</span>
  <span m=''958220''>got</span> <span m=''958400''>area</span> <span m=''958770''>bigger</span>
  <span m=''959250''>than</span> <span m=''959400''>88,</span> <span m=''960550''>add</span>
  <span m=''960730''>them</span> <span m=''960870''>up,</span> <span m=''962110''>get</span>
  <span m=''962300''>area</span> <span m=''963030''>bigger</span> <span m=''963250''>than</span>
  <span m=''963410''>92.</span> <span m=''964820''>So</span> <span m=''964950''>I</span>
  <span m=''965020''>started</span> <span m=''965340''>with</span> <span m=''965460''>90</span>
  <span m=''966280''>and</span> <span m=''966390''>I</span> <span m=''966450''>created</span>
  <span m=''966840''>more</span> <span m=''967090''>than</span> <span m=''967240''>92.</span>
  </p><p><span m=''970220''>All right,</span> <span m=''970410''>what''s</span> <span
  m=''971150''>the</span> <span m=''971250''>problem</span> <span m=''971850''>here?</span>
  <span m=''973860''>This</span> <span m=''974050''>would</span> <span m=''974110''>be</span>
  <span m=''974180''>good</span> <span m=''974350''>if</span> <span m=''974460''>I</span>
  <span m=''974520''>could</span> <span m=''974700''>do</span> <span m=''974890''>it.
  I''d</span> <span m=''974990''>get</span> <span m=''975210''>some</span> <span m=''975470''>gold,</span>
  <span m=''975920''>you know,</span> <span m=''976320''>bars</span> <span m=''976630''>of</span>
  <span m=''976740''>gold</span> <span m=''977140''>and</span> <span m=''977900''>cut</span>
  <span m=''978100''>them</span> <span m=''978240''>up,</span> <span m=''978520''>and</span>
  <span m=''978780''>do</span> <span m=''978880''>the</span> <span m=''979010''>game,</span>
  <span m=''979360''>and</span> <span m=''979480''>I</span> <span m=''979550''>make</span>
  <span m=''979930''>more</span> <span m=''980140''>gold.</span> <span m=''980540''>That</span>
  <span m=''980700''>would</span> <span m=''980840''>be</span> <span m=''981610''>pretty</span>
  <span m=''981850''>good</span> <span m=''982300''>if</span> <span m=''982540''>I</span>
  <span m=''982610''>could</span> <span m=''982770''>do</span> <span m=''982920''>that.</span>
  <span m=''985340''>Because</span> <span m=''985510''>of</span> <span m=''985590''>the</span>
  <span m=''985670''>conservation</span> <span m=''986390''>of</span> <span m=''986470''>area</span>
  <span m=''986740''>axiom?</span> <span m=''988300''>Did</span> <span m=''988460''>I</span>
  <span m=''988590''>assume</span> <span m=''989160''>something</span> <span m=''989500''>there</span>
  <span m=''989650''>that</span> <span m=''989750''>was</span> <span m=''989860''>too</span>
  <span m=''990000''>powerful</span> <span m=''990570''>that if I</span> <span m=''991290''>manipulate</span>
  <span m=''992300''>the</span> <span m=''992500''>area</span> <span m=''992710''>of</span>
  <span m=''992770''>rectangles</span> <span m=''993320''>like</span> <span m=''993530''>this,</span>
  <span m=''994490''>that the</span> <span m=''994540''>area</span> <span m=''994770''>needs</span>
  <span m=''995000''>to</span> <span m=''995090''>be</span> <span m=''995350''>the</span>
  <span m=''995460''>same?</span> <span m=''999050''>Yeah?</span> <span m=''1001630''>My</span>
  <span m=''1001790''>bigger</span> <span m=''1002270''>ones</span> <span m=''1002740''>aren''t</span>
  <span m=''1003120''>closed.</span> <span m=''1004170''>Well,</span> <span m=''1005630''>let''s</span>
  <span m=''1005930''>see,</span> <span m=''1006120''>I</span> <span m=''1006170''>don''t</span>
  <span m=''1006270''>know.</span> <span m=''1006320''>Let''s</span> <span m=''1006500''>go</span>
  <span m=''1006590''>back</span> <span m=''1006800''>and</span> <span m=''1006910''>see</span>
  <span m=''1007040''>I</span> <span m=''1007140''>made</span> <span m=''1007360''>those</span>
  <span m=''1007550''>bigger</span> <span m=''1007800''>ones.</span> <span m=''1010230''>All</span>
  <span m=''1010320''>right,</span> <span m=''1010490''>I</span> <span m=''1010540''>got</span>
  <span m=''1010700''>my</span> <span m=''1010800''>triangles,</span> <span m=''1011570''>right?</span>
  <span m=''1012700''>I''m</span> <span m=''1012840''>just</span> <span m=''1013060''>chopping</span>
  <span m=''1013420''>along</span> <span m=''1013660''>the</span> <span m=''1013750''>line</span>
  <span m=''1014160''>there,</span> <span m=''1014450''>and</span> <span m=''1014510''>I</span>
  <span m=''1014560''>got</span> <span m=''1015030''>2</span> <span m=''1015220''>plus</span>
  <span m=''1015510''>and</span> <span m=''1015800''>9.</span> <span m=''1019210''>Those</span>
  <span m=''1019430''>are</span> <span m=''1019510''>rectangles.</span> <span m=''1021471''>They</span>
  <span m=''1021860''>look</span> <span m=''1022070''>like</span> <span m=''1022230''>rectangles.</span>
  <span m=''1025670''>Yeah.</span> </p><p><span m=''1026541''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''1029319''>PROFESSOR: Well</span> <span m=''1029579''>it looks</span>
  <span m=''1029819''>bigger</span> <span m=''1030050''>than</span> <span m=''1030220''>2,</span>
  <span m=''1031930''>doesn''t</span> <span m=''1032375''>it?</span> <span m=''1035050''>Yeah,</span>
  <span m=''1035420''>2</span> <span m=''1035609''>pluses.</span> <span m=''1036670''>Well</span>
  <span m=''1037079''>bigger</span> <span m=''1037380''>than</span> <span m=''1037520''>2</span>
  <span m=''1037690''>is</span> <span m=''1037790''>bigger</span> <span m=''1037950''>than</span>
  <span m=''1038079''>2,</span> <span m=''1038260''>but,</span> <span m=''1038880''>yeah,</span>
  <span m=''1039099''>maybe</span> <span m=''1039430''>that</span> <span m=''1039470''>should</span>
  <span m=''1039650''>have</span> <span m=''1039740''>been</span> <span m=''1039880''>a</span>
  <span m=''1039970''>2</span> <span m=''1040140''>minus.</span> <span m=''1041329''>Would</span>
  <span m=''1041460''>that</span> <span m=''1041630''>change</span> <span m=''1041890''>anything?</span>
  <span m=''1044190''>Yeah,</span> <span m=''1044619''>if</span> <span m=''1044750''>that</span>
  <span m=''1044900''>had been</span> <span m=''1044960''>a 2</span> <span m=''1045390''>minus,</span>
  <span m=''1047030''>then</span> <span m=''1047200''>we''d</span> <span m=''1047319''>have</span>
  <span m=''1048260''>area</span> <span m=''1049810''>less</span> <span m=''1050060''>than</span>
  <span m=''1050190''>4,</span> <span m=''1050990''>area</span> <span m=''1051300''>less</span>
  <span m=''1051570''>than</span> <span m=''1051670''>88,</span> <span m=''1052170''>and</span>
  <span m=''1052250''>then</span> <span m=''1052500''>90</span> <span m=''1052860''>would</span>
  <span m=''1053010''>be</span> <span m=''1053230''>less</span> <span m=''1053480''>than</span>
  <span m=''1053590''>92.</span> <span m=''1054420''>That</span> <span m=''1054580''>would</span>
  <span m=''1054670''>be</span> <span m=''1054790''>OK.</span> <span m=''1055780''>But</span>
  <span m=''1055960''>it</span> <span m=''1056030''>sure</span> <span m=''1056350''>as
  heck</span> <span m=''1056690''>looks</span> <span m=''1057040''>bigger</span> <span
  m=''1057320''>than--</span> <span m=''1058330''>the</span> <span m=''1058450''>2</span>
  <span m=''1058620''>plus</span> <span m=''1058930''>looks</span> <span m=''1059120''>bigger</span>
  <span m=''1059290''>than</span> <span m=''1059370''>the</span> <span m=''1059480''>2</span>
  <span m=''1059690''>doesn''t</span> <span m=''1059920''>it?</span> <span m=''1060090''>I</span>
  <span m=''1060150''>don''t</span> <span m=''1060250''>know, do</span> <span m=''1060380''>they</span>
  <span m=''1060540''>got</span> <span m=''1060880''>distortion</span> <span m=''1061370''>out</span>
  <span m=''1061490''>there?</span> <span m=''1063240''>I</span> <span m=''1063360''>guarantee</span>
  <span m=''1063880''>you,</span> <span m=''1063980''>if</span> <span m=''1064100''>I</span>
  <span m=''1064180''>measured</span> <span m=''1064600''>on</span> <span m=''1064690''>my</span>
  <span m=''1064820''>screen,</span> <span m=''1065590''>that</span> <span m=''1065800''>2</span>
  <span m=''1065930''>plus</span> <span m=''1066240''>is</span> <span m=''1066360''>bigger</span>
  <span m=''1066560''>than</span> <span m=''1066880''>the</span> <span m=''1066970''>length</span>
  <span m=''1067190''>of</span> <span m=''1067250''>the</span> <span m=''1067340''>tube.</span>
  <span m=''1068890''>I</span> <span m=''1069010''>guarantee</span> <span m=''1069440''>you.</span>
  <span m=''1069530''>We can</span> <span m=''1070280''>to</span> <span m=''1070360''>take</span>
  <span m=''1070520''>a</span> <span m=''1070940''>ruler</span> <span m=''1071750''>on</span>
  <span m=''1072000''>my</span> <span m=''1072150''>screen,</span> <span m=''1072930''>and</span>
  <span m=''1073140''>the</span> <span m=''1073230''>2</span> <span m=''1073390''>plus</span>
  <span m=''1073710''>will</span> <span m=''1073800''>be</span> <span m=''1073910''>longer</span>
  <span m=''1074290''>on</span> <span m=''1074400''>the</span> <span m=''1074550''>ruler</span>
  <span m=''1074790''>than</span> <span m=''1074910''>the</span> <span m=''1075010''>2.</span>
  <span m=''1076510''>That</span> <span m=''1076710''>I</span> <span m=''1076760''>guarantee</span>
  <span m=''1077230''>you,</span> <span m=''1077380''>but</span> <span m=''1077530''>you''re</span>
  <span m=''1077720''>on</span> <span m=''1077970''>the</span> <span m=''1078060''>right</span>
  <span m=''1078260''>track.</span> <span m=''1081090''>Yeah</span> </p><p><span m=''1084700''>Good,</span>
  <span m=''1086220''>all right,</span> <span m=''1086850''>now</span> <span m=''1087010''>how</span>
  <span m=''1087200''>did</span> <span m=''1087350''>you--</span> <span m=''1088200''>but</span>
  <span m=''1088660''>it is</span> <span m=''1088810''>true,</span> <span m=''1089200''>if
  I</span> <span m=''1089290''>measured</span> <span m=''1089730''>on</span> <span
  m=''1089830''>my</span> <span m=''1089970''>screen,</span> <span m=''1090310''>it''s</span>
  <span m=''1090440''>bigger.</span> <span m=''1091100''>Yeah.</span> </p><p><span
  m=''1094500''>AUDIENCE: Are the</span> <span m=''1094650''>triangles,</span> <span
  m=''1094870''>like,</span> <span m=''1095130''>drawn to</span> <span m=''1095550''>scale?</span>
  <span m=''1095970''>It''s like,</span> <span m=''1096390''>on the</span> <span m=''1096810''>SAT</span>
  <span m=''1097233''>they always</span> <span m=''1097656''>say,</span> <span m=''1098079''>not
  to scale,</span> <span m=''1098502''>right?</span> </p><p><span m=''1099350''>PROFESSOR:
  Yeah.</span> <span m=''1100720''>Yeah,</span> <span m=''1100910''>they''re</span>
  <span m=''1101040''>not</span> <span m=''1101240''>drawn</span> <span m=''1101510''>to</span>
  <span m=''1101590''>scale.</span> <span m=''1102780''>In</span> <span m=''1102800''>fact,</span>
  <span m=''1103220''>if</span> <span m=''1103320''>I</span> <span m=''1103420''>go</span>
  <span m=''1103450''>back</span> <span m=''1103670''>to</span> <span m=''1103760''>the</span>
  <span m=''1103830''>beginning,</span> <span m=''1107200''>it</span> <span m=''1107360''>says</span>
  <span m=''1107590''>9</span> <span m=''1107880''>by</span> <span m=''1108030''>10.</span>
  <span m=''1109850''>But</span> <span m=''1109990''>in</span> <span m=''1110070''>fact,</span>
  <span m=''1110460''>if</span> <span m=''1110550''>I</span> <span m=''1110640''>measure</span>
  <span m=''1110930''>the</span> <span m=''1111020''>nine,</span> <span m=''1111350''>it''s</span>
  <span m=''1111510''>bigger</span> <span m=''1111740''>than</span> <span m=''1111880''>the</span>
  <span m=''1111990''>10.</span> <span m=''1114080''>All</span> <span m=''1114180''>right?</span>
  <span m=''1115690''>So</span> <span m=''1116990''>this</span> <span m=''1117230''>is</span>
  <span m=''1117370''>one</span> <span m=''1117680''>of</span> <span m=''1117740''>the</span>
  <span m=''1117810''>big</span> <span m=''1118410''>problems</span> <span m=''1118990''>of</span>
  <span m=''1119290''>proofs</span> <span m=''1119580''>by</span> <span m=''1119710''>picture.</span>
  <span m=''1121040''>Because</span> <span m=''1121230''>look</span> <span m=''1121510''>at</span>
  <span m=''1121600''>it,</span> <span m=''1121870''>you''re</span> <span m=''1122010''>not</span>
  <span m=''1122040''>thinking</span> <span m=''1122370''>which</span> <span m=''1122580''>is</span>
  <span m=''1122690''>bigger,</span> <span m=''1122960''>9</span> <span m=''1123200''>or</span>
  <span m=''1123280''>10</span> <span m=''1123500''>up</span> <span m=''1123590''>there?</span>
  <span m=''1124030''>10''s</span> <span m=''1124310''>bigger</span> <span m=''1124670''>even</span>
  <span m=''1124850''>though</span> <span m=''1124960''>it''s</span> <span m=''1125300''>not,
  it''s</span> <span m=''1125640''>shorter.</span> <span m=''1126670''>But</span>
  <span m=''1126810''>when</span> <span m=''1126880''>you</span> <span m=''1127150''>get</span>
  <span m=''1127350''>down into</span> <span m=''1127480''>the proof,</span> <span
  m=''1127740''>well,</span> <span m=''1128000''>clearly</span> <span m=''1128430''>the</span>
  <span m=''1128530''>2</span> <span m=''1128710''>plus</span> <span m=''1129110''>was</span>
  <span m=''1129270''>bigger</span> <span m=''1129460''>than</span> <span m=''1129580''>the</span>
  <span m=''1129680''>2,</span> <span m=''1129860''>because</span> <span m=''1130040''>it</span>
  <span m=''1130140''>looks</span> <span m=''1130350''>that</span> <span m=''1130510''>way.</span>
  <span m=''1130640''>It</span> <span m=''1130730''>is,</span> <span m=''1131020''>on</span>
  <span m=''1131170''>the</span> <span m=''1131250''>paper.</span> <span m=''1132620''>All</span>
  <span m=''1132740''>right?</span> <span m=''1132980''>In</span> <span m=''1133080''>fact</span>
  <span m=''1133420''>if you</span> <span m=''1133530''>go on a</span> <span m=''1133660''>computer,</span>
  <span m=''1134060''>you''re</span> <span m=''1134160''>probably</span> <span m=''1134290''>right,</span>
  <span m=''1134470''>it''s</span> <span m=''1134570''>1.8,</span> <span m=''1135230''>not</span>
  <span m=''1136000''>2</span> <span m=''1136170''>plus.</span> </p><p><span m=''1137410''>But</span>
  <span m=''1137520''>that''s</span> <span m=''1137730''>how</span> <span m=''1137850''>the</span>
  <span m=''1138000''>error</span> <span m=''1138315''>crept in</span> <span m=''1138630''>and</span>
  <span m=''1138810''>how it</span> <span m=''1139060''>was</span> <span m=''1139230''>drawn,</span>
  <span m=''1140940''>and</span> <span m=''1141080''>then</span> <span m=''1141180''>you''re</span>
  <span m=''1141300''>going</span> <span m=''1141530''>along</span> <span m=''1141750''>with</span>
  <span m=''1141880''>a</span> <span m=''1141920''>proof,</span> <span m=''1142800''>and</span>
  <span m=''1142930''>everything</span> <span m=''1143250''>else</span> <span m=''1143450''>is</span>
  <span m=''1143550''>just</span> <span m=''1143800''>fine.</span> <span m=''1144040''>So</span>
  <span m=''1144160''>the</span> <span m=''1144500''>mistake</span> <span m=''1145040''>is</span>
  <span m=''1145160''>right</span> <span m=''1145430''>up</span> <span m=''1145550''>front.</span>
  <span m=''1145840''>I</span> <span m=''1145880''>drew</span> <span m=''1146130''>it</span>
  <span m=''1146210''>wrong.</span> <span m=''1147680''>OK.</span> <span m=''1149320''>And</span>
  <span m=''1149470''>this</span> <span m=''1149670''>happens,</span> <span m=''1150080''>you''re</span>
  <span m=''1150210''>doing</span> <span m=''1150440''>graphs--</span> <span m=''1150960''>we''ll</span>
  <span m=''1151140''>talk about</span> <span m=''1151190''>graphs</span> <span m=''1151480''>here
  in</span> <span m=''1151620''>a</span> <span m=''1151650''>couple</span> <span m=''1151870''>weeks--</span>
  <span m=''1152170''>over</span> <span m=''1152480''>and</span> <span m=''1152540''>over</span>
  <span m=''1152860''>again,</span> <span m=''1153520''>people</span> <span m=''1153810''>do</span>
  <span m=''1153970''>this.</span> <span m=''1154640''>They</span> <span m=''1154780''>draw</span>
  <span m=''1154990''>it,</span> <span m=''1155090''>it looks</span> <span m=''1155350''>like</span>
  <span m=''1155520''>this,</span> <span m=''1155820''>you</span> <span m=''1155970''>accept</span>
  <span m=''1156340''>that</span> <span m=''1156560''>and</span> <span m=''1156650''>then</span>
  <span m=''1156770''>you''re</span> <span m=''1156860''>dead.</span> <span m=''1157620''>Everything</span>
  <span m=''1157950''>else,</span> <span m=''1158900''>there''s</span> <span m=''1158970''>no</span>
  <span m=''1159280''>hope.</span> <span m=''1160190''>Everybody</span> <span m=''1160750''>clear</span>
  <span m=''1161020''>what</span> <span m=''1161170''>went</span> <span m=''1161290''>wrong</span>
  <span m=''1161550''>in</span> <span m=''1161620''>this</span> <span m=''1161760''>picture?</span>
  <span m=''1163080''>How</span> <span m=''1163280''>we</span> <span m=''1163350''>got</span>
  <span m=''1163840''>off</span> <span m=''1163980''>track?</span> <span m=''1165630''>This</span>
  <span m=''1165925''>is</span> <span m=''1166220''>sort</span> <span m=''1166340''>of</span>
  <span m=''1166410''>a</span> <span m=''1166440''>nasty</span> <span m=''1166750''>one.</span>
  </p><p><span m=''1169280''>OK.</span> <span m=''1172120''>Now</span> <span m=''1173190''>one</span>
  <span m=''1173440''>of</span> <span m=''1173490''>the</span> <span m=''1173570''>nice</span>
  <span m=''1173850''>things</span> <span m=''1174110''>about</span> <span m=''1174360''>proofs</span>
  <span m=''1174840''>is</span> <span m=''1174980''>that</span> <span m=''1175060''>when</span>
  <span m=''1175180''>there</span> <span m=''1175360''>is</span> <span m=''1175510''>a</span>
  <span m=''1175560''>bug,</span> <span m=''1175880''>if</span> <span m=''1175960''>you</span>
  <span m=''1176080''>really</span> <span m=''1176360''>write</span> <span m=''1176610''>it</span>
  <span m=''1176710''>out</span> <span m=''1176880''>step</span> <span m=''1177100''>by</span>
  <span m=''1177230''>step,</span> <span m=''1178160''>and</span> <span m=''1178320''>there''s</span>
  <span m=''1178450''>a</span> <span m=''1178510''>bug,</span> <span m=''1178775''>you
  can</span> <span m=''1179040''>go</span> <span m=''1179140''>back</span> <span m=''1179340''>and</span>
  <span m=''1179470''>find</span> <span m=''1179780''>it.</span> <span m=''1180620''>And</span>
  <span m=''1180820''>so</span> <span m=''1180960''>this,</span> <span m=''1181370''>I</span>
  <span m=''1181420''>didn''t</span> <span m=''1181670''>sort</span> <span m=''1181860''>of</span>
  <span m=''1181980''>really</span> <span m=''1182240''>write</span> <span m=''1182470''>it</span>
  <span m=''1182560''>out</span> <span m=''1182740''>very</span> <span m=''1182900''>well</span>
  <span m=''1183110''>step</span> <span m=''1183330''>by</span> <span m=''1183450''>step,</span>
  <span m=''1183770''>and it</span> <span m=''1183930''>was</span> <span m=''1184480''>harder</span>
  <span m=''1185410''>to</span> <span m=''1185480''>find.</span> <span m=''1186740''>Now,</span>
  <span m=''1187680''>all</span> <span m=''1187770''>right,</span> <span m=''1187960''>so</span>
  <span m=''1188040''>we</span> <span m=''1188130''>can</span> <span m=''1188230''>pull</span>
  <span m=''1188390''>the</span> <span m=''1188480''>screens</span> <span m=''1188830''>up.</span>
  <span m=''1192543''>Thanks.</span> <span m=''1194460''>OK,</span> <span m=''1194820''>so</span>
  <span m=''1196170''>for</span> <span m=''1196290''>the</span> <span m=''1196380''>rest</span>
  <span m=''1196610''>of</span> <span m=''1196690''>today</span> <span m=''1197200''>and</span>
  <span m=''1197340''>the</span> <span m=''1197430''>rest</span> <span m=''1197660''>of</span>
  <span m=''1197710''>this</span> <span m=''1197880''>week,</span> <span m=''1198400''>we''re</span>
  <span m=''1198540''>going</span> <span m=''1198630''>to</span> <span m=''1198690''>talk</span>
  <span m=''1198950''>about</span> <span m=''1199180''>a</span> <span m=''1199220''>different</span>
  <span m=''1199510''>kind</span> <span m=''1199670''>of</span> <span m=''1199740''>proof</span>
  <span m=''1200040''>technique,</span> <span m=''1200930''>which</span> <span m=''1201240''>is</span>
  <span m=''1201570''>induction.</span> <span m=''1203600''>Now,</span> <span m=''1203950''>induction</span>
  <span m=''1204470''>is</span> <span m=''1204570''>by</span> <span m=''1204710''>far</span>
  <span m=''1205230''>the</span> <span m=''1205330''>most</span> <span m=''1205600''>powerful</span>
  <span m=''1206550''>and</span> <span m=''1206670''>commonly</span> <span m=''1207190''>used</span>
  <span m=''1207510''>proof</span> <span m=''1207720''>technique</span> <span m=''1208790''>in</span>
  <span m=''1208900''>computer</span> <span m=''1209260''>science.</span> <span m=''1210350''>If</span>
  <span m=''1210510''>there''s</span> <span m=''1210710''>one</span> <span m=''1211000''>thing</span>
  <span m=''1211220''>you</span> <span m=''1211410''>should</span> <span m=''1211620''>know</span>
  <span m=''1211880''>by</span> <span m=''1211990''>the</span> <span m=''1212110''>time</span>
  <span m=''1212430''>you''re</span> <span m=''1212550''>done</span> <span m=''1212800''>with</span>
  <span m=''1212910''>this</span> <span m=''1213090''>class,</span> <span m=''1214640''>it''s</span>
  <span m=''1214820''>how</span> <span m=''1215040''>to</span> <span m=''1215130''>do</span>
  <span m=''1215250''>a</span> <span m=''1215330''>proof</span> <span m=''1215560''>by</span>
  <span m=''1215740''>induction.</span> <span m=''1216950''>In fact,</span> <span
  m=''1217140''>if</span> <span m=''1217200''>there''s</span> <span m=''1217340''>one</span>
  <span m=''1217530''>thing</span> <span m=''1217660''>you</span> <span m=''1217790''>will</span>
  <span m=''1218080''>know</span> <span m=''1218700''>by the</span> <span m=''1218880''>time
  we''re</span> <span m=''1219270''>done with</span> <span m=''1219410''>this</span>
  <span m=''1219600''>class,</span> <span m=''1220280''>is</span> <span m=''1220420''>how</span>
  <span m=''1220550''>to</span> <span m=''1220640''>do</span> <span m=''1220760''>a</span>
  <span m=''1220840''>proof</span> <span m=''1221080''>by</span> <span m=''1221250''>induction.</span>
  </p><p><span m=''1222020''>And</span> <span m=''1222160''>in</span> <span m=''1222230''>some</span>
  <span m=''1222500''>sense, when</span> <span m=''1222840''>we</span> <span m=''1223110''>get</span>
  <span m=''1223290''>to</span> <span m=''1223370''>grading</span> <span m=''1223750''>the</span>
  <span m=''1223830''>final,</span> <span m=''1225010''>how</span> <span m=''1225240''>we</span>
  <span m=''1225390''>measure</span> <span m=''1225760''>ourselves</span> <span m=''1226070''>as</span>
  <span m=''1226380''>instructors,</span> <span m=''1227020''>the</span> <span m=''1227100''>first</span>
  <span m=''1227510''>test</span> <span m=''1227900''>is,</span> <span m=''1228830''>can</span>
  <span m=''1229160''>you</span> <span m=''1229260''>do</span> <span m=''1229380''>the</span>
  <span m=''1229520''>proof</span> <span m=''1229770''>by</span> <span m=''1229930''>induction</span>
  <span m=''1230320''>question,</span> <span m=''1230900''>and</span> <span m=''1231080''>do</span>
  <span m=''1231200''>a</span> <span m=''1231270''>good</span> <span m=''1231450''>proof</span>
  <span m=''1231710''>there?</span> <span m=''1232250''>You</span> <span m=''1232410''>will</span>
  <span m=''1232550''>see</span> <span m=''1232780''>it</span> <span m=''1232860''>on</span>
  <span m=''1233780''>the</span> <span m=''1233870''>midterm</span> <span m=''1234450''>and</span>
  <span m=''1234640''>the</span> <span m=''1234720''>final,</span> <span m=''1235090''>probably</span>
  <span m=''1235480''>in</span> <span m=''1235570''>multiple</span> <span m=''1236000''>instances.</span>
  <span m=''1238410''>Now</span> <span m=''1238930''>just</span> <span m=''1239180''>to</span>
  <span m=''1239240''>make</span> <span m=''1239390''>sure</span> <span m=''1239560''>you</span>
  <span m=''1239660''>become</span> <span m=''1240010''>intimately</span> <span m=''1240540''>familiar</span>
  <span m=''1240960''>with</span> <span m=''1241110''>induction,</span> <span m=''1242350''>we''re</span>
  <span m=''1242570''>going</span> <span m=''1242700''>to</span> <span m=''1242820''>do</span>
  <span m=''1243490''>over</span> <span m=''1243730''>a</span> <span m=''1243780''>dozen</span>
  <span m=''1244140''>proofs</span> <span m=''1244480''>with</span> <span m=''1244610''>induction</span>
  <span m=''1245000''>in</span> <span m=''1245080''>class,</span> <span m=''1245540''>and</span>
  <span m=''1245870''>many</span> <span m=''1246050''>more in</span> <span m=''1246270''>homework</span>
  <span m=''1246720''>over</span> <span m=''1246860''>the</span> <span m=''1246930''>next</span>
  <span m=''1247440''>five</span> <span m=''1247660''>to</span> <span m=''1247740''>six</span>
  <span m=''1248000''>weeks.</span> <span m=''1249610''>You''ll</span> <span m=''1249740''>probably</span>
  <span m=''1250040''>be</span> <span m=''1250160''>dreaming</span> <span m=''1250950''>about</span>
  <span m=''1251240''>induction,</span> <span m=''1251670''>if</span> <span m=''1251800''>we''re</span>
  <span m=''1251960''>successful</span> <span m=''1252490''>here.</span> <span m=''1253940''>Soon.</span>
  </p><p><span m=''1255130''>The</span> <span m=''1255240''>good</span> <span m=''1255460''>news</span>
  <span m=''1255700''>is</span> <span m=''1256350''>that</span> <span m=''1256480''>induction</span>
  <span m=''1256970''>is</span> <span m=''1257090''>very</span> <span m=''1257550''>easy.</span>
  <span m=''1258210''>Once</span> <span m=''1258480''>you</span> <span m=''1258550''>get</span>
  <span m=''1258700''>your</span> <span m=''1258800''>mind</span> <span m=''1259100''>around</span>
  <span m=''1259350''>it,</span> <span m=''1259440''>get</span> <span m=''1259590''>some</span>
  <span m=''1259710''>practice,</span> <span m=''1260150''>it</span> <span m=''1260520''>really</span>
  <span m=''1260910''>is</span> <span m=''1261040''>not</span> <span m=''1261280''>a</span>
  <span m=''1261340''>hard</span> <span m=''1261630''>thing.</span> <span m=''1262910''>In</span>
  <span m=''1263050''>fact,</span> <span m=''1263410''>induction</span> <span m=''1263910''>is</span>
  <span m=''1264020''>really</span> <span m=''1264390''>just</span> <span m=''1264990''>an</span>
  <span m=''1265130''>axiom.</span> <span m=''1268290''>So</span> <span m=''1268450''>let</span>
  <span m=''1268540''>me</span> <span m=''1268650''>state</span> <span m=''1268920''>it.</span>
  <span m=''1276950''>Let</span> <span m=''1277280''>P(n)</span> <span m=''1279180''>be
  a</span> <span m=''1279450''>predicate.</span> <span m=''1286740''>If</span> <span
  m=''1287410''>P(0)</span> <span m=''1288721''>is</span> <span m=''1289160''>true,</span>
  <span m=''1293110''>and</span> <span m=''1296100''>for</span> <span m=''1296390''>all</span>
  <span m=''1297500''>natural</span> <span m=''1297910''>numbers</span> <span m=''1298340''>n,</span>
  <span m=''1303670''>p</span> <span m=''1303960''>of</span> <span m=''1304040''>n</span>
  <span m=''1304940''>implies</span> <span m=''1305840''>p</span> <span m=''1306140''>of</span>
  <span m=''1306220''>n</span> <span m=''1306390''>plus</span> <span m=''1306680''>1</span>
  <span m=''1308770''>is</span> <span m=''1308950''>true.</span> <span m=''1311140''>So</span>
  <span m=''1311180''>here</span> <span m=''1311390''>I''m</span> <span m=''1311500''>saying</span>
  <span m=''1311920''>that</span> <span m=''1312060''>this</span> <span m=''1312590''>is</span>
  <span m=''1312750''>true</span> <span m=''1313140''>for</span> <span m=''1313360''>all</span>
  <span m=''1313570''>n.</span> <span m=''1319770''>OK.</span> <span m=''1322620''>Then</span>
  <span m=''1324270''>for</span> <span m=''1326380''>all</span> <span m=''1326640''>n,</span>
  <span m=''1328980''>natural</span> <span m=''1329290''>numbers,</span> <span m=''1331010''>P</span>
  <span m=''1331220''>of</span> <span m=''1331300''>n</span> <span m=''1331450''>is</span>
  <span m=''1331540''>true.</span> <span m=''1336170''>I</span> <span m=''1336370''>had</span>
  <span m=''1336450''>another</span> <span m=''1336670''>way</span> <span m=''1336840''>of</span>
  <span m=''1336930''>saying</span> <span m=''1337330''>this</span> <span m=''1337530''>without</span>
  <span m=''1338090''>the</span> <span m=''1338220''>for</span> <span m=''1338485''>alls</span>
  <span m=''1338750''>there,</span> <span m=''1339970''>is</span> <span m=''1340220''>that</span>
  <span m=''1341510''>if</span> <span m=''1343030''>P(0)</span> <span m=''1343670''>is</span>
  <span m=''1343790''>true,</span> <span m=''1345090''>if</span> <span m=''1345260''>P(0)</span>
  <span m=''1346370''>implies</span> <span m=''1347050''>P(1)</span> <span m=''1347600''>is</span>
  <span m=''1347710''>true,</span> <span m=''1349130''>if</span> <span m=''1350380''>P(1)</span>
  <span m=''1351690''>implies</span> <span m=''1352270''>P(2)</span> <span m=''1352720''>is</span>
  <span m=''1352850''>true,</span> <span m=''1354030''>and</span> <span m=''1354330''>so</span>
  <span m=''1354600''>on,</span> <span m=''1354950''>forever,</span> <span m=''1357140''>then</span>
  <span m=''1358070''>p</span> <span m=''1358270''>of</span> <span m=''1358330''>n</span>
  <span m=''1358480''>is</span> <span m=''1358590''>true</span> <span m=''1358790''>for</span>
  <span m=''1358960''>all</span> <span m=''1359110''>that.</span> <span m=''1360240''>So</span>
  <span m=''1360470''>then,</span> <span m=''1362630''>P(0),</span> <span m=''1364320''>P(1),</span>
  <span m=''1366010''>P(2),</span> <span m=''1367690''>forever,</span> <span m=''1368550''>are</span>
  <span m=''1368680''>true.</span> </p><p><span m=''1377760''>OK.</span> <span m=''1379900''>Now</span>
  <span m=''1380300''>you</span> <span m=''1380440''>can</span> <span m=''1380550''>sort</span>
  <span m=''1380820''>of</span> <span m=''1380900''>see</span> <span m=''1381130''>why</span>
  <span m=''1381290''>this</span> <span m=''1381490''>is</span> <span m=''1381610''>a</span>
  <span m=''1381720''>reasonable</span> <span m=''1382630''>axiom,</span> <span m=''1384600''>because</span>
  <span m=''1385110''>if</span> <span m=''1385260''>P(0)</span> <span m=''1385860''>is</span>
  <span m=''1385960''>true,</span> <span m=''1387380''>and</span> <span m=''1388090''>P(0)</span>
  <span m=''1388490''>implies</span> <span m=''1388870''>P(1),</span> <span m=''1390240''>then</span>
  <span m=''1390440''>by</span> <span m=''1390570''>that</span> <span m=''1390770''>modus</span>
  <span m=''1391080''>ponens</span> <span m=''1391510''>thing</span> <span m=''1391710''>or</span>
  <span m=''1391780''>one</span> <span m=''1391920''>of</span> <span m=''1391960''>the</span>
  <span m=''1392020''>logical</span> <span m=''1392420''>deductions,</span> <span
  m=''1393640''>we</span> <span m=''1393740''>know</span> <span m=''1393880''>P(1)</span>
  <span m=''1394220''>is</span> <span m=''1394300''>true.</span> <span m=''1396000''>And</span>
  <span m=''1396310''>if</span> <span m=''1396850''>P(1)</span> <span m=''1397230''>is</span>
  <span m=''1397330''>true,</span> <span m=''1398400''>and</span> <span m=''1398580''>P(1)</span>
  <span m=''1398750''>implies</span> <span m=''1399230''>P(2)</span> <span m=''1399590''>is</span>
  <span m=''1399700''>true,</span> <span m=''1400120''>then</span> <span m=''1400220''>we</span>
  <span m=''1400310''>know</span> <span m=''1400560''>by</span> <span m=''1400670''>the</span>
  <span m=''1400790''>same</span> <span m=''1401060''>reasoning,</span> <span m=''1401770''>P(2)</span>
  <span m=''1402140''>is</span> <span m=''1402250''>true,</span> <span m=''1404020''>and</span>
  <span m=''1404150''>so</span> <span m=''1404480''>on,</span> <span m=''1404710''>forever.</span>
  <span m=''1405770''>Now</span> <span m=''1405890''>the</span> <span m=''1406000''>reason</span>
  <span m=''1406300''>it</span> <span m=''1406350''>becomes</span> <span m=''1406660''>an</span>
  <span m=''1406760''>axiom</span> <span m=''1407310''>is</span> <span m=''1407410''>that</span>
  <span m=''1407930''>and</span> <span m=''1408110''>so</span> <span m=''1408360''>on</span>
  <span m=''1408530''>forever</span> <span m=''1408870''>bit</span> <span m=''1408980''>is</span>
  <span m=''1409090''>part</span> <span m=''1409310''>of</span> <span m=''1409410''>it.</span>
  <span m=''1410200''>That''s</span> <span m=''1410430''>why</span> <span m=''1410530''>we</span>
  <span m=''1410650''>need</span> <span m=''1410810''>it as</span> <span m=''1410980''>an</span>
  <span m=''1411070''>axiom.</span> <span m=''1413370''>You</span> <span m=''1413510''>could</span>
  <span m=''1413650''>sort</span> <span m=''1413820''>of</span> <span m=''1413890''>view</span>
  <span m=''1414150''>this</span> <span m=''1414440''>as</span> <span m=''1414720''>a</span>
  <span m=''1415110''>series</span> <span m=''1415420''>of</span> <span m=''1415540''>dominoes.</span>
  <span m=''1417652''>You know,</span> <span m=''1418020''>I</span> <span m=''1418140''>got</span>
  <span m=''1418320''>a</span> <span m=''1418390''>domino</span> <span m=''1418970''>for</span>
  <span m=''1419190''>each</span> <span m=''1420030''>n,</span> <span m=''1437300''>and</span>
  <span m=''1438230''>each</span> <span m=''1438630''>domino</span> <span m=''1439140''>knocks</span>
  <span m=''1439520''>over</span> <span m=''1439710''>the</span> <span m=''1439820''>next</span>
  <span m=''1440085''>in</span> <span m=''1440350''>terms</span> <span m=''1440750''>of</span>
  <span m=''1440850''>truth,</span> <span m=''1441710''>knocking</span> <span m=''1442040''>over</span>
  <span m=''1442260''>corresponds</span> <span m=''1442840''>to</span> <span m=''1442940''>the</span>
  <span m=''1443040''>truth</span> <span m=''1443200''>here.</span> <span m=''1444230''>And</span>
  <span m=''1444460''>if</span> <span m=''1444570''>I</span> <span m=''1445210''>know</span>
  <span m=''1445390''>P(0)</span> <span m=''1445860''>is</span> <span m=''1445950''>true,</span>
  <span m=''1446190''>that</span> <span m=''1446330''>means</span> <span m=''1446520''>I</span>
  <span m=''1446580''>knock</span> <span m=''1446870''>over</span> <span m=''1447040''>P(0),</span>
  <span m=''1448400''>P(0)</span> <span m=''1448800''>implies</span> <span m=''1449120''>P(1)</span>
  <span m=''1449470''>means</span> <span m=''1449680''>P(1)</span> <span m=''1449830''>one</span>
  <span m=''1450080''>goes</span> <span m=''1450270''>down.</span> <span m=''1451210''>P(1)</span>
  <span m=''1451300''>implies</span> <span m=''1451740''>P(2)</span> <span m=''1452060''>means</span>
  <span m=''1452360''>P(2)</span> <span m=''1452540''>goes</span> <span m=''1452700''>down,</span>
  <span m=''1453110''>and</span> <span m=''1453300''>so</span> <span m=''1453460''>forth.</span>
  </p><p><span m=''1455070''>Pretty</span> <span m=''1455920''>basic.</span> <span
  m=''1459380''>Raise</span> <span m=''1459610''>your</span> <span m=''1459720''>hand</span>
  <span m=''1459980''>if</span> <span m=''1460050''>you</span> <span m=''1460150''>think</span>
  <span m=''1460360''>you</span> <span m=''1460480''>don''t</span> <span m=''1460720''>have</span>
  <span m=''1460900''>a</span> <span m=''1460940''>lot</span> <span m=''1461120''>of</span>
  <span m=''1461190''>experience</span> <span m=''1461660''>with</span> <span m=''1461780''>induction.</span>
  <span m=''1463745''>All right,</span> <span m=''1464210''>yeah,</span> <span m=''1464350''>that''s</span>
  <span m=''1465230''>pretty</span> <span m=''1465790''>typical.</span> <span m=''1466200''>About</span>
  <span m=''1466400''>a</span> <span m=''1466530''>third</span> <span m=''1466630''>to
  a</span> <span m=''1466680''>half</span> <span m=''1466900''>of</span> <span m=''1466980''>you.</span>
  <span m=''1467560''>So</span> <span m=''1467720''>we''re</span> <span m=''1468140''>going</span>
  <span m=''1468270''>to</span> <span m=''1468340''>change</span> <span m=''1468640''>that.</span>
  <span m=''1470640''>Let''s</span> <span m=''1470860''>do</span> <span m=''1470970''>a</span>
  <span m=''1471030''>simple</span> <span m=''1471330''>proof</span> <span m=''1471680''>using</span>
  <span m=''1471970''>induction.</span> <span m=''1476580''>So</span> <span m=''1476750''>let''s</span>
  <span m=''1477190''>prove</span> <span m=''1477600''>that</span> <span m=''1477700''>for
  all</span> <span m=''1478250''>n</span> <span m=''1479280''>bigger</span> <span
  m=''1479500''>than</span> <span m=''1479680''>or</span> <span m=''1479750''>equal</span>
  <span m=''1479940''>to</span> <span m=''1480000''>0,</span> <span m=''1480600''>again</span>
  <span m=''1480890''>natural</span> <span m=''1481230''>numbers,</span> <span m=''1482160''>that</span>
  <span m=''1482300''>1,</span> <span m=''1482660''>plus</span> <span m=''1482950''>2,</span>
  <span m=''1483410''>plus</span> <span m=''1483700''>3,</span> <span m=''1485820''>plus</span>
  <span m=''1486890''>n</span> <span m=''1488140''>equals</span> <span m=''1489360''>n</span>
  <span m=''1489730''>times</span> <span m=''1490000''>n</span> <span m=''1490140''>plus</span>
  <span m=''1490380''>1</span> <span m=''1491340''>over</span> <span m=''1491580''>2.</span>
  <span m=''1493980''>This</span> <span m=''1494140''>is</span> <span m=''1494240''>actually
  a</span> <span m=''1494590''>useful</span> <span m=''1494900''>thing</span> <span
  m=''1495090''>to</span> <span m=''1495160''>remember.</span> <span m=''1495510''>We''re</span>
  <span m=''1495640''>going</span> <span m=''1495750''>to</span> <span m=''1495790''>use</span>
  <span m=''1496080''>this</span> <span m=''1496410''>all</span> <span m=''1496745''>term,
  this</span> <span m=''1497080''>identity.</span> </p><p><span m=''1498820''>Now</span>
  <span m=''1500040''>the</span> <span m=''1500140''>first</span> <span m=''1500430''>thing,</span>
  <span m=''1500660''>before</span> <span m=''1500900''>we</span> <span m=''1501010''>prove</span>
  <span m=''1501350''>it,</span> <span m=''1501740''>I</span> <span m=''1501810''>want</span>
  <span m=''1501960''>to</span> <span m=''1502000''>make</span> <span m=''1502130''>sure</span>
  <span m=''1502320''>we</span> <span m=''1502450''>understand</span> <span m=''1502950''>this</span>
  <span m=''1503780''>dot,</span> <span m=''1504080''>dot,</span> <span m=''1504340''>dot,</span>
  <span m=''1504710''>notation.</span> <span m=''1505740''>Because</span> <span m=''1505890''>it</span>
  <span m=''1505980''>is</span> <span m=''1506110''>the</span> <span m=''1506210''>source</span>
  <span m=''1506630''>of</span> <span m=''1506720''>a</span> <span m=''1506790''>lot</span>
  <span m=''1507100''>of</span> <span m=''1507190''>errors.</span> <span m=''1508690''>What</span>
  <span m=''1508890''>it</span> <span m=''1509040''>means</span> <span m=''1509800''>is</span>
  <span m=''1510080''>that</span> <span m=''1510810''>you</span> <span m=''1510950''>need</span>
  <span m=''1511120''>to</span> <span m=''1511190''>fill</span> <span m=''1511600''>in</span>
  <span m=''1511830''>the</span> <span m=''1511920''>pattern</span> <span m=''1512370''>here,</span>
  <span m=''1514180''>which</span> <span m=''1514550''>is</span> <span m=''1514820''>vague.</span>
  <span m=''1516500''>What</span> <span m=''1516630''>it</span> <span m=''1516700''>means</span>
  <span m=''1516940''>in</span> <span m=''1516990''>this</span> <span m=''1517210''>case,</span>
  <span m=''1517450''>you</span> <span m=''1517670''>fill</span> <span m=''1517930''>in</span>
  <span m=''1518030''>four,</span> <span m=''1518370''>five,</span> <span m=''1518700''>six</span>
  <span m=''1519220''>all</span> <span m=''1519380''>the</span> <span m=''1519440''>way</span>
  <span m=''1519540''>up</span> <span m=''1519650''>to</span> <span m=''1519970''>n</span>
  <span m=''1520150''>minus</span> <span m=''1520510''>1,</span> <span m=''1521160''>and
  then</span> <span m=''1521460''>n.</span> <span m=''1522020''>That''s</span> <span
  m=''1522240''>what</span> <span m=''1522350''>it</span> <span m=''1522430''>means.</span>
  <span m=''1522740''>Figure</span> <span m=''1523060''>out</span> <span m=''1523200''>the</span>
  <span m=''1523290''>pattern</span> <span m=''1523690''>and</span> <span m=''1523810''>fill</span>
  <span m=''1524120''>it in.</span> <span m=''1525020''>Pretty</span> <span m=''1525230''>risky</span>
  <span m=''1525880''>thing.</span> <span m=''1527340''>Now</span> <span m=''1527480''>in</span>
  <span m=''1527560''>this</span> <span m=''1527750''>case,</span> <span m=''1528050''>because</span>
  <span m=''1528390''>that''s</span> <span m=''1528610''>so</span> <span m=''1528770''>vague,</span>
  <span m=''1529490''>there''s</span> <span m=''1529680''>other</span> <span m=''1529990''>terminology</span>
  <span m=''1530640''>we</span> <span m=''1530770''>use</span> <span m=''1531050''>for</span>
  <span m=''1531140''>this.</span> <span m=''1532320''>For</span> <span m=''1532420''>example,</span>
  <span m=''1533030''>we</span> <span m=''1533150''>would</span> <span m=''1533290''>use</span>
  <span m=''1535150''>a</span> <span m=''1535230''>big</span> <span m=''1535710''>sigma,</span>
  <span m=''1536200''>capital</span> <span m=''1536560''>sigma</span> <span m=''1537720''>i</span>
  <span m=''1538060''>equals</span> <span m=''1538470''>0</span> <span m=''1538780''>to</span>
  <span m=''1539070''>n</span> <span m=''1539550''>of</span> <span m=''1539890''>i.</span>
  <span m=''1540250''>That</span> <span m=''1540310''>means</span> <span m=''1540580''>the</span>
  <span m=''1540700''>sum</span> <span m=''1542080''>of</span> <span m=''1542290''>i,</span>
  <span m=''1543170''>where i</span> <span m=''1543610''>is</span> <span m=''1543750''>the</span>
  <span m=''1543920''>integers</span> <span m=''1544150''>from</span> <span m=''1544490''>0</span>
  <span m=''1544940''>to</span> <span m=''1545090''>n</span> <span m=''1545310''>inclusive.</span>
  <span m=''1547030''>Actually,</span> <span m=''1547330''>let me</span> <span m=''1547440''>put</span>
  <span m=''1547620''>1</span> <span m=''1547850''>here.</span> </p><p><span m=''1551470''>Another</span>
  <span m=''1551640''>way</span> <span m=''1551750''>to</span> <span m=''1551860''>write</span>
  <span m=''1552120''>this--</span> <span m=''1553491''>these</span> <span m=''1553950''>are</span>
  <span m=''1554050''>all</span> <span m=''1554270''>equivalent</span> <span m=''1554620''>ways</span>
  <span m=''1554830''>to</span> <span m=''1554930''>write</span> <span m=''1555150''>it--</span>
  <span m=''1556270''>is</span> <span m=''1556460''>you</span> <span m=''1556600''>could</span>
  <span m=''1556760''>put</span> <span m=''1557410''>1</span> <span m=''1557510''>less</span>
  <span m=''1557610''>than</span> <span m=''1557810''>or</span> <span m=''1558160''>equal</span>
  <span m=''1558350''>to</span> <span m=''1558510''>i,</span> <span m=''1559030''>less
  than or</span> <span m=''1559270''>equal</span> <span m=''1559490''>to</span> <span
  m=''1559580''>n</span> <span m=''1560430''>of</span> <span m=''1560590''>i.</span>
  <span m=''1561005''>So</span> <span m=''1561420''>you</span> <span m=''1561480''>could</span>
  <span m=''1561640''>put</span> <span m=''1562430''>something</span> <span m=''1562790''>i</span>
  <span m=''1563010''>over</span> <span m=''1563200''>the</span> <span m=''1563330''>range,</span>
  <span m=''1563850''>from</span> <span m=''1564000''>one to</span> <span m=''1564230''>n,</span>
  <span m=''1564810''>or</span> <span m=''1565230''>you</span> <span m=''1565370''>can</span>
  <span m=''1565510''>write</span> <span m=''1565780''>it</span> <span m=''1565940''>on</span>
  <span m=''1566080''>the</span> <span m=''1566150''>bottom</span> <span m=''1566550''>if</span>
  <span m=''1566630''>you</span> <span m=''1566760''>want.</span> <span m=''1570690''>So</span>
  <span m=''1570810''>these</span> <span m=''1571000''>are</span> <span m=''1571050''>four</span>
  <span m=''1571560''>different</span> <span m=''1571910''>ways</span> <span m=''1572270''>of</span>
  <span m=''1572380''>writing</span> <span m=''1572730''>the</span> <span m=''1572820''>same</span>
  <span m=''1573160''>thing,</span> <span m=''1573530''>the</span> <span m=''1573670''>sum</span>
  <span m=''1573900''>of</span> <span m=''1573970''>the</span> <span m=''1574060''>natural</span>
  <span m=''1574480''>numbers</span> <span m=''1574850''>from</span> <span m=''1575050''>1</span>
  <span m=''1575260''>to</span> <span m=''1575370''>n.</span> <span m=''1576150''>And</span>
  <span m=''1576310''>we''ll</span> <span m=''1576460''>use</span> <span m=''1576660''>them</span>
  <span m=''1576710''>all</span> <span m=''1577190''>during</span> <span m=''1577370''>the</span>
  <span m=''1577460''>term.</span> <span m=''1580810''>All</span> <span m=''1580970''>right,</span>
  <span m=''1581210''>now</span> <span m=''1581460''>there''s</span> <span m=''1581620''>some</span>
  <span m=''1581740''>special</span> <span m=''1582210''>cases</span> <span m=''1582750''>that</span>
  <span m=''1583680''>make</span> <span m=''1583920''>this</span> <span m=''1585300''>a</span>
  <span m=''1585320''>little</span> <span m=''1585470''>more</span> <span m=''1585660''>interesting.</span>
  <span m=''1586430''>What</span> <span m=''1586670''>if</span> <span m=''1586790''>n</span>
  <span m=''1586980''>equals</span> <span m=''1587280''>1?</span> </p><p><span m=''1590520''>I''ve</span>
  <span m=''1590710''>got</span> <span m=''1590900''>1</span> <span m=''1591240''>plus</span>
  <span m=''1591570''>2</span> <span m=''1592780''>plus</span> <span m=''1593140''>dot,</span>
  <span m=''1593340''>dot, dot,</span> <span m=''1594080''>plus</span> <span m=''1595250''>n.</span>
  <span m=''1598490''>What</span> <span m=''1598620''>do</span> <span m=''1598660''>you</span>
  <span m=''1598750''>suppose</span> <span m=''1599180''>it</span> <span m=''1599250''>equals</span>
  <span m=''1599620''>if</span> <span m=''1599720''>n</span> <span m=''1599860''>equals</span>
  <span m=''1600100''>1?</span> <span m=''1603290''>1,</span> <span m=''1604350''>because</span>
  <span m=''1604560''>we''re</span> <span m=''1604670''>summing</span> <span m=''1605160''>the</span>
  <span m=''1605260''>numbers</span> <span m=''1605880''>from</span> <span m=''1606130''>1</span>
  <span m=''1607600''>to</span> <span m=''1607780''>1.</span> <span m=''1608910''>That''s</span>
  <span m=''1609170''>just</span> <span m=''1609780''>1,</span> <span m=''1610440''>the</span>
  <span m=''1610550''>number</span> <span m=''1610800''>1.</span> <span m=''1611390''>There</span>
  <span m=''1611570''>is</span> <span m=''1611800''>no</span> <span m=''1611980''>2.</span>
  <span m=''1613930''>And</span> <span m=''1614100''>there</span> <span m=''1614180''>aren''t</span>
  <span m=''1614580''>two</span> <span m=''1614790''>copies</span> <span m=''1615220''>of</span>
  <span m=''1615310''>1.</span> <span m=''1616880''>So</span> <span m=''1617010''>this</span>
  <span m=''1617210''>notation</span> <span m=''1617700''>is</span> <span m=''1617800''>very</span>
  <span m=''1618310''>ambiguous.</span> <span m=''1618910''>You''ll</span> <span m=''1619010''>see</span>
  <span m=''1619220''>a</span> <span m=''1619310''>2</span> <span m=''1619590''>here</span>
  <span m=''1619750''>in</span> <span m=''1619840''>the</span> <span m=''1619930''>sum.</span>
  <span m=''1620810''>If</span> <span m=''1620950''>n</span> <span m=''1621100''>is</span>
  <span m=''1621200''>1,</span> <span m=''1621430''>you''ll</span> <span m=''1621530''>see</span>
  <span m=''1621690''>a</span> <span m=''1621750''>1</span> <span m=''1621980''>here</span>
  <span m=''1622300''>and</span> <span m=''1622420''>a</span> <span m=''1622480''>1</span>
  <span m=''1622710''>here.</span> </p><p><span m=''1624180''>So you''ve</span> <span
  m=''1624250''>got</span> <span m=''1624400''>to</span> <span m=''1624450''>be</span>
  <span m=''1624560''>careful.</span> <span m=''1624780''>I</span> <span m=''1624900''>guarantee</span>
  <span m=''1625170''>you,</span> <span m=''1625440''>you''ll</span> <span m=''1625700''>make</span>
  <span m=''1625880''>a</span> <span m=''1625930''>mistake</span> <span m=''1626770''>with</span>
  <span m=''1626890''>this.</span> <span m=''1627080''>In fact</span> <span m=''1627420''>I''m</span>
  <span m=''1627480''>going</span> <span m=''1627570''>to</span> <span m=''1627610''>show</span>
  <span m=''1627810''>you</span> <span m=''1627950''>another</span> <span m=''1628190''>false</span>
  <span m=''1628420''>proof</span> <span m=''1628630''>later</span> <span m=''1628880''>where</span>
  <span m=''1628970''>this</span> <span m=''1629180''>comes</span> <span m=''1629390''>into</span>
  <span m=''1629510''>play.</span> <span m=''1631520''>What</span> <span m=''1631670''>about</span>
  <span m=''1631870''>if</span> <span m=''1632050''>n</span> <span m=''1632200''>is</span>
  <span m=''1632330''>less</span> <span m=''1632570''>than</span> <span m=''1632670''>or</span>
  <span m=''1632770''>equal</span> <span m=''1632820''>to</span> <span m=''1632880''>zero?</span>
  <span m=''1635880''>What</span> <span m=''1636110''>is</span> <span m=''1636240''>it
  then?</span> <span m=''1640950''>Any</span> <span m=''1641150''>thoughts?</span>
  <span m=''1645620''>0.</span> </p><p><span m=''1646680''>There</span> <span m=''1646930''>are</span>
  <span m=''1647300''>no</span> <span m=''1647950''>integers</span> <span m=''1648760''>to</span>
  <span m=''1648970''>sum,</span> <span m=''1651370''>no</span> <span m=''1651560''>1,</span>
  <span m=''1651900''>no</span> <span m=''1652030''>2,</span> <span m=''1652260''>no</span>
  <span m=''1652400''>n,</span> <span m=''1652550''>because</span> <span m=''1653310''>you
  never</span> <span m=''1653470''>get</span> <span m=''1653600''>started</span> <span
  m=''1653940''>because--</span> <span m=''1654270''>sorry,</span> <span m=''1654560''>n
  is</span> <span m=''1654810''>less than</span> <span m=''1654930''>or equal</span>
  <span m=''1655050''>to</span> <span m=''1655160''>0--</span> <span m=''1655650''>because</span>
  <span m=''1655860''>you''re</span> <span m=''1656010''>summing</span> <span m=''1656330''>from</span>
  <span m=''1656610''>1</span> <span m=''1656870''>to</span> <span m=''1656920''>0,</span>
  <span m=''1657550''>0 is</span> <span m=''1657910''>below.</span> <span m=''1658320''>You</span>
  <span m=''1658410''>never--</span> <span m=''1658840''>it</span> <span m=''1659160''>doesn''t</span>
  <span m=''1659370''>include</span> <span m=''1659630''>anything.</span> <span m=''1660710''>So</span>
  <span m=''1661040''>these</span> <span m=''1661310''>are</span> <span m=''1661350''>the</span>
  <span m=''1661460''>conventions</span> <span m=''1661990''>to</span> <span m=''1662070''>keep</span>
  <span m=''1662300''>in</span> <span m=''1662380''>mind</span> <span m=''1664181''>with</span>
  <span m=''1664610''>the</span> <span m=''1664850''>edge</span> <span m=''1665120''>cases</span>
  <span m=''1665510''>here.</span> <span m=''1670500''>All right,</span> <span m=''1670660''>it''s</span>
  <span m=''1670810''>easy</span> <span m=''1671270''>enough to</span> <span m=''1671350''>check</span>
  <span m=''1671910''>that</span> <span m=''1672400''>the</span> <span m=''1672490''>theorem</span>
  <span m=''1672890''>is</span> <span m=''1673300''>true</span> <span m=''1673640''>for</span>
  <span m=''1673800''>certain</span> <span m=''1674040''>values</span> <span m=''1674350''>of</span>
  <span m=''1674440''>n.</span> </p><p><span m=''1674640''>For</span> <span m=''1674730''>example,</span>
  <span m=''1675735''>if</span> <span m=''1676040''>n</span> <span m=''1676190''>equals</span>
  <span m=''1676510''>4,</span> <span m=''1677020''>I''ve</span> <span m=''1677060''>got</span>
  <span m=''1677300''>1</span> <span m=''1677620''>plus</span> <span m=''1677930''>2</span>
  <span m=''1678450''>plus</span> <span m=''1678790''>3</span> <span m=''1679270''>plus</span>
  <span m=''1679580''>4.</span> <span m=''1680520''>That''s</span> <span m=''1680860''>10.</span>
  <span m=''1682220''>And</span> <span m=''1682440''>10</span> <span m=''1682690''>equals</span>
  <span m=''1683630''>4</span> <span m=''1684230''>times</span> <span m=''1685340''>5</span>
  <span m=''1686540''>over</span> <span m=''1686760''>2,</span> <span m=''1687730''>plugging</span>
  <span m=''1688020''>in</span> <span m=''1688100''>the</span> <span m=''1688180''>formula.</span>
  <span m=''1689580''>So</span> <span m=''1689630''>for</span> <span m=''1689770''>any</span>
  <span m=''1689990''>value</span> <span m=''1690370''>of n</span> <span m=''1690610''>you</span>
  <span m=''1690710''>could</span> <span m=''1690860''>check</span> <span m=''1691120''>this</span>
  <span m=''1691290''>formula is</span> <span m=''1691700''>true.</span> <span m=''1693030''>Proving</span>
  <span m=''1693440''>is</span> <span m=''1693550''>true</span> <span m=''1693740''>for</span>
  <span m=''1693910''>all</span> <span m=''1694230''>n.</span> <span m=''1695930''>It</span>
  <span m=''1696370''>takes</span> <span m=''1696580''>a</span> <span m=''1696630''>little</span>
  <span m=''1696740''>more</span> <span m=''1696920''>effort</span> <span m=''1697240''>unless</span>
  <span m=''1697560''>you</span> <span m=''1697680''>use</span> <span m=''1698220''>induction.</span>
  <span m=''1699820''>So</span> <span m=''1700140''>let''s</span> <span m=''1700360''>do</span>
  <span m=''1700490''>that.</span> </p><p><span m=''1703430''>So we''ll</span> <span
  m=''1703630''>prove</span> <span m=''1703890''>the</span> <span m=''1703990''>theorem.</span>
  <span m=''1704870''>Now,</span> <span m=''1705020''>whenever</span> <span m=''1705270''>you''re</span>
  <span m=''1705370''>using</span> <span m=''1705610''>a</span> <span m=''1705670''>proof</span>
  <span m=''1705890''>by</span> <span m=''1706050''>induction,</span> <span m=''1707200''>first</span>
  <span m=''1707450''>thing</span> <span m=''1707540''>you</span> <span m=''1707630''>do</span>
  <span m=''1707880''>is</span> <span m=''1707960''>you</span> <span m=''1708080''>write</span>
  <span m=''1708290''>down</span> <span m=''1708590''>by</span> <span m=''1708760''>induction</span>
  <span m=''1710480''>so</span> <span m=''1710620''>we</span> <span m=''1710730''>know</span>
  <span m=''1710890''>what</span> <span m=''1711000''>you''re</span> <span m=''1711100''>going</span>
  <span m=''1711200''>to</span> <span m=''1711270''>do.</span> <span m=''1713920''>And</span>
  <span m=''1713990''>the</span> <span m=''1714750''>next</span> <span m=''1714930''>thing</span>
  <span m=''1715050''>you</span> <span m=''1715160''>need</span> <span m=''1715670''>to</span>
  <span m=''1715740''>do</span> <span m=''1715980''>is</span> <span m=''1716100''>figure</span>
  <span m=''1716410''>out,</span> <span m=''1717830''>what''s</span> <span m=''1718090''>your</span>
  <span m=''1718670''>predicate.</span> <span m=''1720500''>What''s</span> <span m=''1720730''>your</span>
  <span m=''1721470''>inductive</span> <span m=''1721930''>hypothesis?</span> <span
  m=''1723060''>What''s</span> <span m=''1723300''>p?</span> </p><p><span m=''1726310''>So</span>
  <span m=''1727360''>usually</span> <span m=''1728930''>p</span> <span m=''1729340''>will</span>
  <span m=''1729480''>be</span> <span m=''1730370''>the</span> <span m=''1730480''>thing</span>
  <span m=''1730750''>you''re</span> <span m=''1730870''>trying</span> <span m=''1731200''>to</span>
  <span m=''1731270''>prove,</span> <span m=''1731680''>namely</span> <span m=''1731980''>that</span>
  <span m=''1732100''>1 plus</span> <span m=''1732590''>2</span> <span m=''1732710''>plus</span>
  <span m=''1732960''>3</span> <span m=''1733320''>up</span> <span m=''1733420''>to</span>
  <span m=''1733510''>n</span> <span m=''1733820''>is</span> <span m=''1734440''>n</span>
  <span m=''1734640''>times</span> <span m=''1734880''>n</span> <span m=''1734980''>plus</span>
  <span m=''1735160''>1</span> <span m=''1735300''>over</span> <span m=''1735450''>2.</span>
  <span m=''1736460''>And</span> <span m=''1736780''>you</span> <span m=''1736920''>state</span>
  <span m=''1737230''>that.</span> <span m=''1737390''>You</span> <span m=''1737460''>say</span>
  <span m=''1737600''>let</span> <span m=''1737890''>p</span> <span m=''1738120''>of</span>
  <span m=''1738200''>n</span> <span m=''1739875''>be</span> <span m=''1740280''>the</span>
  <span m=''1741010''>proposition,</span> <span m=''1744760''>the</span> <span m=''1744880''>predicate,</span>
  <span m=''1746140''>that</span> <span m=''1748160''>the</span> <span m=''1748260''>sum</span>
  <span m=''1749190''>i</span> <span m=''1749620''>equals</span> <span m=''1750060''>1</span>
  <span m=''1750430''>to</span> <span m=''1750540''>n</span> <span m=''1750930''>of</span>
  <span m=''1751050''>i</span> <span m=''1752010''>equals</span> <span m=''1753180''>n</span>
  <span m=''1753460''>times</span> <span m=''1753760''>n</span> <span m=''1753880''>plus</span>
  <span m=''1754130''>1</span> <span m=''1754300''>over</span> <span m=''1754470''>2.</span>
  </p><p><span m=''1757910''>And</span> <span m=''1758000''>once</span> <span m=''1758180''>you''ve</span>
  <span m=''1758290''>got</span> <span m=''1758450''>that</span> <span m=''1758630''>established,</span>
  <span m=''1759210''>now</span> <span m=''1759390''>we''re</span> <span m=''1759480''>going</span>
  <span m=''1759580''>to</span> <span m=''1759630''>go</span> <span m=''1760870''>verify</span>
  <span m=''1762660''>that</span> <span m=''1763330''>p</span> <span m=''1763490''>0</span>
  <span m=''1763830''>is</span> <span m=''1763940''>true</span> <span m=''1764300''>and
  that</span> <span m=''1764370''>p n</span> <span m=''1765756''>implies</span> <span
  m=''1766218''>p n</span> <span m=''1766680''>plus</span> <span m=''1766890''>1.</span>
  <span m=''1769030''>So</span> <span m=''1769210''>we</span> <span m=''1769490''>always</span>
  <span m=''1769760''>have</span> <span m=''1769860''>to</span> <span m=''1769950''>write</span>
  <span m=''1770130''>this</span> <span m=''1770320''>down.</span> <span m=''1771510''>The</span>
  <span m=''1771580''>next</span> <span m=''1771810''>thing</span> <span m=''1771930''>to</span>
  <span m=''1772010''>do</span> <span m=''1772360''>is</span> <span m=''1772540''>to</span>
  <span m=''1772650''>check</span> <span m=''1772990''>what''s</span> <span m=''1773170''>called</span>
  <span m=''1773500''>the</span> <span m=''1773560''>base</span> <span m=''1773930''>case,</span>
  <span m=''1774740''>p</span> <span m=''1775040''>zero.</span> <span m=''1776165''>So</span>
  <span m=''1776600''>let''s</span> <span m=''1776870''>do</span> <span m=''1777010''>that.</span>
  </p><p><span m=''1792510''>So</span> <span m=''1792680''>we</span> <span m=''1792800''>write</span>
  <span m=''1793050''>down</span> <span m=''1793330''>base</span> <span m=''1793620''>case.</span>
  <span m=''1794130''>Some</span> <span m=''1794270''>people</span> <span m=''1794460''>call</span>
  <span m=''1794710''>it the</span> <span m=''1794790''>basis</span> <span m=''1795280''>step.</span>
  <span m=''1799160''>And</span> <span m=''1799450''>we</span> <span m=''1799530''>have</span>
  <span m=''1799640''>to</span> <span m=''1799750''>check</span> <span m=''1800930''>that</span>
  <span m=''1801300''>p</span> <span m=''1801540''>0</span> <span m=''1802500''>is</span>
  <span m=''1802650''>true.</span> <span m=''1805860''>Well,</span> <span m=''1807150''>what''s</span>
  <span m=''1807410''>the</span> <span m=''1807510''>sum</span> <span m=''1807930''>of</span>
  <span m=''1808050''>i</span> <span m=''1808550''>equals</span> <span m=''1809070''>1</span>
  <span m=''1809720''>to</span> <span m=''1809920''>0</span> <span m=''1810660''>of</span>
  <span m=''1810960''>i?</span> <span m=''1813650''>0.</span> <span m=''1814650''>There</span>
  <span m=''1814820''>are</span> <span m=''1814920''>no</span> <span m=''1815190''>terms</span>
  <span m=''1815600''>in</span> <span m=''1815660''>this</span> <span m=''1815770''>sum.</span>
  <span m=''1818750''>And</span> <span m=''1819030''>if</span> <span m=''1819140''>I</span>
  <span m=''1819230''>look</span> <span m=''1819470''>over</span> <span m=''1819650''>there,</span>
  <span m=''1820040''>n</span> <span m=''1820380''>times</span> <span m=''1820700''>n</span>
  <span m=''1820880''>plus</span> <span m=''1821130''>1</span> <span m=''1821300''>over</span>
  <span m=''1821470''>2.</span> <span m=''1822020''>If n is</span> <span m=''1822270''>0,</span>
  <span m=''1823982''>it</span> <span m=''1824430''>equals</span> <span m=''1824730''>0.</span>
  </p><p><span m=''1828610''>So</span> <span m=''1828790''>we''re</span> <span m=''1828880''>done</span>
  <span m=''1829090''>with</span> <span m=''1829180''>the</span> <span m=''1829250''>base</span>
  <span m=''1829510''>case.</span> <span m=''1829720''>We''ve</span> <span m=''1829870''>now</span>
  <span m=''1830180''>proved</span> <span m=''1830670''>that</span> <span m=''1830780''>p0</span>
  <span m=''1831420''>is</span> <span m=''1831520''>true.</span> <span m=''1833890''>And</span>
  <span m=''1834010''>the</span> <span m=''1834080''>second</span> <span m=''1834460''>part</span>
  <span m=''1835550''>is</span> <span m=''1835660''>called</span> <span m=''1835940''>the</span>
  <span m=''1836010''>inductive</span> <span m=''1836500''>step.</span> <span m=''1842460''>And</span>
  <span m=''1842690''>here</span> <span m=''1843040''>we</span> <span m=''1843150''>have</span>
  <span m=''1843370''>to</span> <span m=''1843480''>show,</span> <span m=''1844510''>for</span>
  <span m=''1844750''>n</span> <span m=''1845150''>greater</span> <span m=''1845440''>than</span>
  <span m=''1845540''>or</span> <span m=''1845640''>equal</span> <span m=''1845710''>to</span>
  <span m=''1845780''>0,</span> <span m=''1847350''>we</span> <span m=''1847430''>need</span>
  <span m=''1847610''>to</span> <span m=''1847670''>show</span> <span m=''1848160''>that</span>
  <span m=''1849360''>pn</span> <span m=''1850840''>implies</span> <span m=''1851830''>pn</span>
  <span m=''1852190''>plus</span> <span m=''1852450''>1</span> <span m=''1852650''>is</span>
  <span m=''1852750''>true.</span> </p><p><span m=''1861620''>Now</span> <span m=''1861790''>how</span>
  <span m=''1862050''>do</span> <span m=''1862100''>we</span> <span m=''1862220''>show</span>
  <span m=''1862620''>an</span> <span m=''1862690''>implication</span> <span m=''1863370''>is</span>
  <span m=''1863470''>true?</span> <span m=''1865380''>How</span> <span m=''1865560''>do</span>
  <span m=''1865680''>I</span> <span m=''1865750''>show</span> <span m=''1866070''>this</span>
  <span m=''1866270''>is</span> <span m=''1866380''>true?</span> <span m=''1866580''>What</span>
  <span m=''1866710''>am</span> <span m=''1866810''>I</span> <span m=''1866870''>going</span>
  <span m=''1866990''>to</span> <span m=''1867080''>do</span> <span m=''1867320''>to</span>
  <span m=''1867390''>show</span> <span m=''1867660''>that''s</span> <span m=''1867890''>true</span>
  <span m=''1868260''>in</span> <span m=''1868390''>general?</span> <span m=''1869810''>Yeah?</span>
  </p><p><span m=''1871290''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''1879060''>PROFESSOR:
  Right.</span> <span m=''1879780''>Because</span> <span m=''1880250''>an</span> <span
  m=''1880330''>implication</span> <span m=''1881010''>is</span> <span m=''1881120''>true</span>
  <span m=''1881770''>in</span> <span m=''1881970''>every</span> <span m=''1882300''>case,</span>
  <span m=''1882740''>except</span> <span m=''1883270''>for</span> <span m=''1884030''>true</span>
  <span m=''1884230''>implies</span> <span m=''1884620''>false.</span> </p><p><span
  m=''1886060''>So</span> <span m=''1886260''>if</span> <span m=''1886430''>pn</span>
  <span m=''1886750''>is</span> <span m=''1886890''>false,</span> <span m=''1887330''>we''re</span>
  <span m=''1887490''>done.</span> <span m=''1887960''>This</span> <span m=''1888140''>implication</span>
  <span m=''1888630''>is</span> <span m=''1888700''>true.</span> <span m=''1889410''>The</span>
  <span m=''1889550''>only</span> <span m=''1889730''>case</span> <span m=''1889980''>we</span>
  <span m=''1890050''>have</span> <span m=''1890140''>to</span> <span m=''1890240''>worry</span>
  <span m=''1890440''>about</span> <span m=''1890660''>is</span> <span m=''1890780''>p</span>
  <span m=''1890980''>of</span> <span m=''1891060''>n</span> <span m=''1891210''>is</span>
  <span m=''1891300''>true.</span> <span m=''1892530''>So</span> <span m=''1892600''>we</span>
  <span m=''1892740''>assume</span> <span m=''1893220''>p</span> <span m=''1893410''>of</span>
  <span m=''1893480''>n</span> <span m=''1893620''>is</span> <span m=''1893720''>true.</span>
  <span m=''1894600''>And</span> <span m=''1894830''>now</span> <span m=''1895050''>we</span>
  <span m=''1895170''>confirm</span> <span m=''1895930''>that</span> <span m=''1896060''>that</span>
  <span m=''1896250''>means</span> <span m=''1896500''>pn</span> <span m=''1896770''>plus</span>
  <span m=''1896990''>1</span> <span m=''1897150''>is</span> <span m=''1897240''>true.</span>
  <span m=''1900920''>So</span> <span m=''1902120''>we</span> <span m=''1902230''>write</span>
  <span m=''1902450''>that</span> <span m=''1902650''>down.</span> <span m=''1903960''>Assume</span>
  <span m=''1906080''>pn</span> <span m=''1907560''>is</span> <span m=''1907750''>true.</span>
  <span m=''1909960''>And</span> <span m=''1910160''>you</span> <span m=''1910230''>might</span>
  <span m=''1910410''>also</span> <span m=''1910690''>write</span> <span m=''1910920''>down,</span>
  <span m=''1911690''>"for</span> <span m=''1912090''>purposes</span> <span m=''1912680''>of</span>
  <span m=''1912800''>induction"</span> <span m=''1913765''>or</span> <span m=''1914980''>"purposes</span>
  <span m=''1915520''>of</span> <span m=''1915610''>it</span> <span m=''1915650''>verifying</span>
  <span m=''1915945''>the</span> <span m=''1916240''>inductive</span> <span m=''1916650''>hypothesis."</span>
  <span m=''1919310''>just</span> <span m=''1919490''>to</span> <span m=''1919570''>let</span>
  <span m=''1919740''>us</span> <span m=''1919900''>know</span> <span m=''1920220''>why</span>
  <span m=''1920570''>you''re</span> <span m=''1920710''>assuming</span> <span m=''1921180''>it.</span>
  </p><p><span m=''1921330''>In</span> <span m=''1921410''>other</span> <span m=''1921550''>words,</span>
  <span m=''1921810''>you''re</span> <span m=''1921860''>not</span> <span m=''1922100''>assuming</span>
  <span m=''1922610''>pn</span> <span m=''1922800''>is</span> <span m=''1922980''>true</span>
  <span m=''1923190''>for</span> <span m=''1923330''>purposes</span> <span m=''1923820''>of</span>
  <span m=''1923900''>contradiction.</span> <span m=''1925760''>You''re</span> <span
  m=''1925880''>assuming</span> <span m=''1926220''>it</span> <span m=''1926300''>for</span>
  <span m=''1926400''>purposes</span> <span m=''1927000''>of</span> <span m=''1927160''>induction.</span>
  <span m=''1930370''>All</span> <span m=''1930500''>right,</span> <span m=''1930630''>let''s</span>
  <span m=''1930830''>do</span> <span m=''1930960''>that.</span> <span m=''1943150''>That</span>
  <span m=''1943420''>means,</span> <span m=''1943970''>in</span> <span m=''1944050''>this</span>
  <span m=''1944270''>case,</span> <span m=''1946380''>i.e.</span> <span m=''1947400''>we</span>
  <span m=''1947550''>assume</span> <span m=''1951270''>1</span> <span m=''1951590''>plus</span>
  <span m=''1951930''>2</span> <span m=''1952410''>plus</span> <span m=''1952790''>up
  to</span> <span m=''1952880''>n</span> <span m=''1954370''>equals</span> <span m=''1956020''>n</span>
  <span m=''1956350''>times</span> <span m=''1956660''>n</span> <span m=''1956820''>plus</span>
  <span m=''1957140''>1</span> <span m=''1957470''>over</span> <span m=''1957740''>2.</span>
  </p><p><span m=''1960270''>And</span> <span m=''1960420''>we</span> <span m=''1960510''>need</span>
  <span m=''1960740''>to</span> <span m=''1960800''>show</span> <span m=''1967436''>that</span>
  <span m=''1967930''>the</span> <span m=''1968190''>n</span> <span m=''1968310''>plus</span>
  <span m=''1968570''>1</span> <span m=''1968810''>case</span> <span m=''1969100''>is</span>
  <span m=''1969190''>true,</span> <span m=''1969910''>and</span> <span m=''1970090''>the</span>
  <span m=''1970210''>1</span> <span m=''1970675''>plus 2</span> <span m=''1971140''>plus</span>
  <span m=''1972740''>n</span> <span m=''1972940''>plus</span> <span m=''1973200''>1</span>
  <span m=''1974740''>equals</span> <span m=''1976440''>n</span> <span m=''1976720''>plus</span>
  <span m=''1977120''>1</span> <span m=''1977550''>times</span> <span m=''1978130''>n</span>
  <span m=''1978350''>plus</span> <span m=''1978750''>2</span> <span m=''1980460''>over</span>
  <span m=''1980680''>2.</span> <span m=''1984710''>It''s</span> <span m=''1985070''>sort</span>
  <span m=''1985310''>of</span> <span m=''1985390''>weird,</span> <span m=''1985980''>and</span>
  <span m=''1986400''>this</span> <span m=''1986660''>does</span> <span m=''1986930''>confuse</span>
  <span m=''1987390''>people</span> <span m=''1988150''>that</span> <span m=''1988290''>aren''t</span>
  <span m=''1988530''>familiar</span> <span m=''1989070''>yet</span> <span m=''1989440''>with</span>
  <span m=''1989530''>induction.</span> <span m=''1990830''>It</span> <span m=''1990950''>looks</span>
  <span m=''1991160''>like</span> <span m=''1991290''>we</span> <span m=''1991400''>just</span>
  <span m=''1991680''>assumed</span> <span m=''1992090''>what we''re</span> <span
  m=''1992260''>trying</span> <span m=''1992540''>to</span> <span m=''1992610''>prove.</span>
  <span m=''1994360''>We''re</span> <span m=''1994460''>trying</span> <span m=''1994730''>to</span>
  <span m=''1994800''>prove</span> <span m=''1995090''>this</span> <span m=''1995250''>is</span>
  <span m=''1995340''>true</span> <span m=''1995520''>for</span> <span m=''1995690''>all</span>
  <span m=''1995880''>n.</span> <span m=''1996410''>And</span> <span m=''1996600''>we</span>
  <span m=''1996690''>just</span> <span m=''1996850''>assumed</span> <span m=''1997250''>it.</span>
  </p><p><span m=''1998280''>But</span> <span m=''1998450''>we''re</span> <span m=''1998590''>assuming</span>
  <span m=''1999090''>it in</span> <span m=''1999200''>the</span> <span m=''1999290''>context</span>
  <span m=''2000030''>of</span> <span m=''2000110''>establishing</span> <span m=''2002360''>this</span>
  <span m=''2002620''>implication</span> <span m=''2003270''>is</span> <span m=''2003370''>true.</span>
  <span m=''2004080''>And</span> <span m=''2004200''>then</span> <span m=''2004390''>we</span>
  <span m=''2004500''>apply</span> <span m=''2004820''>the</span> <span m=''2004950''>induction</span>
  <span m=''2005350''>axiom</span> <span m=''2005980''>to</span> <span m=''2006090''>conclude</span>
  <span m=''2006530''>pn</span> <span m=''2006880''>is true</span> <span m=''2007000''>for
  all n.</span> <span m=''2010540''>All</span> <span m=''2010670''>right,</span> <span
  m=''2013590''>well,</span> <span m=''2014070''>let''s</span> <span m=''2014320''>rewrite</span>
  <span m=''2014810''>this</span> <span m=''2016200''>as</span> <span m=''2017280''>1</span>
  <span m=''2017703''>plus 2</span> <span m=''2019040''>plus</span> <span m=''2020840''>n</span>
  <span m=''2021280''>plus</span> <span m=''2021760''>n</span> <span m=''2021960''>plus</span>
  <span m=''2022240''>1.</span> <span m=''2026140''>Because</span> <span m=''2026570''>I''ve</span>
  <span m=''2026700''>assumed</span> <span m=''2027200''>pn,</span> <span m=''2027780''>I</span>
  <span m=''2027880''>can</span> <span m=''2028050''>rewrite</span> <span m=''2028530''>this</span>
  <span m=''2030130''>as</span> <span m=''2030420''>an</span> <span m=''2031430''>n</span>
  <span m=''2031550''>plus</span> <span m=''2031820''>1</span> <span m=''2032140''>over</span>
  <span m=''2032460''>2.</span> <span m=''2034960''>And</span> <span m=''2035120''>now</span>
  <span m=''2036410''>plus</span> <span m=''2037070''>n</span> <span m=''2037220''>plus</span>
  <span m=''2037480''>1</span> <span m=''2037780''>out</span> <span m=''2037910''>here.</span>
  </p><p><span m=''2039600''>That</span> <span m=''2039940''>equals,</span> <span
  m=''2042490''>well,</span> <span m=''2042740''>I</span> <span m=''2042820''>got</span>
  <span m=''2043390''>n</span> <span m=''2043600''>squared</span> <span m=''2044600''>plus</span>
  <span m=''2045200''>n,</span> <span m=''2046040''>here,</span> <span m=''2046520''>over</span>
  <span m=''2046660''>2,</span> <span m=''2049179''>plus</span> <span m=''2049510''>2</span>
  <span m=''2049719''>n</span> <span m=''2049840''>plus</span> <span m=''2050070''>2.</span>
  <span m=''2055290''>And</span> <span m=''2055420''>that</span> <span m=''2055650''>equals</span>
  <span m=''2057780''>n</span> <span m=''2057909''>plus</span> <span m=''2058179''>one</span>
  <span m=''2059210''>times</span> <span m=''2059460''>n</span> <span m=''2059580''>plus</span>
  <span m=''2059830''>2</span> <span m=''2060719''>over</span> <span m=''2060940''>2,</span>
  <span m=''2062050''>which</span> <span m=''2062250''>is</span> <span m=''2062350''>what</span>
  <span m=''2062560''>we''re</span> <span m=''2062670''>trying</span> <span m=''2062940''>to</span>
  <span m=''2062989''>show.</span> <span m=''2065830''>So</span> <span m=''2065969''>we''ve</span>
  <span m=''2066090''>completed,</span> <span m=''2067159''>now,</span> <span m=''2067429''>the</span>
  <span m=''2067550''>inductive</span> <span m=''2067980''>step.</span> <span m=''2068350''>We</span>
  <span m=''2068449''>have</span> <span m=''2068570''>shown</span> <span m=''2069159''>that</span>
  <span m=''2070429''>for</span> <span m=''2070630''>all</span> <span m=''2070870''>n,</span>
  <span m=''2071736''>pn</span> <span m=''2072170''>implies</span> <span m=''2072909''>pn</span>
  <span m=''2073150''>plus</span> <span m=''2073380''>one</span> <span m=''2073870''>for
  all n</span> <span m=''2074300''>greater than or equal to</span> <span m=''2074780''>0.</span>
  </p><p><span m=''2081710''>Any</span> <span m=''2081920''>questions</span> <span
  m=''2085199''>about</span> <span m=''2085460''>that?</span> <span m=''2085760''>So,</span>
  <span m=''2086580''>the</span> <span m=''2086679''>proof</span> <span m=''2086889''>is</span>
  <span m=''2087010''>done.</span> <span m=''2089370''>We''ve</span> <span m=''2090250''>done</span>
  <span m=''2090429''>everything</span> <span m=''2090739''>we</span> <span m=''2090840''>need</span>
  <span m=''2091010''>to</span> <span m=''2091100''>imply</span> <span m=''2091409''>induction.</span>
  <span m=''2091830''>We''ve</span> <span m=''2091960''>got</span> <span m=''2092580''>p0</span>
  <span m=''2093040''>is</span> <span m=''2093130''>true.</span> <span m=''2093909''>And</span>
  <span m=''2094120''>pn</span> <span m=''2094409''>implies</span> <span m=''2094760''>pn</span>
  <span m=''2095000''>plus</span> <span m=''2095210''>1</span> <span m=''2095469''>for</span>
  <span m=''2095639''>n</span> <span m=''2095810''>bigger than or</span> <span m=''2096230''>equal</span>
  <span m=''2096429''>to</span> <span m=''2096480''>zero.</span> </p><p><span m=''2099650''>Now</span>
  <span m=''2101710''>induction</span> <span m=''2102430''>helped</span> <span m=''2102790''>us</span>
  <span m=''2102910''>prove</span> <span m=''2103130''>the</span> <span m=''2103210''>theorem.</span>
  <span m=''2105310''>Did</span> <span m=''2105430''>it</span> <span m=''2105520''>help</span>
  <span m=''2105750''>us</span> <span m=''2105880''>understand</span> <span m=''2106330''>why</span>
  <span m=''2106430''>the</span> <span m=''2106540''>theorem</span> <span m=''2106760''>is
  true?</span> <span m=''2109990''>Do</span> <span m=''2110070''>you</span> <span
  m=''2110140''>have</span> <span m=''2110310''>any</span> <span m=''2110490''>feel</span>
  <span m=''2110890''>for</span> <span m=''2111000''>why</span> <span m=''2111220''>the</span>
  <span m=''2111320''>theorem</span> <span m=''2111570''>is</span> <span m=''2111670''>true</span>
  <span m=''2111900''>after</span> <span m=''2112100''>seeing</span> <span m=''2112320''>the</span>
  <span m=''2112400''>proof?</span> <span m=''2115410''>Not</span> <span m=''2115650''>really.</span>
  <span m=''2117670''>I</span> <span m=''2117840''>don''t</span> <span m=''2117980''>think--</span>
  <span m=''2118150''>sometimes</span> <span m=''2119570''>induction</span> <span
  m=''2120000''>will</span> <span m=''2120240''>give you</span> <span m=''2120410''>an</span>
  <span m=''2120490''>understanding.</span> <span m=''2121000''>Sometimes</span> <span
  m=''2121510''>it</span> <span m=''2121580''>won''t.</span> <span m=''2121900''>Here</span>
  <span m=''2122220''>you''ve</span> <span m=''2122320''>got</span> <span m=''2123250''>no</span>
  <span m=''2123440''>understanding</span> <span m=''2123980''>of</span> <span m=''2124060''>why</span>
  <span m=''2124300''>the</span> <span m=''2124410''>theorem''s</span> <span m=''2124660''>true,</span>
  <span m=''2124950''>which</span> <span m=''2125110''>is</span> <span m=''2125180''>sort</span>
  <span m=''2125370''>of</span> <span m=''2125450''>unfortunate.</span> </p><p><span
  m=''2127160''>Did</span> <span m=''2127330''>induction</span> <span m=''2127840''>help</span>
  <span m=''2128130''>you</span> <span m=''2128260''>figure</span> <span m=''2128710''>out</span>
  <span m=''2130880''>the</span> <span m=''2131110''>answer</span> <span m=''2131530''>to</span>
  <span m=''2131630''>the</span> <span m=''2131740''>sum?</span> <span m=''2133100''>Namely,</span>
  <span m=''2133360''>say</span> <span m=''2133570''>you</span> <span m=''2133650''>were</span>
  <span m=''2133730''>trying</span> <span m=''2133980''>to</span> <span m=''2134050''>derive</span>
  <span m=''2134520''>this</span> <span m=''2134740''>answer</span> <span m=''2135190''>from</span>
  <span m=''2135380''>this</span> <span m=''2135500''>sum.</span> <span m=''2135810''>Did</span>
  <span m=''2135920''>induction</span> <span m=''2136490''>give</span> <span m=''2136630''>you</span>
  <span m=''2136730''>the</span> <span m=''2136860''>answer?</span> <span m=''2139730''>No.</span>
  <span m=''2140450''>You</span> <span m=''2140620''>had</span> <span m=''2140810''>to</span>
  <span m=''2140890''>know</span> <span m=''2141450''>the</span> <span m=''2141620''>answer,</span>
  <span m=''2142510''>namely</span> <span m=''2143410''>this,</span> <span m=''2144430''>in</span>
  <span m=''2144580''>order</span> <span m=''2144720''>to</span> <span m=''2144800''>prove</span>
  <span m=''2145060''>it</span> <span m=''2145110''>was</span> <span m=''2145260''>true.</span>
  <span m=''2147320''>Now</span> <span m=''2147470''>later</span> <span m=''2147810''>we''ll</span>
  <span m=''2147920''>see</span> <span m=''2148110''>examples</span> <span m=''2148590''>where</span>
  <span m=''2149170''>induction</span> <span m=''2149580''>actually</span> <span m=''2149830''>can</span>
  <span m=''2149990''>give</span> <span m=''2150150''>you</span> <span m=''2150240''>the</span>
  <span m=''2150400''>answer,</span> <span m=''2150690''>but</span> <span m=''2150840''>often</span>
  <span m=''2151220''>it</span> <span m=''2151300''>does</span> <span m=''2151480''>not.</span>
  </p><p><span m=''2152380''>Often,</span> <span m=''2152760''>induction</span> <span
  m=''2153330''>gives</span> <span m=''2153480''>you</span> <span m=''2153560''>no</span>
  <span m=''2153790''>hints,</span> <span m=''2154660''>no</span> <span m=''2154880''>answer,</span>
  <span m=''2155280''>just</span> <span m=''2155620''>prove</span> <span m=''2155950''>that
  it''s</span> <span m=''2156170''>right</span> <span m=''2156710''>once</span> <span
  m=''2157070''>you</span> <span m=''2157160''>had</span> <span m=''2157370''>the</span>
  <span m=''2157440''>clever</span> <span m=''2157920''>idea</span> <span m=''2158780''>that,</span>
  <span m=''2159090''>oh,</span> <span m=''2159230''>maybe</span> <span m=''2159450''>that''s</span>
  <span m=''2159660''>the</span> <span m=''2159790''>answer.</span> <span m=''2161940''>You''ll</span>
  <span m=''2162050''>see</span> <span m=''2162210''>that</span> <span m=''2162370''>with</span>
  <span m=''2162490''>things</span> <span m=''2162690''>like</span> <span m=''2162820''>the</span>
  <span m=''2162890''>beaver</span> <span m=''2163210''>flu</span> <span m=''2163440''>problem.</span>
  <span m=''2166080''>Figuring</span> <span m=''2166840''>out</span> <span m=''2167140''>the</span>
  <span m=''2167240''>inductive</span> <span m=''2167590''>hypothesis</span> <span
  m=''2168410''>or</span> <span m=''2169000''>the</span> <span m=''2169110''>answer,</span>
  <span m=''2170040''>you</span> <span m=''2170150''>know,</span> <span m=''2170300''>the</span>
  <span m=''2170430''>details</span> <span m=''2170900''>of</span> <span m=''2171020''>it</span>
  <span m=''2171300''>is</span> <span m=''2171540''>hard.</span> <span m=''2172040''>But</span>
  <span m=''2172050''>once</span> <span m=''2172270''>you</span> <span m=''2172360''>do</span>
  <span m=''2172550''>it,</span> <span m=''2172650''>then</span> <span m=''2172890''>applying
  the</span> <span m=''2173330''>induction,</span> <span m=''2174840''>not</span>
  <span m=''2175030''>so</span> <span m=''2175160''>hard.</span> <span m=''2175530''>It</span>
  <span m=''2175620''>gives</span> <span m=''2175770''>you</span> <span m=''2175860''>a</span>
  <span m=''2175920''>concrete</span> <span m=''2176320''>proof.</span> </p><p><span
  m=''2179450''>OK,</span> <span m=''2179660''>let''s</span> <span m=''2179820''>do</span>
  <span m=''2179920''>another</span> <span m=''2180190''>one.</span> <span m=''2186070''>In</span>
  <span m=''2186260''>fact,</span> <span m=''2186490''>we''re</span> <span m=''2186600''>just</span>
  <span m=''2186790''>going</span> <span m=''2186890''>to</span> <span m=''2186950''>spend</span>
  <span m=''2187260''>the</span> <span m=''2187310''>rest</span> <span m=''2187500''>of</span>
  <span m=''2187560''>today</span> <span m=''2187850''>doing</span> <span m=''2188270''>induction</span>
  <span m=''2188660''>proofs.</span> <span m=''2195380''>So</span> <span m=''2199410''>for</span>
  <span m=''2199660''>all</span> <span m=''2199920''>natural</span> <span m=''2200340''>numbers</span>
  <span m=''2200760''>n,</span> <span m=''2204300''>3</span> <span m=''2204970''>divides</span>
  <span m=''2205830''>n</span> <span m=''2206080''>cubed</span> <span m=''2207080''>minus</span>
  <span m=''2207430''>n.</span> <span m=''2208780''>Means</span> <span m=''2209140''>than</span>
  <span m=''2209320''>n cubed</span> <span m=''2209410''>minus</span> <span m=''2209670''>n
  is</span> <span m=''2209850''>a</span> <span m=''2209890''>multiple</span> <span
  m=''2210210''>of</span> <span m=''2210290''>three.</span> <span m=''2211740''>For</span>
  <span m=''2211890''>example,</span> <span m=''2213180''>n</span> <span m=''2213370''>is</span>
  <span m=''2213500''>5.</span> <span m=''2218220''>3</span> <span m=''2218810''>divides</span>
  <span m=''2219900''>125</span> <span m=''2221360''>minus</span> <span m=''2221660''>5,</span>
  <span m=''2223450''>because</span> <span m=''2223590''>that''s</span> <span m=''2223690''>120.</span>
  </p><p><span m=''2226720''>Let''s</span> <span m=''2226960''>prove</span> <span
  m=''2227280''>that.</span> <span m=''2229340''>And</span> <span m=''2229660''>we''re</span>
  <span m=''2229750''>going</span> <span m=''2229850''>to</span> <span m=''2229900''>use</span>
  <span m=''2230120''>induction.</span> <span m=''2237620''>What</span> <span m=''2237770''>do</span>
  <span m=''2237810''>you</span> <span m=''2237910''>suppose</span> <span m=''2238280''>pn''s</span>
  <span m=''2238730''>going</span> <span m=''2238850''>to</span> <span m=''2238900''>be?</span>
  <span m=''2242000''>What''s</span> <span m=''2242160''>my</span> <span m=''2242300''>predicate</span>
  <span m=''2242770''>or</span> <span m=''2242830''>my</span> <span m=''2243620''>inductive</span>
  <span m=''2244010''>hypothesis</span> <span m=''2244740''>here?</span> <span m=''2246810''>Any</span>
  <span m=''2246980''>thoughts?</span> <span m=''2250390''>Yeah?</span> </p><p><span
  m=''2251752''>PROFESSOR: [INAUDIBLE]</span> </p><p><span m=''2253460''>PROFESSOR:
  Yeah, that''s you.</span> <span m=''2253850''>Go</span> <span m=''2253950''>ahead.</span>
  </p><p><span m=''2254638''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''2256270''>PROFESSOR:
  Yeah.</span> <span m=''2256890''>First</span> <span m=''2257310''>thing</span> <span
  m=''2257490''>you</span> <span m=''2257690''>always</span> <span m=''2258110''>want</span>
  <span m=''2258270''>to</span> <span m=''2258320''>try</span> <span m=''2258710''>is</span>
  <span m=''2259050''>you</span> <span m=''2259210''>assume</span> <span m=''2259590''>that</span>
  <span m=''2259780''>is your</span> <span m=''2259970''>induction</span> <span m=''2260340''>hypothesis.</span>
  <span m=''2262460''>So</span> <span m=''2263250''>we</span> <span m=''2263380''>say,</span>
  <span m=''2264020''>let</span> <span m=''2264220''>pn</span> <span m=''2266840''>be</span>
  <span m=''2267470''>3</span> <span m=''2268140''>divides</span> <span m=''2269390''>n</span>
  <span m=''2269580''>cubed</span> <span m=''2269870''>minus</span> <span m=''2270180''>n.</span>
  <span m=''2273040''>What''s</span> <span m=''2273360''>the</span> <span m=''2273440''>next</span>
  <span m=''2273660''>thing</span> <span m=''2273790''>we</span> <span m=''2273880''>do</span>
  <span m=''2274020''>in</span> <span m=''2274090''>our</span> <span m=''2274180''>proof?</span>
  <span m=''2276230''>Base</span> <span m=''2276570''>case.</span> <span m=''2279540''>Always</span>
  <span m=''2279850''>easy</span> <span m=''2280100''>to</span> <span m=''2280180''>forget,</span>
  <span m=''2280630''>but</span> <span m=''2280850''>not</span> <span m=''2281050''>a</span>
  <span m=''2281290''>good</span> <span m=''2281490''>idea.</span> <span m=''2283200''>Base</span>
  <span m=''2283450''>case</span> <span m=''2283720''>is</span> <span m=''2283820''>n</span>
  <span m=''2283950''>equals</span> <span m=''2284250''>0.</span> <span m=''2285550''>And</span>
  <span m=''2285770''>sure</span> <span m=''2286060''>enough,</span> <span m=''2286470''>3</span>
  <span m=''2286720''>divides</span> <span m=''2287900''>0</span> <span m=''2288240''>minus</span>
  <span m=''2288590''>0.</span> <span m=''2289850''>So</span> <span m=''2289990''>that''s</span>
  <span m=''2290260''>done.</span> </p><p><span m=''2298650''>What''s</span> <span
  m=''2298910''>the</span> <span m=''2299050''>next</span> <span m=''2299450''>step</span>
  <span m=''2299760''>we</span> <span m=''2299870''>do?</span> <span m=''2304170''>What</span>
  <span m=''2304320''>is</span> <span m=''2304420''>it?</span> <span m=''2304590''>Next</span>
  <span m=''2304810''>step?</span> <span m=''2308710''>Inductive</span> <span m=''2309320''>step.</span>
  <span m=''2316940''>And</span> <span m=''2317310''>for</span> <span m=''2317400''>that</span>
  <span m=''2318700''>we''re</span> <span m=''2318850''>going</span> <span m=''2318980''>to</span>
  <span m=''2319690''>need</span> <span m=''2319850''>to</span> <span m=''2319910''>show</span>
  <span m=''2320310''>for</span> <span m=''2320530''>n</span> <span m=''2321750''>bigger</span>
  <span m=''2321960''>than or</span> <span m=''2322070''>equal</span> <span m=''2322280''>to</span>
  <span m=''2322340''>0,</span> <span m=''2323850''>we</span> <span m=''2323920''>want</span>
  <span m=''2324060''>to</span> <span m=''2324110''>show</span> <span m=''2325410''>pn</span>
  <span m=''2326930''>implies</span> <span m=''2327650''>pn</span> <span m=''2328120''>plus</span>
  <span m=''2328400''>1</span> <span m=''2329760''>is</span> <span m=''2329910''>true.</span>
  </p><p><span m=''2334880''>So</span> <span m=''2335040''>to</span> <span m=''2335150''>do</span>
  <span m=''2335340''>that</span> <span m=''2335610''>we</span> <span m=''2335760''>assume</span>
  <span m=''2336320''>pn is</span> <span m=''2336790''>true.</span> <span m=''2344750''>In</span>
  <span m=''2344880''>other</span> <span m=''2345060''>words,</span> <span m=''2345510''>we</span>
  <span m=''2345560''>assume</span> <span m=''2347570''>that</span> <span m=''2347680''>3</span>
  <span m=''2348160''>divides</span> <span m=''2349170''>n</span> <span m=''2349400''>cubed</span>
  <span m=''2349730''>minus</span> <span m=''2350100''>n.</span> <span m=''2351590''>And</span>
  <span m=''2351730''>we''re</span> <span m=''2351820''>trying</span> <span m=''2352150''>to</span>
  <span m=''2352200''>show</span> <span m=''2352700''>that</span> <span m=''2353290''>3</span>
  <span m=''2353620''>divides</span> <span m=''2354110''>n</span> <span m=''2354310''>plus</span>
  <span m=''2354610''>1</span> <span m=''2354980''>cubed</span> <span m=''2355380''>minus</span>
  <span m=''2355690''>n</span> <span m=''2355820''>plus</span> <span m=''2356090''>1.</span>
  <span m=''2357270''>So</span> <span m=''2357510''>we</span> <span m=''2358130''>take</span>
  <span m=''2358310''>a</span> <span m=''2358370''>look</span> <span m=''2358580''>at,</span>
  <span m=''2358750''>we</span> <span m=''2358850''>examine</span> <span m=''2362130''>n</span>
  <span m=''2362360''>plus</span> <span m=''2362670''>1</span> <span m=''2362950''>cubed</span>
  <span m=''2363870''>minus</span> <span m=''2364290''>n</span> <span m=''2364430''>plus</span>
  <span m=''2364680''>1.</span> <span m=''2365050''>And we</span> <span m=''2365160''>want</span>
  <span m=''2365370''>to</span> <span m=''2365420''>show</span> <span m=''2365700''>it''s</span>
  <span m=''2365810''>a</span> <span m=''2365850''>multiple</span> <span m=''2366210''>of</span>
  <span m=''2366300''>three.</span> </p><p><span m=''2369070''>Well,</span> <span
  m=''2369520''>let''s</span> <span m=''2369900''>expand</span> <span m=''2370320''>that</span>
  <span m=''2370490''>out.</span> <span m=''2372540''>This</span> <span m=''2372840''>is</span>
  <span m=''2373870''>n</span> <span m=''2374140''>cubed</span> <span m=''2374610''>plus</span>
  <span m=''2374950''>3n</span> <span m=''2375420''>squared,</span> <span m=''2376110''>plus</span>
  <span m=''2376420''>3n</span> <span m=''2377420''>plus</span> <span m=''2377740''>1.</span>
  <span m=''2379160''>And</span> <span m=''2379300''>I</span> <span m=''2379350''>subtract</span>
  <span m=''2379960''>off</span> <span m=''2381380''>n</span> <span m=''2381510''>plus</span>
  <span m=''2381770''>1.</span> <span m=''2384100''>So</span> <span m=''2384290''>I</span>
  <span m=''2384380''>get</span> <span m=''2385200''>n</span> <span m=''2385440''>cubed</span>
  <span m=''2385970''>plus</span> <span m=''2386350''>3n</span> <span m=''2386780''>squared</span>
  <span m=''2388060''>plus</span> <span m=''2388460''>2n.</span> <span m=''2394830''>Is</span>
  <span m=''2395020''>this</span> <span m=''2395200''>a</span> <span m=''2395260''>multiple</span>
  <span m=''2395570''>of</span> <span m=''2395660''>3?</span> <span m=''2399600''>I</span>
  <span m=''2399680''>need</span> <span m=''2399840''>to</span> <span m=''2399890''>show</span>
  <span m=''2400060''>that''s</span> <span m=''2400240''>a</span> <span m=''2400280''>multiple</span>
  <span m=''2400590''>of</span> <span m=''2400670''>3</span> <span m=''2401000''>and</span>
  <span m=''2401170''>then I''d</span> <span m=''2401320''>be</span> <span m=''2401430''>all</span>
  <span m=''2401590''>done.</span> <span m=''2404220''>Is</span> <span m=''2404350''>it</span>
  <span m=''2404420''>a</span> <span m=''2404470''>multiple</span> <span m=''2404740''>of</span>
  <span m=''2404820''>3?</span> </p><p><span m=''2408000''>Beats</span> <span m=''2408240''>me.</span>
  <span m=''2409950''>It</span> <span m=''2410010''>doesn''t</span> <span m=''2410240''>look</span>
  <span m=''2410520''>like</span> <span m=''2410680''>a</span> <span m=''2410730''>multiple</span>
  <span m=''2411080''>of</span> <span m=''2411170''>3,</span> <span m=''2412580''>necessarily.</span>
  <span m=''2416350''>So</span> <span m=''2417660''>maybe</span> <span m=''2417860''>we</span>
  <span m=''2417970''>need</span> <span m=''2418110''>to</span> <span m=''2418170''>massage</span>
  <span m=''2418445''>it</span> <span m=''2418720''>a</span> <span m=''2418790''>little</span>
  <span m=''2418980''>bit.</span> <span m=''2419200''>I</span> <span m=''2419410''>do</span>
  <span m=''2419680''>know</span> <span m=''2419990''>that</span> <span m=''2420640''>this</span>
  <span m=''2420990''>is</span> <span m=''2421120''>a</span> <span m=''2421170''>multiple</span>
  <span m=''2421570''>of</span> <span m=''2421660''>3.</span> <span m=''2421890''>I</span>
  <span m=''2421950''>can</span> <span m=''2422110''>use</span> <span m=''2422370''>that</span>
  <span m=''2422640''>fact.</span> <span m=''2423690''>And</span> <span m=''2423860''>in</span>
  <span m=''2423920''>proofs</span> <span m=''2424150''>by</span> <span m=''2424320''>induction</span>
  <span m=''2424740''>you</span> <span m=''2424850''>always</span> <span m=''2425120''>want</span>
  <span m=''2425290''>to--</span> <span m=''2426020''>if you''re</span> <span m=''2426110''>not</span>
  <span m=''2426310''>making</span> <span m=''2426530''>use of</span> <span m=''2426700''>that</span>
  <span m=''2426960''>fact,</span> <span m=''2427290''>then</span> <span m=''2427370''>you''re</span>
  <span m=''2427470''>not</span> <span m=''2427690''>really</span> <span m=''2427880''>making</span>
  <span m=''2428160''>use</span> <span m=''2428320''>of</span> <span m=''2428410''>induction.</span>
  <span m=''2429390''>Sort</span> <span m=''2429630''>of</span> <span m=''2429710''>a</span>
  <span m=''2429780''>warning</span> <span m=''2430100''>sign.</span> </p><p><span
  m=''2430390''>So</span> <span m=''2430590''>I</span> <span m=''2430670''>want</span>
  <span m=''2430870''>to</span> <span m=''2430910''>use</span> <span m=''2431140''>this</span>
  <span m=''2431360''>fact</span> <span m=''2432030''>to</span> <span m=''2432190''>prove</span>
  <span m=''2432480''>this.</span> <span m=''2434220''>Well,</span> <span m=''2435960''>let''s</span>
  <span m=''2437050''>get</span> <span m=''2437180''>a</span> <span m=''2437220''>minus</span>
  <span m=''2437485''>n</span> <span m=''2437810''>in</span> <span m=''2437940''>here.</span>
  <span m=''2439520''>This</span> <span m=''2439720''>equals</span> <span m=''2440020''>n</span>
  <span m=''2440190''>cubed</span> <span m=''2440510''>minus</span> <span m=''2440850''>n</span>
  <span m=''2441640''>plus</span> <span m=''2442240''>3n</span> <span m=''2442670''>squared</span>
  <span m=''2443610''>plus--</span> <span m=''2444700''>if</span> <span m=''2444780''>I</span>
  <span m=''2444840''>subtracted</span> <span m=''2445130''>an</span> <span m=''2445540''>n</span>
  <span m=''2445710''>I</span> <span m=''2445750''>got</span> <span m=''2445880''>to</span>
  <span m=''2445970''>add</span> <span m=''2446280''>an</span> <span m=''2446390''>n--</span>
  <span m=''2446650''>plus</span> <span m=''2446910''>3n.</span> <span m=''2449070''>So</span>
  <span m=''2449200''>I''ve</span> <span m=''2449340''>rewritten</span> <span m=''2449790''>it.</span>
  <span m=''2450700''>Now</span> <span m=''2451030''>is</span> <span m=''2451140''>it</span>
  <span m=''2451200''>clear?</span> <span m=''2453160''>Now</span> <span m=''2453540''>it''s</span>
  <span m=''2453680''>clear.</span> </p><p><span m=''2454740''>Very</span> <span m=''2454980''>simple,</span>
  <span m=''2455350''>because</span> <span m=''2455680''>3</span> <span m=''2455960''>divide</span>
  <span m=''2456320''>this</span> <span m=''2457250''>by</span> <span m=''2457440''>pn.</span>
  <span m=''2458390''>3</span> <span m=''2458610''>divides</span> <span m=''2458960''>that.</span>
  <span m=''2459330''>And</span> <span m=''2459440''>3</span> <span m=''2459600''>divides</span>
  <span m=''2459940''>that.</span> <span m=''2460810''>So</span> <span m=''2460960''>this</span>
  <span m=''2461420''>is</span> <span m=''2461590''>a</span> <span m=''2461650''>multiple</span>
  <span m=''2462040''>of</span> <span m=''2462140''>3,</span> <span m=''2464420''>because</span>
  <span m=''2464960''>I''ve</span> <span m=''2465050''>got</span> <span m=''2465650''>3</span>
  <span m=''2466070''>divides</span> <span m=''2466730''>3n</span> <span m=''2467140''>squared,</span>
  <span m=''2468210''>3</span> <span m=''2468530''>divides</span> <span m=''2469200''>3n,</span>
  <span m=''2470450''>and</span> <span m=''2470580''>3</span> <span m=''2470800''>divides</span>
  <span m=''2471920''>n</span> <span m=''2472150''>cubed</span> <span m=''2472670''>minus</span>
  <span m=''2473070''>n</span> <span m=''2473990''>by</span> <span m=''2475730''>pn.</span>
  <span m=''2477120''>Or</span> <span m=''2477290''>you</span> <span m=''2477360''>could</span>
  <span m=''2477490''>say,</span> <span m=''2477660''>by</span> <span m=''2477870''>the</span>
  <span m=''2477960''>inductive</span> <span m=''2478320''>hypothesis.</span> <span
  m=''2480640''>pn</span> <span m=''2481130''>is</span> <span m=''2481420''>the</span>
  <span m=''2481540''>inductive</span> <span m=''2481960''>hypothesis,</span> <span
  m=''2483300''>another</span> <span m=''2483530''>name</span> <span m=''2483810''>for</span>
  <span m=''2484110''>it.</span> </p><p><span m=''2485680''>So</span> <span m=''2485790''>therefore,</span>
  <span m=''2486190''>3</span> <span m=''2486410''>divides</span> <span m=''2486830''>that,</span>
  <span m=''2487520''>which</span> <span m=''2487780''>means</span> <span m=''2488040''>3</span>
  <span m=''2488190''>divides</span> <span m=''2488710''>this.</span> <span m=''2490820''>So</span>
  <span m=''2490940''>that</span> <span m=''2491120''>means</span> <span m=''2491360''>3</span>
  <span m=''2491550''>divides</span> <span m=''2492240''>n</span> <span m=''2492360''>plus</span>
  <span m=''2492620''>1</span> <span m=''2492830''>cubed</span> <span m=''2494460''>minus</span>
  <span m=''2494780''>n</span> <span m=''2494900''>plus</span> <span m=''2495160''>1.</span>
  <span m=''2496590''>And</span> <span m=''2496990''>we</span> <span m=''2497150''>are</span>
  <span m=''2497300''>done</span> <span m=''2499190''>with</span> <span m=''2499490''>the</span>
  <span m=''2499590''>proof</span> <span m=''2499820''>by</span> <span m=''2499960''>induction.</span>
  <span m=''2502650''>Any</span> <span m=''2502820''>questions</span> <span m=''2503280''>about
  that one?</span> </p><p><span m=''2507680''>So</span> <span m=''2507830''>the</span>
  <span m=''2507950''>key</span> <span m=''2508200''>steps in</span> <span m=''2508580''>induction</span>
  <span m=''2509110''>are</span> <span m=''2509210''>always</span> <span m=''2509490''>the</span>
  <span m=''2509590''>same.</span> <span m=''2510600''>You</span> <span m=''2510750''>write</span>
  <span m=''2510990''>down</span> <span m=''2511700''>"proof</span> <span m=''2511990''>by</span>
  <span m=''2512170''>induction."</span> <span m=''2513490''>You</span> <span m=''2513640''>identify</span>
  <span m=''2514260''>your</span> <span m=''2514410''>predicate.</span> <span m=''2515570''>You</span>
  <span m=''2515700''>do</span> <span m=''2515860''>the</span> <span m=''2515980''>base</span>
  <span m=''2516310''>case,</span> <span m=''2517650''>usually</span> <span m=''2518000''>n</span>
  <span m=''2518130''>equals</span> <span m=''2518380''>0,</span> <span m=''2518610''>but</span>
  <span m=''2518720''>it</span> <span m=''2518790''>could</span> <span m=''2518900''>be</span>
  <span m=''2518990''>something</span> <span m=''2519300''>else.</span> <span m=''2520140''>And</span>
  <span m=''2520270''>then</span> <span m=''2520390''>you</span> <span m=''2520480''>do</span>
  <span m=''2520570''>your</span> <span m=''2520720''>inductive</span> <span m=''2521100''>step.</span>
  </p><p><span m=''2523850''>Now</span> <span m=''2524030''>in</span> <span m=''2524130''>general,</span>
  <span m=''2524700''>you</span> <span m=''2524840''>could</span> <span m=''2524980''>start</span>
  <span m=''2525330''>your</span> <span m=''2525450''>induction--</span> <span m=''2526480''>you
  don''t have to start it</span> <span m=''2526860''>at</span> <span m=''2527270''>0,</span>
  <span m=''2527560''>you could</span> <span m=''2527770''>start it</span> <span m=''2528240''>at</span>
  <span m=''2528570''>some</span> <span m=''2528860''>value</span> <span m=''2529300''>b,</span>
  <span m=''2530290''>some</span> <span m=''2530510''>integer</span> <span m=''2530923''>b.</span>
  <span m=''2536610''>Let''s</span> <span m=''2537040''>take</span> <span m=''2537220''>a</span>
  <span m=''2537280''>look</span> <span m=''2537440''>at</span> <span m=''2537500''>that.</span>
  </p><p><span m=''2545050''>So</span> <span m=''2545430''>you</span> <span m=''2545590''>could</span>
  <span m=''2545860''>have</span> <span m=''2546070''>for</span> <span m=''2546140''>the</span>
  <span m=''2546230''>base</span> <span m=''2546550''>case,</span> <span m=''2549900''>you</span>
  <span m=''2550040''>could</span> <span m=''2550150''>have</span> <span m=''2550530''>p</span>
  <span m=''2550870''>of</span> <span m=''2550950''>b</span> <span m=''2551820''>is</span>
  <span m=''2551980''>true,</span> <span m=''2552350''>not</span> <span m=''2552580''>p</span>
  <span m=''2552730''>of</span> <span m=''2552790''>0.</span> <span m=''2555130''>And</span>
  <span m=''2555310''>then</span> <span m=''2555510''>for</span> <span m=''2555610''>your</span>
  <span m=''2555800''>induction</span> <span m=''2556290''>step</span> <span m=''2560550''>you</span>
  <span m=''2560730''>would</span> <span m=''2560860''>have</span> <span m=''2561770''>for</span>
  <span m=''2562110''>all</span> <span m=''2562500''>n</span> <span m=''2562880''>bigger</span>
  <span m=''2563200''>than</span> <span m=''2563370''>or equal</span> <span m=''2563590''>to</span>
  <span m=''2563660''>b,</span> <span m=''2566460''>pn</span> <span m=''2566720''>implies</span>
  <span m=''2567440''>pn</span> <span m=''2567750''>plus</span> <span m=''2567980''>1.</span>
  <span m=''2570000''>And</span> <span m=''2570200''>then</span> <span m=''2570340''>your</span>
  <span m=''2570490''>conclusion</span> <span m=''2574960''>is</span> <span m=''2575430''>that</span>
  <span m=''2575710''>for</span> <span m=''2575880''>all</span> <span m=''2576270''>n</span>
  <span m=''2576740''>bigger</span> <span m=''2577000''>than or</span> <span m=''2577080''>equal</span>
  <span m=''2577270''>to</span> <span m=''2577340''>b,</span> <span m=''2578290''>pn
  is</span> <span m=''2578710''>true.</span> </p><p><span m=''2580790''>So</span>
  <span m=''2580960''>inductions</span> <span m=''2581480''>don''t</span> <span m=''2581730''>always</span>
  <span m=''2582220''>have</span> <span m=''2582350''>to</span> <span m=''2582440''>start</span>
  <span m=''2582670''>at</span> <span m=''2582760''>0.</span> <span m=''2583630''>You</span>
  <span m=''2583810''>can</span> <span m=''2583980''>pick</span> <span m=''2584190''>where</span>
  <span m=''2584300''>you</span> <span m=''2584410''>start.</span> <span m=''2585790''>Just</span>
  <span m=''2586130''>make</span> <span m=''2586310''>sure</span> <span m=''2586670''>that</span>
  <span m=''2588130''>you</span> <span m=''2588280''>verify</span> <span m=''2588840''>the</span>
  <span m=''2588940''>starting</span> <span m=''2589280''>point</span> <span m=''2590150''>and</span>
  <span m=''2590280''>you</span> <span m=''2590390''>verify</span> <span m=''2590880''>the</span>
  <span m=''2591000''>implication</span> <span m=''2591850''>for</span> <span m=''2591990''>all</span>
  <span m=''2592230''>n</span> <span m=''2592940''>at</span> <span m=''2593110''>that</span>
  <span m=''2593290''>starting</span> <span m=''2593620''>point</span> <span m=''2594060''>and</span>
  <span m=''2594280''>beyond.</span> </p><p><span m=''2600680''>All</span> <span m=''2600860''>right,</span>
  <span m=''2601020''>let''s</span> <span m=''2601330''>now</span> <span m=''2603240''>do</span>
  <span m=''2603430''>a</span> <span m=''2603540''>false</span> <span m=''2604050''>proof</span>
  <span m=''2605180''>using</span> <span m=''2605560''>induction.</span> <span m=''2615090''>We''re</span>
  <span m=''2615270''>going</span> <span m=''2615380''>to</span> <span m=''2615460''>prove</span>
  <span m=''2620160''>that</span> <span m=''2620550''>all</span> <span m=''2620830''>horses</span>
  <span m=''2621330''>are</span> <span m=''2621370''>the</span> <span m=''2621490''>same</span>
  <span m=''2621760''>color.</span> <span m=''2634600''>So</span> <span m=''2634750''>let''s</span>
  <span m=''2634980''>go</span> <span m=''2635120''>through</span> <span m=''2635230''>the</span>
  <span m=''2635330''>process.</span> <span m=''2637270''>So</span> <span m=''2637430''>the</span>
  <span m=''2637510''>proof,</span> <span m=''2638010''>we</span> <span m=''2638120''>write</span>
  <span m=''2638350''>down</span> <span m=''2638580''>"by</span> <span m=''2638780''>induction."</span>
  </p><p><span m=''2644750''>Now</span> <span m=''2644930''>we</span> <span m=''2645020''>need</span>
  <span m=''2645200''>our</span> <span m=''2645320''>induction</span> <span m=''2645660''>hypothesis,</span>
  <span m=''2646420''>the</span> <span m=''2646520''>predicate.</span> <span m=''2648320''>So</span>
  <span m=''2649190''>we''re</span> <span m=''2649330''>going</span> <span m=''2649430''>to</span>
  <span m=''2649490''>let</span> <span m=''2649680''>that</span> <span m=''2649930''>be--</span>
  <span m=''2651670''>we</span> <span m=''2651770''>can''t</span> <span m=''2651990''>let</span>
  <span m=''2652130''>it</span> <span m=''2652190''>be</span> <span m=''2652330''>this.</span>
  <span m=''2652550''>Why</span> <span m=''2652750''>can''t</span> <span m=''2653050''>this</span>
  <span m=''2653250''>be</span> <span m=''2653400''>our</span> <span m=''2653480''>predicate?</span>
  <span m=''2654950''>All</span> <span m=''2655190''>horses</span> <span m=''2655580''>are</span>
  <span m=''2655630''>the</span> <span m=''2655730''>same</span> <span m=''2655970''>color.</span>
  <span m=''2656340''>What''s</span> <span m=''2656570''>wrong</span> <span m=''2656890''>with</span>
  <span m=''2657000''>making</span> <span m=''2657280''>that</span> <span m=''2657550''>be</span>
  <span m=''2657650''>the</span> <span m=''2657750''>induction</span> <span m=''2658080''>hypothesis?</span>
  <span m=''2661090''>You</span> <span m=''2661200''>can''t</span> <span m=''2661440''>plug</span>
  <span m=''2661700''>anything</span> <span m=''2662030''>into</span> <span m=''2662200''>it.</span>
  <span m=''2662250''>There''s</span> <span m=''2662400''>no</span> <span m=''2662570''>number</span>
  <span m=''2663200''>here.</span> <span m=''2663900''>I''ve</span> <span m=''2663990''>got</span>
  <span m=''2664210''>to</span> <span m=''2664250''>have</span> <span m=''2664410''>a</span>
  <span m=''2664480''>number,</span> <span m=''2664810''>n,</span> <span m=''2665470''>to</span>
  <span m=''2665590''>induct</span> <span m=''2665960''>on.</span> </p><p><span m=''2667050''>So</span>
  <span m=''2667510''>what</span> <span m=''2667610''>I''m</span> <span m=''2667690''>going</span>
  <span m=''2667770''>to</span> <span m=''2667840''>say</span> <span m=''2668190''>is</span>
  <span m=''2668350''>that</span> <span m=''2670010''>in</span> <span m=''2670320''>any</span>
  <span m=''2670610''>set</span> <span m=''2673112''>of</span> <span m=''2673540''>n</span>
  <span m=''2673740''>horses--</span> <span m=''2677000''>and</span> <span m=''2677200''>let''s</span>
  <span m=''2677390''>make</span> <span m=''2677660''>n</span> <span m=''2677930''>bigger</span>
  <span m=''2678230''>than or</span> <span m=''2678330''>equal</span> <span m=''2678420''>to</span>
  <span m=''2678490''>1--</span> <span m=''2682180''>the</span> <span m=''2683590''>horses</span>
  <span m=''2686310''>are</span> <span m=''2687460''>all</span> <span m=''2688160''>the</span>
  <span m=''2688250''>same</span> <span m=''2688500''>color.</span> <span m=''2695600''>All</span>
  <span m=''2695720''>right,</span> <span m=''2695860''>now</span> <span m=''2695970''>if</span>
  <span m=''2696060''>I</span> <span m=''2696180''>prove</span> <span m=''2696650''>this</span>
  <span m=''2696830''>is</span> <span m=''2696940''>true</span> <span m=''2697160''>for</span>
  <span m=''2697370''>all</span> <span m=''2697610''>n,</span> <span m=''2698610''>well</span>
  <span m=''2698790''>then</span> <span m=''2698970''>all</span> <span m=''2699150''>horses</span>
  <span m=''2699530''>are</span> <span m=''2699570''>the</span> <span m=''2699680''>same</span>
  <span m=''2699930''>color.</span> <span m=''2700280''>Because</span> <span m=''2700440''>in</span>
  <span m=''2700520''>any</span> <span m=''2700730''>set</span> <span m=''2700960''>of</span>
  <span m=''2701040''>n</span> <span m=''2701170''>horses,</span> <span m=''2701550''>they''re</span>
  <span m=''2701630''>all</span> <span m=''2701720''>the</span> <span m=''2701800''>same</span>
  <span m=''2702020''>color.</span> <span m=''2702360''>So</span> <span m=''2703330''>all</span>
  <span m=''2703530''>horses</span> <span m=''2703870''>must</span> <span m=''2704110''>be</span>
  <span m=''2704170''>the</span> <span m=''2704270''>same</span> <span m=''2704530''>color.</span>
  </p><p><span m=''2705860''>What''s</span> <span m=''2706130''>the</span> <span m=''2706210''>next</span>
  <span m=''2706410''>thing</span> <span m=''2706570''>I</span> <span m=''2706620''>do?</span>
  <span m=''2707020''>What''s</span> <span m=''2707090''>the</span> <span m=''2707150''>next</span>
  <span m=''2707360''>step?</span> <span m=''2709150''>Base</span> <span m=''2709490''>case.</span>
  <span m=''2711870''>Now,</span> <span m=''2712150''>what</span> <span m=''2712490''>am</span>
  <span m=''2712570''>I</span> <span m=''2712640''>going</span> <span m=''2712760''>to</span>
  <span m=''2712800''>use</span> <span m=''2713100''>as</span> <span m=''2713200''>my</span>
  <span m=''2713330''>base</span> <span m=''2713820''>case</span> <span m=''2714100''>here?</span>
  <span m=''2716790''>One</span> <span m=''2717010''>horse,</span> <span m=''2718250''>OK,</span>
  <span m=''2718530''>or</span> <span m=''2718660''>n</span> <span m=''2718840''>equals</span>
  <span m=''2719130''>1.</span> <span m=''2721580''>So</span> <span m=''2721780''>p</span>
  <span m=''2722020''>of</span> <span m=''2722110''>1.</span> <span m=''2722920''>That</span>
  <span m=''2723100''>would</span> <span m=''2723280''>say</span> <span m=''2723590''>that</span>
  <span m=''2723820''>any</span> <span m=''2724160''>set</span> <span m=''2724570''>of</span>
  <span m=''2724770''>one</span> <span m=''2724980''>horses</span> <span m=''2726220''>the</span>
  <span m=''2726310''>horses</span> <span m=''2726650''>are</span> <span m=''2726750''>all</span>
  <span m=''2726860''>the</span> <span m=''2726940''>same</span> <span m=''2727170''>color.</span>
  </p><p><span m=''2728510''>That''s</span> <span m=''2728770''>true.</span> <span
  m=''2729050''>I''ve</span> <span m=''2729140''>got one</span> <span m=''2729320''>horse.</span>
  <span m=''2729650''>It''s</span> <span m=''2729830''>the</span> <span m=''2729930''>same</span>
  <span m=''2730350''>color as</span> <span m=''2730730''>itself.</span> <span m=''2732180''>So</span>
  <span m=''2732690''>that''s</span> <span m=''2732900''>easy.</span> <span m=''2733970''>It''s</span>
  <span m=''2734190''>true</span> <span m=''2735960''>since</span> <span m=''2737420''>just</span>
  <span m=''2737680''>one</span> <span m=''2737820''>horse.</span> <span m=''2763240''>All
  right,</span> <span m=''2763370''>what''s</span> <span m=''2763620''>the</span>
  <span m=''2763750''>next</span> <span m=''2764000''>step</span> <span m=''2766390''>of</span>
  <span m=''2766510''>the</span> <span m=''2766600''>proof?</span> <span m=''2768100''>What''s</span>
  <span m=''2768140''>the next</span> <span m=''2768320''>thing</span> <span m=''2768450''>I</span>
  <span m=''2768510''>do?</span> <span m=''2770200''>Inductive</span> <span m=''2770680''>step.</span>
  </p><p><span m=''2775440''>So</span> <span m=''2776600''>I''m</span> <span m=''2776820''>going</span>
  <span m=''2777090''>to</span> <span m=''2777340''>assume</span> <span m=''2780090''>that</span>
  <span m=''2780310''>pn</span> <span m=''2780680''>is</span> <span m=''2780800''>true</span>
  <span m=''2783760''>to</span> <span m=''2784130''>prove</span> <span m=''2787040''>pn--</span>
  <span m=''2787510''>and</span> <span m=''2787800''>show</span> <span m=''2788060''>pn</span>
  <span m=''2788920''>plus</span> <span m=''2789100''>1</span> <span m=''2789260''>is</span>
  <span m=''2789360''>true.</span> <span m=''2792030''>All</span> <span m=''2792230''>right,</span>
  <span m=''2793560''>so</span> <span m=''2793700''>I''m</span> <span m=''2793810''>going</span>
  <span m=''2794030''>to</span> <span m=''2794230''>assume</span> <span m=''2794630''>that</span>
  <span m=''2794790''>in any</span> <span m=''2795010''>set</span> <span m=''2795220''>of</span>
  <span m=''2795300''>n horses,</span> <span m=''2795860''>the</span> <span m=''2795950''>horses</span>
  <span m=''2796310''>are</span> <span m=''2796410''>all</span> <span m=''2796500''>the</span>
  <span m=''2796570''>same</span> <span m=''2796810''>color</span> <span m=''2797680''>that</span>
  <span m=''2797810''>I</span> <span m=''2797880''>start</span> <span m=''2798180''>with.</span>
  <span m=''2798680''>And</span> <span m=''2798870''>now</span> <span m=''2799050''>I</span>
  <span m=''2799140''>look</span> <span m=''2799370''>at</span> <span m=''2799430''>a</span>
  <span m=''2799490''>set</span> <span m=''2799760''>of</span> <span m=''2800200''>n</span>
  <span m=''2800360''>plus</span> <span m=''2800590''>1</span> <span m=''2800770''>horses.</span>
  </p><p><span m=''2804160''>So</span> <span m=''2804260''>we</span> <span m=''2804370''>consider</span>
  <span m=''2807150''>a</span> <span m=''2807300''>set</span> <span m=''2809260''>of</span>
  <span m=''2809450''>n</span> <span m=''2809690''>plus</span> <span m=''2809980''>1</span>
  <span m=''2810170''>horses.</span> <span m=''2813290''>And</span> <span m=''2813470''>let''s</span>
  <span m=''2813680''>call</span> <span m=''2814040''>those</span> <span m=''2814270''>horses</span>
  <span m=''2814750''>h1,</span> <span m=''2815940''>h2,</span> <span m=''2818894''>hn</span>
  <span m=''2819380''>plus</span> <span m=''2819590''>1.</span> <span m=''2823820''>What</span>
  <span m=''2824040''>do</span> <span m=''2824160''>I</span> <span m=''2824240''>know</span>
  <span m=''2824610''>about</span> <span m=''2826740''>horses</span> <span m=''2827350''>h1</span>
  <span m=''2827610''>to</span> <span m=''2828060''>hn?</span> <span m=''2833740''>They''re</span>
  <span m=''2833820''>the</span> <span m=''2833930''>same</span> <span m=''2834210''>color,</span>
  <span m=''2835680''>because</span> <span m=''2835970''>pn</span> <span m=''2836320''>is</span>
  <span m=''2836440''>true.</span> <span m=''2837340''>There are</span> <span m=''2837460''>a</span>
  <span m=''2837840''>set</span> <span m=''2838030''>of</span> <span m=''2838100''>n
  horses.</span> <span m=''2839290''>By</span> <span m=''2839730''>p1</span> <span
  m=''2840260''>they''re</span> <span m=''2840400''>all</span> <span m=''2840500''>the</span>
  <span m=''2840580''>same</span> <span m=''2840800''>color.</span> </p><p><span m=''2851810''>Also,</span>
  <span m=''2854340''>what</span> <span m=''2854560''>do</span> <span m=''2854640''>I</span>
  <span m=''2854710''>know</span> <span m=''2854930''>but</span> <span m=''2855170''>h2,</span>
  <span m=''2856570''>h3</span> <span m=''2858725''>and</span> <span m=''2859156''>hn</span>
  <span m=''2859590''>plus</span> <span m=''2859860''>1?</span> <span m=''2862310''>All</span>
  <span m=''2862550''>the</span> <span m=''2862640''>same</span> <span m=''2862860''>color,</span>
  <span m=''2863180''>because</span> <span m=''2863360''>they''re</span> <span m=''2863490''>a</span>
  <span m=''2863550''>set</span> <span m=''2863830''>of</span> <span m=''2864010''>n</span>
  <span m=''2864170''>horses.</span> <span m=''2868430''>All</span> <span m=''2868510''>right.</span>
  <span m=''2871170''>Well,</span> <span m=''2874700''>since</span> <span m=''2877020''>the</span>
  <span m=''2877160''>color</span> <span m=''2877510''>of</span> <span m=''2877580''>h1</span>
  <span m=''2881292''>equals</span> <span m=''2881760''>the</span> <span m=''2881860''>color</span>
  <span m=''2882320''>of</span> <span m=''2882820''>those</span> <span m=''2883110''>guys,</span>
  <span m=''2886080''>h2</span> <span m=''2887242''>to</span> <span m=''2887640''>hn,</span>
  <span m=''2889430''>I</span> <span m=''2889540''>know</span> <span m=''2889770''>h1</span>
  <span m=''2890180''>is</span> <span m=''2890270''>the</span> <span m=''2890350''>same</span>
  <span m=''2890560''>color</span> <span m=''2890920''>as these</span> <span m=''2891160''>guys.</span>
  <span m=''2892560''>I</span> <span m=''2892700''>also</span> <span m=''2892930''>know</span>
  <span m=''2893060''>that</span> <span m=''2893190''>hn</span> <span m=''2893610''>plus</span>
  <span m=''2893830''>1</span> <span m=''2894120''>is</span> <span m=''2894210''>the</span>
  <span m=''2894300''>same</span> <span m=''2894560''>color</span> <span m=''2894870''>as</span>
  <span m=''2894980''>those</span> <span m=''2895210''>guys.</span> </p><p><span m=''2902990''>That</span>
  <span m=''2903220''>means</span> <span m=''2903520''>that</span> <span m=''2903990''>h1</span>
  <span m=''2904460''>is the</span> <span m=''2904540''>same</span> <span m=''2904800''>color</span>
  <span m=''2905060''>as</span> <span m=''2905170''>hn</span> <span m=''2905500''>plus</span>
  <span m=''2905750''>1.</span> <span m=''2907440''>And</span> <span m=''2907640''>all</span>
  <span m=''2907840''>n</span> <span m=''2907970''>plus</span> <span m=''2908210''>1</span>
  <span m=''2908420''>are</span> <span m=''2908460''>the</span> <span m=''2908540''>same</span>
  <span m=''2908790''>color.</span> <span m=''2918410''>And</span> <span m=''2918620''>that''s</span>
  <span m=''2918820''>pn</span> <span m=''2919120''>plus</span> <span m=''2919330''>1.</span>
  <span m=''2922460''>That</span> <span m=''2922710''>implies</span> <span m=''2923140''>pn</span>
  <span m=''2923390''>plus</span> <span m=''2923610''>1.</span> <span m=''2925660''>And</span>
  <span m=''2925880''>I''m</span> <span m=''2925980''>done.</span> <span m=''2929820''>Now</span>
  <span m=''2930760''>a</span> <span m=''2930820''>few</span> <span m=''2931040''>years</span>
  <span m=''2931400''>ago</span> <span m=''2932070''>we</span> <span m=''2932270''>assigned</span>
  <span m=''2932630''>this</span> <span m=''2932790''>problem</span> <span m=''2933120''>as</span>
  <span m=''2933240''>homework.</span> <span m=''2934720''>And</span> <span m=''2934930''>we</span>
  <span m=''2935060''>asked</span> <span m=''2935260''>students</span> <span m=''2935620''>to</span>
  <span m=''2935720''>figure</span> <span m=''2936050''>out</span> <span m=''2936210''>what</span>
  <span m=''2936410''>went</span> <span m=''2936610''>wrong</span> <span m=''2936980''>with</span>
  <span m=''2937120''>the</span> <span m=''2937200''>problem.</span> <span m=''2937860''>Why</span>
  <span m=''2938490''>doesn''t</span> <span m=''2938740''>this</span> <span m=''2938870''>work?</span>
  </p><p><span m=''2939740''>And</span> <span m=''2940280''>the</span> <span m=''2940560''>responses</span>
  <span m=''2941160''>were</span> <span m=''2941310''>a</span> <span m=''2941360''>little</span>
  <span m=''2941700''>discouraging.</span> <span m=''2943230''>Half</span> <span m=''2943610''>the</span>
  <span m=''2943710''>class</span> <span m=''2944190''>responded,</span> <span m=''2945310''>effectively</span>
  <span m=''2946020''>as</span> <span m=''2946140''>follows,</span> <span m=''2946950''>this</span>
  <span m=''2947170''>example</span> <span m=''2947650''>just</span> <span m=''2947960''>goes</span>
  <span m=''2948180''>to</span> <span m=''2948270''>show</span> <span m=''2948590''>that</span>
  <span m=''2948740''>induction</span> <span m=''2949240''>doesn''t</span> <span m=''2949590''>always</span>
  <span m=''2949980''>work.</span> <span m=''2952560''>A</span> <span m=''2952670''>third</span>
  <span m=''2952950''>of</span> <span m=''2953000''>the</span> <span m=''2953100''>class</span>
  <span m=''2954080''>said,</span> <span m=''2955010''>I</span> <span m=''2955060''>always</span>
  <span m=''2955430''>knew</span> <span m=''2955660''>that you</span> <span m=''2955850''>can''t</span>
  <span m=''2956160''>trust</span> <span m=''2956470''>mathematics.</span> <span m=''2957390''>This</span>
  <span m=''2957680''>example</span> <span m=''2958210''>just</span> <span m=''2958780''>proves</span>
  <span m=''2959310''>it.</span> <span m=''2961140''>That</span> <span m=''2961310''>really</span>
  <span m=''2961530''>hurt.</span> </p><p><span m=''2963540''>And</span> <span m=''2963920''>most</span>
  <span m=''2964210''>of</span> <span m=''2964250''>the</span> <span m=''2964340''>rest</span>
  <span m=''2964640''>were</span> <span m=''2964800''>something</span> <span m=''2965260''>similar</span>
  <span m=''2965680''>to</span> <span m=''2965790''>that.</span> <span m=''2966930''>Not</span>
  <span m=''2967090''>exactly</span> <span m=''2967580''>what</span> <span m=''2967720''>we</span>
  <span m=''2967840''>were</span> <span m=''2967940''>looking</span> <span m=''2968260''>for</span>
  <span m=''2968650''>in</span> <span m=''2968750''>the</span> <span m=''2968820''>homework.</span>
  <span m=''2969180''>So</span> <span m=''2969300''>now</span> <span m=''2969560''>we</span>
  <span m=''2969940''>don''t</span> <span m=''2970300''>leave</span> <span m=''2970480''>it</span>
  <span m=''2970570''>to</span> <span m=''2970640''>homework.</span> <span m=''2971030''>We</span>
  <span m=''2971300''>do</span> <span m=''2971440''>it</span> <span m=''2971500''>in</span>
  <span m=''2971590''>class.</span> <span m=''2974110''>What''s</span> <span m=''2974490''>the</span>
  <span m=''2974600''>flaw</span> <span m=''2975000''>here?</span> <span m=''2977150''>What
  was</span> <span m=''2977360''>it?</span> </p><p><span m=''2978248''>AUDIENCE: P
  of n.</span> </p><p><span m=''2979580''>PROFESSOR: P of n?</span> <span m=''2979810''>What''s</span>
  <span m=''2979960''>wrong</span> <span m=''2980150''>with</span> <span m=''2980300''>p</span>
  <span m=''2980430''>of n?</span> </p><p><span m=''2981279''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''2985690''>PROFESSOR: No,</span> <span m=''2986190''>this</span>
  <span m=''2986430''>is</span> <span m=''2986510''>a</span> <span m=''2986580''>real</span>
  <span m=''2986900''>assumption</span> <span m=''2987380''>in</span> <span m=''2987590''>any</span>
  <span m=''2987910''>set</span> <span m=''2988340''>of</span> <span m=''2988480''>n</span>
  <span m=''2988680''>horses--</span> <span m=''2990600''>depends</span> <span m=''2990880''>on</span>
  <span m=''2991020''>n--</span> <span m=''2991650''>the</span> <span m=''2991750''>horses</span>
  <span m=''2992170''>are</span> <span m=''2992280''>all</span> <span m=''2992420''>the</span>
  <span m=''2992500''>same</span> <span m=''2992750''>color.</span> <span m=''2993150''>That</span>
  <span m=''2993400''>is</span> <span m=''2993670''>a</span> <span m=''2994430''>proposition.</span>
  <span m=''2995730''>Because</span> <span m=''2995960''>it</span> <span m=''2996020''>depends</span>
  <span m=''2996270''>on</span> <span m=''2996400''>n,</span> <span m=''2996510''>it''s</span>
  <span m=''2996630''>a</span> <span m=''2996680''>predicate.</span> <span m=''2998340''>It''s</span>
  <span m=''2998530''>true</span> <span m=''2998870''>or it''s</span> <span m=''2999040''>false.</span>
  <span m=''3000990''>Now</span> <span m=''3001470''>we</span> <span m=''3001590''>know</span>
  <span m=''3001790''>it''s</span> <span m=''3001920''>false,</span> <span m=''3003030''>because</span>
  <span m=''3003200''>you</span> <span m=''3003310''>could</span> <span m=''3003480''>get</span>
  <span m=''3003620''>a</span> <span m=''3003690''>set</span> <span m=''3003890''>of</span>
  <span m=''3004285''>a</span> <span m=''3004550''>couple</span> <span m=''3004840''>horses</span>
  <span m=''3005220''>with</span> <span m=''3005350''>different</span> <span m=''3005600''>color.</span>
  <span m=''3006670''>But</span> <span m=''3006820''>it</span> <span m=''3006900''>is</span>
  <span m=''3007050''>a</span> <span m=''3007100''>proposition.</span> </p><p><span
  m=''3007740''>Yeah,</span> <span m=''3007940''>way</span> <span m=''3008050''>back</span>
  <span m=''3008250''>there?</span> </p><p><span m=''3010640''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''3011450''>for like a</span> <span m=''3011780''>certain</span> <span m=''3012200''>set
  of</span> <span m=''3012550''>horses.</span> <span m=''3013840''>So</span> <span
  m=''3014260''>even</span> <span m=''3014680''>though it''s</span> <span m=''3015100''>the
  same number</span> <span m=''3015520''>of horses,</span> <span m=''3015940''>so
  it</span> <span m=''3016320''>was</span> <span m=''3016785''>the</span> <span m=''3017250''>same</span>
  <span m=''3018686''>number as</span> <span m=''3019174''>a different</span> <span
  m=''3019662''>set of</span> <span m=''3020150''>horses</span> <span m=''3020638''>it''s</span>
  <span m=''3021126''>not something</span> <span m=''3021614''>you can</span> <span
  m=''3022102''>assume</span> <span m=''3022590''>anymore.</span> </p><p><span m=''3023570''>PROFESSOR:
  That''s</span> <span m=''3023800''>a</span> <span m=''3023860''>great</span> <span
  m=''3024190''>point.</span> <span m=''3024410''>I</span> <span m=''3024480''>did</span>
  <span m=''3024830''>gloss</span> <span m=''3025240''>over</span> <span m=''3025570''>something</span>
  <span m=''3025970''>here,</span> <span m=''3026870''>because</span> <span m=''3027400''>in</span>
  <span m=''3027660''>the</span> <span m=''3027760''>predicate</span> <span m=''3028450''>I''ve</span>
  <span m=''3028610''>got</span> <span m=''3029310''>"in</span> <span m=''3029660''>any</span>
  <span m=''3029990''>set."</span> <span m=''3030860''>So</span> <span m=''3031050''>there''s</span>
  <span m=''3031230''>really</span> <span m=''3031740''>a</span> <span m=''3032210''>"for</span>
  <span m=''3032680''>all</span> <span m=''3033010''>sets"</span> <span m=''3033660''>sitting</span>
  <span m=''3033980''>out</span> <span m=''3034130''>here.</span> <span m=''3035040''>So</span>
  <span m=''3035060''>I''ve</span> <span m=''3035150''>going</span> <span m=''3035280''>to</span>
  <span m=''3035330''>be</span> <span m=''3035440''>careful</span> <span m=''3035890''>that</span>
  <span m=''3036000''>I</span> <span m=''3036140''>establish</span> <span m=''3036810''>that</span>
  <span m=''3037230''>when</span> <span m=''3037360''>I''m</span> <span m=''3038230''>trying</span>
  <span m=''3038530''>to</span> <span m=''3038700''>prove</span> <span m=''3038960''>pn</span>
  <span m=''3039930''>implies</span> <span m=''3040350''>pn</span> <span m=''3040590''>plus</span>
  <span m=''3040800''>1.</span> <span m=''3041080''>So</span> <span m=''3042040''>to</span>
  <span m=''3042160''>establish</span> <span m=''3042640''>pn</span> <span m=''3042910''>plus</span>
  <span m=''3043110''>1</span> <span m=''3043330''>here,</span> <span m=''3043450''>I</span>
  <span m=''3043520''>assume</span> <span m=''3043810''>pn</span> <span m=''3044160''>which</span>
  <span m=''3044310''>means</span> <span m=''3044540''>in</span> <span m=''3044660''>any</span>
  <span m=''3044960''>set</span> <span m=''3045180''>of</span> <span m=''3045260''>n</span>
  <span m=''3045370''>horses</span> <span m=''3045710''>they''re</span> <span m=''3046050''>all</span>
  <span m=''3046220''>the</span> <span m=''3046340''>same</span> <span m=''3046530''>color.</span>
  <span m=''3046860''>That</span> <span m=''3047060''>I''m</span> <span m=''3047190''>given.</span>
  <span m=''3047910''>That''s</span> <span m=''3048100''>pn.</span> </p><p><span m=''3048840''>I''ve</span>
  <span m=''3049210''>got</span> <span m=''3049330''>to</span> <span m=''3049400''>look</span>
  <span m=''3049590''>at</span> <span m=''3049790''>any</span> <span m=''3050270''>set</span>
  <span m=''3051300''>of</span> <span m=''3051440''>n</span> <span m=''3051580''>plus</span>
  <span m=''3051800''>1</span> <span m=''3051980''>horses.</span> <span m=''3052500''>So</span>
  <span m=''3052650''>consider</span> <span m=''3053590''>any</span> <span m=''3053880''>set,</span>
  <span m=''3055180''>not</span> <span m=''3055380''>a</span> <span m=''3055550''>set,</span>
  <span m=''3055830''>any</span> <span m=''3056110''>set</span> <span m=''3056910''>of</span>
  <span m=''3057030''>n</span> <span m=''3057160''>plus</span> <span m=''3057370''>1</span>
  <span m=''3057530''>horses.</span> <span m=''3058270''>So you</span> <span m=''3058470''>pick</span>
  <span m=''3058700''>any</span> <span m=''3058870''>set</span> <span m=''3059080''>you</span>
  <span m=''3059180''>want.</span> <span m=''3060060''>Call them</span> <span m=''3060470''>this,</span>
  <span m=''3061600''>h1</span> <span m=''3062050''>through</span> <span m=''3062280''>hn
  plus</span> <span m=''3062780''>1.</span> <span m=''3063870''>Well</span> <span
  m=''3064420''>then,</span> <span m=''3064820''>the</span> <span m=''3064910''>first</span>
  <span m=''3065260''>n</span> <span m=''3065740''>are</span> <span m=''3066200''>a</span>
  <span m=''3066310''>set</span> <span m=''3066660''>of</span> <span m=''3066810''>n</span>
  <span m=''3066950''>horses,</span> <span m=''3067420''>so</span> <span m=''3067530''>I</span>
  <span m=''3067590''>can</span> <span m=''3067720''>apply</span> <span m=''3068030''>pn,</span>
  <span m=''3068900''>therefore</span> <span m=''3069220''>they</span> <span m=''3069330''>have</span>
  <span m=''3069510''>the</span> <span m=''3069580''>same</span> <span m=''3069810''>color.</span>
  </p><p><span m=''3071290''>The</span> <span m=''3071410''>last</span> <span m=''3071840''>n</span>
  <span m=''3072060''>horses</span> <span m=''3072450''>in</span> <span m=''3072500''>the</span>
  <span m=''3072580''>set</span> <span m=''3073240''>are</span> <span m=''3073470''>a</span>
  <span m=''3073520''>set</span> <span m=''3073720''>of n</span> <span m=''3073900''>horses,</span>
  <span m=''3074860''>so</span> <span m=''3075010''>I</span> <span m=''3075070''>can
  imply</span> <span m=''3075460''>pn.</span> <span m=''3076590''>So</span> <span
  m=''3076770''>these</span> <span m=''3077000''>guys</span> <span m=''3077260''>all</span>
  <span m=''3077490''>have</span> <span m=''3077630''>the</span> <span m=''3077700''>same</span>
  <span m=''3077940''>color,</span> <span m=''3078570''>and</span> <span m=''3078790''>I''m</span>
  <span m=''3078980''>on</span> <span m=''3079070''>my</span> <span m=''3079180''>merry</span>
  <span m=''3079490''>way</span> <span m=''3079750''>here.</span> <span m=''3080810''>So</span>
  <span m=''3080940''>you''re</span> <span m=''3081120''>right,</span> <span m=''3081360''>I</span>
  <span m=''3081420''>had</span> <span m=''3081690''>to</span> <span m=''3081780''>do</span>
  <span m=''3082000''>a</span> <span m=''3082060''>little</span> <span m=''3082250''>bit</span>
  <span m=''3082380''>more</span> <span m=''3082620''>work,</span> <span m=''3083800''>but</span>
  <span m=''3083930''>I</span> <span m=''3083990''>can</span> <span m=''3084150''>do</span>
  <span m=''3084280''>that</span> <span m=''3084480''>work</span> <span m=''3085080''>and</span>
  <span m=''3085160''>I</span> <span m=''3085220''>still</span> <span m=''3085440''>get</span>
  <span m=''3085560''>a proof.</span> <span m=''3086660''>Yeah?</span> </p><p><span
  m=''3088114''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''3089560''>PROFESSOR:
  Good</span> <span m=''3089720''>question.</span> <span m=''3089970''>Is</span> <span
  m=''3090080''>there a</span> <span m=''3090140''>problem</span> <span m=''3090430''>with</span>
  <span m=''3090480''>the</span> <span m=''3090560''>base</span> <span m=''3090980''>case?</span>
  <span m=''3091950''>So</span> <span m=''3092140''>my</span> <span m=''3092270''>base</span>
  <span m=''3092640''>case</span> <span m=''3093180''>was</span> <span m=''3094110''>here,</span>
  <span m=''3095020''>n</span> <span m=''3095210''>equals</span> <span m=''3095500''>1.</span>
  <span m=''3097270''>In</span> <span m=''3097480''>any</span> <span m=''3097740''>set</span>
  <span m=''3098030''>of</span> <span m=''3098160''>one</span> <span m=''3098440''>horse,</span>
  <span m=''3098920''>the</span> <span m=''3099010''>horses--</span> <span m=''3100490''>let''s</span>
  <span m=''3100700''>say</span> <span m=''3101380''>in</span> <span m=''3101630''>the</span>
  <span m=''3101720''>set</span> <span m=''3102060''>just</span> <span m=''3102150''>to</span>
  <span m=''3102230''>be</span> <span m=''3102330''>really</span> <span m=''3104350''>careful--</span>
  <span m=''3106450''>are</span> <span m=''3106620''>all</span> <span m=''3106800''>the</span>
  <span m=''3106860''>same</span> <span m=''3107110''>color.</span> <span m=''3107960''>No,</span>
  <span m=''3108180''>in</span> <span m=''3108290''>any</span> <span m=''3108490''>set</span>
  <span m=''3108720''>of</span> <span m=''3108810''>one</span> <span m=''3109020''>horses</span>
  <span m=''3110430''>there''s</span> <span m=''3110580''>only</span> <span m=''3110730''>one</span>
  <span m=''3110880''>horse,</span> <span m=''3111100''>so</span> <span m=''3111310''>it''s</span>
  <span m=''3111450''>the</span> <span m=''3111540''>same</span> <span m=''3111780''>color
  as</span> <span m=''3112170''>itself.</span> <span m=''3113080''>Yeah?</span> </p><p><span
  m=''3114504''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''3117780''>PROFESSOR:
  n</span> <span m=''3118180''>plus</span> <span m=''3118350''>1</span> <span m=''3118480''>is</span>
  <span m=''3118580''>not</span> <span m=''3118840''>the</span> <span m=''3118930''>same</span>
  <span m=''3119200''>as n,</span> <span m=''3119674''>yeah.</span> </p><p><span m=''3120622''>AUDIENCE:
  [INAUDIBLE].</span> <span m=''3122088''>So you</span> <span m=''3122556''>can''t</span>
  <span m=''3123024''>have the</span> <span m=''3123492''>same assumption</span> <span
  m=''3124896''>because it''s</span> <span m=''3125364''>not</span> <span m=''3125832''>a
  set</span> <span m=''3126300''>of n horses.</span> <span m=''3126768''>It''s</span>
  <span m=''3127236''>a set of n</span> <span m=''3127704''>plus 1?</span> </p><p><span
  m=''3128650''>PROFESSOR: Well,</span> <span m=''3129150''>let''s</span> <span m=''3129380''>see.</span>
  <span m=''3129520''>So</span> <span m=''3129820''>you''re</span> <span m=''3130090''>arguing</span>
  <span m=''3130360''>I</span> <span m=''3130390''>made</span> <span m=''3130560''>a</span>
  <span m=''3130590''>mistake</span> <span m=''3130930''>here,</span> <span m=''3131270''>right?</span>
  <span m=''3132700''>Well,</span> <span m=''3133710''>I''ve</span> <span m=''3133880''>got</span>
  <span m=''3134040''>horses--</span> <span m=''3134630''>horse</span> <span m=''3134870''>2,</span>
  <span m=''3135190''>3,</span> <span m=''3135510''>up</span> <span m=''3135590''>to</span>
  <span m=''3135670''>n</span> <span m=''3135810''>plus</span> <span m=''3136020''>1.</span>
  <span m=''3136230''>How</span> <span m=''3136400''>many</span> <span m=''3136550''>horses</span>
  <span m=''3137070''>are</span> <span m=''3137190''>in</span> <span m=''3137310''>this</span>
  <span m=''3137530''>set</span> <span m=''3137750''>here?</span> </p><p><span m=''3140640''>AUDIENCE:
  Oh,</span> <span m=''3140915''>in</span> <span m=''3141190''>that</span> <span m=''3141420''>set?</span>
  </p><p><span m=''3141820''>PROFESSOR: In</span> <span m=''3142030''>this</span>
  <span m=''3142330''>set.</span> <span m=''3142760''>How many horses</span> <span
  m=''3143160''>are</span> <span m=''3143280''>there?</span> </p><p><span m=''3144540''>AUDIENCE:
  N.</span> </p><p><span m=''3144900''>PROFESSOR: N.</span> <span m=''3145590''>So</span>
  <span m=''3145740''>I</span> <span m=''3145810''>can</span> <span m=''3145940''>apply</span>
  <span m=''3146340''>p</span> <span m=''3146630''>of</span> <span m=''3146710''>n</span>
  <span m=''3146890''>to</span> <span m=''3146990''>this</span> <span m=''3147390''>set</span>
  <span m=''3147630''>just</span> <span m=''3147930''>the</span> <span m=''3148020''>same</span>
  <span m=''3148270''>as</span> <span m=''3148360''>that</span> <span m=''3148570''>set,</span>
  <span m=''3148760''>because</span> <span m=''3148870''>p</span> <span m=''3149010''>of</span>
  <span m=''3149070''>n</span> <span m=''3149180''>is</span> <span m=''3149570''>any</span>
  <span m=''3149880''>set</span> <span m=''3150180''>of n horses.</span> <span m=''3151290''>Well,</span>
  <span m=''3151490''>I''m</span> <span m=''3151660''>picking</span> <span m=''3151930''>this</span>
  <span m=''3152100''>one</span> <span m=''3152260''>now</span> <span m=''3152935''>and</span>
  <span m=''3153310''>applying</span> <span m=''3153720''>pn</span> <span m=''3154060''>to</span>
  <span m=''3154240''>it.</span> <span m=''3155410''>And</span> <span m=''3155560''>so</span>
  <span m=''3155670''>therefore</span> <span m=''3155990''>they''re</span> <span m=''3156150''>all</span>
  <span m=''3156280''>the</span> <span m=''3156340''>same</span> <span m=''3156540''>color.</span>
  <span m=''3159760''>Yeah?</span> </p><p><span m=''3161646''>AUDIENCE: H1,</span>
  <span m=''3162128''>h2,</span> <span m=''3162610''>dot, dot,</span> <span m=''3163092''>dot.</span>
  </p><p><span m=''3164060''>PROFESSOR: Yes.</span> </p><p><span m=''3165450''>AUDIENCE:
  Because</span> <span m=''3165944''>it does</span> <span m=''3166438''>work</span>
  <span m=''3166932''>it there''s</span> <span m=''3167426''>two</span> <span m=''3167920''>or
  more,</span> <span m=''3168414''>but you didn''t</span> <span m=''3168908''>prove</span>
  <span m=''3169402''>it with just</span> <span m=''3169896''>one--</span> <span m=''3170390''>or
  from</span> <span m=''3170884''>one to</span> <span m=''3171378''>two.</span> </p><p><span
  m=''3172370''>PROFESSOR: Exactly.</span> <span m=''3173175''>Remember</span> <span
  m=''3173540''>I told you</span> <span m=''3173590''>that</span> <span m=''3173810''>dot,</span>
  <span m=''3174070''>dot,</span> <span m=''3174320''>dot</span> <span m=''3174585''>is</span>
  <span m=''3174850''>so</span> <span m=''3175020''>reasonable,</span> <span m=''3176700''>so</span>
  <span m=''3176900''>easy</span> <span m=''3177210''>to</span> <span m=''3177260''>use.</span>
  <span m=''3177740''>Everybody</span> <span m=''3178140''>uses</span> <span m=''3178440''>it.</span>
  <span m=''3178540''>It was</span> <span m=''3178670''>going</span> <span m=''3178790''>to</span>
  <span m=''3179260''>catch</span> <span m=''3179560''>us</span> <span m=''3179700''>up.</span>
  <span m=''3180440''>The</span> <span m=''3180550''>bug</span> <span m=''3180830''>is
  in the</span> <span m=''3181270''>dot,</span> <span m=''3181540''>dot,</span> <span
  m=''3182010''>dot.</span> <span m=''3182420''>And</span> <span m=''3182570''>in</span>
  <span m=''3182640''>particular,</span> <span m=''3183310''>it</span> <span m=''3184340''>has</span>
  <span m=''3184630''>to</span> <span m=''3184720''>do</span> <span m=''3184950''>with</span>
  <span m=''3185080''>the</span> <span m=''3185180''>case</span> <span m=''3186350''>n</span>
  <span m=''3187280''>equal</span> <span m=''3188740''>2.</span> <span m=''3189150''>So</span>
  <span m=''3189260''>there''s</span> <span m=''3189390''>two</span> <span m=''3189540''>ways</span>
  <span m=''3189770''>to</span> <span m=''3189820''>look</span> <span m=''3189960''>at</span>
  <span m=''3190010''>the</span> <span m=''3190090''>bug,</span> <span m=''3190400''>dot,</span>
  <span m=''3190610''>dot,</span> <span m=''3190800''>dot,</span> <span m=''3191480''>or</span>
  <span m=''3191840''>we</span> <span m=''3191990''>didn''t</span> <span m=''3192710''>completely</span>
  <span m=''3193580''>do</span> <span m=''3193780''>all</span> <span m=''3193950''>the</span>
  <span m=''3194070''>inductive</span> <span m=''3194500''>steps.</span> </p><p><span
  m=''3196090''>So</span> <span m=''3196270''>let''s</span> <span m=''3196610''>look</span>
  <span m=''3196830''>at</span> <span m=''3196900''>the</span> <span m=''3197010''>case--</span>
  <span m=''3198680''>actually</span> <span m=''3199030''>it''s</span> <span m=''3199160''>the</span>
  <span m=''3199210''>case</span> <span m=''3199540''>n</span> <span m=''3199680''>equals</span>
  <span m=''3199950''>1,</span> <span m=''3202800''>here,</span> <span m=''3203500''>in</span>
  <span m=''3203630''>this</span> <span m=''3203820''>inductive</span> <span m=''3204210''>step.</span>
  <span m=''3205090''>Did</span> <span m=''3205300''>I</span> <span m=''3205400''>prove</span>
  <span m=''3206590''>p1</span> <span m=''3207580''>implies</span> <span m=''3208220''>p2?</span>
  <span m=''3210780''>Let''s</span> <span m=''3211180''>just</span> <span m=''3211460''>double</span>
  <span m=''3211720''>check</span> <span m=''3212000''>that</span> <span m=''3212170''>worked</span>
  <span m=''3212430''>for</span> <span m=''3212550''>n</span> <span m=''3212630''>equals</span>
  <span m=''3212880''>1.</span> <span m=''3220630''>n</span> <span m=''3220770''>equals</span>
  <span m=''3221120''>1.</span> <span m=''3222066''>I''ve</span> <span m=''3222540''>got</span>
  <span m=''3222740''>a</span> <span m=''3222800''>set</span> <span m=''3223650''>of</span>
  <span m=''3224900''>two</span> <span m=''3225290''>horses.</span> <span m=''3226030''>This</span>
  <span m=''3226280''>becomes</span> <span m=''3226680''>2.</span> <span m=''3228360''>So</span>
  <span m=''3228470''>I''ve</span> <span m=''3228570''>got</span> <span m=''3228820''>h1,</span>
  <span m=''3229380''>h2.</span> <span m=''3231640''>Nothing</span> <span m=''3231950''>in</span>
  <span m=''3232030''>the</span> <span m=''3232110''>dot,</span> <span m=''3232320''>dot,</span>
  <span m=''3232520''>dot.</span> <span m=''3232750''>It''s</span> <span m=''3232860''>just</span>
  <span m=''3233060''>h1</span> <span m=''3233240''>and</span> <span m=''3233480''>h2.</span>
  </p><p><span m=''3235310''>Then</span> <span m=''3237330''>this</span> <span m=''3237780''>becomes</span>
  <span m=''3239410''>h1.</span> <span m=''3241570''>So</span> <span m=''3241730''>sure</span>
  <span m=''3241950''>enough,</span> <span m=''3242180''>h1</span> <span m=''3242650''>is</span>
  <span m=''3242750''>the</span> <span m=''3242830''>same</span> <span m=''3243060''>color
  as</span> <span m=''3243400''>itself.</span> <span m=''3244260''>This</span> <span
  m=''3244630''>becomes--</span> <span m=''3245660''>what</span> <span m=''3245790''>does</span>
  <span m=''3245890''>this</span> <span m=''3246040''>become,</span> <span m=''3246360''>this</span>
  <span m=''3246450''>set</span> <span m=''3246630''>of</span> <span m=''3246720''>horses?</span>
  <span m=''3247170''>What</span> <span m=''3247220''>is</span> <span m=''3247320''>it</span>
  <span m=''3247400''>really?</span> <span m=''3248990''>h2.</span> <span m=''3251590''>All</span>
  <span m=''3251770''>right,</span> <span m=''3252350''>so</span> <span m=''3252460''>I''ve</span>
  <span m=''3252540''>got</span> <span m=''3252700''>the</span> <span m=''3252780''>color</span>
  <span m=''3253120''>of h1</span> <span m=''3253190''>equals</span> <span m=''3253940''>the</span>
  <span m=''3254030''>color</span> <span m=''3254430''>of--</span> <span m=''3255940''>oh</span>
  <span m=''3256190''>man,</span> <span m=''3256380''>this</span> <span m=''3256550''>is</span>
  <span m=''3256630''>so</span> <span m=''3256810''>hard</span> <span m=''3257020''>to</span>
  <span m=''3257090''>see</span> <span m=''3257240''>this</span> <span m=''3257430''>bug.</span>
  <span m=''3258850''>I</span> <span m=''3258970''>wrote</span> <span m=''3259210''>down</span>
  <span m=''3259440''>h2</span> <span m=''3260170''>dot,</span> <span m=''3260350''>dot,</span>
  <span m=''3260490''>dot,</span> <span m=''3260690''>to</span> <span m=''3260760''>hn</span>
  <span m=''3261260''>because--</span> <span m=''3263140''>take</span> <span m=''3263400''>out</span>
  <span m=''3263550''>h1,</span> <span m=''3265510''>what''s</span> <span m=''3265840''>left?</span>
  <span m=''3266410''>What''s</span> <span m=''3266610''>left</span> <span m=''3266800''>is</span>
  <span m=''3266910''>h2</span> <span m=''3267070''>through</span> <span m=''3267220''>hn.</span>
  </p><p><span m=''3268550''>But</span> <span m=''3268700''>this</span> <span m=''3268850''>set</span>
  <span m=''3269030''>is</span> <span m=''3269150''>only</span> <span m=''3269390''>h1.</span>
  <span m=''3269870''>What''s</span> <span m=''3270170''>really</span> <span m=''3270420''>left</span>
  <span m=''3270690''>here?</span> <span m=''3270830''>What</span> <span m=''3271000''>is</span>
  <span m=''3271150''>this</span> <span m=''3271280''>set?</span> <span m=''3274400''>What</span>
  <span m=''3274610''>is</span> <span m=''3274770''>this</span> <span m=''3274980''>set?</span>
  <span m=''3279980''>h2,</span> <span m=''3280620''>h1?</span> <span m=''3281962''>No.</span>
  <span m=''3283450''>You</span> <span m=''3283520''>see,</span> <span m=''3283910''>what</span>
  <span m=''3284100''>is</span> <span m=''3284220''>the</span> <span m=''3284310''>whole</span>
  <span m=''3284600''>set?</span> <span m=''3284830''>h1,</span> <span m=''3285040''>dot,</span>
  <span m=''3285300''>dot,</span> <span m=''3285560''>dot,</span> <span m=''3285750''>hn.</span>
  <span m=''3286110''>What</span> <span m=''3286240''>is</span> <span m=''3286320''>the</span>
  <span m=''3286400''>whole</span> <span m=''3286660''>thing?</span> <span m=''3286870''>It''s</span>
  <span m=''3286960''>just</span> <span m=''3287190''>h1.</span> <span m=''3288930''>pull</span>
  <span m=''3289370''>out h1</span> <span m=''3289800''>and</span> <span m=''3289840''>look</span>
  <span m=''3290010''>at</span> <span m=''3290060''>the</span> <span m=''3290150''>rest</span>
  <span m=''3290420''>of</span> <span m=''3290510''>it,</span> <span m=''3292950''>how</span>
  <span m=''3293110''>many</span> <span m=''3293250''>horses</span> <span m=''3293690''>are</span>
  <span m=''3294000''>here?</span> <span m=''3295600''>0</span> <span m=''3296240''>horses.</span>
  </p><p><span m=''3299240''>This</span> <span m=''3299730''>is</span> <span m=''3299880''>the</span>
  <span m=''3300070''>empty</span> <span m=''3300350''>set.</span> <span m=''3301120''>There</span>
  <span m=''3301310''>are</span> <span m=''3301430''>no</span> <span m=''3301790''>horses</span>
  <span m=''3302280''>here</span> <span m=''3302460''>to</span> <span m=''3302530''>compare</span>
  <span m=''3302930''>to.</span> <span m=''3304560''>Even</span> <span m=''3304770''>though</span>
  <span m=''3304840''>I</span> <span m=''3304920''>got</span> <span m=''3305150''>an
  h2,</span> <span m=''3306130''>I</span> <span m=''3306200''>got</span> <span m=''3306340''>an</span>
  <span m=''3306430''>hn,</span> <span m=''3306775''>I got a</span> <span m=''3307120''>dot,
  dot,</span> <span m=''3307320''>dot.</span> <span m=''3308220''>Because</span> <span
  m=''3309050''>generally,</span> <span m=''3309510''>if n is</span> <span m=''3309880''>big,</span>
  <span m=''3311550''>this</span> <span m=''3311770''>has</span> <span m=''3312350''>n</span>
  <span m=''3312550''>minus</span> <span m=''3312860''>1</span> <span m=''3313010''>horses</span>
  <span m=''3313410''>are</span> <span m=''3313490''>here.</span> <span m=''3313870''>There''s</span>
  <span m=''3314060''>n</span> <span m=''3314330''>total.</span> <span m=''3315310''>I</span>
  <span m=''3315420''>got</span> <span m=''3315590''>n</span> <span m=''3315720''>minus</span>
  <span m=''3316030''>1</span> <span m=''3316200''>right</span> <span m=''3316460''>here.</span>
  <span m=''3318120''>But</span> <span m=''3318240''>n</span> <span m=''3318360''>minus</span>
  <span m=''3318630''>1</span> <span m=''3318860''>is</span> <span m=''3319080''>0.</span>
  <span m=''3320280''>There</span> <span m=''3320490''>are</span> <span m=''3320600''>no</span>
  <span m=''3321030''>horses</span> <span m=''3321450''>here.</span> <span m=''3322680''>And</span>
  <span m=''3322880''>so this</span> <span m=''3323160''>bridge</span> <span m=''3323530''>in
  the</span> <span m=''3323730''>equality</span> <span m=''3324200''>totally</span>
  <span m=''3324550''>breaks.</span> </p><p><span m=''3327220''>I</span> <span m=''3327440''>got</span>
  <span m=''3327690''>color</span> <span m=''3327990''>of</span> <span m=''3328060''>h1
  equals--</span> <span m=''3330240''>there''s</span> <span m=''3330440''>no</span>
  <span m=''3330640''>information</span> <span m=''3331130''>here--</span> <span m=''3331910''>equals</span>
  <span m=''3332200''>the</span> <span m=''3332290''>color</span> <span m=''3332770''>of</span>
  <span m=''3332900''>h2.</span> <span m=''3334040''>There''s</span> <span m=''3334210''>no</span>
  <span m=''3334440''>equality</span> <span m=''3335050''>here,</span> <span m=''3335260''>because</span>
  <span m=''3335430''>there''s</span> <span m=''3335590''>no</span> <span m=''3335750''>horses</span>
  <span m=''3336130''>in</span> <span m=''3336210''>this</span> <span m=''3336440''>set,</span>
  <span m=''3337660''>all</span> <span m=''3337850''>because</span> <span m=''3338120''>of</span>
  <span m=''3338160''>that</span> <span m=''3338330''>dot,</span> <span m=''3338550''>dot,</span>
  <span m=''3338750''>dot.</span> <span m=''3339380''>Do you</span> <span m=''3339520''>see</span>
  <span m=''3339790''>where</span> <span m=''3339920''>the</span> <span m=''3340300''>problem</span>
  <span m=''3340700''>is</span> <span m=''3341070''>by</span> <span m=''3341160''>using</span>
  <span m=''3341360''>the</span> <span m=''3341440''>dot,</span> <span m=''3341640''>dot,</span>
  <span m=''3341830''>dot?</span> </p><p><span m=''3343360''>For</span> <span m=''3343440''>the</span>
  <span m=''3343530''>case</span> <span m=''3343790''>n</span> <span m=''3343940''>equals--</span>
  <span m=''3344320''>it</span> <span m=''3344390''>was</span> <span m=''3344510''>true</span>
  <span m=''3344900''>for</span> <span m=''3345090''>every</span> <span m=''3345450''>other</span>
  <span m=''3345620''>case</span> <span m=''3345980''>of</span> <span m=''3346080''>n.</span>
  <span m=''3346912''>n</span> <span m=''3347330''>equals</span> <span m=''3347570''>2,</span>
  <span m=''3347780''>n</span> <span m=''3347870''>equals</span> <span m=''3348090''>3,</span>
  <span m=''3348290''>it''s</span> <span m=''3348450''>all</span> <span m=''3348630''>true.</span>
  <span m=''3351240''>In</span> <span m=''3351340''>fact,</span> <span m=''3352410''>what</span>
  <span m=''3352470''>we</span> <span m=''3352610''>proved,</span> <span m=''3353240''>we</span>
  <span m=''3353420''>proved</span> <span m=''3353670''>the</span> <span m=''3353730''>base</span>
  <span m=''3354070''>case</span> <span m=''3354460''>of</span> <span m=''3354630''>p1</span>
  <span m=''3355360''>is</span> <span m=''3355450''>true.</span> <span m=''3357030''>This</span>
  <span m=''3357420''>is</span> <span m=''3357520''>an</span> <span m=''3357610''>argument</span>
  <span m=''3358000''>that</span> <span m=''3358090''>p2</span> <span m=''3358640''>implies</span>
  <span m=''3359030''>p3.</span> <span m=''3359610''>That</span> <span m=''3359780''>is</span>
  <span m=''3359900''>true.</span> <span m=''3361790''>p3</span> <span m=''3363890''>implies</span>
  <span m=''3364340''>p4,</span> <span m=''3365120''>that</span> <span m=''3365310''>is</span>
  <span m=''3365420''>true.</span> <span m=''3366680''>And</span> <span m=''3366800''>so</span>
  <span m=''3367010''>forth.</span> </p><p><span m=''3368200''>We</span> <span m=''3368270''>proved</span>
  <span m=''3368690''>for</span> <span m=''3368860''>all</span> <span m=''3369160''>n</span>
  <span m=''3369400''>bigger</span> <span m=''3369670''>than or</span> <span m=''3369850''>equal</span>
  <span m=''3370070''>to</span> <span m=''3370160''>2,</span> <span m=''3371050''>pn</span>
  <span m=''3372330''>implies</span> <span m=''3372830''>pn</span> <span m=''3373100''>plus</span>
  <span m=''3373360''>1.</span> <span m=''3373780''>That</span> <span m=''3373970''>we</span>
  <span m=''3374100''>proved.</span> <span m=''3375440''>What</span> <span m=''3375610''>is</span>
  <span m=''3375720''>the</span> <span m=''3375830''>one</span> <span m=''3376220''>missing</span>
  <span m=''3376630''>implication</span> <span m=''3377210''>we</span> <span m=''3377290''>did</span>
  <span m=''3377350''>not</span> <span m=''3377590''>prove?</span> <span m=''3380060''>The</span>
  <span m=''3380140''>missing</span> <span m=''3380690''>link,</span> <span m=''3381230''>p1</span>
  <span m=''3381780''>implies</span> <span m=''3382230''>p2.</span> <span m=''3384410''>We</span>
  <span m=''3384560''>did</span> <span m=''3384770''>not</span> <span m=''3385130''>prove</span>
  <span m=''3385390''>that.</span> <span m=''3386080''>Now</span> <span m=''3386250''>is</span>
  <span m=''3386440''>that</span> <span m=''3386660''>true?</span> <span m=''3388650''>No.</span>
  <span m=''3390350''>You can</span> <span m=''3390500''>find</span> <span m=''3390770''>a</span>
  <span m=''3390820''>set</span> <span m=''3390980''>of</span> <span m=''3391060''>two</span>
  <span m=''3391230''>horses</span> <span m=''3391610''>are</span> <span m=''3391700''>not</span>
  <span m=''3391870''>the</span> <span m=''3391930''>same</span> <span m=''3392170''>color.</span>
  <span m=''3393330''>And</span> <span m=''3393450''>just</span> <span m=''3393630''>because</span>
  <span m=''3393910''>every</span> <span m=''3394440''>horse</span> <span m=''3394800''>is</span>
  <span m=''3394900''>the</span> <span m=''3394970''>same</span> <span m=''3395180''>color</span>
  <span m=''3395480''>as itself,</span> <span m=''3395880''>does</span> <span m=''3396010''>not</span>
  <span m=''3396370''>give</span> <span m=''3396520''>you</span> <span m=''3396640''>that.</span>
  </p><p><span m=''3397400''>That</span> <span m=''3397780''>was</span> <span m=''3397900''>missing</span>
  <span m=''3398350''>in</span> <span m=''3398430''>this</span> <span m=''3398600''>proof.</span>
  <span m=''3399470''>And</span> <span m=''3399610''>so</span> <span m=''3399680''>we</span>
  <span m=''3399750''>have</span> <span m=''3399880''>to</span> <span m=''3399940''>be</span>
  <span m=''3400050''>really</span> <span m=''3400460''>careful</span> <span m=''3400890''>when</span>
  <span m=''3400980''>you''re</span> <span m=''3401070''>doing</span> <span m=''3401320''>these</span>
  <span m=''3401510''>proofs</span> <span m=''3402060''>that</span> <span m=''3402760''>you</span>
  <span m=''3402960''>establish</span> <span m=''3403510''>the</span> <span m=''3403620''>inductive</span>
  <span m=''3404100''>step</span> <span m=''3404460''>for</span> <span m=''3404600''>all</span>
  <span m=''3405070''>n</span> <span m=''3405380''>bigger</span> <span m=''3405620''>than</span>
  <span m=''3405770''>or equal</span> <span m=''3405960''>to the</span> <span m=''3406070''>base</span>
  <span m=''3406340''>case.</span> <span m=''3407540''>And</span> <span m=''3407670''>then</span>
  <span m=''3407820''>make</span> <span m=''3408000''>sure,</span> <span m=''3408250''>if</span>
  <span m=''3408300''>you''re</span> <span m=''3408390''>going</span> <span m=''3408490''>to</span>
  <span m=''3408530''>use</span> <span m=''3408800''>this</span> <span m=''3408980''>really</span>
  <span m=''3409340''>convenient</span> <span m=''3409800''>dot</span> <span m=''3409990''>dot</span>
  <span m=''3410160''>dot</span> <span m=''3410390''>notation,</span> <span m=''3411490''>that
  you</span> <span m=''3411790''>don''t</span> <span m=''3411980''>wind</span> <span
  m=''3412260''>up</span> <span m=''3412410''>here</span> <span m=''3412760''>saying,</span>
  <span m=''3413140''>oh</span> <span m=''3413160''>this</span> <span m=''3413360''>is</span>
  <span m=''3413480''>horses</span> <span m=''3414040''>h2</span> <span m=''3414450''>through</span>
  <span m=''3414840''>hn</span> <span m=''3415650''>when</span> <span m=''3415820''>there''s</span>
  <span m=''3415950''>no</span> <span m=''3416120''>horses</span> <span m=''3416490''>there,</span>
  <span m=''3418240''>because</span> <span m=''3418440''>n is</span> <span m=''3418610''>1.</span>
  </p><p><span m=''3420640''>Any</span> <span m=''3420830''>questions</span> <span
  m=''3421290''>about</span> <span m=''3421530''>this?</span> <span m=''3422370''>Yeah?</span>
  </p><p><span m=''3423688''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''3428580''>PROFESSOR:
  Great</span> <span m=''3428980''>question.</span> <span m=''3429670''>All</span>
  <span m=''3429930''>right,</span> <span m=''3430180''>let''s</span> <span m=''3430400''>fix</span>
  <span m=''3430640''>the</span> <span m=''3430740''>proof.</span> <span m=''3431970''>Start</span>
  <span m=''3432320''>with</span> <span m=''3432410''>the</span> <span m=''3432490''>base</span>
  <span m=''3432870''>case</span> <span m=''3433150''>of</span> <span m=''3433260''>p</span>
  <span m=''3433490''>of</span> <span m=''3433570''>2,</span> <span m=''3434500''>and</span>
  <span m=''3434670''>now</span> <span m=''3434830''>I''ve</span> <span m=''3434960''>got</span>
  <span m=''3435100''>all</span> <span m=''3435500''>this</span> <span m=''3435750''>done.</span>
  <span m=''3436250''>So</span> <span m=''3436280''>therefore,</span> <span m=''3437430''>that''s</span>
  <span m=''3437630''>another</span> <span m=''3437890''>proof.</span> <span m=''3439910''>Yeah?</span>
  <span m=''3443530''>Say</span> <span m=''3443700''>it</span> <span m=''3443760''>again.</span>
  </p><p><span m=''3444766''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''3449360''>PROFESSOR:
  This</span> <span m=''3449540''>is</span> <span m=''3449620''>still</span> <span
  m=''3449850''>the</span> <span m=''3449950''>same.</span> <span m=''3450250''>In</span>
  <span m=''3450360''>any</span> <span m=''3450670''>set</span> <span m=''3451450''>of</span>
  <span m=''3451660''>n</span> <span m=''3451980''>bigger</span> <span m=''3452090''>than</span>
  <span m=''3452240''>or</span> <span m=''3452280''>equal</span> <span m=''3452550''>to</span>
  <span m=''3452940''>two</span> <span m=''3453370''>horses,</span> <span m=''3454700''>all</span>
  <span m=''3454990''>the</span> <span m=''3455070''>horses</span> <span m=''3455460''>in</span>
  <span m=''3455520''>the</span> <span m=''3455610''>set</span> <span m=''3455800''>are</span>
  <span m=''3455860''>the</span> <span m=''3455940''>same</span> <span m=''3456150''>color.</span>
  <span m=''3456390''>That''s</span> <span m=''3456580''>what</span> <span m=''3456660''>he</span>
  <span m=''3456750''>saying.</span> <span m=''3457390''>And</span> <span m=''3457520''>he''s</span>
  <span m=''3457660''>saying,</span> <span m=''3457910''>hey</span> <span m=''3458090''>look,</span>
  <span m=''3458690''>the</span> <span m=''3458810''>proof</span> <span m=''3459070''>worked</span>
  <span m=''3459590''>here.</span> <span m=''3460000''>The inductive</span> <span
  m=''3460420''>step</span> <span m=''3460660''>is</span> <span m=''3460780''>just</span>
  <span m=''3461000''>fine.</span> <span m=''3461930''>p2</span> <span m=''3462750''>does</span>
  <span m=''3463020''>imply</span> <span m=''3463340''>p3.</span> <span m=''3464630''>Yeah?</span>
  </p><p><span m=''3465548''>AUDIENCE: The base case</span> <span m=''3465966''>for
  2</span> <span m=''3466384''>isn''t</span> <span m=''3466802''>true.</span> </p><p><span
  m=''3467220''>PROFESSOR: That''s</span> <span m=''3467580''>right.</span> <span
  m=''3468120''>The base</span> <span m=''3468360''>case</span> <span m=''3468740''>fails.</span>
  <span m=''3471060''>That''s</span> <span m=''3471180''>why</span> <span m=''3471300''>you''ve</span>
  <span m=''3471540''>always</span> <span m=''3472060''>got</span> <span m=''3472230''>to</span>
  <span m=''3472320''>check</span> <span m=''3472640''>the</span> <span m=''3472730''>base</span>
  <span m=''3473020''>case.</span> <span m=''3474450''>Yeah?</span> </p><p><span m=''3475390''>AUDIENCE:
  What it</span> <span m=''3475540''>does</span> <span m=''3476019''>prove</span>
  <span m=''3476498''>is that</span> <span m=''3477935''>if you</span> <span m=''3478414''>find</span>
  <span m=''3478893''>any two</span> <span m=''3479372''>horse</span> <span m=''3479851''>and</span>
  <span m=''3480330''>they''re</span> <span m=''3480809''>always</span> <span m=''3481288''>going
  to</span> <span m=''3481767''>be the same</span> <span m=''3482246''>color,</span>
  <span m=''3482725''>then all</span> <span m=''3483204''>horses have</span> <span
  m=''3483683''>to be the same</span> <span m=''3484162''>color.</span> </p><p><span
  m=''3484650''>PROFESSOR: That''s</span> <span m=''3484990''>correct.</span> <span
  m=''3485770''>That''s</span> <span m=''3486000''>a</span> <span m=''3486050''>great</span>
  <span m=''3486310''>point.</span> <span m=''3487170''>We</span> <span m=''3487250''>have</span>
  <span m=''3487520''>given</span> <span m=''3487730''>a</span> <span m=''3487790''>proof</span>
  <span m=''3488250''>that</span> <span m=''3489050''>if</span> <span m=''3489220''>you</span>
  <span m=''3489350''>look</span> <span m=''3489520''>at</span> <span m=''3489600''>any</span>
  <span m=''3489870''>pair</span> <span m=''3490120''>of</span> <span m=''3490180''>horses</span>
  <span m=''3490580''>and</span> <span m=''3490660''>they''re</span> <span m=''3490750''>the</span>
  <span m=''3490860''>same</span> <span m=''3491130''>color,</span> <span m=''3492190''>then</span>
  <span m=''3492360''>all</span> <span m=''3492700''>horses</span> <span m=''3493070''>are</span>
  <span m=''3493110''>the</span> <span m=''3493220''>same</span> <span m=''3493480''>color.</span>
  <span m=''3494380''>That''s</span> <span m=''3494580''>true.</span> <span m=''3496620''>That</span>
  <span m=''3496820''>is</span> <span m=''3496900''>true.</span> <span m=''3497790''>Of</span>
  <span m=''3497880''>course,</span> <span m=''3498480''>there</span> <span m=''3498670''>are</span>
  <span m=''3498830''>pairs</span> <span m=''3499090''>of</span> <span m=''3499200''>horses
  that</span> <span m=''3499540''>aren''t</span> <span m=''3499720''>the</span> <span
  m=''3499810''>same</span> <span m=''3500010''>color.</span> <span m=''3501000''>So</span>
  <span m=''3501130''>the</span> <span m=''3501220''>base</span> <span m=''3501490''>case</span>
  <span m=''3501720''>would</span> <span m=''3501860''>fail.</span> </p><p><span m=''3502560''>So</span>
  <span m=''3502840''>always</span> <span m=''3503370''>check</span> <span m=''3503610''>the</span>
  <span m=''3503700''>base</span> <span m=''3503980''>case.</span> <span m=''3504170''>You</span>
  <span m=''3504290''>could</span> <span m=''3504430''>prove</span> <span m=''3504660''>some</span>
  <span m=''3504810''>great</span> <span m=''3505280''>stuff</span> <span m=''3505670''>if</span>
  <span m=''3505780''>you</span> <span m=''3505860''>don''t</span> <span m=''3506080''>check</span>
  <span m=''3506300''>the</span> <span m=''3506360''>base</span> <span m=''3506600''>case.</span>
  <span m=''3510670''>All</span> <span m=''3510930''>right,</span> <span m=''3511600''>any</span>
  <span m=''3512060''>other</span> <span m=''3512200''>questions</span> <span m=''3512590''>about</span>
  <span m=''3512840''>that?</span> <span m=''3514262''>Yeah?</span> </p><p><span m=''3517148''>AUDIENCE:
  Negative</span> <span m=''3517629''>number</span> <span m=''3518110''>[INAUDIBLE]?</span>
  </p><p><span m=''3520040''>PROFESSOR: Yeah.</span> <span m=''3520660''>As</span>
  <span m=''3521042''>long as it''s</span> <span m=''3521424''>an integer.</span>
  <span m=''3521806''>And as</span> <span m=''3522190''>long</span> <span m=''3522420''>as</span>
  <span m=''3522510''>you</span> <span m=''3522810''>prove</span> <span m=''3523000''>pn</span>
  <span m=''3523395''>implies</span> <span m=''3523790''>pn plus</span> <span m=''3524070''>1</span>
  <span m=''3524260''>starting</span> <span m=''3524750''>there</span> <span m=''3524980''>all</span>
  <span m=''3525170''>the</span> <span m=''3525250''>way</span> <span m=''3525760''>out.</span>
  <span m=''3526390''>Yeah,</span> <span m=''3526400''>you</span> <span m=''3526530''>can</span>
  <span m=''3526640''>start</span> <span m=''3526830''>at</span> <span m=''3526880''>negative</span>
  <span m=''3527150''>numbers</span> <span m=''3527510''>if</span> <span m=''3527520''>you</span>
  <span m=''3527630''>want.</span> <span m=''3528990''>Usually</span> <span m=''3529520''>there''s</span>
  <span m=''3529680''>not</span> <span m=''3529860''>many</span> <span m=''3530310''>cases</span>
  <span m=''3530710''>where</span> <span m=''3530820''>that</span> <span m=''3531100''>comes</span>
  <span m=''3531350''>up</span> <span m=''3531500''>you</span> <span m=''3531600''>want</span>
  <span m=''3531880''>to,</span> <span m=''3532000''>but</span> <span m=''3532150''>you</span>
  <span m=''3532260''>can.</span> <span m=''3532630''>Nothing</span> <span m=''3532870''>wrong</span>
  <span m=''3533100''>with</span> <span m=''3533190''>that.</span> <span m=''3535030''>Any</span>
  <span m=''3535210''>other</span> <span m=''3535340''>questions?</span> </p><p><span
  m=''3537730''>Yeah,</span> <span m=''3537860''>you</span> <span m=''3537950''>can</span>
  <span m=''3538070''>see</span> <span m=''3538290''>why</span> <span m=''3538450''>it</span>
  <span m=''3538530''>was</span> <span m=''3538690''>a</span> <span m=''3538750''>messy</span>
  <span m=''3539220''>homework</span> <span m=''3540140''>problem.</span> <span m=''3542820''>So</span>
  <span m=''3543030''>far</span> <span m=''3543200''>we''ve</span> <span m=''3543370''>seen</span>
  <span m=''3543540''>examples</span> <span m=''3544020''>of</span> <span m=''3544090''>how</span>
  <span m=''3544270''>induction</span> <span m=''3544790''>is</span> <span m=''3544900''>useful</span>
  <span m=''3546240''>in</span> <span m=''3546460''>proving</span> <span m=''3546900''>the</span>
  <span m=''3546970''>hypothesis</span> <span m=''3547660''>is</span> <span m=''3547760''>true,</span>
  <span m=''3548860''>but</span> <span m=''3548990''>not</span> <span m=''3549220''>in</span>
  <span m=''3549340''>solving</span> <span m=''3550060''>the</span> <span m=''3550160''>problem,</span>
  <span m=''3550910''>per</span> <span m=''3551080''>se.</span> <span m=''3552920''>Or</span>
  <span m=''3553180''>even</span> <span m=''3553380''>figuring</span> <span m=''3553800''>out</span>
  <span m=''3554030''>what</span> <span m=''3554210''>the</span> <span m=''3554280''>hypothesis</span>
  <span m=''3554920''>should</span> <span m=''3555120''>be.</span> <span m=''3556540''>Now</span>
  <span m=''3557490''>in</span> <span m=''3557650''>the</span> <span m=''3557750''>last</span>
  <span m=''3558050''>example,</span> <span m=''3559060''>we''re</span> <span m=''3559300''>going</span>
  <span m=''3559400''>to</span> <span m=''3559460''>show</span> <span m=''3559760''>you</span>
  <span m=''3559950''>how</span> <span m=''3560130''>induction</span> <span m=''3560680''>can</span>
  <span m=''3560830''>be</span> <span m=''3560970''>used</span> <span m=''3561330''>to</span>
  <span m=''3561420''>prove</span> <span m=''3561910''>there</span> <span m=''3562110''>is</span>
  <span m=''3562390''>a</span> <span m=''3562460''>solution</span> <span m=''3562900''>to</span>
  <span m=''3562980''>a</span> <span m=''3563040''>problem,</span> <span m=''3564300''>and</span>
  <span m=''3564460''>also</span> <span m=''3564740''>how</span> <span m=''3564920''>to</span>
  <span m=''3565020''>find</span> <span m=''3565470''>the</span> <span m=''3565560''>solution.</span>
  </p><p><span m=''3566150''>So</span> <span m=''3566200''>it''s</span> <span m=''3566320''>actually</span>
  <span m=''3566630''>going</span> <span m=''3566710''>to</span> <span m=''3566750''>be</span>
  <span m=''3566850''>a</span> <span m=''3566890''>very</span> <span m=''3567130''>useful,</span>
  <span m=''3567550''>constructive</span> <span m=''3568100''>thing</span> <span m=''3568310''>in</span>
  <span m=''3568370''>this</span> <span m=''3568540''>case.</span> <span m=''3569390''>Now</span>
  <span m=''3569540''>this</span> <span m=''3569750''>problem</span> <span m=''3570140''>arose</span>
  <span m=''3570640''>in</span> <span m=''3570730''>the</span> <span m=''3570820''>construction</span>
  <span m=''3571390''>of</span> <span m=''3571470''>the</span> <span m=''3571550''>status</span>
  <span m=''3571950''>center,</span> <span m=''3572840''>the</span> <span m=''3572900''>building</span>
  <span m=''3573410''>we''re</span> <span m=''3573600''>in</span> <span m=''3573710''>now.</span>
  <span m=''3575110''>This</span> <span m=''3575480''>whole</span> <span m=''3575710''>building</span>
  <span m=''3576100''>was</span> <span m=''3576240''>originally</span> <span m=''3576800''>supposed</span>
  <span m=''3577140''>to</span> <span m=''3577210''>cost,</span> <span m=''3577950''>completely</span>
  <span m=''3578310''>furnished,</span> <span m=''3579100''>under</span> <span m=''3579350''>$100</span>
  <span m=''3579680''>million.</span> <span m=''3581120''>That</span> <span m=''3581300''>was</span>
  <span m=''3581430''>the</span> <span m=''3581490''>goal.</span> </p><p><span m=''3582400''>But</span>
  <span m=''3583040''>the</span> <span m=''3583120''>first</span> <span m=''3583440''>mistake</span>
  <span m=''3583820''>they</span> <span m=''3583930''>made</span> <span m=''3584310''>was</span>
  <span m=''3584440''>the</span> <span m=''3584530''>first</span> <span m=''3584780''>step,</span>
  <span m=''3585000''>was</span> <span m=''3585120''>hiring</span> <span m=''3585530''>the</span>
  <span m=''3585640''>architect.</span> <span m=''3586260''>They</span> <span m=''3586400''>hired</span>
  <span m=''3586730''>Frank</span> <span m=''3587020''>Gehry.</span> <span m=''3587820''>I</span>
  <span m=''3587900''>think</span> <span m=''3588220''>MIT</span> <span m=''3588600''>is</span>
  <span m=''3589090''>now</span> <span m=''3589260''>in</span> <span m=''3589310''>a</span>
  <span m=''3589350''>lawsuit</span> <span m=''3589610''>with</span> <span m=''3589870''>Frank</span>
  <span m=''3590100''>Gehry.</span> <span m=''3591350''>So</span> <span m=''3591480''>he</span>
  <span m=''3591630''>was</span> <span m=''3591750''>the</span> <span m=''3591880''>architect.</span>
  <span m=''3593200''>And</span> <span m=''3593610''>costs</span> <span m=''3594010''>just</span>
  <span m=''3594220''>went</span> <span m=''3594410''>nuts.</span> <span m=''3595600''>As</span>
  <span m=''3595660''>you</span> <span m=''3595760''>could</span> <span m=''3595870''>imagine,</span>
  <span m=''3596420''>all</span> <span m=''3596650''>these</span> <span m=''3596850''>slanted</span>
  <span m=''3597390''>walls</span> <span m=''3597960''>and</span> <span m=''3598250''>crazy</span>
  <span m=''3598570''>things</span> <span m=''3598820''>happening</span> <span m=''3599150''>actually</span>
  <span m=''3599600''>are</span> <span m=''3599670''>expensive.</span> <span m=''3600850''>And</span>
  <span m=''3602300''>the</span> <span m=''3602480''>cost</span> <span m=''3602830''>quickly</span>
  <span m=''3603140''>got</span> <span m=''3603310''>over</span> <span m=''3603480''>$300</span>
  <span m=''3603920''>million,</span> <span m=''3604190''>literally.</span> </p><p><span
  m=''3605940''>That</span> <span m=''3606230''>that''s</span> <span m=''3606430''>parts</span>
  <span m=''3606700''>true.</span> <span m=''3606820''>Now</span> <span m=''3606940''>I''m</span>
  <span m=''3607080''>going</span> <span m=''3607170''>to</span> <span m=''3607540''>fabricate</span>
  <span m=''3608020''>a</span> <span m=''3608080''>little</span> <span m=''3608310''>bit.</span>
  <span m=''3610180''>Now</span> <span m=''3610390''>actually,</span> <span m=''3610700''>fund</span>
  <span m=''3611020''>raising</span> <span m=''3611320''>became</span> <span m=''3611700''>a</span>
  <span m=''3612100''>huge</span> <span m=''3612670''>priority</span> <span m=''3613590''>once</span>
  <span m=''3613810''>they''re</span> <span m=''3614240''>more</span> <span m=''3614370''>than</span>
  <span m=''3614500''>$200</span> <span m=''3614780''>million</span> <span m=''3615020''>over</span>
  <span m=''3615180''>budget</span> <span m=''3615520''>they</span> <span m=''3615610''>haven''t</span>
  <span m=''3616010''>even bought</span> <span m=''3616260''>the</span> <span m=''3616340''>furniture</span>
  <span m=''3616700''>yet.</span> <span m=''3617670''>So</span> <span m=''3618380''>some</span>
  <span m=''3618530''>pretty</span> <span m=''3618830''>radical</span> <span m=''3619290''>ideas</span>
  <span m=''3619770''>were</span> <span m=''3619870''>proposed.</span> </p><p><span
  m=''3621000''>And</span> <span m=''3621220''>one</span> <span m=''3621400''>of</span>
  <span m=''3621490''>them</span> <span m=''3622230''>was</span> <span m=''3622500''>to</span>
  <span m=''3622600''>build</span> <span m=''3622830''>a</span> <span m=''3622890''>large</span>
  <span m=''3623390''>2</span> <span m=''3623570''>to</span> <span m=''3623620''>the</span>
  <span m=''3623790''>n</span> <span m=''3624030''>by</span> <span m=''3624170''>2</span>
  <span m=''3624390''>to the</span> <span m=''3624550''>n</span> <span m=''3624740''>courtyard</span>
  <span m=''3626080''>and</span> <span m=''3626360''>put</span> <span m=''3626520''>a</span>
  <span m=''3626580''>statue</span> <span m=''3627080''>of</span> <span m=''3627180''>a</span>
  <span m=''3627250''>wealthy,</span> <span m=''3628260''>potential</span> <span m=''3628740''>donor</span>
  <span m=''3629750''>in</span> <span m=''3629880''>the</span> <span m=''3629960''>center</span>
  <span m=''3630400''>of</span> <span m=''3630450''>the</span> <span m=''3630550''>courtyard.</span>
  <span m=''3631990''>So</span> <span m=''3632300''>let''s</span> <span m=''3634720''>draw</span>
  <span m=''3635020''>this.</span> <span m=''3647370''>So</span> <span m=''3647520''>the</span>
  <span m=''3647630''>courtyard--</span> <span m=''3650350''>and</span> <span m=''3650480''>of</span>
  <span m=''3650530''>course,</span> <span m=''3650780''>you</span> <span m=''3650860''>know,</span>
  <span m=''3650960''>it''s</span> <span m=''3651100''>computer</span> <span m=''3651480''>science,</span>
  <span m=''3652050''>so</span> <span m=''3652070''>it</span> <span m=''3652110''>has</span>
  <span m=''3652350''>to</span> <span m=''3652420''>be</span> <span m=''3652510''>a</span>
  <span m=''3652560''>power</span> <span m=''3652870''>of</span> <span m=''3652970''>2.</span>
  <span m=''3655380''>So</span> <span m=''3655620''>it''s</span> <span m=''3655760''>2</span>
  <span m=''3655940''>to</span> <span m=''3656000''>the</span> <span m=''3656170''>n</span>
  <span m=''3657170''>by</span> <span m=''3657435''>2</span> <span m=''3657700''>to</span>
  <span m=''3657900''>the</span> <span m=''3658080''>n.</span> <span m=''3659760''>And</span>
  <span m=''3659890''>I''ve</span> <span m=''3659970''>drawn</span> <span m=''3660270''>here</span>
  <span m=''3660440''>the</span> <span m=''3660550''>case</span> <span m=''3660880''>n</span>
  <span m=''3661000''>equals</span> <span m=''3661250''>2.</span> </p><p><span m=''3664060''>And</span>
  <span m=''3664230''>we''ve</span> <span m=''3664370''>got</span> <span m=''3664580''>to</span>
  <span m=''3664640''>get</span> <span m=''3666400''>the</span> <span m=''3666530''>statue</span>
  <span m=''3667040''>of</span> <span m=''3667120''>the</span> <span m=''3667210''>wealthy</span>
  <span m=''3667600''>guy</span> <span m=''3667960''>in</span> <span m=''3668070''>the</span>
  <span m=''3668150''>middle.</span> <span m=''3668760''>And</span> <span m=''3668930''>I''m</span>
  <span m=''3669000''>not</span> <span m=''3669180''>supposed</span> <span m=''3669450''>to</span>
  <span m=''3669510''>reveal</span> <span m=''3669800''>his</span> <span m=''3669990''>name.</span>
  <span m=''3670280''>So</span> <span m=''3670460''>we''re</span> <span m=''3670570''>just</span>
  <span m=''3670740''>going</span> <span m=''3670830''>to</span> <span m=''3670890''>call</span>
  <span m=''3671140''>him</span> <span m=''3671520''>Bill.</span> <span m=''3675980''>So</span>
  <span m=''3676150''>Bill''s</span> <span m=''3676480''>got</span> <span m=''3676630''>to</span>
  <span m=''3676680''>go</span> <span m=''3676850''>in</span> <span m=''3676910''>the</span>
  <span m=''3677000''>center.</span> <span m=''3678130''>Now</span> <span m=''3678380''>this</span>
  <span m=''3678590''>would</span> <span m=''3678760''>be</span> <span m=''3678900''>fine,</span>
  <span m=''3679430''>except</span> <span m=''3679790''>to</span> <span m=''3679870''>that</span>
  <span m=''3680580''>nothing</span> <span m=''3680920''>was</span> <span m=''3681080''>easy</span>
  <span m=''3681340''>with</span> <span m=''3681480''>Frank</span> <span m=''3681740''>Gehry,</span>
  <span m=''3682490''>everything</span> <span m=''3682870''>was</span> <span m=''3682970''>some</span>
  <span m=''3683290''>weird,</span> <span m=''3683890''>weird</span> <span m=''3684190''>thing</span>
  <span m=''3684370''>going</span> <span m=''3684610''>on.</span> <span m=''3685310''>And</span>
  <span m=''3685510''>he</span> <span m=''3685740''>insisted</span> <span m=''3686250''>on</span>
  <span m=''3686370''>using</span> <span m=''3686790''>l-shaped</span> <span m=''3687560''>tiles</span>
  <span m=''3688860''>for</span> <span m=''3688950''>the</span> <span m=''3689030''>courtyard.</span>
  </p><p><span m=''3690660''>So</span> <span m=''3690960''>the</span> <span m=''3691080''>tiles</span>
  <span m=''3691740''>that</span> <span m=''3691820''>we''re</span> <span m=''3691910''>going</span>
  <span m=''3692010''>to</span> <span m=''3692060''>use</span> <span m=''3692510''>looked</span>
  <span m=''3692710''>like</span> <span m=''3693600''>this.</span> <span m=''3694560''>So</span>
  <span m=''3694840''>it''s</span> <span m=''3696390''>almost</span> <span m=''3696730''>a</span>
  <span m=''3696790''>two</span> <span m=''3696980''>by</span> <span m=''3697170''>two,</span>
  <span m=''3697770''>except</span> <span m=''3698160''>you''re</span> <span m=''3698260''>missing</span>
  <span m=''3699260''>that</span> <span m=''3699460''>piece.</span> <span m=''3701220''>So</span>
  <span m=''3701430''>what you</span> <span m=''3701530''>need</span> <span m=''3701710''>to</span>
  <span m=''3701780''>figure</span> <span m=''3702030''>out</span> <span m=''3702190''>how</span>
  <span m=''3702310''>to</span> <span m=''3702430''>do</span> <span m=''3702930''>is</span>
  <span m=''3703600''>tie</span> <span m=''3703920''>all</span> <span m=''3704030''>this</span>
  <span m=''3704250''>courtyard</span> <span m=''3704870''>perfectly</span> <span
  m=''3706170''>leaving</span> <span m=''3707000''>one</span> <span m=''3707190''>spot</span>
  <span m=''3707490''>for</span> <span m=''3707590''>Bill</span> <span m=''3708550''>using</span>
  <span m=''3708900''>tiles</span> <span m=''3709530''>like</span> <span m=''3709760''>this,</span>
  <span m=''3710060''>these</span> <span m=''3710290''>l-shaped</span> <span m=''3710870''>tiles.</span>
  <span m=''3717400''>And</span> <span m=''3717500''>this</span> <span m=''3717670''>is</span>
  <span m=''3717810''>2</span> <span m=''3717970''>by</span> <span m=''3718120''>2</span>
  <span m=''3718360''>here.</span> <span m=''3721460''>So</span> <span m=''3721590''>that''s</span>
  <span m=''3721900''>the</span> <span m=''3722000''>task.</span> </p><p><span m=''3723150''>So</span>
  <span m=''3723790''>let''s</span> <span m=''3723970''>see</span> <span m=''3724070''>if</span>
  <span m=''3724180''>we</span> <span m=''3724270''>can</span> <span m=''3724420''>do</span>
  <span m=''3724610''>that</span> <span m=''3725740''>for</span> <span m=''3725870''>n</span>
  <span m=''3726010''>equals</span> <span m=''3726290''>2</span> <span m=''3726540''>here.</span>
  <span m=''3731090''>Let''s</span> <span m=''3731350''>see,</span> <span m=''3731470''>we</span>
  <span m=''3731610''>can</span> <span m=''3731750''>do</span> <span m=''3732230''>a</span>
  <span m=''3732290''>tile</span> <span m=''3732640''>here.</span> <span m=''3735040''>We</span>
  <span m=''3735330''>can</span> <span m=''3735520''>do</span> <span m=''3735860''>a</span>
  <span m=''3735940''>tile</span> <span m=''3736930''>here.</span> <span m=''3739100''>A</span>
  <span m=''3739150''>tile</span> <span m=''3739480''>here.</span> <span m=''3740870''>A</span>
  <span m=''3741000''>tile</span> <span m=''3741380''>here.</span> <span m=''3742520''>And</span>
  <span m=''3742610''>a</span> <span m=''3742670''>tile</span> <span m=''3742960''>there.</span>
  <span m=''3744730''>So</span> <span m=''3744900''>we</span> <span m=''3745010''>can.</span>
  <span m=''3745320''>In</span> <span m=''3745390''>this</span> <span m=''3745550''>case</span>
  <span m=''3746330''>we</span> <span m=''3746540''>can</span> <span m=''3747090''>tile</span>
  <span m=''3747460''>the</span> <span m=''3747550''>courtyard</span> <span m=''3748000''>perfectly</span>
  <span m=''3748530''>using</span> <span m=''3749720''>these</span> <span m=''3749970''>L</span>
  <span m=''3750160''>shaped</span> <span m=''3750440''>tiles,</span> <span m=''3751330''>leaving</span>
  <span m=''3751670''>one</span> <span m=''3751990''>square</span> <span m=''3752440''>in</span>
  <span m=''3752500''>the</span> <span m=''3752600''>Center</span> <span m=''3753890''>for</span>
  <span m=''3753990''>the</span> <span m=''3754100''>statue.</span> </p><p><span m=''3756850''>All
  right,</span> <span m=''3756910''>everyone</span> <span m=''3757150''>understand</span>
  <span m=''3757640''>what</span> <span m=''3757750''>we''re</span> <span m=''3757820''>trying</span>
  <span m=''3758080''>to</span> <span m=''3758140''>do?</span> <span m=''3759110''>The</span>
  <span m=''3759200''>goal?</span> <span m=''3760790''>Now</span> <span m=''3760920''>I</span>
  <span m=''3761000''>want</span> <span m=''3761160''>to</span> <span m=''3761230''>do</span>
  <span m=''3761400''>it</span> <span m=''3761480''>for</span> <span m=''3761939''>n.</span>
  <span m=''3766070''>So</span> <span m=''3766240''>let''s</span> <span m=''3767620''>start</span>
  <span m=''3768180''>proving</span> <span m=''3768710''>it</span> <span m=''3769130''>by</span>
  <span m=''3770120''>induction,</span> <span m=''3771270''>even</span> <span m=''3771490''>though</span>
  <span m=''3771800''>we</span> <span m=''3771900''>don''t</span> <span m=''3772050''>know</span>
  <span m=''3772140''>how</span> <span m=''3772240''>to</span> <span m=''3772350''>do</span>
  <span m=''3772540''>it</span> <span m=''3772630''>yet.</span> <span m=''3772790''>Because</span>
  <span m=''3772910''>we''re</span> <span m=''3772990''>going</span> <span m=''3773070''>to</span>
  <span m=''3773130''>see</span> <span m=''3773280''>how</span> <span m=''3773420''>induction''s</span>
  <span m=''3773970''>going</span> <span m=''3774080''>to</span> <span m=''3774140''>help</span>
  <span m=''3774410''>us</span> <span m=''3775330''>show</span> <span m=''3775670''>it''s</span>
  <span m=''3775790''>possible</span> <span m=''3776480''>and</span> <span m=''3776560''>maybe</span>
  <span m=''3776760''>even</span> <span m=''3777630''>show</span> <span m=''3777820''>us</span>
  <span m=''3777950''>how</span> <span m=''3778140''>to</span> <span m=''3778250''>do
  it.</span> </p><p><span m=''3783700''>So</span> <span m=''3783860''>let''s</span>
  <span m=''3784050''>state</span> <span m=''3784270''>a</span> <span m=''3784330''>theorem.</span>
  <span m=''3787970''>For</span> <span m=''3788200''>all</span> <span m=''3788390''>n</span>
  <span m=''3790070''>there</span> <span m=''3790260''>exists</span> <span m=''3790780''>away</span>
  <span m=''3793600''>to</span> <span m=''3793840''>tile</span> <span m=''3796280''>a</span>
  <span m=''3796570''>2</span> <span m=''3796860''>to</span> <span m=''3796940''>the</span>
  <span m=''3797110''>n</span> <span m=''3797860''>by</span> <span m=''3798260''>2</span>
  <span m=''3798470''>to</span> <span m=''3798540''>the</span> <span m=''3798710''>n</span>
  <span m=''3800410''>region,</span> <span m=''3802420''>or</span> <span m=''3802570''>courtyard,</span>
  <span m=''3805310''>with</span> <span m=''3806030''>a</span> <span m=''3807160''>center</span>
  <span m=''3807680''>square</span> <span m=''3808120''>missing</span> <span m=''3808840''>for</span>
  <span m=''3809120''>Bill.</span> <span m=''3823230''>And</span> <span m=''3823400''>the</span>
  <span m=''3823480''>proof</span> <span m=''3823780''>will</span> <span m=''3823860''>be</span>
  <span m=''3824000''>by</span> <span m=''3824220''>induction.</span> </p><p><span
  m=''3832670''>And</span> <span m=''3833010''>our</span> <span m=''3833140''>induction</span>
  <span m=''3833570''>hypothesis,</span> <span m=''3834440''>the</span> <span m=''3834520''>predicate,</span>
  <span m=''3836250''>pn</span> <span m=''3836830''>is</span> <span m=''3836970''>going</span>
  <span m=''3837210''>to</span> <span m=''3837280''>be</span> <span m=''3838080''>what</span>
  <span m=''3838210''>we''re</span> <span m=''3838280''>trying</span> <span m=''3838470''>to</span>
  <span m=''3838530''>prove.</span> <span m=''3841450''>So</span> <span m=''3841600''>this</span>
  <span m=''3842060''>is</span> <span m=''3842390''>the</span> <span m=''3842570''>induction</span>
  <span m=''3842920''>hypothesis.</span> <span m=''3845960''>Almost</span> <span m=''3846370''>always</span>
  <span m=''3846880''>when</span> <span m=''3846980''>you</span> <span m=''3847070''>do</span>
  <span m=''3847200''>the</span> <span m=''3847290''>induction</span> <span m=''3847680''>you</span>
  <span m=''3847770''>want</span> <span m=''3847880''>to</span> <span m=''3847940''>start</span>
  <span m=''3848180''>out</span> <span m=''3848320''>with</span> <span m=''3848430''>that</span>
  <span m=''3848620''>as</span> <span m=''3848720''>your</span> <span m=''3848860''>hypothesis.</span>
  <span m=''3851380''>What''s</span> <span m=''3851570''>the</span> <span m=''3851640''>next</span>
  <span m=''3851830''>step?</span> <span m=''3854350''>Base</span> <span m=''3854680''>case.</span>
  <span m=''3855040''>Never</span> <span m=''3855490''>ever</span> <span m=''3855780''>forget</span>
  <span m=''3856100''>the</span> <span m=''3856170''>base</span> <span m=''3856460''>case</span>
  <span m=''3858460''>or</span> <span m=''3858710''>you''ll</span> <span m=''3858830''>be</span>
  <span m=''3859340''>thinking all</span> <span m=''3859590''>horses</span> <span
  m=''3860140''>are</span> <span m=''3860180''>the</span> <span m=''3860290''>same</span>
  <span m=''3860570''>color.</span> <span m=''3862660''>p0.</span> </p><p><span m=''3865350''>Well,</span>
  <span m=''3865970''>the</span> <span m=''3866070''>courtyard</span> <span m=''3866800''>for</span>
  <span m=''3866920''>n</span> <span m=''3867080''>equals</span> <span m=''3867410''>0</span>
  <span m=''3868980''>is</span> <span m=''3869160''>just</span> <span m=''3869670''>1</span>
  <span m=''3870090''>square.</span> <span m=''3872190''>And</span> <span m=''3872430''>that''s</span>
  <span m=''3872640''>for</span> <span m=''3872740''>Bill.</span> <span m=''3875150''>So</span>
  <span m=''3875350''>you''re</span> <span m=''3875460''>done.</span> <span m=''3876230''>There''s</span>
  <span m=''3876460''>no</span> <span m=''3876700''>tiles</span> <span m=''3877110''>at</span>
  <span m=''3877180''>all</span> <span m=''3877340''>to</span> <span m=''3877410''>worry</span>
  <span m=''3877640''>about.</span> <span m=''3878790''>That''s</span> <span m=''3879190''>easy.</span>
  <span m=''3880500''>So</span> <span m=''3880700''>that''s</span> <span m=''3880860''>true.</span>
  <span m=''3883070''>And</span> <span m=''3883290''>then</span> <span m=''3883480''>we</span>
  <span m=''3883570''>do</span> <span m=''3883720''>the</span> <span m=''3883910''>inductive</span>
  <span m=''3884410''>step.</span> </p><p><span m=''3911270''>So</span> <span m=''3913280''>inductive</span>
  <span m=''3913650''>step.</span> <span m=''3919650''>For</span> <span m=''3920290''>n</span>
  <span m=''3921100''>bigger</span> <span m=''3921350''>than or</span> <span m=''3921450''>equal</span>
  <span m=''3921570''>to</span> <span m=''3921640''>0,</span> <span m=''3922050''>got</span>
  <span m=''3922200''>to</span> <span m=''3922420''>remember</span> <span m=''3922640''>to</span>
  <span m=''3922710''>keep</span> <span m=''3922910''>track</span> <span m=''3923150''>of</span>
  <span m=''3923220''>that</span> <span m=''3923430''>now,</span> <span m=''3925030''>we</span>
  <span m=''3925190''>assume</span> <span m=''3926950''>pn</span> <span m=''3929020''>to</span>
  <span m=''3929230''>verify</span> <span m=''3929810''>the</span> <span m=''3929920''>inductive</span>
  <span m=''3930330''>hypothesis,</span> <span m=''3931240''>or to</span> <span m=''3931430''>prove</span>
  <span m=''3931780''>pn</span> <span m=''3932070''>plus</span> <span m=''3932330''>1.</span>
  <span m=''3934010''>A</span> <span m=''3934520''>lot</span> <span m=''3934730''>of</span>
  <span m=''3934800''>ways</span> <span m=''3935050''>to</span> <span m=''3935160''>write</span>
  <span m=''3935390''>this</span> <span m=''3935580''>down,</span> <span m=''3935930''>but</span>
  <span m=''3936080''>you</span> <span m=''3936170''>always</span> <span m=''3936440''>want</span>
  <span m=''3936610''>to</span> <span m=''3937040''>say</span> <span m=''3937190''>what</span>
  <span m=''3937390''>you''re</span> <span m=''3937500''>assuming</span> <span m=''3937880''>and</span>
  <span m=''3937960''>why.</span> </p><p><span m=''3940650''>So</span> <span m=''3940910''>we</span>
  <span m=''3941010''>need</span> <span m=''3941220''>to</span> <span m=''3941290''>show</span>
  <span m=''3945050''>pn</span> <span m=''3945450''>plus</span> <span m=''3945650''>1</span>
  <span m=''3945810''>is</span> <span m=''3945900''>true.</span> <span m=''3952940''>Well,</span>
  <span m=''3953160''>so</span> <span m=''3953270''>let''s</span> <span m=''3953510''>look</span>
  <span m=''3953710''>at</span> <span m=''3953770''>a</span> <span m=''3953950''>2</span>
  <span m=''3954130''>to</span> <span m=''3954190''>the</span> <span m=''3954360''>n</span>
  <span m=''3954670''>by--</span> <span m=''3955400''>2 to</span> <span m=''3955530''>the</span>
  <span m=''3955690''>n</span> <span m=''3955780''>plus</span> <span m=''3956000''>1</span>
  <span m=''3956280''>by</span> <span m=''3956410''>2</span> <span m=''3956590''>to</span>
  <span m=''3956630''>the</span> <span m=''3956720''>n</span> <span m=''3956820''>plus</span>
  <span m=''3957020''>1</span> <span m=''3957310''>courtyard.</span> <span m=''3970600''>So</span>
  <span m=''3970790''>let''s</span> <span m=''3970990''>draw</span> <span m=''3971200''>it
  out</span> <span m=''3971380''>here.</span> <span m=''3974450''>2 to</span> <span
  m=''3974660''>the</span> <span m=''3974780''>n</span> <span m=''3974910''>plus</span>
  <span m=''3975170''>1</span> <span m=''3975770''>by</span> <span m=''3975940''>2</span>
  <span m=''3976100''>to</span> <span m=''3976160''>the</span> <span m=''3976260''>n</span>
  <span m=''3976390''>plus</span> <span m=''3976660''>1.</span> </p><p><span m=''3980210''>What</span>
  <span m=''3980420''>are</span> <span m=''3980460''>we</span> <span m=''3980590''>going</span>
  <span m=''3980710''>to</span> <span m=''3980850''>do</span> <span m=''3981770''>to</span>
  <span m=''3981890''>use</span> <span m=''3982140''>our</span> <span m=''3982250''>inductive</span>
  <span m=''3982600''>hypothesis?</span> <span m=''3983400''>Yeah?</span> </p><p><span
  m=''3984380''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''3999580''>PROFESSOR:
  For</span> <span m=''3999820''>the--</span> <span m=''4000610''>yeah.</span> <span
  m=''4001170''>So</span> <span m=''4001770''>you''re</span> <span m=''4001910''>on</span>
  <span m=''4002010''>a</span> <span m=''4002060''>good</span> <span m=''4002270''>track</span>
  <span m=''4002650''>there,</span> <span m=''4002820''>for</span> <span m=''4002940''>sure.</span>
  <span m=''4003920''>But</span> <span m=''4004100''>I''ve</span> <span m=''4004180''>got</span>
  <span m=''4004270''>to</span> <span m=''4004310''>apply--</span> <span m=''4004890''>I''m</span>
  <span m=''4004960''>not</span> <span m=''4005100''>going</span> <span m=''4005250''>from</span>
  <span m=''4005420''>1</span> <span m=''4005640''>to</span> <span m=''4005730''>2,</span>
  <span m=''4006720''>I</span> <span m=''4006800''>want</span> <span m=''4007020''>to</span>
  <span m=''4007080''>get--</span> <span m=''4007570''>I</span> <span m=''4007630''>want</span>
  <span m=''4007790''>to</span> <span m=''4007830''>use</span> <span m=''4008030''>pn</span>
  <span m=''4008430''>here.</span> <span m=''4009590''>So</span> <span m=''4009700''>I''ve</span>
  <span m=''4009760''>got</span> <span m=''4009960''>a</span> <span m=''4010030''>2
  to</span> <span m=''4010250''>the</span> <span m=''4010370''>n plus</span> <span
  m=''4010600''>1 by</span> <span m=''4010730''>2</span> <span m=''4010880''>to</span>
  <span m=''4011000''>the</span> <span m=''4011110''>n</span> <span m=''4011180''>plus</span>
  <span m=''4011360''>1</span> <span m=''4011500''>courtyard.</span> <span m=''4011960''>How</span>
  <span m=''4012100''>do I</span> <span m=''4012240''>use</span> <span m=''4012490''>pn?</span>
  <span m=''4014610''>2</span> <span m=''4014740''>to the</span> <span m=''4014950''>n</span>
  <span m=''4015060''>by</span> <span m=''4015160''>2 to</span> <span m=''4015540''>the</span>
  <span m=''4015920''>n courtyard.</span> <span m=''4016310''>Yeah?</span> </p><p><span
  m=''4017158''>AUDIENCE: Oh, never mind.</span> <span m=''4018006''>I don''t think</span>
  <span m=''4018430''>it works.</span> <span m=''4018870''>I was about</span> <span
  m=''4019362''>to say</span> <span m=''4019854''>that</span> <span m=''4020346''>would
  be</span> <span m=''4020838''>as if 2 to the</span> <span m=''4021330''>n would</span>
  <span m=''4021822''>divide</span> <span m=''4022314''>that into</span> <span m=''4022806''>four
  blocks.</span> </p><p><span m=''4024282''>PROFESSOR: Good idea,</span> <span m=''4024774''>yeah.</span>
  <span m=''4025770''>Let''s</span> <span m=''4026040''>divide</span> <span m=''4026330''>our</span>
  <span m=''4026440''>courtyard</span> <span m=''4026720''>into</span> <span m=''4026990''>four</span>
  <span m=''4027260''>blocks.</span> <span m=''4027830''>That''s</span> <span m=''4028030''>a</span>
  <span m=''4028070''>great</span> <span m=''4028310''>idea.</span> <span m=''4029410''>And</span>
  <span m=''4029640''>now</span> <span m=''4029800''>each</span> <span m=''4030030''>of</span>
  <span m=''4030090''>these</span> <span m=''4030330''>is</span> <span m=''4030440''>2</span>
  <span m=''4030610''>to</span> <span m=''4030670''>the</span> <span m=''4030810''>n</span>
  <span m=''4030960''>by</span> <span m=''4031090''>2</span> <span m=''4031270''>to</span>
  <span m=''4031330''>the</span> <span m=''4031500''>n.</span> <span m=''4033550''>Right?</span>
  <span m=''4035210''>And</span> <span m=''4035430''>I</span> <span m=''4035500''>can</span>
  <span m=''4035630''>apply</span> <span m=''4035970''>the</span> <span m=''4036090''>inductive</span>
  <span m=''4036500''>hypothesis</span> <span m=''4037370''>there.</span> </p><p><span
  m=''4039452''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''4045480''>PROFESSOR:
  Yeah.</span> <span m=''4046490''>Hm.</span> <span m=''4048620''>Yeah,</span> <span
  m=''4048800''>something--</span> <span m=''4049250''>yeah, it</span> <span m=''4049530''>doesn''t</span>
  <span m=''4049850''>quite</span> <span m=''4050110''>work</span> <span m=''4050560''>because</span>
  <span m=''4051620''>Bill</span> <span m=''4051850''>wants</span> <span m=''4052100''>to</span>
  <span m=''4052160''>be</span> <span m=''4052290''>here.</span> <span m=''4054250''>Got
  a</span> <span m=''4054400''>little</span> <span m=''4054530''>square</span> <span
  m=''4054820''>for</span> <span m=''4054920''>Bill</span> <span m=''4055210''>there.</span>
  <span m=''4056280''>But</span> <span m=''4056430''>I</span> <span m=''4056510''>can''t</span>
  <span m=''4057800''>use</span> <span m=''4058020''>my</span> <span m=''4058190''>inductive</span>
  <span m=''4058550''>hypothesis</span> <span m=''4059240''>to</span> <span m=''4059370''>tile</span>
  <span m=''4059780''>this,</span> <span m=''4061760''>because</span> <span m=''4061930''>there''s</span>
  <span m=''4062080''>no</span> <span m=''4062260''>square</span> <span m=''4062620''>missing.</span>
  <span m=''4062980''>In</span> <span m=''4063050''>fact,</span> <span m=''4064025''>even
  if</span> <span m=''4064440''>there</span> <span m=''4064600''>wasn''t</span> <span
  m=''4064810''>a</span> <span m=''4064910''>square</span> <span m=''4065220''>missing,</span>
  <span m=''4065500''>I''m</span> <span m=''4065610''>in</span> <span m=''4065680''>trouble.</span>
  </p><p><span m=''4066190''>If</span> <span m=''4066330''>I''ve</span> <span m=''4066450''>got--</span>
  <span m=''4067490''>say</span> <span m=''4067700''>this</span> <span m=''4067930''>is</span>
  <span m=''4068040''>size</span> <span m=''4068640''>4</span> <span m=''4068930''>by</span>
  <span m=''4069060''>4</span> <span m=''4069340''>here.</span> <span m=''4070480''>Can
  I</span> <span m=''4070820''>tile</span> <span m=''4071160''>a</span> <span m=''4071220''>4</span>
  <span m=''4071430''>by</span> <span m=''4071550''>4</span> <span m=''4071810''>region</span>
  <span m=''4072140''>with</span> <span m=''4072310''>L</span> <span m=''4072470''>shaped</span>
  <span m=''4072700''>tiles?</span> <span m=''4075390''>No, they''re</span> <span
  m=''4075880''>size</span> <span m=''4076220''>3.</span> <span m=''4076475''>3</span>
  <span m=''4076730''>doesn''t</span> <span m=''4076830''>divide</span> <span m=''4076900''>into</span>
  <span m=''4077010''>16.</span> <span m=''4077420''>Yeah?</span> </p><p><span m=''4079282''>AUDIENCE:
  [INAUDIBLE]</span> <span m=''4081178''>There''s one tile</span> <span m=''4081652''>missing
  from</span> <span m=''4082126''>each of those</span> <span m=''4082600''>blocks</span>
  <span m=''4083074''>at the corner</span> <span m=''4083548''>that</span> <span m=''4084022''>[INAUDIBLE].</span>
  </p><p><span m=''4086300''>PROFESSOR: There''s</span> <span m=''4086610''>a</span>
  <span m=''4086650''>great</span> <span m=''4087000''>idea.</span> <span m=''4087400''>All</span>
  <span m=''4087640''>right,</span> <span m=''4087870''>we''re</span> <span m=''4088190''>making</span>
  <span m=''4088470''>progress</span> <span m=''4089050''>now.</span> <span m=''4090030''>Take</span>
  <span m=''4090290''>a</span> <span m=''4090360''>corner</span> <span m=''4090750''>out</span>
  <span m=''4090870''>of</span> <span m=''4090970''>each</span> <span m=''4091170''>of</span>
  <span m=''4091250''>them.</span> <span m=''4092640''>Put</span> <span m=''4092830''>my</span>
  <span m=''4092990''>l-shaped</span> <span m=''4093550''>tile</span> <span m=''4094000''>here.</span>
  <span m=''4096529''>Now</span> <span m=''4097670''>I</span> <span m=''4097790''>can</span>
  <span m=''4097939''>use the</span> <span m=''4098130''>inductive</span> <span m=''4098550''>hypothesis</span>
  <span m=''4099200''>to</span> <span m=''4099319''>tile</span> <span m=''4100310''>each</span>
  <span m=''4100560''>one</span> <span m=''4100800''>of</span> <span m=''4100890''>these.</span>
  <span m=''4104750''>Yeah?</span> <span m=''4106643''>Yeah?</span> </p><p><span m=''4108137''>AUDIENCE:
  Well,</span> <span m=''4108635''>why can''t</span> <span m=''4109133''>you put</span>
  <span m=''4109631''>a 4</span> <span m=''4110129''>in the</span> <span m=''4110627''>center</span>
  <span m=''4111623''>and then you</span> <span m=''4112121''>have a</span> <span
  m=''4112619''>bunch of</span> <span m=''4113117''>2s</span> <span m=''4113615''>on
  the side?</span> </p><p><span m=''4114113''>PROFESSOR: A</span> <span m=''4114620''>4
  in the</span> <span m=''4114990''>center--</span> </p><p><span m=''4115689''>AUDIENCE:
  Like a</span> <span m=''4116119''>2 by</span> <span m=''4116549''>2</span> <span
  m=''4116979''>in the center.</span> </p><p><span m=''4118269''>PROFESSOR: I got
  that.</span> <span m=''4118700''>I got</span> <span m=''4119015''>Bill and</span>
  <span m=''4119330''>the tile.</span> </p><p><span m=''4120790''>AUDIENCE: No,</span>
  <span m=''4121272''>but like</span> <span m=''4121754''>make it</span> <span m=''4122236''>bigger.</span>
  <span m=''4124147''>Not just</span> <span m=''4124634''>like</span> <span m=''4125121''>4
  single</span> <span m=''4125608''>tiles,</span> <span m=''4126095''>but like--</span>
  <span m=''4127069''>so you have</span> <span m=''4127556''>something</span> <span
  m=''4128043''>like that over</span> <span m=''4128530''>there,</span> <span m=''4129017''>right?</span>
  <span m=''4129991''>Put that in</span> <span m=''4130478''>the center.</span> </p><p><span
  m=''4130965''>PROFESSOR: Put that in</span> <span m=''4131452''>the center,</span>
  <span m=''4131939''>OK.</span> </p><p><span m=''4132913''>AUDIENCE: And the rest</span>
  <span m=''4133400''>of them</span> <span m=''4133887''>will have</span> <span m=''4134374''>like</span>
  <span m=''4134861''>[INAUDIBLE].</span> </p><p><span m=''4136529''>PROFESSOR: Well,</span>
  <span m=''4136680''>the</span> <span m=''4136800''>rest</span> <span m=''4137080''>of</span>
  <span m=''4137140''>them</span> <span m=''4137330''>aren''t</span> <span m=''4137910''>2</span>
  <span m=''4138210''>by</span> <span m=''4138490''>2,</span> <span m=''4138720''>because</span>
  <span m=''4138890''>this</span> <span m=''4139060''>is</span> <span m=''4139210''>n.</span>
  <span m=''4140399''>I''ve</span> <span m=''4140490''>got</span> <span m=''4140670''>to</span>
  <span m=''4140710''>use</span> <span m=''4140970''>pn</span> <span m=''4141350''>here.</span>
  <span m=''4141600''>And</span> <span m=''4141689''>pn</span> <span m=''4142109''>says</span>
  <span m=''4142529''>that</span> <span m=''4142660''>I</span> <span m=''4142729''>can--</span>
  <span m=''4143540''>in</span> <span m=''4143689''>a</span> <span m=''4143819''>region</span>
  <span m=''4144260''>2 to</span> <span m=''4144390''>the</span> <span m=''4144560''>n</span>
  <span m=''4144670''>by</span> <span m=''4144779''>2 to</span> <span m=''4145029''>the</span>
  <span m=''4145189''>n</span> <span m=''4145380''>with</span> <span m=''4145540''>a</span>
  <span m=''4145590''>square</span> <span m=''4145950''>out</span> <span m=''4146040''>of</span>
  <span m=''4146100''>the</span> <span m=''4146189''>center,</span> <span m=''4146670''>I</span>
  <span m=''4146729''>can</span> <span m=''4147039''>tile</span> <span m=''4147350''>it.</span>
  <span m=''4149970''>Am</span> <span m=''4150040''>I</span> <span m=''4150279''>good</span>
  <span m=''4150439''>here</span> <span m=''4150630''>so</span> <span m=''4150810''>far?</span>
  <span m=''4151310''>I</span> <span m=''4151380''>claimed</span> <span m=''4151620''>I</span>
  <span m=''4151760''>was</span> <span m=''4151840''>sort</span> <span m=''4152020''>of</span>
  <span m=''4152120''>done.</span> <span m=''4153020''>Yeah?</span> </p><p><span m=''4154271''>AUDIENCE:
  No,</span> <span m=''4155255''>because</span> <span m=''4155747''>p of</span> <span
  m=''4156239''>n</span> <span m=''4156731''>tells us--</span> <span m=''4157715''>well,</span>
  <span m=''4158207''>assume</span> <span m=''4158699''>p of n</span> <span m=''4159191''>tells
  us that</span> <span m=''4159683''>you can set</span> <span m=''4160175''>up a</span>
  <span m=''4160667''>2 to the n</span> <span m=''4161159''>by 2 to the n</span> <span
  m=''4161651''>courtyard with</span> <span m=''4162143''>a centerpiece</span> <span
  m=''4162635''>of--</span> </p><p><span m=''4163140''>PROFESSOR: Yeah.</span> </p><p><span
  m=''4164200''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''4165779''>PROFESSOR:
  Yeah.</span> <span m=''4166350''>And</span> <span m=''4166430''>what''s</span> <span
  m=''4166689''>the</span> <span m=''4166760''>problem</span> <span m=''4167319''>for</span>
  <span m=''4167420''>this</span> <span m=''4167760''>2 to the</span> <span m=''4167920''>n</span>
  <span m=''4168090''>by</span> <span m=''4168189''>2 to the</span> <span m=''4168444''>n</span>
  <span m=''4168700''>region?</span> <span m=''4171029''>Bill''s not in the</span>
  <span m=''4171290''>center.</span> <span m=''4171620''>He</span> <span m=''4171750''>wants</span>
  <span m=''4171960''>to</span> <span m=''4172020''>be</span> <span m=''4172090''>in</span>
  <span m=''4172149''>the</span> <span m=''4172229''>center.</span> <span m=''4173170''>We
  put</span> <span m=''4173580''>Bill</span> <span m=''4173880''>in the</span> <span
  m=''4173960''>corner.</span> <span m=''4175529''>So</span> <span m=''4175660''>you</span>
  <span m=''4175729''>can''t</span> <span m=''4176010''>use the</span> <span m=''4176300''>inductive</span>
  <span m=''4176720''>hypothesis</span> <span m=''4177359''>here.</span> <span m=''4180130''>So</span>
  <span m=''4180270''>I</span> <span m=''4180760''>went</span> <span m=''4180810''>a</span>
  <span m=''4180859''>little</span> <span m=''4181000''>too</span> <span m=''4181130''>fast,</span>
  <span m=''4181510''>here.</span> <span m=''4181899''>This</span> <span m=''4182080''>is</span>
  <span m=''4182189''>not</span> <span m=''4182380''>a proof</span> <span m=''4182689''>so</span>
  <span m=''4182819''>far.</span> <span m=''4184450''>I''ve</span> <span m=''4184540''>got</span>
  <span m=''4184670''>a</span> <span m=''4184710''>problem.</span> <span m=''4185970''>Yeah?</span>
  </p><p><span m=''4187529''>AUDIENCE: [INAUDIBLE]</span> </p><p><span m=''4195260''>PROFESSOR:
  Great.</span> <span m=''4195710''>OK,</span> <span m=''4196050''>let''s</span> <span
  m=''4196560''>then</span> <span m=''4197110''>change</span> <span m=''4197690''>the</span>
  <span m=''4197930''>inductive</span> <span m=''4198430''>hypothesis.</span> <span
  m=''4200060''>Good.</span> <span m=''4200750''>Let''s</span> <span m=''4201150''>say</span>
  <span m=''4201800''>there</span> <span m=''4201910''>exists</span> <span m=''4202240''>a</span>
  <span m=''4202300''>way</span> <span m=''4202460''>to</span> <span m=''4202570''>tile</span>
  <span m=''4202920''>a 2 to</span> <span m=''4203140''>the</span> <span m=''4203310''>n</span>
  <span m=''4203460''>by</span> <span m=''4203570''>2 to</span> <span m=''4203670''>the
  n</span> <span m=''4203920''>region</span> <span m=''4204810''>with</span> <span
  m=''4205090''>a</span> <span m=''4205210''>corner</span> <span m=''4205710''>square</span>
  <span m=''4206040''>missing</span> <span m=''4210530''>for Bill.</span> <span m=''4214050''>All</span>
  <span m=''4214260''>right,</span> <span m=''4218030''>but</span> <span m=''4218200''>now
  I</span> <span m=''4218380''>got</span> <span m=''4218510''>to</span> <span m=''4218560''>put--</span>
  <span m=''4219400''>oh,</span> <span m=''4219550''>but</span> <span m=''4219650''>I</span>
  <span m=''4219700''>can</span> <span m=''4219850''>make</span> <span m=''4220020''>this</span>
  <span m=''4220180''>work.</span> <span m=''4220500''>Yeah.</span> <span m=''4220770''>Yeah.</span>
  <span m=''4220930''>We</span> <span m=''4221030''>can</span> <span m=''4221140''>make</span>
  <span m=''4221350''>something--</span> <span m=''4221470''>we</span> <span m=''4221590''>can</span>
  <span m=''4221760''>prove</span> <span m=''4222000''>this</span> <span m=''4222240''>now.</span>
  </p><p><span m=''4222760''>The</span> <span m=''4222860''>inductive</span> <span
  m=''4223230''>step is</span> <span m=''4223510''>going</span> <span m=''4223610''>to</span>
  <span m=''4223680''>work</span> <span m=''4223970''>because</span> <span m=''4225290''>I''ll</span>
  <span m=''4225450''>put</span> <span m=''4225660''>Bill--</span> <span m=''4226050''>say
  he''s</span> <span m=''4226320''>in</span> <span m=''4226590''>one</span> <span
  m=''4226800''>of</span> <span m=''4226840''>the</span> <span m=''4226910''>four</span>
  <span m=''4227170''>regions.</span> <span m=''4228320''>Then</span> <span m=''4228550''>use</span>
  <span m=''4228760''>the</span> <span m=''4228920''>l</span> <span m=''4229230''>down</span>
  <span m=''4229520''>here.</span> <span m=''4231510''>Put</span> <span m=''4231790''>the
  l</span> <span m=''4231920''>here.</span> <span m=''4232850''>And now</span> <span
  m=''4233130''>I''ve</span> <span m=''4233240''>got</span> <span m=''4233360''>a</span>
  <span m=''4233410''>corner</span> <span m=''4233870''>out</span> <span m=''4234040''>of</span>
  <span m=''4234130''>each</span> <span m=''4234320''>one.</span> <span m=''4234900''>And</span>
  <span m=''4235150''>now</span> <span m=''4235320''>I''m</span> <span m=''4235460''>done</span>
  <span m=''4235680''>by</span> <span m=''4235820''>induction.</span> <span m=''4237810''>I</span>
  <span m=''4237970''>have</span> <span m=''4238225''>proved</span> <span m=''4238480''>there''s</span>
  <span m=''4238640''>a</span> <span m=''4238720''>way</span> <span m=''4238910''>to</span>
  <span m=''4239030''>tile</span> <span m=''4240460''>any</span> <span m=''4240720''>2
  to</span> <span m=''4240940''>the</span> <span m=''4241050''>n</span> <span m=''4241315''>by
  2 to</span> <span m=''4241580''>the n</span> <span m=''4241700''>region</span> <span
  m=''4242930''>with</span> <span m=''4243110''>a</span> <span m=''4243180''>corner</span>
  <span m=''4243590''>square</span> <span m=''4243910''>missing.</span> <span m=''4246050''>I</span>
  <span m=''4246150''>think</span> <span m=''4246310''>that</span> <span m=''4246480''>proof</span>
  <span m=''4246680''>works,</span> <span m=''4247442''>Yeah?</span> </p><p><span
  m=''4248426''>AUDIENCE: [INAUDIBLE]</span> <span m=''4253346''>with Bill in the</span>
  <span m=''4253838''>middle,</span> <span m=''4254330''>because</span> <span m=''4254822''>to</span>
  <span m=''4255314''>prove</span> <span m=''4255806''>that you</span> <span m=''4256298''>can
  put Bill</span> <span m=''4256790''>in the corner</span> <span m=''4257282''>in
  a</span> <span m=''4257774''>2</span> <span m=''4258266''>by 2 case,</span> <span
  m=''4258758''>you can</span> <span m=''4259250''>just</span> <span m=''4259742''>blow
  that</span> <span m=''4260234''>square off.</span> <span m=''4261218''>[INAUDIBLE]</span>
  <span m=''4262694''>just becomes</span> <span m=''4263186''>just another</span>
  <span m=''4263678''>square,</span> <span m=''4264170''>which is</span> <span m=''4264662''>4
  by</span> <span m=''4265154''>4</span> <span m=''4265646''>and then</span> <span
  m=''4266138''>you can</span> <span m=''4266630''>put him in</span> <span m=''4267122''>the
  middle.</span> </p><p><span m=''4268140''>PROFESSOR: That is true.</span> <span
  m=''4268770''>So you''ve jumped</span> <span m=''4269050''>ahead.</span> <span m=''4270140''>We</span>
  <span m=''4270390''>have</span> <span m=''4270680''>successfully</span> <span m=''4271310''>now</span>
  <span m=''4271390''>proved</span> <span m=''4272300''>this</span> <span m=''4272750''>is</span>
  <span m=''4272880''>true</span> <span m=''4273200''>for</span> <span m=''4273350''>p</span>
  <span m=''4273560''>of</span> <span m=''4273650''>n.</span> <span m=''4275050''>But</span>
  <span m=''4275190''>Bill</span> <span m=''4275600''>didn''t</span> <span m=''4275630''>want</span>
  <span m=''4275870''>to</span> <span m=''4275920''>be</span> <span m=''4276040''>in</span>
  <span m=''4276130''>the</span> <span m=''4276230''>corner.</span> <span m=''4276550''>We''re</span>
  <span m=''4276700''>trying</span> <span m=''4276960''>to</span> <span m=''4277040''>prove</span>
  <span m=''4277380''>there''s</span> <span m=''4277520''>a</span> <span m=''4277580''>way</span>
  <span m=''4277720''>to</span> <span m=''4277820''>do</span> <span m=''4277940''>it
  with</span> <span m=''4278110''>Bill</span> <span m=''4278320''>in</span> <span
  m=''4278380''>the</span> <span m=''4278460''>center,</span> <span m=''4279810''>which</span>
  <span m=''4279960''>is</span> <span m=''4280060''>not</span> <span m=''4280340''>what
  we</span> <span m=''4280480''>proved.</span> <span m=''4280760''>And</span> <span
  m=''4280810''>you''ve</span> <span m=''4280990''>come</span> <span m=''4281190''>up</span>
  <span m=''4281290''>with</span> <span m=''4281400''>a</span> <span m=''4281450''>way--</span>
  <span m=''4282200''>yeah,</span> <span m=''4282370''>that</span> <span m=''4282500''>might</span>
  <span m=''4282650''>be</span> <span m=''4282750''>doable.</span> </p><p><span m=''4283120''>First</span>
  <span m=''4283530''>prove</span> <span m=''4283730''>you</span> <span m=''4283810''>can</span>
  <span m=''4283960''>put</span> <span m=''4284030''>Bill</span> <span m=''4284290''>in</span>
  <span m=''4284340''>the</span> <span m=''4284440''>corner.</span> <span m=''4285690''>And</span>
  <span m=''4287600''>do</span> <span m=''4287800''>it</span> <span m=''4287860''>in</span>
  <span m=''4288160''>2 to</span> <span m=''4288380''>the</span> <span m=''4288510''>n</span>
  <span m=''4288630''>by</span> <span m=''4288740''>2 to</span> <span m=''4288970''>the</span>
  <span m=''4289140''>n''s.</span> <span m=''4291420''>I</span> <span m=''4291550''>don''t</span>
  <span m=''4291750''>know</span> <span m=''4291960''>about</span> <span m=''4292220''>this,</span>
  <span m=''4292440''>actually.</span> <span m=''4294300''>I</span> <span m=''4294350''>got</span>
  <span m=''4294530''>Bill</span> <span m=''4294750''>in</span> <span m=''4294800''>the</span>
  <span m=''4294900''>corner.</span> <span m=''4295890''>There''s</span> <span m=''4296040''>some</span>
  <span m=''4296290''>way</span> <span m=''4296420''>to</span> <span m=''4296530''>do</span>
  <span m=''4296780''>it.</span> <span m=''4298010''>But</span> <span m=''4298140''>it</span>
  <span m=''4298200''>might</span> <span m=''4298450''>have</span> <span m=''4298600''>involved</span>
  <span m=''4299030''>doing</span> <span m=''4299300''>this.</span> <span m=''4299630''>And</span>
  <span m=''4299710''>now</span> <span m=''4299840''>I</span> <span m=''4299910''>can''t</span>
  <span m=''4300250''>rotate</span> <span m=''4300900''>that.</span> <span m=''4301910''>I</span>
  <span m=''4302030''>don''t</span> <span m=''4302170''>think</span> <span m=''4302300''>we</span>
  <span m=''4302420''>have--</span> <span m=''4302650''>I don''t</span> <span m=''4302760''>think
  that</span> <span m=''4303020''>proof</span> <span m=''4303360''>necessarily</span>
  <span m=''4303900''>works.</span> </p><p><span m=''4305115''>AUDIENCE: [INAUDIBLE]</span>
  <span m=''4313035''>prove</span> <span m=''4313530''>that he could be</span> <span
  m=''4314025''>here.</span> <span m=''4314520''>But likewise,</span> <span m=''4315015''>we
  could</span> <span m=''4315510''>prove</span> <span m=''4316005''>that</span> <span
  m=''4316500''>if the</span> <span m=''4316995''>block just</span> <span m=''4317490''>rotates</span>
  <span m=''4317985''>you   can</span> <span m=''4318480''>[INAUDIBLE].</span> </p><p><span
  m=''4319470''>PROFESSOR: Yes,</span> <span m=''4319965''>I agree with you</span>
  <span m=''4320470''>and I liked it</span> <span m=''4321170''>when</span> <span
  m=''4321290''>I</span> <span m=''4321360''>first</span> <span m=''4321660''>heard
  it.</span> <span m=''4321960''>And you</span> <span m=''4322100''>might</span> <span
  m=''4322310''>still</span> <span m=''4322550''>convince</span> <span m=''4322980''>me.</span>
  <span m=''4323860''>But</span> <span m=''4324550''>all</span> <span m=''4324860''>we</span>
  <span m=''4325000''>proved</span> <span m=''4326590''>is</span> <span m=''4327070''>this,</span>
  <span m=''4327550''>there''s</span> <span m=''4327750''>a 2 to</span> <span m=''4327980''>the</span>
  <span m=''4328100''>n</span> <span m=''4328230''>by 2</span> <span m=''4328310''>to</span>
  <span m=''4328540''>the</span> <span m=''4328670''>n--</span> <span m=''4329370''>any</span>
  <span m=''4329520''>2 to the</span> <span m=''4329660''>n by</span> <span m=''4329730''>2
  to the</span> <span m=''4329840''>n</span> <span m=''4330390''>region,</span> <span
  m=''4330670''>we</span> <span m=''4330740''>could</span> <span m=''4330870''>tile</span>
  <span m=''4331270''>it with</span> <span m=''4331400''>a</span> <span m=''4331460''>corner,</span>
  <span m=''4331940''>Bill in</span> <span m=''4332230''>a</span> <span m=''4332280''>corner,</span>
  <span m=''4332910''>any</span> <span m=''4333050''>corner</span> <span m=''4333310''>square</span>
  <span m=''4333510''>missing.</span> </p><p><span m=''4335480''>Good,</span> <span
  m=''4336010''>so</span> <span m=''4336410''>now</span> <span m=''4336600''>you</span>
  <span m=''4336750''>want</span> <span m=''4336890''>to</span> <span m=''4336960''>say,</span>
  <span m=''4337200''>I</span> <span m=''4337310''>can</span> <span m=''4337480''>get</span>
  <span m=''4337680''>Bill</span> <span m=''4337880''>in</span> <span m=''4337940''>the</span>
  <span m=''4338010''>middle.</span> <span m=''4338910''>And</span> <span m=''4339100''>what</span>
  <span m=''4339240''>you</span> <span m=''4339330''>want</span> <span m=''4339560''>to</span>
  <span m=''4339630''>say</span> <span m=''4339900''>is</span> <span m=''4340040''>OK,</span>
  <span m=''4340400''>I</span> <span m=''4340510''>tile</span> <span m=''4340910''>this</span>
  <span m=''4341140''>region</span> <span m=''4342330''>with</span> <span m=''4343000''>Bill</span>
  <span m=''4343380''>here,</span> <span m=''4344090''>in</span> <span m=''4344190''>a</span>
  <span m=''4344270''>2</span> <span m=''4344460''>to</span> <span m=''4344530''>the</span>
  <span m=''4344680''>n</span> <span m=''4344880''>by--</span> <span m=''4350540''>maybe</span>
  <span m=''4350780''>you''re</span> <span m=''4350840''>right.</span> <span m=''4351090''>So</span>
  <span m=''4351180''>then</span> <span m=''4351360''>I</span> <span m=''4351410''>would</span>
  <span m=''4351530''>apply</span> <span m=''4352580''>the</span> <span m=''4352700''>theorem</span>
  <span m=''4353200''>here,</span> <span m=''4353650''>with</span> <span m=''4353780''>Bill</span>
  <span m=''4354000''>here.</span> <span m=''4355150''>Oh,</span> <span m=''4355290''>Bill</span>
  <span m=''4355480''>here.</span> <span m=''4355940''>No,</span> <span m=''4356020''>I</span>
  <span m=''4356150''>think</span> <span m=''4356320''>I</span> <span m=''4356390''>like</span>
  <span m=''4356620''>it</span> <span m=''4356720''>now.</span> </p><p><span m=''4357860''>And</span>
  <span m=''4357980''>then</span> <span m=''4358120''>I</span> <span m=''4358190''>would</span>
  <span m=''4358360''>take</span> <span m=''4358570''>these</span> <span m=''4358810''>out.</span>
  </p><p><span m=''4359546''>AUDIENCE: [INAUDIBLE]</span> <span m=''4363274''>just
  takes up</span> <span m=''4363740''>up three</span> <span m=''4364130''>blocks.</span>
  <span m=''4365044''>And</span> <span m=''4365958''>that big</span> <span m=''4366415''>square</span>
  <span m=''4366872''>is</span> <span m=''4367329''>just</span> <span m=''4367790''>like</span>
  <span m=''4368920''>a zoomed</span> <span m=''4369300''>out version</span> <span
  m=''4369780''>of a</span> <span m=''4370260''>little</span> <span m=''4370740''>square.</span>
  <span m=''4372660''>And since you know</span> <span m=''4373140''>that</span> <span
  m=''4373620''>little</span> <span m=''4374100''>square</span> <span m=''4374580''>fits
  in</span> <span m=''4375060''>a</span> <span m=''4375550''>2 by</span> <span m=''4375720''>2--</span>
  <span m=''4375980''>like</span> <span m=''4376240''>for example</span> <span m=''4377668''>in
  the</span> <span m=''4380700''>4 by 4</span> <span m=''4382760''>case.</span> <span
  m=''4384240''>We proved</span> <span m=''4384740''>the 2 by 2</span> <span m=''4385800''>case.</span>
  <span m=''4386470''>In the 4</span> <span m=''4386670''>by 4</span> <span m=''4386840''>case</span>
  <span m=''4388886''>you</span> <span m=''4389368''>have</span> <span m=''4389850''>a</span>
  <span m=''4390430''>big</span> <span m=''4390870''>size.</span> <span m=''4391235''>It''s</span>
  <span m=''4391600''>just</span> <span m=''4391900''>like</span> <span m=''4392320''>a--</span>
  <span m=''4393540''>you have four squares,</span> <span m=''4394010''>right?</span>
  </p><p><span m=''4394770''>And each</span> <span m=''4395231''>of those</span> <span
  m=''4395692''>four</span> <span m=''4396153''>squares</span> <span m=''4396614''>has</span>
  <span m=''4397075''>[INAUDIBLE].</span> <span m=''4398919''>So you take</span> <span
  m=''4399850''>that</span> <span m=''4401390''>top</span> <span m=''4401790''>right</span>
  <span m=''4402190''>square</span> <span m=''4402940''>and</span> <span m=''4403260''>you
  put</span> <span m=''4403640''>Bill</span> <span m=''4403965''>within</span> <span
  m=''4404290''>the</span> <span m=''4404718''>smaller</span> <span m=''4406430''>square</span>
  <span m=''4407560''>exactly</span> <span m=''4407900''>where you</span> <span m=''4408470''>want</span>
  <span m=''4408840''>him to</span> <span m=''4408940''>be.</span> <span m=''4409430''>And
  then</span> <span m=''4409800''>you fill</span> <span m=''4410170''>those</span>
  <span m=''4410750''>other--</span> <span m=''4411380''>all those</span> <span m=''4411850''>empty</span>
  <span m=''4412360''>spaces.</span> </p><p><span m=''4413410''>PROFESSOR: I</span>
  <span m=''4413700''>agree.</span> <span m=''4414390''>You</span> <span m=''4414550''>could
  make</span> <span m=''4414710''>a</span> <span m=''4414970''>proof.</span> <span
  m=''4415300''>So</span> <span m=''4415440''>in</span> <span m=''4415500''>this</span>
  <span m=''4415710''>case</span> <span m=''4415960''>you''d</span> <span m=''4416070''>make</span>
  <span m=''4416310''>a</span> <span m=''4416360''>Lemma</span> <span m=''4417860''>that</span>
  <span m=''4418000''>uses</span> <span m=''4418330''>induction</span> <span m=''4419580''>that</span>
  <span m=''4419720''>says</span> <span m=''4420170''>you</span> <span m=''4420290''>can</span>
  <span m=''4420470''>do it</span> <span m=''4420770''>with</span> <span m=''4420800''>Bill</span>
  <span m=''4421050''>in</span> <span m=''4421090''>the</span> <span m=''4421190''>corner.</span>
  <span m=''4422350''>And</span> <span m=''4422460''>then</span> <span m=''4422580''>as</span>
  <span m=''4422690''>a</span> <span m=''4422750''>corollary</span> <span m=''4423400''>or
  a</span> <span m=''4423570''>theorem</span> <span m=''4424080''>you''d</span> <span
  m=''4424260''>take</span> <span m=''4424530''>that</span> <span m=''4425840''>and</span>
  <span m=''4425990''>apply</span> <span m=''4426390''>it</span> <span m=''4426520''>to</span>
  <span m=''4426620''>four</span> <span m=''4427750''>sub-squares.</span> <span m=''4428980''>Put</span>
  <span m=''4429210''>Bill</span> <span m=''4429570''>in</span> <span m=''4429660''>here.</span>
  <span m=''4430970''>Take</span> <span m=''4431190''>these</span> <span m=''4431430''>out.</span>
  <span m=''4432030''>And</span> <span m=''4432160''>then</span> <span m=''4432230''>now
  you''d</span> <span m=''4432610''>have</span> <span m=''4432730''>your</span> <span
  m=''4432870''>result</span> <span m=''4433250''>of Bill</span> <span m=''4433500''>in
  the</span> <span m=''4433560''>center.</span> </p><p><span m=''4433900''>So that
  is</span> <span m=''4434080''>is</span> <span m=''4434210''>a</span> <span m=''4434270''>way</span>
  <span m=''4434400''>to</span> <span m=''4434510''>do</span> <span m=''4434720''>it.</span>
  <span m=''4435340''>It</span> <span m=''4435520''>ends</span> <span m=''4435710''>up</span>
  <span m=''4435800''>being</span> <span m=''4435970''>more</span> <span m=''4436210''>complicated.</span>
  <span m=''4436860''>There</span> <span m=''4437010''>is</span> <span m=''4437120''>a</span>
  <span m=''4437200''>simpler</span> <span m=''4437720''>approach.</span> <span m=''4438300''>But</span>
  <span m=''4438420''>that</span> <span m=''4438580''>is</span> <span m=''4438830''>a</span>
  <span m=''4439130''>way</span> <span m=''4439260''>that</span> <span m=''4439370''>works.</span>
  <span m=''4439870''>It is</span> <span m=''4440080''>a</span> <span m=''4440140''>natural</span>
  <span m=''4440470''>thing</span> <span m=''4440620''>you</span> <span m=''4440740''>would</span>
  <span m=''4440970''>do</span> <span m=''4441780''>if</span> <span m=''4441890''>you</span>
  <span m=''4441970''>had</span> <span m=''4442110''>this</span> <span m=''4442270''>on</span>
  <span m=''4442370''>homework.</span> <span m=''4443490''>Is</span> <span m=''4443560''>you''d</span>
  <span m=''4443670''>think</span> <span m=''4443890''>of</span> <span m=''4443970''>a</span>
  <span m=''4444040''>different</span> <span m=''4444520''>thing</span> <span m=''4444700''>to</span>
  <span m=''4444780''>prove</span> <span m=''4444980''>by</span> <span m=''4445130''>induction,</span>
  <span m=''4445980''>then</span> <span m=''4446130''>use</span> <span m=''4446330''>that</span>
  <span m=''4446530''>as</span> <span m=''4446640''>a</span> <span m=''4446700''>Lemma</span>
  <span m=''4447300''>to</span> <span m=''4447370''>get</span> <span m=''4447560''>you</span>
  <span m=''4447690''>where</span> <span m=''4447810''>you</span> <span m=''4447910''>wanted</span>
  <span m=''4448110''>to</span> <span m=''4448150''>go.</span> </p><p><span m=''4449540''>There''s</span>
  <span m=''4449730''>another</span> <span m=''4450000''>way</span> <span m=''4450140''>to</span>
  <span m=''4450250''>do</span> <span m=''4450410''>it</span> <span m=''4450520''>without</span>
  <span m=''4451300''>having</span> <span m=''4451590''>that</span> <span m=''4452050''>first</span>
  <span m=''4452360''>step.</span> <span m=''4454290''>And</span> <span m=''4454380''>that''s--</span>
  <span m=''4454700''>yeah?</span> </p><p><span m=''4456870''>AUDIENCE: That courtyard</span>
  <span m=''4457840''>where</span> <span m=''4458810''>n equals</span> <span m=''4459295''>2.</span>
  <span m=''4460750''>Divide</span> <span m=''4461235''>each</span> <span m=''4461720''>cell</span>
  <span m=''4462205''>into</span> <span m=''4462690''>a</span> <span m=''4463175''>2</span>
  <span m=''4463660''>by</span> <span m=''4464145''>2--</span> </p><p><span m=''4468530''>PROFESSOR:
  Yeah.</span> </p><p><span m=''4468820''>AUDIENCE: Something.</span> </p><p><span
  m=''4471180''>PROFESSOR: Well,</span> <span m=''4471640''>yeah.</span> <span m=''4473780''>You</span>
  <span m=''4473870''>want</span> <span m=''4473970''>to</span> <span m=''4474030''>do</span>
  <span m=''4474160''>it</span> <span m=''4474573''>bottoms</span> <span m=''4474986''>up.</span>
  <span m=''4475400''>You</span> <span m=''4475570''>want</span> <span m=''4475750''>to
  take</span> <span m=''4475870''>it and</span> <span m=''4476940''>make</span> <span
  m=''4477120''>that</span> <span m=''4477350''>your</span> <span m=''4478240''>inductive</span>
  <span m=''4478630''>step,</span> <span m=''4479280''>2</span> <span m=''4479450''>by</span>
  <span m=''4479600''>2''s</span> <span m=''4479850''>inside.</span> <span m=''4480310''>I</span>
  <span m=''4480330''>haven''t</span> <span m=''4480660''>thought</span> <span m=''4480890''>about</span>
  <span m=''4481090''>that</span> <span m=''4481230''>approach.</span> </p><p><span
  m=''4482272''>AUDIENCE: [INAUDIBLE]</span> <span m=''4494572''>So if you</span>
  <span m=''4495064''>could do</span> <span m=''4495556''>that then</span> <span m=''4496048''>you''re</span>
  <span m=''4496540''>all set</span> <span m=''4497032''>except</span> <span m=''4497524''>for
  the</span> <span m=''4498016''>2 by</span> <span m=''4498508''>2</span> <span m=''4500968''>where</span>
  <span m=''4501460''>Bill</span> <span m=''4501952''>was.</span> </p><p><span m=''4504440''>PROFESSOR:
  I''m</span> <span m=''4504740''>worried</span> <span m=''4505070''>about</span>
  <span m=''4505400''>a lot of</span> <span m=''4505740''>2 by 2''s</span> <span m=''4505920''>with</span>
  <span m=''4506670''>a corner</span> <span m=''4507083''>missing</span> <span m=''4507910''>if</span>
  <span m=''4508100''>I</span> <span m=''4508150''>do</span> <span m=''4508310''>it</span>
  <span m=''4508420''>that way.</span> <span m=''4508883''>I''ll think</span> <span
  m=''4509346''>about that.</span> <span m=''4511620''>There</span> <span m=''4511790''>is--</span>
  <span m=''4512180''>let</span> <span m=''4512290''>me</span> <span m=''4512420''>get</span>
  <span m=''4512590''>to</span> <span m=''4512810''>another</span> <span m=''4515020''>approach</span>
  <span m=''4515470''>here.</span> <span m=''4517510''>We</span> <span m=''4517640''>couldn''t</span>
  <span m=''4517990''>make</span> <span m=''4518160''>it</span> <span m=''4518220''>work</span>
  <span m=''4518420''>with</span> <span m=''4518520''>the</span> <span m=''4518610''>center.</span>
  <span m=''4519080''>We</span> <span m=''4519200''>could</span> <span m=''4519450''>make</span>
  <span m=''4519630''>it</span> <span m=''4519720''>work</span> <span m=''4519910''>with</span>
  <span m=''4520030''>a</span> <span m=''4520080''>corner.</span> <span m=''4520460''>But</span>
  <span m=''4520590''>then</span> <span m=''4520710''>we</span> <span m=''4520770''>had</span>
  <span m=''4520840''>to</span> <span m=''4520900''>do</span> <span m=''4521020''>more</span>
  <span m=''4521210''>work</span> <span m=''4521430''>after.</span> <span m=''4522960''>One</span>
  <span m=''4523490''>general</span> <span m=''4523940''>technique</span> <span m=''4524330''>to</span>
  <span m=''4524410''>use</span> <span m=''4524900''>with</span> <span m=''4525030''>induction,</span>
  <span m=''4525650''>when</span> <span m=''4525750''>you''re</span> <span m=''4525850''>having</span>
  <span m=''4526110''>struggling,</span> <span m=''4526690''>what''s</span> <span
  m=''4526990''>the</span> <span m=''4527090''>induction</span> <span m=''4527460''>hypothesis</span>
  <span m=''4528020''>to</span> <span m=''4528130''>use.</span> </p><p><span m=''4529140''>If</span>
  <span m=''4529310''>what</span> <span m=''4529460''>you''ve</span> <span m=''4529570''>got</span>
  <span m=''4529820''>doesn''t</span> <span m=''4530100''>work,</span> <span m=''4530930''>you</span>
  <span m=''4531030''>could</span> <span m=''4531180''>pick</span> <span m=''4531330''>a</span>
  <span m=''4531360''>different</span> <span m=''4531800''>one,</span> <span m=''4533040''>but</span>
  <span m=''4533220''>better</span> <span m=''4533700''>to</span> <span m=''4533810''>pick</span>
  <span m=''4533990''>a</span> <span m=''4534050''>stronger</span> <span m=''4534630''>one.</span>
  <span m=''4535180''>Yeah?</span> </p><p><span m=''4537031''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''4540930''>PROFESSOR: Yes.</span> <span m=''4542410''>You</span>
  <span m=''4542620''>could.</span> <span m=''4542890''>And</span> <span m=''4542990''>that</span>
  <span m=''4543140''>is</span> <span m=''4543220''>a</span> <span m=''4543290''>good</span>
  <span m=''4543520''>thing</span> <span m=''4543670''>to</span> <span m=''4543750''>do.</span>
  <span m=''4545110''>Make</span> <span m=''4545770''>the</span> <span m=''4545930''>induction</span>
  <span m=''4546780''>hypothesis</span> <span m=''4547680''>be</span> <span m=''4547830''>much</span>
  <span m=''4548040''>stronger.</span> <span m=''4550460''>I</span> <span m=''4550560''>had</span>
  <span m=''4550720''>trouble</span> <span m=''4551080''>proving</span> <span m=''4552010''>there''s</span>
  <span m=''4552180''>a</span> <span m=''4552240''>way</span> <span m=''4552400''>to</span>
  <span m=''4552500''>do</span> <span m=''4552670''>it</span> <span m=''4552810''>with</span>
  <span m=''4552960''>a</span> <span m=''4553050''>center</span> <span m=''4553430''>square</span>
  <span m=''4553700''>missing.</span> <span m=''4554880''>Turns</span> <span m=''4555160''>out</span>
  <span m=''4555280''>to</span> <span m=''4555360''>be</span> <span m=''4555520''>easier</span>
  <span m=''4556050''>to</span> <span m=''4556130''>prove</span> <span m=''4556450''>it</span>
  <span m=''4557710''>where</span> <span m=''4558100''>you</span> <span m=''4558280''>say</span>
  <span m=''4558530''>any</span> <span m=''4558850''>square</span> <span m=''4559190''>could</span>
  <span m=''4559300''>be</span> <span m=''4559390''>missing.</span> </p><p><span m=''4559890''>Seems</span>
  <span m=''4560190''>like</span> <span m=''4560310''>this</span> <span m=''4560430''>should</span>
  <span m=''4560550''>be</span> <span m=''4560640''>harder,</span> <span m=''4561060''>right?</span>
  <span m=''4561600''>We</span> <span m=''4561720''>had</span> <span m=''4561800''>a</span>
  <span m=''4561840''>hard enough</span> <span m=''4562110''>time</span> <span m=''4562310''>just</span>
  <span m=''4562460''>showing</span> <span m=''4562920''>this</span> <span m=''4563120''>square</span>
  <span m=''4563350''>missing</span> <span m=''4563650''>was</span> <span m=''4564060''>doable.</span>
  <span m=''4565250''>But</span> <span m=''4565400''>by</span> <span m=''4565520''>assuming</span>
  <span m=''4565970''>something--</span> <span m=''4566820''>by</span> <span m=''4566920''>trying</span>
  <span m=''4567120''>to</span> <span m=''4567180''>prove</span> <span m=''4567340''>a</span>
  <span m=''4567390''>harder</span> <span m=''4567850''>problem,</span> <span m=''4568260''>assuming</span>
  <span m=''4568570''>something</span> <span m=''4568830''>stronger</span> <span m=''4569220''>in</span>
  <span m=''4569310''>pn,</span> <span m=''4570330''>it</span> <span m=''4570440''>gets</span>
  <span m=''4570650''>easier</span> <span m=''4570960''>to</span> <span m=''4571040''>prove.</span>
  <span m=''4572680''>All</span> <span m=''4572790''>right,</span> <span m=''4572960''>now</span>
  <span m=''4573050''>we</span> <span m=''4573130''>better</span> <span m=''4573350''>check</span>
  <span m=''4573560''>the</span> <span m=''4573640''>base</span> <span m=''4573930''>case,</span>
  <span m=''4575700''>p0,</span> <span m=''4576140''>but</span> <span m=''4576250''>that''s</span>
  <span m=''4576450''>easy.</span> <span m=''4576900''>There''s</span> <span m=''4576960''>only</span>
  <span m=''4577120''>one</span> <span m=''4577290''>square</span> <span m=''4577550''>Bill</span>
  <span m=''4577750''>can be.</span> </p><p><span m=''4579960''>But</span> <span m=''4580060''>now</span>
  <span m=''4580270''>let''s</span> <span m=''4580520''>look</span> <span m=''4580670''>at</span>
  <span m=''4580760''>pn</span> <span m=''4581100''>implies</span> <span m=''4581480''>pn</span>
  <span m=''4581770''>plus</span> <span m=''4582010''>1.</span> <span m=''4586090''>So</span>
  <span m=''4586170''>we</span> <span m=''4586250''>go</span> <span m=''4586390''>back</span>
  <span m=''4586610''>to</span> <span m=''4586700''>this.</span> <span m=''4586930''>We''ve</span>
  <span m=''4587060''>got</span> <span m=''4587330''>a</span> <span m=''4587460''>2</span>
  <span m=''4587660''>to</span> <span m=''4587720''>the</span> <span m=''4587840''>n</span>
  <span m=''4588000''>plus</span> <span m=''4588230''>1</span> <span m=''4588460''>by</span>
  <span m=''4588580''>2</span> <span m=''4588750''>to</span> <span m=''4588800''>the</span>
  <span m=''4588890''>n</span> <span m=''4589000''>plus</span> <span m=''4589260''>1</span>
  <span m=''4590530''>courtyard.</span> <span m=''4592780''>And</span> <span m=''4593000''>now</span>
  <span m=''4593350''>Bill</span> <span m=''4593800''>can</span> <span m=''4593950''>be</span>
  <span m=''4594520''>anywhere.</span> <span m=''4598030''>Put</span> <span m=''4598180''>him</span>
  <span m=''4598750''>here.</span> <span m=''4599750''>There''s</span> <span m=''4599980''>Bill.</span>
  </p><p><span m=''4602420''>Now</span> <span m=''4602690''>I''m</span> <span m=''4602820''>going</span>
  <span m=''4602930''>to</span> <span m=''4602990''>place</span> <span m=''4603270''>my</span>
  <span m=''4603390''>first</span> <span m=''4603760''>l-shaped</span> <span m=''4604260''>tile</span>
  <span m=''4604550''>here,</span> <span m=''4605660''>in</span> <span m=''4605760''>the</span>
  <span m=''4605850''>other</span> <span m=''4606000''>three</span> <span m=''4606240''>regions.</span>
  <span m=''4609000''>And</span> <span m=''4609170''>now</span> <span m=''4609360''>I</span>
  <span m=''4609450''>apply</span> <span m=''4609820''>pn</span> <span m=''4610185''>to</span>
  <span m=''4610550''>each</span> <span m=''4610740''>region.</span> <span m=''4612710''>A</span>
  <span m=''4612840''>pn</span> <span m=''4613290''>says</span> <span m=''4613510''>I</span>
  <span m=''4613570''>can</span> <span m=''4613740''>do</span> <span m=''4614000''>it</span>
  <span m=''4614090''>with any</span> <span m=''4614340''>square</span> <span m=''4614610''>missing.</span>
  <span m=''4614950''>So</span> <span m=''4615070''>I''ll</span> <span m=''4615170''>pick</span>
  <span m=''4615370''>this</span> <span m=''4615540''>one</span> <span m=''4615690''>out</span>
  <span m=''4615820''>here,</span> <span m=''4616620''>this</span> <span m=''4616800''>one</span>
  <span m=''4616930''>out</span> <span m=''4617080''>here,</span> <span m=''4617540''>that</span>
  <span m=''4617760''>one</span> <span m=''4617920''>there,</span> <span m=''4618260''>that</span>
  <span m=''4618450''>one</span> <span m=''4618570''>there.</span> <span m=''4619520''>And</span>
  <span m=''4619650''>now</span> <span m=''4619800''>I''m</span> <span m=''4619940''>done.</span>
  </p><p><span m=''4621080''>That</span> <span m=''4621330''>was</span> <span m=''4621460''>easy.</span>
  <span m=''4622720''>No</span> <span m=''4622910''>extra</span> <span m=''4623200''>steps.</span>
  <span m=''4625650''>Now,</span> <span m=''4625780''>how</span> <span m=''4626090''>is</span>
  <span m=''4626200''>it</span> <span m=''4626310''>possible</span> <span m=''4626840''>that</span>
  <span m=''4626920''>it</span> <span m=''4626960''>was</span> <span m=''4627160''>easier</span>
  <span m=''4627630''>to</span> <span m=''4627720''>prove</span> <span m=''4628050''>something</span>
  <span m=''4628340''>that</span> <span m=''4628430''>was</span> <span m=''4629340''>harder?</span>
  <span m=''4631370''>Yeah?</span> </p><p><span m=''4633706''>AUDIENCE: First</span>
  <span m=''4634180''>need to be</span> <span m=''4634654''>in the center</span> <span
  m=''4635128''>[INAUDIBLE],</span> <span m=''4635602''>you''re</span> <span m=''4636076''>putting</span>
  <span m=''4636550''>another constraint</span> <span m=''4637024''>on yourself.</span>
  </p><p><span m=''4637500''>PROFESSOR: Yes.</span> <span m=''4638840''>That</span>
  <span m=''4639030''>is</span> <span m=''4639170''>true.</span> <span m=''4639470''>But</span>
  <span m=''4640280''>by</span> <span m=''4640770''>allowing</span> <span m=''4641190''>him
  to</span> <span m=''4641240''>be</span> <span m=''4641440''>anywhere,</span> <span
  m=''4642440''>I</span> <span m=''4642540''>could</span> <span m=''4642690''>have</span>
  <span m=''4642770''>started--</span> <span m=''4644200''>I</span> <span m=''4644330''>have</span>
  <span m=''4644550''>to--</span> <span m=''4644700''>that''s</span> <span m=''4644900''>a</span>
  <span m=''4644950''>possibility.</span> <span m=''4648220''>See,</span> <span m=''4648260''>what</span>
  <span m=''4648380''>I''m</span> <span m=''4648480''>trying</span> <span m=''4648730''>to</span>
  <span m=''4648810''>do</span> <span m=''4649020''>here,</span> <span m=''4650420''>this</span>
  <span m=''4650650''>inductive</span> <span m=''4651070''>step</span> <span m=''4651350''>is</span>
  <span m=''4651470''>all</span> <span m=''4651710''>about</span> <span m=''4652010''>proving</span>
  <span m=''4652370''>pn</span> <span m=''4653690''>implies</span> <span m=''4654130''>pn</span>
  <span m=''4654480''>plus</span> <span m=''4654720''>1</span> <span m=''4654920''>is</span>
  <span m=''4655020''>true.</span> <span m=''4657380''>That''s</span> <span m=''4657630''>what</span>
  <span m=''4657700''>I''m</span> <span m=''4657780''>trying</span> <span m=''4658000''>to</span>
  <span m=''4658060''>show.</span> </p><p><span m=''4660130''>Now,</span> <span m=''4660470''>how</span>
  <span m=''4660810''>is</span> <span m=''4660920''>it</span> <span m=''4661020''>useful</span>
  <span m=''4661420''>for</span> <span m=''4661660''>me</span> <span m=''4661870''>if</span>
  <span m=''4662020''>pn</span> <span m=''4662430''>is</span> <span m=''4662570''>stronger?</span>
  <span m=''4663840''>Has</span> <span m=''4664070''>more?</span> </p><p><span m=''4665826''>AUDIENCE:
  You</span> <span m=''4666290''>grow it.</span> <span m=''4667127''>You prove that</span>
  <span m=''4667504''>he can</span> <span m=''4667881''>be in a</span> <span m=''4668260''>corner.</span>
  <span m=''4668515''>But</span> <span m=''4668770''>when</span> <span m=''4669210''>you
  grow</span> <span m=''4669370''>it,</span> <span m=''4669890''>the</span> <span
  m=''4669980''>corner</span> <span m=''4670425''>moves.</span> <span m=''4671100''>But</span>
  <span m=''4671330''>since</span> <span m=''4671500''>we</span> <span m=''4671630''>proved</span>
  <span m=''4671850''>that it can</span> <span m=''4672345''>be in any,</span> <span
  m=''4672840''>it''s fine</span> <span m=''4673320''>if it</span> <span m=''4673800''>moves.</span>
  </p><p><span m=''4674280''>PROFESSOR: Exactly.</span> <span m=''4674575''>That''s
  exactly</span> <span m=''4674870''>right.</span> <span m=''4676420''>ph</span> <span
  m=''4676910''>got</span> <span m=''4677050''>more</span> <span m=''4677240''>powerful,</span>
  <span m=''4679410''>which</span> <span m=''4679650''>means</span> <span m=''4680150''>I</span>
  <span m=''4680260''>get</span> <span m=''4680460''>more</span> <span m=''4680750''>to</span>
  <span m=''4680850''>assume</span> <span m=''4681220''>here.</span> <span m=''4682560''>In</span>
  <span m=''4682700''>the</span> <span m=''4682780''>recursive</span> <span m=''4683270''>problem,</span>
  <span m=''4684340''>Bill</span> <span m=''4684680''>can</span> <span m=''4684790''>be</span>
  <span m=''4684920''>anywhere</span> <span m=''4685240''>now.</span> <span m=''4686250''>It
  gives</span> <span m=''4686390''>me</span> <span m=''4686500''>more</span> <span
  m=''4686690''>power.</span> <span m=''4687040''>I</span> <span m=''4687080''>can</span>
  <span m=''4687260''>tile</span> <span m=''4687630''>any</span> <span m=''4687890''>courtyard</span>
  <span m=''4689480''>with</span> <span m=''4689640''>any</span> <span m=''4689850''>square</span>
  <span m=''4690100''>missing.</span> <span m=''4690750''>This</span> <span m=''4690980''>is</span>
  <span m=''4691080''>more</span> <span m=''4691260''>powerful.</span> <span m=''4691810''>So</span>
  <span m=''4691910''>this</span> <span m=''4692130''>got</span> <span m=''4692570''>more</span>
  <span m=''4692730''>powerful.</span> <span m=''4693790''>So</span> <span m=''4694080''>did</span>
  <span m=''4694260''>this.</span> </p><p><span m=''4695440''>So</span> <span m=''4695600''>what</span>
  <span m=''4695760''>it</span> <span m=''4695900''>means</span> <span m=''4696210''>is</span>
  <span m=''4696300''>that my</span> <span m=''4696450''>tool</span> <span m=''4696850''>set</span>
  <span m=''4697790''>is</span> <span m=''4697960''>bigger</span> <span m=''4698890''>with</span>
  <span m=''4699030''>a</span> <span m=''4699080''>stronger</span> <span m=''4699460''>pn.</span>
  <span m=''4700450''>And</span> <span m=''4700660''>what</span> <span m=''4700750''>I''m</span>
  <span m=''4700840''>trying</span> <span m=''4701170''>to</span> <span m=''4701240''>construct</span>
  <span m=''4701510''>or</span> <span m=''4701780''>prove</span> <span m=''4702620''>got</span>
  <span m=''4702760''>harder.</span> <span m=''4704240''>And</span> <span m=''4704440''>sometimes,</span>
  <span m=''4706820''>if</span> <span m=''4706970''>I''ve</span> <span m=''4707110''>got</span>
  <span m=''4707300''>more</span> <span m=''4707500''>tools,</span> <span m=''4708430''>it</span>
  <span m=''4708550''>becomes</span> <span m=''4708840''>easier</span> <span m=''4709170''>to</span>
  <span m=''4709260''>prove,</span> <span m=''4709590''>even</span> <span m=''4709780''>a</span>
  <span m=''4709830''>harder</span> <span m=''4710140''>thing.</span> </p><p><span
  m=''4711750''>And</span> <span m=''4711880''>so</span> <span m=''4712010''>a</span>
  <span m=''4712050''>general</span> <span m=''4712430''>rule</span> <span m=''4712720''>with</span>
  <span m=''4712810''>induction</span> <span m=''4713960''>is</span> <span m=''4714160''>if</span>
  <span m=''4714640''>you</span> <span m=''4714770''>don''t</span> <span m=''4715300''>first</span>
  <span m=''4715590''>succeed,</span> <span m=''4716120''>try,</span> <span m=''4716390''>try</span>
  <span m=''4716570''>again.</span> <span m=''4716920''>Well,</span> <span m=''4717030''>the</span>
  <span m=''4717110''>rule with</span> <span m=''4717290''>induction</span> <span
  m=''4717740''>is</span> <span m=''4717900''>if you</span> <span m=''4718000''>don''t</span>
  <span m=''4718190''>succeed</span> <span m=''4718500''>at</span> <span m=''4718560''>first,</span>
  <span m=''4719130''>try</span> <span m=''4719310''>something</span> <span m=''4719600''>harder.</span>
  <span m=''4721310''>All</span> <span m=''4721410''>right?</span> <span m=''4722070''>And</span>
  <span m=''4722350''>it''s</span> <span m=''4722460''>amazing,</span> <span m=''4723010''>but</span>
  <span m=''4723170''>it</span> <span m=''4723350''>actually</span> <span m=''4723870''>works</span>
  <span m=''4724270''>a</span> <span m=''4724320''>lot</span> <span m=''4724610''>of</span>
  <span m=''4724670''>time,</span> <span m=''4725110''>as</span> <span m=''4725280''>it</span>
  <span m=''4725490''>did</span> <span m=''4725700''>here.</span> <span m=''4727010''>If</span>
  <span m=''4727190''>I</span> <span m=''4727270''>don''t</span> <span m=''4727470''>assume</span>
  <span m=''4727770''>something</span> <span m=''4728470''>strong</span> <span m=''4728920''>enough,</span>
  <span m=''4729930''>and</span> <span m=''4730080''>pn is</span> <span m=''4730460''>some</span>
  <span m=''4730890''>little</span> <span m=''4731130''>weak</span> <span m=''4731410''>thing</span>
  <span m=''4731650''>like</span> <span m=''4731850''>Bill</span> <span m=''4732090''>just</span>
  <span m=''4732320''>in</span> <span m=''4732930''>the</span> <span m=''4733010''>center,</span>
  <span m=''4734100''>it''s</span> <span m=''4734300''>not</span> <span m=''4734510''>enough</span>
  <span m=''4734750''>to</span> <span m=''4734860''>go</span> <span m=''4735040''>anywhere.</span>
  </p><p><span m=''4737120''>But</span> <span m=''4737230''>if</span> <span m=''4737320''>I</span>
  <span m=''4737390''>could</span> <span m=''4737520''>assume</span> <span m=''4737830''>a</span>
  <span m=''4737880''>lot</span> <span m=''4738120''>more,</span> <span m=''4738520''>like</span>
  <span m=''4738750''>Bill</span> <span m=''4738940''>could</span> <span m=''4739050''>be</span>
  <span m=''4739270''>anywhere</span> <span m=''4739860''>he</span> <span m=''4740030''>pleases.</span>
  <span m=''4741680''>Then</span> <span m=''4741930''>I</span> <span m=''4741990''>could</span>
  <span m=''4742150''>prove</span> <span m=''4742380''>lots</span> <span m=''4742650''>of</span>
  <span m=''4742770''>things</span> <span m=''4743520''>here.</span> <span m=''4746200''>So</span>
  <span m=''4746350''>it''s all</span> <span m=''4746690''>the</span> <span m=''4746820''>art--</span>
  <span m=''4747100''>and</span> <span m=''4747190''>you''re</span> <span m=''4747350''>going
  to learn</span> <span m=''4747660''>this over</span> <span m=''4747790''>the</span>
  <span m=''4747890''>next</span> <span m=''4748090''>several</span> <span m=''4748320''>weeks--</span>
  <span m=''4748530''>it''s</span> <span m=''4748670''>all</span> <span m=''4748980''>the</span>
  <span m=''4749120''>art</span> <span m=''4750050''>of</span> <span m=''4750190''>what''s</span>
  <span m=''4750380''>your</span> <span m=''4750540''>induction</span> <span m=''4750910''>hypothesis.</span>
  <span m=''4752650''>Picking</span> <span m=''4752850''>a</span> <span m=''4752970''>good</span>
  <span m=''4753180''>one,</span> <span m=''4753400''>life</span> <span m=''4753650''>is</span>
  <span m=''4753790''>easy.</span> <span m=''4754110''>Picking</span> <span m=''4754970''>the</span>
  <span m=''4755110''>wrong</span> <span m=''4755400''>one,</span> <span m=''4756010''>very</span>
  <span m=''4756230''>painful,</span> <span m=''4757140''>as</span> <span m=''4757300''>you''ll</span>
  <span m=''4757420''>see</span> <span m=''4757580''>with</span> <span m=''4757710''>beaver</span>
  <span m=''4757980''>flu.</span> <span m=''4759830''>OK,</span> <span m=''4760170''>that''s</span>
  <span m=''4760400''>it</span> <span m=''4760510''>for</span> <span m=''4760630''>today.</span>
  </p>'
type: course
uid: 538a5a75a30978324d0ba06505eff624

---
None