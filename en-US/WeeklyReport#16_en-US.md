Telos Blockchain Network — Weekly Report — November 1st, 2018

Finding bugs now so they don’t find us later

The Telos Launch Group reconvened on Halloween to decide whether to launch Telos. Since there were still a few yellow dots on the launch checklist, we quickly voted NO. The next vote will be on November 7th. If you’re a close observer or good at math, you’ll notice that this is just one week after the previous launch, rather than two weeks. We’re close enough that it’s measured in single weeks. That’s progress, I guess.

Last week I shared my personal excitement and eagerness about launching Telos, but thank goodness we didn’t. After the vote, we experienced a bug on our Stage-net (a private testnet used solely to practice the launch or test new code prior to implementing it on the mainnet). Do we like new bugs? No. Would we rather find them before launch? Hell yeah. We’ve updated the development tag to version 2.7.1 and will hopefully be deploying a new testnet tomorrow. Yes, I’ve said that before. Almost every day for over a week. But again, we are squashing bugs. There’s a reason why great ideas like rotating BPs or removing those that aren’t producing are not yet implemented in the EOSIO code: they are hard and there are many potential pitfalls. That’s why we are running dozens of practice launch scenarios. How many is it up to now? I’ve stopped counting.

The TLG had a pretty big vote on Tuesday regarding TIP-24. It may not be popular with some people, but I do not want to bury it and hope no one notices. That is not in the spirit of transparency, which is a pillar of the Telos philosophy. So here goes, sharpen your pitchforks. The TLG voted to increase the Telos Founders Rewards Pool from 6 million TLOS to 18 million. That’s a big jump. Are we just “voting ourselves rich”? You can watch the video of the meeting which was live-streamed, as all our TLG meetings are, but let me offer a TL;DR. When I proposed Telos in July, the founders reward was 6 million TLOS. The expected time scale was also about six weeks and we expected just six ABPs to do all the core work. How did that turn out?

Here we are in November, looking to launch soon with over 120 contributors and a very large number of now fully-implemented and tested new features, plus the three almost-implemented or in-testing features. They took us a lot more work than we thought. We also have a novelette-worth of governance documents where we originally thought we would have a snappy little constitution. The act of creating these documents and features revealed their complexity to us. And now they are better than they would have been, by far. Like the bugs or exploits we discovered in the features, the holes in our governance revealed problems that we are lucky to be able to deal with now, rather that while the network is running. Of course, that does not mean that we won’t have problems after launch…just that we won’t have these problems.

So roughly ten times the number of very smart people that we originally expected have now worked for three times as long as I (foolishly? optimistically?) planned. And these people feel like for the value they are creating, more compensation is warranted. It’s hard to argue with this. For reference, consider that EOS raised $4 billion in an ICO and returned 90% of all tokens to the EOS token-buyer community. Worbli, another EOSIO chain preparing to launch raised an undisclosed amount in a private sale and is only returning 36% of their tokens to the EOS token-buyers. (Which they are absolutely free to do.) Telos, in contrast, raised not one penny in an ICO or private sale and even after this week’s self-voted pay increase (hey, Congress does it!) is returning 93% of the network value to the EOS token-buyers. The TLG is now going to receive 5% of the tokens with the balance going to the Telos Foundation for promoting the network, offering RAM grants, providing liability insurance and bootstrapping funds for our arbitrators, providing the first 1 million new user accounts for free, and similar promotional and operational purposes. A 5% “pre-mine” for the founders is pretty low for any blockchain project, especially in these heady ICO days. But the TLG is aware that the network exists for the users and we don’t intend to make this a habit.

Progress continues at a pace much faster than what’s reflected on the Checklist at the moment. We are finishing everything, pushing the limits so that problems show up now instead of on the live chain. We are close to launching — so close it hurts. That doesn’t mean we’re certain to launch on November 7th. But we might. Keep watching those checkmarks!

— Douglas Horn

Here’s what we accomplished this week:

Telos Network Launch ‘Go/No-Go’ Vote FINDEX to list EOS/TLOS TIP Updates Development Updates IPFS Cluster Established Community Rewards Program Submissions Sharedrop Token Recovery Submissions New Website and White Paper Translations

1. Telos Network Launch ‘Go/No-Go’ Vote

The TLG voted ‘no-go’ on launching the network on October 31, 2018 with a vote of: Yes-1, No-23. As with the previous ‘go/no-go’ vote, the decision was made because not all of Launch Checklist items are completed. The next vote is scheduled for November 7th.

Watch the most recent Go/No-Go vote here: https://www.youtube.com/watch?v=5b3fVxTa2RY

View the Launch Checklist here: https://telosfoundation.io/launch

2. FINDEX to list EOS/TLOS

FINDEX, a decentralized exchange built on EOS.IO, will list a TLOS/EOS trading pair. The DEX features a customizable trading platform that easily integrates into DApps and wallets.

Read the full press release here: https://medium.com/@teloslogical/press-release-telos-to-list-on-findex-e73025ac7839

3. TIP Updates

The Telos Launch Contributors spent much of this week discussing several TIP submissions, revisions, votes and retractions, which lead to larger conversations about voting and governance processes within the group. TIP-24 increases the Telos Founders Rewards Pool from 6 million to 18 million TLOS due to the larger number of contributors and much longer time scale than originally anticipated. TIP-3 establishes that Telos will provide ongoing snapshots of the Telos “original” snapshot 29 days after activation and ongoing recent snapshots as the network progresses. The aim of this is to provide a central repository to preserve system resources and not place the burden of snapshots on the Dapps performing airdrops. This is expected to greatly reduce the cost of performing full airdrops on Telos, especially in conjunction with the features of TIP-5 standard tokens. The TIP-5 token standard was also formally adopted. It has been in use for nearly two months on the Telos testnet and EOS mainnet. TIP-27 proposes giving the Telos Foundation RAM Administration Director the ability to purchase RAM early and release it to the network later in order to avoid an initial spike in RAM prices. It was defeated but will be re-voted in a revised form on Friday, November 2.

Read the full October 26th report on TIPs 24–26 here: https://medium.com/@teloslogical/press-release-tips-report-for-october-26-2018-99e65917a9cb

TIP-03. Establishment of common-use snapshots for airgrabs. Approved with a vote of: Yes-27, Abstain-6, No-0.

https://github.com/Telos-Foundation/tips/blob/master/tip-0003.md

TIP-05: Single Token Registry Standard. Passed with a vote of: Yes-27, No-0, Abstain-0.

https://github.com/Telos-Foundation/tips/blob/master/tip-0005.md

TIP-27: A controlled RAM launch on Telos. Not approved with a vote of: Yes-20, Abstain-11, No-4.

https://github.com/Telos-Foundation/tips/blob/master/tip-0027.md

4. Development updates

Calculating missed blocks v.2 has been implemented by Ed Silva and is being tested by the launch directors and ABPs. If deemed acceptible, this will add a new green checkmark to the launch page.

A bug was discovered during a Stagenet test that caused issues with schedule production, and was actually the side effect of another bug in which ‘onblock’ fails to execute under specific conditions. Ed Silva and Peter Bue of GoodBlock and Madalin Barbulescu of Amplified Telos resolved the issues by creating a new ‘dev2.7.1’ release.

The Telos development team is currently merging system contracts into the newly forked ‘eosio.contracts’ repository. This new repository uses the ‘eosio.cdt’. The most recent release of the EOSIO CDT has many breaking changes. This shift to the ‘eosio.contracts’ repository will require the Telos developing team to refactor our contracts. However, this should be a one-time change that puts the Telos code in a position for faster code updates going forward.

5. IPFS Cluster Established

Several Telos contributors are working on implementing IPFS — the interplanetary file system, which is a blockchain-friendly form of decentralized yet secure storage. This has been expected on EOSIO for some time, but is not yet implemented. Because several Telos governance functions such as worker proposals and ratify/amend proposals require IPFS, TLG members are working to implement it now. This will be an enormous benefit to Dapp developers who are also eager to have this tool at their disposal.

Marlon Williams of EOS Miami first implemented an IPFS server in order to implement and test voting features in the Sqrl wallet. Stephanie Sunshine of GoodBlock started an IPFS cluster on its local network of 8 nodes that all interconnect, propagate and heal correctly. IPFS can be created as single instances, clusters, or clusters of clusters. Marlon and Stephanie have created single instances and now clusters. Stephanie is currently developing an EOSIO-friendly process for building a “cluster of clusters” to which many Telos BPs and others may connect nodes and clusters. This will give Telos a functional and robust IPFS implementation that no other EOSIO chain currently has.

Learn how to join the Telos IPFS testnet here: https://gist.github.com/StephanieSunshine/92a3af3fc8577103906ff8142a4349f5

6. Community Rewards Program Submissions

Note: The sign-up time for the Telos Community Rewards Pool program will be ending Nov. 6th.

If you are participating in the Telos Community Rewards Pool program, make sure that you are properly compensated for your time and efforts to spread the word about Telos. After the Telos network is activated, participants will have one week to compile their logged contributions into a single submission form that will be available on the Community Rewards Program web page.

Learn more about the Community Rewards Program here: https://telosfoundation.io/rewards

Check out the Telegram channel to ask questions, resolve technical issues, and meet other community members: https://t.me/teloscommunityrewardsgroup

7. Sharedrop Token Recovery Submissions

Are you an EOS genesis snapshot token holder but lost your keys or otherwise had them compromised? Fortunately, you can still get your Telos sharedrop through our token recovery program. Submissions have nearly doubled in the last week, so make sure that you sign up before the program ends at the network launch date.

Read more about Token Recovery here: https://telosfoundation.io/recovery

8. New Website and White Paper Translations

Translating important organizational documents is critical to expanding Telos’ global community. The Telos Launch Group recently released website translations in Spanish, Portuguese and Russian, and translated the white paper into Russian as well.

Check out the Telos Foundation website, which has now been translated into 10 languages: https://telosfoundation.io/