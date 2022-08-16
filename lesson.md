## Brief

### Preparation

Write about any preparations needed for the lesson, such as tools, installations, prior-knowledge, etcs.

### Self Study Check In

What will you do if there is an earthquake?

``` Step by step on what will you do ```

What will you do if you accidentally drop your production database?

``` Step by step on what will you do ```

What will you do if ....

``` Step by step on what will you do ```


### Lesson Overview

IT infrastructure has become a critical component of today’s business world. As more organizations rely on computing power, storage, and applications; being without these mission-essential assets is an almost unfathomable thought, underpinning the importance of investing in disaster recovery. This glossary explores what disaster recovery is, why it matters, and what goes into developing an effective Disaster Recovery Plan.

---

## Part 1 - Summary Disaster Recovery


<img src="https://user-images.githubusercontent.com/106639884/182769772-4ae3e630-ebaf-4e5d-8c6d-ebc92f538083.png" width="850px"/>


Disaster Recovery, Disaster Recovery Plan (DRP), Disaster Recovery Implementation Plan, or IT Disaster Recovery is a policy and/or process that is designed to assist an organization in executing recovery processes in response to a disaster to protect business IT infrastructure and more generally promote recovery. Disasters take many shapes and forms and can include cyber-attacks, natural disasters, theft or sabotage, power failures, IT network failures, events affecting an organization’s reputation, and also outbreaks of diseases or infections that impact operations.


The **purpose** of a **disaster recovery** is to comprehensively explain the consistent actions that must be taken **BEFORE, DURING and AFTER** the disaster so that the entire team can take those actions. Disaster recovery should address and contains detailed instructions on how to respond to unplanned incidents such as natural disasters, power outages, cyber attacks and any other disruptive events. The plan contains strategies on minimizing the effects of a disaster, so an organization will continue to operate – or quickly resume key operations.


**Why Should a Company or Organization Invest in DR**

Disaster recovery offers organizations a means of salvaging their operational capacity and can save them from devastating losses that could lead to a complete shutdown. By investing in disaster recovery, organizations can build more resilience and a stronger competitive advantage. 

Here are some reasons to why company or organization need to have disaster recovery plan:  

- **Prevent Revenue Loss:** As more businesses rely on technology to operate, IT infrastructure holds tremendous value. Without an operational IT infrastructure, businesses can suffer significant revenue losses.
- **Enhance resilience:** Committing to disaster recovery can be costly, however, it improves an organization’s ability to quickly return to business as usual after a disaster. Through regular DR testing, organizations developed the resiliency they need to limit the effects of disasters on their operations.
- **To Maintain Customer Satisfaction:** DR plans tested develop resilience that pays dividends over time. It’s a well-known fact that customer acquisition costs exceed customer retention costs. By being prepared for disasters, customer attrition is limited if not averted altogether.
- **Improve partner and supply chain confidence:** Due to the connectedness of organizations and their reliance on partner resources and infrastructure, investing in DR can improve relationships and confidence. Short recovery time objectives or RTOs and recovery point objectives or RPOs, as a result of DR planning and investment, are viewed as a commitment to meeting service level agreements, making a stronger case for long-lasting relationships. 
- **Possible Hardware Failure:** IT hardware is machinery and, therefore, prone to breakdown and failure. Having a DR plan accounts for outages and prevents unnecessary downtime.
- **Compliance:** As security and privacy grow in importance, new regulations are introduced to protect sensitive information. Investing in a DR plan ensures that you stay ahead of compliance requirements.

---

## Part 2 - Preparation for Disaster Recovery

<img src="https://user-images.githubusercontent.com/106639884/182758704-a12a06f3-6e10-4e57-8678-1d68485dc1f7.png" width="850px"/>


**1. Know Your Threats**

<img src="https://user-images.githubusercontent.com/106639884/183355867-0d465c59-edd9-47aa-8476-77286be0e7ec.png" width="500px"/>


Learn about the history of your business, the industry and the region, and map out the threats you are most likely to face. These should include natural disasters, geopolitical events like wars or civil unrest, failure to critical equipment like servers, Internet connections or software, and cyber attacks that are most likely to affect your type of business.

Ensure your disaster recovery plan is effective against all, or at least the most likely or most significant threats. If necessary, develop separate DR plans or separate sections within your DR plan for specific types of disasters.


**2. Know Your Assets**


<img src="https://user-images.githubusercontent.com/106639884/183355607-708b065e-1ee7-479a-b79f-35d2dc8f0d86.png" width="500px"/>


It’s important to be comprehensive. Get your team together and make a big list of all the assets that are important for the day-to-day operations of your business. In the IT sphere this includes network equipment, servers, workstations, software, cloud services, mobile devices, and more. Once you have your list organize it into:

- Critical assets your business cannot operate without – for example, an email server
- Important assets that can seriously hamper some activities – for example, a projector used for presentations
- Other assets that will not have a major effect on the business – for example, a recreational system used by employees on their lunch break



**3. Define Your RTO and RPO**


<img src="https://user-images.githubusercontent.com/106639884/183356154-6db65504-83ca-412e-b76b-ca9b6a3a7871.png" width="800px"/>


Define your Recovery Time Objective (RTO) for critical assets. What period of downtime can you sustain? For example, a high traffic eCommerce site sustains major financial damage for every minute of downtime. An accounting firm may be able to sustain a day or two of downtime and resume normal operations, provided there is no data loss. Build a process and obtain technological means that can help you bring operations back online within the RTO.

The term recovery point objective (RPO) refers to the maximum age of files the organization must recover from backup storage to resume normal operations after a disaster occurs. Organizations use RPO to determine the minimum frequency of backups. For example, a four-hour RPO requires backing up at least every four hours.


**4. Set Up Disaster Recovery Sites**

 
1. Cold Computing Sites

The most simplistic type of disaster recovery site. A cold site consists of elements to provide power and networking capability as well as cooling. It does not include other hardware elements such as servers and storage. The use of a cold site is very limiting to a business since before it can be used, backup data along with some additional hardware must be sent to the site and installed. This will impede workflow.


2. Warm Computing Sites

Contain all the elements of a cold site with additional elements including storage hardware such as tape or disk drives along with both servers and switches. Warm sites are "ready to go" in one sense, but they still need to have data transported to them for use in recovery should a disaster occur.

3. Hot Computing Sites

A fully functional backup site that already has important data mirrored to it. This is the ideal disaster recovery site but can be challenging to attain. 


<img src="https://user-images.githubusercontent.com/106639884/183356829-4534866f-6339-49d8-9603-ecfb11c56bae.png" width="500px"/>


**5. Test Backups and Restoration of Services**

Just like how business systems can fail in a disaster, so can backups. There are many horror stories of organizations that had a backup system in place, but discovered too late that backups were not actually working properly. A configuration problem, software error or equipment failure can render your backups useless, and you may never know it unless you test them.

An inseparable part of any disaster recovery plan is to test that data is being replicated correctly to the target location. It’s just as important to test that it’s possible to restore data back to your production site. These tests must be conducted once, when you set up your disaster recovery apparatus, and repeated periodically to ensure the setup is still working.


---


## Part 3 - Activity - Build Your Own Disaster Recovery Plan

```

Work with your group to devine your own business and your own recovery plan
based on discussed threat that might be happen to your business


1. Define your business
2. Define your assets
3. Define your possible threat
4. Define Your RTO and RPO

```
