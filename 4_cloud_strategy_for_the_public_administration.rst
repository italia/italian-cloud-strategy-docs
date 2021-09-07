================================================================================
4. Cloud Strategy for the Public Administration
================================================================================

Currently, most public services are delivered through PA data centres
that often lack sufficient capabilities to ensure adequate standards of
reliability and resilience. Achieving and maintaining such standards
requires investments and skills that are not currently available in many
central and local public administrations. In this context, the Italian
Cloud Strategy is intended as an implementation methodology of the
“\ *Cloud-First*\ ” policy, a key pillar of the digitalization process
of the PA as identified in the Italian PNRR. This will *guide and
encourage the safe, controlled and complete adoption of Cloud
technologies for the PA*, with the aim, in the long run, that all the
services provided are based on “Cloud-native” applications, i.e.
natively developed on the basis of Cloud paradigms.

The Cloud Strategy for the PA is therefore based on the following
strategic guidelines:

1. **Classification of Data and Services:** definition of a data
classification process to guide and support the migration of PA data and
services to the Cloud;

2. **Qualification of Cloud Services:** implementation of a systematic
process of scrutiny and qualification of Cloud services usable by PA;

3. **National Strategic Hub:** creation of a national infrastructure for
the provision of Cloud services, whose management and control are
autonomous from non-EU actors.

The implementation of these macro-actions will make it possible to
harmonise and regulate the adoption of the Cloud in the PA, as well as
to apply economies of scale to encourage a reduction in management costs
by offering more reliable and resilient digital services.

4.1 Classification of Data and Services
================================================================================

In light of the technological and regulatory challenges concerning the
broad spectrum of available Cloud services, Cloud adoption must be
adequately regulated so as to mitigate the systemic risks involved. The
key element for such regulation is to identify a *systematic process of
classification of data and services* managed by PAs, the result of which
can be used to standardise and steer the process of migration to the PA
Cloud. To this end, the classes of data and services are identified on
the basis of the damage that their compromise, in terms of
*confidentiality*, *integrity* and *availability*, would cause to the
country system. These classes are:

* **Strategic**: data and services which, if compromised, may have an
  impact on national security;

* **Critical**: data and services the impairment of which could be
  detrimental to the maintenance of functions that are important to
  society, health, safety and the economic and social well-being of the
  country;

* **Ordinary**: data and services the impairment of which does not cause
  the interruption of state services nor, in any case, damage the economic
  and social well-being of the country.

This classification leaves aside specific regulations and security
requirements; it only focuses on the possible impact on the country. The
application of the classification process, which is outlined below, will
allow an informed analysis of the impacts and the applicable class, as
well as the identification of the appropriate security and regulatory
requirements. For example, data and services related to essential state
functions and services, i.e. identified within the scope of the
Perimetro Sicurezza Nazionale Cibernetica (PSNC), will be classified as
*Strategic*, citizen health data will be classified as *Critical*, while
data and services related to institutional web portals will be
classified as *Ordinary*.

4.2 Qualification of Cloud Services
================================================================================

Public administrations acquire Cloud services through procurement
procedures which are not flexible enough to keep up with the market
development and, most of all, do not allow the appropriate evaluation of
the technical and organisational risks involved in adopting a specific
service.

In the context of facilitating and guiding the implementation of the
“\ *Cloud-First*\ ” policy for the PA, it is crucial to provide an
*ex-ante qualification schema for Cloud services* that can be purchased
by the PA. This qualification, starting from the experience gained by
AgID, aims at simplifying and regulating the adoption of Cloud services
both from a technical and an administrative point of view. In light of
the presented challenges and the spectrum of cloud services considered,
the qualification of Cloud services should include the analysis of the
following aspects:

1. *Operational management* of Cloud services, with details of the
technical and organisational standards [8]_, and data control measures
applied;

2. *Security requirements* applied in data management and service
delivery, such as encryption keys management policies and security
controls;

3. *Service conditions* applied to service delivery and reporting, such
as availability guarantees and contractual instruments available to
administrations.

On the basis of the analysis of the technological and organisational
solutions available on the market, the three aspects of the analysis
make it possible to identify ex ante the following qualification of
Cloud services.

The spectrum of Cloud services varies from:

* *Public Not Qualified (extra-EU / EU)*, for which control tools on data
  and services are essentially non-existent;

* *Qualified Public Cloud (EU)* services ensuring compliance with relevant
  legislation (e.g. GDPR and NIS), with technical and organisational
  security requirements typically through the use of granular encryption
  systems managed by the CSP provider [9]_, and allow greater control over
  the data and services managed;

* The use of solutions based on Public Clouds with on-premise control of
  security mechanisms, i.e. *Encrypted Public Cloud (IT)*, significantly
  increases the available level of control over data and services,
  introducing greater autonomy from non-EU CSPs in the operational
  management and control of technology infrastructures [10]_;

* Private and Hybrid Cloud solutions allow additional isolation from the
  public regions of the main CSPs, ensured through operational management
  performed by a designated provider under the surveillance and monitoring
  of the national authorities. These implementations can be divided in two
  groups: those based on hyperscaler technology licensed from one or more
  CSPs, i.e. *Licensed Private/Hybrid Cloud (IT)*, and those implemented
  using commercial technologies that are qualified by means of
  technological scrutiny and certification procedures, i.e. *Qualified
  Private Cloud (IT)*.

The qualified Cloud services shall be used, according to the data
classification outcome, enforcing the following constraints:

* The Qualified and Encrypted Public Cloud offerings shall host
  *ordinary* data and services;

* The Encrypted Public Cloud, the Licensed Private/Hybrid Cloud shall
  host *critical* data and services;

* The Licensed Private/Hybrid and Qualified Private Cloud shall host
  *strategic* data and services.

The process of qualification of Cloud services, in order to simplify the
adoption of Cloud services in the PA should end with the creation of an
*electronic marketplace of qualified Cloud services*\  [11]_. This
marketplace should be the means by which administrations are guided, in
accordance with the data and services classification process, in the
choice of the Cloud services that are most suitable for them and can be
purchased through simplified and pre-negotiated administrative tools.

4.3 The National Strategic Hub
================================================================================

The rationalisation and enhancement of security and reliability of the
PA’s multiple data centres involves the development of a new IT
infrastructure that is able to serve the multiple PAs located throughout
the country: *the National Strategic Hub (NSH, known in Italian as “Polo
Strategico Nazionale” - PSN)*\  [12]_.

The NSH aims to equip the PA with Cloud technologies and infrastructures
that can benefit from the highest guarantees of reliability, resilience
and independence. To this end, the NSH will be geographically
distributed throughout the country and located at the most suitable
sites [13]_, in order to ensure adequate levels of business continuity
and fault tolerance. The operational management of the NSH will be
entrusted to qualified national providers on the basis of appropriate
technical and organisational requirements. The providers will have to
ensure control over the data in accordance with the relevant
legislation, and it should help the PA to negotiate appropriate
contractual conditions with Cloud Service Providers.

The NSH should allow the PA to guarantee, by design, compliance with
security requirements, e.g. PSNC and NIS, and should enable the
migration - which may in a first phase be performed via a
*lift-and-shift* process - to IaaS and PaaS Cloud service models.

According to the classification provided in the previous section, the
NSH will offer the *Encrypted Public Cloud (IT)* services, i.e. it will
support for instance, on-premise encryption tools integrated on a Public
Cloud for the PA, and the spectrum of private Cloud services, i.e. the
*Licensed Private/Hybrid Cloud (IT)* and the *Qualified Private Cloud
(IT)*.

In accordance with the classification and qualification procedures, the
aim of the NSH is to support central administrations and the main local
administrations, e.g. regional PA, local health authorities and
metropolitan cities.

.. [8]
   For example, the international standards ISO 27017/27018, ISO 22301
   and CSA STAR.

.. [9]
   These services include, for example, the use of key management
   systems (KMS), based on special hardware modules (i.e. HSM).

.. [10]
   For example, by using an on-premise HSM to manage the keys used to
   encrypt data on the Public Cloud.

.. [11]
   This proposal is similar to what has already been successfully
   implemented in other countries, e.g. the UK Digital Marketplace
   https://www.digitalmarketplace.service.gov.uk

.. [12]
   As provided for in Article 33-septies, paragraph 4, of the Decree-Law
   of 18 October 2012, no. 179, converted, with amendments, by Law No.
   179 of 17 December 2012. 221.

.. [13]
   Examples include the physical security levels of data centers,
   mitigation of natural disaster risk and integration with multiple
   connectivity sources.