Microsoft Sentinel Notebooks
Jupyter notebooks are an interactive development and data analysis environment hosted in a browser. The open API supported by Microsoft Sentinel allows you to use Jupyter notebooks to query, transform, analyze and visualize Microsoft Sentinel data. This makes notebooks a powerful addition to Microsoft Sentinel and is especially well-suited to ad-hoc investigations, hunting or customized workflows.

Network Timeline

More information on getting started with Microsoft Sentinel and Azure Notebooks

This repository contains notebooks contributed by Microsoft and the community to assist hunting and investigation tasks in Microsoft Sentinel.

Finding a notebook in the repo
Top Level notebooks
There are several notebooks at the top level of the repo - eventually only a few introductory notebooks will reside here. For the moment, notebooks at the top level include all of those used in the Microsoft Sentinel portal.

If you have never used notebooks in Microsoft Sentinel before you should run through the Getting Started Notebook

Other Folders
scenario-notebooks
This contains notebooks designed for use by you in Microsoft Sentinel. Some of these are intended to illustrate specific techniques or investigation approaches

tutorials-and-examples
example-notebooks Examples of techniques or features
feature-tutorials MSTICPy feature tutorial notebooks
how-tos Articles and notebooks illustrating specific techniques
other-language-kernels Notebooks using alternative kernels
training-notebooks Notebooks used in training webinars
deprecated-notebooks Older, deprecated notebooks
There are also support folders - source and utils

Full list of notebooks

Notebook	Folder
A Getting Started Guide For Azure Sentinel ML Notebooks.ipynb	
A Getting Started Guide For PowerShell AML Notebooks.ipynb	
A Tour of Cybersec notebook features.ipynb	
ConfiguringNotebookEnvironment.ipynb	
Credential Scan on Azure Blob Storage.ipynb	
Credential Scan on Azure Data Explorer.ipynb	
Credential Scan on Azure Log Analytics.ipynb	
Entity Explorer - Account.ipynb	
Entity Explorer - Domain and URL.ipynb	
Entity Explorer - IP Address.ipynb	
Entity Explorer - Linux Host.ipynb	
Entity Explorer - Windows Host.ipynb	
Guided Hunting - Anomalous Office365 Exchange Sessions.ipynb	
Guided Hunting - Azure Resource Explorer.ipynb	
Guided Hunting - Base64-Encoded Linux Commands.ipynb	
Guided Hunting - Covid-19 Themed Threats.ipynb	
Guided Investigation - Anomaly Lookup.ipynb	
Guided Investigation - Incident Triage.ipynb	
Guided Investigation - Process-Alerts.ipynb	
Guided Investigation - Solarwinds Post Compromise Activity.ipynb	
Guided Triage - Alerts.ipynb	
Hands-on 1. Data Discovery using Azure REST API.ipynb	
Hands-on 2. Surfing Data using Azure SDK.ipynb	
Machine Learning in Notebooks Examples.ipynb	
AffectedKeyCredentials-CVE-2021-42306.ipynb	scenario-notebooks
AutomatedNotebooks-IncidentTriage.ipynb	scenario-notebooks
AutomatedNotebooks-Manager.ipynb	scenario-notebooks
Guided Hunting - Detect potential network beaconing using Apache Spark via Azure Synapse.ipynb	scenario-notebooks
Guided Hunting - Office365-Exploring.ipynb	scenario-notebooks
Guided Investigation - MDE Webshell Alerts.ipynb	scenario-notebooks
Guided Investigation - WAF data.ipynb	scenario-notebooks
Guided Analysis - User Security Metadata.ipynb	scenario-notebooks/UserSecurityMetadata
papermill_test_runner.ipynb	src/Test
Example - Azure Storage VT Hash Lookup.ipynb	tutorials-and-examples/example-notebooks
Example - Guided Hunting - Office365-Exploring.ipynb	tutorials-and-examples/example-notebooks
Example - Guided Investigation - Process-Alerts.ipynb	tutorials-and-examples/example-notebooks
M365 Defender - APIs ep3.ipynb	tutorials-and-examples/example-notebooks
M365 Defender - hunting.ipynb	tutorials-and-examples/example-notebooks
MDE APIs Demo Notebook.ipynb	tutorials-and-examples/example-notebooks
MSTICPy Tour.ipynb	tutorials-and-examples/example-notebooks
Senserva Connections Graph Notebook.ipynb	tutorials-and-examples/example-notebooks
SigmaRuleImporter.ipynb	tutorials-and-examples/example-notebooks
VirusTotal File Behavior Explorer - MS and Sysmon detonation.ipynb	tutorials-and-examples/example-notebooks
msticpy demo.ipynb	tutorials-and-examples/example-notebooks
AnomalousSequence.ipynb	tutorials-and-examples/feature-tutorials
AzureBlobStorage.ipynb	tutorials-and-examples/feature-tutorials
AzureSentinelAPIs.ipynb	tutorials-and-examples/feature-tutorials
Base64Unpack.ipynb	tutorials-and-examples/feature-tutorials
DataObfuscation.ipynb	tutorials-and-examples/feature-tutorials
DataUploader.ipynb	tutorials-and-examples/feature-tutorials
DataViewer.ipynb	tutorials-and-examples/feature-tutorials
Data_Queries.ipynb	tutorials-and-examples/feature-tutorials
EventClustering.ipynb	tutorials-and-examples/feature-tutorials
EventTimeline.ipynb	tutorials-and-examples/feature-tutorials
FoliumMap.ipynb	tutorials-and-examples/feature-tutorials
GeoIPLookups.ipynb	tutorials-and-examples/feature-tutorials
IoCExtract.ipynb	tutorials-and-examples/feature-tutorials
MDATPQuery.ipynb	tutorials-and-examples/feature-tutorials
MPSettingsEditor.ipynb	tutorials-and-examples/feature-tutorials
MordorData.ipynb	tutorials-and-examples/feature-tutorials
NotebookWidgets.ipynb	tutorials-and-examples/feature-tutorials
PivotFunctions-Introduction.ipynb	tutorials-and-examples/feature-tutorials
PivotFunctions.ipynb	tutorials-and-examples/feature-tutorials
ProcessTree.ipynb	tutorials-and-examples/feature-tutorials
ResourceGraphDriver.ipynb	tutorials-and-examples/feature-tutorials
Splunk-DataConnector.ipynb	tutorials-and-examples/feature-tutorials
SqlToKql.ipynb	tutorials-and-examples/feature-tutorials
Sumologic-DataConnector.ipynb	tutorials-and-examples/feature-tutorials
TIProviders.ipynb	tutorials-and-examples/feature-tutorials
TimeSeriesAnomaliesVisualization.ipynb	tutorials-and-examples/feature-tutorials
VTLookupV3.ipynb	tutorials-and-examples/feature-tutorials
VirusTotalLookup.ipynb	tutorials-and-examples/feature-tutorials
Adding Hunting Bookmarks.ipynb	tutorials-and-examples/how-tos
Adding Secrets to Azure Key Vault.ipynb	tutorials-and-examples/how-tos
Automation Gallery - Credential Scan on Azure Blob Storage.ipynb	tutorials-and-examples/how-tos
Automation Setup - Configure Azure Machine Learning Compute Cluster and Managed Identity.ipynb	tutorials-and-examples/how-tos
Automation Setup - Configure Azure Machine Learning Pipelines.ipynb	tutorials-and-examples/how-tos
Azure Sentinel Query Creator.ipynb	tutorials-and-examples/how-tos
Configurate Azure ML and Azure Synapse Analytics.ipynb	tutorials-and-examples/how-tos
Notebook Template.ipynb	tutorials-and-examples/how-tos
Provisioning DSVM.ipynb	tutorials-and-examples/how-tos
TroubleShootingNotebooks.ipynb	tutorials-and-examples/how-tos
A Getting Started Guide For CSharp AML Notebooks.ipynb	tutorials-and-examples/other-language-kernels
A Python Crash Course - Part 1 - Fundamentals.ipynb	tutorials-and-examples/training-notebooks
Training - MSTICPy Training 1221.ipynb	tutorials-and-examples/training-notebooks
Training - MSTICPy Training 3 - 2022-01-13.ipynb	tutorials-and-examples/training-notebooks
generate-nb-toc.ipynb	utils
A Getting Started Guide For Azure Sentinel Notebooks.ipynb	tutorials-and-examples/deprecated-notebooks
Example - Step-by-Step Linux-Windows-Office Investigation.ipynb	tutorials-and-examples/deprecated-notebooks
Get Started.ipynb	tutorials-and-examples/deprecated-notebooks
Viewing the notebooks
You can view any of the notebooks directly on GitHub just by clicking on them.

For higher fidelity rendering we'd recommend Jupyter nbviewer.

Open a notebook here and copy the URL (or copy the a link from the table above)
Go to https://nbviewer.jupyter.org/ and paste the URL into the location text box.
Hit the Go! button
Find help and troubleshooting articles in the Wiki
Sentinel Notebooks Wiki

More Information
Getting Started notebook.
Configuring notebook environment notebook.
Run a demonstration notebook in Binder
Read more about the use of Jupyter notebooks in Microsoft Sentinel on the Microsoft Sentinel Technical Community blog.
Read more about the Azure ML Notebooks Service.
Read more about MSTICPy - the CyberSecurity Python library that powers most of the notebooks
Feedback
For questions or feedback, please file an issue or contact asinotebooks@service.microsoft.com

Contributing
This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the Microsoft Open Source Code of Conduct. For more information see the Code of Conduct FAQ or contact opencode@microsoft.com with any additional questions or comments.
