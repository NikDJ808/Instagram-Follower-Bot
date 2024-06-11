### Project: Instagram Follower Automation

## Overview

This project automates the process of following users on Instagram using a Python script. The script interacts with the Instagram web application to follow users based on specific criteria.

## Features

- Automates the process of following users on Instagram.
- Customizable criteria for selecting users to follow.
- Logs actions and decisions for review.

## Requirements

- Python 3.x
- Selenium
- WebDriver (e.g., ChromeDriver for Google Chrome)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/instagram-follower-automation.git
    cd instagram-follower-automation
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the appropriate WebDriver for your browser and place it in your PATH. For example, if you are using Google Chrome, download [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/).

## Usage

1. Open `main.py` and configure your Instagram login credentials and preferences.

2. Run the script:

    ```bash
    python main.py
    ```

## Configuration

Modify the following variables in `main.py` to set your Instagram credentials and preferences:

- `USERNAME`: Your Instagram username.
- `PASSWORD`: Your Instagram password.
- `FOLLOW_CRITERIA`: Criteria to decide whether to follow a user.

## Acknowledgments

- [Selenium](https://www.selenium.dev/) for browser automation.
- [Instagram](https://www.instagram.com/) for providing the platform.
