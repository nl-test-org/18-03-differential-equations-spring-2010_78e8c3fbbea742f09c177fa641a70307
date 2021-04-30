---
about_this_resource_text: '<p><strong>Topics covered: </strong>Use with Impulse Inputs;
  Dirac Delta Function, Weight and Transfer Functions</p><p><strong>Instructor/speaker:
  </strong>Prof. Arthur Mattuck</p>'
course_id: 18-03-differential-equations-spring-2010
embedded_media:
- id: 23.jpg
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  technical_location: https://ocw.mit.edu/courses/mathematics/18-03-differential-equations-spring-2010/video-lectures/lecture-23-use-with-impulse-inputs/23.jpg
  title: 23.jpg
  type: null
  uid: 4520dd4f9bc94888181fdf233ea5a46d
- id: Video-YouTube-Stream
  media_location: peYvLk_HZdw
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  title: Video-YouTube-Stream
  type: Video
  uid: 5bebe3e9f6b62cae81394ec9e9ba002b
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/peYvLk_HZdw/default.jpg
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 3f7f8fed7f959d95a599cbdf7a0d6945
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id354869128
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  title: Video-iTunes U-MP4
  type: Video
  uid: 8b7a5ec12ef3462c12fcc587217a78d6
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.03S06/mit-ocw-18.03-lec23-11apr2003-220k.mp4
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  title: Video-Internet Archive-MP4
  type: Video
  uid: 99315c08af47ec77495ba30068dfe38e
- id: Video-VideoLecturesnet-Stream
  media_location: http://videolectures.net/mit1803s06_differential_equations/
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  title: Video-VideoLectures.net-Stream
  type: Video
  uid: dd319be72514cc8c291caed15f0daa33
- id: Thumbnail-OCW-JPG
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 4ab976299dcfa6edcaadf87abe7c6de8
- id: 3Play-3PlayYouTubeid-MP4
  media_location: peYvLk_HZdw
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 31c9a958bfaf09cf1afc5edc0db75ece
- id: peYvLk_HZdw.srt
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  technical_location: https://ocw.mit.edu/courses/mathematics/18-03-differential-equations-spring-2010/video-lectures/lecture-23-use-with-impulse-inputs/peYvLk_HZdw.srt
  title: 3play caption file
  type: null
  uid: 59487e86a325027f9326256e4614d77c
- id: peYvLk_HZdw.pdf
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  technical_location: https://ocw.mit.edu/courses/mathematics/18-03-differential-equations-spring-2010/video-lectures/lecture-23-use-with-impulse-inputs/peYvLk_HZdw.pdf
  title: 3play pdf file
  type: null
  uid: ae64dba85f10e3696fa3fc525b3030c4
- id: Caption-3Play YouTube id-SRT
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 1efd8df175d9cd0378a1d856cee1ebd9
- id: Transcript-3Play YouTube id-PDF
  parent_uid: cb532e18c85761f13db38b74b7cec1bd
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 0e384fc8c5bdc8ae39937766571437ae
inline_embed_id: 22466244lecture23:usewithimpulseinputs44927702
layout: video
order_index: null
parent_uid: 1555305200815ae857fb572ef6d294a3
related_resources_text: ''
short_url: lecture-23-use-with-impulse-inputs
technical_location: https://ocw.mit.edu/courses/mathematics/18-03-differential-equations-spring-2010/video-lectures/lecture-23-use-with-impulse-inputs
template_type: Tabbed
title: 'Lecture 23: Use with Impulse Inputs'
transcript: <p><span m='8000'>Well, today is the last day on Laplace transform and
  the first</span> <span m='12000'>day before we start the rest of the term, which
  will be spent on</span> <span m='16000'>the study of systems. I would like to spend
  it on one</span> <span m='20000'>more type of input function which, in general,</span>
  <span m='23000'>your teachers in other courses will expect you to have had some</span>
  <span m='28000'>acquaintance with. It is the kind associated with</span> <span m='32000'>an
  impulse, so an input consisted of what is sometimes</span> <span m='36000'>called
  a unit impulse. Now, what's an impulse?</span> </p><p><span m='40000'>It covers
  actually a lot of things.</span> </p><p><span m='43000'>It covers a situation where
  you withdraw from a bank account.</span> </p><p><span m='48000'>For example, take
  half your money out of a</span> <span m='52000'>bank account one day. It also would
  be modeled the</span> <span m='56000'>same way. But the simplest way to</span> <span
  m='59000'>understand it the first time through is as an impulse,</span> <span m='63000'>if
  you know what an impulse is. If you have a variable force</span> <span m='68000'>acting
  over time, and we will assume it is acting</span> <span m='72000'>along a straight
  line so I don't have to worry about it being a</span> <span m='77000'>vector, then
  the impulse, according to physicists,</span> <span m='80000'>the physical definition,
  the impulse of f of t</span> <span m='85000'>over some time interval. Let's say
  the time interval</span> <span m='90000'>running from a to b is, by definition,</span>
  <span m='93000'>the integral from a to b of f of t dt.</span> </p><p><span m='98000'>Actually,
  I am going to do the</span> <span m='102000'>most horrible thing this period. I
  will assume the force is</span> <span m='106000'>actually a constant force. So,
  in that case,</span> <span m='110000'>I wouldn't even have to bother with the integral
  at all.</span> </p><p><span m='115000'>If f of t is a constant, let's say capital
  F,</span> <span m='118000'>then the impulse is -- Well, that integral is simply</span>
  <span m='124000'>the product of the two, the impulse over that time</span> <span
  m='128000'>interval is simply F times b minus a.</span> </p><p><span m='132000'>Just
  the product of those two. The force times the length of</span> <span m='137000'>time
  for which it acts. Now, that is what I want to</span> <span m='141000'>calculate,
  want to consider in connection with our little mass</span> <span m='146000'>system.
  So, once again,</span> <span m='149000'>I think this is probably the last time you'll
  see the little</span> <span m='154000'>spring. Let's bid a tearful farewell to</span>
  <span m='157000'>it. There is our little mass on</span> <span m='159000'>wheels.
  And let's make it an undamped</span> <span m='162000'>mass. It has an equilibrium
  point and</span> <span m='165000'>all the other little things that go with the picture.</span>
  </p><p><span m='169000'>And when I apply an impulse, what I mean is applying a</span>
  <span m='174000'>constant force to this over a definite time interval.</span> </p><p><span
  m='180000'>And that is what I mean by applying an impulse over that</span> <span
  m='183000'>time interval. Now, what is the picture of</span> <span m='186000'>such
  a thing? Well, the force is only going</span> <span m='189000'>to be applied, in
  other words,</span> <span m='191000'>I am going to push on the mass or pull on the
  mass with a</span> <span m='195000'>constant force. With a little electromagnet</span>
  <span m='198000'>here, we will assume, there is a pile of iron filings</span> <span
  m='202000'>or something inside there. I turn on the electromagnet.</span> </p><p><span
  m='206000'>It pulls with a constant force just between time zero and time</span>
  <span m='210000'>two seconds. And then I stop.</span> </p><p><span m='214000'>That
  is going to change the motion of the thing.</span> </p><p><span m='217000'>First
  it is going to start pulling it toward the thing.</span> </p><p><span m='220000'>And
  then, when it lets go, it will zoom back and there</span> <span m='224000'>will
  be a certain motion after that.</span> </p><p><span m='226000'>What the question
  is, if I want to solve that problem</span> <span m='229000'>of the motion of that
  in terms of the Laplace transform,</span> <span m='233000'>how am I going to model
  this force?</span> </p><p><span m='235000'>Well, let's draw a picture of it first.</span>
  </p><p><span m='239000'>It starts here. It is zero for t,</span> <span m='242000'>let's
  say the force is applied between time zero to time h.</span> </p><p><span m='248000'>And
  then its force is turned on, it stays constant and then</span> <span m='254000'>it
  is turned off. And those vertical lines</span> <span m='258000'>shouldn't be there.
  But, since in practice,</span> <span m='263000'>it takes a tiny bit of time to turn
  a force on and off.</span> </p><p><span m='270000'>It is, in practice, not unrealistic
  to suppose that</span> <span m='274000'>there are approximately vertical lines there.</span>
  </p><p><span m='278000'>They are slightly slanted but not too much.</span> </p><p><span
  m='281000'>Now, I want it to be unit impulse.</span> </p><p><span m='284000'>This
  is the force access and this is the time access.</span> </p><p><span m='289000'>Since
  the impulse is the area under this curve,</span> <span m='293000'>if I want that
  to be one, then if this is h,</span> <span m='296000'>the height to which I -- In
  other words,</span> <span m='301000'>the magnitude of the force must be one over
  h in order</span> <span m='305000'>that the area be one, in order, in other words,</span>
  <span m='309000'>that this integral be one, the area under that curve be</span>
  <span m='313000'>one. So the unit impulse looks like</span> <span m='315000'>that.
  The narrower it is here,</span> <span m='317000'>the higher it has to be that way.</span>
  </p><p><span m='320000'>The bigger the force must be if you want the end result
  to be a</span> <span m='324000'>unit impulse. Now, to solve a problem,</span> <span
  m='327000'>a typical problem, then, would be a spring.</span> </p><p><span m='332000'>The
  mass is traveling on the track.</span> </p><p><span m='334000'>Let's suppose the
  spring constant is one,</span> <span m='338000'>so there would be a differential
  equation.</span> </p><p><span m='341000'>And the right-hand side would be this f
  of t.</span> </p><p><span m='345000'>Well, let's give it its name, the name I gave
  it before.</span> </p><p><span m='349000'>Remember, I called the unit box function
  the thing which was one</span> <span m='355000'>between zero and h and zero everywhere
  else.</span> </p><p><span m='360000'>The notation we used for that was u, and then
  it had a double</span> <span m='364000'>subscript from the starting point and the
  finishing point.</span> </p><p><span m='367000'>So oh-- u(oh) of t.</span> </p><p><span
  m='370000'>This much represents the thing if it only rose to the high one.</span>
  </p><p><span m='374000'>But if it, instead, rises to the height one over h</span>
  <span m='377000'>in order to make that area one, I have to multiply it</span> <span
  m='381000'>by the factor one over h. Now, if you want to solve this</span> <span
  m='385000'>by the Laplace transform. In other words,</span> <span m='388000'>see
  what the motion of that mass is as I apply this unit</span> <span m='392000'>impulse
  to it over that time interval.</span> </p><p><span m='394000'>You have to take the
  Laplace transform, if that is the way we</span> <span m='398000'>are doing it. Now,
  the left-hand side is just</span> <span m='401000'>routine and would involve the
  initial conditions.</span> </p><p><span m='404000'>The whole interest is taking
  the Laplace transform of the</span> <span m='408000'>right-hand side. And that is
  what I want to do</span> <span m='411000'>now. The problem is what is the</span>
  <span m='412000'>Laplace transform of this guy?</span> </p><p><span m='422000'>Well,
  remember, to do everything else,</span> <span m='424000'>you do everything by writing
  in terms of the unit step function?</span> </p><p><span m='428000'>This function
  that we are talking about is one over h</span> <span m='432000'>times what you get
  by first stepping up to one.</span> </p><p><span m='436000'>That is the unit step
  function, which goes up by one and tries</span> <span m='440000'>to stay at one
  ever after. And then, when it gets to h,</span> <span m='444000'>it has got to step
  down. Well, the way you make it step</span> <span m='447000'>down is by subtracting
  off the function, which is the unit step</span> <span m='451000'>function but where
  the step takes place, not at time zero</span> <span m='455000'>but at time h. In
  other words,</span> <span m='458000'>I translate the unit step function of course
  with,</span> <span m='462000'>I don't think I have to draw that picture again.</span>
  </p><p><span m='465000'>The unit step function looks like zing.</span> </p><p><span
  m='467000'>And if you translate it to the right by h it looks like zing.</span>
  </p><p><span m='471000'>And then make it negative to subtract it off.</span> </p><p><span
  m='474000'>And what you will get is this box function.</span> </p><p><span m='476000'>So
  we want to take the Laplace transform of this thing.</span> </p><p><span m='481000'>Well,
  let's assume, for the sake of argument that</span> <span m='485000'>you didn't remember.
  Well, you had to use the</span> <span m='488000'>formula at 2:00 AM this morning
  and, therefore,</span> <span m='492000'>you do remember it. [LAUGHTER] So I don't
  have to</span> <span m='496000'>recopy the formula onto the board.</span> </p><p><span
  m='499000'>Maybe if there is room there. All right, let's put it up</span> <span
  m='504000'>there. It says that u of t minus a</span> <span m='506000'>times f, any
  f, so let's call it g so</span> <span m='511000'>you won't confuse it with this
  particular one,</span> <span m='514000'>times g translated. If you translate a function</span>
  <span m='519000'>from t, if you translate it to the right by a then its Laplace</span>
  <span m='524000'>transform is e to the minus a s times whatever the</span> <span
  m='528000'>old Laplace transform was, g of s.</span> </p><p><span m='531000'>Multiply
  by an exponential on the right.</span> </p><p><span m='534000'>On the left that
  corresponds to translation.</span> </p><p><span m='538000'>Except you must remember
  to put in that factor u for a secret</span> <span m='542000'>reason which I spent
  half of Wednesday explaining.</span> </p><p><span m='545000'>What do we have here?
  The Laplace transform of u of t,</span> <span m='549000'>that is easy. That is simply
  one over s.</span> </p><p><span m='553000'>The Laplace transform of this</span>
  <span m='555000'>other guy we get from the formula.</span> </p><p><span m='557000'>It
  is basically one over s. No, the Laplace transform of u</span> <span m='561000'>of
  t. But because it has been</span> <span m='564000'>translated to the right by h,
  I have to multiply it by that</span> <span m='568000'>factor e to the minus h times
  s.</span> </p><p><span m='578000'>That is the answer. And, if you want to solve</span>
  <span m='580000'>problems, this is what you would feed into the equation.</span>
  </p><p><span m='584000'>And you would calculate and calculate and calculate it.</span>
  </p><p><span m='587000'>But that is not what I want to do now because that was</span>
  <span m='591000'>Wednesday and this is Friday. You have the right to expect</span>
  <span m='595000'>something new. Here is what I am going to do</span> <span m='597000'>new.
  I am going to let h go to zero.</span> </p><p><span m='601000'>As h goes to zero,
  this function gets narrower and</span> <span m='606000'>narrower, but it also has
  to get higher and higher because its</span> <span m='612000'>area has to stay one.
  What I am interested in,</span> <span m='616000'>first of all, is what happens to
  the Laplace</span> <span m='620000'>transform as h goes to zero. In other words,</span>
  <span m='625000'>what is the limit, as h goes to zero of --</span> <span m='630000'>Well,
  what is that function? One minus e to the negative hs</span> <span m='634000'>divided
  by hs.</span> </p><p><span m='637000'>Well, this is an 18.01 problem, an ordinary
  calculus problem,</span> <span m='642000'>but let's do it nicely. You see, the nice
  way to do it</span> <span m='646000'>is to make a substitution. We will change h
  s to u</span> <span m='650000'>because it is occurring as a unit in both cases.</span>
  </p><p><span m='655000'>This is going to be the same as the limit as u goes to zero.</span>
  </p><p><span m='660000'>I think there are too many u's</span> <span m='664000'>here
  already. I cannot use u,</span> <span m='667000'>you cannot use t, v is velocity,</span>
  <span m='670000'>w is wavefunction. There is no letter.</span> </p><p><span m='673000'>All
  right, u. It is one minus e to the</span> <span m='677000'>negative u over u.</span>
  </p><p><span m='680000'>So what is the answer? Well, either you know the</span>
  <span m='685000'>answer or you replace this by, say, the first couple of terms</span>
  <span m='690000'>of the Taylor series. But I think most of you would</span> <span
  m='695000'>use L'Hopital's rule, so let's do that.</span> </p><p><span m='698000'>The
  derivative of the top is zero here.</span> </p><p><span m='700000'>The derivative
  by the chain rule of e to the negative u is e</span> <span m='704000'>to the negative
  u times minus one.</span> </p><p><span m='707000'>And that minus one cancels that
  minus.</span> </p><p><span m='709000'>So the derivative of the top is simply e to
  the negative u and</span> <span m='713000'>the derivative of the bottom is one.</span>
  </p><p><span m='715000'>So, as u goes to zero, that limit is one.</span> </p><p><span
  m='720000'>Interesting. Let's draw a picture this way.</span> </p><p><span m='723000'>I
  will draw it schematically. Up here is the function one</span> <span m='728000'>over
  h times u zero h of t, our box function,</span> <span m='734000'>except it has the
  height one over h instead of the</span> <span m='739000'>height one. We have just
  calculated that</span> <span m='743000'>its Laplace transform is that funny thing,
  one minus e to the</span> <span m='748000'>minus hs divided by hs.</span> </p><p><span
  m='754000'>That is the top line. All this is completely kosher,</span> <span m='759000'>but
  now I am going to let h go to zero.</span> </p><p><span m='763000'>And the question
  is what do we get now?</span> </p><p><span m='767000'>Well, I just calculated for
  you that this thing approaches one,</span> <span m='773000'>has the limit one. And
  now, let's fill in the</span> <span m='778000'>picture. What does this thing approach?</span>
  </p><p><span m='783000'>Well, it approaches a function which is zero everywhere.</span>
  </p><p><span m='790000'>As h approaches zero, this green box turns into a box</span>
  <span m='797000'>which is zero everywhere except at zero.</span> </p><p><span m='802000'>And
  there, it is infinitely high.</span> </p><p><span m='806000'>So, keep going up.</span>
  </p><p><span m='815000'>Now, of course, that is not a function.</span> </p><p><span
  m='818000'>People call it a function but it isn't.</span> </p><p><span m='821000'>Mathematicians
  call it a generalized function,</span> <span m='825000'>but that is not a function
  either.</span> </p><p><span m='828000'>It is just a way of making you feel comfortable
  by talking</span> <span m='833000'>about something which isn't really a function.</span>
  </p><p><span m='836000'>It was given the name, introduced formally into</span> <span
  m='840000'>mathematics by a physicist, Dirac.</span> </p><p><span m='845000'>And
  he, looking ahead to the future, did what many people do</span> <span m='849000'>who
  introduce something into the literature, a formula or a</span> <span m='853000'>function
  or something which they think is going to be important.</span> </p><p><span m='857000'>They
  never name it directly after themselves,</span> <span m='860000'>but they always
  use as the symbol for it the first letter</span> <span m='864000'>of their name.
  I cannot tell you how often</span> <span m='866000'>that has happened. Maybe even
  Euler called e for</span> <span m='871000'>that reason, although he claims it was
  in Latin because it has</span> <span m='877000'>to do with exponentials. Well, luckily
  his name began</span> <span m='882000'>with an E, too. That is Paul Dirac's delta</span>
  <span m='885000'>function. I won't dignify it by the name</span> <span m='889000'>function
  by writing that out, by putting the world function</span> <span m='894000'>here,
  too, but it is called the delta function.</span> </p><p><span m='900000'>From this
  point on, the entire rest of the lecture</span> <span m='903000'>has a slight fictional
  element. The entire rest of the lecture</span> <span m='908000'>is in figurative
  quotation marks, so you are not entirely</span> <span m='912000'>responsible for
  anything I say. This is a non-function,</span> <span m='916000'>but you put it in
  there and call it a function.</span> </p><p><span m='919000'>And you naturally want
  to complete, if it's a function</span> <span m='923000'>then it must have a Laplace
  transform, even though it</span> <span m='927000'>doesn't, so the diagram is completed
  that way.</span> </p><p><span m='932000'>And its Laplace transform is declared to
  be one.</span> </p><p><span m='935000'>So let's start listing the properties of
  this weird thing.</span> </p><p><span m='954000'>The delta function, its Laplace
  transform is one.</span> </p><p><span m='965000'>Now, one of the things is we have
  not yet expressed the fact</span> <span m='969000'>that it is a unit impulse. In
  other words,</span> <span m='973000'>since the areas of all of these boxes, they
  all have areas one</span> <span m='977000'>as they are shrunk this way they get
  higher that way.</span> </p><p><span m='982000'>By convention, one says that the
  area under</span> <span m='985000'>the orange curve also remains one in the limit.</span>
  </p><p><span m='990000'>Now, how am I going to express that?</span> </p><p><span
  m='992000'>Well, it is done by the following formula that the</span> <span m='995000'>integral,
  the total impulse of the delta function should be</span> <span m='999000'>one. Now,
  where do I integrate?</span> </p><p><span m='1001000'>Well, from any place that
  it is zero to any place that it is</span> <span m='1005000'>zero on the other side
  of that vertical line.</span> </p><p><span m='1008000'>But, in order to avoid controversy,
  people integrate</span> <span m='1012000'>all the way from negative infinity to
  infinity since it</span> <span m='1015000'>doesn't hurt. Does it?</span> </p><p><span
  m='1017000'>It is zero practically all the time.</span> </p><p><span m='1021000'>This
  is the function whose Laplace transform is one.</span> </p><p><span m='1026000'>Its
  integral from minus infinity to infinity is one.</span> </p><p><span m='1031000'>How
  else can we calculate for it?</span> </p><p><span m='1035000'>Well, I would like
  to calculate its convolution.</span> </p><p><span m='1040000'>Here is f of t. What
  happens if I convolute it</span> <span m='1046000'>with the delta function? Well,
  if you go back to the</span> <span m='1051000'>definition of the convolution, you
  know, it is that funny</span> <span m='1055000'>integral, you are going to do a
  lot of head scratching because</span> <span m='1060000'>it is not really all that
  clear how to integrate with the delta</span> <span m='1064000'>function. Instead
  of doing that let's</span> <span m='1066000'>assume that it follows the laws of
  the Laplace transform.</span> </p><p><span m='1070000'>In that case, its Laplace
  transform would be</span> <span m='1073000'>what? Well, the whole thing of a</span>
  <span m='1075000'>convolution is that the Laplace transform of the convolution is</span>
  <span m='1080000'>the product of the two separate Laplace transforms.</span> </p><p><span
  m='1085000'>So that is going to be F of s times the Laplace</span> <span m='1089000'>transform
  of the delta function, which is one.</span> </p><p><span m='1093000'>Now, what must
  this thing be? Well, there is some ambiguity</span> <span m='1098000'>as to what
  it is for negative values of t.</span> </p><p><span m='1101000'>But if we, by brute
  force, decide for negative values of t</span> <span m='1106000'>it is going to have
  the value zero, that is the way we make</span> <span m='1111000'>things unique.
  In fact, why don't we make f of</span> <span m='1115000'>unique that way to start
  with?</span> </p><p><span m='1118000'>This is a function now that is allowed to
  do anything it wants</span> <span m='1121000'>on the right-hand side of zero starting
  at zero,</span> <span m='1124000'>but on the left-hand side of zero it is wiped
  away and must</span> <span m='1128000'>be zero. This is a definite thing now.</span>
  </p><p><span m='1130000'>Its convolution is this. And the inverse Laplace</span>
  <span m='1133000'>transform is -- The answer, in other words,</span> <span m='1137000'>is
  the same thing as what u of t f of t would be.</span> </p><p><span m='1142000'>It's
  the same thing, F of s.</span> </p><p><span m='1144000'>And so, the conclusion is
  that these are equal,</span> <span m='1148000'>since they must be unique. They have
  been made unique by</span> <span m='1152000'>making them zero for t negative. In
  other words,</span> <span m='1156000'>apply to a function, well, I won't recopy
  it.</span> </p><p><span m='1159000'>But the point is that delta t, for the convolution
  operation,</span> <span m='1164000'>is acting like an identity. If I multiply,</span>
  <span m='1169000'>in the sense of convolution, it is a peculiar operation.</span>
  </p><p><span m='1173000'>But algebraically, it has a lot of the properties</span>
  <span m='1176000'>of multiplication. It is communitive.</span> </p><p><span m='1179000'>It
  is linear in both factors. In other words,</span> <span m='1182000'>it is almost
  anything you would want with multiplication.</span> </p><p><span m='1186000'>It
  has an identity element, identity function.</span> </p><p><span m='1189000'>And
  the identity function is the Dirac delta function.</span> </p><p><span m='1193000'>Anything
  else here? Yeah, I will throw in one more</span> <span m='1197000'>thing. It would
  just require one more</span> <span m='1201000'>phony argument, which I won't bother
  giving</span> <span m='1204000'>you, but it is not totally implausible.</span> </p><p><span
  m='1206000'>After all, u of t, the unit step function is not</span> <span m='1211000'>differentiable,
  is not a differentiable</span> <span m='1213000'>function. It looks like this.</span>
  </p><p><span m='1215000'>Here its derivative is zero, here its derivative is zero,</span>
  <span m='1219000'>and in this class it is not even defined in between.</span> </p><p><span
  m='1223000'>But, I don't care, I will make it go straight up.</span> </p><p><span
  m='1227000'>The question is what's its derivative?</span> </p><p><span m='1231000'>Well,
  zero here, zero there and infinity at</span> <span m='1234000'>zero, so it must
  be the delta function.</span> </p><p><span m='1237000'>That has exactly the right
  properties.</span> </p><p><span m='1240000'>So the same people who will tell you
  this will tell you that</span> <span m='1244000'>also. And, in fact,</span> <span
  m='1245000'>when you use it to solve differential equations it acts</span> <span
  m='1250000'>as if that is true. I think I have given you an</span> <span m='1253000'>example
  on your homework. Let me now show you a typical</span> <span m='1257000'>example
  of the way the Dirac delta function would be used to</span> <span m='1262000'>solve
  a problem. Let's go back to our little</span> <span m='1266000'>spring, since it
  is the easiest thing.</span> </p><p><span m='1269000'>You are familiar with it from
  a physical point of view,</span> <span m='1273000'>and it is the easiest thing to
  illustrate on.</span> </p><p><span m='1276000'>We have our spring mass system. Where
  is it?</span> </p><p><span m='1280000'>Is it on the board? Up there.</span> </p><p><span
  m='1282000'>That one. And the differential equation</span> <span m='1285000'>we
  are going to solve is y double prime plus y</span> <span m='1289000'>equals -- And
  now, I am going to assume</span> <span m='1293000'>that the spring is kicked with
  impulse a.</span> </p><p><span m='1297000'>I am not going to kick it at time t equals
  zero,</span> <span m='1302000'>since that would get us into slight technical difficulties.</span>
  </p><p><span m='1307000'>Anyway, it is more fun to kick it at time pi over two.</span>
  </p><p><span m='1312000'>The thing is,</span> <span m='1314000'>what is happening?
  Well, we have got to have</span> <span m='1318000'>initial conditions. The initial
  conditions are</span> <span m='1322000'>going to be, let's start at time zero.</span>
  </p><p><span m='1325000'>We will start it at the position one.</span> </p><p><span
  m='1328000'>So I take my spring, I drag it to the position one,</span> <span m='1331000'>I
  take the little mass there and then let it go.</span> </p><p><span m='1335000'>And
  so it starts going birr. But right when it gets to the</span> <span m='1339000'>equilibrium
  point I give it a, "cha!" with unit impulse.</span> </p><p><span m='1343000'>I started
  it from rest. Those will be the initial</span> <span m='1347000'>conditions. And
  I want to say that I kicked</span> <span m='1351000'>it, not with unit impulse,
  but with the impulse a.</span> </p><p><span m='1355000'>Bigger. And I did that at
  time pi over</span> <span m='1358000'>two. So how are we going to say</span> <span
  m='1361000'>that? Well, kick it means delivered</span> <span m='1363000'>that impulse
  over an extremely short time interval,</span> <span m='1367000'>but in such a way
  kicked it sufficiently hard that the total</span> <span m='1372000'>impulse was
  a. The way to say that is kick it</span> <span m='1376000'>with the Dirac delta
  function. Translate it to the point time</span> <span m='1382000'>pi over two. Not
  at zero any longer.</span> </p><p><span m='1386000'>t minus pi over two.</span>
  </p><p><span m='1389000'>But that would kick it with a unit impulse.</span> </p><p><span
  m='1392000'>I want it to kick it with the impulse a, so I will just</span> <span
  m='1396000'>multiply that by the constant factor a.</span> </p><p><span m='1400000'>Let's
  put this over here. y of zero equals one,</span> <span m='1404000'>that's the starting
  value. Now we have a problem.</span> </p><p><span m='1410000'>The only thing new
  in solving this with the Laplace transform</span> <span m='1413000'>is I have this
  funny right-hand side.</span> </p><p><span m='1416000'>But it corresponds to a physical
  situation.</span> </p><p><span m='1418000'>Let's do it. You take the Laplace transform</span>
  <span m='1421000'>of both sides of the equation. Remember how to do that?</span>
  </p><p><span m='1424000'>You have to take account of the initial conditions.</span>
  </p><p><span m='1428000'>The Laplace transform of the second derivative is you</span>
  <span m='1431000'>multiply by s squared, and then you have to subtract.</span> </p><p><span
  m='1435000'>You have to use these initial conditions.</span> </p><p><span m='1439000'>This
  one won't give you anything, but the first one</span> <span m='1442000'>means I
  have to subtract one times s.</span> </p><p><span m='1445000'>That is the Laplace
  transform of y double prime.</span> </p><p><span m='1449000'>The Laplace transform
  of y, of course, is just capital Y.</span> </p><p><span m='1453000'>And how about
  the Laplace</span> <span m='1456000'>transform of the right-hand side.</span> </p><p><span
  m='1458000'>Well, we will have the constant factor a because the Laplace</span>
  <span m='1462000'>transform is linear. And now, the delta function</span> <span
  m='1465000'>would have the transform one. But when I translate it,</span> <span
  m='1470000'>pi over two, that means I have to use that</span> <span m='1473000'>formula.
  Translate it by pi over two</span> <span m='1475000'>means take the one that it
  would have been otherwise and multiply</span> <span m='1480000'>it by e, that exponential
  factor.</span> </p><p><span m='1482000'>It would be e to the minus pi over two,</span>
  <span m='1486000'>that is the A times s times one, which would be the g of s,</span>
  <span m='1489000'>the Laplace transform or the delta function before it</span> <span
  m='1494000'>had been translated. But I don't have to put that in</span> <span m='1497000'>because
  it's one. I am multiplying by one.</span> </p><p><span m='1501000'>And to do everything
  now is routine.</span> </p><p><span m='1503000'>Solve for the Laplace transform.</span>
  </p><p><span m='1505000'>Well, what is it? It is y is equal to.</span> </p><p><span
  m='1508000'>I put the s on the other side. That makes the right-hand side</span>
  <span m='1512000'>the sum of two terms. And I divide by the coefficient</span> <span
  m='1515000'>of y, which is s squared plus one.</span> </p><p><span m='1518000'>The
  s is over on the right-hand side and it is divided by s</span> <span m='1522000'>squared
  plus one. And the other factor is there,</span> <span m='1525000'>too. And it, too,</span>
  <span m='1526000'>is divided by s squared plus one.</span> </p><p><span m='1535000'>Now,
  we take the inverse Laplace transform of those two</span> <span m='1538000'>terms
  and add them up.</span> </p><p><span m='1560000'>What will we get? Well, y is equal
  to,</span> <span m='1562000'>the inverse Laplace transform of s over s squared plus
  one is</span> <span m='1567000'>cosine t.</span> </p><p><span m='1571000'>Now, for
  this thing we will have to use our formula.</span> </p><p><span m='1575000'>If this
  weren't here, the inverse Laplace transform</span> <span m='1579000'>of a over s
  squared plus one would</span> <span m='1584000'>be what? Well, it would be a times
  the</span> <span m='1587000'>sine of t.</span> </p><p><span m='1595000'>In other
  words, if this is the g of s</span> <span m='1597000'>then the function on the left
  would be basically A sine t.</span> </p><p><span m='1601000'>But because it has
  been</span> <span m='1603000'>multiplied by that exponential factor, e to the minus
  as</span> <span m='1607000'>where a is pi over two,</span> <span m='1610000'>the
  left-hand side has to be changed from A sine t</span> <span m='1613000'>to what
  it would be with the translated form.</span> </p><p><span m='1618000'>So the rest
  of it is u of t minus pi over two,</span> <span m='1621000'>because a is pi over
  two, times what it would have</span> <span m='1625000'>been just from the factor
  g of s itself.</span> </p><p><span m='1629000'>In other words, A times the sine
  of,</span> <span m='1631000'>again, t minus pi over two.</span> </p><p><span m='1635000'>I
  am applying that formula, but I am applying it in that</span> <span m='1639000'>direction.
  I started with this,</span> <span m='1641000'>and I want to recover the left-hand
  side.</span> </p><p><span m='1644000'>And that is what it must look like.</span>
  </p><p><span m='1646000'>The A, of course, just gets dragged along for the</span>
  <span m='1649000'>free ride. Now, as I emphasized to you</span> <span m='1654000'>last
  time, and I hope you did on your homework that you handed</span> <span m='1658000'>in,
  you mustn't leave it in that form.</span> </p><p><span m='1661000'>You have to make
  cases because people will expect you to tell</span> <span m='1666000'>them what
  the meaning of this is.</span> </p><p><span m='1669000'>Now, if t is less than pi
  over two, this is zero.</span> </p><p><span m='1672000'>And, therefore, that term
  does not exist.</span> </p><p><span m='1676000'>So the first part of it is just
  the cosine t term if</span> <span m='1680000'>t lies between zero and pi over two.</span>
  </p><p><span m='1685000'>If t is bigger than pi over two then this factor is</span>
  <span m='1690000'>one. It's the unit step function.</span> </p><p><span m='1692000'>And
  I, therefore, must add in this term.</span> </p><p><span m='1696000'>Now, what is
  that term? What is the sine of t minus pi</span> <span m='1700000'>over two? The
  sine of t looks</span> <span m='1705000'>like that. The sine of t,</span> <span
  m='1707000'>if I translate it, looks like this.</span> </p><p><span m='1711000'>If
  I translate it by pi over two.</span> </p><p><span m='1713000'>And let's finish
  it up, the pi that was over here moved</span> <span m='1718000'>into position. That
  curve is the curve</span> <span m='1721000'>negative cosine t.</span> </p><p><span
  m='1731000'>And so the answer is if t is bigger than pi over two,</span> <span m='1735000'>it
  is cosine t minus A times cosine t.</span> </p><p><span m='1740000'>Or, in other
  words,</span> <span m='1742000'>it is one minus A times cosine t.</span> </p><p><span
  m='1751000'>Now, do those match up? They have always got to match</span> <span m='1753000'>up,
  or you have made a mistake. You always have to get a</span> <span m='1757000'>continuous
  function when you have just discontinuities.</span> </p><p><span m='1760000'>Do
  we get a continuous function?</span> </p><p><span m='1762000'>Yeah, when t is pi
  over two the value here is</span> <span m='1765000'>zero. The value of this is also
  zero</span> <span m='1767000'>at pi over two. There is no conflict in the</span>
  <span m='1771000'>values. Values doesn't suddenly jump.</span> </p><p><span m='1773000'>The
  function is continuous. It is not differential but it</span> <span m='1778000'>is
  continuous. Well, what function does that</span> <span m='1781000'>look like? There
  are cases.</span> </p><p><span m='1783000'>It starts out life as the function cosine
  t.</span> </p><p><span m='1787000'>So it gets to here. And at t equals pi over two,</span>
  <span m='1791000'>the mass gets kicked and that changes the function.</span> </p><p><span
  m='1795000'>Now, what are the values? Well, if A is bigger than one</span> <span
  m='1801000'>this is a negative number and it therefore becomes</span> <span m='1807000'>the
  function negative cosine t.</span> </p><p><span m='1811000'>Now, negative cosine
  t looks like this, the blue guy.</span> </p><p><span m='1816000'>Negative cosine
  t is a function that looks like this.</span> </p><p><span m='1821000'>So it goes
  from here, it reverses direction,</span> <span m='1826000'>the mass reverses direction
  from what you thought it was</span> <span m='1831000'>going to do. And it does that
  because A is</span> <span m='1836000'>so large that that impulse was enough to make
  it reverse</span> <span m='1840000'>direction. Of course it might only do</span>
  <span m='1842000'>this, but this is what will happen if A is bigger than one.</span>
  </p><p><span m='1847000'>This will be A, which is a lot bigger than one.</span>
  </p><p><span m='1850000'>If it's not so much bigger than one it might look like
  that.</span> </p><p><span m='1855000'>So A is just bigger than one. How's that?</span>
  </p><p><span m='1859000'>Well, what if A is less than one?</span> </p><p><span m='1861000'>Well,
  in that case it stays positive.</span> </p><p><span m='1864000'>If A is less than
  one, this is now still a positive</span> <span m='1867000'>number. And, therefore,</span>
  <span m='1869000'>the cosine continues on its merry way.</span> </p><p><span m='1872000'>The
  only thing is it might be a little more sluggish or it might</span> <span m='1877000'>be
  very peppy and do that. Let's just go that far.</span> </p><p><span m='1880000'>This
  will be the case A less than one.</span> </p><p><span m='1883000'>Well, of course,
  the most interesting case is</span> <span m='1886000'>what happens if A is exactly
  equal to one?</span> </p><p><span m='1892000'>The porridge is exactly just right,
  I think that's the</span> <span m='1897000'>phrase. Too hot.</span> </p><p><span
  m='1898000'>Too cold. Just right.</span> </p><p><span m='1900000'>When A is equal
  to one, it is zero.</span> </p><p><span m='1904000'>It starts out as cosine t.</span>
  </p><p><span m='1908000'>When it gets to t, it continues on ever after as</span>
  <span m='1912000'>the function zero. I have a visual aid for the</span> <span m='1917000'>only
  time this term. It didn't work at all.</span> </p><p><span m='1922000'>I mean, on
  the other hand, the last hour,</span> <span m='1926000'>the people who worked it
  were not intrinsically baseball</span> <span m='1931000'>players, so we will use
  the equation of the pendulum</span> <span m='1935000'>instead. That is a lot easier
  than mass</span> <span m='1938000'>spring. This is a pendulum.</span> </p><p><span
  m='1940000'>It is undamped because I declare it to be and it swings</span> <span
  m='1945000'>back and forth. And here I am releasing it.</span> </p><p><span m='1950000'>The
  variable is not x or y but theta, the angle through.</span> </p><p><span m='1954000'>Here
  theta is one, let's say.</span> </p><p><span m='1957000'>That's about one radian.
  It starts there and swings back</span> <span m='1961000'>and forth. It is not damped,</span>
  <span m='1964000'>so it never loses amplitude, particularly if I swish it,</span>
  <span m='1968000'>if I move my hand a little bit. I want someone who knows how to</span>
  <span m='1973000'>bat a baseball. That was the problem last hour.</span> </p><p><span
  m='1977000'>Two people. One to release it.</span> </p><p><span m='1981000'>I will
  stand up and try to hold it here.</span> </p><p><span m='1984000'>Somebody releases
  it. And then somebody who has to be</span> <span m='1988000'>very skillful should
  apply a unit impulse of exactly one when</span> <span m='1993000'>it gets to the
  equilibrium point.</span> </p><p><span m='1996000'>So who can do that? Who can play
  baseball here?</span> </p><p><span m='2000000'>Come on. Somebody elected?</span>
  </p><p><span m='2010000'>All right. Come on. [APPLAUSE]</span> <span m='2021000'>Somebody
  release it, too.</span> </p><p><span m='2024000'>Somebody tall to handle it all.
  I think that will be me.</span> </p><p><span m='2032000'>Just hold it at what you
  would take to be one radian.</span> </p><p><span m='2040000'>He releases it. When
  it gets to the bottom,</span> <span m='2044000'>you will have to get way down, and
  maybe on this side.</span> </p><p><span m='2051000'>Are you a lefty or a righty?
  Rightly.</span> </p><p><span m='2055000'>Okay. Bat it what part.</span> </p><p><span
  m='2057000'>Give it a good swat. I will stand up higher.</span> </p><p><span m='2062000'>Help.
  I'm not very stable.</span> </p><p><span m='2065000'>[APPLAUSE] A trial run. Again.</span>
  </p><p><span m='2070000'>Okay. A little further out.</span> </p><p><span m='2072000'>First
  of all, you have to see where it's</span> <span m='2076000'>going. Why don't you
  stand,</span> <span m='2078000'>oh, you bat rightly. That's right.</span> </p><p><span
  m='2081000'>Okay. Let's try it again.</span> </p><p></p><p><span m='2099000'>Strike
  one. It's okay. It's the beginning of the baseball season. One more. The Red Sox
  are having trouble, too. Not bad. [APPLAUSE]</span> <span m='2113000'>If he had
  hit even harder it would have reversed direction</span> <span m='2116000'>and gone
  that way. If you hadn't hit it quite as</span> <span m='2120000'>hard it would have
  continued on, still at cosine t,</span> <span m='2124000'>but with less amplitude.
  But if you hit it exactly right</span> <span m='2128000'>-- It is fun to try to
  do.</span> </p><p><span m='2131000'>Toomre in our department is a master at this,</span>
  <span m='2136000'>but he has been practicing for years.</span> </p><p><span m='2140000'>He
  can take a little mallet and go blunk, and it stops</span> <span m='2145000'>absolutely
  dead. It is unbelievable.</span> </p><p><span m='2149000'>I should have had him
  give the lecture.</span> </p><p><span m='2153000'>Now, I would like to do something
  truly serious.</span> </p><p><span m='2160000'>Here, I guess. Because there is a
  certain</span> <span m='2163000'>amount of engineering lingo you have to learn.</span>
  </p><p><span m='2167000'>It is used by almost everybody. Not architects and biologists</span>
  <span m='2172000'>probably quite yet, but anybody that uses the</span> <span m='2176000'>Laplace
  transform will use these words in connection with it.</span> </p><p><span m='2181000'>I
  really think, since it is such a widespread</span> <span m='2185000'>technique,
  that these are things you should know.</span> </p><p><span m='2191000'>Anyway, it
  will be easy. It is just the enrichment of</span> <span m='2194000'>your vocabulary.
  It is always fun to learn new</span> <span m='2197000'>vocabulary words. So, let's
  just consider a</span> <span m='2200000'>general second order equation. By the way,
  all this applies to</span> <span m='2205000'>higher order equations, too.</span>
  </p><p><span m='2207000'>It applies to systems. The same words are used,</span>
  <span m='2210000'>but let's use something that you know.</span> </p><p><span m='2212000'>Here
  is a system. It could be a spring mass</span> <span m='2215000'>dashpot system.
  It could be an RLC circuit.</span> </p><p><span m='2220000'>Or that pendulum, a
  damped pendulum,</span> <span m='2222000'>anything that is modeled by that differential
  equation with</span> <span m='2226000'>constant coefficients, second-order.</span>
  </p><p><span m='2228000'>This is the input. The input can be any kind of a</span>
  <span m='2231000'>function. Exponential functions,</span> <span m='2233000'>sine,
  cosine. It could be a Dirac delta</span> <span m='2236000'>function. It could be
  a sum of these</span> <span m='2238000'>things. It could be a Fourier series.</span>
  </p><p><span m='2241000'>Anything of the sort of stuff we have been talking about</span>
  <span m='2244000'>throughout the last few weeks. And let's have simple initial</span>
  <span m='2250000'>conditions so that doesn't louse things up, the simplest possible</span>
  <span m='2254000'>ones. The mass starts at the</span> <span m='2256000'>equilibrium
  point from rest. Of course, it doesn't stay that</span> <span m='2260000'>way because
  there is an input that is asking it to move along.</span> </p><p><span m='2265000'>Now
  all I want to do is solve this in general with a Laplace</span> <span m='2269000'>transform.
  If I do it in general,</span> <span m='2271000'>that is always easier than doing
  it in particular since you</span> <span m='2276000'>don't ever have to do any calculations.</span>
  </p><p><span m='2280000'>It is s squared Y. There are no other terms here</span>
  <span m='2285000'>because the initial conditions are zero.</span> </p><p><span m='2288000'>This
  part will be a times s Y.</span> </p><p><span m='2292000'>Again, no other terms
  because the initial conditions are zero.</span> </p><p><span m='2297000'>Plus b
  times Y. And all that is equal to</span> <span m='2301000'>whatever the Laplace
  transform is of the right-hand side.</span> </p><p><span m='2306000'>So it is F
  of s. Next step.</span> </p><p><span m='2311000'>Boy, this is an easy problem. You
  solve for Y.</span> </p><p><span m='2315000'>Well, Y is F of s times one over s
  squared plus as plus b.</span> </p><p><span m='2325000'>Now, what is that? The next
  step now is to figure</span> <span m='2330000'>out what the answer to the problem
  is, what's the Y of t?</span> </p><p><span m='2335000'>Well, you do that by taking
  the</span> <span m='2340000'>inverse Laplace transform. But because these are general</span>
  <span m='2344000'>functions, I don't have to write down any specific answer.</span>
  </p><p><span m='2349000'>The only thing is to use the convolution because this is
  the</span> <span m='2353000'>product of two functions of s. The inverse transform
  will be</span> <span m='2358000'>the convolution of their respective things.</span>
  </p><p><span m='2361000'>The answer is going to be the convolution of F of t,</span>
  <span m='2366000'>the input function in other words, convoluted with the</span>
  <span m='2370000'>inverse Laplace transform of that thing.</span> </p><p><span m='2375000'>Now,
  we have to have a name for that, and those are the two</span> <span m='2379000'>words
  I want to introduce you to because they are used</span> <span m='2383000'>everywhere.
  The function,</span> <span m='2384000'>on the right-hand side, this function one
  over s</span> <span m='2388000'>squared plus as plus b,</span> <span m='2391000'>notice
  it only depends upon the left-hand side of the</span> <span m='2395000'>differential
  equation, on the damping constant.</span> </p><p><span m='2400000'>The spring constant
  if you are thinking of a mass spring</span> <span m='2403000'>dashpot system. So
  this depends only on the</span> <span m='2406000'>system, not on what input is going
  into it.</span> </p><p><span m='2408000'>And it is called the transfer function.</span>
  </p><p><span m='2411000'>Is usually called capital W of, sometimes it is</span>
  <span m='2415000'>capital H of s, there are different things,</span> <span m='2418000'>but
  it is always called the transfer function.</span> </p><p><span m='2427000'>What
  we are interested in putting here its inverse Laplace</span> <span m='2431000'>transform.
  Well, I will call that W of t</span> <span m='2434000'>to go with the capital W
  of s by the usual</span> <span m='2439000'>notation. Its inverse Laplace transform,</span>
  <span m='2442000'>well, I cannot calculate that. I will just give it a name,</span>
  <span m='2446000'>W of t. And that is called the weight</span> <span m='2449000'>function
  of the system. This is the transfer function</span> <span m='2453000'>of the system,
  so put in "of the system" if</span> <span m='2457000'>you are taking notes. And
  so the answer is that</span> <span m='2462000'>always the solution is the convolution
  to this differential</span> <span m='2466000'>equation that we have been solving
  for the last three or</span> <span m='2471000'>four weeks. It is the convolution
  of that.</span> </p><p><span m='2474000'>And, therefore, the solution is expressed
  as a</span> <span m='2478000'>definite integral of the function of the input on
  the</span> <span m='2482000'>right-hand side, what is forcing the equation,</span>
  <span m='2486000'>times this magic function but flipped and translated by t.</span>
  </p><p><span m='2492000'>That says du for you guys over there.</span> </p><p><span
  m='2494000'>In other words, the solution to the</span> <span m='2497000'>differential
  equation is presented as a definite</span> <span m='2501000'>integral. Marvelous.</span>
  </p><p><span m='2502000'>And the only thing is the definite integral involves this</span>
  <span m='2507000'>funny function W of t. To understand why that is the</span> <span
  m='2512000'>solution, you have to understand what W of t is.</span> </p><p><span
  m='2515000'>Well, formally, of course, it's that.</span> </p><p><span m='2520000'>But
  what does it really mean? The problem is what is W of t</span> <span m='2525000'>really?
  Not just formally,</span> <span m='2528000'>but what does it really mean? I mean,
  is it real?</span> </p><p><span m='2532000'>I think the simplest way of thinking
  of it,</span> <span m='2536000'>once you know about the delta function is just to
  think of</span> <span m='2541000'>this differential equation y double prime plus
  a y prime plus</span> <span m='2547000'>b. Except use as the input the</span> <span
  m='2552000'>Dirac delta function. In other words,</span> <span m='2555000'>we are
  kicking the mass. The mass starts at rest,</span> <span m='2559000'>so the initial
  conditions are going to be what they were</span> <span m='2563000'>before. y of
  zero,</span> <span m='2566000'>y prime of zero. Both zero.</span> </p><p><span m='2569000'>The
  mass starts at rest from the equilibrium position,</span> <span m='2573000'>and
  it is kicked in the positive direction,</span> <span m='2577000'>I guess that's
  this way, with unit impulse.</span> </p><p><span m='2582000'>At time zero with unit
  impulse. In other words,</span> <span m='2585000'>kick it just hard enough so you
  impart a unit impulse.</span> </p><p><span m='2590000'>So that situation is modeled
  by this differential equation.</span> </p><p><span m='2595000'>The kick at time
  zero is modeled by this input,</span> <span m='2599000'>the Dirac delta function.
  And now, what happens if I</span> <span m='2603000'>solve it? Well, you see,</span>
  <span m='2605000'>everything in the solution is the same.</span> </p><p><span m='2610000'>The
  left stays the same, but on the right-hand side I</span> <span m='2614000'>should
  have not f of s here.</span> </p><p><span m='2617000'>Since this is the delta function,
  I should have one.</span> </p><p><span m='2622000'>What I get is, on the left-hand
  side,</span> <span m='2625000'>s squared Y plus as Y plus bY equals,</span> <span
  m='2630000'>for the Laplace transform of the right-hand side is simply</span> <span
  m='2636000'>one. And, therefore,</span> <span m='2637000'>Y is what? Y is one over
  exactly the</span> <span m='2642000'>transform function. And therefore its inverse</span>
  <span m='2645000'>Laplace transform is that weight function.</span> </p><p><span
  m='2649000'>That is the simplest interpretation I know of what</span> <span m='2653000'>this
  magic weight function is, which gives the solution to all</span> <span m='2658000'>the
  differential equations, no matter what the input is.</span> </p><p><span m='2663000'>The
  weight function is the response of the system at rest</span> <span m='2667000'>to
  a sharp kick at time zero with unit impulse.</span> </p><p><span m='2673000'>And
  read the notes because they will explain to you why this</span> <span m='2677000'>could
  be thought of as the superposition of a lot of sharp</span> <span m='2682000'>kicks
  times zero a little later. Kick, kick, kick,</span> <span m='2686000'>kick. And
  that's what makes the</span> <span m='2689000'>solution. Next time we start systems.</span>
  </p>
type: course
uid: cb532e18c85761f13db38b74b7cec1bd

---
None