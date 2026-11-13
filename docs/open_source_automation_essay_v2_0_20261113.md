# Open source as a public strategy in the age of automation

**Prepared by Neil Thomson**

Version 2.0 · 13 November 2026

Automation is becoming part of the arrangements through which firms earn revenue, public services allocate resources and workers secure a livelihood. Its effects will depend on who controls the systems, who can alter them and how the resulting gains are distributed. Open source deserves a more deliberate place in public strategy because it can widen participation, support competition and preserve the capacity to act when a supplier’s priorities change.

The activities involved are often ordinary: billing, scheduling, procurement, logistics, customer contact and engineering analysis. Their cumulative significance is considerable. Improvements can reduce administrative work, increase productive capacity and allow faults to be detected before equipment fails. The benefits may extend widely, while the costs of adjustment fall heavily on particular occupations, firms or communities. Governing that transition requires attention to the ownership and organisation of the technology through which it proceeds.

Since the first version of this essay, developments in AI have made these questions more pressing. Stanford’s 2026 AI Index records substantial gains in coding and computer use. On SWE-bench Verified, a software engineering benchmark, reported performance rose from around 60% to nearly 100% over the preceding year [1]. These results establish progress within the assessed tasks; their implications for a particular workplace require examination of the work itself.

METR’s report published in May supplies a useful qualification. It found agents capable of substantial coding work, especially where progress could be checked cheaply through tests and repeated experiments. Judgement and reliability were considerably weaker on less constrained tasks [2]. A system can become highly competent at producing an implementation while remaining unreliable at recognising an inadequate specification or deciding whether the result is fit for use.

As these systems acquire access to operational environments, their authority becomes consequential. A proposed configuration can be examined before deployment. An agent permitted to modify infrastructure needs defined permissions, dependable records and a means of recovery. The surrounding architecture determines how a model’s competence, errors and uncertainty affect the organisation using it.

The labour-market implications also require precision. The World Economic Forum’s 2025 report projected 170 million new roles and 92 million displaced by 2030, producing a net increase of 78 million within its modelled labour market. These projections encompass technological change alongside demographic, economic and environmental forces [3]. They describe anticipated structural change across several causes.

IMF staff analysis estimates that roughly 40% of jobs globally are exposed to AI, rising to about 60% in advanced economies [4]. Exposure includes work that AI may complement as well as work it may replace. Neither estimate determines the outcome for an individual occupation or community. Even an eventual increase in aggregate employment can coexist with prolonged disruption for people whose experience loses market value.

These uncertainties strengthen the case for preserving broad access to productive tools and the knowledge needed to use them. Institutions and smaller firms need scope to shape the transition, rather than having their choices determined by technologies whose operation and development remain beyond their influence.

Open source changes those choices through explicit rights to use, inspect, modify and redistribute software [5]. Price is one consideration. The more durable benefit is permission to continue development, commission another supplier or adapt an implementation to a different purpose. Those rights create possibilities for shared ownership of technical capability, although exercising them still requires expertise and resources.

They also affect bargaining power. An organisation able to replace a component or appoint another maintainer has alternatives when prices rise or support deteriorates. Commercial opportunity can extend to integration, hosting, assurance and specialist development. Suppliers retain ample scope to earn revenue through the quality of their work, while customers have greater freedom to choose who performs it.

The economic value extends beyond individual procurement decisions. A European Commission study published in 2021 estimated the impact of open source software on the EU economy at between €65 billion and €95 billion in 2018 [6]. That historical estimate depends on the study’s methods and assumptions. It nevertheless provides an empirical basis for considering shared software infrastructure as a source of innovation and economic activity.

The argument that open source can help societies reduce dependence on single vendors has also acquired more explicit institutional recognition. The UK’s *Artificial Intelligence sector study 2025*, published on 29 October 2026, records businesses’ concerns about reliance on a small number of major model and cloud providers. Interviewees described limited influence over prices, difficulties changing suppliers and competition from providers expanding into their customers’ markets. Some were already using open source components or avoiding dependence on a particular model to retain flexibility [7].

The government response to Parliament’s *Rewiring the state* report, published on 22 October, describes work towards a sourcing strategy favouring interoperable architectures, open standards and APIs, supported by portability and contractual exit provisions [8]. These are intentions whose effectiveness will depend on implementation. Their significance lies in the explicit recognition that technical design and procurement can preserve or diminish public institutions’ freedom of action.

Vendor dependence has been a concern for many years. AI increases its reach because a service can gradually become responsible for an organisation’s documents, workflow definitions, operational history and connections to other systems. Each integration may be reasonable on its own. Together, they can make departure so disruptive that an alternative supplier ceases to be a credible option.

Reducing that dependence requires examination of the whole technical system. Automation rests on hardware, operating systems, libraries, data infrastructure and applications. Openness at one level can coexist with restrictive dependencies elsewhere. An application built from accessible code may still rely on a proprietary service for its essential operation. A model available for independent deployment may require computing resources available from only a few suppliers.

AI also makes the meaning of openness more demanding. The Open Source Initiative’s definition addresses model parameters, the code used to train and run a system, and sufficiently detailed information about its training data [9]. Downloadable weights provide useful access, but weights alone do not supply all the materials and freedoms contemplated by that definition.

Open weights can nevertheless expand practical choice. Mistral’s October release of the weights for Mistral Large 4 provides a recent example of a substantial model becoming available for deployment beyond its developer’s hosted service [10]. The associated licence, documentation and technical requirements determine how far that freedom can be exercised.

The distinction matters economically. Operating a substantial model requires hardware, energy and continuing engineering support. Reproducing its training may remain beyond the resources of almost every prospective user. Greater control over deployment can therefore coexist with concentration in model development and computing infrastructure. Public strategy needs to assess each dependency on its own terms.

Industrial automation presents a related problem over much longer operating lives. Factories, utilities and transport systems combine equipment acquired across decades. New monitoring and optimisation systems must work with existing machinery, established control arrangements and accumulated operational knowledge. Open protocols, documented data models and usable reference implementations can reduce the repeated integration work imposed by incompatible products.

A manufacturer adding condition monitoring to an existing machine should be able to assess competing implementations without unnecessarily replacing functioning equipment or surrendering access to its measurements. Where hardware designs and firmware can also be shared, independent teams gain more scope to reproduce, repair and adapt the equipment [11]. Physical manufacture and qualification still carry costs, but access to the design can widen the range of organisations able to undertake them.

Safety gives this accessibility a further purpose. Systems controlling physical processes require evidence about timing, behaviour under fault and the conditions in which operation remains acceptable [12]. Source access can support independent examination, reproducible builds and investigation of failures. The resulting assurance depends on the evidence produced and the quality of the assessment. Licensing alone establishes none of those properties.

Accountability in public administration requires a similarly complete view. When automation influences access to services, employment decisions or the allocation of resources, affected people need intelligible grounds for decisions and a means of challenging errors. Open implementations can make rules and processing methods available for scrutiny. With learned models, inspection of code and weights still leaves important questions about behaviour to be answered through evaluation and operational evidence.

Public access to software also need not entail publication of confidential records. Councils, hospitals or manufacturers can share implementations while retaining appropriate control over personal, commercial and operational data. Common software can support local responsibility, provided that the institutions using it understand how it behaves and remain accountable for its application.

Resilience requires scrutiny of shared dependencies as well as individual suppliers. Two services may use the same cloud platform, identity provider or underlying model. A fault at that common point can affect both. Conversely, a defect in a widely used open component can propagate across many organisations. A resilient system requires knowledge of these relationships, alternative arrangements where justified and recovery procedures that have been exercised.

Portability should therefore be demonstrated. A compatible API may make another model easy to connect while leaving its behaviour substantially different. Instructions, retrieval methods and quality checks may need revision. A successful transfer must preserve the required service, its access controls and its records. Representative workloads and explicit acceptance criteria allow the organisation to determine whether it has retained a viable alternative.

The distribution of automation’s gains depends partly on these technical and commercial arrangements. If essential workflow logic and operational knowledge accumulate within a few platforms, those providers gain influence over the terms on which other organisations conduct their work. Savings achieved by users can be accompanied by increasing payments for continued access to the systems that produced them.

Open implementations can create a different distribution of opportunity. Smaller suppliers can develop specialist services around shared foundations. Public bodies can pool maintenance and avoid commissioning the same capability repeatedly. Independent researchers and small firms can adapt tools that would otherwise require substantial development expenditure. Improvements made for one setting can become available elsewhere, subject to their suitability and licence.

This supports a practical case for treating some software as shared infrastructure. The organisations benefiting from it can retain distinct responsibilities and commercial interests while contributing to capabilities they all require. Such arrangements demand governance: decisions about development priorities, release authority, security and responsibility for support must be explicit.

Their benefits for workers remain conditional. Open source can accelerate automation by reducing its cost and making tools more widely available. That can increase pressure on existing roles. An open licence determines neither wages nor working conditions, and it provides no income support during a transition. Employment policy, collective bargaining and access to education continue to shape how productivity gains are distributed.

Openness can, however, improve the conditions under which people acquire transferable competence. Accessible systems can be studied, instrumented and modified. Learners can examine how an implementation works, test an alternative and build a portfolio that remains useful across employers. Documentation, testing, localisation and operations provide substantive routes into technical work alongside software development.

Those opportunities require time and supervision. A repository offers material for an apprenticeship; experienced practitioners and funded learning arrangements make that material usable. Training should develop the ability to assess results, diagnose failures and understand operational consequences. These capabilities retain value as particular models and products change.

Security and maintenance are equally dependent on sustained human effort. The 2024 XZ Utils compromise demonstrated that an open software supply chain can be deliberately attacked through its development and release processes [13]. Availability for inspection creates an opportunity for scrutiny, while adequate scrutiny depends on supported maintainers, effective review and control over releases.

NIST’s Secure Software Development Framework provides a common basis for secure development practices and discussions between purchasers and suppliers [14]. Its 2024 profile for generative AI extends those practices to model development and the systems using models [15]. These approaches support evidence about how software is produced and maintained across both proprietary and open implementations.

For critical services, procurement should require appropriate information about components, provenance, vulnerability handling and continuing support. Reproducible builds and independent testing can strengthen that evidence where practicable. Requirements should be proportionate to the consequences of failure and supported by the resources necessary to meet them.

The underlying funding problem is persistent. The value of a widely used project may be shared among thousands of organisations while essential maintenance falls to a small team. Security updates, compatibility work and documentation continue long after an initial development grant has ended. Organisations relying on those activities have a reason to support them through contracts, shared funds or direct engineering contributions.

Recent European activity acknowledges that need. On 9 November, the Sovereign Tech Agency launched a survey to inform the investment priorities of an EU Sovereign Tech Fund pilot concerned with critical open digital infrastructure. The initiative addresses the underlying technologies on which other services depend, including their maintenance and sustainability [16]. Its outcomes remain to be assessed, but its proposed scope recognises that infrastructure requires continuing investment.

More capable coding agents make review capacity increasingly significant. Producing a plausible patch may become easier while establishing its correctness remains demanding. A project can receive more contributions without acquiring more capacity to assess them. Funding arrangements should recognise testing, review and release responsibility as essential work.

Public procurement can connect these arguments to practice. Where public money commissions broadly reusable software, open licensing should receive explicit preference, subject to a reasoned assessment of suitability and restrictions. Open standards, usable documentation and data portability should carry weight in purchasing decisions. Suppliers can compete on implementation quality and support while public institutions retain the ability to commission further work elsewhere.

Interoperability also has a place in competition policy. The ability to replace a component, appoint another provider or move operational data affects entry into a market and the bargaining power of existing customers. Procurement and competition authorities should examine whether stated interoperability works in practice, including the costs and contractual conditions attached to its use.

Public bodies also need enough internal competence to assess the services they buy. Access to code has limited practical value when an institution lacks documentation, support arrangements or the expertise to commission a change. Shared technical teams, open training materials and independent evaluation can make those rights usable across organisations with differing resources.

The costs and trade-offs warrant full comparison. Migration can disrupt services. Internal operation can consume scarce expertise. A poorly supported open deployment can be more expensive and less dependable than an established commercial service. Equally, a convenient service can accumulate substantial costs through integration and dependence. Decisions should address the operating life of the system, including maintenance and eventual replacement.

The case for wider adoption therefore rests on a combination of freedoms and capabilities. Open source can widen access to productive tools, support scrutiny and preserve alternatives to individual suppliers. Its contribution to social resilience depends on institutions being able to exercise those freedoms, maintain the systems they adopt and distribute the resulting benefits through deliberate policy.

Three immediate actions would give that approach practical substance:

1. **Run a bounded procurement and migration trial.** Select a representative service, preserve its working specification and acceptance tests, and transfer it to an alternative implementation or provider. Record the effort, costs, changes in performance and information that cannot be moved. Use the findings to establish credible requirements for documentation, interoperability and exit.

2. **Fund the shared infrastructure already in use.** Identify critical open source dependencies, examine their maintenance and security arrangements, and allocate continuing resources to support them. Organisations sharing a dependency should consider pooling that investment. Assess the expenditure against demonstrable improvements in support, release quality and recoverability.

3. **Build transferable capability around real systems.** Combine supervised work on accessible implementations with independent evaluation of the services they support. Preserve reusable training materials, test methods and operational documentation. This creates practical routes for workers to develop portable skills and for institutions to retain the knowledge needed to direct their own technology.

## References

1. Stanford Institute for Human-Centered Artificial Intelligence (2026). [*The 2026 AI Index Report*](https://hai.stanford.edu/ai-index/2026-ai-index-report), particularly Chapter 2, ‘Technical Performance’.

2. METR (2026). [*Frontier Risk Report (February to March 2026)*](https://metr.org/blog/2026-05-19-frontier-risk-report/). Published 19 May. See particularly ‘Coding agents did real projects that would take humans hours or days’ and ‘Agents had significantly worse judgment and reliability than human experts’.

3. World Economic Forum (2025). [*The Future of Jobs Report 2025*](https://www.weforum.org/publications/the-future-of-jobs-report-2025), particularly ‘Key findings’ and Chapter 2, ‘Jobs outlook’.

4. Cazzaniga, M., Jaumotte, F., Li, L., Melina, G., Panton, A. J., Pizzinelli, C., Rockall, E., and Tavares, M. M. (2024). [*Gen-AI: Artificial Intelligence and the Future of Work*](https://www.imf.org/-/media/files/publications/sdn/2024/english/sdnea2024001.pdf). IMF Staff Discussion Note SDN/2024/001. Washington, DC: International Monetary Fund.

5. Open Source Initiative (n.d.). [*The Open Source Definition*](https://opensource.org/osd), particularly the provisions concerning redistribution, source code and derived works.

6. European Commission, Directorate-General for Communications Networks, Content and Technology (2021). [*The impact of open source software and hardware on technological independence, competitiveness and innovation in the EU economy: Executive summary*](https://op.europa.eu/en/publication-detail/-/publication/84834aa9-2c2d-11ec-bd8e-01aa75ed71a1). Publications Office of the European Union. DOI: 10.2759/526721.

7. UK Government (2026). [*Artificial Intelligence sector study 2025: Web version*](https://www.gov.uk/government/publications/artificial-intelligence-sector-study-2025/artificial-intelligence-sector-study-2025-web-version). Published 29 October. See Section 6.2, ‘Competition’.

8. House of Commons Science and Technology Committee (2026). [*Rewiring the state: Delivering digital government: Government response*](https://publications.parliament.uk/pa/cm5902/cmselect/cmsctech/651/report.html). Third Special Report of Session 2026–27, published 22 October. See the response to Recommendation 21.

9. Open Source Initiative (n.d.). [*The Open Source AI Definition, version 1.0*](https://opensource.org/ai/open-source-ai-definition), particularly ‘Preferred form to make modifications to machine-learning systems’.

10. Mistral AI (2026). [*Mistral Large 4 (Le Chonk): Built for Coders, Trusted by Defenders*](https://mistral.ai/news/mistral-large-4-oss/). October model release announcement.

11. Open Source Hardware Association (n.d.). [*Open Source Hardware Statement of Principles and Definition*](https://oshwa.org/definition/).

12. Health and Safety Executive (n.d.). [*Functional safety*](https://www.hse.gov.uk/eci/functional.htm), particularly the guidance on the safety lifecycle, validation, maintenance and functional safety assessment.

13. CERT-EU (2024). [*Critical Vulnerability in XZ Utils*](https://www.cert.europa.eu/publications/security-advisories/2024-032/). Security Advisory 2024-032, initially published 30 March and updated 2 April.

14. Souppaya, M., Scarfone, K., and Dodson, D. (2022). [*Secure Software Development Framework (SSDF) Version 1.1: Recommendations for Mitigating the Risk of Software Vulnerabilities*](https://doi.org/10.6028/NIST.SP.800-218). NIST Special Publication 800-218.

15. Booth, H., Souppaya, M., Vassilev, A., Ogata, M., Stanley, M., and Scarfone, K. (2024). [*Secure Software Development Practices for Generative AI and Dual-Use Foundation Models: An SSDF Community Profile*](https://doi.org/10.6028/NIST.SP.800-218A). NIST Special Publication 800-218A.

16. Sovereign Tech Agency (2026). [*Which open source does Europe rely on? A survey for the EU Sovereign Tech Fund pilot*](https://www.sovereign.tech/news/survey-for-the-eu-sovereign-tech-fund-pilot). Published 9 November.

Online sources accessed 13 November 2026.
