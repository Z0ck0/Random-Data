# Random-Full-Name-Data
Random First and Last Name 
# Random Data Inserter UserScript

This UserScript is designed to insert random data into input fields on web pages using specific key combinations. It supports inserting random full names, phone numbers, addresses, and email addresses into input fields and text areas.

## Features

- Insert random full name with `Alt + 1`
- Insert random phone number with `Alt + 2`
- Insert random address with `Alt + 3`
- Insert random email address with `Alt + 4`

## Installation

1. Install [Tampermonkey](https://www.tampermonkey.net/) or a similar userscript manager.
2. Create a new script in the userscript manager and paste the code from `random_data_inserter.user.js` into it.
3. Save the script.

## Usage

1. Open any web page with input fields or text areas.
2. Focus on the input field or text area where you want to insert the random data.
3. Use the following key combinations to insert data:
    - `Alt + 1` to insert a random full name
    - `Alt + 2` to insert a random phone number
    - `Alt + 3` to insert a random address
    - `Alt + 4` to insert a random email address

## Configuration

The script fetches random full names from a JSON file hosted online. You need to host your `random_full_name.json` file on a server or a service that allows public access. Update the script with the URL of your JSON file.

## JSON Data Format

The `random_full_name.json` file should have the following format:

```json
{
  "firstNames": [
    "John", "Jane", "David", "Emily", "Michael", "Jessica", "William", "Sarah",
    "Matthew", "Ashley", "Christopher", "Amanda", "Joseph", "Jennifer", "Daniel",
    "Melissa", "Robert", "Stephanie"
  ],
  "lastNames": [
    "Smith", "Johnson", "Williams", "Brown", "Davis", "Miller", "Wilson", "Moore",
   
