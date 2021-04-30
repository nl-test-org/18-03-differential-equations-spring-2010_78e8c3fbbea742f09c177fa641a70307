---
about_this_resource_text: '<p><strong>Topics covered:</strong> Using Laplace Transform
  to Solve ODEs with Discontinuous Inputs.</p><p><strong>Instructor/speaker: </strong>Prof.
  Arthur Mattuck</p>'
course_id: 18-03-differential-equations-spring-2010
embedded_media:
- id: 22.jpg
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  technical_location: https://ocw.mit.edu/courses/mathematics/18-03-differential-equations-spring-2010/video-lectures/lecture-22-using-laplace-transform-to-solve-odes-with-discontinuous-inputs/22.jpg
  title: 22.jpg
  type: null
  uid: 3085432f708b512dbe6087463e8afea8
- id: Video-YouTube-Stream
  media_location: _YVcjNmjHik
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  title: Video-YouTube-Stream
  type: Video
  uid: ad58e485b389c563623ad3d377532d00
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/_YVcjNmjHik/default.jpg
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: d69f577bcfc3b347632be7e12973008d
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id354869128
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  title: Video-iTunes U-MP4
  type: Video
  uid: b56c45c398c37ad13149a09db8d15ae2
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.03S06/mit-ocw-18.03-lec22-09apr2003-220k.mp4
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  title: Video-Internet Archive-MP4
  type: Video
  uid: 7dffab64d9e953461e17177c66bef5d8
- id: Video-VideoLecturesnet-Stream
  media_location: http://videolectures.net/mit1803s06_differential_equations/
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  title: Video-VideoLectures.net-Stream
  type: Video
  uid: 59b307587af00da7f48867b80c97071d
- id: Thumbnail-OCW-JPG
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 7acedd27922eff3e9a141f97f9021e8a
- id: 3Play-3PlayYouTubeid-MP4
  media_location: _YVcjNmjHik
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 9c827bb77217b07be0fdf51bc768b903
- id: YVcjNmjHik.srt
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  technical_location: https://ocw.mit.edu/courses/mathematics/18-03-differential-equations-spring-2010/video-lectures/lecture-22-using-laplace-transform-to-solve-odes-with-discontinuous-inputs/YVcjNmjHik.srt
  title: 3play caption file
  type: null
  uid: c4611f4c285210908186c49a7d27ba2f
- id: YVcjNmjHik.pdf
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  technical_location: https://ocw.mit.edu/courses/mathematics/18-03-differential-equations-spring-2010/video-lectures/lecture-22-using-laplace-transform-to-solve-odes-with-discontinuous-inputs/YVcjNmjHik.pdf
  title: 3play pdf file
  type: null
  uid: 419f31071777faa4a1d78a84b4582120
- id: Caption-3Play YouTube id-SRT
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: f8a9902b7a848b6de4ba4cb31ce8bbbe
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 717edb6734efeac2e8c4c65cdefaac6c
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 365e35f21f2b808292b2458ba00cf579
inline_embed_id: 22501003lecture22:usinglaplacetransformtosolveodeswithdiscontinuousinputs67466445
layout: video
order_index: null
parent_uid: 1555305200815ae857fb572ef6d294a3
related_resources_text: ''
short_url: lecture-22-using-laplace-transform-to-solve-odes-with-discontinuous-inputs
technical_location: https://ocw.mit.edu/courses/mathematics/18-03-differential-equations-spring-2010/video-lectures/lecture-22-using-laplace-transform-to-solve-odes-with-discontinuous-inputs
template_type: Tabbed
title: 'Lecture 22: Using Laplace Transform to Solve ODEs with Discontinuous Inputs'
transcript: <p><span m='10000'>Today we are going to do a last serious topic on the
  Laplace</span> <span m='14000'>transform, the last topic for which I don't have
  to make</span> <span m='19000'>frequent and profuse apologies. One of the things
  the Laplace</span> <span m='24000'>transform does very well and one of the reasons
  why people like</span> <span m='29000'>it, engineers like it, is that it handles
  functions</span> <span m='33000'>with jump discontinuities very nicely.</span> </p><p><span
  m='47000'>Now, the OR function with a jump discontinuity is-- Purple.</span> </p><p><span
  m='54000'>Is a function called the unit step function.</span> </p><p><span m='60000'>I
  will draw a graph of it. Even the graph is</span> <span m='63000'>controversial,
  but everyone is agreed that it</span> <span m='67000'>zero here and one there. What
  people are not agreed upon</span> <span m='72000'>is its value at zero. And some
  people make it zero,</span> <span m='76000'>some people make it one, and some equivocate
  like me.</span> </p><p><span m='80000'>I will leave it undefined. It is u of t.</span>
  </p><p><span m='84000'>It is called the unit step.</span> </p><p><span m='92000'>Because
  that is what it is. And let's say we will leave u</span> <span m='95000'>of zero
  undefined.</span> </p><p><span m='103000'>If that makes you unhappy, get over it.</span>
  </p><p><span m='106000'>Of course, we don't always want the jump to be at zero.</span>
  </p><p><span m='111000'>Sometimes we will want to jump in another place.</span>
  </p><p><span m='115000'>If I want the function to jump, let's say at the point a</span>
  <span m='120000'>instead of jumping at zero, I am going to start doing what</span>
  <span m='125000'>everybody does. You put in the vertical lines,</span> <span m='130000'>even
  though I have no meaning, whatever, but it makes the</span> <span m='135000'>graph
  look more connected and a little easier to read.</span> </p><p><span m='139000'>So
  that function I will call u sub a is the function</span> <span m='144000'>which
  jumps at the point a. How shall I give its</span> <span m='148000'>definition? Well,
  you can see it is just</span> <span m='152000'>the translation by a of the unit
  step function.</span> </p><p><span m='156000'>So that is the way to write it, u
  of t minus a.</span> </p><p><span m='162000'>Now I am not done. There is a unit
  box function,</span> <span m='166000'>which we will draw in general terms like this.</span>
  </p><p><span m='171000'>It gets to a, then it jumps up to one,</span> <span m='174000'>falls
  down again at b and continues onto zero.</span> </p><p><span m='180000'>This happens
  between a and b. And the value to which it</span> <span m='184000'>arises is one.
  I will call this the unit box.</span> </p><p><span m='197000'>It is a function of
  t, a very simple one but an</span> <span m='200000'>important one. And what would
  be the formula</span> <span m='203000'>for the unit box function? Well, in general,</span>
  <span m='206000'>almost all of these functions, as you will see when you use</span>
  <span m='210000'>jump discontinuity, the idea is to write them all</span> <span
  m='213000'>cleverly using nothing but u of.</span> </p><p><span m='217000'>Because
  it is that will have the Laplace transformer.</span> </p><p><span m='221000'>The
  way to write this is (u)ab.</span> </p><p><span m='223000'>And, if you like, you
  can treat this as the</span> <span m='227000'>definition of it. Let's make it a
  definition.</span> </p><p><span m='230000'>Okay, three lines. Or, better yet,</span>
  <span m='233000'>a colon and two lines. I am defining this to be,</span> <span m='237000'>what
  would it be? Make the unit step at a step up</span> <span m='242000'>at a, but then
  I would continue at one all the time.</span> </p><p><span m='247000'>I should, therefore,
  step down at b.</span> </p><p><span m='250000'>Now, the way you step down is just
  by taking the negative of</span> <span m='255000'>the unit step function. I step
  down at b by subtracting</span> <span m='260000'>u sub b of t . In other words,</span>
  <span m='264000'>it is u of t minus a minus u of t minus b.</span> </p><p><span
  m='269000'>And now I have expressed it</span> <span m='272000'>entirely in terms
  of the unit step function.</span> </p><p><span m='275000'>That will be convenient
  when I want take the Laplace transform.</span> </p><p><span m='279000'>What is so
  good about these things?</span> </p><p><span m='281000'>Well, these functions, when
  you use them in</span> <span m='283000'>multiplications, they transform other functions</span>
  <span m='286000'>in a nice way. Not transform.</span> </p><p><span m='288000'>That
  is not the right word. They operate on them.</span> </p><p><span m='291000'>They
  turn them into other strange creatures,</span> <span m='293000'>and it might be
  these strange creatures that you are</span> <span m='296000'>interested in. Let
  me just draw you a picture.</span> </p><p><span m='301000'>That will be good enough.
  Suppose we have some function</span> <span m='307000'>like that, f of t, what would
  the function u sub</span> <span m='312000'>ab, I will put in the variable,</span>
  <span m='316000'>t times f of t, what function would that be?</span> </p><p><span
  m='321000'>I am just going to draw its graph.</span> </p><p><span m='324000'>What
  would its graph be? Well, in between a and b this</span> <span m='330000'>function
  (u)ab of t has the value one.</span> </p><p><span m='334000'>All I am doing is multiplying
  f of t by one.</span> </p><p><span m='339000'>In short, I am not doing anything
  to it at all.</span> </p><p><span m='343000'>Outside of that interval, (u)ab has
  the value zero,</span> <span m='347000'>so that zero times f of t makes zero.</span>
  </p><p><span m='351000'>And, therefore, outside of this it is zero.</span> </p><p><span
  m='355000'>The effect of multiplying an arbitrary function by this unit</span> <span
  m='360000'>box function is, you wipe away all of its graph</span> <span m='363000'>except
  the part between a and b. Now, that is a very useful</span> <span m='370000'>thing
  to be able to do. Well, that is enough of that.</span> </p><p><span m='374000'>Now,
  let's get into the main topic.</span> </p><p><span m='377000'>That is just preliminary.
  I will be using these functions</span> <span m='382000'>all during the period, but
  the real topic is the</span> <span m='385000'>following. Let's calculate the Laplace</span>
  <span m='389000'>transform of the unit step function.</span> </p><p><span m='393000'>Well,
  this is no very big deal. It is the integral from zero to</span> <span m='398000'>infinity
  e to the minus s t times y of t, dt.</span> </p><p><span m='405000'>But, look, when
  t is bigger than zero,</span> <span m='409000'>this has the value one. So it is
  the same of the</span> <span m='413000'>Laplace transform of one. In other words,</span>
  <span m='416000'>it is one over s for positive values of s.</span> </p><p><span
  m='422000'>Or, to make it very clear, the Laplace transform of one is</span> <span
  m='426000'>exactly the same thing. As you see, the Laplace</span> <span m='429000'>transform
  really is not interested in what happens when</span> <span m='433000'>t is less
  than zero because that is not part of the</span> <span m='437000'>domain of integration,
  the interval of integration.</span> </p><p><span m='441000'>That is fine. They both
  have Laplace</span> <span m='444000'>transform of one over s.</span> </p><p><span
  m='446000'>What is the big deal? The big deal is,</span> <span m='450000'>what is
  the inverse Laplace transform of one over s?</span> </p><p><span m='457000'>Will
  the real function please</span> <span m='461000'>stand up? Which of these two should
  I</span> <span m='465000'>pick? Up to now in the course we have</span> <span m='469000'>been
  picking one just because I never made a fuss over it and</span> <span m='476000'>one
  was good enough. For today one is no longer</span> <span m='481000'>going to be
  good enough. And we have to first</span> <span m='485000'>investigate the thing
  in a slightly more theoretical way</span> <span m='489000'>because this problem,
  I have illustrated it on the</span> <span m='493000'>inverse Laplace transform of
  one over x,</span> <span m='497000'>but it occurs for any inverse Laplace transform.</span>
  </p><p><span m='500000'>Suppose I have, in other words,</span> <span m='503000'>that
  a function f of t has as its Laplace transform capital F</span> <span m='507000'>of
  s? And now, I ask what the inverse</span> <span m='512000'>Laplace transform of
  capital F of s is.</span> </p><p><span m='517000'>Well, of course you want to write
  f of t.</span> </p><p><span m='521000'>But the same thing happens. I will draw you
  a picture.</span> </p><p><span m='525000'>Suppose, in other words, that here is
  our function f of</span> <span m='530000'>t. Well, one answer certainly is f</span>
  <span m='533000'>of t. That is okay.</span> </p><p><span m='534000'>That is the
  answer we have been using up until now.</span> </p><p><span m='540000'>But, you
  see, I can complete this function in</span> <span m='544000'>many other ways. Suppose
  I haven't told you what</span> <span m='548000'>it was for s less than zero. Any
  of these possibilities all</span> <span m='554000'>will produce the same Laplace
  transform.</span> </p><p><span m='557000'>In fact, I can even make it this.</span>
  </p><p><span m='560000'>That is okay. Each of these,</span> <span m='563000'>f of
  t with any one of these tails, all have the same</span> <span m='568000'>Laplace
  transform.</span> </p><p><span m='577000'>Because the Laplace transform, remember
  the definition,</span> <span m='581000'>integral zero to infinity, e to the negative
  s t,</span> <span m='584000'>f of t, dt</span> <span m='589000'>because the Laplace
  transform does not care what the function</span> <span m='593000'>was doing for
  negative values of t.</span> </p><p><span m='596000'>Now, if we have to have a unique
  answer --</span> <span m='600000'>And most of the time you don't because, in general,</span>
  <span m='603000'>the Laplace transform is only used for problems for future</span>
  <span m='607000'>time. That is the way the engineers</span> <span m='609000'>and
  physicists and other people who use it habitually think of</span> <span m='613000'>it.
  If your problem is starting now</span> <span m='615000'>and going on into the future
  and you don't have to know anything</span> <span m='620000'>about the past, that
  is a Laplace transform</span> <span m='623000'>problem. If you also have to know
  about</span> <span m='625000'>the past, then it is a Fourier transform problem.</span>
  </p><p><span m='630000'>That is beyond the scope of this course, you will never
  hear</span> <span m='634000'>that word again, but that is the difference.</span>
  </p><p><span m='637000'>We are starting at time zero and going forward.</span> </p><p><span
  m='641000'>All right. It does not care what f of t</span> <span m='644000'>was doing
  for negative values of t.</span> </p><p><span m='646000'>And that gives us a problem
  when we try to make the Laplace</span> <span m='651000'>transform unique. Now, how
  will I make it unique?</span> </p><p><span m='654000'>Well, there is a simple way
  of doing it.</span> </p><p><span m='659000'>Let's agree that wherever it makes a
  difference,</span> <span m='662000'>and most of the time it doesn't, but today it
  will,</span> <span m='666000'>whenever it makes a difference we will declare,</span>
  <span m='669000'>we will by brute force make our function zero for negative</span>
  <span m='674000'>values of t. That makes it unique.</span> </p><p><span m='676000'>I
  am going to say that to make it unique, now,</span> <span m='680000'>how do I make
  f of t zero for negative values</span> <span m='684000'>of t? The answer is multiply
  it by</span> <span m='687000'>the unit step function. That leaves it what it was.</span>
  </p><p><span m='692000'>It multiplies it by one for positive values but multiplies</span>
  <span m='697000'>it by zero for negative values. The answer is going to be u of</span>
  <span m='702000'>t times f of t. That will be the function that</span> <span m='708000'>will
  look just that way that I drew, but I will draw it once</span> <span m='713000'>more.
  It is the function that looks</span> <span m='716000'>like this. And when I do this,</span>
  <span m='718000'>it makes the inverse Laplace transform unique.</span> </p><p><span
  m='724000'>Out of all the possible tails I might have put on f of t,</span> <span
  m='728000'>it picks the least interesting one,</span> <span m='731000'>the tail
  zero.</span> </p><p><span m='743000'>That is a start. But what we have to do now
  is</span> <span m='746000'>--</span> <span m='755000'>What I want is a formula.
  What we are going to need is,</span> <span m='758000'>as you see right even in the
  beginning, if for example,</span> <span m='762000'>if I want to calculate the Laplace
  transform of this,</span> <span m='766000'>what I would like to have is a nice Laplace
  transform for the</span> <span m='770000'>translate. If you translate a function,</span>
  <span m='772000'>how does that effect this Laplace transform?</span> </p><p><span
  m='775000'>In other words, the formula I am looking for is</span> <span m='778000'>--</span>
  <span m='788000'>I want to express the Laplace transform of f of t minus a.</span>
  </p><p><span m='792000'>In other words,</span> <span m='795000'>the function translated,
  let's say a is positive,</span> <span m='799000'>so I translate it to the right
  along the t axis by the distance</span> <span m='805000'>a. I want a formula for
  this in</span> <span m='807000'>terms of the Laplace transform of the function I
  started with.</span> </p><p><span m='814000'>Now, my first task is to convince you
  that,</span> <span m='817000'>though this would be very useful and interesting,</span>
  <span m='820000'>there cannot possibly be such a formula.</span> </p><p><span m='823000'>There
  is no such formula.</span> </p><p><span m='836000'>Why not? Well, I think I will
  explain it</span> <span m='839000'>over there since there is a little piece of board
  I did not</span> <span m='845000'>use. Waste not want not.</span> </p><p><span m='847000'>Why
  can't there be such a formula?</span> </p><p><span m='850000'>What is it we are
  looking for? Let's take a nice average</span> <span m='855000'>function f of t.
  It has a Laplace transform.</span> </p><p><span m='860000'>And now I am going to
  translate it.</span> </p><p><span m='863000'>Let's say this is the point negative
  a.</span> </p><p><span m='869000'>And so the corresponding point positive a will
  be around here.</span> </p><p><span m='874000'>I am going to translate it to the
  right by a.</span> </p><p><span m='878000'>What is it going to look like? Well,
  then it is going to start</span> <span m='883000'>here and is going to look like
  this dashy thing.</span> </p><p><span m='888000'>That is f of t minus a.</span>
  </p><p><span m='891000'>That is not too bad a picture. It will do.</span> </p><p><span
  m='894000'>I just took that curve and shoved it to the right by a.</span> </p><p><span
  m='901000'>Now, why is it impossible to express the Laplace transform of</span>
  <span m='909000'>the dashed line in terms of the Laplace transform of the solid</span>
  <span m='918000'>line? The answer is this piece.</span> </p><p><span m='923000'>I
  will write it this way. The trouble is,</span> <span m='928000'>this piece is not
  used for the Laplace transform of f of t.</span> </p><p><span m='937000'>Why isn't
  it used?</span> </p><p><span m='941000'>Well, because it occurs to the left of the
  vertical axis.</span> </p><p><span m='944000'>It occurs for negative values of t.</span>
  </p><p><span m='947000'>And the Laplace transform of f of t simply does not</span>
  <span m='951000'>care what f of t was doing to the left of that line,</span> <span
  m='955000'>for negative values of t. It does not enter into the</span> <span m='958000'>integral.
  It was not used when I</span> <span m='961000'>calculated this piece of the curve.</span>
  </p><p><span m='964000'>It was not used when I calculated the Laplace transform</span>
  <span m='967000'>of f of t. On the other hand,</span> <span m='970000'>it is going
  to be needed. It occurs here,</span> <span m='973000'>after I shift it to the right.
  It is going to be needed for</span> <span m='977000'>the Laplace transform of f
  of t minus a,</span> <span m='981000'>because I will have to start the integration
  here,</span> <span m='985000'>and I will have to know what that is.</span> </p><p><span
  m='994000'>In other words, when I took the Laplace</span> <span m='997000'>transform,
  I automatically lost all information about the</span> <span m='1001000'>function
  for negative values of t.</span> </p><p><span m='1004000'>If I am later going to
  want some of that information for</span> <span m='1008000'>calculating this, I won't
  have it and,</span> <span m='1011000'>therefore, there cannot be a formula expressing
  one in terms</span> <span m='1016000'>of the other. Now, of course,</span> <span
  m='1019000'>that cannot be the answer, otherwise I would not have</span> <span m='1022000'>raised
  your expectations merely to dash them.</span> </p><p><span m='1025000'>I don't want
  to do that, of course.</span> </p><p><span m='1027000'>There is a formula, of course.</span>
  </p><p><span m='1029000'>It is just, I want to emphasize that you must write it
  my way</span> <span m='1033000'>because, if you write it any other way, you are
  going to get</span> <span m='1037000'>into the deepest trouble. The formula is--
  the good</span> <span m='1041000'>formula, the right formula --</span> <span m='1050000'>--
  accepts the given. It says look,</span> <span m='1052000'>we have lost that pink
  part of it.</span> </p><p><span m='1055000'>Therefore, I can never recover that.</span>
  </p><p><span m='1057000'>Therefore, I won't ask for it. The translation formula
  I will</span> <span m='1062000'>ask for is not one for the Laplace transform of
  f of t</span> <span m='1066000'>minus a, but rather for the Laplace</span> <span
  m='1070000'>transform of this thing where I have wiped away that pink part</span>
  <span m='1074000'>from the translated function. In other words,</span> <span m='1079000'>the
  function I am talking about now is the formula for,</span> <span m='1084000'>I will
  put it over here to show you the function what we are</span> <span m='1090000'>talking
  about. It is the function f of,</span> <span m='1093000'>well, in terms of the pink
  function it is,</span> <span m='1097000'>I will have to reproduce some of that picture.</span>
  </p><p><span m='1101000'>There is f of t. f of t minus a,</span> <span m='1106000'>then,
  looked like this. And so the function I am</span> <span m='1112000'>looking for
  is, this is the thing translated,</span> <span m='1116000'>but when I get down to
  the corresponding,</span> <span m='1119000'>this is the point that corresponds to
  that one,</span> <span m='1123000'>I wipe it away and just go with zero after that.</span>
  </p><p><span m='1128000'>So this is u of t minus a times f of t minus a times f
  of t</span> <span m='1133000'>minus a. What is this Laplace transform?</span> </p><p><span
  m='1140000'>Now that does have a simple answer.</span> </p><p><span m='1144000'>The
  answer is it is e to the minus as,</span> <span m='1150000'>a funny exponential,
  times the Laplace transform of</span> <span m='1156000'>the original function. Now,
  this formula occurs in two</span> <span m='1163000'>forms. This one is not too bad</span>
  <span m='1166000'>looking. The trouble is,</span> <span m='1169000'>when you want
  to solve differential equations you are</span> <span m='1173000'>going to be extremely
  puzzled because the function that you</span> <span m='1177000'>will have to take
  to do the calculation on will not be given</span> <span m='1181000'>to you in the
  form f of t minus a.</span> </p><p><span m='1184000'>It will look sine t or t squared
  or some</span> <span m='1188000'>polynomial in t. It will not be written as t</span>
  <span m='1190000'>minus a. What do you do?</span> </p><p><span m='1193000'>If your
  function does not look like that but instead,</span> <span m='1196000'>in terms
  of symbols looks like this, you can still use the</span> <span m='1200000'>formula.
  Just a trivial change of</span> <span m='1203000'>variable means that you can write
  it instead.</span> </p><p><span m='1206000'>Now, this is one place, there is no
  way of writing the</span> <span m='1210000'>answer in terms of capital F of s.</span>
  </p><p><span m='1213000'>This is one of those cases where this notation is just
  no</span> <span m='1217000'>good anymore. I am going to have to write it</span>
  <span m='1220000'>using the L notation. The Laplace transform of f of,</span> <span
  m='1224000'>and wherever you see a t, you should write t plus a.</span> </p><p><span
  m='1228000'>Basically, this is the same</span> <span m='1231000'>formula as that
  one. But I will have to stand on my</span> <span m='1235000'>head for one minute
  to try to convince you of it.</span> </p><p><span m='1238000'>I won't do that now.
  I would like you just to take a</span> <span m='1242000'>look at the formula. You
  should know what it is</span> <span m='1245000'>called. There are a certain number
  of</span> <span m='1248000'>idiots who call this the exponential shift formula</span>
  <span m='1251000'>because on the right side you multiply by an exponential,</span>
  <span m='1255000'>and that corresponds to shifting the function.</span> </p><p><span
  m='1260000'>Unfortunately, we have preempted that.</span> </p><p><span m='1262000'>We
  are not going to call it this.</span> </p><p><span m='1265000'>I will call it what
  your book calls it.</span> </p><p><span m='1268000'>The difficulty is there is no
  universal designation for this</span> <span m='1273000'>formula, important as it
  is. However, your book calls this</span> <span m='1277000'>t-axis translation formula.
  Translation because I am</span> <span m='1281000'>translating on the t-axis. And
  that is what I do to the</span> <span m='1285000'>function, essentially. And this
  tells me what its new</span> <span m='1290000'>Laplace transform is.</span> </p><p><span
  m='1298000'>The other formula, remember it?</span> </p><p><span m='1300000'>The
  exponential shift formula, the shift or the translation</span> <span m='1304000'>occurs
  on the s-axis. In other words,</span> <span m='1307000'>the formula said that F
  of s minus a,</span> <span m='1311000'>you do the translation in s variable corresponded
  to</span> <span m='1315000'>multiplying this by e to the a t.</span> </p><p><span
  m='1320000'>In other words, the formulas are sort of dual</span> <span m='1322000'>to
  each other. This guy translates on the left</span> <span m='1325000'>side and multiplies
  by the exponential on the right.</span> </p><p><span m='1328000'>The formula that
  you know translates on the right and</span> <span m='1332000'>multiplies by the
  exponential on the left.</span> </p><p><span m='1334000'>What are we going to calculate?
  I am trying to calculate,</span> <span m='1338000'>so I am trying to prove this
  first formula.</span> </p><p><span m='1340000'>The second one will be an easy consequence.</span>
  </p><p><span m='1343000'>I am trying to calculate the Laplace transform of that
  thing.</span> </p><p><span m='1347000'>What is it? Well, it is the integral from</span>
  <span m='1351000'>zero to infinity of e to the minus st times u of t minus a,</span>
  <span m='1355000'>f of t minus a times dt.</span> </p><p><span m='1362000'>That
  is the formula for it. But I am trying to express it</span> <span m='1366000'>in
  terms of the Laplace transform of f itself.</span> </p><p><span m='1369000'>Now,
  it is trying to be the Laplace transform of f.</span> </p><p><span m='1374000'>The
  problem is that here, a (t minus a) occurs,</span> <span m='1378000'>which I don't
  like. I would like that to be just a</span> <span m='1383000'>t. Now, in order not
  to confuse</span> <span m='1385000'>you, and this is what confused everybody, I
  will set t1 equal</span> <span m='1389000'>to t minus a. I will change the variable.</span>
  </p><p><span m='1393000'>This is called changing the variable in a definite integral.</span>
  </p><p><span m='1397000'>How do you change the variable in a definite integral?</span>
  </p><p><span m='1401000'>You do it. Well, let's leave the limits</span> <span m='1404000'>for
  the moment. e to the minus s</span> <span m='1407000'>times -- Now, t, remember
  you can change</span> <span m='1411000'>the variable forwards, direct substitution,</span>
  <span m='1413000'>but now I have to use the inverse substitution.</span> </p><p><span
  m='1417000'>It's trivial, but t is equal to t1 plus a.</span> </p><p><span m='1420000'>To
  change this I must</span> <span m='1422000'>substitute backwards and make that t1
  plus a.</span> </p><p><span m='1425000'>How about the rest of it? Well, this becomes
  u of t1.</span> </p><p><span m='1429000'>This is f of t1.</span> </p><p><span m='1431000'>I
  have to change the dt, too, but that's no problem.</span> </p><p><span m='1435000'>dt1
  equals dt because a is a constant.</span> </p><p><span m='1440000'>That is dt1.
  And the last step is to put in</span> <span m='1443000'>the limits. Now, when t
  is equal to zero,</span> <span m='1446000'>t1 has the value negative a.</span> </p><p><span
  m='1450000'>So this has to be negative a when t is infinity.</span> </p><p><span
  m='1453000'>Infinity minus a is still infinity, so that is still</span> <span m='1457000'>infinity.
  In other words,</span> <span m='1459000'>this changes to that. These two things,</span>
  <span m='1462000'>whatever they are, they have the same value.</span> </p><p><span
  m='1465000'>All I have done is changed the variable.</span> </p><p><span m='1470000'>Make
  it change a variable. But now, of course,</span> <span m='1472000'>I want to make
  this look better.</span> </p><p><span m='1474000'>How am I going to do that? Well,
  first multiply out the</span> <span m='1477000'>exponential and then you get a factor
  e to the minus s(t1).</span> </p><p><span m='1480000'>That is good.</span> </p><p><span
  m='1482000'>That goes with this guy. Now I get a factor e to the</span> <span m='1484000'>minus
  s times a from the exponential law.</span> </p><p><span m='1487000'>But that does
  not have anything to do with the integral.</span> </p><p><span m='1491000'>It is
  a constant as far as the integral is concerned because it</span> <span m='1494000'>doesn't
  involve t1. And, therefore,</span> <span m='1496000'>I can pull it outside of the
  integral sign.</span> </p><p><span m='1500000'>And write that e to the minus s times
  a.</span> </p><p><span m='1505000'>Let's write it the other way. Times the integral
  of what?</span> </p><p><span m='1510000'>Well, e to the negative st1.</span> </p><p><span
  m='1514000'>Now, u of t1, f of t1 times dt1.</span> </p><p><span m='1518000'>Still
  integrated from minus a</span> <span m='1522000'>to infinity. And now the final
  step.</span> </p><p><span m='1529000'>This u of t1 is zero for negative values of
  t.</span> </p><p><span m='1534000'>And, therefore, it is equal to one for positive</span>
  <span m='1538000'>values of t. It is equal to zero for</span> <span m='1542000'>negative
  values of t, which means I can forget about</span> <span m='1547000'>the part of
  the integral that goes from negative a to zero.</span> </p><p><span m='1552000'>I
  better rewrite this.</span> </p><p><span m='1556000'>Okay, leave that. In other
  words,</span> <span m='1560000'>this is equal to e to the minus as times the</span>
  <span m='1564000'>integral from zero to infinity of e to the minus s --</span> <span
  m='1568000'>Let me do the shifty part now.</span> </p><p><span m='1577000'>And this
  is since u of t1 is equal to zero for</span> <span m='1583000'>t1 less than zero.
  That is why I can replace this</span> <span m='1589000'>with zero. Because from
  negative a to</span> <span m='1593000'>zero, nothing is happening. The integrand
  is zero.</span> </p><p><span m='1597000'>And why can I get rid of it after that?</span>
  </p><p><span m='1600000'>Well, because it is one after that.</span> </p><p><span
  m='1603000'>And what is this thing? This is the Laplace transform.</span> </p><p><span
  m='1607000'>No, it is not the Laplace transform they said.</span> </p><p><span m='1611000'>Because
  you had t1 there, not t.</span> </p><p><span m='1613000'>It is the Laplace transform
  because this is a dummy</span> <span m='1618000'>variable. The t1 is integrated
  out.</span> </p><p><span m='1621000'>It is a dummy variable. It doesn't matter what
  you call</span> <span m='1625000'>it. It is still the Laplace</span> <span m='1627000'>transform
  if I make that wiggly t or t star or tau or u.</span> </p><p><span m='1632000'>I
  can call it anything I want and it is still the Laplace</span> <span m='1636000'>transform
  of f of t.</span> </p><p><span m='1644000'>What is the answer? That is e to the
  negative as</span> <span m='1647000'>times the Laplace transform of the function
  f.</span> </p><p><span m='1653000'>That is what I promised you in that formula.</span>
  </p><p><span m='1655000'>Now, how about the other formula?</span> </p><p><span m='1657000'>Well,
  let's look at that quickly.</span> </p><p><span m='1659000'>That is, as I say, just
  sleight of hand.</span> </p><p><span m='1662000'>But since that is the formula you
  will be using at least half</span> <span m='1666000'>the time you better learn it.
  This little sleight of hand is</span> <span m='1670000'>also reproduced in one page
  of notes that I give you,</span> <span m='1673000'>but maybe you will find it easy
  to understand if I talk it out</span> <span m='1677000'>loud. The problem now is
  for the</span> <span m='1680000'>second formula. I am going to have to recopy</span>
  <span m='1683000'>out the first one in order to make the argument in a form in</span>
  <span m='1687000'>which you will understand it, I hope.</span> </p><p><span m='1689000'>This
  goes to e to the minus as F s,</span> <span m='1693000'>except I am now going to
  write that not in F of s;</span> <span m='1696000'>since I will not be able to write
  the second formula using F</span> <span m='1700000'>of s, I am not going to write
  the first formula that way</span> <span m='1704000'>either. I will write it as the
  Laplace</span> <span m='1706000'>transform with f of t.</span> </p><p><span m='1710000'>Now,
  formally if somebody says, okay, how do I calculate the</span> <span m='1714000'>Laplace
  transform of this thing? I say put down this.</span> </p><p><span m='1719000'>Well,
  that has no t in it. It doesn't have the f in it</span> <span m='1723000'>either.
  Then write this.</span> </p><p><span m='1725000'>What formula did I do? I looked
  at that and changed t</span> <span m='1730000'>minus a to t. Now, how did I change
  t minus a?</span> </p><p><span m='1735000'>The way to say it is</span> <span m='1738000'>I
  changed t. Because the t is always there.</span> </p><p><span m='1742000'>t to t
  plus a. You get this by replace t by t</span> <span m='1748000'>plus a to get the
  right-hand side.</span> </p><p><span m='1756000'>I replace this t by t plus a, and
  that turns this</span> <span m='1760000'>into f of t. And that is the f of t</span>
  <span m='1762000'>that went in there. That is the universal rule for</span> <span
  m='1766000'>doing it. Now I am going to use that same</span> <span m='1768000'>rule
  for transforming u of t minus a times f of t.</span> </p><p><span m='1772000'>See,
  the problem is now I have</span> <span m='1776000'>a function like t squared or
  sine t,</span> <span m='1779000'>which is not written in terms of t minus a.</span>
  </p><p><span m='1782000'>And I don't know what to do with it.</span> </p><p><span
  m='1784000'>The answer is, by brute force,</span> <span m='1786000'>write it in
  terms of t minus a.</span> </p><p><span m='1789000'>What is brute force? Brute force
  is the following.</span> </p><p><span m='1792000'>I am going to put a t minus a
  there if it kills me.</span> </p><p><span m='1796000'>t minus a plus a. No harm
  in that,</span> <span m='1801000'>is there? Now there is a t minus a there,</span>
  <span m='1804000'>just the way there was up there.</span> </p><p><span m='1806000'>And
  now what is the rule? I am just going to follow my</span> <span m='1811000'>nose.
  What's sauce for the goose is</span> <span m='1813000'>sauce for the gander. Minus
  as, Laplace transform of</span> <span m='1817000'>f of, now what am I going to write
  here?</span> </p><p><span m='1820000'>Wherever I see a t, I am going to change it
  from t</span> <span m='1824000'>plus a. Here I see a t.</span> </p><p><span m='1829000'>I
  will change that to t plus a.</span> </p><p><span m='1833000'>What do I have? t
  plus a minus a plus a,</span> <span m='1837000'>well, if you can keep count,</span>
  <span m='1841000'>what does that make? It makes t plus a in</span> <span m='1846000'>the
  end.</span> </p><p><span m='1862000'>The peace that passeth understanding.</span>
  </p><p><span m='1864000'>Let's do some examples and suddenly you will breathe a
  sigh</span> <span m='1868000'>of relief that this all is doable anyway.</span> </p><p><span
  m='1871000'>Let's calculate something. I hope I am not covering up any</span> <span
  m='1876000'>crucial, yes I am. I am covering up the u of t's,</span> <span m='1879000'>but
  you know that by now. Let's see.</span> </p><p><span m='1882000'>What should we
  calculate first? What I just covered up.</span> </p><p><span m='1887000'>Let's calculate
  the Laplace transform of (u)ab of t.</span> </p><p><span m='1891000'>What is that
  going to be?</span> </p><p><span m='1894000'>Well, first of all, write out what
  it is in terms</span> <span m='1898000'>of the unit step function.</span> </p><p><span
  m='1905000'>Remember that formula? There.</span> </p><p><span m='1907000'>Now you
  see it. Now you don't.</span> </p><p><span m='1910000'>Its Laplace transform is
  going to be what?</span> </p><p><span m='1914000'>Well, the Laplace transform of
  t minus a,</span> <span m='1919000'>that is a special case here where this function
  is one.</span> </p><p><span m='1925000'>Well, that one. Either one.</span> </p><p><span
  m='1927000'>It makes no difference. It is simply going to be the</span> <span m='1931000'>Laplace
  transform of what f of t would have been,</span> <span m='1935000'>which is --</span>
  <span m='1946000'>See, the Laplace transform of u of t is what?</span> </p><p><span
  m='1950000'>That's one over s, right?</span> </p><p><span m='1951000'>Because this
  is the function one, and we don't care the fact</span> <span m='1956000'>that it
  is zero or negative values of t.</span> </p><p><span m='1959000'>That is my f of
  s. And so I multiply it by e to</span> <span m='1963000'>the minus as times one
  over s.</span> </p><p><span m='1966000'>I am using this formula, e to the minus
  as times the</span> <span m='1970000'>Laplace transform of the unit step function,</span>
  <span m='1973000'>which is one over s. How about the translation?</span> </p><p><span
  m='1979000'>That was taken care of by the exponential factor.</span> </p><p><span
  m='1983000'>And it's minus because this is minus.</span> </p><p><span m='1986000'>The
  same thing with the b. This is the Laplace transform</span> <span m='1990000'>of
  the unit box function. It looks a little hairy.</span> </p><p><span m='1994000'>You
  will learn to work with it, don't worry about it.</span> </p><p><span m='1999000'>How
  about the Laplace transform of --</span> <span m='2003000'>Okay. Let's use the other
  formula.</span> </p><p><span m='2005000'>What would be the Laplace transform of
  u of t minus one</span> <span m='2009000'>times t squared, for example?</span> </p><p><span
  m='2013000'>See, if I gave this to you and you only had the first formula,</span>
  <span m='2018000'>you would say, hey, but there is no t minus</span> <span m='2021000'>one
  in there. There is only t squared.</span> </p><p><span m='2024000'>What am I supposed
  to do?</span> </p><p><span m='2026000'>Well, some of you might dig way back into
  high school and say</span> <span m='2031000'>every polynomial can be written in
  powers of t minus one,</span> <span m='2036000'>that is what I will do. That would
  give the right</span> <span m='2042000'>answer. But in case you had forgotten</span>
  <span m='2045000'>how to do that, you don't have to know because</span> <span m='2048000'>you
  could use the other formula instead, which,</span> <span m='2052000'>by the way,
  is the way you do it.</span> </p><p><span m='2055000'>What are we going to do? It
  goes into e to the minus s.</span> </p><p><span m='2059000'>The a is one in this
  case,</span> <span m='2062000'>plus one. e to the minus s times the</span> <span
  m='2065000'>Laplace transform of what function?</span> </p><p><span m='2070000'>Change
  t to t plus one.</span> </p><p><span m='2073000'>The Laplace transform of t plus
  one squared.</span> </p><p><span m='2078000'>What is that? That is e to the minus
  s times</span> <span m='2081000'>the Laplace transform of t squared plus 2t plus
  one.</span> </p><p><span m='2086000'>What's that?</span> </p><p><span m='2089000'>Well,
  by the formulas which I am not bothering to write on the</span> <span m='2094000'>board
  anymore because you know them, it is e to the minus s</span> <span m='2099000'>times
  -- Laplace transform of t squared</span> <span m='2104000'>is two factorial over
  s cubed.</span> </p><p><span m='2107000'>Remember you always have to</span> <span
  m='2109000'>raise the exponent by one. This is two factorial,</span> <span m='2112000'>but
  that is the same as two. Plus two.</span> </p><p><span m='2115000'>This two comes
  from there. The Laplace transform of t is</span> <span m='2119000'>one over s squared.</span>
  </p><p><span m='2121000'>And, finally, the Laplace transform of one is</span> <span
  m='2124000'>one over s. You mean all that mess from</span> <span m='2130000'>this
  simple-looking function? This function is not so simple.</span> </p><p><span m='2134000'>What
  is its graph? What is it we are calculating</span> <span m='2138000'>the Laplace
  transform of? Well, it is the function t</span> <span m='2142000'>squared. But multiplying
  it by that</span> <span m='2145000'>factor u of t minus one means that the only
  part of</span> <span m='2150000'>it I am using is this part, because u of t minus
  one is one</span> <span m='2155000'>when t is bigger than one.</span> </p><p><span
  m='2160000'>But when t is less than one it is zero.</span> </p><p><span m='2162000'>That
  function doesn't look all that simple to me.</span> </p><p><span m='2165000'>And
  that is why its Laplace transform has three terms in it</span> <span m='2169000'>with
  this exponential factor. Well, it is a discontinuous</span> <span m='2173000'>function.
  And it gets discontinuous at a</span> <span m='2176000'>very peculiar spot. You
  have to expect that.</span> </p><p><span m='2179000'>Where in this does it tell
  you it becomes discontinuous at one?</span> </p><p><span m='2183000'>It is because
  this is e to the minus one times s.</span> </p><p><span m='2189000'>This tells you
  where the discontinuity occurs.</span> </p><p><span m='2192000'>The rest of it is
  just stuff you have to take because it is</span> <span m='2197000'>the function
  t squared. It's what it is.</span> </p><p><span m='2201000'>All right. I think most
  of you are going</span> <span m='2204000'>to encounter the worst troubles when you
  try to calculate</span> <span m='2209000'>inverse Laplace transforms, so let me
  try to explain how</span> <span m='2213000'>that is done. I will give you a simple</span>
  <span m='2216000'>example first. And then I will try to give you</span> <span m='2221000'>a
  slightly more complicated one. But even the simple one won't</span> <span m='2226000'>make
  your head ache. We are going to calculate the</span> <span m='2231000'>inverse Laplace
  transform of this guy, one plus e to the</span> <span m='2236000'>negative pi s
  --</span> <span m='2244000'>-- divided by s squared plus one.</span> </p><p><span
  m='2255000'>All right. Now, the first thing you must</span> <span m='2257000'>do
  is as soon as you see exponential factors in there</span> <span m='2260000'>like
  that you know that these functions, the answer is going</span> <span m='2264000'>to
  be a discontinuous function. And you have got to separate</span> <span m='2268000'>out
  the different pieces of it that go with the different</span> <span m='2272000'>exponentials.
  Because the way the formula</span> <span m='2274000'>works, it has to be used differently
  for each value of a.</span> </p><p><span m='2279000'>Now, in this case, there is
  only one value of a</span> <span m='2282000'>that occurs. Negative pi.</span> </p><p><span
  m='2283000'>But it does mean that we are going to have to begin by</span> <span
  m='2287000'>separating out the thing into one over s squared plus one</span> <span
  m='2291000'>and this other factor e to the negative pi s</span> <span m='2295000'>divided
  by s squared plus one.</span> </p><p><span m='2299000'>Now all I have to do is take
  the inverse Laplace transform of</span> <span m='2303000'>each piece. The inverse
  Laplace transform</span> <span m='2306000'>of one over s squared plus one is --</span>
  <span m='2312000'>Well, up to now we have been saying its sine t,</span> <span m='2316000'>right?
  If you say it is sine t you are</span> <span m='2318000'>going to get into trouble.
  How come?</span> </p><p><span m='2321000'>We didn't get into trouble before.</span>
  </p><p><span m='2323000'>Yes, but that was because there were no exponentials in
  the</span> <span m='2327000'>expression. When there are exponentials you</span>
  <span m='2330000'>have to be more careful. Make the inverse transform</span> <span
  m='2334000'>unique. Make it not sine t,</span> <span m='2336000'>but u of t sine
  t.</span> </p><p><span m='2340000'>You will see why in just a moment.</span> </p><p><span
  m='2342000'>If this weren't there then sine t would be perfectly okay.</span> </p><p><span
  m='2347000'>With that factor there, you have got to put in the u of</span> <span
  m='2351000'>t, otherwise you won't be able to get the formula to</span> <span m='2356000'>work
  right. In other words,</span> <span m='2358000'>I must use this particular one that
  I picked out to make it</span> <span m='2363000'>unique at the beginning of the
  period.</span> </p><p><span m='2366000'>Otherwise, it just won't work. Now, I know
  that is fine.</span> </p><p><span m='2371000'>But now what is the inverse Laplace
  transform of e to the</span> <span m='2375000'>minus pi? In other words,</span>
  <span m='2378000'>it is the same function, except I am now multiplying it</span>
  <span m='2381000'>by e to the negative pi s.</span> </p><p><span m='2384000'>Well,
  now I will use that formula.</span> </p><p><span m='2386000'>My f of s is one over
  s squared plus one,</span> <span m='2390000'>and that corresponds it to sine t.</span>
  </p><p><span m='2394000'>If I multiply it by e to the minus pi s,</span> <span m='2397000'>just
  copy it down. It now corresponds,</span> <span m='2402000'>the inverse Laplace transform,
  to what the left side says it</span> <span m='2408000'>does. u of t minus pi</span>
  <span m='2412000'>times, in other words, this corresponds to that.</span> </p><p><span
  m='2417000'>Then if I multiply it by e to the minus pi s,</span> <span m='2423000'>it
  corresponds to change the t to t minus pi.</span> </p><p><span m='2438000'>What
  is the answer? The answer is you sum these two</span> <span m='2443000'>pieces.
  The first piece is u of time</span> <span m='2447000'>sine t. The second piece is
  u of t</span> <span m='2453000'>minus pi sine t of minus pi.</span> </p><p><span
  m='2460000'>Now, if you leave the answer in that form it is technically</span> <span
  m='2465000'>correct, but you are going to lose a lot of credit.</span> </p><p><span
  m='2469000'>You have to transform it to make it look good.</span> </p><p><span m='2473000'>You
  have to make it intelligible.</span> </p><p><span m='2476000'>You are not allowed
  to leave it in that form.</span> </p><p><span m='2480000'>What could we do to it?
  Well, you see,</span> <span m='2484000'>this part of it is interesting whenever
  t is positive.</span> </p><p><span m='2490000'>This part of it is only interesting
  when t is greater</span> <span m='2494000'>than or equal to pi because this is zero.</span>
  </p><p><span m='2497000'>Before that this is zero. What you have to do is make</span>
  <span m='2501000'>cases. Let's call the answer f of t.</span> </p><p><span m='2504000'>The
  function has to be</span> <span m='2507000'>presented in what is called the cases
  format.</span> </p><p><span m='2510000'>That is what it is called when you type
  in tech,</span> <span m='2514000'>which I think a certain number of you can do anyway.</span>
  </p><p><span m='2520000'>You have to make cases. The first case is what happened</span>
  <span m='2524000'>between zero and pi? Well, between zero and pi,</span> <span m='2528000'>only
  this term is operational. The other one is zero because</span> <span m='2532000'>of
  that factor. Therefore, between zero and pi</span> <span m='2536000'>the function
  looks like, now, I don't have to put in the</span> <span m='2541000'>u of t because
  that is equal to one.</span> </p><p><span m='2544000'>It is equal to sine t between
  zero and pi.</span> </p><p><span m='2550000'>What is it equal to bigger than pi?</span>
  </p><p><span m='2552000'>Well, the first factor, the first term still obtains,</span>
  <span m='2556000'>so I have to include that. But now I have to add the</span> <span
  m='2560000'>second one. Well, what is the second term?</span> </p><p><span m='2563000'>I
  don't include the t minus pi, u of t minus pi</span> <span m='2568000'>anymore because
  that is now one.</span> </p><p><span m='2571000'>That has the value one. It is sine
  of t minus pi.</span> </p><p><span m='2575000'>But what is sine of t minus pi?</span>
  </p><p><span m='2580000'>You take the sine curve and you translate it to the right
  by pi.</span> </p><p><span m='2587000'>So what happens to it? It turns into this
  curve.</span> </p><p><span m='2593000'>In other words, it turns into the curve,</span>
  <span m='2598000'>what curve is that? Minus sine t.</span> </p><p><span m='2610000'>The
  other factor, this factor is one and this</span> <span m='2613000'>becomes negative
  sine t.</span> </p><p><span m='2622000'>And so the final answer is f of t is equal
  to sine t</span> <span m='2630000'>between zero and pi and zero for t greater than
  or equal</span> <span m='2638000'>to pi. That is the right form of the</span> <span
  m='2643000'>answer.</span> </p>
type: course
uid: 717edb6734efeac2e8c4c65cdefaac6c

---
None