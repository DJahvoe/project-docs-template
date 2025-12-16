# Repository Structure

This document lists the complete directory and file structure of the repository.

## project-docs-template/

- **README.md**

- **docs/**
  - **00_project/**
    - `00_glossary.md`
    - `01_scope.md`
    - `02_roles_raci.md`
    - **03_meeting_notes/**
      - `2025-12-16_kickoff.md`
    - `99_decision_log.md`

  - **01_requirements/**
    - `README.md`
    - `01_business_requirements.md`
    - `02_user_stories_and_use_cases.md`
    - `03_nonfunctional_requirements.md`
    - `04_data_requirements.md`
    - `05_acceptance_criteria.md`
    - **diagrams/**
      - `system_context.drawio`
      - `as_is_to_be_flow.drawio`

  - **02_basic_design/**
    - `README.md`
    - `01_system_overview.md`
    - `02_architecture.md`
    - `03_data_model_overview.md`
    - `04_api_overview.md`
    - `05_screen_list.md`
    - `06_error_handling_policy.md`
    - **diagrams/**
      - `deployment.drawio`
      - `sequence_overview.drawio`
      - `er_overview.drawio`

  - **03_detailed_design/**
    - `README.md`
    - `01_module_list.md`
    - **02_database/**
      - `01_tables.md`
      - **diagrams/**
        - `er_detail.drawio`
    - **03_api/**
      - `01_endpoints.md`
      - `02_request_response_examples.md`
      - **diagrams/**
        - `sequence_detail.drawio`
    - **04_batch_jobs/**
      - `batch_job_specs.md`
    - **05_screen_specs/**
      - `00_screen_index.md`
      - **screens/**
        - `SCR-001_login.md`
    - **06_report_specs/**
      - `RPT-001_sales_report.md`
    - `07_testability_notes.md`

  - **04_implementation/**
    - `README.md`
    - `01_coding_guidelines.md`
    - `02_branching_strategy.md`
    - `03_pull_request_guidelines.md`
    - `04_definition_of_done.md`

  - **05_unit_testing/**
    - `README.md`
    - `01_unit_test_policy.md`
    - `02_test_case_matrix.md`
    - **cases/**
      - `UT-API-001_create_user.md`

  - **06_integration_testing/**
    - `README.md`
    - `01_integration_test_policy.md`
    - `02_test_scenarios.md`
    - `03_environment_and_test_data.md`
    - **cases/**
      - `IT-001_user_signup_to_purchase.md`

- **assets/**
  - **images/**
  - **exports/**

- `.gitattributes`
- `.gitignore`

- **.github/**
  - `PULL_REQUEST_TEMPLATE.md`
