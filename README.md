# Assemblyline 4 - Automated malware analysis framework

![Assemblyline Logo](img/al_dark_svg.svg)

[![Discord](https://img.shields.io/badge/chat-on%20discord-7289da.svg?sanitize=true)](https://discord.gg/GUAy9wErNu)
[![Discord](https://img.shields.io/discord/908084610158714900)](https://discord.gg/GUAy9wErNu)
[![License](https://img.shields.io/github/license/CyberCentreCanada/assemblyline)](./LICENCE.md)

AssemblyLine 4 is an open source malware analysis framework. It leverages Kubernetes and Docker to adapt to many use cases; from a small appliance for supporting manual malware analysis and security teams to large-scale enterprise security operations scanning millions of files a day and providing triage capabilities.

AssemblyLine can be easily integrated in your environment using it’s powerful rest API and web interfaces. The platform comes with dozens of services to provide deep file analysis and enable integration with other security platforms such as anti-virus, malware-detonation sandboxes and threat knowledge bases. Best of all, with a little bit of Python code you can extend it yourself by creating new analysis and integration services.

## What is the purpose of this repo?

This is a repository containing development resources for the Assembyline project.

> "A scalable file triage and malware analysis system integrating the cyber security community's best tools!"

Documentation: <https://cybercentrecanada.github.io/assemblyline4_docs/>

-----

> "Plateforme de tri de fichier et d'analyse de « malware » qui intègre les meilleurs outils de la communauté en cyber sécurité!"

Documentation: <https://cybercentrecanada.github.io/assemblyline4_docs/fr/>

## Core Components

| Repository Name | Main Branch | Dev Branch | PyPI Release |

|---|---|---|---|

| [Assemblyline Base](https://github.com/CybercentreCanada/assemblyline-base/) | [![Main Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-base?repoName=CybercentreCanada%2Fassemblyline-base&branchName=master)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=17&repoName=CybercentreCanada%2Fassemblyline-base&branchName=master) | [![Dev Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-base?repoName=CybercentreCanada%2Fassemblyline-base&branchName=dev)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=17&repoName=CybercentreCanada%2Fassemblyline-base&branchName=dev) | [![Latest Stable Release](https://img.shields.io/pypi/v/assemblyline.svg)](https://pypi.org/project/assemblyline/#history) |
| [Assemblyline Core](https://github.com/CybercentreCanada/assemblyline-core/) | [![Main Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-core?repoName=CybercentreCanada%2Fassemblyline-core&branchName=master)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=20&repoName=CybercentreCanada%2Fassemblyline-core&branchName=master) | [![Dev Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-core?repoName=CybercentreCanada%2Fassemblyline-base&branchName=dev)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=20&repoName=CybercentreCanada%2Fassemblyline-core&branchName=dev) | [![Latest Stable Release](https://img.shields.io/pypi/v/assemblyline-core.svg)](https://pypi.org/project/assemblyline-core/#history) |
| [Assemblyline Service Client](https://github.com/CybercentreCanada/assemblyline-service-client/) | [![Main Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-service-client?branchName=master)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=181&repoName=CybercentreCanada%2Fassemblyline-service-client&branchName=master) | [![Dev Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-service-client?branchName=dev)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=181&repoName=CybercentreCanada%2Fassemblyline-service-client&branchName=dev) | [![Latest Stable Release](https://img.shields.io/pypi/v/assemblyline-service-client.svg)](https://pypi.org/project/assemblyline-service-client/#history) |
| [Assemblyline Service Server](https://github.com/CybercentreCanada/assemblyline-service-server) | [![Main Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-service-server?repoName=CybercentreCanada%2Fassemblyline-service-server&branchName=master)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=26&repoName=CybercentreCanada%2Fassemblyline-service-server&branchName=master) | [![Dev Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-service-server?repoName=CybercentreCanada%2Fassemblyline-service-server&branchName=dev)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=26&repoName=CybercentreCanada%2Fassemblyline-service-server&branchName=dev) | [![Latest Stable Release](https://img.shields.io/pypi/v/assemblyline-service-server.svg)](https://pypi.org/project/assemblyline-service-server/#history) |
| [Assemblyline UI](https://github.com/CybercentreCanada/assemblyline-ui) | [![Main Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-ui?repoName=CybercentreCanada%2Fassemblyline-ui&branchName=master)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=24&repoName=CybercentreCanada%2Fassemblyline-ui&branchName=master) | [![Dev Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-ui?repoName=CybercentreCanada%2Fassemblyline-ui&branchName=dev)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=24&repoName=CybercentreCanada%2Fassemblyline-ui&branchName=dev) | [![Latest Stable Release](https://img.shields.io/pypi/v/assemblyline-ui.svg)](https://pypi.org/project/assemblyline-ui/#history) |
| [Assemblyline UI Frontend](https://github.com/CybercentreCanada/assemblyline-ui-frontend) | [![Main Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-ui-frontend?branchName=master)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=189&repoName=CybercentreCanada%2Fassemblyline-ui-frontend&branchName=master) | [![Dev Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-ui-frontend?branchName=dev)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=189&repoName=CybercentreCanada%2Fassemblyline-ui-frontend&branchName=dev) | N/A |
| [Assemblyline Service Base](https://github.com/CybercentreCanada/assemblyline-v4-service) | [![Main Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-v4-service?repoName=CybercentreCanada%2Fassemblyline-v4-service&branchName=master)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=95&repoName=CybercentreCanada%2Fassemblyline-v4-service&branchName=master) | [![Dev Branch Test Status](https://dev.azure.com/CybercentreCanada/Assemblyline/_apis/build/status%2Ftest%20-%20core%20components%2Fassemblyline-v4-service?repoName=CybercentreCanada%2Fassemblyline-v4-service&branchName=dev)](https://dev.azure.com/CybercentreCanada/Assemblyline/_build/latest?definitionId=95&repoName=CybercentreCanada%2Fassemblyline-v4-service&branchName=dev) | [![Latest Stable Release](https://img.shields.io/pypi/v/assemblyline-v4-service.svg)](https://pypi.org/project/assemblyline-v4-service/#history) |

## Auxiliary Components

| Repository Name | PyPI Release |

|---|---|
| [Assemblyline Client](https://github.com/CybercentreCanada/assemblyline_client) | [![Latest Stable Release](https://img.shields.io/pypi/v/assemblyline-client.svg)](https://pypi.org/project/assemblyline-client/#history) |
| [Assemblyline Service Utilities](https://github.com/CybercentreCanada/assemblyline-service-utilities) | [![Latest Stable Release](https://img.shields.io/pypi/v/assemblyline-service-utilities.svg)](https://pypi.org/project/assemblyline-service-utilities/#history) |
| [Assemblyline Incident Manager](https://github.com/CybercentreCanada/assemblyline-incident-manager/) | [![Latest Stable Release](https://img.shields.io/pypi/v/assemblyline-incident-manager.svg)](https://pypi.org/project/assemblyline-incident-manager/#history) |
| [Multidecoder](https://github.com/CybercentreCanada/Multidecoder) | [![Latest Stable Release](https://img.shields.io/pypi/v/multidecoder.svg)](https://pypi.org/project/multidecoder/#history) |
