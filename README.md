# Description
A knowledge mining framework designed for DataDAO members, enabling them to create, publish, and enrich knowledge surrounding their on-chain behaviors and opinions. This knowledge is stored in a hybrid environment, comprising both public and private knowledge. This structure allows knowledge buyers to browse the public profiles of DataDAO members, aiding them in identifying a target audience that aligns with their research requirements. Upon finding the appropriate audience, they can then pay to access a curated and enriched private knowledge, specific to that group. Additionally, we will provide an option for knowledge buyers to request further data directly from DataDAO members, which could be in the form of surveys, interviews, and other interactive methods.

The knowledge is stored in a hybrid of public & private, so that knowledge buyers can browse through the public profile of the dataDAO members and find the target audience in which satisfies their research, and pay to access the curated & enriched knowledge around the target audience & request for futher data from the dataDAO members in terms of surveys, interview, etc.

## Diagram & Architecture flow
<img width="3584" alt="diagramDKG" src="https://github.com/datalatte-ai/dataDAO-DKG-framework/assets/90555973/65a73842-69b3-446e-a089-3f8d987e9d64">


#### Public profile on DKG
Members mint pseudo-anonymous profiles (Knowledge asset NFTs on DKG) combining on-chain features and off-chain interests, making them discoverable to market researchers.
Profiles are owned and controlled by members, who can modify them as desired.
#### LLM Interview, knowledge extraction & data schema 
OpenAI’s API turns into an interviewer to glean further insights from users’ on-chain features. Upon conversation completion, ChatGPT extracts key opinions and relevant topics, ensuring GDPR compliance by omitting personal data.
ChatGPT then formats these opinions & topic pairs into the data schema of DKG.
#### CommunityKG & dataDAO curation
Data owners store their insights (knowledge) in the CommunityKG with the right schema. CommunityKG is monetized and access-controlled for data buyers. DataDAO members can curate content, influencing the quality and weight of opinions. This curation affects the insights' likelihood of use in queries.

## Milestones & timeline
### Milestone 1: Knowledge extraction from an interview via LLM into KG data schema:(Opinion, topic, labels)
#### Timeline: 15th Jan 2024

### Milestone 2: KA (public,private) publish, access controlled via dataDAO membership NFT
#### Timeline: 15th Feb 2024

### Milestone 3: Community's KAs curation & enrichment
#### Timeline: 15th March 2024

### Milestone 4: Query &  monetization framework research
#### Timeline: 15th March 2024
we are broadening our research to develop a monetization & query framework for CommunityKG. This framework is intented to facilitate data buyers in identifying their target audience through natural language queries, enabling them to access and leverage the private knowledge stored within the CommunityKG. This approach aims to create a seamless and intuitive experience for data buyers, providing them with valuable, targeted insights from our monetized knowledge bank, CommunityKG.

## Expected Impact:
Leveraging DKG as the foundational data model and storage mechanism, our DataDAO framework empowers additional dataDAOs to utilize this infrastructure. This approach not only stimulates demand for Knowledge Assets publishing but also fosters a crowdsourced mechanism for populating the DKG. This collaborative effort effectively bridges knowledge gaps within the DKG. 
Furthermore, the primary focus of datalatte DataDAO lies in exploring the relationship between on-chain and off-chain data, a topic that has garnered significant interest among Web3 market researchers.

## Future plans
In this proposal, our primary objective is to emphasize the dataDAO onboarding framework, aligning it with the knowledge mining initiative spearheaded by Nueroweb. As we work towards achieving these milestones, we are planning a launch for our private alpha users in January 2024 & gradually introducing the milestones in our dApp. Moreover, we see a potential to add further enrichment of CommunityKG by adding public information about web3 topics & projects by users, further completing the CommunityKG.
