### Dev7 Studio - v7.22
Release Date: 22/3/2023
### MEGAVAST DEV7 Studio Project

The Dev7 Studio is a powerful project aimed at providing an advanced environment for managing and executing web development projects. This document serves as a guide to setting up and navigating the various components of the Dev7 Studio.

## Prerequisites

Before you begin, ensure you have Perl installed on your system as the project relies on Perl scripts for its operations.

### Installing Perl

1. **Linux/Unix/MacOS:** Perl is usually pre-installed. You can check by running `perl -v` in your terminal. If it's not installed, you can install it via your package manager (e.g., `sudo apt-get install perl` for Debian-based systems).
2. **Windows:** Download and install Strawberry Perl or ActivePerl from their respective websites.

## Getting Started

Upon initialization, Dev7 Studio loads necessary parameters to set up the environment for the MEGAVAST DEV7 project. The configuration details are as follows:

- **Project Name:** MEGAVAST DEV7
- **File Name:** dev7
- **Paths:**
  - CGI-Bin Path: `/var/www/cgi-bin/MEGAVAST/CMS`
  - HTML Directory: `$path/CODE`
  - Code Directory: `$path/CODE`
  - Code Backup Directory: `$path/CODE/BACKUP` (Main backup directory which may include multiple backup directories)
  - Log Directory: `$path/LOG/` (Stores log files)
  - HTML Path: `/var/www/html/CMS`
- **URLs:**
  - Base URL: `https://www.megavast.com/cms`
  - Images URL: `https://www.megavast.com/images`

The system also handles user inputs through various parameters (e.g., `editor_choice`, `content`, `save_page`) to manage page editing and saving tasks dynamically.

## Directory Setup

Ensure that all directories mentioned in the paths are properly set up and have the correct permissions for reading and writing. This setup is crucial for the system to function properly.

## Features

- **Automatic Parameter Handling:** Streamlines processes by automatically managing URL parameters and user sessions.
- **Code Management:** Facilitates efficient code handling with options to edit, backup, and restore code files.
- **Dynamic Content Management:** Supports dynamic adjustments and updates to content without manual file handling.

## Usage

1. **Load Parameters:** Initialize the environment by loading necessary parameters.
2. **Manage Content:** Use the provided URLs and paths to manage project content effectively.
3. **Documentation and Backup:** Ensure documentation and backups are handled automatically to prevent data loss.

### Basic Commands

- **Start the Server:** Navigate to the CGI-bin directory and start the Perl script using `perl filename.pl`.
- **Access the Web Interface:** Open a web browser and go to the base URL specified in the configuration.

## Updates and Maintenance

Regular updates are provided to enhance functionality and address any issues. Ensure that you back up your files before applying updates to prevent unintended data loss.

For more detailed documentation and guides on using Dev7 Studio, please refer to the official documentation or contact the support team at MEGAVAST.

Thank you for choosing Dev7 Studio for your web development needs!
