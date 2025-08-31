# Minecraft Client Project

## 📌 Setup
Чтобы подготовить проект к запуску в **IntelliJ IDEA**:

1. Убедись, что у тебя установлены:
   - **JDK 21** (или версия, совместимая с Minecraft 1.21.4).
   - **Gradle** (можно использовать wrapper `./gradlew`).

2. Открой проект в IntelliJ IDEA.

3. Запусти команду Gradle для генерации конфигурации запуска:
   ```bash
   ./gradlew mcp:createIntelliJRunConfig
