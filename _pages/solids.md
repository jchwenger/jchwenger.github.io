---  
layout: single  
title: Solids (NSFW)  
date: 2016-10-31 18:04:18.000000000 +0000
permalink: /solids/  
wiki:
  - img_path: "/assets/solids/wiki/Tetrahedron.gif" 
    alt: "Tetrahedron"
    title: "Tetrahedron"
    excerpt: "(Fire)"
    img_url: "https://en.wikipedia.org/wiki/Tetrahedron" 
  - img_path: "/assets/solids/wiki/Hexahedron.gif" 
    alt: "Hexahedron"
    title: "Hexahedron"
    excerpt: "(Earth)"
    img_url: "https://en.wikipedia.org/wiki/Cube" 
  - img_path: "/assets/solids/wiki/Octahedron.gif" 
    alt: "Octahedron"
    title: "Octahedron"
    excerpt: "(Air)" 
    img_url: "https://en.wikipedia.org/wiki/Octahedron" 
  - img_path: "/assets/solids/wiki/Dodecahedron.gif"  
    alt: "Dodecahedron"
    title: "Dodecahedron"
    excerpt: "Aether"
    txt_url: "https://en.wikipedia.org/wiki/Aether_classical_element"
    img_url: "https://en.wikipedia.org/wiki/Dodecahedron"
  - img_path: "/assets/solids/wiki/Icosahedron.gif" 
    alt: "Icosahedron"
    title: "Icosahedron"
    excerpt: "(Water)"
    img_url: "https://en.wikipedia.org/wiki/Icosahedron" 
---

*Solids* is a project developed in collaboration with composer [Remmy Canedo](https://vimeo.com/remmycanedo). This page is dedicated to retracing my thought process and keeping record of the various stages of production.

{% include separators.html type='outer' %}

### Texts

      [spheres](/assets/solids/texts/spheres.pdf)  
      [tetrahedra](/assets/solids/texts/tetrahedra.pdf)  
      [hexahedra](/assets/solids/texts/hexahedra.pdf)  
      [octahedra](/assets/solids/texts/octahedra.pdf)  
      [dodecahedra](/assets/solids/texts/dodecahedra.pdf)  
      [icosahedra](/assets/solids/texts/icosahedra.pdf)

{% include separators.html type='outer' %}

### Summary for submissions

*Solids* is an encounter bewteen [Remmy Canedo](https://vimeo.com/remmycanedo)’s music and my own texts, combining Plato’s cosmological thought in the *[Timaeus](https://plato.stanford.edu/entries/plato-timaeus/)* and an enquiry of extreme behaviour in human sexuality.

Having as its starting point an axiomatic conflagration of Plato’s cosmological philosophy (in the *Timaeus*) and the array and extremes of human desire (the most easily accessible forms of which being internet shock videos involving extreme sexuality and violence, which were one of the source of inspiration for the piece), *Solids* is an attempt to draw a bridge between the apparent chaos of human perversion and on of the most fundamental philosophical texts from the tradition aiming at finding a method for deciphering the world through the lens of mathematical structures.

<div class="wiki">
  {% for image in page.wiki %}
  <div>
    <div>
      <a href="{{ image.img_url }}">
        <img src="{{ image.img_path }}">
      </a>
    </div>
    <div>
      <p>{{ image.title }}</p>
      {% if image.txt_url %}
      <p>(<a href="{{ image.txt_url }}">{{ image.excerpt }}</a>)</p>
      {% else %}
      <p>{{ image.excerpt }}</p>
      {% endif %}
    </div>
  </div>
  {% endfor %} 
</div>

Plato’s method of classifying the fundamental elements of the world (fire, air, water, earth and aether, which he inherits from earlier Presocratic figures) using mathematical solids (tetrahedron or pyramid, hexahedron or cube, octahedron, dodecahedron, icosahedron) is used in the same manner, as a structural prism through which it is possible not only to apprehend various sexual perversions (sex addiction, scatophilia, zoophilia, rape, sometimes leading to mutilation or murder, etc.) as material, but also providing a formal framework out of which it is possible to ultimately turn them into literary texts. The last element, [aether](https://en.wikipedia.org/wiki/Aether_(classical_element)), is only fleetingly mentioned in Plato, and becomes more prominent in Aristotle as the supreme element containing the fixed heavenly/divine stars. We take it here as the element associated with this peculiar figure which is no solid but nevertheless plays a defining role in Plato’s cosmology: the sphere.

Thus, the various solids offer a constraint not only at a thematic level (“if one were to classify perversions into five categories, which ones would these be?”), but also at a literary level (“how can writing be developed in five different ways to accomodate each perversion?”, or “given that a particular perversion has as its figure a solid with twelve faces, what are the consequences for texts written about it, if it is to be projected on such a figure?”, “What quotes or allusions from the literary and art canon can be integrated?”).


The first step was to assign each peversion to a solid, which resulted in the following:  
 - sphere: the totality, the world, art as a whole;  
 - tetrahedron (fire): Eros, raw energy often leading to violence and killing;  
 - hexahedron (earth): Thanatos, the death drive;  
 - octahedron (air): obsession, intensity, sex addiction;  
 - dodecahedron (aether): echoes back the sphere, art, science, discovery and creation;  
 - icosahedron (water): perversion, zoophilia, scatophilia.  

 Each solid led to a thought and creation process to adapt and transform the material at hand so that it could fit the specific geometric form (given the number of faces per figure, and the number of edges per face).

The final work will be a combination of three elements:  
 - a set of texts exploring various sides of sexual perversions, using the Platonic framework of thinking;  
 - one or several pieces with video and music created in collaboration with Remmy Canedo, where the texts will be integrated on moving figures of solids projected in 3D;  
 - the creation of a website that allows for further reading and archiving (in a similar vein as [e-x-p-l-o-s-u-r-e](http://e-x-p-l-o-s-u-r-e.tumblr.com/) and [p-r-e-e-x-p-l-o-s-u-r-e](http://p-r-e-e-x-p-l-o-s-u-r-e.tumblr.com/)).

{% include separators.html type='outer' %}

### Computational future

Among various forays into the possibilities at hand using Plato’s framework, one came up that is particularly suited for computerization: starting with a rather simple premise, that given a general ‘theme’ specific to each solid, it possible to have one relevant word on each face. A tetrahedron is then a set of four words, a hexahedron, a set of six, etc. This is already sufficient a level of constraint for an attempt: how to find the best four, or six, words, that create a poetic and powerful set? However, two constraints may be added to that which could then, given the sheer difficulty of finding appropriate sets, give computational search power a good enough *raison d’être*: first, one may restrict the number of letters of each word to the number of faces of the solid, to increase coherence (four-lettered words for the tetrahedron, etc.); second, one could create a true letter puzzle by requiring that each letter be associated with an edge, and that the ‘other side’ of the edge, on the adjacent face, have the same letter attached to it. In the latter option, the gradual covering up of each face with a word would add letter constraints to the other faces, leading to the last face being entirely determined when all the others are complete. If one wishes the word set to be non-random, and, ideally, interesting, on a literary level, and given that it is almost impossible to execute this task in any way but empirically (starting with one word on one face, then going for a second face, each time checking that the letter constraint is being respected), the most efficient scenario would be to have a computer program produce possibilities generated from a comprehensive word list (e.g. the OED) and the rules and then among them separate the wheat from the chaff.

{% include separators.html type='outer' %}

### Two remarks

**The ‘[Mendeleev](https://en.wikipedia.org/wiki/Periodic_table) effect’**

(A scientific thing: also occurring in the [Standard Model](https://en.wikipedia.org/wiki/Standard_Model).)

Through observation of the world and experiments scientists manage to construct abstract descriptive models.

The interesting after-effect occurs when the model reveals empty spots: elements or phenomena that should have been observed and haven’t yet.

The presence of the model in the mind of researchers acts retroactively on observation: they search for the missing planet ([Neptune calculated by Le Verrier](https://en.wikipedia.org/wiki/Urbain_Le_Verrier#Discovery_of_Neptune)), elements on Mendeleev’s table (and gradually discover them), the [Higgs boson](https://en.wikipedia.org/wiki/Higgs_boson) (and find it).

We started with four filthy videos (2 girl 1 cup; 1 guy 1 jar; 1 guy 1 horse; 3 guys 1 hammer). We need to extract *something* from them, a system, categories. Make those strong enough so they can guide our gaze toward finding what we did’t see, and didn’t even realise was missing.

{% include separators.html type='inner' %}

In Plato’s *Timaeus* the Demiurge creates the soul of the world, and then devolves creative powers to the gods he brough into existence, which in turn create mortals. As the soul of the world is itself a copy of something more eternal and uncreated, it is probably arguable that humans are then at least copies of copies, if not worse (the copies of the copies (gods) of the copy (soul of the world?) of the prime essence). In short, worse than works of art.

{% include separators.html type='outer' %}

### Web material (shock videos)

**[1 Guy 1 Jar](http://knowyourmeme.com/memes/1-guy-1-jar)**

1 Guy 1 Jar, also known as “1 Guy 1 Cup,” is a shock site featuring a video of a nude Russian man who sits on a glass jar which enters his rectum and breaks inside of him. Many YouTubers uploaded videos of themselves reacting to the footage, in a similar vein to the 2 Girls 1 Cup and 3 Guys 1 Hammer reaction videos.

{% include separators.html type='inner' %}

**[2 Girls 1 Cup](http://knowyourmeme.com/memes/2-girls-1-cup)**

The phrase, “2 Girls 1 Cup,” refers to the trailer for the Brazilian fetish film *Hungry Bitches* made by MFX Media in 2007. The extreme fetishistic nature of the clip as well as the dramatic piano music playing in the background caused it to go viral in late 2007, with many internet users posting their own or others’ reactions to seeing the video for the first time. This phenomenon received significant attention from the media.

As a result, 2girls1cup.com, hosting the most viewed mirror of the trailer, would become one of the most famous shock sites in internet history. The name, “2 Girls 1 Cup” has also been subject to parody, exemplified in shock sites such as 3Guys1Hammer.

{% include separators.html type='inner' %}

**[2 Guys 1 Horse / Mr. Hands](http://knowyourmeme.com/memes/2-guys-1-horse-mr-hands),  [The Enumclaw horse sex case ](https://en.wikipedia.org/wiki/Enumclaw_horse_sex_case)**

2 Guys 1 Horse is a shock video that shows a man actually having anal sex with a horse. The man in the video, named Kenneth Pinyan, later nicknamed as Mr. Hands, soon died after the act due to a perforated colon.

The Enumclaw horse sex case was a 2005 incident in which Kenneth Pinyan (June 22, 1960 – July 2, 2005), an American Boeing engineer residing in Gig Harbor, Washington, died from injuries received during receptive rectal sex with a stallion at a farm in an unincorporated area in King County, Washington, near the city of Enumclaw. Pinyan distributed zoophile porn under the alias Mr. Hands.

During a July 2005 sex act, videotaped by a friend, Pinyan suffered a perforated colon from receptive anal intercourse with a stallion and later died of his injuries. The story was reported in *The Seattle Times* and was one of that paper’s most read stories of 2005. It was informally referred to as the “Enumclaw horse sex case”. Video footage of Pinyan and a horse was later disseminated through the Internet.

Pinyan’s death rapidly prompted the passing of a bill in Washington prohibiting both sex with animals and the videotaping of the same. Under current Washington law, bestiality is now a Class C felony punishable by up to five years in prison.

A documentary of the life and death of Pinyan, and the life led by those who came to the farm near Enumclaw, debuted at the Sundance Film Festival 2007 under the title *Zoo*. It was one of 16 winners out of 856 candidates for the festival, and played at numerous regional festivals in the United States thereafter. Following Sundance, it was also selected as one of the top five American films to be presented at the prestigious Directors Fortnight sidebar at the 2007 Cannes Film Festival.

{% include separators.html type='inner' %}

**[3 Guys 1 Hammer](http://knowyourmeme.com/memes/3-guys-1-hammer), [The Dnepropetrovsk maniacs](https://en.wikipedia.org/wiki/Dnepropetrovsk_maniacs)**

3 Guys 1 Hammer is a viral shock video involving three young adults murdering a middle-aged man they held captive by primarily bludgeoning his face with a hammer. The title is a pun on another infamous shock video: 2 Girls 1 Cup.

The perpetrators in the video have been dubbed as the Dnepropetrovsk maniacs. The trio are serial killers who are guilty of at least 20 murders. Run the Gauntlet, a shock site that gets progressively gorier as the user chooses, is the first link to appear when searched on Google. Although the video in Run the Gauntlet is watermarked to the gore news site, Best Gore.

The victim in this video was identified as Sergei Yatzenko, a 48 year old male who had recently been forced into retirement due to a cancerous tumor in his throat.

The Dnepropetrovsk maniacs (Ukrainian: Дніпропетровські маніяки, Russian: Днепропетровские маньяки) are Ukrainian serial killers responsible for a string of murders in Dnipropetrovsk in June and July 2007. The case gained additional notoriety because the killers made video recordings of some of the murders, with one of the videos leaking to the Internet. Two 19‑year-old locals, Viktor Sayenko (Ukrainian: Віктор Саєнко, Russian: Виктор Саенко) and Igor Suprunyuk (Ukrainian: Ігор Супрунюк, Russian: Игорь Супрунюк), were arrested and charged with 21 murders.

A third conspirator, Alexander Hanzha (Ukrainian: Олександр Ганжа, Russian: Александр Ганжа) was charged with two armed robberies that took place before the murder spree. On 11 February 2009, all three defendants were found guilty. Suprunyuk and Sayenko were sentenced to life imprisonment, while Hanzha received nine years in prison. The lawyers for Suprunyuk and Sayenko launched an appeal, which was dismissed by the Supreme Court of Ukraine in November 2009.

{% include separators.html type='inner' %}

**[Water Hell (Bakki Visual Planning)](https://www.reddit.com/r/NoFap/comments/1369hu/pornographers_give_opinion_on_women_in_the/) [(Japanese Wiki page)](https://www.reddit.com/r/NoFap/comments/1369hu/pornographers_give_opinion_on_women_in_the/)**

The company is known as Bakky Visual and from 2004 to 2007 “Bakki Visual Planning” published a series of 17 pornographic movies in which they filmed encounters in which porn stars and amateur performers were only told they were to be appearing in a normal gravure or pornographic movie.

In fact they were dragged off and gang raped by the studio’s staff (and friends/relatives of staff), all of which was filmed and sold openly online.

Victims were variously drugged and forced to drink themselves into unconsciousness, and confined, beaten and subjected to various forms of torture (including one scene where a victim is almost thrown off a building), which in one case led to a potentially fatal rectal injury.

The producers apparently managed to cow their victims into believing they had signed a contract which made all this legal, and it was only when filming of the 17th and final movie collapsed with their victim managing to call police in to rescue her that authorities bothered to investigate.

After the usual scandal, police eventually brought a case against the company which saw most of the unrepentant perpetrators handed rape sentences ranging from 18 years in the case of the CEO to suspended sentences in the case of some of the performers whose only crime was to rape a porn star.

Although the company responsible has stopped selling the videos, it is still doing business under a different name. Several of the men who escaped charges continue to appear in pornographic films.

### Additional web material

      [Brutal Gangrape In the Van Japanese Rape Fantasy](http://www.hurtsex.com/video/brutal-gangrape-in-the-van-japanese-rape-fantasy)  (NSFW)  
      [Japanese zoophiliac pornography](http://www.intporn.com/forums/kinky-fetish-videos/3306564-sex-octopuses-worms-maggots-eels-sea-cucumbers.html)  (NSFW)  
      [Vice documentary on the above](http://www.dailymotion.com/video/x6yec3) (and [article](https://www.vice.com/en_us/article/7bke3x/genki-and-the-art-of-eel-porn), both NSFW)  
      [Other article on Japanese zoophiliac pornography](http://www.tokyokinky.com/the-weirdest-strangest-japanese-hentai-porn/) (NSFW)

{% include separators.html type='outer' %}

### Artistic and literary sources (selection)

**[Catullus 16](http://rudy.negenborn.net/catullus/text2/e16.htm)**  **([original Latin](http://rudy.negenborn.net/catullus/text2/l16.htm))**

I’ll push your shit in and stuff your face  
Aurelius, you cocksucker; Furius, you little bitch  
since you think that my little poems  
have gone soft and I must not be too upright!  
It’s true; the devoted poet should stand erect  
in his values, but not necessarily in his little  
poems, which are truly witty and charming  
when they’re a little soft, and not too stiff,  
but can still cause a little tingling  
I don’t just mean for youth, but for hairy men  
who can’t make their own loins stand upright!  
You! You read about my “many kisses”  
and doubt I’m fully a man?  
I’ll push your shit in and stuff your face.

{% include separators.html type='inner' %}

**[Hokusai](https://en.wikipedia.org/wiki/Hokusai), [*The Dream of the Fisherman’s Wife, 1814*](https://en.wikipedia.org/wiki/The_Dream_of_the_Fisherman's_Wife)**

![Hokusai](/assets/solids/images/Hokusai.jpg){: .align-center}

{% include separators.html type='inner' %}

**[Kunisada](https://en.wikipedia.org/wiki/Kunisada), [*Woman and Dog, 日本春宫册页《女人和狗》, 1837*](https://zh.wikipedia.org/wiki/File:%E6%97%A5%E6%9C%AC%E6%98%A5%E5%AE%AB%E5%86%8C%E9%A1%B5%E3%80%8A%E5%A5%B3%E4%BA%BA%E5%92%8C%E7%8B%97%E3%80%8B.jpg)**

![Kunisada](/assets/solids/images/Kunisada.jpg){: .align-center}

{% include separators.html type='inner' %}

**[W. B. Yeats](https://en.wikipedia.org/wiki/W._B._Yeats), ‘[Leda and the Swan](https://en.wikipedia.org/wiki/Leda_and_the_Swan)’**

A sudden blow: the great wings beating still  
Above the staggering girl, her thighs caressed  
By the dark webs, her nape caught in his bill,  
He holds her helpless breast upon his breast.

How can those terrified vague fingers push  
The feathered glory from her loosening thighs?  
And how can body, laid in that white rush,  
But feel the strange heart beating where it lies?

A shudder in the loins engenders there  
The broken wall, the burning roof and tower  
And Agamemnon dead.  
                                        Being so caught up,  
So mastered by the brute blood of the air,  
Did she put on his knowledge with his power  
Before the indifferent beak could let her drop?

{% include separators.html type='inner' %}

**[*Leda and the Swan*, 16th-century copy after a lost painting by Michelangelo](http://www.nationalgalleryimages.co.uk/Imagedetails.aspx?q=NG1868&ng=NG1868&frm=1)**

![Leda](/assets/solids/images/Leda-swan.jpg){: .align-center}

{% include separators.html type='inner' %}

**[Maurizio Cattelan, ‘untitled’, 2007](https://www.perrotin.com/artists/Maurizio_Cattelan/2/untitled/12880)**

![Cattelan](/assets/solids/images/Cattelan.jpg){: .align-center}

{% include separators.html type='inner' %}

**[Makoto Aida, b. 1965, retrospective at the Mori Art Museum, 2012](http://www.mori.art.museum/english/contents/aidamakoto_main/)**

![Makoto Aida](/assets/solids/images/Makoto-Aida.jpg){: .align-center}



