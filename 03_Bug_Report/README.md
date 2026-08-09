# 🐞 ElderCare Connect — Bug Reports

## 📌 Overview

This folder contains bug reports identified during the testing and development of **ElderCare Connect**, a MERN-based web application designed to improve communication and information sharing between elderly residents, caregivers/staff, and guardians.

The bug reports document issues related to application functionality, authorization, data synchronization, audio processing, and AI-powered sentiment analysis.

---

## 🧪 Testing Context

**Project:** ElderCare Connect  
**Testing Type:** Manual Software Testing  
**Application:** MERN Web Application  
**Testing Environment:** Local Development Environment  
**Primary Tools:** Postman, MongoDB Compass, Browser DevTools, Git/GitHub  
**Tester:** Aziz Subhani

---

## 📋 Bug Report Contents

Each bug report contains the following information:

- **Bug ID**
- **Module**
- **Bug Title**
- **Severity**
- **Priority**
- **Environment**
- **Preconditions**
- **Steps to Reproduce**
- **Expected Result**
- **Actual Result**
- **Status**
- **Related Test Case ID**
- **Remarks**

---

## 🐞 Identified Defects

| Bug ID | Module | Description | Severity | Priority |
|---|---|---|---|---|
| BUG-001 | Reports | Incorrect report date displayed on Resident/Guardian view | Medium | High |
| BUG-002 | Audio Recording | Recorded audio was not stored successfully | High | High |
| BUG-003 | Audio Recording | Audio submission returned 403 Forbidden for Resident | High | High |
| BUG-004 | Sentiment Analysis | Sentiment analysis request failed during processing | High | High |
| BUG-005 | Speech-to-Text / Sentiment Analysis | OpenAI API returned 429 Quota Exceeded during audio processing | High | High |
| BUG-006 | User Registration / Resident Management | Resident registration did not create the corresponding Resident record | High | High |
| BUG-007 | Admin / Resident Assignment | Resident assignment did not correctly associate Resident with Staff | High | High |

> **Note:** Some defects may have related or overlapping root causes. The reports are maintained separately where they represent different observable failures or testing scenarios.

---

## 🔍 Bug Reporting Approach

Each defect was documented using a structured format to make it easy for developers and QA engineers to:

1. Understand the problem.
2. Reproduce the issue.
3. Compare the expected and actual behavior.
4. Determine the impact and urgency.
5. Track the defect through its lifecycle.
6. Relate the defect back to its corresponding test case.

---

## 📊 Severity Classification

| Severity | Meaning |
|---|---|
| **Critical** | Causes major system failure or prevents core application functionality. |
| **High** | Significantly affects an important feature or workflow. |
| **Medium** | Affects functionality but does not completely prevent the application from being used. |
| **Low** | Minor issue with limited functional impact. |

---

## 📌 Priority Classification

| Priority | Meaning |
|---|---|
| **High** | Should be addressed as soon as possible because it affects an important workflow. |
| **Medium** | Should be addressed after higher-priority defects. |
| **Low** | Can be addressed when resources are available. |

---

## 🔄 Defect Lifecycle

A typical defect may move through the following states:

```text
Open
  ↓
In Progress
  ↓
Fixed
  ↓
Retest
  ↓
Closed
