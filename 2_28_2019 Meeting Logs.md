## Meeting Logs for February 28th, 2019


```
BigSlim
#9710

BigSlim02/16/2019
 2_28_2019 Meeting Agenda (1 hour)

Whats happened the last 2 months: 10min
1. Aeon community Github updates: Github.io update to new dropdown format, Aeon Timeline added to website, Tester Central added for Beta testing. 
https://github.com/AEONCommunity/TesterCentral
https://aeoncommunity.github.io
https://aeoncommunity.github.io/information/timeline.html
https://github.com/AEONCommunity/RPC-Usage
https://github.com/AEONCommunity/CLI-Usage

2. Aeon Whitepaper update: Thriftyminnow is freshening up the paper to meet current release on Aeon
https://github.com/AEONCommunity/aeon-whitepaper

3. Aeon Funding updates: 
Web Wallet bounty - Who will take this up? How can we attract someone to complete this?
FreeBSD package - We need someone to finish the update, devs at freeBSD are asking for some minor changes to merge. Move the bounty to someone else? 
AeonAPI merge to MonerujoAE with latest 12.8 or 12.9?
Project manager funding - thank you to all who donated
AFS 3 month operation funding success - Thanks!
https://aeonfunding.com/proposals

4. Marketing: Thunderosa has provided an AFS to generate some good marketing materials for the Aeon project. 
https://aeonfunding.com/proposal/25
Cryptoshib marketing for website and article publishing promotion
https://aeonfunding.com/proposal/24
Please provide feedback to Thunderosa on marketing ideas and how we can use them (or how YOU can use them to help Aeon)
 Discussion: 30min
5. Community funds: How should these funds be spent (or if they should even be spent? )
https://aeonfunding.com/donate

6. How should our project manager spend his time? 

7. Aeon Algo change: Monero forking to CN-R soon. Should Aeon do CN-R or CN-X or what??? Who will do this? How can re recruit members to do this?
https://www.reddit.com/r/Aeon/comments/apn3tf/asic_resistance_hashrate_discussion_thread/
7.1 Aeon removing ring sizes 1-4, setting minimum 5. 

Other topics: 10min
* Community Translations: Bigslim has initiated some recruiting for translations of Aeon related material. Process should start 3/2019
* Android phone apps- Enerc Aeon Daemon: https://github.com/enerc/Aeon-daemon   , BigslimVdub prebuilt binaries for armV8 android devices: https://github.com/BigslimVdub/AeonAndroidArmV8 . Please test and report back!
* Beta testing: Recruiting for this: https://github.com/AEONCommunity/TesterCentral. Who is volunteering to do this?
* Aeon Blockchain analysis: BMO-Noire preformed a nice analysis and found good evidence of ASICS on the Aeon Network. Please donate to his cause!
https://aeonfunding.com/proposal/23
https://medium.com/@dedoopbebloop/aeon-monero-a-percent-estimation-of-asics-on-the-network-ce9e7f6e9194

Open Discussion: 10min
Any other topics not in agenda to discuss? 
BigSlim pinned a message to this channel. See all the pins.02/16/2019
BigSlim pinned a message to this channel. See all the pins.02/16/2019
camothegeek02/16/2019
If your a project manager, plan projects and look to get them assigned:completed
BigSlim02/16/2019
It's a discussion that BMO suggested for community members to voice what they think I should be doing with my time (prioritize) I believe is what he meant
Ex: I have my own priorities, but community members may believe that there is a specific task/project they want completed first before anything else. I believe this is an area where people could have their voice heard in a way.
BMO-noire02/16/2019
my idea was that we should discuss shared resources so that the meeting will be meaningful
420 suggested that Slim's time could be considered a shared resource
BigSlim02/16/2019
let's not cloud up this with conversations right now please
:wink:
BMO-noire02/16/2019
tl'dr of my viewpoint in #dev-general: every single topic point needs to end in a Yes/No or someone saying "I'm doing this because of this discussion" or else it's wasting time and should in a news post. Shared resources are a valuable tool that helps keep discussion meaningful
BigSlim02/26/2019
added for discussion: 7.1 Aeon removing ring sizes 1-4, setting minimum 5.
camothegeek02/28/2019
test from meeting channel to irc.
IRC BridgeBOT02/28/2019
<camthegeek> received!
BigSlim02/28/2019
Ok
IRC BridgeBOT02/28/2019
<BigSlim> hi
<stoffu> Hi
<stoffu> Another interesting thread: https://www.reddit.com/r/Monero/comments/avnklu/money_is_not_just_about_technology_its_about/
reddit
r/Monero - Money is not just about technology, it's about psycholo...
16 votes and 26 comments so far on Reddit
<monerobux> [REDDIT] Money is not just about technology, it's about psychology too. (self.Monero) | 17 points (77.0%) | 26 comments | Posted by keksov | Created at 2019-02-28 - 05:54:31
BigSlim02/28/2019
Meeting Starts in 5 Minutes
IRC BridgeBOT02/28/2019
<smooth> If you are talking about general purpose equipment then there is no major cost to changing algorithms. That's sort of double edged sword of it
<camthegeek> time is money
420Coupe02/28/2019
^
IRC BridgeBOT02/28/2019
<smooth> Not much time to switch miners. Or autoswitch for that matter
BigSlim02/28/2019
Hello everyone and welcome to the Community meeting for 2_28_2019!
IT's our Second Community meeting since we started
First I just want to thank everyone that stopped by for the meeting and thanks to everyone in the community who has contributed or is currently contributing to the Aeon project!
Let's start off with a quick recap of the past 2 months since our last meeting:
We invite everyone to visit the Aeon community GitHub repo that was set up. https://github.com/AEONCommunity
GitHub
AEON Community
Projects and documents developed by the AEON Community for the benefit of others. - AEON Community

This repo was created for community members to have a central source for everything Aeon outside the main codebase. Also check out our webpage https://aeoncommunity.github.io/
AEON Community Pages
AEON Community Pages
Various and sundry information related to the AEON digital currency
Props to @thriftyMinnow for his work on a general Aeon Whitepaper https://github.com/AEONCommunity/aeon-whitepaper
GitHub
AEONCommunity/aeon-whitepaper
This is a proposed AEON whitepaper, to be considered by the community. - AEONCommunity/aeon-whitepaper

Ahh for anyone interested in the Agenda for the meeting feel free to check out the topics here: http://paste.debian.net/hidden/393585b0/
Props to @camothegeek  for his AFS that was set up for funding community projects: https://aeonfunding.com/
AEON Funding System
AEON Funding System - Make proposals related to AEON and get paid in cryptocurrency (AEON)!
Please take note for the latest Funding projects up: 25 & 24 marketing.
Any questions or comments from anyone in attendance today?
camothegeek02/28/2019
no? nothing but props and thanks so far.
BigSlim02/28/2019
heh
Thunderosa02/28/2019
nope, all good stuff
BigSlim02/28/2019
good deal. Let's move on to the juicy stuff: Community Discussions
One topic brought up was our Community Fund on AFS. Not many people know about this, but it was set up as a fund where the community (or anyone) can donate to this and then decide how the funds are spent. https://aeonfunding.com/donate
AEON Funding System
AEON Funding System - Make proposals related to AEON and get paid in cryptocurrency (AEON)!
Are there any comments or suggestions on this fund and how we should spend funds currently?
328 Aeons in there right now
IRC BridgeBOT02/28/2019
<camthegeek> Nope. I've continued to keep adding over the past few months. Perhaps a decent proposal will come along.
BMO-noire02/28/2019
I'd like to encourage that a set amount be spend bi-weekly just to encourage activity. For lack of better ideas, maybe donate a pizza to a community member who has done something notable the week prior?
BigSlim02/28/2019
I have been contributing 5 -10 aeon each week
Sounds like a good idea BMO.
IRC BridgeBOT02/28/2019
<camthegeek> Maybe some silly giveaway again.
BigSlim02/28/2019
:wink:
I have another giveaway ready, just waiting to get it posted up.
BMO, would you like to take up the task of brainstorming some ideas for funds to be spent? Possibly make a reddit post for donation exercises?
IRC BridgeBOT02/28/2019
<camthegeek> Then continue to build that fund up until something big comes around.
BMO-noire02/28/2019
well, since devs are here, I'd like to talk about PoW algorithms so we can switch as soon as possible
BigSlim02/28/2019
ok
so you do not want to take the task of making ideas to spend the fund?
BMO-noire02/28/2019
sure, I'll think of something to post
BigSlim02/28/2019
Ok sounds great. Until then let's keep adding those aeons.
Next topic
Are there any suggestions for the project manager to spend their time focused on a particular project right now in Aeon or should they continue the same tasks?
BMO-noire02/28/2019
I think you're doing a great job
BigSlim02/28/2019
thanks!
Anyone else have suggestions?
Ok moving on
Next topic has been a heated one the past few days.
Many community members have voiced their opinions about Aeon making a POW change recently. Members have suggested a few options: CN-Turtle, CN-Random, CN-X, Single Hash change, Prog-POW, and also SHA3
Along with this we wanted to discuss removing rings 1-4 and a possible Locking of ring sizes
Let's talk about these options
BMO-noire02/28/2019
From the conversation earlier today between smooth, stoffu, dEBRUYNE, and moneromoo, only two options were left standing: SHA-3 now, or CN-r and a last effort following by perhaps SHA-3 next year.
I'm not knowledgeable on this subject so I'll just listen. I'd be happy to support any decision that's made.
BigSlim02/28/2019
I have been doing some quick research of SHA3 today
BMO-noire02/28/2019
... as a last effort ^
IRC BridgeBOT02/28/2019
<BigSlim> possibly @smooth @stoffu or @moneromooo can chime in
<smooth> im in favor of trying a lite version of cn-r and maybe randomx if it matures to the point of usability
<smooth> but im not in favor of changing just to change. people need to accept that if the asic-resistance effort reaches the point of clear failure then we make one switch to asic friendly and never change again (absent failure of the hash function itself)
BigSlim02/28/2019
Here are some quick reference links for SHA3: 404Gh available for rent (1000x current aeon hash rate) https://www.miningrigrentals.com/rigs/sha3 , Quick reference of SHA3 supported coins and hash rates https://coinguides.org/keccak-algorithm-miner-coins/ , General wiki for SHA3 https://en.wikipedia.org/wiki/SHA-3
Mining Rig Rentals | Sha3-Keccak Rigs
MiningRigRentals.com focuses on providing a top level mining rig rental service. The focus is to unite renters and rig owners for the purpose of exchanging Crypto-currency for mining time. A secure, safe, better alternative to similar services online.
Coin Guides
coinguides
Keccak hashing algorithm (SHA-3) - Keccak Coins and miner for Keccak
Keccak is SHA-3 encryption algorithm. Here we've listed miners for Keccak and all the coins that are based on Keccak Proof of Work algorithm.

SHA-3
SHA-3 (Secure Hash Algorithm 3) is the latest member of the Secure Hash Algorithm family of standards, released by NIST on August 5, 2015. Although part of the same series of standards, SHA-3 is internally different from the MD5-like structure of SHA-1 and SHA-2.
SHA-3 is a s...
IRC BridgeBOT02/28/2019
<smooth> constant forks is a hazard
<monerobux> [WIKIPEDIA] SHA-3 | "SHA-3 (Secure Hash Algorithm 3) is the latest member of the Secure Hash Algorithm family of standards, released by NIST on August 5, 2015. Although part of the same series of standards, SHA-3 is internally different from the MD5-like structure of SHA-1 and SHA-2.SHA-3 is a subset of the broader cryptographic..."
BigSlim02/28/2019
I believe that our best course of action right now is to merge CNr and see how it goes for Aeon. If it does not work 1-for asic prevention or 2- to maintain lightness of the platform, I believe that we can prepare ourselves for SHA3 algo as suggested by Stoffu since it is still "currently" gpu friendly.
Just note that SHA3 seems to be VERY CUDA (nvidia) GPU favor for mining unlike current AMD favor mining for CN V* algos.
IRC BridgeBOT02/28/2019
<smooth> sha3 is an option today but i dont think we need to make that decision now nor should pre-commit to a particular hash function. next fork would be 6 months or a year away or possibly longer, so we can reevaluate the situation at that time
BigSlim02/28/2019
This is on minimal research though. It may differ on Aeon or other CN coins.
IRC BridgeBOT02/28/2019
<smooth> however it should be some simple function which will be ultimately (even if not immediately) asic-friendly
BMO-noire02/28/2019
I would rather see CN-r, however, I will parrot dEB's argument since he isn't here: Why not go SHA-3 now since this algorithm is ASIC-resistant for the time being, and since we will need to eventually switch?
IRC BridgeBOT02/28/2019
<smooth> sha-3 is not at all asic resistant
BigSlim02/28/2019
I definitely think we should research the best option for Aeon. That takes time, but it seems there are individuals who have already done some research on this topic.
BMO-noire02/28/2019
err, I should say, since asics are currently not made for the algorithm
IRC BridgeBOT02/28/2019
<smooth> when asics are built they will be 1000x faster or something
BigSlim02/28/2019
yes
You have to see though that Aeon has only forked 2 times for POW change since inception
2 times almost 5 years
IRC BridgeBOT02/28/2019
<smooth> prior to 2017 cn was successful asic-resistant
BigSlim02/28/2019
Are there even any current miners that support SHA3 aeon hobby miners could use?
GPU/CPU wise?
IRC BridgeBOT02/28/2019
<smooth> there are probably not any current miners, but it wouldn't be hard to modify them
BigSlim02/28/2019
And if so, will they support current use case or can they be updated?
That will be a big question from smaller miners.
Someone would need to fork and update say CPUmultiminer from way back to account for a new change
IRC BridgeBOT02/28/2019
<smooth> a miner needs to support cryptonote headers as well as the hash algorithm. most miners if they support different algorithms use btc/ltc style headers
<stoffu> smooth: Whatâ€™s your view on the feasibility of ASIC resistance either through 1) POW (like RabdomX) being really resistant, or 2) changing POW indefinitely every time ASICs appear?
<BigSlim> didn't @stoffu update ccminer or something for Aeon in 2017?
<stoffu> Or can it be feasible in some other ways I missed?
<smooth> im not in favor of changing indefinitely, at least not super-frequently
<smooth> i dont like the risk of screw ups being introduced every six months. maybe every few years is okay
<smooth> i think hard forks should become less frequent as a coin matures
<smooth> which would indeed be the case except for this pow change ting
BigSlim02/28/2019
this /\
IRC BridgeBOT02/28/2019
<smooth> *thing
<jwinterm> I wonder if aeon switched to sha3 if it's large enough to attract dedicated hardware
<smooth> jwinterm: probably not but maybe fpgas, at least on some sort of auto-switching basis
<jwinterm> I kind of doubt it, but vertcoin did for something at least a bit more exotic
BigSlim02/28/2019
I think if Aeon put its-self out there and made some big strides that it would attract this
IRC BridgeBOT02/28/2019
<stoffu> I donâ€™t like to wait for unknown amount of times doing what I believe is wrong without no good reason.

IRC BridgeBOT02/28/2019
<monerobux> [ AeonCommunity on Twitter: "Just synced $AEON wallet from block 0 to 1044266 with a local node in 16:04. Love that 1mb scratchpad.â€¦ " ] - twitter.com
BigSlim02/28/2019
sorry 16:04 to sync...
I timed these
this was using GUI not CLI though
IRC BridgeBOT02/28/2019
<smooth> probably the same
BigSlim02/28/2019
14 minutes was the resacan I believe
after sync
cam inquired about these
IRC BridgeBOT02/28/2019
<smooth> sha3 requires not only hooking up the hash in the daemon but also pool and miner code
BigSlim02/28/2019
In relation Monero was 32 minutes IIRC same task
cam has the numbers for those
IRC BridgeBOT02/28/2019
<smooth> (true of any function but cn variants can get most of the work done by monero already, with tiny tweaks)
<stoffu> I'm willing to contribute to that effort.
<smooth> great, that's certainly a positive
BigSlim02/28/2019
what effort?
thinkpol02/28/2019
smooth, stoffu, what would you want if you were choosing? cn-r or sha3?
IRC BridgeBOT02/28/2019
<smooth> im neutral. i respect the arguments for boith
<stoffu> An effort to build software infrastructure for SHA3 mining (pools, CPU/GPU miners)
mosu_forge02/28/2019
The node multi hashing already supports keccak https://github.com/zone117x/node-multi-hashing
Used for pools
IRC BridgeBOT02/28/2019
<stoffu> I'm for SHA3 obviously
BigSlim02/28/2019
Stoffu, would you like to research options like SHA3 or asic friendly  for Aeon and provide an informational document we can present professionally to the community on this?
IRC BridgeBOT02/28/2019
<smooth> 'keccak' and sha3 differs only in terms of some header byte or something i believe
<stoffu> I believe so, too.
mosu_forge02/28/2019
So it wouldn’t be hard to change that module from one to the other. That’s 99.9% of the pool changes
Only caveat is that pools would need both the multi hashing and cryptonote hashing libs for the switch
IRC BridgeBOT02/28/2019
<stoffu> BigSlim: I don't think such document is necessary. SHA3 is already well known.
BigSlim02/28/2019
ok
It would be more so for informational and educational purposes for community members
more like an overview such as "hey this is what sha3 is and why it would be good for aeon" type of deal
IRC BridgeBOT02/28/2019
<jwinterm> https://en.wikipedia.org/wiki/SHA-3
SHA-3
SHA-3 (Secure Hash Algorithm 3) is the latest member of the Secure Hash Algorithm family of standards, released by NIST on August 5, 2015. Although part of the same series of standards, SHA-3 is internally different from the MD5-like structure of SHA-1 and SHA-2.
SHA-3 is a s...
<monerobux> [WIKIPEDIA] SHA-3 | "SHA-3 (Secure Hash Algorithm 3) is the latest member of the Secure Hash Algorithm family of standards, released by NIST on August 5, 2015. Although part of the same series of standards, SHA-3 is internally different from the MD5-like structure of SHA-1 and SHA-2.SHA-3 is a subset of the broader cryptographic..."
<jwinterm> sorry
<stoffu> If we're going SHA3, I guess at some point some final statement has to be made and posted to various channels.
BigSlim02/28/2019
yea a final statement sure but this is more so like opening the door on the idea for the community
IRC BridgeBOT02/28/2019
<stoffu> Yeah, then a discussion thread on reddit maybe
BigSlim02/28/2019
that would be fantastic
So at this point, can we make a decision as to what direction Aeon is going moving forward today?
There have been some good discussions tonight on many topics.
From my tallies tonight there are 6 members for asic friendly change now and 3 members for CN-r changes now
Are there any final thoughts on this tonight before we close out this discussion?
Did everyone lose internet connection?
Thunderosa02/28/2019
If Aeon is going SHA-3 in the future,...might as well go now. For the reasons brought up, but also there would be a goodly amount of attention that Aeon would get from stepping out of Monero's shadow. So,...good for marketing.
thinkpol02/28/2019
agreed
BigSlim02/28/2019
thanks for the comment
IRC BridgeBOT02/28/2019
<stoffu> Iâ€™m sure itâ€™ll catch a lot of attention. moneromooo also said heâ€™d be curious what SHA3 Aeon will look like.
BigSlim02/28/2019
So I believe we will close out tonights discussion on POW change with a consensus that Aeon will move to step out of the CN hash to a possible more asic friendly hash algo such as SHA3 and that Stoffu has approved drafting a document with research for this proposed change along with formulating an infrastructure for mining these proposed changes.
IRC BridgeBOT02/28/2019
<stoffu> If it catches attention, the price will rise, and ASICs appear :P
<stoffu> If not, hobby miners can continue enjoy GPU mining
Thunderosa02/28/2019
No more botnets though.
IRC BridgeBOT02/28/2019
<stoffu> I think CPU mining wonâ€™t be really worthwhile
<stoffu> GPU seems far better
BigSlim02/28/2019
On our last topic Thunderosa says he wanted to answer any questions or comments in regards to  his AFS proposal or marketing
are there any thing you want to add tonight @Thunderosa ?
Thunderosa02/28/2019
Not really, I've started working on some ideas ahead of the funding....so it's moving along.
IRC BridgeBOT02/28/2019
<stoffu> I think the decision is still pending. There are many people who couldnâ€™t join this time.
BigSlim02/28/2019
We can allow additional comments at tomorrow AM community meeting in #mar_1_2019-6am-cst
At that point we can make a final decision on Friday and draft a post for the community on this.
IRC BridgeBOT02/28/2019
<stoffu> Iâ€™ll post a discussion thread on reddit and a link to it on bitcointalk
BigSlim02/28/2019
Community members have been given a chance to attend todays meeting and also tomorrows meeting with supplied agenda.
If you have any additional timeline suggestions before closing out the discussion with a final decision please feel free to post a response time window in your reddit post.
Leaving the door open on major decisions such as this will only lead to further delay and community members have voiced their opinions on aeon not committing to any changes or direction.
We have had 2 days of good constructive discussion on discord and IRC in regards to this major POW change and direction of Aeon and also some good discussion tonight. I will post a link on twitter for your reddit post and if @smooth could post on the official Aeon account that would be great.
IF there are no further questions or comments I believe we can close out this meeting tonight.
IRC BridgeBOT02/28/2019
<stoffu> Thank you for organizing it!
thinkpol02/28/2019
thank you smooth and stoffu for hanging out and answering questions!
thanks @BigSlim for running everything
BMO-noire02/28/2019
It's good to see things in motion again!
BigSlim02/28/2019
Thank you everyone for joining tonight and voicing your thoughts and opinions about the Aeon community and Aeon project!
IRC BridgeBOT02/28/2019
<stoffu> My pleasure
BigSlim02/28/2019
A full log will be provided within a few days here on our official Aeon Community Repo.
Let's hope for a good 2019 for Aeon!!
:wave:
I will be locking the channel for comments now. IRC bridge will be down until tomorrow AM.
IRC BridgeBOT03/01/2019
<stoffu> https://www.reddit.com/r/Aeon/comments/aw2xhn/proposal_to_switch_to_sha3_proof_of_work/
<monerobux> [REDDIT] Proposal to switch to SHA-3 proof of work (self.Aeon) | 1 points (100.0%) | 0 comments | Posted by stoffu | Created at 2019-03-01 - 09:29:57
IRC BridgeBOT03/01/2019
<durinsmine> How about just use a different algo to XMR problem solved until we get large enough to matter
<durinsmine> embracing asics is the death of this coin
<durinsmine> Coins dead now with asics, no real miners, dont know why you think making it more asic friendly will bring more miners/users -.-
<stoffu> I guess youâ€™ll never change your opinion, so I wonâ€™t even try :)
<durinsmine> killing this coin lol
<durinsmine> do it to xmr first see what happens lol
<stoffu> Thatâ€™s surely harder than with Aeon.
<durinsmine> So what youre making aeon the asic friendly testing ground. Most ridiculous thing going this. If this goes through will be closing my pool anyway
<stoffu> There are plenty many other Monero forks, like TRTL
<stoffu> moneromooo doesnâ€™t seem to ever agree with me on this :)
<durinsmine> well you know ive been supporting this "asic resistant" coin for two years running a pool for free out of pocket this crap is just a slap in the face to everyone who doesn't own asics. Waste of two years mining I suppose
<stoffu> Too bad, but thatâ€™s your fault. No one is liable.
<durinsmine> Well no lol this massive change is ridiculous IMO
<durinsmine> Why not just change to a different algorithm than xmr that no other coin is using? asic resistance there until Aeons big enough to develop asics for
IRC BridgeBOT03/01/2019
<wowario> stoffu: What do you think about the social contract argument. The coin was launched to be ASIC resistant. Miners invested time and equipment with this understanding, so making such a radical change would be unethical tantamount to changing the coin supply.
<durinsmine> Its in their self interest no other reason
<durinsmine> What possible reason could there be to add BTC asics to aeon?
<durinsmine> Unless they or the group pushing for it has those asics
IRC BridgeBOT03/01/2019
<ksk> nice post stoffu.
<ksk> not sure about mining heaters though, the engergy density of things like coal or oil is very big compared to just burning energy off the grid
<ksk> countrys like france might beg to differ though..
<ksk> "Aeon will be the first CryptoNote coin that deployed SHA-3. I believe this is a very good opportunity for marketing as well.
<ksk> " I totally agree, would be nice to have something no other coin has.
<ksk> btw, does anyone know about the asic situation with ETHereum? Are they used to mine it? Guess yes, because there was word of eth gpu farms switching to xmr-based coins some time ago?^^

```
