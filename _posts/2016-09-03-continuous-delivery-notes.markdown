---
layout: default
title:  "Continuous Delivery - Notes"
date:   2016-09-03
categories: main
---

# Continuous Delivery

### Anatomy of the Deployment Pipeline

> What we end up with is (in lean parlance) a pull system. Testing teams deploy
> builds into testing environments themselves, at the push of a button. Operations 
> can deploy builds into staging and production environments at the push of a 
> button. Developers can see which builds have been through which stages in the 
> release process, and what problems were found. Managers can watch such key 
> metrics as cycle time, throughput, and code quality. As a result, everybody in the 
> delivery process gets two things: access to the things they need when they need 
> them, and visibility into the release process to improve feedback so that bottle-
> necks can be identified, optimized, and removed. This leads to a delivery process 
> which is not only faster but also safer.

### Testing Nonfunctional Requirements

>   A similar strategy can be useful for protecting known performance hot spots 
> from getting worse over time as the code develops. When such a hot spot is 
> identified, create a “guard test” that runs very quickly as part of you commit test 
> cycle. Such tests act as a kind of performance smoke test—they aren’t going to 
> tell you that your application meets all of its performance criteria, but they may 
> highlight trends in the wrong direction and let you tackle them before they become 
> a problem. However, watch out that you don’t introduce untrustworthy tests 
> that fail intermittently with this strategy.

