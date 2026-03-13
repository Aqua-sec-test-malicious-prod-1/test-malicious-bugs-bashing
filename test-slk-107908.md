# SLK-107908 Production Verification Test

Testing that the AQUA_REGION fix is deployed to production.

## Expected Results:
1. **test-custom-cspm-with-region**: Should PASS (uses AQUA_REGION=singapore)
2. **test-custom-cspm-no-region**: Should FAIL with error: 'custom CSPM URL detected but cannot determine trivy-server URL'
