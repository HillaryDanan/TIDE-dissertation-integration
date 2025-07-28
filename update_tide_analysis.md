# Updates for TIDE-analysis

Add to your existing analyze.py:

```python
# Dissertation validation markers
DISSERTATION_VALIDATED = {
    "features": 14,
    "factors": ["Internal", "External", "Concrete"],
    "participants": {"Study1": 687, "Study2": 20, "Study3": 120, "Study5": 41},
    "key_region": "dmPFC",
    "p_value": 0.005
}
```

Your systematic testing already implements Study 2 methodology!