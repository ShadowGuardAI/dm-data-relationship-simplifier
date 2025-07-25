# dm-data-relationship-simplifier
Simplifies complex relationships between datasets by identifying and removing redundant or non-essential relationships. This reduces the attack surface and complexity of data masking operations, making it easier to manage data anonymization. - Focused on Tools designed to generate or mask sensitive data with realistic-looking but meaningless values

## Install
`git clone https://github.com/ShadowGuardAI/dm-data-relationship-simplifier`

## Usage
`./dm-data-relationship-simplifier [params]`

## Parameters
- `-h`: Show help message and exit
- `-i`: Path to the input JSON file containing data relationships.
- `-o`: Path to the output JSON file to save the simplified relationships.
- `--remove-redundant`: Remove redundant relationships.
- `--remove-non-essential`: Remove non-essential relationships.
- `--anonymize-data`: Anonymize data in the datasets.
- `--anonymization-level`: No description provided
- `--seed`: No description provided

## License
Copyright (c) ShadowGuardAI
