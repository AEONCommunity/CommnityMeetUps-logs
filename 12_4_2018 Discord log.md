BigSlimLast Tuesday at 7:57 PM
bummer we can't have meetings where everyone can join, but that's just earth
not everyone in the world is in the same time zone

Luke_ClashProjectLast Tuesday at 7:58 PM
Just wanted to say that my code of AN v0 is online now, a few Testbenchmarks (all 2MB Cache) would be the following
Syntax: 
 CPU-Name / CNv0-Hashrate / ANv0-Hashrate (both hashrate in h/s)

E3 1225 v2 / 200 / 1700
R7 1700 / 600 / 9000

I think, If we would put it to 1MB scratchpad to get ANv0-light we could see even higher improvements
By the way, what exactly is the difference between CN and CN-light? You said that light as approximately 3.5 times faster, but how is that possible, of the only visible change is the reduction of the scratchpad size?

BMO-noireLast Tuesday at 8:02 PM
Meeting starting up?
I don't have much to say but I'll read along and take notes if needed.
Oh, i guess my only question: do we want to do the Pauper's Fund

BigSlimLast Tuesday at 8:03 PM
Well hello all who are here for the community meet up for december 4, 2018
any roll call's of who is here ?

Luke_ClashProjectLast Tuesday at 8:03 PM
@here

BigSlimLast Tuesday at 8:04 PM
Up at the top I posted a topics discussion /\ from comunity interest

mosu_forgeLast Tuesday at 8:04 PM
I’m here observing

BigSlimLast Tuesday at 8:05 PM
First off I think we should thank all those community members that have brought the Aeon community back to life
@camthegeek for creating and getting this discord put together
@BigSlim and @BMO-noire for getting additional community related things started
all the pool operators that sometimes operate at a loss to help secure the network @Pool Operators
and all the @Community Contributor or @Community Writer that help in those ways(edited)
also the @Core Developer 's that help update and keep Aeon safe, decentralized, and a different project from the other 1000+ coins out there
Just a note to the people attending, we started a community github account where people can join and add things such as how-to's, informational usage of aeon, or just anything Aeon related. https://github.com/AEONCommunity
GitHub AEON Community Projects and documents developed by the AEON Community for the benefit of others. - AEON Community

cryptoziLast Tuesday at 8:12 PM
And a huge thanks to BigSlim

camthegeekLast Tuesday at 8:12 PM
I’m semi-here by the way.

LucianoLast Tuesday at 8:12 PM
if it help i can translate some stuff to spanish. im still learning how to push things to git.. But i can try

BigSlimLast Tuesday at 8:12 PM
cam, you're always here lol
you can always fork stuff, edit the files, then push a pr. Or just open the file you want to edit online and edit as necessary then create a PR.

LucianoLast Tuesday at 8:14 PM
yes.. but just said this because maybe i mess up a little so have patience with me

BigSlimLast Tuesday at 8:14 PM
or github desktop
everone has patience

LucianoLast Tuesday at 8:15 PM
:smiley:

BigSlimLast Tuesday at 8:15 PM
Next up is a long standing github PR https://github.com/aeonix/aeonix.github.io/issues/34
GitHub branding pack · Issue #34 · aeonix/aeonix.github.io
the reddit sidebar includes a link to a branding pack which is hosted on dropbox. I don't know who uploaded it there but I think it should be reuploaded to this github and also linked to github...

Aeon branding pack update
Currently, its Aeon lifestyle

Luke_ClashProjectLast Tuesday at 8:15 PM
@Luciano add your files to the cache, usually done via git add * then create a commit to the current branch git commit -m "your message" and afterwords push it git push -u <link-to-your-git-repo> master
That's all!

BigSlimLast Tuesday at 8:16 PM
thanks luke

LucianoLast Tuesday at 8:16 PM
thnaks!

BigSlimLast Tuesday at 8:17 PM
In regards to the branding pack, Currently we do not have anyone with some graphic design background that has stepped in to say they could make a new branding pack for Aeon
We have wanted to change the tagline to " Aeon, A lightweight digital currency " from the current "AEON isn't just a currency.
It's a lifestyle"
Does everyone agree that we should change the tagline to "Aeon, A lightweight digital currency" ?
we can still live the aeon lifestyle

420CoupeLast Tuesday at 8:19 PM
What was the reason against a liteweight private digital currency?

Luke_ClashProjectLast Tuesday at 8:20 PM
Could do that in like five minutes, if that's all you want. Just hit me up later on, it's 3AM for me right now.

About the tagline, I don't think it should contain a comma. What about a dash instead?

BigSlimLast Tuesday at 8:20 PM
Here is what i've been using for Medium posts that I edited

420CoupeLast Tuesday at 8:21 PM
also think it should be a play on Lite from CN-Lite

BigSlimLast Tuesday at 8:21 PM
jwintern opened this pr back in February : https://github.com/aeonix/aeonix.github.io/issues/2
" GitHub Language in banner "
### AEON isn't a cryptocurrency. It's a lifestyle.

Luke_ClashProjectLast Tuesday at 8:21 PM
It's looking good, but the blue word was in the middle previously, now it's on the left side.

BigSlimLast Tuesday at 8:21 PM
@wowario (WOW)
SO using " Aeon a liteweight private digital currency "

cryptoziLast Tuesday at 8:22 PM
Agree 420Coupe, lightweight private..

BigSlimLast Tuesday at 8:23 PM
feel free to make a comment on the Git bug 2 for your thoughts on this branding name change
if you want to re-do the branding pack feel free to download and edit and post samples on the git bug 34 for the website
ok so moving on, some people have expressed their thoughts on the next network upgrade moving to CNv8 to match Monero https://github.com/aeonix/aeon/issues/72
GitHub
Aeon POW V8 / What about? · Issue #72 · aeonix/aeon
label:enhancement What about this encasement in future? Any movements?

is this something we want to do with the next fork?

420CoupeLast Tuesday at 8:24 PM
I'm more concerned with CT + BP

BigSlimLast Tuesday at 8:25 PM
that is next
Ring-CT and Bulletproofs
Both have to be done at the same time, so its like a package deal(edited)
I think the general consensus is that the Aeon community wants this on the next fork
No timeline has been set for implementing this

BMO-noireLast Tuesday at 8:27 PM
is there anything that can be done to help speed things up?

420CoupeLast Tuesday at 8:27 PM
Aside from porting over from current monero code what else is required?

BigSlimLast Tuesday at 8:28 PM
review of finalized code by most likely moneromooo
iirc he did the last rebase review when he had time available
along with CNv8, RingCT, and BP, there has been little to no discussion since  october 15 about removing ring size 1-4 and also possibly using a locked ring size : https://github.com/aeonix/aeon/issues/65
GitHub
Removal of Ring Size 1-4 and or using fixed Ring Size for Aeon · ...
There has been some discussion as to remove lower ring sizes to keep Aeon a fungible digital currency ( https://www.reddit.com/r/Aeon/comments/9mwj5p/removal_of_0_mixing_as_and_when_bulletproofs/ )...

420CoupeLast Tuesday at 8:31 PM
not sure if smooth or stoffu had mentioned the other day that the reduced cost would be amplified once CT + BP was implemented
What i vote for is to have ring size 1-4 only be allowed of 5% max of each block

BigSlimLast Tuesday at 8:31 PM
Smooth and Stoffu stated some research needed to be done if locking ring size at say 5 or 7 or 3 would cause any bloat of the chain or if 3/5 would be enough to keep Aeon Fungible as a privacy coin
if using 1-4 still, would that reduce privacy and fungibility of Aeon?

420CoupeLast Tuesday at 8:33 PM
if combined only allowed at that % im not sure. Is this something we can bounty out to MRL to do a study ?

BigSlimLast Tuesday at 8:34 PM
Do we as a community need to source a reputable source like sarang to research all of this?
or has the research been completed or even started by smoth/stoffu?

420CoupeLast Tuesday at 8:35 PM
dont really care who it goes to
just someone reputable

BigSlimLast Tuesday at 8:35 PM
I think we need to get smooth/stoffu input for this before moving forward
see what already HAS been researched
so consensus - see what has been done and if needed source to MRL for bloat post ringCT/BP implementation
??

cryptoziLast Tuesday at 8:37 PM
From memory Samsung Galaxy made some comments on GitHub re this..
For Aeon..

camthegeekLast Tuesday at 8:37 PM
sgp does have some information available. Some of it is related to when Monero was pre-ringct like aeon.

BigSlimLast Tuesday at 8:38 PM
we need to know post ring CT though since it would not be implemented before that
would want to avoid another fork for just this if we had to fork to lock ring sizes ect...
@samsunggalaxy "Ranked in terms of best to worst for 7 and (then) 5:" in regards to ring sizes
"I do not recommend mandatory ringsize 3 after looking at the current distribution. Aeon has a healthy number of ringsize  4 transactions that help thwart basic analysis."
stoffu's response " As far as I can see in the chart, since mid 2018, the majority of ring sizes being used is dominated by 4, then by 3, and then by 1. Other ring sizes, including 5, have been next to negligible throughout the whole history."
OK, moving on next topic: how to spread the word for aeon
This is one of those "grow organically" deals
Any community thoughts on this?

cryptoziLast Tuesday at 8:44 PM
Binance listing could help spread the word :) was surprised to read your comment their fee was only 2 BTC
Shigutso pooltupi.comLast Tuesday at 8:44 PM
I have to go to sleep, but I'll read e everything later. To spread the word, I would try to talk about Aeon in more crypto forum by mentioning Monero, which is familiar

cryptoziLast Tuesday at 8:44 PM
Agree

BigSlimLast Tuesday at 8:44 PM
ok thanks @Shigutso pooltupi.com you have brought many new faces to this discord
aeon 1

camthegeekLast Tuesday at 8:45 PM
Of course market listings would help spread word, however, what things could be done on a lower budget?

BigSlimLast Tuesday at 8:46 PM
lower budget as in < $100

420CoupeLast Tuesday at 8:46 PM
integration into merchant services?
at least get our named mentioned
or pay for some fluff pieces from likes of CT etc

BigSlimLast Tuesday at 8:46 PM
$10,000 to list on coinpayments.net
then it is the process trying to get merchants to add the widget to their site

cryptoziLast Tuesday at 8:47 PM
Fair enough think we likely have some large bagholders who'd be willing to fund something like that. Also mean we not relying on one decent exchange, Bittrex

BigSlimLast Tuesday at 8:47 PM
If Binance is truely free to list now (or at least not $10k) I would not have a problem contacting them for this.
need to set up an account for that

cryptoziLast Tuesday at 8:50 PM
Even if $10k worth giving community a chance. Nothing to lose in contacting them

BigSlimLast Tuesday at 8:50 PM
Marketing ideas from the community ?
Is there interest in Kraken?
or Cryptopia
HitBTC
TradeSatoshi/ Yobit
Liquid?
Bigmarkets.io

Shigutso pooltupi.comLast Tuesday at 8:52 PM
it would be great to fix aeon on hitbtc... that could be a priority but I know they are difficult to talk to

BigSlimLast Tuesday at 8:52 PM
Blocktrades?
HitBTC is not difficult to talk to, they work on their own time
All exchanges work on their own time since their reputation and money is also at stake

camthegeekLast Tuesday at 8:53 PM
HitBTC has been a headache to deal with but we've made some progress with them.

BigSlimLast Tuesday at 8:53 PM
It just takes time
plus community interest also helps(edited)
not asking to spam their twitter account, but if more members of the community voiced their opinion, it would speed up the process

cryptoziLast Tuesday at 8:54 PM
Binance worth a try, and if Cam can add a Monero donation address to AFS, so no need to dump Aeon

BigSlimLast Tuesday at 8:55 PM
@camthegeek thoughts on adding non Aeon payments to AFS?

camthegeekLast Tuesday at 8:56 PM
It can be done but funds would not be tracked easily. If there were a service we could do XMR->BTC without needing a minimum amount, then it's absolutely do-able.
By tracked, I simply mean accounted for on the proposal.
bad words to use on a privacy coin!  lol

cryptoziLast Tuesday at 8:57 PM
Hah

BigSlimLast Tuesday at 8:57 PM
xmr.to

cryptoziLast Tuesday at 8:57 PM
Sounds good

camthegeekLast Tuesday at 8:57 PM
that goes xmr>btc

BigSlimLast Tuesday at 8:57 PM
works fine for me just like @aeonapi.com
heh
oh u mean BTC->XMR

mosu_forgeLast Tuesday at 8:58 PM
The funding system could be modified without a whole lot of work to track xmr as well

camthegeekLast Tuesday at 8:58 PM
correct it could

mosu_forgeLast Tuesday at 8:58 PM
But it would be a bit of a pain

BigSlimLast Tuesday at 8:59 PM
fyi the bitliber exchange has AEON<->XMR and soon LTC and ETH pairs
low volume though
good ideas here

camthegeekLast Tuesday at 8:59 PM
I'll look into being able to accept xmr and possible btc. each would be converted to aeon in the end since payouts are done in aeon.

BigSlimLast Tuesday at 9:00 PM
my only thoughts are that I think AFS should be funded to proposal holders as AEON, but payments incoming could be anything

mosu_forgeLast Tuesday at 9:00 PM
Or actually, you could make it simpler if you consider the donation in xmr to be converted to aeons value(edited)

BigSlimLast Tuesday at 9:01 PM
still need to track the opposing currency for proper conversion and it changes daily so amounts can change before funded
total value. so take the World of Ether proposal, its $5000

BMO-noireLast Tuesday at 9:01 PM
if the funding system was in $ it would probably be more useful right now..

BigSlimLast Tuesday at 9:01 PM
if you ask 17k Aeon today its about $5k, but in a month when funded it could be $6k
ok so lets move on to next few topics before wrapping up here
so consensus for marketing/ spread the word: Talk on forums about aeon if possible, Contact Binance for listing, community involvement with HitBTC for wallet updating, possibly add xmr/btc to AFS to attract additional funding
cam inquired about Request for devs with experience in any language

cryptoziLast Tuesday at 9:03 PM
BigSlim can you follow up with Binance?

BigSlimLast Tuesday at 9:03 PM
yea no problem. may be a few days here. EOQ at work and been off 5 days so need to catch up double time

cryptoziLast Tuesday at 9:03 PM
Great

BigSlimLast Tuesday at 9:03 PM
plus usually takes 3-5 business days for a reply post the auto reply
and its usually asking the same questions I already answered in inital email inquiry like the email was not read(edited)
no issues reporting back results

cryptoziLast Tuesday at 9:05 PM
Ta

BigSlimLast Tuesday at 9:06 PM
Aeon needs to attract some additonal multilanguage devs
if anyone knows members looking to help translate stuff or possibly work on core code feel free to let us know
Some updates on multi-asset wallet support
Monerujo-AE and Cake Wallet : looks like they are waiting to integrate any updates after the next Aeon fork so that Aeon is running the most up to date Monero code 13.0+

Luke_ClashProjectLast Tuesday at 9:08 PM
Multilanguage Devs? Which languages would you prefer? C family is necessary, but what other languages could be nice?

BigSlimLast Tuesday at 9:09 PM
anything at all honestly can help
if you have experience, hit up Stoffu or Smooth on IRC and or make some PR's that you think need changes

camthegeekLast Tuesday at 9:10 PM
There are dozens of projects out there already made that require fork-ing that AEON could benefit from. Those who understand whatever languages those projects are developed in could also use their skills to improve whatever project it may be.

BigSlimLast Tuesday at 9:11 PM
ios dev would be key

camthegeekLast Tuesday at 9:11 PM
In short, a few more to step up would be great!

BigSlimLast Tuesday at 9:11 PM
C++
nothing is written in golang iirc
for monero/aeon

Luke_ClashProjectLast Tuesday at 9:12 PM
Well, which languages are you talking about. Most aren't difficult to comprehend, just hilariously stupid to pick (golang as a slower, less fancy cpp alternative with less libraries)

BigSlimLast Tuesday at 9:12 PM
there are many android how-to's out there but I do not believe many have skimmed the android code
Luke_ClashProjectLast Tuesday at 9:13 PM
Android is plain java with some libraries

BigSlimLast Tuesday at 9:13 PM
yes
I do not have access to compile and test android, only ios

Luke_ClashProjectLast Tuesday at 9:13 PM
What's difficult about this one then, if you know java

BigSlimLast Tuesday at 9:13 PM
basically my testing is with VM
A side note for multiwallet support, Atomic wallet is looking into Aeon for integration currently.

Luke_ClashProjectLast Tuesday at 9:15 PM
Ah, okay. I think visual studio comes with a build-in VM. If I recall correctly you can embed something like that in Android studio as well. If you cant find these, your only other option is to use a VM, preferably an optimized on like bluestacks, yes

BigSlimLast Tuesday at 9:17 PM
So consensus for additonal language support is that Aeon needs to attract these tallents. I think this would be a good discussion for a reddit post or another meet up. How can the community attract this tallent?

Luke_ClashProjectLast Tuesday at 9:18 PM
Just grow or shrink. People usually support big or tiny projects, it looks like aeon is in this difficult phase right now

BigSlimLast Tuesday at 9:18 PM
Any other thoughts or discussion topics today?
beta testing aeon: anyone can beta test. Keep on the lookout for reddit/twitter/medium posts for beta testing the latest pre-release code
merging pr's in a timely manner: what is considered a timely manner?
aeon payment processors : is this in the future for aeon?

camthegeekLast Tuesday at 9:21 PM
I think the more important thing is, if you want AEON to grow, get involved. Every voice can lead to a destination.

Luke_ClashProjectLast Tuesday at 9:21 PM
Does aeon plan to move away from the Blockchain to make synchronisation be faster?

BigSlimLast Tuesday at 9:21 PM
agreed cam
aeon sync is very efficient compared to other CN projects

Luke_ClashProjectLast Tuesday at 9:22 PM
True, but you could improve it with a DAG

BigSlimLast Tuesday at 9:23 PM
currently; 10,000 blocks syncs in about 15 seconds

Luke_ClashProjectLast Tuesday at 9:23 PM
For example IOTA. You don't even have to sync the whole chain to mine the next "block".
I know, that's working differently, but if you just want to verify that one block is legit, you don't want to sync the whole chain
10'000 Blocks in 15 seconds? How is that possible? Isn't this like 200MB?

BigSlimLast Tuesday at 9:26 PM
:smiley:
it takes about 45minutes on SSD hardware and 4 core cpu to sync from scratch to sync over 1million aeon blocks post rebase
Aeon , A liteweight private digital currency
ok I think we will wrap it up here
Thank you everyone for visiting today for the 12_4_2018 Aeon Community Meeting

cryptoziLast Tuesday at 9:28 PM
Thanks guys

BigSlimLast Tuesday at 9:28 PM
NP

Luke_ClashProjectLast Tuesday at 9:29 PM
And that's the point I wanted to tackle, with the improvement I had in mind, you woulnt sync 1 million blocks (if you just wanted to verify that the last one is legit), you would sync 20.

420CoupeLast Tuesday at 9:29 PM
what are the downsides

IRC BridgeBOTLast Tuesday at 9:29 PM
<eamonnw> are blocks slow at the mo?

camthegeekLast Tuesday at 9:30 PM
probably. nethash dropped, diff is adjusting
