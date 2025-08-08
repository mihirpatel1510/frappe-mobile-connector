### Frappe Mobile Connector

**frappe\\_mobile\\_connector** is a Frappe app that acts as a backend bridge for Flutter apps using the `frappe_mobile` package. It provides ready-to-use APIs, authentication, and secure access to DocTypes for seamless mobile integration.

### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch develop
bench install-app frappe_mobile_connector
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/frappe_mobile_connector
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

mit
