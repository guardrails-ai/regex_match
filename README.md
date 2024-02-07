## Details

| Developed by | Guardrails AI |
| --- | --- |
| Date of development | Feb 15, 2024 |
| Validator type | Rule-following |
| Blog |  |
| License | Apache 2 |
| Input/Output | Output |

## Description

This validator ensures that any given output follows a pre-specified regex rule.

## Example Usage Guide

### Installation

```bash
$ gudardrails hub install regex_match
```

### Initialization

```python
regex_validator = RegexMatch(
	regex="pattern",
	match_type="str"
	on_fail="noop"
)

# Create Guard with Validator
guard = Guard.from_string(
    validators=[regex_validator, ...],
)
```

### Invocation

```python
guard("LLM output")
```

## Intended use

- Primary intended uses: No restrictions on use cases
- Out-of-scope use cases:

## Expected deployment metrics

|  | CPU | GPU |
| --- | --- | --- |
| Latency |  | - |
| Memory |  | - |
| Cost |  | - |
| Expected quality |  | - |

## Resources required

- Dependencies: na
- Foundation model access keys: na
- Compute: na

## Validator Performance

### Evaluation Dataset

### Model Performance Measures

| Accuracy |  |
| --- | --- |
| F1 Score |  |

### Decision thresholds
