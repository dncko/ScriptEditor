# ScriptEditor
Database scripts editor for the VMaNGOS emulator.

## Changes
- .NET 10 Runtime
- Using MySqlConnector instead of MySql.Data

## Configuration
Create `config.ini` next to `ScriptEditor.exe`:

```ini
Host=localhost
Port=3306
User=root
Pass=root
DB=mangos
Locale=en-US
Highlight=false
```

## Build
Open `ScriptEditor.sln` and build.
