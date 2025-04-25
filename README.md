# AI-Powered Clinical Documentation Assistant

This repository contains notebooks and documentation for an AI-powered clinical documentation assistant. This work was done as part of the 5-day Kaggle Generative AI Intensive Course capstone project.

## Overview

This project demonstrates how generative AI can be used to automate medical documentation workflows, reducing the burden on healthcare professionals and improving data quality.

## Notebooks

*   [soap-qr](docs/soap-qr.md): This notebook demonstrates an AI-powered workflow designed to alleviate the burden of medical documentation. It automatically processes audio recordings of physician-patient encounters to extract structured medical information, pre-fill relevant clinical forms, generate standardized clinic notes (SOAP notes), and output data in FHIR format for seamless integration with EHRs. The solution employs a multi-step process orchestrated using LangGraph, including questionnaire discovery (RAG), audio processing & form filling, and SOAP note generation.
*   [soap-fhir](docs/soap-fhir.md): This notebook demonstrates an AI-powered workflow that leverages generative AI to transform physician-patient audio conversations into structured electronic health data that adheres to the FHIR standard. The process consists of three main steps: Audio Understanding, Intent Extraction, and FHIR Resource Generation. The AI agent recognizes relevant medical history and generates FHIR resources, automatically incorporating standardized codes from SNOMED CT and LOINC for interoperability and semantic precision.

## Contributors

This project was made possible by the following contributors:

<table>
  <tr>
    <td  align="center" valign="top" width="25%" style="text-align: center;">
      <img src="https://via.placeholder.com/100" alt="Hari Vennelakanti" style="border-radius: 50%;">
      <div>
        <strong>Hari Vennelakanti </strong>
        <br>
        <span>PT, DPT</span>
      </div>
      <div>
        <a href="https://www.linkedin.com/in/harivennelakanti/">LinkedIn</a>
      </div>
    </td>
    <td  align="center" valign="top" width="25%" style="text-align: center;">
      <img src="#" alt="Likhitha Satulur" style="border-radius: 50%;">
      <div>
        <strong>Likhitha Satulur</strong>
        <br>
        <span>B.Tech</span>
      </div>
      <div>
        <a href="https://www.linkedin.com/in/likhitha-satuluri-72a283224/">LinkedIn</a>
      </div>
    </td>
    <td  align="center" valign="top" width="25%" style="text-align: center;">
      <img src="https://via.placeholder.com/100" alt="Lakshay Roopchandani " style="border-radius: 50%;">
      <div>
        <strong>Lakshay Roopchandani</strong>
        <br>
        <span>B. Tech</span>
      </div>
      <div>
        <a href="https://www.linkedin.com/in/lakshay-roopchandani-990a63240/">LinkedIn</a>
      </div>
    </td>
    <td  align="center" valign="top" width="25%" style="text-align: center;">
      <img src="https://avatars.githubusercontent.com/u/28119869?v=4" alt="Peter Muriuki" style="border-radius: 50%;">
      <div>
        <strong>Peter Muriuki</strong>
        <br>
        <span>Software Engineer</span>
      </div>
      <div>
        <a href="https://github.com/peterMuriuki/">GitHub</a> | <a href="https://www.linkedin.com/in/peter-muriuki-094b8411a/">LinkedIn</a>
      </div>
    </td>
  </tr>
</table>
