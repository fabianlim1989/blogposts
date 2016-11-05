# How Singapore's Education System Can Affect Individual's Security Mindset

_Disclaimer: This article is an effort solely by Fabian Lim, written from my point of view and does not represent any organization. Born and brew as a Singaporean, I am using my country as a case study but facts apply worldwide. I am utterly thankful, and consider myself lucky to be in a generation for my bilingual ability and knowledge in information security._

## Motivation

My personal goal is a noble one - I aim to raise awareness in security for the general public as well as in software developers. Being a DevSecOps engineer myself, I want to apply practical improvements with the knowledge I acquired while on this journey to make this world a more secure place.
I have heard many incidents of scams and according to [Channel News Asia](http://www.channelnewsasia.com/news/singapore/scams-exploiting-infocomm/2872234.html) scams in Singapore are indeed on the rise. That made me wonder if it has anything to do with the culture, mindset or education system or all?

## Let me lay the premises - facts, figures and history

### Introducing English in the Education System

Surprise surprise to many foreigners, little do they know that Singapore claims to be an English-speaking country. Road signs, books, conversations, are communicated in English. Sort of...

But this was not always the case, it was since the independence of our nation.

In 1965, the Singapore government merged the ethnically diverse educational streams into a single national system with the adoption of bilingual education policy (English and the Mother Tongues).
Students who attended schools with the national system after 1965 had bilingual education.

Assuming a child starts school at age 6 in the year 1965, he / she will experience the benefits of a bilingual education system. Vice versa, assuming a child that had already started school in 1965 will continue to follow the same (non-bilingual) system through out his education.

Fast forward to 2016, we can safely deduce that majority of the people (population BELOW the age of 56) who started attending schools before 1965 had very little or none of the bilingual education and English is not a language within their mastery.

Here are some references to Singapore's education system:
* http://eresources.nlb.gov.sg/infopedia/articles/SIP_2016-09-01_093402.html
* http://siteresources.worldbank.org/INTAFRREGTOPEDUCATION/Resources/444659-1204656846740/4734984-1204738243676/Session15-ProfLeoTan-OverviewofSingaporesMilestoneReforms.pdf

### Estimated Population that Do Not Grasp English
As of 2016, according [SingStat](http://www.singstat.gov.sg/statistics/visualising-data/charts/age-pyramid-of-resident-population), there are about 1 million Singaporean residents above 56 years old.

Also, according to [SingStat](http://www.singstat.gov.sg/docs/default-source/default-document-library/statistics/visualising_data/population-trends2016.pdf), the Singaporean residential population is 3.93 million.

From a statistics point of view, that is about 1 out of 4 people who do not have mastery over English possibly due to the lack of education during their time, as of the time of writing this post.

## Let Me Paint the Picture - How this matters

If I may deduce why English was used as the main language in today's technology: Most technologies we use today is about data transfer over the Internet. If you are familiar with the history of Internet (http://www.internetsociety.org/internet/what-internet/history-internet/brief-history-internet), it first started in DARPA (in MIT) as `ARPANET` and later spread across the entire world. Different protocols on top of the Internet are later written to different the many types of data traffic. However, all protocols and programming languages are all written in English. Slowly but surely, other tools and technologies that ride on this Internet are also essentially written in English. Needless to say the concept of 'username' and 'password' is also, incepted in the same manner. Although some websites can extend its language abilities to accept characters but that will require custom libraries and handling that is out of the norm for a small-to-medium sized tech company. There are talks about passwords being obsolete in the future but I personally think that [passwords are going to stay for a while](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/Persistence-authorcopy.pdf).

Merging the 2 stories above together, the picture might be clearer in inferring why a large fraction of Singaporeans, who has a weak grasp of English, can have a disdvantage in their ability to manage their usernames and passwords.

Now, I am not equating the grasp of the English language to the grasp of the concept username and password. The concept of secrets and keeping information private has been around since the start of mankind, and is language-agnostic. However, if most of our current technologies rely on usernames and passwords being implemented in English, naturally the grasp of English plays a critical role in determining if users are able to manage their own usernames and passwords effectively. This may strongly translate into certain social behaviors and psychologically hinder password manageability.

For example, Singaporeans who do not have a grasp of English will find generating an alphanumeric username or password difficult and may often pick an easily identifiable alphanumeric to remember (National Registration Identity Card, car plate number, house number, etc). These can be easily identified by a malicious user. Simply put, we stick to the things we can manage and if we can only manage a few words, we will only put the same few words as our usernames or passwords.

The level of demand required might be:

| Criteria | Difficulty for non-Engish educated | Difficulty to Hack |
| --- | --- | --- |
| Numbers-only | Okay | Effortless |
| Alphanumeric | Tough | Depends on length |
| Alphanumeric and Symbols | Near Impossible | Harder, depends on length |

Another behavior I personally observed is that the older generations rely on and trust the younger generations to help them with technology - even it means to provide their usernames, passwords, and 2FA tokens. For example, a man was trying to pay for his taxes and he was required to login to a system. However, due to the fact that the login was in English and he was not proficient in English, he handed his username, password, and 2FA token to a person over the counter to help him with the task. To people like him, it is easier to provide all that information and get the tasks done, as their lack of knowledge English and technology make them feel daunted to handle those tasks themselves. They naturally become easy targets for scams and crimes.

With a limited ability to manage their own usernames and passwords, and the technologies involved, users rely on other means that reduce their security posture, compromising their security without even realising the risks and impacts.

### Attack Vectors are HUGE

As Singapore strives to become the world's leading tech-hub, emerging technologies are welcomed and integrated into our ecosystem, so much so that it is influencing our day-to-day lives. Businesses are using technologies to drive their business and users are welcomed to use them at a rapid pace. Citizens can have many types of accounts: a few for banking; one central account with the government managing personal information; one for managing your tax; etc.

## Interesting Solutions

### Singapore's Tech Solutions

In order to consolidate and have a centralized authentication method for the whole of Singapore, [SingPass](https://www.singpass.gov.sg/singpass/common/about) was borned. SingPass even added 2FA login to increase the security of its service. All government related transactions will authenticate through SingPass to identify a Singapoean and then he / she will then be able to complete government related tasks. Kudos to Singapore government in this area, correct me if i'm wrong, I have not heard of any country that implemented a centralized authentication system with 2FA for its citizens.

Even though SingPass was a good tool to increase security but it is still just a tool. Human layer is still breech-able as explained above!

### English Aside, Assume All Equal Now, Maybe Security Education Next?

One principle of a good password is that it has to be a non-dictionary word, and to be even better, made of a phrase that is easily remembered.

I'd recommended using native [Singlish](http://www.bbc.com/news/magazine-33809914) passphrases - they are perfect non-dictionary words that aren't found in commonly found in dictionaries. One interesting example can be: `2912jiaksimi?` - it translates to Singlish for "Tonight want to jiak simi?" - which ultimately means "What would you like to have for dinner tonight?" We have an advantage in this because Singlish was made and understood only by Singaporeans. [Check out more Singlish words.](http://www.singlishdictionary.com/)

However, this was better [before Oxford added Singlish words to their dictionary](http://www.straitstimes.com/singapore/shiok-19-singlish-items-added-to-the-oxford-english-dictionary). So slow your horses on getting those words into Oxford dictionary!

### Technology Without Security Education = Exploitable

We need to instill Singapore citizens with the security mindset through education and campaigns, like we did for [staying vigilant against physical terrorism](http://www.straitstimes.com/opinion/enhancing-singapores-response-to-terrorism). The cyber threats are real. Read more about them [here](https://www.wired.com/2015/09/cyberwar-global-guide-nation-state-digital-attacks/) and
[here](https://www.fireeye.com/content/dam/fireeye-www/global/en/current-threats/pdfs/fireeye-wwc-report.pdf)

Educating the safe usage should come along with the technology for everyone. We cannot separate technology apart from educating the safe use of it, both have to go hand-in-hand in to reduce exploitability. However, the implementors of technology seldom want to incur this as an overhead cost; the government do not know-it-all to educate-all. Plus, we are always playing catch-up with technology's bad debt. In my opinion, it will take a lot of passionate educators to start a movement in this direction.

## So what's next?

My next study will be talking about `Singapore's State of Wifi`.
