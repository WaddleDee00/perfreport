# PerfReport — Rust Migration

PerfReport is a system performance assessment tool originally written in C++ and migrated to Rust for IS2083 Lab 3.

## Features

- Displays the number of logical processors
- Reports total and available system memory
- Measures system uptime
- Reports disk capacity and usage
- Calculates a system efficiency score

## Development and Testing

The Rust application uses the `sysinfo` library to collect real system information.

The project includes five unit tests covering memory usage, disk usage, scoring thresholds, and efficiency ratings.

The application was successfully compiled and tested on Windows 11 and packaged into a Docker container for Linux.

## How to Run

Run the Rust application:

`cargo run`

Run the automated tests:

`cargo test`

Build the Docker image:

`docker build -t perfreport .`

Run the Docker container:

`docker run --rm perfreport`

## Technologies Used

- C++
- Rust
- Cargo
- Docker
- Git and GitHub
- GitHub Actions

## AI Assistance Disclosure

ChatGPT was used to help interpret assignment instructions, troubleshoot development tools, and assist with implementing and testing portions of the Rust application. The code and results were reviewed and tested during the assignment.