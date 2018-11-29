# IBM Cognos Business Intelligence :smiley: fa18-523-81

| Harika Putti
| haputti@iu.edu
| Indiana University
| hid: fa18-523-81
| github: [:cloud:](https://github.com/cloudmesh-community/fa18-523-81/blob/master/paper/paper.md)

## Introduction

IBM Cognos [@fa18-523-81-cognosintro] is a business intelligence suite that can help users to provide powerful insights to drive better business decisions. Business intelligence is an all-encompassing term that includes tools, infrastructure and applications that help in analyzing, evaluating and visualizing data. With help of BI software, one can envision relationships within the data that help organizations make knowledgeable business decisions. Using business intelligence tools, organizations can integrate their data and create reports, dashboards, metrics and scorecards to gain insights. 
Business intelligence suites by definition need to incorporate techniques like data processing, data modelling, querying, visualizing among other things. IBMs Cognos Business Intelligence is one among the many suites that has an extensive set of options ranging from exploration, modelling and querying to data visualization. The Cognos BI suite has multiple components including report studio, event studio, metric studio, framework manager, workspace among many others.

---

Keywords: hid fa18-523-81, business intelligence, BI, cognos, analytics, reports, queries

---

## History

Cognos was a consulting and performance management company that was founded in 1969. It was acquired by IBM into its Infosphere product line in 2008 when companies like SAP, Oracle, Microsoft were fighting to become leaders in the BI market. In 2005, the company had released its Cognos 8 suite which introduced tools such as the Report studio, Query studio, Analysis studio and many others. After the acquisition by IBM, IBM Cognos 10 was released that had the capability to incorporate SPSS predictive analytics, historical and real-time analysis, better, faster and more flexible way of generating reports and dashboards. The next version of Cognos was the IBM Cognos Business Intelligence 10.2.2 that had the ability to integrate Microsoft Office with Cognos [@fa18-523-81-history].
The latest edition of Cognos is the IBM Cognos Analytics 11.0 which is a state-of-the-art Analytics tool. This version of Cognos is a very powerful BI tool with ability to connect to Hadoop, an in-built AI assistant and smart data-discovery

## Architecture

Cognos has a 3-tiered architecture. Each tier separated by network firewalls. 

* Tier 1: Web servers and Gateways

* Tier 2: Applications

* Tier 3: Data and Content store

+@fig: CognosBIArchitecture shows the architecture for the Cognos Business intelligence suite. 

![Architecture for cognos [@fa18-523-81-architecture]](images/crn_arch_struc-1.jpg){#fig:CognosBIArchitecture}

## Components

The various components of Cognos Business intelligence are [@fa-18-523-81-cognos8]– 

|Component| Application| 
| ------------- |:-------------:|
| IBM Cognos Connection | Publishing, managing, and viewing content |
| IBM Cognos Insight | Managed workspaces |
| IBM Cognos Workspace | Interactive workspaces |
| IBM Cognos Workspace Advanced | Ad hoc querying and exploring data |
| IBM Cognos Report Studio | Creating reports |
| IBM Cognos Event Studio | Event management and alerting |
| IBM Cognos Metric Studio | Metrics and Scorecards|
| IBM Cognos for Microsoft Office | Cognos in Microsoft Office |
| IBM Cognos Query Studio | Ad hoc querying |
| IBM Cognos Analysis Studio |Exploring Data|
|IBM Framework Manager | Creating metadata models|
|IBM Cognos Transformer | Multi-dimensional data modeling| [@fa18-523-81-cognos10.2doc]

### IBM Cognos Connection

IBM Cognos Connection is a web-based user interface that is used to access various cognos services such as Query Studio, Report Studio, Analysis Studio, Metric Studio etc. Using IBM Cognos connection one can access all the available reports and perform different operations such as create, run, schedule and access the reports. The admin has the ability to set up access permissions, manage data sources and provide individual and group memberships with in the interface. Users can personalize the connection as per their choice.

### IBM Cognos Insight

Insight [@fa18-523-81-insight] is an individual entity with-in the Cognos family that incorporates a range of analytic abilities like ad-hoc querying and analyzing what-if scenarios. It is very user-friendly since one can perform data analysis, do off-hand querying, create dashboards with utmost ease. It’s almost like tableau where you can drag and drop the data files and insight automatically creates crosstabs and charts using something called smart metadata. Insight has the ability to create natural hierarchies between the data it receives to create OLAP cubes which makes it easier for the users to slice and dice the data as they prefer. Insight also comes with write back functionality that provides the ability to create models using prior data or new data that the user provides. 

### IBM Cognos Workspace

Workspace [@fa18-523-81-workspace] is a web-based tool that can be used to create interactive dashboards known as workspaces using existing or new reports with in the IBM Cognos connection. This allows the users to create insightful visuals that can convey as much meaning from the information at a time as possible. It contains widgets and filters that users could use while creating the dashboards. 

### IBM Cognos Workspace Advanced

Business Intelligence is an area with a lot of options to choose from i.e. which studio, which data package etc. Most of the Cognos BI users are perplexed about the time wasted in navigating between different studios. Cognos Workspace Advanced was designed to bridge the gap between various studios. With the advent of Cognos Workspace Advanced, the redundancy of having three different studios is clearly noticed [@fa18-523-81-workspaceadvanced]. The advanced Cognos was designed in a way that it can amalgamate all the services on one platform where the users can use multiple services at the same time. It provides a single interface for querying and analysis and is very flexible in terms of presentation options.

### IBM Cognos Report Studio

Report Studio [@fa18-523-81-reportstudio] is a report composing instrument that proficient report creators and designers use to fabricate complex, various page reports against numerous databases. It’s the most used component in the IBM Cognos Business intelligence suite. With Report Studio, you can make any reports that your association requires. Report Studio offers a variety of services such as creating and formatting report using grouping, headers, footers, and other formatting options. Report Studio also enables focusing reports by filtering data and using prompts. The report studio also aids in adding value to the reports by performing different manipulations. It enhances the visual appeal of the reports though advanced formatting and exceptional data highlighting. 

### IBM Cognos Event Studio

The Cognos Event Studio [@fa18-523-81-eventstudio] is predominantly used to keep track of the events in an organization to ensure that the decision-makers are notified of the upcoming events to make timely and effective decisions. An event is generally a situation that can create some impact on the business. When there are significant changes in the data, an event is detected to be taking place and agents are placed within this framework to detect the occurrence of events in organizational data. The sole purpose of an event studio is to notify the decision-makers about an event which is otherwise inconspicuous. When these agents are activated by the changes in data, the activation gets passed as notification to for further action such as sending an e-mail, adding information to the portal and running reports.

### IBM Cognos Metric Studio

This service of IBM cognos helps to manage the performance of an organization by measuring the metrics at all the levels of the organization through creation of scorecards. The sole purpose behind creating score cards is to put performance indicators alongside the organization’s main performance measures. These scorecards then can be used to link to reports containing related information. These score cards can be customized using metric studio which helps in monitoring and analyzing metrics and projects throughout the organization [@fa18-523-81-metricstudio]. Metric Studio helps in converting an organization’s strategy into relevant and measurable goals. That align every employee’s actions with a strategic plan. An environment rich of scorecards is analogous to a quick review document that shows how successful is an organization and where the flaws are to work and improve upon. It helps the decision-makers at all levels to react and plan based on the reports generated from the comparison of performance against targets while also simultaneously making a note of the current status of the business. 

### IBM Cognos Query Studio

This service of IBM Cognos is preliminarily for people with little or no training, one can quickly design, create and save reports that are not covered by the organizational reports. One can use query studio for ad-hoc reporting and can view data in hierarchies, create crosstab views and filter, sort, suppress and group the data easily without having to create any complex reports. One cannot define the properties of a data object like we can do in report studio, one cannot create multi-query or multipage reports either. Report studio offers a lot more visualizations and templates. Query studio is generally used by customers to quickly create reports that can be used as a reference to create higher level reports by the developer [@fa18-523-81-querystudio]. 

### IBM Cognos Analysis Studio

Analytics studio [@fa18-523-81-analysisstudio] can be used to intelligently manipulate the data to understand the relationships within it. It provides support for filtering, calculating, sorting and analyzing the data. It can be used to comprehend patterns and inconsistencies, look at information, for example, points of interest to outlines, or real outcomes to planned outcomes evaluate execution by concentrating on the best or most exceedingly bad outcomes. It helps in multidimensional examination and investigation of expansive data sources. IBM Cognos Analytics is intended to enable one to report and dissect an organization's performance rapidly and effortlessly.

## Cognos Analytics

Cognos Analytics [@fa18-523-81-cognos11doc] is a futuristic tool which can provide analytic solutions with ease. It’s very user-friendly and has the ability to perform machine learning, pattern detection and smart visualization. It also enables sharing visualizations and reports on platforms like slack.

### Big data and Cognos

With the increase in the amount of information that an organization can gather, the need for an integration between big-data and business intelligence tools has also increased. IBM having recognized that, created the possibility to connect to Hadoop databases. 

## Conclusions


In conclusion, Cognos is IBM’s business intelligence tool that can be used for a thorough scrutiny of performance of a business. This product is intended to empower business clients without programming prowess to extract corporate information, analyze and create reports using that information. Cognos empowers even a layman to create professional reports which are otherwise created only using years of expertise. Cognos provides exceptionally good implementation and deployment options that support scalability to grow along with the organization. It integrates well with other applications such as its seamless ability to integrate email and pdf functionality thereby allowing one to schedule reporting data deliveries. Cognos facilitates connection to multiple databases which can be stored within cognos’ content store.
