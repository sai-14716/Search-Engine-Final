# Solr Benchmark Summary Report

Generated on: 2025-05-03 12:20:09

Target Solr URL: http://localhost:8983/solr/searchcloud_ensemble
Benchmark timestamp: 2025-05-03T06:45:08Z

## Performance Summary

| Concurrent Users | Response Time (s) | Transaction Rate | Availability (%) | Success | Failures |
|------------------|------------------|-----------------|-----------------|---------|----------|
| 2 | 0.01 | 336.11 | 100.0 | 0 | 0 |
| 3 | 0.0 | 763.52 | 100.0 | 0 | 0 |
| 5 | 0.0 | 372.39 | 100.0 | 0 | 0 |
| 7 | 0.0 | 800.3 | 100.0 | 0 | 0 |
| 11 | 0.0 | 319.58 | 100.0 | 0 | 0 |
| 13 | 0.0 | 395.37 | 99.97 | 0 | 1 |
| 17 | 0.01 | 7.35 | 100.0 | 0 | 0 |
| 19 | 0.01 | 14.1 | 100.0 | 0 | 0 |
| 23 | 0.0 | 672.23 | 100.0 | 0 | 0 |
| 29 | 0.0 | 480.08 | 100.0 | 0 | 0 |
| 31 | 0.03 | 10.16 | 100.0 | 0 | 0 |
| 37 | 0.03 | 14.6 | 100.0 | 0 | 0 |
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

- Best response time: 0.0s at 3 concurrent users
- Maximum transaction rate: 800.3 tps at 7 concurrent users
- **Warning**: Availability dropped below 99.5% in some test scenarios

## Visualization Files

- response_time_{timestamp}.png - Response time vs concurrent users
- transaction_rate_{timestamp}.png - Transaction rate vs concurrent users
- availability_{timestamp}.png - Availability vs concurrent users
- success_failure_{timestamp}.png - Successful vs failed transactions
- combined_metrics_{timestamp}.png - Combined performance metrics
