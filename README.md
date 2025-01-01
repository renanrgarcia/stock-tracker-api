# 🚀 Stock Tracker API
This repository houses the backend API for a robust stock portfolio tracker application. It provides the core logic and data management for user accounts, portfolios, transactions, and real-time stock information.

- Development Roadmap: [Notion - Stock Tracker](https://polyester-begonia-b2d.notion.site/Stock-Portfolio-Tracker-16d19b18c25580ce9df0f7458de3bd00)
- Stock Tracker UI: [Stock Tracker UI](https://github.com/renanrgarcia/stock-tracker-ui)

# ✨ Key Features
- Secure Authentication: User authentication and authorization with JWT tokens and role-based access control. 🔒
- Portfolio Management: Add, remove, and manage stocks within user portfolios, including share quantities. 💼
- Transaction History: Detailed record of all buy/sell orders with comprehensive transaction information. 🧾
- Real-time Valuation: Calculates portfolio value based on up-to-the-minute stock prices. 📈
- Performance Metrics: Tracks key metrics like total gain/loss and percentage gain/loss. 📊
- Automated Updates: Scheduled daily portfolio valuations and reports. ⏰
- Real-time Stock Data: Fetches live stock prices from external APIs (e.g., Alpha Vantage, IEX Cloud). 💰
  
# 🛠️ Technology Stack
Java 21
Spring Boot 3.x
Spring Security
Spring Data JPA
Spring Scheduling
REST Client (RestTemplate or WebClient)
PostgreSQL Database 🐘
JUnit & Mockito for testing 
Redis for caching

# ⚙️ Getting Started
1. Prerequisites:
Java 21+ JDK installed
Maven installed

2. Clone the repository:
```bash
git clone https://github.com/renanrgarcia/stock-tracker-api.git
```

3. Navigate to the project directory:
```bash
cd stock-tracker-api
```

4. Build and run the application:
```bash
mvn spring-boot:run
```

# 🧪 Running Tests
Navigate to the project root and execute:
```bash
mvn test
```

# 🤝 Contributing
Contributions are welcome! Feel free to opening pull requests. Please, use git flow technique.

# 📚 Resources
- Spring Boot: https://spring.io/projects/spring-boot/
- Spring Security: https://spring.io/projects/spring-security/
- Spring Data JPA: https://spring.io/projects/spring-data-jpa/
- PostgreSQL: https://www.postgresql.org/docs/

# 🐛 Issues
Report bugs and feature requests by opening an issue on this repository.

Part of the larger Stock Portfolio Tracker project.
