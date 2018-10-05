# Telos区块链网络运行协议(TBNOA)

## 1.序言

本文的目的是在所有Telos区块链网络用户之间建立共同的协议, 以便实现一个安全、稳定和可控的区块链。在这里价值和信息可以被存储, 所有争端都只需要使用本文和“Telos治理文档”中所述的方法而得到仲裁.它包括本协议,Telos区块链网络仲裁规则和过程, Telos"regproducer"合同人类语言术语, Telos"regarb"合同人类语言术语,Telos区块生产者最低要求, Telos仲裁员最低要求和Telos区块链网络的数据保护政策。 Telos区块链网络由一群选择使用区块链作为价值、信息和商业的跨国交易形式来进行自我组织的成员们组成。 Telos网络已同意通过Telos区块链网络运行协议(本“协议”)来管理Telos区块链、交易和本地通证，该协议列举了一套用户之间相互代理和协议的集合。

## 2. 法律选择

任何使用Telos区块链网络存储、交换或处理价值或信息的个人或实体在本协议中称为“成员”。各成员同意仅受本协议条款或根据本协议条款批准或修订的最新Telos区块链网络运营协议的约束，并在交易时选择当前协议的条款作为它们之间关于存储在Telos区块链上的任何价值及信息交互的约束。 每个成员都有责任遵守当地的法律和法规。

## 3. 价值和信息的记录

Telos区块链将会用来记录价值和信息，并执行与这些相关的计算。 这些信息会记录在连续的区块和加密安全信息中，这些信息由网络上的计算机节点测试和验证。

## 4. 帐户

每个成员可以控制区块链上的一个或多个帐户。 帐户记录各种通证和资源的所有权, 并由密钥控制。 帐户可以发布智能合约, 包括发行新通证的合约。

## 5. 本地价值单位

在Telos区块链上的本地价值单位为 TLOS 令牌。 每个 TLOS 通证代表Telos区块链系统资源的使用百分比, 这与区块链上记录的 TLOS 通证的总数有关。 作为系统资源使用权限的比例百分比, 每个 TLOS 通证将赋予持有它的帐户相应比例的投票权和使用Telos区块链运行计算机资源的权利。

## 6. 区块链的操作和执行

Telos区块链中的价值和交易记录使用委托股份证明机制达成共识，即主验证节点(“区块生产者”)和备用验证节点(“备用区块生产者”)是由TLOS通证的持有者的投票选出。他们作为代表，根据作为EOSIO软件分支的Telos的技术规格，处理和验证区块链中的交易和区块。

## 7. 修改区块链

只有当区块生产者就包含它们的区块的有效性达成最终一致意见时，Telos区块链上的交易才不可逆。 一旦2/3 的区块生产者提出了一个区块是有效的, 一个额外的区块生产者接受了提议的有效区块, 那么它应被视为一个“不可撤销的区块”。Telos区块链将永远不会修改任何不可撤销的区块。 对区块链的修改只能通过拒绝尚未被接受为不可撤销的区块以及在当前区块中添加新信息来完成。

## 8. 区块生产者提名、资格和选举

任何Telos成员可以通过执行“regproducer”合约并接受其人类语言条款，以自荐为区块生产者的候选人。 Telos区块链对于成为区块生产者或备用区块生产者的有一个最低要求列表(“区块生产者最低要求”)。 当前获得最高权重票数且满足区块生产者最低要求的21个区块生产者候选人会成为区块生产者。 当前满足区块生产者最低要求，但没有获得最高权重票数的的30个区块生产者候选人，应作为备用区块生产者。 区块生产者最低要求的通过“enforcebpmins”合约强制执行。

## 9. 区块生产者的功能

区块生产者们应按照Telos区块生产者最低要求运行计算机和网络设备。 区块生产者应按照“regproducer”合约的人类语言条款所规定的时间表来生产区块。 作为Telos区块链的执行机构，区块生产者们对Telos区块链拥有广泛的行政权力。 他们可以暂停Telos区块链，进行软件更新，发行新的通证，在不违反协议的情况下对区块链执行附加的运行规则，并通过以2/3+1区块生产者的多数票通过的方式执行适当处理的仲裁命令。

## 10. Block Producer Pay

Block Producer and Standby Block Producers shall be paid each day from a daily fund consisting of the daily share of 1% annual inflation of the entire value of the Telos blockchain as measured in TLOS tokens. Every day, this total amount shall be allocated such that each Block Producer receives the same pay for the time spent as a Block Producer as every other Block Producer and each Standby receives pay that is half of the rate of each Block Producer for its time spent as a Standby, with the provision that Block Producers and Standby Block Producers may have their daily pay allotment deducted in proportion with the percentage of blocks they were expected to produce in their most recent production period of 180,000 blocks (approximately 24 hours) or fewer, but failed to produce. Loss of pay from failing to regularly execute the "claimrewards" action, shall be borne by the Block Producer or Standby Block Producer, not the network.

## 11. Binding Arbitrations

All Members of the Telos blockchain agree to be bound to binding arbitration by Members elected by the votes of the TLOS token holders to serve this function ("Elected Arbitrators"), or by other arbitration forums that Members freely agree upon except where both parties of a transaction explicitly choose to waive such arbitration. Members expressly waive all rights to have matters pertaining to value or information stored on the Telos blockchain decided in a court of any terrestrial jurisdiction. Any dispute arising out of or in connection with this Agreement, including any question regarding its existence, validity or termination, shall be referred to and finally resolved by arbitration by one or more Telos Elected Arbitrators in accordance with the Arbitration Rules of the Telos Blockchain Network Arbitration Rules and Procedures for the time being in force, which rules are deemed to be incorporated by reference in this clause. Other arbitration forums may be used under that forum's rules when freely selected by both parties at the time of contract execution, and when the dispute does not question the existence, validity, or termination of this Agreement. Any dispute questioning the existence, validity, or termination of this Agreement must be resolved by arbitration by one or more Telos Elected Arbitrators in accordance with the Arbitration Rules of the Telos Blockchain Network Arbitration Rules and Procedures for the time being in force, which rules are deemed to be incorporated by reference in this clause.

## 12. Arbitration Exclusions

Waiving of arbitration waives all forms of dispute resolution; it does not invite terrestrial jurisdictions to arbitrate transactions on the Telos blockchain. Neither Elected Arbitrators nor Block Producers are required by this Agreement to fulfill the orders of any terrestrial jurisdictions in the operations of the Telos blockchain.

## 13. Selection of Arbitration Forum

The parties to each transaction on the Telos blockchain may select an arbitration forum when each party freely elects to use the same arbitration forum. If no election for a common alternative forum is so recorded in the transaction, then the arbitration forum shall be the Elected Arbitrators.

## 14. Elected Arbitrator Nomination, Qualification, and Election

Any Telos Member may self-nominate as a candidate to be an Elected Arbitrator by executing the "regarbitrator" contract and accepting the its human-language terms. The Telos blockchain maintains a list of minimum requirements for acting as an Elected Arbitrator (the "Elected Arbitrator Minimum Requirements"). The number of Elected Arbitrators at any time and the method for deciding the terms under which some number of Elected Arbitrators will be assigned to each arbitration case shall be decided by the most recent 2/3+1 vote of all Block Producers. The arbitrator candidates currently in compliance with the Elected Arbitrator Minimum Requirements and receiving the highest weight of Member votes shall serve as Elected Arbitrators. Enforcement of compliance with the Elected Arbitrator Minimum Requirements shall be by the "enforcearbmins" contract.

## 15. Arbitration Rules and Procedures

The Telos Blockchain Network Arbitration Rules and Procedures document describes the rules and procedures for arbitration.

## 16. Freezing Accounts Under Arbitration

Upon assignment of an Elected Arbitrator(s) to an arbitration case, any Assigned Arbitrator may issue an emergency order to freeze all transactions from the Respondent account. The Assigned Arbitrator may add the account to a list of frozen accounts (the " Telos Blacklist") maintained on the Telos blockchain, which all Block Producers shall reference and exclude from validating transactions.

## 17. Execution of Arbitration Decision

An Assigned Arbitrator(s) in a case shall render their arbitration Decision in the form of a transaction or set of transactions to be appended to the Telos blockchain by the duly elected Block Producers at the time the Decision is rendered. The transactions shall be in the form of a standard value transfer transaction from Respondent to Plaintiff, a "revisecontract" action which forcibly adjusts the code of a faulty or misleading contract, or a "changekeys" action which assigns new private keys to an account that has been adjudicated to have been improperly acquired by Respondent from Plaintiff. The Assigned Arbitrator(s) shall also provide a public explanation of the rationale for the Decision. The arbitration Decision may include transactions to pay the arbitration Fee associated with the case.

## 18. Enforcement of Arbitration Decisions

Block Producers, having been duly provided with a valid arbitration Decision as defined in the Telos Blockchain Network Arbitration Rules and Procedures Document, shall fully enforce the Decision within 180,000 blocks (approximately 24 hours) of receipt. Every Block Producer shall be required to enforce the action and any Block Producer that has not enforced the action within 180,000 blocks (approximately 24 hours) shall be liable for penalty under the "enforcebpmins" action until the adjudication action is fully enforced.

## 19. Restrictions on the Use of Sudo Powers

The Block Producers have the authority to use the "sudo" command to execute commands on an account as if by the owner, or a similarly-powered "super user" command if under a different name, only as an element of the "revisecontract" action which forcibly adjusts the code of a faulty or misleading contract, or a "changekeys" action which assigns new private keys to an account that has been adjudicated to have been improperly acquired, and only in cases of an adjudication Decision entered by an Assigned Arbitrator(s) in due process of a bona fide arbitration case. In the event that a Block Producer becomes aware of an apparent theft in action, that Block Producer may use sudo powers to freeze an account for up to 180,000 blocks (approximately 24 hours). After this time, the sudo freezing action shall expire or be removed by the Block Producer unless an Elected Arbitrator issues an order extending the freeze action.

## 20. Voting

Telos Members may vote to elect block producer and arbitrator candidates as described in this Agreement. Each Member may vote the entire number of TLOS tokens in any account they control via private keys. Members may vote for up to 30 block producer candidates and 30 arbitrator candidates at any time and each vote for any candidate will share the same weight as that of all the other candidates of the same type, either block producer or arbitrator candidates candidates. All votes, whether cast directly or by proxy shall have their voting weight reduced according to a non-linear equation known as inverse-weighted voting, as expressed in the Telos code, whereby the value of a vote is reduced when fewer than the maximum amount of allowed candidates are cast.

## 21. Proxies

Members may delegate their votes to another Member as a voting proxy ("Proxy") using the "proxy" contract included in the EOSIO software. Only a token's true beneficial owner or a voting Proxy recorded on the blockchain may vote tokens. Any Member holding tokens in trust for another beneficial owner, such as a centralized exchange, may not cast votes for or assign to a Proxy such tokens.

## 22. Initial Token Allocation

The initial distribution of TLOS tokens on the Telos network ("Telos Initial Distribution") will follow the EOS ERC-20 token snapshot as recorded June 2, 2018 from records of the EOS tokensale as recorded on the Ethereum blockchain (the "EOS Snapshot") on a 1:1 basis. The Telos Initial Distribution will create all accounts that were included on the EOS Snapshot with the same account names and public keys that match except that the prefix "TLOS" may be used instead of "EOS". These accounts will each be recorded as having the same number of TLOS tokens as the number of EOS on the corresponding account in the EOS Snapshot, except that each account that has a balance of over 40,000 tokens will receive exactly 40,000 TLOS tokens. EOS token holders who provide cryptographically signed messages requesting new keys for their accounts in the publicly documented process shall have their keys changed up until the time of network launch. New Telos accounts will be created to fund the Telos Foundation which will receive 6,000,000 TLOS tokens, the Telos Founders' Rewards Pool which will receive 6,000,000 TLOS tokens, the Telos Community Rewards Pool which will receive 1,000,000 TLOS tokens, and the Telos Exchange Tokem Reserve Fund which will receive 140,279,973 TLOS tokens. No value was accepted in exchange for tokens in the Telos Initial Distribution. No value was accepted in exchange for tokens in the Telos Initial Distribution.

## 23. Requirement to Opt-in as a Member

The Telos Initial Distribution will include all accounts from the EOS Snapshot. However, it is unknown which EOS Snapshot account owners may wish to opt in and become Members of the Telos network. Because all token holders must agree to become Members by accepting the mutual representations of this Agreement, accounts that have no transactions 63,000,000 blocks (approximately 365 days) after the activation of the Telos network are subject to deletion by the Block Producers at that time or in the future, provided no transactions have yet been made. Tokens in any deleted accounts will be deleted from the blockchain.

## 24. Worker Proposal Fund

A value equal to the daily share of 1.5% annual inflation of the entire value of the Telos blockchain as measured in TLOS tokens shall be deposited to an account on the Telos Network with the account name of "eosio.savings" (the "Worker Proposal Fund") each day.

## 25. Worker Proposal Submission

Any Telos Member or group of Members may submit proposals for the usage of these accumulated funds by executing the "submission" action of the "workerproposal" contract (the "Proposer") and providing the required information including, at least, a full description of the proposal, a link to a fixed source of information, and the exact deposit transaction, including deposit account or accounts, that will occur should the proposal be accepted by the Telos Members.

## 26. Worker Proposal Voting Period

Once a proposal is submitted, there will be a period of 5,000,000 blocks (approximately 29 days) in which a proposal may be voted (the "Voting Period").

## 27. Worker Proposal Submission Fee

A submission fee of 3% of the requested amount with a minimum of 50 TLOS will be required as part of the submission. The fee shall be refunded to the Proposer if the worker proposal reaches a minimum threshold of 20% YES vote amongst all votes and a minimum voting total (YES or NO) of at least 0.1% of all TLOS tokens at the end of the Voting Period.

## 28. Passage of a Worker Proposal

Any Worker Proposal that receives a simple majority of YES votes and a minimum threshold of 5.0% of votes from all votable TLOS tokens at the conclusion of the Voting Period shall be an "Accepted Proposal."

## 29. Execution of a Worker Proposal

Each Accepted Proposal shall have the transaction described in the proposal execute immediately, provided sufficient funds exist in the Worker Proposal Fund account. If sufficient funds do not exist, transactions from Accepted Proposals will be queued to execute as soon as the Worker Proposal Fund account accumulates sufficient funds, in the order accepted. Accepted Proposals that include multiple cycles will recalculate the total votes and percentage tally at the beginning of each new cycle of 5,000,000 blocks (approximately 29 days). Proposals that continue to qualify will again be funded at the beginning of the new cycle. Proposals that no longer qualify will not be paid for that cycle, but may be paid in a future cycle, up to the number of cycles listed in the initial proposal. Voters may change or withdraw their vote from any proposal at any time.

## 30. Failure to Provide Worker Proposal Deliverables

The Block Producers may, by 2/3+1 majority vote, elect to file an arbitration case against the Proposer on behalf of the Worker Proposal Fund account to reclaim some or all of the disbursed funds from an Accepted Proposal that has been executed, but where the proposed work appears not to have been performed as described in the Proposal. The arbitration will proceed with Telos Elected Arbitrators and any Decision will be transmitted to the Worker Proposal Fund account.

## 31. No Fiduciary

No Member shall have fiduciary responsibility to support the value of the TLOS token. The Members do not authorize anyone to hold assets, borrow, nor contract on behalf of the Members collectively. The Telos Blockchain Network has no owners, managers nor fiduciaries.

## 32. Publication to the Telos Blockchain

Each Member grants all other Members an irrevocable license to view transactions as recorded and published to the blockchain.

## 33. Responsibility for Information

The Telos Network shall bear no responsibility or enforcement role for any information, data, or content improperly recorded on the blockchain. Any penalties or Decisions for improperly recorded information, data, or content shall be the sole responsibility of the Member that posted it.

## 34. Restitution

Each Member agrees that penalties for breach of this contract may include, but are not limited to, fines, loss of account, and any other measures decided by Elected Arbitrators as defined in this Agreement.

## 35. Developers

Each Member who makes available a smart contract on the Telos blockchain (a "Developer") may designate original elements of their contracts as either open source or proprietary code. Each smart contract shall be documented with human-language terms stating the intent of all parties and naming the arbitration forum that will resolve disputes arising from that contract. Developers who designate contracts as proprietary code may claim that code as intellectual property and may initiate arbitration actions against those who violate their control of their intellectual property for restraint and/or restitution.

## 36. Prevailing Language

The Developer of a contract may offer its human-language terms in multiple language translations. When human-language terms are available in more than one language, the Member executing the contract may select the translation that they wish to execute. The human language of the terms that was provided by the Developer and selected by the Member executing the contract will prevail where there are ambiguities between this version of the terms and other versions. In scenarios where the contract language or contract selection by the Member is ambiguous, the Elected Arbitrator will have the authority to select the contract used in the dispute.

## 37. Recording of Agreement

The text of this Agreement or the most currently ratified or amended version of the Agreement shall be recorded on the Telos blockchain and each block will contain a pointer to the block containing the text of this Agreement. Validating any block shall be deemed a further acceptance of all terms of this contract.

## 38. Amending

The Telos Governance Documents may be amended by a vote of the TLOS token holders using the "ratifyamend" contract. To ratify or amend any Telos Governance Document, any user may execute the "ratifyamend" contract, paying its contract fee of 700 TLOS (the "Ratify/Amend Contract Fee"), which may be returned if the contract receives a minimum of 1% of votes from all TLOS voters. This fee may be paid by one Member or collected from many Members over time to execute when the full cost has been collected. Once the fee has been fully paid, the full text of the proposed new document, or the existing document in the case of ratification, shall be recorded to the Telos blockchain. No Telos Governance Documents shall be ratified or amended except by a vote of the TLOS token holders, as recorded by the "ratifyamend" contract with no less than 15% vote participation among TLOS tokens and no fewer than 10% more Yes than No votes, at the end of a 15,000,000 block voting period (approximately 3 months).

## 39. Severability

If any part of this Agreement is declared unenforceable or invalid, the remainder will continue to be valid and enforceable. No part of this Agreement is to be given higher importance than any other due to its ordinal position within the document.

## 40. Termination

A Member is automatically released from all revocable obligations under this Agreement three years after the Member has sold or otherwise relinquished all TLOS tokens. Any arbitration cases already filed against the Member shall proceed and the Decision shall be enforced. Valid arbitration Decisions entered against a Member shall persist indefinitely in case the Member once again interacts with the network.

## 41. Developer Liability

The Telos network uses "Free and Open Source Software" defined as software which has been authored by single or separate authors who do not retain proprietary ownership to said software and make its source code freely available on a public repository. Members agree to hold Developers of all open source software exempt of liability for mistakes, errors, or breach of contract made in the expression of contractual intent, whether or not said mistakes were due to actual or perceived negligence.

## 42. Grammar

Any noun in this document used in the singular form shall also apply in the plural form and vice versa. Likewise, any masculine or feminine reference shall also apply in the opposite gender or neutral tense.

## 43. Consideration

All rights and obligations under this Agreement are mutual and reciprocal and of equally significant value and cost to all parties.

## 44. Acceptance

A contract is deemed accepted when a Member signs a transaction which incorporates a Transaction as Proof of Stake (TAPOS) proof of a block whose implied state incorporates an Application Binary Interface (ABI) of said contract and said transaction is incorporated into the blockchain.

## 45. Counterparts

This Agreement may be executed in any number of counterparts, each of which when executed and delivered shall constitute a duplicate original, but all counterparts together shall constitute a single agreement.

## 46. Complete Agreement

This Agreement is accepted as complete and needs no further ratification to be valid and enforceable. A method for ratifying this Agreement has been included in the Agreement and Telos network code in the form of the "ratifyamend" contract, however, such ratification is not required for this Agreement to be enforceable and in the event the "ratifyamend" contract is executed, a failure to successfully ratify the Agreement does not nullify the acceptance, validity, or enforceability of this Agreement.