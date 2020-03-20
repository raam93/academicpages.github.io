---
title: "Optimizing Peer Referrals for Public Awareness using Contextual Bandits"
excerpt: "*How can we optimize peer-to-peer referrals to create public awareness in a low-resource setting?*<br/><img src='/images/optimize-cover.png'>" 
collection: projects
---

Joint work with [Amit Sharma](http://www.amitsharma.in/), and [Amulya Yadav](http://amulyayadav.com/)
## Abstract:
Programs that reward people for referring their friends are increasingly being used to raise awareness about important
topics. With a fixed budget for referral incentives, a natural goal for such referral programs is to maximize the number
of people reached. Unlike a typical influence maximization problem, however, the social network of potential adopters is unknown apriori. Further, people’s response to a referral incentive can depend on various factors such as their preference for the content, size of their social network, and their estimated value for sharing. Therefore, we introduce an incentive-aware variant of the influence maximization problem and formalize it under an online learning setting. Given the lack of initial information about the social network or how people respond to referral incentives, we use an explore-exploit strategy and present a contextual bandit agent CoBBI that optimizes the incentives for each user by learning from the results of its past actions. We demonstrate the effectiveness of CoBBI on data from a real-world referral program for raising land rights’ awareness among farmers. Compared to a wide range of baselines, we find that CoBBI is consistently more cost-effective, across a wide range of influence probabilities and people’s response to incentives.

<img src='/images/optimize-inside.png'>

## Publication:
__Ramaravind Kommiya Mothilal__, Amulya Yadav, and Amit Sharma. ["Optimizing peer referrals for public awareness using contextual bandits."](https://raam93.github.io/files/optimize-peer-referrals-compass.pdf) In Proceedings of the 2nd ACM SIGCAS Conference on Computing and Sustainable Societies (COMPASS 2019), pp. 74-85. 2019.

[[slides]](https://raam93.github.io/files/optimize-peer-referrals-slides.pptx) [[video]](https://www.youtube.com/watch?v=46gIqhB24KU&t=22289s)

## Related: deployement support.
The above research is based on the data of [Learn2Earn](https://www.microsoft.com/en-us/research/uploads/prod/2019/08/Learn2Earn-CSCW.pdf) pilots. Learn2Earn is an Interactive Voice Response (IVR) based system that leverages mobile payments to bolster public awareness campaigns in rural India. I provide data analysis support for various pilots to create awareness on public issues such as HIV/AIDS and local elections, and to share hyper-local media contents in local language. This is a joint work with Devansh Mehta, Alok Sharma, [Amit Sharma](http://www.amitsharma.in/), and [Bill Thies](http://billthies.net/).

## Publications:
* __Ramaravind Kommiya Mothilal__, Devansh Mehta, Alok Sharma, William Thies, and Amit Sharma. ["Learnings from an ongoing deployment of an IVR-based platform for voter awareness."](https://raam93.github.io/files/learn2earn-deployement.pdf) In Conference Companion Publication of the 2019 on Computer Supported Cooperative Work and Social Computing (CSCW 2019), pp. 257-261. 2019. **(a non-archival version won *Outstanding Poster Award* at COMPASS 2019)**

* Devansh Mehta, Sebastin Santy, __Ramaravind Kommiya Mothilal__, Brij Mohan Lal Srivastava, Alok Sharma, Anurag Shukla, Vishnu Prasad, Venkanna U, Amit Sharma, and Kalika Bali *(in press)*. ["Learnings from Technological Interventions in a Low Resource Language: A Case-Study on Gondi."]() In Proceedings of the Twelfth International Conference on Language Resources and Evaluation (LREC 2020). 2020.

* Devansh Mehta, Alok Sharma, __Ramaravind Kommiya Mothilal__, Chiraag Chiraag, Anurag Shukla, Vishnu Prasad, William Thies, Venkanna U, 	Colin Scott, and Amit Sharma *(in press)*. ["Facilitating Media Distribution with Monetary Incentives."]() In Extended Abstracts of the 2020 CHI Conference on Human Factors in Computing Systems. 2020.
