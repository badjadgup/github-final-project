# Simple Interest Calculator

A Bash calculator that computes simple interest from the principal amount, annual interest rate, and time period in years.

## Inputs

- Principal: the initial amount of money.
- Rate: the annual interest rate as a percentage (enter `5` for 5%).
- Time: the time period in years.

## Formula

```text
Simple interest = principal * rate * time / 100
```

## Run

With Bash and the standard `expr` utility installed:

```bash
bash simple-interest.sh
```

Enter whole numbers when prompted. For principal `1000`, rate `5`, and time `2`, the result is `100`.

This educational script uses integer arithmetic; fractional results are truncated.

## Contributing

All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## License and attribution

Licensed under the [Apache License 2.0](LICENSE). The calculator script originates from the IBM Introduction to Git and GitHub lab by Upkar Lidder.
