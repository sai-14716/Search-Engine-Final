# Solr Benchmark Summary Report

Generated on: 2025-05-03 13:02:13

Target Solr URL: http://localhost:8983/solr/searchcloud_ensemble
Benchmark timestamp: 2025-05-03T07:30:07Z

## Performance Summary

| Concurrent Users | Response Time (s) | Transaction Rate | Availability (%) | Success | Failures |
|------------------|------------------|-----------------|-----------------|---------|----------|
| 2 | 0.01 | 170.5 | 100.0 | 0 | 0 |
| 3 | 0.01 | 276.69 | 99.88 | 0 | 1 |
| 5 | 0.02 | 312.97 | 99.78 | 0 | 2 |
| 7 | 0.02 | 332.65 | 99.9 | 0 | 1 |
| 11 | 0.02 | 24.07 | 100.0 | 0 | 0 |
| 13 | 0.0 | 244.9 | 100.0 | 0 | 0 |
| 17 | 0.03 | 17.29 | 100.0 | 0 | 0 |
| 19 | 0.04 | 18.71 | 100.0 | 0 | 0 |
| 23 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 29 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 31 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 37 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 41 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 43 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 47 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 53 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 59 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 61 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 67 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 71 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 73 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 79 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 83 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 89 | 0.0 | 0.0 | 0.0 | 0 | 0 |
| 97 | 0.0 | 0.0 | 0.0 | 0 | 0 |

## Key Findings

- Best response time: 0.0s at 13 concurrent users
- Maximum transaction rate: 332.65 tps at 7 concurrent users
- **Warning**: Availability dropped below 99.5% in some test scenarios

## Visualization Files

- response_time_{timestamp}.png - Response time vs concurrent users
- transaction_rate_{timestamp}.png - Transaction rate vs concurrent users
- availability_{timestamp}.png - Availability vs concurrent users
- success_failure_{timestamp}.png - Successful vs failed transactions
- combined_metrics_{timestamp}.png - Combined performance metrics
