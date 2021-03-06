---
layout: base
title:  'xcomp'
shortdef : 'open clausal complement'
---

## xcomp (open clausal complement) <a name="sec-xcomp"></a>

The dependency type `xcomp` is reserved for clausal complements which have an external subject, that is, whose subject is shared with the complemented verb (phenomenon also known as subject control). Note that the subject of the complementing clause must be the *subject* of the complemented verb, not any other sentence element.


<!-- fname:xcomp.pdf -->
<div class="sd-parse">
Hän alkoi hakata halkoja . \n He started chopping the_wood .
nsubj(alkoi-2, Hän-1)
xcomp(alkoi-2, hakata-3)
dobj(hakata-3, halkoja-4)
punct(alkoi-2, .-5)
</div>


Many of the complements with an external subject resemble cases that are analyzed as main verbs with auxiliaries. Both auxiliaries and `xcomp` complements share their subject with another verb, but only a closed list of verbs are analyzed as auxiliaries in TDT (see Section [aux](#sec-aux)). Note also that in auxiliary cases the second verb is the governor, whereas with `xcomp` the first verb becomes governor (unless the word order is inverse).

