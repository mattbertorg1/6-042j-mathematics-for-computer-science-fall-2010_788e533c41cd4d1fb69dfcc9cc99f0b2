---
about_this_resource_text: <p><strong>Description:</strong> Continues exploring expectation
  with a discussion of likelihood in cases of card games, bit transmission errors,
  and algorithms, and concludes with definitions of variance and standard deviation
  for random variables.</p> <p><strong>Speaker:</strong> Tom Leighton</p>
course_id: 6-042j-mathematics-for-computer-science-fall-2010
embedded_media:
- id: Video-YouTube-Stream
  media_location: oI9fMUqgfxY
  parent_uid: ffc3342feaa1ee9e66c8d6cdbb30ca8d
  title: Video-YouTube-Stream
  type: Video
  uid: 00cc25ea9d045ee384206da5483679a8
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/oI9fMUqgfxY/default.jpg
  parent_uid: ffc3342feaa1ee9e66c8d6cdbb30ca8d
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 46e816daac7c1e62a5e127410640dca3
- id: Video-iTunesU-MP4
  media_location: http://itunes.apple.com/us/itunes-u/lecture-23-expectation-ii/id503873536?i=110644971
  parent_uid: ffc3342feaa1ee9e66c8d6cdbb30ca8d
  title: Video-iTunes U-MP4
  type: Video
  uid: adf6e3b665c8cad1bdf8f9a4eea7bbaf
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT6.042JF10/MIT6_042JF10_lec23_300k.mp4
  parent_uid: ffc3342feaa1ee9e66c8d6cdbb30ca8d
  title: Video-Internet Archive-MP4
  type: Video
  uid: 8b7f04e5735d047ffbb7d214b18d400e
- id: 3Play-3PlayYouTubeid-MP4
  media_location: oI9fMUqgfxY
  parent_uid: ffc3342feaa1ee9e66c8d6cdbb30ca8d
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 6c3faef93f8c6b0e0001a4289ad64146
- id: oI9fMUqgfxY.srt
  parent_uid: ffc3342feaa1ee9e66c8d6cdbb30ca8d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/lecture-23-expectation-ii/oI9fMUqgfxY.srt
  title: 3play caption file
  type: null
  uid: d6af25e59476fede9a1a2dda059b5a26
- id: oI9fMUqgfxY.pdf
  parent_uid: ffc3342feaa1ee9e66c8d6cdbb30ca8d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/lecture-23-expectation-ii/oI9fMUqgfxY.pdf
  title: 3play pdf file
  type: null
  uid: dc4f198af215cde514be1c46c806d063
- id: Caption-3Play YouTube id-SRT
  parent_uid: ffc3342feaa1ee9e66c8d6cdbb30ca8d
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: c9f2099beba6be5202a5b05babb6b449
- id: Transcript-3Play YouTube id-PDF
  parent_uid: ffc3342feaa1ee9e66c8d6cdbb30ca8d
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 0cba4e7a01329ab9a414f3e238c531c5
inline_embed_id: 37177022lecture23:expectationii59556567
layout: video
order_index: null
parent_uid: 7e5e792254d703550b60881541fa6160
related_resources_text: ''
short_url: lecture-23-expectation-ii
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/lecture-23-expectation-ii
template_type: Tabbed
title: 'Lecture 23: Expectation II'
transcript: '<p><span m=''380''>The</span> <span m=''510''>following</span> <span
  m=''950''>content</span> <span m=''1540''>is</span> <span m=''1660''>provided</span>
  <span m=''2100''>under</span> <span m=''2380''>a</span> <span m=''2420''>Creative</span>
  <span m=''2820''>Commons</span> <span m=''3230''>license.</span> <span m=''4340''>Your</span>
  <span m=''4520''>support</span> <span m=''5030''>will</span> <span m=''5190''>help</span>
  <span m=''5430''>MIT</span> <span m=''5880''>OpenCourseWare</span> <span m=''6670''>continue</span>
  <span m=''7180''>to</span> <span m=''7270''>offer</span> <span m=''7680''>high</span>
  <span m=''7910''>quality</span> <span m=''8440''>educational</span> <span m=''9060''>resources</span>
  <span m=''9690''>for</span> <span m=''9840''>free.</span> <span m=''11040''>To</span>
  <span m=''11050''>make</span> <span m=''11250''>a</span> <span m=''11300''>donation</span>
  <span m=''11990''>or</span> <span m=''12250''>view</span> <span m=''12690''>additional</span>
  <span m=''13120''>materials</span> <span m=''13650''>from</span> <span m=''13800''>hundreds</span>
  <span m=''14240''>of</span> <span m=''14350''>MIT</span> <span m=''14780''>courses,</span>
  <span m=''15890''>visit</span> <span m=''16100''>MIT</span> <span m=''16520''>OpenCourseWare</span>
  <span m=''17570''>at</span> <span m=''17740''>ocw.mit.edu.</span> </p><p></p><p><span
  m=''23540''>PROFESSOR: Last</span> <span m=''23830''>time</span> <span m=''24050''>we</span>
  <span m=''24150''>defined</span> <span m=''24620''>the</span> <span m=''24710''>expected</span>
  <span m=''25280''>value</span> <span m=''25620''>of</span> <span m=''25690''>a</span>
  <span m=''25800''>random</span> <span m=''26150''>variable.</span> <span m=''27030''>And</span>
  <span m=''27180''>we</span> <span m=''27300''>talked</span> <span m=''27590''>about</span>
  <span m=''27760''>a</span> <span m=''27820''>lot</span> <span m=''28170''>of</span>
  <span m=''28290''>ways</span> <span m=''28750''>it</span> <span m=''28830''>could</span>
  <span m=''28930''>be</span> <span m=''29040''>computed.</span> <span m=''29570''>We</span>
  <span m=''30010''>proved</span> <span m=''30320''>all</span> <span m=''30460''>sorts</span>
  <span m=''30700''>of</span> <span m=''30770''>equivalent</span> <span m=''31310''>definitions.</span>
  </p><p><span m=''33090''>Today,</span> <span m=''33390''>we''re</span> <span m=''33510''>going</span>
  <span m=''33610''>to</span> <span m=''33670''>keep</span> <span m=''33880''>talking</span>
  <span m=''34250''>about</span> <span m=''34460''>expectation.</span> <span m=''35730''>And</span>
  <span m=''35930''>we''re</span> <span m=''36020''>going</span> <span m=''36110''>to</span>
  <span m=''36170''>start</span> <span m=''36580''>with</span> <span m=''36730''>an</span>
  <span m=''36790''>example</span> <span m=''37330''>that</span> <span m=''38970''>talks</span>
  <span m=''39290''>about</span> <span m=''39860''>the</span> <span m=''40040''>expected</span>
  <span m=''40660''>number</span> <span m=''40930''>of</span> <span m=''41030''>events</span>
  <span m=''42030''>that</span> <span m=''42450''>you</span> <span m=''42600''>expect</span>
  <span m=''42930''>to</span> <span m=''42990''>have</span> <span m=''43200''>occur.</span>
  <span m=''43770''>And</span> <span m=''43920''>it''s</span> <span m=''44060''>a</span>
  <span m=''44130''>generalization</span> <span m=''45020''>of</span> <span m=''45070''>what</span>
  <span m=''45200''>we</span> <span m=''45310''>did</span> <span m=''45650''>with</span>
  <span m=''46240''>Chinese</span> <span m=''46690''>appetizer</span> <span m=''47510''>and</span>
  <span m=''47670''>hat</span> <span m=''47980''>check</span> <span m=''48270''>from</span>
  <span m=''48420''>last</span> <span m=''48720''>time.</span> </p><p><span m=''50946''>We''re</span>
  <span m=''51440''>going</span> <span m=''51570''>to</span> <span m=''51630''>call</span>
  <span m=''51920''>this</span> <span m=''52180''>theorem</span> <span m=''52520''>1.</span>
  <span m=''55600''>If</span> <span m=''55770''>you</span> <span m=''55890''>have</span>
  <span m=''56200''>a</span> <span m=''56270''>probability</span> <span m=''57010''>space,</span>
  <span m=''58990''>s,</span> <span m=''66360''>and</span> <span m=''66860''>you''ve</span>
  <span m=''66990''>got</span> <span m=''67150''>a</span> <span m=''67210''>collection</span>
  <span m=''67730''>of</span> <span m=''67820''>n</span> <span m=''67970''>events,</span>
  <span m=''70860''>let''s</span> <span m=''71060''>call</span> <span m=''71360''>them</span>
  <span m=''72050''>A1</span> <span m=''72550''>through</span> <span m=''72820''>A</span>
  <span m=''73110''>n,</span> <span m=''79560''>and</span> <span m=''79750''>these</span>
  <span m=''79960''>are</span> <span m=''80020''>just</span> <span m=''80310''>subsets</span>
  <span m=''80840''>of</span> <span m=''80950''>s,</span> <span m=''83490''>then</span>
  <span m=''83730''>the</span> <span m=''83870''>expected</span> <span m=''84540''>number</span>
  <span m=''85540''>of</span> <span m=''85640''>events</span> <span m=''86010''>to</span>
  <span m=''86160''>occur,</span> <span m=''91750''>of</span> <span m=''91920''>these</span>
  <span m=''92170''>events,</span> <span m=''102370''>is</span> <span m=''102570''>simply</span>
  <span m=''104150''>the</span> <span m=''104270''>sum</span> <span m=''105260''>of</span>
  <span m=''105480''>i</span> <span m=''105740''>equals</span> <span m=''106010''>1</span>
  <span m=''106290''>to</span> <span m=''106400''>n</span> <span m=''107375''>of</span>
  <span m=''107820''>the</span> <span m=''108030''>probability</span> <span m=''109980''>of</span>
  <span m=''110060''>the</span> <span m=''110210''>i-th</span> <span m=''110440''>event</span>
  <span m=''110760''>occurring.</span> <span m=''112610''>So</span> <span m=''112760''>you</span>
  <span m=''112930''>just</span> <span m=''113130''>sum</span> <span m=''113420''>up</span>
  <span m=''113550''>the</span> <span m=''113650''>probabilities</span> <span m=''114380''>that</span>
  <span m=''114520''>the</span> <span m=''114680''>events</span> <span m=''115030''>occur.</span>
  <span m=''116250''>And</span> <span m=''116530''>that</span> <span m=''116780''>tells</span>
  <span m=''117120''>you</span> <span m=''117250''>the</span> <span m=''117420''>expected</span>
  <span m=''118160''>number</span> <span m=''118400''>of</span> <span m=''118480''>events</span>
  <span m=''119010''>that</span> <span m=''119160''>will</span> <span m=''119400''>occur.</span>
  <span m=''120185''>So</span> <span m=''120620''>a</span> <span m=''120690''>very</span>
  <span m=''121040''>simple</span> <span m=''121470''>formula.</span> </p><p><span
  m=''123320''>So</span> <span m=''123500''>for</span> <span m=''123630''>example,</span>
  <span m=''124790''>A</span> <span m=''125100''>i</span> <span m=''125640''>might</span>
  <span m=''126080''>be</span> <span m=''126200''>the</span> <span m=''126350''>event</span>
  <span m=''126730''>if</span> <span m=''126800''>the</span> <span m=''126970''>i-th</span>
  <span m=''127310''>man</span> <span m=''127730''>gets</span> <span m=''127960''>the</span>
  <span m=''128070''>right</span> <span m=''128699''>hat</span> <span m=''129000''>back</span>
  <span m=''129550''>from</span> <span m=''129720''>last</span> <span m=''130000''>time.</span>
  <span m=''130829''>Or</span> <span m=''131240''>it</span> <span m=''131320''>could</span>
  <span m=''131630''>be</span> <span m=''131890''>the</span> <span m=''132050''>event</span>
  <span m=''132390''>if</span> <span m=''132460''>the</span> <span m=''132600''>i-th</span>
  <span m=''132940''>person</span> <span m=''133340''>gets</span> <span m=''133570''>the</span>
  <span m=''133690''>right</span> <span m=''134130''>appetizer</span> <span m=''134800''>back</span>
  <span m=''135110''>at</span> <span m=''135190''>the</span> <span m=''135280''>Chinese</span>
  <span m=''135680''>restaurant</span> <span m=''136140''>after</span> <span m=''136370''>we</span>
  <span m=''136990''>spin</span> <span m=''137620''>the</span> <span m=''137830''>wheel</span>
  <span m=''138070''>in</span> <span m=''138130''>the</span> <span m=''138230''>center.</span>
  <span m=''140320''>So</span> <span m=''140820''>we''re</span> <span m=''140950''>going</span>
  <span m=''141030''>to</span> <span m=''141080''>prove</span> <span m=''141450''>this.</span>
  <span m=''141890''>And</span> <span m=''141990''>the</span> <span m=''142090''>proof</span>
  <span m=''142240''>is</span> <span m=''142400''>very</span> <span m=''142660''>similar</span>
  <span m=''143100''>to</span> <span m=''143150''>what</span> <span m=''143270''>we</span>
  <span m=''143360''>did</span> <span m=''143510''>last</span> <span m=''143820''>time</span>
  <span m=''144520''>when</span> <span m=''144740''>we</span> <span m=''144850''>figured</span>
  <span m=''145130''>out</span> <span m=''145290''>the</span> <span m=''145400''>expected</span>
  <span m=''145870''>number</span> <span m=''146100''>of</span> <span m=''146170''>people</span>
  <span m=''146510''>to</span> <span m=''146570''>get</span> <span m=''146770''>the</span>
  <span m=''146870''>right</span> <span m=''147080''>hat</span> <span m=''147340''>back.</span>
  </p><p><span m=''148350''>In</span> <span m=''148550''>particular,</span> <span
  m=''149600''>we''re</span> <span m=''149690''>going</span> <span m=''149770''>to</span>
  <span m=''149840''>start</span> <span m=''150390''>by</span> <span m=''151320''>setting</span>
  <span m=''151700''>up</span> <span m=''151810''>an</span> <span m=''151910''>indicator</span>
  <span m=''152500''>variable,</span> <span m=''153140''>T</span> <span m=''153340''>sub</span>
  <span m=''153490''>i,</span> <span m=''154570''>that</span> <span m=''154730''>tells</span>
  <span m=''155190''>us</span> <span m=''155360''>whether</span> <span m=''155800''>or</span>
  <span m=''155830''>not</span> <span m=''156160''>the</span> <span m=''156320''>i-th</span>
  <span m=''156620''>event,</span> <span m=''157550''>A sub</span> <span m=''157870''>i</span>
  <span m=''158270''>occurs.</span> <span m=''162710''>So</span> <span m=''162900''>we</span>
  <span m=''163000''>define</span> <span m=''164240''>T</span> <span m=''164780''>sub</span>
  <span m=''164930''>i--</span> <span m=''166380''>and</span> <span m=''166550''>it''s</span>
  <span m=''166670''>a</span> <span m=''166730''>function</span> <span m=''167190''>of</span>
  <span m=''167540''>a</span> <span m=''167610''>sample</span> <span m=''168030''>point--</span>
  <span m=''170400''>to</span> <span m=''170550''>be</span> <span m=''170700''>1</span>
  <span m=''172430''>if</span> <span m=''173300''>the</span> <span m=''173420''>sample</span>
  <span m=''173850''>point</span> <span m=''174330''>is</span> <span m=''174520''>in</span>
  <span m=''174650''>the</span> <span m=''174810''>i-th</span> <span m=''174990''>event,</span>
  <span m=''175650''>meaning</span> <span m=''175860''>the</span> <span m=''176160''>i-th</span>
  <span m=''176460''>event</span> <span m=''176790''>occurs,</span> <span m=''178280''>and</span>
  <span m=''178470''>0</span> <span m=''178950''>otherwise.</span> <span m=''183050''>And</span>
  <span m=''183070''>this</span> <span m=''183250''>is</span> <span m=''183410''>just</span>
  <span m=''183720''>another</span> <span m=''184360''>way</span> <span m=''184560''>of</span>
  <span m=''184650''>saying</span> <span m=''185220''>that</span> <span m=''186770''>T</span>
  <span m=''186980''>sub</span> <span m=''187160''>i</span> <span m=''188100''>is</span>
  <span m=''188310''>1</span> <span m=''189570''>if</span> <span m=''189800''>and</span>
  <span m=''189910''>only</span> <span m=''190340''>if</span> <span m=''191340''>A
  sub</span> <span m=''191750''>i</span> <span m=''192380''>happens</span> <span m=''193490''>or</span>
  <span m=''193620''>occurs.</span> </p><p></p><p><span m=''198810''>Now</span> <span
  m=''198960''>what</span> <span m=''199070''>we</span> <span m=''199190''>care</span>
  <span m=''199550''>about</span> <span m=''199820''>is</span> <span m=''199940''>the</span>
  <span m=''200060''>number</span> <span m=''200540''>of</span> <span m=''200610''>events</span>
  <span m=''201060''>that</span> <span m=''201170''>occur.</span> <span m=''201970''>And</span>
  <span m=''202130''>we</span> <span m=''202230''>get</span> <span m=''202460''>that</span>
  <span m=''203430''>just</span> <span m=''203740''>by</span> <span m=''203930''>summing</span>
  <span m=''204400''>up</span> <span m=''204700''>the</span> <span m=''204790''>T
  sub</span> <span m=''205170''>i.</span> <span m=''205550''>So</span> <span m=''205730''>we''ll</span>
  <span m=''205840''>let</span> <span m=''206100''>T</span> <span m=''207100''>be</span>
  <span m=''207850''>T1</span> <span m=''208520''>plus</span> <span m=''208900''>T2</span>
  <span m=''211110''>plus</span> <span m=''211490''>T n.</span> <span m=''213805''>And</span>
  <span m=''214270''>that''ll</span> <span m=''214470''>count</span> <span m=''214910''>because</span>
  <span m=''215040''>we''ll</span> <span m=''215120''>get</span> <span m=''215240''>a</span>
  <span m=''215320''>1</span> <span m=''215780''>every</span> <span m=''215970''>time</span>
  <span m=''216220''>an</span> <span m=''216290''>event</span> <span m=''216570''>occurs.</span>
  <span m=''217060''>By</span> <span m=''217230''>adding</span> <span m=''217560''>those</span>
  <span m=''217810''>up,</span> <span m=''218560''>we''ll</span> <span m=''218700''>get</span>
  <span m=''218870''>the</span> <span m=''218960''>number</span> <span m=''219260''>of</span>
  <span m=''219410''>events</span> <span m=''219830''>that</span> <span m=''219980''>occur.</span>
  </p><p><span m=''222600''>All</span> <span m=''222790''>right.</span> <span m=''223070''>Now</span>
  <span m=''224180''>we</span> <span m=''224310''>care</span> <span m=''224620''>about</span>
  <span m=''224850''>the</span> <span m=''224950''>expected</span> <span m=''225810''>value</span>
  <span m=''226210''>of</span> <span m=''226310''>T,</span> <span m=''226770''>the</span>
  <span m=''226860''>expected</span> <span m=''227330''>number</span> <span m=''227550''>of</span>
  <span m=''227630''>events</span> <span m=''227960''>to</span> <span m=''228070''>occur.</span>
  <span m=''229760''>And</span> <span m=''231100''>I</span> <span m=''231180''>claim</span>
  <span m=''231580''>that''s</span> <span m=''231840''>just</span> <span m=''232040''>the</span>
  <span m=''232140''>sum</span> <span m=''232630''>i</span> <span m=''232820''>equals</span>
  <span m=''233090''>1</span> <span m=''233370''>to</span> <span m=''233460''>n</span>
  <span m=''233870''>of</span> <span m=''233970''>the</span> <span m=''234060''>expected</span>
  <span m=''234640''>value</span> <span m=''235050''>of</span> <span m=''235140''>T</span>
  <span m=''235420''>i.</span> <span m=''237200''>Why</span> <span m=''237390''>is</span>
  <span m=''237520''>that</span> <span m=''237700''>true?</span> <span m=''241540''>Why</span>
  <span m=''241770''>is</span> <span m=''244140''>the expected</span> <span m=''244340''>value</span>
  <span m=''244920''>of</span> <span m=''245400''>T</span> <span m=''245660''>the</span>
  <span m=''245780''>sum</span> <span m=''246020''>of</span> <span m=''246070''>the</span>
  <span m=''246140''>expected</span> <span m=''246510''>values</span> <span m=''246740''>of</span>
  <span m=''246800''>the</span> <span m=''246930''>T</span> <span m=''247110''>sub
  i?</span> </p><p><span m=''249440''>Linearity</span> <span m=''250090''>of</span>
  <span m=''250150''>expectations.</span> <span m=''251610''>Now</span> <span m=''251780''>did</span>
  <span m=''251950''>we</span> <span m=''252060''>need</span> <span m=''252290''>the</span>
  <span m=''252370''>T</span> <span m=''252560''>sub</span> <span m=''252760''>i''s</span>
  <span m=''253030''>to</span> <span m=''253130''>be</span> <span m=''253270''>independent</span>
  <span m=''253760''>events</span> <span m=''254260''>for</span> <span m=''254340''>that?</span>
  <span m=''255910''>No.</span> <span m=''256970''>OK,</span> <span m=''257329''>very</span>
  <span m=''257620''>good.</span> </p><p><span m=''260480''>Now</span> <span m=''260750''>the</span>
  <span m=''260880''>expected</span> <span m=''261380''>value</span> <span m=''261660''>of</span>
  <span m=''261730''>T i</span> <span m=''262170''>is</span> <span m=''262340''>really</span>
  <span m=''262820''>easy</span> <span m=''264580''>to</span> <span m=''264730''>evaluate.</span>
  <span m=''265180''>It''s</span> <span m=''265500''>just</span> <span m=''265780''>a</span>
  <span m=''265810''>0,</span> <span m=''266180''>1</span> <span m=''266650''>variable.</span>
  <span m=''267220''>So</span> <span m=''267530''>it''s</span> <span m=''267750''>just</span>
  <span m=''268790''>the</span> <span m=''268890''>probability</span> <span m=''270540''>that</span>
  <span m=''270750''>T</span> <span m=''270980''>i</span> <span m=''271220''>is</span>
  <span m=''271380''>1</span> <span m=''273130''>because</span> <span m=''273320''>it''s</span>
  <span m=''273450''>1</span> <span m=''273840''>times</span> <span m=''274230''>this</span>
  <span m=''274600''>plus</span> <span m=''274840''>0</span> <span m=''275290''>times</span>
  <span m=''275580''>the</span> <span m=''275660''>probability</span> <span m=''276240''>of</span>
  <span m=''276320''>0,</span> <span m=''276800''>and</span> <span m=''276970''>that</span>
  <span m=''277210''>cancels</span> <span m=''277660''>out.</span> <span m=''279470''>And</span>
  <span m=''279640''>the</span> <span m=''279750''>event that</span> <span m=''280060''>T
  i</span> <span m=''280540''>equals</span> <span m=''280800''>1</span> <span m=''281090''>is</span>
  <span m=''281190''>just</span> <span m=''281440''>the</span> <span m=''282270''>situation</span>
  <span m=''282900''>where</span> <span m=''283000''>the</span> <span m=''283150''>i-th</span>
  <span m=''283390''>event</span> <span m=''283640''>occurs</span> <span m=''291710''>because</span>
  <span m=''292760''>T i</span> <span m=''293260''>equals</span> <span m=''293530''>1</span>
  <span m=''293860''>is</span> <span m=''294120''>the</span> <span m=''294220''>case</span>
  <span m=''294630''>that</span> <span m=''294830''>A i</span> <span m=''295170''>occurs.</span>
  <span m=''296090''>That''s</span> <span m=''296300''>what</span> <span m=''296420''>it</span>
  <span m=''296500''>is.</span> </p><p><span m=''298770''>So</span> <span m=''298880''>we''ve</span>
  <span m=''299030''>shown</span> <span m=''299460''>that</span> <span m=''299570''>the</span>
  <span m=''299660''>expected</span> <span m=''300130''>number</span> <span m=''300330''>of</span>
  <span m=''300420''>events</span> <span m=''300760''>to</span> <span m=''300890''>occur</span>
  <span m=''301770''>is</span> <span m=''301880''>simply</span> <span m=''302460''>the</span>
  <span m=''302580''>sum</span> <span m=''302910''>of</span> <span m=''302960''>the</span>
  <span m=''303040''>probabilities</span> <span m=''304070''>that</span> <span m=''304140''>the</span>
  <span m=''304260''>events</span> <span m=''304600''>occur.</span> <span m=''305620''>So
  a</span> <span m=''305750''>very</span> <span m=''306240''>simple</span> <span m=''306600''>formula,</span>
  <span m=''308830''>very</span> <span m=''309180''>handy.</span> <span m=''310630''>And</span>
  <span m=''310790''>you</span> <span m=''310860''>don''t</span> <span m=''311090''>need</span>
  <span m=''311240''>independence</span> <span m=''311830''>for</span> <span m=''311900''>that.</span>
  <span m=''313630''>Any</span> <span m=''313690''>questions</span> <span m=''315200''>about</span>
  <span m=''315450''>that?</span> <span m=''318020''>We''re</span> <span m=''318210''>going</span>
  <span m=''318370''>to</span> <span m=''318410''>use</span> <span m=''318590''>that</span>
  <span m=''318860''>theorem</span> <span m=''319130''>a lot</span> <span m=''319400''>today.</span>
  </p><p><span m=''320210''>As</span> <span m=''320650''>a</span> <span m=''320730''>simple</span>
  <span m=''321100''>example,</span> <span m=''322460''>suppose</span> <span m=''322870''>we</span>
  <span m=''323020''>flip</span> <span m=''325070''>n</span> <span m=''325670''>fair</span>
  <span m=''326170''>coins.</span> <span m=''330110''>And</span> <span m=''330440''>we</span>
  <span m=''330530''>let</span> <span m=''330740''>A i</span> <span m=''331910''>be</span>
  <span m=''332070''>the</span> <span m=''332220''>event</span> <span m=''334330''>that
  the</span> <span m=''334530''>i-th</span> <span m=''334830''>coin is</span> <span
  m=''335250''>heads.</span> <span m=''340560''>And</span> <span m=''340730''>suppose</span>
  <span m=''341260''>we</span> <span m=''341340''>want</span> <span m=''341580''>to</span>
  <span m=''341620''>know</span> <span m=''341820''>the</span> <span m=''341970''>expected</span>
  <span m=''342720''>number</span> <span m=''343010''>of</span> <span m=''343080''>heads</span>
  <span m=''343590''>in</span> <span m=''343670''>the</span> <span m=''343800''>n</span>
  <span m=''344000''>flips.</span> <span m=''346640''>Well,</span> <span m=''346780''>we</span>
  <span m=''346900''>can</span> <span m=''347050''>use</span> <span m=''347280''>this</span>
  <span m=''347490''>theorem.</span> <span m=''349530''>The</span> <span m=''349620''>expected</span>
  <span m=''350130''>number</span> <span m=''350390''>of</span> <span m=''350470''>heads</span>
  <span m=''351600''>is</span> <span m=''351770''>just</span> <span m=''352010''>going</span>
  <span m=''352110''>to</span> <span m=''352150''>be</span> <span m=''352270''>the</span>
  <span m=''352370''>sum</span> <span m=''352680''>of</span> <span m=''352730''>the</span>
  <span m=''352810''>probabilities</span> <span m=''353620''>that</span> <span m=''353730''>each</span>
  <span m=''353930''>coin</span> <span m=''354260''>is</span> <span m=''354430''>a</span>
  <span m=''354490''>heads.</span> </p><p><span m=''355930''>So</span> <span m=''356220''>let''s</span>
  <span m=''356470''>do</span> <span m=''356610''>that.</span> <span m=''357960''>T</span>
  <span m=''358370''>is</span> <span m=''358500''>the</span> <span m=''358580''>number</span>
  <span m=''358920''>of</span> <span m=''359010''>heads.</span> <span m=''362880''>We</span>
  <span m=''362990''>want</span> <span m=''363250''>to</span> <span m=''363290''>know</span>
  <span m=''363390''>the</span> <span m=''363520''>expected</span> <span m=''364090''>value</span>
  <span m=''364450''>of</span> <span m=''364540''>T.</span> <span m=''365460''>And</span>
  <span m=''365650''>from</span> <span m=''365830''>theorem</span> <span m=''366220''>one,</span>
  <span m=''366610''>that''s</span> <span m=''366870''>just</span> <span m=''367810''>the</span>
  <span m=''368120''>probability</span> <span m=''368680''>the</span> <span m=''368790''>first</span>
  <span m=''369100''>coin</span> <span m=''369340''>is</span> <span m=''369480''>heads</span>
  <span m=''369950''>plus</span> <span m=''370210''>the</span> <span m=''370290''>probability</span>
  <span m=''371070''>the</span> <span m=''371090''>second</span> <span m=''371540''>coin</span>
  <span m=''371820''>is</span> <span m=''371950''>heads.</span> <span m=''373700''>And</span>
  <span m=''373880''>the</span> <span m=''373970''>same</span> <span m=''374310''>out</span>
  <span m=''374660''>to</span> <span m=''374700''>the</span> <span m=''374770''>probability</span>
  <span m=''375175''>the</span> <span m=''375580''>n-th</span> <span m=''375860''>coin
  is</span> <span m=''376280''>heads.</span> </p><p><span m=''378700''>What''s</span>
  <span m=''378920''>the</span> <span m=''379010''>probability</span> <span m=''379500''>the</span>
  <span m=''379590''>first</span> <span m=''379850''>coin</span> <span m=''380080''>is</span>
  <span m=''380200''>heads?</span> <span m=''383750''>And</span> <span m=''383860''>1/2.</span>
  <span m=''385620''>The probability</span> <span m=''386110''>the</span> <span m=''386210''>second</span>
  <span m=''386610''>coin</span> <span m=''386870''>is</span> <span m=''387000''>heads</span>
  <span m=''387290''>is</span> <span m=''387410''>a</span> <span m=''387460''>1/2.</span>
  <span m=''389730''>The probability</span> <span m=''390005''>the</span> <span m=''390280''>last</span>
  <span m=''390710''>coin</span> <span m=''391000''>is</span> <span m=''391140''>heads</span>
  <span m=''391350''>is</span> <span m=''391470''>1/2.</span> <span m=''394730''>And</span>
  <span m=''394920''>so</span> <span m=''395870''>the</span> <span m=''395960''>expected</span>
  <span m=''396430''>number</span> <span m=''396660''>of</span> <span m=''396720''>heads--</span>
  <span m=''397180''>we</span> <span m=''397380''>add</span> <span m=''397610''>up</span>
  <span m=''397770''>1/2</span> <span m=''398140''>n</span> <span m=''398330''>times--</span>
  <span m=''398740''>is</span> <span m=''398870''>just</span> <span m=''399200''>n/2.</span>
  </p><p><span m=''401798''>Of</span> <span m=''402260''>course,</span> <span m=''402630''>you</span>
  <span m=''402780''>all</span> <span m=''403010''>knew</span> <span m=''403220''>that.</span>
  <span m=''403470''>If</span> <span m=''403540''>you</span> <span m=''403650''>flip</span>
  <span m=''403890''>n</span> <span m=''404100''>fair</span> <span m=''404320''>coins,</span>
  <span m=''404760''>the</span> <span m=''404850''>expected</span> <span m=''405200''>number</span>
  <span m=''405440''>of</span> <span m=''405500''>heads</span> <span m=''405800''>is</span>
  <span m=''405930''>half</span> <span m=''406180''>of</span> <span m=''406270''>them.</span>
  <span m=''406900''>But</span> <span m=''407080''>that''s</span> <span m=''407310''>a</span>
  <span m=''407360''>very</span> <span m=''407720''>simple</span> <span m=''408100''>way</span>
  <span m=''408230''>to</span> <span m=''408320''>prove</span> <span m=''408660''>it.</span>
  </p><p><span m=''410770''>Did</span> <span m=''410940''>we</span> <span m=''411050''>need</span>
  <span m=''411350''>the</span> <span m=''411430''>coin</span> <span m=''411870''>tosses</span>
  <span m=''412420''>to</span> <span m=''412540''>be</span> <span m=''412680''>mutually</span>
  <span m=''413290''>independent</span> <span m=''414660''>to</span> <span m=''414830''>conclude</span>
  <span m=''415320''>that?</span> <span m=''418290''>No.</span> <span m=''419050''>I</span>
  <span m=''419430''>could''ve</span> <span m=''419790''>glued</span> <span m=''420100''>them</span>
  <span m=''420280''>together</span> <span m=''420870''>in</span> <span m=''420980''>some</span>
  <span m=''421300''>weird</span> <span m=''421630''>way.</span> <span m=''423140''>In
  fact,</span> <span m=''423340''>I</span> <span m=''423400''>could</span> <span m=''423600''>have</span>
  <span m=''423690''>glued</span> <span m=''424020''>some</span> <span m=''424860''>face</span>
  <span m=''425240''>up</span> <span m=''425470''>and</span> <span m=''425590''>some</span>
  <span m=''425900''>face</span> <span m=''426260''>down</span> <span m=''426740''>and
  done</span> <span m=''427130''>weird</span> <span m=''427450''>things,</span> <span
  m=''428340''>and</span> <span m=''428560''>you</span> <span m=''428650''>still</span>
  <span m=''428920''>expect</span> <span m=''429400''>n/2</span> <span m=''429740''>heads</span>
  <span m=''430890''>even</span> <span m=''431110''>if</span> <span m=''431200''>they</span>
  <span m=''431340''>were</span> <span m=''431390''>glued</span> <span m=''431710''>together</span>
  <span m=''432060''>in</span> <span m=''432140''>strange</span> <span m=''432550''>ways.</span>
  <span m=''433480''>Because</span> <span m=''433810''>I</span> <span m=''433880''>don''t</span>
  <span m=''434310''>need</span> <span m=''434880''>independence</span> <span m=''435490''>for</span>
  <span m=''435600''>linearity</span> <span m=''436040''>of</span> <span m=''436130''>expectation</span>
  <span m=''436860''>to</span> <span m=''436950''>prove</span> <span m=''437180''>this.</span>
  </p><p><span m=''441080''>Now</span> <span m=''441160''>that''s</span> <span m=''441430''>the</span>
  <span m=''441550''>easy</span> <span m=''441950''>way</span> <span m=''443580''>to</span>
  <span m=''443670''>evaluate</span> <span m=''444280''>the</span> <span m=''444360''>expected</span>
  <span m=''444760''>number</span> <span m=''444980''>of</span> <span m=''445040''>heads.</span>
  <span m=''445450''>There</span> <span m=''445610''>is</span> <span m=''445880''>a</span>
  <span m=''446020''>hard</span> <span m=''446370''>way</span> <span m=''446520''>to</span>
  <span m=''446640''>do</span> <span m=''446850''>it.</span> <span m=''447920''>Let</span>
  <span m=''448050''>me</span> <span m=''448160''>set</span> <span m=''448470''>that</span>
  <span m=''448670''>up.</span> </p><p><span m=''449790''>We</span> <span m=''449890''>could</span>
  <span m=''450040''>start</span> <span m=''450420''>from</span> <span m=''450510''>the</span>
  <span m=''450600''>definition,</span> <span m=''451630''>a</span> <span m=''451730''>different</span>
  <span m=''452030''>definition,</span> <span m=''452630''>namely,</span> <span m=''453140''>that</span>
  <span m=''453460''>the</span> <span m=''453730''>expected</span> <span m=''454230''>value</span>
  <span m=''454710''>of</span> <span m=''455390''>T</span> <span m=''458040''>is</span>
  <span m=''458290''>the</span> <span m=''458410''>sum</span> <span m=''459960''>from</span>
  <span m=''460670''>i</span> <span m=''460940''>equals</span> <span m=''461320''>0</span>
  <span m=''461700''>to</span> <span m=''461810''>n.</span> <span m=''463140''>i</span>
  <span m=''464290''>times</span> <span m=''464590''>the</span> <span m=''464670''>probability</span>
  <span m=''465410''>that</span> <span m=''465560''>you</span> <span m=''465650''>have</span>
  <span m=''465950''>i</span> <span m=''466130''>heads.</span> <span m=''468300''>This</span>
  <span m=''468480''>would</span> <span m=''468580''>be</span> <span m=''468720''>a</span>
  <span m=''468760''>natural</span> <span m=''469310''>way</span> <span m=''470160''>to</span>
  <span m=''470390''>compute</span> <span m=''470670''>the</span> <span m=''470770''>expected</span>
  <span m=''471070''>number</span> <span m=''471280''>of</span> <span m=''471340''>heads.</span>
  <span m=''472260''>You</span> <span m=''472810''>add</span> <span m=''473010''>up</span>
  <span m=''473120''>the</span> <span m=''473200''>case</span> <span m=''473570''>where</span>
  <span m=''473760''>there''s</span> <span m=''474050''>zero</span> <span m=''474430''>heads</span>
  <span m=''474900''>times the</span> <span m=''475200''>probability</span> <span
  m=''475620''>of</span> <span m=''475690''>0,</span> <span m=''476390''>1</span>
  <span m=''476850''>times</span> <span m=''477050''>the</span> <span m=''477090''>probability</span>
  <span m=''477440''>of</span> <span m=''477500''>one</span> <span m=''477750''>head,</span>
  <span m=''478080''>2</span> <span m=''478330''>times</span> <span m=''478600''>probably</span>
  <span m=''478950''>two</span> <span m=''479140''>heads,</span> <span m=''479390''>and</span>
  <span m=''479510''>so</span> <span m=''479680''>forth.</span> <span m=''480430''>That''s</span>
  <span m=''480730''>one</span> <span m=''480880''>of the</span> <span m=''480990''>first</span>
  <span m=''481290''>definitions</span> <span m=''481780''>of</span> <span m=''481870''>expectation.</span>
  </p><p><span m=''484820''>So</span> <span m=''484920''>let''s</span> <span m=''485510''>keep</span>
  <span m=''485730''>trying</span> <span m=''486010''>to</span> <span m=''486070''>do</span>
  <span m=''486260''>this.</span> <span m=''489410''>What</span> <span m=''489610''>is</span>
  <span m=''489800''>the</span> <span m=''489910''>probability</span> <span m=''490590''>of</span>
  <span m=''490700''>getting</span> <span m=''491390''>i</span> <span m=''491630''>heads?</span>
  <span m=''492530''>And</span> <span m=''492660''>now</span> <span m=''492800''>I''m</span>
  <span m=''492940''>going</span> <span m=''493040''>to</span> <span m=''493090''>have</span>
  <span m=''493410''>to</span> <span m=''493540''>assume</span> <span m=''493860''>mutual
  independence</span> <span m=''494760''>actually.</span> <span m=''495530''>Now</span>
  <span m=''495800''>I''m</span> <span m=''495940''>going</span> <span m=''496060''>to</span>
  <span m=''496130''>need</span> <span m=''496350''>mutual independence.</span> </p><p><span
  m=''498360''>So</span> <span m=''498540''>already,</span> <span m=''498890''>this</span>
  <span m=''499080''>method</span> <span m=''499390''>isn''t</span> <span m=''499640''>as</span>
  <span m=''499780''>good</span> <span m=''500510''>because</span> <span m=''500670''>I</span>
  <span m=''500750''>had</span> <span m=''501070''>to</span> <span m=''501130''>make</span>
  <span m=''501300''>that</span> <span m=''501460''>assumption</span> <span m=''501980''>to</span>
  <span m=''502240''>answer</span> <span m=''502550''>this</span> <span m=''502760''>question.</span>
  <span m=''504810''>If</span> <span m=''504910''>you</span> <span m=''504990''>don''t</span>
  <span m=''505120''>make</span> <span m=''505270''>that</span> <span m=''505380''>assumption,</span>
  <span m=''505940''>you</span> <span m=''506050''>can''t</span> <span m=''506280''>answer</span>
  <span m=''506510''>that</span> <span m=''506660''>question.</span> <span m=''507420''>What''s</span>
  <span m=''507710''>the</span> <span m=''507800''>probability</span> <span m=''508055''>of</span>
  <span m=''508310''>getting</span> <span m=''508590''>i</span> <span m=''508860''>heads</span>
  <span m=''509690''>out of</span> <span m=''509870''>n.</span> <span m=''511040''>Yeah?</span>
  </p><p><span m=''512745''>AUDIENCE: s</span> <span m=''513190''>to the n-th</span>
  <span m=''513635''>power</span> <span m=''514809''>times</span> <span m=''515184''>n</span>
  <span m=''515559''>[INAUDIBLE]</span> <span m=''515809''>i.</span> </p><p><span
  m=''516700''>PROFESSOR: Yes,</span> <span m=''517730''>because</span> <span m=''518380''>if</span>
  <span m=''518470''>you</span> <span m=''518580''>look</span> <span m=''518730''>at</span>
  <span m=''518799''>the</span> <span m=''518870''>sample</span> <span m=''519280''>space,</span>
  <span m=''520789''>there</span> <span m=''521140''>are</span> <span m=''521659''>2</span>
  <span m=''521840''>to</span> <span m=''521909''>the</span> <span m=''522049''>n</span>
  <span m=''522740''>sample</span> <span m=''523150''>points</span> <span m=''523530''>all</span>
  <span m=''523960''>equally</span> <span m=''524320''>likely.</span> <span m=''525110''>They''re</span>
  <span m=''525280''>all</span> <span m=''525490''>probability</span> <span m=''526020''>2</span>
  <span m=''526150''>the</span> <span m=''526280''>minus</span> <span m=''526620''>n.</span>
  <span m=''527310''>And</span> <span m=''527400''>there''s</span> <span m=''527580''>n</span>
  <span m=''527850''>choose</span> <span m=''528240''>i</span> <span m=''528540''>of</span>
  <span m=''528680''>them</span> <span m=''528860''>that</span> <span m=''528970''>have</span>
  <span m=''529900''>i heads.</span> </p><p><span m=''532590''>And</span> <span m=''532780''>now</span>
  <span m=''532990''>you''d</span> <span m=''533140''>have</span> <span m=''533470''>to</span>
  <span m=''533890''>evaluate</span> <span m=''535470''>that</span> <span m=''535730''>sum</span>
  <span m=''537106''>which</span> <span m=''537570''>is</span> <span m=''537690''>sort</span>
  <span m=''537920''>of</span> <span m=''538010''>a</span> <span m=''538070''>pain.</span>
  <span m=''539520''>That</span> <span m=''539730''>one</span> <span m=''539960''>won''t</span>
  <span m=''540170''>come</span> <span m=''540400''>to</span> <span m=''540470''>mind</span>
  <span m=''541070''>readily.</span> <span m=''543320''>So</span> <span m=''543650''>you</span>
  <span m=''543800''>might</span> <span m=''544020''>say</span> <span m=''544220''>I</span>
  <span m=''544430''>reached</span> <span m=''544610''>sort</span> <span m=''544860''>of</span>
  <span m=''544940''>a</span> <span m=''545020''>dead</span> <span m=''545240''>end</span>
  <span m=''545480''>here.</span> <span m=''546940''>But</span> <span m=''546960''>in</span>
  <span m=''547040''>fact,</span> <span m=''547230''>the</span> <span m=''547420''>answer</span>
  <span m=''548070''>is</span> <span m=''548440''>easy</span> <span m=''548830''>to</span>
  <span m=''548880''>use,</span> <span m=''549740''>easy</span> <span m=''549910''>to</span>
  <span m=''549980''>get</span> <span m=''550320''>using</span> <span m=''550610''>this</span>
  <span m=''550800''>method.</span> </p><p><span m=''553330''>In</span> <span m=''553450''>fact,</span>
  <span m=''553790''>we''ve</span> <span m=''553980''>actually</span> <span m=''554370''>proved
  an</span> <span m=''554820''>identity</span> <span m=''555280''>here</span> <span
  m=''556580''>because</span> <span m=''556970''>we</span> <span m=''557080''>know</span>
  <span m=''557360''>the</span> <span m=''557540''>answer</span> <span m=''557780''>is</span>
  <span m=''557870''>n/2.</span> <span m=''558440''>We''ve</span> <span m=''558580''>just</span>
  <span m=''558890''>proved</span> <span m=''560220''>that</span> <span m=''560460''>this</span>
  <span m=''560710''>messy</span> <span m=''561080''>thing</span> <span m=''562870''>is</span>
  <span m=''563220''>n/2.</span> <span m=''566400''>In</span> <span m=''566500''>fact,</span>
  <span m=''567320''>you</span> <span m=''567410''>can</span> <span m=''567570''>multiply</span>
  <span m=''568000''>by</span> <span m=''568140''>2 to</span> <span m=''568380''>the</span>
  <span m=''568550''>n</span> <span m=''568710''>here.</span> <span m=''568930''>We
  have</span> <span m=''569070''>proved,</span> <span m=''570690''>using</span> <span
  m=''570980''>probability</span> <span m=''571580''>theory</span> <span m=''572070''>and</span>
  <span m=''572550''>theorem</span> <span m=''572840''>1</span> <span m=''573030''>over</span>
  <span m=''573220''>there,</span> <span m=''574400''>the</span> <span m=''574550''>sum</span>
  <span m=''574880''>of</span> <span m=''575010''>i</span> <span m=''575910''>n</span>
  <span m=''576150''>choose</span> <span m=''576460''>i</span> <span m=''578130''>equals</span>
  <span m=''579170''>n</span> <span m=''579540''>2 to</span> <span m=''579780''>the</span>
  <span m=''579980''>n</span> <span m=''580690''>minus</span> <span m=''580980''>1.</span>
  <span m=''583770''>Just</span> <span m=''583970''>multiply</span> <span m=''584100''>by</span>
  <span m=''584350''>2 to</span> <span m=''584520''>the n</span> <span m=''584670''>on</span>
  <span m=''584870''>each</span> <span m=''585000''>side.</span> </p><p><span m=''586370''>So</span>
  <span m=''586510''>we''ve</span> <span m=''586670''>given</span> <span m=''586950''>a</span>
  <span m=''587390''>probability</span> <span m=''588260''>based</span> <span m=''588700''>proof</span>
  <span m=''589765''>of</span> <span m=''590200''>this</span> <span m=''591150''>identity</span>
  <span m=''592490''>which</span> <span m=''592700''>is</span> <span m=''592780''>sort</span>
  <span m=''592960''>of</span> <span m=''593000''>hard</span> <span m=''593290''>to</span>
  <span m=''593390''>do</span> <span m=''594520''>otherwise,</span> <span m=''595040''>could</span>
  <span m=''595170''>be</span> <span m=''595280''>harder</span> <span m=''595510''>to</span>
  <span m=''595630''>do.</span> <span m=''596630''>Any</span> <span m=''596780''>questions</span>
  <span m=''599100''>about</span> <span m=''599370''>that?</span> <span m=''599640''>So</span>
  <span m=''600210''>again,</span> <span m=''601130''>if</span> <span m=''601220''>it</span>
  <span m=''601300''>comes</span> <span m=''601530''>time</span> <span m=''601850''>for</span>
  <span m=''601990''>a</span> <span m=''602020''>homework</span> <span m=''602340''>problem</span>
  <span m=''602720''>or</span> <span m=''603150''>a</span> <span m=''603270''>test</span>
  <span m=''603570''>problem,</span> <span m=''605020''>if</span> <span m=''605340''>it</span>
  <span m=''605530''>naturally</span> <span m=''606050''>divides</span> <span m=''606610''>up</span>
  <span m=''606950''>in</span> <span m=''607080''>this</span> <span m=''607270''>way</span>
  <span m=''609250''>where</span> <span m=''609620''>you</span> <span m=''609740''>can</span>
  <span m=''609910''>take</span> <span m=''610190''>a</span> <span m=''610260''>random</span>
  <span m=''610570''>variable</span> <span m=''610930''>when</span> <span m=''611030''>you</span>
  <span m=''611090''>got a</span> <span m=''611340''>computer''s</span> <span m=''611670''>expectation</span>
  <span m=''612310''>to</span> <span m=''612390''>make</span> <span m=''612710''>it</span>
  <span m=''612790''>a</span> <span m=''612860''>sum</span> <span m=''613160''>of</span>
  <span m=''613270''>indicator</span> <span m=''613750''>variables,</span> <span m=''614370''>if</span>
  <span m=''614680''>that</span> <span m=''614950''>is</span> <span m=''615100''>a</span>
  <span m=''615180''>natural</span> <span m=''615550''>thing</span> <span m=''615730''>to</span>
  <span m=''615800''>do,</span> <span m=''616732''>do</span> <span m=''617200''>it</span>
  <span m=''617300''>that</span> <span m=''617500''>way.</span> <span m=''617760''>Because</span>
  <span m=''617940''>it''s</span> <span m=''618180''>so</span> <span m=''618380''>much</span>
  <span m=''618630''>easier</span> <span m=''619870''>than</span> <span m=''620020''>trying</span>
  <span m=''620370''>to</span> <span m=''620430''>go</span> <span m=''621180''>from</span>
  <span m=''621300''>the</span> <span m=''621420''>definition</span> <span m=''622530''>because</span>
  <span m=''622660''>you</span> <span m=''622770''>might</span> <span m=''623050''>encounter</span>
  <span m=''623550''>nasty</span> <span m=''623980''>things</span> <span m=''624240''>like</span>
  <span m=''624430''>that</span> <span m=''625180''>that</span> <span m=''625550''>you</span>
  <span m=''625670''>got to</span> <span m=''625980''>evaluate.</span> </p><p><span
  m=''632150''>So</span> <span m=''632330''>in</span> <span m=''632390''>this</span>
  <span m=''632590''>case,</span> <span m=''632870''>we</span> <span m=''632980''>flipped
  n</span> <span m=''633420''>coins.</span> <span m=''633840''>We</span> <span m=''633930''>expect</span>
  <span m=''634400''>n/2</span> <span m=''634780''>heads.</span> <span m=''636050''>In</span>
  <span m=''636260''>the</span> <span m=''636420''>hat</span> <span m=''636710''>check,</span>
  <span m=''637540''>in</span> <span m=''637680''>Chinese</span> <span m=''638100''>appetizer</span>
  <span m=''638720''>problems--</span> <span m=''639650''>we</span> <span m=''639810''>had</span>
  <span m=''640030''>n</span> <span m=''640405''>hats</span> <span m=''640780''>or
  n</span> <span m=''640920''>appetizers--</span> <span m=''641910''>we</span> <span
  m=''642120''>expected</span> <span m=''642620''>to</span> <span m=''642670''>get</span>
  <span m=''642840''>one</span> <span m=''643350''>back</span> <span m=''643750''>to</span>
  <span m=''643860''>the</span> <span m=''643950''>right</span> <span m=''644200''>person--</span>
  <span m=''645060''>so</span> <span m=''645170''>a smaller</span> <span m=''646010''>expected</span>
  <span m=''646490''>value.</span> </p><p><span m=''648150''>For</span> <span m=''648310''>some</span>
  <span m=''648650''>problems,</span> <span m=''649870''>the</span> <span m=''650000''>expected</span>
  <span m=''650620''>value</span> <span m=''651040''>is</span> <span m=''651170''>even</span>
  <span m=''651390''>less.</span> <span m=''651890''>The</span> <span m=''652010''>expected</span>
  <span m=''652450''>number</span> <span m=''652700''>of</span> <span m=''652770''>events</span>
  <span m=''653110''>to</span> <span m=''653230''>occur</span> <span m=''653570''>is</span>
  <span m=''653720''>less</span> <span m=''654100''>than</span> <span m=''654270''>1.</span>
  <span m=''654550''>In</span> <span m=''654630''>fact,</span> <span m=''654980''>it</span>
  <span m=''655080''>might</span> <span m=''655110''>be</span> <span m=''655220''>much</span>
  <span m=''655530''>less</span> <span m=''655750''>than</span> <span m=''655870''>1.</span>
  </p><p><span m=''657130''>Now</span> <span m=''657480''>in</span> <span m=''657610''>those</span>
  <span m=''657910''>cases</span> <span m=''658360''>it</span> <span m=''658500''>turns</span>
  <span m=''658870''>out</span> <span m=''659620''>that</span> <span m=''660150''>the</span>
  <span m=''660370''>expected</span> <span m=''660820''>value</span> <span m=''661980''>is</span>
  <span m=''662170''>an</span> <span m=''662390''>upper</span> <span m=''662700''>bound</span>
  <span m=''663670''>on</span> <span m=''663880''>the</span> <span m=''663980''>probability</span>
  <span m=''667710''>that</span> <span m=''667810''>one</span> <span m=''668140''>or</span>
  <span m=''668180''>more</span> <span m=''668410''>events</span> <span m=''668990''>occur.</span>
  <span m=''670280''>We''re</span> <span m=''670430''>going</span> <span m=''670510''>to</span>
  <span m=''670560''>state</span> <span m=''670840''>this</span> <span m=''671030''>as</span>
  <span m=''671170''>theorem</span> <span m=''671480''>2.</span> <span m=''678090''>The</span>
  <span m=''678200''>probability</span> <span m=''678880''>that</span> <span m=''678990''>at</span>
  <span m=''679130''>least</span> <span m=''679490''>one</span> <span m=''679850''>event</span>
  <span m=''680250''>occurs</span> <span m=''682190''>is</span> <span m=''682440''>always</span>
  <span m=''682940''>upper</span> <span m=''683200''>bounded</span> <span m=''683660''>by</span>
  <span m=''683910''>the</span> <span m=''684080''>expected</span> <span m=''684790''>number</span>
  <span m=''685050''>of</span> <span m=''685140''>events</span> <span m=''685570''>to</span>
  <span m=''685740''>occur.</span> <span m=''687450''>Now</span> <span m=''687470''>this</span>
  <span m=''687710''>theorem</span> <span m=''687970''>is</span> <span m=''688090''>pretty</span>
  <span m=''688300''>useless</span> <span m=''689090''>if</span> <span m=''689240''>the</span>
  <span m=''689360''>expected</span> <span m=''689830''>number</span> <span m=''690020''>of</span>
  <span m=''690100''>events</span> <span m=''690430''>to</span> <span m=''690550''>occur</span>
  <span m=''690820''>is</span> <span m=''690950''>bigger</span> <span m=''691170''>than</span>
  <span m=''691310''>1</span> <span m=''692220''>because</span> <span m=''692420''>all</span>
  <span m=''692670''>probabilities</span> <span m=''693320''>are</span> <span m=''693680''>at</span>
  <span m=''693850''>most</span> <span m=''694160''>1.</span> <span m=''695230''>But</span>
  <span m=''695360''>if</span> <span m=''695460''>the</span> <span m=''695570''>expected</span>
  <span m=''696090''>number</span> <span m=''696300''>of</span> <span m=''696380''>events</span>
  <span m=''696710''>to</span> <span m=''696840''>occur</span> <span m=''697190''>is</span>
  <span m=''697310''>small,</span> <span m=''698260''>something</span> <span m=''698610''>much</span>
  <span m=''698840''>less</span> <span m=''699070''>than</span> <span m=''699160''>1,</span>
  <span m=''700080''>this</span> <span m=''700290''>is</span> <span m=''700440''>a</span>
  <span m=''700510''>pretty</span> <span m=''700740''>useful</span> <span m=''701110''>bound.</span>
  </p><p><span m=''703100''>So</span> <span m=''703240''>let''s</span> <span m=''703400''>prove</span>
  <span m=''703670''>that.</span> <span m=''707380''>The</span> <span m=''707630''>expected</span>
  <span m=''708200''>value</span> <span m=''708610''>of</span> <span m=''708720''>T--</span>
  <span m=''709815''>and</span> <span m=''710230''>in</span> <span m=''710340''>this</span>
  <span m=''710490''>case</span> <span m=''710710''>we''ll</span> <span m=''710830''>use</span>
  <span m=''711020''>one</span> <span m=''711330''>of</span> <span m=''711370''>the</span>
  <span m=''711450''>definitions</span> <span m=''712020''>we</span> <span m=''712140''>have</span>
  <span m=''712380''>of</span> <span m=''712490''>expected</span> <span m=''712930''>value,</span>
  <span m=''714200''>name</span> <span m=''714470''>of</span> <span m=''714550''>the</span>
  <span m=''714660''>one</span> <span m=''715020''>where</span> <span m=''715890''>you</span>
  <span m=''716000''>sum</span> <span m=''716290''>from</span> <span m=''716520''>i</span>
  <span m=''716710''>equals</span> <span m=''716960''>1</span> <span m=''717190''>to</span>
  <span m=''717310''>infinity</span> <span m=''718790''>of the</span> <span m=''719130''>probability</span>
  <span m=''720190''>T</span> <span m=''721056''>is</span> <span m=''721490''>greater
  than or</span> <span m=''721820''>equal to</span> <span m=''722230''>i.</span> </p><p><span
  m=''724210''>Now</span> <span m=''724380''>what</span> <span m=''724650''>did</span>
  <span m=''724800''>we</span> <span m=''724910''>have</span> <span m=''725130''>to</span>
  <span m=''725240''>know</span> <span m=''725420''>about</span> <span m=''725810''>T</span>
  <span m=''726080''>to</span> <span m=''726350''>use</span> <span m=''726760''>that</span>
  <span m=''727020''>definition?</span> <span m=''728951''>That</span> <span m=''729390''>doesn''t</span>
  <span m=''729660''>work</span> <span m=''729940''>for</span> <span m=''730090''>all</span>
  <span m=''730440''>random</span> <span m=''730800''>variables</span> <span m=''731240''>T.</span>
  <span m=''733600''>What</span> <span m=''733950''>condition</span> <span m=''734460''>do</span>
  <span m=''734480''>I</span> <span m=''734560''>have</span> <span m=''734740''>on</span>
  <span m=''734910''>T</span> <span m=''736080''>to</span> <span m=''736170''>be</span>
  <span m=''736270''>able</span> <span m=''736400''>to</span> <span m=''736470''>use</span>
  <span m=''736730''>this</span> <span m=''736950''>one?</span> <span m=''739650''>Anybody</span>
  <span m=''739900''>remember?</span> <span m=''740770''>Yeah.</span> </p><p><span
  m=''741367''>AUDIENCE: Must be</span> <span m=''741744''>defined</span> <span m=''742121''>on
  the natural</span> <span m=''742500''>numbers?</span> </p><p><span m=''743330''>PROFESSOR:
  T</span> <span m=''743640''>must</span> <span m=''744060''>defined</span> <span
  m=''744400''>on</span> <span m=''744470''>the</span> <span m=''744530''>natural</span>
  <span m=''744870''>numbers.</span> <span m=''745260''>If</span> <span m=''745370''>it</span>
  <span m=''745470''>is,</span> <span m=''745940''>I</span> <span m=''746000''>can</span>
  <span m=''746200''>use</span> <span m=''746410''>this</span> <span m=''746660''>very</span>
  <span m=''746880''>simple</span> <span m=''747200''>definition.</span> <span m=''748890''>And</span>
  <span m=''749080''>is</span> <span m=''749280''>T</span> <span m=''749760''>defined</span>
  <span m=''750220''>on</span> <span m=''750290''>the</span> <span m=''750350''>natural</span>
  <span m=''750670''>numbers</span> <span m=''751040''>here?</span> <span m=''751260''>Is</span>
  <span m=''751370''>the</span> <span m=''751440''>range</span> <span m=''751690''>of</span>
  <span m=''751790''>T</span> <span m=''752790''>natural</span> <span m=''753030''>numbers?</span>
  </p><p><span m=''754560''>Well,</span> <span m=''755370''>I''m</span> <span m=''755570''>counting</span>
  <span m=''755980''>the</span> <span m=''756070''>number</span> <span m=''756340''>of</span>
  <span m=''756400''>events</span> <span m=''756750''>that</span> <span m=''756860''>occurred.</span>
  <span m=''757920''>Could</span> <span m=''758060''>be</span> <span m=''758190''>0,</span>
  <span m=''758640''>1,</span> <span m=''758970''>2,</span> <span m=''759220''>3,</span>
  <span m=''759490''>4.</span> <span m=''759750''>Has to</span> <span m=''759980''>be
  a</span> <span m=''760110''>natural</span> <span m=''760410''>number.</span> <span
  m=''760700''>So</span> <span m=''760840''>it''s</span> <span m=''760960''>OK.</span>
  <span m=''762240''>So</span> <span m=''762400''>I</span> <span m=''762490''>can</span>
  <span m=''762660''>use</span> <span m=''763110''>this</span> <span m=''763300''>definition.</span>
  </p><p><span m=''765300''>Now</span> <span m=''766100''>this</span> <span m=''766310''>is</span>
  <span m=''766420''>summing</span> <span m=''766820''>up</span> <span m=''766980''>probability</span>
  <span m=''767340''>T</span> <span m=''767700''>is</span> <span m=''768120''>at</span>
  <span m=''768220''>least</span> <span m=''768480''>1</span> <span m=''768860''>plus</span>
  <span m=''769120''>probability</span> <span m=''769415''>T is</span> <span m=''769710''>at</span>
  <span m=''769780''>least</span> <span m=''770040''>2</span> <span m=''770370''>and</span>
  <span m=''770470''>so</span> <span m=''770600''>forth.</span> <span m=''771680''>I''m</span>
  <span m=''771900''>just</span> <span m=''772100''>going</span> <span m=''772210''>to</span>
  <span m=''772860''>use</span> <span m=''773180''>the</span> <span m=''773270''>first</span>
  <span m=''773550''>term.</span> <span m=''773960''>This</span> <span m=''774020''>is</span>
  <span m=''774130''>at</span> <span m=''774290''>least</span> <span m=''775220''>the</span>
  <span m=''775290''>size</span> <span m=''775650''>of</span> <span m=''775690''>the</span>
  <span m=''775750''>first</span> <span m=''776040''>term</span> <span m=''776850''>because</span>
  <span m=''777040''>probabilities</span> <span m=''777620''>are</span> <span m=''777680''>non-negative.</span>
  <span m=''780660''>So</span> <span m=''780730''>I''m</span> <span m=''780830''>just</span>
  <span m=''780980''>going</span> <span m=''781090''>to</span> <span m=''781160''>throw</span>
  <span m=''781450''>away</span> <span m=''781780''>all</span> <span m=''781940''>the</span>
  <span m=''782040''>terms</span> <span m=''782320''>after</span> <span m=''782500''>the</span>
  <span m=''782580''>first</span> <span m=''782890''>and</span> <span m=''782990''>conclude</span>
  <span m=''783460''>that</span> <span m=''783600''>this</span> <span m=''783940''>is</span>
  <span m=''784120''>at</span> <span m=''784240''>least</span> <span m=''784660''>the</span>
  <span m=''784750''>probability</span> <span m=''785075''>T</span> <span m=''785400''>is</span>
  <span m=''785530''>bigger</span> <span m=''785730''>than</span> <span m=''785860''>or</span>
  <span m=''785880''>equal</span> <span m=''786070''>to</span> <span m=''786140''>1.</span>
  <span m=''787000''>And</span> <span m=''787210''>I''m</span> <span m=''787300''>done.</span>
  </p><p><span m=''788920''>I</span> <span m=''789000''>just</span> <span m=''789230''>look</span>
  <span m=''789390''>at</span> <span m=''789490''>it</span> <span m=''789550''>in</span>
  <span m=''789640''>reverse.</span> <span m=''790090''>The</span> <span m=''790180''>probability</span>
  <span m=''790780''>of</span> <span m=''790850''>at</span> <span m=''790980''>least</span>
  <span m=''791240''>one</span> <span m=''791450''>event</span> <span m=''791700''>occurring</span>
  <span m=''792680''>is</span> <span m=''793010''>at</span> <span m=''793240''>most</span>
  <span m=''794950''>the</span> <span m=''794960''>expected</span> <span m=''795430''>value.</span>
  <span m=''797480''>Very</span> <span m=''797720''>simple.</span> <span m=''798850''>There''s</span>
  <span m=''799020''>a</span> <span m=''799090''>very</span> <span m=''799340''>quick</span>
  <span m=''799630''>corollary</span> <span m=''800220''>here.</span> </p><p><span
  m=''804330''>The</span> <span m=''804390''>probability</span> <span m=''805290''>at</span>
  <span m=''805370''>least</span> <span m=''805670''>one</span> <span m=''805870''>event</span>
  <span m=''806140''>occurs</span> <span m=''807430''>is</span> <span m=''807650''>at</span>
  <span m=''807740''>most</span> <span m=''808160''>the</span> <span m=''808250''>sum</span>
  <span m=''808600''>of</span> <span m=''808650''>the</span> <span m=''808720''>probabilities</span>
  <span m=''810360''>of</span> <span m=''810520''>the</span> <span m=''810630''>events.</span>
  <span m=''814870''>And</span> <span m=''815180''>the</span> <span m=''815260''>proof</span>
  <span m=''815560''>there</span> <span m=''816000''>is</span> <span m=''816460''>just</span>
  <span m=''816700''>plugging</span> <span m=''817040''>in</span> <span m=''817240''>theorem</span>
  <span m=''817550''>1.</span> <span m=''819260''>Because</span> <span m=''819530''>the</span>
  <span m=''819640''>expected</span> <span m=''820210''>value</span> <span m=''820720''>is</span>
  <span m=''820830''>the</span> <span m=''820910''>sum</span> <span m=''821100''>of</span>
  <span m=''821140''>the</span> <span m=''821220''>probabilities.</span> </p><p><span
  m=''823920''>So</span> <span m=''824080''>we</span> <span m=''824170''>just</span>
  <span m=''824340''>plug-in</span> <span m=''824670''>theorem</span> <span m=''824990''>1</span>
  <span m=''827300''>for</span> <span m=''827410''>the</span> <span m=''827520''>expected</span>
  <span m=''828000''>value</span> <span m=''828460''>because</span> <span m=''828840''>it''s</span>
  <span m=''829010''>just</span> <span m=''829240''>that.</span> <span m=''833930''>Any</span>
  <span m=''834090''>questions</span> <span m=''834590''>about</span> <span m=''835940''>the</span>
  <span m=''836040''>proof?</span> <span m=''837900''>Very</span> <span m=''838150''>simple.</span>
  </p><p><span m=''839670''>Now</span> <span m=''840390''>this</span> <span m=''841000''>theorem</span>
  <span m=''841470''>is</span> <span m=''841610''>very</span> <span m=''842030''>useful</span>
  <span m=''842570''>in</span> <span m=''842650''>situations</span> <span m=''843530''>where</span>
  <span m=''843610''>you''re</span> <span m=''843740''>trying</span> <span m=''844280''>to</span>
  <span m=''844410''>upper</span> <span m=''844710''>bound</span> <span m=''845100''>the</span>
  <span m=''845170''>probability</span> <span m=''845830''>of</span> <span m=''845910''>some</span>
  <span m=''846230''>kind</span> <span m=''846470''>of</span> <span m=''846570''>disaster</span>
  <span m=''847820''>or</span> <span m=''848020''>something</span> <span m=''848400''>bad</span>
  <span m=''848730''>happening.</span> <span m=''850160''>For</span> <span m=''850280''>example,</span>
  <span m=''850730''>suppose</span> <span m=''851260''>you</span> <span m=''851400''>want</span>
  <span m=''851750''>to</span> <span m=''851800''>compute</span> <span m=''852210''>the</span>
  <span m=''852310''>probability</span> <span m=''853490''>that</span> <span m=''853640''>a</span>
  <span m=''853720''>nuclear</span> <span m=''854240''>plant</span> <span m=''854670''>melts</span>
  <span m=''855070''>down.</span> <span m=''856570''>Now</span> <span m=''856860''>actually,</span>
  <span m=''857630''>the</span> <span m=''857760''>government</span> <span m=''858180''>does</span>
  <span m=''858450''>this.</span> <span m=''859540''>They</span> <span m=''859660''>got</span>
  <span m=''859800''>to</span> <span m=''859870''>figure</span> <span m=''860140''>this</span>
  <span m=''860370''>thing</span> <span m=''860600''>out</span> <span m=''860780''>because</span>
  <span m=''860940''>if</span> <span m=''861020''>it''s</span> <span m=''861120''>a</span>
  <span m=''861180''>high</span> <span m=''861360''>probability,</span> <span m=''862080''>well,</span>
  <span m=''862310''>we''re</span> <span m=''862400''>not</span> <span m=''862570''>going</span>
  <span m=''862670''>to</span> <span m=''862900''>allow</span> <span m=''863170''>anybody</span>
  <span m=''863480''>to</span> <span m=''863560''>build</span> <span m=''863830''>them.</span>
  </p><p><span m=''864810''>And</span> <span m=''865070''>the</span> <span m=''865150''>way</span>
  <span m=''865330''>they</span> <span m=''865490''>do</span> <span m=''865760''>it</span>
  <span m=''866550''>is</span> <span m=''866780''>they</span> <span m=''866920''>convene</span>
  <span m=''867300''>a</span> <span m=''867360''>panel</span> <span m=''867780''>of</span>
  <span m=''867900''>experts.</span> <span m=''869250''>They</span> <span m=''869370''>get</span>
  <span m=''869520''>some</span> <span m=''869660''>people</span> <span m=''870080''>from</span>
  <span m=''870500''>various</span> <span m=''871240''>good</span> <span m=''871440''>universities</span>
  <span m=''872160''>and</span> <span m=''872230''>they</span> <span m=''872300''>bring</span>
  <span m=''872510''>them</span> <span m=''872620''>down</span> <span m=''872840''>to</span>
  <span m=''872930''>Washington.</span> <span m=''873950''>And</span> <span m=''874120''>they</span>
  <span m=''874230''>have</span> <span m=''874580''>them</span> <span m=''874740''>figure</span>
  <span m=''875100''>out</span> <span m=''875350''>every</span> <span m=''875720''>way</span>
  <span m=''875940''>they</span> <span m=''876070''>can</span> <span m=''876240''>think</span>
  <span m=''876560''>of</span> <span m=''877600''>that</span> <span m=''877720''>a</span>
  <span m=''877770''>meltdown</span> <span m=''878250''>could</span> <span m=''878380''>occur,</span>
  <span m=''879450''>every</span> <span m=''879790''>possible</span> <span m=''880350''>event</span>
  <span m=''881150''>that</span> <span m=''881300''>would</span> <span m=''881430''>lead</span>
  <span m=''881650''>to</span> <span m=''881760''>a</span> <span m=''881810''>meltdown.</span>
  <span m=''882800''>And</span> <span m=''883000''>then</span> <span m=''883170''>they''d</span>
  <span m=''883350''>have</span> <span m=''883530''>them</span> <span m=''883660''>figure</span>
  <span m=''884010''>out</span> <span m=''884880''>the</span> <span m=''885000''>probability</span>
  <span m=''886470''>for</span> <span m=''886650''>each</span> <span m=''886830''>one</span>
  <span m=''887000''>of</span> <span m=''887050''>those</span> <span m=''887260''>events.</span>
  </p><p><span m=''888600''>For</span> <span m=''888710''>example,</span> <span m=''889480''>A1</span>
  <span m=''890370''>could</span> <span m=''890530''>be</span> <span m=''890670''>the</span>
  <span m=''890810''>event</span> <span m=''891240''>that</span> <span m=''891360''>the</span>
  <span m=''891950''>operator</span> <span m=''892570''>goes</span> <span m=''892830''>crazy</span>
  <span m=''894070''>and</span> <span m=''894330''>makes</span> <span m=''894590''>it</span>
  <span m=''894690''>meltdown.</span> <span m=''896180''>A2</span> <span m=''896900''>could</span>
  <span m=''897040''>be</span> <span m=''897160''>the</span> <span m=''897300''>event</span>
  <span m=''897640''>that</span> <span m=''897690''>an</span> <span m=''897860''>earthquake</span>
  <span m=''898490''>hits</span> <span m=''899450''>and</span> <span m=''899610''>the</span>
  <span m=''899700''>cooling</span> <span m=''900150''>pipes</span> <span m=''900580''>are</span>
  <span m=''900760''>ruptured,</span> <span m=''901950''>and</span> <span m=''902140''>then</span>
  <span m=''902320''>you</span> <span m=''902420''>got</span> <span m=''902620''>a</span>
  <span m=''902800''>meltdown.</span> <span m=''904340''>A3</span> <span m=''905000''>is</span>
  <span m=''905110''>the</span> <span m=''905250''>event</span> <span m=''905570''>that</span>
  <span m=''905680''>terrorists</span> <span m=''906270''>shoot</span> <span m=''906540''>their</span>
  <span m=''906670''>way</span> <span m=''906930''>in</span> <span m=''907190''>and</span>
  <span m=''907470''>cause</span> <span m=''907800''>a</span> <span m=''907850''>meltdown.</span>
  </p><p><span m=''909670''>So you''ve got</span> <span m=''909840''>a</span> <span
  m=''909890''>lot</span> <span m=''910260''>of</span> <span m=''910340''>possibilities</span>
  <span m=''911100''>for</span> <span m=''911220''>how</span> <span m=''911410''>the</span>
  <span m=''911540''>thing</span> <span m=''911780''>can</span> <span m=''912420''>melt</span>
  <span m=''912700''>down.</span> <span m=''913730''>And</span> <span m=''913920''>then</span>
  <span m=''914020''>they</span> <span m=''914130''>compute</span> <span m=''914490''>the</span>
  <span m=''914590''>probabilities.</span> <span m=''916000''>And</span> <span m=''916200''>then</span>
  <span m=''916390''>they</span> <span m=''916990''>add</span> <span m=''917210''>them</span>
  <span m=''917340''>up</span> <span m=''919290''>just</span> <span m=''919630''>using</span>
  <span m=''919960''>this</span> <span m=''920140''>result.</span> <span m=''921260''>And</span>
  <span m=''921450''>they</span> <span m=''921570''>say,</span> <span m=''921850''>well,</span>
  <span m=''922150''>the</span> <span m=''922250''>probability</span> <span m=''923120''>that</span>
  <span m=''924130''>a</span> <span m=''924240''>meltdown-causing</span> <span m=''925190''>event</span>
  <span m=''925580''>or</span> <span m=''925780''>one</span> <span m=''926210''>or</span>
  <span m=''926250''>more</span> <span m=''926600''>occurs</span> <span m=''927510''>is</span>
  <span m=''927710''>at</span> <span m=''927810''>most</span> <span m=''928260''>this</span>
  <span m=''928360''>small</span> <span m=''929040''>number.</span> <span m=''929270''>And</span>
  <span m=''929500''>hopefully</span> <span m=''930240''>it''s</span> <span m=''930380''>small.</span>
  </p><p><span m=''931510''>So</span> <span m=''931690''>for</span> <span m=''931810''>example,</span>
  <span m=''933750''>suppose</span> <span m=''934330''>there''s</span> <span m=''934510''>100</span>
  <span m=''935060''>ways</span> <span m=''936700''>that</span> <span m=''936880''>a</span>
  <span m=''936930''>meltdown</span> <span m=''937400''>could</span> <span m=''937530''>occur,</span>
  <span m=''938510''>100</span> <span m=''938930''>things</span> <span m=''939230''>that</span>
  <span m=''939300''>could</span> <span m=''939420''>cause</span> <span m=''939670''>a</span>
  <span m=''939720''>meltdown.</span> <span m=''940730''>And</span> <span m=''940990''>each</span>
  <span m=''941260''>one</span> <span m=''941590''>happens</span> <span m=''942040''>with</span>
  <span m=''942140''>probability</span> <span m=''942850''>one in</span> <span m=''943220''>a</span>
  <span m=''943270''>million.</span> <span m=''945350''>What</span> <span m=''945640''>can</span>
  <span m=''945780''>you</span> <span m=''945890''>say</span> <span m=''946700''>about</span>
  <span m=''948040''>the</span> <span m=''948160''>probability</span> <span m=''948710''>that</span>
  <span m=''948820''>a</span> <span m=''948870''>meltdown</span> <span m=''949260''>occurs?</span>
  </p><p><span m=''953510''>You</span> <span m=''953600''>got a</span> <span m=''953770''>hundred</span>
  <span m=''954080''>ways</span> <span m=''954370''>it</span> <span m=''954440''>could</span>
  <span m=''954560''>happen</span> <span m=''954890''>only.</span> <span m=''955820''>Each</span>
  <span m=''956080''>is</span> <span m=''956180''>a</span> <span m=''956250''>one</span>
  <span m=''956550''>in</span> <span m=''956650''>a</span> <span m=''956750''>million</span>
  <span m=''956940''>chance.</span> <span m=''958980''>What''s</span> <span m=''959190''>the</span>
  <span m=''959270''>probability</span> <span m=''959770''>a</span> <span m=''959810''>meltdown</span>
  <span m=''960180''>occurs?</span> </p><p><span m=''963370''>1</span> <span m=''963740''>in</span>
  <span m=''963860''>10,000</span> <span m=''965200''>because</span> <span m=''965340''>you''re</span>
  <span m=''965470''>adding</span> <span m=''965780''>up</span> <span m=''966000''>one
  in a</span> <span m=''966360''>million</span> <span m=''967940''>100</span> <span
  m=''968330''>times.</span> <span m=''968940''>n is</span> <span m=''969270''>100.</span>
  <span m=''970000''>Each</span> <span m=''970210''>of</span> <span m=''970280''>these</span>
  <span m=''970470''>is</span> <span m=''970580''>one in a</span> <span m=''970970''>million.</span>
  </p><p><span m=''972300''>So</span> <span m=''972410''>you</span> <span m=''972460''>get</span>
  <span m=''972570''>100</span> <span m=''972940''>over</span> <span m=''973270''>a</span>
  <span m=''973310''>million.</span> <span m=''973630''>There''s</span> <span m=''973740''>1</span>
  <span m=''973950''>in 10,000.</span> <span m=''974880''>And</span> <span m=''975280''>so</span>
  <span m=''975390''>then</span> <span m=''975560''>they</span> <span m=''975660''>publish</span>
  <span m=''976060''>a</span> <span m=''976100''>report</span> <span m=''976470''>that</span>
  <span m=''976570''>says</span> <span m=''976800''>the</span> <span m=''976890''>chance</span>
  <span m=''977210''>of</span> <span m=''977320''>this</span> <span m=''977510''>reactor</span>
  <span m=''977900''>melting</span> <span m=''978230''>down</span> <span m=''978490''>is</span>
  <span m=''978590''>1 in 10,000.</span> </p><p><span m=''980500''>Now</span> <span
  m=''980770''>what</span> <span m=''980940''>if</span> <span m=''981050''>I''ve</span>
  <span m=''981190''>got</span> <span m=''981760''>100</span> <span m=''982310''>reactors?</span>
  <span m=''985040''>What''s</span> <span m=''985260''>the</span> <span m=''985360''>chance
  that</span> <span m=''985830''>at</span> <span m=''985980''>least</span> <span m=''986240''>one</span>
  <span m=''986480''>of</span> <span m=''986540''>them</span> <span m=''986640''>melts</span>
  <span m=''986950''>down?</span> <span m=''990990''>1 in 100</span> <span m=''991410''>because</span>
  <span m=''991830''>I</span> <span m=''991880''>got</span> <span m=''991980''>100</span>
  <span m=''992450''>over</span> <span m=''992650''>10,000--</span> <span m=''993790''>same</span>
  <span m=''994140''>theorem.</span> <span m=''995020''>So</span> <span m=''995140''>there''s</span>
  <span m=''995330''>a</span> <span m=''995400''>1 in</span> <span m=''995680''>100</span>
  <span m=''995960''>chance</span> <span m=''996350''>something</span> <span m=''996730''>melts</span>
  <span m=''996990''>down</span> <span m=''997250''>somewhere,</span> <span m=''998065''>at</span>
  <span m=''998370''>most.</span> <span m=''1001130''>Hopefully,</span> <span m=''1001410''>the</span>
  <span m=''1001490''>numbers</span> <span m=''1001760''>are</span> <span m=''1001810''>better</span>
  <span m=''1002000''>than</span> <span m=''1002140''>that.</span> </p><p><span m=''1005030''>Same</span>
  <span m=''1005300''>thing</span> <span m=''1005440''>if</span> <span m=''1005510''>you</span>
  <span m=''1005600''>bought</span> <span m=''1005820''>100</span> <span m=''1006260''>lottery</span>
  <span m=''1006680''>tickets,</span> <span m=''1007620''>each</span> <span m=''1007870''>a</span>
  <span m=''1007940''>one in a</span> <span m=''1008310''>million</span> <span m=''1008640''>chance,</span>
  <span m=''1009790''>you</span> <span m=''1009830''>got</span> <span m=''1009990''>a</span>
  <span m=''1010040''>1</span> <span m=''1010270''>in</span> <span m=''1010370''>10,000</span>
  <span m=''1010960''>chance</span> <span m=''1011780''>of</span> <span m=''1011900''>winning,</span>
  <span m=''1012550''>at</span> <span m=''1012820''>most.</span> <span m=''1014780''>So</span>
  <span m=''1014990''>simple</span> <span m=''1015350''>fact</span> <span m=''1015710''>but</span>
  <span m=''1015850''>powerful</span> <span m=''1016670''>and</span> <span m=''1017070''>used</span>
  <span m=''1017910''>a</span> <span m=''1018000''>lot</span> <span m=''1018200''>in</span>
  <span m=''1018280''>practice.</span> <span m=''1019980''>And</span> <span m=''1020080''>this</span>
  <span m=''1020240''>is</span> <span m=''1020340''>sort</span> <span m=''1020500''>of</span>
  <span m=''1020550''>the</span> <span m=''1020640''>good</span> <span m=''1020870''>case</span>
  <span m=''1021360''>when</span> <span m=''1023080''>the</span> <span m=''1023570''>expected</span>
  <span m=''1024300''>number</span> <span m=''1024609''>of</span> <span m=''1024680''>events</span>
  <span m=''1026089''>that</span> <span m=''1026230''>are</span> <span m=''1026290''>bad</span>
  <span m=''1026599''>to</span> <span m=''1026680''>happen</span> <span m=''1027010''>is</span>
  <span m=''1027099''>small,</span> <span m=''1028900''>like</span> <span m=''1029050''>a</span>
  <span m=''1029109''>lot</span> <span m=''1029310''>less</span> <span m=''1029540''>than</span>
  <span m=''1029660''>1.</span> </p><p><span m=''1031569''>But</span> <span m=''1031710''>what</span>
  <span m=''1031930''>if</span> <span m=''1032099''>the</span> <span m=''1032220''>expected</span>
  <span m=''1032839''>number</span> <span m=''1033119''>of</span> <span m=''1033190''>events</span>
  <span m=''1034490''>to</span> <span m=''1034589''>happen</span> <span m=''1034980''>is</span>
  <span m=''1035130''>big.</span> <span m=''1035760''>Say</span> <span m=''1035990''>it''s</span>
  <span m=''1036190''>10.</span> <span m=''1038819''>Say</span> <span m=''1039099''>this</span>
  <span m=''1039349''>government</span> <span m=''1039690''>panel</span> <span m=''1040010''>gets</span>
  <span m=''1040220''>together</span> <span m=''1041020''>and</span> <span m=''1041410''>they</span>
  <span m=''1041880''>add</span> <span m=''1042060''>up</span> <span m=''1042160''>all</span>
  <span m=''1042300''>the</span> <span m=''1042380''>probabilities</span> <span m=''1043030''>and
  it</span> <span m=''1043180''>comes</span> <span m=''1043390''>out</span> <span
  m=''1043520''>to</span> <span m=''1043560''>be</span> <span m=''1043690''>10.</span>
  </p><p><span m=''1045530''>Well,</span> <span m=''1046510''>it</span> <span m=''1046710''>doesn''t</span>
  <span m=''1046980''>sound</span> <span m=''1047300''>so</span> <span m=''1047450''>good</span>
  <span m=''1048540''>if</span> <span m=''1048620''>that''s</span> <span m=''1048840''>the</span>
  <span m=''1048930''>case.</span> <span m=''1049260''>But</span> <span m=''1049470''>is</span>
  <span m=''1049650''>it</span> <span m=''1049800''>necessarily</span> <span m=''1050520''>bad?</span>
  <span m=''1050880''>Does</span> <span m=''1050990''>it</span> <span m=''1051500''>necessarily</span>
  <span m=''1052300''>mean</span> <span m=''1053740''>that</span> <span m=''1053890''>you''re</span>
  <span m=''1054000''>going</span> <span m=''1054100''>to</span> <span m=''1054160''>have</span>
  <span m=''1054370''>a</span> <span m=''1054440''>meltdown.</span> </p><p><span m=''1055160''>So</span>
  <span m=''1055250''>for</span> <span m=''1055370''>example,</span> <span m=''1055930''>let''s</span>
  <span m=''1056050''>say</span> <span m=''1056660''>there''s</span> <span m=''1056810''>1,000</span>
  <span m=''1057370''>ways</span> <span m=''1057630''>you</span> <span m=''1057740''>could</span>
  <span m=''1057880''>melt</span> <span m=''1058130''>down.</span> <span m=''1059590''>And</span>
  <span m=''1059770''>let''s</span> <span m=''1060030''>say</span> <span m=''1060230''>that</span>
  <span m=''1060670''>the</span> <span m=''1060790''>probability</span> <span m=''1061430''>of</span>
  <span m=''1061500''>each</span> <span m=''1061700''>one</span> <span m=''1063350''>is</span>
  <span m=''1063710''>1 in</span> <span m=''1064075''>100.</span> <span m=''1066860''>So</span>
  <span m=''1067000''>the</span> <span m=''1067140''>expected</span> <span m=''1067760''>number</span>
  <span m=''1068130''>of</span> <span m=''1068690''>things</span> <span m=''1069150''>that</span>
  <span m=''1069220''>could</span> <span m=''1069340''>happen</span> <span m=''1069710''>to</span>
  <span m=''1069780''>cause</span> <span m=''1070050''>a</span> <span m=''1070110''>meltdown</span>
  <span m=''1070600''>is</span> <span m=''1070720''>10.</span> </p><p><span m=''1073400''>Am</span>
  <span m=''1073550''>I</span> <span m=''1073620''>guaranteed</span> <span m=''1074230''>we''re</span>
  <span m=''1074340''>going</span> <span m=''1074420''>to</span> <span m=''1074480''>melt</span>
  <span m=''1074700''>down?</span> <span m=''1078590''>No.</span> <span m=''1079710''>Can</span>
  <span m=''1079850''>anybody</span> <span m=''1080270''>think</span> <span m=''1080590''>of</span>
  <span m=''1080680''>a</span> <span m=''1080780''>way</span> <span m=''1081160''>where</span>
  <span m=''1081440''>it''s</span> <span m=''1081680''>unlikely</span> <span m=''1083130''>we''re</span>
  <span m=''1083280''>going</span> <span m=''1083370''>to</span> <span m=''1083430''>melt</span>
  <span m=''1083690''>down</span> <span m=''1084720''>but</span> <span m=''1084860''>respect</span>
  <span m=''1085390''>these</span> <span m=''1085630''>values</span> <span m=''1086070''>here,</span>
  <span m=''1087860''>hypothetically?</span> <span m=''1092300''>Is</span> <span m=''1092450''>there</span>
  <span m=''1092560''>any</span> <span m=''1092750''>chance that</span> <span m=''1093210''>it''s</span>
  <span m=''1093390''>still</span> <span m=''1093740''>unlikely</span> <span m=''1094210''>to</span>
  <span m=''1094270''>have</span> <span m=''1094440''>a</span> <span m=''1094500''>meltdown?</span>
  <span m=''1097900''>We''re going to</span> <span m=''1098380''>think of</span> <span
  m=''1098670''>a way?</span> <span m=''1100150''>Yeah.</span> </p><p><span m=''1100800''>AUDIENCE:
  They all happen</span> <span m=''1101186''>at the same</span> <span m=''1101572''>time.</span>
  </p><p><span m=''1101960''>PROFESSOR: They</span> <span m=''1102160''>all</span>
  <span m=''1102430''>happen at</span> <span m=''1102800''>the</span> <span m=''1102900''>same</span>
  <span m=''1103190''>time.</span> <span m=''1104800''>Now</span> <span m=''1105020''>the</span>
  <span m=''1105100''>examples</span> <span m=''1105520''>I</span> <span m=''1105570''>gave</span>
  <span m=''1105740''>you--</span> <span m=''1105870''>the</span> <span m=''1106010''>terrorists,</span>
  <span m=''1106750''>the</span> <span m=''1107140''>earthquake,</span> <span m=''1107565''>and</span>
  <span m=''1107990''>the</span> <span m=''1108270''>crazy</span> <span m=''1108640''>operator--</span>
  <span m=''1109980''>put</span> <span m=''1110140''>that</span> <span m=''1110300''>on</span>
  <span m=''1110390''>the</span> <span m=''1110470''>side.</span> <span m=''1111470''>If</span>
  <span m=''1111790''>they</span> <span m=''1112010''>all</span> <span m=''1112390''>happen</span>
  <span m=''1112960''>together,</span> <span m=''1113540''>when</span> <span m=''1113690''>any
  one</span> <span m=''1114110''>happens,</span> <span m=''1114490''>the</span> <span
  m=''1114610''>others</span> <span m=''1115110''>have</span> <span m=''1115340''>to</span>
  <span m=''1115450''>happen.</span> <span m=''1117360''>So</span> <span m=''1117480''>we</span>
  <span m=''1117580''>can</span> <span m=''1117740''>express</span> <span m=''1118220''>that</span>
  <span m=''1118680''>as</span> <span m=''1120130''>for</span> <span m=''1120340''>all</span>
  <span m=''1120710''>ij,</span> <span m=''1122380''>probability</span> <span m=''1123050''>of</span>
  <span m=''1123250''>the</span> <span m=''1123440''>i-th</span> <span m=''1123750''>event</span>
  <span m=''1124070''>happening</span> <span m=''1124750''>given</span> <span m=''1125000''>the</span>
  <span m=''1125090''>j-th</span> <span m=''1125450''>event</span> <span m=''1125790''>happening</span>
  <span m=''1126660''>is</span> <span m=''1126820''>one,</span> <span m=''1128470''>so</span>
  <span m=''1128780''>total</span> <span m=''1129520''>dependence.</span> </p><p><span
  m=''1131440''>What''s</span> <span m=''1131770''>the</span> <span m=''1131860''>probability</span>
  <span m=''1132320''>of</span> <span m=''1132390''>a</span> <span m=''1132440''>meltdown</span>
  <span m=''1133420''>in</span> <span m=''1133570''>that</span> <span m=''1133790''>scenario?</span>
  <span m=''1138780''>What''s</span> <span m=''1139010''>the</span> <span m=''1139090''>probability</span>
  <span m=''1139640''>one</span> <span m=''1139820''>of</span> <span m=''1139880''>those</span>
  <span m=''1140070''>meltdown-inducing</span> <span m=''1140970''>events</span> <span
  m=''1141350''>occurs?</span> <span m=''1144960''>They</span> <span m=''1145100''>all</span>
  <span m=''1145250''>happen at</span> <span m=''1145500''>once.</span> </p><p><span
  m=''1147332''>AUDIENCE: 1 in 100.</span> </p><p><span m=''1148320''>PROFESSOR: 1
  in 100.</span> <span m=''1155210''>Because</span> <span m=''1155550''>it''s</span>
  <span m=''1155650''>the</span> <span m=''1155740''>same</span> <span m=''1156020''>as</span>
  <span m=''1156100''>the</span> <span m=''1156190''>probability</span> <span m=''1156770''>of</span>
  <span m=''1156820''>the</span> <span m=''1156900''>first</span> <span m=''1157200''>event</span>
  <span m=''1157600''>happening</span> <span m=''1158810''>which,</span> <span m=''1159040''>by</span>
  <span m=''1159160''>definition,</span> <span m=''1159670''>was 1  in</span> <span
  m=''1159810''>100.</span> </p><p><span m=''1162180''>So</span> <span m=''1162350''>it</span>
  <span m=''1162440''>could</span> <span m=''1162840''>be</span> <span m=''1164280''>that</span>
  <span m=''1164370''>the</span> <span m=''1164460''>probability</span> <span m=''1165050''>of</span>
  <span m=''1165120''>a</span> <span m=''1165170''>meltdown is</span> <span m=''1165700''>small.</span>
  <span m=''1167520''>But</span> <span m=''1167710''>it</span> <span m=''1167790''>might</span>
  <span m=''1168070''>not</span> <span m=''1168360''>be</span> <span m=''1168550''>as</span>
  <span m=''1168660''>well.</span> <span m=''1169270''>There''s</span> <span m=''1169360''>no</span>
  <span m=''1169540''>way,</span> <span m=''1170500''>given</span> <span m=''1170750''>this,</span>
  <span m=''1171020''>to</span> <span m=''1171150''>know.</span> </p><p><span m=''1175030''>What</span>
  <span m=''1175280''>if</span> <span m=''1175410''>I</span> <span m=''1175760''>chain--</span>
  <span m=''1176160''>in fact,</span> <span m=''1176430''>this</span> <span m=''1176610''>is</span>
  <span m=''1176720''>like</span> <span m=''1177810''>Chinese</span> <span m=''1178260''>appetizer,</span>
  <span m=''1178940''>right?</span> <span m=''1180140''>If</span> <span m=''1180290''>one</span>
  <span m=''1180680''>person</span> <span m=''1181150''>gets</span> <span m=''1182090''>their</span>
  <span m=''1182260''>appetizer</span> <span m=''1182810''>back,</span> <span m=''1183690''>everybody</span>
  <span m=''1184230''>does.</span> <span m=''1185040''>So</span> <span m=''1185180''>there</span>
  <span m=''1185370''>are</span> <span m=''1185490''>circumstances</span> <span m=''1186260''>where</span>
  <span m=''1186810''>you</span> <span m=''1186920''>have</span> <span m=''1187040''>the</span>
  <span m=''1187140''>total</span> <span m=''1187400''>dependence</span> <span m=''1187870''>like</span>
  <span m=''1188060''>that.</span> </p><p><span m=''1191160''>Let''s</span> <span
  m=''1191380''>say</span> <span m=''1191500''>I</span> <span m=''1191610''>change</span>
  <span m=''1192030''>a</span> <span m=''1192080''>little</span> <span m=''1192290''>bit</span>
  <span m=''1192750''>and</span> <span m=''1192870''>I</span> <span m=''1192930''>don''t</span>
  <span m=''1193220''>do</span> <span m=''1193330''>this</span> <span m=''1193570''>scenario.</span>
  <span m=''1194760''>In</span> <span m=''1194870''>fact,</span> <span m=''1195160''>say</span>
  <span m=''1195490''>I</span> <span m=''1195580''>tell</span> <span m=''1195930''>you</span>
  <span m=''1196100''>the</span> <span m=''1196290''>events</span> <span m=''1196760''>are</span>
  <span m=''1196940''>mutually</span> <span m=''1197640''>independent,</span> <span
  m=''1199790''>but</span> <span m=''1199950''>you</span> <span m=''1200080''>expect</span>
  <span m=''1200580''>10</span> <span m=''1200860''>to</span> <span m=''1201010''>occur.</span>
  <span m=''1202850''>Do</span> <span m=''1203020''>you</span> <span m=''1203160''>sleep</span>
  <span m=''1203480''>at</span> <span m=''1203570''>night</span> <span m=''1203810''>now?</span>
  <span m=''1206210''>Of</span> <span m=''1206700''>course,</span> <span m=''1206880''>1%</span>
  <span m=''1207155''>is</span> <span m=''1207430''>still</span> <span m=''1207610''>a</span>
  <span m=''1207670''>pretty</span> <span m=''1207880''>high</span> <span m=''1208020''>number.</span>
  </p><p><span m=''1208470''>But</span> <span m=''1210130''>how</span> <span m=''1210240''>many</span>
  <span m=''1210430''>people</span> <span m=''1210740''>think</span> <span m=''1211130''>that</span>
  <span m=''1211260''>if</span> <span m=''1211340''>they''re</span> <span m=''1211480''>mutually</span>
  <span m=''1212100''>independent</span> <span m=''1212690''>and</span> <span m=''1212800''>you</span>
  <span m=''1212930''>expect</span> <span m=''1213430''>10</span> <span m=''1215440''>that,</span>
  <span m=''1216010''>no</span> <span m=''1216100''>matter</span> <span m=''1216380''>what,</span>
  <span m=''1216630''>there''s</span> <span m=''1216770''>a</span> <span m=''1216840''>least</span>
  <span m=''1217170''>a</span> <span m=''1217230''>50%</span> <span m=''1217870''>chance</span>
  <span m=''1218180''>of</span> <span m=''1218270''>a</span> <span m=''1218320''>meltdown?</span>
  <span m=''1220970''>Anybody?</span> <span m=''1224400''>OK.</span> <span m=''1225290''>In</span>
  <span m=''1225520''>fact,</span> <span m=''1227610''>if</span> <span m=''1227790''>you</span>
  <span m=''1228200''>expect</span> <span m=''1228610''>10</span> <span m=''1230290''>and</span>
  <span m=''1230890''>they''re</span> <span m=''1231010''>mutually</span> <span m=''1231440''>independent,</span>
  <span m=''1232840''>a</span> <span m=''1232940''>meltdown</span> <span m=''1233470''>is</span>
  <span m=''1233570''>a</span> <span m=''1233610''>virtual</span> <span m=''1233990''>certainty.</span>
  <span m=''1235260''>The</span> <span m=''1235360''>chance</span> <span m=''1235740''>you</span>
  <span m=''1235840''>don''t</span> <span m=''1236140''>melt</span> <span m=''1236510''>down</span>
  <span m=''1237370''>is</span> <span m=''1237570''>less</span> <span m=''1237920''>than</span>
  <span m=''1238100''>1</span> <span m=''1238380''>in</span> <span m=''1238750''>22,000.</span>
  </p><p><span m=''1241890''>For</span> <span m=''1242010''>sure</span> <span m=''1242470''>something</span>
  <span m=''1242760''>will</span> <span m=''1242930''>occur</span> <span m=''1243270''>that''s</span>
  <span m=''1243500''>bad.</span> <span m=''1244270''>And</span> <span m=''1244900''>this
  is a</span> <span m=''1245290''>theorem</span> <span m=''1246790''>that</span> <span
  m=''1247330''>we</span> <span m=''1247450''>call</span> <span m=''1247740''>Murphy''s</span>
  <span m=''1248160''>law.</span> <span m=''1250580''>And</span> <span m=''1250740''>Murphy''s</span>
  <span m=''1251120''>law,</span> <span m=''1251390''>probably</span> <span m=''1251770''>you''ve
  all</span> <span m=''1252100''>heard</span> <span m=''1252320''>of</span> <span
  m=''1252420''>it,</span> <span m=''1252555''>it</span> <span m=''1252690''>says--</span>
  <span m=''1253120''>it''s</span> <span m=''1253250''>a</span> <span m=''1253290''>famous</span>
  <span m=''1253650''>saying.</span> <span m=''1253920''>If</span> <span m=''1254020''>something</span>
  <span m=''1254420''>can</span> <span m=''1254680''>go</span> <span m=''1254860''>wrong,</span>
  <span m=''1255280''>it</span> <span m=''1255290''>will</span> <span m=''1255480''>go</span>
  <span m=''1255650''>wrong.</span> <span m=''1257170''>And</span> <span m=''1257260''>we''re</span>
  <span m=''1257350''>going</span> <span m=''1257430''>to</span> <span m=''1257480''>see</span>
  <span m=''1257680''>why</span> <span m=''1257850''>that''s</span> <span m=''1258070''>true,</span>
  <span m=''1258360''>at</span> <span m=''1258430''>least,</span> <span m=''1258720''>in</span>
  <span m=''1259650''>our</span> <span m=''1259820''>circumstances</span> <span m=''1260600''>here.</span>
  </p><p></p><p><span m=''1273950''>That''s</span> <span m=''1274140''>a</span> <span
  m=''1274200''>pretty</span> <span m=''1274550''>powerful</span> <span m=''1275070''>theorem.</span>
  </p><p></p><p><span m=''1288870''>If</span> <span m=''1289040''>you</span> <span
  m=''1289170''>have</span> <span m=''1292080''>mutually</span> <span m=''1292630''>independent</span>
  <span m=''1297450''>events</span> <span m=''1299900''>A1</span> <span m=''1300400''>through</span>
  <span m=''1300660''>A</span> <span m=''1300830''>n,</span> <span m=''1308800''>then</span>
  <span m=''1309380''>the</span> <span m=''1309520''>probability</span> <span m=''1311300''>that</span>
  <span m=''1311550''>none</span> <span m=''1311950''>of</span> <span m=''1312030''>them</span>
  <span m=''1312220''>occur,</span> <span m=''1313840''>t</span> <span m=''1314050''>equals</span>
  <span m=''1314310''>0,</span> <span m=''1315300''>is</span> <span m=''1315490''>upper</span>
  <span m=''1315740''>bounded</span> <span m=''1316100''>by</span> <span m=''1316400''>e</span>
  <span m=''1317240''>to</span> <span m=''1317340''>the</span> <span m=''1317460''>minus</span>
  <span m=''1318760''>expected</span> <span m=''1319520''>number</span> <span m=''1319810''>of</span>
  <span m=''1319850''>events</span> <span m=''1320190''>to</span> <span m=''1320340''>occur.</span>
  <span m=''1322980''>So</span> <span m=''1323110''>if</span> <span m=''1323220''>I</span>
  <span m=''1323830''>expect</span> <span m=''1324660''>10</span> <span m=''1325120''>to</span>
  <span m=''1325290''>occur,</span> <span m=''1327370''>the</span> <span m=''1327480''>chance</span>
  <span m=''1327890''>that</span> <span m=''1328060''>none</span> <span m=''1328440''>do</span>
  <span m=''1329430''>is</span> <span m=''1329680''>upper</span> <span m=''1329970''>bounded</span>
  <span m=''1330320''>by</span> <span m=''1330540''>e</span> <span m=''1330760''>to</span>
  <span m=''1330830''>the</span> <span m=''1330950''>minus</span> <span m=''1331520''>10,</span>
  <span m=''1332940''>which</span> <span m=''1333050''>is</span> <span m=''1333190''>very</span>
  <span m=''1333490''>small,</span> <span m=''1334660''>which</span> <span m=''1334780''>means</span>
  <span m=''1335600''>almost</span> <span m=''1336090''>surely</span> <span m=''1336820''>one</span>
  <span m=''1337160''>of</span> <span m=''1337240''>the</span> <span m=''1337360''>events</span>
  <span m=''1337720''>or</span> <span m=''1337880''>more</span> <span m=''1338880''>will</span>
  <span m=''1339070''>occur.</span> <span m=''1341640''>And</span> <span m=''1341710''>that''s</span>
  <span m=''1342400''>bad</span> <span m=''1342740''>news</span> <span m=''1343270''>in</span>
  <span m=''1343380''>this</span> <span m=''1343560''>case.</span> <span m=''1346110''>So</span>
  <span m=''1346340''>let''s</span> <span m=''1347040''>prove</span> <span m=''1347430''>that.</span>
  </p><p><span m=''1351900''>Well,</span> <span m=''1351945''>the</span> <span m=''1351990''>probability</span>
  <span m=''1352300''>that</span> <span m=''1352700''>t</span> <span m=''1353080''>equals</span>
  <span m=''1353530''>0</span> <span m=''1355690''>is</span> <span m=''1355900''>the</span>
  <span m=''1355990''>same</span> <span m=''1356340''>as</span> <span m=''1356460''>the</span>
  <span m=''1356560''>probability</span> <span m=''1357070''>that</span> <span m=''1357290''>A1</span>
  <span m=''1357900''>does</span> <span m=''1358070''>not</span> <span m=''1358300''>occur</span>
  <span m=''1359150''>and</span> <span m=''1359800''>A2</span> <span m=''1360510''>does</span>
  <span m=''1360750''>not</span> <span m=''1361060''>occur</span> <span m=''1362500''>and</span>
  <span m=''1362970''>all</span> <span m=''1363140''>the</span> <span m=''1363230''>way
  to</span> <span m=''1363590''>A</span> <span m=''1363920''>n</span> <span m=''1364250''>does</span>
  <span m=''1364380''>not</span> <span m=''1364600''>occur.</span> <span m=''1367880''>And</span>
  <span m=''1368190''>I</span> <span m=''1368260''>claim</span> <span m=''1368690''>this</span>
  <span m=''1368970''>[INAUDIBLE]</span> <span m=''1369300''>is</span> <span m=''1370060''>the</span>
  <span m=''1370160''>product</span> <span m=''1370700''>of</span> <span m=''1370750''>the</span>
  <span m=''1370820''>probabilities</span> <span m=''1371480''>they</span> <span m=''1371570''>don''t</span>
  <span m=''1371800''>occur.</span> <span m=''1374300''>So</span> <span m=''1374340''>I''m</span>
  <span m=''1374450''>taking</span> <span m=''1374670''>the</span> <span m=''1374770''>product</span>
  <span m=''1375310''>i</span> <span m=''1375510''>equals</span> <span m=''1375650''>1</span>
  <span m=''1375870''>to</span> <span m=''1376240''>n</span> <span m=''1377110''>of</span>
  <span m=''1377550''>the</span> <span m=''1377680''>probability</span> <span m=''1378350''>that</span>
  <span m=''1378610''>A</span> <span m=''1378980''>i</span> <span m=''1379620''>does</span>
  <span m=''1379780''>not</span> <span m=''1380110''>occur.</span> </p><p><span m=''1381240''>Now</span>
  <span m=''1381390''>why</span> <span m=''1381590''>can</span> <span m=''1381780''>I</span>
  <span m=''1381840''>make</span> <span m=''1382090''>that</span> <span m=''1382330''>step?</span>
  <span m=''1386040''>Yeah.</span> <span m=''1386350''>Independence.</span> <span
  m=''1388270''>This</span> <span m=''1388470''>is</span> <span m=''1388630''>the</span>
  <span m=''1389200''>product</span> <span m=''1389710''>rule</span> <span m=''1390470''>for</span>
  <span m=''1390690''>independent</span> <span m=''1391370''>events.</span> </p><p></p><p><span
  m=''1403840''>Now</span> <span m=''1404000''>the</span> <span m=''1404050''>probability</span>
  <span m=''1404650''>that</span> <span m=''1405540''>A i</span> <span m=''1405810''>does</span>
  <span m=''1406000''>not</span> <span m=''1406250''>occur</span> <span m=''1408560''>is</span>
  <span m=''1408760''>simply</span> <span m=''1409150''>1</span> <span m=''1409490''>minus</span>
  <span m=''1409870''>the</span> <span m=''1409960''>probability</span> <span m=''1410600''>it</span>
  <span m=''1410720''>does</span> <span m=''1410980''>occur.</span> <span m=''1415440''>And</span>
  <span m=''1415550''>now</span> <span m=''1415700''>I''m</span> <span m=''1415840''>going</span>
  <span m=''1415950''>to</span> <span m=''1415990''>use</span> <span m=''1416300''>a</span>
  <span m=''1417360''>simple</span> <span m=''1417790''>fact,</span> <span m=''1419450''>which</span>
  <span m=''1419620''>is</span> <span m=''1419930''>that</span> <span m=''1420090''>for</span>
  <span m=''1420220''>any</span> <span m=''1420400''>number</span> <span m=''1420800''>x,</span>
  <span m=''1422504''>1</span> <span m=''1422930''>minus</span> <span m=''1423330''>x</span>
  <span m=''1423840''>is</span> <span m=''1424020''>at</span> <span m=''1424130''>most</span>
  <span m=''1424530''>e</span> <span m=''1424710''>to</span> <span m=''1424760''>the</span>
  <span m=''1424860''>minus</span> <span m=''1425260''>x.</span> <span m=''1427410''>Just</span>
  <span m=''1427620''>a</span> <span m=''1427680''>simple</span> <span m=''1428000''>fact
  from</span> <span m=''1428410''>algebra.</span> </p><p><span m=''1428700''>So</span>
  <span m=''1428980''>I''ve</span> <span m=''1429130''>got</span> <span m=''1429980''>1</span>
  <span m=''1430310''>minus--</span> <span m=''1431060''>I''m</span> <span m=''1431180''>going</span>
  <span m=''1431280''>to</span> <span m=''1431340''>treat</span> <span m=''1431620''>this</span>
  <span m=''1431850''>as</span> <span m=''1432140''>the</span> <span m=''1432330''>x.</span>
  <span m=''1433980''>So</span> <span m=''1434370''>this</span> <span m=''1434750''>is</span>
  <span m=''1435440''>at</span> <span m=''1435650''>most</span> <span m=''1439570''>e</span>
  <span m=''1439820''>to</span> <span m=''1439890''>the</span> <span m=''1439980''>minus</span>
  <span m=''1441030''>probability</span> <span m=''1441315''>of</span> <span m=''1441600''>A</span>
  <span m=''1441690''>i</span> <span m=''1443180''>using</span> <span m=''1443490''>that</span>
  <span m=''1443710''>fact.</span> <span m=''1445710''>And</span> <span m=''1445940''>now</span>
  <span m=''1446550''>I''ll</span> <span m=''1446760''>take</span> <span m=''1447040''>the</span>
  <span m=''1447130''>product</span> <span m=''1447560''>and</span> <span m=''1447640''>put
  it</span> <span m=''1447820''>into</span> <span m=''1448030''>a</span> <span m=''1448090''>sum</span>
  <span m=''1448490''>in</span> <span m=''1448560''>the</span> <span m=''1448680''>exponent.</span>
  </p><p></p><p><span m=''1459440''>And</span> <span m=''1459560''>then</span> <span
  m=''1461310''>some</span> <span m=''1461460''>of</span> <span m=''1461500''>the</span>
  <span m=''1461590''>probabilities</span> <span m=''1462170''>of</span> <span m=''1462210''>the</span>
  <span m=''1462310''>events</span> <span m=''1463450''>is</span> <span m=''1463620''>just</span>
  <span m=''1463870''>the</span> <span m=''1463960''>expected</span> <span m=''1464410''>value.</span>
  <span m=''1465190''>That</span> <span m=''1465250''>was</span> <span m=''1465410''>theorem</span>
  <span m=''1465710''>1</span> <span m=''1465950''>that</span> <span m=''1466070''>I</span>
  <span m=''1466330''>just</span> <span m=''1466600''>erased.</span> <span m=''1468390''>So</span>
  <span m=''1468510''>this</span> <span m=''1468720''>is</span> <span m=''1468850''>e</span>
  <span m=''1469060''>to</span> <span m=''1469120''>the</span> <span m=''1469200''>minus</span>
  <span m=''1469830''>expected</span> <span m=''1471090''>number</span> <span m=''1471290''>of</span>
  <span m=''1471380''>events</span> <span m=''1471720''>to</span> <span m=''1471860''>occur.</span>
  </p><p><span m=''1474650''>So</span> <span m=''1475400''>not</span> <span m=''1475580''>too</span>
  <span m=''1475720''>hard a</span> <span m=''1475970''>proof.</span> <span m=''1476220''>We</span>
  <span m=''1476330''>had</span> <span m=''1476490''>to</span> <span m=''1476540''>use</span>
  <span m=''1476780''>that</span> <span m=''1477710''>fact.</span> <span m=''1478190''>But</span>
  <span m=''1479280''>that</span> <span m=''1479530''>gets</span> <span m=''1479750''>the</span>
  <span m=''1479860''>expected</span> <span m=''1480390''>number</span> <span m=''1480590''>of</span>
  <span m=''1480670''>events</span> <span m=''1481000''>to</span> <span m=''1481110''>occur</span>
  <span m=''1481860''>in</span> <span m=''1481980''>the</span> <span m=''1482100''>exponent.</span>
  <span m=''1484080''>So</span> <span m=''1484220''>a</span> <span m=''1484280''>simple</span>
  <span m=''1484690''>corollary</span> <span m=''1490200''>is</span> <span m=''1490390''>the</span>
  <span m=''1490500''>case</span> <span m=''1490850''>when</span> <span m=''1491010''>we</span>
  <span m=''1491130''>expect</span> <span m=''1491580''>10</span> <span m=''1492010''>events</span>
  <span m=''1492340''>to</span> <span m=''1492490''>occur.</span> </p><p><span m=''1503840''>So</span>
  <span m=''1503970''>if</span> <span m=''1504080''>we</span> <span m=''1504210''>expect</span>
  <span m=''1508050''>10</span> <span m=''1509170''>or</span> <span m=''1509360''>more</span>
  <span m=''1512760''>mutually</span> <span m=''1514700''>independent</span> <span
  m=''1517020''>events</span> <span m=''1519040''>to</span> <span m=''1519230''>occur,</span>
  <span m=''1525540''>the</span> <span m=''1525620''>probability</span> <span m=''1528640''>that</span>
  <span m=''1528890''>no</span> <span m=''1529270''>event</span> <span m=''1529610''>occurs</span>
  <span m=''1535870''>is</span> <span m=''1537420''>at</span> <span m=''1537590''>most</span>
  <span m=''1538090''>e</span> <span m=''1538270''>to</span> <span m=''1538340''>the</span>
  <span m=''1538430''>minus</span> <span m=''1538840''>10,</span> <span m=''1540010''>which</span>
  <span m=''1540170''>is</span> <span m=''1540310''>less</span> <span m=''1540610''>than</span>
  <span m=''1540770''>1</span> <span m=''1541020''>over</span> <span m=''1541190''>22,000.</span>
  <span m=''1546490''>Now</span> <span m=''1546640''>there''s</span> <span m=''1546780''>not</span>
  <span m=''1546990''>even</span> <span m=''1547200''>any</span> <span m=''1547360''>dependence</span>
  <span m=''1547940''>on</span> <span m=''1548080''>n</span> <span m=''1548260''>here.</span>
  <span m=''1550610''>It had</span> <span m=''1550740''>nothing</span> <span m=''1551010''>to</span>
  <span m=''1551090''>do</span> <span m=''1551270''>with</span> <span m=''1551350''>a</span>
  <span m=''1551400''>number</span> <span m=''1551800''>of</span> <span m=''1551860''>possible</span>
  <span m=''1552390''>events,</span> <span m=''1552740''>just that</span> <span m=''1552990''>if</span>
  <span m=''1553070''>you</span> <span m=''1553160''>expect</span> <span m=''1553580''>10</span>
  <span m=''1553780''>of them</span> <span m=''1553870''>to</span> <span m=''1554090''>occur,</span>
  <span m=''1555460''>you''re</span> <span m=''1555660''>pretty</span> <span m=''1555870''>sure</span>
  <span m=''1556370''>one</span> <span m=''1556650''>of</span> <span m=''1556710''>them</span>
  <span m=''1556860''>will.</span> </p><p><span m=''1558910''>And</span> <span m=''1559040''>this</span>
  <span m=''1559220''>explains</span> <span m=''1561000''>why</span> <span m=''1561630''>you</span>
  <span m=''1561770''>see</span> <span m=''1562020''>weird</span> <span m=''1562300''>coincidences.</span>
  <span m=''1564270''>Or</span> <span m=''1564620''>people</span> <span m=''1564940''>sometimes</span>
  <span m=''1565350''>see</span> <span m=''1565510''>what</span> <span m=''1565600''>they</span>
  <span m=''1565700''>think</span> <span m=''1566030''>are</span> <span m=''1566160''>miracles.</span>
  <span m=''1567880''>Because</span> <span m=''1568820''>out</span> <span m=''1569010''>in</span>
  <span m=''1569060''>the</span> <span m=''1569190''>real</span> <span m=''1569440''>world,</span>
  <span m=''1570460''>there''s</span> <span m=''1570720''>billions</span> <span m=''1572300''>of</span>
  <span m=''1572490''>possible</span> <span m=''1573180''>weird</span> <span m=''1573630''>things</span>
  <span m=''1573920''>that</span> <span m=''1574050''>could</span> <span m=''1574160''>happen.</span>
  <span m=''1575360''>You just</span> <span m=''1575690''>can</span> <span m=''1576410''>create</span>
  <span m=''1576830''>all</span> <span m=''1577020''>sorts</span> <span m=''1577300''>of</span>
  <span m=''1577360''>crazy</span> <span m=''1577720''>possibilities.</span> </p><p><span
  m=''1579450''>And</span> <span m=''1579660''>each</span> <span m=''1579850''>one</span>
  <span m=''1580250''>might</span> <span m=''1580470''>be</span> <span m=''1580700''>one
  in a</span> <span m=''1581090''>billion</span> <span m=''1581890''>chance</span>
  <span m=''1582230''>of</span> <span m=''1582490''>actually</span> <span m=''1582890''>happening.</span>
  <span m=''1584800''>But</span> <span m=''1585670''>you</span> <span m=''1585820''>got</span>
  <span m=''1586130''>billions</span> <span m=''1586740''>that</span> <span m=''1586890''>could''ve.</span>
  <span m=''1588970''>And</span> <span m=''1589160''>if</span> <span m=''1589270''>they''re</span>
  <span m=''1589500''>all</span> <span m=''1589710''>mutually</span> <span m=''1590170''>independent--</span>
  <span m=''1590710''>because</span> <span m=''1590840''>you</span> <span m=''1590960''>made</span>
  <span m=''1591180''>up</span> <span m=''1591290''>all</span> <span m=''1591460''>these</span>
  <span m=''1591680''>different</span> <span m=''1592010''>things--</span> <span m=''1593570''>than</span>
  <span m=''1593740''>you</span> <span m=''1593870''>expect</span> <span m=''1594530''>some</span>
  <span m=''1594820''>of</span> <span m=''1594920''>them</span> <span m=''1595100''>to</span>
  <span m=''1595170''>happen.</span> <span m=''1596940''>And</span> <span m=''1597160''>so</span>
  <span m=''1597260''>you</span> <span m=''1597470''>should--</span> <span m=''1597960''>in</span>
  <span m=''1598080''>fact,</span> <span m=''1598980''>you''re</span> <span m=''1599110''>going</span>
  <span m=''1599230''>to</span> <span m=''1599330''>know</span> <span m=''1599660''>that</span>
  <span m=''1600640''>for</span> <span m=''1600840''>sure</span> <span m=''1601340''>some</span>
  <span m=''1601580''>of</span> <span m=''1601640''>those</span> <span m=''1601850''>weird</span>
  <span m=''1602210''>things</span> <span m=''1602470''>are</span> <span m=''1602540''>going</span>
  <span m=''1602650''>to</span> <span m=''1602720''>happen.</span> <span m=''1603545''>At</span>
  <span m=''1603890''>least</span> <span m=''1604120''>the</span> <span m=''1604210''>chance</span>
  <span m=''1604550''>that</span> <span m=''1604650''>no</span> <span m=''1604890''>weird</span>
  <span m=''1605150''>thing</span> <span m=''1605320''>happens</span> <span m=''1605720''>is</span>
  <span m=''1605820''>1 in 22,000.</span> </p><p><span m=''1608500''>And</span> <span
  m=''1608630''>so</span> <span m=''1608700''>this can</span> <span m=''1608840''>be</span>
  <span m=''1609860''>why</span> <span m=''1610140''>somebody</span> <span m=''1610500''>will</span>
  <span m=''1610660''>go along and</span> <span m=''1611000''>say,</span> <span m=''1612240''>oh</span>
  <span m=''1612260''>my</span> <span m=''1612390''>goodness.</span> <span m=''1612710''>You
  won''t</span> <span m=''1612950''>believe</span> <span m=''1613280''>what</span>
  <span m=''1613420''>happened,</span> <span m=''1613860''>a</span> <span m=''1613940''>coincidence.</span>
  <span m=''1615650''>And</span> <span m=''1615950''>it''s</span> <span m=''1616140''>like,</span>
  <span m=''1616600''>wow,</span> <span m=''1616950''>the</span> <span m=''1617040''>chance</span>
  <span m=''1617320''>of</span> <span m=''1617380''>that</span> <span m=''1617560''>happening</span>
  <span m=''1617880''>was</span> <span m=''1618010''>one in</span> <span m=''1618360''>a</span>
  <span m=''1618440''>billion.</span> <span m=''1619380''>It</span> <span m=''1619660''>must''ve</span>
  <span m=''1619980''>been</span> <span m=''1620110''>a</span> <span m=''1620150''>miracle</span>
  <span m=''1620620''>or</span> <span m=''1620750''>an</span> <span m=''1620810''>act</span>
  <span m=''1621050''>of</span> <span m=''1621170''>God</span> <span m=''1621720''>that</span>
  <span m=''1621870''>this</span> <span m=''1622040''>happened.</span> <span m=''1624220''>But</span>
  <span m=''1624430''>you''re</span> <span m=''1624520''>not</span> <span m=''1624730''>thinking</span>
  <span m=''1625010''>about</span> <span m=''1625290''>the</span> <span m=''1625400''>other</span>
  <span m=''1625580''>10</span> <span m=''1625880''>billion</span> <span m=''1626190''>things</span>
  <span m=''1626420''>that</span> <span m=''1626480''>didn''t</span> <span m=''1626820''>happen.</span>
  <span m=''1629930''>So</span> <span m=''1630100''>for</span> <span m=''1630240''>sure</span>
  <span m=''1630820''>some</span> <span m=''1630950''>of</span> <span m=''1631010''>those</span>
  <span m=''1631220''>things</span> <span m=''1631420''>are</span> <span m=''1631480''>going</span>
  <span m=''1631580''>to</span> <span m=''1631620''>happen.</span> </p><p><span m=''1633050''>It''s</span>
  <span m=''1633220''>not</span> <span m=''1633440''>likely</span> <span m=''1634140''>that</span>
  <span m=''1634410''>I''m</span> <span m=''1634570''>going</span> <span m=''1634680''>to</span>
  <span m=''1634740''>win</span> <span m=''1634910''>megabucks</span> <span m=''1635460''>next</span>
  <span m=''1635720''>week.</span> <span m=''1637080''>But</span> <span m=''1637330''>somebody''s</span>
  <span m=''1637820''>going</span> <span m=''1637930''>to</span> <span m=''1637980''>win.</span>
  <span m=''1639310''>If</span> <span m=''1639410''>enough</span> <span m=''1639670''>people</span>
  <span m=''1639950''>play</span> <span m=''1640440''>and</span> <span m=''1640540''>it''s</span>
  <span m=''1640660''>more</span> <span m=''1640850''>than</span> <span m=''1642600''>1</span>
  <span m=''1642860''>over</span> <span m=''1642980''>the</span> <span m=''1643070''>probability</span>
  <span m=''1643710''>that</span> <span m=''1644150''>you''re</span> <span m=''1644290''>going</span>
  <span m=''1644380''>to</span> <span m=''1644450''>win,</span> <span m=''1645220''>than</span>
  <span m=''1645270''>it''s</span> <span m=''1645380''>very</span> <span m=''1645630''>likely</span>
  <span m=''1645940''>somebody will</span> <span m=''1646310''>win</span> <span m=''1646580''>if</span>
  <span m=''1646770''>everybody</span> <span m=''1647120''>is</span> <span m=''1647310''>guessing</span>
  <span m=''1648230''>randomly.</span> <span m=''1650010''>Any</span> <span m=''1650170''>questions</span>
  <span m=''1652130''>about</span> <span m=''1652500''>what</span> <span m=''1652630''>we''re</span>
  <span m=''1652740''>doing?</span> </p><p><span m=''1656780''>So</span> <span m=''1656860''>this</span>
  <span m=''1657540''>is</span> <span m=''1657660''>amazingly</span> <span m=''1658150''>powerful,</span>
  <span m=''1658550''>this</span> <span m=''1658710''>result.</span> <span m=''1659700''>In</span>
  <span m=''1659740''>fact,</span> <span m=''1660110''>it''s</span> <span m=''1660330''>so</span>
  <span m=''1660560''>powerful</span> <span m=''1661770''>that</span> <span m=''1661910''>it''s</span>
  <span m=''1662030''>going</span> <span m=''1662110''>to</span> <span m=''1662190''>let</span>
  <span m=''1662380''>me</span> <span m=''1662560''>read</span> <span m=''1663040''>somebody''s</span>
  <span m=''1663470''>mind</span> <span m=''1664390''>in</span> <span m=''1664500''>the</span>
  <span m=''1664590''>class.</span> <span m=''1664860''>We''re going</span> <span
  m=''1665130''>to</span> <span m=''1665200''>do</span> <span m=''1665360''>a</span>
  <span m=''1665410''>little</span> <span m=''1666010''>card</span> <span m=''1666440''>trick</span>
  <span m=''1666730''>here.</span> </p><p><span m=''1668980''>Now</span> <span m=''1669890''>the</span>
  <span m=''1669990''>way</span> <span m=''1670140''>this</span> <span m=''1670340''>card</span>
  <span m=''1670600''>trick</span> <span m=''1671260''>works--</span> <span m=''1671810''>it''s</span>
  <span m=''1671820''>a</span> <span m=''1671850''>little</span> <span m=''1672110''>complicated.</span>
  <span m=''1672730''>I''m</span> <span m=''1672800''>going</span> <span m=''1672880''>to</span>
  <span m=''1672920''>need</span> <span m=''1673060''>a</span> <span m=''1673090''>volunteer,</span>
  <span m=''1673730''>probably</span> <span m=''1673940''>one</span> <span m=''1674240''>of</span>
  <span m=''1674290''>you</span> <span m=''1674410''>guys</span> <span m=''1674660''>down</span>
  <span m=''1674860''>front.</span> <span m=''1675390''>We''ll</span> <span m=''1675480''>get</span>
  <span m=''1675650''>you.</span> <span m=''1676480''>And</span> <span m=''1676940''>one</span>
  <span m=''1677130''>of</span> <span m=''1677170''>your</span> <span m=''1677280''>buddies</span>
  <span m=''1677620''>is</span> <span m=''1677700''>going</span> <span m=''1677800''>to</span>
  <span m=''1677870''>keep</span> <span m=''1678070''>you</span> <span m=''1678160''>honest</span>
  <span m=''1678890''>for</span> <span m=''1679190''>me</span> <span m=''1679320''>here.</span>
  </p><p><span m=''1680410''>I''m</span> <span m=''1680630''>going</span> <span m=''1680740''>to</span>
  <span m=''1680850''>reveal--</span> <span m=''1681680''>first</span> <span m=''1681910''>I''m
  going to</span> <span m=''1681990''>let</span> <span m=''1682220''>you</span> <span
  m=''1682370''>shuffle</span> <span m=''1682730''>the</span> <span m=''1682830''>deck.</span>
  <span m=''1683300''>So</span> <span m=''1683500''>go</span> <span m=''1683610''>ahead
  and</span> <span m=''1683820''>shuffle</span> <span m=''1684180''>it,</span> <span
  m=''1684250''>do</span> <span m=''1684570''>whatever</span> <span m=''1684770''>you</span>
  <span m=''1684840''>want.</span> <span m=''1685070''>It''s</span> <span m=''1685220''>a</span>
  <span m=''1685310''>normal</span> <span m=''1685710''>deck.</span> <span m=''1686040''>It''s</span>
  <span m=''1686200''>got</span> <span m=''1686770''>52</span> <span m=''1687260''>cards</span>
  <span m=''1687780''>and two</span> <span m=''1688070''>jokers.</span> <span m=''1689760''>And</span>
  <span m=''1690500''>I</span> <span m=''1690570''>don''t</span> <span m=''1690730''>care</span>
  <span m=''1690900''>what</span> <span m=''1691140''>order</span> <span m=''1691380''>they''re</span>
  <span m=''1691620''>in.</span> </p><p><span m=''1692970''>I''m</span> <span m=''1693140''>going</span>
  <span m=''1693240''>to</span> <span m=''1693310''>turn</span> <span m=''1693550''>over</span>
  <span m=''1693750''>the</span> <span m=''1693850''>cards</span> <span m=''1694230''>one</span>
  <span m=''1694490''>at</span> <span m=''1694540''>a</span> <span m=''1694640''>time.</span>
  <span m=''1696410''>Now</span> <span m=''1696670''>I''m</span> <span m=''1696810''>going</span>
  <span m=''1696910''>to</span> <span m=''1696990''>ask</span> <span m=''1697420''>you</span>
  <span m=''1697590''>to</span> <span m=''1697940''>pick</span> <span m=''1698130''>a</span>
  <span m=''1698180''>number</span> <span m=''1698860''>from</span> <span m=''1699090''>1</span>
  <span m=''1699360''>to</span> <span m=''1699440''>9</span> <span m=''1701110''>ahead</span>
  <span m=''1701330''>of</span> <span m=''1701400''>time.</span> <span m=''1702200''>Don''t</span>
  <span m=''1702470''>tell</span> <span m=''1703110''>me</span> <span m=''1703350''>or</span>
  <span m=''1703420''>anybody</span> <span m=''1703740''>else.</span> <span m=''1704530''>In</span>
  <span m=''1704630''>fact,</span> <span m=''1704820''>I''m</span> <span m=''1704910''>going</span>
  <span m=''1705010''>to</span> <span m=''1705070''>want</span> <span m=''1705280''>you</span>
  <span m=''1705380''>guys</span> <span m=''1705610''>to</span> <span m=''1705700''>play</span>
  <span m=''1705940''>along</span> <span m=''1706350''>too.</span> <span m=''1707550''>And
  we''re</span> <span m=''1707640''>going</span> <span m=''1707780''>to</span> <span
  m=''1707830''>see</span> <span m=''1708390''>where we</span> <span m=''1708710''>all</span>
  <span m=''1708910''>end</span> <span m=''1709050''>up</span> <span m=''1709200''>here.</span>
  </p><p><span m=''1711120''>And</span> <span m=''1711730''>that''s</span> <span m=''1711920''>your</span>
  <span m=''1712060''>starting</span> <span m=''1712450''>number.</span> <span m=''1713110''>And</span>
  <span m=''1713260''>as</span> <span m=''1713370''>I</span> <span m=''1713470''>turn</span>
  <span m=''1713790''>over</span> <span m=''1713980''>the</span> <span m=''1714080''>cards</span>
  <span m=''1714560''>one</span> <span m=''1714810''>at</span> <span m=''1714850''>a</span>
  <span m=''1714960''>time--</span> <span m=''1716360''>say</span> <span m=''1716520''>you</span>
  <span m=''1716700''>started</span> <span m=''1717080''>with</span> <span m=''1717230''>a</span>
  <span m=''1717290''>3</span> <span m=''1717870''>was</span> <span m=''1718050''>the</span>
  <span m=''1718130''>number</span> <span m=''1718310''>you</span> <span m=''1718380''>had</span>
  <span m=''1718750''>in</span> <span m=''1718910''>mind--</span> <span m=''1719630''>on</span>
  <span m=''1719820''>the</span> <span m=''1719920''>third</span> <span m=''1720410''>card</span>
  <span m=''1720870''>I</span> <span m=''1720960''>show,</span> <span m=''1722470''>that</span>
  <span m=''1722680''>becomes</span> <span m=''1723000''>your</span> <span m=''1723110''>card.</span>
  <span m=''1724100''>You</span> <span m=''1724210''>don''t</span> <span m=''1724430''>tell</span>
  <span m=''1724670''>me</span> <span m=''1724920''>or</span> <span m=''1725050''>jump</span>
  <span m=''1725250''>up</span> <span m=''1725360''>and</span> <span m=''1725430''>down</span>
  <span m=''1725700''>or</span> <span m=''1725820''>anything.</span> <span m=''1726890''>But</span>
  <span m=''1727050''>that''s</span> <span m=''1727260''>your</span> <span m=''1727430''>card.</span>
  </p><p><span m=''1727740''>And</span> <span m=''1727880''>say</span> <span m=''1728190''>it''s</span>
  <span m=''1730682''>a 4 of</span> <span m=''1731170''>diamonds.</span> <span m=''1732650''>Now
  a</span> <span m=''1733030''>4</span> <span m=''1733470''>replaces</span> <span
  m=''1733930''>the</span> <span m=''1734030''>three</span> <span m=''1734320''>in</span>
  <span m=''1734390''>your</span> <span m=''1734500''>mind</span> <span m=''1735110''>and</span>
  <span m=''1735370''>you</span> <span m=''1735480''>count</span> <span m=''1735790''>4</span>
  <span m=''1736180''>more</span> <span m=''1736430''>cards,</span> <span m=''1737920''>then</span>
  <span m=''1738150''>that</span> <span m=''1738330''>becomes</span> <span m=''1738640''>your</span>
  <span m=''1738750''>card.</span> <span m=''1740130''>Now let''s</span> <span m=''1740300''>say</span>
  <span m=''1740430''>that''s</span> <span m=''1740640''>a</span> <span m=''1740700''>jack</span>
  <span m=''1741570''>or a</span> <span m=''1741780''>face</span> <span m=''1742080''>card</span>
  <span m=''1742340''>or</span> <span m=''1742420''>a</span> <span m=''1742490''>10</span>
  <span m=''1742820''>or</span> <span m=''1742910''>a</span> <span m=''1742950''>joker.</span>
  <span m=''1744350''>10,</span> <span m=''1744770''>face</span> <span m=''1745040''>card,</span>
  <span m=''1745310''>and</span> <span m=''1745400''>jokers</span> <span m=''1745810''>all</span>
  <span m=''1746030''>count</span> <span m=''1746260''>as</span> <span m=''1746370''>1</span>
  <span m=''1746840''>just</span> <span m=''1747040''>like</span> <span m=''1747180''>an</span>
  <span m=''1747270''>ace</span> <span m=''1747530''>counts</span> <span m=''1747780''>as</span>
  <span m=''1747900''>1.</span> <span m=''1748730''>And</span> <span m=''1748970''>so</span>
  <span m=''1749060''>then</span> <span m=''1749220''>the</span> <span m=''1749290''>next</span>
  <span m=''1749650''>card</span> <span m=''1750080''>would</span> <span m=''1750210''>be</span>
  <span m=''1750360''>your</span> <span m=''1750530''>card</span> <span m=''1750940''>because</span>
  <span m=''1751080''>you</span> <span m=''1751160''>count</span> <span m=''1751440''>1.</span>
  </p><p><span m=''1752540''>And</span> <span m=''1752710''>we</span> <span m=''1752850''>keep</span>
  <span m=''1753090''>on</span> <span m=''1753310''>going</span> <span m=''1754480''>until</span>
  <span m=''1754790''>you</span> <span m=''1754930''>have</span> <span m=''1755180''>a</span>
  <span m=''1755250''>card,</span> <span m=''1756140''>maybe</span> <span m=''1756390''>it''s</span>
  <span m=''1756530''>a</span> <span m=''1756590''>7.</span> <span m=''1757510''>But</span>
  <span m=''1757620''>there''s</span> <span m=''1757760''>only</span> <span m=''1758030''>four</span>
  <span m=''1758420''>cards</span> <span m=''1758700''>left</span> <span m=''1758910''>in</span>
  <span m=''1758950''>the</span> <span m=''1759050''>deck.</span> <span m=''1760230''>And</span>
  <span m=''1760270''>so</span> <span m=''1760350''>you</span> <span m=''1760400''>don''t</span>
  <span m=''1760590''>get</span> <span m=''1760720''>a</span> <span m=''1760750''>new</span>
  <span m=''1761000''>one.</span> <span m=''1761760''>And</span> <span m=''1761990''>your</span>
  <span m=''1762090''>last</span> <span m=''1762400''>card</span> <span m=''1762640''>is</span>
  <span m=''1762770''>the</span> <span m=''1762880''>7.</span> </p><p><span m=''1764390''>And</span>
  <span m=''1764480''>then</span> <span m=''1764590''>you''re</span> <span m=''1764730''>going</span>
  <span m=''1764830''>to</span> <span m=''1764930''>write</span> <span m=''1765240''>that</span>
  <span m=''1765470''>down</span> <span m=''1766810''>here,</span> <span m=''1767170''>not</span>
  <span m=''1767540''>showing</span> <span m=''1767880''>me.</span> <span m=''1769300''>And</span>
  <span m=''1770270''>you''re</span> <span m=''1770400''>going</span> <span m=''1770490''>to</span>
  <span m=''1770560''>do</span> <span m=''1770740''>this,</span> <span m=''1770960''>maybe</span>
  <span m=''1771180''>do</span> <span m=''1771310''>this</span> <span m=''1771510''>with</span>
  <span m=''1771680''>a</span> <span m=''1771900''>friend</span> <span m=''1772240''>over</span>
  <span m=''1772410''>there.</span> <span m=''1773610''>And</span> <span m=''1774340''>you''re</span>
  <span m=''1774510''>going</span> <span m=''1774590''>to</span> <span m=''1774630''>make</span>
  <span m=''1774780''>sure</span> <span m=''1774920''>you</span> <span m=''1775040''>count</span>
  <span m=''1775360''>right</span> <span m=''1775570''>on</span> <span m=''1775650''>the</span>
  <span m=''1775740''>deck</span> <span m=''1776030''>because</span> <span m=''1776120''>if</span>
  <span m=''1776190''>you</span> <span m=''1776280''>screw</span> <span m=''1776490''>up
  the</span> <span m=''1776610''>counting,</span> <span m=''1777070''>it''s</span>
  <span m=''1777380''>going</span> <span m=''1777470''>to</span> <span m=''1777520''>be</span>
  <span m=''1777620''>hard</span> <span m=''1778260''>for</span> <span m=''1778390''>me</span>
  <span m=''1778720''>to</span> <span m=''1778840''>read</span> <span m=''1779020''>your</span>
  <span m=''1779120''>mind.</span> </p><p><span m=''1780800''>So</span> <span m=''1780850''>just</span>
  <span m=''1781060''>to</span> <span m=''1781120''>make</span> <span m=''1781260''>sure</span>
  <span m=''1781430''>we</span> <span m=''1781530''>all</span> <span m=''1781660''>understand</span>
  <span m=''1782250''>this,</span> <span m=''1782920''>let me</span> <span m=''1783010''>write</span>
  <span m=''1783230''>the</span> <span m=''1783330''>rules</span> <span m=''1783590''>down</span>
  <span m=''1783750''>here because</span> <span m=''1783950''>I</span> <span m=''1784000''>want</span>
  <span m=''1784180''>the</span> <span m=''1784280''>whole</span> <span m=''1784450''>class</span>
  <span m=''1784860''>to</span> <span m=''1785750''>pick</span> <span m=''1785900''>a</span>
  <span m=''1785960''>number</span> <span m=''1786190''>from</span> <span m=''1786350''>1</span>
  <span m=''1786530''>to</span> <span m=''1786610''>9</span> <span m=''1787010''>and</span>
  <span m=''1787120''>play</span> <span m=''1787360''>the</span> <span m=''1787470''>same</span>
  <span m=''1787800''>game.</span> <span m=''1789270''>And</span> <span m=''1789760''>we''re</span>
  <span m=''1789880''>going</span> <span m=''1789970''>to</span> <span m=''1790060''>see</span>
  <span m=''1791980''>what</span> <span m=''1792110''>happens.</span> <span m=''1793800''>So</span>
  <span m=''1793900''>let</span> <span m=''1793990''>me</span> <span m=''1794090''>show</span>
  <span m=''1794260''>you</span> <span m=''1794350''>the</span> <span m=''1794460''>rules</span>
  <span m=''1794720''>again</span> <span m=''1794950''>just</span> <span m=''1795190''>to</span>
  <span m=''1795250''>make</span> <span m=''1795410''>sure</span> <span m=''1795610''>everybody</span>
  <span m=''1795800''>understands.</span> </p><p><span m=''1799520''>So</span> <span
  m=''1801420''>say</span> <span m=''1801580''>the</span> <span m=''1801680''>deck</span>
  <span m=''1802250''>starts</span> <span m=''1802670''>out</span> <span m=''1802800''>like</span>
  <span m=''1802980''>this.</span> <span m=''1803260''>I</span> <span m=''1803290''>got</span>
  <span m=''1803410''>a</span> <span m=''1803450''>4,</span> <span m=''1804030''>a</span>
  <span m=''1804070''>5.</span> <span m=''1805760''>So</span> <span m=''1805960''>my</span>
  <span m=''1806180''>first</span> <span m=''1806540''>few</span> <span m=''1806700''>cards</span>
  <span m=''1807050''>of the</span> <span m=''1807160''>deck</span> <span m=''1807430''>go</span>
  <span m=''1807610''>like</span> <span m=''1807840''>this.</span> </p><p><span m=''1808890''>10</span>
  <span m=''1809090''>equals</span> <span m=''1809370''>a</span> <span m=''1809450''>1.</span>
  <span m=''1810410''>Then I</span> <span m=''1810550''>got</span> <span m=''1810690''>a</span>
  <span m=''1810740''>queen</span> <span m=''1811110''>equals</span> <span m=''1811400''>a</span>
  <span m=''1811470''>1.</span> <span m=''1812630''>3,</span> <span m=''1813510''>7,</span>
  <span m=''1814390''>6,</span> <span m=''1814830''>4,</span> <span m=''1815400''>2.</span>
  <span m=''1816060''>Say</span> <span m=''1816220''>it''s</span> <span m=''1816350''>a</span>
  <span m=''1816400''>small</span> <span m=''1816740''>deck.</span> <span m=''1816940''>I''m</span>
  <span m=''1817060''>going</span> <span m=''1817160''>to</span> <span m=''1817200''>use</span>
  <span m=''1817440''>54</span> <span m=''1817890''>cards.</span> </p><p><span m=''1819740''>And</span>
  <span m=''1819950''>say</span> <span m=''1820260''>you''re</span> <span m=''1822220''>chosen</span>
  <span m=''1822650''>number</span> <span m=''1822890''>to</span> <span m=''1822970''>start,</span>
  <span m=''1824170''>you</span> <span m=''1824300''>start</span> <span m=''1825760''>with</span>
  <span m=''1825920''>a</span> <span m=''1825980''>three.</span> <span m=''1829030''>As</span>
  <span m=''1829170''>I</span> <span m=''1829230''>show</span> <span m=''1829460''>the</span>
  <span m=''1829580''>cards,</span> <span m=''1829920''>you''re</span> <span m=''1830000''>going</span>
  <span m=''1830090''>to</span> <span m=''1830160''>count</span> <span m=''1830490''>1,</span>
  <span m=''1831510''>2,</span> <span m=''1832690''>3.</span> <span m=''1834640''>That</span>
  <span m=''1834860''>becomes</span> <span m=''1835170''>your</span> <span m=''1835260''>new</span>
  <span m=''1835410''>card.</span> </p><p><span m=''1836650''>Then</span> <span m=''1836810''>you''re</span>
  <span m=''1836900''>going</span> <span m=''1836990''>to</span> <span m=''1837050''>count</span>
  <span m=''1837320''>1,</span> <span m=''1837750''>2.</span> <span m=''1838340''>That</span>
  <span m=''1838650''>becomes</span> <span m=''1838960''>your</span> <span m=''1839070''>card.</span>
  <span m=''1839430''>It''s</span> <span m=''1839570''>a</span> <span m=''1839670''>10,</span>
  <span m=''1839910''>so</span> <span m=''1840150''>you</span> <span m=''1840320''>convert
  it</span> <span m=''1840780''>to</span> <span m=''1840870''>a</span> <span m=''1841020''>1</span>
  <span m=''1842220''>because we''re only</span> <span m=''1842580''>doing</span>
  <span m=''1842750''>single</span> <span m=''1843070''>digit</span> <span m=''1843330''>numbers.</span>
  </p><p><span m=''1844390''>Go</span> <span m=''1844510''>to</span> <span m=''1844610''>1,</span>
  <span m=''1845030''>that</span> <span m=''1845270''>becomes</span> <span m=''1845590''>your</span>
  <span m=''1845690''>card.</span> <span m=''1846760''>Queen</span> <span m=''1847180''>converts
  to a</span> <span m=''1847670''>1.</span> <span m=''1847910''>You</span> <span m=''1847980''>go</span>
  <span m=''1848150''>1,</span> <span m=''1848420''>that</span> <span m=''1848630''>becomes</span>
  <span m=''1848920''>your</span> <span m=''1849030''>card.</span> <span m=''1849520''>3,</span>
  <span m=''1850310''>1,</span> <span m=''1850930''>2,</span> <span m=''1851520''>3.</span>
  <span m=''1852320''>That</span> <span m=''1852560''>becomes</span> <span m=''1852880''>your</span>
  <span m=''1852990''>card.</span> </p><p><span m=''1854730''>And</span> <span m=''1854880''>you</span>
  <span m=''1855420''>can''t</span> <span m=''1855700''>get</span> <span m=''1855960''>4,</span>
  <span m=''1857370''>so</span> <span m=''1857560''>you</span> <span m=''1857740''>remember</span>
  <span m=''1858270''>the</span> <span m=''1858390''>final</span> <span m=''1858780''>card.</span>
  <span m=''1860240''>Does</span> <span m=''1860490''>everybody</span> <span m=''1860640''>understand</span>
  <span m=''1861140''>what</span> <span m=''1861220''>you''re</span> <span m=''1861300''>supposed</span>
  <span m=''1861570''>to</span> <span m=''1861650''>do?</span> <span m=''1863230''>Because</span>
  <span m=''1863310''>we''re</span> <span m=''1863420''>going</span> <span m=''1863510''>to</span>
  <span m=''1863580''>do</span> <span m=''1863780''>54</span> <span m=''1864300''>cards</span>
  <span m=''1864670''>of</span> <span m=''1864740''>this.</span> </p><p><span m=''1866410''>Maybe</span>
  <span m=''1866550''>we</span> <span m=''1866660''>get</span> <span m=''1866780''>the</span>
  <span m=''1866870''>TAs</span> <span m=''1867230''>to play</span> <span m=''1867530''>along</span>
  <span m=''1867900''>here.</span> <span m=''1869180''>And</span> <span m=''1869380''>as</span>
  <span m=''1869450''>you</span> <span m=''1869540''>do</span> <span m=''1869750''>it,</span>
  <span m=''1869810''>maybe</span> <span m=''1870010''>you</span> <span m=''1870100''>want</span>
  <span m=''1870250''>to</span> <span m=''1870300''>talk</span> <span m=''1870600''>to</span>
  <span m=''1870660''>your</span> <span m=''1870740''>buddy,</span> <span m=''1871150''>make</span>
  <span m=''1871310''>sure</span> <span m=''1871660''>you</span> <span m=''1871790''>got</span>
  <span m=''1872000''>it</span> <span m=''1872210''>worked</span> <span m=''1872500''>out</span>
  <span m=''1872690''>there.</span> <span m=''1876900''>And if</span> <span m=''1877090''>I</span>
  <span m=''1877150''>could</span> <span m=''1877290''>read</span> <span m=''1877470''>your</span>
  <span m=''1877560''>mind</span> <span m=''1877950''>maybe</span> <span m=''1878200''>we''ll</span>
  <span m=''1878620''>have</span> <span m=''1878770''>a</span> <span m=''1878810''>gift</span>
  <span m=''1879020''>certificate</span> <span m=''1879450''>or</span> <span m=''1879540''>something.</span>
  </p><p><span m=''1881510''>So</span> <span m=''1882180''>you</span> <span m=''1882280''>shuffle</span>
  <span m=''1882550''>the</span> <span m=''1882630''>deck?</span> <span m=''1883330''>Got
  it</span> <span m=''1883470''>good?</span> <span m=''1884350''>All</span> <span
  m=''1884530''>right.</span> </p><p><span m=''1884880''>So</span> <span m=''1884980''>I''m</span>
  <span m=''1885100''>going</span> <span m=''1885190''>to</span> <span m=''1885250''>start</span>
  <span m=''1885510''>revealing</span> <span m=''1885850''>the</span> <span m=''1885930''>cards</span>
  <span m=''1886240''>one at</span> <span m=''1886560''>a</span> <span m=''1886640''>time.</span>
  <span m=''1887030''>So</span> <span m=''1887170''>you</span> <span m=''1887280''>guys</span>
  <span m=''1887550''>play</span> <span m=''1887770''>along</span> <span m=''1888440''>quietly</span>
  <span m=''1888930''>in</span> <span m=''1889000''>your</span> <span m=''1889090''>mind.</span>
  <span m=''1890190''>And</span> <span m=''1890820''>we''ll</span> <span m=''1891570''>see
  if</span> <span m=''1891730''>we</span> <span m=''1891800''>can</span> <span m=''1891920''>concentrate</span>
  <span m=''1892490''>long</span> <span m=''1892720''>enough.</span> </p><p></p><p><span
  m=''1902750''>Aces</span> <span m=''1903240''>are</span> <span m=''1903340''>1.</span>
  </p><p></p><p><span m=''1919950''>Jacks</span> <span m=''1920280''>are</span> <span
  m=''1920350''>1.</span> </p><p></p><p><span m=''1938790''>10''s</span> <span m=''1939160''>are</span>
  <span m=''1939250''>1.</span> </p><p></p><p><span m=''2007530''>10''s</span> <span
  m=''2007840''>are</span> <span m=''2007920''>1.</span> </p><p></p><p><span m=''2051410''>We''re</span>
  <span m=''2052030''>halfway</span> <span m=''2052460''>done.</span> </p><p></p><p><span
  m=''2122260''>Jokers</span> <span m=''2122990''>are</span> <span m=''2123210''>1.</span>
  </p><p></p><p><span m=''2128690''>OK.</span> <span m=''2128970''>That''s</span>
  <span m=''2129190''>the</span> <span m=''2129260''>last</span> <span m=''2129560''>card.</span>
  <span m=''2130070''>So</span> <span m=''2130720''>remember</span> <span m=''2131100''>the</span>
  <span m=''2131210''>last</span> <span m=''2131580''>one</span> <span m=''2131710''>that</span>
  <span m=''2131810''>was</span> <span m=''2131940''>yours.</span> </p><p><span m=''2132560''>And
  you got</span> <span m=''2132670''>to</span> <span m=''2132730''>go</span> <span
  m=''2133240''>check with your</span> <span m=''2133510''>buddy to</span> <span m=''2133960''>make</span>
  <span m=''2134140''>sure</span> <span m=''2134320''>you</span> <span m=''2134420''>guys</span>
  <span m=''2135880''>agree</span> <span m=''2136290''>on</span> <span m=''2136400''>the</span>
  <span m=''2136490''>counting</span> <span m=''2136920''>there.</span> <span m=''2138720''>And</span>
  <span m=''2138870''>then</span> <span m=''2139020''>write</span> <span m=''2139250''>it</span>
  <span m=''2139360''>down.</span> <span m=''2143840''>Don''t</span> <span m=''2144060''>tell</span>
  <span m=''2144220''>me</span> <span m=''2145770''>because</span> <span m=''2145940''>I''m</span>
  <span m=''2146080''>going</span> <span m=''2146170''>to</span> <span m=''2146250''>read</span>
  <span m=''2146460''>your</span> <span m=''2146560''>mind.</span> <span m=''2147040''>I''m</span>
  <span m=''2147110''>going</span> <span m=''2147200''>to</span> <span m=''2147260''>tell</span>
  <span m=''2147490''>you.</span> </p><p><span m=''2153360''>This</span> <span m=''2153540''>is</span>
  <span m=''2153670''>not good.</span> <span m=''2154020''>They''re</span> <span m=''2154310''>arguing</span>
  <span m=''2154680''>over</span> <span m=''2154830''>the</span> <span m=''2154910''>last</span>
  <span m=''2155220''>card.</span> <span m=''2157690''>I''ll have</span> <span m=''2157940''>to</span>
  <span m=''2158040''>read</span> <span m=''2158230''>one</span> <span m=''2158440''>of</span>
  <span m=''2158520''>your</span> <span m=''2158650''>minds.</span> </p><p><span m=''2161240''>What''s</span>
  <span m=''2161340''>that?</span> <span m=''2161480''>The</span> <span m=''2161620''>11
  of</span> <span m=''2162010''>clubs.</span> <span m=''2162380''>That''s</span> <span
  m=''2162640''>hard</span> <span m=''2162910''>one</span> <span m=''2163040''>to</span>
  <span m=''2163130''>predict.</span> </p><p></p><p><span m=''2173290''>Make</span>
  <span m=''2173450''>your</span> <span m=''2173550''>best</span> <span m=''2173780''>guess</span>
  <span m=''2173930''>and</span> <span m=''2174020''>write</span> <span m=''2174210''>it</span>
  <span m=''2174290''>down.</span> <span m=''2174600''>Don''t</span> <span m=''2174670''>tell</span>
  <span m=''2174780''>me.</span> <span m=''2174890''>Write</span> <span m=''2175050''>it</span>
  <span m=''2175130''>down.</span> </p><p><span m=''2176152''>You</span> <span m=''2176520''>got</span>
  <span m=''2176700''>two?</span> <span m=''2176830''>Well,</span> <span m=''2176980''>write</span>
  <span m=''2177150''>them</span> <span m=''2177260''>both.</span> <span m=''2177480''>I''ll</span>
  <span m=''2177600''>predict</span> <span m=''2177910''>one</span> <span m=''2178140''>of</span>
  <span m=''2178280''>them.</span> </p><p></p><p><span m=''2190000''>I''ve</span>
  <span m=''2190490''>never</span> <span m=''2190740''>had</span> <span m=''2190980''>a</span>
  <span m=''2191030''>dispute</span> <span m=''2191510''>on</span> <span m=''2191610''>what</span>
  <span m=''2191770''>the--</span> <span m=''2193070''>because</span> <span m=''2193270''>if</span>
  <span m=''2193350''>you</span> <span m=''2193450''>started</span> <span m=''2193780''>with</span>
  <span m=''2193850''>the</span> <span m=''2193940''>same</span> <span m=''2194210''>position,</span>
  <span m=''2194620''>you''ve</span> <span m=''2194720''>got</span> <span m=''2194880''>to</span>
  <span m=''2194960''>wind</span> <span m=''2195230''>up</span> <span m=''2195350''>in</span>
  <span m=''2195430''>the</span> <span m=''2195520''>same</span> <span m=''2195770''>position.</span>
  <span m=''2196870''>You</span> <span m=''2196990''>wrote</span> <span m=''2197180''>it</span>
  <span m=''2197250''>down?</span> <span m=''2198330''>Now</span> <span m=''2198480''>think</span>
  <span m=''2198710''>about</span> <span m=''2198910''>your</span> <span m=''2199000''>number</span>
  <span m=''2199250''>really</span> <span m=''2199520''>hard.</span> </p><p><span
  m=''2199910''>We''ll</span> <span m=''2200150''>take</span> <span m=''2200430''>yours.</span>
  <span m=''2200690''>I''ll</span> <span m=''2200830''>trust you</span> <span m=''2201190''>there.</span>
  <span m=''2201370''>Think</span> <span m=''2201590''>about</span> <span m=''2201780''>it</span>
  <span m=''2201850''>really</span> <span m=''2202170''>hard</span> <span m=''2202490''>because
  I</span> <span m=''2202580''>need</span> <span m=''2202810''>the</span> <span m=''2202950''>brain</span>
  <span m=''2203270''>waves</span> <span m=''2203510''>to</span> <span m=''2203590''>come</span>
  <span m=''2203750''>over</span> <span m=''2205050''>and</span> <span m=''2205320''>read</span>
  <span m=''2205520''>the</span> <span m=''2205580''>mind</span> <span m=''2205930''>here.</span>
  </p><p><span m=''2209900''>Yeah,</span> <span m=''2210220''>yeah.</span> <span m=''2211920''>I''m</span>
  <span m=''2212040''>getting</span> <span m=''2212200''>a</span> <span m=''2212280''>really</span>
  <span m=''2212650''>strong</span> <span m=''2213070''>signal</span> <span m=''2214670''>on</span>
  <span m=''2214990''>the</span> <span m=''2215090''>last</span> <span m=''2215430''>card.</span>
  <span m=''2215770''>Maybe</span> <span m=''2216060''>I</span> <span m=''2216110''>don''t</span>
  <span m=''2216260''>know.</span> <span m=''2216350''>Maybe it''s</span> <span m=''2216650''>something--</span>
  <span m=''2216990''>it''s</span> <span m=''2217250''>really</span> <span m=''2217520''>powerful.</span>
  </p><p><span m=''2218010''>I''m</span> <span m=''2218130''>going to</span> <span
  m=''2218320''>say</span> <span m=''2218460''>it''s</span> <span m=''2218590''>the</span>
  <span m=''2218670''>queen</span> <span m=''2218890''>of</span> <span m=''2218960''>hearts.</span>
  <span m=''2220941''>Is that</span> <span m=''2221430''>right?</span> <span m=''2223200''>Both
  were</span> <span m=''2223550''>the queen of--</span> <span m=''2223950''>oh,</span>
  <span m=''2224180''>you were</span> <span m=''2224390''>trying</span> <span m=''2224600''>to</span>
  <span m=''2224670''>screw</span> <span m=''2224930''>me</span> <span m=''2225070''>up,</span>
  <span m=''2225360''>mess with</span> <span m=''2225700''>me.</span> <span m=''2226080''>So</span>
  <span m=''2226420''>you</span> <span m=''2226490''>both</span> <span m=''2226790''>got</span>
  <span m=''2226940''>the</span> <span m=''2227020''>queen of</span> <span m=''2227270''>hearts.</span>
  <span m=''2229066''>Oh,</span> <span m=''2229450''>you</span> <span m=''2229570''>did.</span>
  </p><p><span m=''2229820''>So</span> <span m=''2230140''>how</span> <span m=''2230560''>many</span>
  <span m=''2230720''>people</span> <span m=''2230950''>got</span> <span m=''2231090''>the</span>
  <span m=''2231170''>queen</span> <span m=''2231380''>of</span> <span m=''2231430''>hearts?</span>
  <span m=''2234090''>Oh</span> <span m=''2234280''>wow.</span> <span m=''2234530''>How</span>
  <span m=''2234640''>many</span> <span m=''2234760''>people</span> <span m=''2235000''>did</span>
  <span m=''2235220''>not</span> <span m=''2235460''>get</span> <span m=''2235590''>the</span>
  <span m=''2235670''>queen</span> <span m=''2235880''>of</span> <span m=''2235920''>hearts.</span>
  <span m=''2238200''>Somebody.</span> <span m=''2238700''>OK.</span> </p><p><span
  m=''2239680''>Now</span> <span m=''2240060''>there''s</span> <span m=''2240230''>a</span>
  <span m=''2240310''>chance</span> <span m=''2240630''>you</span> <span m=''2240740''>did</span>
  <span m=''2240890''>it</span> <span m=''2240930''>legitimately.</span> <span m=''2242490''>But</span>
  <span m=''2243260''>usually,</span> <span m=''2244210''>with</span> <span m=''2244380''>a</span>
  <span m=''2244430''>deck,</span> <span m=''2245500''>we''re</span> <span m=''2245720''>all</span>
  <span m=''2246030''>going</span> <span m=''2246140''>to</span> <span m=''2246190''>get</span>
  <span m=''2246360''>the</span> <span m=''2246450''>same</span> <span m=''2246760''>last</span>
  <span m=''2247100''>card.</span> <span m=''2248510''>Now</span> <span m=''2248620''>in</span>
  <span m=''2248680''>this</span> <span m=''2248850''>case,</span> <span m=''2249160''>it</span>
  <span m=''2249260''>happened</span> <span m=''2249420''>to</span> <span m=''2249460''>be</span>
  <span m=''2249580''>the</span> <span m=''2249670''>very</span> <span m=''2250030''>last</span>
  <span m=''2250310''>card.</span> <span m=''2250620''>That</span> <span m=''2250780''>is</span>
  <span m=''2250930''>typically</span> <span m=''2251310''>not</span> <span m=''2251640''>the</span>
  <span m=''2251740''>case.</span> <span m=''2252880''>So</span> <span m=''2254180''>very</span>
  <span m=''2254450''>good.</span> </p><p><span m=''2254660''>So</span> <span m=''2254770''>I</span>
  <span m=''2254860''>read</span> <span m=''2255060''>your</span> <span m=''2255160''>mind.</span>
  <span m=''2255670''>So</span> <span m=''2255770''>you</span> <span m=''2255940''>guys</span>
  <span m=''2256240''>get</span> <span m=''2257330''>the</span> <span m=''2257420''>gift</span>
  <span m=''2257600''>certificates</span> <span m=''2258160''>here.</span> <span m=''2258740''>Very</span>
  <span m=''2258970''>good.</span> <span m=''2259170''>One</span> <span m=''2259380''>for</span>
  <span m=''2259490''>you</span> <span m=''2259760''>and</span> <span m=''2259840''>your</span>
  <span m=''2260380''>sponsor</span> <span m=''2260880''>there.</span> </p><p><span
  m=''2262220''>So</span> <span m=''2263650''>it''s</span> <span m=''2263810''>clear</span>
  <span m=''2264090''>how</span> <span m=''2264200''>I</span> <span m=''2264310''>read</span>
  <span m=''2264480''>his</span> <span m=''2264610''>mind</span> <span m=''2265490''>because</span>
  <span m=''2266960''>I</span> <span m=''2267130''>got</span> <span m=''2267300''>the</span>
  <span m=''2267400''>same</span> <span m=''2267640''>number</span> <span m=''2267900''>everybody</span>
  <span m=''2268330''>did.</span> <span m=''2269350''>And</span> <span m=''2269520''>somehow
  it</span> <span m=''2269900''>doesn''t</span> <span m=''2270210''>matter</span>
  <span m=''2270510''>where</span> <span m=''2270770''>we</span> <span m=''2270890''>started.</span>
  <span m=''2272630''>We</span> <span m=''2272810''>all</span> <span m=''2272970''>had</span>
  <span m=''2273150''>the</span> <span m=''2273230''>same</span> <span m=''2273510''>card</span>
  <span m=''2273980''>at</span> <span m=''2274070''>the</span> <span m=''2274230''>end.</span>
  </p><p><span m=''2275322''>How</span> <span m=''2275710''>is</span> <span m=''2275830''>that</span>
  <span m=''2276010''>possible?</span> <span m=''2278150''>There''s</span> <span m=''2278340''>nine</span>
  <span m=''2278650''>different</span> <span m=''2278920''>starting</span> <span m=''2279290''>points.</span>
  <span m=''2280980''>Why</span> <span m=''2281160''>don''t</span> <span m=''2281260''>we</span>
  <span m=''2281350''>wind</span> <span m=''2281630''>up</span> <span m=''2281720''>in</span>
  <span m=''2281820''>nine</span> <span m=''2282080''>different</span> <span m=''2282350''>places?</span>
  </p><p><span m=''2282790''>And</span> <span m=''2282890''>why</span> <span m=''2283070''>isn''t</span>
  <span m=''2283270''>there a</span> <span m=''2283420''>one</span> <span m=''2283670''>in</span>
  <span m=''2283760''>nine</span> <span m=''2284000''>chance</span> <span m=''2284460''>that</span>
  <span m=''2284580''>I</span> <span m=''2284640''>guess</span> <span m=''2285650''>his</span>
  <span m=''2285900''>card?</span> <span m=''2287420''>Why</span> <span m=''2287630''>do</span>
  <span m=''2287710''>we</span> <span m=''2287810''>all</span> <span m=''2287960''>wind</span>
  <span m=''2288180''>up</span> <span m=''2288280''>in</span> <span m=''2288330''>the</span>
  <span m=''2288420''>same</span> <span m=''2288630''>place?</span> <span m=''2290830''>Any</span>
  <span m=''2291030''>thoughts?</span> <span m=''2291370''>Yeah?</span> </p><p><span
  m=''2292860''>AUDIENCE: Get the</span> <span m=''2293305''>same</span> <span m=''2293750''>card.</span>
  <span m=''2293972''>After</span> <span m=''2294195''>that</span> <span m=''2294640''>you</span>
  <span m=''2295085''>stay</span> <span m=''2295975''>[INAUDIBLE].</span> </p><p><span
  m=''2296870''>PROFESSOR: That''s</span> <span m=''2297230''>right.</span> <span
  m=''2297525''>If</span> <span m=''2297820''>ever</span> <span m=''2298270''>we</span>
  <span m=''2298440''>had</span> <span m=''2298730''>the same</span> <span m=''2299170''>card,</span>
  <span m=''2300680''>then</span> <span m=''2300850''>we''re</span> <span m=''2300960''>going</span>
  <span m=''2301040''>to</span> <span m=''2301100''>track</span> <span m=''2301470''>forever</span>
  <span m=''2301930''>and</span> <span m=''2302070''>finish in</span> <span m=''2302520''>the</span>
  <span m=''2302610''>same</span> <span m=''2302910''>card.</span> <span m=''2303910''>But</span>
  <span m=''2304060''>why</span> <span m=''2304200''>should</span> <span m=''2304400''>we</span>
  <span m=''2304500''>ever</span> <span m=''2304650''>get</span> <span m=''2304790''>the</span>
  <span m=''2304870''>same</span> <span m=''2305100''>card?</span> <span m=''2305710''>What</span>
  <span m=''2306010''>are</span> <span m=''2306030''>the</span> <span m=''2306170''>chances</span>
  <span m=''2306610''>of</span> <span m=''2306720''>that,</span> <span m=''2308520''>that</span>
  <span m=''2308610''>we</span> <span m=''2308720''>land on</span> <span m=''2309020''>the</span>
  <span m=''2309110''>same</span> <span m=''2309350''>card?</span> </p><p><span m=''2312120''>Why</span>
  <span m=''2312280''>don''t</span> <span m=''2312380''>we</span> <span m=''2312470''>just</span>
  <span m=''2312670''>keep</span> <span m=''2312870''>missing</span> <span m=''2313230''>each</span>
  <span m=''2313430''>other?</span> <span m=''2313810''>It''s</span> <span m=''2313950''>a</span>
  <span m=''2314170''>1 in</span> <span m=''2314260''>9</span> <span m=''2314510''>chance</span>
  <span m=''2314920''>or</span> <span m=''2315000''>something.</span> <span m=''2315410''>I</span>
  <span m=''2315540''>don''t</span> <span m=''2315690''>know.</span> <span m=''2316440''>Why</span>
  <span m=''2316590''>don''t we</span> <span m=''2316790''>keep</span> <span m=''2316980''>missing?</span>
  </p><p><span m=''2317330''>AUDIENCE: It</span> <span m=''2317610''>seems</span>
  <span m=''2317910''>like</span> <span m=''2318120''>there are enough</span> <span
  m=''2318570''>low</span> <span m=''2318760''>cards</span> <span m=''2319420''>that
  you</span> <span m=''2319780''>just move</span> <span m=''2320270''>slowly</span>
  <span m=''2320720''>along</span> <span m=''2321190''>and,</span> <span m=''2321380''>eventually,</span>
  <span m=''2321880''>you''re going</span> <span m=''2322380''>to intersect.</span>
  </p><p><span m=''2323550''>PROFESSOR: Yeah.</span> <span m=''2324190''>I</span>
  <span m=''2324280''>did</span> <span m=''2324640''>make</span> <span m=''2324820''>a</span>
  <span m=''2324880''>lot</span> <span m=''2325060''>of</span> <span m=''2325140''>1''s</span>
  <span m=''2325395''>in the</span> <span m=''2325650''>deck.</span> <span m=''2327060''>If</span>
  <span m=''2327460''>I would''ve</span> <span m=''2327610''>made</span> <span m=''2327850''>all
  these</span> <span m=''2328120''>face</span> <span m=''2328460''>cards be</span>
  <span m=''2328850''>10''s,</span> <span m=''2330020''>the</span> <span m=''2330100''>chances</span>
  <span m=''2330490''>of</span> <span m=''2330550''>my</span> <span m=''2330930''>reading</span>
  <span m=''2331170''>your</span> <span m=''2331280''>mind</span> <span m=''2331630''>go</span>
  <span m=''2331800''>down.</span> </p><p><span m=''2333360''>Why</span> <span m=''2333580''>do</span>
  <span m=''2333650''>they</span> <span m=''2333780''>go</span> <span m=''2333930''>down?</span>
  <span m=''2335590''>What</span> <span m=''2335780''>does</span> <span m=''2335940''>it</span>
  <span m=''2335990''>have</span> <span m=''2336120''>to</span> <span m=''2336190''>do?</span>
  <span m=''2336300''>Why did</span> <span m=''2336590''>I</span> <span m=''2336800''>put</span>
  <span m=''2336950''>a</span> <span m=''2336990''>lot</span> <span m=''2337170''>of</span>
  <span m=''2337240''>1''s</span> <span m=''2337560''>in</span> <span m=''2337600''>the</span>
  <span m=''2337700''>deck?</span> </p><p><span m=''2340320''>AUDIENCE: It</span>
  <span m=''2340600''>goes</span> <span m=''2340840''>on longer.</span> </p><p><span
  m=''2341770''>PROFESSOR: What''s</span> <span m=''2341970''>that?</span> </p><p><span
  m=''2342400''>AUDIENCE: The game</span> <span m=''2342650''>goes</span> <span m=''2342880''>on
  longer?</span> </p><p><span m=''2344520''>PROFESSOR: The</span> <span m=''2344590''>game</span>
  <span m=''2344860''>goes</span> <span m=''2345060''>on</span> <span m=''2345210''>longer.</span>
  <span m=''2345510''>So</span> <span m=''2345610''>there''s</span> <span m=''2345800''>more</span>
  <span m=''2346040''>chances</span> <span m=''2346840''>to</span> <span m=''2346970''>hit</span>
  <span m=''2347900''>together.</span> <span m=''2349180''>Because</span> <span m=''2349380''>at</span>
  <span m=''2349450''>any</span> <span m=''2349660''>given</span> <span m=''2349920''>time--</span>
  <span m=''2351790''>you''ve</span> <span m=''2351960''>got</span> <span m=''2352140''>your</span>
  <span m=''2352300''>card.</span> <span m=''2352630''>I''ve</span> <span m=''2352760''>got</span>
  <span m=''2352950''>mine.</span> </p><p><span m=''2353250''>If</span> <span m=''2353370''>mine
  is</span> <span m=''2353670''>behind</span> <span m=''2354330''>you,</span> <span
  m=''2355030''>I</span> <span m=''2355140''>got</span> <span m=''2355280''>a</span>
  <span m=''2355330''>chance</span> <span m=''2355700''>to</span> <span m=''2355860''>land</span>
  <span m=''2356300''>on</span> <span m=''2356490''>you.</span> <span m=''2357590''>And</span>
  <span m=''2357730''>if</span> <span m=''2357810''>you''re</span> <span m=''2358050''>behind</span>
  <span m=''2358590''>me</span> <span m=''2358780''>in</span> <span m=''2358850''>the</span>
  <span m=''2358930''>deck,</span> <span m=''2359170''>you''ve</span> <span m=''2359260''>got</span>
  <span m=''2359370''>a</span> <span m=''2359410''>chance</span> <span m=''2359710''>to</span>
  <span m=''2359800''>land</span> <span m=''2360190''>on</span> <span m=''2360340''>me</span>
  <span m=''2360540''>with</span> <span m=''2360670''>your</span> <span m=''2360770''>number.</span>
  <span m=''2362180''>And</span> <span m=''2362530''>if</span> <span m=''2362600''>the</span>
  <span m=''2362690''>numbers</span> <span m=''2363020''>are</span> <span m=''2363120''>smaller,</span>
  <span m=''2363680''>there''s</span> <span m=''2363770''>more</span> <span m=''2364000''>chances</span>
  <span m=''2365240''>to</span> <span m=''2365440''>land</span> <span m=''2365850''>on</span>
  <span m=''2366010''>each</span> <span m=''2366210''>other.</span> </p><p><span m=''2367190''>And</span>
  <span m=''2367560''>it</span> <span m=''2367640''>is</span> <span m=''2367810''>true</span>
  <span m=''2368120''>that</span> <span m=''2368300''>on</span> <span m=''2368440''>any</span>
  <span m=''2368770''>given</span> <span m=''2369070''>chance,</span> <span m=''2370010''>the</span>
  <span m=''2370110''>chances</span> <span m=''2370490''>are</span> <span m=''2370580''>low</span>
  <span m=''2370920''>that</span> <span m=''2371020''>we</span> <span m=''2371150''>land</span>
  <span m=''2371370''>on</span> <span m=''2371450''>the</span> <span m=''2371520''>same</span>
  <span m=''2371780''>card.</span> <span m=''2373300''>But</span> <span m=''2373820''>there''s</span>
  <span m=''2373980''>a</span> <span m=''2374040''>lot</span> <span m=''2374270''>of</span>
  <span m=''2374320''>chances.</span> <span m=''2375990''>And</span> <span m=''2376180''>if</span>
  <span m=''2376250''>there''s</span> <span m=''2376410''>a</span> <span m=''2376470''>lot</span>
  <span m=''2376700''>more</span> <span m=''2376890''>chances</span> <span m=''2377610''>than</span>
  <span m=''2377700''>the</span> <span m=''2377780''>probability</span> <span m=''2378270''>of</span>
  <span m=''2378370''>landing</span> <span m=''2378770''>on</span> <span m=''2378900''>each</span>
  <span m=''2379090''>other,</span> <span m=''2380720''>we''ve</span> <span m=''2380830''>got</span>
  <span m=''2381790''>Murphy''s</span> <span m=''2382220''>law.</span> <span m=''2384580''>If
  you''ve</span> <span m=''2384740''>got</span> <span m=''2384880''>a</span> <span
  m=''2384930''>lot</span> <span m=''2385220''>of</span> <span m=''2386020''>chances</span>
  <span m=''2387490''>and</span> <span m=''2387680''>they''re</span> <span m=''2387770''>not</span>
  <span m=''2388820''>less</span> <span m=''2389230''>likely</span> <span m=''2389600''>than
  the</span> <span m=''2389720''>number of</span> <span m=''2390120''>chances</span>
  <span m=''2390550''>or</span> <span m=''2390590''>the</span> <span m=''2390710''>inverse</span>
  <span m=''2391040''>of</span> <span m=''2391110''>that,</span> <span m=''2391690''>then</span>
  <span m=''2391850''>we</span> <span m=''2391960''>expect</span> <span m=''2392670''>to</span>
  <span m=''2392740''>have</span> <span m=''2392910''>a</span> <span m=''2392990''>certain</span>
  <span m=''2393350''>bunch</span> <span m=''2393680''>of</span> <span m=''2393750''>times
  that</span> <span m=''2394010''>we''re</span> <span m=''2394130''>going</span> <span
  m=''2394210''>to</span> <span m=''2394270''>land</span> <span m=''2394550''>on</span>
  <span m=''2394670''>each</span> <span m=''2394860''>other.</span> <span m=''2396050''>And</span>
  <span m=''2396170''>therefore,</span> <span m=''2396620''>a very</span> <span m=''2396970''>high</span>
  <span m=''2397080''>probability</span> <span m=''2397530''>we</span> <span m=''2397670''>do.</span>
  </p><p><span m=''2399970''>Now</span> <span m=''2401340''>that</span> <span m=''2401500''>was</span>
  <span m=''2401640''>a</span> <span m=''2401710''>little</span> <span m=''2402030''>hand-wavy.</span>
  <span m=''2406430''>And</span> <span m=''2406710''>in</span> <span m=''2406810''>fact,</span>
  <span m=''2407140''>there''s</span> <span m=''2407280''>a</span> <span m=''2407360''>reason</span>
  <span m=''2407750''>it</span> <span m=''2407850''>was</span> <span m=''2407860''>hand-wavy.</span>
  <span m=''2409210''>Why</span> <span m=''2409720''>doesn''t</span> <span m=''2410100''>Murphy''s</span>
  <span m=''2410450''>law</span> <span m=''2410770''>really</span> <span m=''2411430''>apply</span>
  <span m=''2412790''>in</span> <span m=''2412970''>this</span> <span m=''2413180''>case,</span>
  <span m=''2413510''>really</span> <span m=''2413860''>mathematically</span> <span
  m=''2414500''>apply?</span> <span m=''2414820''>Yeah.</span> </p><p><span m=''2418794''>AUDIENCE:
  They''re not</span> <span m=''2419250''>mutually independent.</span> <span m=''2420190''>Once
  you</span> <span m=''2421110''>draw one</span> <span m=''2421570''>card,</span>
  <span m=''2422530''>it''s</span> <span m=''2422720''>not coming</span> <span m=''2423050''>back.</span>
  </p><p><span m=''2423940''>PROFESSOR: That''s</span> <span m=''2424270''>correct.</span>
  <span m=''2425240''>And</span> <span m=''2425440''>it</span> <span m=''2425560''>means</span>
  <span m=''2425990''>that</span> <span m=''2426170''>the</span> <span m=''2426260''>knowledge</span>
  <span m=''2426940''>that</span> <span m=''2427080''>we</span> <span m=''2427190''>haven''t</span>
  <span m=''2427470''>collided</span> <span m=''2427970''>yet</span> <span m=''2429640''>tells</span>
  <span m=''2429950''>me</span> <span m=''2430080''>something</span> <span m=''2430580''>about</span>
  <span m=''2430820''>the</span> <span m=''2430900''>cards</span> <span m=''2431300''>we''ve</span>
  <span m=''2431480''>seen--</span> <span m=''2431980''>not</span> <span m=''2432280''>a</span>
  <span m=''2432350''>lot,</span> <span m=''2432670''>but</span> <span m=''2432800''>something</span>
  <span m=''2433280''>maybe.</span> <span m=''2434670''>And</span> <span m=''2435020''>it''s</span>
  <span m=''2435160''>a</span> <span m=''2435210''>finite</span> <span m=''2435710''>deck</span>
  <span m=''2436510''>which</span> <span m=''2436740''>tells</span> <span m=''2436980''>me</span>
  <span m=''2437080''>something</span> <span m=''2437410''>about</span> <span m=''2437600''>the</span>
  <span m=''2437680''>cards</span> <span m=''2438070''>that</span> <span m=''2438160''>are</span>
  <span m=''2438260''>coming.</span> </p><p><span m=''2439180''>And</span> <span m=''2439360''>it</span>
  <span m=''2439410''>might</span> <span m=''2439610''>influence</span> <span m=''2440140''>the</span>
  <span m=''2440220''>probability</span> <span m=''2440840''>that</span> <span m=''2441020''>we</span>
  <span m=''2441230''>land</span> <span m=''2441680''>together,</span> <span m=''2442220''>the</span>
  <span m=''2442230''>next</span> <span m=''2442440''>person</span> <span m=''2442710''>who''s</span>
  <span m=''2442890''>jumping</span> <span m=''2444210''>on</span> <span m=''2444350''>the</span>
  <span m=''2444450''>deck.</span> <span m=''2445390''>And</span> <span m=''2445630''>so</span>
  <span m=''2446160''>the</span> <span m=''2446370''>events</span> <span m=''2446970''>of--</span>
  <span m=''2447850''>like</span> <span m=''2447980''>for</span> <span m=''2448070''>example,</span>
  <span m=''2448480''>in</span> <span m=''2448580''>this</span> <span m=''2448610''>case,</span>
  <span m=''2448870''>we</span> <span m=''2449030''>let</span> <span m=''2449360''>A
  i</span> <span m=''2449750''>be</span> <span m=''2449990''>the</span> <span m=''2450150''>event</span>
  <span m=''2451080''>of</span> <span m=''2451200''>a</span> <span m=''2451270''>collision</span>
  <span m=''2451760''>on</span> <span m=''2451860''>the</span> <span m=''2451990''>i-th</span>
  <span m=''2452230''>jump.</span> <span m=''2454930''>And</span> <span m=''2455010''>there''s</span>
  <span m=''2455150''>about</span> <span m=''2455430''>20</span> <span m=''2455760''>jumps</span>
  <span m=''2456130''>in</span> <span m=''2456170''>this</span> <span m=''2456340''>game,</span>
  <span m=''2456580''>10</span> <span m=''2456850''>for</span> <span m=''2457050''>each</span>
  <span m=''2457230''>of</span> <span m=''2457330''>us</span> <span m=''2458180''>expected.</span>
  <span m=''2461230''>So</span> <span m=''2461370''>A i</span> <span m=''2461670''>is</span>
  <span m=''2461830''>the</span> <span m=''2461940''>event</span> <span m=''2462250''>that
  we</span> <span m=''2462450''>collide</span> <span m=''2466020''>on</span> <span
  m=''2466190''>the</span> <span m=''2466330''>i-th</span> <span m=''2466570''>jump.</span>
  <span m=''2471420''>These</span> <span m=''2471720''>events</span> <span m=''2472230''>are</span>
  <span m=''2472410''>not</span> <span m=''2472980''>necessarily</span> <span m=''2473570''>mutually</span>
  <span m=''2473930''>independent.</span> </p><p><span m=''2475710''>Now</span> <span
  m=''2476140''>if</span> <span m=''2476390''>I</span> <span m=''2476510''>had</span>
  <span m=''2476820''>an</span> <span m=''2477310''>infinite</span> <span m=''2478090''>deck</span>
  <span m=''2478850''>or</span> <span m=''2479180''>a</span> <span m=''2479440''>deck</span>
  <span m=''2479900''>with</span> <span m=''2480080''>replacement</span> <span m=''2481850''>so</span>
  <span m=''2482350''>every</span> <span m=''2482690''>card</span> <span m=''2483000''>is</span>
  <span m=''2483100''>equally</span> <span m=''2483410''>likely</span> <span m=''2483710''>to</span>
  <span m=''2483770''>come</span> <span m=''2484010''>next</span> <span m=''2484360''>no</span>
  <span m=''2484410''>matter</span> <span m=''2484600''>what''s</span> <span m=''2484880''>come</span>
  <span m=''2485030''>in</span> <span m=''2485080''>the</span> <span m=''2485170''>past,</span>
  <span m=''2486230''>now</span> <span m=''2486480''>you</span> <span m=''2486620''>can</span>
  <span m=''2486740''>start</span> <span m=''2486980''>getting</span> <span m=''2487230''>some</span>
  <span m=''2487410''>mutual</span> <span m=''2487820''>independence</span> <span
  m=''2488330''>here.</span> <span m=''2488630''>And</span> <span m=''2488740''>then</span>
  <span m=''2488890''>you</span> <span m=''2488970''>could</span> <span m=''2489100''>start</span>
  <span m=''2489350''>really</span> <span m=''2489640''>applying</span> <span m=''2490120''>the</span>
  <span m=''2490200''>theorem.</span> <span m=''2491880''>Now</span> <span m=''2492000''>in</span>
  <span m=''2492060''>this</span> <span m=''2492240''>case,</span> <span m=''2492500''>you</span>
  <span m=''2492570''>don''t</span> <span m=''2492730''>expect</span> <span m=''2493190''>10</span>
  <span m=''2493450''>things</span> <span m=''2493750''>to</span> <span m=''2493860''>happen.</span>
  <span m=''2494730''>You</span> <span m=''2494880''>expect</span> <span m=''2495280''>a</span>
  <span m=''2495330''>few.</span> </p><p><span m=''2496190''>But</span> <span m=''2496310''>that''s</span>
  <span m=''2496550''>good</span> <span m=''2496720''>enough</span> <span m=''2497280''>that,</span>
  <span m=''2497410''>in</span> <span m=''2497490''>fact--</span> <span m=''2498860''>so
  we</span> <span m=''2499030''>did</span> <span m=''2499150''>a</span> <span m=''2499230''>computer</span>
  <span m=''2499640''>simulation</span> <span m=''2500230''>once</span> <span m=''2500990''>and</span>
  <span m=''2501250''>I</span> <span m=''2501320''>got</span> <span m=''2501490''>about</span>
  <span m=''2501720''>a</span> <span m=''2501760''>90%</span> <span m=''2502630''>chance</span>
  <span m=''2503790''>that</span> <span m=''2503910''>we''ll</span> <span m=''2504060''>all</span>
  <span m=''2504300''>be</span> <span m=''2504440''>on</span> <span m=''2504530''>the</span>
  <span m=''2504610''>same</span> <span m=''2504870''>card.</span> <span m=''2505970''>So</span>
  <span m=''2506090''>I</span> <span m=''2506110''>have</span> <span m=''2506200''>a</span>
  <span m=''2506280''>pretty</span> <span m=''2506600''>good</span> <span m=''2506780''>chance</span>
  <span m=''2507240''>that</span> <span m=''2507460''>I''m</span> <span m=''2507630''>going</span>
  <span m=''2507760''>to</span> <span m=''2507830''>guess</span> <span m=''2508160''>right.</span>
  <span m=''2508640''>And</span> <span m=''2508900''>so</span> <span m=''2509040''>far,</span>
  <span m=''2509180''>I</span> <span m=''2509310''>haven''t</span> <span m=''2509660''>guessed</span>
  <span m=''2509910''>wrong.</span> <span m=''2511410''>But</span> <span m=''2511730''>it</span>
  <span m=''2511800''>will</span> <span m=''2511990''>happen</span> <span m=''2512300''>some</span>
  <span m=''2512540''>day</span> <span m=''2513270''>that</span> <span m=''2513410''>we''ll</span>
  <span m=''2513670''>start</span> <span m=''2513900''>with</span> <span m=''2514030''>a</span>
  <span m=''2514080''>different</span> <span m=''2514400''>first</span> <span m=''2514660''>number,</span>
  <span m=''2515180''>and</span> <span m=''2515470''>we</span> <span m=''2515580''>will</span>
  <span m=''2515720''>miss</span> <span m=''2516170''>at</span> <span m=''2516280''>the</span>
  <span m=''2516430''>end</span> <span m=''2517130''>because</span> <span m=''2517360''>they''ll</span>
  <span m=''2517450''>be</span> <span m=''2517620''>two</span> <span m=''2518010''>possible</span>
  <span m=''2518530''>outcomes.</span> <span m=''2520000''>Just</span> <span m=''2520180''>the</span>
  <span m=''2520260''>way</span> <span m=''2520380''>it</span> <span m=''2520450''>works
  out</span> <span m=''2520700''>with</span> <span m=''2520830''>52</span> <span m=''2521240''>cards.</span>
  </p><p><span m=''2521620''>Now</span> <span m=''2521710''>of</span> <span m=''2521770''>course,</span>
  <span m=''2521990''>if</span> <span m=''2522070''>we</span> <span m=''2522150''>have</span>
  <span m=''2522280''>more</span> <span m=''2522530''>cards</span> <span m=''2523320''>or</span>
  <span m=''2523560''>I</span> <span m=''2523950''>made</span> <span m=''2524250''>more</span>
  <span m=''2524460''>things</span> <span m=''2524730''>be</span> <span m=''2524860''>1''s</span>
  <span m=''2525360''>instead</span> <span m=''2525610''>of</span> <span m=''2525690''>9''s,</span>
  <span m=''2526210''>say,</span> <span m=''2527020''>my</span> <span m=''2527220''>odds</span>
  <span m=''2527510''>go</span> <span m=''2527670''>up</span> <span m=''2527870''>because</span>
  <span m=''2528040''>the</span> <span m=''2529240''>number</span> <span m=''2529440''>of</span>
  <span m=''2529520''>events</span> <span m=''2529900''>I''ve</span> <span m=''2529970''>got,</span>
  <span m=''2530290''>the</span> <span m=''2530360''>number</span> <span m=''2530520''>of</span>
  <span m=''2530580''>chances</span> <span m=''2531070''>to</span> <span m=''2531190''>collide,</span>
  <span m=''2532080''>increases.</span> <span m=''2533970''>And</span> <span m=''2534180''>the</span>
  <span m=''2534250''>chance</span> <span m=''2534640''>of</span> <span m=''2534870''>hitting</span>
  <span m=''2535210''>when</span> <span m=''2535330''>I</span> <span m=''2535410''>jump</span>
  <span m=''2535730''>also</span> <span m=''2536140''>increases.</span> <span m=''2537920''>Any</span>
  <span m=''2538080''>questions</span> <span m=''2539140''>on</span> <span m=''2539290''>that</span>
  <span m=''2539470''>game?</span> </p><p><span m=''2543490''>So</span> <span m=''2543620''>the</span>
  <span m=''2543700''>point</span> <span m=''2544030''>of</span> <span m=''2544140''>all</span>
  <span m=''2544330''>this</span> <span m=''2544650''>is</span> <span m=''2545010''>that</span>
  <span m=''2546760''>if</span> <span m=''2547000''>the</span> <span m=''2547140''>expected</span>
  <span m=''2547790''>number</span> <span m=''2548090''>of</span> <span m=''2548140''>events</span>
  <span m=''2548440''>to</span> <span m=''2548550''>occur</span> <span m=''2549000''>is</span>
  <span m=''2549200''>small,</span> <span m=''2551660''>then</span> <span m=''2551730''>it''s</span>
  <span m=''2551870''>an</span> <span m=''2551990''>upper</span> <span m=''2552260''>bound</span>
  <span m=''2552600''>on</span> <span m=''2552670''>the</span> <span m=''2552760''>probability</span>
  <span m=''2553400''>that</span> <span m=''2553620''>something</span> <span m=''2554000''>happens,</span>
  <span m=''2556060''>whether</span> <span m=''2556250''>they''re</span> <span m=''2556450''>independent</span>
  <span m=''2556960''>or</span> <span m=''2557060''>not.</span> <span m=''2558550''>If</span>
  <span m=''2558850''>the</span> <span m=''2559000''>expected</span> <span m=''2559550''>number</span>
  <span m=''2559770''>of</span> <span m=''2559840''>events</span> <span m=''2560230''>to</span>
  <span m=''2560360''>occur</span> <span m=''2561130''>is</span> <span m=''2561320''>bigger</span>
  <span m=''2561650''>than</span> <span m=''2561840''>1,</span> <span m=''2562310''>large,</span>
  <span m=''2563940''>and</span> <span m=''2564380''>if</span> <span m=''2564480''>the</span>
  <span m=''2564610''>events</span> <span m=''2564900''>are</span> <span m=''2564950''>mutually</span>
  <span m=''2565300''>independent,</span> <span m=''2566390''>then</span> <span m=''2566580''>you</span>
  <span m=''2566730''>can</span> <span m=''2566870''>be</span> <span m=''2566980''>sure</span>
  <span m=''2568350''>one</span> <span m=''2568590''>of</span> <span m=''2568630''>those</span>
  <span m=''2568830''>events</span> <span m=''2569140''>is</span> <span m=''2569240''>going</span>
  <span m=''2569370''>to</span> <span m=''2569460''>occur--</span> <span m=''2570010''>very,</span>
  <span m=''2570790''>very</span> <span m=''2570950''>likely</span> <span m=''2571470''>one</span>
  <span m=''2571660''>of</span> <span m=''2571710''>them</span> <span m=''2571790''>will</span>
  <span m=''2572010''>occur.</span> <span m=''2572260''>And that''s</span> <span m=''2572470''>Murphy''s</span>
  <span m=''2572850''>law.</span> <span m=''2574690''>Any</span> <span m=''2574860''>questions</span>
  <span m=''2575310''>about</span> <span m=''2576370''>numbers</span> <span m=''2576730''>of</span>
  <span m=''2576820''>events</span> <span m=''2577140''>to</span> <span m=''2577250''>occur?</span>
  </p><p></p><p><span m=''2581930''>We''ll</span> <span m=''2582410''>talk</span>
  <span m=''2582740''>more</span> <span m=''2583220''>about</span> <span m=''2583650''>the</span>
  <span m=''2583740''>probability</span> <span m=''2584470''>in</span> <span m=''2584560''>the</span>
  <span m=''2584630''>numbers</span> <span m=''2585010''>of</span> <span m=''2585090''>events</span>
  <span m=''2585520''>that</span> <span m=''2585600''>occur</span> <span m=''2586040''>next</span>
  <span m=''2586350''>time.</span> <span m=''2589250''>Before</span> <span m=''2589510''>we</span>
  <span m=''2589610''>do</span> <span m=''2589740''>that,</span> <span m=''2590050''>I
  want</span> <span m=''2590150''>to</span> <span m=''2590200''>talk</span> <span
  m=''2590430''>about</span> <span m=''2590600''>some</span> <span m=''2590710''>more</span>
  <span m=''2590880''>useful</span> <span m=''2591320''>facts</span> <span m=''2591970''>about</span>
  <span m=''2592360''>expectation.</span> <span m=''2596100''>Now</span> <span m=''2597390''>we</span>
  <span m=''2597520''>know</span> <span m=''2597830''>from</span> <span m=''2598060''>linearity</span>
  <span m=''2598620''>of</span> <span m=''2598680''>expectation</span> <span m=''2600020''>that</span>
  <span m=''2600150''>the</span> <span m=''2600280''>expected</span> <span m=''2600870''>value</span>
  <span m=''2601240''>of</span> <span m=''2601320''>a</span> <span m=''2601390''>sum</span>
  <span m=''2602940''>of</span> <span m=''2603100''>random</span> <span m=''2603420''>variables</span>
  <span m=''2604330''>is</span> <span m=''2604550''>the</span> <span m=''2604640''>sum</span>
  <span m=''2605360''>of</span> <span m=''2605510''>the</span> <span m=''2605620''>expected</span>
  <span m=''2606130''>values</span> <span m=''2607320''>of</span> <span m=''2607410''>the</span>
  <span m=''2607510''>random</span> <span m=''2607790''>variables.</span> </p><p><span
  m=''2610550''>Now</span> <span m=''2610860''>we''re</span> <span m=''2610960''>going</span>
  <span m=''2611040''>to</span> <span m=''2611100''>look</span> <span m=''2611350''>at</span>
  <span m=''2611830''>the</span> <span m=''2611960''>expected</span> <span m=''2612520''>value</span>
  <span m=''2613180''>of</span> <span m=''2613300''>a</span> <span m=''2613380''>product</span>
  <span m=''2614600''>of</span> <span m=''2614730''>random</span> <span m=''2615070''>variables.</span>
  <span m=''2616660''>And</span> <span m=''2616800''>it</span> <span m=''2616880''>turns</span>
  <span m=''2617200''>out</span> <span m=''2617320''>there''s</span> <span m=''2617490''>a</span>
  <span m=''2617540''>very</span> <span m=''2617830''>nice</span> <span m=''2618170''>rule</span>
  <span m=''2618530''>for</span> <span m=''2618650''>that.</span> <span m=''2621530''>Theorem</span>
  <span m=''2621870''>4,</span> <span m=''2622430''>and</span> <span m=''2622550''>it''s</span>
  <span m=''2622700''>the</span> <span m=''2622790''>product</span> <span m=''2623340''>rule</span>
  <span m=''2626320''>for</span> <span m=''2626440''>expectation.</span> <span m=''2633010''>And</span>
  <span m=''2633160''>it</span> <span m=''2633280''>says</span> <span m=''2633770''>that</span>
  <span m=''2634780''>for--</span> <span m=''2635610''>if</span> <span m=''2635770''>your</span>
  <span m=''2636070''>random</span> <span m=''2636360''>variables</span> <span m=''2636770''>are</span>
  <span m=''2637000''>independent,</span> <span m=''2646120''>R1</span> <span m=''2646455''>and</span>
  <span m=''2646790''>R2</span> <span m=''2647550''>are</span> <span m=''2647770''>independent,</span>
  <span m=''2649140''>then</span> <span m=''2649210''>the</span> <span m=''2649360''>expected</span>
  <span m=''2650450''>value</span> <span m=''2650990''>of</span> <span m=''2651160''>their</span>
  <span m=''2651310''>product,</span> <span m=''2652690''>also a</span> <span m=''2653020''>random</span>
  <span m=''2653330''>variable,</span> <span m=''2654550''>is</span> <span m=''2654710''>simply</span>
  <span m=''2655110''>the</span> <span m=''2655210''>product</span> <span m=''2656410''>of</span>
  <span m=''2656590''>the</span> <span m=''2656710''>expected</span> <span m=''2657210''>values.</span>
  </p><p><span m=''2660150''>So</span> <span m=''2660330''>it''s</span> <span m=''2661440''>sort</span>
  <span m=''2661750''>of</span> <span m=''2662390''>the</span> <span m=''2662760''>equivalent</span>
  <span m=''2663460''>thing</span> <span m=''2663650''>to</span> <span m=''2663740''>linearity</span>
  <span m=''2664140''>of</span> <span m=''2664210''>expectation,</span> <span m=''2664980''>except</span>
  <span m=''2665390''>we''re</span> <span m=''2665480''>doing</span> <span m=''2665680''>products.</span>
  <span m=''2666910''>And</span> <span m=''2667080''>you</span> <span m=''2667180''>need</span>
  <span m=''2667470''>independence.</span> <span m=''2671970''>Now</span> <span m=''2672100''>the</span>
  <span m=''2672200''>proof</span> <span m=''2672430''>of</span> <span m=''2672490''>this</span>
  <span m=''2672650''>is</span> <span m=''2672760''>not</span> <span m=''2672990''>too</span>
  <span m=''2673120''>hard,</span> <span m=''2673580''>and</span> <span m=''2673660''>it''s</span>
  <span m=''2673780''>in</span> <span m=''2673860''>the</span> <span m=''2673940''>book.</span>
  <span m=''2674280''>So</span> <span m=''2674380''>we''re</span> <span m=''2674470''>not</span>
  <span m=''2674660''>going</span> <span m=''2674760''>to</span> <span m=''2675330''>do</span>
  <span m=''2675510''>it</span> <span m=''2675560''>in</span> <span m=''2675650''>class.</span>
  <span m=''2677400''>But</span> <span m=''2677500''>we can</span> <span m=''2677600''>give</span>
  <span m=''2677650''>an</span> <span m=''2677730''>example.</span> </p><p><span m=''2681030''>Say</span>
  <span m=''2681360''>we</span> <span m=''2681520''>roll</span> <span m=''2683610''>two</span>
  <span m=''2684420''>six-sided</span> <span m=''2687640''>fair</span> <span m=''2689070''>and</span>
  <span m=''2689310''>independent</span> <span m=''2692360''>dice.</span> <span m=''2698230''>And</span>
  <span m=''2698520''>I</span> <span m=''2698560''>want</span> <span m=''2698840''>to</span>
  <span m=''2698880''>know</span> <span m=''2699200''>what''s</span> <span m=''2699580''>the</span>
  <span m=''2699720''>expected</span> <span m=''2700440''>product</span> <span m=''2701420''>of</span>
  <span m=''2701600''>the</span> <span m=''2701700''>dice.</span> </p><p></p><p><span
  m=''2710900''>So</span> <span m=''2711030''>we''re</span> <span m=''2711130''>going</span>
  <span m=''2711210''>to</span> <span m=''2711280''>let</span> <span m=''2711670''>R1</span>
  <span m=''2712570''>be</span> <span m=''2713020''>the</span> <span m=''2713130''>value</span>
  <span m=''2715070''>on</span> <span m=''2715220''>the</span> <span m=''2715310''>first</span>
  <span m=''2715640''>die,</span> <span m=''2718720''>and</span> <span m=''2718980''>R2</span>
  <span m=''2720340''>would</span> <span m=''2720470''>be</span> <span m=''2720600''>the</span>
  <span m=''2720690''>value</span> <span m=''2721250''>on</span> <span m=''2721480''>the</span>
  <span m=''2721560''>second</span> <span m=''2721940''>one.</span> <span m=''2725060''>And</span>
  <span m=''2725280''>the</span> <span m=''2725410''>expected</span> <span m=''2726040''>value</span>
  <span m=''2728080''>of</span> <span m=''2728170''>the</span> <span m=''2728260''>product</span>
  <span m=''2731670''>is</span> <span m=''2732170''>the</span> <span m=''2732280''>product</span>
  <span m=''2732790''>of</span> <span m=''2732860''>the</span> <span m=''2732960''>expectations.</span>
  <span m=''2737910''>And</span> <span m=''2738310''>we</span> <span m=''2738440''>already</span>
  <span m=''2738690''>know</span> <span m=''2738930''>the</span> <span m=''2739040''>expected</span>
  <span m=''2739540''>value</span> <span m=''2739900''>of a</span> <span m=''2739970''>single</span>
  <span m=''2740320''>die</span> <span m=''2740640''>is</span> <span m=''2740790''>7/2.</span>
  <span m=''2743160''>So</span> <span m=''2743270''>we</span> <span m=''2743370''>get</span>
  <span m=''2743490''>7/2</span> <span m=''2744080''>times</span> <span m=''2744300''>7/2</span>
  <span m=''2745100''>is</span> <span m=''2745730''>49/4</span> <span m=''2746670''>or</span>
  <span m=''2746750''>12 and</span> <span m=''2747140''>1/4.</span> </p><p><span m=''2749260''>So</span>
  <span m=''2749430''>it''s</span> <span m=''2749540''>easy</span> <span m=''2749830''>to</span>
  <span m=''2749890''>compute</span> <span m=''2750290''>the</span> <span m=''2750390''>expected</span>
  <span m=''2752010''>product</span> <span m=''2753060''>of</span> <span m=''2753250''>two</span>
  <span m=''2753440''>dice.</span> <span m=''2755400''>Any</span> <span m=''2755560''>questions</span>
  <span m=''2756500''>about</span> <span m=''2756730''>that?</span> <span m=''2760910''>Much</span>
  <span m=''2761170''>easier</span> <span m=''2761400''>than</span> <span m=''2761570''>looking</span>
  <span m=''2761800''>at</span> <span m=''2761850''>all</span> <span m=''2762060''>36</span>
  <span m=''2762570''>outcomes</span> <span m=''2763650''>to</span> <span m=''2764000''>use</span>
  <span m=''2764260''>this</span> <span m=''2764460''>rule.</span> </p><p><span m=''2766200''>Now</span>
  <span m=''2766260''>what</span> <span m=''2766530''>if</span> <span m=''2766620''>the</span>
  <span m=''2766740''>dice</span> <span m=''2767100''>we''re</span> <span m=''2767310''>rigged,</span>
  <span m=''2769480''>glued</span> <span m=''2769830''>together</span> <span m=''2770550''>somehow</span>
  <span m=''2771350''>so</span> <span m=''2771470''>they</span> <span m=''2771630''>always</span>
  <span m=''2771950''>came</span> <span m=''2772160''>up</span> <span m=''2772280''>the</span>
  <span m=''2772360''>same?</span> <span m=''2775780''>Would</span> <span m=''2775960''>the</span>
  <span m=''2776090''>expected</span> <span m=''2776660''>product</span> <span m=''2777120''>B</span>
  <span m=''2777510''>12</span> <span m=''2777790''>and</span> <span m=''2777830''>1/4</span>
  <span m=''2778150''>then?</span> <span m=''2781990''>No?</span> <span m=''2782610''>Why</span>
  <span m=''2782930''>not?</span> </p><p><span m=''2784460''>Why</span> <span m=''2785130''>wouldn''t</span>
  <span m=''2785380''>it</span> <span m=''2785450''>be</span> <span m=''2785540''>the</span>
  <span m=''2785660''>case?</span> <span m=''2789670''>Why</span> <span m=''2789970''>isn''t</span>
  <span m=''2790190''>the</span> <span m=''2790310''>expected</span> <span m=''2790860''>value</span>
  <span m=''2791240''>of</span> <span m=''2791340''>R1</span> <span m=''2791890''>squared</span>
  <span m=''2793140''>the</span> <span m=''2793240''>square</span> <span m=''2793500''>of</span>
  <span m=''2793760''>the</span> <span m=''2794250''>expected</span> <span m=''2794600''>value</span>
  <span m=''2794840''>of</span> <span m=''2794940''>R1?</span> <span m=''2797060''>Isn''t
  that</span> <span m=''2797320''>what</span> <span m=''2797580''>this</span> <span
  m=''2797610''>says?</span> </p><p><span m=''2800174''>AUDIENCE: Independent.</span>
  </p><p><span m=''2801150''>PROFESSOR: They''re</span> <span m=''2801270''>not</span>
  <span m=''2801540''>independent.</span> <span m=''2802730''>R1</span> <span m=''2803480''>is</span>
  <span m=''2803600''>not</span> <span m=''2803890''>independent</span> <span m=''2804350''>of</span>
  <span m=''2804450''>R1</span> <span m=''2805020''>In fact,</span> <span m=''2805120''>it''s</span>
  <span m=''2805310''>the same</span> <span m=''2805680''>thing.</span> <span m=''2807120''>And
  you</span> <span m=''2807340''>need</span> <span m=''2807620''>independence</span>
  <span m=''2808160''>for</span> <span m=''2808240''>that</span> <span m=''2808420''>to</span>
  <span m=''2808490''>be</span> <span m=''2808590''>the</span> <span m=''2808690''>case.</span>
  </p><p><span m=''2810490''>So</span> <span m=''2811540''>a</span> <span m=''2811600''>non</span>
  <span m=''2812000''>example,</span> <span m=''2816430''>the</span> <span m=''2816500''>expected</span>
  <span m=''2817010''>value</span> <span m=''2817520''>of</span> <span m=''2817660''>R1</span>
  <span m=''2818920''>times</span> <span m=''2819300''>R1</span> <span m=''2822140''>is</span>
  <span m=''2823610''>the</span> <span m=''2823680''>expected</span> <span m=''2824210''>value</span>
  <span m=''2825220''>of</span> <span m=''2825370''>R1</span> <span m=''2825880''>squared.</span>
  <span m=''2827950''>And</span> <span m=''2828310''>to</span> <span m=''2828460''>do</span>
  <span m=''2828600''>that,</span> <span m=''2828960''>we</span> <span m=''2829060''>got</span>
  <span m=''2829090''>to</span> <span m=''2829130''>go</span> <span m=''2829230''>back</span>
  <span m=''2829460''>to</span> <span m=''2829540''>the</span> <span m=''2829620''>basics.</span>
  <span m=''2830210''>We''re</span> <span m=''2830230''>taking</span> <span m=''2830560''>the</span>
  <span m=''2830630''>six</span> <span m=''2830960''>possible</span> <span m=''2831340''>values</span>
  <span m=''2831650''>of</span> <span m=''2831750''>R1.</span> </p><p><span m=''2832805''>i</span>
  <span m=''2833250''>equals</span> <span m=''2833490''>1</span> <span m=''2833710''>to</span>
  <span m=''2833780''>6.</span> <span m=''2835400''>i</span> <span m=''2835660''>squared,</span>
  <span m=''2836360''>because</span> <span m=''2836540''>we''re</span> <span m=''2837110''>squaring</span>
  <span m=''2837630''>it,</span> <span m=''2838550''>times</span> <span m=''2839050''>the</span>
  <span m=''2839120''>probability</span> <span m=''2839830''>R1</span> <span m=''2840370''>equals</span>
  <span m=''2840660''>i.</span> <span m=''2843660''>And</span> <span m=''2844750''>each</span>
  <span m=''2844960''>of</span> <span m=''2845010''>those</span> <span m=''2845160''>probabilities</span>
  <span m=''2845670''>is</span> <span m=''2845780''>1/6.</span> <span m=''2846020''>So</span>
  <span m=''2846490''>we</span> <span m=''2846620''>get</span> <span m=''2846740''>1/6</span>
  <span m=''2847290''>times</span> <span m=''2848580''>1</span> <span m=''2848950''>plus</span>
  <span m=''2849280''>4</span> <span m=''2849730''>plus</span> <span m=''2850090''>9</span>
  <span m=''2851100''>plus</span> <span m=''2851380''>16</span> <span m=''2852020''>plus</span>
  <span m=''2852340''>25</span> <span m=''2853520''>plus</span> <span m=''2853830''>36.</span>
  </p><p><span m=''2856470''>And</span> <span m=''2856680''>if</span> <span m=''2856760''>you</span>
  <span m=''2856850''>add</span> <span m=''2857040''>all</span> <span m=''2857210''>that</span>
  <span m=''2857390''>up</span> <span m=''2857640''>you</span> <span m=''2857760''>get</span>
  <span m=''2858870''>15</span> <span m=''2859160''>and</span> <span m=''2859450''>1/6,</span>
  <span m=''2862250''>which</span> <span m=''2862500''>is</span> <span m=''2862630''>not</span>
  <span m=''2865360''>3</span> <span m=''2865730''>and</span> <span m=''2866100''>1/2</span>
  <span m=''2866380''>squared,</span> <span m=''2868400''>which</span> <span m=''2868570''>is</span>
  <span m=''2869510''>the</span> <span m=''2869770''>expected</span> <span m=''2870180''>value</span>
  <span m=''2870450''>of</span> <span m=''2870530''>R1</span> <span m=''2871980''>squared.</span>
  <span m=''2874340''>So</span> <span m=''2874460''>the</span> <span m=''2875300''>expected</span>
  <span m=''2875800''>value</span> <span m=''2876070''>of</span> <span m=''2876120''>the</span>
  <span m=''2876220''>square</span> <span m=''2876660''>is</span> <span m=''2876950''>not</span>
  <span m=''2877420''>necessarily</span> <span m=''2878840''>the</span> <span m=''2878930''>square</span>
  <span m=''2879270''>of</span> <span m=''2879330''>the</span> <span m=''2879410''>expectation.</span>
  <span m=''2881150''>Because</span> <span m=''2882090''>a</span> <span m=''2882160''>random</span>
  <span m=''2882360''>variable</span> <span m=''2882620''>is</span> <span m=''2882690''>not</span>
  <span m=''2882930''>independent</span> <span m=''2883330''>of</span> <span m=''2883440''>itself</span>
  <span m=''2883820''>generally.</span> </p><p><span m=''2887450''>OK.</span> <span
  m=''2888190''>Any</span> <span m=''2888290''>questions</span> <span m=''2889990''>there?</span>
  <span m=''2892910''>There''s</span> <span m=''2893090''>a</span> <span m=''2893140''>couple
  of</span> <span m=''2893390''>quick</span> <span m=''2893620''>corollaries.</span>
  </p><p></p><p><span m=''2899250''>The</span> <span m=''2899400''>first</span> <span
  m=''2899800''>is</span> <span m=''2900010''>you</span> <span m=''2900370''>take</span>
  <span m=''2900640''>this</span> <span m=''2900830''>rule and</span> <span m=''2901140''>apply
  it</span> <span m=''2901590''>to</span> <span m=''2901740''>many</span> <span m=''2902230''>random</span>
  <span m=''2902570''>variables</span> <span m=''2904020''>as</span> <span m=''2904160''>long</span>
  <span m=''2904400''>as</span> <span m=''2904490''>they''re</span> <span m=''2904620''>mutually</span>
  <span m=''2905090''>dependent.</span> <span m=''2906067''>So if</span> <span m=''2906524''>R1</span>
  <span m=''2907780''>R2</span> <span m=''2909550''>out</span> <span m=''2910000''>to</span>
  <span m=''2910110''>R</span> <span m=''2910514''>n</span> <span m=''2911726''>are</span>
  <span m=''2912130''>mutually</span> <span m=''2912630''>independent,</span> <span
  m=''2920580''>then</span> <span m=''2920850''>the</span> <span m=''2920970''>expected</span>
  <span m=''2921580''>value</span> <span m=''2921970''>of</span> <span m=''2922040''>their</span>
  <span m=''2922190''>product</span> <span m=''2928620''>is</span> <span m=''2928990''>the</span>
  <span m=''2929080''>product</span> <span m=''2929640''>of</span> <span m=''2929720''>the</span>
  <span m=''2929790''>expected</span> <span m=''2930240''>values.</span> <span m=''2939720''>And</span>
  <span m=''2939980''>the</span> <span m=''2940070''>proof</span> <span m=''2940460''>is</span>
  <span m=''2940750''>just</span> <span m=''2940990''>by</span> <span m=''2941140''>induction</span>
  <span m=''2942340''>on</span> <span m=''2943270''>the</span> <span m=''2943360''>number</span>
  <span m=''2943620''>of</span> <span m=''2943680''>random</span> <span m=''2943930''>variables.</span>
  <span m=''2944550''>So</span> <span m=''2944650''>that''s</span> <span m=''2944670''>pretty</span>
  <span m=''2944900''>easy.</span> </p><p><span m=''2946550''>There''s</span> <span
  m=''2946720''>another</span> <span m=''2947010''>easy</span> <span m=''2947360''>corollary.</span>
  <span m=''2951718''>And</span> <span m=''2952170''>that</span> <span m=''2952380''>says,</span>
  <span m=''2953410''>for</span> <span m=''2953620''>any</span> <span m=''2953830''>constants,</span>
  <span m=''2955350''>constant</span> <span m=''2955800''>values,</span> <span m=''2959670''>a
  and</span> <span m=''2960020''>b,</span> <span m=''2962610''>and</span> <span m=''2963440''>any</span>
  <span m=''2963760''>random</span> <span m=''2964120''>variable</span> <span m=''2964550''>R,</span>
  <span m=''2968150''>the</span> <span m=''2968280''>expected</span> <span m=''2968880''>value</span>
  <span m=''2970050''>of</span> <span m=''2970330''>a</span> <span m=''2970630''>times</span>
  <span m=''2971040''>R</span> <span m=''2971430''>plus</span> <span m=''2971770''>b</span>
  <span m=''2973410''>is</span> <span m=''2973580''>simply</span> <span m=''2974720''>a</span>
  <span m=''2975060''>times</span> <span m=''2975460''>the</span> <span m=''2975570''>expected</span>
  <span m=''2976080''>value</span> <span m=''2976390''>of</span> <span m=''2976480''>R</span>
  <span m=''2978040''>plus</span> <span m=''2978310''>b.</span> <span m=''2981360''>And</span>
  <span m=''2981480''>the</span> <span m=''2981560''>reason</span> <span m=''2981870''>that''s</span>
  <span m=''2982120''>true--</span> <span m=''2983090''>well,</span> <span m=''2983320''>the</span>
  <span m=''2983420''>sum</span> <span m=''2983860''>works</span> <span m=''2984230''>because</span>
  <span m=''2984590''>of</span> <span m=''2984690''>linearity</span> <span m=''2985150''>of</span>
  <span m=''2985220''>expectation</span> <span m=''2986110''>for</span> <span m=''2986190''>the</span>
  <span m=''2986290''>sum.</span> <span m=''2987300''>You</span> <span m=''2987410''>can</span>
  <span m=''2987550''>think</span> <span m=''2987740''>of</span> <span m=''2987820''>b</span>
  <span m=''2988070''>as</span> <span m=''2988180''>a</span> <span m=''2988270''>random</span>
  <span m=''2988620''>variable</span> <span m=''2989150''>that</span> <span m=''2989240''>just</span>
  <span m=''2989680''>always</span> <span m=''2990030''>has</span> <span m=''2990230''>the</span>
  <span m=''2990270''>value</span> <span m=''2990590''>b.</span> </p><p><span m=''2992950''>And</span>
  <span m=''2993255''>the</span> <span m=''2993560''>a</span> <span m=''2993860''>comes</span>
  <span m=''2994170''>out</span> <span m=''2994830''>in</span> <span m=''2994980''>front</span>
  <span m=''2995770''>because</span> <span m=''2996980''>you</span> <span m=''2997110''>can</span>
  <span m=''2997240''>think</span> <span m=''2997420''>of</span> <span m=''2997500''>it</span>
  <span m=''2997560''>as</span> <span m=''2997680''>a</span> <span m=''2997760''>random</span>
  <span m=''2998080''>variable</span> <span m=''2998460''>that</span> <span m=''2998570''>always</span>
  <span m=''2999000''>has</span> <span m=''2999260''>a</span> <span m=''2999420''>value</span>
  <span m=''2999740''>a.</span> <span m=''3001225''>And</span> <span m=''3001720''>that''s</span>
  <span m=''3001930''>independent</span> <span m=''3002480''>of</span> <span m=''3002810''>any</span>
  <span m=''3003040''>other</span> <span m=''3003200''>random</span> <span m=''3003440''>variable</span>
  <span m=''3004240''>because</span> <span m=''3005000''>it</span> <span m=''3005150''>never</span>
  <span m=''3005360''>changes.</span> <span m=''3006630''>So</span> <span m=''3007050''>by</span>
  <span m=''3007310''>the</span> <span m=''3007410''>product</span> <span m=''3007850''>rule,</span>
  <span m=''3008290''>the</span> <span m=''3008450''>a</span> <span m=''3008610''>can</span>
  <span m=''3008780''>come</span> <span m=''3008960''>out.</span> </p><p><span m=''3010550''>Now
  you''ve</span> <span m=''3010710''>got</span> <span m=''3010850''>to</span> <span
  m=''3010920''>prove</span> <span m=''3011360''>all</span> <span m=''3011500''>that.</span>
  <span m=''3011700''>But</span> <span m=''3011790''>it''s</span> <span m=''3012260''>not</span>
  <span m=''3012420''>too</span> <span m=''3012520''>hard</span> <span m=''3012820''>and</span>
  <span m=''3013100''>not</span> <span m=''3013330''>especially</span> <span m=''3013800''>interesting.</span>
  <span m=''3014180''>So</span> <span m=''3014300''>we</span> <span m=''3014370''>won''t</span>
  <span m=''3014570''>do</span> <span m=''3014700''>that</span> <span m=''3014890''>here.</span>
  <span m=''3018390''>Any</span> <span m=''3018530''>questions</span> <span m=''3018940''>about</span>
  <span m=''3019190''>those?</span> </p><p></p><p><span m=''3027140''>So</span> <span
  m=''3027260''>we''ve</span> <span m=''3027330''>got</span> <span m=''3027480''>a</span>
  <span m=''3027560''>rule</span> <span m=''3027970''>for</span> <span m=''3028110''>computing</span>
  <span m=''3028530''>the</span> <span m=''3028620''>sum</span> <span m=''3029050''>of</span>
  <span m=''3029150''>random</span> <span m=''3029470''>variables,</span> <span m=''3030680''>a</span>
  <span m=''3030860''>rule</span> <span m=''3031310''>for</span> <span m=''3031430''>the</span>
  <span m=''3031550''>product</span> <span m=''3032170''>of</span> <span m=''3032260''>random</span>
  <span m=''3032590''>variables.</span> <span m=''3034420''>What</span> <span m=''3034610''>about</span>
  <span m=''3034950''>a</span> <span m=''3035090''>rule</span> <span m=''3035640''>for</span>
  <span m=''3036530''>the</span> <span m=''3036700''>ratio</span> <span m=''3038170''>of</span>
  <span m=''3038340''>random</span> <span m=''3038710''>variables?</span> <span m=''3039350''>Let''s
  look at</span> <span m=''3039815''>that.</span> </p><p><span m=''3045330''>So</span>
  <span m=''3046770''>is</span> <span m=''3046940''>this</span> <span m=''3047140''>the</span>
  <span m=''3047220''>corollary?</span> <span m=''3050490''>In</span> <span m=''3050610''>fact,</span>
  <span m=''3051050''>let''s</span> <span m=''3051130''>take</span> <span m=''3051330''>the</span>
  <span m=''3051520''>inverse</span> <span m=''3051850''>of</span> <span m=''3052180''>random</span>
  <span m=''3052550''>variable.</span> <span m=''3052890''>Is</span> <span m=''3053140''>the</span>
  <span m=''3053310''>expected</span> <span m=''3053880''>value</span> <span m=''3054330''>of</span>
  <span m=''3054490''>1/R</span> <span m=''3056730''>equal</span> <span m=''3057140''>to</span>
  <span m=''3057290''>1</span> <span m=''3057690''>over</span> <span m=''3058020''>the</span>
  <span m=''3058180''>expected</span> <span m=''3058750''>value</span> <span m=''3060130''>of</span>
  <span m=''3060300''>R</span> <span m=''3060710''>for</span> <span m=''3060880''>any</span>
  <span m=''3061120''>random</span> <span m=''3061470''>variable</span> <span m=''3061840''>R?</span>
  <span m=''3064510''>Some</span> <span m=''3064800''>folks</span> <span m=''3065910''>saying</span>
  <span m=''3066150''>yes.</span> <span m=''3066560''>Some</span> <span m=''3066660''>saying</span>
  <span m=''3066970''>no.</span> </p><p><span m=''3069240''>What</span> <span m=''3069490''>do</span>
  <span m=''3069540''>you</span> <span m=''3069640''>think?</span> <span m=''3070350''>Is</span>
  <span m=''3070610''>that</span> <span m=''3071150''>true?</span> <span m=''3074610''>Oh,</span>
  <span m=''3074905''>got a</span> <span m=''3075200''>mix.</span> <span m=''3075790''>How</span>
  <span m=''3075900''>many</span> <span m=''3076040''>say</span> <span m=''3076200''>yes?</span>
  <span m=''3077910''>How</span> <span m=''3078000''>many</span> <span m=''3078130''>say</span>
  <span m=''3078310''>no?</span> </p><p><span m=''3079385''>Oh,</span> <span m=''3079730''>more</span>
  <span m=''3079980''>no''s.</span> <span m=''3080500''>Somebody</span> <span m=''3080870''>tell</span>
  <span m=''3081040''>me</span> <span m=''3081160''>why</span> <span m=''3081390''>that''s</span>
  <span m=''3081630''>not</span> <span m=''3081810''>true.</span> <span m=''3082940''>Who</span>
  <span m=''3082980''>would</span> <span m=''3083070''>like</span> <span m=''3083200''>to</span>
  <span m=''3083280''>give</span> <span m=''3083450''>me</span> <span m=''3083510''>an</span>
  <span m=''3083560''>example?</span> <span m=''3086058''>Give us</span> <span m=''3086520''>an</span>
  <span m=''3086590''>example</span> <span m=''3087120''>there</span> <span m=''3088390''>that''ll</span>
  <span m=''3088950''>be</span> <span m=''3089060''>very</span> <span m=''3089360''>convincing.</span>
  <span m=''3091345''>Yeah?</span> </p><p><span m=''3094075''>AUDIENCE: I don''t</span>
  <span m=''3094540''>think</span> <span m=''3094700''>it''s one</span> <span m=''3094860''>that
  would</span> <span m=''3095070''>be</span> <span m=''3095930''>immediately</span>
  <span m=''3096370''>obvious,</span> <span m=''3096790''>but</span> <span m=''3097470''>I</span>
  <span m=''3097580''>think</span> <span m=''3097910''>if</span> <span m=''3098140''>R</span>
  <span m=''3098450''>is</span> <span m=''3098670''>the</span> <span m=''3099470''>result</span>
  <span m=''3099750''>of</span> <span m=''3100480''>the roll of a</span> <span m=''3100800''>die,</span>
  <span m=''3101558''>I</span> <span m=''3102494''>don''t think it works</span> <span
  m=''3102962''>out.</span> </p><p><span m=''3103900''>PROFESSOR: So</span> <span
  m=''3104550''>it''s</span> <span m=''3104730''>50</span> <span m=''3105030''>chance</span>
  <span m=''3105510''>of--</span> <span m=''3106430''>oh,</span> <span m=''3106680''>I</span>
  <span m=''3106780''>see.</span> <span m=''3107060''>So</span> <span m=''3108560''>I</span>
  <span m=''3108670''>take</span> <span m=''3108850''>the</span> <span m=''3109010''>average</span>
  <span m=''3109380''>of</span> <span m=''3109520''>1/i--</span> <span m=''3112320''>that''s</span>
  <span m=''3112450''>sort</span> <span m=''3112680''>of</span> <span m=''3112730''>hard</span>
  <span m=''3112940''>to</span> <span m=''3113000''>compute.</span> <span m=''3113380''>I</span>
  <span m=''3113420''>got</span> <span m=''3113580''>to do</span> <span m=''3113620''>[INAUDIBLE]</span>
  <span m=''3113900''>the</span> <span m=''3114040''>sixth</span> <span m=''3114360''>harmonic</span>
  <span m=''3114850''>number</span> <span m=''3115200''>and</span> <span m=''3115290''>then</span>
  <span m=''3115430''>invert</span> <span m=''3115840''>it.</span> <span m=''3116825''>There''s</span>
  <span m=''3117240''>an</span> <span m=''3117380''>easier</span> <span m=''3117740''>way</span>
  <span m=''3118090''>to</span> <span m=''3118130''>show that</span> <span m=''3118450''>this</span>
  <span m=''3118790''>is</span> <span m=''3119240''>false.</span> <span m=''3120474''>Yeah?</span>
  </p><p><span m=''3120938''>AUDIENCE: The expected</span> <span m=''3121402''>value</span>
  <span m=''3121866''>equals 0?</span> </p><p><span m=''3123260''>PROFESSOR: Yeah.</span>
  <span m=''3123535''>The</span> <span m=''3123810''>expected</span> <span m=''3124250''>value</span>
  <span m=''3124590''>equals</span> <span m=''3125050''>0</span> <span m=''3127120''>which</span>
  <span m=''3127330''>could</span> <span m=''3127450''>happen</span> <span m=''3127830''>if</span>
  <span m=''3128100''>R</span> <span m=''3128490''>is</span> <span m=''3128770''>plus</span>
  <span m=''3129080''>1</span> <span m=''3129410''>or</span> <span m=''3129550''>minus</span>
  <span m=''3130010''>1</span> <span m=''3130240''>equally</span> <span m=''3130620''>likely.</span>
  <span m=''3132520''>So</span> <span m=''3133240''>here''s</span> <span m=''3133780''>an</span>
  <span m=''3133860''>example</span> <span m=''3134410''>here.</span> <span m=''3135840''>So</span>
  <span m=''3136180''>R</span> <span m=''3136650''>equals</span> <span m=''3138040''>1</span>
  <span m=''3139240''>with</span> <span m=''3139480''>probability</span> <span m=''3140040''>1/2,</span>
  <span m=''3141860''>and</span> <span m=''3142010''>minus</span> <span m=''3142440''>1</span>
  <span m=''3143640''>with</span> <span m=''3143780''>probability</span> <span m=''3144320''>1/2.</span>
  <span m=''3145500''>So</span> <span m=''3145670''>the</span> <span m=''3145830''>expected</span>
  <span m=''3146400''>value</span> <span m=''3146700''>of</span> <span m=''3146810''>R</span>
  <span m=''3147160''>is</span> <span m=''3147390''>0.</span> </p><p></p><p><span
  m=''3152370''>So</span> <span m=''3152520''>that</span> <span m=''3152750''>blows</span>
  <span m=''3153100''>up.</span> <span m=''3153370''>That''s</span> <span m=''3153600''>infinity.</span>
  <span m=''3154760''>What''s</span> <span m=''3154900''>the</span> <span m=''3155010''>expected</span>
  <span m=''3155450''>value</span> <span m=''3155730''>of</span> <span m=''3155790''>1/R?</span>
  </p><p></p><p><span m=''3161320''>Well,</span> <span m=''3161670''>1/1</span> <span
  m=''3162060''>and</span> <span m=''3162380''>1</span> <span m=''3162570''>over</span>
  <span m=''3162700''>minus</span> <span m=''3163050''>1,</span> <span m=''3163400''>it''s</span>
  <span m=''3163480''>the</span> <span m=''3163560''>same.</span> <span m=''3164300''>It</span>
  <span m=''3164620''>equals</span> <span m=''3164940''>0.</span> <span m=''3166300''>And</span>
  <span m=''3166430''>this</span> <span m=''3166570''>would</span> <span m=''3166710''>say</span>
  <span m=''3167625''>0</span> <span m=''3168090''>equals</span> <span m=''3168340''>1/0.</span>
  </p><p><span m=''3168930''>That''s</span> <span m=''3169150''>not</span> <span m=''3169300''>true.</span>
  <span m=''3170030''>So</span> <span m=''3170140''>this</span> <span m=''3170350''>is</span>
  <span m=''3170480''>false.</span> <span m=''3171980''>It is</span> <span m=''3172240''>not</span>
  <span m=''3172500''>true</span> <span m=''3172750''>for</span> <span m=''3172940''>every</span>
  <span m=''3173610''>random</span> <span m=''3173900''>variable.</span> </p><p><span
  m=''3177350''>So</span> <span m=''3177950''>once</span> <span m=''3178210''>you</span>
  <span m=''3178300''>see</span> <span m=''3178450''>this</span> <span m=''3178640''>example,</span>
  <span m=''3179150''>just</span> <span m=''3179410''>obviously</span> <span m=''3179890''>not</span>
  <span m=''3180070''>true.</span> <span m=''3180180''>In</span> <span m=''3180260''>fact,</span>
  <span m=''3180760''>there''s</span> <span m=''3180960''>very</span> <span m=''3181240''>few</span>
  <span m=''3181450''>random</span> <span m=''3181750''>variables</span> <span m=''3182010''>for</span>
  <span m=''3182270''>which</span> <span m=''3182450''>this</span> <span m=''3182560''>is</span>
  <span m=''3182700''>true,</span> <span m=''3183840''>even an</span> <span m=''3184140''>indicator</span>
  <span m=''3184730''>random</span> <span m=''3185020''>variable.</span> <span m=''3186440''>So</span>
  <span m=''3187210''>it''s</span> <span m=''3187400''>1</span> <span m=''3187800''>with</span>
  <span m=''3187940''>probability</span> <span m=''3188490''>1/2</span> <span m=''3188840''>and</span>
  <span m=''3188940''>0</span> <span m=''3189390''>with</span> <span m=''3189550''>probability</span>
  <span m=''3190030''>1/2.</span> </p><p><span m=''3191290''>Then</span> <span m=''3191440''>the</span>
  <span m=''3191540''>expected</span> <span m=''3192080''>value</span> <span m=''3192360''>of</span>
  <span m=''3192430''>1/R</span> <span m=''3193150''>is</span> <span m=''3193260''>infinite.</span>
  <span m=''3194950''>1</span> <span m=''3195220''>over</span> <span m=''3195360''>the</span>
  <span m=''3195440''>expected</span> <span m=''3195860''>value</span> <span m=''3196090''>of</span>
  <span m=''3196170''>R is</span> <span m=''3196420''>2.</span> <span m=''3200940''>So</span>
  <span m=''3201410''>it''s</span> <span m=''3201590''>clearly</span> <span m=''3202160''>not</span>
  <span m=''3202420''>true.</span> <span m=''3204570''>Let''s</span> <span m=''3204820''>do</span>
  <span m=''3206110''>another</span> <span m=''3206588''>one.</span> </p><p></p><p><span
  m=''3214730''>What</span> <span m=''3214930''>about</span> <span m=''3215490''>this</span>
  <span m=''3216240''>potential</span> <span m=''3216750''>corollary?</span> <span
  m=''3222310''>Given</span> <span m=''3223490''>independent</span> <span m=''3225900''>random</span>
  <span m=''3226320''>variables</span> <span m=''3229100''>R</span> <span m=''3229430''>and</span>
  <span m=''3229560''>T,</span> <span m=''3233530''>if</span> <span m=''3233960''>the</span>
  <span m=''3234110''>expected</span> <span m=''3234850''>value</span> <span m=''3236450''>or</span>
  <span m=''3236785''>R/T</span> <span m=''3238360''>is</span> <span m=''3238530''>bigger</span>
  <span m=''3238790''>than</span> <span m=''3238980''>1,</span> <span m=''3242570''>then</span>
  <span m=''3243630''>the</span> <span m=''3243730''>expected</span> <span m=''3244340''>value</span>
  <span m=''3244790''>of</span> <span m=''3244890''>R</span> <span m=''3246330''>is</span>
  <span m=''3246510''>bigger</span> <span m=''3246800''>than</span> <span m=''3246950''>the</span>
  <span m=''3247070''>expected</span> <span m=''3247630''>value</span> <span m=''3248010''>of</span>
  <span m=''3248140''>T.</span> <span m=''3250050''>And</span> <span m=''3250160''>let</span>
  <span m=''3250270''>me even</span> <span m=''3250610''>give</span> <span m=''3250830''>you</span>
  <span m=''3251050''>a</span> <span m=''3252910''>potential</span> <span m=''3253500''>proof</span>
  <span m=''3253820''>of</span> <span m=''3253930''>this,</span> <span m=''3255970''>see
  if</span> <span m=''3256200''>you</span> <span m=''3256320''>like</span> <span m=''3256540''>this</span>
  <span m=''3256740''>proof.</span> </p><p><span m=''3258960''>Well,</span> <span
  m=''3259440''>let''s</span> <span m=''3259650''>assume</span> <span m=''3260070''>the</span>
  <span m=''3260170''>expected</span> <span m=''3260630''>value of</span> <span m=''3260920''>R/T</span>
  <span m=''3261560''>is</span> <span m=''3261690''>bigger</span> <span m=''3261880''>than</span>
  <span m=''3261980''>1.</span> <span m=''3265970''>And</span> <span m=''3266140''>let''s</span>
  <span m=''3266330''>multiply</span> <span m=''3266860''>both</span> <span m=''3267160''>sides</span>
  <span m=''3267640''>by</span> <span m=''3267790''>the</span> <span m=''3267910''>expected</span>
  <span m=''3268370''>value</span> <span m=''3268680''>of</span> <span m=''3268770''>T.</span>
  <span m=''3279620''>And</span> <span m=''3279740''>well,</span> <span m=''3280050''>the</span>
  <span m=''3280140''>product</span> <span m=''3280580''>rule</span> <span m=''3280880''>says</span>
  <span m=''3281620''>that</span> <span m=''3281780''>this</span> <span m=''3282050''>is</span>
  <span m=''3282240''>just</span> <span m=''3282530''>the</span> <span m=''3282630''>expected</span>
  <span m=''3283150''>value</span> <span m=''3284700''>of</span> <span m=''3285080''>R/T</span>
  <span m=''3286450''>times</span> <span m=''3286870''>T,</span> <span m=''3288590''>which</span>
  <span m=''3288830''>is</span> <span m=''3288990''>just</span> <span m=''3289330''>the</span>
  <span m=''3289440''>expected</span> <span m=''3290000''>value</span> <span m=''3290420''>of</span>
  <span m=''3290530''>R</span> <span m=''3290990''>because</span> <span m=''3291170''>the</span>
  <span m=''3291270''>T''s</span> <span m=''3291520''>cancel.</span> </p><p></p><p><span
  m=''3302690''>So</span> <span m=''3302820''>I</span> <span m=''3302880''>gave</span>
  <span m=''3303140''>you</span> <span m=''3303240''>a proof.</span> <span m=''3306370''>Anybody</span>
  <span m=''3308360''>have</span> <span m=''3308510''>any</span> <span m=''3308590''>quibbles</span>
  <span m=''3309060''>with</span> <span m=''3309170''>this</span> <span m=''3309340''>proof?</span>
  <span m=''3315190''>Yeah?</span> </p><p><span m=''3319050''>That''s</span> <span
  m=''3319360''>a</span> <span m=''3319420''>big</span> <span m=''3319610''>problem.</span>
  <span m=''3320330''>R/T</span> <span m=''3320990''>is</span> <span m=''3321140''>not</span>
  <span m=''3321500''>independent</span> <span m=''3322050''>of</span> <span m=''3322150''>T.</span>
  <span m=''3323450''>[INAUDIBLE]</span> <span m=''3323680''>if</span> <span m=''3323790''>T</span>
  <span m=''3324020''>is</span> <span m=''3324160''>very</span> <span m=''3324440''>big,</span>
  <span m=''3325690''>likely that</span> <span m=''3326120''>R/T</span> <span m=''3326640''>is</span>
  <span m=''3326760''>small.</span> </p><p><span m=''3328240''>So</span> <span m=''3328410''>we</span>
  <span m=''3328510''>can''t</span> <span m=''3328840''>do</span> <span m=''3328950''>that</span>
  <span m=''3329200''>step.</span> <span m=''3330280''>We</span> <span m=''3330420''>can''t</span>
  <span m=''3330800''>use</span> <span m=''3331180''>the</span> <span m=''3331280''>independence</span>
  <span m=''3331920''>here</span> <span m=''3332490''>to</span> <span m=''3332950''>go</span>
  <span m=''3333280''>from</span> <span m=''3333480''>here</span> <span m=''3333990''>to</span>
  <span m=''3334070''>here.</span> <span m=''3334950''>That''s</span> <span m=''3335230''>wrong.</span>
  </p><p><span m=''3336030''>There''s</span> <span m=''3336530''>actually</span> <span
  m=''3336780''>another</span> <span m=''3337050''>big</span> <span m=''3337310''>problem</span>
  <span m=''3337610''>with</span> <span m=''3337700''>this</span> <span m=''3337870''>proof.</span>
  <span m=''3339530''>Anybody</span> <span m=''3339620''>see</span> <span m=''3339790''>another</span>
  <span m=''3340050''>problem?</span> <span m=''3340640''>Yeah?</span> </p><p><span
  m=''3343990''>Yeah.</span> <span m=''3344880''>If</span> <span m=''3345020''>the</span>
  <span m=''3345090''>expected</span> <span m=''3345590''>value</span> <span m=''3345950''>of</span>
  <span m=''3346040''>T</span> <span m=''3346310''>is</span> <span m=''3346470''>negative,</span>
  <span m=''3347840''>I</span> <span m=''3348050''>would</span> <span m=''3348530''>end</span>
  <span m=''3348710''>up</span> <span m=''3348830''>doing</span> <span m=''3349060''>that.</span>
  <span m=''3350440''>So</span> <span m=''3350550''>that</span> <span m=''3350830''>step''s</span>
  <span m=''3351110''>wrong.</span> </p><p><span m=''3352030''>So</span> <span m=''3352170''>this</span>
  <span m=''3352430''>is</span> <span m=''3352700''>a</span> <span m=''3352760''>pretty</span>
  <span m=''3352950''>lousy</span> <span m=''3353310''>proof.</span> <span m=''3353600''>Every</span>
  <span m=''3353820''>step</span> <span m=''3354110''>is</span> <span m=''3354490''>wrong.</span>
  <span m=''3355900''>So</span> <span m=''3356020''>this</span> <span m=''3356190''>is</span>
  <span m=''3356300''>not</span> <span m=''3356570''>a</span> <span m=''3356630''>good</span>
  <span m=''3356830''>one</span> <span m=''3357080''>to</span> <span m=''3357190''>use.</span>
  </p><p><span m=''3358170''>And</span> <span m=''3358610''>in</span> <span m=''3358820''>fact,</span>
  <span m=''3361570''>the</span> <span m=''3361680''>theorem</span> <span m=''3362050''>is</span>
  <span m=''3362160''>wrong.</span> <span m=''3364780''>Not only is the</span> <span
  m=''3365150''>proof</span> <span m=''3365450''>wrong,</span> <span m=''3365690''>but</span>
  <span m=''3365810''>the</span> <span m=''3365890''>result</span> <span m=''3366270''>is</span>
  <span m=''3366380''>wrong.</span> <span m=''3367100''>It''s</span> <span m=''3367320''>not</span>
  <span m=''3367720''>true.</span> <span m=''3368950''>And</span> <span m=''3369140''>we</span>
  <span m=''3369260''>can</span> <span m=''3369840''>see</span> <span m=''3370070''>examples.</span>
  <span m=''3371890''>We''ll</span> <span m=''3372020''>do</span> <span m=''3372130''>some</span>
  <span m=''3372290''>examples</span> <span m=''3372730''>in</span> <span m=''3372810''>a</span>
  <span m=''3372860''>minute.</span> </p><p><span m=''3373840''>Now</span> <span m=''3374200''>the</span>
  <span m=''3374340''>amazing</span> <span m=''3374790''>thing</span> <span m=''3375030''>is</span>
  <span m=''3375230''>that</span> <span m=''3375330''>despite</span> <span m=''3375680''>the</span>
  <span m=''3375770''>fact</span> <span m=''3376050''>that</span> <span m=''3376150''>this</span>
  <span m=''3376350''>is</span> <span m=''3376470''>just</span> <span m=''3377820''>blatantly</span>
  <span m=''3378360''>wrong,</span> <span m=''3379520''>it</span> <span m=''3379660''>is</span>
  <span m=''3379820''>used</span> <span m=''3380280''>all</span> <span m=''3380480''>the</span>
  <span m=''3380590''>time</span> <span m=''3381610''>in</span> <span m=''3381760''>research</span>
  <span m=''3382110''>papers.</span> <span m=''3383270''>And</span> <span m=''3383400''>let</span>
  <span m=''3383500''>me</span> <span m=''3383620''>give</span> <span m=''3383790''>you</span>
  <span m=''3384370''>a</span> <span m=''3384450''>famous</span> <span m=''3384880''>example.</span>
  <span m=''3386280''>This</span> <span m=''3386550''>is</span> <span m=''3386650''>a</span>
  <span m=''3386700''>case</span> <span m=''3387970''>of,</span> <span m=''3389080''>actually,</span>
  <span m=''3389220''>a</span> <span m=''3389360''>pretty</span> <span m=''3389580''>well-known</span>
  <span m=''3390830''>paper</span> <span m=''3392070''>written</span> <span m=''3392430''>by</span>
  <span m=''3392710''>some</span> <span m=''3393260''>very</span> <span m=''3393700''>famous</span>
  <span m=''3394350''>computer</span> <span m=''3394710''>science</span> <span m=''3395100''>professors</span>
  <span m=''3395610''>at</span> <span m=''3395710''>Berkeley.</span> <span m=''3398640''>And</span>
  <span m=''3399020''>let</span> <span m=''3399110''>me</span> <span m=''3399210''>show</span>
  <span m=''3399450''>you</span> <span m=''3399670''>what</span> <span m=''3399800''>they</span>
  <span m=''3399920''>did.</span> <span m=''3402130''>And</span> <span m=''3402260''>this</span>
  <span m=''3402430''>is</span> <span m=''3402520''>so</span> <span m=''3402740''>that</span>
  <span m=''3402910''>you</span> <span m=''3403110''>will</span> <span m=''3403280''>never</span>
  <span m=''3403780''>do</span> <span m=''3403970''>this.</span> </p><p><span m=''3405950''>They</span>
  <span m=''3406130''>were</span> <span m=''3406250''>trying</span> <span m=''3406600''>to</span>
  <span m=''3406670''>compare</span> <span m=''3410540''>two</span> <span m=''3412540''>instruction</span>
  <span m=''3413130''>sets</span> <span m=''3414350''>way</span> <span m=''3414610''>back</span>
  <span m=''3414870''>in</span> <span m=''3414930''>the</span> <span m=''3415020''>day.</span>
  <span m=''3415510''>And</span> <span m=''3415650''>they</span> <span m=''3415760''>were</span>
  <span m=''3415900''>comparing</span> <span m=''3416510''>the</span> <span m=''3417040''>RISC</span>
  <span m=''3417940''>architecture</span> <span m=''3418750''>to</span> <span m=''3418870''>something</span>
  <span m=''3419120''>called</span> <span m=''3419420''>the</span> <span m=''3419490''>Z8002.</span>
  <span m=''3421740''>And</span> <span m=''3422290''>they</span> <span m=''3422380''>were</span>
  <span m=''3422490''>proponents</span> <span m=''3422970''>of</span> <span m=''3423070''>RISC.</span>
  <span m=''3424260''>And</span> <span m=''3425800''>they</span> <span m=''3425960''>were</span>
  <span m=''3426070''>using</span> <span m=''3426330''>this</span> <span m=''3426460''>to</span>
  <span m=''3426550''>prove that</span> <span m=''3426910''>it</span> <span m=''3427030''>was</span>
  <span m=''3427170''>a</span> <span m=''3427220''>better</span> <span m=''3427470''>way</span>
  <span m=''3427600''>to</span> <span m=''3427700''>do</span> <span m=''3427840''>things.</span>
  </p><p><span m=''3429290''>So</span> <span m=''3429310''>they</span> <span m=''3429410''>had</span>
  <span m=''3429490''>a</span> <span m=''3429520''>bunch</span> <span m=''3429750''>of</span>
  <span m=''3429830''>benchmark</span> <span m=''3430410''>problems,</span> <span
  m=''3432650''>probably</span> <span m=''3432920''>20</span> <span m=''3433290''>or</span>
  <span m=''3433390''>so</span> <span m=''3434290''>in</span> <span m=''3434420''>the</span>
  <span m=''3434510''>paper.</span> <span m=''3434940''>And</span> <span m=''3435060''>I''m</span>
  <span m=''3435170''>not</span> <span m=''3435370''>going</span> <span m=''3435480''>to</span>
  <span m=''3435550''>do</span> <span m=''3435720''>all</span> <span m=''3435990''>20</span>
  <span m=''3436310''>here.</span> <span m=''3436520''>I''m</span> <span m=''3436630''>going</span>
  <span m=''3436710''>to</span> <span m=''3436750''>give</span> <span m=''3436950''>you</span>
  <span m=''3437050''>a</span> <span m=''3437100''>flavor</span> <span m=''3437540''>for</span>
  <span m=''3437640''>what</span> <span m=''3437760''>the</span> <span m=''3437860''>data</span>
  <span m=''3438130''>showed.</span> <span m=''3439210''>And</span> <span m=''3439370''>then</span>
  <span m=''3439490''>they</span> <span m=''3439580''>looked</span> <span m=''3439820''>at</span>
  <span m=''3439890''>the</span> <span m=''3439990''>code</span> <span m=''3440370''>size</span>
  <span m=''3444100''>for</span> <span m=''3444530''>RISC</span> <span m=''3447110''>and</span>
  <span m=''3447560''>the</span> <span m=''3448750''>other</span> <span m=''3448970''>guys,</span>
  <span m=''3449320''>Z8002.</span> <span m=''3452290''>And</span> <span m=''3452460''>then</span>
  <span m=''3452600''>they</span> <span m=''3452710''>took</span> <span m=''3452940''>the</span>
  <span m=''3453050''>ratio.</span> </p><p></p><p><span m=''3460020''>So</span> <span
  m=''3460290''>the</span> <span m=''3460410''>first</span> <span m=''3460750''>problem</span>
  <span m=''3461190''>was</span> <span m=''3461350''>called</span> <span m=''3461910''>E-string</span>
  <span m=''3462480''>search,</span> <span m=''3464720''>whatever</span> <span m=''3464920''>that</span>
  <span m=''3465160''>is.</span> <span m=''3465440''>But</span> <span m=''3465540''>it</span>
  <span m=''3465620''>was</span> <span m=''3465720''>some</span> <span m=''3465950''>benchmark</span>
  <span m=''3466480''>problem</span> <span m=''3466870''>out</span> <span m=''3467050''>there
  at the</span> <span m=''3467530''>time.</span> <span m=''3468820''>And</span> <span
  m=''3469090''>the</span> <span m=''3469170''>code</span> <span m=''3469450''>length</span>
  <span m=''3469750''>on</span> <span m=''3469890''>RISC</span> <span m=''3470250''>was</span>
  <span m=''3470380''>150</span> <span m=''3471510''>say--</span> <span m=''3472210''>I''ve</span>
  <span m=''3472360''>changed these</span> <span m=''3472760''>numbers</span> <span
  m=''3472990''>a</span> <span m=''3473040''>little</span> <span m=''3473300''>bit</span>
  <span m=''3473450''>to</span> <span m=''3473530''>make</span> <span m=''3473660''>them</span>
  <span m=''3473780''>simpler.</span> <span m=''3474820''>Code</span> <span m=''3475050''>length</span>
  <span m=''3475320''>here</span> <span m=''3475870''>and</span> <span m=''3476140''>the</span>
  <span m=''3476405''>Z8002</span> <span m=''3477570''>is</span> <span m=''3477660''>120.</span>
  </p><p><span m=''3478930''>The</span> <span m=''3479030''>ratio</span> <span m=''3479460''>is</span>
  <span m=''3479570''>0.8.</span> <span m=''3481270''>So</span> <span m=''3481520''>for</span>
  <span m=''3481600''>this</span> <span m=''3481800''>problem,</span> <span m=''3482920''>you''re</span>
  <span m=''3483000''>trying</span> <span m=''3483240''>to</span> <span m=''3483290''>get</span>
  <span m=''3483470''>low,</span> <span m=''3484290''>short</span> <span m=''3484590''>code.</span>
  <span m=''3485020''>So</span> <span m=''3485100''>this</span> <span m=''3485260''>was</span>
  <span m=''3485390''>a</span> <span m=''3485440''>better</span> <span m=''3485700''>way</span>
  <span m=''3485830''>to</span> <span m=''3485910''>go</span> <span m=''3486610''>to</span>
  <span m=''3486750''>support</span> <span m=''3487110''>that.</span> </p><p><span
  m=''3488410''>And</span> <span m=''3488540''>they</span> <span m=''3488660''>had</span>
  <span m=''3488920''>something</span> <span m=''3489170''>called</span> <span m=''3489500''>F-bit</span>
  <span m=''3490020''>test.</span> <span m=''3492640''>And</span> <span m=''3492810''>here</span>
  <span m=''3493020''>you</span> <span m=''3493110''>have</span> <span m=''3493290''>120</span>
  <span m=''3494100''>lines.</span> <span m=''3494530''>Here''s</span> <span m=''3494790''>180.</span>
  <span m=''3496750''>So</span> <span m=''3496910''>in</span> <span m=''3496970''>this</span>
  <span m=''3497120''>case,</span> <span m=''3497420''>risk</span> <span m=''3497570''>is</span>
  <span m=''3497700''>better.</span> <span m=''3500260''>So</span> <span m=''3500400''>the</span>
  <span m=''3500550''>ratio</span> <span m=''3501850''>of</span> <span m=''3501970''>that</span>
  <span m=''3502200''>way to</span> <span m=''3502380''>this</span> <span m=''3502680''>way</span>
  <span m=''3502900''>would</span> <span m=''3503050''>be</span> <span m=''3503790''>1.5.</span>
  </p><p><span m=''3506500''>And</span> <span m=''3506600''>they</span> <span m=''3506700''>had</span>
  <span m=''3507160''>computing</span> <span m=''3507650''>and</span> <span m=''3507730''>Ackermann</span>
  <span m=''3508150''>function.</span> <span m=''3511540''>And</span> <span m=''3511770''>that</span>
  <span m=''3511910''>was</span> <span m=''3512040''>150</span> <span m=''3512750''>and</span>
  <span m=''3512860''>300.</span> <span m=''3514260''>So</span> <span m=''3514490''>a</span>
  <span m=''3514540''>big</span> <span m=''3514820''>win</span> <span m=''3515080''>for</span>
  <span m=''3515240''>RISC,</span> <span m=''3516380''>ratio</span> <span m=''3516790''>of</span>
  <span m=''3516900''>2.</span> </p><p><span m=''3519390''>And</span> <span m=''3519580''>then</span>
  <span m=''3519690''>they</span> <span m=''3519790''>had</span> <span m=''3521020''>a</span>
  <span m=''3521230''>thing</span> <span m=''3521340''>called</span> <span m=''3521620''>recursive</span>
  <span m=''3522690''>sorting</span> <span m=''3524920''>problem.</span> <span m=''3525690''>This</span>
  <span m=''3525880''>is</span> <span m=''3525970''>a</span> <span m=''3526020''>hard</span>
  <span m=''3526300''>problem.</span> <span m=''3527530''>There''s</span> <span m=''3527690''>2,800</span>
  <span m=''3528500''>lines</span> <span m=''3528930''>on</span> <span m=''3529080''>RISC.</span>
  <span m=''3530040''>1400</span> <span m=''3531940''>on</span> <span m=''3532200''>the</span>
  <span m=''3532330''>old</span> <span m=''3532540''>way.</span> <span m=''3534190''>Ratio</span>
  <span m=''3534455''>of</span> <span m=''3534720''>0.5.</span> </p><p><span m=''3537200''>And</span>
  <span m=''3537410''>there</span> <span m=''3537500''>was</span> <span m=''3537650''>a</span>
  <span m=''3537700''>bunch</span> <span m=''3538080''>more</span> <span m=''3538330''>which</span>
  <span m=''3538510''>I''m</span> <span m=''3538610''>not</span> <span m=''3538800''>going</span>
  <span m=''3538900''>to</span> <span m=''3538950''>go</span> <span m=''3539180''>through.</span>
  <span m=''3540400''>But</span> <span m=''3540630''>their</span> <span m=''3540810''>analysis,</span>
  <span m=''3541310''>what</span> <span m=''3541430''>they</span> <span m=''3541550''>did</span>
  <span m=''3541870''>is</span> <span m=''3542020''>they</span> <span m=''3542620''>took</span>
  <span m=''3542820''>the</span> <span m=''3542920''>ratio,</span> <span m=''3544470''>and</span>
  <span m=''3544590''>then</span> <span m=''3544680''>they</span> <span m=''3544880''>averaged</span>
  <span m=''3545450''>it.</span> <span m=''3546380''>And</span> <span m=''3546530''>so</span>
  <span m=''3546650''>when</span> <span m=''3546740''>you</span> <span m=''3546840''>do</span>
  <span m=''3547060''>this,</span> <span m=''3548030''>you</span> <span m=''3548180''>get</span>
  <span m=''3548390''>an</span> <span m=''3548490''>average</span> <span m=''3549000''>of,</span>
  <span m=''3550720''>well,</span> <span m=''3551250''>2.3,</span> <span m=''3551990''>4.3,</span>
  <span m=''3552715''>4.8/4</span> <span m=''3556510''>is</span> <span m=''3556690''>1.2.</span>
  </p><p><span m=''3559250''>So</span> <span m=''3559620''>the</span> <span m=''3559720''>conclusion</span>
  <span m=''3560310''>is</span> <span m=''3560580''>that</span> <span m=''3560820''>on</span>
  <span m=''3561090''>average</span> <span m=''3562570''>code</span> <span m=''3563080''>in</span>
  <span m=''3563180''>this</span> <span m=''3563420''>framework</span> <span m=''3563890''>is</span>
  <span m=''3564040''>20%</span> <span m=''3564700''>longer</span> <span m=''3565060''>than</span>
  <span m=''3565190''>the</span> <span m=''3565270''>code</span> <span m=''3565560''>on</span>
  <span m=''3565690''>RISC.</span> <span m=''3567400''>Therefore,</span> <span m=''3567860''>clearly,</span>
  <span m=''3568320''>RISC</span> <span m=''3568570''>is</span> <span m=''3568680''>a</span>
  <span m=''3568730''>better</span> <span m=''3568960''>way</span> <span m=''3569080''>to</span>
  <span m=''3569160''>go.</span> <span m=''3570100''>Your</span> <span m=''3570260''>code</span>
  <span m=''3571120''>on</span> <span m=''3571280''>average</span> <span m=''3571590''>will
  be</span> <span m=''3571690''>shorter.</span> <span m=''3573020''>Using</span> <span
  m=''3573410''>the</span> <span m=''3573480''>Z8002</span> <span m=''3574590''>on</span>
  <span m=''3574770''>average,</span> <span m=''3575120''>the</span> <span m=''3575220''>code</span>
  <span m=''3575480''>will</span> <span m=''3575550''>be</span> <span m=''3575660''>20%</span>
  <span m=''3576240''>longer.</span> <span m=''3578080''>Makes</span> <span m=''3578270''>perfect</span>
  <span m=''3578620''>sense,</span> <span m=''3578760''>right?</span> </p><p><span
  m=''3582162''>In fact,</span> <span m=''3582770''>this</span> <span m=''3583000''>is</span>
  <span m=''3583550''>one</span> <span m=''3583850''>of</span> <span m=''3583890''>the</span>
  <span m=''3583950''>most</span> <span m=''3584180''>common</span> <span m=''3584540''>things</span>
  <span m=''3584840''>that is</span> <span m=''3585100''>done</span> <span m=''3585490''>when</span>
  <span m=''3585620''>people</span> <span m=''3585980''>are</span> <span m=''3586060''>comparing</span>
  <span m=''3586650''>two systems.</span> <span m=''3590514''>Now</span> <span m=''3591000''>just</span>
  <span m=''3591610''>one</span> <span m=''3591920''>problem</span> <span m=''3592400''>with</span>
  <span m=''3592510''>this</span> <span m=''3593610''>approach,</span> <span m=''3595030''>and</span>
  <span m=''3596130''>that''s</span> <span m=''3596420''>that</span> <span m=''3596490''>it''s</span>
  <span m=''3596870''>completely</span> <span m=''3597410''>bogus,</span> <span m=''3598880''>completely</span>
  <span m=''3599380''>bogus.</span> <span m=''3599840''>You</span> <span m=''3599940''>cannot</span>
  <span m=''3600340''>conclude--</span> <span m=''3601720''>let''s</span> <span m=''3601930''>make</span>
  <span m=''3602060''>this</span> <span m=''3602210''>conclusion.</span> <span m=''3602820''>So</span>
  <span m=''3602830''>their</span> <span m=''3603000''>conclusion,</span> <span m=''3604720''>they</span>
  <span m=''3605170''>concluded</span> <span m=''3605760''>that</span> <span m=''3606310''>Z8002</span>
  <span m=''3608120''>programs</span> <span m=''3613090''>are</span> <span m=''3613220''>20%</span>
  <span m=''3613980''>longer</span> <span m=''3617450''>on</span> <span m=''3617650''>average.</span>
  </p><p></p><p><span m=''3624890''>Everybody</span> <span m=''3625210''>understands</span>
  <span m=''3625640''>the</span> <span m=''3625750''>reasoning</span> <span m=''3626140''>why,</span>
  <span m=''3626610''>right?</span> <span m=''3628110''>Take</span> <span m=''3628350''>the</span>
  <span m=''3628840''>ratio of</span> <span m=''3629390''>all the</span> <span m=''3629700''>test</span>
  <span m=''3629970''>cases,</span> <span m=''3630510''>average</span> <span m=''3630890''>them</span>
  <span m=''3631020''>up.</span> <span m=''3631875''>Then</span> <span m=''3632330''>you</span>
  <span m=''3632420''>get</span> <span m=''3632540''>the</span> <span m=''3632680''>average</span>
  <span m=''3632960''>ratio.</span> </p><p></p><p><span m=''3638380''>Now</span> <span
  m=''3638550''>there</span> <span m=''3638630''>could</span> <span m=''3638820''>be</span>
  <span m=''3638910''>some</span> <span m=''3639300''>hint</span> <span m=''3639790''>why</span>
  <span m=''3640020''>this</span> <span m=''3640250''>is</span> <span m=''3640360''>bogus.</span>
  <span m=''3641030''>If</span> <span m=''3641120''>I</span> <span m=''3641230''>just</span>
  <span m=''3641460''>looked</span> <span m=''3641760''>at--</span> <span m=''3643130''>I</span>
  <span m=''3643270''>took</span> <span m=''3644100''>and</span> <span m=''3644480''>summed</span>
  <span m=''3645000''>these</span> <span m=''3645310''>numbers,</span> <span m=''3647160''>if</span>
  <span m=''3647320''>I</span> <span m=''3647450''>add</span> <span m=''3647660''>all</span>
  <span m=''3647840''>those</span> <span m=''3648090''>numbers</span> <span m=''3648400''>up,</span>
  <span m=''3648520''>I</span> <span m=''3648640''>get</span> <span m=''3649600''>3,220.</span>
  <span m=''3651670''>And</span> <span m=''3651790''>all</span> <span m=''3651950''>these,</span>
  <span m=''3652250''>I</span> <span m=''3652320''>get</span> <span m=''3652750''>2,000.</span>
  <span m=''3655570''>RISC</span> <span m=''3656000''>code</span> <span m=''3656230''>is</span>
  <span m=''3656350''>not</span> <span m=''3656600''>looking</span> <span m=''3656860''>shorter</span>
  <span m=''3657280''>if</span> <span m=''3657400''>I</span> <span m=''3657480''>do</span>
  <span m=''3657650''>that.</span> <span m=''3659500''>Looking</span> <span m=''3659690''>longer.</span>
  </p><p><span m=''3662340''>But</span> <span m=''3663440''>all</span> <span m=''3663800''>that</span>
  <span m=''3664080''>gain,</span> <span m=''3665020''>all</span> <span m=''3665210''>the</span>
  <span m=''3665290''>loss of</span> <span m=''3665660''>RISC</span> <span m=''3665990''>is
  in</span> <span m=''3666140''>this</span> <span m=''3666300''>one</span> <span m=''3666850''>problem.</span>
  <span m=''3668200''>And</span> <span m=''3668330''>maybe</span> <span m=''3668530''>it''s</span>
  <span m=''3669010''>not</span> <span m=''3669280''>fair</span> <span m=''3670400''>to</span>
  <span m=''3670500''>do</span> <span m=''3670640''>that.</span> <span m=''3670960''>And</span>
  <span m=''3671060''>that''s</span> <span m=''3671200''>why</span> <span m=''3672990''>when</span>
  <span m=''3673110''>people</span> <span m=''3673390''>have</span> <span m=''3673620''>data</span>
  <span m=''3673920''>like</span> <span m=''3674160''>this,</span> <span m=''3674580''>they</span>
  <span m=''3674680''>just</span> <span m=''3674830''>take</span> <span m=''3674990''>the</span>
  <span m=''3675090''>ratios.</span> <span m=''3675620''>Because</span> <span m=''3675790''>now</span>
  <span m=''3676410''>it</span> <span m=''3676500''>would</span> <span m=''3676590''>be--</span>
  <span m=''3678090''>if</span> <span m=''3678280''>I</span> <span m=''3678380''>just</span>
  <span m=''3679140''>took</span> <span m=''3679310''>the</span> <span m=''3679470''>average</span>
  <span m=''3679800''>code</span> <span m=''3680110''>length</span> <span m=''3681290''>and</span>
  <span m=''3681390''>took</span> <span m=''3681520''>the</span> <span m=''3681630''>ratio
  of</span> <span m=''3682020''>that,</span> <span m=''3682290''>it''s</span> <span
  m=''3682430''>not</span> <span m=''3682660''>fair</span> <span m=''3682910''>because</span>
  <span m=''3683060''>one</span> <span m=''3683290''>problem</span> <span m=''3683720''>just</span>
  <span m=''3683950''>wiped</span> <span m=''3684230''>out</span> <span m=''3684370''>the</span>
  <span m=''3684440''>whole</span> <span m=''3684660''>thing.</span> </p><p><span
  m=''3686490''>I might as</span> <span m=''3686630''>well</span> <span m=''3686780''>not</span>
  <span m=''3686850''>even</span> <span m=''3687160''>do</span> <span m=''3687350''>it.</span>
  <span m=''3687700''>And</span> <span m=''3687840''>they</span> <span m=''3687910''>want</span>
  <span m=''3688120''>every</span> <span m=''3688330''>problem</span> <span m=''3688620''>to</span>
  <span m=''3688730''>count</span> <span m=''3688950''>equally.</span> <span m=''3689880''>And</span>
  <span m=''3690000''>that''s</span> <span m=''3690180''>why</span> <span m=''3690290''>they</span>
  <span m=''3690400''>take</span> <span m=''3690620''>the</span> <span m=''3690710''>ratio,</span>
  <span m=''3692210''>to</span> <span m=''3692320''>make</span> <span m=''3692500''>them
  all</span> <span m=''3692700''>count equally.</span> </p><p><span m=''3694840''>Let''s</span>
  <span m=''3695160''>do</span> <span m=''3695330''>one</span> <span m=''3695570''>more</span>
  <span m=''3695800''>thing</span> <span m=''3696080''>here.</span> <span m=''3696330''>Let''s</span>
  <span m=''3696730''>look</span> <span m=''3696970''>at</span> <span m=''3699870''>what</span>
  <span m=''3700090''>happens</span> <span m=''3701620''>if</span> <span m=''3701820''>we</span>
  <span m=''3701950''>take</span> <span m=''3702220''>the</span> <span m=''3702340''>ratio</span>
  <span m=''3702780''>of</span> <span m=''3702950''>RISC</span> <span m=''3704130''>to</span>
  <span m=''3704330''>the</span> <span m=''3704460''>Z8002.</span> <span m=''3707420''>Make</span>
  <span m=''3707640''>some</span> <span m=''3707790''>room for</span> <span m=''3708020''>that.</span>
  <span m=''3708355''>So this</span> <span m=''3708690''>is--</span> <span m=''3709870''>this</span>
  <span m=''3710070''>column</span> <span m=''3710400''>is</span> <span m=''3710540''>Z8002</span>
  <span m=''3712410''>over</span> <span m=''3712710''>RISC.</span> </p><p><span m=''3714630''>What</span>
  <span m=''3714760''>if</span> <span m=''3714880''>I</span> <span m=''3714950''>just</span>
  <span m=''3715310''>did</span> <span m=''3715470''>this--</span> <span m=''3715750''>RISC</span>
  <span m=''3717320''>over</span> <span m=''3717640''>the</span> <span m=''3717790''>Z8002</span>
  <span m=''3720730''>I</span> <span m=''3720800''>mean</span> <span m=''3720930''>the</span>
  <span m=''3721030''>answer</span> <span m=''3721290''>should</span> <span m=''3721580''>come</span>
  <span m=''3721750''>out</span> <span m=''3721920''>to</span> <span m=''3722020''>1/1.2,</span>
  <span m=''3723040''>right?</span> <span m=''3724035''>That''s what</span> <span
  m=''3724430''>we</span> <span m=''3724580''>expect,</span> <span m=''3725060''>because
  I''ve</span> <span m=''3725130''>just</span> <span m=''3725420''>been</span> <span
  m=''3725680''>turning</span> <span m=''3725940''>it</span> <span m=''3726000''>upside</span>
  <span m=''3726360''>down.</span> <span m=''3727820''>Well,</span> <span m=''3728980''>I</span>
  <span m=''3729080''>get</span> <span m=''3729250''>1.25</span> <span m=''3730220''>here.</span>
  <span m=''3730490''>These</span> <span m=''3730690''>are</span> <span m=''3730720''>just</span>
  <span m=''3730910''>being</span> <span m=''3731090''>inverted.</span> </p><p><span
  m=''3732100''>Here</span> <span m=''3732400''>I''ve</span> <span m=''3732470''>got</span>
  <span m=''3732650''>2/3,</span> <span m=''3733230''>0.67.</span> <span m=''3734500''>Here</span>
  <span m=''3734780''>I</span> <span m=''3734820''>get</span> <span m=''3734970''>1/2.</span>
  <span m=''3738500''>Here</span> <span m=''3738820''>I</span> <span m=''3738870''>get</span>
  <span m=''3739070''>2.</span> </p><p><span m=''3742400''>Let''s</span> <span m=''3742600''>add</span>
  <span m=''3742790''>those</span> <span m=''3742990''>up.</span> <span m=''3743815''>I</span>
  <span m=''3744300''>get</span> <span m=''3744380''>1.92,</span> <span m=''3746364''>2.42,</span>
  <span m=''3748508''>4.42.</span> <span m=''3752250''>Divide</span> <span m=''3752580''>by</span>
  <span m=''3752700''>4--</span> <span m=''3754170''>wow,</span> <span m=''3754450''>I</span>
  <span m=''3754520''>get</span> <span m=''3754810''>1.1</span> <span m=''3756240''>something</span>
  <span m=''3758020''>which</span> <span m=''3758240''>says,</span> <span m=''3759820''>well,</span>
  <span m=''3760110''>that on</span> <span m=''3760340''>average,</span> <span m=''3760700''>RISC</span>
  <span m=''3761000''>is</span> <span m=''3761100''>10%</span> <span m=''3761680''>longer</span>
  <span m=''3762140''>than</span> <span m=''3762930''>the</span> <span m=''3763050''>other</span>
  <span m=''3763220''>one.</span> </p><p><span m=''3764740''>So</span> <span m=''3764940''>same</span>
  <span m=''3765270''>analysis</span> <span m=''3766080''>says</span> <span m=''3766540''>that</span>
  <span m=''3768280''>RISC</span> <span m=''3768640''>programs</span> <span m=''3770430''>are</span>
  <span m=''3771060''>10%</span> <span m=''3772690''>longer</span> <span m=''3773350''>on</span>
  <span m=''3773560''>average.</span> <span m=''3777430''>Now</span> <span m=''3777450''>the</span>
  <span m=''3777540''>beauty</span> <span m=''3777910''>of</span> <span m=''3777960''>this</span>
  <span m=''3778140''>method</span> <span m=''3779840''>is</span> <span m=''3780010''>you</span>
  <span m=''3780210''>can</span> <span m=''3780350''>make</span> <span m=''3780610''>any
  conclusion</span> <span m=''3781410''>you</span> <span m=''3781520''>want</span>
  <span m=''3781860''>seem</span> <span m=''3782060''>reasonable,</span> <span m=''3783200''>typically.</span>
  <span m=''3785410''>You</span> <span m=''3785540''>could</span> <span m=''3785680''>have</span>
  <span m=''3785830''>the</span> <span m=''3786030''>exact</span> <span m=''3786390''>same</span>
  <span m=''3786700''>data.</span> <span m=''3788590''>And</span> <span m=''3788810''>if</span>
  <span m=''3788900''>you</span> <span m=''3789030''>want</span> <span m=''3790180''>RISC</span>
  <span m=''3790490''>to</span> <span m=''3790580''>look</span> <span m=''3790760''>better</span>
  <span m=''3791030''>you</span> <span m=''3791140''>do</span> <span m=''3791270''>it</span>
  <span m=''3791360''>this</span> <span m=''3791550''>way.</span> <span m=''3793330''>If</span>
  <span m=''3793460''>you</span> <span m=''3793560''>want</span> <span m=''3793740''>RISC
  to</span> <span m=''3794090''>look</span> <span m=''3794250''>worse,</span> <span
  m=''3795060''>you</span> <span m=''3795180''>do</span> <span m=''3795310''>it</span>
  <span m=''3795400''>that</span> <span m=''3795620''>way.</span> </p><p><span m=''3797720''>You</span>
  <span m=''3797810''>see?</span> <span m=''3798540''>Is</span> <span m=''3798790''>that
  possible?</span> <span m=''3799690''>Is it</span> <span m=''3799800''>possible</span>
  <span m=''3800210''>for</span> <span m=''3800300''>one</span> <span m=''3800550''>to</span>
  <span m=''3800610''>be</span> <span m=''3800730''>20%</span> <span m=''3801230''>longer</span>
  <span m=''3801470''>than</span> <span m=''3801590''>the</span> <span m=''3801670''>other</span>
  <span m=''3801810''>on</span> <span m=''3801920''>average,</span> <span m=''3802850''>but</span>
  <span m=''3803040''>the</span> <span m=''3803120''>other</span> <span m=''3803270''>be</span>
  <span m=''3803430''>10%</span> <span m=''3803860''>longer</span> <span m=''3804140''>on</span>
  <span m=''3804260''>average?</span> </p><p><span m=''3807040''>How</span> <span
  m=''3807200''>many</span> <span m=''3807320''>people</span> <span m=''3807550''>think</span>
  <span m=''3807700''>that''s</span> <span m=''3807900''>possible?</span> <span m=''3809000''>We</span>
  <span m=''3809140''>had</span> <span m=''3809300''>some</span> <span m=''3809430''>weird</span>
  <span m=''3809670''>things</span> <span m=''3809890''>happen</span> <span m=''3810190''>in</span>
  <span m=''3810260''>this</span> <span m=''3810410''>class,</span> <span m=''3811440''>but</span>
  <span m=''3811620''>that''s</span> <span m=''3811860''>not</span> <span m=''3812100''>possible.</span>
  <span m=''3813650''>That</span> <span m=''3813850''>can''t</span> <span m=''3814160''>happen.</span>
  <span m=''3814830''>These</span> <span m=''3815110''>conclusions</span> <span m=''3815750''>are</span>
  <span m=''3815820''>both</span> <span m=''3816160''>bogus.</span> </p><p><span m=''3821090''>Now</span>
  <span m=''3821270''>I''m</span> <span m=''3821510''>not</span> <span m=''3821770''>teaching</span>
  <span m=''3822150''>you</span> <span m=''3822270''>this</span> <span m=''3823430''>so</span>
  <span m=''3823570''>that</span> <span m=''3823730''>later</span> <span m=''3824100''>when</span>
  <span m=''3824210''>you''re</span> <span m=''3824300''>doing</span> <span m=''3824550''>your</span>
  <span m=''3824660''>PhD</span> <span m=''3825300''>thesis</span> <span m=''3825700''>and</span>
  <span m=''3825780''>it''s</span> <span m=''3825930''>down</span> <span m=''3826190''>to</span>
  <span m=''3826230''>the</span> <span m=''3826330''>wire and</span> <span m=''3826690''>you
  need a</span> <span m=''3827000''>conclusion to</span> <span m=''3827490''>be</span>
  <span m=''3827590''>proved,</span> <span m=''3828660''>good</span> <span m=''3828830''>news.</span>
  <span m=''3829250''>You</span> <span m=''3829380''>can</span> <span m=''3829530''>prove</span>
  <span m=''3829820''>it.</span> <span m=''3831240''>No</span> <span m=''3831340''>matter</span>
  <span m=''3831560''>what</span> <span m=''3831740''>your</span> <span m=''3831890''>conclusion</span>
  <span m=''3832380''>is,</span> <span m=''3832510''>you</span> <span m=''3832650''>can</span>
  <span m=''3832790''>prove</span> <span m=''3833090''>it.</span> </p><p><span m=''3834380''>That''s</span>
  <span m=''3834510''>not</span> <span m=''3834760''>why</span> <span m=''3834880''>we''re</span>
  <span m=''3835010''>doing</span> <span m=''3835210''>this.</span> <span m=''3835290''>We''re</span>
  <span m=''3835380''>doing</span> <span m=''3835690''>this so</span> <span m=''3835890''>you</span>
  <span m=''3836020''>can</span> <span m=''3836170''>spot</span> <span m=''3836600''>the</span>
  <span m=''3836690''>flaw</span> <span m=''3837510''>in</span> <span m=''3837680''>this</span>
  <span m=''3837830''>whole</span> <span m=''3838090''>setup</span> <span m=''3838990''>and
  that</span> <span m=''3839190''>you''ll</span> <span m=''3839340''>never</span>
  <span m=''3839670''>do</span> <span m=''3839870''>this.</span> <span m=''3840080''>And
  you''ll</span> <span m=''3840260''>see</span> <span m=''3840530''>it</span> <span
  m=''3840620''>when</span> <span m=''3840740''>other</span> <span m=''3840900''>people</span>
  <span m=''3841180''>do</span> <span m=''3841310''>because</span> <span m=''3841480''>people</span>
  <span m=''3841740''>do</span> <span m=''3841940''>it</span> <span m=''3842510''>all</span>
  <span m=''3842730''>the</span> <span m=''3842820''>time.</span> </p><p><span m=''3846160''>So</span>
  <span m=''3846540''>let''s</span> <span m=''3846730''>try</span> <span m=''3846930''>to</span>
  <span m=''3847040''>put</span> <span m=''3847360''>some</span> <span m=''3848400''>formality</span>
  <span m=''3849090''>under</span> <span m=''3849240''>this</span> <span m=''3849460''>in</span>
  <span m=''3849520''>terms</span> <span m=''3849750''>of</span> <span m=''3849820''>probability.</span>
  <span m=''3850460''>Because</span> <span m=''3850590''>when you</span> <span m=''3850720''>start</span>
  <span m=''3850930''>talking</span> <span m=''3851170''>about</span> <span m=''3851370''>averages,</span>
  <span m=''3852740''>really</span> <span m=''3853110''>think</span> <span m=''3853300''>about</span>
  <span m=''3853470''>expectations</span> <span m=''3853810''>of</span> <span m=''3854150''>random</span>
  <span m=''3854520''>variables</span> <span m=''3854890''>and</span> <span m=''3855000''>stuff.</span>
  <span m=''3855190''>So</span> <span m=''3855320''>let''s</span> <span m=''3855990''>try</span>
  <span m=''3856150''>to</span> <span m=''3856250''>view</span> <span m=''3856530''>this</span>
  <span m=''3856830''>as</span> <span m=''3857110''>a</span> <span m=''3857220''>probability</span>
  <span m=''3857810''>problem</span> <span m=''3859970''>and</span> <span m=''3860120''>see</span>
  <span m=''3860360''>if</span> <span m=''3860490''>we</span> <span m=''3860600''>can</span>
  <span m=''3860730''>shed</span> <span m=''3861050''>some</span> <span m=''3861230''>light</span>
  <span m=''3861520''>on</span> <span m=''3861980''>what''s</span> <span m=''3862410''>going</span>
  <span m=''3862900''>on</span> <span m=''3863160''>here</span> <span m=''3864360''>because</span>
  <span m=''3864540''>it</span> <span m=''3864650''>sure</span> <span m=''3864900''>seemed</span>
  <span m=''3865280''>reasonable.</span> </p><p></p><p><span m=''3875850''>So</span>
  <span m=''3877480''>let''s</span> <span m=''3877730''>let</span> <span m=''3878650''>x</span>
  <span m=''3879000''>be</span> <span m=''3879120''>the</span> <span m=''3879220''>benchmark.</span>
  <span m=''3881890''>And</span> <span m=''3881970''>maybe</span> <span m=''3882210''>that''ll</span>
  <span m=''3882460''>be</span> <span m=''3884090''>something</span> <span m=''3884450''>in</span>
  <span m=''3884530''>the</span> <span m=''3884620''>sample</span> <span m=''3885010''>space,</span>
  <span m=''3885400''>an</span> <span m=''3885460''>outcome</span> <span m=''3885610''>in</span>
  <span m=''3885800''>the</span> <span m=''3885880''>sample</span> <span m=''3886250''>space.</span>
  <span m=''3887280''>Let''s</span> <span m=''3887490''>let</span> <span m=''3887660''>R</span>
  <span m=''3887910''>x</span> <span m=''3889360''>be</span> <span m=''3889510''>the</span>
  <span m=''3889630''>code</span> <span m=''3889990''>length</span> <span m=''3894700''>for</span>
  <span m=''3894940''>RISC</span> <span m=''3898610''>on</span> <span m=''3898810''>x</span>
  <span m=''3899630''>and</span> <span m=''3899890''>Z x</span> <span m=''3900490''>be</span>
  <span m=''3900620''>the</span> <span m=''3900740''>code</span> <span m=''3901080''>length</span>
  <span m=''3904150''>for</span> <span m=''3904450''>the</span> <span m=''3904730''>other</span>
  <span m=''3905000''>processor</span> <span m=''3907030''>on</span> <span m=''3907210''>x.</span>
  <span m=''3909340''>And</span> <span m=''3909500''>then</span> <span m=''3913610''>we''ll</span>
  <span m=''3913730''>define</span> <span m=''3914010''>a</span> <span m=''3914070''>probability</span>
  <span m=''3915816''>of</span> <span m=''3916250''>seeing</span> <span m=''3916680''>x.</span>
  </p><p><span m=''3919060''>That''s</span> <span m=''3919320''>our</span> <span m=''3919440''>problem</span>
  <span m=''3919890''>we''re</span> <span m=''3919980''>looking</span> <span m=''3920290''>at.</span>
  <span m=''3921560''>And</span> <span m=''3921930''>typically,</span> <span m=''3922370''>you</span>
  <span m=''3922460''>might</span> <span m=''3922630''>assume</span> <span m=''3922980''>that
  it''s</span> <span m=''3923200''>uniform,</span> <span m=''3928290''>the</span>
  <span m=''3928360''>distribution</span> <span m=''3928990''>there.</span> <span
  m=''3930790''>We</span> <span m=''3930930''>need</span> <span m=''3931140''>this</span>
  <span m=''3931420''>to</span> <span m=''3931510''>be</span> <span m=''3931600''>able</span>
  <span m=''3931740''>to</span> <span m=''3931830''>define</span> <span m=''3932240''>an</span>
  <span m=''3932300''>expected</span> <span m=''3932750''>value</span> <span m=''3933830''>for</span>
  <span m=''3934000''>R</span> <span m=''3934310''>and</span> <span m=''3934380''>for</span>
  <span m=''3934500''>Z.</span> </p><p><span m=''3937350''>Now</span> <span m=''3938450''>what</span>
  <span m=''3938630''>they''re</span> <span m=''3938740''>doing</span> <span m=''3939110''>in</span>
  <span m=''3939180''>the</span> <span m=''3939280''>paper,</span> <span m=''3940940''>what</span>
  <span m=''3941650''>really</span> <span m=''3942060''>is</span> <span m=''3942180''>happening</span>
  <span m=''3942610''>here,</span> <span m=''3943480''>is</span> <span m=''3943630''>instead</span>
  <span m=''3944010''>of</span> <span m=''3944120''>this,</span> <span m=''3946220''>they</span>
  <span m=''3946400''>have</span> <span m=''3946690''>the</span> <span m=''3946800''>expected</span>
  <span m=''3947320''>value</span> <span m=''3947760''>of</span> <span m=''3947850''>Z/R</span>
  <span m=''3950230''>is</span> <span m=''3950480''>1.2.</span> <span m=''3952160''>That</span>
  <span m=''3952480''>is</span> <span m=''3952590''>what</span> <span m=''3952730''>they</span>
  <span m=''3952830''>can</span> <span m=''3953000''>conclude.</span> <span m=''3954880''>That</span>
  <span m=''3955110''>does</span> <span m=''3955300''>not</span> <span m=''3955720''>mean</span>
  <span m=''3959000''>that</span> <span m=''3959220''>the</span> <span m=''3959340''>expected</span>
  <span m=''3959820''>value</span> <span m=''3960140''>of</span> <span m=''3960210''>Z</span>
  <span m=''3961630''>is</span> <span m=''3961830''>1.2,</span> <span m=''3962610''>the</span>
  <span m=''3962760''>expected</span> <span m=''3963220''>value</span> <span m=''3963500''>of</span>
  <span m=''3963610''>R,</span> <span m=''3965260''>which</span> <span m=''3965350''>is</span>
  <span m=''3965420''>what</span> <span m=''3965610''>they</span> <span m=''3965710''>conclude</span>
  <span m=''3967220''>that</span> <span m=''3968690''>the</span> <span m=''3968860''>Z8002</span>
  <span m=''3969690''>code</span> <span m=''3969990''>is</span> <span m=''3970200''>20%</span>
  <span m=''3970750''>longer</span> <span m=''3971040''>than</span> <span m=''3971180''>RISC</span>
  <span m=''3971420''>code.</span> <span m=''3972430''>This</span> <span m=''3973830''>is</span>
  <span m=''3974010''>true.</span> <span m=''3974860''>That</span> <span m=''3975430''>is</span>
  <span m=''3975580''>not</span> <span m=''3975890''>implied.</span> </p><p><span
  m=''3979070''>And</span> <span m=''3979460''>why</span> <span m=''3979670''>not?</span>
  <span m=''3981506''>That''s</span> <span m=''3981890''>just,</span> <span m=''3983320''>actually,</span>
  <span m=''3983680''>what</span> <span m=''3983820''>this</span> <span m=''3983970''>corollary</span>
  <span m=''3984430''>was</span> <span m=''3984610''>doing.</span> <span m=''3987350''>Really,</span>
  <span m=''3987510''>it''s</span> <span m=''3987650''>just</span> <span m=''3987810''>what</span>
  <span m=''3987880''>we</span> <span m=''3988010''>were--</span> <span m=''3988250''>they</span>
  <span m=''3988450''>made</span> <span m=''3988650''>the</span> <span m=''3988730''>same</span>
  <span m=''3989150''>false</span> <span m=''3990110''>assumption</span> <span m=''3990395''>as</span>
  <span m=''3990680''>happened</span> <span m=''3990980''>in</span> <span m=''3991040''>the</span>
  <span m=''3991140''>corollary.</span> </p><p><span m=''3993100''>You</span> <span
  m=''3993250''>can''t</span> <span m=''3993640''>multiply</span> <span m=''3994220''>both</span>
  <span m=''3994490''>sides</span> <span m=''3994900''>here</span> <span m=''3995070''>by</span>
  <span m=''3995220''>the</span> <span m=''3995310''>expected</span> <span m=''3995770''>value</span>
  <span m=''3996080''>of</span> <span m=''3996180''>R</span> <span m=''3997210''>and</span>
  <span m=''3997320''>then</span> <span m=''3997510''>get</span> <span m=''3997680''>the</span>
  <span m=''3997760''>expected</span> <span m=''3998210''>value</span> <span m=''3998570''>Z.</span>
  <span m=''4000110''>Of</span> <span m=''4000240''>course,</span> <span m=''4000490''>if</span>
  <span m=''4000560''>you</span> <span m=''4000660''>ask</span> <span m=''4001030''>them,</span>
  <span m=''4001240''>they</span> <span m=''4001340''>would</span> <span m=''4001360''>have</span>
  <span m=''4001440''>known</span> <span m=''4001750''>that.</span> <span m=''4003070''>But</span>
  <span m=''4003590''>they</span> <span m=''4003750''>don''t</span> <span m=''4003860''>even</span>
  <span m=''4004030''>think</span> <span m=''4004300''>through</span> <span m=''4004440''>that,</span>
  <span m=''4004660''>they</span> <span m=''4004750''>just</span> <span m=''4004990''>used</span>
  <span m=''4005280''>the</span> <span m=''4005370''>standard</span> <span m=''4005750''>method</span>
  <span m=''4006050''>of</span> <span m=''4006130''>taking</span> <span m=''4006370''>the</span>
  <span m=''4006440''>expected</span> <span m=''4006870''>value</span> <span m=''4007130''>of</span>
  <span m=''4007190''>a</span> <span m=''4007270''>ratio.</span> </p><p><span m=''4009290''>So</span>
  <span m=''4009640''>this</span> <span m=''4009920''>is</span> <span m=''4010060''>fair</span>
  <span m=''4010280''>to</span> <span m=''4010350''>conclude.</span> <span m=''4011220''>But</span>
  <span m=''4011340''>as</span> <span m=''4011440''>we</span> <span m=''4011550''>saw,</span>
  <span m=''4012780''>the</span> <span m=''4012840''>expected</span> <span m=''4013310''>value
  of</span> <span m=''4013600''>R/Z</span> <span m=''4014940''>was</span> <span m=''4015100''>1.1.</span>
  <span m=''4018340''>So</span> <span m=''4018490''>both</span> <span m=''4018820''>of</span>
  <span m=''4018900''>these</span> <span m=''4019160''>can</span> <span m=''4019280''>be</span>
  <span m=''4019380''>true</span> <span m=''4019840''>at</span> <span m=''4020210''>the</span>
  <span m=''4020320''>same</span> <span m=''4020600''>time.</span> <span m=''4020950''>That''s</span>
  <span m=''4021240''>fine.</span> <span m=''4021960''>But</span> <span m=''4022100''>you</span>
  <span m=''4022180''>can''t</span> <span m=''4022460''>make</span> <span m=''4022640''>the</span>
  <span m=''4022740''>conclusions</span> <span m=''4023420''>that</span> <span m=''4023550''>they</span>
  <span m=''4023660''>tried</span> <span m=''4023880''>to</span> <span m=''4023940''>make.</span>
  </p><p><span m=''4028000''>Here''s</span> <span m=''4028340''>another--</span> <span
  m=''4030265''>in</span> <span m=''4030740''>fact,</span> <span m=''4030950''>in</span>
  <span m=''4030990''>this</span> <span m=''4031160''>case,</span> <span m=''4031470''>if</span>
  <span m=''4031570''>we</span> <span m=''4031670''>had</span> <span m=''4031760''>a</span>
  <span m=''4031820''>uniform</span> <span m=''4032180''>distribution,</span> <span
  m=''4034100''>the</span> <span m=''4034190''>expected</span> <span m=''4034690''>value</span>
  <span m=''4035130''>of</span> <span m=''4035740''>R</span> <span m=''4036210''>is</span>
  <span m=''4036400''>like</span> <span m=''4037530''>805</span> <span m=''4039040''>for</span>
  <span m=''4039140''>uniform.</span> <span m=''4041396''>And the</span> <span m=''4041820''>expected</span>
  <span m=''4042115''>value</span> <span m=''4042480''>of</span> <span m=''4043836''>Z</span>
  <span m=''4045150''>is</span> <span m=''4045300''>500.</span> <span m=''4048990''>And</span>
  <span m=''4049130''>that''s</span> <span m=''4049370''>all</span> <span m=''4049510''>you</span>
  <span m=''4049630''>can</span> <span m=''4049760''>conclude</span> <span m=''4051082''>if
  you''re taking</span> <span m=''4051490''>uniform</span> <span m=''4051880''>distribution.</span>
  <span m=''4052420''>In</span> <span m=''4053020''>which</span> <span m=''4053250''>case,</span>
  <span m=''4053870''>of</span> <span m=''4053970''>course,</span> <span m=''4054460''>if</span>
  <span m=''4054580''>they''re</span> <span m=''4054690''>promoting</span> <span m=''4055100''>RISC,</span>
  <span m=''4056310''>well,</span> <span m=''4056450''>you don''t</span> <span m=''4056650''>like</span>
  <span m=''4056830''>that</span> <span m=''4057020''>conclusion.</span> </p><p><span
  m=''4059240''>So</span> <span m=''4059410''>it''s</span> <span m=''4059520''>better</span>
  <span m=''4059750''>to</span> <span m=''4059810''>get</span> <span m=''4060930''>this</span>
  <span m=''4061290''>one''s.</span> <span m=''4062140''>I</span> <span m=''4062230''>don''t</span>
  <span m=''4062370''>think it</span> <span m=''4062480''>was</span> <span m=''4062620''>intentional</span>
  <span m=''4062895''>of</span> <span m=''4063170''>course.</span> <span m=''4063530''>But</span>
  <span m=''4065490''>it''s</span> <span m=''4065660''>nice that</span> <span m=''4065930''>it</span>
  <span m=''4066050''>came</span> <span m=''4066240''>out</span> <span m=''4066400''>that</span>
  <span m=''4066560''>way.</span> </p><p><span m=''4069430''>Here''s</span> <span
  m=''4069590''>another</span> <span m=''4069840''>example</span> <span m=''4070240''>that</span>
  <span m=''4070390''>really</span> <span m=''4070840''>makes</span> <span m=''4071090''>it</span>
  <span m=''4071200''>painfully</span> <span m=''4071710''>clear</span> <span m=''4073770''>why</span>
  <span m=''4074060''>you</span> <span m=''4074160''>never</span> <span m=''4074450''>want</span>
  <span m=''4074600''>to</span> <span m=''4074670''>do</span> <span m=''4074830''>this.</span>
  <span m=''4077060''>So</span> <span m=''4077210''>a</span> <span m=''4077330''>really</span>
  <span m=''4077640''>simple</span> <span m=''4078000''>case,</span> <span m=''4079500''>just</span>
  <span m=''4079720''>generic</span> <span m=''4080150''>variables</span> <span m=''4080750''>R</span>
  <span m=''4081080''>and</span> <span m=''4081190''>Z.</span> <span m=''4082150''>And</span>
  <span m=''4082240''>I</span> <span m=''4082290''>got</span> <span m=''4082490''>two</span>
  <span m=''4082630''>problems</span> <span m=''4083170''>only--</span> <span m=''4083940''>problem</span>
  <span m=''4084410''>one,</span> <span m=''4085370''>problem</span> <span m=''4085850''>two.</span>
  </p><p><span m=''4088550''>R</span> <span m=''4088860''>is</span> <span m=''4089000''>2
  for</span> <span m=''4089380''>problem</span> <span m=''4089760''>1,</span> <span
  m=''4090050''>and</span> <span m=''4090210''>z</span> <span m=''4090390''>is</span>
  <span m=''4090530''>1.</span> <span m=''4091020''>And</span> <span m=''4091190''>they</span>
  <span m=''4091290''>reverse</span> <span m=''4091810''>on</span> <span m=''4091930''>problem</span>
  <span m=''4092330''>2.</span> <span m=''4095396''>Z/R</span> <span m=''4097450''>is</span>
  <span m=''4097630''>2</span> <span m=''4098575''>and</span> <span m=''4098890''>1/2.</span>
  <span m=''4101760''>R/Z,</span> <span m=''4103260''>just</span> <span m=''4103520''>the</span>
  <span m=''4103600''>reverse.</span> </p><p><span m=''4108029''>Now</span> <span
  m=''4108689''>the</span> <span m=''4108830''>expected</span> <span m=''4109450''>value
  of</span> <span m=''4109899''>R/Z</span> <span m=''4110899''>here</span> <span m=''4116200''>is</span>
  <span m=''4117040''>2</span> <span m=''4117240''>plus</span> <span m=''4117520''>1/2</span>
  <span m=''4118100''>divided</span> <span m=''4118420''>by</span> <span m=''4118529''>2</span>
  <span m=''4118800''>is</span> <span m=''4118890''>1</span> <span m=''4119149''>and</span>
  <span m=''4119189''>1/4.</span> <span m=''4122810''>And</span> <span m=''4123000''>what''s</span>
  <span m=''4123200''>the</span> <span m=''4123300''>expected</span> <span m=''4123750''>value</span>
  <span m=''4124069''>of</span> <span m=''4124140''>Z/R?</span> <span m=''4129399''>The</span>
  <span m=''4129490''>average</span> <span m=''4129819''>of</span> <span m=''4129880''>these
  is</span> <span m=''4130220''>1</span> <span m=''4130479''>and</span> <span m=''4130529''>1/4,</span>
  <span m=''4130859''>what''s</span> <span m=''4131060''>the</span> <span m=''4131180''>average</span>
  <span m=''4131439''>of</span> <span m=''4131510''>these?</span> <span m=''4133470''>Same</span>
  <span m=''4133840''>thing,</span> <span m=''4134149''>1 and</span> <span m=''4134370''>1/4.</span>
  </p><p><span m=''4138020''>So</span> <span m=''4138170''>never,</span> <span m=''4138620''>ever</span>
  <span m=''4138930''>take</span> <span m=''4139180''>averages of</span> <span m=''4139649''>ratios</span>
  <span m=''4140830''>without</span> <span m=''4141109''>really</span> <span m=''4141490''>knowing</span>
  <span m=''4142140''>what</span> <span m=''4142310''>you''re</span> <span m=''4142430''>doing.</span>
  <span m=''4145560''>Any</span> <span m=''4145729''>questions?</span> <span m=''4147470''>Yeah.</span>
  </p><p><span m=''4149960''>AUDIENCE: What</span> <span m=''4150240''>would</span>
  <span m=''4150359''>be</span> <span m=''4150720''>the</span> <span m=''4150850''>word</span>
  <span m=''4151109''>explanation</span> <span m=''4151720''>of</span> <span m=''4151779''>the</span>
  <span m=''4152180''>expected</span> <span m=''4152640''>value</span> <span m=''4152930''>of</span>
  <span m=''4153020''>Z/R?</span> <span m=''4154240''>What</span> <span m=''4154420''>is</span>
  <span m=''4154560''>that?</span> </p><p><span m=''4155430''>PROFESSOR: That</span>
  <span m=''4155600''>is</span> <span m=''4155840''>the</span> <span m=''4157340''>average</span>
  <span m=''4157750''>of</span> <span m=''4157800''>the</span> <span m=''4157890''>ratio.</span>
  <span m=''4161270''>It</span> <span m=''4161399''>is</span> <span m=''4161600''>not</span>
  <span m=''4163890''>the</span> <span m=''4163990''>ratio</span> <span m=''4164390''>of</span>
  <span m=''4164450''>the</span> <span m=''4164560''>average.</span> <span m=''4165859''>They</span>
  <span m=''4166029''>are</span> <span m=''4166200''>very</span> <span m=''4166529''>different</span>
  <span m=''4166819''>things.</span> </p><p><span m=''4168050''>And</span> <span m=''4168210''>you
  can</span> <span m=''4168370''>see how you</span> <span m=''4168590''>get</span>
  <span m=''4168790''>caught</span> <span m=''4169100''>up</span> <span m=''4169220''>in</span>
  <span m=''4169359''>that.</span> <span m=''4169660''>You could see how you</span>
  <span m=''4169750''>have</span> <span m=''4169890''>linearity</span> <span m=''4170290''>of</span>
  <span m=''4170359''>expectation,</span> <span m=''4171060''>you got</span> <span
  m=''4171210''>the</span> <span m=''4171290''>product</span> <span m=''4171720''>rule</span>
  <span m=''4171870''>for</span> <span m=''4172000''>expectation.</span> <span m=''4173010''>You</span>
  <span m=''4173130''>do</span> <span m=''4173240''>not</span> <span m=''4173569''>have</span>
  <span m=''4173740''>a</span> <span m=''4173859''>rule</span> <span m=''4174210''>that</span>
  <span m=''4174359''>says</span> <span m=''4175819''>this</span> <span m=''4176000''>implies</span>
  <span m=''4177450''>that.</span> </p><p><span m=''4179135''>AUDIENCE: [INAUDIBLE]</span>
  </p><p><span m=''4181870''>PROFESSOR: Which</span> <span m=''4182180''>two?</span>
  </p><p><span m=''4182465''>AUDIENCE: [INAUDIBLE]</span> <span m=''4185020''>Z/R?</span>
  </p><p><span m=''4186710''>PROFESSOR: Well,</span> <span m=''4186910''>in</span>
  <span m=''4187010''>this</span> <span m=''4187250''>case,</span> <span m=''4187680''>they''re</span>
  <span m=''4187850''>one.</span> <span m=''4188910''>I don''t think</span> <span
  m=''4189279''>that''ll</span> <span m=''4189450''>be</span> <span m=''4189510''>true</span>
  <span m=''4189689''>in</span> <span m=''4189779''>general.</span> </p><p><span m=''4190968''>AUDIENCE:
  Does that</span> <span m=''4191372''>give you</span> <span m=''4191830''>information?</span>
  </p><p><span m=''4193990''>PROFESSOR: They</span> <span m=''4194109''>give</span>
  <span m=''4194279''>you</span> <span m=''4194410''>information.</span> <span m=''4195820''>That</span>
  <span m=''4196000''>may</span> <span m=''4196200''>not</span> <span m=''4196420''>be</span>
  <span m=''4196580''>the</span> <span m=''4196780''>information</span> <span m=''4197310''>you</span>
  <span m=''4197440''>want.</span> <span m=''4200020''>It wouldn''t</span> <span m=''4200320''>imply</span>
  <span m=''4200690''>that</span> <span m=''4201030''>which is</span> <span m=''4201370''>what</span>
  <span m=''4201530''>you''re</span> <span m=''4201710''>after in</span> <span m=''4202100''>some</span>
  <span m=''4202390''>sense.</span> <span m=''4204220''>But</span> <span m=''4204360''>it</span>
  <span m=''4204420''>gives</span> <span m=''4204540''>you</span> <span m=''4204640''>some</span>
  <span m=''4204940''>information.</span> <span m=''4206140''>It''s the</span> <span
  m=''4206340''>expected</span> <span m=''4206790''>average</span> <span m=''4207190''>ratio.</span>
  </p><p><span m=''4208170''>The</span> <span m=''4208280''>problem</span> <span m=''4208710''>is</span>
  <span m=''4208820''>the</span> <span m=''4208920''>human</span> <span m=''4209180''>brain</span>
  <span m=''4209610''>goes</span> <span m=''4209830''>right</span> <span m=''4210210''>from</span>
  <span m=''4210370''>there</span> <span m=''4211160''>to</span> <span m=''4211240''>here.</span>
  <span m=''4212700''>It''s</span> <span m=''4212720''>just</span> <span m=''4212910''>you</span>
  <span m=''4212980''>do.</span> <span m=''4214450''>It''s</span> <span m=''4214550''>hard</span>
  <span m=''4214810''>to</span> <span m=''4214890''>help</span> <span m=''4215110''>yourself
  from</span> <span m=''4215590''>doing</span> <span m=''4215900''>it.</span> <span
  m=''4217400''>And</span> <span m=''4217550''>it''s</span> <span m=''4217780''>not</span>
  <span m=''4217970''>true.</span> <span m=''4220510''>That''s</span> <span m=''4220550''>the</span>
  <span m=''4220610''>problem.</span> </p><p><span m=''4223430''>We</span> <span m=''4223550''>have</span>
  <span m=''4223850''>a</span> <span m=''4223900''>version</span> <span m=''4224380''>of</span>
  <span m=''4224450''>this</span> <span m=''4224650''>in</span> <span m=''4224730''>the</span>
  <span m=''4224800''>one in</span> <span m=''4224960''>the</span> <span m=''4225030''>homework</span>
  <span m=''4225350''>questions</span> <span m=''4226170''>which</span> <span m=''4226450''>is</span>
  <span m=''4226630''>true.</span> <span m=''4227420''>But</span> <span m=''4227650''>it''s</span>
  <span m=''4227820''>a</span> <span m=''4228000''>special</span> <span m=''4228400''>version</span>
  <span m=''4228830''>of</span> <span m=''4228940''>it</span> <span m=''4229270''>where</span>
  <span m=''4229490''>you</span> <span m=''4229610''>can</span> <span m=''4229880''>say</span>
  <span m=''4230040''>something</span> <span m=''4230360''>positive.</span> <span
  m=''4233030''>Any</span> <span m=''4233170''>questions</span> <span m=''4233650''>about</span>
  <span m=''4233930''>this?</span> </p><p><span m=''4236020''>So</span> <span m=''4236170''>anybody</span>
  <span m=''4236520''>ever</span> <span m=''4236710''>shows</span> <span m=''4237070''>you</span>
  <span m=''4237960''>an</span> <span m=''4238120''>average</span> <span m=''4238500''>of</span>
  <span m=''4238580''>ratios,</span> <span m=''4239180''>you</span> <span m=''4239280''>want</span>
  <span m=''4239640''>the</span> <span m=''4239800''>light to</span> <span m=''4240020''>go</span>
  <span m=''4240190''>off and</span> <span m=''4240480''>say,</span> <span m=''4240650''>danger,</span>
  <span m=''4241110''>danger.</span> <span m=''4242120''>Think</span> <span m=''4242410''>what''s</span>
  <span m=''4242700''>happening</span> <span m=''4243080''>here.</span> <span m=''4244910''>Or</span>
  <span m=''4245040''>if</span> <span m=''4245100''>you''re</span> <span m=''4245230''>ever</span>
  <span m=''4245390''>analyzing</span> <span m=''4245850''>data</span> <span m=''4246140''>to</span>
  <span m=''4246200''>compare</span> <span m=''4246550''>two</span> <span m=''4246710''>systems.</span>
  </p><p></p><p><span m=''4252880''>So</span> <span m=''4253150''>we</span> <span
  m=''4253260''>talked</span> <span m=''4253460''>a</span> <span m=''4253510''>lot</span>
  <span m=''4253710''>about</span> <span m=''4254000''>expectation,</span> <span m=''4255420''>seen</span>
  <span m=''4255540''>a</span> <span m=''4255610''>lot</span> <span m=''4255880''>of</span>
  <span m=''4255950''>ways</span> <span m=''4256180''>of</span> <span m=''4256240''>computing</span>
  <span m=''4256720''>it.</span> <span m=''4256840''>We''ve</span> <span m=''4256990''>done</span>
  <span m=''4257530''>a</span> <span m=''4257600''>lot</span> <span m=''4257830''>of</span>
  <span m=''4257910''>examples.</span> <span m=''4259310''>For</span> <span m=''4259410''>the</span>
  <span m=''4259500''>rest</span> <span m=''4259750''>of</span> <span m=''4259840''>today</span>
  <span m=''4260230''>and</span> <span m=''4260370''>for</span> <span m=''4260460''>next</span>
  <span m=''4260760''>time,</span> <span m=''4261420''>we''re</span> <span m=''4261680''>going</span>
  <span m=''4261760''>to</span> <span m=''4261800''>talk</span> <span m=''4262080''>about</span>
  <span m=''4262750''>deviations</span> <span m=''4264180''>from</span> <span m=''4264910''>the</span>
  <span m=''4265040''>expected</span> <span m=''4265460''>value.</span> </p><p><span
  m=''4266870''>Now</span> <span m=''4267820''>for</span> <span m=''4267920''>some</span>
  <span m=''4268130''>random</span> <span m=''4268440''>variables,</span> <span m=''4269770''>they</span>
  <span m=''4269830''>are</span> <span m=''4269930''>very</span> <span m=''4270360''>likely</span>
  <span m=''4270870''>to</span> <span m=''4270940''>take</span> <span m=''4271180''>on</span>
  <span m=''4271340''>values that</span> <span m=''4271880''>are</span> <span m=''4271930''>near</span>
  <span m=''4272120''>their</span> <span m=''4272280''>expectation.</span> <span m=''4273850''>For</span>
  <span m=''4273940''>example,</span> <span m=''4275300''>if</span> <span m=''4275460''>I</span>
  <span m=''4275560''>flip</span> <span m=''4276140''>100</span> <span m=''4276530''>coins.</span>
  <span m=''4277510''>And</span> <span m=''4277590''>say</span> <span m=''4277710''>they''re</span>
  <span m=''4277860''>fair</span> <span m=''4278280''>and</span> <span m=''4278350''>mutually</span>
  <span m=''4278650''>independent.</span> <span m=''4280770''>We</span> <span m=''4280940''>know</span>
  <span m=''4281340''>that the</span> <span m=''4281560''>expected</span> <span m=''4282040''>number</span>
  <span m=''4282240''>of</span> <span m=''4282300''>heads</span> <span m=''4282640''>is</span>
  <span m=''4282790''>50.</span> </p><p><span m=''4284450''>Does</span> <span m=''4284590''>anybody</span>
  <span m=''4284920''>remember</span> <span m=''4285150''>the</span> <span m=''4285260''>probability</span>
  <span m=''4285930''>of</span> <span m=''4286100''>getting</span> <span m=''4286760''>far</span>
  <span m=''4287250''>from</span> <span m=''4287420''>that,</span> <span m=''4287810''>namely</span>
  <span m=''4288090''>having</span> <span m=''4288420''>25</span> <span m=''4289020''>or</span>
  <span m=''4289100''>fewer</span> <span m=''4289410''>heads</span> <span m=''4289760''>or</span>
  <span m=''4290300''>75</span> <span m=''4290990''>or</span> <span m=''4291050''>more</span>
  <span m=''4291280''>heads?</span> <span m=''4292890''>Remember,</span> <span m=''4292980''>we</span>
  <span m=''4293090''>did</span> <span m=''4293270''>that?</span> <span m=''4293480''>It
  was</span> <span m=''4293610''>a</span> <span m=''4293710''>couple of</span> <span
  m=''4293920''>weeks</span> <span m=''4294140''>ago?</span> <span m=''4295760''>Is</span>
  <span m=''4295920''>it</span> <span m=''4296000''>likely</span> <span m=''4296550''>to</span>
  <span m=''4296610''>have</span> <span m=''4297010''>25</span> <span m=''4297520''>or</span>
  <span m=''4297590''>fewer</span> <span m=''4297870''>heads?</span> </p><p><span
  m=''4299366''>AUDIENCE: It''s less than</span> <span m=''4299830''>1</span> <span
  m=''4299990''>in a</span> <span m=''4300326''>million?</span> </p><p><span m=''4301000''>PROFESSOR:
  Less</span> <span m=''4301260''>than</span> <span m=''4301380''>1</span> <span m=''4301480''>in</span>
  <span m=''4301640''>a</span> <span m=''4301690''>million.</span> <span m=''4302140''>Yeah.</span>
  <span m=''4302400''>It was 1 in</span> <span m=''4302690''>5</span> <span m=''4303040''>million</span>
  <span m=''4303280''>or</span> <span m=''4303350''>something.</span> <span m=''4303450''>I
  don''t know,</span> <span m=''4303760''>some</span> <span m=''4304280''>horribly</span>
  <span m=''4304610''>small</span> <span m=''4304940''>number.</span> </p><p><span
  m=''4305420''>So</span> <span m=''4305900''>if</span> <span m=''4305980''>I</span>
  <span m=''4306070''>flip</span> <span m=''4306300''>100</span> <span m=''4306560''>coins,</span>
  <span m=''4307640''>I</span> <span m=''4307750''>expect</span> <span m=''4308160''>to</span>
  <span m=''4308220''>get</span> <span m=''4308390''>50</span> <span m=''4308660''>heads.</span>
  <span m=''4309510''>And</span> <span m=''4309620''>I''m</span> <span m=''4309800''>very</span>
  <span m=''4310150''>likely</span> <span m=''4310550''>to</span> <span m=''4310610''>get</span>
  <span m=''4310740''>close</span> <span m=''4310980''>to</span> <span m=''4311080''>50</span>
  <span m=''4311400''>heads.</span> <span m=''4312480''>I''m</span> <span m=''4312650''>not</span>
  <span m=''4312830''>going</span> <span m=''4312930''>to</span> <span m=''4312970''>be</span>
  <span m=''4313080''>25</span> <span m=''4313630''>off.</span> </p><p><span m=''4316080''>And</span>
  <span m=''4316210''>then</span> <span m=''4316320''>the</span> <span m=''4316410''>example</span>
  <span m=''4316820''>we</span> <span m=''4316920''>had</span> <span m=''4317190''>in</span>
  <span m=''4317790''>recitation,</span> <span m=''4319240''>you</span> <span m=''4319350''>got</span>
  <span m=''4319500''>a</span> <span m=''4319540''>noisy</span> <span m=''4319940''>channel,</span>
  <span m=''4321430''>and</span> <span m=''4321670''>you</span> <span m=''4321830''>expect</span>
  <span m=''4322350''>an</span> <span m=''4322450''>error</span> <span m=''4322770''>rate,</span>
  <span m=''4323140''>1%</span> <span m=''4323940''>of</span> <span m=''4324020''>your</span>
  <span m=''4324120''>10,000</span> <span m=''4324690''>bits</span> <span m=''4324890''>to</span>
  <span m=''4324990''>be</span> <span m=''4325100''>corrupted.</span> <span m=''4326640''>The</span>
  <span m=''4326750''>chance</span> <span m=''4327130''>of</span> <span m=''4327220''>getting</span>
  <span m=''4327620''>2%</span> <span m=''4328330''>corrupted</span> <span m=''4328830''>was</span>
  <span m=''4329000''>like--</span> <span m=''4329450''>what was it,</span> <span
  m=''4330100''>2 to</span> <span m=''4330320''>the</span> <span m=''4330390''>minus</span>
  <span m=''4330760''>60</span> <span m=''4331090''>or</span> <span m=''4331170''>something?</span>
  <span m=''4332210''>Extremely</span> <span m=''4332960''>unlikely</span> <span m=''4333440''>to</span>
  <span m=''4333490''>be</span> <span m=''4333630''>far</span> <span m=''4334550''>from</span>
  <span m=''4334700''>the</span> <span m=''4334780''>expected</span> <span m=''4335260''>value.</span>
  </p><p><span m=''4337710''>But</span> <span m=''4337980''>there''s</span> <span
  m=''4338130''>other</span> <span m=''4338340''>cases</span> <span m=''4338760''>where</span>
  <span m=''4340190''>you</span> <span m=''4340380''>are</span> <span m=''4340600''>likely--</span>
  <span m=''4341120''>you</span> <span m=''4341420''>could</span> <span m=''4341620''>well</span>
  <span m=''4341900''>be</span> <span m=''4342490''>far</span> <span m=''4342770''>from</span>
  <span m=''4342870''>the</span> <span m=''4342960''>expected</span> <span m=''4343370''>value.</span>
  <span m=''4344430''>Can</span> <span m=''4344560''>anybody</span> <span m=''4344870''>remember
  an</span> <span m=''4345140''>example</span> <span m=''4345560''>we''ve</span> <span
  m=''4345730''>done</span> <span m=''4346090''>where</span> <span m=''4348470''>you</span>
  <span m=''4348860''>are</span> <span m=''4349470''>almost</span> <span m=''4349830''>surely</span>
  <span m=''4351120''>way</span> <span m=''4351700''>off</span> <span m=''4351930''>your</span>
  <span m=''4352070''>expected</span> <span m=''4352510''>value</span> <span m=''4353480''>for
  a</span> <span m=''4353630''>random</span> <span m=''4353890''>variable?</span>
  <span m=''4355700''>Anybody</span> <span m=''4355840''>remember an</span> <span
  m=''4356240''>example</span> <span m=''4356650''>we</span> <span m=''4356760''>did</span>
  <span m=''4356970''>that</span> <span m=''4357030''>has</span> <span m=''4357260''>that</span>
  <span m=''4357810''>feature?</span> </p><p><span m=''4359730''>AUDIENCE: The appetizer</span>
  <span m=''4360180''>I think.</span> </p><p><span m=''4361310''>PROFESSOR: The</span>
  <span m=''4361470''>appetizer.</span> <span m=''4362280''>Let''s</span> <span m=''4362510''>see.</span>
  <span m=''4363460''>Appetizers,</span> <span m=''4364220''>you</span> <span m=''4364330''>expect</span>
  <span m=''4364940''>1,</span> <span m=''4366320''>but</span> <span m=''4366640''>you''re</span>
  <span m=''4366790''>almost</span> <span m=''4367110''>certain</span> <span m=''4367365''>to
  be</span> <span m=''4367620''>0.</span> </p><p><span m=''4369350''>Or</span> <span
  m=''4369650''>actually,</span> <span m=''4370120''>you''re</span> <span m=''4370290''>almost</span>
  <span m=''4370590''>certain</span> <span m=''4370730''>to</span> <span m=''4370770''>be</span>
  <span m=''4370850''>0,</span> <span m=''4371290''>and</span> <span m=''4371470''>you</span>
  <span m=''4371520''>have</span> <span m=''4371600''>a</span> <span m=''4371650''>chance</span>
  <span m=''4371900''>of</span> <span m=''4371960''>being</span> <span m=''4372190''>n.</span>
  <span m=''4373560''>So if you</span> <span m=''4373850''>count</span> <span m=''4374180''>0</span>
  <span m=''4374460''>as</span> <span m=''4374560''>being</span> <span m=''4374710''>close</span>
  <span m=''4374990''>to</span> <span m=''4375100''>1,</span> <span m=''4375450''>you''re</span>
  <span m=''4375590''>likely</span> <span m=''4375890''>to</span> <span m=''4375950''>be</span>
  <span m=''4376040''>close to</span> <span m=''4376330''>your</span> <span m=''4376460''>expectation.</span>
  <span m=''4377120''>Because</span> <span m=''4377280''>you''re</span> <span m=''4377390''>likely</span>
  <span m=''4377720''>to</span> <span m=''4377780''>be</span> <span m=''4377880''>0,</span>
  <span m=''4378670''>and</span> <span m=''4378780''>you</span> <span m=''4378880''>expect</span>
  <span m=''4379260''>1.</span> </p><p><span m=''4381690''>Remember</span> <span m=''4382000''>that</span>
  <span m=''4382300''>noisy</span> <span m=''4382640''>channel</span> <span m=''4383000''>problem--</span>
  <span m=''4385060''>not the</span> <span m=''4385250''>noisy</span> <span m=''4385560''>channel,</span>
  <span m=''4385690''>the</span> <span m=''4385800''>latency</span> <span m=''4386340''>problem</span>
  <span m=''4386600''>across</span> <span m=''4386910''>the</span> <span m=''4387000''>channel?</span>
  <span m=''4388330''>And</span> <span m=''4388650''>we</span> <span m=''4388740''>show
  that</span> <span m=''4388970''>the</span> <span m=''4389210''>expected</span> <span
  m=''4389910''>latency</span> <span m=''4390440''>was</span> <span m=''4390600''>infinite?</span>
  <span m=''4392310''>But</span> <span m=''4392750''>99%</span> <span m=''4393510''>of</span>
  <span m=''4393550''>the</span> <span m=''4393650''>time</span> <span m=''4393930''>you</span>
  <span m=''4394010''>had</span> <span m=''4394180''>10</span> <span m=''4394370''>milliseconds,</span>
  <span m=''4395580''>something</span> <span m=''4395860''>like</span> <span m=''4396050''>that?</span>
  <span m=''4397770''>There''s</span> <span m=''4398080''>an</span> <span m=''4398150''>example</span>
  <span m=''4398660''>where</span> <span m=''4398830''>almost</span> <span m=''4399140''>all</span>
  <span m=''4399300''>the</span> <span m=''4399400''>time</span> <span m=''4399880''>you</span>
  <span m=''4400020''>are</span> <span m=''4400130''>far</span> <span m=''4400480''>from
  your</span> <span m=''4400690''>expectation</span> <span m=''4401390''>which</span>
  <span m=''4401570''>is</span> <span m=''4401680''>infinite.</span> <span m=''4402870''>So</span>
  <span m=''4403120''>there</span> <span m=''4403230''>are</span> <span m=''4403390''>examples</span>
  <span m=''4403660''>that</span> <span m=''4403930''>go</span> <span m=''4404190''>both</span>
  <span m=''4404910''>ways.</span> </p><p><span m=''4408250''>Now</span> <span m=''4410730''>let''s</span>
  <span m=''4411000''>look</span> <span m=''4411190''>at</span> <span m=''4412380''>another</span>
  <span m=''4412640''>couple</span> <span m=''4412910''>of</span> <span m=''4412990''>examples</span>
  <span m=''4413570''>that''ll</span> <span m=''4413740''>motivate</span> <span m=''4414900''>the</span>
  <span m=''4414970''>definition</span> <span m=''4415590''>that</span> <span m=''4415710''>measures</span>
  <span m=''4416205''>this.</span> <span m=''4421160''>I''d</span> <span m=''4421440''>say</span>
  <span m=''4421700''>that</span> <span m=''4421830''>we''ve</span> <span m=''4422010''>got</span>
  <span m=''4422440''>a</span> <span m=''4422500''>simple</span> <span m=''4422790''>Bernoulli</span>
  <span m=''4423870''>random</span> <span m=''4424160''>variable</span> <span m=''4425640''>where</span>
  <span m=''4425930''>the</span> <span m=''4426050''>probability</span> <span m=''4426710''>that</span>
  <span m=''4426890''>R</span> <span m=''4427420''>is</span> <span m=''4427680''>1,000</span>
  <span m=''4429930''>is</span> <span m=''4430090''>1/2,</span> <span m=''4431250''>and</span>
  <span m=''4431550''>the</span> <span m=''4431630''>probability</span> <span m=''4432270''>that</span>
  <span m=''4432690''>R</span> <span m=''4433800''>is</span> <span m=''4433990''>minus</span>
  <span m=''4434560''>1,000</span> <span m=''4436480''>is</span> <span m=''4436670''>1/2.</span>
  <span m=''4438660''>Then</span> <span m=''4438890''>the</span> <span m=''4439000''>expected</span>
  <span m=''4439530''>value</span> <span m=''4439860''>of</span> <span m=''4439960''>R
  is</span> <span m=''4440210''>0.</span> </p><p></p><p><span m=''4445440''>Similarly,</span>
  <span m=''4446010''>we</span> <span m=''4446130''>could</span> <span m=''4446260''>have</span>
  <span m=''4446450''>another</span> <span m=''4446780''>one,</span> <span m=''4447275''>S,</span>
  <span m=''4447770''>where</span> <span m=''4447890''>the</span> <span m=''4447990''>probability</span>
  <span m=''4448510''>that</span> <span m=''4448680''>S</span> <span m=''4449050''>equals</span>
  <span m=''4449430''>1</span> <span m=''4451000''>is</span> <span m=''4451220''>1/2,</span>
  <span m=''4452540''>and</span> <span m=''4452670''>the</span> <span m=''4452760''>probability</span>
  <span m=''4453230''>that</span> <span m=''4453370''>S</span> <span m=''4453740''>equals</span>
  <span m=''4454040''>minus</span> <span m=''4454500''>1</span> <span m=''4454710''>is</span>
  <span m=''4454830''>1/2.</span> <span m=''4456230''>And</span> <span m=''4456490''>the</span>
  <span m=''4456590''>expected</span> <span m=''4457090''>value</span> <span m=''4457380''>of</span>
  <span m=''4457440''>S</span> <span m=''4457680''>is</span> <span m=''4457820''>0.</span>
  <span m=''4460820''>Now</span> <span m=''4461090''>if</span> <span m=''4461170''>this</span>
  <span m=''4461360''>was</span> <span m=''4461520''>a</span> <span m=''4461590''>betting</span>
  <span m=''4462060''>game</span> <span m=''4462960''>and</span> <span m=''4463150''>we''re</span>
  <span m=''4463240''>talking</span> <span m=''4463580''>about</span> <span m=''4464110''>dollars--</span>
  <span m=''4465910''>here''s</span> <span m=''4466240''>where</span> <span m=''4466370''>you''re</span>
  <span m=''4466470''>wagering</span> <span m=''4466960''>$1,000,</span> <span m=''4468320''>fair</span>
  <span m=''4468590''>game.</span> <span m=''4468910''>Here''s</span> <span m=''4469200''>where
  you''re</span> <span m=''4469380''>wagering</span> <span m=''4469830''>$1.</span>
  </p><p><span m=''4471550''>Now</span> <span m=''4473930''>in</span> <span m=''4474120''>this</span>
  <span m=''4474780''>game--</span> <span m=''4475850''>both games</span> <span m=''4476210''>are</span>
  <span m=''4476450''>fair.</span> <span m=''4476950''>Expected</span> <span m=''4477380''>value</span>
  <span m=''4477760''>is</span> <span m=''4477800''>0.</span> <span m=''4478980''>But</span>
  <span m=''4479100''>here</span> <span m=''4479370''>you''re</span> <span m=''4479530''>likely</span>
  <span m=''4480070''>to</span> <span m=''4480130''>end</span> <span m=''4480470''>up</span>
  <span m=''4480780''>near</span> <span m=''4480960''>your</span> <span m=''4481120''>expected</span>
  <span m=''4481550''>value.</span> <span m=''4483070''>Here</span> <span m=''4483370''>you''re</span>
  <span m=''4483530''>certain</span> <span m=''4483900''>to</span> <span m=''4483950''>be</span>
  <span m=''4484070''>far</span> <span m=''4484860''>by</span> <span m=''4484990''>some</span>
  <span m=''4485200''>measure</span> <span m=''4485500''>from your</span> <span m=''4485730''>expected</span>
  <span m=''4486130''>value.</span> </p><p><span m=''4487290''>And</span> <span m=''4487430''>in</span>
  <span m=''4487520''>fact,</span> <span m=''4488910''>if</span> <span m=''4489010''>you</span>
  <span m=''4489030''>were</span> <span m=''4489110''>offered</span> <span m=''4489830''>to</span>
  <span m=''4489990''>play</span> <span m=''4490300''>a</span> <span m=''4490340''>game,</span>
  <span m=''4492740''>you</span> <span m=''4492850''>might</span> <span m=''4493010''>have</span>
  <span m=''4493140''>a</span> <span m=''4493210''>real</span> <span m=''4493380''>decision</span>
  <span m=''4493830''>as</span> <span m=''4493920''>to</span> <span m=''4494020''>which</span>
  <span m=''4494220''>game</span> <span m=''4494420''>you</span> <span m=''4494530''>played.</span>
  <span m=''4496270''>If</span> <span m=''4496440''>you</span> <span m=''4496860''>like</span>
  <span m=''4497240''>risk,</span> <span m=''4498980''>you</span> <span m=''4499010''>might</span>
  <span m=''4499220''>play</span> <span m=''4499380''>that</span> <span m=''4499610''>game.</span>
  <span m=''4500990''>If</span> <span m=''4501140''>you''re</span> <span m=''4501340''>risk</span>
  <span m=''4501690''>averse,</span> <span m=''4502840''>maybe you</span> <span m=''4503160''>stick</span>
  <span m=''4503400''>with</span> <span m=''4503500''>this</span> <span m=''4503720''>game</span>
  <span m=''4505000''>because</span> <span m=''4505505''>what</span> <span m=''4505930''>you</span>
  <span m=''4506050''>could</span> <span m=''4506180''>lose</span> <span m=''4506490''>would</span>
  <span m=''4506580''>be</span> <span m=''4506710''>less.</span> </p><p><span m=''4510460''>Now</span>
  <span m=''4510590''>this</span> <span m=''4510790''>motivates</span> <span m=''4512080''>the</span>
  <span m=''4512200''>definition</span> <span m=''4513780''>of</span> <span m=''4514390''>the</span>
  <span m=''4514540''>variance</span> <span m=''4516770''>because</span> <span m=''4516940''>it</span>
  <span m=''4517110''>helps</span> <span m=''4518170''>mathematicians</span> <span
  m=''4519000''>distinguish</span> <span m=''4519630''>between</span> <span m=''4520030''>these</span>
  <span m=''4520290''>two</span> <span m=''4520700''>cases</span> <span m=''4521430''>with
  a simple</span> <span m=''4521914''>statistic.</span> </p><p></p><p><span m=''4533530''>The</span>
  <span m=''4533640''>variance</span> <span m=''4538258''>of a</span> <span m=''4538720''>random</span>
  <span m=''4539240''>variable</span> <span m=''4542270''>R--</span> <span m=''4544670''>we''ll</span>
  <span m=''4544840''>denote</span> <span m=''4545140''>it</span> <span m=''4545250''>by</span>
  <span m=''4546340''>var,</span> <span m=''4546870''>V-A-R,</span> <span m=''4547700''>of</span>
  <span m=''4548115''>R--</span> <span m=''4549170''>is</span> <span m=''4549380''>defined</span>
  <span m=''4549910''>as</span> <span m=''4550040''>the</span> <span m=''4550180''>expected</span>
  <span m=''4550870''>value</span> <span m=''4552205''>of</span> <span m=''4552670''>the</span>
  <span m=''4552870''>random</span> <span m=''4553260''>variable</span> <span m=''4554210''>minus</span>
  <span m=''4554790''>this</span> <span m=''4554950''>expected</span> <span m=''4555460''>value</span>
  <span m=''4558580''>squared.</span> <span m=''4561250''>That''s</span> <span m=''4561380''>sort</span>
  <span m=''4561600''>of</span> <span m=''4561920''>a</span> <span m=''4562000''>mouthful</span>
  <span m=''4562560''>there.</span> <span m=''4562950''>So</span> <span m=''4563090''>let''s</span>
  <span m=''4563270''>break</span> <span m=''4563710''>it</span> <span m=''4563810''>down.</span>
  </p><p><span m=''4567285''>This</span> <span m=''4567730''>is</span> <span m=''4567830''>the</span>
  <span m=''4567910''>expected</span> <span m=''4568330''>value</span> <span m=''4568590''>of</span>
  <span m=''4568710''>R.</span> <span m=''4569520''>This</span> <span m=''4569900''>is</span>
  <span m=''4570020''>the</span> <span m=''4570160''>deviation</span> <span m=''4571240''>from</span>
  <span m=''4571450''>the</span> <span m=''4572030''>expected</span> <span m=''4572460''>value.</span>
  <span m=''4574130''>So</span> <span m=''4574290''>this</span> <span m=''4574520''>is</span>
  <span m=''4574630''>the</span> <span m=''4574740''>deviation</span> <span m=''4576010''>from</span>
  <span m=''4576180''>the</span> <span m=''4576270''>mean.</span> <span m=''4581490''>Then</span>
  <span m=''4581660''>we</span> <span m=''4581790''>square</span> <span m=''4582400''>it.</span>
  </p><p><span m=''4585590''>So</span> <span m=''4585710''>that</span> <span m=''4585940''>equals</span>
  <span m=''4586300''>the</span> <span m=''4586410''>square</span> <span m=''4589170''>of</span>
  <span m=''4589300''>the</span> <span m=''4589390''>deviation.</span> <span m=''4591800''>And</span>
  <span m=''4592030''>then</span> <span m=''4593040''>we</span> <span m=''4593180''>take</span>
  <span m=''4593590''>the</span> <span m=''4593710''>expected</span> <span m=''4594270''>value</span>
  <span m=''4595060''>of</span> <span m=''4595200''>the</span> <span m=''4595300''>square.</span>
  <span m=''4596810''>So</span> <span m=''4596990''>the</span> <span m=''4597470''>variance</span>
  <span m=''4599100''>equals</span> <span m=''4599610''>the</span> <span m=''4600260''>expected</span>
  <span m=''4600920''>value</span> <span m=''4602190''>of</span> <span m=''4602390''>the</span>
  <span m=''4602470''>square</span> <span m=''4605196''>of</span> <span m=''4605640''>the</span>
  <span m=''4605820''>deviation.</span> <span m=''4611010''>In</span> <span m=''4611100''>other</span>
  <span m=''4611260''>words,</span> <span m=''4611460''>the</span> <span m=''4611510''>variance</span>
  <span m=''4612050''>gives</span> <span m=''4612230''>us</span> <span m=''4612370''>the</span>
  <span m=''4612540''>average</span> <span m=''4613010''>of</span> <span m=''4613100''>the</span>
  <span m=''4613200''>squares</span> <span m=''4615260''>of</span> <span m=''4615310''>the</span>
  <span m=''4615400''>amount</span> <span m=''4615630''>by</span> <span m=''4615700''>which</span>
  <span m=''4615960''>the</span> <span m=''4616980''>random</span> <span m=''4617280''>variable</span>
  <span m=''4617640''>deviates</span> <span m=''4618260''>from its</span> <span m=''4618560''>mean.</span>
  </p><p><span m=''4619662''>Now</span> <span m=''4620100''>the</span> <span m=''4620210''>idea</span>
  <span m=''4620610''>behind</span> <span m=''4621040''>this</span> <span m=''4621330''>is</span>
  <span m=''4621470''>that</span> <span m=''4623410''>if</span> <span m=''4623590''>a</span>
  <span m=''4623680''>random</span> <span m=''4624020''>variable</span> <span m=''4624400''>is</span>
  <span m=''4624500''>likely</span> <span m=''4625040''>to</span> <span m=''4625130''>deviate</span>
  <span m=''4626160''>from</span> <span m=''4626340''>its</span> <span m=''4626480''>mean,</span>
  <span m=''4626960''>the</span> <span m=''4627040''>variance will</span> <span m=''4627490''>be</span>
  <span m=''4627580''>high.</span> <span m=''4628710''>And</span> <span m=''4628980''>if</span>
  <span m=''4629070''>it''s</span> <span m=''4629230''>likely</span> <span m=''4629570''>to</span>
  <span m=''4629630''>be</span> <span m=''4629740''>near</span> <span m=''4630090''>its</span>
  <span m=''4630240''>mean,</span> <span m=''4630580''>the</span> <span m=''4630670''>variance
  will</span> <span m=''4631170''>be</span> <span m=''4631290''>low.</span> <span
  m=''4632180''>And</span> <span m=''4632360''>so</span> <span m=''4632460''>variance</span>
  <span m=''4632930''>can</span> <span m=''4633100''>tell</span> <span m=''4633440''>us</span>
  <span m=''4634070''>something</span> <span m=''4634550''>about</span> <span m=''4635210''>the</span>
  <span m=''4635340''>expected</span> <span m=''4635830''>deviation.</span> </p><p></p><p><span
  m=''4643920''>So</span> <span m=''4643960''>let''s</span> <span m=''4644170''>compute</span>
  <span m=''4644530''>the</span> <span m=''4644620''>variance</span> <span m=''4646130''>for</span>
  <span m=''4646270''>R and</span> <span m=''4646560''>S</span> <span m=''4646835''>and</span>
  <span m=''4647110''>see</span> <span m=''4647250''>what</span> <span m=''4647570''>happens.</span>
  <span m=''4649220''>So</span> <span m=''4649310''>with</span> <span m=''4649840''>R</span>
  <span m=''4650190''>minus</span> <span m=''4650700''>the</span> <span m=''4650790''>expected</span>
  <span m=''4651300''>value</span> <span m=''4651690''>of</span> <span m=''4651810''>R,</span>
  <span m=''4654290''>well,</span> <span m=''4655010''>that</span> <span m=''4655330''>is</span>
  <span m=''4655450''>going</span> <span m=''4655560''>to</span> <span m=''4655620''>be</span>
  <span m=''4655770''>1,000,</span> <span m=''4657210''>because</span> <span m=''4657370''>you</span>
  <span m=''4657450''>expect</span> <span m=''4657670''>the</span> <span m=''4657750''>value</span>
  <span m=''4658020''>of</span> <span m=''4658060''>0,</span> <span m=''4658960''>with</span>
  <span m=''4659180''>probability</span> <span m=''4659700''>1/2,</span> <span m=''4660110''>and</span>
  <span m=''4660230''>minus</span> <span m=''4660680''>1,000</span> <span m=''4662420''>with</span>
  <span m=''4662560''>probability</span> <span m=''4663070''>1/2.</span> <span m=''4664770''>Then</span>
  <span m=''4664930''>I</span> <span m=''4665010''>square</span> <span m=''4665530''>that.</span>
  </p><p></p><p><span m=''4671220''>Well,</span> <span m=''4671510''>I</span> <span
  m=''4671620''>square</span> <span m=''4672090''>1,000,</span> <span m=''4673240''>I</span>
  <span m=''4673340''>get</span> <span m=''4673510''>a</span> <span m=''4673570''>million</span>
  <span m=''4676450''>with</span> <span m=''4676590''>probability</span> <span m=''4677130''>1/2.</span>
  <span m=''4678430''>And</span> <span m=''4678780''>I</span> <span m=''4678840''>square</span>
  <span m=''4679300''>minus</span> <span m=''4679565''>1,000,</span> <span m=''4680140''>I</span>
  <span m=''4680210''>get</span> <span m=''4680350''>a</span> <span m=''4680400''>million</span>
  <span m=''4680700''>again</span> <span m=''4682230''>with</span> <span m=''4682360''>probability</span>
  <span m=''4683000''>1/2.</span> <span m=''4685340''>And</span> <span m=''4685550''>so</span>
  <span m=''4685720''>therefore,</span> <span m=''4686280''>the</span> <span m=''4686390''>variance</span>
  <span m=''4687020''>of</span> <span m=''4687130''>R,</span> <span m=''4689620''>well,</span>
  <span m=''4689870''>it''s</span> <span m=''4690000''>the</span> <span m=''4690080''>expected</span>
  <span m=''4690640''>value</span> <span m=''4691080''>of</span> <span m=''4691160''>this,</span>
  <span m=''4691720''>which</span> <span m=''4691980''>is--</span> <span m=''4692470''>well,</span>
  <span m=''4692700''>it''s</span> <span m=''4692800''>always</span> <span m=''4693120''>a</span>
  <span m=''4693170''>million.</span> <span m=''4693580''>So</span> <span m=''4693790''>it''s</span>
  <span m=''4693910''>just</span> <span m=''4694140''>a</span> <span m=''4694190''>million.</span>
  <span m=''4698650''>Big.</span> </p><p><span m=''4700160''>Now</span> <span m=''4700310''>if</span>
  <span m=''4700400''>I</span> <span m=''4700450''>were</span> <span m=''4700580''>to</span>
  <span m=''4700660''>do</span> <span m=''4700800''>this</span> <span m=''4700990''>with</span>
  <span m=''4701130''>S,</span> <span m=''4703026''>S</span> <span m=''4703500''>minus</span>
  <span m=''4703830''>the</span> <span m=''4703910''>expected</span> <span m=''4704360''>value</span>
  <span m=''4704710''>of</span> <span m=''4704790''>S</span> <span m=''4706140''>is</span>
  <span m=''4706630''>1</span> <span m=''4707250''>with</span> <span m=''4707390''>probability</span>
  <span m=''4707840''>1/2,</span> <span m=''4708690''>minus</span> <span m=''4709090''>1</span>
  <span m=''4709300''>with</span> <span m=''4709430''>probability</span> <span m=''4709840''>1/2.</span>
  <span m=''4711170''>If</span> <span m=''4711310''>I</span> <span m=''4711390''>square</span>
  <span m=''4711860''>that,</span> <span m=''4716911''>well,</span> <span m=''4717410''>I</span>
  <span m=''4717550''>get</span> <span m=''4717970''>1</span> <span m=''4718170''>squared</span>
  <span m=''4718480''>is</span> <span m=''4718600''>1,</span> <span m=''4719290''>minus</span>
  <span m=''4719650''>1</span> <span m=''4719800''>squared</span> <span m=''4720070''>is</span>
  <span m=''4720180''>1.</span> <span m=''4722670''>And</span> <span m=''4722850''>so</span>
  <span m=''4722970''>the</span> <span m=''4723070''>variance</span> <span m=''4723600''>of</span>
  <span m=''4723710''>S</span> <span m=''4725720''>is</span> <span m=''4725920''>the</span>
  <span m=''4726020''>expected</span> <span m=''4726540''>value</span> <span m=''4726860''>of</span>
  <span m=''4726940''>this.</span> <span m=''4727280''>And that''s</span> <span m=''4727580''>just</span>
  <span m=''4727830''>1.</span> <span m=''4730010''>So</span> <span m=''4730140''>a</span>
  <span m=''4730190''>big</span> <span m=''4730630''>difference</span> <span m=''4731120''>in</span>
  <span m=''4731180''>the</span> <span m=''4731260''>variance.</span> </p><p><span
  m=''4732590''>So</span> <span m=''4732630''>the</span> <span m=''4732710''>variance</span>
  <span m=''4733230''>being</span> <span m=''4733460''>different</span> <span m=''4733890''>tells</span>
  <span m=''4734300''>us</span> <span m=''4734450''>these</span> <span m=''4734630''>random</span>
  <span m=''4734970''>variables</span> <span m=''4735520''>are--</span> <span m=''4736220''>the</span>
  <span m=''4736330''>distributions</span> <span m=''4736940''>are</span> <span m=''4737010''>very</span>
  <span m=''4737390''>different</span> <span m=''4737790''>even</span> <span m=''4738110''>though</span>
  <span m=''4738260''>their</span> <span m=''4738410''>expected</span> <span m=''4738880''>values</span>
  <span m=''4739310''>are</span> <span m=''4739390''>the</span> <span m=''4739480''>same.</span>
  <span m=''4741220''>And</span> <span m=''4741380''>the</span> <span m=''4741460''>guy</span>
  <span m=''4741620''>with</span> <span m=''4741760''>big</span> <span m=''4741970''>variance</span>
  <span m=''4742440''>says,</span> <span m=''4742870''>hey,</span> <span m=''4743000''>we''re</span>
  <span m=''4743160''>likely</span> <span m=''4743530''>to</span> <span m=''4743620''>deviate</span>
  <span m=''4744160''>from</span> <span m=''4744270''>the</span> <span m=''4744340''>mean</span>
  <span m=''4745320''>here.</span> <span m=''4746920''>And</span> <span m=''4747110''>so</span>
  <span m=''4747340''>risk</span> <span m=''4747640''>averse</span> <span m=''4747950''>people</span>
  <span m=''4748330''>stay</span> <span m=''4748620''>away</span> <span m=''4748980''>from</span>
  <span m=''4749190''>strategies</span> <span m=''4749930''>when</span> <span m=''4750050''>they''re</span>
  <span m=''4750380''>investing</span> <span m=''4750980''>that have</span> <span
  m=''4751200''>high variance.</span> </p><p></p><p><span m=''4758370''>Now</span>
  <span m=''4760560''>does</span> <span m=''4760710''>anybody</span> <span m=''4761030''>have</span>
  <span m=''4761200''>any</span> <span m=''4761320''>idea</span> <span m=''4761720''>why</span>
  <span m=''4762200''>we</span> <span m=''4762800''>square</span> <span m=''4764000''>the</span>
  <span m=''4764110''>deviation?</span> <span m=''4764710''>Why</span> <span m=''4764890''>don''t</span>
  <span m=''4765020''>we</span> <span m=''4765130''>just--</span> <span m=''4765650''>why
  didn''t</span> <span m=''4766090''>mathematicians</span> <span m=''4766850''>when
  they</span> <span m=''4767060''>figured</span> <span m=''4767350''>out</span> <span
  m=''4767530''>this</span> <span m=''4767640''>stuff</span> <span m=''4768610''>I</span>
  <span m=''4768730''>don''t</span> <span m=''4768810''>know</span> <span m=''4768890''>how</span>
  <span m=''4769000''>many</span> <span m=''4769140''>centuries</span> <span m=''4769610''>ago,</span>
  <span m=''4769830''>why</span> <span m=''4770010''>didn''t</span> <span m=''4770150''>they</span>
  <span m=''4770240''>just</span> <span m=''4770430''>take</span> <span m=''4770610''>the</span>
  <span m=''4770740''>expected</span> <span m=''4771420''>deviation?</span> <span
  m=''4772930''>Why</span> <span m=''4773170''>do</span> <span m=''4773300''>the</span>
  <span m=''4773440''>stupid</span> <span m=''4773840''>squaring</span> <span m=''4774300''>thing?</span>
  <span m=''4774510''>That</span> <span m=''4774670''>only</span> <span m=''4774990''>is
  going</span> <span m=''4775100''>to</span> <span m=''4775190''>complicate</span>
  <span m=''4775510''>it?</span> </p><p><span m=''4777110''>Why</span> <span m=''4777630''>don''t</span>
  <span m=''4777990''>we</span> <span m=''4779060''>instead</span> <span m=''4781360''>compute</span>
  <span m=''4782980''>the</span> <span m=''4783130''>expected</span> <span m=''4783690''>value</span>
  <span m=''4784250''>of</span> <span m=''4784440''>R</span> <span m=''4785240''>minus</span>
  <span m=''4786370''>the</span> <span m=''4786460''>mean?</span> <span m=''4788730''>Why</span>
  <span m=''4788830''>didn''t</span> <span m=''4789070''>they</span> <span m=''4789180''>do</span>
  <span m=''4789370''>that</span> <span m=''4789680''>and</span> <span m=''4789720''>call</span>
  <span m=''4790040''>that</span> <span m=''4790250''>the</span> <span m=''4790330''>variance?</span>
  <span m=''4791620''>Yeah?</span> </p><p><span m=''4793170''>That''s</span> <span
  m=''4793390''>zero.</span> <span m=''4794252''>Yeah.</span> <span m=''4795490''>Because</span>
  <span m=''4795790''>by</span> <span m=''4795910''>linearity</span> <span m=''4796350''>of</span>
  <span m=''4796430''>expectation,</span> <span m=''4797210''>that</span> <span m=''4797670''>corollary</span>
  <span m=''4798260''>[? 4-2 ?]</span> <span m=''4798690''>or</span> <span m=''4798760''>whatever,</span>
  <span m=''4799670''>this</span> <span m=''4799860''>is</span> <span m=''4799990''>just</span>
  <span m=''4800240''>the</span> <span m=''4800310''>expected</span> <span m=''4800810''>value</span>
  <span m=''4801110''>of</span> <span m=''4801230''>R</span> <span m=''4802090''>minus</span>
  <span m=''4802450''>the</span> <span m=''4802520''>expected</span> <span m=''4803040''>value</span>
  <span m=''4803590''>of</span> <span m=''4803670''>the</span> <span m=''4803780''>expected</span>
  <span m=''4804320''>value of</span> <span m=''4804770''>R.</span> <span m=''4806560''>The</span>
  <span m=''4806650''>expected</span> <span m=''4807140''>value</span> <span m=''4807500''>of</span>
  <span m=''4807580''>a</span> <span m=''4807650''>scalar</span> <span m=''4808860''>is</span>
  <span m=''4809030''>just</span> <span m=''4809410''>that</span> <span m=''4809640''>scalar.</span>
  <span m=''4813400''>And</span> <span m=''4813510''>that</span> <span m=''4813750''>is</span>
  <span m=''4814960''>0.</span> </p><p><span m=''4817270''>So</span> <span m=''4817440''>the</span>
  <span m=''4817600''>expected</span> <span m=''4818320''>deviation</span> <span m=''4819380''>from</span>
  <span m=''4819540''>the</span> <span m=''4819630''>mean</span> <span m=''4820570''>is</span>
  <span m=''4820770''>0</span> <span m=''4821700''>because</span> <span m=''4821980''>of</span>
  <span m=''4822050''>how</span> <span m=''4822190''>the</span> <span m=''4822290''>mean</span>
  <span m=''4822660''>is</span> <span m=''4822890''>defined.</span> <span m=''4824070''>It''s</span>
  <span m=''4824270''>the</span> <span m=''4824350''>midpoint,</span> <span m=''4824980''>the
  weighted</span> <span m=''4825290''>midpoint.</span> <span m=''4825750''>The</span>
  <span m=''4826480''>times</span> <span m=''4826820''>you''re</span> <span m=''4826900''>high</span>
  <span m=''4827220''>cancel</span> <span m=''4827720''>out</span> <span m=''4827820''>the</span>
  <span m=''4827910''>times</span> <span m=''4828220''>you''re</span> <span m=''4828320''>low
  if you</span> <span m=''4828740''>got</span> <span m=''4830620''>the</span> <span
  m=''4830710''>mean</span> <span m=''4830930''>right.</span> <span m=''4831950''>And</span>
  <span m=''4832110''>so</span> <span m=''4832210''>this</span> <span m=''4832440''>is</span>
  <span m=''4832560''>a</span> <span m=''4832690''>useless</span> <span m=''4833280''>definition.</span>
  <span m=''4833820''>It''s</span> <span m=''4833960''>always</span> <span m=''4834280''>0.</span>
  </p><p><span m=''4836150''>So</span> <span m=''4836230''>mathematicians</span> <span
  m=''4836890''>had</span> <span m=''4837120''>to</span> <span m=''4837190''>do</span>
  <span m=''4837330''>something</span> <span m=''4838580''>to</span> <span m=''4838690''>capture</span>
  <span m=''4839090''>this.</span> <span m=''4840430''>Now</span> <span m=''4840680''>what</span>
  <span m=''4840860''>would</span> <span m=''4840970''>have</span> <span m=''4841060''>been</span>
  <span m=''4841190''>the</span> <span m=''4841270''>more</span> <span m=''4841460''>logical</span>
  <span m=''4842000''>thing</span> <span m=''4842220''>to</span> <span m=''4842300''>do</span>
  <span m=''4842540''>that</span> <span m=''4842640''>is</span> <span m=''4842790''>the
  next</span> <span m=''4842910''>step.</span> <span m=''4843390''>This</span> <span
  m=''4843550''>doesn''t</span> <span m=''4843800''>work,</span> <span m=''4843990''>but</span>
  <span m=''4844395''>what</span> <span m=''4844800''>would</span> <span m=''4844910''>you</span>
  <span m=''4845000''>think</span> <span m=''4845270''>the</span> <span m=''4845340''>mathematicians</span>
  <span m=''4845675''>would''ve</span> <span m=''4846150''>done?</span> </p><p><span
  m=''4847730''>Absolute</span> <span m=''4848330''>value</span> <span m=''4848660''>would</span>
  <span m=''4848740''>have</span> <span m=''4848810''>made</span> <span m=''4848970''>a</span>
  <span m=''4849020''>lot</span> <span m=''4849320''>of</span> <span m=''4849400''>sense</span>
  <span m=''4849800''>here.</span> <span m=''4851670''>Why</span> <span m=''4852000''>they</span>
  <span m=''4852340''>didn''t</span> <span m=''4852620''>do</span> <span m=''4852730''>that?</span>
  <span m=''4854370''>Well,</span> <span m=''4855310''>you</span> <span m=''4855470''>could</span>
  <span m=''4855720''>do</span> <span m=''4855820''>that,</span> <span m=''4856200''>but</span>
  <span m=''4856300''>it''s</span> <span m=''4856440''>hard</span> <span m=''4856760''>to</span>
  <span m=''4856850''>work</span> <span m=''4857180''>with</span> <span m=''4857330''>mathematically.</span>
  <span m=''4857960''>You</span> <span m=''4858060''>can''t</span> <span m=''4858370''>prove</span>
  <span m=''4858640''>nice</span> <span m=''4858960''>theorems,</span> <span m=''4859630''>it</span>
  <span m=''4859760''>turns</span> <span m=''4860050''>out.</span> </p><p><span m=''4861470''>If</span>
  <span m=''4861610''>you</span> <span m=''4861700''>put</span> <span m=''4861880''>the</span>
  <span m=''4861980''>square</span> <span m=''4862470''>in</span> <span m=''4862560''>there</span>
  <span m=''4863830''>and</span> <span m=''4863940''>make</span> <span m=''4864120''>that
  be</span> <span m=''4864330''>the</span> <span m=''4864520''>variance,</span> <span
  m=''4865050''>you</span> <span m=''4865200''>can</span> <span m=''4866040''>prove</span>
  <span m=''4866390''>a</span> <span m=''4866450''>theorem</span> <span m=''4866810''>about</span>
  <span m=''4867040''>linearity</span> <span m=''4867610''>of</span> <span m=''4867650''>variance.</span>
  <span m=''4869030''>And</span> <span m=''4869490''>if</span> <span m=''4869660''>the</span>
  <span m=''4869760''>random</span> <span m=''4870050''>variables</span> <span m=''4870470''>are</span>
  <span m=''4870550''>independent,</span> <span m=''4871290''>then</span> <span m=''4871320''>the</span>
  <span m=''4871400''>variance</span> <span m=''4871840''>of</span> <span m=''4871900''>the</span>
  <span m=''4871990''>sum</span> <span m=''4872350''>is</span> <span m=''4872430''>the</span>
  <span m=''4872550''>sum</span> <span m=''4872860''>of</span> <span m=''4872910''>the</span>
  <span m=''4872980''>variances.</span> <span m=''4874090''>And</span> <span m=''4874150''>mathematicians</span>
  <span m=''4874760''>like</span> <span m=''4875010''>that</span> <span m=''4875170''>kind</span>
  <span m=''4875330''>of</span> <span m=''4875430''>thing.</span> <span m=''4876630''>It
  makes</span> <span m=''4876920''>it</span> <span m=''4876990''>easier</span> <span
  m=''4877320''>to</span> <span m=''4877390''>work</span> <span m=''4877680''>with</span>
  <span m=''4877990''>and do</span> <span m=''4878150''>things</span> <span m=''4878450''>with.</span>
  </p><p><span m=''4879640''>Now</span> <span m=''4879760''>there</span> <span m=''4879990''>are</span>
  <span m=''4880170''>also</span> <span m=''4880530''>other</span> <span m=''4880740''>choices</span>
  <span m=''4882580''>like,</span> <span m=''4883030''>in</span> <span m=''4883090''>fact,</span>
  <span m=''4883320''>there''s</span> <span m=''4883490''>a</span> <span m=''4883550''>special</span>
  <span m=''4883950''>name</span> <span m=''4884150''>for</span> <span m=''4884290''>a</span>
  <span m=''4884350''>weird</span> <span m=''4884720''>case</span> <span m=''4885260''>where</span>
  <span m=''4886120''>you</span> <span m=''4886220''>take</span> <span m=''4886550''>the</span>
  <span m=''4886850''>fourth</span> <span m=''4887310''>power.</span> <span m=''4892450''>You</span>
  <span m=''4892600''>could</span> <span m=''4892930''>do</span> <span m=''4893050''>that.</span>
  <span m=''4893360''>As</span> <span m=''4893460''>long</span> <span m=''4893630''>as</span>
  <span m=''4893750''>an</span> <span m=''4893850''>even</span> <span m=''4894150''>power,</span>
  <span m=''4894460''>you</span> <span m=''4894550''>could</span> <span m=''4894720''>do</span>
  <span m=''4894930''>it.</span> </p><p><span m=''4895690''>And</span> <span m=''4895740''>that''s</span>
  <span m=''4895940''>actually</span> <span m=''4896210''>called</span> <span m=''4896530''>the</span>
  <span m=''4896630''>kurtosis.</span> <span m=''4899040''>Sounds</span> <span m=''4899240''>like</span>
  <span m=''4899350''>a</span> <span m=''4899420''>foot</span> <span m=''4899760''>disease.</span>
  <span m=''4901260''>But</span> <span m=''4901390''>it''s</span> <span m=''4901510''>the</span>
  <span m=''4901610''>kurtosis</span> <span m=''4902410''>of</span> <span m=''4902500''>the</span>
  <span m=''4902610''>random</span> <span m=''4902920''>variable.</span> <span m=''4904370''>Now</span>
  <span m=''4904520''>we''re</span> <span m=''4904630''>not</span> <span m=''4904790''>going</span>
  <span m=''4904880''>to</span> <span m=''4904940''>worry</span> <span m=''4905180''>about</span>
  <span m=''4905460''>that</span> <span m=''4905780''>in</span> <span m=''4905860''>this</span>
  <span m=''4906030''>class.</span> </p><p><span m=''4906915''>But</span> <span m=''4907370''>we</span>
  <span m=''4907530''>are</span> <span m=''4907720''>going</span> <span m=''4907810''>to</span>
  <span m=''4907880''>worry</span> <span m=''4908170''>about</span> <span m=''4908780''>variance.</span>
  <span m=''4910030''>And</span> <span m=''4910790''>let</span> <span m=''4911110''>me</span>
  <span m=''4911230''>do</span> <span m=''4911340''>one</span> <span m=''4911590''>more</span>
  <span m=''4911760''>definition,</span> <span m=''4912350''>then</span> <span m=''4912480''>we''ll</span>
  <span m=''4912580''>talk</span> <span m=''4912790''>about</span> <span m=''4912980''>variance
  a</span> <span m=''4913320''>lot</span> <span m=''4913530''>more</span> <span m=''4913680''>tomorrow.</span>
  <span m=''4916560''>That</span> <span m=''4916720''>square</span> <span m=''4917170''>is</span>
  <span m=''4917410''>a</span> <span m=''4917470''>bit</span> <span m=''4917590''>of</span>
  <span m=''4917680''>a</span> <span m=''4917740''>pain.</span> <span m=''4918480''>And</span>
  <span m=''4918640''>to</span> <span m=''4918720''>get</span> <span m=''4918920''>rid</span>
  <span m=''4919220''>of</span> <span m=''4919340''>it,</span> <span m=''4920630''>they</span>
  <span m=''4920780''>made</span> <span m=''4921000''>another</span> <span m=''4921300''>definition</span>
  <span m=''4922310''>after</span> <span m=''4922630''>the</span> <span m=''4922720''>fact</span>
  <span m=''4923020''>called</span> <span m=''4923310''>the</span> <span m=''4923390''>standard</span>
  <span m=''4923840''>deviation.</span> </p><p><span m=''4926590''>And</span> <span
  m=''4927910''>standard</span> <span m=''4928260''>deviation</span> <span m=''4928850''>is</span>
  <span m=''4928940''>defined</span> <span m=''4930290''>as</span> <span m=''4930330''>follows.</span>
  <span m=''4933790''>For a</span> <span m=''4933930''>random</span> <span m=''4934270''>variable</span>
  <span m=''4934750''>R,</span> <span m=''4937000''>the</span> <span m=''4937100''>standard</span>
  <span m=''4937420''>deviation</span> <span m=''4946160''>of</span> <span m=''4946615''>R</span>
  <span m=''4949650''>is</span> <span m=''4949940''>denoted</span> <span m=''4950620''>by</span>
  <span m=''4950980''>a</span> <span m=''4951040''>sigma</span> <span m=''4952095''>of</span>
  <span m=''4952390''>R.</span> <span m=''4954150''>And</span> <span m=''4954340''>it''s</span>
  <span m=''4954550''>just</span> <span m=''4954810''>the</span> <span m=''4954910''>square</span>
  <span m=''4955360''>root</span> <span m=''4955650''>of</span> <span m=''4955780''>the</span>
  <span m=''4955850''>variance,</span> <span m=''4958140''>undoing</span> <span m=''4958750''>that</span>
  <span m=''4958950''>nasty</span> <span m=''4959340''>square</span> <span m=''4959730''>root</span>
  <span m=''4960010''>after</span> <span m=''4960310''>the</span> <span m=''4960390''>fact.</span>
  <span m=''4961650''>So</span> <span m=''4961790''>it</span> <span m=''4961890''>turns</span>
  <span m=''4962230''>out</span> <span m=''4962440''>to</span> <span m=''4962520''>be</span>
  <span m=''4962620''>the</span> <span m=''4962720''>square</span> <span m=''4963200''>root</span>
  <span m=''4963580''>of</span> <span m=''4963730''>the</span> <span m=''4963890''>expectation</span>
  <span m=''4965250''>of</span> <span m=''4965400''>the</span> <span m=''4965510''>deviation</span>
  <span m=''4966770''>squared.</span> </p><p><span m=''4968940''>Another</span> <span
  m=''4969300''>name</span> <span m=''4969610''>for</span> <span m=''4969690''>this</span>
  <span m=''4970020''>you''ve</span> <span m=''4970170''>probably</span> <span m=''4970500''>seen,</span>
  <span m=''4972090''>it''s</span> <span m=''4972320''>the</span> <span m=''4972460''>root</span>
  <span m=''4973590''>of</span> <span m=''4973780''>the</span> <span m=''4973860''>mean</span>
  <span m=''4975741''>of</span> <span m=''4976290''>the</span> <span m=''4976500''>square</span>
  <span m=''4979246''>of</span> <span m=''4979700''>the</span> <span m=''4979860''>deviations.</span>
  <span m=''4982770''>And</span> <span m=''4982910''>so</span> <span m=''4982990''>you</span>
  <span m=''4983060''>get</span> <span m=''4983190''>this</span> <span m=''4983350''>thing</span>
  <span m=''4983490''>called</span> <span m=''4983720''>root-mean-square,</span> <span
  m=''4985580''>which</span> <span m=''4985770''>if</span> <span m=''4985860''>any
  of you</span> <span m=''4986140''>ever</span> <span m=''4986370''>done</span> <span
  m=''4986540''>curve</span> <span m=''4986990''>fitting</span> <span m=''4987410''>or</span>
  <span m=''4987480''>any</span> <span m=''4987620''>of</span> <span m=''4987670''>those</span>
  <span m=''4987830''>kinds</span> <span m=''4988070''>of</span> <span m=''4988150''>things</span>
  <span m=''4988510''>in</span> <span m=''4989110''>statistics</span> <span m=''4989750''>or</span>
  <span m=''4989790''>whatever,</span> <span m=''4990740''>this</span> <span m=''4990960''>is</span>
  <span m=''4991070''>what</span> <span m=''4991240''>you''re</span> <span m=''4991350''>talking</span>
  <span m=''4991690''>about.</span> <span m=''4992640''>And</span> <span m=''4992760''>so</span>
  <span m=''4992830''>that''s</span> <span m=''4992990''>why</span> <span m=''4993150''>that</span>
  <span m=''4993330''>expression were</span> <span m=''4993710''>to</span> <span m=''4993850''>come</span>
  <span m=''4994050''>about.</span> </p><p></p><p><span m=''4998090''>So</span> <span
  m=''4998260''>for</span> <span m=''4998560''>the</span> <span m=''4998650''>standard</span>
  <span m=''4998960''>deviation</span> <span m=''4999530''>of</span> <span m=''5000380''>R--</span>
  <span m=''5000780''>what''s</span> <span m=''5000960''>the</span> <span m=''5001030''>standard</span>
  <span m=''5001300''>deviation</span> <span m=''5001730''>of</span> <span m=''5001830''>R?</span>
  <span m=''5003670''>1,000?</span> <span m=''5004800''>In</span> <span m=''5004930''>effect,</span>
  <span m=''5005180''>that''s</span> <span m=''5005380''>pretty</span> <span m=''5005560''>close</span>
  <span m=''5005860''>to</span> <span m=''5005990''>what</span> <span m=''5006180''>you</span>
  <span m=''5006250''>expect</span> <span m=''5006590''>the</span> <span m=''5006640''>deviation</span>
  <span m=''5006930''>to</span> <span m=''5007280''>be.</span> </p><p><span m=''5008360''>What''s</span>
  <span m=''5008580''>the</span> <span m=''5008670''>standard</span> <span m=''5009010''>deviation</span>
  <span m=''5009680''>of</span> <span m=''5009810''>S?</span> <span m=''5013020''>1.</span>
  <span m=''5013450''>Square root of</span> <span m=''5013880''>1</span> <span m=''5014060''>is</span>
  <span m=''5014160''>1,</span> <span m=''5014430''>and</span> <span m=''5014490''>that''s</span>
  <span m=''5014640''>what</span> <span m=''5014790''>you</span> <span m=''5014900''>expect</span>
  <span m=''5015165''>its</span> <span m=''5015430''>deviation</span> <span m=''5015735''>to</span>
  <span m=''5016040''>be.</span> </p><p><span m=''5017240''>So</span> <span m=''5017380''>we''ll</span>
  <span m=''5017490''>do</span> <span m=''5017610''>more of</span> <span m=''5017930''>this</span>
  <span m=''5018290''>tomorrow</span> <span m=''5018550''>on</span> <span m=''5018660''>recitation.</span>
  </p><p></p>'
type: course
uid: ffc3342feaa1ee9e66c8d6cdbb30ca8d

---
None