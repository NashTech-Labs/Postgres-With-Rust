# Incorporate Postgres With Rust Programming

PostgreSQL is a powerful, open source object-relational database system with over 30 years of active development that has earned it a strong reputation for reliability, feature robustness, and performance.

So, in this example We have incorporated the Postgres with Rust Programming Language.

## Setup
Before going through the code first <a href="https://www.youtube.com/watch?v=-LwI4HMR_Eg">Setup</a> the Postgres in the system.
After that you have to configure the username, Password and database name which we will use in the code.

### Configure 
Now configure the username, password and database name in the code.
`Client::connect("postgresql://USERNAME:PASSWORD@localhost:5432/DATABASE-NAME", NoTls)?;`

## Run
No all set to run the Code.

`cargo run`

## Contributing
We thrive for the best and want you to contribute towards a better Project. See [`CONTRIBUTING.md`](CONTRIBUTING.md) for giving your valuable feedbacks and contributions.