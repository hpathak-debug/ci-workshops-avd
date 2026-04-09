# ANTA Report

**Table of Contents:**

- [ANTA Report](#anta-report)
  - [Test Results Summary](#test-results-summary)
    - [Summary Totals](#summary-totals)
    - [Summary Totals Device Under Test](#summary-totals-device-under-test)
    - [Summary Totals Per Category](#summary-totals-per-category)
  - [Test Results](#test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Success | Total Tests Skipped | Total Tests Failure | Total Tests Error |
| ----------- | ------------------- | ------------------- | ------------------- | ------------------|
| 13 | 0 | 0 | 13 | 0 |

### Summary Totals Device Under Test

| Device Under Test | Total Tests | Tests Success | Tests Skipped | Tests Failure | Tests Error | Categories Skipped | Categories Failed |
| ------------------| ----------- | ------------- | ------------- | ------------- | ----------- | -------------------| ------------------|
| s1-brdr1 | 2 | 0 | 0 | 2 | 0 | - | System |
| s1-brdr2 | 2 | 0 | 0 | 2 | 0 | - | System |
| s1-leaf1 | 1 | 0 | 0 | 1 | 0 | - | System |
| s1-leaf2 | 1 | 0 | 0 | 1 | 0 | - | System |
| s1-leaf3 | 2 | 0 | 0 | 2 | 0 | - | System |
| s1-leaf4 | 1 | 0 | 0 | 1 | 0 | - | System |
| s1-spine1 | 2 | 0 | 0 | 2 | 0 | - | System |
| s1-spine2 | 2 | 0 | 0 | 2 | 0 | - | System |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Success | Tests Skipped | Tests Failure | Tests Error |
| ------------- | ----------- | ------------- | ------------- | ------------- | ----------- |
| System | 13 | 0 | 0 | 13 | 0 |

## Test Results

| Device Under Test | Categories | Test | Description | Custom Field | Result | Messages |
| ----------------- | ---------- | ---- | ----------- | ------------ | ------ | -------- |
| s1-brdr1 | System | VerifyCPUUtilization | Verifies whether the CPU utilization is below 75%. | - | failure | Device has reported a high CPU utilization -  Expected: < 75% Actual: 75.4% |
| s1-brdr1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 82.90% |
| s1-brdr2 | System | VerifyCPUUtilization | Verifies whether the CPU utilization is below 75%. | - | failure | Device has reported a high CPU utilization -  Expected: < 75% Actual: 90.5% |
| s1-brdr2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 82.84% |
| s1-leaf1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 82.44% |
| s1-leaf2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 82.39% |
| s1-leaf3 | System | VerifyCPUUtilization | Verifies whether the CPU utilization is below 75%. | - | failure | Device has reported a high CPU utilization -  Expected: < 75% Actual: 84.3% |
| s1-leaf3 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 82.99% |
| s1-leaf4 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 82.64% |
| s1-spine1 | System | VerifyCPUUtilization | Verifies whether the CPU utilization is below 75%. | - | failure | Device has reported a high CPU utilization -  Expected: < 75% Actual: 87.2% |
| s1-spine1 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 83.00% |
| s1-spine2 | System | VerifyCPUUtilization | Verifies whether the CPU utilization is below 75%. | - | failure | Device has reported a high CPU utilization -  Expected: < 75% Actual: 89.9% |
| s1-spine2 | System | VerifyMemoryUtilization | Verifies whether the memory utilization is below 75%. | - | failure | Device has reported a high memory usage - Expected: < 75% Actual: 82.84% |
