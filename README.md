<h1 align="center">
  <br>
  <!-- TODO: add icon -->
    <!-- <img src="" alt="extension-icon" width="200"> -->
  <br>
  DB Explorer for Firebird&reg; databases
  <br>
  <br>
</h1>
<h4 align="center">Explore and run queries against your Firebird&reg; databases without leaving VS Code.</h4>

<!-- TODO: add badges -->
<!-- <p align="center">
  <a href="https://">
    <img src="https://" alt="badge1">
  </a>
  <a href="https://">
    <img src="" alt="bdage2">
  </a>
  <a href="https://">
    <img src="https://" alt="badge3">
  </a>
</p> -->

This extension allows you to connect directly to your [Firebird&reg; databases](https://firebirdsql.org/), list tables and fields, run queries, display/export results and more.

<!-- TODO: add banner  -->
<!-- ![banner]() -->

## Supported features

- Manage multiple database connections
- List hosts, databases, tables and fields inside **Explorer View**
- [Firebird Reserved Words](https://firebirdsql.org/refdocs/langrefupd25-reskeywords-full-reswords.html) **Code Completion**
- Table and field names **Code Completion**
- Run Firebird **SQL** queries
- Run **predefined** custom queries
- View results in a **table**
- **Realtime** results filtering and sorting
- Export results to **JSON**, **CSV**, **XSLX** or **PDF** file

## Getting Started

<!-- TODO: add link -->

1. [Install the extension]()
2. Restart VS Code and switch to DB Explorer view by clicking the newly added **Firebird icon** located at the VS Code **Activity Bar**.

## Using the extension

### Add new connection

You can add new connection to your Firebird database by clicking the _Add New Connection_ icon in the DB Explorer title bar. You will be presented with a Connection Wizard to guide you through the process. After the process is complete, your database connection will appear inside DB Explorer View

### Explore the database contents

You can view the database structure by expaning it's tree inside DB Explorer View.

> **Tip**: Right-clicking the tree nodes will give you the list of predefined custom queries.

### Set an active database

Before running your queries, remember to set an active database! You can:

- Right-click the database node and select _Set Active_
- Click the Firebird indicator in the bottom left status bar and select database from a list

> **Tip**: The _New Query_ command sets the selected database active and creates new SQL document.

### Running SQL queries

Execute your SQL query by pressing `Ctrl+Alt+Q` or by right-clicking the editor and selecting the _Run Firebird Query_ command.
The results will be displayed in new tab.

> **Important**: Multiple queries are currently **not supported**.
> If you have multiple queries written in your SQL document, make the selection around the one you want to run, otherwise you'll get an error.

## Settings

- `firebird.codeCompletion.keywords: <boolean>` | Enable Code Completion for Firebird Reserved Words (Default **true**)
- `firebird.codeCompletion.database: <boolean>` | Enable Code Completion for Table and Field names (Default **true**)
- `firebird.logLevel: <string>` | Logging level to display in the output channel. (Default **INFO**)
- `firebird.maxTablesCount: <number>` | The max table count shown in the tree view. Use 0 to show all tables. (Default **10**)
- `firebird.recordsPerPage: <string>` | Number of records to display per page. (Default **10**)

## Disclaimer

This extensions is still in the early development stage, and as such it may not be suitable for usage in active development environment.

## Bugs reports & Features requests

<!-- TODO: add link -->

You can submit a bug report or a feature suggestion via [GitHub Issue Tracker]().
