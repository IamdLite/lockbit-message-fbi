![fbi-leak-countdown-lockbit](assets/image-fbi-leak-countdown.jpg)

-----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA512

## What happened. (Incident | Threat Analysis)

> On February 19, 2024 penetration testing of two of my servers took place, at 06:39 UTC I found an error on the site 502 Bad Gateway, restarted nginx - nothing changed, restarted mysql - nothing changed, restarted PHP - the site worked. I didn't pay much attention to it, because for 5 years of swimming in money I became very lazy, and continued to ride on a yacht with titsy girls. At 20:47 I found that the site gives a new error 404 Not Found nginx, tried to enter the server through SSH and could not, the password did not fit, as it turned out later all the information on the disks was erased.

Due to my **personal negligence and irresponsibility** I relaxed and did not update PHP in time, the servers had _PHP 8.1.2_ version installed, which was successfully penetration tested most likely by this [CVE](https://www.cvedetails.com/cve/CVE-2023-3824/) , as a result of which **access was gained to the two main servers where this version of PHP was installed.** I realize that it may not have been this CVE, but something else like **0day** for PHP, but I can't be 100% sure, because the version installed on my servers was already known to have a known vulnerability, so this is most likely how the victims' admin and chat panel servers and the blog server were accessed. The new servers are now running the latest version of _PHP 8.3.3_. `If anyone recognizes a CVE for this version, be the first to let me know and you will be rewarded.`

The problem doesn't just affect me. Anyone who has used a **vulnerable version of PHP keep in mind that your server may have been compromised**, I'm sure many competitors may have been hacked in the same way, but they didn't even realize how it happened. I'm sure the forums I know are also hacked in the same way via PHP, there are good reasons to be sure, not only because of my hack but also because of information from _whistleblowers_. I noticed the PHP problem by accident, and I'm the only one with a _decentralized infrastructure_ with different servers, so I was able to quickly figure out how the attack happened, **if I didn't have backup servers that didn't have PHP on them**, I probably wouldn't have figured out how the hack happened.

## Threat Intelligence

The FBI decided to hack now for one reason only, because they didn't want to leak information from [leaked data](https://fultoncountyga.gov/) the stolen documents contain a lot of interesting things and `Donald Trump's court cases` that could **affect the upcoming US election**.

> Personally I will vote for Trump because the situation on the border with Mexico is some kind of nightmare, Biden should retire, he is a puppet.

If it wasn't for the FBI attack, the documents would have been released the same day, because the negotiations stalled, right after the partner posted the press release to the blog, the FBI really didn't like the public finding out the true reasons for the failure of all the systems of this city. Had it not been for the election situation, the FBI would have continued to sit on my server waiting for any leads to arrest me and my associates, but all you need to do to not get caught is just **quality cryptocurrency laundering**.

The FBI can sit on your resources and also collect information useful for the FBI, but do not show the whole world that you are hacked, because you do not cause any critical damage, you bring only benefit. What conclusions can be drawn from this situation? Very simple, that I need to attack the .gov sector more often and more, it is after such attacks that the FBI will be forced to show me _weaknesses and vulnerabilities_ and make me stronger. By attacking the .gov sector you can know exactly if the FBI has the ability to attack us or not.

## Post Incident Activities 1

> Even if you **updated** your _PHP version_ after reading this information, it will not be enough, because you have to change the **hoster**, **server**, all possible **passwords**, **user passwords** in the _database_, **audit** the _source code_ and **migrate** everything, there is no guarantee that you have not been **hardened** on the server. There is no guarantee that the FBI does not have _0day_ for your servers about which they have already learned enough information to _re-hack_, so only a _complete change_ of everything that can only be replaced will help.

## Impact Analysis

> All other servers with backup blogs that did not have PHP installed are unaffected and will continue to give out data stolen from the attacked companies.

As a result of hacking the servers, the FBI obtained:

- A database
- Web panel sources
- Locker stubs

1. The locker stubs are not source as they claim and a small portion of unprotected decryptors, they claim 1000 decryptors, although there were almost 20000 decryptors on the server, most of which were protected and cannot be used by the FBI.

2. Thanks to the database they found out the _generated nicknames_ of the partners, which have nothing to do with their _real nicknames_ on _forums_ and even nicknames in _messengers_, not deleted chats with the _attacked companies_ and accordingly _wallets for money_, which will be investigated and searched for all those who do not launder crypto, and possibly arrest people involved in laundering and accuse them of being my partners, although they are not. `All of this information has no value because it is all passed to the FBI and without hacking the panel, after every transaction by insurance agents or negotiators.`

3. The only thing that is of _value_ and _potential threat_ is the **source code** of the _panel_, because of it is `probably possible future hacks` if you let everyone into the panel, but now the panel will be _divided_ into many servers, for verified partners and for random people, up to 1 copy of the panel for 1 partner on a separate server, before there was one panel for everyone.
   - Due to the separation of the panel and _greater decentralization_, the absence of trial decrypts in automatic mode, maximum protection of decryptors for each company, the chance of hacking will be significantly reduced.
     > `Leak of the panel source code was also happening at competitors, it didn't stop them from continuing their work, it won't stop me either.`

## Incidence Report | Disaster Recovery

The FBI says they received about 1000 decryptors, a nice figure, but it doesn't look like the truth, yes they received some unprotected decryptors, those builds of the locker that were made without the "maximum decryptor protection" checkbox could only be received by the FBI in the last 30 days, it's not known on what day the FBI got access to the server, but we know exactly the date of CVE disclosure and the date when PHP generated an error, before Feb 19th the attacked companies were regularly paying even for unprotected decryptors, so there is a chance the FBI were only on the server for 1 day, it would be nice if the FBI released all the decryptors to the public, then you could trust them that they really own the decryptors, not bluffing and praising their superiority, not the superiority of 1 smart pentester with a public CVE.

Note that the vast majority of unprotected decryptors are from partners who encrypt brute force dedicas and spam single computers, taking $2000 ransoms, i.e. even if the FBI has 1000 decryptors, they are of little use, the main thing is that they didn't get all the decryptors for the entire 5 years of operation, which number is about 40000. It turns out that the FBI were only able to get hold of 2.5% of the total number of decryptors, yes it's bad, but it's not fatal.

### Recovery Point Objective

> From this significant moment, when the FBI cheered me up, I will stop being lazy and make it so that absolutely every build loker will be with maximum protection, now there will be no automatic trial decrypt, all trial decrypts and the issuance of decryptors will be made only in manual mode. Thus in the possible next attack, the FBI will not be able to get a single decryptor for free.

### Entry Point

Probably, everyone has already noticed how beautifully the FBI has changed the design of the blog, no one has ever been given such honors, usually everyone just put the usual plug with the praise of all the special services of the world. Although in fact only one person from all over the planet deserves praise, the one who pentest my site and picked up the right public CVE, I wonder how much he was paid, how much was his bonus? If less than a million dollars, then come work for me, you'll probably make more with me. Or just come talk to me at tox `3085B89A0C515D2FB124D645906F5D3DA5CB97CEBEA975959AE4F95302A04E1D709C3C4AE9B7` remember that I always have an active **bug bounty** program and I pay money for bugs found. FBI doesn't appreciate your talents, but I do and am willing to pay generously.

> I wonder why the alpha, revil, hive blogs were not designed so nicely? Why weren't their deanons published? Even though the FBI knows their identities? Strange isn't it? Because with such stupid methods FBI is trying to intimidate me and make me stop working. The FBI designer should work for me, you have good taste, I especially liked the new preloader, in the new update I should do something similar, USA, UK and Europe revolve around my logo, brilliant idea, right there made me feel very good, thanks.

A couple of my partners were arrested, to be honest I doubt that very much, they are probably just people who are laundering cryptocurrencies, maybe they were working for some mixers and exchangers with drops, that's why they were arrested and considered my partners, it would be interesting to see the video of the arrest, where at their homes, Lamborghinis and laptops with evidence of their involvement in our activities, but I somehow think we will not see it, because the FBI arrested random people to get a certificate of merit from the management, say look there are arrests, we are not getting money for nothing, we are honestly working off taxes and imprisoning random people, when real pentesters quietly continue their work. Basssterlord is not caught, I know Basssterlord's real name, and it's different than the poor guy the FBI caught.

I don't know any military journalist from Sevastopol Colonel Cassad, and I never donated to anyone, it would be nice if the FBI showed the transaction so I could check on the blockchain where they drew such conclusions from and why they claim it was me who did it, I never do any transaction without a bitcoin mixer.

If I may have used the same cryptocurrency exchange service that someone from **Evil Corp** used it absolutely does not mean I have anything to do with Evil Corp, again where are the transactions? How do I know who is using which exchanger? I use different exchangers and I don't concentrate all my money on one **cryptocurrency exchanger**. Let's blame the hundreds of other people who use publicly available exchanges on Evil Corp.
I really dislike that all such throw-ins are made without publishing transactions and wallets, thus it is impossible to verify what is true. You can accuse me of anything without proving anything, and there is no way I can refute it, because there are no transactions and bitcoin wallets.

The FBI states that my income is over 100 million dollars, this is true, I am very happy that I deleted chats with very large payouts, now I will delete more often and small payouts too. These numbers show that I am on the right track, that even if I make mistakes it doesn't stop me and I correct my mistakes and keep making money. This shows that no hack from the FBI can stop a business from thriving, because what doesn't kill me makes me stronger.

### Threat Objective

> All FBI actions are aimed at destroying the reputation of my affiliate program, my demoralization, they want me to leave and quit my job, they want to scare me because they can not find and eliminate me, I can not be stopped, you can not even hope, as long as I am alive I will continue to do pentest with postpaid.

I am very pleased that the FBI has cheered me up, energized me and made me get away from entertainment and spending money, it is very hard to sit at the computer with hundreds of millions of dollars, `the only thing that motivates me to work is strong competitors and the FBI`, there is a sporting interest and desire to compete. With competitors who will make more money and attack more companies, and with the FBI whether they can catch me or not, and I'm sure they can't, looking at the way they work.

The FBI promised to publish my deanon but they didn't fulfill their promise, these people dare to lie about me supposedly not deleting stolen information of companies after paying the ransom, clowning around. It turns out that the FBI officially recognized themselves as liars and they lie very often, as my familiar lawyers Arkady Buch, Dmitry Naskavets and Victor Smilyanets stated, now I believe them 100%. They made a foolish attempt to discredit me by claiming that I work for the FBI, a man who encrypts US companies every day and makes hundreds of millions of dollars does it with the approval of the FBI? Is that how it works? Very clever.

### Mission Statement

> You're thinking, why would I work for hundreds of millions of dollars? And I will answer that I am just bored, I love my work, it brings me joy from life, money and luxury do not bring such joy as my work, that's why I am ready to risk my life for the sake of my work, that's how bright, rich and dangerous life should be in my opinion.

when I write the word FBI I mean not only FBI, but also all their assistants, who know how to arrest servers of partners, which act as the first lining after stealing data from the attacked company and do not represent any value: South West Regional Organized Crime Unit in the U.K., Metropolitan Police Service in the U.K., Europol, Gendarmerie-C3N in France, the State Criminal Police Office L-K-A and Federal Criminal Police Office in Germany, Fedpol and Zurich Cantonal Police in Switzerland, the National Police Agency in Japan, the Australian Federal Police in Australia, the Swedish Police Authority in Sweden, the National Bureau of Investigation in Finland, the Royal Canadian Mounted Police in Canada, and the National Police in the Netherlands. So please don't take offense, I haven't forgotten about you, you were also very helpful in this operation. But let me remind you that personally I think the only person who deserves an award and an honorable mention is the person who found a suitable public PHP CVE for my servers, I'm assuming it's someone from Prodaft.

---

## Links to Leaked Resouces

A list of backup blog domains that the FBI couldn't reach because they don't have PHP installed on these servers.

These servers host not only the companies that you can see on the main domain, but also many companies that have been handed over for manual download, i.e. links that are secret and published if the company refuses to pay the ransom, for example:
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/d8103cc7ba967d32a268d5cb3cff5b29/8x8.com
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/7bbed20cee2fef7f16def020b3690b0f/muellersystems.com
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/7b20fb8ef3064e45ce4954446cc6e858/boeing.com
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/c852ee1bccff6830b7316afb016be962/estes-express.com
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/a38cdf047c11d9a8cdcff00da7f62385/cityofclarksville.com
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/23f187fabd0681c79f1b0107275bdd27/esser-ps.de
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/8c877f8eae9e950552605a44f0485835/heinrichseegers.de
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/0fa4f7c543ddc8203f772322a2b0203e/hotelemc2.com
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/46216a24a00ccd4cdc6d96c7c82ebd69/roehr-stolberg.de
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/ab738d1822d63fa3e81193b75b89fb8b/roth-werkzeugbau.de
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/dd20772d156397072e50c5ce8af54994/schuett-grundei.de
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/0b8fe87adbd6a829b1af92bbb482f473/starkpower.de
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/8d1ff2c9e62ae75972b8371b789c8a69/thewalkerschool.org
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/b7f14428465e73416571d7f0ace4e1f8/unitednotions.com
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/cad65f46efbec2e5f1ab35d1b1d40b34/wombleco.com
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/2a366160a6eeba8ffb0d21d734148e57/gitiusa.com
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/70ef5f8ac50d8d7e09ad8c4478cff8e8/Good-Lawyer.com
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/12eee65c430a7f2a3a8317acb68b1303/aei.cc
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/secret/b946864a63e28e9177d4a5fe7834ed1d/carsonteam.com
http://lockbit7z2mmiz3ryxafn5kapbvbbiywsxwovasfkgf5dqqp5kxlajad.onion/secret/5c60836b0eccdc9845b9c9e278e0033a/dena.de/
These and many other companies have been saved, they will be published later in a new blog.

## Backup Mirror Links

Backup blog mirrors, any domain can be substituted for the secret links, in case any domain is overloaded from people wanting to download the stolen data:
http://lockbit7z2jwcskxpbokpemdxmltipntwlkmidcll2qirbu7ykg46eyd.onion/
http://lockbit7z2mmiz3ryxafn5kapbvbbiywsxwovasfkgf5dqqp5kxlajad.onion/
http://lockbit7z2og4jlsmdy7dzty3g42eu3gh2sx2b6ywtvhrjtss7li4fyd.onion/
http://lockbit7z355oalq4hiy5p7de64l6rsqutwlvydqje56uvevcc57r6qd.onion/
http://lockbit7z36ynytxwjzuoao46ck7b3753gpedary3qvuizn3iczhe4id.onion/
http://lockbit7z37ntefjdbjextn6tmdkry4j546ejnru5cejeguitiopvhad.onion/
http://lockbit7z3azdoxdpqxzliszutufbc2fldagztdu47xyucp25p4xtqad.onion/
http://lockbit7z3ddvg5vuez2vznt73ljqgwx5tnuqaa2ye7lns742yiv2zyd.onion/
http://lockbit7z3hv7ev5knxbrhsvv2mmu2rddwqizdz4vwfvxt5izrq6zqqd.onion/
http://lockbit7z3ujnkhxwahhjduh5me2updvzxewhhc5qvk2snxezoi5drad.onion/
http://lockbit7z4bsm63m3dagp5xglyacr4z4bwytkvkkwtn6enmuo5fi5iyd.onion/
http://lockbit7z4cgxvictidwfxpuiov4scdw34nxotmbdjyxpkvkg34mykyd.onion/
http://lockbit7z4k5zer5fbqi2vdq5sx2vuggatwyqvoodrkhubxftyrvncid.onion/
http://lockbit7z4ndl6thsct34yd47jrzdkpnfg3acfvpacuccb45pnars2ad.onion/

## New .onion domains

New domains of the main blog
http://lockbit3753ekiocyo5epmpy6klmejchjtzddoekjlnt6mu3qh4de2id.onion/
http://lockbit3g3ohd3katajf6zaehxz4h4cnhmz5t735zpltywhwpc6oy3id.onion/
http://lockbit3olp7oetlc4tl5zydnoluphh7fvdt5oa6arcp2757r7xkutid.onion/
http://lockbit435xk3ki62yun7z5nhwz6jyjdp2c64j5vge536if2eny3gtid.onion/
http://lockbit4lahhluquhoka3t4spqym2m3dhe66d6lr337glmnlgg2nndad.onion/
http://lockbit6knrauo3qafoksvl742vieqbujxw7rd6ofzdtapjb4rrawqad.onion/
http://lockbit7ouvrsdgtojeoj5hvu6bljqtghitekwpdy3b6y62ixtsu5jqd.onion/

## Business Continuity

---

Even after the FBI hack, the stolen data will be published on the blog, there is no chance of destroying the stolen data without payment. And after introducing maximum protection on every build of locker, there will be no chance of free decryption even for 2.5% of attacked companies.

New affiliates can work in my affiliate program if they have a reputation on the forums, can prove that they are pentesters with post-payment, or by making a deposit of 2 bitcoins, the deposit increase is due to proof and beautiful advertising from the FBI, which is that my affiliates and I earn together hundreds of millions of dollars, and that no FBI with their assistants can scare me and stop me, the stability of the service is guaranteed by years of continuous work.

Write tox 3085B89A0C515D2FB124D645906F5D3DA5CB97CEBEA975959AE4F95302A04E1D709C3C4AE9B7

> Why did it take 4 days to recover? Because I had to edit the source code for the latest version of PHP, as there was incompatibility.

Regards, LockBit.
February 24, 2024

-----BEGIN PGP SIGNATURE-----

iQGTBAEBCgB9FiEED/QWqWKNTn7Q9cGmBa++qhk4O2AFAmXaWU1fFIAAAAAALgAo
aXNzdWVyLWZwckBub3RhdGlvbnMub3BlbnBncC5maWZ0aGhvcnNlbWFuLm5ldDBG
RjQxNkE5NjI4RDRFN0VEMEY1QzFBNjA1QUZCRUFBMTkzODNCNjAACgkQBa++qhk4
O2DPrQf/cQgo9h2Giu8cChRpa+fej8nhvmyxTipDLkHf26pY69tsHg9GBbSuEJZa
NN6tbrB4xuL7S8zG5vG6pQlCV9encJFlOmKx0+RnDimMb5YsCROWT031m0NATCUN
2WNVkS3ilXtsuZnAYlVWbgU5U+5PYMSGa/Y6BFVmjcY7qPRj5jNZDhAvy9Ad9xC1
KpRQpJpgFb6yP2xIT8fy+BcpTBjOyAmRoxHjsVL7+HynMrFzywWpguv5g5beFv1r
ywHZP8yf1s/8sJcpRfSpBaRDI4JzJMy2zeKXztUTCVVK3qGeoPiTFeNKxKQ93axC
7X/YO757Mcca5X5bseGSEmK4ElGqYg==
=Jnpr
-----END PGP SIGNATURE-----

`Original Document` via [vx-underground](https://samples.vx-underground.org/tmp/Lockbit_Statement_2024-02-24.txt)
