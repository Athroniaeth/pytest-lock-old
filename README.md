# pytest-lock
Enhances pytest by allowing you to 'freeze' unit test results. Use the 'lock' fixture to specify tests and input arguments to freeze. Outcomes are saved in a .pytest-lock directory as JSON files. Subsequent pytest runs compare new results with these locked values, issuing warnings for discrepancies. Ideal for costly or deterministic tests
