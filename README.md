Audience and Need

As someone who works for an organization of some significant size, 

I need to:
•	know the precise business meanings, as shared among all my colleagues by definitions, that they intend for the words and phrases they use when they author business documents, especially policy and other governance documents; 

		so that:
•	I can collaborate and communicate most effectively with my colleagues, and 
•	make intelligent decisions and take intelligent actions using those documents and my gifts that:
o	minimize risk to us and our organization, and 
o	maximize value to our organization and its customers; and
•	my colleagues who are responsible for sourcing the software I use have the yardstick of unambiguous business policies and behavioural rules by which to measure the acceptability of that software, based on how well it currently implements these polices and rules, so that I am free to use my judgment and other God-given gifts and never have to say “the computer won’t let us to do that” again.

•	have available a business dictionary, rich with meaning, showing interrelationships among the meanings and the things in the organization that are referred to when using words and phrases in given contexts;                

so that:
•	I can find all the terms and meanings that I share with my colleagues as used in business communication, and understand them in the context of how everything the organization deals with fits together in right relationship, and
•	my colleagues who are responsible for the software I use have the yardstick of shared, agreed business meanings and their business terms by which to measure the acceptability of that software, based on how well its screens and reports use the shared business terms with their single agreed meaning in the given usage context.


What this Project Plans to Build

To realize this vision, a foundation has now been laid in an international standard, “Semantics of Business Vocabulary and Business Rules (SBVR)” (http://www.omg.org/spec/SBVR/1.3/PDF), whose development was led by Donald Chapin. 

SBVR is built on top of the International Standards Organization (ISO)’s terminology science standards of ISO Technical Committee 37 “Terminology and other language and content resources” (www.iso.org/iso/iso_technical_committee.html%3Fcommid%3D48104).

This  Kingdom Code open source project is to build some key standards-related function that can be freely used by anyone.  The tactical purpose of this project is to “prime the pump” by providing enough of an “ecosystem” around the SBVR standard and natural language grammar structure standards (de-facto and formal) to encourage others to provide additional functions that make this vision real in organizations around the world.  

Strangely, but in a very real way known from long experience, the IT community does not have the eyes to see or value this vision.  That is why priming the pump with this ecosystem of function to demonstrate the possibilities, and enable the benefits to begin to be experienced is critical to the realization of this vision.

The scope and benefit of this “ecosystem” is described in a paper “Using Natural Language and SBVR to Author Unambiguous Business Governance Documents” presented in June 2015 at the ISO TC 37 Plenary Meeting Workshop in Japan (http://www.businesssemantics.com/UsingNaturalLanguageAndSBVRToAuthorUnambiguousBusinessGovernanceDocuments(DonaldChapinAndJohn%20Hall).pdf). 

The following components are planned for this SBVR standard “ecosystem”:

1.	A Microsoft Office 365 Word Add-in (for maximum initial coverage) that accesses a specified online SBVR Terminological Dictionary and pastes the meaning the author intended behind his/her words and phrases in the document text using HTML <span>…</span> SBVR-based mark-up.	

Since the pasted meanings appear as mouse-over tool tips, this component will enable business document authors to produce document content where there will be no question in the minds of the readers about the document’s intended meaning.

2.	A simple website interface to some of the REST API function to enable terminologists, business meaning ontologists and other people who create business glossary and SBVR Terminological Dictionary content to determine what entries are needed and gain a head start of the contents of those entries.

3.	A simple website interface to some of the REST API function to enable governance document authors to submit natural language business policy and behavioural rule sentences, have help in clarifying them, and receive back an outline of the formal meaning structure of the sentence and file containing the SBVR Semantic Formulation for the sentence.

These SBVR Semantics Formulations are interpretable in formal logic and serve as the basis for a partially automated transformation of the meaning of natural language sentence into an executable rule in some IT rule language without loosing the original business meaning of the rule.

4.	Most of the function envisioned for this SBVR standard “ecosystem” will be:
•	linguistic analysis-based software using existing linguistic analysis open source capability.  
•	designed as REST APIs capable of being run in the cloud.

Some possible API functions for this ecosystem are:
•	Extraction of noun phrases that are subjects of verbs and objects of verbs or prepositions, as well as verb phrases, in the context of their sentence clauses as input to creating SBVR Terminological Dictionary content.
•	Transformation to/from JSON canonical equivalent of the SBVR standard interchange file (XML) for use with the REST APIs.
•	APIs that implement the vision of the “Using Natural Language and SBVR to Author Unambiguous Business Governance Documents” paper mentioned above.

The primary operational platform of design is Microsoft Azure using the .Net Web API capability with the APIs exposed using Azure App Service API Apps (https://azure.microsoft.com/en-gb/services/app-service/api/).

The planned development platform is the new Microsoft .Net 6 MVC 5 that is cross-platform.  The planned development tools are free .Net tools like Microsoft Visual Studio Community 2015 and Visual Studio Code.  The coding language(s) will be those supported by Azure running under .NET with the nature of the function to be coded determining the choice among alternatives.  GitHub will be the code and documentation repository and continuous deployment to Azure environment.  The project management tool is still be decided.




