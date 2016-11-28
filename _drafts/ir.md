---
layout: page
title: Interesting Reads
---

Articles I've blogged about:

{% for post in site.posts %}
  {% for tag in post.tags %}
    {% if tag == 'ia' %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
    {% endif %}
  {% endfor %}
{% endfor %}

Articles I've enjoyed (long list - those in bold are **highly** recommended):

  * **Ingenious: Scott Aaronson** - From computational complexity to quantum mechanics. [[link]](http://nautil.us/issue/21/information/ingenious-scott-aaronson)
  * **The Man Who Tried to Redeem the World with Logic**: Walter Pitts rose from the streets to MIT, but couldn’t escape himself. [[link]](http://nautil.us/issue/21/information/the-man-who-tried-to-redeem-the-world-with-logic)
  * **The Quantum Mechanics of Fate**: How time travel might explain some of science’s biggest puzzles. [[link]](http://nautil.us/issue/21/information/the-quantum-mechanics-of-fate-rp)
  * What Problems to Solve - By Richard Feynman [[link]](http://genius.cat-v.org/richard-feynman/writtings/letters/problems)
  * Why We Can’t Rule Out Bigfoot: How the null hypothesis keeps the hairy hominid alive. [[link]](http://nautil.us/issue/16/nothingness/why-we-cant-rule-out-bigfoot)
  * An Atheist’s Guide to Spirituality: "I did not have to believe anything irrational about the universe.” [[link]](http://nautil.us/issue/16/nothingness/an-atheists-guide-to-spirituality)
  * This Is Where Your Childhood Memories Went: Your brain needs to forget in order to grow. [[link]](http://nautil.us/issue/16/nothingness/this-is-where-your-childhood-memories-went)
  * Information Theory And The Origin of Life: The nature of information places important new limits on how the first living things must have emerged [[link]](https://medium.com/the-physics-arxiv-blog/information-theory-and-the-origin-of-life-4cf6b93d156c)
  * It’s complicated: Human ingenuity has created a world that the mind cannot master. Have we finally reached our limits? [[link]](http://aeon.co/magazine/technology/is-technology-making-the-world-too-complex/)
  * **Omens**: When we peer into the fog of the deep future what do we see – human extinction or a future among the stars? [[link]](http://aeon.co/magazine/philosophy/ross-andersen-human-extinction/)
  * This Shape-Shifter Could Tell Us Why Matter Exists: Neutrinos can flit between states effortlessly, hinting at deep new physics. [[link]](http://nautil.us/issue/14/mutation/this-shape_shifter-could-tell-us-why-matter-exists)
  * How to choose?: When your reasons are worse than useless, sometimes the most rational choice is a random stab in the dark [[link]](http://aeon.co/magazine/philosophy/is-the-most-rational-choice-the-random-one/)
  * How Physics Is Like Three-Chord Rock: Like a set of common chords, the same math appears in diverse fields of physics. [[link]](http://nautil.us/issue/14/mutation/how-physics-is-like-three_chord-rock)
  * **Meet the Father of Digital Life**: This maverick forerunner of artificial life and animation remains largely unknown. [[link]](http://nautil.us/issue/14/mutation/meet-the-father-of-digital-life)
  * Interesting problems: The Church-Turing-Deutsch Principle [[link]](http://michaelnielsen.org/blog/interesting-problems-the-church-turing-deutsch-principle/)
  * The Existential Risk Of Mathematical Error [[link]](http://www.gwern.net/The%20Existential%20Risk%20of%20Mathematical%20Error)
  * Simulation Inferences [[link]](http://www.gwern.net/Simulation%20inferences)
  * **The Man Who Invented Modern Probability**: Chance encounters in the life of Andrei Kolmogorov. [[link]](http://nautil.us/issue/4/the-unlikely/the-man-who-invented-modern-probability)
  * At the Far Ends of a New Universal Law [[link]](https://www.quantamagazine.org/20141015-at-the-far-ends-of-a-new-universal-law/)
  * Paul Dirac: The Quiet Genius Died 30 Years Ago [[link]](http://blog.lindau-nobel.org/paul-dirac-the-quiet-genius-died-30-years-ago/)
  * San Francisco Is Smarter Than You Are: The city is a big brain that can solve big problems. [[link]](http://nautil.us/issue/18/genius/san-francisco-is-smarter-than-you-are-rd)
  * Why the Chess Computer Deep Blue Played Like a Human: Randomness may be key to both human and computer creativity. [[link]](http://nautil.us/issue/18/genius/why-the-chess-computer-deep-blue-played-like-a-human)
  * **The Fermi Paradox** [[link]](http://waitbutwhy.com/2014/05/fermi-paradox.html)
  * **The AI Revolution**: The Road to Superintelligence [[link]](http://waitbutwhy.com/2015/01/artificial-intelligence-revolution-1.html)
  * **The AI Revolution**: Our Immortality or Extinction [[link]](http://waitbutwhy.com/2015/01/artificial-intelligence-revolution-2.html)
  * Goodbye, Turing Test; Bring on the Turing Decathlon [[link]](http://nautil.us/blog/goodbye-turing-test-bring-on-the-turing-decathlon)