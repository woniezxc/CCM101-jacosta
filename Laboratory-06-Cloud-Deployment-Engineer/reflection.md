---

### File 4: `reflection.md`

```markdown
# Mission Reflection

Writing a `docker-compose.yml` file makes a cloud engineer's work vastly more efficient, reliable, and repeatable. Instead of manually typing multiple lengthy `docker run` commands—which are prone to syntax errors and hard to replicate—Docker Compose lets you define an entire infrastructure in a single configuration file. This enables seamless deployments across different environments with just one command (`docker-compose up -d`), saving time and eliminating configuration drift.

Working with YAML highlighted the importance of strict formatting. Because YAML relies on precise indentation to define structure, introducing formatting errors like using tabs instead of spaces or placing keys at the wrong depth breaks parser validation. The file fails to execute, and Docker Compose throws syntax errors when trying to read the configuration.

Environment variables like `MYSQL_PASSWORD` play an important role in configuring containers dynamically without altering image code or hardcoding values inside application logic. They allow us to pass credentials, hostnames, and database settings securely into containers at runtime, keeping configuration separate from application images.

Deploying a full enterprise-grade cloud storage system like Nextcloud in just a few minutes was a rewarding experience. Seeing two independent containers start, connect automatically, and present a functional web application with a single command made the practical power of orchestration very clear.

Since Mission 1, my understanding of cloud computing has evolved from seeing it as remote server storage to recognizing it as an ecosystem powered by code and automation. I now understand how infrastructure is defined, connected, and scaled programmatically, moving from manual command-line tasks to senior-level engineering principles.
