# Project Title

Building Threat Group profiles from CTI knowledge bases. 

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Requirements](#requirements)
- [Data Sources](#data-sources)
- [Examples](#examples)
- [Usage](#usage)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview

Indicators of Compromise (IOCs) such as IP addresses, file hashes, and domain names are commonly used
for threat detection and attribution. However, IOCs tend to be short-lived as they are easy to change. As a result,
the cybersecurity community is shifting focus towards more
persistent behavioral profiles such as the Tactics, Techniques,
and Procedures (TTPs) and the software used by a threat
group. However, the distinctiveness and completeness of such
behavioral profiles remain largely unexplored. In this work,
we systematically analyze threat group profiles built from
two open cyber threat intelligence (CTI) knowledge bases:
MITRE ATT&CK and Malpedia. We first investigate what
fraction of threat groups have group-specific behaviors, i.e.,
behaviors used exclusively by a single group. 

## Features

- Group and Software profiles from MITRE ATT&CK and Malpedia
- Extended Group profiles using exploited vulnerabilities

## Installation

1. Clone the repository:
```bash
  git clone https://github.com/sahaaakanksha7/CTITTP.git
   cd CTITTP
```

2. Create and activate a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

## Requirements

Python 3.10.10

## Repository Structure

- `attack_spreadsheets/`: Contains MITRE ATTA&CK spreadsheet for threat groups, softwares and techniques.
- `mitre_malpedia_dataset_analysis/`: Jupyter notebooks for data processing, analysis, and visualization.
- `mitre_attack_group/`: Jupyter notebooks for group and associated techniques analysis.
- `group_profile_analysis/`: Jupyter notebooks for building group profiles. 