# AI-Powered Clinical Documentation Assistant

This repository contains notebooks and documentation for an AI-powered clinical documentation assistant. This work was done as part of the 5-day Kaggle Generative AI Intensive Course capstone project.

## Overview

This project demonstrates how generative AI can be used to automate medical documentation workflows, reducing the burden on healthcare professionals and improving data quality.

## Notebooks

*   [sooap-qr](docs/sooap-qr.md): This notebook demonstrates an AI-powered workflow designed to alleviate the burden of medical documentation. It automatically processes audio recordings of physician-patient encounters to extract structured medical information, pre-fill relevant clinical forms, generate standardized clinical notes (SOAP notes), and output data in FHIR format for seamless integration with EHRs. The solution employs a multi-step process orchestrated using LangGraph, including questionnaire discovery (RAG), audio processing & form filling, SOAP note generation, and FHIR resource creation.
*   [soap-fhir](docs/soap-fhir.md): This notebook demonstrates an AI-powered workflow that leverages generative AI to transform physician-patient audio conversations into structured electronic health data that adheres to the FHIR standard. The process consists of three main steps: Audio Understanding, Intent Extraction, and FHIR Resource Generation. The AI agent recognizes relevant medical history and generates FHIR resources, automatically incorporating standardized codes from SNOMED CT and LOINC for interoperability and semantic precision.

## Contributors

This project was made possible by the following contributors:

<div style="display: flex; flex-direction: row;">
  <div style="margin-right: 20px; text-align: center;">
    <img src="https://via.placeholder.com/100" alt="Hari" style="border-radius: 50%;">
    <div>
      <strong>Hari Vennelakanti</strong>
      <br>
      <span>PT, DPT</span>
    </div>
    <!-- <div style="margin-top: 5px;">
      <a href="#">LinkedIn</a> | <a href="#">Twitter</a>
    </div> -->
  </div>
  <div style="margin-right: 20px; text-align: center;">
    <img src="https://via.placeholder.com/100" alt="Likhitha" style="border-radius: 50%;">
    <div>
      <strong>Likhitha Satulur</strong>
      <br>
      <span>B. Tech</span>
    </div>
    <!-- <div style="margin-top: 5px;">
      <a href="#">LinkedIn</a> | <a href="#">Twitter</a>
    </div> -->
  </div>
  <div style="margin-right: 20px; text-align: center;">
    <img src="https://via.placeholder.com/100" alt="Lakshay" style="border-radius: 50%;">
    <div>
      <strong>Lakshay Roopchandani</strong>
      <br>
      <span>B. Tech</span>
    </div>
    <!-- <div style="margin-top: 5px;">
      <a href="#">GitHub</a> | <a href="#">LinkedIn</a> | <a href="#">Twitter</a>
    </div> -->
  </div>
  <div style="margin-right: 20px; text-align: center;">
    <img src="https://via.placeholder.com/100" alt="Peter" style="border-radius: 50%;">
    <div>
      <strong>Peter Muriuki</strong>
      <br>
      <span>Software Engineer</span>
    </div>
    <!-- <div style="margin-top: 5px;">
      <a href="https://github.com/peterMuriuki/">GitHub</a> | <a href="https://www.linkedin.com/in/peter-muriuki-094b8411a/">LinkedIn</a> | <a href="https://x.com/p_netm">Twitter</a>
    </div> -->
  </div>
</div>
