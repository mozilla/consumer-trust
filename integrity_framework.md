# integrity framework

The integrity framework outlines high level guidelines for product creators to design and develop ethical products that help users succeed and uphold basic human rights in societies around the world. This is how we build a better internet: by creating products that (1) amplify the good, promoting greater individual autonomy and agency over digital experiences and (2) filter out the bad by actively combatting pervasive harmful practices, such as surveillance, data extraction, and manipulation. 

We are focused on five pillars of integrity in our products: privacy, security, safety, inclusion, and sustainability. Basic descriptions, best practices, and key resources are outlined for each pillar below. For a more detailed, action-oriented resource about *how* to apply these best practices in product design and development, check out our self-assessment checklist.

For more information about the integrity program, check out the [README](https://github.com/MozillaDPX/integrity).


## using the toolkit
If you are new to building for integrity in products and/or trying to learn more, you may find it useful to read through the framework in its entirety. 

For readers with specific questions about one of the pillars, you can find high level descriptions, best practices, and useful resources for each area of experience integrity below (pillars are in no particular priority order). 

If you are a product owner, designer, or developer, you can use the experience integrity toolkit and self-assessment for a more direct approach in applying these principles in practice.

* [privacy](#privacy)
* [security](#security)
* [safety](#safety)
* [inclusion](#inclusion)
* [sustainability](#sustainability)

## integrity  pillars

### privacy
In tech, privacy is often used as a synonym for data protection. However, at Mozilla, privacy goes beyond data access and manipulation. Not only do we consider the consequences of providing increasingly integrated tools for people in their lives; we thoughtfully consider the impacts of product decisions on the people and creators who use them through privacy by design.

People’s ability to trust the platforms they use online without the burden of feeling or being observed can impact how they learn, think, and express themselves. Many scholars believe freedom from surveillance serves as a fundamental tenet to a democratic, free-thinking society. Oftentimes, information about the people using a product is necessary for it to best serve their needs, and therefore trust and lean data collection are tools to meet people’s expectations from usefulness to ownership of their experience. [1, 2]

#### best practices
1. embed privacy by design
2. ensure privacy by default
3. protect personal identity and information
4. prevent harm to people and society
5. respect each person
6. responsible data collection

#### key resources
* [Mozilla Lean Data Toolkit](https://docs.google.com/document/d/1TJafYmeFT3LIQe6YPLEHWwh37PGbK2RunntDIaN2lL8/edit)
* [Mozilla Data Stewardship](https://wiki.mozilla.org/Firefox/Data_Collection)
* [Mozilla Data Privacy Principles](https://www.mozilla.org/en-US/privacy/principles/)
* [General Data Protections Regulation (EU)](https://gdpr-info.eu/)

### security
Product security is about providing a trustworthy and reliable product, by limiting the risks our users and the business could face should something go wrong.

At Mozilla, we use the following concepts to think about security and risk:
* Confidentiality: sensitive user information and product assets (such as accounts credentials, secret API keys) are kept private and are protected appropriately against unauthorized access.
* Integrity: the software, services and information we deliver to consumers are reliable, trustworthy and protected against malicious attempts at modifying it.
* Availability: we deliver a continuity of service and we design it so that it doesn’t put users at a greater risk in a case it is down, by informing them or offering an alternative.

Security can be assessed with different and complementary aspects in mind such as the impact on the people who use our products, as well as business imperatives such as reputation of the company, productivity and finances.

#### best practices
We strongly encourage thinking about security at the different stages of life of the product/service: design and implementation of a new service or product, significant architecture changes and new features, maintenance.

1. KISS: Keep it simple and thus secure.
2. Apply the Principle of least privilege.
3. Design your product keeping Defense In Depth principles in mind.
4. Think about what could go wrong in the worst case scenario and do some threat modeling (see self-assessment Security section for more detailed guidelines).
5. Provide a medium to report and manage product security issues, fraud, and abuse.
6. Communicate security fixes transparently (e.g. product security advisories)
7. Monitor security fixes to third-party libraries to apply relevant security patches in the product in a timely manner.
8. Reach out for support to your security team.

#### key resources
* [Web Security Guidelines](https://infosec.mozilla.org/guidelines/web_security.html)
* [Rapid Risk Assessment](https://infosec.mozilla.org/guidelines/risk/rapid_risk_assessment)
* [Mozilla Security Principles](https://infosec.mozilla.org/fundamentals/security_principles.html)

## safety
The principle of product safety at Mozilla refers to the ways in which a product may be used for abuse or malintent. Oftentimes, it is difficult for product owners, designers, and developers to identify and account for the myriad of ways a product might be used. 

Although aspects of security in product relate to technically keeping product users safe, safety refers to the broader scope of use. The pursuit of some principles, like safety and privacy, can introduce product development tradeoffs as the maximization of one necessitates reduction of the other. For example, a product that completely anonymizes image sharing is private, but can create the potential for networks of criminal activity. 

Safety at Mozilla is not just about ensuring privacy and safety for our users within our products, but taking a pro-active stand against the malicious use of our products for nefarious purposes like: exploitation and manipulation, corruption, human trafficking, abuse, and harassment. 

#### best practices
1. Establish guidelines for intended safe use 
2. Provide opportunities for reporting
3. Have a plan for content moderation

#### key resources
* [Ethical OS](https://ethicalos.org/)
* [Child Abuse and Neglect Prevention](https://www.cdc.gov/violenceprevention/childabuseandneglect/index.html)
* [National Human Trafficking Hotline](https://humantraffickinghotline.org/)

## inclusion
At Mozilla, we are committed to an internet that includes all people in diverse communities collaborating for the common good. Working to employ a diverse and inclusive workforce is a critical element in building more universally conscientious tools. Equally important is an active effort to incorporate inclusive, accessible, and equitable practices into the way that we build and design products. 

When we speak about inclusivity at Mozilla, we are speaking of groups diverse across (including but not limited to): 
* Race
* Gender
* Disability
* Age
* LGBTQIA+
* National origin

#### best practices
1. Incorporate the voices of marginalized groups at every stage of design and development
2. Provide agency
3. Diversify teams
4. "Nothing for us without us"
5. Implement de-biasing methodologies

#### key resources
* [Mozilla Accessibility Release Guidelines](https://wiki.mozilla.org/Accessibility/Guidelines)
* [Accessibility at Mozilla](https://developer.mozilla.org/en-US/docs/Web/Accessibility)
* [Decolonising Design](https://www.decolonisingdesign.com/)

## sustainability
The internet is a powerful enabler of sustainability and a major contributor of greenhouse gas (GHG) emissions that are fueling the climate crisis. The internet is also core to Mozilla’s business. As an organization that aspires to positively impact the lives of humans and our planet, we must account for the effect our products and technologies have on our environment. 

Sustainability at Mozilla focuses on three core values: social connection, economic well-being, and healthy environment. We can implement sustainability in our design and development processes by being good stewards of the online environment. We can start with the following best practices.

#### best practices (adapted from [sustainable web manifesto](https://www.sustainablewebmanifesto.com/))
1. Clean: use renewable energy to power products whenever possible
2. Efficient: use the least amount of energy and material resources possible
3. Open: create accessible products and services 
4. Honest: do not mislead or exploit the people who use your products
5. Regenerative: consider how the product fosters an economy that nourishes people and planet
6. Resilient: make sure your products and services function for people

#### key resources
* [Sustainability at Mozilla](https://wiki.mozilla.org/Projects/Sustainability)
* [Sustainable web manifesto](https://www.sustainablewebmanifesto.com/)
* [Low impact website manifesto](https://lowimpact.organicbasics.com/eur#manifesto)


The integrity toolkit is thanks in LARGE part to my incredible colleagues and friends in the space who helped to refine the draft. Thanks to everyone who contributed to this document! Please feel free to add your names here if you would like to be credited publicly. 

Contributors: 
@nshadowen314







