# AdonisJS 6 Hexagonal Architecture Boilerplate

Welcome to the **AdonisJS 6 Hexagonal Architecture Boilerplate**! This project is designed to help developers kickstart their AdonisJS 6 applications using a clean and maintainable hexagonal architecture.

## 🏗️ Project Structure

The boilerplate follows a hexagonal architecture with the following main directories:

- **`src/adapters`**: Contains the code responsible for interacting with external systems (e.g., HTTP controllers, CLI commands, etc.).
- **`src/domain`**: Represents the core business logic and domain entities, isolated from external concerns.
- **`src/infrastructure`**: Handles technical details such as database access, third-party services, and configurations.

## 🚀 Getting Started

1. **Use the starter kit:**

   ```bash
   npm init adonisjs@latest -- -K="CePseudoBE/adonis-hexa-boilerplate"
   ```

2. **Run the application:**

   ```bash
   npm run dev
   ```

## ✨ Features

- **Hexagonal Architecture**: Clear separation of concerns using ports and adapters.
- **AdonisJS**: Built on top of the latest version of AdonisJS for modern web development.
- **TypeScript**: Full TypeScript support for better type safety.
- **Testing**: Integrated with Japa for comprehensive test coverage.
- **Use HMR Adonis fonctionnality**

## 🛠️ Development

- To add new features, create your domain logic in the `src/domain` folder.
- Use the `src/adapters` folder to interact with external systems (e.g., APIs, HTTP).
- Store infrastructure-related code such as database access in `src/infrastructure`.

## 🤝 Contributing

Feel free to fork this project and submit pull requests if you have improvements or new ideas!
