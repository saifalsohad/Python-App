# Python-App
# Python App Instructions

## Introduction
This Python application performs the following tasks:

### Step 1: Read and Modify Excel File

1. **Read an Excel File of a Location**
   - The application will read an Excel file containing location data.

2. **Check SSN (Social Security Number) and Plan ID Formatting**
   - Verify if SSN is a 9-digit number and Plan ID is a 4-digit number.
   - If either SSN or Plan ID does not meet the format:
     - Add '0' at the beginning to make SSN 9 digits long.
     - Add '0's at the beginning to make Plan ID 4 digits long.

   Example:
   - If SSN is `12345678`, convert it to `0012345678`.
   - If Plan ID is `123`, convert it to `0123`.

## Usage
To use the Python application, follow these steps:

1. Clone the repository:
   ```bash
   $ git clone https://github.com/yourusername/your-repo.git
