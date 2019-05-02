# PHBS_BlockChain.2018
PHBS BlockChain Course Final Report
- Qihang Zhang 
- 1801212975

# The Application Study of Blockchain Technology in Supply Chain Finance



**Abstract:** Supply chain finance has become one of the hotspots application of blockchain, for the reason includes that blockchain based supply chain finance can simplify the application process, promote credit and credit investigation related business, and improve the social and economic benefits of this system. In order to give a comprehensive analysis and systematic overview of blockchain-enabled supply chain finance, this paper firstly introduce the definition and composition of supply chain finance and blockchain technology, then summarize the finding results in the literature. Specifically, practical application cases are also introduced to provide helpful guidance and reference for future research efforts of blockchain-enabled supply chain finance.

**Keywords:** supply chain finance; blockchain technology; smart contract

## 1.Introduction 

Because in supply chain finance the credit sharing and risk sharing of core enterprises have reduced the requirement of borrowing qualification, supply chain finance can play a role in solving the financing problems of small and medium-sized enterprises (SMEs). However, the supply chain finance has not been developed rapidly though the demand is huge and the financing problem of SMEs is still serious. This is because the supply chain itself is a complex network system and the problems of asymmetric information and low transmission efficiency existing among participants restrict the development of supply chain finance. Blockchain technology has inherent advantages to solve the problem of financial information asymmetry and others in supply chain, which is a comprehensive system integrates consensus mechanism, encryption algorithm, distributed data storage and other advanced researching results.

## 2.Conceptual background

### 2.1	Supply chain finance and its challenges 

Due to globalization, increased competition and higher levels of risks in the supply chain, many companies are facing complexity and uncertainty in their businesses (De Boer et al., 2015). Many firms have recognized to optimize not only the flow of materials and information, but also the financial streams. The optimization of financial flows and the allocation of working capital in the supply chain has led to improvements of the overall supply chain performance and to a reduction of financial risk (Omran et al.,2017). supply chain finance has been defined in different ways in literature. Timme (2000) puts forward the concept of supply chain finance,  he defines it as the cooperation between enterprises in the supply chain and financial service providers off the supply chain, considering the material flow, information flow and financial flow integrated in the supply chain. Hofmann (2005) describes supply chain finance as an approach for two or more participants in a supply chain, including external service providers to jointly create value through means of planning, steering, and controlling of financial resources on an inter-organizational level. Hu and Huang (2009) define supply chain finance as financing and related services pricing and market trading activities carried out by people in order to meet the capital needs of supply chain producing system. Zhou and Li (2016) describe supply chain finance as a comprehensive financial solution provided for small and medium enterprises (SMEs). supply chain finance itself has also evolved from the earliest version, which is artificial credit granting mode based on the credit of core enterprise, to integrated information platform supported by internet technologies. By supply chain finance, bank can obtain all the information of organizations in the supply chain and make breakthroughs in service to cover more SMEs.
![supply chain finance system](https://github.com/QihangZhang/PHBS_BlockChain.2018/blob/master/supply%20chain%20finance%20system.jpg)

There has already existed several financing modes of supply chain finance, where reverse factoring, prepayment financing and inventory financing are three main instruments. In reverse factoring, receivables are sold to a bank at a discount as soon as they are approved by the buyer. The bank then commits to pay the company’s invoices to the suppliers. Reverse factoring is mainly an approach to financing the upstream suppliers, banks focus more on the repayment ability of the buyer instead of the SMEs. In prepayment financing, downstream SMEs can obtain the right of adopting payment by installment, which will also relieve enterprises’ short-term financing pressure. In inventory financing, all the organizations on the supply chain are allowed to receive fund from financier by taking inventories as pledge.

![Three financing instruments in supply chain finance](https://github.com/QihangZhang/PHBS_BlockChain.2018/blob/master/2.Three%20financing%20instruments%20in%20supply%20chain%20finance.jpg)

### 2.2	Blockchain technology

Created by Satoshi Nakamoto in 2008, bitcoin is firstly designed as digital currency to achieve peer-to-peer transactions without a central manager. However, blockchain, the underlying technology of bitcoin has been given more attention and evolves with time. Blockchain refers to a new form of decentralized data management and is further a synonym for a public accessible distributed ledger that ensures the integrity of all kinds of transactions (Omran et al.,2017). Each block contains a cryptographic hash of the previous block, a timestamp, and transaction data (generally represented as Merkle tree). The increasing attention for block chain technology is the result of its features such as transparency, immutability, traceability, and the ability to establish trust between participants in a decentralized network. Here are several basic design of blockchain (Narayanan et al.,2016):
1)	Identity: Each entity is represented with a unique public key, which is generated from private key by ECDSA. The algorithms used here guarantee that no one shares the same private key or is able to know your private key through your public key.
2)	Record: Instead of a central manager keeps track of account balances and verifies that transactions are valid, Blockchain keeps track of unspent money and stores the information by nodes, everyone has a copy of the blockchain.
3)	Consensus : block chain technology use the mechanism as Proof of Work (PoW, and other methods like Proof of Stack) to avoid sybil attack and form consensus among the participants. In order to propose a block, people must include Proof-of -Work or the solution to a hash puzzle, which can only be solved using brute-force computation.
With the development of technology, blockchain can be divided into three basic types according to access authority and they are public blockchain, consortium blockchain and private blockchain.

![](https://github.com/QihangZhang/PHBS_BlockChain.2018/blob/master/3..JPG)

Except some differences like difference in the programming language used and underlying database, the above three mainstream blockchain platforms are all mainly composed of five layers: data layer, internet layer, consensus layer, smart contract layer and application layer.

![](https://github.com/QihangZhang/PHBS_BlockChain.2018/blob/master/4.%20A%20basic%20framework%20of%20blockchain.png)

M.Swan (2015) divides the development of blockchain into three stages, the first is programmable currency stage, where bitcoin is the representative application. The second is programmable financing stage, where smart contract is added and peer-peer payment, record, right confirmation and intellectual management can be achieved, as well as other applications improving traditional financial system. The third is programmable security stage, where blockchain will be more widely used not only in financing field but also in retail business, logistic, law and so on. Blockchain can lead the change of socio-economic life style by revolving traditional business models and social production relationships. Currently we are at the second stage and blockchain-enabled smart contracts will be further discussed in this paper.

### 2.3	Smart contact

Smart contract refers to code that facilitates, verifies, or enforces the negotiation or execution of a digital contract and trusted entity must run this code (Zhao, 2018). Firstly put forward by Nick Szabo, smart contract is found to fit in blockchain naturally. Blockchain can use the smart contract to standardize and package the complex behaviors of each distributed node, while smart contract can achieve decentralization, automatic execution and safety by blockchain. Ouyang et al.(2019) propose a basic model of smart contracts which employs a six-layer architecture.

![](https://github.com/QihangZhang/PHBS_BlockChain.2018/blob/master/5.A%20basic%20framework%20of%20smart%20contracts.jpg)

Infrastructure layer of blockchain packages all the infrastructure used to support smart contract and derivative applications, including distributed ledger, development environment and so on. These basic algorithms make the smart contract based on block chain has the characteristics of tamper-resistant, data confidentiality, self-repairment and operating ecologicalization. Contract layer packages all the static contract data, which can be considered as a static database of smart contract. Operation layer contains all the dynamic operations to the static contact in the contract layer, which is crucial to make the smart contract operate correctly, safely and efficiently according to the designer’s intention. Intelligence layer packages all the intelligent algorithms that give smart contract possibility to make self-decision which develops with artificial intelligence. Performance layer contains all the specific forms of the realization of smart contract and application layer contains concrete applying fields.
The Bitcoin Scripting Language is the smart contract layer of bitcoin, but because of its single instruction and limited function, it is considered as an embryonic form of smart contract. Ethereum provides Turing-complete scripts named Solidity and Serpent, and also a sandbox environment as Ethereum Virtual Machine (EVM), enabling Ethereum users to write and run smart contract. Hyperledger Fabric also provides smart contract named Chaincode. As a result, Ethereum is the most widely used platform in public blockchains and Hyperledger Fabric is the most widely used platform in consortium blockchains (Shao et al.,2018). When applying block chain technology in supply chain finance, Hyperledger Fabric can be a most available platform for which supports Go and Java to write smart contract and the implement of general enterprise application.

## 3.	Relevant literature

There are papers studied the coupling relationship between the block chain and the supply chain finance, many potential improvements of blockchain-enabled supply chain finance have been put forward. Wang et al. (2017) found that there are coupling relationship between the block chain technology and Supply Chain in the subjects, the transaction mechanism and the smart contract.
Chris (2016) considers that the traceability of block chain information can solve the supply chain guarantee problem, as in traditional supply chain it’s hard for SMEs separated from the core enterprises by more than two levels to obtain funds . Yang et al. (2018) find if block chain technology is applied in the automobile supply chain, the supply chain information platform can efficiently connects the supply chain alliance, financial institutions and government supervision departments, SMEs can obtain funds base on the transaction record instead of core enterprises’ credit. Zhu et al. (2018) design a Consortium blockchain where all the participants can carry out operations such as supply chain finance and targeted marketing and find with the blockchain based supply chain organizations can establish a sharing allied platform, intelligently adjust the residual line of credit, realize on time payment and settlement with the help of smart contract and so on. C.Meijer (2017) thinks block chain technology can offer great potential for both corporates and banks in terms of speed, reliability of their supply chain. B.McDermott thinks block chain technology provides a system of trusted records that addresses all three primary areas of supply chain, that are visibility, process optimization and demand management. Wang(2018) think supply chain finance used blockchain technology can promote the healthy development of supply chain finance and attract funds to enter the substantial economy. 

Main shortcomings of present application of blockchain in supply chain finance are also listed, such as low throughput, low transaction processing and concurrent processing capability, inferior query and statistics function and no access control(Shao et al.,2018). Compare to traditional information base, the smart contract is elaborated, verified and implemented by code, which will face hacker attacks and higher requirements are put forward to ensure the security of digital assets and resources .(He et al, 2018). 

## 4.	Case Analysis

Since the year of 2017, the number of blockchain projects to improve supply chain finance is growing firmly. And basically, these platforms leverage advanced block chain technology to meet the hugely underserved needs of supply chain finance in China, which have been limited by existing technology and only served about 15 percent of suppliers needing financial resources. The typical applications of block chain based supply chain finance in China can be divided into three types according to the dominant enterprise, that are core enterprise-oriented, technology provider-oriented and financial institution-oriented supply chain finance platforms. We will respectively choose Chained Finance, Trade Gold and One Enterprise Chain to give more details. 

### 4.1	Chained Finance

Launched in 2017, Chained Finance is created by China-based electronic firm Dianrong and online marketplace lender FnConn (a Foxconn subsidiary). Both companies expect that Chained Finance could help supply chain finance operators potentially triple the number of SME supply chain operators with access to funding in China.
To achieve this, Chained Finance leverages blockchain technology using Hyperledger, converts core enterprises’ (Anchors) account payable to digital assets (eAP) on blockchain, where all eAP owners can pay others or get funded with their eAP anytime.

![](https://github.com/QihangZhang/PHBS_BlockChain.2018/blob/master/6.%20the%20basic%20financial%20structure%20of%20Chained%20Finance.jpg)

After Account Payables are created between Anchor and direct suppliers (L1s), the assets are digitalized and written into L1s’ virtual account on Blockchain. L1s can then split their owned eAP any way they like to pay their suppliers (L2s), so on and so forth until eAP is circulated to facilitate transactions within the entire supply chain. At any time, any eAP owners can choose to get cash with their eAP via Chained Finance, which has partnered with various funding sources to serve all needs.
Chained Finance has been successfully tested in the supply chain of the electronic manufacturing industry, and will be used in automotive and apparel industry in the future. 

### 4.2	Trade Gold

Trade Gold is created by Zhongshang Beidou, which is a Beijing-based supply chain management company. Zhongshang Beidou established under the leadership of the Commercial Network Construction and Development Center under the SASAC. The strategic positioning of Zhongshang Beidou is to be a comprehensive solution provider in commercial circulation supply chain filed and build a M2S2B commercial circulation supply chain system, where M means manufactory, S means supply chain platform and B means business. In the system there are five sectors and Trade Gold is the crucial one, leverages advanced technologies including block chain technology to achieve the integrated delivery of trade, logistics and Finance. 

![](https://github.com/QihangZhang/PHBS_BlockChain.2018/blob/master/7.%20the%20flow%20diagram%20of%20trade%20gold%20operation.jpg)

In the Zhongshang Beidou system, Trade Gold plays the role of credit provider and trading platform provider. Outside the Zhongshang Beidou system, Trade Gold is a trading platform provider, dealers or other core enterprises using Trade Gold paly as credit provider to provide credit endorsement for the related SMEs. The financing methods include purchase order financing, inventory financing and so on.

![](https://github.com/QihangZhang/PHBS_BlockChain.2018/blob/master/8.The%20financial%20structure%20of%20Trade%20Gold.jpg)

For now, Zhongshang Beidou has used block chain technology in factoring, all the participants can share the trading, goods and credit information in real time. The receivables assets have been digitalized and verifiable through blockchain, making the further portfolio or financial instrument design more possible. 

### 4.3	One Enterprise Chain

In 2017, OneConnect, the main fintech subsidiary of Ping An corporation launched a major supply chain finance platform on its One Enterprise Chain. Using a “two small, one big” approach the initiative aims to target large corporates to bring along their SME suppliers. The funding is to be supplied by small to medium-sized banks.
Led by the co-founder of HyperLedger Fabric, the blockchain team of OneConnect has independently innovated and developed the industry-leading BaaS platform and its core framework, FiMAX. By the technologies developed by OneConnect, One Enterprise Chain has broken some limitations, such as single chain TPS can reach or exceed the level of a traditional database, the average speed to generate a block is about 0.01 seconds.

![](https://github.com/QihangZhang/PHBS_BlockChain.2018/blob/master/9.The%20basic%20financial%20structure%20of%20One%20Enterprise%20Chain.jpg)

The supply chain finance platform encrypts important data such as order and logistics information through FiMAX BaaS platform, and implemented various functionalities such as paperless contracts, smart contract judgment, compliance verification, and financing risk assessment. Additionally, The platform enables transparency in multiple dimensions. The identity of the participants is fully verified. Transactions and payments are visible because of integration with banks. What’s more, the paperwork such as orders, invoices, and delivery notes is available on the blockchain. Integration using IoT at the warehouse enables goods tracking. And the data is protected using Zero-Knowledge cryptography, so it’s all on a need-to-know basis.

Ping An has applied its blockchain platform in many fields, including All-Link supply chain cooperated with Foton Automoblie, ALFA intelligent ABS platform and blockchain pilot project in Tianjin port.

## 5.	Conclusion 

This paper is devoted to studying the application of blockchain technology in supply chain finance, giving a relative comprehensive presentation of the development of blockchain and the existing supply chain finance model. Since the birth of Bitcoin in 2008, the blockchain technology represented by Bitcoin has a rapid rise and has become a hot research topic in academia and industry. After experiencing the era of block chain 1.0 represented by digital currency, blockchain 2.0 is an era of smart contract, which can adapt to more complex application scenarios.

This paper selects Chained Finance, Trade Gold and One Enterprise Chain as the respective representative of core enterprise-oriented, technology provider-oriented and financial institution-oriented supply chain finance platforms to give a further presentation of the practical application scenarios. We can find the supply chain partners strongly benefit from the blockchain technology’s three key characteristics in form of efficiency, transparency and trust. The development of technology can also synchronize the material, information and financial flows more efficiently. 

For further research, a more practical research approach is necessary and concrete evaluation on the platforms’ effectiveness is suggested. A conceptual model is also needed for further development and a widespread adoption of blockchain technology applications.

## Reference

[1]Antonopoulus, A.M. 2015. Mastering Bitcoin: Unlocking Digital Cryptocurrencies. 1st Edition, O´Reilly Media: Sebastopol.

[2] CHRIS G. DASKALOS. Increasing supply chain assurance via the blockchain[D]. Pittsbwgh: Carnegie Mellon University, 2016

[3]储雪俭,高博.区块链驱动下的供应链金融创新研究[J].金融发展研究,2018(08):68-71.

[4]李长银,李虹含,高寒,陈涛.区块链技术的发展趋势及其对金融业的影响[J].海南金融,2017(02):31-37.

[5]马小峰,杜明晓,余文兵,王意.基于区块链的供应链金融服务平台[J].大数据,2018,4(01):13-21.

[6]SHAO Qi-Feng, JIN Che- Qing, ZHANG Zhao, QIAN Wei-Ning, ZHOU Ao-Ying.Blockchain: Architecture and Research Progress[J].Chinese journal of computers,2018,41(5):969-989.

[7]汪传雷,万一荻,秦琴,汪宁宁.基于区块链的供应链物流信息生态圈模型[J].情报理论与实践,2017,40(07):115-121.

[8]王玥. 区块链在供应链金融中的应用研究[D].对外经济贸易大学,2018.

[9]吴俊.区块链技术在供应链金融中的应用——基于信息不对称的视角[J].物流技术,2017,36(11):121-124.

[10]许荻迪.区块链技术在供应链金融中的应用研究[J].西南金融,2019(02):74-82.

[11]杨慧琴,孙磊,赵西超.基于区块链技术的互信共赢型供应链信息平台构建[J].科技进步与对策,2018,35(05):21-31.

[12]朱兴雄,何清素,郭善琪.区块链技术在供应链金融中的应用[J].中国流通经济,2018,32(03):111-119.

[13]朱苹苹,粟恒.基于区块链背景的供应链金融创新分析[J].现代商贸工业,2019,40(14):47-49.

[14]周立群,李智华.区块链在供应链金融的应用[J].信息系统工程,2016(07):49-51.

[15]张璟霖,伦祖炜.区块链技术与供应链金融结合研究[J].合作经济与科技,2017(21):58-59.
