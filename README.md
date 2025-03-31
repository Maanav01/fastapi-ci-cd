# FastAPI Backend with Automated Tests and GitHub Actions

This project demonstrates how to set up a basic FastAPI backend with automated API tests using Python and integrate those tests into a GitHub Actions CI/CD pipeline. 

## Table of Contents
- [Overview](#overview)
- [Task 1: Set Up the FastAPI Server](#task-1-set-up-the-fastapi-server)
- [Task 2: Writing Automated Tests for the API](#task-2-writing-automated-tests-for-the-api)
- [Task 3: Enhancing the Tests with Pytest](#task-3-enhancing-the-tests-with-pytest)
- [Task 4: Integrating Test Automation with GitHub Actions](#task-4-integrating-test-automation-with-github-actions)
- [Task 5: Expanding the Automation for Real-World Projects](#task-5-expanding-the-automation-for-real-world-projects)
- [Contributing](#contributing)

## Overview

This repository contains:
1. A FastAPI server with three basic mathematical operations: `add`, `subtract`, and `multiply`.
2. Automated tests using Python's `requests` library and `pytest`.
3. A GitHub Actions workflow that automatically runs the tests when code is pushed or a pull request is made.

## Task 1: Set Up the FastAPI Server

### Install Required Packages

Install the required dependencies:

```bash
pip install fastapi uvicorn
