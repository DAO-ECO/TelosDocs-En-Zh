Telos 周报告- 2018年10月25日

我们今天就可以上线 Telos。

说完这句话后，让我们等一等。

我们确实今天就可以上线 Telos。 Telos 贡献者组中的不同 BPs 为检查不同的参数，已测试区块链上线几乎30次了。 我们顺利保持测试网络的最新阶段运行，超过1000万个区块和几乎1.5亿次交易。 这些数字已经比许多现有的高估值区块链都有更多的区块和交易。 所以今天就我们是否有可以上线 Telos 主网的能力，真的无可争议。 我们可以。

但我们还不会上线。

我们不会在今天或明天上线主网, 我们也不太可能在10月31日投票上线。 也许会吧，但我猜我们不会。 干嘛不呢？ 因为我们可能还有一个清单项目, 没有变成绿色。

一个！

Telos 贡献者小组承诺, 在所有承诺的功能就绪之前, 不启动网络。 所以, 如果我们有一个清单项目不是绿色的, 我们就不会上线。 这点让我很难受！ 明明我们可以上线, 但因为一个未完成的清单项目而不这样做，让我很难受。 但我知道这是正确的方式。

这个清单项目有关 "仲裁" 合同。 我希望在星期三的表决之前, 其他一切任务都能完成。 The ‘arbitration’ contract is a single contract that handles the election and management of Telos arbitrators, the filing of cases (currently 15 distinct types), the handling of messages between parties, evidence submission, arbitrator recusal, tribunal proceedings, rendering decisions, enforcement by the BPs, and preservation of cases for which there are not enough funds to collect. This is a BIG contract. (One that no one has managed to deliver yet.) For a little perspective, if the Telos ‘arbitration’ contract were a DApp, it would be one of the top 3 most complex DApps in EOSIO. It’s exciting to be working on this, but it’s also frustrating, because — have I mentioned — we could easily launch Telos tomorrow.

When we do launch (soon, I pinky-swear), we will deliver all of our promised pieces. Now, we may still have some pieces to improve, like enabling more voting options or adding web portals for submitting proposals — things like that. But these are just conveniences that we will add as we go along. Everything that we promised will be there at launch. We all agree that launching Telos with all our promises fulfilled is more important than launching tomorrow, more important than “being done”, more important that launching on Guy Fawkes Day (Remember, Remember the 5th of November!). And so we will keep working away. A little bit longer. Because standing behind your promises can be agonizing, but it’s always worth it.

— Douglas Horn

Checklist Updates at a Glance

Functional/In Testing → Complete & Tested

Telos Foundation System Agree upon ABP launch group Lost tokens processed (processing will continue until launch) Define final TLOS token balance (EOS snapshot + Rewards +/- lost/compromised keys) Here’s what we accomplished this week:

Testnet 2.6 reaches 10 million blocks, 149 million transactions, 48 BPs Telos ABPs selected Testnet relaunch and voting system improvements Telos key prefix changed (back) from TLOS to EOS More TIPs voted and introduced Telos Interim RAM Administration Director position paper Introducing TLOS: The Telos Token

1. Testnet 2.6 reaches 10 million blocks, 149 million transactions, 48 BPs

The Telos testnet is hitting big milestones. On Wednesday, EOS Green produced the 1- millionth block on this stage of the testnet. Even more impressive, that includes over 149 million transactions thanks to ongoing stress testing by J.T. Buice (Big Iron BP/Kainos). This number signifies Telos’ commitment to launching only with an established and resilient network in place. There are currently 48 block producers who have have either successfully produced blocks on the testnet or are in the process of being rotated in to do so.

2. Telos ABPs selected

The Telos white paper calls for six public appointed block producers (ABPs) to launch the Telos mainnet after a successful “Go” vote. For nearly two weeks, the Launch Directors (see last week’s report) have been running test launches and dialing in various tests. The current count for full network launch rehearsals is 28. Now six Telos BPs have either completed all the requirements or are in the late stages of completing them so that the ABPs who will actually launch the network have been selected. This is a crucial step towards launching the network. The Telos ABPs are Blindblocart (Seychelles), CalEOS (USA), EOS Barcelona (Spain), EOS Metal (Iceland), KainosBP (Texas), and Telos Venezuela (Venezuela). Congrats to all of the newly selected ABPs — our launch is in your very capable hands!

3. Testnet relaunch and voting system improvements

The code for the final Telos testnet, Stage 3, is complete and in the process of merging. Telos Testnet Stage 3 is scheduled to be launched by one of the ABPs from the launch rehearsal group next week. This is expected to be the version of the testnet that continues beyond launch for the foreseeable future. This version will bring several new improvements and features including the injection of the Telos genesis accounts and key-recovery accounts submitted to date. Telos community members will be able to join the network, find their accounts and build their confidence and excitement about the upcoming launch.

Craig Branscom (GoodBlock) has been leading the development team in refactoring the voting system being used on the ‘worker proposal’, ‘ratify.amend’, and ‘arbitration’ contracts. In the previous version of this system, Madalin Barbulescu (Amplified Telos) discovered that a loophole in the voting process would enable a member to vote multiple times in the same election cycle. This was eliminated by revisions from Craig, Madalin, Peter Bue and Ed Silva.

Ed Silva (GoodBlock) refined the ‘removebp’ feature which removes block producers for missing too many blocks (so that other BPs can cycle in and hopefully provide better operations for a period of time). Madalin Barbulescu, and the rest of the Telos development team contributed feedback towards the solution to many edge cases that were revealed in stress-testing.

The development team has also designed a new, more robust ‘eosio.system’ system to resolve the issue of latency in the blockchain that caused additional missed blocks to be calculated where none existed. Additionally, the ‘trail service’, ‘ratify.amend’, and ‘worker.proposal’ contracts are being merged to the source repository and the newly forked ‘eosio.contracts’ repository so that Telos is compatible with future upstream merges.

Marlon Williams (EOS Miami) designed a new user interface for the Sqrl wallet to streamline the Worker Proposal submission process. Users will be able to propose, read, and vote WPS proposals from the main Sqrl interface. Marlon is currently working on adding interfaces for the ‘ratify.amend’, ‘arbitration’, and generic TIP-5 token voting contracts so that they will be easily used through Sqrl after launch.

4. Telos key prefix changed (back) from TLOS to EOS

When the Telos project first began, we anticipated there would soon be dozens of similar EOSIO chains and that as a convenience to users, changing the public key prefix would allow easy identification of which chain keys belonged to. Now, due to coding changes by Block.One, Scatter, and others, it became clear that it will be more convenient for users to have Telos public keys start with the EOS prefix as key prefixes are soon to be changed altogether and only ‘EOS’ will be preserved as a legacy key prefix. There are more immediate advantages as well including better Scatter integration at launch. The new code will go into the testnet with the EOS prefix upon launch of Stage 3. In fact, the new (old?) key prefix is the main reason for relaunching the testnet.

5. More TIPs voted and introduced

Several Telos Improvement Proposals (TIPs) were proposed, voted on and withdrawn this week as the Telos Launch Group continues to propose changes to network governance and operations.

TIPs 15–19 were previously withdrawn from consideration by Ian Panchevre of Amplified Telos, who later requested a down vote on these TIPs as a formality for closing the proposal process. All TIPs were voted down with a vote of: Yes — 0, No — 30, Abstain — 0

Text: https://github.com/Telos-Foundation/tips/blob/master/tip-0015.md

TIP-23: Increase block producer inflation on a one year schedule. This sets a very focused schedule for additional inflation for block producers for BPs. Passed with a vote of: Yes — 28, No — 3, Abstain — 6.

Text: https://github.com/Telos-Foundation/tips/blob/master/tip-0023.md

TIP-27 Title: Creating a RAM reserve for RAM Administration. Introduced for consideration by Telos Foundation Interim RAM Administration Director, Jan Smit (Dutch EOS)

https://github.com/Telos-Foundation/tips/blob/master/tip-0027.md

TIP-28: Modifying the TLOS token economy. Introduced for consideration by Ian Panchevre (Amplified Telos).

https://github.com/Telos-Foundation/tips/blob/master/tip-0028.md

6. Telos Interim RAM Administration Director position paper

This paper by Interim RAM Administration Director Jan Smit (Dutch EOS) defines the roles of the RAM director and RAM advisory council and their obligation to establish fair and stable RAM prices on Telos. The document expands on the RAM specifications outlined in the Telos white paper by holding specific roles within the Telos Foundation accountable for maintaining a functional RAM pricing and distribution system.

Jan and Douglas Horn (GoodBlock) spoke for an hour on Telos Talks, Weds Oct. 24th about how RAM will work on Telos, how Jan’s office will work with block producers to limit speculation, and to vigorously debate the merits and concerns around Jan’s TIP-28 proposal. It’s required reading for anyone interested in RAM on Telos, especially prospective speculators.

Read the full document here: https://medium.com/@teloslogical/telos-interim-ram-administration-director-position-paper-ace4aaf7c467

See the Telos Talks show here:

https://www.youtube.com/watch?v=J_-O2CIe090

7. Introducing TLOS: The Telos Token

Read this comprehensive guide to the TLOS token to learn how to acquire TLOS and about the many ways they can be used and exchanged on Telos. The guide also explains about how TLOS tokens will be distributed to community members including launch group contributors and EOS genesis snapshot token holders. If you’re looking for one paper to share with friends about Telos, this is it!

Read the full TLOS guide here: https://medium.com/@teloslogical/introducing-tlos-the-telos-token-d6af451e161f

Join the Telos conversation and get more info!