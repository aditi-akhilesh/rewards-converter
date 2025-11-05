# ✈️ Credit Rewards Converter ✈️

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JPMorgan Chase](https://img.shields.io/badge/JPMorgan_Chase-Project-blue?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 📋 Project Overview

Credit Rewards Converter is a Java application developed as part of the **JPMorgan Chase Software Engineering Lite Program**. This project demonstrates practical software engineering skills including object-oriented programming, unit testing, and Git workflow management.

The application converts between different types of credit card reward points, helping users understand the value of their rewards across different redemption options (cash back, airline miles, hotel points, etc.).

## ✨ Features

- **💳 Multiple Conversion Options**
  - Convert cash rewards to airline miles
  - Calculate hotel points equivalence
  - Compare different reward redemption values
  - Support for various credit card reward programs

- **📊 Value Optimization**
  - Calculate the best redemption option
  - Compare reward values across categories
  - Real-time conversion calculations
  - Clear value breakdowns

- **🧑‍💻 Clean Code Architecture**
  - Object-oriented design principles
  - Modular and maintainable code structure
  - Comprehensive unit testing
  - Well-documented methods

## 🛠️ Technologies Used

- **Java**: Core programming language
- **JUnit**: Unit testing framework
- **Git**: Version control and collaboration
- **Maven/Gradle**: Build and dependency management

## 🚀 Getting Started

### Prerequisites

```bash
Java JDK 8 or higher
Maven or Gradle (for dependency management)
Git
```

### Installation

1. **Clone the repository**:
```bash
git clone https://github.com/aditi-akhilesh/rewards-converter.git
cd rewards-converter
```

2. **Build the project**:

Using Maven:
```bash
mvn clean install
```

Using Gradle:
```bash
gradle build
```

3. **Run the application**:
```bash
java -jar target/rewards-converter.jar
# or
gradle run
```

### Running Tests

```bash
# Run all tests
mvn test
# or
gradle test

# Run specific test class
mvn test -Dtest=RewardValueTest
```

## 📚 Usage Examples

### Basic Conversion

```java
// Convert cash back to airline miles
RewardValue rewardValue = new RewardValue(100.0, "cash");
double airlineMiles = rewardValue.convertToMiles();
System.out.println("Airline Miles: " + airlineMiles);

// Calculate hotel points value
RewardValue hotelPoints = new RewardValue(10000, "hotel_points");
double cashValue = hotelPoints.getCashValue();
System.out.println("Cash Value: $" + cashValue);
```

### Conversion Rates

| Reward Type | Conversion Rate |
|-------------|----------------|
| Cash Back | 1.0x base value |
| Airline Miles | 1.5x value (approx) |
| Hotel Points | 1.2x value (varies) |
| General Points | 1.0x value |

## 📊 Project Structure

```
rewards-converter/
├── src/
│   ├── main/
│   │   └── java/
│   │       └── rewards/
│   │           ├── RewardValue.java
│   │           ├── RewardsConverter.java
│   │           └── Main.java
│   └── test/
│       └── java/
│           └── rewards/
│               └── RewardValueTest.java
├── pom.xml / build.gradle
├── readme.md
└── .gitignore
```

## 🏆 Key Learning Outcomes

This project demonstrates proficiency in:

- **Object-Oriented Programming**: 
  - Encapsulation and data abstraction
  - Class design and method implementation
  - Java best practices

- **Software Testing**:
  - Unit test development with JUnit
  - Test-driven development (TDD) approach
  - Code coverage and quality assurance

- **Version Control**:
  - Git workflow and branching
  - Collaborative development practices
  - Code review and pull requests

- **Problem Solving**:
  - Algorithm design for conversions
  - Edge case handling
  - Input validation

## 🔧 Development Process

### Git Workflow

1. Create feature branch from `main`
2. Implement feature with clean commits
3. Write comprehensive unit tests
4. Submit pull request for review
5. Merge after approval

### Code Quality Standards

- Follow Java naming conventions
- Maintain comprehensive JavaDoc comments
- Achieve >80% test coverage
- Pass all unit tests before merging

## 📝 JPMorgan Chase Software Engineering Program

This project was completed as part of the **JPMorgan Chase Software Engineering Lite Program**, which focuses on:

- Practical software development skills
- Industry-standard tools and practices
- Real-world engineering challenges
- Professional development experience

## 🚀 Future Enhancements

- [ ] Add support for more reward programs
- [ ] Implement GUI interface
- [ ] Real-time exchange rate updates
- [ ] Database integration for historical data
- [ ] Multi-currency support
- [ ] Mobile app version
- [ ] API integration with credit card providers

## 🤝 Contributing

This is a learning project, but suggestions and improvements are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is part of the JPMorgan Chase Software Engineering Program.

## 👤 Author

**Aditi Akhilesh**
- GitHub: [@aditi-akhilesh](https://github.com/aditi-akhilesh)
- LinkedIn: [aditi-akhilesh](https://www.linkedin.com/in/aditi-akhilesh/)

## 🌟 Acknowledgments

- JPMorgan Chase & Co. for the Software Engineering Lite Program
- Program instructors and mentors
- Open source Java community

---

💼 **Skills Demonstrated**: Java, OOP, Unit Testing, Git, Problem Solving, Software Engineering Best Practices

⭐ If you find this project interesting, please give it a star!
