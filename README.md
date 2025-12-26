Sri Lanka NIC Details Checker 🇱🇰

📌 Project Description
    The Sri Lanka NIC Details Checker is a simple application that analyzes a Sri Lankan National Identity Card (NIC) number and extracts personal information such as:
                  📅 Date of Birth
                  👤 Gender   
    The user enters an NIC number, and the system decodes it according to the official Sri Lankan NIC format.

🚀 Features
    Validate Sri Lankan NIC numbers (Old & New formats)
    Extract Date of Birth
    Identify Gender
    Simple and user-friendly input system
    Fast and accurate analysis

🆔 Sri Lanka NIC Format Overview
    Old NIC Format (10 characters)
            Example: 921234567V
            First 2 digits → Year of Birth (19XX)
            Next 3 digits → Day of year + Gender
                    001–366 → Male
                    501–866 → Female
            Last character → V or X

    New NIC Format (12 digits)
            Example: 199212345678
            First 4 digits → Year of Birth
            Next 3 digits → Day of year + Gender
                001–366 → Male
                501–866 → Female

🛠️ Technologies Used

            Programming Language:  JavaScript
            Framework : React
            UI: HTML / CSS / Bootstrap
            IDE: VS Code 


📥 How It Works

        User enters a valid Sri Lankan NIC number
        System detects NIC format (Old or New)
        NIC number is decoded
        Output displays:
                Birthday
                Gender

❗ Validations

        NIC length must be correct
        Day value must be within valid range
        Invalid NIC numbers return error messages
