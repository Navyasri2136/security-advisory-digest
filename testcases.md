# Test Cases â€“ Security Advisory Digest

## Test Case 1: Single Advisory Processing
### Input
One security advisory document.

### Steps
1. Upload advisory.
2. Run digest generation.

### Expected Result
System generates a concise summary containing:
- Vulnerability details
- Severity level
- Recommended actions

### Status
Pass

---

## Test Case 2: Multiple Advisory Documents
Expected Result: Combined digest generated successfully.

## Test Case 3: High Severity Advisory
Expected Result: Critical risks are highlighted.

## Test Case 4: Empty File Upload
Expected Result: Validation error shown.

## Test Case 5: Unsupported File Format
Expected Result: File rejected.

## Test Case 6: Retrieval Accuracy
Expected Result: Relevant advisory retrieved.

## Test Case 7: Summary Quality
Expected Result: Short, readable summary.

## Test Case 8: User Query Handling
Expected Result: Relevant digest information returned.