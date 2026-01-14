# How to Execute Test Cases – Manual Testing Guide

## Purpose
This document provides step-by-step guidance on how to execute manual test cases for the E-Commerce Web Application practice project, following industry-standard QA processes.

## 1. Prerequisites
- Staging/Test environment is accessible  
- Test cases are reviewed and approved  
- Test data (users, products) is available  
- Required browsers and devices are ready  

## 2. Understanding Test Case Structure
Each test case contains:
- TC_ID  
- Module  
- Title  
- Preconditions  
- Steps  
- Expected Result  
- Priority  
- Test Type  

## 3. Test Execution Steps
1. Open the Test Case Excel sheet.  
2. Select the test case to execute.  
3. Verify all preconditions are met.  
4. Execute steps exactly as mentioned.  
5. Observe actual behavior.  
6. Compare actual vs expected result.  
7. Update execution status.

## 4. Test Case Status Definitions
- **Pass** – Actual result matches expected result  
- **Fail** – Actual result does not match expected result  
- **Blocked** – Test cannot be executed due to dependency  
- **Not Executed** – Test not yet run  

## 5. Recording Execution Results
- Update Status column  
- Enter tester name in Executed By  
- Add execution date  
- Mention defect ID or observation in Notes  

## 6. Regression Testing
- Identify critical regression test cases  
- Re-execute after defect fixes  
- Focus on Login, Cart, Checkout, and Order flows  

## 7. Best Practices
- Execute high-priority test cases first  
- Capture screenshots for failures  
- Avoid skipping steps  
- Maintain clear documentation
