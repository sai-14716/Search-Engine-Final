# Solr Benchmark Summary Report

Generated on: 2025-04-28 14:40:30

Target Solr URL: 
Benchmark timestamp: 2025-04-28T09:02:15Z

## Performance Summary

| Concurrent Users | Response Time (s) | Transaction Rate | Availability (%) | Success | Failures |
|------------------|------------------|-----------------|-----------------|---------|----------|
| 2 | 0.0 | 766.78 | 100.0 | 6970 | 0 |
| 3 | 0.0 | 1728.3 | 100.0 | 17162 | 0 |
| 5 | 0.0 | 1816.82 | 100.0 | 18041 | 0 |
| 7 | 0.0 | 3716.52 | 100.0 | 36905 | 0 |
| 11 | 0.0 | 4708.04 | 100.0 | 46845 | 0 |
| 13 | 0.0 | 4186.33 | 100.0 | 41654 | 0 |
| 17 | 0.0 | 3997.49 | 100.0 | 39735 | 0 |
| 19 | 0.01 | 3701.11 | 100.0 | 36790 | 0 |
| 23 | 0.01 | 3764.69 | 100.0 | 37421 | 0 |
| 29 | 0.01 | 3797.79 | 100.0 | 37750 | 0 |
| 31 | 0.01 | 3759.66 | 100.0 | 37371 | 0 |
| 37 | 0.01 | 3782.39 | 100.0 | 37597 | 0 |
| 41 | 0.01 | 3874.55 | 100.0 | 38513 | 0 |
| 43 | 0.01 | 3812.48 | 100.0 | 37896 | 0 |
| 47 | 0.01 | 3822.23 | 100.0 | 37993 | 0 |
| 53 | 0.01 | 3752.36 | 100.0 | 37336 | 0 |
| 59 | 0.02 | 3521.15 | 100.0 | 34966 | 0 |
| 61 | 0.02 | 3243.42 | 100.0 | 32273 | 0 |
| 67 | 0.02 | 3255.75 | 100.0 | 32297 | 0 |
| 71 | 0.02 | 3256.04 | 100.0 | 32365 | 0 |
| 73 | 0.02 | 3245.67 | 100.0 | 32262 | 0 |
| 79 | 0.02 | 3263.85 | 100.0 | 32411 | 0 |
| 83 | 0.03 | 3254.97 | 100.0 | 32387 | 0 |
| 89 | 0.02 | 3514.82 | 100.0 | 34867 | 0 |
| 97 | 0.03 | 3751.36 | 100.0 | 37251 | 0 |

## Key Findings

- Best response time: 0.0s at 2 concurrent users
- Maximum transaction rate: 4708.04 tps at 11 concurrent users
- **Scaling concern**: Response time increased significantly at higher concurrency levels

## Visualization Files

- response_time_{timestamp}.png - Response time vs concurrent users
- transaction_rate_{timestamp}.png - Transaction rate vs concurrent users
- availability_{timestamp}.png - Availability vs concurrent users
- success_failure_{timestamp}.png - Successful vs failed transactions
- combined_metrics_{timestamp}.png - Combined performance metrics
