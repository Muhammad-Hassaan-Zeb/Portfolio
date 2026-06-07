# Portfolio Backend

This project includes a simple Flask backend to accept contact form submissions and store them in an Excel file.

## Setup

1. Open a terminal in the project folder:

```bash
cd "c:\M.Hassaan\Portfolio"
```

2. Install dependencies:

```bash
python -m pip install -r requirements.txt
```

3. Start the server:

```bash
python backend.py
```

4. Open the portfolio in your browser:

```bash
http://127.0.0.1:5000
```

## How messages are stored

- The contact form posts to `/submit-contact`
- Submissions are saved in `messages.xlsx`
- The Excel file contains columns: `Timestamp`, `Name`, `Email`, `Subject`, `Message`

## Notes

- If `messages.xlsx` does not exist, it will be created automatically on the first message.
- The portfolio HTML is served from `Muhammad_Hassaan_Zeb_Portfolio_v2.html`.
