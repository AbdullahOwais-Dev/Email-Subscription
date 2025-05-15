# Email Subscription System
 
This is a simple email subscription system that allows users to enter their email addresses to subscribe to updates. The system securely stores emails using Google Sheets via Google Apps Script.

## Features

- Simple and responsive subscription form
- Email validation before submission
- Google Sheets as a backend for storing emails
- Success and error message alerts
- Easy integration with other projects

## Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Google Apps Script
- **Database:** Google Sheets

## Configuration

To configure this project:

1. Replace the **Google Apps Script URL** in `index.html` with your own script URL.
2. Ensure that your Google Apps Script has permission to accept form submissions.

## Installation & Usage

To use this project, follow these steps:

```bash
git clone https://github.com/AbdullahOwais-Dev/Email-Subscription.git
cd Email-Subscription
```

1. Open `index.html` in a browser to access the subscription form.
2. Update the **Google Apps Script URL** in `index.html`.
3. Test the form by entering an email and clicking submit.

## Project Structure

```plaintext
/Email-Subscription
│── index.html        # Subscription Form UI
│── style.css         # Styling for the UI
│── script.js         # Frontend Logic (Validation, AJAX)
│── images/           # Assets (Icons, Backgrounds, etc.)
└── README.md         # Project Documentation
```

## Contributing

Pull requests are welcome! If you have suggestions or improvements, feel free to submit a PR.

## License

This project is licensed under the **MIT License**.

---

Developed by [Abdullah Owais](https://github.com/AbdullahOwais-Dev)

