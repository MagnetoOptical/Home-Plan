# Home Plan - Household Resource Planning

This is a proof-of-concept of a household resource planning suite.  It should
be available on-prem in as a cloud service.  The idea, generally, is to apply
the concepts and capabilities available in Enterprise Resource Planning software
to the household.

This project will attempt to integrate:
* Finances
  - Income
  - Bill reminders and payments
  - Allowances
  - Asset management
  - Liability mitigation
  - Reporting
  - Maintenance
* School
* Human Resources
  - Work/School Commute times
  - Human resource availability
  - Vacation reminders
* Demand planning
  - Groceries, etc

And other services as a need is found a good fit in the software is determined.
The above list is very incomplete.

## Getting Started

If this is an on-prem installation, the best way to install it is through
your OS's supported software distribution channels.  A stand alone install is
possible, but it is up to you to figure that out.  This software is unsupported.

### Prerequisites (broadly)

* Linux (3.18+)
* GNU coreutils 8.2+
* Python 3.6+
* Nginx
* Curiosity
* Patience

## Contributing

Contributions can be initiated via gists and issues within GitHub.

## Versioning

We use a form of date versioning.  Versions are in the format Y.p-s, where:
Y = the full year
p = the development period (we have 5, every 73 days)
s = status (e.g. alpha1, beta2, rc1, stable)
For example:
AndromedaDB 2020.2-concept1 would be a valid version within this repo.

## License

This project is licensed under the AGPLv3 License - see the [LICENSE](LICENSE) file for details.  This license has been selected intentionally and with great thought,
and is non-negotiable.
