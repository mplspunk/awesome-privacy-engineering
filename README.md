## Awesome Privacy Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources related to privacy engineering

### Content
---
* [Courses](#courses)
* [Books](#books)
* [Data Deletion, Data Mapping, and Data Subject Access Requests](#data-deletion-data-mapping-and-data-subject-access-requests)
* [Privacy Tech Series](#privacy-tech-series-by-lea-kissner)
* [Privacy Threat Modeling](#privacy-threat-modeling)
* [Machine Learning and Algorithmic Bias](#machine-learning-and-algorithmic-bias)
* [Facial Recognition](#facial-recognition)
* [De-Identification and Anonymization](#de-identification-and-anonymization)
* [Homomorphic Encryption](#homomorphic-encryption)
* [Tokenization](#tokenization)
* [Secure Multi-Party Computation](#secure-multi-party-computation)
* [Synthetic Data](#synthetic-data)
* [Differential Privacy and Federated Learning](#differential-privacy-and-federated-learning)
* [Designing for Trust with Users](#designing-for-trust-with-users)
* [Deceptive Design Patterns](#deceptive-design-patterns)
* [Tagging Personally Identifiable Information](#tagging-personally-identifiable-information)
* [Regulatory and Framework Resources](#regulatory-and-framework-resources)
* [Conferences](#conferences)
* [Career](#career)
* [Miscelleaneous](#miscellaneous)
* [Other Awesome Privacy Curations](#other-awesome-privacy-curations)
* [Related Github Topics](#related-github-topics)



### Courses
---
* [OpenMined Courses](https://courses.openmined.org/)
    * Our Privacy Opportunity (Beginner) (7.7 hours)
    * Introduction to Remote Data Science (Intermediate) (8 hours)
    * Foundations of Private Computation (Intermediate) (60 hours)
    * Federated Learning on Mobile (Intermediate) (40 hours) (Not Yet Released)
* [Data Privacy and Anonymization in R](https://www.datacamp.com/courses/data-privacy-and-anonymization-in-r) - Datacamp course that covers publicly releasing data sets with a differential privacy guarantee. 
* [Data Privacy and Anonymization in Python](https://www.datacamp.com/courses/data-privacy-and-anonymization-in-python) - Datacamp course on learning to process sensitive information with privacy-preserving techniques.
* [Secure and Private AI (Udacity)](https://www.udacity.com/course/secure-and-private-ai--ud185#) - Udacity course that covers how to extend PyTorch with the tools necessary to train AI models that preserve user privacy.
* [Practical Data Ethics](https://ethics.fast.ai) - This class was originally taught in-person at the University of San Francisco Data Institute in January-February 2020.
* [Privacy-Conscious Computer Systems](http://cs.brown.edu/courses/csci2390/2021/index.html) - This class at Brown University (CSCI 2390) focuses on how to design computer systems that protect users' privacy.
* [Privacy by Design: Data Classification](https://www.linkedin.com/learning/privacy-by-design-data-classification/my-path-to-privacy) - LinkedIn Learning course by Nishant Bhajaria.
* [Privacy by Design: Data Sharing](https://www.linkedin.com/learning/privacy-by-design-data-sharing/privacy-and-data-sharing) - LinkedIn Learning course by Nishant Bhajaria.
* [Implementing a Privacy, Risk, and Assurance Program](https://www.linkedin.com/learning/implementing-a-privacy-risk-and-assurance-program/privacy-and-your-business) - LinkedIn Learning course by Nishant Bhajaria.
* [Data Protocol](https://dataprotocol.com/courses) - Courses to teach developers and technical professionals how to build products responsibly and partner with platforms effectively.
* [Carnegie Mellon University - Privacy Engineering Certificate](https://privacy.cs.cmu.edu/privacy-cert/index.html) - Four-week certificate program that revolves around a combination of mini-tutorials, class discussions, and hands-on exercises designed to ensure that students develop practical knowledge of all key privacy engineering areas.
* [Technical Privacy Masterclass](https://learn.privado.ai/courses/technical-privacy-masterclass) - In four modules, this course from Privado is designed to deliver privacy leaders and their teams with an overview of the pillars of a proactive privacy program.
* [Privacy Quest](https://www.privacyquest.org/) - A gamified approach to learning about privacy engineering, Privacy Quest uses challenges and competitions to build your privacy and security knowledge.
* [Hitchhiker's Guide to Privacy Engineering](https://hgpe.orderofepoch.com/) - The goal of this creative privacy project is to offer a fun, engaging, and immersive privacy learning experience for privacy lawyers to improve their technical privacy skills.

### Books
---
* [The Privacy Engineer's Manifesto: Getting from Policy to Code to QA to Value (Michelle Dennedy, Jonathan Fox, Tom Finneran)](https://www.amazon.com/Privacy-Engineers-Manifesto-Getting-Policy/dp/1430263555)
* [Information Privacy Engineering and Privacy by Design: Understanding Privacy Threats, Technology, and Regulations Based on Standards and Best Practices (William Stallings)](https://www.amazon.com/Information-Privacy-Engineering-Design-Understanding/dp/0135302153)
* [The Algorithmic Foundation of Differential Privacy (Cynthia Dwork, Aaron Roth)](https://columbia.github.io/private-systems-class/papers/Dwork2013Foundations.pdf)
* [Building an Anonymization Pipeline: Creating Safe Data (Luk Arbuckle, Khaled El Emam)](https://www.amazon.com/Building-Anonymization-Pipeline-Creating-Safe/dp/1492053430)
* [Strategic Privacy by Design (R. Jason Cronk)](https://iapp.org/store/books/a191a00000345yDAAQ/)
* [The Architecture of Privacy: On Engineering Technologies that Can Deliver Trustworthy Safeguards (Courtney Bowman, Ari Gesher, John K. Grant, Daniel Slate, Elissa Lerner)](https://www.amazon.com/Architecture-Privacy-Engineering-Technologies-Trustworthy-ebook/dp/B014LPOXU2)
* [Data Privacy: A Runbook for Engineers (Nishant Bhajaria)](https://www.manning.com/books/data-privacy)
* [Privacy Design Strategies (The Little Blue Book) (Jaap-Henk Hoepman)](https://www.cs.ru.nl/~jhh/publications/pds-booklet.pdf)
* [Privacy Is Hard and Seven Other Myths: Achieving Privacy through Careful Design (Jaap-Henk Hoepman)](https://www.amazon.com/Privacy-Hard-Seven-Other-Myths/dp/0262045826/)
* [Privacy Engineering: A Dataflow and Ontological Approach (Ian Oliver)](https://www.amazon.com/Privacy-Engineering-Dataflow-Ontological-Approach/dp/1497569710)
* [Practical Data Privacy (Katharine Jarmul)](https://www.oreilly.com/library/view/practical-data-privacy/9781098129453/) [(and accompanying Jupyter notebooks)](https://github.com/kjam/practical-data-privacy)
* [Threat Modeling: Designing for Security (Adam Shostack)](https://www.amazon.com/Threat-Modeling-Designing-Adam-Shostack/dp/1118809998/)

### Data Deletion, Data Mapping, and Data Subject Access Requests
---
* [Deleting Data Distributed Throughout Your Microservices Architecture](https://blog.twitter.com/engineering/en_us/topics/infrastructure/2020/deleting-data-distributed-throughout-your-microservices-architecture.html) - Microservices architectures tend to distribute responsibility for data throughout an organization. This poses challenges to ensuring that data is deleted.
* [Handling Data Erasure Requests in Your Data Lake with Amazon S3 Find and Forget](https://aws.amazon.com/blogs/big-data/handling-data-erasure-requests-in-your-data-lake-with-amazon-s3-find-and-forget/) - Amazon S3 Find and Forget enables you to find and delete records automatically in data lakes on Amazon S3. 
    * [Amazon S3 Find and Forget](https://github.com/awslabs/amazon-s3-find-and-forget)
* [How to Delete User Data in an AWS Data Lake](https://aws.amazon.com/blogs/big-data/how-to-delete-user-data-in-an-aws-data-lake/) - This post walks through a framework that helps you purge individual user data within your organization’s AWS hosted data lake, and an analytics solution that uses different AWS storage layers, along with sample code targeting Amazon S3.
    * [Data Purging AWS Data Lake](https://github.com/aws-samples/data-purging-aws-data-lake)
* [Best Practices: GDPR and CCPA Compliance Using Delta Lake](https://docs.databricks.com/security/privacy/gdpr-delta.html) - Article that describes how to use Delta Lake on Databricks to manage General Data Protection Regulation (GDPR) and California Consumer Privacy Act (CCPA) compliance for a data lake. 
* [Klaro!](https://github.com/kiprotect/klaro) - Klaro is a simple consent management platform (CMP) and privacy tool that helps you to be transparent about the third-party applications on your website.
* [OpenDSR](https://github.com/opengdpr/OpenDSR) - A common framework enabling companies to work together to protect consumers' privacy and data rights (formerly known as OpenGDPR.)
* [PrivacyBot](https://github.com/privacybot-berkeley/privacybot) - PrivacyBot is a simple automated service to initiate CCPA deletion requests with data brokers.
* [Cookie Consent](https://github.com/osano/cookieconsent) - An opensource, lightweight JavaScript plugin for alerting users about the use of cookies on a website. It is designed to help quickly comply with the European Union Cookie Law, CCPA, GDPR and other privacy laws.
* [Fides](https://github.com/ethyca/fides) - An open-source tool that allows you to easily declare your systems' privacy characteristics, track privacy related changes to systems and data in version control, and enforce policies in both your source code and your runtime infrastructure.
    * [Fideslang](https://github.com/ethyca/fideslang) - Open-source description language for privacy to declare data types and data behaviors in your tech stack in order to simplify data privacy globally. Supports GDPR, CCPA, LGPD and ISO 19944.
    * [Fidesops](https://github.com/ethyca/fidesops) - DSAR Orchestration: Privacy Request automation to fulfill GDPR, CCPA, and LGPD data subject requests.
* [Privado](https://github.com/Privado-Inc/privado) - Privado is an open source static code analysis tool to discover data flows in the code. It detects the personal data being processed, and further maps the journey of the data from the point of collection to going to interesting sinks such as third parties, databases, logs, and internal APIs.
* [Detecting PII Using Amazon Comprehend](https://docs.aws.amazon.com/comprehend/latest/dg/get-started-api-pii.html) - To detect entities that contain personally identifiable information (PII) in a document, use the Amazon Comprehend DetectPiiEntities operation. 
* [Octopii](https://github.com/redhuntlabs/Octopii) - Octopii is an open-source AI-powered PII scanner that can look for image assets such as Government IDs, passports, photos and signatures in a directory.
* [Data Profiler](https://github.com/capitalone/DataProfiler) - DataProfiler is a Python library created by Capital One to make data analysis, monitoring, and sensitive data detection easy.
* [PII Catcher](https://github.com/tokern/piicatcher) - Scan databases and data warehouses for PII data. Tag tables and columns in data catalogs like Amundsen and Datahub.

### Privacy Tech Series by [Lea Kissner](https://twitter.com/leakissner?lang=en)
---
* [Interface Design: The Who/What/Where Rule](https://iapp.org/news/a/interface-design-the-who-what-where-rule/)
* [Vulnerability versus Incident](https://iapp.org/news/a/tech-talk-vulnerability-vs-incident/)
* [Deidentification versus Anonymization](https://iapp.org/news/a/de-identification-vs-anonymization/)
* [Aggregating Over Anonymized Data](https://iapp.org/news/a/aggregating-over-anonymized-data/)
* [Thinking Through ACL-Aware Data Processing](https://iapp.org/news/a/acl-aware-data-processing/)
* [Settings and Surfaces](https://iapp.org/news/a/talking-tech-settings-and-surfaces/)
* [Comprehensible Access Control Lists](https://iapp.org/news/a/privacy-engineering-comprehensible-access-control-lists/)
* [Data Retention in a Distributed System](https://iapp.org/news/a/data-retention-in-a-distributed-system/)
* [Setting Data Retention Timelines](https://iapp.org/news/a/setting-data-retention-timelines/)
* [Handling Human Names](https://iapp.org/news/a/talking-tech-handling-human-names/)

### Privacy Threat Modeling
---
* [LINDDUN](https://www.linddun.org/linddun) - The LINDDUN privacy engineering framework provides systematic support for the elicitation and mitigation of privacy threats in software systems.
* [LINDDUN GO](https://www.linddun.org/go) - LINDDUN GO is designed to give you a quick start to privacy threat modeling.
* [PLOT4AI](https://plot4.ai/) - Privacy Library Of Threats 4 Artificial Intelligence (PLOT4AI) is a threat modeling library to help practitioners build responsible artificial intelligence.
* [Draw.io Libraries for Threat Modeling](https://github.com/michenriksen/drawio-threatmodeling) - Collection of custom libraries for using the Draw.io diagramming application for threat modeling.
* [Models of Applied Privacy (MAP)](https://github.com/comcast/map) - A privacy threat modeling persona framework that developers can use to test and document privacy threats, and find edge cases of privacy harm.
* [Privacy Adversarial Framework (PAF)](https://github.com/facebookresearch/privacy_adversarial_framework) - Developed by Facebook, the Privacy Adversarial Framework (PAF) is a knowledgebase of privacy-focused adversarial tactics and techniques that is heavily inspired by MITRE ATT&CK®.
* [PANOPTIC™ Privacy Threat Model](https://ptmworkshop.gitlab.io/#/panoptic) - MITRE PANOPTIC™, the Pattern and Action Nomenclature Of Privacy Threats In Context, is a privacy threat taxonomy for breaking down and describing privacy attacks against individuals and groups of individuals.

### Machine Learning and Algorithmic Bias
---
* [Pribot and Polisis](https://pribot.org) - Polisis is a unique way of visualizing privacy policies. Using deep learning, it allows you to know what the company is collecting about you, what it is sharing, etc.
* [Ethical Machine Learning - Spotting and Preventing Proxy Bias](https://github.com/ropenscilabs/proxy-bias-vignette/blob/master/EthicalMachineLearning.ipynb) - Jupyter Notebook from rOpenSciLabs that explores several ways of detecting unintentional bias and removing it from a predictive model.
* [Aequitas](https://dsapp.uchicago.edu/aequitas/) - An open source bias audit toolkit developed by the Center for Data Science and Public Policy at University of Chicago, can be used to audit the predictions of machine learning based risk assessment tools  to understand different types of biases, and make informed decisions about developing and deploying such systems.
* [Fairness in Machine Learning Engineering](https://developers.google.com/machine-learning/crash-course/fairness/video-lecture) - Google's Machine Learning Crash Course includes a 70-minute section on fairness.
* [How to Incorporate Ethics and Risk into Your Machine Learning Development Process](https://medium.com/the-official-integrate-ai-blog/how-to-incorporate-ethics-and-risk-into-your-machine-learning-development-process-4b8e9bc78ce0) - To help highlight ethics and risk in machine learning, this article looks at the six steps involved in developing an ML system, what happens in each step, and the risk and ethics questions that arise.
* [DrivenData: Deon](https://deon.drivendata.org/examples/) - A command line tool to easily add an ethics checklist to your data science projects.
* [People + AI Guidebook](https://pair.withgoogle.com) - A friendly, practical guide that lays out some best practices for creating useful, responsible AI applications.
    * [Why Some Models Leak Data](https://pair.withgoogle.com/explorables/data-leak/) - Machine learning models use large amounts of data, some of which can be sensitive. If they're not trained correctly, sometimes that data is inadvertently revealed.
    * [Datasets Have Worldviews](https://pair.withgoogle.com/explorables/dataset-worldviews/) - Every dataset communicates a different perspective. When you shift your perspective, your conclusions can shift, too.
    * [Measuring Fairness](https://pair.withgoogle.com/explorables/measuring-fairness/) - How do you make sure a model works equally well for different groups of people? 
    * [How Randomized Response Can Help Collect Sensitive Information Responsibly](https://pair.withgoogle.com/explorables/anonymization/) - Giant datasets are revealing new patterns in cancer, income inequality and other important areas. However, the widespread availability of fast computers that can cross reference public data is making it harder to collect private information without inadvertently violating people's privacy. Modern randomization techniques can help preserve anonymity.
    * [Can a Model Be Differentially Private and Fair?](https://pair.withgoogle.com/explorables/private-and-fair/) - Training with differential privacy limits the information about any one data point that is extractable but in some cases there’s an unexpected side-effect: reduced accuracy with underrepresented subgroups disparately impacted.
    * [Hidden Bias](https://pair.withgoogle.com/explorables/hidden-bias/) - Models trained on real-world data can encode real-world bias. Hiding information about protected classes doesn't always fix things — sometimes it can even hurt.
    * [How Federated Learning Protects Privacy](https://pair.withgoogle.com/explorables/federated-learning/) - With federated learning, it’s possible to collaboratively train a model with data from multiple users without any raw data leaving their devices.
* [Fairlearn](https://github.com/fairlearn/fairlearn) - A Python package to assess and improve fairness of machine learning models. 
* [InterpretML](https://interpret.ml) - A toolkit to help understand models and enable responsible machine learning.
* [ML Privacy Meter](https://github.com/privacytrustlab/ml_privacy_meter) - A tool to quantify the privacy risks of machine learning models with respect to inference attacks, notably membership inference attacks 
* [Failure Modes in Machine Learning](https://docs.microsoft.com/en-us/security/engineering/failure-modes-in-machine-learning) - Privacy concerns can include model inversion, membership inference attack, etc.
* [Privacy Considerations in Large Language Models](https://ai.googleblog.com/2020/12/privacy-considerations-in-large.html) - 
The potential for models to leak details from the data on which they’re trained may be a concern for all large language models, and additional issues may arise if a model trained on private data were to be made publicly available.
* [Explaining Decisions Made with AI](https://ico.org.uk/for-organisations/guide-to-data-protection/key-data-protection-themes/explaining-decisions-made-with-artificial-intelligence/) - Guidance by the UK's Information Commissioner's Office (ICO) and The Alan Turing Institute aims to give organisations practical advice to help explain the processes, services and decisions delivered or assisted by AI, to the individuals affected by them.
* [Considerations for Sensitive Data within Machine Learning Datasets](https://cloud.google.com/architecture/sensitive-data-and-ml-datasets) - This Google Cloud article aims to highlight some strategies for identifying and protecting sensitive information, and processes to help address security concerns you might have with your machine learning data.
* [Responsible AI Toolbox](https://github.com/microsoft/responsible-ai-toolbox) - Responsible AI Toolbox is a suite of tools from Microsoft that provides a collection of model and data exploration and assessment user interfaces that enable a better understanding of AI systems. The Toolbox consists of four dashboards: an Error Analysis dashboard, an Interpretability dashboard, a Fairness dashboard, and a Responsible AI dashboard.
* [Of Oaths and Checklists](https://www.oreilly.com/radar/of-oaths-and-checklists/) - A checklist for people who are working on data projects, authored by DJ Patil, Hilary Mason, and Mike Loukides.
* [Intro to AI Ethics](https://www.kaggle.com/learn/intro-to-ai-ethics) - A Kaggle Learn course to explore practical tools to guide the moral design of AI systems.
* [Failure Modes in Machine Learning](https://docs.microsoft.com/en-us/security/engineering/failure-modes-in-machine-learning) - Documentation compiled by Microsoft regarding the different ways that machine learning can fail, both intentionally (through adversarial attack) and unintentionally (formally correct but completely unsafe outcome).
* [Apple Privacy-Preserving Machine Learning Workshop 2022](https://machinelearning.apple.com/updates/ppml-workshop-2022) - In June 2022, Apple hosted the Workshop on Privacy-Preserving Machine Learning (PPML), which brought Apple and members of the academic research communities together to discuss the state of the art in the field of privacy-preserving machine learning through a series of talks and discussions. This post includes highlights from workshop discussions and recordings of select workshop talks.
* [Machine Unlearning](https://github.com/jjbrophy47/machine_unlearning) - A compilation of existing literature about machine unlearning, a process through which a machine learning model can be made to forget one of its training data points.
* [Fairness and Machine Learning: Limitations and Opportunities](https://fairmlbook.org/) - An online textbook by Solon Barocas, Moritz Hardt, and Arvind Narayanan.
* [AI Fairness 360 (AIF360)](https://github.com/Trusted-AI/AIF360) - A comprehensive set of fairness metrics for datasets and machine learning models, explanations for these metrics, and algorithms to mitigate bias in datasets and models.
* [Model Card Toolkit](https://github.com/tensorflow/model-card-toolkit) - Google's Model Card Toolkit streamlines and automates generation of [Model Cards](https://modelcards.withgoogle.com/about), machine learning documents that provide context and transparency into a model's development and performance.
* [Responsible AI by Design](https://www.microsoft.com/en-us/ai/responsible-ai?activetab=pivot1%3aprimaryr6) - Microsoft's hub for policies, practices, and tools that make up its framework for Responsible AI by Design. Includes a Responsible AI Standard, Responsible AI Impact Assessment Guide, and Responsible AI Impact Assessment Template.
* [Private AI Bootcamp](https://www.youtube.com/playlist?list=PLD7HFcN7LXRef-eTSGt_XOUJLZNoDINUn) - Youtube playlist of lectures from the Private AI Bootcamp at Microsoft Research Redmond in December 2019.
* [Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox) - Python library from the Linux Foundation AI & Data Foundation (LF AI & Data) that enables developers and researchers to defend and evaluate machine learning models and applications against the adversarial threats of evasion, poisoning, extraction, and inference. 
* [Trustworthy ML Initiative](https://www.trustworthyml.org/home) - The Trustworthy ML Initiative is a community of researchers and practitioners working on topics related to machine learning models and algorithms that are accurate, explainable, fair, privacy-preserving, causal, and robust.
* [AI Nutrition Facts Labels](https://nutrition-facts.ai/) - Tool from Twilio that allows generation of AI Nutrition Labels intended to give consumers and businesses a more transparent and clear view into ‘what's in the box’.
* [Explainable Artificial Intelligence](https://interpretable-ml-class.github.io/) - This course syllabus from Harvard University aims to familiarize students with the recent advances in the emerging field of eXplainable Artificial Intelligence (XAI).

### Facial Recognition
---
* [Understanding Facial Detection, Characterization and Recognition Technologies (Future of Privacy Forum (FPF) Infographic)](https://fpf.org/wp-content/uploads/2018/09/FPF_FaceRecognitionPoster_R5.pdf)
* [Fawkes](https://github.com/Shawn-Shan/fawkes) - Fawkes, privacy preserving tool against facial recognition systems, developed by researchers at SANDLab, University of Chicago.
* [LowKey: Leveraging Adversarial Attacks to Protect Social Media Users from Facial Recognition](https://openreview.net/forum?id=hJmtwocEqzc) - Adversarial filter that accounts for the entire image processing pipeline and is demonstrably effective against industrial-grade pipelines that include face detection and large scale databases.  Also includes an [easy-to-use webtool](https://lowkey.umiacs.umd.edu/) that significantly degrades the accuracy of Amazon Rekognition and the Microsoft Azure Face Recognition API.
* [Magritte](https://github.com/google/magritte) - Google's Magritte is a MediaPipe-based library to redact faces from photos and videos. It provides processing graphs to reliably detect faces, track their movements in videos, and disguise the person's identity by obfuscating their face.
* [Creating a Serverless Face Blurring Service for Photos in Amazon S3](https://aws.amazon.com/blogs/compute/creating-a-serverless-face-blurring-service-for-photos-in-amazon-s3/) - This blog post shows how to build a serverless face blurring service for photos uploaded to an Amazon S3 bucket.

### De-Identification and Anonymization
---
* [A Visual Guide to Practical Data De-Identification (FPF Infographic)](https://fpf.org/wp-content/uploads/2017/06/FPF_Visual-Guide-to-Practical-Data-DeID.pdf)
* [NIST Privacy Engineering Program - De-Identification Tools](https://www.nist.gov/itl/applied-cybersecurity/privacy-engineering/collaboration-space/browse/de-identification-tools)
* [Presidio](https://github.com/microsoft/presidio) - Context aware, pluggable and customizable PII anonymization service for text and images, developed by Microsoft.
* [Redacting Sensitive Information with User-Defined Functions in Amazon Athena](https://aws.amazon.com/blogs/big-data/redacting-sensitive-information-with-user-defined-functions-in-amazon-athena/) - Amazon Athena supports user-defined functions, a feature that enables you to write custom scalar functions and invoke them in SQL queries. 
* [AWS AI-Powered Health Data Masking](https://aws.amazon.com/solutions/implementations/ai-powered-health-data-masking/) - The AI-Powered Health Data Masking solution in the AWS Solutions Library helps healthcare organizations identify and mask health data in images or text.
* [Anonymize Your Data Using Amazon S3 Object Lambda](https://jeromevdl.medium.com/anonymise-your-data-using-amazon-s3-object-lambda-4489f0ec3863) - Leverage AWS S3 Object Lambdas in order to anonymize data.
* [Static Data Masking for Azure SQL Database and SQL Server](https://azure.microsoft.com/en-us/blog/static-data-masking-preview/) - Microsoft's Static Data Masking is a data protection feature that helps users sanitize sensitive data in a copy of their SQL databases. It is compatible with SQL Server (SQL Server 2012 and newer), Azure SQL Database (DTU and vCore-based hosting options, excluding Hyperscale), and SQL Server on Azure Virtual Machines.
* [Google Cloud Data Loss Prevention](https://cloud.google.com/dlp) - Google Cloud's fully managed service designed to help you discover, classify, and protect sensitive data.
* [ARX Data Anonymization Tool](https://arx.deidentifier.org/) - ARX is a comprehensive open source software for anonymizing sensitive personal data.
* [UTD Anonymization ToolBox](http://cs.utdallas.edu/dspl/cgi-bin/toolbox/index.php) - UT Dallas Data Security and Privacy Lab compiled various anonymization methods into a toolbox for public use by researchers.
* [Kodex](https://github.com/kiprotect/kodex) - An open-source toolkit for privacy and security engineering. It helps you to automate data security and data protection measures in your data engineering workflows.
* [Data Anonymizer Extension for PostgreSQL](https://pgxn.org/dist/postgresql_anonymizer/0.0.3/) - A set of SQL functions that remove personally identifiable values from a PostgreSQL table and replace them with random-but-plausible values.
* [Anonimatron](https://realrolfje.github.io/anonimatron/) - Free, extendable, open source data anonymization tool.
* [Anonymizer MySQL](https://www.npmjs.com/package/anonymizer-mysql) - This simple tool will allow you to make anonymizerd clone of your database.
* [MySQL Data Anonymizer](https://github.com/globalis-ms/mysql-data-anonymizer) - MySQL Data Anonymizer is a PHP library that anonymizes your data in the database.
* [Anonymizer](https://github.com/DivanteLtd/anonymizer) - Anonymizer is a universal tool to create anonymized DBs for projects.
* [anonymize-it](https://github.com/elastic/anonymize-it) - The Elastic Machine Learning Team's general purpose tool for suppression, masking, and generalization of fields to aid data pseudonymization.
* [Singapore Guide to Anonymization](https://www.pdpc.gov.sg/-/media/Files/PDPC/PDF-Files/Advisory-Guidelines/Guide-to-Basic-Anonymisation-31-March-2022.ashx) - The Singapore Personal Data Protection Commission (PDPC) has published the Guide on Basic Anonymization to provide more practical guidance for businesses on how to appropriately perform basic anonymization and de-identification of various datasets.
* [Transforming Data in Google Cloud Platform](https://cloud.google.com/dlp/docs/transformations-reference) - This reference covers the available de-identification techniques, or transformations, that can be applied in Google Cloud's Data Loss Prevention (i.e., redaction, replacement, masking, crypto-based tokenization, bucketing, date shifting, and time extraction).
* Measuring Re-Identification Risk / Privacy Definitions - A series of helpful blog posts by Damien Desfontaines on privacy definitions that attempt to quantify the level of risk associated with a dataset.
    *  [k-anonymity](https://desfontain.es/privacy/k-anonymity.html)
    *  [k-map](https://desfontain.es/privacy/k-map.html)
    *  [l-diversity](https://desfontain.es/privacy/l-diversity.html)
    *  [delta-presence](https://desfontain.es/privacy/delta-presence.html)
* [Technical Privacy Metrics: a Systematic Survey](https://arxiv.org/abs/1512.00327) - Paper by Isabel Wagner and David Eckhoff that discusses over 80 privacy metrics and introduces categorizations based on the aspect of privacy they measure, their required inputs, and the type of data that needs protection. They also present a method on how to choose privacy metrics based on nine questions that help identify the right privacy metrics for a given scenario.
* [Data Anonymization Tool](https://www.pdpc.gov.sg/Help-and-Resources/2018/01/Basic-Anonymisation) - The Singapore PDPC has launched a free Data Anonymization tool to help organizations transform simple datasets by applying basic anonymization techniques. 
* [Masked AI](https://github.com/cado-security/masked-ai) - Python SDK and CLI wrappers that enable safer usage of public large language models (LLMs) like OpenAI/GPT4 by removing sensitive data from prompts and replacing it with fake data before submitting to the OpenAI API.

### Homomorphic Encryption
---
* [Building Safe A.I.: A Tutorial for Encrypted Deep Learning](https://iamtrask.github.io/2017/03/17/safe-ai/) - Blogpost on how to train a neural network that is fully encrypted during training.
* [HElib](https://github.com/homenc/HElib) - HElib is an open-source software library that implements homomorphic encryption.
* [Microsoft SEAL](https://github.com/microsoft/SEAL) - Microsoft SEAL is an easy-to-use open-source (MIT licensed) homomorphic encryption library developed by the Cryptography and Privacy Research group at Microsoft.
* [nGraph-HE: A Graph Compiler for Deep Learning on Homomorphically Encrypted Data](https://arxiv.org/abs/1810.10121) - Intel Research proposes an extension to its deep learning compiler to operate on homomorphically encrypted data.
* [Google Fully-Homomorphic-Encryption](https://github.com/google/fully-homomorphic-encryption) - This repository created by Google contains open-source libraries and tools to perform fully homomorphic encryption operations on an encrypted data set.
* [Palisade Homomorphic Encryption Software Library](https://palisade-crypto.org/) - An open-source project that provides efficient implementations of lattice cryptography building blocks and homomorphic encryption schemes.
* [TFHE](https://github.com/tfhe/tfhe) - The original version of TFHE (Fast Fully Homomorphic Encryption Library over the Torus) that implements the base arithmetic and functionalities (bootstrapped and leveled), allowing you to perform computations over encrypted data.
* [Concrete](https://github.com/zama-ai/concrete) - The concrete ecosystem is a set of crates (packages in the Rust language) that implements Zama's variant of TFHE, while most of the complexity of fully homomorphic encryption is hidden under high-level APIs.
* [FHE.org](https://fhe.org/) - Community of researchers and developers interested in advancing Fully Homomorphic Encryption (FHE) and other secure computation techniques.

### Tokenization
---
* [AWS Serverless Tokenization](https://github.com/aws-samples/aws-serverless-tokenization) - Learn how to use Lambda Layers to develop a serverless tokenization solution in AWS.
* [auto-data-tokenize](https://github.com/GoogleCloudPlatform/auto-data-tokenize) - This repo demonstrates a reference implementation of detecting and tokenizing sensitive structured data within Google Cloud Platform.

### Secure Multi-Party Computation
---
* [Private Join and Compute](https://github.com/Google/private-join-and-compute) - Google's implementation of the "Private Join and Compute" functionality. This functionality allows two users, each holding an input file, to privately compute the sum of associated values for records that have common identifiers.
* [Facebook Private Computation Solutions](https://github.com/facebookresearch/FBPCS) - Facebook Private Computation Solutions (FBPCS) is a secure, privacy safe and scalable architecture to deploy multi-party computation applications in a distributed way on virtual private clouds via Private Scaling architecture. FBPCS consists of various services, interfaces that enable various private measurement solutions, e.g. Private Lift.
* [Facebook Private Computation Framework](https://github.com/facebookresearch/fbpcf) - Facebook Private Computation Framework (FBPCF) library allows developers to perform randomized controlled trials, without leaking information about who participated or what action an individual took. It uses secure multiparty computation to guarantee this privacy. FBPCF is for scaling multi-party computation up via threading.

### Synthetic Data
---
* [Data Synthesizer](https://github.com/DataResponsibly/DataSynthesizer) - DataSynthesizer generates synthetic data that simulates a given dataset.
* [Faker](https://pypi.org/project/faker) - Faker is a Python package that generates fake data for you.
* [Pynonymizer](https://pypi.org/project/pynonymizer/) - Pynonymizer is a universal tool for translating sensitive production database dumps into anonymized copies.
* [Synthetic Data Vault](https://sdv.dev) - The Synthetic Data Vault (SDV) enables end users to easily generate Synthetic Data for different data modalities, including single table, multi-table and time series data.
* [Synthetic Data Generation: Quality, Privacy, Bias (Workshop at ICLR 2021)](https://sdg-quality-privacy-bias.github.io/) - Workshop on the intersection of challenges regarding quality, privacy and bias in synthetic data generation.
* [synthpop](https://cran.r-project.org/web/packages/synthpop/index.html) - R package for producing synthetic versions of microdata containing confidential information so that they are safe to be released to users for exploratory analysis.
* [Synthea](https://synthetichealth.github.io/synthea/) - An open-source, synthetic patient generator that models the medical history of synthetic patients.
* [Presidio Evaluator - Data Generator](
https://github.com/microsoft/presidio-research/tree/master/presidio_evaluator/data_generator) - This data generator takes a text file with templates (e.g. my name is x]) and creates a list of InputSamples which contain fake PII entities instead of placeholders.
* [Mimesis](https://github.com/lk-geimfari/mimesis) - Mimesis is a high-performance fake data generator for Python, which provides data for a variety of purposes in a variety of languages. 
* [plaitpy](https://github.com/plaitpy/plaitpy) - plait.py is a program for generating fake data from composable yaml templates.
* [Bogus](https://github.com/bchavez/Bogus) - Bogus is a simple fake data generator for .NET languages like C#, F# and VB.NET.
* Gretel AI:
    * [Gretel Synthetics](https://github.com/gretelai/gretel-synthetics) - Synthetic data generators for structured and unstructured text, featuring differentially private learning.
    * [GDPR Helpers](https://github.com/gretelai/gdpr-helpers) - Generative models to automatically anonymize data to meet GDPR & CCPA standards.
    * [Anonymize Tabular Data to Meet GDPR Privacy Requirements](https://gretel.ai/blog/anonymize-tabular-data-to-meet-gdpr-privacy-requirements) - A blog post covering how to use Gretel's GDPR Helpers.

### Differential Privacy and Federated Learning
---
* [A Friendly, Non-Technical Introduction to Differential Privacy](https://desfontain.es/privacy/friendly-intro-to-differential-privacy.html) - Blog post that provides simple explanations for the core concepts behind differential privacy.
* [A List of Real-World Uses of Differential Privacy](https://desfontain.es/privacy/real-world-differential-privacy.html) - Blog post that compiles a list of real-world deployments of differential privacy, with their privacy parameters.
* [Differential Privacy at the U.S. Census Bureau](https://youtu.be/pT19VwBAqKA) - Video on how differential privacy is being implemented in the U.S. Census.
* [Privacy-Preserving AI](https://www.youtube.com/watch?v=4zrU54VIK6k) - Video on Privacy Preserving AI (Andrew Trask) | MIT Deep Learning Series
* [PySyft](https://github.com/OpenMined/PySyft) - PySyft is a Python library for secure and private Deep Learning.
* [CrypTen](https://github.com/facebookresearch/CrypTen) - CrypTen is a framework for Privacy Preserving Machine Learning built on PyTorch.
* [Opacus](https://github.com/pytorch/opacus) - A library that enables training PyTorch models with differential privacy.
* [Uber SQL Differential Privacy](https://github.com/uber/sql-differential-privacy) - This repository contains a query analysis and rewriting framework to enforce differential privacy for general-purpose SQL queries. (deprecated)
* [Google Differential Privacy Library](https://github.com/google/differential-privacy) - This repository contains libraries to generate ε- and (ε, δ)-differentially private statistics over datasets.
* [PyDP](https://github.com/OpenMined/PyDP) - Python wrapper for Google's Differential Privacy project. The library provides a set of ε-differentially private algorithms, which can be used to produce aggregate statistics over numeric data sets containing private or sensitive information.
* [IBM's Differential Privacy Library](https://github.com/IBM/differential-privacy-library) - Diffprivlib is a general-purpose library for experimenting with, investigating and developing applications in, differential privacy.
* [Microsoft's SmartNoise](https://opendifferentialprivacy.github.io) - This toolkit uses state-of-the-art differential privacy techniques to inject noise into data, to prevent disclosure of sensitive information and manage exposure risk. 
* [NIST Differential Privacy Blog Series](https://www.nist.gov/itl/applied-cybersecurity/privacy-engineering/collaboration-space/focus-areas/de-id/dp-blog) - This series is designed to help business process owners and privacy program personnel understand basic concepts about differential privacy and applicable use cases and to help privacy engineers and IT professionals implement the tools.
* [RAPPOR](https://github.com/google/rappor) - Randomized Aggregatable Privacy-Preserving Ordinal Response (RAPPOR) is a technology for crowdsourcing statistics from end-user client software, anonymously, with strong privacy guarantees.
* [FedML](https://fedml.ai) - FedML - The federated learning and distributed training library enabling machine learning anywhere at any scale. It's backed by [FedML, Inc](https://FedML.ai). Supporting large-scale geo-distributed training, cross-device federated learning on smartphones/IoTs, cross-silo federated learning on data silos, and research simulation. Best Paper Award at NeurIPS 2020.
* [FedJAX](https://github.com/google/fedjax) - Google's JAX-based open source library for federated learning simulations that emphasizes ease-of-use in research.
* [diffpriv: Easy Differential Privacy](https://cran.r-project.org/package=diffpriv) - R package that is an implementation of major general-purpose mechanisms for privatizing statistics, models, and machine learners, within the framework of differential privacy of Dwork et al. (2006).
* [sdcMicro: Statistical Disclosure Control Methods for Anonymization of Microdata and Risk Estimation](https://cran.r-project.org/package=sdcMicro) -  R package that can be used for the generation of anonymized (micro)data, i.e. for the creation of public- and scientific-use files. 
* [PPRL: Privacy Preserving Record Linkage](https://rdrr.io/cran/PPRL/) - R package that is a toolbox for deterministic, probabilistic and privacy-preserving record linkage techniques.
* [PipelineDP](https://pipelinedp.io/) - Write fast, flexible pipelines that use modern techniques to aggregate user data in a privacy-preserving manner.
* [Compute Private Statistics with PipelineDP](https://codelabs.developers.google.com/codelabs/compute-private-statistics-with-pipelinedp#0) - This Google Developer Codelab walks through how to produce private statistics with differentially private aggregations using the PipelineDP Python framework.
* [Practical Differential Privacy w/ Apache Beam](https://dev.to/bamnet/practical-differential-privacy-w-apache-beam-4bki) - Blog post showing how to use Privacy on Beam from Google's differential privacy library.
* [Computing Private Statistics with Privacy on Beam](https://codelabs.developers.google.com/codelabs/privacy-on-beam#0) - This Google Developer Codelab walks through the use of Privacy on Beam to perform differentially private analysis in Go.
* [Tumult Analytics](https://www.tmlt.dev/) - Tumult Analytics is a Python library for computing aggregate queries on tabular data using differential privacy.
* [FLUTE](https://github.com/microsoft/msrflute) - Created by Microsoft Research, Federated Learning Utilities and Tools for Experimentation (FLUTE) is a framework for running large-scale offline federated learning simulations.
* [Flower](https://flower.dev/) - Originated from a research project at the University of Oxford, [Flower (flwr)](https://github.com/adap/flower) is a framework for building federated learning systems with a goal to make federated learning accessible to everyone.
* TensorFlow
    * [TensorFlow Privacy](https://github.com/tensorflow/privacy) - Python library that includes implementations of TensorFlow optimizers for training machine learning models with differential privacy.
    * [TensorFlow Federated](https://www.tensorflow.org/federated) - TensorFlow Federated (TFF) is an open-source framework for machine learning and other computations on decentralized data.
    * [TensorFlow Encrypted](https://github.com/tf-encrypted/tf-encrypted) - TF Encrypted is a framework for encrypted machine learning in TensorFlow.
    * [CrypTFlow](https://github.com/mpc-msri/EzPC) - CrypTFlow is a system for end-to-end secure inference of deep neural networks written in TensorFlow.
* Four-Episode Podcast on Differential Privacy by [This Week in Machine Learning and AI](https://twimlai.com)
    * [Differential Privacy Theory & Practice with Aaron Roth](https://twimlai.com/twiml-talk-132-differential-privacy-theory-practice-with-aaron-roth/)
    * [Differential Privacy at Bluecore with Zahi Karam](https://twimlai.com/twiml-talk-133-differential-privacy-at-bluecore-with-zahi-karam/)
    * [Scalable Differential Privacy for Deep Learning with Nicolas Papernot](https://twimlai.com/twiml-talk-134-scalable-differential-privacy-for-deep-learning-with-nicolas-papernot/)
    * [Epsilon Software for Private Machine Learning with Chang Lu](https://twimlai.com/twiml-talk-135-epsilon-software-for-private-machine-learning-with-chang-liu/)
* Episode of This Week in Machine Learning and AI Podcast:
    * [Privacy-Preserving Decentralized Data Science with Andrew Trask](https://twimlai.com/twiml-talk-241-privacy-preserving-decentralized-data-science/)
* Four-Article Series on Differential Privacy by Singapore's Data Privacy Protection Capability Centre (DPPCC):
    * [Sharing Data with Differential Privacy: A Primer](https://medium.com/dsaid-govtech/protecting-your-data-privacy-with-differential-privacy-an-introduction-abee1d7fcb63)
    * [Practitioners’ Guide to Accessing Emerging Differential Privacy Tools](https://medium.com/dsaid-govtech/practitioners-guide-to-accessing-emerging-differential-privacy-tools-861acddb2a44#c4c0)
    * [Evaluating Differential Privacy Tools’ Performance](https://medium.com/dsaid-govtech/evaluating-differential-privacy-tools-performance-dc75e8efb03e#0829)
    * [Getting Started with Scalable Differential Privacy Tools on the Cloud](https://medium.com/dsaid-govtech/getting-started-with-scalable-differential-privacy-tools-on-the-cloud-53ed65322584)

### Designing for Trust with Users
---
* [Data Permissions Catalogue](https://catalogue.projectsbyif.com) - Catalogue created by the data consultancy IF to help teams make decisions about how, when, and why to collect and use data about people.
* [Privacy Patterns](https://privacypatterns.org/patterns/) - UC Berkeley collection of design patterns attempting to standardize language for privacy-preserving technologies, document common solutions to privacy problems, and help designers identify and address privacy concerns. 
* [How to Protect Your Users with the Privacy by Design Framework](https://www.smashingmagazine.com/2017/07/privacy-by-design-framework/) - Developers can help to defend their users’ personal privacy by adopting the Privacy by Design (PbD) framework.
* [The UX Guide to Getting Consent](https://iapp.org/media/pdf/resource_center/UX_FINAL.pdf) - Short guide by the International Association of Privacy Professionals (IAPP) about obtaining consent under the EU's GDPR.
* [Creepiness-Convenience Tradeoff](https://www.nngroup.com/articles/creepiness/) - As people consider whether to use the new "creepy" technologies, they do a type of cost-benefit analysis weighing the loss of privacy against the benefits they will receive in return.
* [Building a Privacy Policy Users Actually Want to Read](https://www.artificiallawyer.com/2018/05/02/privacy-by-design-building-a-privacy-policy-people-actually-want-to-read/) - Creation of a user-friendly privacy notice through privacy journeying and using a layered notice approach.
* [Contract Design Pattern Library](https://contract-design.iaccm.com/library) - Library of guidelines, explanations, and examples to inspire and support you in exploring user-friendly approaches to contract simplification and visualization.
* Privacy UX Series in Smashing Magazine:
    * [Part 1: Common Concerns and Privacy in Web Forms](https://www.smashingmagazine.com/2019/04/privacy-concerns-ux-web-forms/)
    * [Part 2: Better Cookie Consent Experiences](https://www.smashingmagazine.com/2019/04/privacy-ux-better-cookie-consent-experiences/)
    * [Part 3: Better Notifications UX and Permissions Requests](https://www.smashingmagazine.com/2019/04/privacy-better-notifications-ux-permission-requests/)
    * [Part 4: Privacy-Aware Design Framework](https://www.smashingmagazine.com/2019/04/privacy-ux-aware-design-framework/)
* [Lean Privacy Review](http://www.leanprivacyreview.com/#) - Carnegie Mellon University researchers developed a fast, easy method to catch privacy issues early in a system’s development process by gathering feedback from users.

### Deceptive Design Patterns
---
* [Deceptive Design Patterns](https://www.deceptive.design/) - Deceptive design patterns (also known as "dark patterns") are tricks used in websites and apps that make you do things that you didn't mean to, like buying or signing up for something.
* [The Dark Side of UX Design](https://darkpatterns.uxp2.com) - Practitioner-identified examples of stakeholder values superseding user values.
* [Dark Patterns Tipline](https://darkpatternstipline.org/sightings/) - Gallery of deceptive patterns identified and submitted by individuals.
* [10 Examples of Manipulative Consent Requests](https://wideangle.co/blog/dark-patterns-examples-of-manipulative-consent-requests) - Blog post that illustrates ten examples of manipulative consent patterns in cookie banners.

### Tagging Personally Identifiable Information
___
* [Managing Tags in AWS Resource Groups](https://docs.aws.amazon.com/ARG/latest/userguide/tagging-resources.html) - Tags are words or phrases that act as metadata that you can use to identify and organize your AWS resources. A resource can have up to 50 user-applied tags.
* [Categorizing Your AWS S3 Storage Using Tags](https://docs.aws.amazon.com/AmazonS3/latest/userguide/object-tagging.html) - In addition to data classification, tagging offers benefits such as fine-grained access control of permissions and object lifecycle management.
* [Quickstart for Tagging Tables in Google Cloud](https://cloud.google.com/data-catalog/docs/quickstart-tagging) - Tutorial shows how to create a BigQuery dataset, copy data to a new table in your dataset, create a tag template, and attach the tag to your table.
* [Using Policy Tags in Google Cloud's BigQuery](https://cloud.google.com/bigquery/docs/best-practices-policy-tags) - Use policy tags to define access to your data, for example, when you use BigQuery column-level security.
* [Adding a Tag-Based PII Policy in Cloudera](https://docs.cloudera.com/runtime/7.0.2/security-ranger-authorization/topics/security-ranger-tag-policy-add-pii.html) - How to add a PII tag-based policy. In this example, the author creates a tag-based policy for objects tagged "PII" in Atlas.
* [BigQuery PII Classifier](https://github.com/GoogleCloudPlatform/bq-pii-classifier) - Google Cloud BigQuery PII Classifier is a solution to automate the process of discovering and tagging PII data across BigQuery tables and applying column-level access controls to restrict specific PII data types to certain users/groups.

### Regulatory and Framework Resources
---
* [Global Comprehensive Privacy Law Mapping Chart](https://iapp.org/resources/article/global-comprehensive-privacy-law-mapping-chart/) - The IAPP's Westin Research Center has created this chart mapping several comprehensive data protection laws.
* [US State Privacy Legislation Tracker](https://iapp.org/resources/article/us-state-privacy-legislation-tracker/) - The IAPP Westin Research Center actively tracks the proposed and enacted comprehensive privacy bills from across the United States.
* [Privacy in M&A Transactions: The Playbook](https://iapp.org/resources/article/privacy-in-ma-transactions-playbook/) - The playbook is directed to mergers and acquisitions (M&A) and privacy teams to help identify potential privacy-related issues.
* [European Data Protection Supervisor Website Evidence Collector](https://github.com/EU-EDPS/website-evidence-collector) - The Website Evidence Collector tool automates the collection of evidence of personal data processing, such as cookies, or requests to third parties.
* [webXray](https://webxray.org/) - webXray is a command line tool for analyzing webpage traffic and content, extracting legal policies, and identifying the companies which collect user data.
* [GDPR Developer Guide](https://github.com/LINCnil/GDPR-Developer-Guide) - In order to assist web and application developers in making their work GDPR-compliant, France's Data Protection Agency, the CNIL, has drawn up a guide of best practices.
* [Data Protection/Privacy Mapping Project](https://github.com/microsoft/data-protection-mapping-project) - Microsoft's Data Protection/Privacy Mapping Project facilitates consistent global comprehension and implementation of data protection with an open source mapping between ISO/IEC 27701 and global data protection and/or privacy laws and regulations.
* [European Data Protection Board Guidelines 4/2019 on Article 25, Data Protection by Design and by Default](https://edpb.europa.eu/sites/default/files/files/file1/edpb_guidelines_201904_dataprotection_by_design_and_by_default_v2.0_en.pdf) - This document gives general guidance on the obligation of Data Protection by Design and by Default set forth in Article 25 in the GDPR.
* [A Guide to Privacy by Design](https://www.aepd.es/sites/default/files/2019-12/guia-privacivdad-desde-diseno_en.pdf) - This document by Spain's Data Protection Agency, AEPD, provides guidance on implementation of Privacy by Design into systems and applications.
* [Guidance on Anonymisation and Pseudonymisation](https://www.dataprotection.ie/sites/default/files/uploads/2022-04/Anonymisation%20and%20Pseudonymisation%20-%20latest%20April%202022.pdf) - This document from the Irish Data Protection Commission (DPC) offers guidance on implementation of anonymization and pseudonuymization.
* [Emerging Privacy Enhancing Technologies: Current Regulatory and Policy Approaches](https://www.oecd-ilibrary.org/science-and-technology/emerging-privacy-enhancing-technologies_bf121be4-en) - The Organisation for Economic Co-operation and Development (OECD)'s report reviews recent technological advancements and evaluates the effectiveness of different types of privacy enhancing technologies (PETs), as well as the challenges and opportunities they present.
* [UN Guide on Privacy-Enhancing Technologies for Official Statistics](https://unstats.un.org/bigdata/task-teams/privacy/guide/) - This United Nations (UN) document presents methodologies and approaches to mitigating privacy risks when using sensitive or confidential data.
* [An Introduction to Privacy Engineering and Risk Management in Federal Systems (NIST IR 8062)](https://nvlpubs.nist.gov/nistpubs/ir/2017/NIST.IR.8062.pdf) - National Institute of Standards and Technology (NIST) Internal Report 8062 provides an introduction to the concepts of privacy engineering and risk management for US federal systems.
* [De-Identifying Government Datasets: Techniques and Governance (NIST SP 800-188)](https://csrc.nist.gov/pubs/sp/800/188/final) - NIST Special Publication 800-188 describes the use of deidentification while still allowing for the production of meaningful statistical analysis for US federal agencies.
* [Guidelines for Evaluating Differential Privacy Guarantees (NIST SP 800-226)](https://csrc.nist.gov/pubs/sp/800/226/ipd) - NIST Special Publication 800-226 is intended to help US federal agencies and practitioners of all backgrounds better understand how to evaluate promises made (and not made) when deploying differential privacy.

### Conferences
---
* [USENIX Conference on Privacy Engineering Practice and Respect (PEPR)](https://www.usenix.org/conference/pepr23)
    * [PEPR 2023 Conference](https://www.usenix.org/conference/pepr23) | [Videos](https://www.youtube.com/playlist?list=PLbRoZ5Rrl5le5MLOePeumxpQfUg2Gyfui)
    * [PEPR 2022 Conference](https://www.usenix.org/conference/pepr22/conference-program) | [Videos](https://www.youtube.com/playlist?list=PLbRoZ5Rrl5lfUtLXo1bRFILHssRK-5ETT)
    * [PEPR 2021 Conference](https://fpf.org/fpf-event/pepr-2021-conference-on-privacy-engineering-practice-and-respect-2/) | [Videos](https://www.youtube.com/watch?v=lenVTvDMWxM&list=PL_cjZ5iVWe7n0sU5g0o8zTZSMLAvfl4nL)
    * [PEPR 2020 Conference](https://www.usenix.org/conference/pepr20/conference-program) | [Videos](https://www.youtube.com/playlist?list=PLbRoZ5Rrl5lcie8IH64gqw6L9C7qXqu8x)
    * [PEPR 2019 Conference](https://www.usenix.org/conference/pepr19/conference-program) (slides only)
* [USENIX Enigma Conference](https://www.usenix.org/enigma)
* [Symposium on Usable Privacy and Security (SOUPS)](https://www.usenix.org/conference/soups2023)
* [International Workshop on Privacy Engineering](https://iwpe.info/index.html)

### Career
___
* [What Does a Privacy Engineer Do, Anyway?](https://desfontain.es/privacy/privacy-engineer.html)
* [What to Expect in a Privacy Interview](https://theprivacypractitioner.com/what-to-expect-in-a-privacy-interview/)
* [Ethyca's Privacy Engineering Job Board](https://ethyca.com/privacy-engineering-jobs-board)

### Miscellaneous
___
* [The World of Geolocation Data (FPF Infographic)](https://fpf.org/wp-content/uploads/2020/05/FPF_Geolocation_Infographic_May_2020.pdf)
* [Data and the Connected Car (FPF Infographic)](https://fpf.org/wp-content/uploads/2017/06/2017_0627-FPF-Connected-Car-Infographic-Version-1.0.pdf)
* [Microphones and the Internet of Things (FPF Infographic)](https://fpf.org/wp-content/uploads/2017/08/Microphones-Infographic-Final.pdf)
* [GDPR – A Practical Guide For Developers](https://techblog.bozho.net/gdpr-practical-guide-developers/)
* [W3C Self-Review Questionnaire: Security and Privacy](https://www.w3.org/TR/security-privacy-questionnaire/)
* [Privacy is an Afterthought in the Software Lifecycle. That Needs to Change](https://stackoverflow.blog/2021/07/19/privacy-is-an-afterthought-in-the-software-lifecycle-that-needs-to-change/)
* [How Uber is Approaching Data Privacy Architecture](https://thecustomer.net/uber-data-privacy-architecture/)
* [Microsoft - Code with Engineering Playbook: Privacy Fundamentals](https://microsoft.github.io/code-with-engineering-playbook/privacy/)
* [Private AI - PETs Decision Tree](https://www.private-ai.com/wp-content/uploads/2021/10/PETs-Decision-Tree.pdf)
* [IAPP Privacy Engineering Section](https://iapp.org/connect/communities/sections/privacy-engineering/)
* [VISCHER's Website and App Tracking Legal Checklist](https://www.rosenthal.ch/downloads/VISCHER-Tracking-Checklist.pdf)
* [VISCHER's Marketing Communications Legal Checklist](https://www.rosenthal.ch/downloads/VISCHER-Marcom-Checklist.pdf)

### Other Awesome Privacy Curations
---
* [awesome-data-privacy](https://github.com/yilmaztolga/awesome-data-privacy)
* [awesome-federated-computing](https://github.com/tushar-semwal/awesome-federated-computing)
* [awesome-gdpr](https://github.com/bakke92/awesome-gdpr)
* [awesome-artificial-intelligence-guidelines](https://github.com/EthicalML/awesome-artificial-intelligence-guidelines)
* [awesome-ml-privacy-attacks](https://github.com/stratosphereips/awesome-ml-privacy-attacks/)
* [awesome-privacy-on-blockchains](https://github.com/Mikerah/awesome-privacy-on-blockchains)
* [awesome-zero-knowledge-proofs](https://github.com/matter-labs/awesome-zero-knowledge-proofs)
* [awesome-privacy-papers](https://github.com/brighter-ai/awesome-privacy-papers)
* [awesome-ml-sp-papers](https://github.com/gnipping/Awesome-ML-SP-Papers)
* [awesome-synethetic-data](https://github.com/gretelai/awesome-synthetic-data)
* [awesome-privacy](https://github.com/Lissy93/awesome-privacy)

### Related GitHub Topics
___
* [GDPR](https://github.com/topics/gdpr)
* [CCPA](https://github.com/topics/ccpa)
* [Right-to-be-Forgotten](https://github.com/topics/right-to-be-forgotten)
* [Privacy-Tech](https://github.com/topics/privacy-tech)
* [Privacy-Enhancing-Technologies](https://github.com/topics/privacy-enhancing-technologies)
* [Differential-Privacy](https://github.com/topics/differential-privacy)
* [Federated-Learning](https://github.com/topics/federated-learning)
* [Privacy](https://github.com/topics/privacy)
