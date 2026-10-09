# Computational Theory Assessment

This is my repository for the Computational Theory assessment (Winter 26/27). The problems are based on the [Secure Hash Standard](https://doi.org/10.6028/NIST.FIPS.180-4), and the aim is to build SHA-256 from scratch in Python, one problem at a time.

## What's in here

- `problems.ipynb` - the notebook with all the problems and my explanations
- `AGENTS.md` - the AI instructions file the assessment asks for
- `.gitignore` - files git should ignore
- `README.md` - this file
- `requirements.txt` - the python packages needed to run the notebook



## Running the notebook

You'll need Python 3 and pip. I'm working in a GitHub Codespace.

```bash
git clone https://github.com/DavidDonoghue1601/computationaltheory.git
cd computationaltheory
pip install -r requirements.txt
jupyter notebook problems.ipynb
```

## Problems

I'm tracking progress in the [Issues tab](https://github.com/DavidDonoghue1601/computationaltheory/issues), with one issue for each problem.

0. GitHub Issues
1. Representing SHA-256 data
2. SHA-256 bitwise operations
3. Generating the SHA-256 constants
4. Padding and parsing messages
5. The SHA-256 compression function
6. Complete SHA-256

## Use of AI

I've used Claude (Anthropic) to help me understand the assessment brief and to format my GitHub Issues. I'm following the rules in `AGENTS.md`, so I write the solutions myself and check anything Claude suggests against the standard and the documentation.

## References

References are linked in the notebook next to where I use them.