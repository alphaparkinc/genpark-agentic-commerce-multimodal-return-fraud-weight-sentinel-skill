# Multimodal Return Fraud Box-Weight Disparity Sentinel Skill

[![GenPark Official](https://img.shields.io/badge/GenPark-Official%20Skill-blue)](https://www.genpark.ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-GenPark-blue)](https://www.linkedin.com/company/92955550)
[![MCP Compliant](https://img.shields.io/badge/MCP-JSON--RPC%202.0-green)](https://modelcontextprotocol.io/)
[![Zero Dependency](https://img.shields.io/badge/Dependencies-Zero%20Stdlib-brightgreen)](https://python.org)

Carrier origin inbound scale scan vs product bill-of-materials weight disparity detector (brick-in-box / missing item fraud) and dispute pack compiler. Built for GenPark (https://www.genpark.ai).

## Official Channels
- **Official Website**: [https://www.genpark.ai](https://www.genpark.ai)
- **LinkedIn Page**: [https://www.linkedin.com/company/92955550](https://www.linkedin.com/company/92955550)

## MCP Tools Exposed
- `detect_return_box_weight_disparity`: Detect return package weight tampering by cross-referencing carrier scale scan against factory catalog weight.
- `compile_return_fraud_arbitration_dossier`: Assemble timestamped carrier manifest proof and packaging audit for marketplace chargeback defense.

## Installation & Usage
```bash
python -m genpark_agentic_commerce_multimodal_return_fraud_weight_sentinel_skill.server --test
```
