# Data and software services - case thermal camera analysis



## Face temperature measurements from crowd thermal camera image

- Shared experience in the audience
- Temperature measurement using thermal camera footage
- Extracting temperature measurements.
  - Converting the data files to temperatures
  - Can we track individual faces in the video?


***

## Data and computing is everywhere

![Examples of data and RSE projects. Data collection platform for smart devices - SCI. Make code easily installable - ELEC. Interactive website visualizing force fields - CHEM. Data processing, spreadsheets to code Publishing microscope control data- SCI. DigiTraffic API scraper - BIZ.](projects.png)

- [Data Agents](https://www.aalto.fi/en/services/data-agents)
- [Aalto Scientific Computing](https://scicomp.aalto.fi/)
- [Aalto Research Software Engineers](https://scicomp.aalto.fi/rse/)

***


## Research Software Engineers

![Researcher - RSE - Software Developer. A researcher is focused on research and may not have software developments skills. A professional software developer is too formal for the chaos of a research project. A research software engineer sits in between, trained in research and software development.](RSE.png)
- The best way to contact us is our [daily Zoom garage](https://scicomp.aalto.fi/help/garage/)

<table style="width:100%">
  <tr>
    <th style="width:50%">Skills</th>
    <th style="width:50%">Broadly, we</th>
  </tr>
  <tr>
    <td style="width:50%">
      <ul>
        <li><b>Programming and software</b></li>
        <li><b>Data</b>, data systems, databases, data pipelines</li>
        <li><b>Scale-up</b>, high-performance computing</li>
        <li><b>Automation</b> and <b>reproducibility</b></li>
        <li><b>Open-source</b> software: packaging, distribution</li>
        <li><b>Data analysis</b>: preprocessing, software support
          <ul><li>Anonymization as a service</li></ul>
        </li>
      </ul>
      … and literally whatever else you may need about software, data, and computing.
    </td>
    <td style="width:50%">
      <ul>
        <li><b>Do it for you</b><. You need some custom technical software/platform.  We do it for you, you get straight to your work.</li>
        <li><b>Do it with you</b><. We co-work with your group, teaching as much as we can.</li>
        <li><b>Make it reusable</b><. Something has already done something, but it doesn't work for others. This is a waste (and prevents citations).</li>
      </ul>
      On average, researchers >5 times speedup (time we spend vs time they save)
    </td>
  </tr>
</table>


***


## Data Agents: domain-aware data support

- **Help** researchers with data handling related questions, including handling personal data
- **Advice and review** of data management plans
- **Support** data-based research
- **Promote and communicate** open science and best practices, such as FAIR data
- **Connect** research groups with existing RDM tools, services and infrastructures
- **Teach** beginner and advanced RDM and Open Science lectures and tutorials [See future training](https://www.aalto.fi/en/services/research-data-management-rdm-and-open-science#1-learn-about-research-data-management)


***


## Reading the file
- Extracting a grid of temperature values from the seq file data.
- https://github.com/rantahar/seq_file

![Example thermal camera image of 5 people sitting facing the same direction](thermal_example.png)


***


## Face tracking

- Simple face location algorithms:
  - Fitting an oval
  - watershead
- Using a mean temperature image as a guide
- Manual labeling and training a machine learning algorithm
- https://github.com/rantahar/thermal_faces

![Curves displaying multiple individual temperatures around 35C.](temp_data_original.png)

***



## Individual temperatures

- Noice, outliers and spurious correlations
  - Inconsistent face detection
  - Moving subjects
  - Room and camera temperature changes
- Control signal from an empty seat

![Curves displaying individual temperature fluctuations.](temp_data_final.png)

***


## The rest is research

**Contacting RSEs:**
 - scicomp.aalto.fi/rse
 - scicomp.aalto.fi/help/garage
 - rse-group@aalto.fi

**Contacting data agents:**
  - Often found locally
  - aalto.fi/en/services/data-agents
  - researchdata@aalto.fi

