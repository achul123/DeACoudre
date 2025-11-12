# DeACoudre - Bukkit Plugin

## Installation

### Prerequisites
- Java 8 or higher
- Maven 3.6+
- A Bukkit/Spigot server

### Required dependencies (to be installed on the server)
- **Vault** - For the economy
- **PlaceholderAPI** (optional) - For placeholders

### Steps

1. **Clone the project**
   ```bash
   git clone https://github.com/Lefraudeur/DeACoudre.git
   cd DeACoudre
   ```

2. **Compile the plugin**
   ```bash
   mvn clean package
   ```

3. **Get the compiled JAR**
   The JAR file will be generated in the `target/` folder
   ```
   target/DeACoudre-1.0-SNAPSHOT.jar
   ```

4. **Install the plugin**
   - Copy the JAR into the `plugins/` folder of your Bukkit server
   - Restart the server

## Configuration

After the first launch, a `config.yml` file will be created in `plugins/DeACoudre/`

## Commands

- `/dacreload` - Reload the configuration
- `/dacadmin` - Administration commands
- `/forcestart` - Force start a game
- `/scoreboard` - Display the scoreboard