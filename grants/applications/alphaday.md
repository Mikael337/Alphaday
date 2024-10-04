# Technical Grant Proposal

* **Project:** Alphaday - PlatON Dashboard

## Project Overview  

Alphaday is a powerful crypto workflow aggregator that pulls in news, on-chain data, social media, web3 services and much more into one customizable UI.

We help solve the issue of information fragmentation and aim to serve as a central point where any user (whether they are a developer, enthusiast, investor) can instantly get the PlatON information they need, stay up to date on the latest videos & podcasts featuring PlatON and much more.

Alphaday is and will remain to be free-to-use for end users.

### Project Details

We are aiming to be the de facto homepage for all crypto users. People using Alphaday to stay up to date with their favourite crypto projects, listen to podcasts, do research, participate in discussions and much more. Other competitors are all competing within much narrower niches. We get their services and integrate them into our app so users don’t have to jump from one service to another, it's all available on Alphaday.

Example Dashboard we built for Arbitrum: https://app.alphaday.com/b/arbitrum/

Alphaday is a React-Typescript dashboard on the frontend using a Python-Django backend built on distributed infrastructure with Postgres and Redis Databases.

Data importation is automated through RSS feeds and APIs; this refers to widgets such as Discord, News, Market price, Reddit, Podcasts, Videos, Latest Video, TVL, Blog, Forum, and DAO (Snapshot).

Other widgets such as Hiring Directory/Career, Events in Calendar, Documentation, Links, etc. are manually created and updated.

Alphaday is open-source with an MIT license:
https://github.com/AlphadayHQ/alphaday 

### Project Advantages

We do not have direct competitors who are competing in the experience aggregator space but our individual widgets do overlap with features offered by Dune, Nansen, Zapper/Zerion, Coingecko, Discord, DeFiLama, Snapshot.

Bear in mind that the above are feeding data to Alphaday itself.

### Project Code Repos

https://github.com/AlphadayHQ 

## Team
* **Alphaday**

### Team members

|  Member Name  | GitHub Code Repos |LinkedIn Profiles (if available)|
|  ----  | ----  |----|
| Deniz Omer, Founder | | https://www.linkedin.com/in/denizomer/ |
| Felipe Faraggi, Co-founder | https://github.com/faraggi | https://www.linkedin.com/in/faraggi/ |
| Charles Nwankwo, Developer | https://github.com/Xavier-Charles | https://www.linkedin.com/in/charles-nwankwo-01/ |
| Jonathan Irhodia, Developer | https://github.com/elcharitas | https://linkedin.com/in/elcharitas |
| Gideon Anyalewechi, Developer | https://github.com/getgiddy | https://www.linkedin.com/in/getgiddy/ |
| Michael Hagopian, QA & Partnerships | https://github.com/Mikael337 | https://www.linkedin.com/in/mikael-h-87bb4ba4/ |


### Contact
- **Contact Name:** Michael Hagopian
- **Contact Email:** mike@alphaday.com
- **Website:** app.alphaday.com 

### Team's experience
Deniz has been involved in the Ethereum space since early 2016 and joined Kyber Network in 2017 as Head of Ecosystem Growth before quitting to start Alphaday full-time in 2021. Previously he worked at Thomson Reuters for a decade building financial products that rivaled the Bloomberg Terminal. He is currently also a Venture Partner at IOSG.VC.
https://twitter.com/DenizOmer, https://www.linkedin.com/in/denizomer/ 

Felipe has also been involved in Ethereum since 2016 and was a Developer Advocate at Pegasys and Consensys before quitting to work full time on Alphaday.
https://github.com/faraggi, https://twitter.com/felipefaraggi, https://www.linkedin.com/in/faraggi/ 

Our team has been cohesively working together since early 2022.

Established partners: Aave, Chiliz, TheGraph, Avalanche, Metis, Dfinity, Zcash, XRPL, Ethereum Classic, RocketPool, Starknet and others.

## Development Roadmap

### Overview
- **Total Estimated Duration:** 2 months
- **Full-Time Equivalent (FTE):**  2 FTE
- **Total Costs:** 3,000 USD

### Milestone 1 — Development & Deployment of the Dashboard

- **Estimated duration:** 2 months
- **FTE:**  2
- **Costs:** 1,500 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | MIT |
| 0b. | Documentation | We can provide a document as a guide to give a bit more detail on how to test a completed dashboard's functionality. It will be a reference to the points listed below (1-12) |
| 0c. | Testing Guide | The product is already live and can be tested directly once the dashboard is completed. We can provide a briefing in the documents. |
| 0d. | Docker | The dashboard would be live and visible to anyone that accesses the url. As such, a Docker file would be deemed unnecessary. |
| 0e. | Article | We will publish articles and other posts about the dashboard and the project once we deploy it. |
| 1. | Blog | The latest PlatON official announcements and blog post content. |
| 2. | News | A feed of all news mentions of PlatON from coindesk, cointelegraph and 20+ other news sources aggregated from across the internet. |
| 3. | Calendar | A calendar containing all PlatON events including meetups, hackathons with bounties, AMAs. |
| 4. | Documentation | Complete PlatON Documentation directory. |  
| 5. | Forum | Integration with PlatON Forum to show the latest and trending discussion topics. |  
| 6. | Social | Discord & Reddit Integration to show a feed of latest discussions for both PlatON. |  
| 7. | Misc | FAQ, PlatON Whitepapers, ‘Learn’ directory, LAT tokenomics information. |
| 8. | Token Price | Live LAT spot price chart. |
| 9. | Developer Resources | Developer tools, tutorials, guides, development center links & descriptions, grants & bounties, and any other resources that can help build with PlatON. |  
| 10. | Roadmap |  A widget featuring the PlatON roadmap with all the descriptions. |  
| 11. | Ecosystem | Categorized links and descriptions of dapps, solutions, products and services offered in the PlatON ecosystem. |  
| 12. | Team | Other relevant important links. |

### Milestone 2 — Maintenance & Curation of Dashboard

- **Estimated duration:** Indefinitely
- **FTE:**  1
- **Costs:** 1,500 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 1. | API’s & RSS feeds | Changes in API or RSI feeds that need to be updated on a regular basis. |
| 2. | Updating Automated Sources | News sources or other content sources to be added or removed. |
| 3. | Manual Data Curation | Manually import data, such as upcoming events, that are not picked up by the Alphaday aggregator engine. |
| 4. | Further Development & Upkeep |  New developments or integrations, and quality assurance/testing of new features and widgets |

## Future Plans
If we get a grant we will start working on the board immediately and we should have it ready within 2 months. Once we’ve launched the board, we use forums and other channels available to gather feedback and tune the dashboard. We will continue this process of iterating, deploying, and collecting feedback continuously to build a dashboard that PlatON stakeholders truly love to use.

We have just recently released a new mobile app version of Alphaday. The dashboard will be available on the desktop version, and we will adapt the new mobile app to automatically filter the ‘superfeed’ based on each project’s url; e.g. ‘/b/platon would direct users to the alphaday superfeed page and automatically filter it for PlatON.

Other future plans include further development of the app as a whole, and adding new features and functionalities. We have also started focusing on marketing more this year to boost the value our partners get from us, as well as to increase awareness of Alphaday.

## Additional Information

We have just recently released a new mobile app version of Alphaday. The dashboard will be available on the desktop version, and we will adapt the new mobile app to automatically filter the ‘superfeed’ based on each project’s url; e.g. ‘/b/platon’ would direct users to the Alphaday superfeed page and automatically filter it for PlatON.

We are also currently building a separate supplementary mobile application that enhances our marketing capabilities. Please see: https://getpulse.xyz/ (App is already live and still being developed).

Note that we can also create an exclusive PlatON application through the Pulse app in the near future.

**Relevant Links:**
- Live Product: https://app.alphaday.com/ 
- Landing Page: https://alphaday.com/ 
- Twitter: https://twitter.com/AlphadayHQ 
- Discord: https://discord.com/invite/8KSmPyT5k8 
- Github: https://github.com/AlphadayHQ 
- Linkedin: https://www.linkedin.com/company/alphaday
- Blog: https://blog.alphaday.com/
- Faraster: https://warpcast.com/alphaday 
- Phaver: @Alphaday
- Paragraph Newsletter: https://paragraph.xyz/@alphaday
- Pitch Deck: https://alphaday.com/deck 
- Demo: https://www.youtube.com/watch?v=ThCd_W3rK_8 
