# Solr Benchmark Summary Report

Generated on: 2025-05-03 11:51:19

Target Solr URL: http://localhost:8983/solr/searchcloud_1
Benchmark timestamp: 2025-05-03T06:16:17Z

## Performance Summary

| Concurrent Users | Response Time (s) | Transaction Rate | Availability (%) | Success | Failures |
|------------------|------------------|-----------------|-----------------|---------|----------|
| 2 | 0.01 | 357.48 | 100.0 | 0 | 0 |
| 3 | 0.0 | 649.05 | 99.98 | 0 | 1 |
| 5 | 0.0 | 2064.62 | 100.0 | 0 | 0 |
| 7 | 0.0 | 2946.29 | 100.0 | 0 | 0 |
| 11 | 0.0 | 2381.63 | 100.0 | 0 | 0 |
| 13 | 0.0 | 147.39 | 100.0 | 0 | 0 |
| 17 | 0.01 | 20.28 | 100.0 | 0 | 0 |
| 19 | 0.0 | 729.42 | 100.0 | 0 | 0 |
| 23 | 0.0 | 1242.05 | 100.0 | 0 | 0 |
| 29 | 0.01 | 142.97 | 100.0 | 0 | 0 |
| 31 | 0.0 | 831.59 | 100.0 | 0 | 0 |
| 37 | 0.0 | 353.62 | 100.0 | 0 | 0 |
| 41 | 0.0 | 338.93 | 100.0 | 0 | 0 |
| 43 | 0.02 | 92.45 | 100.0 | 0 | 0 |
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

- Best response time: 0.0s at 3 concurrent users
- Maximum transaction rate: 2946.29 tps at 7 concurrent users
- **Warning**: Availability dropped below 99.5% in some test scenarios

## Visualization Files

- response_time_{timestamp}.png - Response time vs concurrent users
- transaction_rate_{timestamp}.png - Transaction rate vs concurrent users
- availability_{timestamp}.png - Availability vs concurrent users
- success_failure_{timestamp}.png - Successful vs failed transactions
- combined_metrics_{timestamp}.png - Combined performance metrics
