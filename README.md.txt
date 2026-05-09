# AttackLab Evidence Package

This repository contains supporting evidence for the thesis:

**IoT AttackLab: An automated hardware-based test environment for reproducible security evaluation of IoT devices**

The material supports the implementation and result sections of the thesis. It includes selected run artefacts, logs, manifests, checksum files, generated figures and summary outputs from the implemented Wi-Fi-based scenarios.

## Contents

- `logs/` contains selected text logs from reconnect, DoS/overload and eavesdropping scenarios.
- `manifests/` contains selected manifest files documenting run configuration and execution context.
- `summaries/` contains selected summary outputs from the executed scenarios.
- `checksums/` contains checksum outputs used for evidence integrity.
- `figures/` contains generated result figures and analysis figures.
- `runs/` may contain run-specific output material when preserved as complete run folders.

## Scenario scope

The evidence package covers the implemented Wi-Fi-based scenarios:

1. Wi-Fi reconnect
2. Wi-Fi DoS/overload
3. Wi-Fi eavesdropping

The material supports the thesis results and is intended for transparency and reproducibility. It should not be interpreted as a complete product-security audit.

## Target scope

The material includes evidence from:

- ESP32-based reference nodes
- iPhone target
- SmartSpa target under authorised test conditions

## Ethical and practical note

The material has been prepared for academic documentation purposes. Sensitive information such as credentials, private network details, unnecessary identifiers and unrelated traffic content should be removed or anonymised before public release.