# Currency Converter

Java console app that fetches real-time exchange rates from the
[OpenExchangeRates API](https://openexchangerates.org) and converts
between multiple currencies interactively.

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![HTTP Client](https://img.shields.io/badge/HttpClient-007396?style=flat&logo=java&logoColor=white)
![JSON](https://img.shields.io/badge/Gson-000000?style=flat&logo=json&logoColor=white)

## How it works

1. Run the application
2. Choose the currencies you want to convert between
3. Enter the amount
4. Get the converted value using live exchange rates

## Getting started

### Prerequisites

- Java 8+
- OpenExchangeRates API key (free tier works) — get one at [openexchangerates.org](https://openexchangerates.org)
- Internet connection

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/Ccirhack/Conversor-de-Moneda---Challenge-ONE--Java---Back-end.git
cd Conversor-de-Moneda---Challenge-ONE--Java---Back-end

# 2. Add your API key in src/main/java/.../OpenExchangeRateApi.java
private static final String API_KEY = "YOUR_API_KEY_HERE";

# 3. Compile and run
javac Main.java
java Main
```

## Supported currencies

| Code | Currency |
|------|----------|
| USD | US Dollar |
| EUR | Euro |
| PEN | Peruvian Sol |
| BRL | Brazilian Real |
| ARS | Argentine Peso |
| COP | Colombian Peso |

## What I learned

- Making HTTP requests with Java HttpClient
- Parsing JSON responses with Gson
- Structuring a console-driven Java application
- Working with external APIs and API keys

## Contributing

Contributions are welcome. Please open an issue first to discuss
any changes, then submit a pull request.

## Contact

Yuan Retamozo · [LinkedIn](https://www.linkedin.com/in/yuan-retamozo/) · yretamozovilca@gmail.com
